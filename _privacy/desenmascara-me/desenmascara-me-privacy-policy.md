---
api_specs:
- filename: desenmascara-me-domain-check-api-openapi.yml
  format: yaml
  label: Desenmascara.me Domain Check API
  slug: desenmascara-me-domain-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desenmascara-me/openapi/desenmascara-me-domain-check-api-openapi.yml
- filename: desenmascara-me-fraud-feed-api-openapi.yml
  format: yaml
  label: Desenmascara.me Fraud Feed API
  slug: desenmascara-me-fraud-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desenmascara-me/openapi/desenmascara-me-fraud-feed-api-openapi.yml
- filename: desenmascara-me-public-api-openapi.yml
  format: yaml
  label: Desenmascara.me Public API
  slug: desenmascara-me-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desenmascara-me/openapi/desenmascara-me-public-api-openapi.yml
- filename: desenmascara-me-search-api-openapi.yml
  format: yaml
  label: Desenmascara.me Search API
  slug: desenmascara-me-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desenmascara-me/openapi/desenmascara-me-search-api-openapi.yml
- filename: desenmascara-me-threat-intel-api-openapi.yml
  format: yaml
  label: Desenmascara.me Threat Intel API
  slug: desenmascara-me-threat-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desenmascara-me/openapi/desenmascara-me-threat-intel-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email, username, authentication and access logs.'
  - category: other
    text: 'Service data: analyzed domains, timestamps, verdicts, and report metadata.'
  - category: device
    text: 'Security data: IP, user-agent, and language headers for abuse prevention and traceability.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery and account management
    text: Service delivery and account management (Art. 6(1)(b)).
  - purpose: Security, anti-abuse, and fraud prevention
    text: Security, anti-abuse, and fraud prevention (Art. 6(1)(f)).
  - purpose: Legal obligations and compliance
    text: Legal obligations and compliance requirements (Art. 6(1)(c)).
  - purpose: Product updates and service communications
    text: Product updates and service communications when applicable (Art. 6(1)(a)/(f)).
  retention:
  - period: null
    scope: General data
    text: Data is retained only as long as required for operations, security, and legal obligations.
  - period: 14 days
    scope: MCP web server logs (IP address)
    text: appears in our web server logs, kept 14 days.
  - period: 30 days
    scope: MCP application logs (domain asked about)
    text: The domain asked about is kept in our application logs for 30 days, without your IP address.
  - period: 60 seconds
    scope: MCP per-address rate limit counter
    text: a counter that expires after 60 seconds
  rights:
  - right: access, correction, deletion, objection, restriction, portability
    text: You may request access, correction, deletion, objection, restriction, or portability.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Payments are processed by Stripe as payment processor.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Desenmascara.me
provenance_date: '2026-11-09'
provider_name: Desenmascara.me
provider_slug: desenmascara-me
slug: desenmascara-me-privacy-policy
source_date: '2026-11-09'
source_filename: desenmascara-me-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://desenmascara.me/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Desenmascara.me\naid: desenmascara-me\nurl: https://desenmascara.me/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: email, username, authentication and access logs.'\n- category: other\n  text: 'Service data: analyzed domains, timestamps, verdicts, and report metadata.'\n- category: device\n  text: 'Security data: IP, user-agent, and language headers for abuse prevention and traceability.'\npurposes:\n- purpose: Service delivery and account management\n  text: Service delivery and account management (Art. 6(1)(b)).\n\
  - purpose: Security, anti-abuse, and fraud prevention\n  text: Security, anti-abuse, and fraud prevention (Art. 6(1)(f)).\n- purpose: Legal obligations and compliance\n  text: Legal obligations and compliance requirements (Art. 6(1)(c)).\n- purpose: Product updates and service communications\n  text: Product updates and service communications when applicable (Art. 6(1)(a)/(f)).\nretention:\n- scope: General data\n  period: null\n  text: Data is retained only as long as required for operations, security, and legal obligations.\n- scope: MCP web server logs (IP address)\n  period: 14 days\n  text: appears in our web server logs, kept 14 days.\n- scope: MCP application logs (domain asked about)\n  period: 30 days\n  text: The domain asked about is kept in our application logs for 30 days, without your IP address.\n- scope: MCP per-address rate limit counter\n  period: 60 seconds\n  text: a counter that expires after 60 seconds\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n \
  \ text: Payments are processed by Stripe as payment processor.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correction, deletion, objection, restriction, portability\n  text: You may request access, correction, deletion, objection, restriction, or portability.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/desenmascara-me/privacy/desenmascara-me-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- rights
summary_line: 13 quoted statements, read from Desenmascara.me's own page on 2026-11-09.
synthetic: false
tags:
- Fraud Prevention
- Scam Prevention
- Security
- Risk Intelligence
---
