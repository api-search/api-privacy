---
api_specs:
- filename: bol-ai-billing-api-openapi.yml
  format: yaml
  label: Bol.ai Billing API
  slug: bol-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-billing-api-openapi.yml
- filename: bol-ai-bol-api-openapi.yml
  format: yaml
  label: Bol.ai Bol API
  slug: bol-ai-bol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-bol-api-openapi.yml
- filename: bol-ai-mcp-api-openapi.yml
  format: yaml
  label: Bol.ai MCP API
  slug: bol-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-mcp-api-openapi.yml
- filename: bol-ai-me-api-openapi.yml
  format: yaml
  label: Bol.ai Me API
  slug: bol-ai-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-me-api-openapi.yml
- filename: bol-ai-usage-api-openapi.yml
  format: yaml
  label: Bol.ai Usage API
  slug: bol-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bol-ai/openapi/bol-ai-usage-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data Email address, hashed password, API key hashes
  - category: other
    text: Bills of Lading you upload, email in, or submit via API; the structured fields extracted from them; your corrections
  - category: financial
    text: Billing data Subscription status, purchases, usage counts.
  - category: device
    text: IP address (rate limiting)
  - category: communication
    text: Email address and message content for transactional email (password resets)
  deletion:
    route: Account settings in the app, or email support@bol.ai
    text: You can delete your entire account from Account settings in the app (email confirmation and password required) or by emailing support@bol.ai
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the service
    text: Providing the service (contract, art. 6(1)(b))
  - purpose: Security and service quality
    text: Security and service quality (legitimate interest, art. 6(1)(f))
  - purpose: Contract and legal (tax) obligations
    text: Contract and legal (tax) obligations
  residency:
  - region: European Union
    text: Documents and extracted data are stored exclusively in the European Union
  - region: Sentry EU (Frankfurt)
    text: Error monitoring uses Sentry's EU (Frankfurt) ingestion region.
  retention:
  - period: 90 days
    scope: Error data in Sentry
    text: Error data in Sentry is retained for 90 days.
  - period: while your account is active
    scope: Documents and extractions
    text: Documents and extractions are retained while your account is active so you can access your history.
  - period: immediately
    scope: Personal data on self-service deletion
    text: we delete personal data immediately on self-service deletion.
  - period: null
    scope: Billing records
    text: Billing records required for tax law may be retained without personal identifiers.
  rights:
  - right: access, correction, deletion, restriction, portability, objection
    text: Under the GDPR you can request access, correction, deletion, restriction, portability, and object to processing based on legitimate interest.
  - right: complaint to Dutch DPA
    text: You can also lodge a complaint with the Dutch DPA
  role:
    text: you are the controller and we act as your processor under article 28 GDPR
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data
  subprocessors:
    text: We engage the sub-processors below to run the Service.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bol.ai
provenance_date: '2026-11-09'
provider_name: Bol.ai
provider_slug: bol-ai
slug: bol-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bol-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bol.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bol.ai\naid: bol-ai\nurl: https://bol.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: you are the controller and we act as your processor under article 28 GDPR\ndata_categories:\n- category: identifying\n  text: Account data Email address, hashed password, API key hashes\n- category: other\n  text: Bills of Lading you upload, email in, or submit via API; the structured fields extracted from them; your\n    corrections\n- category: financial\n  text: Billing data Subscription status, purchases, usage counts.\n- category: device\n  text: IP address (rate limiting)\n- category: communication\n\
  \  text: Email address and message content for transactional email (password resets)\npurposes:\n- purpose: Providing the service\n  text: Providing the service (contract, art. 6(1)(b))\n- purpose: Security and service quality\n  text: Security and service quality (legitimate interest, art. 6(1)(f))\n- purpose: Contract and legal (tax) obligations\n  text: Contract and legal (tax) obligations\nretention:\n- scope: Error data in Sentry\n  period: 90 days\n  text: Error data in Sentry is retained for 90 days.\n- scope: Documents and extractions\n  period: while your account is active\n  text: Documents and extractions are retained while your account is active so you can access your history.\n- scope: Personal data on self-service deletion\n  period: immediately\n  text: we delete personal data immediately on self-service deletion.\n- scope: Billing records\n  period: null\n  text: Billing records required for tax law may be retained without personal identifiers.\nresidency:\n- region: European\
  \ Union\n  text: Documents and extracted data are stored exclusively in the European Union\n- region: Sentry EU (Frankfurt)\n  text: Error monitoring uses Sentry's EU (Frankfurt) ingestion region.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We engage the sub-processors below to run the Service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings in the app, or email support@bol.ai\n  text: You can delete your entire account from Account settings in the app (email confirmation and password required)\n    or by emailing support@bol.ai\nrights:\n- right: access, correction, deletion, restriction, portability, objection\n  text: Under the GDPR you can request access, correction, deletion, restriction, portability, and object to processing\n    based on legitimate interest.\n- right: complaint to Dutch DPA\n  text: You can also lodge a complaint with the Dutch DPA\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data\n"
source_yaml_url: https://artifacts.apis.io/bol-ai/privacy/bol-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Bol.ai's own page on 2026-11-09.
synthetic: false
tags:
- Freight Documents
- Data Extraction
- Bill of Lading
- 3PL
---
