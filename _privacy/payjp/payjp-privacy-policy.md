---
api_specs:
- filename: payjp-3d-secure-api-openapi.yml
  format: yaml
  label: PAY.JP 3D Secure API
  slug: payjp-3d-secure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-3d-secure-api-openapi.yml
- filename: payjp-account-api-openapi.yml
  format: yaml
  label: PAY.JP Account API
  slug: payjp-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-account-api-openapi.yml
- filename: payjp-balances-api-openapi.yml
  format: yaml
  label: PAY.JP Balances API
  slug: payjp-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-balances-api-openapi.yml
- filename: payjp-cards-api-openapi.yml
  format: yaml
  label: PAY.JP Cards API
  slug: payjp-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-cards-api-openapi.yml
- filename: payjp-charges-api-openapi.yml
  format: yaml
  label: PAY.JP Charges API
  slug: payjp-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-charges-api-openapi.yml
- filename: payjp-customers-api-openapi.yml
  format: yaml
  label: PAY.JP Customers API
  slug: payjp-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-customers-api-openapi.yml
- filename: payjp-events-api-openapi.yml
  format: yaml
  label: PAY.JP Events API
  slug: payjp-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-events-api-openapi.yml
- filename: payjp-plans-api-openapi.yml
  format: yaml
  label: PAY.JP Plans API
  slug: payjp-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-plans-api-openapi.yml
- filename: payjp-platform-api-openapi.yml
  format: yaml
  label: PAY.JP Platform API
  slug: payjp-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-platform-api-openapi.yml
- filename: payjp-statements-api-openapi.yml
  format: yaml
  label: PAY.JP Statements API
  slug: payjp-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-statements-api-openapi.yml
- filename: payjp-subscriptions-api-openapi.yml
  format: yaml
  label: PAY.JP Subscriptions API
  slug: payjp-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-subscriptions-api-openapi.yml
- filename: payjp-terms-api-openapi.yml
  format: yaml
  label: PAY.JP Terms API
  slug: payjp-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-terms-api-openapi.yml
- filename: payjp-tokens-api-openapi.yml
  format: yaml
  label: PAY.JP Tokens API
  slug: payjp-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-tokens-api-openapi.yml
- filename: payjp-transfers-api-openapi.yml
  format: yaml
  label: PAY.JP Transfers API
  slug: payjp-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-transfers-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: 氏名、生年月日その他の記述等により特定の個人を識別することができるもの
  - category: behavioral
    text: 閲覧履歴、位置情報、ウェブビーコン等の行動履歴、趣味嗜好等
  - category: device
    text: Cookie、ADID/IDFA、IPアドレス、MACアドレス、SSID、RDID
  - category: demographic
    text: 年齢、性別
  - category: financial
    text: 商品等購入・販売履歴
  deletion:
    route: Customer request for use cessation or deletion under the Personal Information Protection Act
    text: the Company will conduct use cessation, etc. without delay and notify the customer to that effect
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Responding to inquiries
    text: 当社サービスに関するご案内、お問い合わせ等への対応のため
  - purpose: Fraud prevention
    text: 当社サービスの不正利用の防止及び不正利用発生時の対応のため
  - purpose: Service improvement via data processing (including AI)
    text: データ処理技術（人工知能等を含みます）を用いて分析・処理し、社内業務改善・効率化、当社サービスの改善、新サービスの開発等に役立てるため
  - purpose: Statistical data creation
    text: 個人を識別できない形式に加工した統計データを作成するため
  residency:
  - region: foreign third country
    text: The Company may store personal information on the servers managed by a business operator in a third country.
  rights:
  - right: Disclosure
    text: the Company will disclose to the customer without delay after confirming that the request is from the customer
  - right: Correction, addition or deletion
    text: the Company will correct the contents of personal information
  - right: Suspension of use or deletion
    text: the Company will conduct use cessation, etc. without delay
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PAY.JP
provenance_date: '2026-11-10'
provider_name: PAY.JP
provider_slug: payjp
slug: payjp-privacy-policy
source_date: '2026-11-10'
source_filename: payjp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pay.co.jp/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PAY.JP\naid: payjp\nurl: https://pay.co.jp/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 氏名、生年月日その他の記述等により特定の個人を識別することができるもの\n- category: behavioral\n  text: 閲覧履歴、位置情報、ウェブビーコン等の行動履歴、趣味嗜好等\n- category: device\n  text: Cookie、ADID/IDFA、IPアドレス、MACアドレス、SSID、RDID\n- category: demographic\n  text: 年齢、性別\n- category: financial\n  text: 商品等購入・販売履歴\npurposes:\n- purpose: Responding to inquiries\n  text: 当社サービスに関するご案内、お問い合わせ等への対応のため\n- purpose: Fraud prevention\n  text: 当社サービスの不正利用の防止及び不正利用発生時の対応のため\n- purpose: Service improvement via data\
  \ processing (including AI)\n  text: データ処理技術（人工知能等を含みます）を用いて分析・処理し、社内業務改善・効率化、当社サービスの改善、新サービスの開発等に役立てるため\n- purpose: Statistical data creation\n  text: 個人を識別できない形式に加工した統計データを作成するため\nretention: []\nresidency:\n- region: foreign third country\n  text: The Company may store personal information on the servers managed by a business operator in a third country.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Customer request for use cessation or deletion under the Personal Information Protection Act\n  text: the Company will conduct use cessation, etc. without delay and notify the customer to that effect\nrights:\n- right: Disclosure\n  text: the Company will disclose to the customer without delay after confirming that the request is from the customer\n- right: Correction, addition or deletion\n  text: the Company will correct the contents of personal information\n- right: Suspension of use or deletion\n  text:\
  \ the Company will conduct use cessation, etc. without delay\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/payjp/privacy/payjp-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- deletion
- rights
summary_line: 14 quoted statements, read from PAY.JP's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Japan
- Credit Cards
- Subscription
- Tokenization
---
