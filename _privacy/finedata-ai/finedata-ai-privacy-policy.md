---
api_specs:
- filename: finedata-ai-api-keys-api-openapi.yml
  format: yaml
  label: finedata-ai API Keys API
  slug: finedata-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-api-keys-api-openapi.yml
- filename: finedata-ai-async-scraping-api-openapi.yml
  format: yaml
  label: finedata-ai Async Scraping API
  slug: finedata-ai-async-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-async-scraping-api-openapi.yml
- filename: finedata-ai-google-serp-api-openapi.yml
  format: yaml
  label: finedata-ai Google SERP API
  slug: finedata-ai-google-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-google-serp-api-openapi.yml
- filename: finedata-ai-oauth-api-openapi.yml
  format: yaml
  label: finedata-ai OAuth API
  slug: finedata-ai-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-oauth-api-openapi.yml
- filename: finedata-ai-plans-api-openapi.yml
  format: yaml
  label: finedata-ai Plans API
  slug: finedata-ai-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-plans-api-openapi.yml
- filename: finedata-ai-proxy-profiles-byop-api-openapi.yml
  format: yaml
  label: finedata-ai Proxy Profiles (BYOP) API
  slug: finedata-ai-proxy-profiles-byop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-proxy-profiles-byop-api-openapi.yml
- filename: finedata-ai-user-api-openapi.yml
  format: yaml
  label: finedata-ai User API
  slug: finedata-ai-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-user-api-openapi.yml
- filename: finedata-ai-user-statistics-api-openapi.yml
  format: yaml
  label: finedata-ai User Statistics API
  slug: finedata-ai-user-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-user-statistics-api-openapi.yml
