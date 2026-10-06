---
title: 繰り返し配信と連続メール配信の作成
description: 繰り返し配信と連続配信の設定方法およびこれら 2 つのアプローチの違いについて説明します。
feature: Workflows
jira: KT-7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Intermediate
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
TQID: 'https://experienceleague.adobe.com/pdYTRO3rBq3BdS-WUGcx3POKjD6V4lH1dco4W9L6FwM'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: d0e9f0b2-1f2b-4134-9844-49cd4e950f27
    internal-label: Campaign v8
feature_v2:
  - id: a658c786-869b-4194-a780-2594d663adda
    internal-label: Data management
subfeature_v2:
  - id: fcb46c0f-76e1-48bc-9dd0-fcf9d97526cf
    internal-label: Workflows
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
source-git-commit: 369f9c3691b6326e521ebc9139aac1d2ee7c3ce2
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 100%
---
# 繰り返し配信と連続メール配信の作成

このチュートリアルでは、繰り返し配信と連続配信の設定方法およびこれら 2 つのアプローチの違いについて説明します。

## 繰り返し配信および連続配信のトラッキング {#recurring-and-continuous-delivery-tracking}

繰り返し配信と連続配信は、連絡先データの管理方法が異なります。

* **連続配信**&#x200B;では、新しい受信者を既存の配信に追加できるので、新しい受信者を追加するたびに配信を作成する必要はありません。 クリエイティブはキャンペーンのワークフロー内で直接更新でき、配信テンプレートリソースフォルダーのテンプレートも更新されます。

  連続配信は、単一の配信と複数の配信ログ（broadLog）を生成します。その単一の配信を参照する複数のトラッキングログは、配信を実行するたびに追加されます。

![連続配信](/help/assets/delivery_continuous.jpg)

* **繰り返し配信**&#x200B;では、実行するたびに新しい配信インスタンスを作成します。 例えば、ワークフローが週に 1 回実行されるようにスケジュールされている場合、1 年後には 52 件の配信が存在することになります。 つまり、broadLog とトラッキングログは、各配信インスタンスで分離されます。

![繰り返し配信](/help/assets/delivery_recurring.jpg)

## 繰り返し配信の設定方法 {#how-to-set-up-a-recurring-delivery}

このビデオでは、繰り返し配信とスケジューラーアクティビティを設定する方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/3446875?captions=jpn&quality=12&learn=on){transcript=true}

## 連続配信の設定方法 {#how-to-set-up-a-continuous-delivery}

このビデオでは、増分処理クエリを使用して連続配信を設定する方法について説明します。

>[!VIDEO](https://video.tv.adobe.com/v/3444568?captions=jpn&quality=12&learn=on){transcript=true}
