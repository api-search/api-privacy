---
api_specs:
- filename: arkrel-com-account-data-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Account Data API
  slug: arkrel-com-account-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-account-data-api-openapi.yml
- filename: arkrel-com-auth-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Auth API
  slug: arkrel-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-auth-api-openapi.yml
- filename: arkrel-com-billing-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Billing API
  slug: arkrel-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-billing-api-openapi.yml
- filename: arkrel-com-businesses-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Businesses API
  slug: arkrel-com-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-businesses-api-openapi.yml
- filename: arkrel-com-category-rules-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Category Rules API
  slug: arkrel-com-category-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-category-rules-api-openapi.yml
- filename: arkrel-com-chart-of-accounts-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Chart Of Accounts API
  slug: arkrel-com-chart-of-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-chart-of-accounts-api-openapi.yml
- filename: arkrel-com-connections-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Connections API
  slug: arkrel-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-connections-api-openapi.yml
- filename: arkrel-com-documents-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Documents API
  slug: arkrel-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-documents-api-openapi.yml
- filename: arkrel-com-mcp-api-openapi.yml
  format: yaml
  label: Conecta Media LLC MCP API
  slug: arkrel-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-mcp-api-openapi.yml
- filename: arkrel-com-ops-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Ops API
  slug: arkrel-com-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-ops-api-openapi.yml
- filename: arkrel-com-schemas-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Schemas API
  slug: arkrel-com-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-schemas-api-openapi.yml
- filename: arkrel-com-settings-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Settings API
  slug: arkrel-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-settings-api-openapi.yml
- filename: arkrel-com-statement-sets-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Statement Sets API
  slug: arkrel-com-statement-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-statement-sets-api-openapi.yml
- filename: arkrel-com-tax-report-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Tax Report API
  slug: arkrel-com-tax-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-tax-report-api-openapi.yml
- filename: arkrel-com-tax-years-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Tax Years API
  slug: arkrel-com-tax-years-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-tax-years-api-openapi.yml
- filename: arkrel-com-usage-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Usage API
  slug: arkrel-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-usage-api-openapi.yml
- filename: arkrel-com-webhooks-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Webhooks API
  slug: arkrel-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-webhooks-api-openapi.yml
- filename: arkrel-com-year-overview-api-openapi.yml
  format: yaml
  label: Conecta Media LLC Year Overview API
  slug: arkrel-com-year-overview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkrel-com/openapi/arkrel-com-year-overview-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information. When you sign up, we collect your email address, organization name, and the way you chose to sign in
  - category: financial
    text: Payment details (card numbers, etc.) are collected and stored by Stripe, our payment processor; we do not store full card numbers ourselves.
  - category: financial
    text: We store an encrypted access token, account names and masks, transaction dates, descriptions and amounts, and statement identifiers and dates.
  - category: device
    text: Standard web server logs (IP address, browser type, pages visited) for the marketing site and dashboard, used for security and troubleshooting.
  - category: behavioral
    text: We record how many pages you process, which endpoints you call, and timestamps
  deletion:
    route: Account deletion from Settings in the dashboard, or email support@arkrel.com
    text: You can delete your account yourself, at any time, from Settings in the dashboard, with no need to contact us.
  dpa:
    available: true
    text: see our Data Processing Addendum for how we handle personal data you submit to us as a processor
    url: https://arkrel.com/legal/dpa
  purposes:
  - purpose: provide and operate the Service
    text: provide and operate the Service;
  - purpose: verify and process documents
    text: verify and process the documents you send us;
  - purpose: enforce plan quotas and bill for usage
    text: enforce plan quotas and bill for usage;
  - purpose: detect and prevent abuse
    text: detect and prevent abuse of the Service.
  residency:
  - region: unstated
    text: Data is stored using Cloudflare's global infrastructure (D1 for structured data, R2 for file storage)
  retention:
  - period: 30 days
    scope: uploaded documents and extraction results
    text: Documents and results are deleted automatically 30 days after processing by default.
  - period: 30 days
    scope: deleted data in backups
    text: Deleted data is removed from our live system as cleanup completes, and from every backup copy within 30 days.
  - period: 30 days
    scope: first-visit cookie
    text: We also save first-visit source information in the first-party `arkrel_first_touch` cookie for up to 30 days
  rights:
  - right: access, correct, export, or delete
    text: Depending on where you live, you may have rights to access, correct, export, or delete your personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal information or your documents, to anyone, for any reason.
  subprocessors:
    text: We share information with the subprocessors listed on our Subprocessors page
    url: https://arkrel.com/legal/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Conecta Media LLC
provenance_date: '2026-11-09'
provider_name: Conecta Media LLC
provider_slug: arkrel-com
slug: arkrel-com-privacy-policy
source_date: '2026-11-09'
source_filename: arkrel-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://arkrel.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Conecta Media LLC\naid: arkrel-com\nurl: https://arkrel.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information. When you sign up, we collect your email address, organization name, and the way you\n    chose to sign in\n- category: financial\n  text: Payment details (card numbers, etc.) are collected and stored by Stripe, our payment processor; we do not\n    store full card numbers ourselves.\n- category: financial\n  text: We store an encrypted access token, account names and masks, transaction dates, descriptions\
  \ and amounts,\n    and statement identifiers and dates.\n- category: device\n  text: Standard web server logs (IP address, browser type, pages visited) for the marketing site and dashboard,\n    used for security and troubleshooting.\n- category: behavioral\n  text: We record how many pages you process, which endpoints you call, and timestamps\npurposes:\n- purpose: provide and operate the Service\n  text: provide and operate the Service;\n- purpose: verify and process documents\n  text: verify and process the documents you send us;\n- purpose: enforce plan quotas and bill for usage\n  text: enforce plan quotas and bill for usage;\n- purpose: detect and prevent abuse\n  text: detect and prevent abuse of the Service.\nretention:\n- scope: uploaded documents and extraction results\n  period: 30 days\n  text: Documents and results are deleted automatically 30 days after processing by default.\n- scope: deleted data in backups\n  period: 30 days\n  text: Deleted data is removed from our live\
  \ system as cleanup completes, and from every backup copy within 30\n    days.\n- scope: first-visit cookie\n  period: 30 days\n  text: We also save first-visit source information in the first-party `arkrel_first_touch` cookie for up to 30\n    days\nresidency:\n- region: unstated\n  text: Data is stored using Cloudflare's global infrastructure (D1 for structured data, R2 for file storage)\ntransfers: []\nsubprocessors:\n  url: https://arkrel.com/legal/subprocessors\n  text: We share information with the subprocessors listed on our Subprocessors page\ndpa:\n  available: true\n  url: https://arkrel.com/legal/dpa\n  text: see our Data Processing Addendum for how we handle personal data you submit to us as a processor\ndeletion:\n  route: Account deletion from Settings in the dashboard, or email support@arkrel.com\n  text: You can delete your account yourself, at any time, from Settings in the dashboard, with no need to contact\n    us.\nrights:\n- right: access, correct, export, or delete\n\
  \  text: Depending on where you live, you may have rights to access, correct, export, or delete your personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal information or your documents, to anyone, for any reason.\n"
source_yaml_url: https://artifacts.apis.io/arkrel-com/privacy/arkrel-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Conecta Media LLC's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Bookkeeping
- Tax
- Software-as-a-Service
- Self-Employed
---
