---
title: 繰り返し配信と連続メール配信の作成
description: 繰り返し配信と連続配信の設定方法およびこれら 2 つのアプローチの違いについて説明します。
feature: Workflows
kt: 7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
source-git-commit: b1b8d8a99a551239c445fb588cbd126b66a53c9b
workflow-type: ht
source-wordcount: '232'
ht-degree: 100%

---

# 繰り返し配信と連続メール配信の作成

このチュートリアルでは、繰り返し配信と連続配信の設定方法およびこれら 2 つのアプローチの違いについて説明します。

## 繰り返し配信および連続配信のトラッキング {#recurring-and-continuous-delivery-tracking}

繰り返し配信と連続配信は、連絡先データの管理方法が異なります。

* **連続配信**&#x200B;では、新しい受信者を既存の配信に追加できるので、新しい受信者を追加するたびに配信を作成する必要はありません。クリエイティブはキャンペーンのワークフロー内で直接更新でき、配信テンプレートリソースフォルダーのテンプレートも更新されます。

   連続配信は、単一の配信と複数の配信ログ（broadLog）を生成します。その単一の配信を参照する複数のトラッキングログは、配信を実行するたびに追加されます。

![連続配信](/help/assets/delivery_continuous.jpg)

* **繰り返し配信**&#x200B;では、実行するたびに新しい配信インスタンスを作成します。例えば、ワークフローが週に 1 回実行されるようにスケジュールされている場合、1 年後には 52 件の配信が存在することになります。つまり、broadLog とトラッキングログは、各配信インスタンスで分離されます。

![繰り返し配信](/help/assets/delivery_recurring.jpg)

## 繰り返し配信の設定方法 {#how-to-set-up-a-recurring-delivery}

このビデオでは、繰り返し配信とスケジューラーアクティビティを設定する方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/342638?quality=12&learn=on)

## 連続配信の設定方法 {#how-to-set-up-a-continuous-delivery}

このビデオでは、増分処理クエリを使用して連続配信を設定する方法について説明します。

>[!VIDEO](https://video.tv.adobe.com/v/342637?quality=12&learn=on)
