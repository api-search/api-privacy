---
api_specs:
- filename: fitbit-user-api-openapi.yml
  format: yaml
  label: Fitbit User API
  slug: fitbit-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbit/openapi/fitbit-user-api-openapi.yml
- filename: fitbit-foods-api-openapi.yml
  format: yaml
  label: Fitbit Foods API
  slug: fitbit-foods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbit/openapi/fitbit-foods-api-openapi.yml
- filename: fitbit-oauth2-api-openapi.yml
  format: yaml
  label: Fitbit Oauth2 API
  slug: fitbit-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbit/openapi/fitbit-oauth2-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers , like your name or username, email address, mailing address, phone number, IP address, account ID, device ID, cookie ID, and other similar identifiers.
  - category: health
    text: Demographic information , such as your gender, age, health information, and physical characteristics or description, which may be protected by law.
  - category: financial
    text: Commercial information , including your payment information and records of the Services or devices you purchased, obtained, or considered
  - category: biometric
    text: Biometric information , such as your exercise, activity, sleep, or health data, including the number of steps you take, distance traveled, calories burned, weight, heart rate, sleep stages
  - category: location
    text: Geolocation data , including GPS signals, device sensors, Wi-Fi access points, and cell tower IDs, if you have granted us access to that information.
  - category: communication
    text: If you contact us or participate in a survey, contest, or promotion, we collect the information you submit such as your name, contact information, and message.
  deletion:
    route: Account settings and tools; account deletion
    text: while most of your information will be deleted within 30 days, it may take up to 90 days to delete all of your information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Services
    text: we need to use your information to provide you with your Fitbit dashboard tracking your exercise, activity, and other trends
  - purpose: Improve, personalize, and develop the Services
    text: develop new features and Services, which may include generative artificial intelligence models.
  - purpose: Communicate with you
    text: We use your information when needed to send you Service notifications and respond to you when you contact us.
  - purpose: Promote safety and security
    text: protect against fraud and abuse, respond to a legal request or claim, conduct audits, and enforce our terms and policies.
  retention:
  - period: null
    scope: Account information
    text: We keep your account information, like your name, email address, and password, for as long as your account is in existence
  - period: null
    scope: Contact list
    text: when you provide your contact list for finding friends on the Services, we delete the list after it is used for adding contacts as friends.
  rights:
  - right: Access and export
    text: Using your account settings, you can also download information in a commonly used file format
  - right: Edit and delete
    text: By logging into your account and using your account settings, you can change and delete your personal information.
  - right: Object to data use
    text: For example, through your privacy settings, you can limit how your information is visible to other users of the Services
  - right: Withdraw consent
    text: You can use your account settings and tools to withdraw your consent at any time
  - right: Lodge complaint
    text: You also have a right to lodge a complaint with your local data protection authority or with the Irish Data Protection Commission
  role:
    text: Fitbit International Unlimited, an Irish company, is your data controller and provides the Services if you live in the EEA, UK, or Switzerland.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell the personal information of our users.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: EU-U.S. and Swiss-U.S. Data Privacy Frameworks, and the UK Extension to the EU-U.S. DPF.
  - mechanism: adequacy
    text: European Commission’s , the United Kingdom’s and Switzerland’s Adequacy Decisions.
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses and supplementary measures.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fitbit
provenance_date: '2026-11-09'
provider_name: Fitbit
provider_slug: fitbit
slug: fitbit-privacy-policy
source_date: '2026-11-09'
source_filename: fitbit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://support.google.com/product-documentation/answer/14815921
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fitbit\naid: fitbit\nurl: https://support.google.com/product-documentation/answer/14815921\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Fitbit International Unlimited, an Irish company, is your data controller and provides the Services if you\n    live in the EEA, UK, or Switzerland.\ndata_categories:\n- category: identifying\n  text: Identifiers , like your name or username, email address, mailing address, phone number, IP address, account\n    ID, device ID, cookie ID, and other similar identifiers.\n- category: health\n  text: Demographic information , such as your gender, age, health\
  \ information, and physical characteristics or\n    description, which may be protected by law.\n- category: financial\n  text: Commercial information , including your payment information and records of the Services or devices you purchased,\n    obtained, or considered\n- category: biometric\n  text: Biometric information , such as your exercise, activity, sleep, or health data, including the number of\n    steps you take, distance traveled, calories burned, weight, heart rate, sleep stages\n- category: location\n  text: Geolocation data , including GPS signals, device sensors, Wi-Fi access points, and cell tower IDs, if you\n    have granted us access to that information.\n- category: communication\n  text: If you contact us or participate in a survey, contest, or promotion, we collect the information you submit\n    such as your name, contact information, and message.\npurposes:\n- purpose: Provide and maintain the Services\n  text: we need to use your information to provide you with\
  \ your Fitbit dashboard tracking your exercise, activity,\n    and other trends\n- purpose: Improve, personalize, and develop the Services\n  text: develop new features and Services, which may include generative artificial intelligence models.\n- purpose: Communicate with you\n  text: We use your information when needed to send you Service notifications and respond to you when you contact\n    us.\n- purpose: Promote safety and security\n  text: protect against fraud and abuse, respond to a legal request or claim, conduct audits, and enforce our terms\n    and policies.\nretention:\n- scope: Account information\n  period: null\n  text: We keep your account information, like your name, email address, and password, for as long as your account\n    is in existence\n- scope: Contact list\n  period: null\n  text: when you provide your contact list for finding friends on the Services, we delete the list after it is used\n    for adding contacts as friends.\nresidency: []\ntransfers:\n- mechanism:\
  \ DPF\n  text: EU-U.S. and Swiss-U.S. Data Privacy Frameworks, and the UK Extension to the EU-U.S. DPF.\n- mechanism: adequacy\n  text: European Commission’s , the United Kingdom’s and Switzerland’s Adequacy Decisions.\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses and supplementary measures.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings and tools; account deletion\n  text: while most of your information will be deleted within 30 days, it may take up to 90 days to delete all of\n    your information\nrights:\n- right: Access and export\n  text: Using your account settings, you can also download information in a commonly used file format\n- right: Edit and delete\n  text: By logging into your account and using your account settings, you can change and delete your personal information.\n- right: Object to data use\n  text: For example, through your privacy settings, you can limit how\
  \ your information is visible to other users\n    of the Services\n- right: Withdraw consent\n  text: You can use your account settings and tools to withdraw your consent at any time\n- right: Lodge complaint\n  text: You also have a right to lodge a complaint with your local data protection authority or with the Irish Data\n    Protection Commission\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell the personal information of our users.\n"
source_yaml_url: https://artifacts.apis.io/fitbit/privacy/fitbit-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Fitbit's own page on 2026-11-09.
synthetic: false
tags:
- Wearables
- Health
- Fitness
- Activity Tracking
- Heart Rate
- Sleep
- Google
- IoT
- Wellness
---
