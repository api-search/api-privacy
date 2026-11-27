---
api_specs:
- filename: acall-event-api-api-openapi.yml
  format: yaml
  label: Acall Event API
  slug: acall-event-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-event-api-api-openapi.yml
- filename: acall-facility-api-api-openapi.yml
  format: yaml
  label: Acall Facility API
  slug: acall-facility-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-facility-api-api-openapi.yml
- filename: acall-gate-api-api-openapi.yml
  format: yaml
  label: Acall Gate API
  slug: acall-gate-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-gate-api-api-openapi.yml
- filename: acall-spot-api-api-openapi.yml
  format: yaml
  label: Acall Spot API
  slug: acall-spot-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-spot-api-api-openapi.yml
- filename: acall-spot-reservation-api-api-openapi.yml
  format: yaml
  label: Acall Spot Reservation API
  slug: acall-spot-reservation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-spot-reservation-api-api-openapi.yml
- filename: acall-user-api-api-openapi.yml
  format: yaml
  label: Acall User API
  slug: acall-user-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acall/openapi/acall-user-api-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 氏名、Eメールアドレス、部署名、会社名、企業住所、電話番号、内線番号及びアイコン顔画像
  - category: contact
    text: 氏名、住所及びEメールアドレス
  - category: communication
    text: サービスの利用履歴を分析し、サービスの開発、お客様へのリリース・障害などの個別対応時に役立てるため
  deletion:
    route: Contact by email on request
    text: 当社はお客様がご本人様から利用目的の通知、個人情報又は第三者提供記録の開示修正・削除などをご希望される場合には、ご本人であることを確認の上、遅延なく対応させていただきます。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contact and service communication
    text: 当社からのご連絡や業務のご案内やご質問に対する回答として、電子メールや資料のご送付に利用いたします。
  - purpose: Service analysis and development
    text: サービスの利用履歴を分析し、サービスの開発、お客様へのリリース・障害などの個別対応時に役立てるため
  - purpose: Employment and personnel management
    text: 雇用及び人事管理のため
  - purpose: Recruitment selection
    text: 選考および採否に関する連絡のため
  residency:
  - region: Japan
    text: 日本
  - region: United States
    text: アメリカ
  - region: Ireland
    text: アイルランド
  - region: Australia
    text: オーストラリア
  - region: Singapore
    text: シンガポール
  retention:
  - period: null
    scope: Personal data collected by programs
    text: 本サービスの機能提供に必要のない個人情報は正当な理由なく保存せず、必要な範囲でのみ保存及び利用し
  rights:
  - right: Disclosure, correction, deletion
    text: 個人情報又は第三者提供記録の開示修正・削除などをご希望される場合には、ご本人であることを確認の上、遅延なく対応させていただきます。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 当社は、お客様よりお預かりした個人情報を適切に管理し、次のいずれかに該当する場合を除き、個人情報を第三者に開示いたしません。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Acall
provenance_date: '2026-11-09'
provider_name: Acall
provider_slug: acall
slug: acall-privacy-policy
source_date: '2026-11-09'
source_filename: acall-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.acall.inc/privacypolicy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Acall\naid: acall\nurl: https://www.acall.inc/privacypolicy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 氏名、Eメールアドレス、部署名、会社名、企業住所、電話番号、内線番号及びアイコン顔画像\n- category: contact\n  text: 氏名、住所及びEメールアドレス\n- category: communication\n  text: サービスの利用履歴を分析し、サービスの開発、お客様へのリリース・障害などの個別対応時に役立てるため\npurposes:\n- purpose: Contact and service communication\n  text: 当社からのご連絡や業務のご案内やご質問に対する回答として、電子メールや資料のご送付に利用いたします。\n- purpose: Service analysis and development\n  text: サービスの利用履歴を分析し、サービスの開発、お客様へのリリース・障害などの個別対応時に役立てるため\n- purpose: Employment and personnel\
  \ management\n  text: 雇用及び人事管理のため\n- purpose: Recruitment selection\n  text: 選考および採否に関する連絡のため\nretention:\n- scope: Personal data collected by programs\n  period: null\n  text: 本サービスの機能提供に必要のない個人情報は正当な理由なく保存せず、必要な範囲でのみ保存及び利用し\nresidency:\n- region: Japan\n  text: 日本\n- region: United States\n  text: アメリカ\n- region: Ireland\n  text: アイルランド\n- region: Australia\n  text: オーストラリア\n- region: Singapore\n  text: シンガポール\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact by email on request\n  text: 当社はお客様がご本人様から利用目的の通知、個人情報又は第三者提供記録の開示修正・削除などをご希望される場合には、ご本人であることを確認の上、遅延なく対応させていただきます。\nrights:\n- right: Disclosure, correction, deletion\n  text: 個人情報又は第三者提供記録の開示修正・削除などをご希望される場合には、ご本人であることを確認の上、遅延なく対応させていただきます。\nsale_or_sharing:\n  stance: conditional\n  text: 当社は、お客様よりお預かりした個人情報を適切に管理し、次のいずれかに該当する場合を除き、個人情報を第三者に開示いたしません。\n"
source_yaml_url: https://artifacts.apis.io/acall/privacy/acall-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Acall's own page on 2026-11-09.
synthetic: false
tags:
- Workplace Management
- Visitor Management
- Meeting Room Booking
- Desk Booking
- Hybrid Work
- Access Control
- Facilities
- Smart Office
- Japan
- Software-as-a-Service
---
