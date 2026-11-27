---
api_specs:
- filename: zabbix-actions-api-openapi.yml
  format: yaml
  label: Zabbix Actions API
  slug: zabbix-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-actions-api-openapi.yml
- filename: zabbix-authentication-api-openapi.yml
  format: yaml
  label: Zabbix Authentication API
  slug: zabbix-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-authentication-api-openapi.yml
- filename: zabbix-events-api-openapi.yml
  format: yaml
  label: Zabbix Events API
  slug: zabbix-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-events-api-openapi.yml
- filename: zabbix-history-api-openapi.yml
  format: yaml
  label: Zabbix History API
  slug: zabbix-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-history-api-openapi.yml
- filename: zabbix-host-groups-api-openapi.yml
  format: yaml
  label: Zabbix Host Groups API
  slug: zabbix-host-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-host-groups-api-openapi.yml
- filename: zabbix-hosts-api-openapi.yml
  format: yaml
  label: Zabbix Hosts API
  slug: zabbix-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-hosts-api-openapi.yml
- filename: zabbix-items-api-openapi.yml
  format: yaml
  label: Zabbix Items API
  slug: zabbix-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-items-api-openapi.yml
- filename: zabbix-problems-api-openapi.yml
  format: yaml
  label: Zabbix Problems API
  slug: zabbix-problems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-problems-api-openapi.yml
- filename: zabbix-triggers-api-openapi.yml
  format: yaml
  label: Zabbix Triggers API
  slug: zabbix-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-triggers-api-openapi.yml
- filename: zabbix-users-api-openapi.yml
  format: yaml
  label: Zabbix Users API
  slug: zabbix-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zabbix/openapi/zabbix-users-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: e-mail address, name, surname, phone number, work place, tax payer number, etc.
  - category: identifying
    text: The Controller may process the scope of the personal data including both name, surname, and personal identity number, as well as contact information
  - category: financial
    text: payment information arising from the transaction, including the account number and information regarding the credit institution
  - category: communication
    text: Recordings of online meetings may include your name and other identifying information, your voice and, where your camera is enabled, your image
  deletion:
    route: Written request to the Controller's e-mail or registered office
    text: Data Subject is entitled to request deletion of his/her personal data or to object against the processing
  dpa:
    available: null
    text: Microsoft provides hosting and storage services as a processor under the applicable Microsoft Products and Services Data Protection Addendum (DPA)
    url: null
  purposes:
  - purpose: Marketing communications
    text: we may, from time to time, contact you with information about our services and latest offers
  - purpose: Record and store telephone calls and online meetings
    text: We make recordings of telephone conversations and notify caller about it before the call is initiated.
  residency:
  - region: European Union
    text: We store telephone conversation records in a secure manner within the European Union.
  - region: Latvia
    text: Telephone call recordings made through the services provided by our communication solutions provider, SIA "Callgear", a company based in Latvia with registration No. 40203221051, are stored securely and confidentially on servers located in Latvia, Riga.
  retention:
  - period: five years
    scope: Marketing consent information
    text: Consent information can be stored five years from the date of withdrawal of consent.
  - period: 90 (ninety) days
    scope: Telephone call recordings
    text: We shall store phone conversation recordings for no more than 90 (ninety) days from the moment of the conversation.
  - period: 60 (sixty) days
    scope: Microsoft Teams meeting recordings
    text: Microsoft Teams meeting recordings are subject to an automatic expiration period of 60 (sixty) days from their creation.
  rights:
  - right: access
    text: Data Subject is entitled to request from the Controller access to his/her personal data
  - right: correction
    text: the Data Subject is entitled to request the correction of his/her personal data.
  - right: erasure
    text: Data Subject is entitled to request deletion of his/her personal data or to object against the processing
  - right: withdraw consent
    text: Where processing is based on consent, Data Subject are entitled to withdraw the consent given for the data processing at any time
  - right: complaint
    text: Data Subject is entitled to submit a complaint to the Latvian Data State Inspectorate
  role:
    text: The controller of the personal data processing set out in this Privacy Policy is SIA Zabbix
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: The transfer is based on a contract with the processor or subprocessor, to ensure an adequate level of protection of personal data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zabbix
provenance_date: '2026-11-10'
provider_name: Zabbix
provider_slug: zabbix
slug: zabbix-privacy-policy
source_date: '2026-11-10'
source_filename: zabbix-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zabbix.com/privacy_policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zabbix\naid: zabbix\nurl: https://www.zabbix.com/privacy_policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data processing set out in this Privacy Policy is SIA Zabbix\ndata_categories:\n- category: contact\n  text: e-mail address, name, surname, phone number, work place, tax payer number, etc.\n- category: identifying\n  text: The Controller may process the scope of the personal data including both name, surname, and personal identity\n    number, as well as contact information\n- category: financial\n  text: payment information arising from the transaction,\
  \ including the account number and information regarding\n    the credit institution\n- category: communication\n  text: Recordings of online meetings may include your name and other identifying information, your voice and, where\n    your camera is enabled, your image\npurposes:\n- purpose: Marketing communications\n  text: we may, from time to time, contact you with information about our services and latest offers\n- purpose: Record and store telephone calls and online meetings\n  text: We make recordings of telephone conversations and notify caller about it before the call is initiated.\nretention:\n- scope: Marketing consent information\n  period: five years\n  text: Consent information can be stored five years from the date of withdrawal of consent.\n- scope: Telephone call recordings\n  period: 90 (ninety) days\n  text: We shall store phone conversation recordings for no more than 90 (ninety) days from the moment of the conversation.\n- scope: Microsoft Teams meeting recordings\n\
  \  period: 60 (sixty) days\n  text: Microsoft Teams meeting recordings are subject to an automatic expiration period of 60 (sixty) days from\n    their creation.\nresidency:\n- region: European Union\n  text: We store telephone conversation records in a secure manner within the European Union.\n- region: Latvia\n  text: Telephone call recordings made through the services provided by our communication solutions provider, SIA\n    \"Callgear\", a company based in Latvia with registration No. 40203221051, are stored securely and confidentially\n    on servers located in Latvia, Riga.\ntransfers:\n- mechanism: other\n  text: The transfer is based on a contract with the processor or subprocessor, to ensure an adequate level of protection\n    of personal data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Microsoft provides hosting and storage services as a processor under the applicable Microsoft Products and\n    Services Data Protection Addendum\
  \ (DPA)\ndeletion:\n  route: Written request to the Controller's e-mail or registered office\n  text: Data Subject is entitled to request deletion of his/her personal data or to object against the processing\nrights:\n- right: access\n  text: Data Subject is entitled to request from the Controller access to his/her personal data\n- right: correction\n  text: the Data Subject is entitled to request the correction of his/her personal data.\n- right: erasure\n  text: Data Subject is entitled to request deletion of his/her personal data or to object against the processing\n- right: withdraw consent\n  text: Where processing is based on consent, Data Subject are entitled to withdraw the consent given for the data\n    processing at any time\n- right: complaint\n  text: Data Subject is entitled to submit a complaint to the Latvian Data State Inspectorate\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zabbix/privacy/zabbix-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 20 quoted statements, read from Zabbix's own page on 2026-11-10.
synthetic: false
tags:
- Monitoring
- Infrastructure
- Networks
- Alerting
- Open Source
- Observability
---
