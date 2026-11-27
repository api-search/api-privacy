---
api_specs:
- filename: beecargo-net-agent-api-openapi.yml
  format: yaml
  label: Beecargo Agent API
  slug: beecargo-net-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-agent-api-openapi.yml
- filename: beecargo-net-connect-api-openapi.yml
  format: yaml
  label: Beecargo Connect API
  slug: beecargo-net-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-connect-api-openapi.yml
- filename: beecargo-net-downloads-api-openapi.yml
  format: yaml
  label: Beecargo Downloads API
  slug: beecargo-net-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-downloads-api-openapi.yml
- filename: beecargo-net-files-api-openapi.yml
  format: yaml
  label: Beecargo Files API
  slug: beecargo-net-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-files-api-openapi.yml
- filename: beecargo-net-folders-api-openapi.yml
  format: yaml
  label: Beecargo Folders API
  slug: beecargo-net-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-folders-api-openapi.yml
- filename: beecargo-net-system-api-openapi.yml
  format: yaml
  label: Beecargo System API
  slug: beecargo-net-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-system-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: email address and authentication data when you sign in or create an account.'
  - category: contact
    text: 'Communications: messages you send to support or legal@beecargo.net.'
  - category: financial
    text: 'Payment data: subscription status and billing identifiers processed by our payment provider (we do not store full card numbers).'
  - category: location
    text: approximate location derived from IP
  - category: device
    text: IP address, browser type, device information
  - category: behavioral
    text: pages visited, features used
  deletion:
    route: Remove files or contact legal@beecargo.net
    text: Files and associated metadata may be deleted when you remove them, when links expire, or when we enforce our policies.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, and secure the Service
    text: Provide, operate, and secure the Service (uploads, downloads, links, API, and accounts).
  - purpose: Process payments
    text: Process payments and manage Pro subscriptions.
  - purpose: Detect abuse and fraud
    text: Detect abuse, malware, fraud, and violations of our policies.
  - purpose: Improve product
    text: Improve reliability, performance, and product experience.
  retention:
  - period: null
    scope: Personal information
    text: We retain personal information for as long as needed to provide the Service, comply with legal obligations, resolve disputes, and enforce agreements.
  - period: null
    scope: Backups
    text: Backup copies may persist for a limited period.
  rights:
  - right: Access, correct, or delete
    text: Access, correct, or delete personal information we hold about you.
  - right: Object or restrict processing
    text: Object to or restrict certain processing.
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  - right: Data portability
    text: Request a copy of your data in a portable format.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Beecargo
provenance_date: '2026-11-09'
provider_name: Beecargo
provider_slug: beecargo-net
slug: beecargo-net-privacy-policy
source_date: '2026-11-09'
source_filename: beecargo-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://beecargo.net/docs/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Beecargo\naid: beecargo-net\nurl: https://beecargo.net/docs/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: email address and authentication data when you sign in or create an account.'\n- category: contact\n  text: 'Communications: messages you send to support or legal@beecargo.net.'\n- category: financial\n  text: 'Payment data: subscription status and billing identifiers processed by our payment provider (we do not\n    store full card numbers).'\n- category: location\n  text: approximate location derived\
  \ from IP\n- category: device\n  text: IP address, browser type, device information\n- category: behavioral\n  text: pages visited, features used\npurposes:\n- purpose: Provide, operate, and secure the Service\n  text: Provide, operate, and secure the Service (uploads, downloads, links, API, and accounts).\n- purpose: Process payments\n  text: Process payments and manage Pro subscriptions.\n- purpose: Detect abuse and fraud\n  text: Detect abuse, malware, fraud, and violations of our policies.\n- purpose: Improve product\n  text: Improve reliability, performance, and product experience.\nretention:\n- scope: Personal information\n  period: null\n  text: We retain personal information for as long as needed to provide the Service, comply with legal obligations,\n    resolve disputes, and enforce agreements.\n- scope: Backups\n  period: null\n  text: Backup copies may persist for a limited period.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Remove files or contact legal@beecargo.net\n  text: Files and associated metadata may be deleted when you remove them, when links expire, or when we enforce\n    our policies.\nrights:\n- right: Access, correct, or delete\n  text: Access, correct, or delete personal information we hold about you.\n- right: Object or restrict processing\n  text: Object to or restrict certain processing.\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent.\n- right: Data portability\n  text: Request a copy of your data in a portable format.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/beecargo-net/privacy/beecargo-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Beecargo's own page on 2026-11-09.
synthetic: false
tags:
- File Hosting
- Share Links
- Developers
- Agents
---
