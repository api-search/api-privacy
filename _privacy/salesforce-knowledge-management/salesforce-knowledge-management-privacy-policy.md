---
api_specs:
- filename: salesforce-knowledge-management-articles-api-openapi.yml
  format: yaml
  label: Salesforce Knowledge Management Articles API
  slug: salesforce-knowledge-management-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesforce-knowledge-management/openapi/salesforce-knowledge-management-articles-api-openapi.yml
- filename: salesforce-knowledge-management-categories-api-openapi.yml
  format: yaml
  label: Salesforce Knowledge Management Categories API
  slug: salesforce-knowledge-management-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesforce-knowledge-management/openapi/salesforce-knowledge-management-categories-api-openapi.yml
- filename: salesforce-knowledge-management-search-api-openapi.yml
  format: yaml
  label: Salesforce Knowledge Management Search API
  slug: salesforce-knowledge-management-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesforce-knowledge-management/openapi/salesforce-knowledge-management-search-api-openapi.yml
- filename: salesforce-knowledge-management-suggestions-api-openapi.yml
  format: yaml
  label: Salesforce Knowledge Management Suggestions API
  slug: salesforce-knowledge-management-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesforce-knowledge-management/openapi/salesforce-knowledge-management-suggestions-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information, such as your name, job title, company name, address, phone number, email address, username and password
  - category: financial
    text: Contact information, financial and billing information, such as billing name and address, credit card number or bank account information
  - category: biometric
    text: your biometric information, such as an image of your facial features for identification purposes
  - category: health
    text: To the extent that national or local laws require it, this may also include health status, including your temperature, COVID-19-related symptoms, exposure to COVID-19 positive individuals, vaccination status, testing results, and recent travel history
  - category: location
    text: location information from third parties, which helps us offer features like identity management and multi-factor authentication for security purposes
  - category: behavioral
    text: inferences about preferences and behaviors
  - category: device
    text: Information about your device and your usage of our websites or emails (such as Internet Protocol (IP) addresses or other identifiers)
  - category: communication
    text: Information such as your name, voice, telephone number and any other Personal Data voluntarily shared
  - category: professional
    text: professional or employment-related information, financial account information
  deletion:
    route: web form or email to privacy@salesforce.com
    text: To exercise your rights relating to your Personal Data, or if you have questions regarding our privacy practices, please fill out this form, email us at privacy@salesforce.com
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: display personalized advertisements and content
    text: to display personalized advertisements and content
  - purpose: send marketing communications
    text: to send marketing communications
  - purpose: ensure safety and security of offices, premises, employees and events
    text: to ensure the safety and security of our offices, premises, employees and events
  retention:
  - period: null
    scope: general
    text: We may retain your Personal Data for a period of time consistent with the original purpose of collection (see Section 5 above) or as long as required to fulfill our legal and/or regulatory obligations.
  rights:
  - right: access
    text: Access your Personal Data held by us
  - right: erase or delete
    text: Erase or delete your Personal Data
  - right: object
    text: Object to any processing of your Personal Data
  - right: opt out of sharing for advertising
    text: Opt out of the sharing of your Personal Data for delivering advertisements on non-Salesforce websites, applications, and services
  - right: appeal
    text: Appeal our refusal to act upon your request to exercise a right relating to your Personal Data by following the steps provided in response to your inquiry
  role:
    text: act as the controllers of your Personal Data and are responsible for its processing
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Opt out of the sharing of your Personal Data for delivering advertisements on non-Salesforce websites, applications, and services
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
name: Salesforce Knowledge Management
provenance_date: '2026-11-10'
provider_name: Salesforce Knowledge Management
provider_slug: salesforce-knowledge-management
slug: salesforce-knowledge-management-privacy-policy
source_date: '2026-11-10'
source_filename: salesforce-knowledge-management-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.salesforce.com/company/legal/privacy/?bc=OTH
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Salesforce Knowledge Management\naid: salesforce-knowledge-management\nurl: https://www.salesforce.com/company/legal/privacy/?bc=OTH\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: act as the controllers of your Personal Data and are responsible for its processing\ndata_categories:\n- category: contact\n  text: Contact information, such as your name, job title, company name, address, phone number, email address, username\n    and password\n- category: financial\n  text: Contact information, financial and billing information, such as billing name and address, credit card number\n\
  \    or bank account information\n- category: biometric\n  text: your biometric information, such as an image of your facial features for identification purposes\n- category: health\n  text: To the extent that national or local laws require it, this may also include health status, including your\n    temperature, COVID-19-related symptoms, exposure to COVID-19 positive individuals, vaccination status, testing\n    results, and recent travel history\n- category: location\n  text: location information from third parties, which helps us offer features like identity management and multi-factor\n    authentication for security purposes\n- category: behavioral\n  text: inferences about preferences and behaviors\n- category: device\n  text: Information about your device and your usage of our websites or emails (such as Internet Protocol (IP) addresses\n    or other identifiers)\n- category: communication\n  text: Information such as your name, voice, telephone number and any other Personal Data\
  \ voluntarily shared\n- category: professional\n  text: professional or employment-related information, financial account information\npurposes:\n- purpose: display personalized advertisements and content\n  text: to display personalized advertisements and content\n- purpose: send marketing communications\n  text: to send marketing communications\n- purpose: ensure safety and security of offices, premises, employees and events\n  text: to ensure the safety and security of our offices, premises, employees and events\nretention:\n- scope: general\n  period: null\n  text: We may retain your Personal Data for a period of time consistent with the original purpose of collection\n    (see Section 5 above) or as long as required to fulfill our legal and/or regulatory obligations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: standard contractual clauses or an alternative mechanism for the transfer of Personal Data as approved by\n    the European Commission\n- mechanism: DPF\n  text: Salesforce\
  \ also commits to comply with the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: web form or email to privacy@salesforce.com\n  text: To exercise your rights relating to your Personal Data, or if you have questions regarding our privacy practices,\n    please fill out this form, email us at privacy@salesforce.com\nrights:\n- right: access\n  text: Access your Personal Data held by us\n- right: erase or delete\n  text: Erase or delete your Personal Data\n- right: object\n  text: Object to any processing of your Personal Data\n- right: opt out of sharing for advertising\n  text: Opt out of the sharing of your Personal Data for delivering advertisements on non-Salesforce websites, applications,\n    and services\n- right: appeal\n  text: Appeal our refusal to act upon your request to exercise a right relating to your Personal Data by following\n    the steps provided in\
  \ response to your inquiry\nsale_or_sharing:\n  stance: conditional\n  text: Opt out of the sharing of your Personal Data for delivering advertisements on non-Salesforce websites, applications,\n    and services\n"
source_yaml_url: https://artifacts.apis.io/salesforce-knowledge-management/privacy/salesforce-knowledge-management-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Salesforce Knowledge Management's own page on 2026-11-10.
synthetic: false
tags:
- Articles
- CRM
- Customer Service
- Documentation
- Knowledge Management
- Support
---
