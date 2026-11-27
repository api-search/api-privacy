---
api_specs:
- filename: opera-inventory-api-openapi.yml
  format: yaml
  label: Opera Inventory API
  slug: opera-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-inventory-api-openapi.yml
- filename: opera-marketing-api-openapi.yml
  format: yaml
  label: Opera Marketing API
  slug: opera-marketing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-marketing-api-openapi.yml
- filename: opera-report-api-openapi.yml
  format: yaml
  label: Opera Report API
  slug: opera-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-report-api-openapi.yml
- filename: opera-dspreport-api-openapi.yml
  format: yaml
  label: Opera DSP Report API
  slug: opera-dspreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-dspreport-api-openapi.yml
- filename: opera-publisherreport-api-openapi.yml
  format: yaml
  label: Opera Publisher Report API
  slug: opera-publisherreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-publisherreport-api-openapi.yml
- filename: opera-upload-api-openapi.yml
  format: yaml
  label: Opera Upload API
  slug: opera-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-upload-api-openapi.yml
- filename: opera-file-management-api-openapi.yml
  format: yaml
  label: Opera File Management API
  slug: opera-file-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-file-management-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: we ask for a preferred username and an email address
  - category: device
    text: we collect this identifier, as well as Machine ID, hardware specifications (model, release date, etc.), operating system, environment configuration, and feature usage data
  - category: location
    text: your general location (your city or country)
  - category: financial
    text: Your payment data may be stored for up to five years due to regulatory requirements.
  - category: behavioral
    text: the articles you read in the News Feed
  - category: communication
    text: we may ask for information such as your name, age, phone number, email, or postal address
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services to user
    text: To allow you to access certain services.
  - purpose: Improving products
    text: Improving our products.
  - purpose: Monetization
    text: we monetize our products in various ways, primarily by selling advertising within the Applications themselves.
  retention:
  - period: seven days
    scope: Opera account after discontinuation
    text: We retain your data for seven days after you’ve decided to discontinue your Opera account in case you choose to change your mind.
  - period: six months of inactivity
    scope: Unverified-email account
    text: Accounts with unverified email addresses will be deleted after six months of inactivity.
  - period: 365 days
    scope: AI Chat data (logged in)
    text: will be automatically deleted after 365 days if you use AI Chat while logged into your Opera Account.
  - period: up to three years
    scope: Usage statistics
    text: We retain this usage data linked to installation ID for up to three years.
  - period: up to five months
    scope: Crash logs
    text: Crash logs are kept for up to five months.
  - period: up to one year
    scope: Personalized ads profile
    text: We retain this data for up to one year, after which it is deleted automatically.
  rights:
  - right: Access or copy of data
    text: request a copy of your data using your profile page
  - right: Delete data
    text: request a copy of your data using your profile page
  - right: Withdraw consent
    text: If you would like to withdraw your consent, you can go to the Settings menu under ‘Privacy and security’ and ‘Privacy consent settings’
  role:
    text: For the purposes of this Privacy Statement, this is Opera Norway AS.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell users’ personal data to anyone, either to monetize or to provide advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Opera
provenance_date: '2026-11-10'
provider_name: Opera
provider_slug: opera
slug: opera-privacy-policy
source_date: '2026-11-10'
source_filename: opera-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.opera.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Opera\naid: opera\nurl: https://www.opera.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: For the purposes of this Privacy Statement, this is Opera Norway AS.\ndata_categories:\n- category: identifying\n  text: we ask for a preferred username and an email address\n- category: device\n  text: we collect this identifier, as well as Machine ID, hardware specifications (model, release date, etc.),\n    operating system, environment configuration, and feature usage data\n- category: location\n  text: your general location (your city or country)\n- category: financial\n\
  \  text: Your payment data may be stored for up to five years due to regulatory requirements.\n- category: behavioral\n  text: the articles you read in the News Feed\n- category: communication\n  text: we may ask for information such as your name, age, phone number, email, or postal address\npurposes:\n- purpose: Provide services to user\n  text: To allow you to access certain services.\n- purpose: Improving products\n  text: Improving our products.\n- purpose: Monetization\n  text: we monetize our products in various ways, primarily by selling advertising within the Applications themselves.\nretention:\n- scope: Opera account after discontinuation\n  period: seven days\n  text: We retain your data for seven days after you’ve decided to discontinue your Opera account in case you choose\n    to change your mind.\n- scope: Unverified-email account\n  period: six months of inactivity\n  text: Accounts with unverified email addresses will be deleted after six months of inactivity.\n- scope:\
  \ AI Chat data (logged in)\n  period: 365 days\n  text: will be automatically deleted after 365 days if you use AI Chat while logged into your Opera Account.\n- scope: Usage statistics\n  period: up to three years\n  text: We retain this usage data linked to installation ID for up to three years.\n- scope: Crash logs\n  period: up to five months\n  text: Crash logs are kept for up to five months.\n- scope: Personalized ads profile\n  period: up to one year\n  text: We retain this data for up to one year, after which it is deleted automatically.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access or copy of data\n  text: request a copy of your data using your profile page\n- right: Delete data\n  text: request a copy of your data using your profile page\n- right: Withdraw consent\n  text: If you would like to withdraw your consent, you can go to the\
  \ Settings menu under ‘Privacy and security’\n    and ‘Privacy consent settings’\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell users’ personal data to anyone, either to monetize or to provide advertising.\n"
source_yaml_url: https://artifacts.apis.io/opera/privacy/opera-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Opera's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer Technology
- Advertising
- AdTech
- Browser
- Monetization
- OpenRTB
- Marketing
- Mobile SDK
- Header Bidding
- Publisher Monetization
- Reporting
---
