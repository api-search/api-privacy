---
api_specs:
- filename: riskified-automation-endpoints-api-openapi.yml
  format: yaml
  label: Riskified Automation Endpoints API
  slug: riskified-automation-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-automation-endpoints-api-openapi.yml
- filename: riskified-customer-actions-api-openapi.yml
  format: yaml
  label: Riskified Customer Actions API
  slug: riskified-customer-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-customer-actions-api-openapi.yml
- filename: riskified-customer-management-api-openapi.yml
  format: yaml
  label: Riskified Customer Management API
  slug: riskified-customer-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-customer-management-api-openapi.yml
- filename: riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api-openapi.yml
  format: yaml
  label: Riskified Order Pre-Auth Review and PSD2/3DS/CVV Recommendations API
  slug: riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api-openapi.yml
- filename: riskified-otp-recover-sync-flow-api-openapi.yml
  format: yaml
  label: Riskified OTP Recover (Sync flow) API
  slug: riskified-otp-recover-sync-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-otp-recover-sync-flow-api-openapi.yml
- filename: riskified-post-authorization-flow-api-openapi.yml
  format: yaml
  label: Riskified Post-Authorization Flow API
  slug: riskified-post-authorization-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-post-authorization-flow-api-openapi.yml
- filename: riskified-pre-authorization-flow-api-openapi.yml
  format: yaml
  label: Riskified Pre-Authorization Flow API
  slug: riskified-pre-authorization-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-pre-authorization-flow-api-openapi.yml
- filename: riskified-refunds-api-openapi.yml
  format: yaml
  label: Riskified Refunds API
  slug: riskified-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-refunds-api-openapi.yml
- filename: riskified-returns-api-openapi.yml
  format: yaml
  label: Riskified Returns API
  slug: riskified-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riskified/openapi/riskified-returns-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your name, email, address, phone number
  - category: contact
    text: identifiers such as your name, email address, postal address, telephone number and other contact information
  - category: financial
    text: payment method, billing method, shipping information
  - category: device
    text: This includes, for example, the device model, operating system, unique identifiers, browser type
  - category: location
    text: information about your device’s general location
  - category: behavioral
    text: We collect analytical data about your use of the Merchant Website.
  - category: other
    text: Depending on your interactions with certain Merchants, we may collect personal data that is considered sensitive under certain applicable laws.
  deletion:
    route: data deletion request
    text: Personal data may be deleted earlier subject to contractual agreements with Merchants or pursuant to a data deletion request.
  dpa:
    available: true
    text: 'Riskified shall process personal data in accordance with the Data Processing Addendum, available at: https://security.riskified.com/'
    url: https://security.riskified.com/
  purposes:
  - purpose: Providing Services with AI fraud analysis
    text: Providing our Services, including through use of Artificial Intelligence (AI) systems that support our fraud analysis services
  - purpose: Improving services and developing new services
    text: Improving and enhancing Services and developing new services
  residency:
  - region: United States, European Union, Israel and other countries
    text: we may store and process your information in the United States, the European Union, Israel and in other countries.
  retention:
  - period: up to 48 months
    scope: personal data
    text: up to 48 months from when such personal data was received by us.
  rights:
  - right: access, correction and deletion
    text: you may request to access, correct or delete your personal data that is stored in our systems
  - right: objection
    text: object to the processing of your personal data
  - right: restriction of processing
    text: request restriction of processing of your personal data
  - right: portability
    text: You may also be entitled to obtain personal data that you directly provided us and have the right to transmit it to another party.
  - right: complaint to supervisory authority
    text: you have the right to lodge your complaint with a supervisory authority.
  role:
    text: As a Data Controller, we rely on our legitimate interests to process your information
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Adequacy Decisions, as adopted by the European Commission (EC) based on Article 45 of General Data Protection Regulation
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) and the UK Information Commissioner’s Office’s International Data Transfer Addendum (IDTA), as applicable
  - mechanism: DPF
    text: adheres to and is covered by Riskified’s submission to the EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Riskified
provenance_date: '2026-11-10'
provider_name: Riskified
provider_slug: riskified
slug: riskified-privacy-policy
source_date: '2026-11-10'
source_filename: riskified-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.riskified.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Riskified\naid: riskified\nurl: https://www.riskified.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: As a Data Controller, we rely on our legitimate interests to process your information\ndata_categories:\n- category: identifying\n  text: such as your name, email, address, phone number\n- category: contact\n  text: identifiers such as your name, email address, postal address, telephone number and other contact information\n- category: financial\n  text: payment method, billing method, shipping information\n- category: device\n  text: This includes, for example, the\
  \ device model, operating system, unique identifiers, browser type\n- category: location\n  text: information about your device’s general location\n- category: behavioral\n  text: We collect analytical data about your use of the Merchant Website.\n- category: other\n  text: Depending on your interactions with certain Merchants, we may collect personal data that is considered sensitive\n    under certain applicable laws.\npurposes:\n- purpose: Providing Services with AI fraud analysis\n  text: Providing our Services, including through use of Artificial Intelligence (AI) systems that support our fraud\n    analysis services\n- purpose: Improving services and developing new services\n  text: Improving and enhancing Services and developing new services\nretention:\n- scope: personal data\n  period: up to 48 months\n  text: up to 48 months from when such personal data was received by us.\nresidency:\n- region: United States, European Union, Israel and other countries\n  text: we may store and\
  \ process your information in the United States, the European Union, Israel and in other\n    countries.\ntransfers:\n- mechanism: adequacy\n  text: Adequacy Decisions, as adopted by the European Commission (EC) based on Article 45 of General Data Protection\n    Regulation\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) and the UK Information Commissioner’s Office’s International Data Transfer\n    Addendum (IDTA), as applicable\n- mechanism: DPF\n  text: adheres to and is covered by Riskified’s submission to the EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://security.riskified.com/\n  text: 'Riskified shall process personal data in accordance with the Data Processing Addendum, available at: https://security.riskified.com/'\ndeletion:\n  route: data deletion request\n  text: Personal data may be deleted earlier subject to contractual agreements with Merchants or pursuant to a data\n    deletion request.\n\
  rights:\n- right: access, correction and deletion\n  text: you may request to access, correct or delete your personal data that is stored in our systems\n- right: objection\n  text: object to the processing of your personal data\n- right: restriction of processing\n  text: request restriction of processing of your personal data\n- right: portability\n  text: You may also be entitled to obtain personal data that you directly provided us and have the right to transmit\n    it to another party.\n- right: complaint to supervisory authority\n  text: you have the right to lodge your complaint with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/riskified/privacy/riskified-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Riskified's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Chargebacks
- E-Commerce
- Payments
- Risk Management
- Machine Learning
- Account Takeover
- Policy Abuse
- 3D
- PSD2
- Returns
---
