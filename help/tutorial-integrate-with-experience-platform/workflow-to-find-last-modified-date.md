---
title: 書き出しワークフローの作成（パート 1） - 受信者リストの最終変更日を検索する
description: 「書き出しワークフローの作成」チュートリアルの最初の部分では、Experience Platform セグメントから作成された受信者リストの最終変更日を検索するワークフローの作成方法を説明します。
feature: Data Management, Workflows
jira: KT-8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: 6fd70eea-3be7-4589-a608-05b0a8de93a6
source-git-commit: a6b4e7f12c6565bcef644705b23f96803c5b6f85
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---

# 書き出しワークフローの作成（パート 1） - 受信者リストの最終変更日を検索する

「書き出しワークフローの作成」チュートリアルの最初の部分では、Experience Platform セグメントから作成された受信者リストの最終変更日を検索するワークフローの作成方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12&learn=on)

## Assets

JavaScript で日付範囲を確立：

```java
 var DEFAULT_LOOKBACK_DAYS = 90;
 vars.OPTION_NAME = "BroadLog_CaptureTime";

 logInfo("=====================");
 logInfo("Starting Execution...");

 // Establish the last and next RunTimes
 var lastRunTime = getOption(vars.OPTION_NAME);
 var nextRunTime = getCurrentDate();

 //To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
 //lastRunTime = null;

 logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
 logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

 //Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
 if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

   logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
   lastRunTime = new Date();
   lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
   logInfo("LAST Run Date Set: [" + lastRunTime + "]");

 } 

 //Persist values through execution of this instance of the workflow.
 vars.lastRunTime = lastRunTime;
 vars.nextRunTime = nextRunTime;

 logInfo("Finished Execution.");
 logInfo("===================");
```

## 次のビデオ

[書き出しワークフローの作成（パート 2） - データの抽出、書式設定、外部アカウントへの保存](extract-format-save-data-to-external-account.md)
