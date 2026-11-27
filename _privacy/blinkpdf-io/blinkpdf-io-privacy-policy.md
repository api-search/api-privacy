---
api_specs:
- filename: blinkpdf-io-account-api-openapi.yml
  format: yaml
  label: blinkpdf-io Account API
  slug: blinkpdf-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-account-api-openapi.yml
- filename: blinkpdf-io-compose-api-openapi.yml
  format: yaml
  label: blinkpdf-io Compose API
  slug: blinkpdf-io-compose-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-compose-api-openapi.yml
- filename: blinkpdf-io-discovery-api-openapi.yml
  format: yaml
  label: blinkpdf-io Discovery API
  slug: blinkpdf-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-discovery-api-openapi.yml
- filename: blinkpdf-io-docs-api-openapi.yml
  format: yaml
  label: blinkpdf-io Docs API
  slug: blinkpdf-io-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-docs-api-openapi.yml
- filename: blinkpdf-io-fill-api-openapi.yml
  format: yaml
  label: blinkpdf-io Fill API
  slug: blinkpdf-io-fill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-fill-api-openapi.yml
- filename: blinkpdf-io-fonts-api-openapi.yml
  format: yaml
  label: blinkpdf-io Fonts API
  slug: blinkpdf-io-fonts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-fonts-api-openapi.yml
- filename: blinkpdf-io-health-api-openapi.yml
  format: yaml
  label: blinkpdf-io Health API
  slug: blinkpdf-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-health-api-openapi.yml
- filename: blinkpdf-io-layoutdocument-api-openapi.yml
  format: yaml
  label: blinkpdf-io Layout Document API
  slug: blinkpdf-io-layoutdocument-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-layoutdocument-api-openapi.yml
- filename: blinkpdf-io-pages-api-openapi.yml
  format: yaml
  label: blinkpdf-io Pages API
  slug: blinkpdf-io-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-pages-api-openapi.yml
- filename: blinkpdf-io-read-api-openapi.yml
  format: yaml
  label: blinkpdf-io Read API
  slug: blinkpdf-io-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-read-api-openapi.yml
- filename: blinkpdf-io-render-api-openapi.yml
  format: yaml
  label: blinkpdf-io Render API
  slug: blinkpdf-io-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-render-api-openapi.yml
- filename: blinkpdf-io-sandwichdocument-api-openapi.yml
  format: yaml
  label: blinkpdf-io Sandwich Document API
  slug: blinkpdf-io-sandwichdocument-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-sandwichdocument-api-openapi.yml
- filename: blinkpdf-io-stamp-api-openapi.yml
  format: yaml
  label: blinkpdf-io Stamp API
  slug: blinkpdf-io-stamp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-stamp-api-openapi.yml
- filename: blinkpdf-io-templates-api-openapi.yml
  format: yaml
  label: blinkpdf-io Templates API
  slug: blinkpdf-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkpdf-io/openapi/blinkpdf-io-templates-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name — your first name, last name, and a display name associated with your account.
  - category: contact
    text: Email address — to identify your account, send transactional emails (email verification, password reset), and contact you about the Service.
  - category: device
    text: the IP address and browser user-agent string associated with the session
  - category: financial
    text: Subscription metadata — subscription ID, status, the price/plan you are on, the current period end date
  - category: behavioral
    text: 'Usage events (an append-only ledger): your user ID, the API key ID, the metric ( pdf_render ), the quantity of render units (1–16)'
  deletion:
    route: Manual deletion on request by email to the privacy contact
    text: There is no self-service data-export or account-deletion feature in the Service. To request access to or deletion of your data, contact me at [email protected] . Deletion is performed manually
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Create and manage account
    text: Create and manage your account.
  - purpose: Process payments and meter usage
    text: Process payments and meter usage for billing.
  - purpose: Transactional emails
    text: Send transactional emails (email verification, password reset).
  - purpose: Operate, secure, and debug
    text: Operate, secure, and debug the Service, including abuse prevention and rate limiting.
  residency:
  - region: United States (Virginia)
    text: The Service is hosted in the United States (Virginia).
  retention:
  - period: Until your account is deleted
    scope: Account data
    text: Account data (name, email, hashed password) Until your account is deleted (see Section 8)
  - period: 24 hours
    scope: MCP-hosted PDFs
    text: These files are stored for 24 hours , after which they are automatically removed.
  - period: Not stored
    scope: Direct API render content
    text: Direct API render content Not stored (held only briefly in memory; see Section 3)
  - period: null
    scope: Usage and audit records
    text: The Service does not currently apply an automatic purge to usage, aggregate, or audit records; they are retained for as long as needed for billing and audit.
  rights:
  - right: Access, correction, deletion, objection, restriction
    text: Depending on your location, you may have rights to access, correct, or delete your personal data, and to object to or restrict certain processing.
  - right: GDPR and UK GDPR
    text: EEA/UK residents may have rights under the GDPR and UK GDPR.
  - right: CCPA
    text: California residents may have rights under the CCPA.
  role:
    text: Blink PDF is operated by Diego Cesar Lerma Torres , an individual (“I”, “me”, or “my”).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: I do not sell or share personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you are located outside the United States, your data is transferred to and processed there, as well as by the sub-processors listed in Section 5.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: blinkpdf-io
