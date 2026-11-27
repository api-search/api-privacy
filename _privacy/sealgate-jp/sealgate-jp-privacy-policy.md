---
api_specs:
- filename: sealgate-jp-openapi-generated.yml
  format: yaml
  label: sealgate-jp API
  slug: sealgate-jp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sealgate-jp/openapi/_ae-authored/sealgate-jp-openapi-generated.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: '問い合わせ情報: フォームに入力された会社名、氏名、メールアドレス、電話番号、問い合わせ内容'
  - category: identifying
    text: 管理画面にログインする担当者のメールアドレス、表示名、会社名
  - category: financial
    text: '支払いの情報: 請求先の情報と支払いの状況。'
  - category: device
    text: '技術情報: IP アドレス、ブラウザの種類、API の呼び出し記録、エラーの発生状況'
  - category: behavioral
    text: 'アクセス情報: 本サービスのサイトの閲覧状況 (Google アナリティクスによる)'
  deletion:
    route: contact form
    text: お問い合わせフォームからご連絡ください。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision, authentication, billing
    text: 本サービスの提供、認証、請求
  - purpose: site usage analysis and improvement
    text: サイトの利用状況の分析と改善
  - purpose: fault detection and fraud prevention
    text: 障害の検知と対応、不正利用の防止
  - purpose: inquiry response
    text: 問い合わせへの対応
  rights:
  - right: access, correction, deletion
    text: 契約者およびその利用者は、自らの個人情報の開示、訂正、削除を求めることができます。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 当社は、法令に基づく場合を除き、個人情報を第三者に提供しません。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: sealgate-jp
provenance_date: '2026-11-10'
provider_name: sealgate-jp
provider_slug: sealgate-jp
slug: sealgate-jp-privacy-policy
source_date: '2026-11-10'
source_filename: sealgate-jp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sealgate.jp/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: sealgate-jp\naid: sealgate-jp\nurl: https://sealgate.jp/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: '問い合わせ情報: フォームに入力された会社名、氏名、メールアドレス、電話番号、問い合わせ内容'\n- category: identifying\n  text: 管理画面にログインする担当者のメールアドレス、表示名、会社名\n- category: financial\n  text: '支払いの情報: 請求先の情報と支払いの状況。'\n- category: device\n  text: '技術情報: IP アドレス、ブラウザの種類、API の呼び出し記録、エラーの発生状況'\n- category: behavioral\n  text: 'アクセス情報: 本サービスのサイトの閲覧状況 (Google アナリティクスによる)'\npurposes:\n- purpose: service provision, authentication, billing\n  text: 本サービスの提供、認証、請求\n- purpose: site usage\
  \ analysis and improvement\n  text: サイトの利用状況の分析と改善\n- purpose: fault detection and fraud prevention\n  text: 障害の検知と対応、不正利用の防止\n- purpose: inquiry response\n  text: 問い合わせへの対応\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact form\n  text: お問い合わせフォームからご連絡ください。\nrights:\n- right: access, correction, deletion\n  text: 契約者およびその利用者は、自らの個人情報の開示、訂正、削除を求めることができます。\nsale_or_sharing:\n  stance: conditional\n  text: 当社は、法令に基づく場合を除き、個人情報を第三者に提供しません。\n"
source_yaml_url: https://artifacts.apis.io/sealgate-jp/privacy/sealgate-jp-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from sealgate-jp's own page on 2026-11-10.
synthetic: false
tags:
- Authentication
- WebAuthn
- FIDO2
- Security
- Japan
---
