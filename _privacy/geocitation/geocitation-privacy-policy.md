---
api_specs:
- filename: geocitation-audits-api-openapi.yml
  format: yaml
  label: GEOCitation Audits API
  slug: geocitation-audits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-audits-api-openapi.yml
- filename: geocitation-gdpr-api-openapi.yml
  format: yaml
  label: GEOCitation Gdpr API
  slug: geocitation-gdpr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-gdpr-api-openapi.yml
- filename: geocitation-health-api-openapi.yml
  format: yaml
  label: GEOCitation Health API
  slug: geocitation-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-health-api-openapi.yml
- filename: geocitation-meta-api-openapi.yml
  format: yaml
  label: GEOCitation Meta API
  slug: geocitation-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-meta-api-openapi.yml
- filename: geocitation-opt-out-api-openapi.yml
  format: yaml
  label: GEOCitation Opt Out API
  slug: geocitation-opt-out-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-opt-out-api-openapi.yml
- filename: geocitation-usage-api-openapi.yml
  format: yaml
  label: GEOCitation Usage API
  slug: geocitation-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-usage-api-openapi.yml
- filename: geocitation-agent-tasks-api-openapi.yml
  format: yaml
  label: GEOCitation Agent Tasks API
  slug: geocitation-agent-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-agent-tasks-api-openapi.yml
- filename: geocitation-agents-api-openapi.yml
  format: yaml
  label: GEOCitation Agents API
  slug: geocitation-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-agents-api-openapi.yml
- filename: geocitation-campaigns-api-openapi.yml
  format: yaml
  label: GEOCitation Campaigns API
  slug: geocitation-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-campaigns-api-openapi.yml
- filename: geocitation-crawler-traffic-api-openapi.yml
  format: yaml
  label: GEOCitation Crawler Traffic API
  slug: geocitation-crawler-traffic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-crawler-traffic-api-openapi.yml
- filename: geocitation-google-auth-api-openapi.yml
  format: yaml
  label: GEOCitation Google Auth API
  slug: geocitation-google-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-google-auth-api-openapi.yml
- filename: geocitation-report-pptx-api-openapi.yml
  format: yaml
  label: GEOCitation Report Pptx API
  slug: geocitation-report-pptx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-report-pptx-api-openapi.yml
- filename: geocitation-user-agents-api-openapi.yml
  format: yaml
  label: GEOCitation User Agents API
  slug: geocitation-user-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geocitation/openapi/geocitation-user-agents-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: account information (email, name, organization) via Clerk
  - category: financial
    text: billing data via our payment provider
  - category: device
    text: technical data (hashed IP, user-agent) for security
  - category: behavioral
    text: audit data (keywords, URLs, results) you submit to us
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: All subprocessors are under GDPR-compliant DPA.
    url: null
  purposes:
  - purpose: provide the Service
    text: 'Data is used to: provide the Service, communicate with you, improve features, comply with legal obligations.'
  - purpose: improve features
    text: 'Data is used to: provide the Service, communicate with you, improve features, comply with legal obligations.'
  residency:
  - region: EU
    text: Our data is hosted exclusively in the EU (Google Cloud europe-west1 Belgium).
  retention:
  - period: 3 years after cancellation
    scope: Account data
    text: 'Account data: retained while the account is active + 3 years after cancellation (accounting obligations).'
  - period: 30 days
    scope: Technical logs
    text: 'Technical logs: 30 days.'
  - period: 7 years
    scope: SOC2 audit logs
    text: 'SOC2 audit logs: 7 years.'
  rights:
  - right: access
    text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction of processing.'
  - right: rectification
    text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction of processing.'
  - right: erasure
    text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction of processing.'
  - right: portability
    text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction of processing.'
  - right: objection
    text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction of processing.'
  - right: restriction of processing
    text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction of processing.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data to third parties.
  subprocessors:
    text: 'We share strictly necessary data with: Clerk (authentication), Supabase (database), Google Cloud (hosting), our payment provider.'
    url: null
  transfers:
  - mechanism: SCC
    text: No transfer outside the EU is made without appropriate safeguards (EU Standard Contractual Clauses).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GEOCitation
provenance_date: '2026-11-09'
provider_name: GEOCitation
provider_slug: geocitation
slug: geocitation-privacy-policy
source_date: '2026-11-09'
source_filename: geocitation-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.geocitation.io/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GEOCitation\naid: geocitation\nurl: https://www.geocitation.io/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: account information (email, name, organization) via Clerk\n- category: financial\n  text: billing data via our payment provider\n- category: device\n  text: technical data (hashed IP, user-agent) for security\n- category: behavioral\n  text: audit data (keywords, URLs, results) you submit to us\npurposes:\n- purpose: provide the Service\n  text: 'Data is used to: provide the Service, communicate with you, improve features,\
  \ comply with legal obligations.'\n- purpose: improve features\n  text: 'Data is used to: provide the Service, communicate with you, improve features, comply with legal obligations.'\nretention:\n- scope: Account data\n  period: 3 years after cancellation\n  text: 'Account data: retained while the account is active + 3 years after cancellation (accounting obligations).'\n- scope: Technical logs\n  period: 30 days\n  text: 'Technical logs: 30 days.'\n- scope: SOC2 audit logs\n  period: 7 years\n  text: 'SOC2 audit logs: 7 years.'\nresidency:\n- region: EU\n  text: Our data is hosted exclusively in the EU (Google Cloud europe-west1 Belgium).\ntransfers:\n- mechanism: SCC\n  text: No transfer outside the EU is made without appropriate safeguards (EU Standard Contractual Clauses).\nsubprocessors:\n  url: null\n  text: 'We share strictly necessary data with: Clerk (authentication), Supabase (database), Google Cloud (hosting),\n    our payment provider.'\ndpa:\n  available: true\n  url: null\n\
  \  text: All subprocessors are under GDPR-compliant DPA.\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction\n    of processing.'\n- right: rectification\n  text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction\n    of processing.'\n- right: erasure\n  text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction\n    of processing.'\n- right: portability\n  text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction\n    of processing.'\n- right: objection\n  text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection, and restriction\n    of processing.'\n- right: restriction of processing\n  text: 'Under GDPR you have rights to: access, rectification, erasure, portability, objection,\
  \ and restriction\n    of processing.'\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/geocitation/privacy/geocitation-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from GEOCitation's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- Geo
- Answer Engine Optimization
- AI Search Visibility
- Content Intelligence
- Competitive Intelligence
- Marketing
- MarTech
- White Label
- Agency Tooling
- Web Data & Analytics
---
