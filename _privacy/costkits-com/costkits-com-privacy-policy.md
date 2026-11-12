---
api_specs:
- filename: costkits-com-bill-analysis-api-openapi.yml
  format: yaml
  label: CostKits Bill Analysis API
  slug: costkits-com-bill-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-bill-analysis-api-openapi.yml
- filename: costkits-com-cost-estimation-api-openapi.yml
  format: yaml
  label: CostKits Cost Estimation API
  slug: costkits-com-cost-estimation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-cost-estimation-api-openapi.yml
- filename: costkits-com-coverage-rules-api-openapi.yml
  format: yaml
  label: CostKits Coverage Rules API
  slug: costkits-com-coverage-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-coverage-rules-api-openapi.yml
- filename: costkits-com-demo-api-openapi.yml
  format: yaml
  label: CostKits Demo API
  slug: costkits-com-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-demo-api-openapi.yml
- filename: costkits-com-procedure-ontology-api-openapi.yml
  format: yaml
  label: CostKits Procedure Ontology API
  slug: costkits-com-procedure-ontology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-procedure-ontology-api-openapi.yml
- filename: costkits-com-provider-graph-api-openapi.yml
  format: yaml
  label: CostKits Provider Graph API
  slug: costkits-com-provider-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/costkits-com/openapi/costkits-com-provider-graph-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and contact information (email address, phone number)
  - category: financial
    text: Payment and billing information
  - category: health
    text: Medical bill information you choose to upload or analyze
  - category: communication
    text: Communications with our support team
  - category: behavioral
    text: Email engagement, such as whether you open an email from us and which links you click
  - category: device
    text: the type of client making the request and, where applicable, the procedure and state
  deletion:
    route: Access, update, or delete your personal information
    text: Access, update, or delete your personal information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide, maintain, and improve our medical bill analysis services
  - purpose: Transactions
    text: Process transactions and send related information
  - purpose: De-identified data for product and marketing
    text: Create de-identified data from the medical bills you submit
  - purpose: Service provider functions
    text: We may share information with third-party service providers who perform services on our behalf, such as payment processing, data analysis, and customer service.
  retention:
  - period: null
    scope: Personal information
    text: We retain your personal information for as long as necessary to provide our services and as required by applicable law.
  - period: null
    scope: AI assistant tool inputs
    text: We do not store them, and we do not write them to our logs or to the links we return.
  rights:
  - right: Access, update or delete
    text: Access, update, or delete your personal information
  - right: Opt out of certain communications
    text: Opt out of certain communications from us
  - right: Request a copy
    text: Request a copy of your personal information
  - right: Object to use
    text: Object to our use of your personal information
  role:
    text: Cost Kits, a limited liability company based in Connecticut, collects information you provide directly to us
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CostKits
provenance_date: '2026-11-09'
provider_name: CostKits
provider_slug: costkits-com
slug: costkits-com-privacy-policy
source_date: '2026-11-09'
source_filename: costkits-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.costkits.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CostKits\naid: costkits-com\nurl: https://www.costkits.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Cost Kits, a limited liability company based in Connecticut, collects information you provide directly to\n    us\ndata_categories:\n- category: identifying\n  text: Name and contact information (email address, phone number)\n- category: financial\n  text: Payment and billing information\n- category: health\n  text: Medical bill information you choose to upload or analyze\n- category: communication\n  text: Communications with our support team\n- category: behavioral\n  text:\
  \ Email engagement, such as whether you open an email from us and which links you click\n- category: device\n  text: the type of client making the request and, where applicable, the procedure and state\npurposes:\n- purpose: Provide and improve services\n  text: Provide, maintain, and improve our medical bill analysis services\n- purpose: Transactions\n  text: Process transactions and send related information\n- purpose: De-identified data for product and marketing\n  text: Create de-identified data from the medical bills you submit\n- purpose: Service provider functions\n  text: We may share information with third-party service providers who perform services on our behalf, such as\n    payment processing, data analysis, and customer service.\nretention:\n- scope: Personal information\n  period: null\n  text: We retain your personal information for as long as necessary to provide our services and as required by\n    applicable law.\n- scope: AI assistant tool inputs\n  period: null\n \
  \ text: We do not store them, and we do not write them to our logs or to the links we return.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Access, update, or delete your personal information\n  text: Access, update, or delete your personal information\nrights:\n- right: Access, update or delete\n  text: Access, update, or delete your personal information\n- right: Opt out of certain communications\n  text: Opt out of certain communications from us\n- right: Request a copy\n  text: Request a copy of your personal information\n- right: Object to use\n  text: Object to our use of your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/costkits-com/privacy/costkits-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from CostKits's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Billing
- Healthcare Costs
- Price Transparency
- Caregivers
- Insurance
- MCP
---
