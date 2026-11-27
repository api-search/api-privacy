---
api_specs:
- filename: myfitnesspal-notifications-asyncapi.yml
  format: yaml
  label: MyFitnessPal API v2
  slug: myfitnesspal-api-v2
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/myfitnesspal/asyncapi/myfitnesspal-notifications-asyncapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and Profile Information . This includes your name, email address, general location information (country/zip code)
  - category: health
    text: Food and Activity Diary Data may include sensitive personal information when the information indicates or allows someone to infer a health condition.
  - category: financial
    text: This information is not directly collected or stored by MyFitnessPal but instead, is collected by a third party payment platform MyFitnessPal uses to facilitate the transaction.
  - category: device
    text: This may include details about your browser, operating system, or device
  - category: location
    text: general location information (including inferred location based off of your IP address)
  - category: behavioral
    text: actions that you take while using the Services, information about how you interact with the Services
  - category: communication
    text: 'This includes your: email address, name, and any other content provided when you communicate with us'
  deletion:
    route: MyFitnessPal Privacy Request Center
    text: The right to request that we delete your personal information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services
    text: We use your personal information in connection with the provision, administration, and management of the Services
  - purpose: targeted advertising
    text: We engage in targeted advertising.
  - purpose: analytics
    text: We engage third-party analytics providers to help us analyze traffic to evaluate usage of the Services
  - purpose: enhance and personalize services
    text: We use your personal information to improve and enhance our Services, including through the use of various technologies (e.g., business intelligence tools, machine learning systems, and artificial intelligence)
  residency:
  - region: United States
    text: Personal information of residents of Korea is processed in the United States by MyFitnessPal.
  retention:
  - period: null
    scope: general
    text: We will retain your personal information as long as necessary to fulfill the purposes outlined in this Policy
  rights:
  - right: access and data portability
    text: The right to confirm whether we are processing your personal information
  - right: correction
    text: The right to request that we correct inaccuracies in your personal information
  - right: opt out of sharing for cross-context behavioral advertising
    text: You have the right to opt out of sharing your personal information with third parties that generate a profile about you for marketing purposes.
  role:
    text: For the purposes of applicable data protection laws, MyFitnessPal, Inc. is the controller of the personal information you provide us.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: While MyFitnessPal does not expressly “sell” information to others, certain uses of Functional Cookies and/or Targeted Advertising Cookies on our website to collect, use, and disclose information may constitute “sales” or “sharing” of personal information
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We have put in place adequate measures, and where necessary, we have implemented additional contractual, organizational and technical measures to protect your personal information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MyFitnessPal
provenance_date: '2026-11-10'
provider_name: MyFitnessPal
provider_slug: myfitnesspal
slug: myfitnesspal-privacy-policy
source_date: '2026-11-10'
source_filename: myfitnesspal-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.myfitnesspal.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MyFitnessPal\naid: myfitnesspal\nurl: https://www.myfitnesspal.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: For the purposes of applicable data protection laws, MyFitnessPal, Inc. is the controller of the personal\n    information you provide us.\ndata_categories:\n- category: identifying\n  text: Account and Profile Information . This includes your name, email address, general location information (country/zip\n    code)\n- category: health\n  text: Food and Activity Diary Data may include sensitive personal information when the information indicates\
  \ or\n    allows someone to infer a health condition.\n- category: financial\n  text: This information is not directly collected or stored by MyFitnessPal but instead, is collected by a third\n    party payment platform MyFitnessPal uses to facilitate the transaction.\n- category: device\n  text: This may include details about your browser, operating system, or device\n- category: location\n  text: general location information (including inferred location based off of your IP address)\n- category: behavioral\n  text: actions that you take while using the Services, information about how you interact with the Services\n- category: communication\n  text: 'This includes your: email address, name, and any other content provided when you communicate with us'\npurposes:\n- purpose: provide services\n  text: We use your personal information in connection with the provision, administration, and management of the\n    Services\n- purpose: targeted advertising\n  text: We engage in targeted advertising.\n\
  - purpose: analytics\n  text: We engage third-party analytics providers to help us analyze traffic to evaluate usage of the Services\n- purpose: enhance and personalize services\n  text: We use your personal information to improve and enhance our Services, including through the use of various\n    technologies (e.g., business intelligence tools, machine learning systems, and artificial intelligence)\nretention:\n- scope: general\n  period: null\n  text: We will retain your personal information as long as necessary to fulfill the purposes outlined in this Policy\nresidency:\n- region: United States\n  text: Personal information of residents of Korea is processed in the United States by MyFitnessPal.\ntransfers:\n- mechanism: other\n  text: We have put in place adequate measures, and where necessary, we have implemented additional contractual,\n    organizational and technical measures to protect your personal information.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: MyFitnessPal Privacy Request Center\n  text: The right to request that we delete your personal information\nrights:\n- right: access and data portability\n  text: The right to confirm whether we are processing your personal information\n- right: correction\n  text: The right to request that we correct inaccuracies in your personal information\n- right: opt out of sharing for cross-context behavioral advertising\n  text: You have the right to opt out of sharing your personal information with third parties that generate a profile\n    about you for marketing purposes.\nsale_or_sharing:\n  stance: conditional\n  text: While MyFitnessPal does not expressly “sell” information to others, certain uses of Functional Cookies and/or\n    Targeted Advertising Cookies on our website to collect, use, and disclose information may constitute “sales”\n    or “sharing” of personal information\n"
source_yaml_url: https://artifacts.apis.io/myfitnesspal/privacy/myfitnesspal-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from MyFitnessPal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Health and Fitness
- Nutrition
- Fitness Tracking
- Food Diary
- Wellness
- Webhook
- OAuth
- Authentication
---
