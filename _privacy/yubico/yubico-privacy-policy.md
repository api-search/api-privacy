---
api_specs:
- filename: yubico-validation-api-openapi.yml
  format: yaml
  label: Yubico Validation API
  slug: yubico-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yubico/openapi/yubico-validation-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Examples of such data are name, email address, government issued identification number, billing information, contact details, IP address and user behavior.
  - category: communication
    text: we may process information you have volunteered, such as name, home and/or delivery address, telephone number, e-mail address, payment information, historical order information and product you bought.
  - category: device
    text: We also automatically receive and store information from your web browser, such as IP address, language preferences cookie information and the pages you visit
  deletion:
    route: contact Yubico via the contact details listed below
    text: to request that we shall stop processing and delete your personal data
  dpa:
    available: null
    text: Companies that process personal data on our behalf must always sign an agreement with us so that we are able to ensure a high level of protection of your personal data even with our partners.
    url: null
  purposes:
  - purpose: respond to requests and improve websites
    text: We use the information collected to respond to your requests regarding products and services, to improve the content on our websites and the services, to track and prevent abuse of our websites and services, and to develop anonymous usage statistics.
  - purpose: direct marketing
    text: We also use personal data for direct marketing and advertising in accordance with applicable law and market practice.
  - purpose: AI-assisted customer support
    text: to understand and respond to your request, to escalate the request to a human agent where necessary, and to improve the quality and accuracy of our support services.
  retention:
  - period: null
    scope: collected personal data
    text: We delete collected personal data when the purpose of the processing has been completed.
  - period: null
    scope: bookkeeping data
    text: Some of this information is retained for the duration required by applicable bookkeeping legislation.
  - period: null
    scope: AI Assistant conversations
    text: Conversations with the AI Assistant may be logged and retained for quality assurance, training, and improvement of our support tools, and to maintain a record of your support case.
  rights:
  - right: access
    text: request access to the personal data that is processed about you
  - right: correction
    text: to have erroneous personal data corrected
  - right: deletion
    text: to request that we shall stop processing and delete your personal data
  - right: restriction
    text: to request that the processing of your personal data is restricted
  - right: portability
    text: to exercise your right to data portability
  - right: objection
    text: to object to the processing of your personal data
  role:
    text: Yubico AB or the specific Yubico Group company providing services (as identified when your personal data is collected) acts as the data controller.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: like the standardized model clauses for data transfers adopted by the EU Commission, which are available on the EU Commission’s website, or the ASEAN model contractual clauses for data transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yubico
provenance_date: '2026-11-10'
provider_name: Yubico
provider_slug: yubico
slug: yubico-privacy-policy
source_date: '2026-11-10'
source_filename: yubico-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.yubico.com/support/terms-conditions/privacy-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yubico\naid: yubico\nurl: https://www.yubico.com/support/terms-conditions/privacy-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Yubico AB or the specific Yubico Group company providing services (as identified when your personal data\n    is collected) acts as the data controller.\ndata_categories:\n- category: identifying\n  text: Examples of such data are name, email address, government issued identification number, billing information,\n    contact details, IP address and user behavior.\n- category: communication\n  text: we may process information you have volunteered, such as\
  \ name, home and/or delivery address, telephone number,\n    e-mail address, payment information, historical order information and product you bought.\n- category: device\n  text: We also automatically receive and store information from your web browser, such as IP address, language\n    preferences cookie information and the pages you visit\npurposes:\n- purpose: respond to requests and improve websites\n  text: We use the information collected to respond to your requests regarding products and services, to improve\n    the content on our websites and the services, to track and prevent abuse of our websites and services, and to\n    develop anonymous usage statistics.\n- purpose: direct marketing\n  text: We also use personal data for direct marketing and advertising in accordance with applicable law and market\n    practice.\n- purpose: AI-assisted customer support\n  text: to understand and respond to your request, to escalate the request to a human agent where necessary, and\n    to\
  \ improve the quality and accuracy of our support services.\nretention:\n- scope: collected personal data\n  period: null\n  text: We delete collected personal data when the purpose of the processing has been completed.\n- scope: bookkeeping data\n  period: null\n  text: Some of this information is retained for the duration required by applicable bookkeeping legislation.\n- scope: AI Assistant conversations\n  period: null\n  text: Conversations with the AI Assistant may be logged and retained for quality assurance, training, and improvement\n    of our support tools, and to maintain a record of your support case.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: like the standardized model clauses for data transfers adopted by the EU Commission, which are available\n    on the EU Commission’s website, or the ASEAN model contractual clauses for data transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Companies that process personal data\
  \ on our behalf must always sign an agreement with us so that we are\n    able to ensure a high level of protection of your personal data even with our partners.\ndeletion:\n  route: contact Yubico via the contact details listed below\n  text: to request that we shall stop processing and delete your personal data\nrights:\n- right: access\n  text: request access to the personal data that is processed about you\n- right: correction\n  text: to have erroneous personal data corrected\n- right: deletion\n  text: to request that we shall stop processing and delete your personal data\n- right: restriction\n  text: to request that the processing of your personal data is restricted\n- right: portability\n  text: to exercise your right to data portability\n- right: objection\n  text: to object to the processing of your personal data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yubico/privacy/yubico-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 19 quoted statements, read from Yubico's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Authentication
- Security
- Identity
- Hardware Security
- FIDO2
- WebAuthn
- One-Time Password
---
