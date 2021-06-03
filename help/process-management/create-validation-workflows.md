---
title: 検証ワークフローの作成
description: 様々な承認検証ワークフローを設定する方法について説明します。
feature: ワークフロー、承認
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
source-git-commit: f6bb16306773a4b6ff7aa390a514e9b31fe047d6
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# 検証ワークフローの作成

Adobe Campaignは、配信コンテンツ、キャンペーンターゲット、データ抽出、予算の承認を確認および提供するためのオプションを、マーケター向けにいくつか用意しています。

このチュートリアルでは、様々な承認検証ワークフローを設定する方法について説明します。

## 前提条件 {#prerequisite}

承認手順を有効にする前に、マーケティングチームは個々のレビュー担当者を定義する必要があります。

* 承認アクティビティ内のAdobe Campaignのレビュー担当者の役割は、1人のレビュー担当者（オペレーター）か、レビュー担当者のグループ（オペレーターの役割）のいずれかです。
* キャンペーン開発者がキャンペーンまたは配信の承認者としてレビュー担当者を選択できるようにするには、管理者がAdobe Campaignでレビュー担当者とレビュー担当者グループを設定する必要があります。

## キャンペーンの承認の設定{#configuring-approvals-for-campaigns}

キャンペーンワークフローのすべての配信で同じレビュー担当者のセットがある場合は、承認とレビュー担当者をキャンペーンレベルで設定して、キャンペーン承認機能を適用します。 承認タスクとレビュー担当者は、ワークフローが実行されると、ワークフローの各配信アクティビティにプッシュされます。

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## 配信の承認の設定{#configuring-approvals-for-deliveries}

また、配信レベルで承認を設定することもできます。 配信の承認手順とレビュー担当者がキャンペーンの承認手順とレビュー担当者と異なる場合は、配信設定がキャンペーン設定を上書きします。

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## 承認アクティビティの設定{#configuring-an-approval-activity}

配信やキャンペーンの承認とは異なり、「承認」アクティビティを使用すると、ワークフロー内に承認プロセスを作成できます。 これにより、配信を開始する前にターゲティングの選択ロジックを承認できます。 また、必要に応じて、ワークフロー内の複数のレベルで承認をおこなうこともできます。

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

詳しくは、[承認に関するドキュメント](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)を参照してください。
