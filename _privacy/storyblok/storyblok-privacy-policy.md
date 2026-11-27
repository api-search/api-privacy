---
api_specs:
- filename: storyblok-webhooks-asyncapi.yml
  format: yaml
  label: Storyblok Webhooks
  slug: storyblok-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/storyblok/asyncapi/storyblok-webhooks-asyncapi.yml
- filename: storyblok-assets-api-openapi.yml
  format: yaml
  label: Storyblok Assets API
  slug: storyblok-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-assets-api-openapi.yml
- filename: storyblok-collaborators-api-openapi.yml
  format: yaml
  label: Storyblok Collaborators API
  slug: storyblok-collaborators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-collaborators-api-openapi.yml
- filename: storyblok-components-api-openapi.yml
  format: yaml
  label: Storyblok Components API
  slug: storyblok-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-components-api-openapi.yml
- filename: storyblok-image-transformation-api-openapi.yml
  format: yaml
  label: Storyblok Image Transformation API
  slug: storyblok-image-transformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-image-transformation-api-openapi.yml
- filename: storyblok-links-api-openapi.yml
  format: yaml
  label: Storyblok Links API
  slug: storyblok-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-links-api-openapi.yml
- filename: storyblok-spaces-api-openapi.yml
  format: yaml
  label: Storyblok Spaces API
  slug: storyblok-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-spaces-api-openapi.yml
- filename: storyblok-stories-api-openapi.yml
  format: yaml
  label: Storyblok Stories API
  slug: storyblok-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-stories-api-openapi.yml
- filename: storyblok-tags-api-openapi.yml
  format: yaml
  label: Storyblok Tags API
  slug: storyblok-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-tags-api-openapi.yml
- filename: storyblok-webhooks-api-openapi.yml
  format: yaml
  label: Storyblok Webhooks API
  slug: storyblok-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-webhooks-api-openapi.yml
- filename: storyblok-data-sources-api-openapi.yml
  format: yaml
  label: Storyblok Data Sources API
  slug: storyblok-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/storyblok/openapi/storyblok-data-sources-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process personal data (such as IP address, name, email address or contact information) you share with us
  - category: contact
    text: we may collect your first name, last name, email address, country, phone number and other contact details to fulfill your request
  - category: financial
    text: we collect your name, contact information, and your payment information (which may include your credit card provider and expiration date, and other related billing information)
  - category: device
    text: This includes a device's IP address (processed during your session and stored in a de-identified form), device screen size, device type (unique device identifiers), browser information
  - category: location
    text: geographic location (country only)
  - category: behavioral
    text: how much time they spend on which pages, which links they choose to click
  - category: biometric
    text: a video recording of the interview
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: our customer agrees to enter into and be bound by the Storyblok Data Processing Agreement and all attachments thereto
    url: null
  purposes:
  - purpose: Operate and secure website and services
    text: We need to process these log files in order to ensure the functionality, stability and security of our website
  - purpose: Analytics and marketing via cookies
    text: We collect this data to analyze and regularly improve the use of our website, to provide functionality, to recognize you across different services and devices
  - purpose: Newsletter
    text: We offer the Newsletter to inform you about our services and products.
  - purpose: Contract performance and sales
    text: We process Contact Information in order to offer, market, and sell our products and services to you or to reply to your request.
  retention:
  - period: 30 days
    scope: Log Files & Usage Information
    text: 'Log Files & Usage Information: 30 days in its original form.'
  - period: 7 years
    scope: Financial records
    text: Financial records have to be kept 7 years according to applicable law (e.g. § 132 BAO).
  - period: null
    scope: Account Information
    text: We retain your account information until you delete or request the removal of your account.
  rights:
  - right: Deletion
    text: you have the right to request the deletion of your personal data
  - right: Object
    text: You have the right to object to the processing of your personal data for this purpose at any time.
  - right: Withdraw consent
    text: You may unsubscribe from our newsletter, e.g. by withdrawing your consent, at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We would like to point out that user data may also be processed outside the European Union.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Storyblok
provenance_date: '2026-11-10'
provider_name: Storyblok
provider_slug: storyblok
slug: storyblok-privacy-policy
source_date: '2026-11-10'
source_filename: storyblok-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.storyblok.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Storyblok\naid: storyblok\nurl: https://www.storyblok.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We process personal data (such as IP address, name, email address or contact information) you share with\n    us\n- category: contact\n  text: we may collect your first name, last name, email address, country, phone number and other contact details\n    to fulfill your request\n- category: financial\n  text: we collect your name, contact information, and your payment information (which may include\
  \ your credit card\n    provider and expiration date, and other related billing information)\n- category: device\n  text: This includes a device's IP address (processed during your session and stored in a de-identified form),\n    device screen size, device type (unique device identifiers), browser information\n- category: location\n  text: geographic location (country only)\n- category: behavioral\n  text: how much time they spend on which pages, which links they choose to click\n- category: biometric\n  text: a video recording of the interview\npurposes:\n- purpose: Operate and secure website and services\n  text: We need to process these log files in order to ensure the functionality, stability and security of our website\n- purpose: Analytics and marketing via cookies\n  text: We collect this data to analyze and regularly improve the use of our website, to provide functionality,\n    to recognize you across different services and devices\n- purpose: Newsletter\n  text: We offer the\
  \ Newsletter to inform you about our services and products.\n- purpose: Contract performance and sales\n  text: We process Contact Information in order to offer, market, and sell our products and services to you or to\n    reply to your request.\nretention:\n- scope: Log Files & Usage Information\n  period: 30 days\n  text: 'Log Files & Usage Information: 30 days in its original form.'\n- scope: Financial records\n  period: 7 years\n  text: Financial records have to be kept 7 years according to applicable law (e.g. § 132 BAO).\n- scope: Account Information\n  period: null\n  text: We retain your account information until you delete or request the removal of your account.\nresidency: []\ntransfers:\n- mechanism: other\n  text: We would like to point out that user data may also be processed outside the European Union.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: our customer agrees to enter into and be bound by the Storyblok Data Processing Agreement\
  \ and all attachments\n    thereto\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Deletion\n  text: you have the right to request the deletion of your personal data\n- right: Object\n  text: You have the right to object to the processing of your personal data for this purpose at any time.\n- right: Withdraw consent\n  text: You may unsubscribe from our newsletter, e.g. by withdrawing your consent, at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/storyblok/privacy/storyblok-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- rights
summary_line: 19 quoted statements, read from Storyblok's own page on 2026-11-10.
synthetic: false
tags:
- CMS
- Content Delivery
- Content Management
- Headless CMS
- Image Optimization
- REST API
- Visual Editor
- Webhook
---
