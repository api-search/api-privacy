---
api_specs:
- filename: bykaranteli-x402-api-openapi.yml
  format: yaml
  label: ByKaranteli X402 API
  slug: bykaranteli-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-x402-api-openapi.yml
- filename: bykaranteli-public-api-openapi.yml
  format: yaml
  label: ByKaranteli Public API
  slug: bykaranteli-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-public-api-openapi.yml
- filename: bykaranteli-public-api-openapi.yml
  format: yaml
  label: ByKaranteli Public API
  slug: bykaranteli-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-public-api-openapi.yml
- filename: bykaranteli-series-api-openapi.yml
  format: yaml
  label: ByKaranteli Series API
  slug: bykaranteli-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-series-api-openapi.yml
- filename: bykaranteli-usage-api-openapi.yml
  format: yaml
  label: ByKaranteli Usage API
  slug: bykaranteli-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bykaranteli/openapi/bykaranteli-usage-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address. It is the account identifier and the only contact detail we require.
  - category: identifying
    text: A password hash, if you set a password. We store an argon2id hash, never the password itself.
  - category: location
    text: the country Cloudflare attaches to that request
  - category: device
    text: the browser's user agent
  - category: financial
    text: the invoice, the on-chain transaction that paid it and every charge and return on the balance
  - category: communication
    text: the questions you ask, the answers you receive
  - category: behavioral
    text: Product events such as page views inside the member workspace and successful sign-ins.
  deletion:
    route: Account page (Data tab, Danger zone) on the site, or in the app under More tab, Account section, Delete account, or by writing to support@bykaranteli.com
    text: In the app, the More tab, Account section, Delete account does the same after you confirm with a fresh sign-in code; on the site use the Account page (the Data tab, Danger zone) or write to support@bykaranteli.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account access and sign-in
    text: Signing in with the six-digit code emailed to you opens the same account as on the site; no password is set.
  - purpose: abuse prevention and debugging
    text: exist for abuse prevention, rate limiting and debugging
  - purpose: billing and quota
    text: daily call counts per key for quota and billing
  - purpose: security audit
    text: Security and audit records for account actions such as sign-in, password reset and email verification.
  retention:
  - period: 7 days
    scope: Sign-in sessions
    text: 'Sign-in sessions: 7 days from sign-in, or until you sign out; expired rows are removed daily.'
  - period: 180 days
    scope: Product events
    text: 'Product events (page views and sign-ins inside the workspace): 180 days.'
  - period: 180 days
    scope: Security and audit records
    text: 'Security and audit records for account actions: 180 days.'
  - period: 90 days
    scope: Page-view beacon rows
    text: 'The page-view beacon rows: 90 days; the daily totals derived from them are kept.'
  rights:
  - right: access
    text: You can ask us for a copy of the personal data attached to your account
  - right: correction
    text: ask us to correct it
  - right: deletion
    text: delete the account from your Account page on the site (the Data tab, Danger zone).
  - right: complaint to supervisory authority
    text: If you are in a jurisdiction with a supervisory authority for data protection, you also have the right to complain to it.
  role:
    text: We are the controller of the personal data described here.
    value: controller
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
name: ByKaranteli
provenance_date: '2026-11-09'
provider_name: ByKaranteli
provider_slug: bykaranteli
slug: bykaranteli-privacy-policy
source_date: '2026-11-09'
source_filename: bykaranteli-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bykaranteli.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ByKaranteli\naid: bykaranteli\nurl: https://bykaranteli.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal data described here.\ndata_categories:\n- category: contact\n  text: Your email address. It is the account identifier and the only contact detail we require.\n- category: identifying\n  text: A password hash, if you set a password. We store an argon2id hash, never the password itself.\n- category: location\n  text: the country Cloudflare attaches to that request\n- category: device\n  text: the browser's user agent\n- category: financial\n\
  \  text: the invoice, the on-chain transaction that paid it and every charge and return on the balance\n- category: communication\n  text: the questions you ask, the answers you receive\n- category: behavioral\n  text: Product events such as page views inside the member workspace and successful sign-ins.\npurposes:\n- purpose: account access and sign-in\n  text: Signing in with the six-digit code emailed to you opens the same account as on the site; no password is\n    set.\n- purpose: abuse prevention and debugging\n  text: exist for abuse prevention, rate limiting and debugging\n- purpose: billing and quota\n  text: daily call counts per key for quota and billing\n- purpose: security audit\n  text: Security and audit records for account actions such as sign-in, password reset and email verification.\nretention:\n- scope: Sign-in sessions\n  period: 7 days\n  text: 'Sign-in sessions: 7 days from sign-in, or until you sign out; expired rows are removed daily.'\n- scope: Product events\n\
  \  period: 180 days\n  text: 'Product events (page views and sign-ins inside the workspace): 180 days.'\n- scope: Security and audit records\n  period: 180 days\n  text: 'Security and audit records for account actions: 180 days.'\n- scope: Page-view beacon rows\n  period: 90 days\n  text: 'The page-view beacon rows: 90 days; the daily totals derived from them are kept.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page (Data tab, Danger zone) on the site, or in the app under More tab, Account section, Delete\n    account, or by writing to support@bykaranteli.com\n  text: In the app, the More tab, Account section, Delete account does the same after you confirm with a fresh sign-in\n    code; on the site use the Account page (the Data tab, Danger zone) or write to support@bykaranteli.com.\nrights:\n- right: access\n  text: You can ask us for a copy of the personal data attached to\
  \ your account\n- right: correction\n  text: ask us to correct it\n- right: deletion\n  text: delete the account from your Account page on the site (the Data tab, Danger zone).\n- right: complaint to supervisory authority\n  text: If you are in a jurisdiction with a supervisory authority for data protection, you also have the right to\n    complain to it.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bykaranteli/privacy/bykaranteli-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 21 quoted statements, read from ByKaranteli's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Crypto Derivatives
- Market Data
- Funding Rates
- Open Interest
- Liquidations
- Options
- ETF Flows
- Financial Data
- MCP
- x402
- Agents
---
