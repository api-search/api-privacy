---
api_specs:
- filename: seon-tech-aml-api-openapi.yml
  format: yaml
  label: SEON AML API
  slug: seon-tech-aml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-aml-api-openapi.yml
- filename: seon-tech-bin-api-openapi.yml
  format: yaml
  label: SEON BIN API
  slug: seon-tech-bin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-bin-api-openapi.yml
- filename: seon-tech-email-api-openapi.yml
  format: yaml
  label: SEON Email API
  slug: seon-tech-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-email-api-openapi.yml
- filename: seon-tech-fraud-api-openapi.yml
  format: yaml
  label: SEON Fraud API
  slug: seon-tech-fraud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-fraud-api-openapi.yml
- filename: seon-tech-ip-api-openapi.yml
  format: yaml
  label: SEON IP API
  slug: seon-tech-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-ip-api-openapi.yml
- filename: seon-tech-phone-api-openapi.yml
  format: yaml
  label: SEON Phone API
  slug: seon-tech-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-phone-api-openapi.yml
- filename: seon-tech-labels-api-openapi.yml
  format: yaml
  label: SEON Labels API
  slug: seon-tech-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seon-tech/openapi/seon-tech-labels-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Personal data provided by you, for example, contact details, information necessary to create an account, information related to the usage of the services, and communication-related to the services.
  - category: financial
    text: information necessary for billing
  - category: behavioral
    text: data collected via cookies
  - category: identifying
    text: identifiers that you submit to us through forms on our Website (such as your email address, phone number and name)
  deletion:
    route: request to SEON contact
    text: You may request early deletion at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing the services and contracts
    text: providing the services, including registration on the Website, providing demos, establishing contractual relationships, and concluding contracts
  - purpose: processing payments
    text: processing payments from our customers
  - purpose: information security and fraud prevention
    text: ensuring information security of the services and preventing frauds
  - purpose: direct marketing
    text: lead generation, sending newsletters and other direct marketing communications
  - purpose: advertising conversion measurement
    text: measuring the effectiveness and attribution of our online advertising, including through Google Ads Enhanced Conversions
  residency:
  - region: EEA and UK
    text: we may share your personal data with SEON entities outside the EEA, in particular, we may transfer your personal data to the UK.
  - region: United States
    text: we may transfer your personal data to the US and various third countries.
  retention:
  - period: 5 years
    scope: customer account and contract data
    text: 'Retention period: 5 years which is based on the applicable limitation period for enforcing legal claims and the statutory retention period in case of accounting documents.'
  - period: 5 years
    scope: fraud check data
    text: 'Retention period: 5 years after the fraud check query is completed.'
  - period: one (1) year
    scope: End-user query data (processor role)
    text: SEON will continue to process your data related to any queries for a period of one (1) year from the completion of the relevant query, unless the data controller (customer) instructs SEON otherwise.
  - period: 24 months
    scope: event recordings and transcripts
    text: 24 months from the event date for raw recordings and transcripts, after which they are permanently deleted
  rights:
  - right: access
    text: Right to access
  - right: rectification
    text: Right to rectification
  - right: erasure
    text: Right to erasure
  - right: restriction of processing
    text: Right to restriction of processing
  - right: object
    text: Right to object to processing
  - right: portability
    text: Right to data portability
  - right: withdraw consent
    text: Right to withdraw your consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell Personal Information, as this term is defined under California law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: SEON Technologies US Inc., an affiliate of SEON Technologies Kft., complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)
  - mechanism: SCC
    text: We enter into standard contractual clauses adopted by the European Commission with these business partners to ensure the adequate protection of your personal data.
  - mechanism: adequacy
    text: We rely on the adequacy decision adopted by the European Commission for transfers of personal data to the UK.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SEON
provenance_date: '2026-11-10'
provider_name: SEON
provider_slug: seon-tech
slug: seon-tech-privacy-policy
source_date: '2026-11-10'
source_filename: seon-tech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://seon.io/legal-and-security/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SEON\naid: seon-tech\nurl: https://seon.io/legal-and-security/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Personal data provided by you, for example, contact details, information necessary to create an account,\n    information related to the usage of the services, and communication-related to the services.\n- category: financial\n  text: information necessary for billing\n- category: behavioral\n  text: data collected via cookies\n- category: identifying\n  text: identifiers that you submit to us through forms on our Website (such\
  \ as your email address, phone number\n    and name)\npurposes:\n- purpose: providing the services and contracts\n  text: providing the services, including registration on the Website, providing demos, establishing contractual\n    relationships, and concluding contracts\n- purpose: processing payments\n  text: processing payments from our customers\n- purpose: information security and fraud prevention\n  text: ensuring information security of the services and preventing frauds\n- purpose: direct marketing\n  text: lead generation, sending newsletters and other direct marketing communications\n- purpose: advertising conversion measurement\n  text: measuring the effectiveness and attribution of our online advertising, including through Google Ads Enhanced\n    Conversions\nretention:\n- scope: customer account and contract data\n  period: 5 years\n  text: 'Retention period: 5 years which is based on the applicable limitation period for enforcing legal claims\n    and the statutory retention\
  \ period in case of accounting documents.'\n- scope: fraud check data\n  period: 5 years\n  text: 'Retention period: 5 years after the fraud check query is completed.'\n- scope: End-user query data (processor role)\n  period: one (1) year\n  text: SEON will continue to process your data related to any queries for a period of one (1) year from the completion\n    of the relevant query, unless the data controller (customer) instructs SEON otherwise.\n- scope: event recordings and transcripts\n  period: 24 months\n  text: 24 months from the event date for raw recordings and transcripts, after which they are permanently deleted\nresidency:\n- region: EEA and UK\n  text: we may share your personal data with SEON entities outside the EEA, in particular, we may transfer your\n    personal data to the UK.\n- region: United States\n  text: we may transfer your personal data to the US and various third countries.\ntransfers:\n- mechanism: DPF\n  text: SEON Technologies US Inc., an affiliate of SEON\
  \ Technologies Kft., complies with the EU-U.S. Data Privacy\n    Framework (EU-U.S. DPF)\n- mechanism: SCC\n  text: We enter into standard contractual clauses adopted by the European Commission with these business partners\n    to ensure the adequate protection of your personal data.\n- mechanism: adequacy\n  text: We rely on the adequacy decision adopted by the European Commission for transfers of personal data to the\n    UK.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to SEON contact\n  text: You may request early deletion at any time.\nrights:\n- right: access\n  text: Right to access\n- right: rectification\n  text: Right to rectification\n- right: erasure\n  text: Right to erasure\n- right: restriction of processing\n  text: Right to restriction of processing\n- right: object\n  text: Right to object to processing\n- right: portability\n  text: Right to data portability\n- right: withdraw consent\n  text:\
  \ Right to withdraw your consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell Personal Information, as this term is defined under California law.\n"
source_yaml_url: https://artifacts.apis.io/seon-tech/privacy/seon-tech-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from SEON's own page on 2026-11-10.
synthetic: false
tags:
- AML Compliance
- Device Intelligence
- Digital Footprint
- Fraud Prevention
- Identity Verification
- Risk Scoring
---
