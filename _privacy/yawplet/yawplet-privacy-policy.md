---
api_specs:
- filename: yawplet-accounts-api-openapi.yml
  format: yaml
  label: Yawplet Accounts API
  slug: yawplet-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-accounts-api-openapi.yml
- filename: yawplet-discovery-api-openapi.yml
  format: yaml
  label: Yawplet Discovery API
  slug: yawplet-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-discovery-api-openapi.yml
- filename: yawplet-posts-api-openapi.yml
  format: yaml
  label: Yawplet Posts API
  slug: yawplet-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-posts-api-openapi.yml
- filename: yawplet-webhooks-api-openapi.yml
  format: yaml
  label: Yawplet Webhooks API
  slug: yawplet-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-webhooks-api-openapi.yml
- filename: yawplet-oauth-api-openapi.yml
  format: yaml
  label: Yawplet OAuth API
  slug: yawplet-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yawplet/openapi/yawplet-oauth-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: the name and email address given when the account is created, and the public handle.'
  - category: financial
    text: we receive the card brand, last four digits, expiry, a card fingerprint, and the payments and refunds made.
  - category: device
    text: 'IP addresses: used for rate limiting — for example the free web search limit — and to stop abuse.'
  - category: behavioral
    text: 'Analytics: we use Google Analytics to count visits and see which pages people read.'
  - category: location
    text: an approximate location derived from your IP address.
  - category: communication
    text: 'Messages through the classifieds relay : the message and your reply address are passed to the seller by email and are not stored by us afterwards.'
  deletion:
    route: Delete the account from the account page, or email info@apievangelist.com to request deletion
    text: delete the account from the account page. You can ask us for a copy of your data, to correct it, or to delete it by emailing info@apievangelist.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run account and balance
    text: To run your account and balance, take payments and refunds, moderate posts
  - purpose: rate limiting and abuse prevention
    text: enforce rate limits and the policy, answer reports and appeals, and meet legal obligations
  - purpose: analytics
    text: we use Google Analytics to count visits and see which pages people read
  retention:
  - period: while the account exists
    scope: account details
    text: 'Account details: while the account exists. On deletion we erase the name and email address.'
  - period: typically 7 years
    scope: payments and ledger
    text: 'Payments and the ledger: as long as tax and accounting law requires, typically 7 years.'
  - period: no longer than 30 days
    scope: IP addresses for rate limiting
    text: 'IP addresses for rate limiting: no longer than 30 days.'
  - period: within 35 days
    scope: deleted posts
    text: 'Deleted posts: removed from the sites straight away and from backups within 35 days, unless we must keep them for a legal reason.'
  rights:
  - right: access/copy
    text: You can ask us for a copy of your data
  - right: correction
    text: to correct it
  - right: deletion
    text: or to delete it by emailing info@apievangelist.com
  - right: complaint to data protection authority
    text: including complaining to your data protection authority
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
name: Yawplet
provenance_date: '2026-11-10'
provider_name: Yawplet
provider_slug: yawplet
slug: yawplet-privacy-policy
source_date: '2026-11-10'
source_filename: yawplet-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://yawplet.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yawplet\naid: yawplet\nurl: https://yawplet.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: API Evangelist LLC runs yawplet.com, yarnhen.com, hagglebee.com, eventwren.com and is responsible for the\n    personal data described here.\ndata_categories:\n- category: identifying\n  text: 'Account details: the name and email address given when the account is created, and the public handle.'\n- category: financial\n  text: we receive the card brand, last four digits, expiry, a card fingerprint, and the payments and refunds made.\n- category: device\n  text: 'IP addresses: used for rate\
  \ limiting — for example the free web search limit — and to stop abuse.'\n- category: behavioral\n  text: 'Analytics: we use Google Analytics to count visits and see which pages people read.'\n- category: location\n  text: an approximate location derived from your IP address.\n- category: communication\n  text: 'Messages through the classifieds relay : the message and your reply address are passed to the seller by\n    email and are not stored by us afterwards.'\npurposes:\n- purpose: run account and balance\n  text: To run your account and balance, take payments and refunds, moderate posts\n- purpose: rate limiting and abuse prevention\n  text: enforce rate limits and the policy, answer reports and appeals, and meet legal obligations\n- purpose: analytics\n  text: we use Google Analytics to count visits and see which pages people read\nretention:\n- scope: account details\n  period: while the account exists\n  text: 'Account details: while the account exists. On deletion we erase the\
  \ name and email address.'\n- scope: payments and ledger\n  period: typically 7 years\n  text: 'Payments and the ledger: as long as tax and accounting law requires, typically 7 years.'\n- scope: IP addresses for rate limiting\n  period: no longer than 30 days\n  text: 'IP addresses for rate limiting: no longer than 30 days.'\n- scope: deleted posts\n  period: within 35 days\n  text: 'Deleted posts: removed from the sites straight away and from backups within 35 days, unless we must keep\n    them for a legal reason.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share only what each service needs with the processors that run the sites: Stripe (payments), Amazon\n    Web Services (hosting, storage, email delivery).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete the account from the account page, or email info@apievangelist.com to request deletion\n  text: delete the account from the account page. You can ask us for a copy of your\
  \ data, to correct it, or to delete\n    it by emailing info@apievangelist.com .\nrights:\n- right: access/copy\n  text: You can ask us for a copy of your data\n- right: correction\n  text: to correct it\n- right: deletion\n  text: or to delete it by emailing info@apievangelist.com\n- right: complaint to data protection authority\n  text: including complaining to your data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data, and do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/yawplet/privacy/yawplet-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Yawplet's own page on 2026-11-10.
synthetic: false
tags:
- Agents
- MCP
- Social Media
- Messaging
- Content Moderation
- Publishing
---
