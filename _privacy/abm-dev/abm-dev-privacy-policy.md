---
api_specs:
- filename: abm-dev-campaigns-api-openapi.yml
  format: yaml
  label: abm-dev Campaigns API
  slug: abm-dev-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-campaigns-api-openapi.yml
- filename: abm-dev-crm-api-openapi.yml
  format: yaml
  label: abm-dev CRM API
  slug: abm-dev-crm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-crm-api-openapi.yml
- filename: abm-dev-enrichment-api-openapi.yml
  format: yaml
  label: abm-dev Enrichment API
  slug: abm-dev-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-enrichment-api-openapi.yml
- filename: abm-dev-enrichment-config-api-openapi.yml
  format: yaml
  label: abm-dev Enrichment Config API
  slug: abm-dev-enrichment-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-enrichment-config-api-openapi.yml
- filename: abm-dev-field-configuration-api-openapi.yml
  format: yaml
  label: abm-dev Field Configuration API
  slug: abm-dev-field-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-field-configuration-api-openapi.yml
- filename: abm-dev-health-api-openapi.yml
  format: yaml
  label: abm-dev Health API
  slug: abm-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-health-api-openapi.yml
- filename: abm-dev-organization-api-openapi.yml
  format: yaml
  label: abm-dev Organization API
  slug: abm-dev-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-organization-api-openapi.yml
- filename: abm-dev-people-finder-api-openapi.yml
  format: yaml
  label: abm-dev People Finder API
  slug: abm-dev-people-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-people-finder-api-openapi.yml
- filename: abm-dev-webhooks-api-openapi.yml
  format: yaml
  label: abm-dev Webhooks API
  slug: abm-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abm-dev/openapi/abm-dev-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email, organization, role, authentication identifiers.'
  - category: financial
    text: 'Billing data: subscription details, invoices, payment method references via Stripe (we do not store full card data).'
  - category: behavioral
    text: 'Telemetry: performance, errors, usage events, cost metrics (e.g., tokens, model provider, latency).'
  - category: device
    text: 'Website data: cookies, device, IP address, analytics events.'
  - category: other
    text: 'Service data: seed inputs (e.g., emails, domains), API requests and responses, metadata (request_id, timestamps, confidence scores, sources).'
  deletion:
    route: Email the privacy contact
    text: 'To exercise rights: [email protected] .'
  dpa:
    available: true
    text: under our Data Processing Addendum (DPA) where applicable
    url: null
  purposes:
  - purpose: Provide and secure the Service
    text: Provide and secure the Service (contract).
  - purpose: Billing and account management
    text: Billing and account management (contract, legal obligation).
  - purpose: Fraud, abuse, and rate-limit enforcement
    text: Fraud, abuse, and rate-limit enforcement (legitimate interests).
  - purpose: Product analytics and cost monitoring
    text: Product analytics and cost monitoring (legitimate interests, with opt-out where applicable).
  - purpose: Compliance with law
    text: Compliance with law and requests from authorities (legal obligation).
  retention:
  - period: 6 years
    scope: Account and billing records
    text: 'Account and billing records: as required by law (typically 6 years in the UK).'
  - period: 12 months
    scope: Service logs and telemetry
    text: 'Service logs and telemetry: default 12 months unless you request a shorter window.'
  - period: 30 days
    scope: Cached enrichment data
    text: 'Cached enrichment data: default 30 days (configurable by customer).'
  rights:
  - right: Access
    text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.
  - right: Rectification
    text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.
  - right: Erasure
    text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.
  - right: Restriction
    text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.
  - right: Portability
    text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.
  - right: Objection
    text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.
  role:
    text: We act as controller for account, billing, and website data, and as processor for Service data you submit, under our Data Processing Addendum (DPA) where applicable.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A current list is available on request.
    url: null
  transfers:
  - mechanism: adequacy
    text: We may transfer data outside the UK/EEA. Where we do, we rely on adequacy decisions or Standard Contractual Clauses with supplemental measures.
  - mechanism: SCC
    text: Where we do, we rely on adequacy decisions or Standard Contractual Clauses with supplemental measures.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: abm-dev
provenance_date: '2026-11-09'
provider_name: abm-dev
provider_slug: abm-dev
slug: abm-dev-privacy-policy
source_date: '2026-11-09'
source_filename: abm-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://abm.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: abm-dev\naid: abm-dev\nurl: https://abm.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We act as controller for account, billing, and website data, and as processor for Service data you submit,\n    under our Data Processing Addendum (DPA) where applicable.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email, organization, role, authentication identifiers.'\n- category: financial\n  text: 'Billing data: subscription details, invoices, payment method references via Stripe (we do not store full\n    card data).'\n- category: behavioral\n  text: 'Telemetry: performance,\
  \ errors, usage events, cost metrics (e.g., tokens, model provider, latency).'\n- category: device\n  text: 'Website data: cookies, device, IP address, analytics events.'\n- category: other\n  text: 'Service data: seed inputs (e.g., emails, domains), API requests and responses, metadata (request_id, timestamps,\n    confidence scores, sources).'\npurposes:\n- purpose: Provide and secure the Service\n  text: Provide and secure the Service (contract).\n- purpose: Billing and account management\n  text: Billing and account management (contract, legal obligation).\n- purpose: Fraud, abuse, and rate-limit enforcement\n  text: Fraud, abuse, and rate-limit enforcement (legitimate interests).\n- purpose: Product analytics and cost monitoring\n  text: Product analytics and cost monitoring (legitimate interests, with opt-out where applicable).\n- purpose: Compliance with law\n  text: Compliance with law and requests from authorities (legal obligation).\nretention:\n- scope: Account and billing records\n\
  \  period: 6 years\n  text: 'Account and billing records: as required by law (typically 6 years in the UK).'\n- scope: Service logs and telemetry\n  period: 12 months\n  text: 'Service logs and telemetry: default 12 months unless you request a shorter window.'\n- scope: Cached enrichment data\n  period: 30 days\n  text: 'Cached enrichment data: default 30 days (configurable by customer).'\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: We may transfer data outside the UK/EEA. Where we do, we rely on adequacy decisions or Standard Contractual\n    Clauses with supplemental measures.\n- mechanism: SCC\n  text: Where we do, we rely on adequacy decisions or Standard Contractual Clauses with supplemental measures.\nsubprocessors:\n  url: null\n  text: A current list is available on request.\ndpa:\n  available: true\n  url: null\n  text: under our Data Processing Addendum (DPA) where applicable\ndeletion:\n  route: Email the privacy contact\n  text: 'To exercise rights: [email protected]\
  \ .'\nrights:\n- right: Access\n  text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.\n- right: Rectification\n  text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.\n- right: Erasure\n  text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.\n- right: Restriction\n  text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.\n- right: Portability\n  text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.\n- right: Objection\n  text: Access, rectification, erasure, restriction, portability, objection, and the right to complain to the ICO.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/abm-dev/privacy/abm-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 25 quoted statements, read from abm-dev's own page on 2026-11-09.
synthetic: false
tags:
- Account Based Marketing
- AI Agents
- Data Enrichment
- B2B
- Marketing API
---
