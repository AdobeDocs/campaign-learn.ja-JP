---
title: マーケター向け Adobe Campaign v8 の基本を学ぶ
description: このチュートリアルでは、Campaign v8 の主な機能の概要について説明します。Campaign Standard から Campaign v8 に移行するマーケターを対象としています。
role: User
level: Beginner, Experienced
jira: KT-15788
source-git-commit: 93a68053823fe4aefbd6a755b957b4eea8d6a163
workflow-type: tm+mt
source-wordcount: '849'
ht-degree: 100%

---


# マーケター向けの基本を学ぶ

このガイドでは、Campaign v8 の主な機能の概要について説明します。Campaign Standard から Campaign v8 に移行するマーケターを対象としています。

Adobe Campaign v8 には、クライアントコンソールまたは web ユーザーインターフェイスからアクセスできます。Web インターフェイスを使用すると、主なマーケティングアクションを作成、管理、実行できます。

>[!NOTE]
> Adobe Campaign web ユーザーインターフェイスのリリースは、機能のデプロイメントに対して、よりスケーラブルで段階的なアプローチを実現できる継続的配信モデルに基づいて動作します。最新の更新については、定期的に[リリースノート](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/release-notes/release-notes)を参照してください。

## Campaign web ユーザーインターフェイスへのアクセスと探索