provenance_date: '2026-11-09'
provider_name: blinkpdf-io
provider_slug: blinkpdf-io
slug: blinkpdf-io-privacy-policy
source_date: '2026-11-09'
source_filename: blinkpdf-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blinkpdf.io/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: blinkpdf-io\naid: blinkpdf-io\nurl: https://blinkpdf.io/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Blink PDF is operated by Diego Cesar Lerma Torres , an individual (“I”, “me”, or “my”).\ndata_categories:\n- category: identifying\n  text: Name — your first name, last name, and a display name associated with your account.\n- category: contact\n  text: Email address — to identify your account, send transactional emails (email verification, password reset),\n    and contact you about the Service.\n- category: device\n  text: the IP address and browser user-agent string associated\
  \ with the session\n- category: financial\n  text: Subscription metadata — subscription ID, status, the price/plan you are on, the current period end date\n- category: behavioral\n  text: 'Usage events (an append-only ledger): your user ID, the API key ID, the metric ( pdf_render ), the quantity\n    of render units (1–16)'\npurposes:\n- purpose: Create and manage account\n  text: Create and manage your account.\n- purpose: Process payments and meter usage\n  text: Process payments and meter usage for billing.\n- purpose: Transactional emails\n  text: Send transactional emails (email verification, password reset).\n- purpose: Operate, secure, and debug\n  text: Operate, secure, and debug the Service, including abuse prevention and rate limiting.\nretention:\n- scope: Account data\n  period: Until your account is deleted\n  text: Account data (name, email, hashed password) Until your account is deleted (see Section 8)\n- scope: MCP-hosted PDFs\n  period: 24 hours\n  text: These files are\
  \ stored for 24 hours , after which they are automatically removed.\n- scope: Direct API render content\n  period: Not stored\n  text: Direct API render content Not stored (held only briefly in memory; see Section 3)\n- scope: Usage and audit records\n  period: null\n  text: The Service does not currently apply an automatic purge to usage, aggregate, or audit records; they are\n    retained for as long as needed for billing and audit.\nresidency:\n- region: United States (Virginia)\n  text: The Service is hosted in the United States (Virginia).\ntransfers:\n- mechanism: other\n  text: If you are located outside the United States, your data is transferred to and processed there, as well as\n    by the sub-processors listed in Section 5.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Manual deletion on request by email to the privacy contact\n  text: There is no self-service data-export or account-deletion feature in the\
  \ Service. To request access to or\n    deletion of your data, contact me at [email protected] . Deletion is performed manually\nrights:\n- right: Access, correction, deletion, objection, restriction\n  text: Depending on your location, you may have rights to access, correct, or delete your personal data, and to\n    object to or restrict certain processing.\n- right: GDPR and UK GDPR\n  text: EEA/UK residents may have rights under the GDPR and UK GDPR.\n- right: CCPA\n  text: California residents may have rights under the CCPA.\nsale_or_sharing:\n  stance: prohibited\n  text: I do not sell or share personal data.\n"
source_yaml_url: https://artifacts.apis.io/blinkpdf-io/privacy/blinkpdf-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from blinkpdf-io's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Document Processing
- Software-as-a-Service
- Automation
---
