---
api_specs:
- filename: compamir-com-conflicts-api-openapi.yml
  format: yaml
  label: COMPAMIR Conflicts API
  slug: compamir-com-conflicts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compamir-com/openapi/compamir-com-conflicts-api-openapi.yml
- filename: compamir-com-events-api-openapi.yml
  format: yaml
  label: COMPAMIR Events API
  slug: compamir-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compamir-com/openapi/compamir-com-events-api-openapi.yml
- filename: compamir-com-keys-api-openapi.yml
  format: yaml
  label: COMPAMIR Keys API
  slug: compamir-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compamir-com/openapi/compamir-com-keys-api-openapi.yml
- filename: compamir-com-meta-api-openapi.yml
  format: yaml
  label: COMPAMIR Meta API
  slug: compamir-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compamir-com/openapi/compamir-com-meta-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 氏名（表示名）、メールアドレス、プロフィール画像
  - category: contact
    text: メールアドレス
  - category: location
    text: 位置情報
  - category: device
    text: 端末識別子、IPアドレス、Cookie情報、閲覧履歴、検索履歴、位置情報、OSおよびブラウザの種類とバージョン
  - category: behavioral
    text: 閲覧履歴、検索履歴
  - category: communication
    text: お問い合わせ内容
  deletion:
    route: null
    text: アカウントが削除された場合、または利用目的が達成され保存の必要がなくなった場合は、法令により保存が義務付けられている情報を除き、遅滞なく当該個人情報を消去または不可逆的な匿名化処理を行います。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account registration and management
    text: 本サービスへの登録受付、本人確認、ユーザー認証、およびアカウント管理のため
  - purpose: Personalized content and search
    text: パーソナライズされたニュースの提供、検索結果の最適化、およびユーザーの興味関心に合わせたコンテンツ表示のため
  - purpose: Targeted advertising
    text: ターゲティング広告を含む広告の配信、表示、および効果測定のため
  - purpose: Generative AI model improvement
    text: 生成AIモデルの精度向上、アルゴリズムの改善、および統計データの作成のため
  retention:
  - period: null
    scope: Personal information
    text: 運営者は、利用目的の達成に必要な範囲内で個人情報を保存します。
  - period: null
    scope: After account deletion or purpose achieved
    text: アカウントが削除された場合、または利用目的が達成され保存の必要がなくなった場合は、法令により保存が義務付けられている情報を除き、遅滞なく当該個人情報を消去または不可逆的な匿名化処理を行います。
  rights:
  - right: Disclosure, correction, addition, deletion, suspension of use, erasure
    text: ユーザーは、運営者に対し、個人情報保護法の定めに基づき、自己の個人情報の開示、訂正、追加、削除、利用停止、または消去（以下「開示等」といいます。）を請求することができます。
  - right: Withdraw external service linkage
    text: ユーザーは、Google アカウント等の外部サービス側の設定を変更することにより、本サービスとの連携をいつでも解除し、情報の提供を停止することができます。
  - right: Unsubscribe from newsletter
    text: ユーザーは、配信される各メール内の購読解除リンクから、いつでも配信を停止することができます。
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
  - mechanism: SCC
    text: regulator-approved Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: COMPAMIR
provenance_date: '2026-11-09'
provider_name: COMPAMIR
provider_slug: compamir-com
slug: compamir-com-privacy-policy
source_date: '2026-11-09'
source_filename: compamir-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://compamir.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: COMPAMIR\naid: compamir-com\nurl: https://compamir.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 氏名（表示名）、メールアドレス、プロフィール画像\n- category: contact\n  text: メールアドレス\n- category: location\n  text: 位置情報\n- category: device\n  text: 端末識別子、IPアドレス、Cookie情報、閲覧履歴、検索履歴、位置情報、OSおよびブラウザの種類とバージョン\n- category: behavioral\n  text: 閲覧履歴、検索履歴\n- category: communication\n  text: お問い合わせ内容\npurposes:\n- purpose: Account registration and management\n  text: 本サービスへの登録受付、本人確認、ユーザー認証、およびアカウント管理のため\n- purpose: Personalized content and search\n  text:\
  \ パーソナライズされたニュースの提供、検索結果の最適化、およびユーザーの興味関心に合わせたコンテンツ表示のため\n- purpose: Targeted advertising\n  text: ターゲティング広告を含む広告の配信、表示、および効果測定のため\n- purpose: Generative AI model improvement\n  text: 生成AIモデルの精度向上、アルゴリズムの改善、および統計データの作成のため\nretention:\n- scope: Personal information\n  period: null\n  text: 運営者は、利用目的の達成に必要な範囲内で個人情報を保存します。\n- scope: After account deletion or purpose achieved\n  period: null\n  text: アカウントが削除された場合、または利用目的が達成され保存の必要がなくなった場合は、法令により保存が義務付けられている情報を除き、遅滞なく当該個人情報を消去または不可逆的な匿名化処理を行います。\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: regulator-approved Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: アカウントが削除された場合、または利用目的が達成され保存の必要がなくなった場合は、法令により保存が義務付けられている情報を除き、遅滞なく当該個人情報を消去または不可逆的な匿名化処理を行います。\nrights:\n- right: Disclosure, correction, addition, deletion, suspension of use, erasure\n  text: ユーザーは、運営者に対し、個人情報保護法の定めに基づき、自己の個人情報の開示、訂正、追加、削除、利用停止、または消去（以下「開示等」といいます。）を請求することができます。\n\
  - right: Withdraw external service linkage\n  text: ユーザーは、Google アカウント等の外部サービス側の設定を変更することにより、本サービスとの連携をいつでも解除し、情報の提供を停止することができます。\n- right: Unsubscribe from newsletter\n  text: ユーザーは、配信される各メール内の購読解除リンクから、いつでも配信を停止することができます。\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/compamir-com/privacy/compamir-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from COMPAMIR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- Media Monitoring
- Fact Comparison
- MCP
- AI Agents
- Japanese
- REST API
---
