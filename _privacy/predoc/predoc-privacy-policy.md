---
api_specs:
- filename: predoc-authentication-api-openapi.yml
  format: yaml
  label: Predoc Authentication API
  slug: predoc-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-authentication-api-openapi.yml
- filename: predoc-documents-api-openapi.yml
  format: yaml
  label: Predoc Documents API
  slug: predoc-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-documents-api-openapi.yml
- filename: predoc-events-api-openapi.yml
  format: yaml
  label: Predoc Events API
  slug: predoc-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-events-api-openapi.yml
- filename: predoc-patient-api-openapi.yml
  format: yaml
  label: Predoc Patient API
  slug: predoc-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-patient-api-openapi.yml
- filename: predoc-record-request-api-openapi.yml
  format: yaml
  label: Predoc Record Request API
  slug: predoc-record-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-record-request-api-openapi.yml
- filename: predoc-record-upload-api-openapi.yml
  format: yaml
  label: Predoc Record Upload API
  slug: predoc-record-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-record-upload-api-openapi.yml
- filename: predoc-retrieval-api-openapi.yml
  format: yaml
  label: Predoc Retrieval API
  slug: predoc-retrieval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-retrieval-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: By which you may be personally identified, including name, email and/or phone number.
  - category: health
    text: Protected Health Information (PHI) of your participants, such as medical records, health history, treatment information, lab results, medications, diagnoses, and other health-related data
  - category: financial
    text: Records and financial information for the purpose of payment, such as, bank account and routing numbers, credit and debit card information
  - category: device
    text: About your internet connection, the equipment you use to access our Website, and usage details.
  - category: behavioral
    text: Your search queries on the Website.
  deletion:
    route: Delete user account
    text: We cannot delete your personal information except by also deleting your user account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Develop and train AI/ML models
    text: To develop, train, improve, and validate our artificial intelligence and machine learning models, algorithms, and systems, which may involve processing your personal information and participant PHI.
  - purpose: Provide requested services
    text: To provide you with information, products, or services that you request from us.
  - purpose: Advertising to advertisers' target audiences
    text: We may use the information we have collected from you to enable us to display advertisements to our advertisers' target audiences.
  retention:
  - period: null
    scope: Personal information and PHI
    text: We will retain your information (including your participant's PHI) only for as long as is necessary for the purposes set out in this Privacy Policy, and as required by law, including HIPAA.
  - period: null
    scope: Automatically collected data
    text: This information is generally retained for a shorter period of time, except when this data is used to strengthen the security or to improve the functionality of our Service
  rights:
  - right: Access and correct PHI
    text: You may request access to, obtain copies of, or request amendments to your PHI by contacting our Privacy Officer at support@predoc.ai .
  - right: Accounting of disclosures
    text: You have the right to receive an accounting of disclosures of your PHI as provided by HIPAA.
  - right: Opt-out of targeted advertising and sales (Colorado, Connecticut, Virginia, Utah)
    text: Opt-out of personal data processing for targeted advertising and sales.
  - right: Opt-out of third-party sharing for promotional purposes
    text: If you do not want us to share your personal information with unaffiliated or non-agent third parties for promotional purposes, you can opt-out by sending us an email with your request to support@predoc.ai .
  role:
    text: null
    value: unstated
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
name: Predoc
provenance_date: '2026-11-10'
provider_name: Predoc
provider_slug: predoc
slug: predoc-privacy-policy
source_date: '2026-11-10'
source_filename: predoc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.predoc.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Predoc\naid: predoc\nurl: https://www.predoc.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: By which you may be personally identified, including name, email and/or phone number.\n- category: health\n  text: Protected Health Information (PHI) of your participants, such as medical records, health history, treatment\n    information, lab results, medications, diagnoses, and other health-related data\n- category: financial\n  text: Records and financial information for the purpose of payment, such as, bank account and routing numbers,\n\
  \    credit and debit card information\n- category: device\n  text: About your internet connection, the equipment you use to access our Website, and usage details.\n- category: behavioral\n  text: Your search queries on the Website.\npurposes:\n- purpose: Develop and train AI/ML models\n  text: To develop, train, improve, and validate our artificial intelligence and machine learning models, algorithms,\n    and systems, which may involve processing your personal information and participant PHI.\n- purpose: Provide requested services\n  text: To provide you with information, products, or services that you request from us.\n- purpose: Advertising to advertisers' target audiences\n  text: We may use the information we have collected from you to enable us to display advertisements to our advertisers'\n    target audiences.\nretention:\n- scope: Personal information and PHI\n  period: null\n  text: We will retain your information (including your participant's PHI) only for as long as is necessary\
  \ for\n    the purposes set out in this Privacy Policy, and as required by law, including HIPAA.\n- scope: Automatically collected data\n  period: null\n  text: This information is generally retained for a shorter period of time, except when this data is used to strengthen\n    the security or to improve the functionality of our Service\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete user account\n  text: We cannot delete your personal information except by also deleting your user account.\nrights:\n- right: Access and correct PHI\n  text: You may request access to, obtain copies of, or request amendments to your PHI by contacting our Privacy\n    Officer at support@predoc.ai .\n- right: Accounting of disclosures\n  text: You have the right to receive an accounting of disclosures of your PHI as provided by HIPAA.\n- right: Opt-out of targeted advertising and sales (Colorado, Connecticut,\
  \ Virginia, Utah)\n  text: Opt-out of personal data processing for targeted advertising and sales.\n- right: Opt-out of third-party sharing for promotional purposes\n  text: If you do not want us to share your personal information with unaffiliated or non-agent third parties for\n    promotional purposes, you can opt-out by sending us an email with your request to support@predoc.ai .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/predoc/privacy/predoc-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 15 quoted statements, read from Predoc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Records
- Health Information Exchange
- FHIR
- Clinical Data
- Artificial Intelligence
- Interoperability
- EHR Integration
- Webhook
- Clinical Research
---
