---
api_specs:
- filename: docuqueue-com-batch-api-openapi.yml
  format: yaml
  label: docuqueue-com Batch API
  slug: docuqueue-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-batch-api-openapi.yml
- filename: docuqueue-com-conversion-api-openapi.yml
  format: yaml
  label: docuqueue-com Conversion API
  slug: docuqueue-com-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-conversion-api-openapi.yml
- filename: docuqueue-com-document-generation-api-openapi.yml
  format: yaml
  label: docuqueue-com Document Generation API
  slug: docuqueue-com-document-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-document-generation-api-openapi.yml
- filename: docuqueue-com-forms-api-openapi.yml
  format: yaml
  label: docuqueue-com Forms API
  slug: docuqueue-com-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-forms-api-openapi.yml
- filename: docuqueue-com-research-api-openapi.yml
  format: yaml
  label: docuqueue-com Research API
  slug: docuqueue-com-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-research-api-openapi.yml
- filename: docuqueue-com-shared-documents-api-openapi.yml
  format: yaml
  label: docuqueue-com Shared Documents API
  slug: docuqueue-com-shared-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-shared-documents-api-openapi.yml
- filename: docuqueue-com-sharing-api-openapi.yml
  format: yaml
  label: docuqueue-com Sharing API
  slug: docuqueue-com-sharing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-sharing-api-openapi.yml
- filename: docuqueue-com-system-api-openapi.yml
  format: yaml
  label: docuqueue-com System API
  slug: docuqueue-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-system-api-openapi.yml
- filename: docuqueue-com-templates-api-openapi.yml
  format: yaml
  label: docuqueue-com Templates API
  slug: docuqueue-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-templates-api-openapi.yml
- filename: docuqueue-com-upload-api-openapi.yml
  format: yaml
  label: docuqueue-com Upload API
  slug: docuqueue-com-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docuqueue-com/openapi/docuqueue-com-upload-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (required for account creation)
  - category: financial
    text: We do not store credit card numbers, UPI IDs, or bank details on our servers
  - category: behavioral
    text: API request logs (endpoints called, timestamps, response codes)
  - category: device
    text: IP address (logged for rate limiting and abuse prevention)
  - category: device
    text: User-Agent header (logged for API abuse detection)
  - category: communication
    text: 'Session data: A session identifier to correlate requests from the same AI client session.'
  deletion:
    route: Delete your account via account settings or email arun@docuqueue.com
    text: Delete your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To process your conversion requests and serve PDFs
  - purpose: Authentication
    text: To verify your identity and API key
  - purpose: Billing
    text: To manage subscriptions and process payments
  - purpose: Rate limiting
    text: To enforce plan-based rate limits and credit allocations
  - purpose: Abuse prevention
    text: To detect and prevent unauthorized use
  - purpose: Communication
    text: To send service updates, billing notifications, and support responses
  residency:
  - region: India
    text: DocuQueue is based in India and primarily serves Indian users
  - region: Outside India
    text: We do not transfer data outside India except as required for infrastructure (hosting)
  retention:
  - period: Until account deletion
    scope: Account details
    text: Account details Until account deletion
  - period: 30 days
    scope: API request logs
    text: API request logs 30 days
  - period: 1 hour (Redis cache), then deleted
    scope: Generated PDFs
    text: Generated PDFs 1 hour (Redis cache), then deleted
  - period: 7 years (Indian tax law requirement)
    scope: Billing records
    text: Billing records 7 years (Indian tax law requirement)
  - period: 30 days
    scope: IP logs
    text: IP logs 30 days
  - period: 30 minutes (then expired)
    scope: OAuth access tokens
    text: OAuth access tokens 30 minutes (then expired)
  - period: 7 days or until disconnection
    scope: OAuth refresh tokens
    text: OAuth refresh tokens 7 days or until disconnection
  - period: 30 days
    scope: MCP tool call logs
    text: MCP tool call logs 30 days
  rights:
  - right: Access
    text: Access your personal data we hold
  - right: Correction
    text: Correct inaccurate data in your account
  - right: Deletion
    text: Delete your account and associated data
  - right: Export
    text: Export your usage data in a portable format
  - right: Revoke AI client access
    text: Revoke AI client access at any time via your account settings
  - right: Opt out of non-essential communications
    text: Opt out of non-essential communications
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: docuqueue-com
provenance_date: '2026-11-09'
provider_name: docuqueue-com
provider_slug: docuqueue-com
slug: docuqueue-com-privacy-policy
source_date: '2026-11-09'
source_filename: docuqueue-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docuqueue.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: docuqueue-com\naid: docuqueue-com\nurl: https://docuqueue.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (required for account creation)\n- category: financial\n  text: We do not store credit card numbers, UPI IDs, or bank details on our servers\n- category: behavioral\n  text: API request logs (endpoints called, timestamps, response codes)\n- category: device\n  text: IP address (logged for rate limiting and abuse prevention)\n- category: device\n  text: User-Agent header (logged for API abuse detection)\n- category:\
  \ communication\n  text: 'Session data: A session identifier to correlate requests from the same AI client session.'\npurposes:\n- purpose: Service delivery\n  text: To process your conversion requests and serve PDFs\n- purpose: Authentication\n  text: To verify your identity and API key\n- purpose: Billing\n  text: To manage subscriptions and process payments\n- purpose: Rate limiting\n  text: To enforce plan-based rate limits and credit allocations\n- purpose: Abuse prevention\n  text: To detect and prevent unauthorized use\n- purpose: Communication\n  text: To send service updates, billing notifications, and support responses\nretention:\n- scope: Account details\n  period: Until account deletion\n  text: Account details Until account deletion\n- scope: API request logs\n  period: 30 days\n  text: API request logs 30 days\n- scope: Generated PDFs\n  period: 1 hour (Redis cache), then deleted\n  text: Generated PDFs 1 hour (Redis cache), then deleted\n- scope: Billing records\n  period:\
  \ 7 years (Indian tax law requirement)\n  text: Billing records 7 years (Indian tax law requirement)\n- scope: IP logs\n  period: 30 days\n  text: IP logs 30 days\n- scope: OAuth access tokens\n  period: 30 minutes (then expired)\n  text: OAuth access tokens 30 minutes (then expired)\n- scope: OAuth refresh tokens\n  period: 7 days or until disconnection\n  text: OAuth refresh tokens 7 days or until disconnection\n- scope: MCP tool call logs\n  period: 30 days\n  text: MCP tool call logs 30 days\nresidency:\n- region: India\n  text: DocuQueue is based in India and primarily serves Indian users\n- region: Outside India\n  text: We do not transfer data outside India except as required for infrastructure (hosting)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account via account settings or email arun@docuqueue.com\n  text: Delete your account and associated data\nrights:\n- right: Access\n  text:\
  \ Access your personal data we hold\n- right: Correction\n  text: Correct inaccurate data in your account\n- right: Deletion\n  text: Delete your account and associated data\n- right: Export\n  text: Export your usage data in a portable format\n- right: Revoke AI client access\n  text: Revoke AI client access at any time via your account settings\n- right: Opt out of non-essential communications\n  text: Opt out of non-essential communications\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal information.\n"
source_yaml_url: https://artifacts.apis.io/docuqueue-com/privacy/docuqueue-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from docuqueue-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Automation
- PDF
- REST API
- MCP
---
