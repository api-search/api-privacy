---
api_specs:
- filename: lazybird-app-auth-api-openapi.yml
  format: yaml
  label: Lazybird Auth API
  slug: lazybird-app-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-auth-api-openapi.yml
- filename: lazybird-app-checkout-api-openapi.yml
  format: yaml
  label: Lazybird Checkout API
  slug: lazybird-app-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-checkout-api-openapi.yml
- filename: lazybird-app-generate-speech-api-openapi.yml
  format: yaml
  label: Lazybird Generate Speech API
  slug: lazybird-app-generate-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-generate-speech-api-openapi.yml
- filename: lazybird-app-me-api-openapi.yml
  format: yaml
  label: Lazybird Me API
  slug: lazybird-app-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-me-api-openapi.yml
- filename: lazybird-app-music-api-openapi.yml
  format: yaml
  label: Lazybird Music API
  slug: lazybird-app-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-music-api-openapi.yml
- filename: lazybird-app-projects-api-openapi.yml
  format: yaml
  label: Lazybird Projects API
  slug: lazybird-app-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-projects-api-openapi.yml
- filename: lazybird-app-status-api-openapi.yml
  format: yaml
  label: Lazybird Status API
  slug: lazybird-app-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-status-api-openapi.yml
- filename: lazybird-app-stock-api-openapi.yml
  format: yaml
  label: Lazybird Stock API
  slug: lazybird-app-stock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-stock-api-openapi.yml
- filename: lazybird-app-voices-api-openapi.yml
  format: yaml
  label: Lazybird Voices API
  slug: lazybird-app-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-voices-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, or your Google account's name, email and profile picture if you sign in with Google.
  - category: biometric
    text: A voice recording can identify the person speaking, and some laws treat it as biometric or sensitive data.
  - category: contact
    text: Emails you send us and our replies.
  - category: financial
    text: 'We receive only what we need to give you what you bought: your name, email, the plan or product and its status.'
  - category: location
    text: 'Device and browser information: browser type, device type, language, time zone, the page that referred you and campaign tags.'
  - category: behavioral
    text: Whether you opened or clicked our emails.
  deletion:
    route: Settings → Account → Delete account
    text: You can delete your account and everything in it yourself, from Settings → Account → Delete account .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run account and generate audio
    text: We collect what we need to run your account and generate audio
  - purpose: Fraud and abuse prevention
    text: Prevent fraud, abuse and violations of our Terms or Acceptable Use Policy
  - purpose: Analytics and product improvement
    text: Understand how Lazybird is used and improve it
  - purpose: Advertising
    text: No sale of data, no targeted advertising.
  retention:
  - period: null
    scope: Speech generation records including text
    text: Records of each speech generation, including its text
  - period: null
    scope: Temporary copies of generated audio
    text: Temporary copies of generated audio
  - period: Until you delete them or delete your account
    scope: Account, projects, voices, uploads
    text: Until you delete them or delete your account
  - period: As long as needed for tax, accounting, refunds and chargebacks, as the law requires
    scope: Payment and license records
    text: As long as needed for tax, accounting, refunds and chargebacks, as the law requires
  rights:
  - right: Access
    text: Access the personal data we hold about you and get a copy of it.
  - right: Correct
    text: Correct inaccurate data.
  - right: Delete
    text: Delete your data.
  - right: Restrict or object
    text: Restrict or object to certain processing, including processing based on legitimate interest.
  - right: Port
    text: Port your data to another service.
  - right: Withdraw consent
    text: Withdraw consent where we rely on it (for example for a voice recording), without affecting earlier processing.
  role:
    text: We are the controller of the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data, and we do not use your scripts, uploads or voice recordings to train AI models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: lazybird-app
provenance_date: '2026-11-09'
provider_name: Lazybird
provider_slug: lazybird-app
slug: lazybird-app-privacy-policy
source_date: '2026-11-09'
source_filename: lazybird-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lazybird.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: lazybird-app\naid: lazybird-app\nurl: https://www.lazybird.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: Email address, or your Google account's name, email and profile picture if you sign in with Google.\n- category: biometric\n  text: A voice recording can identify the person speaking, and some laws treat it as biometric or sensitive data.\n- category: contact\n  text: Emails you send us and our replies.\n- category: financial\n  text: 'We receive only what\
  \ we need to give you what you bought: your name, email, the plan or product and its\n    status.'\n- category: location\n  text: 'Device and browser information: browser type, device type, language, time zone, the page that referred\n    you and campaign tags.'\n- category: behavioral\n  text: Whether you opened or clicked our emails.\npurposes:\n- purpose: Run account and generate audio\n  text: We collect what we need to run your account and generate audio\n- purpose: Fraud and abuse prevention\n  text: Prevent fraud, abuse and violations of our Terms or Acceptable Use Policy\n- purpose: Analytics and product improvement\n  text: Understand how Lazybird is used and improve it\n- purpose: Advertising\n  text: No sale of data, no targeted advertising.\nretention:\n- scope: Speech generation records including text\n  period: null\n  text: Records of each speech generation, including its text\n- scope: Temporary copies of generated audio\n  period: null\n  text: Temporary copies of generated\
  \ audio\n- scope: Account, projects, voices, uploads\n  period: Until you delete them or delete your account\n  text: Until you delete them or delete your account\n- scope: Payment and license records\n  period: As long as needed for tax, accounting, refunds and chargebacks, as the law requires\n  text: As long as needed for tax, accounting, refunds and chargebacks, as the law requires\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Account → Delete account\n  text: You can delete your account and everything in it yourself, from Settings → Account → Delete account .\nrights:\n- right: Access\n  text: Access the personal data we hold about you and get a copy of it.\n- right: Correct\n  text: Correct inaccurate data.\n- right: Delete\n  text: Delete your data.\n- right: Restrict or object\n  text: Restrict or object to certain processing, including processing based on legitimate interest.\n\
  - right: Port\n  text: Port your data to another service.\n- right: Withdraw consent\n  text: Withdraw consent where we rely on it (for example for a voice recording), without affecting earlier processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data, and we do not use your scripts, uploads or voice recordings to train\n    AI models.\n"
source_yaml_url: https://artifacts.apis.io/lazybird-app/privacy/lazybird-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from lazybird-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voiceover
- Text-to-Speech
- Creator Tools
- Multilingual
---
