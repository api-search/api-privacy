---
api_specs:
- filename: wefitter-app-api-openapi.yml
  format: yaml
  label: WeFitter App API
  slug: wefitter-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-app-api-openapi.yml
- filename: wefitter-challenge-api-openapi.yml
  format: yaml
  label: WeFitter Challenge API
  slug: wefitter-challenge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-challenge-api-openapi.yml
- filename: wefitter-connection-api-openapi.yml
  format: yaml
  label: WeFitter Connection API
  slug: wefitter-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-connection-api-openapi.yml
- filename: wefitter-insights-api-openapi.yml
  format: yaml
  label: WeFitter Insights API
  slug: wefitter-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-insights-api-openapi.yml
- filename: wefitter-loyalty-api-openapi.yml
  format: yaml
  label: WeFitter Loyalty API
  slug: wefitter-loyalty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-loyalty-api-openapi.yml
- filename: wefitter-notification-api-openapi.yml
  format: yaml
  label: WeFitter Notification API
  slug: wefitter-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-notification-api-openapi.yml
- filename: wefitter-profile-api-openapi.yml
  format: yaml
  label: WeFitter Profile API
  slug: wefitter-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-profile-api-openapi.yml
- filename: wefitter-team-api-openapi.yml
  format: yaml
  label: WeFitter Team API
  slug: wefitter-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-team-api-openapi.yml
- filename: wefitter-token-api-openapi.yml
  format: yaml
  label: WeFitter Token API
  slug: wefitter-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wefitter/openapi/wefitter-token-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: the Wefitter.com website only stores your contact information (if supplied by you)
  - category: device
    text: This includes a device's IP address (processed during your session and stored in a de-identified form)
  - category: location
    text: geographic location (country only)
  - category: behavioral
    text: how much time they spend on which pages, which links they choose to click
  deletion:
    route: email privacy@wefitter.com
    text: You can send a request to do so to privacy@wefitter.com
  dpa:
    available: true
    text: Any data we share with third parties is based on a data processing agreement with these parties.
    url: null
  purposes:
  - purpose: optional contact registration
    text: To optionally register your contact information
  - purpose: provide relevant information
    text: To enable the Wefitter.com website to provide you with relevant information
  - purpose: website analytics
    text: To analyze the way the Wefitter.com website Is used, in order to improve the quality of the website in the future.
  retention:
  - period: 1 month
    scope: IP address for security
    text: For security reasons we store your IP address up to a maximum duration of 1 month.
  - period: 2 years
    scope: IP address for suspicious activity
    text: the IP address may be stored for a maximum of 2 years for security purposes
  - period: as long as you agree
    scope: contact information
    text: the Wefitter.com website only stores your contact information (if supplied by you) as long as you agree.
  rights:
  - right: access
    text: You are entitled to view your data stored by the Wefitter.com website
  - right: correction or removal
    text: you are entitled to have your data corrected or removed.
  role:
    text: As the controller we consider taking proper care of your data of utmost importance.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: E-vitality B.V. does not sell your data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WeFitter
provenance_date: '2026-11-10'
provider_name: WeFitter
provider_slug: wefitter
slug: wefitter-privacy-policy
source_date: '2026-11-10'
source_filename: wefitter-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.wefitter.com/nl/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WeFitter\naid: wefitter\nurl: https://www.wefitter.com/nl/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: As the controller we consider taking proper care of your data of utmost importance.\ndata_categories:\n- category: contact\n  text: the Wefitter.com website only stores your contact information (if supplied by you)\n- category: device\n  text: This includes a device's IP address (processed during your session and stored in a de-identified form)\n- category: location\n  text: geographic location (country only)\n- category: behavioral\n  text: how much time they spend on which\
  \ pages, which links they choose to click\npurposes:\n- purpose: optional contact registration\n  text: To optionally register your contact information\n- purpose: provide relevant information\n  text: To enable the Wefitter.com website to provide you with relevant information\n- purpose: website analytics\n  text: To analyze the way the Wefitter.com website Is used, in order to improve the quality of the website in the\n    future.\nretention:\n- scope: IP address for security\n  period: 1 month\n  text: For security reasons we store your IP address up to a maximum duration of 1 month.\n- scope: IP address for suspicious activity\n  period: 2 years\n  text: the IP address may be stored for a maximum of 2 years for security purposes\n- scope: contact information\n  period: as long as you agree\n  text: the Wefitter.com website only stores your contact information (if supplied by you) as long as you agree.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n\
  \  available: true\n  url: null\n  text: Any data we share with third parties is based on a data processing agreement with these parties.\ndeletion:\n  route: email privacy@wefitter.com\n  text: You can send a request to do so to privacy@wefitter.com\nrights:\n- right: access\n  text: You are entitled to view your data stored by the Wefitter.com website\n- right: correction or removal\n  text: you are entitled to have your data corrected or removed.\nsale_or_sharing:\n  stance: prohibited\n  text: E-vitality B.V. does not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/wefitter/privacy/wefitter-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from WeFitter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Fitness
- Wearables
- Health Data
- Wellbeing
- Gamification
- Digital Health
- Insurance
- Activity Tracking
---
