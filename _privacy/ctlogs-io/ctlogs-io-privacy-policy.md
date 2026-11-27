---
api_specs:
- filename: ctlogs-io-certs-api-openapi.yml
  format: yaml
  label: CTlogs.io Certs API
  slug: ctlogs-io-certs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-certs-api-openapi.yml
- filename: ctlogs-io-me-api-openapi.yml
  format: yaml
  label: CTlogs.io Me API
  slug: ctlogs-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-me-api-openapi.yml
- filename: ctlogs-io-search-api-openapi.yml
  format: yaml
  label: CTlogs.io Search API
  slug: ctlogs-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-search-api-openapi.yml
- filename: ctlogs-io-stats-api-openapi.yml
  format: yaml
  label: CTlogs.io Stats API
  slug: ctlogs-io-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-stats-api-openapi.yml
- filename: ctlogs-io-subdomains-api-openapi.yml
  format: yaml
  label: CTlogs.io Subdomains API
  slug: ctlogs-io-subdomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctlogs-io/openapi/ctlogs-io-subdomains-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account Name, email address, password, the network and the page the account was opened from
  - category: financial
    text: Stripe customer identifier, subscription status and dates, card brand and last four digits.
  - category: device
    text: for each active sign-in, the network and browser identification of the session
  - category: behavioral
    text: A pseudonymised record of each search and each use of a free tool
  - category: communication
    text: The subject and text of ticket messages with their timestamps.
  - category: other
    text: 'For each logged certificate: the hostnames it covers and their registrable domain, the issuing authority, the validation type, the validity period, the fingerprint'
  deletion:
    route: Email the privacy contact to exercise rights
    text: To exercise them, write to
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service availability
    text: kept for 7 days to keep the service available
  - purpose: Providing the account
    text: 'Basis: Art. 6(1)(b) GDPR, providing the account'
  - purpose: Metering and attributing abuse
    text: Art. 6(1)(f) for attributing abuse to an account
  - purpose: Preventing repeat abuse and re-registration
    text: preventing repeat abuse and re-registration
  - purpose: Certificate security monitoring
    text: Detecting mis-issued and unauthorised certificates, impersonation and phishing
  residency:
  - region: United States
    text: These processors process data in the United States.
  retention:
  - period: 7 days
    scope: Search records
    text: kept for 7 days to keep the service available
  - period: as long as the account exists
    scope: Account
    text: Kept for as long as the account exists; sign-in records for 30 days.
  - period: eight to ten years
    scope: Billing
    text: Kept for eight to ten years as German commercial and tax law requires.
  - period: up to two years after the account is closed
    scope: Abuse records
    text: Kept for up to two years after the account is closed.
  - period: as long as the index is maintained
    scope: Certificate index
    text: For as long as the index is maintained; expired certificates remain as history.
  - period: three years afterwards
    scope: Objection handling
    text: keep them for as long as a removal is in force and for three years afterwards
  rights:
  - right: Access
    text: You have the right of access (Art. 15 GDPR)
  - right: Rectification
    text: rectification (Art. 16)
  - right: Erasure
    text: erasure (Art. 17)
  - right: Restriction of processing
    text: restriction of processing (Art. 18)
  - right: Data portability
    text: data portability (Art. 20)
  - right: Object
    text: You may object at any time, on grounds relating to your particular situation
  - right: Lodge complaint
    text: You have the right to lodge a complaint with a supervisory authority.
  role:
    text: Controller Lyalpha GmbH
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Stripe Payment processing and subscriptions. Resend Delivery of email. Cloudflare Content delivery and protection. Hivelocity Hosting of the application and its databases.
    url: null
  transfers:
  - mechanism: DPF
    text: Transfers are covered by the EU-US Data Privacy Framework where the processor is certified under it
  - mechanism: SCC
    text: otherwise by the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CTlogs.io
provenance_date: '2026-11-09'
provider_name: CTlogs.io
provider_slug: ctlogs-io
slug: ctlogs-io-privacy-policy
source_date: '2026-11-09'
source_filename: ctlogs-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ctlogs.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CTlogs.io\naid: ctlogs-io\nurl: https://ctlogs.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller Lyalpha GmbH\ndata_categories:\n- category: identifying\n  text: Account Name, email address, password, the network and the page the account was opened from\n- category: financial\n  text: Stripe customer identifier, subscription status and dates, card brand and last four digits.\n- category: device\n  text: for each active sign-in, the network and browser identification of the session\n- category: behavioral\n  text: A pseudonymised record of each search and each use of a free\
  \ tool\n- category: communication\n  text: The subject and text of ticket messages with their timestamps.\n- category: other\n  text: 'For each logged certificate: the hostnames it covers and their registrable domain, the issuing authority,\n    the validation type, the validity period, the fingerprint'\npurposes:\n- purpose: Service availability\n  text: kept for 7 days to keep the service available\n- purpose: Providing the account\n  text: 'Basis: Art. 6(1)(b) GDPR, providing the account'\n- purpose: Metering and attributing abuse\n  text: Art. 6(1)(f) for attributing abuse to an account\n- purpose: Preventing repeat abuse and re-registration\n  text: preventing repeat abuse and re-registration\n- purpose: Certificate security monitoring\n  text: Detecting mis-issued and unauthorised certificates, impersonation and phishing\nretention:\n- scope: Search records\n  period: 7 days\n  text: kept for 7 days to keep the service available\n- scope: Account\n  period: as long as the account\
  \ exists\n  text: Kept for as long as the account exists; sign-in records for 30 days.\n- scope: Billing\n  period: eight to ten years\n  text: Kept for eight to ten years as German commercial and tax law requires.\n- scope: Abuse records\n  period: up to two years after the account is closed\n  text: Kept for up to two years after the account is closed.\n- scope: Certificate index\n  period: as long as the index is maintained\n  text: For as long as the index is maintained; expired certificates remain as history.\n- scope: Objection handling\n  period: three years afterwards\n  text: keep them for as long as a removal is in force and for three years afterwards\nresidency:\n- region: United States\n  text: These processors process data in the United States.\ntransfers:\n- mechanism: DPF\n  text: Transfers are covered by the EU-US Data Privacy Framework where the processor is certified under it\n- mechanism: SCC\n  text: otherwise by the European Commission's Standard Contractual Clauses.\n\
  subprocessors:\n  url: null\n  text: Stripe Payment processing and subscriptions. Resend Delivery of email. Cloudflare Content delivery and protection.\n    Hivelocity Hosting of the application and its databases.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the privacy contact to exercise rights\n  text: To exercise them, write to\nrights:\n- right: Access\n  text: You have the right of access (Art. 15 GDPR)\n- right: Rectification\n  text: rectification (Art. 16)\n- right: Erasure\n  text: erasure (Art. 17)\n- right: Restriction of processing\n  text: restriction of processing (Art. 18)\n- right: Data portability\n  text: data portability (Art. 20)\n- right: Object\n  text: You may object at any time, on grounds relating to your particular situation\n- right: Lodge complaint\n  text: You have the right to lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ctlogs-io/privacy/ctlogs-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 30 quoted statements, read from CTlogs.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Certificate Transparency
- TLS Certificates
- SSL
- Security
- PKI
- Domains
- MCP
---
