---
api_specs:
- filename: garner-facilities-api-openapi.yml
  format: yaml
  label: Garner Facilities API
  slug: garner-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-facilities-api-openapi.yml
- filename: garner-professionals-api-openapi.yml
  format: yaml
  label: Garner Professionals API
  slug: garner-professionals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-professionals-api-openapi.yml
- filename: garner-provider-annotations-api-openapi.yml
  format: yaml
  label: Garner Provider Annotations API
  slug: garner-provider-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-provider-annotations-api-openapi.yml
- filename: garner-providers-api-openapi.yml
  format: yaml
  label: Garner Providers API
  slug: garner-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-providers-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers , such as name, email address, phone number, business address, mailing/billing addresses, information used to sign into your account (including username and password), IP address, Social Security Number
  - category: financial
    text: 'Financial Information for Reimbursements: If you submit a reimbursement request via the Service, subject to the terms of your HRA and in accordance with the Terms of Service , we may collect the financial information necessary to process your reimbursements, such as your bank account number and routing information.'
  - category: location
    text: Location Information , such as your city and zip code and general location information derived from your IP address.
  - category: health
    text: Health Information about you or your dependents, such as information and documentation related to the payment for medical services
  - category: biometric
    text: 'Audio and Visual Information: The Mobile App allows you the option to submit claims documentation for reimbursement by taking a photo of the documentation'
  - category: behavioral
    text: Inferences based on any of the information above, such as inferences about you, your preferences, and your health.
  - category: device
    text: your device name, operating system, device ID; your browser type and settings
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
  - purpose: Marketing
    text: To market and advertise ourselves and the Service (subject to applicable laws and any preferences you have communicated to us);
  - purpose: Research and development
    text: To conduct research and develop new products and services;
  - purpose: Fraud prevention and security
    text: To prevent fraud, criminal activity, or misuses of our Service, and to ensure the security of the Service and our IT systems, architecture, and networks;
  residency:
  - region: United States
    text: The Service is based and hosted in the United States, and is designed solely for use by United States residents.
  retention:
  - period: null
    scope: Customer and user information
    text: We may retain your information for as long as reasonably necessary for the purposes described in this Privacy Policy or as required by law (e.g. for tax, legal, accounting, medical record retention, or other purposes), whichever is longer.
  rights:
  - right: Access
    text: Provide you access to and/or a copy of certain personal information we hold about you.
  - right: Correct
    text: Correct or update personal information we hold about you.
  - right: Delete
    text: Delete certain personal information we have about you.
  - right: Opt out of sales and sharing
    text: You have the right to opt out of “sales” of your information and “sharing/use of your information for targeted advertising”
  role:
    text: we collect your information on your Employer’s behalf as a “service provider” or “business associate.”
    value: both
  sale_or_sharing:
    stance: conditional
    text: We may disclose your personal information to third parties in connection with our advertising activities.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Garner
provenance_date: '2026-11-09'
provider_name: Garner
provider_slug: garner
slug: garner-privacy-policy
source_date: '2026-11-09'
source_filename: garner-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://garnerhealth.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Garner\naid: garner\nurl: https://garnerhealth.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we collect your information on your Employer’s behalf as a “service provider” or “business associate.”\ndata_categories:\n- category: identifying\n  text: Identifiers , such as name, email address, phone number, business address, mailing/billing addresses, information\n    used to sign into your account (including username and password), IP address, Social Security Number\n- category: financial\n  text: 'Financial Information for Reimbursements: If you submit a reimbursement request via\
  \ the Service, subject\n    to the terms of your HRA and in accordance with the Terms of Service , we may collect the financial information\n    necessary to process your reimbursements, such as your bank account number and routing information.'\n- category: location\n  text: Location Information , such as your city and zip code and general location information derived from your\n    IP address.\n- category: health\n  text: Health Information about you or your dependents, such as information and documentation related to the payment\n    for medical services\n- category: biometric\n  text: 'Audio and Visual Information: The Mobile App allows you the option to submit claims documentation for reimbursement\n    by taking a photo of the documentation'\n- category: behavioral\n  text: Inferences based on any of the information above, such as inferences about you, your preferences, and your\n    health.\n- category: device\n  text: your device name, operating system, device ID; your browser\
  \ type and settings\npurposes:\n- purpose: Provide the Service\n  text: To provide the Service, including to maintain your account and authenticate you;\n- purpose: Marketing\n  text: To market and advertise ourselves and the Service (subject to applicable laws and any preferences you have\n    communicated to us);\n- purpose: Research and development\n  text: To conduct research and develop new products and services;\n- purpose: Fraud prevention and security\n  text: To prevent fraud, criminal activity, or misuses of our Service, and to ensure the security of the Service\n    and our IT systems, architecture, and networks;\nretention:\n- scope: Customer and user information\n  period: null\n  text: We may retain your information for as long as reasonably necessary for the purposes described in this Privacy\n    Policy or as required by law (e.g. for tax, legal, accounting, medical record retention, or other purposes),\n    whichever is longer.\nresidency:\n- region: United States\n  text:\
  \ The Service is based and hosted in the United States, and is designed solely for use by United States residents.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@getgarner.com\n  text: If you would like to request to exercise any of these rights, you may email us at privacy@getgarner.com\n    .\nrights:\n- right: Access\n  text: Provide you access to and/or a copy of certain personal information we hold about you.\n- right: Correct\n  text: Correct or update personal information we hold about you.\n- right: Delete\n  text: Delete certain personal information we have about you.\n- right: Opt out of sales and sharing\n  text: You have the right to opt out of “sales” of your information and “sharing/use of your information for targeted\n    advertising”\nsale_or_sharing:\n  stance: conditional\n  text: We may disclose your personal information to third parties in connection with our advertising\
  \ activities.\n"
source_yaml_url: https://artifacts.apis.io/garner/privacy/garner-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Garner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Healthcare
- Provider Data
- Care Navigation
- Health Insurance
- Claims Analytics
- Provider Search
- Doctor Quality
---
