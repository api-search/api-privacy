---
api_specs:
- filename: findigs-applications-api-openapi.yml
  format: yaml
  label: Findigs Applications API
  slug: findigs-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findigs/openapi/findigs-applications-api-openapi.yml
- filename: findigs-groups-api-openapi.yml
  format: yaml
  label: Findigs Groups API
  slug: findigs-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findigs/openapi/findigs-groups-api-openapi.yml
- filename: findigs-listings-api-openapi.yml
  format: yaml
  label: Findigs Listings API
  slug: findigs-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findigs/openapi/findigs-listings-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers. Your Social Security number and government-issued identification.
  - category: biometric
    text: Biometric information. Faceprints or other scans of face geometry used to identify you.
  - category: financial
    text: Payment information. Your payment card type, last 4 digits of payment card, and billing address, phone number, and email.
  - category: location
    text: Geolocation information. The geolocation information for your city, state and region, including IP-address-based location information and precise geolocation information.
  - category: behavioral
    text: Device, internet or other information about your electronic activity.
  - category: professional
    text: Employment history. Information about where you have worked, including your employer name, job title, and contact information.
  - category: demographic
    text: Demographic information. Your gender, date of birth, zip code, and age.
  deletion:
    route: email support@findigs.com
    text: California users under the age of 18 may request the removal of their content or information publicly posted on the Site or Services by e-mailing us at support@findigs.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide requested services
    text: Receive, process, and confirm your request for Services.
  - purpose: Marketing and promotional
    text: Marketing and promotional purposes, unless you have requested that we do not send you marketing or promotional communications
  - purpose: Verify identity
    text: Verify your identity and accuracy of application documentation you have provided.
  - purpose: Fraud prevention
    text: To protect the Site and Services, Findigs, and others and to prevent fraud, theft and misconduct.
  retention:
  - period: null
    scope: Profile and credentials
    text: We retain your profile information and credentials for as long as you have an account with us.
  - period: null
    scope: Payment data
    text: We retain your payment data for as long as we need to process your purchase or subscription.
  - period: null
    scope: Device/IP data
    text: We retain your device/IP data for as long as we need it to ensure that our systems are working appropriately, effectively and efficiently.
  rights:
  - right: Opt out of marketing emails
    text: You can opt out of receiving marketing e-mails from us by following the link provided at the bottom of all marketing e-mails you receive from us.
  - right: Opt out of third-party sharing for direct marketing
    text: To opt out of sharing your Personal Information with third parties for their direct marketing purposes, please e-mail us at support@findigs.com
  - right: Opt out of sale (Nevada)
    text: If you are a resident of Nevada, you have the right to opt-out of the sale of certain Personal Information to third parties.
  role:
    text: we are a service provider to the property manager and do not make any decisions about your eligibility for housing
    value: both
  sale_or_sharing:
    stance: conditional
    text: Please note that we do not currently sell your Personal Information as sales are defined in Nevada Revised Statutes Chapter 603A.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Findigs
provenance_date: '2026-11-09'
provider_name: Findigs
provider_slug: findigs
slug: findigs-privacy-policy
source_date: '2026-11-09'
source_filename: findigs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.findigs.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Findigs\naid: findigs\nurl: https://www.findigs.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we are a service provider to the property manager and do not make any decisions about your eligibility for\n    housing\ndata_categories:\n- category: identifying\n  text: Identifiers. Your Social Security number and government-issued identification.\n- category: biometric\n  text: Biometric information. Faceprints or other scans of face geometry used to identify you.\n- category: financial\n  text: Payment information. Your payment card type, last 4 digits of payment card, and\
  \ billing address, phone number,\n    and email.\n- category: location\n  text: Geolocation information. The geolocation information for your city, state and region, including IP-address-based\n    location information and precise geolocation information.\n- category: behavioral\n  text: Device, internet or other information about your electronic activity.\n- category: professional\n  text: Employment history. Information about where you have worked, including your employer name, job title, and\n    contact information.\n- category: demographic\n  text: Demographic information. Your gender, date of birth, zip code, and age.\npurposes:\n- purpose: Provide requested services\n  text: Receive, process, and confirm your request for Services.\n- purpose: Marketing and promotional\n  text: Marketing and promotional purposes, unless you have requested that we do not send you marketing or promotional\n    communications\n- purpose: Verify identity\n  text: Verify your identity and accuracy of\
  \ application documentation you have provided.\n- purpose: Fraud prevention\n  text: To protect the Site and Services, Findigs, and others and to prevent fraud, theft and misconduct.\nretention:\n- scope: Profile and credentials\n  period: null\n  text: We retain your profile information and credentials for as long as you have an account with us.\n- scope: Payment data\n  period: null\n  text: We retain your payment data for as long as we need to process your purchase or subscription.\n- scope: Device/IP data\n  period: null\n  text: We retain your device/IP data for as long as we need it to ensure that our systems are working appropriately,\n    effectively and efficiently.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@findigs.com\n  text: California users under the age of 18 may request the removal of their content or information publicly posted\n    on the Site or Services\
  \ by e-mailing us at support@findigs.com .\nrights:\n- right: Opt out of marketing emails\n  text: You can opt out of receiving marketing e-mails from us by following the link provided at the bottom of all\n    marketing e-mails you receive from us.\n- right: Opt out of third-party sharing for direct marketing\n  text: To opt out of sharing your Personal Information with third parties for their direct marketing purposes,\n    please e-mail us at support@findigs.com\n- right: Opt out of sale (Nevada)\n  text: If you are a resident of Nevada, you have the right to opt-out of the sale of certain Personal Information\n    to third parties.\nsale_or_sharing:\n  stance: conditional\n  text: Please note that we do not currently sell your Personal Information as sales are defined in Nevada Revised\n    Statutes Chapter 603A.\n"
source_yaml_url: https://artifacts.apis.io/findigs/privacy/findigs-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Findigs's own page on 2026-11-09.
synthetic: false
tags:
- rental-screening
- Tenant Screening
- Resident Screening
- rental-application
- Underwriting
- Decisioning
- Identity Verification
- Income Verification
- Credit Check
- Background Checks
- Fraud Prevention
- Property Management
- Real Estate
- PropTech
- FCRA
- Fair Housing
- Webhook
---
