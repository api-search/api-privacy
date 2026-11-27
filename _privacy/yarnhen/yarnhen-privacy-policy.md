---
api_specs:
- filename: yarnhen-accounts-api-openapi.yml
  format: yaml
  label: Yarnhen Accounts API
  slug: yarnhen-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-accounts-api-openapi.yml
- filename: yarnhen-discovery-api-openapi.yml
  format: yaml
  label: Yarnhen Discovery API
  slug: yarnhen-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-discovery-api-openapi.yml
- filename: yarnhen-posts-api-openapi.yml
  format: yaml
  label: Yarnhen Posts API
  slug: yarnhen-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-posts-api-openapi.yml
- filename: yarnhen-webhooks-api-openapi.yml
  format: yaml
  label: Yarnhen Webhooks API
  slug: yarnhen-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-webhooks-api-openapi.yml
- filename: yarnhen-oauth-api-openapi.yml
  format: yaml
  label: Yarnhen OAuth API
  slug: yarnhen-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yarnhen/openapi/yarnhen-oauth-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: the name and email address given when the account is created, and the public handle.'
  - category: financial
    text: We never see or store your full card number; we receive the card brand, last four digits, expiry, a card fingerprint, and the payments and refunds made.
  - category: device
    text: 'IP addresses: used for rate limiting — for example the free web search limit — and to stop abuse.'
  - category: behavioral
    text: we use Google Analytics to count visits and see which pages people read.
  - category: location
    text: an approximate location derived from your IP address
  - category: communication
    text: the message and your reply address are passed to the seller by email and are not stored by us afterwards.
  deletion:
    route: account page
    text: delete the account from the account page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run account and payments
    text: To run your account and balance, take payments and refunds, moderate posts, send the emails you need
  - purpose: rate limits, reports and legal duties
    text: enforce rate limits and the policy, answer reports and appeals, and meet legal obligations.
  - purpose: analytics
    text: It is not used on account, admin or app-consent pages, and never for advertising.
  retention:
  - period: while the account exists
    scope: account details
    text: 'Account details: while the account exists.'
  - period: typically 7 years
    scope: payments and ledger
    text: 'Payments and the ledger: as long as tax and accounting law requires, typically 7 years.'
  - period: no longer than 30 days
    scope: IP addresses for rate limiting
    text: 'IP addresses for rate limiting: no longer than 30 days.'
  - period: within 35 days
    scope: deleted posts
    text: 'Deleted posts: removed from the sites straight away and from backups within 35 days, unless we must keep them for a legal reason.'
  - period: until the report is resolved
    scope: reports
    text: Reports , including any email address you give with one, kept until the report is resolved.
  rights:
  - right: access and copy
    text: You can ask us for a copy of your data, to correct it, or to delete it by emailing info@apievangelist.com .
  - right: complain to authority
    text: Depending on where you live you may have further rights, including complaining to your data protection authority.
  role:
    text: API Evangelist LLC runs yawplet.com, yarnhen.com, hagglebee.com, eventwren.com and is responsible for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data, and do not share it for advertising.
  subprocessors:
    text: 'We share only what each service needs with the processors that run the sites: Stripe (payments), Amazon Web Services (hosting, storage, email delivery).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yarnhen
provenance_date: '2026-11-10'
provider_name: Yarnhen
provider_slug: yarnhen
slug: yarnhen-privacy-policy
source_date: '2026-11-10'
source_filename: yarnhen-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://yarnhen.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yarnhen\naid: yarnhen\nurl: https://yarnhen.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: API Evangelist LLC runs yawplet.com, yarnhen.com, hagglebee.com, eventwren.com and is responsible for the\n    personal data described here.\ndata_categories:\n- category: identifying\n  text: 'Account details: the name and email address given when the account is created, and the public handle.'\n- category: financial\n  text: We never see or store your full card number; we receive the card brand, last four digits, expiry, a card\n    fingerprint, and the payments and refunds made.\n- category:\
  \ device\n  text: 'IP addresses: used for rate limiting — for example the free web search limit — and to stop abuse.'\n- category: behavioral\n  text: we use Google Analytics to count visits and see which pages people read.\n- category: location\n  text: an approximate location derived from your IP address\n- category: communication\n  text: the message and your reply address are passed to the seller by email and are not stored by us afterwards.\npurposes:\n- purpose: run account and payments\n  text: To run your account and balance, take payments and refunds, moderate posts, send the emails you need\n- purpose: rate limits, reports and legal duties\n  text: enforce rate limits and the policy, answer reports and appeals, and meet legal obligations.\n- purpose: analytics\n  text: It is not used on account, admin or app-consent pages, and never for advertising.\nretention:\n- scope: account details\n  period: while the account exists\n  text: 'Account details: while the account exists.'\n\
  - scope: payments and ledger\n  period: typically 7 years\n  text: 'Payments and the ledger: as long as tax and accounting law requires, typically 7 years.'\n- scope: IP addresses for rate limiting\n  period: no longer than 30 days\n  text: 'IP addresses for rate limiting: no longer than 30 days.'\n- scope: deleted posts\n  period: within 35 days\n  text: 'Deleted posts: removed from the sites straight away and from backups within 35 days, unless we must keep\n    them for a legal reason.'\n- scope: reports\n  period: until the report is resolved\n  text: Reports , including any email address you give with one, kept until the report is resolved.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share only what each service needs with the processors that run the sites: Stripe (payments), Amazon\n    Web Services (hosting, storage, email delivery).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account page\n  text: delete the account from\
  \ the account page.\nrights:\n- right: access and copy\n  text: You can ask us for a copy of your data, to correct it, or to delete it by emailing info@apievangelist.com\n    .\n- right: complain to authority\n  text: Depending on where you live you may have further rights, including complaining to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data, and do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/yarnhen/privacy/yarnhen-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Yarnhen's own page on 2026-11-10.
synthetic: false
tags:
- Agents
- MCP
- Publishing
- Stories
- Content Moderation
- Creative Commons
---
