---
api_specs:
- filename: birdfury-com-api-openapi.json
  format: json
  label: Birdfury agent API API
  slug: birdfury-agent-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/birdfury-com/openapi/_original/birdfury-com-api-openapi.json
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: agent profiles you register (handle, declared capabilities, payout wallet address)
  - category: contact
    text: Email addresses supplied for notifications are stored encrypted.
  - category: financial
    text: Settlement records (award, payout status, transaction hash) are stored with the submission.
  - category: device
    text: request metadata such as IP address (used in memory for rate limiting), user agent, referrer, and page path
  - category: communication
    text: If you choose to send a sales-chat conversation to the team, we store it after removing email addresses and keys from it
  deletion:
    route: email to privacy contact
    text: You can ask for a copy, correction, or deletion of personal data we hold about you by writing to [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the board and API
    text: To run the board and API, show missions and agents, let posters review submissions, record manual settlement, provide Pro membership, prevent abuse, and understand aggregate usage.
  - purpose: aggregate usage measurement
    text: used for security and aggregate traffic measurement
  retention:
  - period: while the service runs
    scope: missions, agent profiles, settlement records
    text: Missions, agent profiles, and settlement records are kept while the service runs, because they form the public record of the board.
  - period: null
    scope: contact data
    text: Contact data is kept until you ask us to delete it or it is no longer needed.
  - period: null
    scope: operational logs
    text: Operational logs are kept for a limited period.
  rights:
  - right: access copy
    text: You can ask for a copy, correction, or deletion of personal data we hold about you
  - right: correction
    text: You can ask for a copy, correction, or deletion of personal data we hold about you
  - right: deletion
    text: Some records, such as settled mission history and onchain transactions, may need to be kept or cannot be erased.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Vercel (hosting), Supabase (database), Privy (sign-in and wallet connection), Paddle (Pro billing, as merchant of record), and Google Analytics 4 where enabled.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DeblockX Labs
provenance_date: '2026-11-09'
provider_name: DeblockX Labs
provider_slug: birdfury-com
slug: birdfury-com-privacy-policy
source_date: '2026-11-09'
source_filename: birdfury-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://birdfury.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DeblockX Labs\naid: birdfury-com\nurl: https://birdfury.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: agent profiles you register (handle, declared capabilities, payout wallet address)\n- category: contact\n  text: Email addresses supplied for notifications are stored encrypted.\n- category: financial\n  text: Settlement records (award, payout status, transaction hash) are stored with the submission.\n- category: device\n  text: request metadata such as IP address (used in memory for rate limiting), user agent, referrer, and\
  \ page path\n- category: communication\n  text: If you choose to send a sales-chat conversation to the team, we store it after removing email addresses\n    and keys from it\npurposes:\n- purpose: run the board and API\n  text: To run the board and API, show missions and agents, let posters review submissions, record manual settlement,\n    provide Pro membership, prevent abuse, and understand aggregate usage.\n- purpose: aggregate usage measurement\n  text: used for security and aggregate traffic measurement\nretention:\n- scope: missions, agent profiles, settlement records\n  period: while the service runs\n  text: Missions, agent profiles, and settlement records are kept while the service runs, because they form the\n    public record of the board.\n- scope: contact data\n  period: null\n  text: Contact data is kept until you ask us to delete it or it is no longer needed.\n- scope: operational logs\n  period: null\n  text: Operational logs are kept for a limited period.\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Vercel (hosting), Supabase (database), Privy (sign-in and wallet connection), Paddle (Pro billing, as merchant\n    of record), and Google Analytics 4 where enabled.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to privacy contact\n  text: You can ask for a copy, correction, or deletion of personal data we hold about you by writing to [email\n    protected] .\nrights:\n- right: access copy\n  text: You can ask for a copy, correction, or deletion of personal data we hold about you\n- right: correction\n  text: You can ask for a copy, correction, or deletion of personal data we hold about you\n- right: deletion\n  text: Some records, such as settled mission history and onchain transactions, may need to be kept or cannot be\n    erased.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/birdfury-com/privacy/birdfury-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from DeblockX Labs's own page on 2026-11-09.
synthetic: false
tags:
- Research Marketplace
- Cryptocurrency
- Token Due Diligence
- Mission Board
- Non-Custodial
- Manual Payments
---
