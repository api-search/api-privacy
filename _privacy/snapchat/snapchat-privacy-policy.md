---
api_specs:
- filename: snapchat-conversion-events-api-openapi.yml
  format: yaml
  label: Snapchat Conversion Events API
  slug: snapchat-conversion-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snapchat/openapi/snapchat-conversion-events-api-openapi.yml
- filename: snapchat-user-profile-api-openapi.yml
  format: yaml
  label: Snapchat User Profile API
  slug: snapchat-user-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snapchat/openapi/snapchat-user-profile-api-openapi.yml
- filename: snapchat-oauth-api-openapi.yml
  format: yaml
  label: Snapchat O Auth API
  slug: snapchat-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snapchat/openapi/snapchat-oauth-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: account details (information about you, like your name, username, email address, birthday, and phone number)
  - category: location
    text: precise location information (precise location through methods like GPS signals)
  - category: financial
    text: payment information, so we can process the payment, and transaction history
  - category: device
    text: device information (such as your device hardware or software, operating system, device memory, advertising identifiers, apps installed, browser type
  - category: behavioral
    text: usage information (information about how you interact with our Services
  - category: communication
    text: content and communications shared with Support
  - category: demographic
    text: estimate or infer your age
  deletion:
    route: Delete your information within the app or by deleting your account
    text: If you want to delete your account, learn how here . You can also delete some information within our Services
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and maintain services
    text: We use the information we collect in order to operate, deliver, and maintain our Services.
  - purpose: personalization
    text: Personalize Your Experience & Give Context
  - purpose: develop algorithms and machine learning models
    text: we also develop and improve the algorithms and machine learning models
  - purpose: safety and security
    text: We use your information to enhance the safety and security of our Services, verify Snapchatter identity or age, and prevent fraud or other unauthorized or illegal activity.
  - purpose: analytics
    text: We perform analytics in order to identify, monitor, and analyze trends and usage.
  residency:
  - region: United States
    text: we may collect your personal information from, transfer it to, and store and process it in the United States or other countries outside of where you live
  retention:
  - period: 24 hours
    scope: Chats sent in Snapchat
    text: our systems are designed to delete Chats you send within 24 hours after your friend reads it
  - period: null
    scope: general
    text: As a general rule, we keep information as long as you tell us to, and otherwise as long as we need it to provide our Services, or as required by law.
  rights:
  - right: access and update
    text: You can access and edit most of your basic information
  - right: download data
    text: You can make a request in our Download My Data tool to export a copy of your Snapchat information.
  - right: object to processing
    text: Depending on where you live and the particular data we are processing, you may have the right to object to our processing of that information.
  - right: opt out of promotional messages
    text: You have the option to opt out or unsubscribe from promotional emails and messages sent by SMS or other messaging platforms.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We maintain a list of categories of service providers here .
    url: null
  transfers:
  - mechanism: other
    text: we ensure safeguards are in place to protect the data as required by law where you live
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Snapchat
provenance_date: '2026-11-10'
provider_name: Snapchat
provider_slug: snapchat
slug: snapchat-privacy-policy
source_date: '2026-11-10'
source_filename: snapchat-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://values.snap.com/privacy/privacy-policy?lang=en-US
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Snapchat\naid: snapchat\nurl: https://values.snap.com/privacy/privacy-policy?lang=en-US\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: account details (information about you, like your name, username, email address, birthday, and phone number)\n- category: location\n  text: precise location information (precise location through methods like GPS signals)\n- category: financial\n  text: payment information, so we can process the payment, and transaction history\n- category: device\n  text: device information (such as your device hardware\
  \ or software, operating system, device memory, advertising\n    identifiers, apps installed, browser type\n- category: behavioral\n  text: usage information (information about how you interact with our Services\n- category: communication\n  text: content and communications shared with Support\n- category: demographic\n  text: estimate or infer your age\npurposes:\n- purpose: operate and maintain services\n  text: We use the information we collect in order to operate, deliver, and maintain our Services.\n- purpose: personalization\n  text: Personalize Your Experience & Give Context\n- purpose: develop algorithms and machine learning models\n  text: we also develop and improve the algorithms and machine learning models\n- purpose: safety and security\n  text: We use your information to enhance the safety and security of our Services, verify Snapchatter identity\n    or age, and prevent fraud or other unauthorized or illegal activity.\n- purpose: analytics\n  text: We perform analytics in\
  \ order to identify, monitor, and analyze trends and usage.\nretention:\n- scope: Chats sent in Snapchat\n  period: 24 hours\n  text: our systems are designed to delete Chats you send within 24 hours after your friend reads it\n- scope: general\n  period: null\n  text: As a general rule, we keep information as long as you tell us to, and otherwise as long as we need it to\n    provide our Services, or as required by law.\nresidency:\n- region: United States\n  text: we may collect your personal information from, transfer it to, and store and process it in the United States\n    or other countries outside of where you live\ntransfers:\n- mechanism: other\n  text: we ensure safeguards are in place to protect the data as required by law where you live\nsubprocessors:\n  url: null\n  text: We maintain a list of categories of service providers here .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your information within the app or by deleting your account\n\
  \  text: If you want to delete your account, learn how here . You can also delete some information within our Services\nrights:\n- right: access and update\n  text: You can access and edit most of your basic information\n- right: download data\n  text: You can make a request in our Download My Data tool to export a copy of your Snapchat information.\n- right: object to processing\n  text: Depending on where you live and the particular data we are processing, you may have the right to object\n    to our processing of that information.\n- right: opt out of promotional messages\n  text: You have the option to opt out or unsubscribe from promotional emails and messages sent by SMS or other\n    messaging platforms.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/snapchat/privacy/snapchat-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 22 quoted statements, read from Snapchat's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Augmented Reality
- Marketing
- Messaging
- Social Media
---
