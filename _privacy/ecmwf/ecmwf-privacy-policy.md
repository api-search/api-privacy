---
api_specs:
- filename: ecmwf-data-stores-processing-openapi.yml
  format: yaml
  label: ECMWF Data Stores Processing API
  slug: ecmwf-data-stores-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecmwf/openapi/ecmwf-data-stores-processing-openapi.yml
- filename: ecmwf-data-stores-catalogue-openapi.yml
  format: yaml
  label: ECMWF Data Stores STAC Catalogue API
  slug: ecmwf-data-stores-stac-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecmwf/openapi/ecmwf-data-stores-catalogue-openapi.yml
- filename: ecmwf-data-stores-profiles-openapi.yml
  format: yaml
  label: ECMWF Data Stores Profile API
  slug: ecmwf-data-stores-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecmwf/openapi/ecmwf-data-stores-profiles-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: The compulsory fields concern your name and surname, a valid email account, and your country of residence (if you provide one) as well as your sector of work (if you provide one).
  - category: location
    text: It is possible to derive users' locations from their IP addresses.
  - category: professional
    text: This includes your name, contact information (such as address details, phone numbers, email address), date and place of birth, gender, nationalities, military service commitment if applicable, family details, marital status, language skills, your employment and education history, qualifications, your current employment status, your employment and remuneration details, your membership in professional societies, details of the persons providing references for you, your photographic image if you provide one and any other personal data you include in your CV, cover letter or other document you provide to us during the application process.
  deletion:
    route: Request account deletion or written request to PII Protection Officer
    text: If you are a registered user, in order to do either, you can request deletion of your account at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Website usage analysis
    text: we may use the personal data collected to perform an analysis of the use of the services and to derive use statistics of all items and services available on the ECMWF web in order to improve service performance as well as user relations and experience.
  - purpose: Processing service contracts
    text: we collect and process your personal data to provide you with an ever-improving service experience and the products and services you have requested
  - purpose: Job applications
    text: we collect and process your personal data to process your job application and manage the selection process.
  retention:
  - period: 5 years
    scope: Web access information
    text: The information collected and processed when accessing our web will be retained for 5 years.
  - period: 12 months
    scope: Job application information
    text: The information you provide during a job application process will be retained for 12 months.
  - period: null
    scope: Service contract information
    text: The information you provide in order to enter into the service contract will be retained for the duration of this contract.
  rights:
  - right: Access
    text: You may ask ECMWF to access a copy of your personal data, as well as to rectify and erase any such data.
  - right: Objection
    text: You have right to object to ECMWF processing your personal data.
  role:
    text: ECMWF is committed to achieving an adequate level of protection for the rights and freedoms of individuals in respect of the processing of personal data and assume the responsibilities akin to a data controller in the context of GDPR.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We will only transfer personal data outside the European Economic Area or to another international organisation if we determined that adequate safeguards are in place to protect such personal data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ECMWF
provenance_date: '2026-11-09'
provider_name: ECMWF
provider_slug: ecmwf
slug: ecmwf-privacy-policy
source_date: '2026-11-09'
source_filename: ecmwf-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ecmwf.int/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ECMWF\naid: ecmwf\nurl: https://www.ecmwf.int/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ECMWF is committed to achieving an adequate level of protection for the rights and freedoms of individuals\n    in respect of the processing of personal data and assume the responsibilities akin to a data controller in the\n    context of GDPR.\ndata_categories:\n- category: identifying\n  text: The compulsory fields concern your name and surname, a valid email account, and your country of residence\n    (if you provide one) as well as your sector of work (if you provide one).\n- category:\
  \ location\n  text: It is possible to derive users' locations from their IP addresses.\n- category: professional\n  text: This includes your name, contact information (such as address details, phone numbers, email address), date\n    and place of birth, gender, nationalities, military service commitment if applicable, family details, marital\n    status, language skills, your employment and education history, qualifications, your current employment status,\n    your employment and remuneration details, your membership in professional societies, details of the persons\n    providing references for you, your photographic image if you provide one and any other personal data you include\n    in your CV, cover letter or other document you provide to us during the application process.\npurposes:\n- purpose: Website usage analysis\n  text: we may use the personal data collected to perform an analysis of the use of the services and to derive use\n    statistics of all items and services available\
  \ on the ECMWF web in order to improve service performance as well\n    as user relations and experience.\n- purpose: Processing service contracts\n  text: we collect and process your personal data to provide you with an ever-improving service experience and the\n    products and services you have requested\n- purpose: Job applications\n  text: we collect and process your personal data to process your job application and manage the selection process.\nretention:\n- scope: Web access information\n  period: 5 years\n  text: The information collected and processed when accessing our web will be retained for 5 years.\n- scope: Job application information\n  period: 12 months\n  text: The information you provide during a job application process will be retained for 12 months.\n- scope: Service contract information\n  period: null\n  text: The information you provide in order to enter into the service contract will be retained for the duration\n    of this contract.\nresidency: []\ntransfers:\n\
  - mechanism: other\n  text: We will only transfer personal data outside the European Economic Area or to another international organisation\n    if we determined that adequate safeguards are in place to protect such personal data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account deletion or written request to PII Protection Officer\n  text: If you are a registered user, in order to do either, you can request deletion of your account at any time.\nrights:\n- right: Access\n  text: You may ask ECMWF to access a copy of your personal data, as well as to rectify and erase any such data.\n- right: Objection\n  text: You have right to object to ECMWF processing your personal data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ecmwf/privacy/ecmwf-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 14 quoted statements, read from ECMWF's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Weather
- Meteorology
- Forecasting
- Climate
- Open Data
- Research
- Intergovernmental
---
