---
api_specs:
- filename: app-avots-ai-openapi.json
  format: json
  label: OpenAI-compatible API
  slug: openai-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avots-ai/openapi/app-avots-ai-openapi.json
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email address, password (hashed), preferred interface language, referral code'
  - category: contact
    text: 'Account data: name, email address, password (hashed), preferred interface language, referral code'
  - category: financial
    text: 'Payment data: subscription plan, transaction history, invoice records.'
  - category: device
    text: 'Technical data: IP address, device type, browser, access timestamps'
  - category: behavioral
    text: 'Usage data: conversations, messages, file uploads, model preferences, generated media (images, audio, video)'
  - category: biometric
    text: We do not use facial recognition and we do not create biometric templates, faceprints or any other biometric identifiers.
  deletion:
    route: Settings
    text: You can request account deletion at any time through Settings
  dpa:
    available: null
    text: These processors are bound by their own privacy policies and data processing agreements providing protection consistent with this policy and applicable EU data protection law (GDPR).
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: To provide and maintain the avots.ai service
  - purpose: Authentication and account management
    text: To authenticate your identity and manage your account
  - purpose: Payments and subscriptions
    text: To process payments and manage subscriptions, including sending crypto renewal reminders before subscription expiry
  - purpose: Routing AI requests
    text: To route your requests to third-party AI model providers (OpenRouter, Fal.ai)
  - purpose: Fraud and abuse prevention
    text: To prevent fraud and abuse (rate limiting, refresh-token reuse detection)
  - purpose: Service improvement
    text: To improve our service and fix issues
  residency:
  - region: European Union
    text: Your data is stored on servers located in the European Union.
  retention:
  - period: as long as your account is active
    scope: Account data
    text: Account data is retained as long as your account is active
  - period: 30 days
    scope: Deleted conversations
    text: Deleted conversations are permanently removed after 30 days
  - period: 90 days
    scope: Access logs
    text: Access logs are retained for 90 days
  - period: null
    scope: Face data uploads and generated media
    text: your uploads and generated media are retained while your account is active so you can access them in your archive
  rights:
  - right: Access
    text: Access your personal data
  - right: Rectify
    text: Rectify inaccurate data
  - right: Delete
    text: Delete your data ("right to be forgotten")
  - right: Restrict or object
    text: Restrict or object to data processing
  - right: Portability
    text: Data portability
  - right: Withdraw consent
    text: Withdraw consent at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: avots.ai
provenance_date: '2026-11-09'
provider_name: avots.ai
provider_slug: avots-ai
slug: avots-ai-privacy-policy
source_date: '2026-11-09'
source_filename: avots-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://avots.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: avots.ai\naid: avots-ai\nurl: https://avots.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email address, password (hashed), preferred interface language, referral code'\n- category: contact\n  text: 'Account data: name, email address, password (hashed), preferred interface language, referral code'\n- category: financial\n  text: 'Payment data: subscription plan, transaction history, invoice records.'\n- category: device\n  text: 'Technical data: IP address, device type, browser, access timestamps'\n\
  - category: behavioral\n  text: 'Usage data: conversations, messages, file uploads, model preferences, generated media (images, audio, video)'\n- category: biometric\n  text: We do not use facial recognition and we do not create biometric templates, faceprints or any other biometric\n    identifiers.\npurposes:\n- purpose: Provide and maintain service\n  text: To provide and maintain the avots.ai service\n- purpose: Authentication and account management\n  text: To authenticate your identity and manage your account\n- purpose: Payments and subscriptions\n  text: To process payments and manage subscriptions, including sending crypto renewal reminders before subscription\n    expiry\n- purpose: Routing AI requests\n  text: To route your requests to third-party AI model providers (OpenRouter, Fal.ai)\n- purpose: Fraud and abuse prevention\n  text: To prevent fraud and abuse (rate limiting, refresh-token reuse detection)\n- purpose: Service improvement\n  text: To improve our service and fix\
  \ issues\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: Account data is retained as long as your account is active\n- scope: Deleted conversations\n  period: 30 days\n  text: Deleted conversations are permanently removed after 30 days\n- scope: Access logs\n  period: 90 days\n  text: Access logs are retained for 90 days\n- scope: Face data uploads and generated media\n  period: null\n  text: your uploads and generated media are retained while your account is active so you can access them in your\n    archive\nresidency:\n- region: European Union\n  text: Your data is stored on servers located in the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: These processors are bound by their own privacy policies and data processing agreements providing protection\n    consistent with this policy and applicable EU data protection law (GDPR).\ndeletion:\n  route: Settings\n  text: You\
  \ can request account deletion at any time through Settings\nrights:\n- right: Access\n  text: Access your personal data\n- right: Rectify\n  text: Rectify inaccurate data\n- right: Delete\n  text: Delete your data (\"right to be forgotten\")\n- right: Restrict or object\n  text: Restrict or object to data processing\n- right: Portability\n  text: Data portability\n- right: Withdraw consent\n  text: Withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/avots-ai/privacy/avots-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from avots.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Subscription
- Generative AI
- Platform
- Aggregator
---
