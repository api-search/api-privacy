---
api_specs:
- filename: avacast-jp-openapi-generated.yml
  format: yaml
  label: avacast-jp API
  slug: avacast-jp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avacast-jp/openapi/_ae-authored/avacast-jp-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: メールアドレス、会社名、外部のアカウントでログインする場合はそのアカウントの識別子とメールアドレス
  - category: financial
    text: クレジットカード情報は決済代行事業者（Stripe）が保持し、当社は保持しません。当社は請求に必要な顧客 ID とプランの情報を保持します
  - category: communication
    text: フォームに入力された会社名、氏名、メールアドレス、電話番号、問い合わせ内容
  - category: device
    text: IP アドレス、ブラウザの種類、エラーの発生状況
  - category: behavioral
    text: セッションの開始・終了時刻、接続時間、発話の文字数と秒数、使用したアバターと言語、API キーの利用日時
  deletion:
    route: お問い合わせフォームからご連絡ください
    text: 利用者は、自らの個人情報の開示、訂正、削除を求めることができます。お問い合わせフォームからご連絡ください。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: サービスの提供、認証、課金および請求
    text: 本サービスの提供、認証、課金および請求
  - purpose: 利用状況の集計と上限の判定、通知
    text: 利用状況の集計と上限の判定、利用者への通知（上限の接近など）
  - purpose: 障害の検知と対応、不正利用の防止
    text: 障害の検知と対応、不正利用の防止
  - purpose: 問い合わせへの対応
    text: 問い合わせへの対応
  - purpose: サービスの改善
    text: 本サービスの改善。ただし、発話テキストを機械学習モデルの学習に使用することはありません
  retention:
  - period: null
    scope: utterance text
    text: 発話のテキストは保存しません。
  - period: 30 日
    scope: generated audio
    text: 生成した音声を最後に使われてから 30 日まで保持します。
  rights:
  - right: disclosure, correction, deletion
    text: 利用者は、自らの個人情報の開示、訂正、削除を求めることができます。
  role:
    text: シャノン合同会社（以下「当社」）は、リアルタイムアバター配信 API「avacast」（以下「本サービス」）において取得する個人情報を、次のとおり取り扱います。
    value: controller
  sale_or_sharing:
    stance: conditional
    text: 当社は、法令に基づく場合を除き、個人情報を第三者に提供しません。
  subprocessors:
    text: 本サービスの提供にあたり、クラウド、GPU サーバー、決済、メールの送信、エラーの監視、アクセス解析の事業者に処理を委託しています。これらの事業者の一部は日本国外に所在します。
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: avacast-jp
provenance_date: '2026-11-09'
provider_name: avacast-jp
provider_slug: avacast-jp
slug: avacast-jp-privacy-policy
source_date: '2026-11-09'
source_filename: avacast-jp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://avacast.jp/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: avacast-jp\naid: avacast-jp\nurl: https://avacast.jp/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: シャノン合同会社（以下「当社」）は、リアルタイムアバター配信 API「avacast」（以下「本サービス」）において取得する個人情報を、次のとおり取り扱います。\ndata_categories:\n- category: contact\n  text: メールアドレス、会社名、外部のアカウントでログインする場合はそのアカウントの識別子とメールアドレス\n- category: financial\n  text: クレジットカード情報は決済代行事業者（Stripe）が保持し、当社は保持しません。当社は請求に必要な顧客 ID とプランの情報を保持します\n- category: communication\n  text: フォームに入力された会社名、氏名、メールアドレス、電話番号、問い合わせ内容\n- category: device\n  text: IP アドレス、ブラウザの種類、エラーの発生状況\n- category: behavioral\n  text: セッションの開始・終了時刻、接続時間、発話の文字数と秒数、使用したアバターと言語、API キーの利用日時\n\
  purposes:\n- purpose: サービスの提供、認証、課金および請求\n  text: 本サービスの提供、認証、課金および請求\n- purpose: 利用状況の集計と上限の判定、通知\n  text: 利用状況の集計と上限の判定、利用者への通知（上限の接近など）\n- purpose: 障害の検知と対応、不正利用の防止\n  text: 障害の検知と対応、不正利用の防止\n- purpose: 問い合わせへの対応\n  text: 問い合わせへの対応\n- purpose: サービスの改善\n  text: 本サービスの改善。ただし、発話テキストを機械学習モデルの学習に使用することはありません\nretention:\n- scope: utterance text\n  period: null\n  text: 発話のテキストは保存しません。\n- scope: generated audio\n  period: 30 日\n  text: 生成した音声を最後に使われてから 30 日まで保持します。\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 本サービスの提供にあたり、クラウド、GPU サーバー、決済、メールの送信、エラーの監視、アクセス解析の事業者に処理を委託しています。これらの事業者の一部は日本国外に所在します。\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: お問い合わせフォームからご連絡ください\n  text: 利用者は、自らの個人情報の開示、訂正、削除を求めることができます。お問い合わせフォームからご連絡ください。\nrights:\n- right: disclosure, correction, deletion\n  text: 利用者は、自らの個人情報の開示、訂正、削除を求めることができます。\nsale_or_sharing:\n  stance: conditional\n  text: 当社は、法令に基づく場合を除き、個人情報を第三者に提供しません。\n"
source_yaml_url: https://artifacts.apis.io/avacast-jp/privacy/avacast-jp-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from avacast-jp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Avatars
- Real-Time
- Japan
---
