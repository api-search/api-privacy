---
api_specs:
- filename: imejis-io-analytics-api-openapi.yml
  format: yaml
  label: imejis-io Analytics API
  slug: imejis-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-analytics-api-openapi.yml
- filename: imejis-io-designs-api-openapi.yml
  format: yaml
  label: imejis-io Designs API
  slug: imejis-io-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-designs-api-openapi.yml
- filename: imejis-io-keys-api-openapi.yml
  format: yaml
  label: imejis-io Keys API
  slug: imejis-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-keys-api-openapi.yml
- filename: imejis-io-render-api-openapi.yml
  format: yaml
  label: imejis-io Render API
  slug: imejis-io-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-render-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and authentication identifiers when you sign up or sign in (including via Google or another OAuth provider).
  - category: financial
    text: Plan, subscription status, and transaction records.
  - category: behavioral
    text: IP address, browser and device type, pages viewed, and interactions, collected through cookies and analytics tools
  - category: communication
    text: Messages you send to support and your preferences.
  - category: other
    text: Designs, templates, uploaded images and fonts, text, data you render into images, and any values you send to the API or MCP server.
  deletion:
    route: Email support@imejis.io
    text: If you believe a child has provided us data, contact support@imejis.io and we will delete it.
  dpa:
    available: true
    text: our Data Processing Addendum governs
    url: https://www.imejis.io/dpa
  purposes:
  - purpose: Provide, operate, secure, and improve the Service
    text: Provide, operate, secure, and improve the Service;
  - purpose: Process payments and manage subscriptions
    text: Process payments and manage subscriptions;
  - purpose: Enforce quotas, prevent fraud and abuse
    text: Enforce quotas, prevent fraud and abuse, and maintain security;
  - purpose: Marketing communications
    text: send service and, where permitted, marketing communications (you can opt out at any time)
  residency:
  - region: United States
    text: We are based in the United States and our providers may process data in the United States and other countries.
  retention:
  - period: 90 days
    scope: Account data after account closure
    text: After account closure we delete or anonymize personal data within 90 days, except where we must retain records to comply with legal, tax, accounting, or security obligations.
  rights:
  - right: access, correct, delete, port, restrict, object, withdraw consent
    text: you may have the right to access, correct, delete, port, or restrict processing of your personal data, to object to processing, and to withdraw consent.
  - right: opt out of sales or sharing (CCPA/CPRA)
    text: to opt out of "sales" or "sharing" (we do not sell your data)
  - right: lodge complaint with supervisory authority
    text: EEA/UK users may also lodge a complaint with their local supervisory authority.
  role:
    text: For account and marketing data, JAGODANA LLC is the controller. When we process content and end-user data on behalf of a customer's account (for example, the data you render into images through the API), we act as a processor and the customer is the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'See the current list: Sub-processors .'
    url: https://www.imejis.io/sub-processors
  transfers:
  - mechanism: SCC
    text: Where we transfer personal data from the EEA, UK, or Switzerland, we rely on appropriate safeguards such as the Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: imejis-io
provenance_date: '2026-11-09'
provider_name: imejis-io
provider_slug: imejis-io
slug: imejis-io-privacy-policy
source_date: '2026-11-09'
source_filename: imejis-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.imejis.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: imejis-io\naid: imejis-io\nurl: https://www.imejis.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account and marketing data, JAGODANA LLC is the controller. When we process content and end-user data\n    on behalf of a customer's account (for example, the data you render into images through the API), we act as\n    a processor and the customer is the controller.\ndata_categories:\n- category: identifying\n  text: Name, email address, and authentication identifiers when you sign up or sign in (including via Google or\n    another OAuth provider).\n- category: financial\n  text:\
  \ Plan, subscription status, and transaction records.\n- category: behavioral\n  text: IP address, browser and device type, pages viewed, and interactions, collected through cookies and analytics\n    tools\n- category: communication\n  text: Messages you send to support and your preferences.\n- category: other\n  text: Designs, templates, uploaded images and fonts, text, data you render into images, and any values you send\n    to the API or MCP server.\npurposes:\n- purpose: Provide, operate, secure, and improve the Service\n  text: Provide, operate, secure, and improve the Service;\n- purpose: Process payments and manage subscriptions\n  text: Process payments and manage subscriptions;\n- purpose: Enforce quotas, prevent fraud and abuse\n  text: Enforce quotas, prevent fraud and abuse, and maintain security;\n- purpose: Marketing communications\n  text: send service and, where permitted, marketing communications (you can opt out at any time)\nretention:\n- scope: Account data after\
  \ account closure\n  period: 90 days\n  text: After account closure we delete or anonymize personal data within 90 days, except where we must retain records\n    to comply with legal, tax, accounting, or security obligations.\nresidency:\n- region: United States\n  text: We are based in the United States and our providers may process data in the United States and other countries.\ntransfers:\n- mechanism: SCC\n  text: Where we transfer personal data from the EEA, UK, or Switzerland, we rely on appropriate safeguards such\n    as the Standard Contractual Clauses.\nsubprocessors:\n  url: https://www.imejis.io/sub-processors\n  text: 'See the current list: Sub-processors .'\ndpa:\n  available: true\n  url: https://www.imejis.io/dpa\n  text: our Data Processing Addendum governs\ndeletion:\n  route: Email support@imejis.io\n  text: If you believe a child has provided us data, contact support@imejis.io and we will delete it.\nrights:\n- right: access, correct, delete, port, restrict, object,\
  \ withdraw consent\n  text: you may have the right to access, correct, delete, port, or restrict processing of your personal data, to\n    object to processing, and to withdraw consent.\n- right: opt out of sales or sharing (CCPA/CPRA)\n  text: to opt out of \"sales\" or \"sharing\" (we do not sell your data)\n- right: lodge complaint with supervisory authority\n  text: EEA/UK users may also lodge a complaint with their local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/imejis-io/privacy/imejis-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from imejis-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
