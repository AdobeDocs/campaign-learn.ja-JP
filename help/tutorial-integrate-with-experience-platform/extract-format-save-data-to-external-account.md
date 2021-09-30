---
title: エクスポートワークフローの作成（パート 2） — データの抽出、書式設定、外部アカウントへの保存
Description: In this second part of the Create an Export Workflow tutorial, you learn how to format the data for export and how to save the data to an external account. 
feature: Data Import/Export, Workflows
kt: 8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
source-git-commit: c685927a01d08ae6533399ad2466967c6cd3f9fd
workflow-type: tm+mt
source-wordcount: '62'
ht-degree: 1%

---


# エクスポートワークフローの作成（パート 2）:データの抽出、書式設定、外部アカウントへの保存

「エクスポートワークフローの作成」チュートリアルのこの 2 番目のパートでは、エクスポートするデータをフォーマットする方法と、データを外部アカウントに保存する方法を学びます。

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12)

## アセット

JavaScript:保存日

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
