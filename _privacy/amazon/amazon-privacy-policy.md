---
api_specs:
- filename: amazon-ad-groups-api-openapi.yml
  format: yaml
  label: Amazon Ad Groups API
  slug: amazon-ad-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-ad-groups-api-openapi.yml
- filename: amazon-campaigns-api-openapi.yml
  format: yaml
  label: Amazon Campaigns API
  slug: amazon-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-campaigns-api-openapi.yml
- filename: amazon-charge-permissions-api-openapi.yml
  format: yaml
  label: Amazon Charge Permissions API
  slug: amazon-charge-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-charge-permissions-api-openapi.yml
- filename: amazon-charges-api-openapi.yml
  format: yaml
  label: Amazon Charges API
  slug: amazon-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-charges-api-openapi.yml
- filename: amazon-checkout-sessions-api-openapi.yml
  format: yaml
  label: Amazon Checkout Sessions API
  slug: amazon-checkout-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-checkout-sessions-api-openapi.yml
- filename: amazon-keywords-api-openapi.yml
  format: yaml
  label: Amazon Keywords API
  slug: amazon-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-keywords-api-openapi.yml
- filename: amazon-profiles-api-openapi.yml
  format: yaml
  label: Amazon Profiles API
  slug: amazon-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-profiles-api-openapi.yml
- filename: amazon-refunds-api-openapi.yml
  format: yaml
  label: Amazon Refunds API
  slug: amazon-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-refunds-api-openapi.yml
- filename: amazon-reports-api-openapi.yml
  format: yaml
  label: Amazon Ads Reports API
  slug: amazon-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-reports-api-openapi.yml
- filename: amazon-targets-api-openapi.yml
  format: yaml
  label: Amazon Targets API
  slug: amazon-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-targets-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: identifying information such as your name, address, and phone numbers
  - category: financial
    text: payment information
  - category: location
    text: the location of your device or computer
  - category: behavioral
    text: products and content you viewed or searched for
  - category: device
    text: device metrics such as when a device is in use, application usage, connectivity data, and any errors or event failures
  - category: communication
    text: voice recordings when you speak to Alexa
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Purchase and delivery of products and services
    text: We use your personal information to take and handle orders, deliver products and services, process payments, and communicate with you about orders, products and services, and promotional offers.
  - purpose: Provide, troubleshoot, and improve services
    text: We use your personal information to provide functionality, analyze performance, fix errors, and improve the usability and effectiveness of the Amazon Services.
  - purpose: Generative AI development
    text: This includes using data to develop or deploy our generative AI models and services.
  - purpose: Advertising
    text: We use your personal information to display interest-based ads for features, products, and services that might be of interest to you.
  - purpose: Fraud prevention and credit risk
    text: We use personal information to prevent and detect fraud and abuse in order to protect the security of our customers, Amazon, and others.
  rights:
  - right: access or deletion
    text: to the extent required by applicable law, you may have the right to request access to or delete your personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we are not in the business of selling our customers' personal information to others
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Amazon.com, Inc. participates in the EU-US Data Privacy Framework, the UK Extension to the EU-US Data Privacy Framework, and the Swiss-US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Amazon
provenance_date: '2026-11-09'
provider_name: Amazon
provider_slug: amazon
slug: amazon-privacy-policy
source_date: '2026-11-09'
source_filename: amazon-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.amazon.com/gp/help/customer/display.html?nodeId=GX7NJQ4ZB8MHFRNJ
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Amazon\naid: amazon\nurl: https://www.amazon.com/gp/help/customer/display.html?nodeId=GX7NJQ4ZB8MHFRNJ\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: identifying information such as your name, address, and phone numbers\n- category: financial\n  text: payment information\n- category: location\n  text: the location of your device or computer\n- category: behavioral\n  text: products and content you viewed or searched for\n- category: device\n  text: device metrics such as when a device is in use, application usage, connectivity data, and\
  \ any errors or\n    event failures\n- category: communication\n  text: voice recordings when you speak to Alexa\npurposes:\n- purpose: Purchase and delivery of products and services\n  text: We use your personal information to take and handle orders, deliver products and services, process payments,\n    and communicate with you about orders, products and services, and promotional offers.\n- purpose: Provide, troubleshoot, and improve services\n  text: We use your personal information to provide functionality, analyze performance, fix errors, and improve\n    the usability and effectiveness of the Amazon Services.\n- purpose: Generative AI development\n  text: This includes using data to develop or deploy our generative AI models and services.\n- purpose: Advertising\n  text: We use your personal information to display interest-based ads for features, products, and services that\n    might be of interest to you.\n- purpose: Fraud prevention and credit risk\n  text: We use personal information\
  \ to prevent and detect fraud and abuse in order to protect the security of our\n    customers, Amazon, and others.\nretention: []\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Amazon.com, Inc. participates in the EU-US Data Privacy Framework, the UK Extension to the EU-US Data Privacy\n    Framework, and the Swiss-US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access or deletion\n  text: to the extent required by applicable law, you may have the right to request access to or delete your personal\n    information\nsale_or_sharing:\n  stance: prohibited\n  text: we are not in the business of selling our customers' personal information to others\n"
source_yaml_url: https://artifacts.apis.io/amazon/privacy/amazon-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- transfers
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Amazon's own page on 2026-11-09.
synthetic: false
tags:
- Amazon
- Advertising
- Alexa
- E-Commerce
- Marketplace
- Payments
- Voice
- Fortune 100
- Agentic Commerce
---
