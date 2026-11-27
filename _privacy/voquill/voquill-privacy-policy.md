---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (via email/password sign-up or Google OAuth)
  - category: identifying
    text: Display name (from Google OAuth, or as you provide it)
  - category: behavioral
    text: Page views and navigation within the app
  - category: device
    text: General device information (platform, locale)
  - category: financial
    text: We receive limited billing information from these processors, such as your subscription status and Stripe customer ID, to manage your account.
  - category: communication
    text: Send transactional emails (e.g., account verification)
  deletion:
    route: Delete account via application settings
    text: You can delete your account through the application settings, which removes your data from our servers and clears your local data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Process transcriptions in cloud mode
    text: Process transcriptions in cloud mode
  - purpose: Manage account and subscription
    text: Manage your account and subscription
  - purpose: Product analytics
    text: We use Mixpanel to collect anonymous product analytics to help us improve Voquill.
  - purpose: Support requests
    text: Respond to support requests
  residency:
  - region: United States
    text: your information may be transferred to and processed in the United States, where our servers and service providers are located.
  retention:
  - period: Never retained
    scope: Voice/audio data
    text: 'Voice/audio data: Never retained. Processed transiently in cloud mode and immediately discarded.'
  - period: null
    scope: Transcriptions
    text: 'Transcriptions: Stored locally on your device indefinitely until you delete them or delete your account.'
  - period: null
    scope: Account data
    text: 'Account data: Retained while your account is active.'
  - period: null
    scope: Analytics data
    text: 'Analytics data: Retained in accordance with Mixpanel''s data retention policies.'
  rights:
  - right: Access and export
    text: 'Access and export: Your transcription data is stored locally on your device and is accessible to you at any time.'
  - right: Deletion
    text: 'Deletion: You can delete your account through the application settings'
  - right: Opt out of analytics
    text: 'Opt out of analytics: Enterprise deployments have analytics disabled by default.'
  - right: Incognito mode
    text: 'Incognito mode: You can enable incognito mode to prevent transcriptions from being stored, even locally.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you are located outside the United States, your information may be transferred to and processed in the United States, where our servers and service providers are located. By using the Service, you consent to this transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Voquill
provenance_date: '2026-11-10'
provider_name: Voquill
provider_slug: voquill
slug: voquill-privacy-policy
source_date: '2026-11-10'
source_filename: voquill-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://voquill.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Voquill\naid: voquill\nurl: https://voquill.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (via email/password sign-up or Google OAuth)\n- category: identifying\n  text: Display name (from Google OAuth, or as you provide it)\n- category: behavioral\n  text: Page views and navigation within the app\n- category: device\n  text: General device information (platform, locale)\n- category: financial\n  text: We receive limited billing information from these processors, such as your subscription status and Stripe\n\
  \    customer ID, to manage your account.\n- category: communication\n  text: Send transactional emails (e.g., account verification)\npurposes:\n- purpose: Provide, maintain and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Process transcriptions in cloud mode\n  text: Process transcriptions in cloud mode\n- purpose: Manage account and subscription\n  text: Manage your account and subscription\n- purpose: Product analytics\n  text: We use Mixpanel to collect anonymous product analytics to help us improve Voquill.\n- purpose: Support requests\n  text: Respond to support requests\nretention:\n- scope: Voice/audio data\n  period: Never retained\n  text: 'Voice/audio data: Never retained. Processed transiently in cloud mode and immediately discarded.'\n- scope: Transcriptions\n  period: null\n  text: 'Transcriptions: Stored locally on your device indefinitely until you delete them or delete your account.'\n- scope: Account data\n  period: null\n  text:\
  \ 'Account data: Retained while your account is active.'\n- scope: Analytics data\n  period: null\n  text: 'Analytics data: Retained in accordance with Mixpanel''s data retention policies.'\nresidency:\n- region: United States\n  text: your information may be transferred to and processed in the United States, where our servers and service\n    providers are located.\ntransfers:\n- mechanism: other\n  text: If you are located outside the United States, your information may be transferred to and processed in the\n    United States, where our servers and service providers are located. By using the Service, you consent to this\n    transfer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account via application settings\n  text: You can delete your account through the application settings, which removes your data from our servers and\n    clears your local data.\nrights:\n- right: Access and export\n  text: 'Access\
  \ and export: Your transcription data is stored locally on your device and is accessible to you at\n    any time.'\n- right: Deletion\n  text: 'Deletion: You can delete your account through the application settings'\n- right: Opt out of analytics\n  text: 'Opt out of analytics: Enterprise deployments have analytics disabled by default.'\n- right: Incognito mode\n  text: 'Incognito mode: You can enable incognito mode to prevent transcriptions from being stored, even locally.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/voquill/privacy/voquill-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Voquill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Voice
- Dictation
- Speech-to-Text
- Artificial Intelligence
- Open Source
- Healthcare
- Pathology
- Productivity
---
