---
api_specs:
- filename: mnemoverse-com-health-api-openapi.yml
  format: yaml
  label: Mnemoverse Health API
  slug: mnemoverse-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-health-api-openapi.yml
- filename: mnemoverse-com-memory-api-openapi.yml
  format: yaml
  label: Mnemoverse Memory API
  slug: mnemoverse-com-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-memory-api-openapi.yml
- filename: mnemoverse-com-memory-v1-api-openapi.yml
  format: yaml
  label: Mnemoverse Memory V1 API
  slug: mnemoverse-com-memory-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-memory-v1-api-openapi.yml
- filename: mnemoverse-com-vault-api-openapi.yml
  format: yaml
  label: Mnemoverse Vault API
  slug: mnemoverse-com-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-vault-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: when you create or sign in to an account, your name, email address, username, profile picture
  - category: contact
    text: messages, your email address, attachments, and anything else you include when you contact us, ask for support, or exercise a privacy right
  - category: financial
    text: your plan, billing status, and the transaction and subscription identifiers of your payments
  - category: device
    text: the IP address and user agent of each sign-in session
  - category: location
    text: the approximate country derived from it
  - category: behavioral
    text: including IP address, browser type, pages visited, and page performance on our website
  - category: other
    text: Memory content may contain personal data you choose to provide.
  deletion:
    route: email support@mnemoverse.com
    text: email support@mnemoverse.com from the address on the account
  dpa:
    available: true
    text: Business customers who require a data-processing agreement (DPA) can request one at support@mnemoverse.com
    url: null
  purposes:
  - purpose: Authenticate and secure accounts
    text: Authenticate you, keep you signed in, and enforce permissions.
  - purpose: Store and manage memories at direction
    text: Store, search, return, organise, rate, and delete memories at your direction
  - purpose: Support and billing
    text: Provide support, billing, and service notices, and meet our legal obligations.
  - purpose: Improve website
    text: Improve our website and user experience.
  residency:
  - region: Netherlands
    text: Railway Hosts the Memory API, its database, and the remote MCP server Netherlands (EU)
  - region: European Union
    text: Reviews run inside disposable containers on a server we rent from Scaleway in the European Union.
  retention:
  - period: 30 days
    scope: account deletion
    text: When you ask us to delete your account, we delete the account record and the data section 11.5 lists within 30 days of verifying the request.
  - period: until you delete them
    scope: private memory atoms
    text: Private memory atoms are retained until you delete them
  - period: up to 7 years after the transaction
    scope: billing records
    text: up to 7 years after the transaction
  - period: up to 24 months after the last message
    scope: support conversations
    text: kept for up to 24 months after the last message
  - period: rolling schedule of our database provider
    scope: backups
    text: Backups of the primary memory store are kept on the rolling schedule of our database provider.
  rights:
  - right: Access
    text: Access the data we hold about you
  - right: Correction or deletion
    text: Request correction or deletion
  - right: Object or restrict
    text: Object to or restrict data processing
  - right: Portability
    text: Receive data you provided in a portable format where the right to portability applies
  - right: Withdraw consent
    text: Withdraw consent at any time
  - right: Complain to authority
    text: Lodge a complaint with the data-protection authority responsible for your place of residence, work, or the alleged infringement
  role:
    text: UINSIDE Inc. is the data controller for the account, billing, and operational data described in this policy
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal data to third parties
  subprocessors:
    text: A current list of the sub-processors we use is available on request at support@mnemoverse.com
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses (with the UK Addendum where applicable)
  - mechanism: DPF
    text: the EU–US Data Privacy Framework
  - mechanism: adequacy
    text: an adequacy decision where one applies
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mnemoverse
provenance_date: '2026-11-10'
provider_name: Mnemoverse
provider_slug: mnemoverse-com
slug: mnemoverse-com-privacy-policy
source_date: '2026-11-10'
source_filename: mnemoverse-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mnemoverse.com/docs/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mnemoverse\naid: mnemoverse-com\nurl: https://mnemoverse.com/docs/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: UINSIDE Inc. is the data controller for the account, billing, and operational data described in this policy\ndata_categories:\n- category: identifying\n  text: when you create or sign in to an account, your name, email address, username, profile picture\n- category: contact\n  text: messages, your email address, attachments, and anything else you include when you contact us, ask for support,\n    or exercise a privacy right\n- category: financial\n  text: your plan,\
  \ billing status, and the transaction and subscription identifiers of your payments\n- category: device\n  text: the IP address and user agent of each sign-in session\n- category: location\n  text: the approximate country derived from it\n- category: behavioral\n  text: including IP address, browser type, pages visited, and page performance on our website\n- category: other\n  text: Memory content may contain personal data you choose to provide.\npurposes:\n- purpose: Authenticate and secure accounts\n  text: Authenticate you, keep you signed in, and enforce permissions.\n- purpose: Store and manage memories at direction\n  text: Store, search, return, organise, rate, and delete memories at your direction\n- purpose: Support and billing\n  text: Provide support, billing, and service notices, and meet our legal obligations.\n- purpose: Improve website\n  text: Improve our website and user experience.\nretention:\n- scope: account deletion\n  period: 30 days\n  text: When you ask us to delete\
  \ your account, we delete the account record and the data section 11.5 lists within\n    30 days of verifying the request.\n- scope: private memory atoms\n  period: until you delete them\n  text: Private memory atoms are retained until you delete them\n- scope: billing records\n  period: up to 7 years after the transaction\n  text: up to 7 years after the transaction\n- scope: support conversations\n  period: up to 24 months after the last message\n  text: kept for up to 24 months after the last message\n- scope: backups\n  period: rolling schedule of our database provider\n  text: Backups of the primary memory store are kept on the rolling schedule of our database provider.\nresidency:\n- region: Netherlands\n  text: Railway Hosts the Memory API, its database, and the remote MCP server Netherlands (EU)\n- region: European Union\n  text: Reviews run inside disposable containers on a server we rent from Scaleway in the European Union.\ntransfers:\n- mechanism: SCC\n  text: the European\
  \ Commission's Standard Contractual Clauses (with the UK Addendum where applicable)\n- mechanism: DPF\n  text: the EU–US Data Privacy Framework\n- mechanism: adequacy\n  text: an adequacy decision where one applies\nsubprocessors:\n  url: null\n  text: A current list of the sub-processors we use is available on request at support@mnemoverse.com\ndpa:\n  available: true\n  url: null\n  text: Business customers who require a data-processing agreement (DPA) can request one at support@mnemoverse.com\ndeletion:\n  route: email support@mnemoverse.com\n  text: email support@mnemoverse.com from the address on the account\nrights:\n- right: Access\n  text: Access the data we hold about you\n- right: Correction or deletion\n  text: Request correction or deletion\n- right: Object or restrict\n  text: Object to or restrict data processing\n- right: Portability\n  text: Receive data you provided in a portable format where the right to portability applies\n- right: Withdraw consent\n  text: Withdraw\
  \ consent at any time\n- right: Complain to authority\n  text: Lodge a complaint with the data-protection authority responsible for your place of residence, work, or the\n    alleged infringement\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal data to third parties\n"
source_yaml_url: https://artifacts.apis.io/mnemoverse-com/privacy/mnemoverse-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from Mnemoverse's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Persistent
---
