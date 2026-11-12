---
api_specs:
- filename: euroref-dev-alerts-api-openapi.yml
  format: yaml
  label: Euroref Alerts API
  slug: euroref-dev-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-alerts-api-openapi.yml
- filename: euroref-dev-answers-api-openapi.yml
  format: yaml
  label: Euroref Answers API
  slug: euroref-dev-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-answers-api-openapi.yml
- filename: euroref-dev-certified-api-openapi.yml
  format: yaml
  label: Euroref Certified API
  slug: euroref-dev-certified-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-certified-api-openapi.yml
- filename: euroref-dev-discovery-api-openapi.yml
  format: yaml
  label: Euroref Discovery API
  slug: euroref-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-discovery-api-openapi.yml
- filename: euroref-dev-free-api-openapi.yml
  format: yaml
  label: Euroref Free API
  slug: euroref-dev-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-free-api-openapi.yml
- filename: euroref-dev-jobs-api-openapi.yml
  format: yaml
  label: Euroref Jobs API
  slug: euroref-dev-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-jobs-api-openapi.yml
- filename: euroref-dev-keys-api-openapi.yml
  format: yaml
  label: Euroref Keys API
  slug: euroref-dev-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-keys-api-openapi.yml
- filename: euroref-dev-reference-data-api-openapi.yml
  format: yaml
  label: Euroref Reference data API
  slug: euroref-dev-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-reference-data-api-openapi.yml
- filename: euroref-dev-x402-sellers-api-openapi.yml
  format: yaml
  label: Euroref x402 sellers API
  slug: euroref-dev-x402-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/euroref-dev/openapi/euroref-dev-x402-sellers-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: We do not store your IP address. It is replaced, before anything is written, by a short salted SHA-256 hash
  - category: contact
    text: we store your email address, a normalised form of it used to allow one key per mailbox
  - category: financial
    text: We record the paying wallet address, amount, transaction hash and time in a payment ledger
  - category: behavioral
    text: Our web pages count visits without cookies.
  - category: device
    text: the browser, operating system and device type, and a visitor code
  - category: communication
    text: We store your message, the email address if you choose to give one
  deletion:
    route: email request to privacy contact
    text: Email [email protected] and we will respond within two business days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse prevention and rate limiting
    text: enough to count distinct callers and to apply rate limits and abuse blocks
  - purpose: accounting
    text: We keep this for accounting.
  - purpose: issuing API keys
    text: so we can issue your API key
  - purpose: operator alerts
    text: forward the message to our operators’ private alert channel
  retention:
  - period: about nine weeks
    scope: server journal request logs
    text: at present it reaches back about nine weeks
  - period: about five weeks
    scope: system log copy
    text: A copy in the system log is kept for about five weeks.
  - period: 90 days
    scope: visitor statistics full records
    text: Full records are kept for 90 days.
  - period: deleted at midnight (SAST)
    scope: visitor code
    text: a salt that changes every day and is deleted at midnight (SAST)
  - period: as long as tax and accounting law requires
    scope: purchase records
    text: These purchase records are kept for as long as tax and accounting law requires.
  - period: while the key exists
    scope: free API key email
    text: The address is kept while the key exists
  rights:
  - right: access
    text: You may ask for access to, correction of, or deletion of personal data we hold about you
  - right: correction
    text: You may ask for access to, correction of, or deletion of personal data we hold about you
  - right: deletion
    text: You may ask for access to, correction of, or deletion of personal data we hold about you
  - right: objection
    text: or object to its processing
  - right: complaint to regulator
    text: you may also complain to the Information Regulator of South Africa
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent data and do not build profiles of callers.
  subprocessors:
    text: Cloudflare sits in front of all seven services for delivery and protection, and therefore sees each connection, including your IP address, under its own terms.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Euroref
provenance_date: '2026-11-09'
provider_name: Euroref
provider_slug: euroref-dev
slug: euroref-dev-privacy-policy
source_date: '2026-11-09'
source_filename: euroref-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://euroref.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Euroref\naid: euroref-dev\nurl: https://euroref.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We do not store your IP address. It is replaced, before anything is written, by a short salted SHA-256 hash\n- category: contact\n  text: we store your email address, a normalised form of it used to allow one key per mailbox\n- category: financial\n  text: We record the paying wallet address, amount, transaction hash and time in a payment ledger\n- category: behavioral\n  text: Our web pages count visits without cookies.\n- category:\
  \ device\n  text: the browser, operating system and device type, and a visitor code\n- category: communication\n  text: We store your message, the email address if you choose to give one\npurposes:\n- purpose: abuse prevention and rate limiting\n  text: enough to count distinct callers and to apply rate limits and abuse blocks\n- purpose: accounting\n  text: We keep this for accounting.\n- purpose: issuing API keys\n  text: so we can issue your API key\n- purpose: operator alerts\n  text: forward the message to our operators’ private alert channel\nretention:\n- scope: server journal request logs\n  period: about nine weeks\n  text: at present it reaches back about nine weeks\n- scope: system log copy\n  period: about five weeks\n  text: A copy in the system log is kept for about five weeks.\n- scope: visitor statistics full records\n  period: 90 days\n  text: Full records are kept for 90 days.\n- scope: visitor code\n  period: deleted at midnight (SAST)\n  text: a salt that changes every\
  \ day and is deleted at midnight (SAST)\n- scope: purchase records\n  period: as long as tax and accounting law requires\n  text: These purchase records are kept for as long as tax and accounting law requires.\n- scope: free API key email\n  period: while the key exists\n  text: The address is kept while the key exists\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare sits in front of all seven services for delivery and protection, and therefore sees each connection,\n    including your IP address, under its own terms.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to privacy contact\n  text: Email [email protected] and we will respond within two business days.\nrights:\n- right: access\n  text: You may ask for access to, correction of, or deletion of personal data we hold about you\n- right: correction\n  text: You may ask for access to, correction of, or deletion of personal data we hold about you\n- right: deletion\n\
  \  text: You may ask for access to, correction of, or deletion of personal data we hold about you\n- right: objection\n  text: or object to its processing\n- right: complaint to regulator\n  text: you may also complain to the Information Regulator of South Africa\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent data and do not build profiles of callers.\n"
source_yaml_url: https://artifacts.apis.io/euroref-dev/privacy/euroref-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Euroref's own page on 2026-11-09.
synthetic: false
tags:
- Reference Data
- Government
- Europe
- API
- Open Data
---
