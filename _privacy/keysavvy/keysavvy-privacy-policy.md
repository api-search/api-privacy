---
api_specs:
- filename: keysavvy-authentication-api-openapi.yml
  format: yaml
  label: KeySavvy Authentication API
  slug: keysavvy-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-authentication-api-openapi.yml
- filename: keysavvy-deal-documents-api-openapi.yml
  format: yaml
  label: KeySavvy Deal Documents API
  slug: keysavvy-deal-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-deal-documents-api-openapi.yml
- filename: keysavvy-deal-management-api-openapi.yml
  format: yaml
  label: KeySavvy Deal Management API
  slug: keysavvy-deal-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-deal-management-api-openapi.yml
- filename: keysavvy-documents-api-openapi.yml
  format: yaml
  label: KeySavvy Documents API
  slug: keysavvy-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-documents-api-openapi.yml
- filename: keysavvy-keysavvy-partner-api-api-openapi.yml
  format: yaml
  label: KeySavvy KeySavvy Partner API
  slug: keysavvy-keysavvy-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-keysavvy-partner-api-api-openapi.yml
- filename: keysavvy-marketplace-management-api-openapi.yml
  format: yaml
  label: KeySavvy Marketplace Management API
  slug: keysavvy-marketplace-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-marketplace-management-api-openapi.yml
- filename: keysavvy-organization-management-api-openapi.yml
  format: yaml
  label: KeySavvy Organization Management API
  slug: keysavvy-organization-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-organization-management-api-openapi.yml
- filename: keysavvy-reporting-api-openapi.yml
  format: yaml
  label: KeySavvy Reporting API
  slug: keysavvy-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-reporting-api-openapi.yml
- filename: keysavvy-user-management-api-openapi.yml
  format: yaml
  label: KeySavvy User Management API
  slug: keysavvy-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-user-management-api-openapi.yml
- filename: keysavvy-vehicle-management-api-openapi.yml
  format: yaml
  label: KeySavvy Vehicle Management API
  slug: keysavvy-vehicle-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-vehicle-management-api-openapi.yml
- filename: keysavvy-webhook-management-api-openapi.yml
  format: yaml
  label: KeySavvy Webhook Management API
  slug: keysavvy-webhook-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-webhook-management-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: we may receive information about you such as your name, email address, phone number
  - category: financial
    text: Payment Data. We may collect data necessary to process your payment if you make purchases, such as your payment instrument (such as a credit card number)
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: intent data (or user behavior data)
  - category: identifying
    text: your vehicle identification number, vehicle owner names, registered vehicle address, vehicle loan status, and billing addresses
  deletion:
    route: Contact us or log in to account settings; request account termination
    text: 'If you would at any time like to review or change the information in your account or terminate your account, you can: Contact us using the contact information provided. Log in to your account settings and update your user account.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and authentication
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: deliver services
    text: To deliver and facilitate delivery of services to the user.
  - purpose: marketing and advertising
    text: To market and advertise our Services. We may process your information to send direct marketing emails and target advertisements to you through third party providers on third party web properties.
  - purpose: security and fraud prevention
    text: To protect our Services. We may process your information as part of our efforts to keep our Services safe and secure, including fraud monitoring and prevention.
  - purpose: legal compliance
    text: To comply with our legal obligations. We may process your information to comply with our legal obligations, respond to legal requests, and exercise, establish, or defend our legal rights.
  retention:
  - period: null
    scope: account termination
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  rights:
  - right: review, change, or terminate account
    text: You may review, change, or terminate your account at any time.
  - right: opt out of marketing emails
    text: You can opt out of marketing emails by following the "unsubscribe" instructions in the emails we send
  - right: opt out of location collection
    text: You can opt out of allowing us to collect this information either by refusing access to the information or by disabling your Location setting on your device.
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
name: KeySavvy
provenance_date: '2026-11-09'
provider_name: KeySavvy
provider_slug: keysavvy
slug: keysavvy-privacy-policy
source_date: '2026-11-09'
source_filename: keysavvy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.keysavvy.com:443/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: KeySavvy\naid: keysavvy\nurl: https://www.keysavvy.com:443/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we may receive information about you such as your name, email address, phone number\n- category: financial\n  text: Payment Data. We may collect data necessary to process your payment if you make purchases, such as your\n    payment instrument (such as a credit card number)\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access\
  \ the Services.\n- category: location\n  text: Location Data. We collect location data such as information about your device's location, which can be either\n    precise or imprecise.\n- category: behavioral\n  text: intent data (or user behavior data)\n- category: identifying\n  text: your vehicle identification number, vehicle owner names, registered vehicle address, vehicle loan status,\n    and billing addresses\npurposes:\n- purpose: account creation and authentication\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: deliver services\n  text: To deliver and facilitate delivery of services to the user.\n- purpose: marketing and advertising\n  text: To market and advertise our Services. We may process your information to send direct marketing emails and\n    target advertisements to you through third party providers on third party web properties.\n- purpose: security and fraud prevention\n  text: To protect our Services. We may\
  \ process your information as part of our efforts to keep our Services safe\n    and secure, including fraud monitoring and prevention.\n- purpose: legal compliance\n  text: To comply with our legal obligations. We may process your information to comply with our legal obligations,\n    respond to legal requests, and exercise, establish, or defend our legal rights.\nretention:\n- scope: account termination\n  period: null\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us or log in to account settings; request account termination\n  text: 'If you would at any time like to review or change the information in your account or terminate your account,\n    you can: Contact us using the contact information provided. Log in to your account settings\
  \ and update your\n    user account.'\nrights:\n- right: review, change, or terminate account\n  text: You may review, change, or terminate your account at any time.\n- right: opt out of marketing emails\n  text: You can opt out of marketing emails by following the \"unsubscribe\" instructions in the emails we send\n- right: opt out of location collection\n  text: You can opt out of allowing us to collect this information either by refusing access to the information\n    or by disabling your Location setting on your device.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/keysavvy/privacy/keysavvy-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from KeySavvy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Marketplace
- Fintech
---
