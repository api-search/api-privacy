---
api_specs:
- filename: algoum-de-common-api-openapi.yml
  format: yaml
  label: algoum-de Common API
  slug: algoum-de-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-common-api-openapi.yml
- filename: algoum-de-events-api-openapi.yml
  format: yaml
  label: algoum-de Events API
  slug: algoum-de-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-events-api-openapi.yml
- filename: algoum-de-insider-api-openapi.yml
  format: yaml
  label: algoum-de Insider API
  slug: algoum-de-insider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-insider-api-openapi.yml
- filename: algoum-de-institutional-api-openapi.yml
  format: yaml
  label: algoum-de Institutional API
  slug: algoum-de-institutional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algoum-de/openapi/algoum-de-institutional-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Password (in encrypted form) Phone number First name, last name, nickname, display name Gender
  - category: device
    text: API key (in encrypted form) Timestamp of API key creation
  - category: financial
    text: personal data required for payment processing and invoicing (e.g., name, billing address, payment details, transaction IDs) will be processed
  - category: professional
    text: including personal data of corporate officers, directors, and major shareholders that have been made public pursuant to statutory disclosure requirements
  - category: communication
    text: Personal data transmitted in the context of a request (name, email address, subject and content of the request)
  deletion:
    route: Delete account or API key
    text: The user can delete their API key at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and processing capital market data
    text: legitimate interest in providing and processing publicly accessible capital market data
  - purpose: User registration and service use
    text: Art. 6(1)(b) GDPR (performance of a contract / use of the service)
  - purpose: Processing support inquiries
    text: Personal data transmitted in the context of a request (name, email address, subject and content of the request) is used solely to process the inquiry.
  - purpose: Spam and misuse prevention on contact form
    text: The IP address the message was submitted from is included in that email and serves solely to identify and prevent misuse of the form (Art. 6(1)(f) GDPR).
  residency:
  - region: European Union
    text: Personal user data is stored and processed on servers located within the European Union.
  retention:
  - period: null
    scope: User data
    text: Personal user data is erased as soon as it is no longer required for the provision of the service or when the user deletes their account, provided that no statutory retention obligations prevent such erasure.
  - period: null
    scope: Contact form messages
    text: Such messages are erased once the inquiry has been dealt with, provided that no statutory retention obligations prevent such erasure.
  rights:
  - right: Access
    text: to obtain access to their stored personal data (Art. 15 GDPR)
  - right: Rectification
    text: to request the rectification of inaccurate data (Art. 16 GDPR)
  - right: Erasure
    text: to request erasure (“right to be forgotten”, Art. 17 GDPR)
  - right: Restriction
    text: to request restriction of processing (Art. 18 GDPR)
  - right: Objection
    text: to object to processing (Art. 21 GDPR)
  - right: Portability
    text: to data portability (Art. 20 GDPR)
  role:
    text: 'The controller responsible for the processing of personal data within the scope of this online service is: Vladislav Kravitski Schwalbenplatz 15, Hamburg, Germany'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: algoum-de
provenance_date: '2026-11-09'
provider_name: Algoum
provider_slug: algoum-de
slug: algoum-de-privacy-policy
source_date: '2026-11-09'
source_filename: algoum-de-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://algoum.de/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: algoum-de\naid: algoum-de\nurl: https://algoum.de/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller responsible for the processing of personal data within the scope of this online service\n    is: Vladislav Kravitski Schwalbenplatz 15, Hamburg, Germany'\ndata_categories:\n- category: identifying\n  text: Email address Password (in encrypted form) Phone number First name, last name, nickname, display name Gender\n- category: device\n  text: API key (in encrypted form) Timestamp of API key creation\n- category: financial\n  text: personal data required for payment\
  \ processing and invoicing (e.g., name, billing address, payment details,\n    transaction IDs) will be processed\n- category: professional\n  text: including personal data of corporate officers, directors, and major shareholders that have been made public\n    pursuant to statutory disclosure requirements\n- category: communication\n  text: Personal data transmitted in the context of a request (name, email address, subject and content of the request)\npurposes:\n- purpose: Providing and processing capital market data\n  text: legitimate interest in providing and processing publicly accessible capital market data\n- purpose: User registration and service use\n  text: Art. 6(1)(b) GDPR (performance of a contract / use of the service)\n- purpose: Processing support inquiries\n  text: Personal data transmitted in the context of a request (name, email address, subject and content of the request)\n    is used solely to process the inquiry.\n- purpose: Spam and misuse prevention on contact form\n\
  \  text: The IP address the message was submitted from is included in that email and serves solely to identify and\n    prevent misuse of the form (Art. 6(1)(f) GDPR).\nretention:\n- scope: User data\n  period: null\n  text: Personal user data is erased as soon as it is no longer required for the provision of the service or when\n    the user deletes their account, provided that no statutory retention obligations prevent such erasure.\n- scope: Contact form messages\n  period: null\n  text: Such messages are erased once the inquiry has been dealt with, provided that no statutory retention obligations\n    prevent such erasure.\nresidency:\n- region: European Union\n  text: Personal user data is stored and processed on servers located within the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account or API key\n  text: The user can delete their API key at any time.\nrights:\n- right:\
  \ Access\n  text: to obtain access to their stored personal data (Art. 15 GDPR)\n- right: Rectification\n  text: to request the rectification of inaccurate data (Art. 16 GDPR)\n- right: Erasure\n  text: to request erasure (“right to be forgotten”, Art. 17 GDPR)\n- right: Restriction\n  text: to request restriction of processing (Art. 18 GDPR)\n- right: Objection\n  text: to object to processing (Art. 21 GDPR)\n- right: Portability\n  text: to data portability (Art. 20 GDPR)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/algoum-de/privacy/algoum-de-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 20 quoted statements, read from algoum-de's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- SEC
- Insider Trading
---
