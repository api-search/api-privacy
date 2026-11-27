---
api_specs:
- filename: flexyield-io-agents-api-openapi.yml
  format: yaml
  label: flexyield-io Agents API
  slug: flexyield-io-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-agents-api-openapi.yml
- filename: flexyield-io-data-api-openapi.yml
  format: yaml
  label: flexyield-io Data API
  slug: flexyield-io-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-data-api-openapi.yml
- filename: flexyield-io-keys-api-openapi.yml
  format: yaml
  label: flexyield-io Keys API
  slug: flexyield-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-keys-api-openapi.yml
- filename: flexyield-io-rpc-api-openapi.yml
  format: yaml
  label: flexyield-io Rpc API
  slug: flexyield-io-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-rpc-api-openapi.yml
- filename: flexyield-io-statements-api-openapi.yml
  format: yaml
  label: flexyield-io Statements API
  slug: flexyield-io-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-statements-api-openapi.yml
- filename: flexyield-io-toolbox-api-openapi.yml
  format: yaml
  label: flexyield-io Toolbox API
  slug: flexyield-io-toolbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-toolbox-api-openapi.yml
- filename: flexyield-io-x402-api-openapi.yml
  format: yaml
  label: flexyield-io X402 API
  slug: flexyield-io-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexyield-io/openapi/flexyield-io-x402-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: e-mail address, password (hashed), optional profile and billing details (name, phone, address, tax ID) you provide.'
  - category: behavioral
    text: 'Usage metadata: per-request timestamps, chain, method name, status, and latency, associated with your API key'
  - category: device
    text: 'our servers record technical access data: IP address, date and time, requested page, referrer, browser and operating system identifiers.'
  - category: contact
    text: 'Waitlist entries: e-mail, self-selected qualifier, referral source.'
  deletion:
    route: dashboard self-service
    text: You can also delete your account yourself in the dashboard; personal data is erased immediately, subject only to statutory retention (anonymized billing records).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision and billing
    text: To provide and bill the service, enforce limits and caps you configure, and send transactional e-mail
  - purpose: Abuse prevention and reliability
    text: Abuse prevention, rate limiting, and service reliability rest on our legitimate interest (Art. 6 (1)(f)) in operating a secure, fair service.
  - purpose: Product updates
    text: Occasional product updates — sent only to people who ticked the optional product-updates box when joining the waitlist — to waitlist and funnel contacts rest on consent (Art. 6 (1)(a))
  residency:
  - region: EU
    text: data centres in the EU
  retention:
  - period: 30 days
    scope: raw request metadata
    text: Raw request metadata is deleted after 30 days
  - period: 30 days
    scope: website visitor logs
    text: are deleted after 30 days unless an incident requires a longer hold for its investigation.
  - period: seven years
    scope: invoices and bookkeeping records
    text: invoices and bookkeeping records are kept for seven years under § 132 BAO.
  rights:
  - right: access, correction, export, deletion
    text: You can request access, correction, export, or deletion of your personal data
  - right: object or restrict processing
    text: object to or restrict processing
  - right: lodge complaint
    text: You may also lodge a complaint with your supervisory authority
  role:
    text: The data controller is JadeMind GmbH
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: 'We share the minimum necessary data with these processors:'
    url: null
  transfers:
  - mechanism: DPF
    text: adequacy decisions (EU–US Data Privacy Framework, UK adequacy)
  - mechanism: SCC
    text: or EU standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: flexyield-io
provenance_date: '2026-11-09'
provider_name: flexyield-io
provider_slug: flexyield-io
slug: flexyield-io-privacy-policy
source_date: '2026-11-09'
source_filename: flexyield-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flexyield.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: flexyield-io\naid: flexyield-io\nurl: https://flexyield.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is JadeMind GmbH\ndata_categories:\n- category: identifying\n  text: 'Account data: e-mail address, password (hashed), optional profile and billing details (name, phone, address,\n    tax ID) you provide.'\n- category: behavioral\n  text: 'Usage metadata: per-request timestamps, chain, method name, status, and latency, associated with your API\n    key'\n- category: device\n  text: 'our servers record technical access data: IP address, date and time, requested\
  \ page, referrer, browser\n    and operating system identifiers.'\n- category: contact\n  text: 'Waitlist entries: e-mail, self-selected qualifier, referral source.'\npurposes:\n- purpose: Service provision and billing\n  text: To provide and bill the service, enforce limits and caps you configure, and send transactional e-mail\n- purpose: Abuse prevention and reliability\n  text: Abuse prevention, rate limiting, and service reliability rest on our legitimate interest (Art. 6 (1)(f))\n    in operating a secure, fair service.\n- purpose: Product updates\n  text: Occasional product updates — sent only to people who ticked the optional product-updates box when joining\n    the waitlist — to waitlist and funnel contacts rest on consent (Art. 6 (1)(a))\nretention:\n- scope: raw request metadata\n  period: 30 days\n  text: Raw request metadata is deleted after 30 days\n- scope: website visitor logs\n  period: 30 days\n  text: are deleted after 30 days unless an incident requires a longer hold\
  \ for its investigation.\n- scope: invoices and bookkeeping records\n  period: seven years\n  text: invoices and bookkeeping records are kept for seven years under § 132 BAO.\nresidency:\n- region: EU\n  text: data centres in the EU\ntransfers:\n- mechanism: DPF\n  text: adequacy decisions (EU–US Data Privacy Framework, UK adequacy)\n- mechanism: SCC\n  text: or EU standard contractual clauses\nsubprocessors:\n  url: null\n  text: 'We share the minimum necessary data with these processors:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard self-service\n  text: You can also delete your account yourself in the dashboard; personal data is erased immediately, subject\n    only to statutory retention (anonymized billing records).\nrights:\n- right: access, correction, export, deletion\n  text: You can request access, correction, export, or deletion of your personal data\n- right: object or restrict processing\n  text: object to or restrict processing\n- right:\
  \ lodge complaint\n  text: You may also lodge a complaint with your supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/flexyield-io/privacy/flexyield-io-privacy-policy.yml
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
- sale_or_sharing
summary_line: 20 quoted statements, read from flexyield-io's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- API Gateway
- Unified Billing
- Multi-Chain
- Free Tier
---
