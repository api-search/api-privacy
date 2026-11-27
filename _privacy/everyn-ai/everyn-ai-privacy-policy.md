---
api_specs:
- filename: everyn-ai-alert-rules-api-openapi.yml
  format: yaml
  label: Everyn Alert Rules API
  slug: everyn-ai-alert-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-alert-rules-api-openapi.yml
- filename: everyn-ai-billing-api-openapi.yml
  format: yaml
  label: Everyn Billing API
  slug: everyn-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-billing-api-openapi.yml
- filename: everyn-ai-callable-jobs-api-openapi.yml
  format: yaml
  label: Everyn Callable Jobs API
  slug: everyn-ai-callable-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-callable-jobs-api-openapi.yml
- filename: everyn-ai-dataset-uploads-api-openapi.yml
  format: yaml
  label: Everyn Dataset Uploads API
  slug: everyn-ai-dataset-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-dataset-uploads-api-openapi.yml
- filename: everyn-ai-datasets-api-openapi.yml
  format: yaml
  label: Everyn Datasets API
  slug: everyn-ai-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-datasets-api-openapi.yml
- filename: everyn-ai-exports-api-openapi.yml
  format: yaml
  label: Everyn Exports API
  slug: everyn-ai-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-exports-api-openapi.yml
- filename: everyn-ai-health-api-openapi.yml
  format: yaml
  label: Everyn Health API
  slug: everyn-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-health-api-openapi.yml
- filename: everyn-ai-job-specs-api-openapi.yml
  format: yaml
  label: Everyn Job Specs API
  slug: everyn-ai-job-specs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-job-specs-api-openapi.yml
- filename: everyn-ai-models-api-openapi.yml
  format: yaml
  label: Everyn Models API
  slug: everyn-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-models-api-openapi.yml
- filename: everyn-ai-organization-admin-api-openapi.yml
  format: yaml
  label: Everyn Organization Admin API
  slug: everyn-ai-organization-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-organization-admin-api-openapi.yml
- filename: everyn-ai-runs-api-openapi.yml
  format: yaml
  label: Everyn Runs API
  slug: everyn-ai-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-runs-api-openapi.yml
- filename: everyn-ai-usage-api-openapi.yml
  format: yaml
  label: Everyn Usage API
  slug: everyn-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-usage-api-openapi.yml
- filename: everyn-ai-webhooks-api-openapi.yml
  format: yaml
  label: Everyn Webhooks API
  slug: everyn-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everyn-ai/openapi/everyn-ai-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, work email address, display name, organization, role, authentication identifiers, account settings, and communications with Everyn.
  - category: financial
    text: Plan, subscription, usage, invoice, payment-status, tax, and transaction information.
  - category: other
    text: Data, files, instructions, prompts, configurations, model selections, generated results, review information, and exports submitted to or produced through the Services.
  - category: device
    text: Internet protocol address, browser and device type, operating system, session and authentication events, pages or route templates viewed, feature interactions, timestamps, performance measurements, error information, and security logs.
  deletion:
    route: email legal@everyn.ai
    text: Email legal@everyn.ai (or legal@geteveryn.com ) and describe your request and relationship with Everyn.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate Services
    text: provide, operate, support, and secure the Services and requested workflows
  - purpose: account creation and authentication
    text: create and authenticate accounts and manage organization access
  - purpose: billing and payments
    text: process subscriptions, usage, payments, invoices, taxes, and credits
  - purpose: product improvement
    text: understand product use and improve the Services using usage information that does not include Customer Input or Output
  - purpose: fraud and abuse prevention
    text: detect and prevent fraud, abuse, unauthorized access, and violations of our agreements
  retention:
  - period: null
    scope: personal information
    text: We retain personal information only for as long as reasonably necessary to provide the Services, meet the purposes described in this policy, secure our systems, resolve disputes, enforce agreements, and comply with legal, tax, accounting, and reporting obligations.
  rights:
  - right: access, correction, deletion, copy
    text: Depending on applicable law, you may ask to access, correct, delete, or obtain a copy of certain personal information.
  - right: marketing opt-out
    text: You may unsubscribe from marketing email using the link in the message
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Everyn does not sell personal information or use or share it for cross-context behavioral advertising or targeted advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Everyn
provenance_date: '2026-11-09'
provider_name: Everyn
provider_slug: everyn-ai
slug: everyn-ai-privacy-policy
source_date: '2026-11-09'
source_filename: everyn-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.everyn.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Everyn\naid: everyn-ai\nurl: https://www.everyn.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, work email address, display name, organization, role, authentication identifiers, account settings,\n    and communications with Everyn.\n- category: financial\n  text: Plan, subscription, usage, invoice, payment-status, tax, and transaction information.\n- category: other\n  text: Data, files, instructions, prompts, configurations, model selections, generated results, review information,\n    and exports submitted to or produced\
  \ through the Services.\n- category: device\n  text: Internet protocol address, browser and device type, operating system, session and authentication events,\n    pages or route templates viewed, feature interactions, timestamps, performance measurements, error information,\n    and security logs.\npurposes:\n- purpose: provide and operate Services\n  text: provide, operate, support, and secure the Services and requested workflows\n- purpose: account creation and authentication\n  text: create and authenticate accounts and manage organization access\n- purpose: billing and payments\n  text: process subscriptions, usage, payments, invoices, taxes, and credits\n- purpose: product improvement\n  text: understand product use and improve the Services using usage information that does not include Customer Input\n    or Output\n- purpose: fraud and abuse prevention\n  text: detect and prevent fraud, abuse, unauthorized access, and violations of our agreements\nretention:\n- scope: personal information\n\
  \  period: null\n  text: We retain personal information only for as long as reasonably necessary to provide the Services, meet the\n    purposes described in this policy, secure our systems, resolve disputes, enforce agreements, and comply with\n    legal, tax, accounting, and reporting obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email legal@everyn.ai\n  text: Email legal@everyn.ai (or legal@geteveryn.com ) and describe your request and relationship with Everyn.\nrights:\n- right: access, correction, deletion, copy\n  text: Depending on applicable law, you may ask to access, correct, delete, or obtain a copy of certain personal\n    information.\n- right: marketing opt-out\n  text: You may unsubscribe from marketing email using the link in the message\nsale_or_sharing:\n  stance: prohibited\n  text: Everyn does not sell personal information or use or share it for cross-context\
  \ behavioral advertising or\n    targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/everyn-ai/privacy/everyn-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Everyn's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Productivity
- Agents
- Platform
---
