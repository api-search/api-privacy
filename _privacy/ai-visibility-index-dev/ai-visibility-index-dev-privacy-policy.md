---
api_specs:
- filename: ai-visibility-index-dev-openapi-generated.yml
  format: yaml
  label: AI Visibility Index API
  slug: ai-visibility-index-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-visibility-index-dev/openapi/_ae-authored/ai-visibility-index-dev-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 氏名 お問い合わせフォーム 必須
  - category: contact
    text: メールアドレス 改善診断レポート購入時（Stripe Checkout）、お問い合わせフォーム 必須
  - category: financial
    text: 当社は、カード番号、有効期限、セキュリティコード等のカード情報を取得・保存しません。
  - category: device
    text: ブラウザ情報（User-Agent） HTTPリクエストヘッダー サービス改善・互換性確保
  - category: behavioral
    text: ページ閲覧データ Google Analytics 4（Cookie使用） アクセス解析
  - category: location
    text: IPアドレス Webサーバーのアクセスログ 不正アクセス防止・レートリミット
  deletion:
    route: お問い合わせフォーム または contact@pulse-digital.dev
    text: 上記権利の行使を希望される場合は、 お問い合わせフォーム または contact@pulse-digital.dev までご連絡ください。
  dpa:
    available: null
    text: Anthropic PBC 米国 同上 委託 同上 本人同意（スキャン実行時） 有料API条件上の訓練不使用、DPA未締結（締結可能）
    url: null
  purposes:
  - purpose: 本サービスの提供・運用・維持管理
    text: 本サービスの提供・運用・維持管理（オンデマンドスキャン実行、レポート生成・送付を含む）
  - purpose: 決済処理・請求管理
    text: 改善診断レポートの決済処理・請求管理
  - purpose: お問い合わせ対応
    text: お問い合わせへの対応・返信
  - purpose: サービス改善・新機能開発
    text: サービスの改善・新機能の開発
  - purpose: 外部AI APIによるスコア算出・レポート生成
    text: 外部AI APIを用いたスコア算出・レポート生成
  retention:
  - period: 90日間
    scope: アクセスログ（IPアドレス等）
    text: アクセスログ（IPアドレス等） 90日間 不正アクセス調査
  - period: 法令に定める保存期間（7年間）
    scope: 決済記録
    text: 決済記録 法令に定める保存期間（7年間） 所得税法・消費税法
  - period: 対応完了後1年間
    scope: お問い合わせ内容
    text: お問い合わせ内容 対応完了後1年間 事業上の記録保持
  - period: 1日間
    scope: GitHub Actionsの非公開生成物
    text: GitHub Actionsの非公開生成物（暗号化メールアドレス、レポート原本） 1日間 人間による品質確認と承認後送信
  - period: 14か月間（GA4デフォルト）
    scope: Google Analytics データ
    text: Google Analytics データ 14か月間（GA4デフォルト） Google設定に準拠
  rights:
  - right: 開示請求
    text: '開示請求 : 当社が保有する個人情報の開示を求めることができます。'
  - right: 訂正・追加・削除
    text: '訂正・追加・削除 : 個人情報の内容が事実と異なる場合、訂正・追加・削除を求めることができます。'
  - right: 利用停止・消去
    text: '利用停止・消去 : 個人情報が利用目的の範囲を超えて利用されている場合、または不正に取得された場合、利用の停止または消去を求めることができます。'
  - right: 第三者提供の停止
    text: '第三者提供の停止 : 個人情報が本人の同意なく第三者に提供されている場合、提供の停止を求めることができます。'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Web3Forms インド 2023年DPDP Act 委託 氏名、メールアドレス、会社名、問い合わせ内容 本人同意（フォーム送信時）
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Visibility Index
provenance_date: '2026-11-09'
provider_name: AI Visibility Index
provider_slug: ai-visibility-index-dev
slug: ai-visibility-index-dev-privacy-policy
source_date: '2026-11-09'
source_filename: ai-visibility-index-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ai-visibility-index.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Visibility Index\naid: ai-visibility-index-dev\nurl: https://ai-visibility-index.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 氏名 お問い合わせフォーム 必須\n- category: contact\n  text: メールアドレス 改善診断レポート購入時（Stripe Checkout）、お問い合わせフォーム 必須\n- category: financial\n  text: 当社は、カード番号、有効期限、セキュリティコード等のカード情報を取得・保存しません。\n- category: device\n  text: ブラウザ情報（User-Agent） HTTPリクエストヘッダー サービス改善・互換性確保\n- category: behavioral\n  text: ページ閲覧データ Google Analytics 4（Cookie使用） アクセス解析\n- category: location\n  text: IPアドレス Webサーバーのアクセスログ 不正アクセス防止・レートリミット\n\
  purposes:\n- purpose: 本サービスの提供・運用・維持管理\n  text: 本サービスの提供・運用・維持管理（オンデマンドスキャン実行、レポート生成・送付を含む）\n- purpose: 決済処理・請求管理\n  text: 改善診断レポートの決済処理・請求管理\n- purpose: お問い合わせ対応\n  text: お問い合わせへの対応・返信\n- purpose: サービス改善・新機能開発\n  text: サービスの改善・新機能の開発\n- purpose: 外部AI APIによるスコア算出・レポート生成\n  text: 外部AI APIを用いたスコア算出・レポート生成\nretention:\n- scope: アクセスログ（IPアドレス等）\n  period: 90日間\n  text: アクセスログ（IPアドレス等） 90日間 不正アクセス調査\n- scope: 決済記録\n  period: 法令に定める保存期間（7年間）\n  text: 決済記録 法令に定める保存期間（7年間） 所得税法・消費税法\n- scope: お問い合わせ内容\n  period: 対応完了後1年間\n  text: お問い合わせ内容 対応完了後1年間 事業上の記録保持\n- scope: GitHub Actionsの非公開生成物\n  period: 1日間\n  text: GitHub Actionsの非公開生成物（暗号化メールアドレス、レポート原本） 1日間 人間による品質確認と承認後送信\n- scope: Google Analytics データ\n  period: 14か月間（GA4デフォルト）\n  text: Google Analytics データ 14か月間（GA4デフォルト） Google設定に準拠\nresidency: []\ntransfers:\n- mechanism: other\n  text: Web3Forms インド 2023年DPDP Act 委託 氏名、メールアドレス、会社名、問い合わせ内容 本人同意（フォーム送信時）\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text:\
  \ Anthropic PBC 米国 同上 委託 同上 本人同意（スキャン実行時） 有料API条件上の訓練不使用、DPA未締結（締結可能）\ndeletion:\n  route: お問い合わせフォーム または contact@pulse-digital.dev\n  text: 上記権利の行使を希望される場合は、 お問い合わせフォーム または contact@pulse-digital.dev までご連絡ください。\nrights:\n- right: 開示請求\n  text: '開示請求 : 当社が保有する個人情報の開示を求めることができます。'\n- right: 訂正・追加・削除\n  text: '訂正・追加・削除 : 個人情報の内容が事実と異なる場合、訂正・追加・削除を求めることができます。'\n- right: 利用停止・消去\n  text: '利用停止・消去 : 個人情報が利用目的の範囲を超えて利用されている場合、または不正に取得された場合、利用の停止または消去を求めることができます。'\n- right: 第三者提供の停止\n  text: '第三者提供の停止 : 個人情報が本人の同意なく第三者に提供されている場合、提供の停止を求めることができます。'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ai-visibility-index-dev/privacy/ai-visibility-index-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 23 quoted statements, read from AI Visibility Index's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Visibility
- Index
- Rankings
- EC104
---
