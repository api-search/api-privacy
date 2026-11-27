---
claim_count: 12
description: ''
doc:
  data_categories:
  - category: other
    text: Your affiliate network API credentials and OAuth tokens.
  - category: contact
    text: For paying subscribers only, one billing email address.
  - category: other
    text: Per-tenant brand and client-strategy context.
  deletion:
    route: delete hosted account from dashboard
    text: 'Hosted: disconnect a network from the dashboard, or delete the whole account and everything stored with it, at any time.'
  dpa:
    available: false
    text: There is no SOC 2 or ISO 27001 certification and no data processing agreement on offer at present.
    url: null
  purposes:
  - purpose: serving the user
    text: Your affiliate data is not used for analytics, for training, or for any purpose beyond serving you.
  - purpose: serving a request
    text: Credentials are decrypted only at call time, in memory, to serve the request that needs them.
  retention:
  - period: null
    scope: hosted account deletion
    text: Deleting your hosted account deletes the encrypted credentials, the key protecting them, the account record, and the subscription record including the billing email.
  rights:
  - right: delete account
    text: delete the whole account and everything stored with it, at any time
  - right: disconnect network
    text: disconnect a network from the dashboard
  role:
    text: For the hosted tier we act as a processor of the data you store with us.
    value: processor
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Beyond the affiliate networks themselves, the hosted tier uses three sub-processors: Cloudflare (compute, storage, and the credential vault), Stripe (payments and billing), and Resend (sign-in and digest email).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Affiliate MCP
provenance_date: '2026-11-09'
provider_name: Affiliate MCP
provider_slug: agenticaffiliate-ai
slug: agenticaffiliate-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agenticaffiliate-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenticaffiliate.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Affiliate MCP\naid: agenticaffiliate-ai\nurl: https://agenticaffiliate.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: For the hosted tier we act as a processor of the data you store with us.\ndata_categories:\n- category: other\n  text: Your affiliate network API credentials and OAuth tokens.\n- category: contact\n  text: For paying subscribers only, one billing email address.\n- category: other\n  text: Per-tenant brand and client-strategy context.\npurposes:\n- purpose: serving the user\n  text: Your affiliate data is not used for analytics, for training, or for any purpose beyond\
  \ serving you.\n- purpose: serving a request\n  text: Credentials are decrypted only at call time, in memory, to serve the request that needs them.\nretention:\n- scope: hosted account deletion\n  period: null\n  text: Deleting your hosted account deletes the encrypted credentials, the key protecting them, the account record,\n    and the subscription record including the billing email.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Beyond the affiliate networks themselves, the hosted tier uses three sub-processors: Cloudflare (compute,\n    storage, and the credential vault), Stripe (payments and billing), and Resend (sign-in and digest email).'\ndpa:\n  available: false\n  url: null\n  text: There is no SOC 2 or ISO 27001 certification and no data processing agreement on offer at present.\ndeletion:\n  route: delete hosted account from dashboard\n  text: 'Hosted: disconnect a network from the dashboard, or delete the whole account and everything stored with\n  \
  \  it, at any time.'\nrights:\n- right: delete account\n  text: delete the whole account and everything stored with it, at any time\n- right: disconnect network\n  text: disconnect a network from the dashboard\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agenticaffiliate-ai/privacy/agenticaffiliate-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
summary_line: 12 quoted statements, read from Affiliate MCP's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- Automation
- Artificial Intelligence
- Open Source
- Local-First
---
