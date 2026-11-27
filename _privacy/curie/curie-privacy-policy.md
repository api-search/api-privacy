---
api_specs:
- filename: curie-catalog-api-openapi.yml
  format: yaml
  label: Curie Catalog API
  slug: curie-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curie/openapi/curie-catalog-api-openapi.yml
- filename: curie-products-api-openapi.yml
  format: yaml
  label: Curie Products API
  slug: curie-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curie/openapi/curie-products-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Store owner email address
  - category: contact
    text: Store owner email address
  - category: financial
    text: Credit usage and billing information
  - category: behavioral
    text: Product search queries
  - category: communication
    text: Chat messages and queries (anonymized, not linked to individual customers)
  - category: device
    text: API request logs (anonymized)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: AI-powered shopping
    text: Power conversational product discovery, search, and recommendations
  - purpose: Generate 3D models
    text: Create interactive 3D models from your product images using AI processing
  - purpose: Sync product data
    text: Keep your product catalog up-to-date between Shopify and our platform
  - purpose: Manage billing
    text: Track credit usage and process subscription payments through Shopify Billing
  - purpose: Improve the service
    text: Analyze usage patterns to improve AI accuracy and feature development
  retention:
  - period: 30 days
    scope: Store data after uninstall
    text: All store data (products, conversations, billing records, 3D models, and configuration) is permanently deleted within 30 days of uninstall
  - period: 90 days
    scope: Conversation logs
    text: Anonymized conversation data may be retained for up to 90 days for service improvement
  - period: 7 years
    scope: Billing records
    text: Payment transaction records are retained for 7 years as required by applicable tax and accounting regulations.
  rights:
  - right: Access
    text: 'Access: Request a copy of the data we hold about your store.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your data (also triggered automatically by Shopify GDPR webhooks).'
  - right: Portability
    text: 'Portability: Request your data in a machine-readable format.'
  - right: Objection
    text: 'Objection: Object to certain processing activities.'
  role:
    text: Curie Vision, Inc. ("Curie," "we," "us," or "our") operates the Curie Shopping application
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Curie
provenance_date: '2026-11-09'
provider_name: Curie
provider_slug: curie
slug: curie-privacy-policy
source_date: '2026-11-09'
source_filename: curie-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chat.curie.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Curie\naid: curie\nurl: https://chat.curie.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Curie Vision, Inc. (\"Curie,\" \"we,\" \"us,\" or \"our\") operates the Curie Shopping application\ndata_categories:\n- category: identifying\n  text: Store owner email address\n- category: contact\n  text: Store owner email address\n- category: financial\n  text: Credit usage and billing information\n- category: behavioral\n  text: Product search queries\n- category: communication\n  text: Chat messages and queries (anonymized, not linked to individual customers)\n- category: device\n  text:\
  \ API request logs (anonymized)\npurposes:\n- purpose: AI-powered shopping\n  text: Power conversational product discovery, search, and recommendations\n- purpose: Generate 3D models\n  text: Create interactive 3D models from your product images using AI processing\n- purpose: Sync product data\n  text: Keep your product catalog up-to-date between Shopify and our platform\n- purpose: Manage billing\n  text: Track credit usage and process subscription payments through Shopify Billing\n- purpose: Improve the service\n  text: Analyze usage patterns to improve AI accuracy and feature development\nretention:\n- scope: Store data after uninstall\n  period: 30 days\n  text: All store data (products, conversations, billing records, 3D models, and configuration) is permanently deleted\n    within 30 days of uninstall\n- scope: Conversation logs\n  period: 90 days\n  text: Anonymized conversation data may be retained for up to 90 days for service improvement\n- scope: Billing records\n  period:\
  \ 7 years\n  text: Payment transaction records are retained for 7 years as required by applicable tax and accounting regulations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: 'Access: Request a copy of the data we hold about your store.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your data (also triggered automatically by Shopify GDPR webhooks).'\n- right: Portability\n  text: 'Portability: Request your data in a machine-readable format.'\n- right: Objection\n  text: 'Objection: Object to certain processing activities.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/curie/privacy/curie-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Curie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Shopify
- Artificial Intelligence
- MCP
- Agentic Commerce
- Product Discovery
- 3D
---
