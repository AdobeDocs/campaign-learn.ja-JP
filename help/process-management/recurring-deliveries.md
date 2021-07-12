---
title: 繰り返しメールキャンペーンと連続メールキャンペーンの設定方法
description: 繰り返し配信と連続配信の設定方法およびこれら 2 つのアプローチの違いについて説明します。
feature: ワークフロー
kt: 7982
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
source-git-commit: 02a6238163a7c8f887236e03b78673c57c836a45
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 100%

---

# 繰り返しおよび連続 E メールキャンペーンの設定方法

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

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## 連続配信の設定方法 {#how-to-set-up-a-continuous-delivery}

このビデオでは、増分クエリを使用して連続配信を設定する方法について説明します。

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)
