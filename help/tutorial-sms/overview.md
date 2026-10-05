---
title: テクニカルチュートリアル - Adobe Campaign の SMS の設定
description: SMTP プロバイダー用の SMS アカウントの設定方法と、設定の分析およびトラブルシューティング方法について説明します。
feature: SMS
role: Admin, Developer
badgeV7V8: label="v7 および v8 に適用" type="Positive"
thumbnail: 340957.jpg
exl-id: c1eaabbf-c349-431d-9bbb-6ae987926d99
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: d0e9f0b2-1f2b-4134-9844-49cd4e950f27
    internal-label: Campaign v8
feature_v2:
  - id: a4671286-a59f-47e3-b97b-90627a1977d5
    internal-label: Communication channels
subfeature_v2:
  - id: b1bd1421-1927-4c59-9bc6-ce292360e43b
    internal-label: SMS Messaging
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
source-git-commit: 369f9c3691b6326e521ebc9139aac1d2ee7c3ce2
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 100%
---
# テクニカルチュートリアル - Adobe Campaign の SMS の設定

このセクションのチュートリアルは、Adobe Campaign の SMS チャネルを設定する管理者を対象としています。

ここでは、以下のトピックを取り上げます。

* **[SMS の概要](/help/tutorial-sms/introduction-to-sms.md)**：
  *SMS の仕組みと、Adobe Campaign での SMS の送信方法について説明します。*

* **[標準の SMPP プロバイダーに対応する SMS アカウントの設定](/help/tutorial-sms/set-up-account-for-standard-smpp-provider.md)**
  *SMS コネクタを SMPP プロバイダーに適応させる方法について説明します。 接続の制限に対応できるように SMS 設定を微調整します。  TLS を使用して最大スループット、送信ウィンドウ、暗号化を設定する方法を学びます。*

* **[SMPP プロバイダーへの SMS コネクタの適応](/help/tutorial-sms/adapt-sms-connector-to-smpp-provider.md)**
  *接続制限を処理するために SMS 設定を微調整する方法を説明します。 TLS を使用して最大スループット、送信ウィンドウ、暗号化を設定する方法を学びます。*

* **[SMPP プロトコルの詳細とトラブルシューティング](/help/tutorial-sms/smpp-deep-dive-and-troubleshooting.md)**
  *SMPP 接続を確立する方法および SMPP が PDU を介してデータを交換する方法について説明します。 接続のトラブルシューティング方法を説明します。*

>[!NOTE]
>
>このチュートリアルは、Adobe Campaign V7 および Campaign V8 を対象としています。 その他の関連リソースは、製品ドキュメント [SMS コネクタのプロトコルと設定](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/sending-messages/sending-messages-on-mobiles/sms-set-up/sms-protocol)を参照してください。
