---
api_specs:
- filename: service-cloud-bot-api-openapi.yml
  format: yaml
  label: Salesforce Service Cloud APIs Bot API
  slug: service-cloud-bot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/service-cloud/openapi/service-cloud-bot-api-openapi.yml
- filename: service-cloud-health-api-openapi.yml
  format: yaml
  label: Salesforce Service Cloud APIs Health API
  slug: service-cloud-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/service-cloud/openapi/service-cloud-health-api-openapi.yml
- filename: service-cloud-versions-api-openapi.yml
  format: yaml
  label: Salesforce Service Cloud APIs Versions API
  slug: service-cloud-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/service-cloud/openapi/service-cloud-versions-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact information, such as your name, job title, company name, address, phone number, email address, username and password
  - category: financial
    text: Contact information, financial and billing information, such as billing name and address, credit card number or bank account information
  - category: biometric
    text: If you give your explicit consent and only for specified events, your biometric information, such as an image of your facial features for identification purposes
  - category: health
    text: To the extent that national or local laws require it, this may also include health status, including your temperature, COVID-19-related symptoms, exposure to COVID-19 positive individuals, vaccination status, testing results, and recent travel history
  - category: device
    text: Information about your device and your usage of our websites or emails (such as Internet Protocol (IP) addresses or other identifiers)
  - category: communication
    text: Information such as your name, voice, telephone number and any other Personal Data voluntarily shared
  deletion:
    route: Contact privacy team via form or privacy@salesforce.com
    text: To exercise your rights relating to your personal data, or if you have questions regarding our privacy practices, please fill out this form, email us at privacy@salesforce.com
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: Displaying personalized advertisements and content
    text: to display personalized advertisements and content
  - purpose: Sending marketing communications
    text: to send marketing communications
  - purpose: Developing and optimizing services
    text: to develop and optimize the performance of our services
  - purpose: Complying with legal obligations and defending Salesforce
    text: to comply with our legal obligations and defend Salesforce
  retention:
  - period: null
    scope: Personal Data generally
    text: We may retain your Personal Data for a period of time consistent with the original purpose of collection (see Section 5 above) or as long as required to fulfill our legal and/or regulatory obligations.
  rights:
  - right: Access
    text: Access your Personal Data held by us
  - right: Erase or delete
    text: Erase or delete your Personal Data
  - right: Rectify
    text: Rectify inaccurate Personal Data
  - right: Object
    text: Object to any processing of your Personal Data
  - right: Restrict processing
    text: Restrict our processing of your Personal Data
  - right: Portability
    text: Transfer your Personal Data to another controller (data portability), to the extent possible
  - right: Withdraw consent
    text: Withdraw your consent at any time (to the extent we rely on consent as our legal basis for processing)
  - right: Opt out of sharing for advertising
    text: Opt out of the sharing of your Personal Data for delivering advertisements on non-Salesforce websites, applications, and services
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
  - mechanism: SCC
    text: including, where required, standard contractual clauses or an alternative mechanism for the transfer of Personal Data as approved by the European Commission
  - mechanism: DPF
    text: Salesforce also commits to comply with the EU-U.S. Data Privacy Framework, the Swiss-U.S. Data Privacy Framework, and the UK Extension to the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Salesforce Service Cloud APIs
provenance_date: '2026-11-10'
provider_name: Salesforce Service Cloud APIs
provider_slug: service-cloud
slug: service-cloud-privacy-policy
source_date: '2026-11-10'
source_filename: service-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.salesforce.com/company/legal/privacy/?bc=OTH
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Salesforce Service Cloud APIs\naid: service-cloud\nurl: https://www.salesforce.com/company/legal/privacy/?bc=OTH\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Contact information, such as your name, job title, company name, address, phone number, email address, username\n    and password\n- category: financial\n  text: Contact information, financial and billing information, such as billing name and address, credit card number\n    or bank account information\n- category: biometric\n  text: If you give your explicit\
  \ consent and only for specified events, your biometric information, such as an\n    image of your facial features for identification purposes\n- category: health\n  text: To the extent that national or local laws require it, this may also include health status, including your\n    temperature, COVID-19-related symptoms, exposure to COVID-19 positive individuals, vaccination status, testing\n    results, and recent travel history\n- category: device\n  text: Information about your device and your usage of our websites or emails (such as Internet Protocol (IP) addresses\n    or other identifiers)\n- category: communication\n  text: Information such as your name, voice, telephone number and any other Personal Data voluntarily shared\npurposes:\n- purpose: Displaying personalized advertisements and content\n  text: to display personalized advertisements and content\n- purpose: Sending marketing communications\n  text: to send marketing communications\n- purpose: Developing and optimizing\
  \ services\n  text: to develop and optimize the performance of our services\n- purpose: Complying with legal obligations and defending Salesforce\n  text: to comply with our legal obligations and defend Salesforce\nretention:\n- scope: Personal Data generally\n  period: null\n  text: We may retain your Personal Data for a period of time consistent with the original purpose of collection\n    (see Section 5 above) or as long as required to fulfill our legal and/or regulatory obligations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: including, where required, standard contractual clauses or an alternative mechanism for the transfer of\n    Personal Data as approved by the European Commission\n- mechanism: DPF\n  text: Salesforce also commits to comply with the EU-U.S. Data Privacy Framework, the Swiss-U.S. Data Privacy Framework,\n    and the UK Extension to the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text:\
  \ Data Processing Addendum\ndeletion:\n  route: Contact privacy team via form or privacy@salesforce.com\n  text: To exercise your rights relating to your personal data, or if you have questions regarding our privacy practices,\n    please fill out this form, email us at privacy@salesforce.com\nrights:\n- right: Access\n  text: Access your Personal Data held by us\n- right: Erase or delete\n  text: Erase or delete your Personal Data\n- right: Rectify\n  text: Rectify inaccurate Personal Data\n- right: Object\n  text: Object to any processing of your Personal Data\n- right: Restrict processing\n  text: Restrict our processing of your Personal Data\n- right: Portability\n  text: Transfer your Personal Data to another controller (data portability), to the extent possible\n- right: Withdraw consent\n  text: Withdraw your consent at any time (to the extent we rely on consent as our legal basis for processing)\n- right: Opt out of sharing for advertising\n  text: Opt out of the sharing of your\
  \ Personal Data for delivering advertisements on non-Salesforce websites, applications,\n    and services\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/service-cloud/privacy/service-cloud-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 23 quoted statements, read from Salesforce Service Cloud APIs's own page on 2026-11-10.
synthetic: false
tags:
- Cloud
- CRM
- Customer Service
- Enterprise
- Salesforce
- Support
---
