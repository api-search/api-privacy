---
api_specs:
- filename: persona-accounts-api-openapi.yml
  format: yaml
  label: Persona Accounts API
  slug: persona-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-accounts-api-openapi.yml
- filename: persona-inquiries-api-openapi.yml
  format: yaml
  label: Persona Inquiries API
  slug: persona-inquiries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-inquiries-api-openapi.yml
- filename: persona-lists-api-openapi.yml
  format: yaml
  label: Persona Lists API
  slug: persona-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-lists-api-openapi.yml
- filename: persona-reports-api-openapi.yml
  format: yaml
  label: Persona Reports API
  slug: persona-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-reports-api-openapi.yml
- filename: persona-transactions-api-openapi.yml
  format: yaml
  label: Persona Transactions API
  slug: persona-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-transactions-api-openapi.yml
- filename: persona-verifications-api-openapi.yml
  format: yaml
  label: Persona Verifications API
  slug: persona-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-verifications-api-openapi.yml
- filename: persona-webhooks-api-openapi.yml
  format: yaml
  label: Persona Webhooks API
  slug: persona-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-webhooks-api-openapi.yml
- filename: persona-cases-api-openapi.yml
  format: yaml
  label: Persona Cases API
  slug: persona-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-cases-api-openapi.yml
- filename: persona-devices-api-openapi.yml
  format: yaml
  label: Persona Devices API
  slug: persona-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-devices-api-openapi.yml
- filename: persona-documents-api-openapi.yml
  format: yaml
  label: Persona Documents API
  slug: persona-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-documents-api-openapi.yml
- filename: persona-events-api-openapi.yml
  format: yaml
  label: Persona Events API
  slug: persona-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-events-api-openapi.yml
- filename: persona-importers-api-openapi.yml
  format: yaml
  label: Persona Importers API
  slug: persona-importers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-importers-api-openapi.yml
- filename: persona-inquiry-sessions-api-openapi.yml
  format: yaml
  label: Persona Inquiry Sessions API
  slug: persona-inquiry-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-inquiry-sessions-api-openapi.yml
- filename: persona-workflows-api-openapi.yml
  format: yaml
  label: Persona Workflows API
  slug: persona-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/persona/openapi/persona-workflows-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and contact information, including name, email address, address, and phone number
  - category: demographic
    text: Demographic data, including birthdate and age
  - category: biometric
    text: Biometric Data, only with your express consent, including a scan of your facial geometry based on the photos or video you provide
  - category: location
    text: Geolocation data, as we may infer your general geographic location (such as city, state, and country) based on your IP address. We do not collect precise geolocation data
  - category: financial
    text: Files you upload, such as tax forms and utility bills
  deletion:
    route: Contact the customer, who is the controller
    text: To exercise any privacy rights you may have, please contact the appropriate customer who will be better able to help you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Age assurance and identity verification for customers
    text: so that our customers may verify your age and prevent fraud
  - purpose: Fraud detection and investigation
    text: Use your information, including ID and Selfie Scan Data, to detect, prevent, and investigate fraud and abuse.
  - purpose: Compliance with applicable laws
    text: complying with applicable laws, for example performing AML/KYC checks for regulated customers
  residency:
  - region: United States and Germany
    text: Currently, we primarily use data centers in the United States and Germany.
  retention:
  - period: immediately
    scope: Age Estimation Scan Data
    text: Age Estimation Scan Data is deleted immediately as soon as an outcome has been determined
  - period: within three years of your last interaction with Persona
    scope: ID and Selfie Scan Data
    text: Persona will permanently destroy ID and Selfie Scan Data upon completion of identity verification services or within three years of your last interaction with Persona
  rights:
  - right: access
    text: such as the right to access or correct your personal data
  - right: correction
    text: such as the right to access or correct your personal data
  role:
    text: Persona acts as a processor (or similar role under applicable law) on behalf of the customer controller who has contracted with us
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: Persona does not sell or share personal data with third parties.
  subprocessors:
    text: We may disclose personal data to service providers, including hosting, cloud services and other information technology services providers
    url: null
  transfers:
  - mechanism: DPF
    text: Persona complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework
  - mechanism: other
    text: When we do so, we use legal mechanisms, including contracts, to help ensure your rights and protections.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Persona
provenance_date: '2026-11-10'
provider_name: Persona
provider_slug: persona
slug: persona-privacy-policy
source_date: '2026-11-10'
source_filename: persona-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://withpersona.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Persona\naid: persona\nurl: https://withpersona.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Persona acts as a processor (or similar role under applicable law) on behalf of the customer controller\n    who has contracted with us\ndata_categories:\n- category: identifying\n  text: Name and contact information, including name, email address, address, and phone number\n- category: demographic\n  text: Demographic data, including birthdate and age\n- category: biometric\n  text: Biometric Data, only with your express consent, including a scan of your facial geometry based\
  \ on the photos\n    or video you provide\n- category: location\n  text: Geolocation data, as we may infer your general geographic location (such as city, state, and country) based\n    on your IP address. We do not collect precise geolocation data\n- category: financial\n  text: Files you upload, such as tax forms and utility bills\npurposes:\n- purpose: Age assurance and identity verification for customers\n  text: so that our customers may verify your age and prevent fraud\n- purpose: Fraud detection and investigation\n  text: Use your information, including ID and Selfie Scan Data, to detect, prevent, and investigate fraud and abuse.\n- purpose: Compliance with applicable laws\n  text: complying with applicable laws, for example performing AML/KYC checks for regulated customers\nretention:\n- scope: Age Estimation Scan Data\n  period: immediately\n  text: Age Estimation Scan Data is deleted immediately as soon as an outcome has been determined\n- scope: ID and Selfie Scan Data\n  period:\
  \ within three years of your last interaction with Persona\n  text: Persona will permanently destroy ID and Selfie Scan Data upon completion of identity verification services\n    or within three years of your last interaction with Persona\nresidency:\n- region: United States and Germany\n  text: Currently, we primarily use data centers in the United States and Germany.\ntransfers:\n- mechanism: DPF\n  text: Persona complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework\n- mechanism: other\n  text: When we do so, we use legal mechanisms, including contracts, to help ensure your rights and protections.\nsubprocessors:\n  url: null\n  text: We may disclose personal data to service providers, including hosting, cloud services and other information\n    technology services providers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the customer, who is the controller\n\
  \  text: To exercise any privacy rights you may have, please contact the appropriate customer who will be better\n    able to help you.\nrights:\n- right: access\n  text: such as the right to access or correct your personal data\n- right: correction\n  text: such as the right to access or correct your personal data\nsale_or_sharing:\n  stance: prohibited\n  text: Persona does not sell or share personal data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/persona/privacy/persona-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Persona's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Identity Verification
- KYC
---
