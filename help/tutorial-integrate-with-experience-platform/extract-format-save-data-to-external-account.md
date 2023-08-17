---
title: 書き出しワークフローの作成（パート 2） - データの抽出、書式設定、外部アカウントへの保存
description: 「書き出しワークフローの作成」チュートリアルのこの 2 番目のパートでは、書き出すデータの書式設定方法と、データを外部アカウントに保存する方法を学びます。
feature: Data Management, Workflows
jira: KT-8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: a6b4e7f12c6565bcef644705b23f96803c5b6f85
workflow-type: ht
source-wordcount: '92'
ht-degree: 100%

---

# 書き出しワークフローの作成（パート 2）：データの抽出、書式設定、外部アカウントへの保存

「書き出しワークフローの作成」チュートリアルのこの 2 番目のパートでは、書き出すデータの書式設定方法と、データを外部アカウントに保存する方法を学びます。

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12&learn=on)

## Assets

JavaScript：保存日

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```
