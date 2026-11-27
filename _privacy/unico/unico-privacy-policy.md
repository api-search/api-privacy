---
api_specs:
- filename: unico-api-integration.postman_collection.json
  format: json
  label: Unico IDCloud API
  slug: idcloud-api
  spec_type: Postman
  url: https://artifacts.apis.io/unico/postman/unico-api-integration.postman_collection.json
- filename: unico-web-sdk-integration.postman_collection.json
  format: json
  label: Unico IDCloud Web & SDK API
  slug: idcloud-web-sdk
  spec_type: Postman
  url: https://artifacts.apis.io/unico/postman/unico-web-sdk-integration.postman_collection.json
- filename: unico-oauth2.postman_collection.json
  format: json
  label: Unico Identity OAuth2
  slug: identity-oauth2
  spec_type: Postman
  url: https://artifacts.apis.io/unico/postman/unico-oauth2.postman_collection.json
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, phone number, date of birth, gender, marital status, business name, email address, postal address
  - category: biometric
    text: biometric information (specifically, facial scans)
  - category: device
    text: your hardware model, operating system version, mobile network, IP address, unique device identifiers, browser type, and app version
  - category: behavioral
    text: access times, pages viewed, links clicked, and the page you visited before navigating to our Services
  - category: location
    text: we may infer aspects of your identity or device location based on device usage data, precise geolocation, or facial scan data processed during verification
  - category: professional
    text: information regarding the company you work for and your title
  deletion:
    route: Email privacy.us@unico.io to request deletion
    text: Request correction of inaccurate personal information or request deletion of your personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve services
    text: Provide, maintain, and improve our Services
  - purpose: Identity verification
    text: generating the unique human token for identity verification
  - purpose: Security and fraud prevention
    text: Detect, investigate, and prevent security incidents and other malicious, deceptive, fraudulent, or illegal activity
  - purpose: Marketing communications
    text: Communicate with you about products, services, and events offered by Unico and others
  - purpose: Analytics
    text: We use this information to analyze usage trends, determine content popularity, and better understand your online activity.
  retention:
  - period: null
    scope: Personal information generally
    text: We store personal information for as long as necessary to carry out the purposes for which we originally collected it
  - period: null
    scope: Biometric information
    text: For biometric information retention periods, please refer to Unico Biometric Data Policy .
  rights:
  - right: Access
    text: Confirm whether we process your personal data and request access to it
  - right: Correction
    text: Request correction of inaccurate personal information
  - right: Deletion
    text: request deletion of your personal data
  - right: Opt-out of profiling or automated decision-making
    text: Opt out of profiling or automated decision-making.
  - right: Limit sensitive data processing
    text: Limit or opt out of the processing of sensitive personal information (such as facial scans)
  - right: Appeal and non-discrimination
    text: Exercise your rights without discrimination, and appeal any decision if we decline to fulfill a privacy request.
  role:
    text: Unico acts strictly as a service provider on behalf of our clients (the data controllers).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or share it for targeted advertising purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Unico
provenance_date: '2026-11-10'
provider_name: Unico
provider_slug: unico
slug: unico-privacy-policy
source_date: '2026-11-10'
source_filename: unico-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://devcenter.unico.io/privacy/usa/policies/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Unico\naid: unico\nurl: https://devcenter.unico.io/privacy/usa/policies/privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Unico acts strictly as a service provider on behalf of our clients (the data controllers).\ndata_categories:\n- category: identifying\n  text: name, phone number, date of birth, gender, marital status, business name, email address, postal address\n- category: biometric\n  text: biometric information (specifically, facial scans)\n- category: device\n  text: your hardware model, operating system version, mobile network, IP address, unique device identifiers, browser\n\
  \    type, and app version\n- category: behavioral\n  text: access times, pages viewed, links clicked, and the page you visited before navigating to our Services\n- category: location\n  text: we may infer aspects of your identity or device location based on device usage data, precise geolocation,\n    or facial scan data processed during verification\n- category: professional\n  text: information regarding the company you work for and your title\npurposes:\n- purpose: Provide, maintain, and improve services\n  text: Provide, maintain, and improve our Services\n- purpose: Identity verification\n  text: generating the unique human token for identity verification\n- purpose: Security and fraud prevention\n  text: Detect, investigate, and prevent security incidents and other malicious, deceptive, fraudulent, or illegal\n    activity\n- purpose: Marketing communications\n  text: Communicate with you about products, services, and events offered by Unico and others\n- purpose: Analytics\n  text:\
  \ We use this information to analyze usage trends, determine content popularity, and better understand your\n    online activity.\nretention:\n- scope: Personal information generally\n  period: null\n  text: We store personal information for as long as necessary to carry out the purposes for which we originally\n    collected it\n- scope: Biometric information\n  period: null\n  text: For biometric information retention periods, please refer to Unico Biometric Data Policy .\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy.us@unico.io to request deletion\n  text: Request correction of inaccurate personal information or request deletion of your personal data.\nrights:\n- right: Access\n  text: Confirm whether we process your personal data and request access to it\n- right: Correction\n  text: Request correction of inaccurate personal information\n- right: Deletion\n  text: request\
  \ deletion of your personal data\n- right: Opt-out of profiling or automated decision-making\n  text: Opt out of profiling or automated decision-making.\n- right: Limit sensitive data processing\n  text: Limit or opt out of the processing of sensitive personal information (such as facial scans)\n- right: Appeal and non-discrimination\n  text: Exercise your rights without discrimination, and appeal any decision if we decline to fulfill a privacy\n    request.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or share it for targeted advertising purposes.\n"
source_yaml_url: https://artifacts.apis.io/unico/privacy/unico-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Unico's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- Biometrics
- Facial Recognition
- Liveness Detection
- KYC
- Fraud Prevention
- Onboarding
- Authentication
- AML
- Age Verification
- Document Verification
- Identity
- Brazil
- Latin America
---
