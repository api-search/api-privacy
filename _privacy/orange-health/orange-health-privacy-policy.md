---
api_specs:
- filename: orange-health-orders-api-openapi.yml
  format: yaml
  label: Orange Health Orders API
  slug: orange-health-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-orders-api-openapi.yml
- filename: orange-health-results-api-openapi.yml
  format: yaml
  label: Orange Health Results API
  slug: orange-health-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-results-api-openapi.yml
- filename: orange-health-serviceability-api-openapi.yml
  format: yaml
  label: Orange Health Serviceability API
  slug: orange-health-serviceability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-serviceability-api-openapi.yml
- filename: orange-health-orange-health-partner-api-api-openapi.yml
  format: yaml
  label: Orange Health Orange Health Partner API
  slug: orange-health-orange-health-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orange-health/openapi/orange-health-orange-health-partner-api-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, gender, address (including pin code), date of birth, email id, phone number, photograph, national identification proof, login name and password
  - category: health
    text: if you are an End User, we will also collect information about your medical history (drug allergies, chronic conditions), health habits, health indicators (BMI, weight, height), diagnostics reports, prescriptions
  - category: financial
    text: billing information and credit or payment card information
  - category: location
    text: Our application may access your device’s location information to provide location-based services such as personalised diagnostics or recommendations.
  - category: behavioral
    text: the full Uniform Resource Locators (URL), the type of Services you requested or provided, comments, domain names, search results selected, number of clicks, information and pages viewed and searched for
  - category: device
    text: 'Wi-Fi Information: Includes details about the Wi-Fi networks you’re connected to.'
  - category: communication
    text: When you communicate with us (via email, text, phone, through the Application or otherwise), we may maintain a record of your communication
  deletion:
    route: Grievance Officer / Data Protection Officer by email
    text: Upon expiry of the applicable retention period, we will delete or anonymize your information, save where retention is required under applicable law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide requested services
    text: To provide the Services that you choose to receive through or by use of the Application and to fulfil any obligations inuring upon us therefrom
  - purpose: Marketing communications
    text: To provide you with information about Services we consider similar to those that you are already using, or have enquired about, or may interest you.
  - purpose: Research and analytics
    text: To generate and review reports and data about, and to conduct research on, our user base and Service usage patterns
  - purpose: Store footfall analytics
    text: to analyse anonymized and aggregated customer footfall, movement patterns and cohort trends at our retail collection centres for business planning, staffing, marketing effectiveness and store layout optimisation
  residency:
  - region: outside India
    text: which may store this data on servers located outside India
  retention:
  - period: not less than 8 years
    scope: Diagnostic reports and medical records
    text: in any event for not less than 8 years from the date of the last consultation or test, whichever is later
  - period: null
    scope: Account and transaction information
    text: account and transaction information is retained for the duration of your relationship with us and for 8 years thereafter
  - period: null
    scope: Raw CCTV footage
    text: Raw CCTV footage is retained for a maximum period of thirty (30) days from the date of recording
  - period: null
    scope: Marketing data
    text: marketing and promotional data is retained until you withdraw your consent to receive such communications
  rights:
  - right: Access summary
    text: obtain a summary of the Personal Information and Sensitive Personal Data or Information processed by us
  - right: Correction, completion, updating or erasure
    text: request correction, completion, updating or erasure of your Personal Information and Sensitive Personal Data or Information
  - right: Withdraw consent
    text: withdraw your consent at any time, in the manner described in Section 1 (Your Consent) above
  - right: Nominate another individual
    text: nominate, in the manner prescribed under applicable law, another individual to exercise your rights under this Policy in the event of your death or incapacity
  - right: Grievance redressal
    text: grievance redressal in the manner described in Section 14 (Grievance Officer, Data Protection Officer and Application Security) below
  role:
    text: 'Orchard Healthcare Private Limited (Corporate Identification Number: U85110HR2020PTC124467), an Indian company having its registered office at Prem Tower, Plot No. 4, Kirti Nagar, Sector 15, Part 1, Gurgaon, Haryana - 122001'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Such service providers and business partners include, without limitation, diagnostic and pathology laboratories, logistics and last-mile delivery partners engaged for home sample collection, payment gateways and payment processors, cloud and information technology infrastructure providers
    url: null
  transfers:
  - mechanism: other
    text: Where your Personal Information or Sensitive Personal Data or Information is transferred outside India, we ensure that such transfer is undertaken in compliance with Section 16 of the DPDP Act and any rules, notifications or restrictions issued by the Central Government
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Orange Health
provenance_date: '2026-11-10'
provider_name: Orange Health
provider_slug: orange-health
slug: orange-health-privacy-policy
source_date: '2026-11-10'
source_filename: orange-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.orangehealth.in/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Orange Health\naid: orange-health\nurl: https://www.orangehealth.in/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Orchard Healthcare Private Limited (Corporate Identification Number: U85110HR2020PTC124467), an Indian\n    company having its registered office at Prem Tower, Plot No. 4, Kirti Nagar, Sector 15, Part 1, Gurgaon, Haryana\n    - 122001'\ndata_categories:\n- category: identifying\n  text: your name, gender, address (including pin code), date of birth, email id, phone number, photograph, national\n    identification proof, login name and password\n- category: health\n\
  \  text: if you are an End User, we will also collect information about your medical history (drug allergies, chronic\n    conditions), health habits, health indicators (BMI, weight, height), diagnostics reports, prescriptions\n- category: financial\n  text: billing information and credit or payment card information\n- category: location\n  text: Our application may access your device’s location information to provide location-based services such as\n    personalised diagnostics or recommendations.\n- category: behavioral\n  text: the full Uniform Resource Locators (URL), the type of Services you requested or provided, comments, domain\n    names, search results selected, number of clicks, information and pages viewed and searched for\n- category: device\n  text: 'Wi-Fi Information: Includes details about the Wi-Fi networks you’re connected to.'\n- category: communication\n  text: When you communicate with us (via email, text, phone, through the Application or otherwise), we may maintain\n\
  \    a record of your communication\npurposes:\n- purpose: Provide requested services\n  text: To provide the Services that you choose to receive through or by use of the Application and to fulfil any\n    obligations inuring upon us therefrom\n- purpose: Marketing communications\n  text: To provide you with information about Services we consider similar to those that you are already using,\n    or have enquired about, or may interest you.\n- purpose: Research and analytics\n  text: To generate and review reports and data about, and to conduct research on, our user base and Service usage\n    patterns\n- purpose: Store footfall analytics\n  text: to analyse anonymized and aggregated customer footfall, movement patterns and cohort trends at our retail\n    collection centres for business planning, staffing, marketing effectiveness and store layout optimisation\nretention:\n- scope: Diagnostic reports and medical records\n  period: not less than 8 years\n  text: in any event for not less\
  \ than 8 years from the date of the last consultation or test, whichever is later\n- scope: Account and transaction information\n  period: null\n  text: account and transaction information is retained for the duration of your relationship with us and for 8\n    years thereafter\n- scope: Raw CCTV footage\n  period: null\n  text: Raw CCTV footage is retained for a maximum period of thirty (30) days from the date of recording\n- scope: Marketing data\n  period: null\n  text: marketing and promotional data is retained until you withdraw your consent to receive such communications\nresidency:\n- region: outside India\n  text: which may store this data on servers located outside India\ntransfers:\n- mechanism: other\n  text: Where your Personal Information or Sensitive Personal Data or Information is transferred outside India,\n    we ensure that such transfer is undertaken in compliance with Section 16 of the DPDP Act and any rules, notifications\n    or restrictions issued by the Central\
  \ Government\nsubprocessors:\n  url: null\n  text: Such service providers and business partners include, without limitation, diagnostic and pathology laboratories,\n    logistics and last-mile delivery partners engaged for home sample collection, payment gateways and payment processors,\n    cloud and information technology infrastructure providers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Grievance Officer / Data Protection Officer by email\n  text: Upon expiry of the applicable retention period, we will delete or anonymize your information, save where\n    retention is required under applicable law.\nrights:\n- right: Access summary\n  text: obtain a summary of the Personal Information and Sensitive Personal Data or Information processed by us\n- right: Correction, completion, updating or erasure\n  text: request correction, completion, updating or erasure of your Personal Information and Sensitive Personal\n    Data or Information\n- right: Withdraw consent\n\
  \  text: withdraw your consent at any time, in the manner described in Section 1 (Your Consent) above\n- right: Nominate another individual\n  text: nominate, in the manner prescribed under applicable law, another individual to exercise your rights under\n    this Policy in the event of your death or incapacity\n- right: Grievance redressal\n  text: grievance redressal in the manner described in Section 14 (Grievance Officer, Data Protection Officer and\n    Application Security) below\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/orange-health/privacy/orange-health-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Orange Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobile
- Healthcare
- Diagnostics
- Lab Testing
- Home Collection
- Webhook
- India
---
