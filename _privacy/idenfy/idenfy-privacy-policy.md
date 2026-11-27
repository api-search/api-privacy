---
api_specs:
- filename: idenfy-age-estimation-api-openapi.yml
  format: yaml
  label: iDenfy Age Estimation API
  slug: idenfy-age-estimation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-age-estimation-api-openapi.yml
- filename: idenfy-aml-checks-api-openapi.yml
  format: yaml
  label: iDenfy AML Checks API
  slug: idenfy-aml-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-aml-checks-api-openapi.yml
- filename: idenfy-aml-monitorings-api-openapi.yml
  format: yaml
  label: iDenfy AML Monitorings API
  slug: idenfy-aml-monitorings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-aml-monitorings-api-openapi.yml
- filename: idenfy-bank-api-openapi.yml
  format: yaml
  label: iDenfy Bank API
  slug: idenfy-bank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-bank-api-openapi.yml
- filename: idenfy-bank-card-verification-api-openapi.yml
  format: yaml
  label: iDenfy Bank Card Verification API
  slug: idenfy-bank-card-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-bank-card-verification-api-openapi.yml
- filename: idenfy-beneficiaries-api-openapi.yml
  format: yaml
  label: iDenfy Beneficiaries API
  slug: idenfy-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-beneficiaries-api-openapi.yml
- filename: idenfy-companies-api-openapi.yml
  format: yaml
  label: iDenfy Companies API
  slug: idenfy-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-companies-api-openapi.yml
- filename: idenfy-face-auth-sessions-api-openapi.yml
  format: yaml
  label: iDenfy Face Auth Sessions API
  slug: idenfy-face-auth-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-face-auth-sessions-api-openapi.yml
- filename: idenfy-gov-orders-api-openapi.yml
  format: yaml
  label: iDenfy GOV Orders API
  slug: idenfy-gov-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-gov-orders-api-openapi.yml
- filename: idenfy-kyb-documents-api-openapi.yml
  format: yaml
  label: iDenfy KYB Documents API
  slug: idenfy-kyb-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-kyb-documents-api-openapi.yml
- filename: idenfy-kyb-forms-api-openapi.yml
  format: yaml
  label: iDenfy KYB Forms API
  slug: idenfy-kyb-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-kyb-forms-api-openapi.yml
- filename: idenfy-kyb-questionnaires-api-openapi.yml
  format: yaml
  label: iDenfy KYB Questionnaires API
  slug: idenfy-kyb-questionnaires-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-kyb-questionnaires-api-openapi.yml
- filename: idenfy-kyb-token-api-openapi.yml
  format: yaml
  label: iDenfy KYB Token API
  slug: idenfy-kyb-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-kyb-token-api-openapi.yml
- filename: idenfy-kyc-blocklist-api-openapi.yml
  format: yaml
  label: iDenfy KYC Blocklist API
  slug: idenfy-kyc-blocklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-kyc-blocklist-api-openapi.yml
- filename: idenfy-kyc-token-api-openapi.yml
  format: yaml
  label: iDenfy KYC Token API
  slug: idenfy-kyc-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-kyc-token-api-openapi.yml
- filename: idenfy-kyc-verifications-api-openapi.yml
  format: yaml
  label: iDenfy KYC Verifications API
  slug: idenfy-kyc-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-kyc-verifications-api-openapi.yml
- filename: idenfy-poa-api-openapi.yml
  format: yaml
  label: iDenfy POA API
  slug: idenfy-poa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-poa-api-openapi.yml
- filename: idenfy-registry-center-checks-api-openapi.yml
  format: yaml
  label: iDenfy Registry Center Checks API
  slug: idenfy-registry-center-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-registry-center-checks-api-openapi.yml
- filename: idenfy-sos-reports-api-openapi.yml
  format: yaml
  label: iDenfy SOS Reports API
  slug: idenfy-sos-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-sos-reports-api-openapi.yml
