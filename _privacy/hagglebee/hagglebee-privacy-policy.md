---
api_specs:
- filename: hagglebee-accounts-api-openapi.yml
  format: yaml
  label: Hagglebee Accounts API
  slug: hagglebee-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-accounts-api-openapi.yml
- filename: hagglebee-discovery-api-openapi.yml
  format: yaml
  label: Hagglebee Discovery API
  slug: hagglebee-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-discovery-api-openapi.yml
- filename: hagglebee-posts-api-openapi.yml
  format: yaml
  label: Hagglebee Posts API
  slug: hagglebee-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-posts-api-openapi.yml
- filename: hagglebee-webhooks-api-openapi.yml
  format: yaml
  label: Hagglebee Webhooks API
  slug: hagglebee-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-webhooks-api-openapi.yml
- filename: hagglebee-oauth-api-openapi.yml
  format: yaml
  label: Hagglebee OAuth API
  slug: hagglebee-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hagglebee/openapi/hagglebee-oauth-api-openapi.yml
claim_count: 20
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
  - category: communication
    text: 'Messages through the classifieds relay : the message and your reply address are passed to the seller by email and are not stored by us afterwards.'
  deletion:
    route: Delete the account from the account page, or email info@apievangelist.com to request deletion.
    text: delete the account from the account page. You can ask us for a copy of your data, to correct it, or to delete it by emailing info@apievangelist.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run account and balance
    text: To run your account and balance, take payments and refunds, moderate posts, send the emails you need
  - purpose: Rate limiting and abuse prevention
    text: enforce rate limits and the policy, answer reports and appeals, and meet legal obligations.
  - purpose: Analytics
    text: we use Google Analytics to count visits and see which pages people read.
  retention:
  - period: while the account exists
    scope: Account details
    text: 'Account details: while the account exists. On deletion we erase the name and email address.'
  - period: typically 7 years
    scope: Payments and ledger
    text: 'Payments and the ledger: as long as tax and accounting law requires, typically 7 years.'
  - period: no longer than 30 days
    scope: IP addresses for rate limiting
    text: 'IP addresses for rate limiting: no longer than 30 days.'
  - period: within 35 days
    scope: Deleted posts
    text: 'Deleted posts: removed from the sites straight away and from backups within 35 days, unless we must keep them for a legal reason.'
  rights:
  - right: Access/copy
    text: You can ask us for a copy of your data
  - right: Correction
    text: to correct it
  - right: Deletion
    text: or to delete it by emailing info@apievangelist.com
  - right: Complain to authority
    text: including complaining to your data protection authority.
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
name: Hagglebee
provenance_date: '2026-11-09'
provider_name: Hagglebee
provider_slug: hagglebee
slug: hagglebee-privacy-policy
source_date: '2026-11-09'
source_filename: hagglebee-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hagglebee.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hagglebee\naid: hagglebee\nurl: https://hagglebee.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: API Evangelist LLC runs yawplet.com, yarnhen.com, hagglebee.com, eventwren.com and is responsible for the\n    personal data described here.\ndata_categories:\n- category: identifying\n  text: 'Account details: the name and email address given when the account is created, and the public handle.'\n- category: financial\n  text: we receive the card brand, last four digits, expiry, a card fingerprint, and the payments and refunds made.\n- category: device\n  text: 'IP addresses: used\
  \ for rate limiting — for example the free web search limit — and to stop abuse.'\n- category: behavioral\n  text: 'Analytics: we use Google Analytics to count visits and see which pages people read.'\n- category: communication\n  text: 'Messages through the classifieds relay : the message and your reply address are passed to the seller by\n    email and are not stored by us afterwards.'\npurposes:\n- purpose: Run account and balance\n  text: To run your account and balance, take payments and refunds, moderate posts, send the emails you need\n- purpose: Rate limiting and abuse prevention\n  text: enforce rate limits and the policy, answer reports and appeals, and meet legal obligations.\n- purpose: Analytics\n  text: we use Google Analytics to count visits and see which pages people read.\nretention:\n- scope: Account details\n  period: while the account exists\n  text: 'Account details: while the account exists. On deletion we erase the name and email address.'\n- scope: Payments and\
  \ ledger\n  period: typically 7 years\n  text: 'Payments and the ledger: as long as tax and accounting law requires, typically 7 years.'\n- scope: IP addresses for rate limiting\n  period: no longer than 30 days\n  text: 'IP addresses for rate limiting: no longer than 30 days.'\n- scope: Deleted posts\n  period: within 35 days\n  text: 'Deleted posts: removed from the sites straight away and from backups within 35 days, unless we must keep\n    them for a legal reason.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share only what each service needs with the processors that run the sites: Stripe (payments), Amazon\n    Web Services (hosting, storage, email delivery).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete the account from the account page, or email info@apievangelist.com to request deletion.\n  text: delete the account from the account page. You can ask us for a copy of your data, to correct it, or to delete\n    it by\
  \ emailing info@apievangelist.com .\nrights:\n- right: Access/copy\n  text: You can ask us for a copy of your data\n- right: Correction\n  text: to correct it\n- right: Deletion\n  text: or to delete it by emailing info@apievangelist.com\n- right: Complain to authority\n  text: including complaining to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data, and do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/hagglebee/privacy/hagglebee-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Hagglebee's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- MCP
- Classifieds
- Marketplace
- Content Moderation
- Publishing
---
