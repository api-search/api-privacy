---
api_specs:
- filename: dopesecurity-authorization-api-openapi.yml
  format: yaml
  label: dope.security Authorization API
  slug: dopesecurity-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-authorization-api-openapi.yml
- filename: dopesecurity-custom-categories-api-openapi.yml
  format: yaml
  label: dope.security Custom Categories API
  slug: dopesecurity-custom-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-custom-categories-api-openapi.yml
- filename: dopesecurity-endpoints-api-openapi.yml
  format: yaml
  label: dope.security Endpoints API
  slug: dopesecurity-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-endpoints-api-openapi.yml
- filename: dopesecurity-policies-api-openapi.yml
  format: yaml
  label: dope.security Policies API
  slug: dopesecurity-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dopesecurity/openapi/dopesecurity-policies-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Registration Data may consist of the name, email address, and other contact information
  - category: behavioral
    text: Information about your interactions with the Services, most commonly our website, which includes the date and time of any requests you make.
  - category: device
    text: unique device IDs, device attributes, network connection type (e.g. WiFi, 4G, LTE, Bluetooth) and provider, network and device performance, browser type, language
  - category: location
    text: location of a device being used by a user
  - category: financial
    text: Payment Data is the information necessary to process your payments for the Services.
  - category: communication
    text: messages you send or receive via the Services and your interactions with us, but not including the content of those interactions and messages
  deletion:
    route: Contact legal@dope.security
    text: If you would like to access your information, if you have any questions, comments, or suggestions or if you find any errors in our information about you, please contact us at legal@dope.security .
  dpa:
    available: true
    text: You will find a cover letter and data processing agreement at https://dope.security/legal .
    url: https://dope.security/legal
  purposes:
  - purpose: Provide the Services
    text: We use Registration Data to provide the Services to you.
  - purpose: Improve the Services
    text: We may use Usage Data to make improvements to the Services.
  - purpose: Facilitate payment
    text: We only use Payment Data to facilitate payment, and we only communicate it to those parties who are strictly necessary for that purpose.
  - purpose: Marketing own goods or services
    text: We may also use your Registration Data to offer our own goods or services to you, either directly through emails or through third-party platforms, but you may opt out of those communications at any time.
  residency:
  - region: United States
    text: We are based in California, USA. However, due to the nature of our Services, we may process your Data throughout the world.
  retention:
  - period: null
    scope: Data generally
    text: We will keep your Data for as long as it remains necessary for the identified purpose or as required by law, which may extend beyond the termination of our relationship with you.
  rights:
  - right: Access, correct, update, or request deletion
    text: The right to access, correct, update, or request deletion of your Data.
  - right: Object or restrict processing
    text: The right to object to processing or restrict the processing of your Data
  - right: Portability
    text: The right to request portability of your Data.
  - right: Opt-out of marketing
    text: The right to opt-out of marketing communications we send you.
  - right: Complaint to regulator
    text: The right to submit a complaint to any applicable regulatory authority about our processing activities.
  - right: Opt-out of sharing (CPRA)
    text: The right to opt-out of us sharing (as defined in the CPRA) your Data
  role:
    text: Due to the nature of our Services, we act as a “Processor” as defined under the GDPR.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We never sell your Data, and we always have a lawful basis for gathering the Data
  subprocessors:
    text: we may share your Registration Data with our service providers, referenced at https://dope.security/legal
    url: https://dope.security/legal
  transfers:
  - mechanism: other
    text: By accessing or using the Services or otherwise providing information to us, you understand that your information will be subject to processing, transfer, and storage in and to the United States and other regions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: dope.security
provenance_date: '2026-11-09'
provider_name: dope.security
provider_slug: dopesecurity
slug: dopesecurity-privacy-policy
source_date: '2026-11-09'
source_filename: dopesecurity-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dope.security/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: dope.security\naid: dopesecurity\nurl: https://dope.security/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Due to the nature of our Services, we act as a “Processor” as defined under the GDPR.\ndata_categories:\n- category: identifying\n  text: Registration Data may consist of the name, email address, and other contact information\n- category: behavioral\n  text: Information about your interactions with the Services, most commonly our website, which includes the date\n    and time of any requests you make.\n- category: device\n  text: unique device IDs, device attributes,\
  \ network connection type (e.g. WiFi, 4G, LTE, Bluetooth) and provider,\n    network and device performance, browser type, language\n- category: location\n  text: location of a device being used by a user\n- category: financial\n  text: Payment Data is the information necessary to process your payments for the Services.\n- category: communication\n  text: messages you send or receive via the Services and your interactions with us, but not including the content\n    of those interactions and messages\npurposes:\n- purpose: Provide the Services\n  text: We use Registration Data to provide the Services to you.\n- purpose: Improve the Services\n  text: We may use Usage Data to make improvements to the Services.\n- purpose: Facilitate payment\n  text: We only use Payment Data to facilitate payment, and we only communicate it to those parties who are strictly\n    necessary for that purpose.\n- purpose: Marketing own goods or services\n  text: We may also use your Registration Data to offer\
  \ our own goods or services to you, either directly through\n    emails or through third-party platforms, but you may opt out of those communications at any time.\nretention:\n- scope: Data generally\n  period: null\n  text: We will keep your Data for as long as it remains necessary for the identified purpose or as required by\n    law, which may extend beyond the termination of our relationship with you.\nresidency:\n- region: United States\n  text: We are based in California, USA. However, due to the nature of our Services, we may process your Data throughout\n    the world.\ntransfers:\n- mechanism: other\n  text: By accessing or using the Services or otherwise providing information to us, you understand that your information\n    will be subject to processing, transfer, and storage in and to the United States and other regions.\nsubprocessors:\n  url: https://dope.security/legal\n  text: we may share your Registration Data with our service providers, referenced at https://dope.security/legal\n\
  dpa:\n  available: true\n  url: https://dope.security/legal\n  text: You will find a cover letter and data processing agreement at https://dope.security/legal .\ndeletion:\n  route: Contact legal@dope.security\n  text: If you would like to access your information, if you have any questions, comments, or suggestions or if\n    you find any errors in our information about you, please contact us at legal@dope.security .\nrights:\n- right: Access, correct, update, or request deletion\n  text: The right to access, correct, update, or request deletion of your Data.\n- right: Object or restrict processing\n  text: The right to object to processing or restrict the processing of your Data\n- right: Portability\n  text: The right to request portability of your Data.\n- right: Opt-out of marketing\n  text: The right to opt-out of marketing communications we send you.\n- right: Complaint to regulator\n  text: The right to submit a complaint to any applicable regulatory authority about our processing\
  \ activities.\n- right: Opt-out of sharing (CPRA)\n  text: The right to opt-out of us sharing (as defined in the CPRA) your Data\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your Data, and we always have a lawful basis for gathering the Data\n"
source_yaml_url: https://artifacts.apis.io/dopesecurity/privacy/dopesecurity-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from dope.security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Security
- Cybersecurity
- Secure Web Gateway
- SASE
- SSE
- Data Loss Prevention
- CASB
- Endpoint Security
---
