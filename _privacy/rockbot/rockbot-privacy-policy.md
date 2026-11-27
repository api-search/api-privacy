---
api_specs:
- filename: rockbot-audio-messaging-api-openapi.yml
  format: yaml
  label: Rockbot Audio Messaging API
  slug: rockbot-audio-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rockbot/openapi/rockbot-audio-messaging-api-openapi.yml
- filename: rockbot-auth-api-openapi.yml
  format: yaml
  label: Rockbot Auth API
  slug: rockbot-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rockbot/openapi/rockbot-auth-api-openapi.yml
- filename: rockbot-data-api-openapi.yml
  format: yaml
  label: Rockbot Data API
  slug: rockbot-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rockbot/openapi/rockbot-data-api-openapi.yml
- filename: rockbot-devices-api-openapi.yml
  format: yaml
  label: Rockbot Devices API
  slug: rockbot-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rockbot/openapi/rockbot-devices-api-openapi.yml
- filename: rockbot-music-api-openapi.yml
  format: yaml
  label: Rockbot Music API
  slug: rockbot-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rockbot/openapi/rockbot-music-api-openapi.yml
- filename: rockbot-signage-api-openapi.yml
  format: yaml
  label: Rockbot Signage API
  slug: rockbot-signage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rockbot/openapi/rockbot-signage-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: You provide us information about yourself, such as your name, email address, mobile phone number and carrier, etc., if you register for a Member Account with our Service.
  - category: location
    text: we access your personal data and the geographic location of your mobile device to verify that it is within an acceptable radius of the Venue before allowing a check in.
  - category: device
    text: 'Log File Information: Log file information is automatically reported by your browser each time you access a web page.'
  - category: behavioral
    text: Internet or other electronic network activity information, such as your activity on the Rockbot Services
  - category: demographic
    text: Characteristics about you, such as age and gender
  - category: financial
    text: your name, address, email, phone number and your credit card’s type, number, expiration date and CVC number and your order total (collectively referred to as your Billing Information) will be shared
  deletion:
    route: email privacy@rockbot.com
    text: You have the right to request the deletion of personal information that we collect or maintain about you and your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and provide the Service
    text: We use the personal information you submit to operate, maintain, and provide to you the features and functionality of the Service.
  - purpose: advertising and tracking
    text: We may also, either directly or through third party companies and individuals we engage to provide services to us, track your behavior on our own Platform to market and advertise our services to you on the Platform and third party websites.
  - purpose: analytics and fraud prevention
    text: for purposes of our own customer support, analytics, research, product development, fraud prevention, risk assessment, regulatory compliance, investigation
  rights:
  - right: Right to Know
    text: Right to Know. You have the right to request that we disclose to you the categories and specific pieces of personal information we have collected about you
  - right: Right to Delete
    text: Right to Delete. You have the right to request the deletion of personal information that we collect or maintain about you and your account.
  - right: Right to Opt Out of Sale
    text: Right to Opt Out of “Sale”. Rockbot may disclose certain information about you if you are a registered user of the Rockbot Services
  role:
    text: Rockbot, Inc. (“Rockbot,” “we,” or “us”), is an out-of-home service that provides streaming music, video and other content
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Rockbot does not share your personally identifiable information or personally-identifiable location information with other, third-party companies for their commercial or marketing use without your express consent or unless you have opted-in to be part of a specific program or feature.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Rockbot
provenance_date: '2026-11-10'
provider_name: Rockbot
provider_slug: rockbot
slug: rockbot-privacy-policy
source_date: '2026-11-10'
source_filename: rockbot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rockbot.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Rockbot\naid: rockbot\nurl: https://rockbot.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Rockbot, Inc. (“Rockbot,” “we,” or “us”), is an out-of-home service that provides streaming music, video\n    and other content\ndata_categories:\n- category: identifying\n  text: You provide us information about yourself, such as your name, email address, mobile phone number and carrier,\n    etc., if you register for a Member Account with our Service.\n- category: location\n  text: we access your personal data and the geographic location of your mobile device to verify that it is within\n\
  \    an acceptable radius of the Venue before allowing a check in.\n- category: device\n  text: 'Log File Information: Log file information is automatically reported by your browser each time you access\n    a web page.'\n- category: behavioral\n  text: Internet or other electronic network activity information, such as your activity on the Rockbot Services\n- category: demographic\n  text: Characteristics about you, such as age and gender\n- category: financial\n  text: your name, address, email, phone number and your credit card’s type, number, expiration date and CVC number\n    and your order total (collectively referred to as your Billing Information) will be shared\npurposes:\n- purpose: operate and provide the Service\n  text: We use the personal information you submit to operate, maintain, and provide to you the features and functionality\n    of the Service.\n- purpose: advertising and tracking\n  text: We may also, either directly or through third party companies and individuals\
  \ we engage to provide services\n    to us, track your behavior on our own Platform to market and advertise our services to you on the Platform and\n    third party websites.\n- purpose: analytics and fraud prevention\n  text: for purposes of our own customer support, analytics, research, product development, fraud prevention, risk\n    assessment, regulatory compliance, investigation\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@rockbot.com\n  text: You have the right to request the deletion of personal information that we collect or maintain about you\n    and your account.\nrights:\n- right: Right to Know\n  text: Right to Know. You have the right to request that we disclose to you the categories and specific pieces\n    of personal information we have collected about you\n- right: Right to Delete\n  text: Right to Delete. You have the right to request the\
  \ deletion of personal information that we collect or maintain\n    about you and your account.\n- right: Right to Opt Out of Sale\n  text: Right to Opt Out of “Sale”. Rockbot may disclose certain information about you if you are a registered user\n    of the Rockbot Services\nsale_or_sharing:\n  stance: conditional\n  text: Rockbot does not share your personally identifiable information or personally-identifiable location information\n    with other, third-party companies for their commercial or marketing use without your express consent or unless\n    you have opted-in to be part of a specific program or feature.\n"
source_yaml_url: https://artifacts.apis.io/rockbot/privacy/rockbot-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Rockbot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Music
- Digital Signage
- Audio Messaging
- Retail Media
- In-Location Media
- Media
- Entertainment
---
