---
api_specs:
- filename: nordicmcp-eu-openapi-generated.yml
  format: yaml
  label: nordicmcp-eu API
  slug: nordicmcp-eu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nordicmcp-eu/openapi/_ae-authored/nordicmcp-eu-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address when you create an account.
  - category: device
    text: IP addresses (first octet only in logs), browser type, operating system, pages visited, timestamps, and referrer URLs for security monitoring.
  - category: behavioral
    text: Integration activations, endpoint URLs generated, call volumes, response times, error rates, and API request patterns
  - category: financial
    text: the only exception is payment processing via Stripe, which requires transmission of billing information to Stripe's US-based servers.
  deletion:
    route: account deletion
    text: Upon account deletion, we remove personal data within 30 days, except where retention is required for legal obligations or legitimate business interests
  dpa:
    available: null
    text: 'Infrastructure Providers: Cloud hosting, CDN, and DDoS protection services — bound by standard data processing agreements.'
    url: null
  purposes:
  - purpose: provide and maintain the Service
    text: provide and maintain the Service
  - purpose: service notifications
    text: send service-related notifications (outages, maintenance windows, policy changes)
  - purpose: improve platform
    text: improve our platform based on aggregated usage patterns
  - purpose: prevent fraud and abuse
    text: prevent fraud and abuse
  - purpose: legal obligations
    text: comply with legal obligations
  residency:
  - region: EEA (Sweden)
    text: NordicMCP's infrastructure is hosted entirely within the European Economic Area (EEA), specifically in Sweden.
  retention:
  - period: while your account is active
    scope: account data
    text: We retain your account data while your account is active.
  - period: 30 days
    scope: personal data after account deletion
    text: Upon account deletion, we remove personal data within 30 days
  - period: up to 1 year
    scope: security incident records
    text: 'security incident records: up to 1 year'
  rights:
  - right: access
    text: 'Access: Request a copy of your personal data in machine-readable format'
  - right: correction
    text: 'Correction: Request correction of inaccurate or incomplete data'
  - right: deletion
    text: 'Deletion: Request deletion of your account and personal data'
  - right: portability
    text: 'Portability: Receive your data in a commonly used, machine-readable format'
  - right: objection
    text: 'Objection: Object to processing based on legitimate interests'
  role:
    text: NordicMCP is operated by Peter Frank, based in Malmö, Sweden.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Stripe is an EU-approved data processor with appropriate safeguards in place (Standard Contractual Clauses).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: nordicmcp-eu
provenance_date: '2026-11-10'
provider_name: nordicmcp-eu
provider_slug: nordicmcp-eu
slug: nordicmcp-eu-privacy-policy
source_date: '2026-11-10'
source_filename: nordicmcp-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nordicmcp.eu/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: nordicmcp-eu\naid: nordicmcp-eu\nurl: https://nordicmcp.eu/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: NordicMCP is operated by Peter Frank, based in Malmö, Sweden.\ndata_categories:\n- category: identifying\n  text: Name and email address when you create an account.\n- category: device\n  text: IP addresses (first octet only in logs), browser type, operating system, pages visited, timestamps, and\n    referrer URLs for security monitoring.\n- category: behavioral\n  text: Integration activations, endpoint URLs generated, call volumes, response times, error rates, and API request\n\
  \    patterns\n- category: financial\n  text: the only exception is payment processing via Stripe, which requires transmission of billing information\n    to Stripe's US-based servers.\npurposes:\n- purpose: provide and maintain the Service\n  text: provide and maintain the Service\n- purpose: service notifications\n  text: send service-related notifications (outages, maintenance windows, policy changes)\n- purpose: improve platform\n  text: improve our platform based on aggregated usage patterns\n- purpose: prevent fraud and abuse\n  text: prevent fraud and abuse\n- purpose: legal obligations\n  text: comply with legal obligations\nretention:\n- scope: account data\n  period: while your account is active\n  text: We retain your account data while your account is active.\n- scope: personal data after account deletion\n  period: 30 days\n  text: Upon account deletion, we remove personal data within 30 days\n- scope: security incident records\n  period: up to 1 year\n  text: 'security incident\
  \ records: up to 1 year'\nresidency:\n- region: EEA (Sweden)\n  text: NordicMCP's infrastructure is hosted entirely within the European Economic Area (EEA), specifically in Sweden.\ntransfers:\n- mechanism: SCC\n  text: Stripe is an EU-approved data processor with appropriate safeguards in place (Standard Contractual Clauses).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: 'Infrastructure Providers: Cloud hosting, CDN, and DDoS protection services — bound by standard data processing\n    agreements.'\ndeletion:\n  route: account deletion\n  text: Upon account deletion, we remove personal data within 30 days, except where retention is required for legal\n    obligations or legitimate business interests\nrights:\n- right: access\n  text: 'Access: Request a copy of your personal data in machine-readable format'\n- right: correction\n  text: 'Correction: Request correction of inaccurate or incomplete data'\n- right: deletion\n  text: 'Deletion: Request\
  \ deletion of your account and personal data'\n- right: portability\n  text: 'Portability: Receive your data in a commonly used, machine-readable format'\n- right: objection\n  text: 'Objection: Object to processing based on legitimate interests'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal data.\n"
source_yaml_url: https://artifacts.apis.io/nordicmcp-eu/privacy/nordicmcp-eu-privacy-policy.yml
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
- sale_or_sharing
summary_line: 23 quoted statements, read from nordicmcp-eu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- Artificial Intelligence
- Integration
- Sweden
---
