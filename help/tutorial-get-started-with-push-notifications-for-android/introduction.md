---
title: Android 向けプッシュ通知の概要 - はじめに
description: このチュートリアルでは、プッシュ通知を Adobe Campaign から送信し、Android™ アプリで受信する手順について説明します。
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noCatalog
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
source-git-commit: 05b49ca012d0d505b117a2fb6b12ff41b51be63e
workflow-type: ht
source-wordcount: '317'
ht-degree: 100%

---

# Android 向けプッシュ通知の概要 - はじめに

Adobe Campaign では、パーソナライズおよびセグメント化された [!DNL push] 通知を [!DNL iOS] および [!DNL Android™] モバイルデバイスに送信できます。このチュートリアルでは、[!DNL push] 通知を Adobe Campaign から送信し、[!DNL Android™] アプリで受信する手順について説明します。

## 前提条件

この操作には、以下が必要です。

1) **Android™ モバイルアプリケーション**

   このチュートリアルでは、モバイルアプリケーションの設定に必要な詳細手順については説明しません。**[!DNL Android™]モバイルアプリケーション（[!DNL Campaign SDK] が統合されたもの）が必要です**。

   必要な手順の詳細については、製品ドキュメントを参照してください。

   [Campaign SDK をモバイルアプリケーションに統合する](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=ja)

2) **[!DNL Mobile App channel]パッケージ（インストール済み）**

   [!DNL Mobile App channel] パッケージを [!DNL Campaign] インスタンスにインストールする必要があります。次のビデオでは、[!DNL Mobile App channel] がインスタンスにインストールされているかどうかを確認する方法と、インストールしていない場合は、インストールの方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on)

## チュートリアルの概要

目的は [!DNL Neotrip] [!DNL Android™] モバイルアプリのサブスクリプション購読者に、パーソナライズされたプロモーションの [!DNL push] 通知を送信することです。[!DNL Neotrip] アプリは [!DNL Campaign SDK] で設定され、[!DNL Mobile App channel] は [!DNL Campaign] インスタンスで有効化されます。

次の設定手順が必要です。

### ステップ 1：アプリの購読スキーマを拡張して[!DNL push]通知をパーソナライズする

[!DNL push] 通知をパーソナライズできるようにするには、まず[アプリ購読スキーマを拡張](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)する必要があります。これにより、ユーザーがサービスにサブスクライブしたときにアプリから受け取ったパーソナライズ値を保存できるようになります。

### 手順 2：Campaign で Android™ サービスを設定してモバイルアプリケーションを作成する

次に、[Campaign で Android™ サービスを設定し、モバイルアプリケーションを作成する必要があります](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md)。この手順では、[!DNL Neotrip] アプリをプッシュ通知のターゲットとして定義します。

### 手順 3：プッシュ通知を設定して送信する

これで、プッシュ通知を[設定して送信](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md)する準備が整いました。

## チュートリアルの開始

ステップ 1：[アプリ購読スキーマを拡張する](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
