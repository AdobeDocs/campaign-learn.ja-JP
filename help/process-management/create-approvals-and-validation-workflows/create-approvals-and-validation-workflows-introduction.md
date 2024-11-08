---
title: 承認および検証ワークフローの作成 - はじめに
description: 様々な承認検証ワークフローを設定する方法について説明します。
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Intermediate
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 4d21755204c22fbeb4ac3a2916e9ee68cd2e0f9a
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%

---

# 承認および検証ワークフローの作成 - はじめに

Adobe Campaign には、マーケターが配信コンテンツ、キャンペーンターゲット、データ抽出、予算承認などを審査して提供するためのオプションがいくつか用意されています。[承認の管理](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md)方法について説明します

## 前提条件 {#prerequisite}

承認手順を有効にする前に、マーケティングチームは個々のレビュー担当者を定義する必要があります。

* 承認アクティビティにおける Adobe Campaign のレビュー担当者の役割は、1 人のレビュー担当者（オペレーター）か、1 つのレビュー担当者グループ（オペレーターロール）が担います。
* キャンペーン開発者がキャンペーンまたは配信の承認者としてレビュー担当者を選択できるようにするには、管理者が Adobe Campaign でレビュー担当者とレビュー担当者グループを設定する必要があります。

## 承認の設定 {#configuring-approvals}

1. [キャンペーンの承認の設定](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md)：
キャンペーンワークフローのすべての配信についてレビュー担当者セットが同じ場合は、キャンペーンレベルで承認とレビュー担当者を設定して、キャンペーン承認機能を適用します。ワークフローを実行すると、承認タスクとレビュー担当者がワークフローの各配信アクティビティにプッシュされます。
2. [配信の承認の設定](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md)：
配信レベルで承認を設定することもできます。承認手順とレビュー担当者が配信とキャンペーンとで異なる場合は、配信の設定がキャンペーンの設定をオーバーライドします。
3. [ワークフローでの承認プロセスの作成](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md)：
承認アクティビティを使用すると、ワークフロー内に承認プロセスを作成できます。これにより、配信を開始する前にターゲティングの選択ロジックを承認できます。必要に応じて、ワークフロー内の複数のレベルで承認をおこなうこともできます。

詳しくは、[ドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=ja)を参照してください。
