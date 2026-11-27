---
api_specs:
- filename: salesforce-marketing-cloud-assets-api-openapi.yml
  format: yaml
  label: Salesforce Marketing Cloud Assets API
  slug: salesforce-marketing-cloud-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesforce-marketing-cloud/openapi/salesforce-marketing-cloud-assets-api-openapi.yml
- filename: salesforce-marketing-cloud-contacts-api-openapi.yml
  format: yaml
  label: Salesforce Marketing Cloud Contacts API
  slug: salesforce-marketing-cloud-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesforce-marketing-cloud/openapi/salesforce-marketing-cloud-contacts-api-openapi.yml
- filename: salesforce-marketing-cloud-journeys-api-openapi.yml
  format: yaml
  label: Salesforce Marketing Cloud Journeys API
  slug: salesforce-marketing-cloud-journeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesforce-marketing-cloud/openapi/salesforce-marketing-cloud-journeys-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information, such as your name, job title, company name, address, phone number, email address, username and password
  - category: financial
    text: financial and billing information, such as billing name and address, credit card number or bank account information
  - category: biometric
    text: your biometric information, such as an image of your facial features for identification purposes
  - category: health
    text: health status, including your temperature, COVID-19-related symptoms, exposure to COVID-19 positive individuals, vaccination status, testing results, and recent travel history
  - category: behavioral
    text: inferences about preferences and behaviors
  - category: device
    text: Information about your device and your usage of our websites or emails (such as Internet Protocol (IP) addresses or other identifiers)
  - category: location
    text: location information from third parties, which helps us offer features like identity management and multi-factor authentication
  - category: communication
    text: Information such as your name, voice, telephone number and any other Personal Data voluntarily shared
  deletion:
    route: privacy@salesforce.com
    text: email us at privacy@salesforce.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: display personalized advertisements and content
    text: to display personalized advertisements and content
  - purpose: send marketing communications
    text: to send marketing communications
  - purpose: develop and optimize the performance of our services
    text: to develop and optimize the performance of our services
  - purpose: ensure safety and security of offices and events
    text: to ensure the safety and security of our offices, premises, employees and events
  retention:
  - period: null
    scope: general
    text: We may retain your Personal Data for a period of time consistent with the original purpose of collection (see Section 5 above) or as long as required to fulfill our legal and/or regulatory obligations.
  rights:
  - right: erase or delete
    text: Erase or delete your Personal Data
  - right: object to processing
    text: Object to any processing of your Personal Data
  - right: opt out of sharing for advertising
    text: Opt out of the sharing of your Personal Data for delivering advertisements on non-Salesforce websites, applications, and services
  - right: appeal refusal
    text: Appeal our refusal to act upon your request to exercise a right relating to your Personal Data
  role:
    text: act as the controllers of your Personal Data
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: standard contractual clauses or an alternative mechanism for the transfer of Personal Data as approved by the European Commission
  - mechanism: DPF
    text: Salesforce also commits to comply with the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Salesforce Marketing Cloud
provenance_date: '2026-11-10'
provider_name: Salesforce Marketing Cloud
provider_slug: salesforce-marketing-cloud
slug: salesforce-marketing-cloud-privacy-policy
source_date: '2026-11-10'
source_filename: salesforce-marketing-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.salesforce.com/company/legal/privacy/?bc=OTH
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Salesforce Marketing Cloud\naid: salesforce-marketing-cloud\nurl: https://www.salesforce.com/company/legal/privacy/?bc=OTH\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: act as the controllers of your Personal Data\ndata_categories:\n- category: contact\n  text: Contact information, such as your name, job title, company name, address, phone number, email address, username\n    and password\n- category: financial\n  text: financial and billing information, such as billing name and address, credit card number or bank account\n    information\n- category: biometric\n  text:\
  \ your biometric information, such as an image of your facial features for identification purposes\n- category: health\n  text: health status, including your temperature, COVID-19-related symptoms, exposure to COVID-19 positive individuals,\n    vaccination status, testing results, and recent travel history\n- category: behavioral\n  text: inferences about preferences and behaviors\n- category: device\n  text: Information about your device and your usage of our websites or emails (such as Internet Protocol (IP) addresses\n    or other identifiers)\n- category: location\n  text: location information from third parties, which helps us offer features like identity management and multi-factor\n    authentication\n- category: communication\n  text: Information such as your name, voice, telephone number and any other Personal Data voluntarily shared\npurposes:\n- purpose: display personalized advertisements and content\n  text: to display personalized advertisements and content\n- purpose: send\
  \ marketing communications\n  text: to send marketing communications\n- purpose: develop and optimize the performance of our services\n  text: to develop and optimize the performance of our services\n- purpose: ensure safety and security of offices and events\n  text: to ensure the safety and security of our offices, premises, employees and events\nretention:\n- scope: general\n  period: null\n  text: We may retain your Personal Data for a period of time consistent with the original purpose of collection\n    (see Section 5 above) or as long as required to fulfill our legal and/or regulatory obligations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: standard contractual clauses or an alternative mechanism for the transfer of Personal Data as approved by\n    the European Commission\n- mechanism: DPF\n  text: Salesforce also commits to comply with the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: privacy@salesforce.com\n  text: email us at privacy@salesforce.com\nrights:\n- right: erase or delete\n  text: Erase or delete your Personal Data\n- right: object to processing\n  text: Object to any processing of your Personal Data\n- right: opt out of sharing for advertising\n  text: Opt out of the sharing of your Personal Data for delivering advertisements on non-Salesforce websites, applications,\n    and services\n- right: appeal refusal\n  text: Appeal our refusal to act upon your request to exercise a right relating to your Personal Data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/salesforce-marketing-cloud/privacy/salesforce-marketing-cloud-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from Salesforce Marketing Cloud's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Content Management
- Customer Journey
- Digital Marketing
- Email
- Marketing
- Marketing Automation
- MCP
- Mobile Messaging
- Personalization
- SMS
- Webhook
---
