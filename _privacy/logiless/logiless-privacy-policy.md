---
api_specs:
- filename: logiless-articles-api-openapi.yml
  format: yaml
  label: Logiless Articles API
  slug: logiless-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-articles-api-openapi.yml
- filename: logiless-inbound-deliveries-api-openapi.yml
  format: yaml
  label: Logiless Inbound Deliveries API
  slug: logiless-inbound-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-inbound-deliveries-api-openapi.yml
- filename: logiless-inter-warehouse-transfers-api-openapi.yml
  format: yaml
  label: Logiless Inter-Warehouse Transfers API
  slug: logiless-inter-warehouse-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-inter-warehouse-transfers-api-openapi.yml
- filename: logiless-inventory-api-openapi.yml
  format: yaml
  label: Logiless Inventory API
  slug: logiless-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-inventory-api-openapi.yml
- filename: logiless-locations-api-openapi.yml
  format: yaml
  label: Logiless Locations API
  slug: logiless-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-locations-api-openapi.yml
- filename: logiless-outbound-deliveries-api-openapi.yml
  format: yaml
  label: Logiless Outbound Deliveries API
  slug: logiless-outbound-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-outbound-deliveries-api-openapi.yml
- filename: logiless-sales-orders-api-openapi.yml
  format: yaml
  label: Logiless Sales Orders API
  slug: logiless-sales-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-sales-orders-api-openapi.yml
- filename: logiless-sales-returns-api-openapi.yml
  format: yaml
  label: Logiless Sales Returns API
  slug: logiless-sales-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-sales-returns-api-openapi.yml
- filename: logiless-suppliers-api-openapi.yml
  format: yaml
  label: Logiless Suppliers API
  slug: logiless-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-suppliers-api-openapi.yml
claim_count: 7
description: ''
doc:
  data_categories:
  - category: contact
    text: 氏名、住所、電話番号、 メールアドレス、所属先名、ログ情報、サービス利用履歴等
  - category: health
    text: 氏名、住所、電話番号、メールアドレス、生年月日、性別、健康診断結果、特定個人情報、容姿の写真等
  deletion:
    route: request via disclosure procedure document (PDF)
    text: 保有個人データに関する開示・訂正・削除又は利用停止等の措置については、「個人情報に関する開示等申請についてのご案内」（PDF）をご参照ください。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision
    text: 当社サービスの提供のため
  - purpose: billing
    text: 当社サービスのご利用料金の請求のため
  rights:
  - right: disclosure, correction, deletion, suspension of use
    text: 保有個人データに関する開示・訂正・削除又は利用停止等の措置については、「個人情報に関する開示等申請についてのご案内」（PDF）をご参照ください。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 当社は、原則として、個人データ（個人情報保護法第16条第3項により定義された「個人データ」をいい、以下同様とします。）を第三者に提供しません。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Logiless
provenance_date: '2026-11-09'
provider_name: Logiless
provider_slug: logiless
slug: logiless-privacy-policy
source_date: '2026-11-09'
source_filename: logiless-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.logiless.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Logiless\naid: logiless\nurl: https://www.logiless.com/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 氏名、住所、電話番号、 メールアドレス、所属先名、ログ情報、サービス利用履歴等\n- category: health\n  text: 氏名、住所、電話番号、メールアドレス、生年月日、性別、健康診断結果、特定個人情報、容姿の写真等\npurposes:\n- purpose: service provision\n  text: 当社サービスの提供のため\n- purpose: billing\n  text: 当社サービスのご利用料金の請求のため\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request via disclosure procedure\
  \ document (PDF)\n  text: 保有個人データに関する開示・訂正・削除又は利用停止等の措置については、「個人情報に関する開示等申請についてのご案内」（PDF）をご参照ください。\nrights:\n- right: disclosure, correction, deletion, suspension of use\n  text: 保有個人データに関する開示・訂正・削除又は利用停止等の措置については、「個人情報に関する開示等申請についてのご案内」（PDF）をご参照ください。\nsale_or_sharing:\n  stance: conditional\n  text: 当社は、原則として、個人データ（個人情報保護法第16条第3項により定義された「個人データ」をいい、以下同様とします。）を第三者に提供しません。\n"
source_yaml_url: https://artifacts.apis.io/logiless/privacy/logiless-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
- sale_or_sharing
summary_line: 7 quoted statements, read from Logiless's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- E-Commerce
- Order Management
- Warehouse Management
- Inventory
- Fulfillment
- Shipping
- OMS
- WMS
- Japan
---
