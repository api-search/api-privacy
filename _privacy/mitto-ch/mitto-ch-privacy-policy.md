---
api_specs:
- filename: mitto-ch-apis-api-openapi.yml
  format: yaml
  label: Mitto APIs API
  slug: mitto-ch-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mitto-ch/openapi/mitto-ch-apis-api-openapi.yml
- filename: mitto-ch-autoreplyconfigs-api-openapi.yml
  format: yaml
  label: Mitto Auto Reply Configs API
  slug: mitto-ch-autoreplyconfigs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mitto-ch/openapi/mitto-ch-autoreplyconfigs-api-openapi.yml
- filename: mitto-ch-customers-api-openapi.yml
  format: yaml
  label: Mitto Customers API
  slug: mitto-ch-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mitto-ch/openapi/mitto-ch-customers-api-openapi.yml
- filename: mitto-ch-mitto-api-api-openapi.yml
  format: yaml
  label: Mitto Mitto API
  slug: mitto-ch-mitto-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mitto-ch/openapi/mitto-ch-mitto-api-api-openapi.yml
- filename: mitto-ch-statistic-api-openapi.yml
  format: yaml
  label: Mitto Statistic API
  slug: mitto-ch-statistic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mitto-ch/openapi/mitto-ch-statistic-api-openapi.yml
- filename: mitto-ch-webhooks-api-openapi.yml
  format: yaml
  label: Mitto Webhooks API
  slug: mitto-ch-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mitto-ch/openapi/mitto-ch-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: First and Last Name
  - category: contact
    text: E-mail address
  - category: contact
    text: Telephone number
  - category: professional
    text: Job Title
  - category: device
    text: IP address of the requesting computer or host
  - category: behavioral
    text: Website from which our domain was accessed as well as the last opened website
  deletion:
    route: request deletion via info@mitto.ch or dpo@mitto.ch
    text: To exercise your rights, you can write to the data controller at info@mitto.ch or to the DPO at dpo@mitto.ch .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: website security and functionality
    text: legitimate interest of the data controller in preserving the security of the website and its functionalities (Art. 6 (1) (f) GDPR)
  - purpose: responding to contact requests
    text: The acquired data, such as contact details and the content of communications, will be used exclusively to respond to the requests received.
  - purpose: account creation and access
    text: we process the data necessary to allow you to create and/or access your account
  - purpose: evaluating job applications
    text: We will process the information contained in the CV and the information you provide us to evaluate your application.
  retention:
  - period: null
    scope: contact form and communications
    text: it is deleted when the respective conversation with the user has ended
  - period: null
    scope: website registration data
    text: The data related to your website registration will be retained until you request the deletion of your profile.
  - period: 12 months
    scope: job application CV and data
    text: Your CV and the personal data you provide to us when you send us your application for a job position will be stored for 12 months after the recruitment process, unless you request its deletion earlier.
  rights:
  - right: access
    text: 'Right of access : You have the right to obtain information regarding the processing of your personal data and to access and receive a copy of it'
  - right: rectification
    text: 'Right to rectification : You have the right to obtain the update, integration, or rectification of data.'
  - right: portability
    text: 'Right to data portability : You can request the portability of data processed in the context of contract performance or based on your consent'
  - right: erasure
    text: 'Right to erasure : You have the right to request the deletion of stored data.'
  - right: restriction and objection
    text: 'Right to restriction and objection : You have the right to request the restriction of processing or to object'
  role:
    text: The data controller is Mitto AG, with its headquarters at 6300 Zug, Switzerland, Bahnhofstraße 21.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: In the past 12 months we have not sold any of your personal information
  subprocessors:
    text: A detailed list of all recipients is available at the headquarters of the Data Controller and will be provided upon request.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mitto
provenance_date: '2026-11-10'
provider_name: Mitto
provider_slug: mitto-ch
slug: mitto-ch-privacy-policy
source_date: '2026-11-10'
source_filename: mitto-ch-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mitto.ch/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mitto\naid: mitto-ch\nurl: https://mitto.ch/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Mitto AG, with its headquarters at 6300 Zug, Switzerland, Bahnhofstraße 21.\ndata_categories:\n- category: identifying\n  text: First and Last Name\n- category: contact\n  text: E-mail address\n- category: contact\n  text: Telephone number\n- category: professional\n  text: Job Title\n- category: device\n  text: IP address of the requesting computer or host\n- category: behavioral\n  text: Website from which our domain was accessed as well as the last opened website\n\
  purposes:\n- purpose: website security and functionality\n  text: legitimate interest of the data controller in preserving the security of the website and its functionalities\n    (Art. 6 (1) (f) GDPR)\n- purpose: responding to contact requests\n  text: The acquired data, such as contact details and the content of communications, will be used exclusively to\n    respond to the requests received.\n- purpose: account creation and access\n  text: we process the data necessary to allow you to create and/or access your account\n- purpose: evaluating job applications\n  text: We will process the information contained in the CV and the information you provide us to evaluate your\n    application.\nretention:\n- scope: contact form and communications\n  period: null\n  text: it is deleted when the respective conversation with the user has ended\n- scope: website registration data\n  period: null\n  text: The data related to your website registration will be retained until you request the deletion\
  \ of your profile.\n- scope: job application CV and data\n  period: 12 months\n  text: Your CV and the personal data you provide to us when you send us your application for a job position will\n    be stored for 12 months after the recruitment process, unless you request its deletion earlier.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: A detailed list of all recipients is available at the headquarters of the Data Controller and will be provided\n    upon request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request deletion via info@mitto.ch or dpo@mitto.ch\n  text: To exercise your rights, you can write to the data controller at info@mitto.ch or to the DPO at dpo@mitto.ch\n    .\nrights:\n- right: access\n  text: 'Right of access : You have the right to obtain information regarding the processing of your personal data\n    and to access and receive a copy of it'\n- right: rectification\n  text: 'Right to rectification : You have the\
  \ right to obtain the update, integration, or rectification of data.'\n- right: portability\n  text: 'Right to data portability : You can request the portability of data processed in the context of contract\n    performance or based on your consent'\n- right: erasure\n  text: 'Right to erasure : You have the right to request the deletion of stored data.'\n- right: restriction and objection\n  text: 'Right to restriction and objection : You have the right to request the restriction of processing or to\n    object'\nsale_or_sharing:\n  stance: unstated\n  text: In the past 12 months we have not sold any of your personal information\n"
source_yaml_url: https://artifacts.apis.io/mitto-ch/privacy/mitto-ch-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 21 quoted statements, read from Mitto's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Omnichannel
- Communications
- Enterprise
---
