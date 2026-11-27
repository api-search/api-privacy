---
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: お名前・会社名・部署名・役職
  - category: contact
    text: メールアドレス・電話番号
  - category: financial
    text: 請求書・お支払いに必要な情報
  - category: communication
    text: お問い合わせ・お打ち合わせ・ヒアリングの内容
  - category: device
    text: 本サービスのご利用状況に関する情報（アクセスログ・Cookie・利用デバイス情報等）
  - category: other
    text: お客様が AI への入力として送信したテキスト・画像・スクリーンショット等
  - category: identifying
    source: https://mcp.hakuto-0209.com/terms
    text: LINEのユーザーID・表示名・友だち追加日時
  - category: behavioral
    source: https://mcp.hakuto-0209.com/terms
    text: ライセンスごとの利用回数（累計・日別）
  - category: device
    source: https://mcp.hakuto-0209.com/terms
    text: 端末ID（配布パッケージをお使いの場合のみ）
  - category: communication
    source: https://mcp.hakuto-0209.com/terms
    text: お使いの場合のみ、送られた本文と時刻を保存します。
  - category: financial
    source: https://mcp.hakuto-0209.com/terms
    text: 当社が持つのは Stripe 上の顧客・契約の識別子と契約状態で、カード番号は持ちません。
  - category: other
    source: https://mcp.hakuto-0209.com/terms
    text: 日時・パス・ステータス・IPアドレス等の
  deletion:
    route: request to the contact window
    text: お客様ご本人は、当社に対し、ご自身の個人情報の開示・訂正・追加・削除・利用停止等を請求することができます。
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision and improvement
    text: 本サービスのご提供・運営・改善のため
  - purpose: inquiry response
    text: お客様からのお問い合わせ・ご依頼への対応のため
  - purpose: contract performance and billing
    text: ご契約に基づく業務遂行・代金請求のため
  - purpose: service notices
    text: 本サービスに関するご案内・お知らせ送付のため
  - purpose: AI proposals and implementation support
    text: AI による提案・要件整理・実装支援を行うため
  - purpose: terms violation response
    text: 利用規約等の違反対応のため
  - purpose: legal compliance
    text: 法令に基づく対応のため
  - purpose: license management and misuse prevention
    source: https://mcp.hakuto-0209.com/terms
    text: ライセンスの管理と不正利用の防止のため、次の情報を記録しています。
  retention:
  - period: null
    scope: license usage records
    source: https://mcp.hakuto-0209.com/terms
    text: ご契約の管理に使うため、自動では削除しません。
  - period: null
    scope: distinct source counts
    source: https://mcp.hakuto-0209.com/terms
    text: 8日で自動削除します。
  - period: null
    scope: device ID
    source: https://mcp.hakuto-0209.com/terms
    text: 60日使われなければ自動削除します。
  - period: null
    scope: LINE memo text
    source: https://mcp.hakuto-0209.com/terms
    text: 90日で自動削除します。
  - period: null
    scope: hosting operational logs
    source: https://mcp.hakuto-0209.com/terms
    text: 保存期間はホスティング事業者の定めによります。
  rights:
  - right: access, correction, addition, deletion, suspension of use
    text: 開示・訂正・追加・削除・利用停止等を請求することができます
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 当社は、以下の場合を除き、お客様の同意なく個人情報を第三者に提供しません。
  subprocessors:
    source: https://mcp.hakuto-0209.com/terms
    text: 決済は Stripe 社が処理します。
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HaneruTo
provenance_date: '2026-11-09'
provider_name: HaneruTo
provider_slug: hakuto-0209-com
slug: hakuto-0209-com-privacy-policy
source_date: '2026-11-09'
source_filename: hakuto-0209-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hakuto-0209.com/legal/hakuto-privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HaneruTo\naid: hakuto-0209-com\nurl: https://hakuto-0209.com/legal/hakuto-privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://hakuto-0209.com/legal/hakuto-privacy.html\n  - https://mcp.hakuto-0209.com/terms\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: お名前・会社名・部署名・役職\n- category: contact\n  text: メールアドレス・電話番号\n- category: financial\n  text: 請求書・お支払いに必要な情報\n- category: communication\n  text: お問い合わせ・お打ち合わせ・ヒアリングの内容\n- category: device\n  text: 本サービスのご利用状況に関する情報（アクセスログ・Cookie・利用デバイス情報等）\n- category: other\n  text: お客様が AI への入力として送信したテキスト・画像・スクリーンショット等\n\
  - category: identifying\n  text: LINEのユーザーID・表示名・友だち追加日時\n  source: https://mcp.hakuto-0209.com/terms\n- category: behavioral\n  text: ライセンスごとの利用回数（累計・日別）\n  source: https://mcp.hakuto-0209.com/terms\n- category: device\n  text: 端末ID（配布パッケージをお使いの場合のみ）\n  source: https://mcp.hakuto-0209.com/terms\n- category: communication\n  text: お使いの場合のみ、送られた本文と時刻を保存します。\n  source: https://mcp.hakuto-0209.com/terms\n- category: financial\n  text: 当社が持つのは Stripe 上の顧客・契約の識別子と契約状態で、カード番号は持ちません。\n  source: https://mcp.hakuto-0209.com/terms\n- category: other\n  text: 日時・パス・ステータス・IPアドレス等の\n  source: https://mcp.hakuto-0209.com/terms\npurposes:\n- purpose: service provision and improvement\n  text: 本サービスのご提供・運営・改善のため\n- purpose: inquiry response\n  text: お客様からのお問い合わせ・ご依頼への対応のため\n- purpose: contract performance and billing\n  text: ご契約に基づく業務遂行・代金請求のため\n- purpose: service notices\n  text: 本サービスに関するご案内・お知らせ送付のため\n- purpose: AI proposals and implementation support\n  text: AI による提案・要件整理・実装支援を行うため\n- purpose: terms\
  \ violation response\n  text: 利用規約等の違反対応のため\n- purpose: legal compliance\n  text: 法令に基づく対応のため\n- purpose: license management and misuse prevention\n  text: ライセンスの管理と不正利用の防止のため、次の情報を記録しています。\n  source: https://mcp.hakuto-0209.com/terms\nretention:\n- scope: license usage records\n  period: null\n  text: ご契約の管理に使うため、自動では削除しません。\n  source: https://mcp.hakuto-0209.com/terms\n- scope: distinct source counts\n  period: null\n  text: 8日で自動削除します。\n  source: https://mcp.hakuto-0209.com/terms\n- scope: device ID\n  period: null\n  text: 60日使われなければ自動削除します。\n  source: https://mcp.hakuto-0209.com/terms\n- scope: LINE memo text\n  period: null\n  text: 90日で自動削除します。\n  source: https://mcp.hakuto-0209.com/terms\n- scope: hosting operational logs\n  period: null\n  text: 保存期間はホスティング事業者の定めによります。\n  source: https://mcp.hakuto-0209.com/terms\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 決済は Stripe 社が処理します。\n  source: https://mcp.hakuto-0209.com/terms\ndpa:\n  available: null\n  url:\
  \ null\n  text: null\ndeletion:\n  route: request to the contact window\n  text: お客様ご本人は、当社に対し、ご自身の個人情報の開示・訂正・追加・削除・利用停止等を請求することができます。\nrights:\n- right: access, correction, addition, deletion, suspension of use\n  text: 開示・訂正・追加・削除・利用停止等を請求することができます\nsale_or_sharing:\n  stance: conditional\n  text: 当社は、以下の場合を除き、お客様の同意なく個人情報を第三者に提供しません。\n"
source_yaml_url: https://artifacts.apis.io/hakuto-0209-com/privacy/hakuto-0209-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from HaneruTo's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- MCP
- A2A
- Code Review
- Static Analysis
- Developer Tools
- Compliance
- Web Development
- Japan
- Agent-Native
---
