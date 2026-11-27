---
api_specs:
- filename: sonde-health-authentication-api-openapi.yml
  format: yaml
  label: Sonde Health Authentication API
  slug: sonde-health-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonde-health/openapi/sonde-health-authentication-api-openapi.yml
- filename: sonde-health-platform-api-openapi.yml
  format: yaml
  label: Sonde Health Platform API
  slug: sonde-health-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonde-health/openapi/sonde-health-platform-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: create an account by providing us with information such as your full name, a valid email address, phone number, billing information, and a strong password
  - category: health
    text: We may ask you to provide information about your general health and habits, such as whether you are a smoker, or whether you have asthma.
  - category: location
    text: We derive general information about your location from your IP address or global positioning system (GPS) sensors when you use our App.
  - category: device
    text: we collect information from you, such as your IP address, referring URL, operating system, cookie information, GPS coordinates, and Internet Service Provider
  - category: communication
    text: This collection specifically includes records of your voice that you provide when using the App.
  - category: financial
    text: such as your name, credit, debit or other card number, card expiration date, and CVV code. This information is encrypted and sent to the third-party payment processor on our behalf.
  deletion:
    route: Delete account in the App or contact us; data deleted within 7 days, up to 30 days for backups
    text: If you choose to delete your account, please note that while most of your information will be deleted within 7 (seven) days, it may take up to 30 (thirty) days to delete all of your information, like the data stored in our backup systems.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the App
    text: We use the personal information we collect to provide, maintain, improve, and enhance the App.
  - purpose: Communicate with you
    text: We use your personal information when needed to send you Service notifications and respond to you when you contact us.
  - purpose: Marketing and advertising
    text: We also use your personal information to promote new features or products that we think you would be interested in.
  - purpose: Safety and security
    text: We use the personal information we collect to promote the safety and security of the Services, our users, and other parties.
  residency:
  - region: United States
    text: Our services are hosted in the United States and intended for visitors located within the United States.
  retention:
  - period: null
    scope: Account data
    text: We keep your personal information for as long as your account is in existence, because we need it to operate your account.
  rights:
  - right: Access
    text: By logging into your account in the App, you can access much of your personal information and request that we delete your personal information.
  - right: Edit
    text: You may change your personal information through the App.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The service providers we currently use help us with payment processing, advertising, analytics, disaster recovery, information technology, storage, audio processing and content delivery, among others.
    url: null
  transfers:
  - mechanism: other
    text: If you choose to use the App from the European Union or other regions of the world with laws governing data collection and use that may differ from U.S. law, then please note that you are transferring your personal information outside of those regions to the United States for storage and processing.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sonde Health
provenance_date: '2026-11-10'
provider_name: Sonde Health
provider_slug: sonde-health
slug: sonde-health-privacy-policy
source_date: '2026-11-10'
source_filename: sonde-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sondehealth.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sonde Health\naid: sonde-health\nurl: https://www.sondehealth.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: create an account by providing us with information such as your full name, a valid email address, phone\n    number, billing information, and a strong password\n- category: health\n  text: We may ask you to provide information about your general health and habits, such as whether you are a smoker,\n    or whether you have asthma.\n- category: location\n  text: We derive general information about your location from your\
  \ IP address or global positioning system (GPS)\n    sensors when you use our App.\n- category: device\n  text: we collect information from you, such as your IP address, referring URL, operating system, cookie information,\n    GPS coordinates, and Internet Service Provider\n- category: communication\n  text: This collection specifically includes records of your voice that you provide when using the App.\n- category: financial\n  text: such as your name, credit, debit or other card number, card expiration date, and CVV code. This information\n    is encrypted and sent to the third-party payment processor on our behalf.\npurposes:\n- purpose: Provide and improve the App\n  text: We use the personal information we collect to provide, maintain, improve, and enhance the App.\n- purpose: Communicate with you\n  text: We use your personal information when needed to send you Service notifications and respond to you when you\n    contact us.\n- purpose: Marketing and advertising\n  text: We also\
  \ use your personal information to promote new features or products that we think you would be interested\n    in.\n- purpose: Safety and security\n  text: We use the personal information we collect to promote the safety and security of the Services, our users,\n    and other parties.\nretention:\n- scope: Account data\n  period: null\n  text: We keep your personal information for as long as your account is in existence, because we need it to operate\n    your account.\nresidency:\n- region: United States\n  text: Our services are hosted in the United States and intended for visitors located within the United States.\ntransfers:\n- mechanism: other\n  text: If you choose to use the App from the European Union or other regions of the world with laws governing data\n    collection and use that may differ from U.S. law, then please note that you are transferring your personal information\n    outside of those regions to the United States for storage and processing.\nsubprocessors:\n  url:\
  \ null\n  text: The service providers we currently use help us with payment processing, advertising, analytics, disaster\n    recovery, information technology, storage, audio processing and content delivery, among others.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in the App or contact us; data deleted within 7 days, up to 30 days for backups\n  text: If you choose to delete your account, please note that while most of your information will be deleted within\n    7 (seven) days, it may take up to 30 (thirty) days to delete all of your information, like the data stored in\n    our backup systems.\nrights:\n- right: Access\n  text: By logging into your account in the App, you can access much of your personal information and request that\n    we delete your personal information.\n- right: Edit\n  text: You may change your personal information through the App.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sonde-health/privacy/sonde-health-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from Sonde Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Vocal Biomarkers
- Voice
- Audio
- Machine Learning
- Artificial Intelligence
- Mental Health
- Respiratory
- Remote Patient Monitoring
- Wellness
- HIPAA
---
