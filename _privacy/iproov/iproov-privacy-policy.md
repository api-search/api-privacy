---
api_specs:
- filename: iproov-enrol-api-openapi.yml
  format: yaml
  label: iProov Enrol API
  slug: iproov-enrol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iproov/openapi/iproov-enrol-api-openapi.yml
- filename: iproov-management-api-openapi.yml
  format: yaml
  label: iProov Management API
  slug: iproov-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iproov/openapi/iproov-management-api-openapi.yml
- filename: iproov-user-api-openapi.yml
  format: yaml
  label: iProov User API
  slug: iproov-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iproov/openapi/iproov-user-api-openapi.yml
- filename: iproov-verify-api-openapi.yml
  format: yaml
  label: iProov Verify API
  slug: iproov-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iproov/openapi/iproov-verify-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your name, contact details, and details about your interactions on IProov Sites
  - category: contact
    text: your name, contact details
  - category: behavioral
    text: information collected automatically, through the use of cookies and other tracking technologies
  - category: communication
    text: records of your interactions with us (for example if you contact a member of our team or interact with us through social media
  - category: other
    text: preferences for the marketing you wish to receive from us and your communication preferences concerning that marketing
  deletion:
    route: erasure request
    text: Request erasure of your personal information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: personalised experience
    text: to provide a personalised experience on the iProov Sites
  - purpose: customer service
    text: to manage and respond to any queries you may raise with our customer service team
  - purpose: market research
    text: conducting market research
  - purpose: marketing
    text: to send you marketing messages and show you targeted content or advertising
  - purpose: legal compliance
    text: to comply with our legal and regulatory obligations
  retention:
  - period: null
    scope: personal information generally
    text: We will keep your personal information for as long as necessary for the purposes stated.
  - period: null
    scope: end of need
    text: Upon conclusion of the need for your personal data, we either delete or anonymise it.
  rights:
  - right: access
    text: Request access to your personal information (commonly known as a data subject access request).
  - right: correction
    text: Request correction of your personal information that we hold about you.
  - right: erasure
    text: Request erasure of your personal information.
  - right: objection
    text: Object to processing of your personal information where we are relying on our legitimate interests
  - right: restriction
    text: Request restriction of processing of your personal information.
  - right: portability
    text: Request the transfer of your personal information to you or to a third party.
  - right: withdraw consent
    text: Withdraw consent to the processing of your personal information
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
    text: iProov relies on Article 49 of the GDPR as the basis for such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: iProov
provenance_date: '2026-11-09'
provider_name: iProov
provider_slug: iproov
slug: iproov-privacy-policy
source_date: '2026-11-09'
source_filename: iproov-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.iproov.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: iProov\naid: iproov\nurl: https://www.iproov.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: such as your name, contact details, and details about your interactions on IProov Sites\n- category: contact\n  text: your name, contact details\n- category: behavioral\n  text: information collected automatically, through the use of cookies and other tracking technologies\n- category: communication\n  text: records of your interactions with us (for example if you contact a member of our team or interact with us\n    through social\
  \ media\n- category: other\n  text: preferences for the marketing you wish to receive from us and your communication preferences concerning\n    that marketing\npurposes:\n- purpose: personalised experience\n  text: to provide a personalised experience on the iProov Sites\n- purpose: customer service\n  text: to manage and respond to any queries you may raise with our customer service team\n- purpose: market research\n  text: conducting market research\n- purpose: marketing\n  text: to send you marketing messages and show you targeted content or advertising\n- purpose: legal compliance\n  text: to comply with our legal and regulatory obligations\nretention:\n- scope: personal information generally\n  period: null\n  text: We will keep your personal information for as long as necessary for the purposes stated.\n- scope: end of need\n  period: null\n  text: Upon conclusion of the need for your personal data, we either delete or anonymise it.\nresidency: []\ntransfers:\n- mechanism: other\n\
  \  text: iProov relies on Article 49 of the GDPR as the basis for such transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: erasure request\n  text: Request erasure of your personal information.\nrights:\n- right: access\n  text: Request access to your personal information (commonly known as a data subject access request).\n- right: correction\n  text: Request correction of your personal information that we hold about you.\n- right: erasure\n  text: Request erasure of your personal information.\n- right: objection\n  text: Object to processing of your personal information where we are relying on our legitimate interests\n- right: restriction\n  text: Request restriction of processing of your personal information.\n- right: portability\n  text: Request the transfer of your personal information to you or to a third party.\n- right: withdraw consent\n  text: Withdraw consent to the processing of your personal information\n\
  sale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iproov/privacy/iproov-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from iProov's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biometrics
- Identity Verification
- Authentication
- Liveness Detection
- Face Verification
- Fraud Prevention
- Deepfake Detection
---
