---
api_specs:
- filename: gbg-as-api-openapi.yml
  format: yaml
  label: GBG As API
  slug: gbg-as-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-as-api-openapi.yml
- filename: gbg-authentication-api-openapi.yml
  format: yaml
  label: GBG Authentication API
  slug: gbg-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-authentication-api-openapi.yml
- filename: gbg-customer-apis-api-openapi.yml
  format: yaml
  label: GBG Customer APIs API
  slug: gbg-customer-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-customer-apis-api-openapi.yml
- filename: gbg-device-api-openapi.yml
  format: yaml
  label: GBG Device API
  slug: gbg-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-device-api-openapi.yml
- filename: gbg-end-user-apis-api-openapi.yml
  format: yaml
  label: GBG End User APIs API
  slug: gbg-end-user-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-end-user-apis-api-openapi.yml
- filename: gbg-health-api-openapi.yml
  format: yaml
  label: GBG Health API
  slug: gbg-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-health-api-openapi.yml
- filename: gbg-interaction-api-openapi.yml
  format: yaml
  label: GBG Interaction API
  slug: gbg-interaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-interaction-api-openapi.yml
- filename: gbg-interaction-service-api-openapi.yml
  format: yaml
  label: GBG Interaction Service API
  slug: gbg-interaction-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-interaction-service-api-openapi.yml
- filename: gbg-journey-api-openapi.yml
  format: yaml
  label: GBG Journey API
  slug: gbg-journey-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-journey-api-openapi.yml
- filename: gbg-journey-execution-api-openapi.yml
  format: yaml
  label: GBG Journey execution API
  slug: gbg-journey-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-journey-execution-api-openapi.yml
- filename: gbg-sandbox-api-openapi.yml
  format: yaml
  label: GBG Sandbox API
  slug: gbg-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gbg/openapi/gbg-sandbox-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact Information Full name, email address, mailing address, employer or company name, job title, phone number
  - category: financial
    text: account balances, payment and purchase history information
  - category: behavioral
    text: including browsing history, search history, interaction with an internet-based application
  - category: device
    text: Technical Information Any identifiers, including unique personal identifier, online identifier, Internet Protocol address
  - category: other
    text: Audio, electronic, visual, thermal, olfactory, or similar information , such as photographs, video recordings and voice recordings
  deletion:
    route: webform
    text: Please use our webform
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Performing services
    text: 'Performing Services : Providing our services'
  - purpose: Marketing
    text: 'Marketing : Marketing purposes, such as developing and providing promotional and advertising materials'
  - purpose: Fraud and incident prevention
    text: 'Fraud and Incident Prevention : Detecting security incidents, preventing and protecting against malicious, deceptive, fraudulent, or illegal activity'
  - purpose: Legal and compliance obligations
    text: 'Legal and Compliance Obligations : For complying with our legal obligations'
  - purpose: Training and coaching
    text: Some calls are recorded and are used to ensure GBG’s team deliver an excellent experience for our customers.
  retention:
  - period: null
    scope: Marketing
    text: You can opt-out at any time by clicking the unsubscribe link in the email or contacting Privacy.Rights@gbg.com
  - period: 6 months
    scope: Prospecting
    text: If there is no interaction, we will delete this record after 6 months.
  - period: 6 years
    scope: Account management
    text: for audit purposes for 6 years
  - period: 30 calendar days
    scope: CCTV
    text: Generally, recordings will be retained for up to 30 calendar days, after which they will be deleted.
  rights:
  - right: Access/know
    text: The right to access/know your personal data
  - right: Portability
    text: The right to data portability
  - right: Erasure/delete
    text: The right to erasure/delete
  - right: Withdraw consent
    text: The right to withdraw consent
  - right: Object to processing
    text: The right to object to processing
  - right: Opt-out of sale
    text: The right to opt-out of sale of your personal data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any of the categories of personal information
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: implementing the European Commission’s Standard Contractual Clauses
  - mechanism: other
    text: the UK International Data Transfer Agreement for international data transfers between our group companies
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GBG
provenance_date: '2026-11-09'
provider_name: GBG
provider_slug: gbg
slug: gbg-privacy-policy
source_date: '2026-11-09'
source_filename: gbg-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.gbgplc.com/legal-and-regulatory/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GBG\naid: gbg\nurl: https://www.gbgplc.com/legal-and-regulatory/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact Information Full name, email address, mailing address, employer or company name, job title, phone\n    number\n- category: financial\n  text: account balances, payment and purchase history information\n- category: behavioral\n  text: including browsing history, search history, interaction with an internet-based application\n- category: device\n  text: Technical Information Any identifiers, including unique\
  \ personal identifier, online identifier, Internet\n    Protocol address\n- category: other\n  text: Audio, electronic, visual, thermal, olfactory, or similar information , such as photographs, video recordings\n    and voice recordings\npurposes:\n- purpose: Performing services\n  text: 'Performing Services : Providing our services'\n- purpose: Marketing\n  text: 'Marketing : Marketing purposes, such as developing and providing promotional and advertising materials'\n- purpose: Fraud and incident prevention\n  text: 'Fraud and Incident Prevention : Detecting security incidents, preventing and protecting against malicious,\n    deceptive, fraudulent, or illegal activity'\n- purpose: Legal and compliance obligations\n  text: 'Legal and Compliance Obligations : For complying with our legal obligations'\n- purpose: Training and coaching\n  text: Some calls are recorded and are used to ensure GBG’s team deliver an excellent experience for our customers.\nretention:\n- scope: Marketing\n  period:\
  \ null\n  text: You can opt-out at any time by clicking the unsubscribe link in the email or contacting Privacy.Rights@gbg.com\n- scope: Prospecting\n  period: 6 months\n  text: If there is no interaction, we will delete this record after 6 months.\n- scope: Account management\n  period: 6 years\n  text: for audit purposes for 6 years\n- scope: CCTV\n  period: 30 calendar days\n  text: Generally, recordings will be retained for up to 30 calendar days, after which they will be deleted.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: implementing the European Commission’s Standard Contractual Clauses\n- mechanism: other\n  text: the UK International Data Transfer Agreement for international data transfers between our group companies\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: webform\n  text: Please use our webform\nrights:\n- right: Access/know\n  text: The right to access/know your personal data\n- right: Portability\n\
  \  text: The right to data portability\n- right: Erasure/delete\n  text: The right to erasure/delete\n- right: Withdraw consent\n  text: The right to withdraw consent\n- right: Object to processing\n  text: The right to object to processing\n- right: Opt-out of sale\n  text: The right to opt-out of sale of your personal data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any of the categories of personal information\n"
source_yaml_url: https://artifacts.apis.io/gbg/privacy/gbg-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from GBG's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity Verification
- Fraud Prevention
- KYC
- Location Intelligence
- Compliance
- Digital Identity
---
