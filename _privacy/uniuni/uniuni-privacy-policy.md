---
api_specs:
- filename: uniuni-batches-api-openapi.yml
  format: yaml
  label: UniUni Batches API
  slug: uniuni-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-batches-api-openapi.yml
- filename: uniuni-labels-api-openapi.yml
  format: yaml
  label: UniUni Labels API
  slug: uniuni-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-labels-api-openapi.yml
- filename: uniuni-shipments-api-openapi.yml
  format: yaml
  label: UniUni Shipments API
  slug: uniuni-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-shipments-api-openapi.yml
- filename: uniuni-tracking-api-openapi.yml
  format: yaml
  label: UniUni Tracking API
  slug: uniuni-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-tracking-api-openapi.yml
- filename: uniuni-webhooks-api-openapi.yml
  format: yaml
  label: UniUni Webhooks API
  slug: uniuni-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uniuni/openapi/uniuni-webhooks-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: your first and last name, employer, position, email address, phone number, mailing address, personal preferences, hours of availability and/or photo
  - category: location
    text: If you are a Driver or a Recipient, we may also collect information about your precise or approximate location.
  - category: device
    text: the type of mobile device, your mobile device unique ID and your mobile operating system
  - category: behavioral
    text: your browsing history on the Website; the length of time you spend on certain pages
  - category: financial
    text: business name, address, type of products that are shipped, volume of shipments and payment information
  deletion:
    route: Written request to privacy@uniuni.com or la.support@uniuni.com
    text: You may also contact us using the methods described below under “Contact Us” to request access to, correction of, or deletion of, any Personal Information that you have provided to us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service
    text: 'To provide the Service to you: To deliver a package for or to you'
  - purpose: targeted advertising
    text: To deliver targeted advertising to you
  - purpose: evaluate and improve the Service
    text: To evaluate and improve the Service, products, services, marketing and your experience.
  residency:
  - region: Canada
    text: Your information, including your Personal Information, is processed at the Company’s operating offices in Richmond, British Columbia.
  retention:
  - period: null
    scope: personal information
    text: for as long as is necessary for the purposes set out in this Privacy Policy; and to the extent required by law.
  - period: null
    scope: usage data
    text: We retain usage data in an anonymized form.
  rights:
  - right: access
    text: You have a right to access your Personal Information subject to some exceptions.
  - right: correction
    text: You may request correction to your Personal Information in order to ensure its accuracy and completeness.
  - right: know, delete, correct (California)
    text: You have the right to request that we delete any of your Personal Information that we collected from you and retained, subject to certain exceptions.
  - right: opt-out of sale or sharing (California)
    text: You have the right to prevent the sale and sharing of your Personal Information to third parties at any time by requesting that we stop doing so
  role:
    text: We may collect, use or disclose your Personal Information
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We may sell the categories of Personal Information and/or Sensitive Personal Information we collect or share it with third parties for cross-context behavioral advertising, as indicated in the tables below.
  subprocessors:
    text: More information about the Service Providers we use can be found here
    url: https://www.uniuni.com/service-provider-ca-privacy-policy/
  transfers:
  - mechanism: other
    text: Your Personal Information will not be transferred to a Service Provider or another country unless the Company has confirmed that there are adequate controls in place to maintain the security of your Personal Information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UniUni
provenance_date: '2026-11-10'
provider_name: UniUni
provider_slug: uniuni
slug: uniuni-privacy-policy
source_date: '2026-11-10'
source_filename: uniuni-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.uniuni.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UniUni\naid: uniuni\nurl: https://www.uniuni.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: We may collect, use or disclose your Personal Information\ndata_categories:\n- category: identifying\n  text: your first and last name, employer, position, email address, phone number, mailing address, personal preferences,\n    hours of availability and/or photo\n- category: location\n  text: If you are a Driver or a Recipient, we may also collect information about your precise or approximate location.\n- category: device\n  text: the type of mobile device, your\
  \ mobile device unique ID and your mobile operating system\n- category: behavioral\n  text: your browsing history on the Website; the length of time you spend on certain pages\n- category: financial\n  text: business name, address, type of products that are shipped, volume of shipments and payment information\npurposes:\n- purpose: provide the Service\n  text: 'To provide the Service to you: To deliver a package for or to you'\n- purpose: targeted advertising\n  text: To deliver targeted advertising to you\n- purpose: evaluate and improve the Service\n  text: To evaluate and improve the Service, products, services, marketing and your experience.\nretention:\n- scope: personal information\n  period: null\n  text: for as long as is necessary for the purposes set out in this Privacy Policy; and to the extent required\n    by law.\n- scope: usage data\n  period: null\n  text: We retain usage data in an anonymized form.\nresidency:\n- region: Canada\n  text: Your information, including your\
  \ Personal Information, is processed at the Company’s operating offices in\n    Richmond, British Columbia.\ntransfers:\n- mechanism: other\n  text: Your Personal Information will not be transferred to a Service Provider or another country unless the Company\n    has confirmed that there are adequate controls in place to maintain the security of your Personal Information.\nsubprocessors:\n  url: https://www.uniuni.com/service-provider-ca-privacy-policy/\n  text: More information about the Service Providers we use can be found here\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Written request to privacy@uniuni.com or la.support@uniuni.com\n  text: You may also contact us using the methods described below under “Contact Us” to request access to, correction\n    of, or deletion of, any Personal Information that you have provided to us.\nrights:\n- right: access\n  text: You have a right to access your Personal Information subject to some exceptions.\n- right: correction\n\
  \  text: You may request correction to your Personal Information in order to ensure its accuracy and completeness.\n- right: know, delete, correct (California)\n  text: You have the right to request that we delete any of your Personal Information that we collected from you\n    and retained, subject to certain exceptions.\n- right: opt-out of sale or sharing (California)\n  text: You have the right to prevent the sale and sharing of your Personal Information to third parties at any\n    time by requesting that we stop doing so\nsale_or_sharing:\n  stance: conditional\n  text: We may sell the categories of Personal Information and/or Sensitive Personal Information we collect or share\n    it with third parties for cross-context behavioral advertising, as indicated in the tables below.\n"
source_yaml_url: https://artifacts.apis.io/uniuni/privacy/uniuni-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from UniUni's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Last Mile Delivery
- E-Commerce
- Tracking
- Delivery
---
