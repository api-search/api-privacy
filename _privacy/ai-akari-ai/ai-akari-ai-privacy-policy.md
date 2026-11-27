---
api_specs:
- filename: ai-akari-ai-a2a-api-openapi.yml
  format: yaml
  label: ai-akari-ai A2A API
  slug: ai-akari-ai-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-akari-ai/openapi/ai-akari-ai-a2a-api-openapi.yml
- filename: ai-akari-ai-mcp-api-openapi.yml
  format: yaml
  label: ai-akari-ai MCP API
  slug: ai-akari-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-akari-ai/openapi/ai-akari-ai-mcp-api-openapi.yml
- filename: ai-akari-ai-public-support-api-openapi.yml
  format: yaml
  label: ai-akari-ai Public support API
  slug: ai-akari-ai-public-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-akari-ai/openapi/ai-akari-ai-public-support-api-openapi.yml
- filename: ai-akari-ai-trust-api-openapi.yml
  format: yaml
  label: ai-akari-ai Trust API
  slug: ai-akari-ai-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-akari-ai/openapi/ai-akari-ai-trust-api-openapi.yml
- filename: ai-akari-ai-x402-api-openapi.yml
  format: yaml
  label: ai-akari-ai X402 API
  slug: ai-akari-ai-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ai-akari-ai/openapi/ai-akari-ai-x402-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: behavioral
    text: 公開MCPの初期化・ツール一覧・購入入口の要求時に、日時、経路、一般的なリクエスト情報、選択された商品識別子など、運用と不正防止に必要な最小限の記録を取得する場合があります。
  - category: financial
    text: 当社のMCPはカード番号を受け取らず、決済を自動実行しません。
  deletion:
    route: email
    text: 開示、訂正、削除に関する問い合わせはメールで受け付けます。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision, fraud prevention, improvement
    text: 購入入口の提供、デジタル商品の納品、問い合わせ対応、不正利用の防止、外部AIからの発見・利用状況の集計、サービス改善のために利用します。
  - purpose: no identifying use of AI conversations
    text: 個人を特定する目的で外部AIの会話内容を収集しません。
  retention:
  - period: null
    scope: operational records
    text: 運用記録は目的達成に必要な期間だけ保持し、不要になった情報は削除または匿名化します。
  rights:
  - right: disclosure, correction, deletion requests
    text: 開示、訂正、削除に関する問い合わせはメールで受け付けます。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 法令に基づく場合を除き、取得した個人情報を本人の同意なく第三者へ販売しません。
  subprocessors:
    text: 決済、配信、ホスティングなど提供に必要な範囲で委託先を利用する場合があります。
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ai-akari-ai
provenance_date: '2026-11-09'
provider_name: ai-akari-ai
provider_slug: ai-akari-ai
slug: ai-akari-ai-privacy-policy
source_date: '2026-11-09'
source_filename: ai-akari-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ai-akari.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ai-akari-ai\naid: ai-akari-ai\nurl: https://ai-akari.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: 公開MCPの初期化・ツール一覧・購入入口の要求時に、日時、経路、一般的なリクエスト情報、選択された商品識別子など、運用と不正防止に必要な最小限の記録を取得する場合があります。\n- category: financial\n  text: 当社のMCPはカード番号を受け取らず、決済を自動実行しません。\npurposes:\n- purpose: service provision, fraud prevention, improvement\n  text: 購入入口の提供、デジタル商品の納品、問い合わせ対応、不正利用の防止、外部AIからの発見・利用状況の集計、サービス改善のために利用します。\n- purpose: no identifying use of AI conversations\n  text: 個人を特定する目的で外部AIの会話内容を収集しません。\nretention:\n- scope: operational records\n\
  \  period: null\n  text: 運用記録は目的達成に必要な期間だけ保持し、不要になった情報は削除または匿名化します。\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 決済、配信、ホスティングなど提供に必要な範囲で委託先を利用する場合があります。\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: 開示、訂正、削除に関する問い合わせはメールで受け付けます。\nrights:\n- right: disclosure, correction, deletion requests\n  text: 開示、訂正、削除に関する問い合わせはメールで受け付けます。\nsale_or_sharing:\n  stance: conditional\n  text: 法令に基づく場合を除き、取得した個人情報を本人の同意なく第三者へ販売しません。\n"
source_yaml_url: https://artifacts.apis.io/ai-akari-ai/privacy/ai-akari-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 9 quoted statements, read from ai-akari-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Music
- DigitalTown
- Community
- Japanese
---
