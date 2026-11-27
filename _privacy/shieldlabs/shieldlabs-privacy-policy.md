---
api_specs:
- filename: shieldlabs-history-api-api-openapi.yml
  format: yaml
  label: ShieldLabs History API
  slug: shieldlabs-history-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shieldlabs/openapi/shieldlabs-history-api-api-openapi.yml
- filename: shieldlabs-management-api-api-openapi.yml
  format: yaml
  label: ShieldLabs Management API
  slug: shieldlabs-management-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shieldlabs/openapi/shieldlabs-management-api-api-openapi.yml
- filename: shieldlabs-shieldlabs-api-api-openapi.yml
  format: yaml
  label: ShieldLabs API
  slug: shieldlabs-shieldlabs-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shieldlabs/openapi/shieldlabs-shieldlabs-api-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Categories may include device and browser signals (including fingerprinting-related signals), network identifiers (e.g., IP address)
  - category: behavioral
    text: behavioral and event signals, WebRTC/network connectivity metadata, and derived risk scores or labels
  - category: contact
    text: we process account and contact information, authentication and access logs, billing and payment records, support communications, product usage metrics, and marketing preferences.
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: Standard Contractual Clauses under a Data Processing Addendum when executed with Customer.
    url: null
  purposes:
  - purpose: Provide and secure the Service
    text: We process Controller Data to provide and secure the Service, authenticate users, process payments, prevent abuse, analyze product and website performance, provide support
  - purpose: Customer fraud and security decisions
    text: The Service produces risk scores, signals, and labels to support Customer’s fraud and security decisions.
  residency:
  - region: European Union (Germany / Frankfurt)
    text: Primary processing and storage for the Service are in the European Union (Germany / Frankfurt region).
  retention:
  - period: twelve (12) months
    scope: Customer Data
    text: Customer Data retention is up to twelve (12) months and may vary by plan, including on the Free Plan.
  - period: null
    scope: Controller Data
    text: Controller Data is retained as long as needed for the purposes above and as required by law.
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: We handle requests from individuals (e.g., access, rectification, erasure, restriction, portability, objection, and the right to lodge a complaint with a supervisory authority)
  role:
    text: We act as a processor for Customer end-user technical data processed on Customer’s behalf, and as a controller for our own account, billing, marketing, and website data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use appropriate contractual safeguards, including Standard Contractual Clauses under a Data Processing Addendum when executed with Customer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ShieldLabs
provenance_date: '2026-11-10'
provider_name: ShieldLabs
provider_slug: shieldlabs
slug: shieldlabs-privacy-policy
source_date: '2026-11-10'
source_filename: shieldlabs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.shieldlabs.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ShieldLabs\naid: shieldlabs\nurl: https://docs.shieldlabs.ai/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We act as a processor for Customer end-user technical data processed on Customer’s behalf, and as a controller\n    for our own account, billing, marketing, and website data.\ndata_categories:\n- category: identifying\n  text: Categories may include device and browser signals (including fingerprinting-related signals), network identifiers\n    (e.g., IP address)\n- category: behavioral\n  text: behavioral and event signals, WebRTC/network connectivity metadata, and derived\
  \ risk scores or labels\n- category: contact\n  text: we process account and contact information, authentication and access logs, billing and payment records,\n    support communications, product usage metrics, and marketing preferences.\npurposes:\n- purpose: Provide and secure the Service\n  text: We process Controller Data to provide and secure the Service, authenticate users, process payments, prevent\n    abuse, analyze product and website performance, provide support\n- purpose: Customer fraud and security decisions\n  text: The Service produces risk scores, signals, and labels to support Customer’s fraud and security decisions.\nretention:\n- scope: Customer Data\n  period: twelve (12) months\n  text: Customer Data retention is up to twelve (12) months and may vary by plan, including on the Free Plan.\n- scope: Controller Data\n  period: null\n  text: Controller Data is retained as long as needed for the purposes above and as required by law.\nresidency:\n- region: European Union\
  \ (Germany / Frankfurt)\n  text: Primary processing and storage for the Service are in the European Union (Germany / Frankfurt region).\ntransfers:\n- mechanism: SCC\n  text: Where required, we use appropriate contractual safeguards, including Standard Contractual Clauses under\n    a Data Processing Addendum when executed with Customer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Standard Contractual Clauses under a Data Processing Addendum when executed with Customer.\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: We handle requests from individuals (e.g., access, rectification, erasure, restriction, portability, objection,\n    and the right to lodge a complaint with a supervisory authority)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/shieldlabs/privacy/shieldlabs-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from ShieldLabs's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Abuse Prevention
- Visitor Identification
- Device Fingerprinting
- Bot Detection
- vpn-proxy-detection
- Risk Scoring
- Identity
- Security
- Webhook
- Traffic Quality
- A2A
---
