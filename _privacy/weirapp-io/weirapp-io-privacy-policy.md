---
api_specs:
- filename: weirapp-io-account-api-openapi.yml
  format: yaml
  label: weirapp-io Account API
  slug: weirapp-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-account-api-openapi.yml
- filename: weirapp-io-monitors-api-openapi.yml
  format: yaml
  label: weirapp-io Monitors API
  slug: weirapp-io-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-monitors-api-openapi.yml
- filename: weirapp-io-reddit-api-openapi.yml
  format: yaml
  label: weirapp-io Reddit API
  slug: weirapp-io-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-reddit-api-openapi.yml
- filename: weirapp-io-system-api-openapi.yml
  format: yaml
  label: weirapp-io System API
  slug: weirapp-io-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-system-api-openapi.yml
- filename: weirapp-io-webhooks-api-openapi.yml
  format: yaml
  label: weirapp-io Webhooks API
  slug: weirapp-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-webhooks-api-openapi.yml
- filename: weirapp-io-x-api-openapi.yml
  format: yaml
  label: weirapp-io X API
  slug: weirapp-io-x-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weirapp-io/openapi/weirapp-io-x-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, and — if you sign in with Google or GitHub — the profile picture address that provider shares.
  - category: contact
    text: invitations you send (the invitee's email and a hash of the invitation link)
  - category: device
    text: the client's user agent
  - category: financial
    text: Dodo Payments collects your payment details as Merchant of Record. We receive a record of each purchase — amount, credits, status, and Dodo's reference — but never your full card number.
  - category: behavioral
    text: Monitors and webhooks. The searches and targets you set up, the results they find, your webhook endpoint addresses, signing secrets (encrypted), and a record of each delivery attempt and its response code.
  - category: communication
    text: Support messages you send us, and our replies.
  deletion:
    route: Delete a workspace from its settings, or email support@weirapp.io
    text: You can update your name in the dashboard and delete a workspace from its settings; for anything else, email support@weirapp.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'To provide the Service: authenticate you, run your requests and monitors, deliver webhooks, and meter and bill usage — because it is necessary to perform our contract with you.'
  - purpose: Security and fairness
    text: 'To keep the Service secure and fair: detect abuse, enforce rate limits and the Acceptable Use Policy , and investigate incidents'
  - purpose: Support and account messages
    text: To support you and send messages about your account and the Service, such as security notices and changes to these terms
  - purpose: Aggregate usage analytics
    text: To understand, in aggregate, how the Service is used so we can improve it — in our legitimate interest. This uses de-identified, aggregated figures.
  - purpose: Legal obligations
    text: To meet legal, tax, and accounting obligations.
  residency:
  - region: Japan
    text: Our primary database is in Japan.
  retention:
  - period: 30 to 60 days
    scope: API request logs
    text: 'API request logs: 30 to 60 days .'
  - period: 14 to 44 days
    scope: Logs of requests to source platforms
    text: 'Logs of our requests to source platforms: 14 to 44 days , for the same reason.'
  - period: until you delete the monitor or the workspace
    scope: Monitor results
    text: 'Monitor results: until you delete the monitor or the workspace .'
  - period: 30 days
    scope: Webhook delivery records
    text: 'Webhook delivery records: 30 days .'
  - period: for as long as tax and accounting law requires
    scope: Billing records
    text: 'Billing records: for as long as tax and accounting law requires.'
  rights:
  - right: Access
    text: the right to access the personal data we hold about you
  - right: Correction
    text: to correct it
  - right: Deletion
    text: to have it deleted
  - right: Portability
    text: to receive it in a portable format
  - right: Objection or restriction
    text: to object to or restrict how we use it
  - right: Withdraw consent
    text: to withdraw consent where we rely on it
  - right: Complain to authority
    text: You also have the right to complain to your local data protection authority
  role:
    text: We are the controller of the personal data described in this policy, except where we say otherwise.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, share it for cross-context advertising, or use advertising trackers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Where data leaves the European Economic Area, the United Kingdom, or another region that restricts transfers, we rely on adequacy decisions or on standard contractual clauses with the provider.
  - mechanism: SCC
    text: we rely on adequacy decisions or on standard contractual clauses with the provider.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: weirapp-io
provenance_date: '2026-11-10'
provider_name: weirapp-io
provider_slug: weirapp-io
slug: weirapp-io-privacy-policy
source_date: '2026-11-10'
source_filename: weirapp-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://weirapp.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: weirapp-io\naid: weirapp-io\nurl: https://weirapp.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal data described in this policy, except where we say otherwise.\ndata_categories:\n- category: identifying\n  text: Your name, email address, and — if you sign in with Google or GitHub — the profile picture address that\n    provider shares.\n- category: contact\n  text: invitations you send (the invitee's email and a hash of the invitation link)\n- category: device\n  text: the client's user agent\n- category: financial\n  text: Dodo Payments collects\
  \ your payment details as Merchant of Record. We receive a record of each purchase\n    — amount, credits, status, and Dodo's reference — but never your full card number.\n- category: behavioral\n  text: Monitors and webhooks. The searches and targets you set up, the results they find, your webhook endpoint\n    addresses, signing secrets (encrypted), and a record of each delivery attempt and its response code.\n- category: communication\n  text: Support messages you send us, and our replies.\npurposes:\n- purpose: Provide the Service\n  text: 'To provide the Service: authenticate you, run your requests and monitors, deliver webhooks, and meter and\n    bill usage — because it is necessary to perform our contract with you.'\n- purpose: Security and fairness\n  text: 'To keep the Service secure and fair: detect abuse, enforce rate limits and the Acceptable Use Policy ,\n    and investigate incidents'\n- purpose: Support and account messages\n  text: To support you and send messages about\
  \ your account and the Service, such as security notices and changes\n    to these terms\n- purpose: Aggregate usage analytics\n  text: To understand, in aggregate, how the Service is used so we can improve it — in our legitimate interest.\n    This uses de-identified, aggregated figures.\n- purpose: Legal obligations\n  text: To meet legal, tax, and accounting obligations.\nretention:\n- scope: API request logs\n  period: 30 to 60 days\n  text: 'API request logs: 30 to 60 days .'\n- scope: Logs of requests to source platforms\n  period: 14 to 44 days\n  text: 'Logs of our requests to source platforms: 14 to 44 days , for the same reason.'\n- scope: Monitor results\n  period: until you delete the monitor or the workspace\n  text: 'Monitor results: until you delete the monitor or the workspace .'\n- scope: Webhook delivery records\n  period: 30 days\n  text: 'Webhook delivery records: 30 days .'\n- scope: Billing records\n  period: for as long as tax and accounting law requires\n  text:\
  \ 'Billing records: for as long as tax and accounting law requires.'\nresidency:\n- region: Japan\n  text: Our primary database is in Japan.\ntransfers:\n- mechanism: adequacy\n  text: Where data leaves the European Economic Area, the United Kingdom, or another region that restricts transfers,\n    we rely on adequacy decisions or on standard contractual clauses with the provider.\n- mechanism: SCC\n  text: we rely on adequacy decisions or on standard contractual clauses with the provider.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a workspace from its settings, or email support@weirapp.io\n  text: You can update your name in the dashboard and delete a workspace from its settings; for anything else, email\n    support@weirapp.io .\nrights:\n- right: Access\n  text: the right to access the personal data we hold about you\n- right: Correction\n  text: to correct it\n- right: Deletion\n  text: to have it deleted\n\
  - right: Portability\n  text: to receive it in a portable format\n- right: Objection or restriction\n  text: to object to or restrict how we use it\n- right: Withdraw consent\n  text: to withdraw consent where we rely on it\n- right: Complain to authority\n  text: You also have the right to complain to your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, share it for cross-context advertising, or use advertising trackers.\n"
source_yaml_url: https://artifacts.apis.io/weirapp-io/privacy/weirapp-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from weirapp-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Social Media
- MCP
---
