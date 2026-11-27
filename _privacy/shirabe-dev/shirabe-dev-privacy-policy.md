---
api_specs:
- filename: shirabe-dev-calendar-api-openapi.yml
  format: yaml
  label: shirabe-dev Calendar API
  slug: shirabe-dev-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shirabe-dev/openapi/shirabe-dev-calendar-api-openapi.yml
- filename: shirabe-dev-hub-api-openapi.yml
  format: yaml
  label: shirabe-dev Hub API
  slug: shirabe-dev-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shirabe-dev/openapi/shirabe-dev-hub-api-openapi.yml
- filename: shirabe-dev-system-api-openapi.yml
  format: yaml
  label: shirabe-dev System API
  slug: shirabe-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shirabe-dev/openapi/shirabe-dev-system-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: APIキー 利用者を識別するために発行・保存します
  - category: other
    text: APIリクエストに含まれる入力（住所・氏名・法人名・日付等）。レスポンス生成のためにのみ処理します
  - category: device
    text: IPアドレス、リクエストURL、タイムスタンプ、レスポンスステータス（リクエスト本文は含みません）
  - category: financial
    text: Stripe経由の決済情報（当社はカード情報を直接保持しません）
  deletion:
    route: request to contact address
    text: 開示・訂正・削除を請求することができます
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision and operation
    text: サービスの提供・運営
  - purpose: usage-based billing
    text: 利用量に基づく課金処理
  - purpose: fraud detection and prevention
    text: 不正利用の検知・防止
  - purpose: service improvement
    text: サービスの改善・品質向上
  retention:
  - period: 最長1時間程度
    scope: input data
    text: 処理高速化のための短期キャッシュ〔最長1時間程度〕を除き、レスポンス生成後に破棄します
  - period: 90日間
    scope: request logs
    text: リクエストログ 90日間
  - period: サービス利用期間中および解約後1年間
    scope: usage data
    text: 利用量データ サービス利用期間中および解約後1年間
  - period: 法令に基づく保持期間
    scope: payment-related data
    text: 決済関連データ 法令に基づく保持期間
  rights:
  - right: access, correction and deletion
    text: 開示・訂正・削除を請求することができます
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 当社は、以下の場合を除き、個人情報を第三者に提供しません。
  subprocessors:
    text: Stripe, Inc. 課金処理のため
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: shirabe-dev
provenance_date: '2026-11-10'
provider_name: shirabe-dev
provider_slug: shirabe-dev
slug: shirabe-dev-privacy-policy
source_date: '2026-11-10'
source_filename: shirabe-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shirabe.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: shirabe-dev\naid: shirabe-dev\nurl: https://shirabe.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: APIキー 利用者を識別するために発行・保存します\n- category: other\n  text: APIリクエストに含まれる入力（住所・氏名・法人名・日付等）。レスポンス生成のためにのみ処理します\n- category: device\n  text: IPアドレス、リクエストURL、タイムスタンプ、レスポンスステータス（リクエスト本文は含みません）\n- category: financial\n  text: Stripe経由の決済情報（当社はカード情報を直接保持しません）\npurposes:\n- purpose: service provision and operation\n  text: サービスの提供・運営\n- purpose: usage-based billing\n  text: 利用量に基づく課金処理\n- purpose: fraud detection and prevention\n  text: 不正利用の検知・防止\n\
  - purpose: service improvement\n  text: サービスの改善・品質向上\nretention:\n- scope: input data\n  period: 最長1時間程度\n  text: 処理高速化のための短期キャッシュ〔最長1時間程度〕を除き、レスポンス生成後に破棄します\n- scope: request logs\n  period: 90日間\n  text: リクエストログ 90日間\n- scope: usage data\n  period: サービス利用期間中および解約後1年間\n  text: 利用量データ サービス利用期間中および解約後1年間\n- scope: payment-related data\n  period: 法令に基づく保持期間\n  text: 決済関連データ 法令に基づく保持期間\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe, Inc. 課金処理のため\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to contact address\n  text: 開示・訂正・削除を請求することができます\nrights:\n- right: access, correction and deletion\n  text: 開示・訂正・削除を請求することができます\nsale_or_sharing:\n  stance: conditional\n  text: 当社は、以下の場合を除き、個人情報を第三者に提供しません。\n"
source_yaml_url: https://artifacts.apis.io/shirabe-dev/privacy/shirabe-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from shirabe-dev's own page on 2026-11-10.
synthetic: false
tags:
- API Platform
- Japanese Data
- Free Tier
- AI Integration
---