- filename: idenfy-webhooks-api-openapi.yml
  format: yaml
  label: iDenfy Webhooks API
  slug: idenfy-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idenfy/openapi/idenfy-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: identity document photograph(s); face photograph(s); citizenship/nationality; client id; identification date and method.
  - category: biometric
    text: face images/templates used for liveness/face-match
  - category: device
    text: device fingerprint (“user-agent”).
  - category: communication
    text: We may collect phone numbers, communication preferences, and opt-in/opt-out records.
  - category: location
    text: Geolocation (approximate) coarse location inferred from IP
  - category: behavioral
    text: Inferences derived preferences/propensity from site interactions (marketing only)
  deletion:
    route: Request to any employee of the controller or to iDenfy, which forwards it
    text: An employee of UAB “iDenfy” shall promptly ensure that the erasure request is complied with immediately.
  dpa:
    available: true
    text: iDenfy will act upon a Data Processing Agreement that is made with the Data Controller
    url: null
  purposes:
  - purpose: Identity verification and fraud prevention
    text: Identity verification; fraud prevention; security
  - purpose: Website operation and security
    text: Processed information is needed to (1) deliver the content of our website correctly, (2) optimize the content of our website as well as its advertisement
  residency:
  - region: European Union (Dublin, Ireland)
    text: iDenfy stores data until retention only in the Amazon AWS Europe (Dublin, Ireland).
  retention:
  - period: 13 months
    scope: Website cookies
    text: device & cookie IDs up to 13 months
  - period: 12 months
    scope: Website logs
    text: Logs 12 months
  rights:
  - right: Access
    text: Right of access, Each data subject shall have the right granted by the European legislator
  - right: Rectification
    text: Right to rectification
  - right: Erasure
    text: Right to erasure (Right to be forgotten)
  - right: Restriction of processing
    text: Right of restriction of processing
  - right: Data portability
    text: Right to data portability
  - right: Object
    text: Right to object
  - right: Withdraw consent
    text: Right to withdraw data protection consent
  - right: US state rights (access, correct, delete, portable copy, opt-out)
    text: you may have the right to access, correct, delete, obtain a portable copy, opt-out of sales/sharing and targeted advertising
  role:
    text: iDenfy may act in the role either as a Data Controller or Data Processor.
    value: both
  sale_or_sharing:
    stance: allowed
    text: We may “share” identifiers, internet/network activity, and inferences with ad/analytics providers (Google, LinkedIn, HubSpot, G2, Hotjar) for cross-context behavioral/targeted advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: In some extra cases, data can be sent outside the European Union, but only if additional and necessary safety guards are ensured (Standard contractual clauses and similar).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: iDenfy
provenance_date: '2026-11-09'
provider_name: iDenfy
provider_slug: idenfy
slug: idenfy-privacy-policy
source_date: '2026-11-09'
source_filename: idenfy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://idenfy.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: iDenfy\naid: idenfy\nurl: https://idenfy.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: iDenfy may act in the role either as a Data Controller or Data Processor.\ndata_categories:\n- category: identifying\n  text: identity document photograph(s); face photograph(s); citizenship/nationality; client id; identification\n    date and method.\n- category: biometric\n  text: face images/templates used for liveness/face-match\n- category: device\n  text: device fingerprint (“user-agent”).\n- category: communication\n  text: We may collect phone numbers, communication\
  \ preferences, and opt-in/opt-out records.\n- category: location\n  text: Geolocation (approximate) coarse location inferred from IP\n- category: behavioral\n  text: Inferences derived preferences/propensity from site interactions (marketing only)\npurposes:\n- purpose: Identity verification and fraud prevention\n  text: Identity verification; fraud prevention; security\n- purpose: Website operation and security\n  text: Processed information is needed to (1) deliver the content of our website correctly, (2) optimize the content\n    of our website as well as its advertisement\nretention:\n- scope: Website cookies\n  period: 13 months\n  text: device & cookie IDs up to 13 months\n- scope: Website logs\n  period: 12 months\n  text: Logs 12 months\nresidency:\n- region: European Union (Dublin, Ireland)\n  text: iDenfy stores data until retention only in the Amazon AWS Europe (Dublin, Ireland).\ntransfers:\n- mechanism: SCC\n  text: In some extra cases, data can be sent outside the European\
  \ Union, but only if additional and necessary safety\n    guards are ensured (Standard contractual clauses and similar).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: iDenfy will act upon a Data Processing Agreement that is made with the Data Controller\ndeletion:\n  route: Request to any employee of the controller or to iDenfy, which forwards it\n  text: An employee of UAB “iDenfy” shall promptly ensure that the erasure request is complied with immediately.\nrights:\n- right: Access\n  text: Right of access, Each data subject shall have the right granted by the European legislator\n- right: Rectification\n  text: Right to rectification\n- right: Erasure\n  text: Right to erasure (Right to be forgotten)\n- right: Restriction of processing\n  text: Right of restriction of processing\n- right: Data portability\n  text: Right to data portability\n- right: Object\n  text: Right to object\n- right: Withdraw consent\n  text: Right to withdraw data\
  \ protection consent\n- right: US state rights (access, correct, delete, portable copy, opt-out)\n  text: you may have the right to access, correct, delete, obtain a portable copy, opt-out of sales/sharing and\n    targeted advertising\nsale_or_sharing:\n  stance: allowed\n  text: We may “share” identifiers, internet/network activity, and inferences with ad/analytics providers (Google,\n    LinkedIn, HubSpot, G2, Hotjar) for cross-context behavioral/targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/idenfy/privacy/idenfy-privacy-policy.yml
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
- sale_or_sharing
summary_line: 24 quoted statements, read from iDenfy's own page on 2026-11-09.
synthetic: false
tags:
- AML
- Age Verification
- Bank Verification
- Biometrics
- Compliance
- Fraud Prevention
- Identity Verification
- KYB
- KYC
- MCP
- Open Banking
- RegTech
- Sanctions Screening
- Webhook
- A2A
---