>[!VIDEO](https://video.tv.adobe.com/v/3427278?quality=12&learn=on){transcript=true}

1. [インターフェイスの確認](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/start/user-interface)
2. [リストの参照とフィルタリング](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/start/list-filters)

## ヘルプとガイダンスの検索

[Adobe Campaign Web ユーザーインターフェイスドキュメント](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/campaign-web-home)

## プロファイルとオーディエンスの作成と管理

### オーディエンス管理

Campaign v8 でオーディエンスを作成および管理する一般的な概念は、Adobe Campaign Standard と同じです。

1. Campaign web ユーザーインターフェイスを使用してプロファイルにアクセス、管理および探索する方法について説明します。

   >[!VIDEO](https://video.tv.adobe.com/v/3427293?quality=12&learn=on){transcript=true}

   詳しくは、[プロファイルの基本を学ぶ](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/audiences/work-with-profiles/about-recipients){target="_blank"}を参照してください。

2. オーディエンスの作成と管理方法、配信用のオーディエンスの選択方法、コントロール母集団の定義方法について説明します。

   >[!VIDEO](https://video.tv.adobe.com/v/3425861?quality=12&learn=on){transcript=true}

   詳しくは、[ オーディエンスの基本を学ぶ](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/audiences/audiences/manage-audience){target="_blank"}を参照してください。

3. [テストプロファイルの作成と管理](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/audiences/work-with-profiles/test-profiles){target="_blank"}

### 購読を管理

Adobe Campaign Web を使用すると、ニュースレターなどのサービスの管理と作成を行ったり、それらのサービスの購読または登録解除を確認したりできます。詳細情報：

<table style="table-layout:fixed"><tr style="border: 0;">
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/audiences/work-with-services/manage-services">
<img alt="低頻度" src="_assets/lp-list.jpg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/audiences/work-with-services/manage-services"><strong>購読サービスの作成</strong></a>
</div>
<p></td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/audiences/work-with-services/manage-subscribers">
<img alt="低頻度" src="_assets/workflow-activities.jpeg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/audiences/work-with-services/manage-subscribers"><strong>購読者の管理<strong></strong></a>
</div>
<p></td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/send-to-subscribers">
<img alt="検証" src="_assets/workflow-create.jpeg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/send-to-subscribers"><strong>メッセージをサービスのサブスクライバーに送信</strong></a>
</div>
<p>
</td>
</tr>
</table>

## クロスチャネルキャンペーンとワークフローの作成と管理

![キャンペーンフロー](/help/tutorial-get-started-with-acv8-migrating-from-acs/_assets/campaign-flow.png)

### キャンペーンの作成

1. [キャンペーンの基本を学ぶ](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/campaigns/gs-campaigns){target="_blank"}
2. [キャンペーンへのアクセスと管理](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/campaigns/manage-campaigns){target="_blank"}
3. [最初のキャンペーンを作成](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/campaigns/create-campaigns){target="_blank"}

### ワークフローの作成

1. ワークフローの仕組みと、ターゲティングワークフローの作成方法を説明します。

   >[!VIDEO](https://video.tv.adobe.com/v/3425873?quality=12&learn=on){transcript=true}

1. [ワークフローアクティビティの操作](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/wf/design-workflows/about-activities){target="_blank"}
1. [ワークフローのガードレールと制限](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/wf/guardrails){target="_blank"}

## 配信の作成と管理

### メール配信

メール配信をゼロから作成し、オーディエンスの定義、コンテンツの設計、プレビューのシミュレートを行い、配達確認を送信する方法について説明します。

>[!VIDEO](https://video.tv.adobe.com/v/3425866?quality=12&learn=on){transcript=true}

1. **コンテンツの設計と定義**

   E メールデザイナーの操作方法について説明します。メールをゼロから構造化して設計する方法と、メールをパーソナライズしてテストする方法ついて説明します。

   >[!VIDEO](https://video.tv.adobe.com/v/3425867?quality=12&learn=on){transcript=true}

   HTML をアップロードしてメールを作成する方法、E メールデザイナーと互換性を持たせる方法、テンプレートに変換する方法について説明します。

   >[!VIDEO](https://video.tv.adobe.com/v/3427633?quality=12&learn=on){transcript=true}

2. **プレビューとテスト**

   メールメッセージのコンテンツとパーソナライゼーションをプレビューし、テスト配信（配達確認）を送信し、一般的なデスクトップ、モバイル、web ベースのクライアントでメールのレンダリングを確認する方法について説明します。

   >[!VIDEO](https://video.tv.adobe.com/v/3425862?quality=12&learn=on){transcript=true}

3. **メールの送信とログの確認**

   * [メールの準備と送信](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/email/monitor/prepare-send){target="_blank"}
   * [配信の送信スケジュール設定](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/email/monitor/schedule-sending){target="_blank"}
   * [配信ログの監視](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/email/monitor/delivery-logs){target="_blank"}

### SMS 配信

<table style="table-layout:fixed"><tr style="border: 0;">
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/sms/create-sms">
<img alt="リード" src="_assets/create_sms.png">
</a>
<div><a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/sms/create-sms"><strong>SMS 配信を作成</strong>
</div>
<p>
</td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/sms/content-sms">
<img alt="低頻度" src="_assets/design_sms.png">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/sms/content-sms"><strong>SMS 配信をデザイン<strong></strong></a>
</div>
<p></td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/sms/send-sms">
<img alt="検証" src="_assets/send_sms.png">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/sms/send-sms"><strong>SMS 配信のプレビューと送信</strong></a>
</div>
<p>
</td>
</tr></table>

### プッシュ通知の作成と管理

Adobe Campaign v8 では、Android™ と iOS の両方のプッシュチャネルをサポートしています。プッシュチャネルを使用している既存のワークフローと配信を移行するには、Adobe Campaign トランジショマネージャーにお問い合わせください。

<table style="table-layout:fixed"><tr style="border: 0;">
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/push/create-push">
<img alt="リード" src="_assets/push_create.jpeg">
</a>
<div><a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/push/create-push"><strong>プッシュ配信を作成</strong>
</div>
<p>
</td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/push/content-push">
<img alt="低頻度" src="_assets/push_design.jpeg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/push/content-push"><strong>プッシュ配信をデザイン<strong></strong></a>
</div>
<p></td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/push/send-push">
<img alt="検証" src="_assets/push_send.jpeg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/push/send-push"><strong>プッシュ配信のプレビューと送信</strong></a>
</div>
<p>
</tr></table>

### ダイレクトメール

1. [ダイレクトメール配信の作成](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/direct-mail/create-direct-mail)
2. [コンテンツの定義](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/direct-mail/content-direct-mail){target="_blank"}
3. [プレビューと送信](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/direct-mail/send-direct-mail){target="_blank"}

### 配信のベストプラクティス

* [配信テンプレートの使用](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/delivery-template){target="_blank"}

## ランディングページの作成と管理

<table style="table-layout:fixed"><tr style="border: 0;">
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/landing-pages/create-lp">
<img alt="リード" src="_assets/lp-subscription.jpeg">
</a>
<div><a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/landing-pages/create-lp"><strong>ランディングページの作成</strong>
</div>
<p>
</td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/landing-pages/lp-content">
<img alt="検証" src="_assets/lp-design.jpg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/landing-pages/lp-content"><strong>ランディングページの設計</strong></a>
</div>
<p>
</td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/landing-pages/lp-templates">
<img alt="検証" src="_assets/lp-reporting.jpg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/landing-pages/lp-templates"><strong>ランディングページテンプレートの操作</strong></a>
</div>
<p>
</td>
</tr></table>


## コンテンツ管理

* [コンテンツのパーソナライズ](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/dynamic-content/personalize){target="_blank"}
* [条件付きコンテンツ](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/dynamic-content/conditions){target="_blank"}
* [コンテンツブロック](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/dynamic-content/content-blocks){target="_blank"}
* [コンテンツフラグメント](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/email/content/manage-reusable-content/fragments){target="_blank"}
* [メールへのビジュアルフラグメントの追加](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/email/content/manage-reusable-content/use-visual-fragments){target="_blank"}
* [メッセージにオファーを追加](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/offers){target="_blank"}
* [メールテンプレートの作成](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/email/content/manage-reusable-content/create-email-templates){target="_blank"}

## 配信の送信

* [スタンドアロン配信のスケジュール設定](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/gs-deliveries#gs-schedule){target="_blank"}
* [ワークフローでの配信のスケジュール設定](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/msg/email/monitor/schedule-sending#schedule-a-delivery-in-a-campaign-workflow){target="_blank"}


## レポート

Adobe Campaign には 3 つの異なるレポートがあります。

<table style="table-layout:fixed"><tr style="border: 0;">
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/reports/campaign-report/campaign-reports">
<img alt="検証" src="./_assets/campaign_report.jpeg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/reports/campaign-report/campaign-reports"><strong>キャンペーンレポート</strong></a>
</div>
<p>
<div>
<a>個々の配信のパフォーマンス、有効性、結果に関する詳細情報が提供され、包括的な概要が得られます。</a>
</div>
<p>
</td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/reports/delivery-report/delivery-reports">
<img alt="リード" src="_assets/email_report.jpeg">
</a>
<div><a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/reports/delivery-report/delivery-reports"><strong>配信レポート</strong>
</div>
<p>
<div>
<a>成功率、オーディエンスのエンゲージメント、その他の重要な指標など、各配信のチャネルごとのパフォーマンスを完全に分析します。キャンペーンの全体的な有効性と影響を評価できます。</a>
</div>
<p>
</td>
<td>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/reports/global-report/global-reports">
<img alt="グローバルレポート" src="_assets/push_report.jpeg">
</a>
<div>
<a href="https://experienceleague.adobe.com/ja/docs/campaign-web/v8/reports/global-report/global-reports"><strong> グローバルレポート</strong></a>
</div>
<p>
<div>
<a>Campaign インスタンス内の各チャネルについて、トラフィックとエンゲージメント指標を連結した全体的な概要を提供します。これらのレポートは、様々なウィジェットで構成されます。各ウィジェットは、キャンペーンや配信パフォーマンスについての明確な観点を提供します。</a>
</div>
<p>
</td>
</tr></table>

## 統合

### Adobe Experience Manager

* [Adobe Experience Manager Assets as a Cloud Service でのアセットの管理](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/integrations/aem-assets){target="_blank"}
* [Adobe Experience Manager as a Cloud Service でのテンプレートの管理](https://experienceleague.adobe.com/ja/docs/campaign-web/v8/integrations/aem-content){target="_blank"}

### その他

次の統合は、Adobe Campaign クライアントコンソールから使用できますが、Campaign Web ユーザーインターフェイスではまだ使用できません。提供されたリンクを使用して、Campaign v8（クライアントコンソール）ドキュメントを参照し、これらの統合について詳細を確認してください。

* Adobe Analytics データの使用と KPI の共有。[詳細情報](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/connect/ac-aa){target="_blank"}
* Adobe Experience Cloud（Adobe Audience Manager）とのオーディエンスの共有。[詳細情報](https://experienceleague.adobe.com/ja/docs/campaign-classic/using/integrating-with-adobe-experience-cloud/audience-sharing/sharing-audiences-with-adobe-experience-cloud){target="_blank"}
* Adobe Target との統合。[詳細情報](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/connect/ac-at){target="_blank"}
* Adobe Experience Cloud トリガーとの統合。[詳細情報](https://experienceleague.adobe.com/ja/docs/campaign/campaign-v8/connect/ac-triggers){target="_blank"}


