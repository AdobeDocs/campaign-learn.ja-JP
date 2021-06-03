---
title: Android 向けプッシュ通知の概要 - はじめに
description: このチュートリアルでは、Adobe Campaignからプッシュ通知を送信し、Android™アプリでこれらの通知を受信する手順について説明します。
feature: プッシュ
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 41%

---

# Android 向けプッシュ通知の概要 - はじめに

Adobe Campaign では、パーソナライズおよびセグメント化された [!DNL push] 通知を [!DNL iOS] および [!DNL Android™] モバイルデバイスに送信できます。このチュートリアルでは、Adobe Campaignから[!DNL push]アプリに[!DNL Android™]通知を送信する手順について説明します。

## 前提条件

開始する前に、次の条件を満たす必要があります。

1) **Android™モバイルアプリケーション**

   このチュートリアルでは、モバイルアプリケーションの設定に必要な詳細手順については説明しません。 [!DNL Campaign SDK]が統合された&#x200B;**の**[!DNL Android™]&#x200B;モバイルアプリケーションが必要です。

   必要な手順の詳細については、製品ドキュメントを参照してください。

   [Campaign SDK をモバイルアプリケーションに統合する](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=ja)

2) インストール済みの **[!DNL Mobile App channel]パッケージ**

   [!DNL Mobile App channel]パッケージを[!DNL Campaign]インスタンスにインストールする必要があります。 次のビデオでは、[!DNL Mobile App channel] がインスタンスにインストールされているかどうかを確認する方法と、インストールしていない場合は、インストールの方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## チュートリアルの概要

目的は、 [!DNL Neotrip] [!DNL Android™]モバイルアプリの購読者に、パーソナライズされたプロモーション[!DNL push]通知を送信することです。 [!DNL Neotrip]アプリは[!DNL Campaign SDK]で設定され、[!DNL Mobile App channel]は[!DNL Campaign]インスタンスで有効化されます。

次の設定手順が必要です。

### ステップ 1：アプリの購読スキーマを拡張して[!DNL push]通知をパーソナライズする

[!DNL push]通知をパーソナライズするには、まず[アプリ購読スキーマ](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)を拡張する必要があります。 THisを使用すると、ユーザーがサービスを購読したときにアプリから受け取るパーソナライゼーション値を保存できます。

### 手順2:Android™サービスを設定し、Campaignでモバイルアプリケーションを作成する

次に、[Android™サービスを設定し、Campaignで作成したモバイルアプリケーションを](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md)する必要があります。 この手順では、[!DNL Neotrip]アプリをプッシュ通知のターゲットとして定義します。

### ステップ 3：プッシュ通知を設定および送信する

これで、プッシュ通知を[設定して送信する準備が整いました。](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md)

## チュートリアルの開始

ステップ 1：[アプリ購読スキーマを拡張する](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
