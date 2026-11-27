---
api_specs:
- filename: plansource-aca-api-openapi.yml
  format: yaml
  label: PlanSource ACA API
  slug: plansource-aca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-aca-api-openapi.yml
- filename: plansource-administrators-api-openapi.yml
  format: yaml
  label: PlanSource Administrators API
  slug: plansource-administrators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-administrators-api-openapi.yml
- filename: plansource-collections-api-openapi.yml
  format: yaml
  label: PlanSource Collections API
  slug: plansource-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-collections-api-openapi.yml
- filename: plansource-coverage-api-openapi.yml
  format: yaml
  label: PlanSource Coverage API
  slug: plansource-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-coverage-api-openapi.yml
- filename: plansource-demographic-api-openapi.yml
  format: yaml
  label: PlanSource Demographic API
  slug: plansource-demographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-demographic-api-openapi.yml
- filename: plansource-eoi-api-openapi.yml
  format: yaml
  label: PlanSource EOI API
  slug: plansource-eoi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-eoi-api-openapi.yml
- filename: plansource-page-content-api-openapi.yml
  format: yaml
  label: PlanSource Page Content API
  slug: plansource-page-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-page-content-api-openapi.yml
- filename: plansource-payroll-api-openapi.yml
  format: yaml
  label: PlanSource Payroll API
  slug: plansource-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-payroll-api-openapi.yml
