---
title: 検証ワークフローの作成
description: 様々な承認検証ワークフローを設定する方法について説明します。
feature: ワークフロー、承認
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 02a6238163a7c8f887236e03b78673c57c836a45
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 100%

---

# 検証ワークフローの作成

Adobe Campaign には、マーケターが配信コンテンツ、キャンペーンターゲット、データ抽出、予算承認などを確認して提供するための複数のオプションが用意されています。

このチュートリアルでは、様々な承認検証ワークフローを設定する方法について説明します。

## 前提条件 {#prerequisite}

承認手順を有効にする前に、マーケティングチームは個々のレビュー担当者を定義する必要があります。

* 承認アクティビティにおける Adobe Campaign のレビュー担当者の役割は、1 人のレビュー担当者（オペレーター）か、1 つのレビュー担当者グループ（オペレーターロール）が担います。
* キャンペーン開発者がキャンペーンまたは配信の承認者としてレビュー担当者を選択できるようにするには、管理者が Adobe Campaign でレビュー担当者とレビュー担当者グループを設定する必要があります。

## キャンペーンの承認の設定  {#configuring-approvals-for-campaigns}

キャンペーンワークフローのすべての配信で一組の同じレビュー担当者がいる場合は、キャンペーンレベルで承認とレビュー担当者を設定して、キャンペーン承認機能を適用します。ワークフローを実行すると、承認タスクとレビュー担当者がワークフローの各配信アクティビティにプッシュされます。

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## 配信の承認の設定  {#configuring-approvals-for-deliveries}

配信レベルで承認を設定することもできます。承認手順とレビュー担当者が配信とキャンペーンとで異なる場合は、配信の設定がキャンペーンの設定を上書きします。

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## 承認アクティビティの設定  {#configuring-an-approval-activity}

配信やキャンペーンの承認とは異なり、承認アクティビティを使用すると、ワークフロー内に承認プロセスを作成できます。これにより、配信を開始する前にターゲティングの選択ロジックを承認できます。必要に応じて、ワークフロー内の複数のレベルで承認をおこなうこともできます。

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

詳しくは、[承認ドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=ja)を参照してください。
