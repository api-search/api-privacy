---
api_specs:
- filename: vettly-moderation-api-openapi.yml
  format: yaml
  label: Vettly Moderation API
  slug: vettly-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vettly/openapi/vettly-moderation-api-openapi.yml
- filename: vettly-system-api-openapi.yml
  format: yaml
  label: Vettly System API
  slug: vettly-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vettly/openapi/vettly-system-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name and email address
  - category: financial
    text: Payment information (processed securely through Stripe or Polar - we do not store full card numbers)
  - category: device
    text: Device information (browser type, version, operating system, device model)
  - category: behavioral
    text: Log data (access times, pages viewed, click paths, errors encountered)
  - category: communication
    text: Support tickets, inquiries, and correspondence
  - category: location
    text: Location check-ins, family place events, and app/screen usage summaries when enabled
  - category: demographic
    text: approximate age or birth date
  deletion:
    route: Dashboard or API
    text: You can request earlier deletion through the dashboard or API.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision
    text: Process API requests and generate decisions using AI providers
  - purpose: Model improvement
    text: Improve AI model accuracy and decision quality (with anonymized/aggregated data)
  - purpose: Fraud and security
    text: Detect, investigate, and prevent fraud, abuse, and security threats
  - purpose: Marketing with consent
    text: Send promotional emails about new features and updates (opt-in only)
  residency:
  - region: Primary
    text: Depends on hosting/provider configuration (Cloudflare is global; PostgreSQL database region varies)
  - region: Options
    text: Data residency options may be available by separate written arrangement
  retention:
  - period: 24 hours
    scope: Free tier content
    text: 'Free tier: 24 hours'
  - period: 1 year
    scope: Starter tier content
    text: 'Starter tier: 1 year'
  - period: 3 years
    scope: Growth tier content
    text: 'Growth tier: 3 years'
  - period: 90 days
    scope: API logs
    text: 'API logs: Retained for 90 days for debugging and security'
  - period: 7 years
    scope: Billing records
    text: 'Billing records: Retained for 7 years as required by tax and accounting laws'
  - period: up to 90 days after deletion
    scope: Backup copies
    text: Backup copies may persist for up to 90 days after deletion.
  rights:
  - right: Access
    text: 'Access: Request access to your personal data and download it'
  - right: Correction
    text: 'Correction: Update inaccurate or incomplete personal data'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data ("right to be forgotten")'
  - right: Portability
    text: 'Portability: Receive your data in a structured, machine-readable format'
  - right: Objection
    text: 'Right to Object: Object to processing based on legitimate interests or for direct marketing'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 'Opt-Out of Sale: We do not sell personal information'
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you require specific transfer mechanisms (e.g., SCCs) or region pinning, contact us before using the Services.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vettly
provenance_date: '2026-11-10'
provider_name: Vettly
provider_slug: vettly
slug: vettly-privacy-policy
source_date: '2026-11-10'
source_filename: vettly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vettly.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vettly\naid: vettly\nurl: https://vettly.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Full name and email address\n- category: financial\n  text: Payment information (processed securely through Stripe or Polar - we do not store full card numbers)\n- category: device\n  text: Device information (browser type, version, operating system, device model)\n- category: behavioral\n  text: Log data (access times, pages viewed, click paths, errors encountered)\n- category: communication\n  text: Support tickets, inquiries, and correspondence\n\
  - category: location\n  text: Location check-ins, family place events, and app/screen usage summaries when enabled\n- category: demographic\n  text: approximate age or birth date\npurposes:\n- purpose: Service provision\n  text: Process API requests and generate decisions using AI providers\n- purpose: Model improvement\n  text: Improve AI model accuracy and decision quality (with anonymized/aggregated data)\n- purpose: Fraud and security\n  text: Detect, investigate, and prevent fraud, abuse, and security threats\n- purpose: Marketing with consent\n  text: Send promotional emails about new features and updates (opt-in only)\nretention:\n- scope: Free tier content\n  period: 24 hours\n  text: 'Free tier: 24 hours'\n- scope: Starter tier content\n  period: 1 year\n  text: 'Starter tier: 1 year'\n- scope: Growth tier content\n  period: 3 years\n  text: 'Growth tier: 3 years'\n- scope: API logs\n  period: 90 days\n  text: 'API logs: Retained for 90 days for debugging and security'\n- scope:\
  \ Billing records\n  period: 7 years\n  text: 'Billing records: Retained for 7 years as required by tax and accounting laws'\n- scope: Backup copies\n  period: up to 90 days after deletion\n  text: Backup copies may persist for up to 90 days after deletion.\nresidency:\n- region: Primary\n  text: Depends on hosting/provider configuration (Cloudflare is global; PostgreSQL database region varies)\n- region: Options\n  text: Data residency options may be available by separate written arrangement\ntransfers:\n- mechanism: other\n  text: If you require specific transfer mechanisms (e.g., SCCs) or region pinning, contact us before using the\n    Services.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard or API\n  text: You can request earlier deletion through the dashboard or API.\nrights:\n- right: Access\n  text: 'Access: Request access to your personal data and download it'\n- right: Correction\n  text: 'Correction:\
  \ Update inaccurate or incomplete personal data'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data (\"right to be forgotten\")'\n- right: Portability\n  text: 'Portability: Receive your data in a structured, machine-readable format'\n- right: Objection\n  text: 'Right to Object: Object to processing based on legitimate interests or for direct marketing'\nsale_or_sharing:\n  stance: prohibited\n  text: 'Opt-Out of Sale: We do not sell personal information'\n"
source_yaml_url: https://artifacts.apis.io/vettly/privacy/vettly-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Vettly's own page on 2026-11-10.
synthetic: false
tags:
- Content Moderation
- Trust and Safety
- Security
- Text Analysis
- Image Moderation
- video-moderation
- UGC
- Compliance
- agent-guardrails
- MCP
---