- filename: plansource-security-api-openapi.yml
  format: yaml
  label: PlanSource Security API
  slug: plansource-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plansource/openapi/plansource-security-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Basic identifiers , such as your full legal name, date of birth, postal address, phone number, personal email address, and work email address.
  - category: contact
    text: Basic identifiers , such as your full legal name, date of birth, postal address, phone number, personal email address, and work email address.
  - category: location
    text: Location information , such as imprecise geolocation (based on IP address).
  - category: behavioral
    text: Other information regarding your interaction with the Services , such as operating system, browser type, log data, date and time stamps, device screen resolution, the pages you access on the Services, the websites you access before and after visiting the Services, the length of time you spend on the Services, clickstream data, and ad impressions.
  - category: device
    text: Device information , such as device type, operating system, device ID numbers and unique device identifier, media access control (MAC) address, and internet protocol (IP) address.
  - category: health
    text: Health Information , such as your health history or your family health history, and other information to determine appropriate insurance coverage as needed to deliver the Services.
  - category: demographic
    text: Demographic information , such as your age, gender, race, ethnicity, and/or marital status.
  deletion:
    route: Request via compliance@plansource.com or the privacy request page
    text: Parents or guardians of children under 13 years of age who have provided us with their personal information may contact us using the information below to request that such information be deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Communication with you and services administration
    text: to process and communicate with you in connection with your use of the Services, to process your requests for information
  - purpose: Provision of benefits
    text: We use information we collected about you for the purpose of processing and managing employee benefits, employee payroll, and business-to-business transactions.
  - purpose: Personalization, advertising and analytics
    text: To tailor the content and information that we may send or display to you
  - purpose: Marketing communications
    text: To send you marketing communications about our business, products, Services, and other programs that may be of interest to you.
  - purpose: Evaluation and improvement
    text: To analyze, develop, and improve the content, materials, products, and the Services
  - purpose: Quality assurance
    text: To perform quality assurance; to assist with fraud identification
  retention:
  - period: null
    scope: General personal information
    text: We retain information about you for as long as it is reasonably necessary for the purposes specified in this Privacy Notice
  - period: null
    scope: Chatbot data
    text: The data from the chats is retained for as long as the data is needed.
  rights:
  - right: Right to know
    text: 'Right to Know : Know (1) the categories of personal information collected, disclosed, sold and/or shared'
  - right: Right to data portability
    text: 'Right to Data Portability : Access and receive the specific personal information we process about you in a structured, commonly used and machine-readable format'
  - right: Right to delete
    text: 'Right to Delete : Delete personal information about you.'
  - right: Right to correct
    text: 'Right to Correct : Correct personal information about you.'
  - right: Right to no discrimination
    text: 'Right to No Discrimination : Not be discriminated against due to your exercise of the rights provided under applicable California law'
  - right: Right to lodge a complaint
    text: 'Right to Lodge a Complaint : To lodge a complaint with a government regulator'
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
name: PlanSource
provenance_date: '2026-11-10'
provider_name: PlanSource
provider_slug: plansource
slug: plansource-privacy-policy
source_date: '2026-11-10'
source_filename: plansource-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://plansource.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PlanSource\naid: plansource\nurl: https://plansource.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Basic identifiers , such as your full legal name, date of birth, postal address, phone number, personal\n    email address, and work email address.\n- category: contact\n  text: Basic identifiers , such as your full legal name, date of birth, postal address, phone number, personal\n    email address, and work email address.\n- category: location\n  text: Location information , such as imprecise geolocation (based on IP address).\n\
  - category: behavioral\n  text: Other information regarding your interaction with the Services , such as operating system, browser type,\n    log data, date and time stamps, device screen resolution, the pages you access on the Services, the websites\n    you access before and after visiting the Services, the length of time you spend on the Services, clickstream\n    data, and ad impressions.\n- category: device\n  text: Device information , such as device type, operating system, device ID numbers and unique device identifier,\n    media access control (MAC) address, and internet protocol (IP) address.\n- category: health\n  text: Health Information , such as your health history or your family health history, and other information to\n    determine appropriate insurance coverage as needed to deliver the Services.\n- category: demographic\n  text: Demographic information , such as your age, gender, race, ethnicity, and/or marital status.\npurposes:\n- purpose: Communication with you and\
  \ services administration\n  text: to process and communicate with you in connection with your use of the Services, to process your requests\n    for information\n- purpose: Provision of benefits\n  text: We use information we collected about you for the purpose of processing and managing employee benefits,\n    employee payroll, and business-to-business transactions.\n- purpose: Personalization, advertising and analytics\n  text: To tailor the content and information that we may send or display to you\n- purpose: Marketing communications\n  text: To send you marketing communications about our business, products, Services, and other programs that may\n    be of interest to you.\n- purpose: Evaluation and improvement\n  text: To analyze, develop, and improve the content, materials, products, and the Services\n- purpose: Quality assurance\n  text: To perform quality assurance; to assist with fraud identification\nretention:\n- scope: General personal information\n  period: null\n  text:\
  \ We retain information about you for as long as it is reasonably necessary for the purposes specified in\n    this Privacy Notice\n- scope: Chatbot data\n  period: null\n  text: The data from the chats is retained for as long as the data is needed.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via compliance@plansource.com or the privacy request page\n  text: Parents or guardians of children under 13 years of age who have provided us with their personal information\n    may contact us using the information below to request that such information be deleted.\nrights:\n- right: Right to know\n  text: 'Right to Know : Know (1) the categories of personal information collected, disclosed, sold and/or shared'\n- right: Right to data portability\n  text: 'Right to Data Portability : Access and receive the specific personal information we process about you in\n    a structured, commonly\
  \ used and machine-readable format'\n- right: Right to delete\n  text: 'Right to Delete : Delete personal information about you.'\n- right: Right to correct\n  text: 'Right to Correct : Correct personal information about you.'\n- right: Right to no discrimination\n  text: 'Right to No Discrimination : Not be discriminated against due to your exercise of the rights provided under\n    applicable California law'\n- right: Right to lodge a complaint\n  text: 'Right to Lodge a Complaint : To lodge a complaint with a government regulator'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plansource/privacy/plansource-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 22 quoted statements, read from PlanSource's own page on 2026-11-10.
synthetic: false
tags:
- Employee Benefits
- Benefits Administration
- Insurance
- Human Resources
- Payroll
- Health Insurance
- Enrollment
- HR Technology
- Evidence of Insurability
- ACA Reporting
- Eligibility
- SSO
- Identity Federation
---
