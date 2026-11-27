---
api_specs:
- filename: garner-health-facilities-api-openapi.yml
  format: yaml
  label: Garner Health Facilities API
  slug: garner-health-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner-health/openapi/garner-health-facilities-api-openapi.yml
- filename: garner-health-professionals-api-openapi.yml
  format: yaml
  label: Garner Health Professionals API
  slug: garner-health-professionals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner-health/openapi/garner-health-professionals-api-openapi.yml
- filename: garner-health-provider-annotations-api-openapi.yml
  format: yaml
  label: Garner Health Provider Annotations API
  slug: garner-health-provider-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner-health/openapi/garner-health-provider-annotations-api-openapi.yml
- filename: garner-health-providers-api-openapi.yml
  format: yaml
  label: Garner Health Providers API
  slug: garner-health-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner-health/openapi/garner-health-providers-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers , such as name, email address, phone number, business address, mailing/billing addresses, information used to sign into your account (including username and password), IP address, Social Security Number, and the employee ID assigned by your Employer.
  - category: financial
    text: 'Financial Information for Reimbursements: If you submit a reimbursement request via the Service, subject to the terms of your HRA and in accordance with the Terms of Service , we may collect the financial information necessary to process your reimbursements, such as your bank account number and routing information.'
  - category: health
    text: Health Information about you or your dependents, such as information and documentation related to the payment for medical services, the content of your communications with our Concierge Service, the history of your search, information about your medical history
  - category: location
    text: Location Information , such as your city and zip code and general location information derived from your IP address.
  - category: behavioral
    text: 'Internet or Other Electronic Network Activity Information: When you visit, use, and otherwise interact with the Service, we and our third-party vendors may automatically collect certain information about your device, browser, and interactions with the Services'
  - category: demographic
    text: Demographic Information , such as age, gender, gender identity, income level, marital status, and date of birth.
  - category: professional
    text: Professional or Employment-Related Information , such as your position, company name, Employer Identification Number, employment history, and information about income or other compensation.
  deletion:
    route: Email privacy@getgarner.com
    text: If you would like to request to exercise any of these rights, you may email us at privacy@getgarner.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: To provide the Service, including to maintain your account and authenticate you;
  - purpose: Facilitate transactions
    text: To facilitate transactions through the Service;
  - purpose: Analytics and improvement
    text: To analyze use of the Service;
  - purpose: Marketing and advertising
    text: To market and advertise ourselves and the Service (subject to applicable laws and any preferences you have communicated to us);
  - purpose: Research and development
    text: To conduct research and develop new products and services;
  residency:
  - region: United States
    text: The Service is based and hosted in the United States, and is designed solely for use by United States residents.
  retention:
  - period: null
    scope: General user information
    text: We may retain your information for as long as reasonably necessary for the purposes described in this Privacy Policy or as required by law
  rights:
  - right: Access
    text: Provide you access to and/or a copy of certain personal information we hold about you.
  - right: Correct
    text: Correct or update personal information we hold about you.
  - right: Delete
    text: Delete certain personal information we have about you.
  - right: Opt out of sale and targeted advertising sharing
    text: You have the right to opt out of “sales” of your information and “sharing/use of your information for targeted advertising”
  role:
    text: we collect your information on your Employer’s behalf as a “service provider” or “business associate.”
    value: both
  sale_or_sharing:
    stance: conditional
    text: You can opt out of such “sharing” by emailing us at privacy@getgarner.com .
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Garner Health
provenance_date: '2026-11-09'
provider_name: Garner Health
provider_slug: garner-health
slug: garner-health-privacy-policy
source_date: '2026-11-09'
source_filename: garner-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://garnerhealth.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Garner Health\naid: garner-health\nurl: https://garnerhealth.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we collect your information on your Employer’s behalf as a “service provider” or “business associate.”\ndata_categories:\n- category: identifying\n  text: Identifiers , such as name, email address, phone number, business address, mailing/billing addresses, information\n    used to sign into your account (including username and password), IP address, Social Security Number, and the\n    employee ID assigned by your Employer.\n- category: financial\n  text: 'Financial Information\
  \ for Reimbursements: If you submit a reimbursement request via the Service, subject\n    to the terms of your HRA and in accordance with the Terms of Service , we may collect the financial information\n    necessary to process your reimbursements, such as your bank account number and routing information.'\n- category: health\n  text: Health Information about you or your dependents, such as information and documentation related to the payment\n    for medical services, the content of your communications with our Concierge Service, the history of your search,\n    information about your medical history\n- category: location\n  text: Location Information , such as your city and zip code and general location information derived from your\n    IP address.\n- category: behavioral\n  text: 'Internet or Other Electronic Network Activity Information: When you visit, use, and otherwise interact\n    with the Service, we and our third-party vendors may automatically collect certain information about\
  \ your device,\n    browser, and interactions with the Services'\n- category: demographic\n  text: Demographic Information , such as age, gender, gender identity, income level, marital status, and date of\n    birth.\n- category: professional\n  text: Professional or Employment-Related Information , such as your position, company name, Employer Identification\n    Number, employment history, and information about income or other compensation.\npurposes:\n- purpose: Provide the Service\n  text: To provide the Service, including to maintain your account and authenticate you;\n- purpose: Facilitate transactions\n  text: To facilitate transactions through the Service;\n- purpose: Analytics and improvement\n  text: To analyze use of the Service;\n- purpose: Marketing and advertising\n  text: To market and advertise ourselves and the Service (subject to applicable laws and any preferences you have\n    communicated to us);\n- purpose: Research and development\n  text: To conduct research and\
  \ develop new products and services;\nretention:\n- scope: General user information\n  period: null\n  text: We may retain your information for as long as reasonably necessary for the purposes described in this Privacy\n    Policy or as required by law\nresidency:\n- region: United States\n  text: The Service is based and hosted in the United States, and is designed solely for use by United States residents.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@getgarner.com\n  text: If you would like to request to exercise any of these rights, you may email us at privacy@getgarner.com\n    .\nrights:\n- right: Access\n  text: Provide you access to and/or a copy of certain personal information we hold about you.\n- right: Correct\n  text: Correct or update personal information we hold about you.\n- right: Delete\n  text: Delete certain personal information we have about you.\n- right: Opt out of\
  \ sale and targeted advertising sharing\n  text: You have the right to opt out of “sales” of your information and “sharing/use of your information for targeted\n    advertising”\nsale_or_sharing:\n  stance: conditional\n  text: You can opt out of such “sharing” by emailing us at privacy@getgarner.com .\n"
source_yaml_url: https://artifacts.apis.io/garner-health/privacy/garner-health-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Garner Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Data
- Provider Directory
- Care Navigation
- Claims Analytics
- Health Plans
- Employee Benefits
---