- filename: finedata-ai-web-scraping-api-openapi.yml
  format: yaml
  label: finedata-ai Web Scraping API
  slug: finedata-ai-web-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finedata-ai/openapi/finedata-ai-web-scraping-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Name (if provided) Company name (if provided)
  - category: financial
    text: Billing address Transaction history and invoice records
  - category: device
    text: Browser type and version Operating system
  - category: location
    text: Approximate geographic location (country/region level, derived from IP)
  - category: behavioral
    text: Pages visited and time spent Referring URL
  - category: communication
    text: Support communications and emails
  deletion:
    route: Email support@finedata.ai with the subject line "Data Deletion Request"
    text: To request deletion of your account and the personal data associated with it, email support@finedata.ai with the subject line "Data Deletion Request".
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and manage services
    text: Provide and manage services
  - purpose: Process payments and invoicing
    text: Process payments, invoicing
  - purpose: Security and abuse prevention
    text: Security, abuse prevention, metering, support
  - purpose: Improve website experience
    text: Improve website experience
  - purpose: Product updates and newsletters
    text: Product updates, newsletters
  residency:
  - region: EU (Frankfurt) and Germany
    text: Our primary infrastructure is hosted in EU (Frankfurt) and Germany via AWS and Hetzner.
  - region: United States
    text: Only billing and account management may involve US-based processing
  retention:
  - period: as long as your account is active
    scope: Account data
    text: Retained for as long as your account is active.
  - period: 7 years
    scope: Billing records
    text: 'Billing records: Retained for 7 years as required by tax and accounting regulations.'
  - period: 365 days
    scope: Request audit trail detailed events
    text: Detailed events (IP address, API key ID, request method/path/target URL, status, timing) are retained for 365 days for security, abuse prevention, and support, then automatically purged.
  - period: 24 hours
    scope: Async / MCP job results
    text: Job output (including page content and any requested screenshot) is retained for up to 24 hours so it can be retrieved, then deleted.
  - period: 7 days
    scope: Async / MCP job metadata
    text: Job metadata (request options and status, used to list recent jobs) is retained for up to 7 days, then deleted.
  - period: 30 days
    scope: OAuth connections
    text: A refresh token is valid for up to 30 days from issuance and is deleted immediately when you revoke the connection from your dashboard, change your password, or let it expire.
  - period: 12 months
    scope: Website analytics
    text: 'Website analytics: Retained for up to 12 months in anonymized form.'
  rights:
  - right: Access
    text: Access — request a copy of the personal data we hold about you
  - right: Correction / Rectification
    text: Correction / Rectification — request correction of inaccurate or incomplete data
  - right: Deletion / Erasure
    text: Deletion / Erasure — request deletion of your personal data (subject to legal retention requirements)
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format (JSON or CSV)
  - right: Restriction
    text: Restriction — request that we limit processing of your data in certain circumstances
  - right: Objection
    text: Objection — object to processing of your data based on legitimate interest
  - right: Withdraw Consent
    text: Withdraw Consent — where processing is based on consent, withdraw it at any time without affecting the lawfulness of prior processing
  - right: Lodge a Complaint
    text: Lodge a Complaint — file a complaint with a supervisory authority in your jurisdiction if you believe your rights have been violated
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, so no opt-out for data sales is necessary
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) — We use the European Commission's Standard Contractual Clauses as the primary mechanism for EU/EEA data transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: finedata-ai
provenance_date: '2026-11-09'
provider_name: finedata-ai
provider_slug: finedata-ai
slug: finedata-ai-privacy-policy
source_date: '2026-11-09'
source_filename: finedata-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://finedata.ai/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: finedata-ai\naid: finedata-ai\nurl: https://finedata.ai/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address Name (if provided) Company name (if provided)\n- category: financial\n  text: Billing address Transaction history and invoice records\n- category: device\n  text: Browser type and version Operating system\n- category: location\n  text: Approximate geographic location (country/region level, derived from IP)\n- category: behavioral\n  text: Pages visited and time spent Referring URL\n- category: communication\n\
  \  text: Support communications and emails\npurposes:\n- purpose: Provide and manage services\n  text: Provide and manage services\n- purpose: Process payments and invoicing\n  text: Process payments, invoicing\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention, metering, support\n- purpose: Improve website experience\n  text: Improve website experience\n- purpose: Product updates and newsletters\n  text: Product updates, newsletters\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: Retained for as long as your account is active.\n- scope: Billing records\n  period: 7 years\n  text: 'Billing records: Retained for 7 years as required by tax and accounting regulations.'\n- scope: Request audit trail detailed events\n  period: 365 days\n  text: Detailed events (IP address, API key ID, request method/path/target URL, status, timing) are retained for\n    365 days for security, abuse prevention, and support, then automatically\
  \ purged.\n- scope: Async / MCP job results\n  period: 24 hours\n  text: Job output (including page content and any requested screenshot) is retained for up to 24 hours so it can\n    be retrieved, then deleted.\n- scope: Async / MCP job metadata\n  period: 7 days\n  text: Job metadata (request options and status, used to list recent jobs) is retained for up to 7 days, then deleted.\n- scope: OAuth connections\n  period: 30 days\n  text: A refresh token is valid for up to 30 days from issuance and is deleted immediately when you revoke the\n    connection from your dashboard, change your password, or let it expire.\n- scope: Website analytics\n  period: 12 months\n  text: 'Website analytics: Retained for up to 12 months in anonymized form.'\nresidency:\n- region: EU (Frankfurt) and Germany\n  text: Our primary infrastructure is hosted in EU (Frankfurt) and Germany via AWS and Hetzner.\n- region: United States\n  text: Only billing and account management may involve US-based processing\n\
  transfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) — We use the European Commission's Standard Contractual Clauses as the\n    primary mechanism for EU/EEA data transfers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@finedata.ai with the subject line \"Data Deletion Request\"\n  text: To request deletion of your account and the personal data associated with it, email support@finedata.ai\n    with the subject line \"Data Deletion Request\".\nrights:\n- right: Access\n  text: Access — request a copy of the personal data we hold about you\n- right: Correction / Rectification\n  text: Correction / Rectification — request correction of inaccurate or incomplete data\n- right: Deletion / Erasure\n  text: Deletion / Erasure — request deletion of your personal data (subject to legal retention requirements)\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable\
  \ format (JSON or CSV)\n- right: Restriction\n  text: Restriction — request that we limit processing of your data in certain circumstances\n- right: Objection\n  text: Objection — object to processing of your data based on legitimate interest\n- right: Withdraw Consent\n  text: Withdraw Consent — where processing is based on consent, withdraw it at any time without affecting the lawfulness\n    of prior processing\n- right: Lodge a Complaint\n  text: Lodge a Complaint — file a complaint with a supervisory authority in your jurisdiction if you believe your\n    rights have been violated\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, so no opt-out for data sales is necessary\n"
source_yaml_url: https://artifacts.apis.io/finedata-ai/privacy/finedata-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from finedata-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Web Scraping
- Data Extraction
- MCP
- LLM
---
