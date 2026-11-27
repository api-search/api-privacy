---
api_specs:
- filename: echorelay-openapi-generated.yml
  format: yaml
  label: EchoRelay API
  slug: echorelay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/_ae-authored/echorelay-openapi-generated.yml
- filename: echorelay-keys-api-openapi.yml
  format: yaml
  label: EchoRelay Keys API
  slug: echorelay-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/echorelay-keys-api-openapi.yml
- filename: echorelay-projects-api-openapi.yml
  format: yaml
  label: EchoRelay Projects API
  slug: echorelay-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echorelay/openapi/echorelay-projects-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data : email address, hashed password, TOTP secret, optional display name.'
  - category: contact
    text: email address
  - category: financial
    text: 'Billing data : tier or pack purchased, invoice IDs, billing country.'
  - category: device
    text: 'Server logs : IP addresses, user-agent strings, request paths.'
  - category: behavioral
    text: 'Acquisition records : when you arrive from a tagged link, from a search engine, or from another website, an opaque identifier, cohort, the site or tag you came from, medium, campaign tags, entry path, and timestamps.'
  - category: communication
    text: 'Newsletter : if you subscribe, your email address, the exact wording you agreed to, the date and IP address the request came from, and whether you confirmed it.'
  deletion:
    route: close your account in the panel
    text: You can exercise your right of erasure directly by closing your account in the panel — this erases your personal data immediately.
  dpa:
    available: true
    text: is maintained in §5 of our DPA
    url: null
  purposes:
  - purpose: provide the service
    text: To provide the service you signed up for (contract).
  - purpose: billing and accounting
    text: To bill you and meet our accounting obligations (legal obligation).
  - purpose: fraud and security prevention
    text: To prevent fraud, abuse, and security incidents (legitimate interest).
  - purpose: marketing campaign measurement
    text: To understand which first-party campaigns lead to signups and paid accounts, so we can evaluate and improve our marketing (legitimate interest).
  - purpose: newsletter
    text: To send you the newsletter you asked for, and to keep the record that shows you asked for it (consent).
  - purpose: support requests
    text: To respond to your support requests (contract / legitimate interest).
  residency:
  - region: European Union
    text: Production data is stored on infrastructure located in the European Union.
  retention:
  - period: up to 90 days
    scope: server logs
    text: 'Server logs: up to 90 days.'
  - period: up to 30 days
    scope: dead-letter queue entries
    text: 'Dead-letter queue entries (request bodies and headers for permanently-failed deliveries): up to 30 days from the failure time, or until you clear them — whichever is earlier.'
  - period: row-level data up to 24 months
    scope: usage metadata
    text: 'Usage metadata: aggregated indefinitely; row-level data up to 24 months.'
  - period: up to 180 days
    scope: unjoined acquisition sessions
    text: 'Unjoined acquisition sessions: up to 180 days.'
  - period: seven days
    scope: unconfirmed newsletter address
    text: 'Newsletter: an address that is never confirmed is deleted after seven days.'
  - period: statutory period
    scope: invoice and accounting data
    text: invoice records and accounting data are retained for the statutory period required by applicable tax and accounting law.
  rights:
  - right: access
    text: access the personal data we hold about you
  - right: correct
    text: correct inaccurate data
  - right: erasure
    text: request erasure of your personal data (the right to be forgotten)
  - right: restrict or object
    text: restrict or object to processing
  - right: portability
    text: request portability
  role:
    text: EchoRelay is the data controller for personal data you provide directly (account email, billing details, support correspondence).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: The complete, authoritative list of sub-processors who may process your personal data on our behalf — with the data categories, region, and transfer mechanism for each — is maintained in §5 of our DPA .
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers rely on standard contractual clauses where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EchoRelay
provenance_date: '2026-11-09'
provider_name: EchoRelay
provider_slug: echorelay
slug: echorelay-privacy-policy
source_date: '2026-11-09'
source_filename: echorelay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://echorelay.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EchoRelay\naid: echorelay\nurl: https://echorelay.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: EchoRelay is the data controller for personal data you provide directly (account email, billing details,\n    support correspondence).\ndata_categories:\n- category: identifying\n  text: 'Account data : email address, hashed password, TOTP secret, optional display name.'\n- category: contact\n  text: email address\n- category: financial\n  text: 'Billing data : tier or pack purchased, invoice IDs, billing country.'\n- category: device\n  text: 'Server logs : IP addresses, user-agent\
  \ strings, request paths.'\n- category: behavioral\n  text: 'Acquisition records : when you arrive from a tagged link, from a search engine, or from another website,\n    an opaque identifier, cohort, the site or tag you came from, medium, campaign tags, entry path, and timestamps.'\n- category: communication\n  text: 'Newsletter : if you subscribe, your email address, the exact wording you agreed to, the date and IP address\n    the request came from, and whether you confirmed it.'\npurposes:\n- purpose: provide the service\n  text: To provide the service you signed up for (contract).\n- purpose: billing and accounting\n  text: To bill you and meet our accounting obligations (legal obligation).\n- purpose: fraud and security prevention\n  text: To prevent fraud, abuse, and security incidents (legitimate interest).\n- purpose: marketing campaign measurement\n  text: To understand which first-party campaigns lead to signups and paid accounts, so we can evaluate and improve\n    our marketing\
  \ (legitimate interest).\n- purpose: newsletter\n  text: To send you the newsletter you asked for, and to keep the record that shows you asked for it (consent).\n- purpose: support requests\n  text: To respond to your support requests (contract / legitimate interest).\nretention:\n- scope: server logs\n  period: up to 90 days\n  text: 'Server logs: up to 90 days.'\n- scope: dead-letter queue entries\n  period: up to 30 days\n  text: 'Dead-letter queue entries (request bodies and headers for permanently-failed deliveries): up to 30 days\n    from the failure time, or until you clear them — whichever is earlier.'\n- scope: usage metadata\n  period: row-level data up to 24 months\n  text: 'Usage metadata: aggregated indefinitely; row-level data up to 24 months.'\n- scope: unjoined acquisition sessions\n  period: up to 180 days\n  text: 'Unjoined acquisition sessions: up to 180 days.'\n- scope: unconfirmed newsletter address\n  period: seven days\n  text: 'Newsletter: an address that is never\
  \ confirmed is deleted after seven days.'\n- scope: invoice and accounting data\n  period: statutory period\n  text: invoice records and accounting data are retained for the statutory period required by applicable tax and\n    accounting law.\nresidency:\n- region: European Union\n  text: Production data is stored on infrastructure located in the European Union.\ntransfers:\n- mechanism: SCC\n  text: Transfers rely on standard contractual clauses where applicable.\nsubprocessors:\n  url: null\n  text: The complete, authoritative list of sub-processors who may process your personal data on our behalf — with\n    the data categories, region, and transfer mechanism for each — is maintained in §5 of our DPA .\ndpa:\n  available: true\n  url: null\n  text: is maintained in §5 of our DPA\ndeletion:\n  route: close your account in the panel\n  text: You can exercise your right of erasure directly by closing your account in the panel — this erases your\n    personal data immediately.\nrights:\n\
  - right: access\n  text: access the personal data we hold about you\n- right: correct\n  text: correct inaccurate data\n- right: erasure\n  text: request erasure of your personal data (the right to be forgotten)\n- right: restrict or object\n  text: restrict or object to processing\n- right: portability\n  text: request portability\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/echorelay/privacy/echorelay-privacy-policy.yml
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
summary_line: 30 quoted statements, read from EchoRelay's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Platform
- Automation
- No-Code
- Company
---
