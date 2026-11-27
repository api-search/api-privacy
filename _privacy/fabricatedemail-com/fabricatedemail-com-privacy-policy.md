---
api_specs:
- filename: fabricatedemail-com-health-api-openapi.yml
  format: yaml
  label: fabricatedemail-com Health API
  slug: fabricatedemail-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-health-api-openapi.yml
- filename: fabricatedemail-com-mcp-api-openapi.yml
  format: yaml
  label: fabricatedemail-com MCP API
  slug: fabricatedemail-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-mcp-api-openapi.yml
- filename: fabricatedemail-com-messages-api-openapi.yml
  format: yaml
  label: fabricatedemail-com Messages API
  slug: fabricatedemail-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-messages-api-openapi.yml
- filename: fabricatedemail-com-subscriptions-api-openapi.yml
  format: yaml
  label: fabricatedemail-com Subscriptions API
  slug: fabricatedemail-com-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabricatedemail-com/openapi/fabricatedemail-com-subscriptions-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: the email address you sign in with, your identity provider's user identifier, your tier and account state
  - category: communication
    text: Mail sent to your addresses — headers, subject, text and HTML bodies, sender and recipient
  - category: device
    text: API keys — a hash of the key, its name, and when it was created and revoked
  - category: behavioral
    text: Usage counters — messages stored and dropped, per month
  - category: financial
    text: Stripe customer, subscription and price identifiers
  deletion:
    route: Delete the account from the dashboard
    text: 'Deleting your account from the dashboard does most of this immediately: your addresses, the mail held for them, your keys and your account record are removed'
  dpa:
    available: true
    text: the Data Processing Agreement sets out the terms
    url: null
  purposes:
  - purpose: performing the contract
    text: Performing our contract with you (GDPR Article 6(1)(b)) — your account, your keys, your addresses, the mail we store for you to read, and the service emails we send you
  - purpose: legitimate interests
    text: Our legitimate interests (Article 6(1)(f)) — logs, usage counters and synchronisation records, kept to run the service, to keep it available, and to detect and stop abuse.
  - purpose: legal obligation
    text: A legal obligation (Article 6(1)(c)) — accounting records, and responses to valid legal process.
  residency:
  - region: European Union (EEUR region)
    text: Cloudflare D1, EEUR region (European Union)
  - region: Sweden Central
    text: Azure Cosmos DB, Sweden Central
  retention:
  - period: 24 hours
    scope: Mail sent to addresses
    text: 24 hours from receipt, or until the address expires or is deleted, whichever is sooner
  - period: Until you delete the account
    scope: Account
    text: Until you delete the account
  - period: null
    scope: Cloudflare Email Routing log
    text: Cloudflare's log of every message sent to the mail domain
  - period: null
    scope: Synchronisation logs and service email records
    text: Synchronisation logs, which record account identifiers and the changes pushed between our two systems, and a record of each service email we send
  - period: 7 days
    scope: Quota-warning markers
    text: Quota-warning markers — your account identifier and the month a warning was sent Azure, Sweden Central 7 days
  - period: 7 days
    scope: Restorable history
    text: Both databases keep a restorable history for 7 days
  rights:
  - right: access
    text: You may ask for a copy of your data
  - right: rectification
    text: for it to be corrected or deleted
  - right: erasure
    text: for it to be corrected or deleted
  - right: restriction
    text: for processing to be restricted
  - right: objection
    text: to object to processing based on our legitimate interests
  - right: complaint
    text: You also have the right to complain to a supervisory authority — in Sweden, Integritetsskyddsmyndigheten (IMY).
  role:
    text: 'We are the controller for the data described below, except for the mail that arrives at your addresses: for that we act as processor on your instructions'
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers outside the European Economic Area rest on the providers' standard contractual clauses and their own transfer frameworks.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fabricatedemail-com
provenance_date: '2026-11-09'
provider_name: fabricatedemail-com
provider_slug: fabricatedemail-com
slug: fabricatedemail-com-privacy-policy
source_date: '2026-11-09'
source_filename: fabricatedemail-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fabricatedemail.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fabricatedemail-com\naid: fabricatedemail-com\nurl: https://fabricatedemail.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'We are the controller for the data described below, except for the mail that arrives at your addresses:\n    for that we act as processor on your instructions'\ndata_categories:\n- category: contact\n  text: the email address you sign in with, your identity provider's user identifier, your tier and account state\n- category: communication\n  text: Mail sent to your addresses — headers, subject, text and HTML bodies, sender and recipient\n- category: device\n  text:\
  \ API keys — a hash of the key, its name, and when it was created and revoked\n- category: behavioral\n  text: Usage counters — messages stored and dropped, per month\n- category: financial\n  text: Stripe customer, subscription and price identifiers\npurposes:\n- purpose: performing the contract\n  text: Performing our contract with you (GDPR Article 6(1)(b)) — your account, your keys, your addresses, the mail\n    we store for you to read, and the service emails we send you\n- purpose: legitimate interests\n  text: Our legitimate interests (Article 6(1)(f)) — logs, usage counters and synchronisation records, kept to run\n    the service, to keep it available, and to detect and stop abuse.\n- purpose: legal obligation\n  text: A legal obligation (Article 6(1)(c)) — accounting records, and responses to valid legal process.\nretention:\n- scope: Mail sent to addresses\n  period: 24 hours\n  text: 24 hours from receipt, or until the address expires or is deleted, whichever is sooner\n- scope:\
  \ Account\n  period: Until you delete the account\n  text: Until you delete the account\n- scope: Cloudflare Email Routing log\n  period: null\n  text: Cloudflare's log of every message sent to the mail domain\n- scope: Synchronisation logs and service email records\n  period: null\n  text: Synchronisation logs, which record account identifiers and the changes pushed between our two systems, and\n    a record of each service email we send\n- scope: Quota-warning markers\n  period: 7 days\n  text: Quota-warning markers — your account identifier and the month a warning was sent Azure, Sweden Central 7\n    days\n- scope: Restorable history\n  period: 7 days\n  text: Both databases keep a restorable history for 7 days\nresidency:\n- region: European Union (EEUR region)\n  text: Cloudflare D1, EEUR region (European Union)\n- region: Sweden Central\n  text: Azure Cosmos DB, Sweden Central\ntransfers:\n- mechanism: SCC\n  text: Transfers outside the European Economic Area rest on the providers'\
  \ standard contractual clauses and their\n    own transfer frameworks.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: the Data Processing Agreement sets out the terms\ndeletion:\n  route: Delete the account from the dashboard\n  text: 'Deleting your account from the dashboard does most of this immediately: your addresses, the mail held for\n    them, your keys and your account record are removed'\nrights:\n- right: access\n  text: You may ask for a copy of your data\n- right: rectification\n  text: for it to be corrected or deleted\n- right: erasure\n  text: for it to be corrected or deleted\n- right: restriction\n  text: for processing to be restricted\n- right: objection\n  text: to object to processing based on our legitimate interests\n- right: complaint\n  text: You also have the right to complain to a supervisory authority — in Sweden, Integritetsskyddsmyndigheten\n    (IMY).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fabricatedemail-com/privacy/fabricatedemail-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 26 quoted statements, read from fabricatedemail-com's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Disposable
- Testing
- Automation
- Services
---
