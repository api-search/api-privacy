---
api_specs:
- filename: collabpls-com-agent-api-openapi.yml
  format: yaml
  label: CollabPls Agent API
  slug: collabpls-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collabpls-com/openapi/collabpls-com-agent-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Display name, X handle, profile picture URL, and bio
  - category: contact
    text: Email address
  - category: financial
    text: We store Stripe reference IDs (customer ID, session ID, payment intent ID) to link transactions to your account
  - category: biometric
    text: Stripe Identity collects a government-issued photo ID and a selfie for biometric face matching
  - category: location
    text: incident date, time, and location (full address)
  - category: communication
    text: we store the message content, sender, recipient, and timestamp
  - category: health
    text: STD test date (self-reported date only — we do not collect, store, or request any medical records, test results, or health documentation)
  - category: behavioral
    text: We track page views, profile views, listing views, and X click events.
  deletion:
    route: Self-service deletion in Settings > Danger Zone; or contact us
    text: 'Delete: Self-service account deletion is available in Settings > Danger Zone. This permanently removes your profile, listings, chat messages, and all associated data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Profile creation
    text: Your X data is used to pre-fill your CollabPls profile so you can get started quickly.
  - purpose: Payments
    text: Processing ID verification and featured listing payments via Stripe.
  - purpose: Safety & Moderation
    text: AI-assisted review of user reports and chat messages.
  - purpose: Analytics
    text: Aggregating anonymized usage data to improve the platform.
  retention:
  - period: 30 days
    scope: Direct messages
    text: 'Direct messages: Automatically and permanently deleted 30 days after being sent.'
  - period: 7 years
    scope: Financial records
    text: 'Financial records: Retained for 7 years as required for tax and accounting compliance.'
  - period: 7 years
    scope: Emergency incident reports
    text: 'Emergency incident reports: Retained for 7 years (aligns with statute of limitations).'
  - period: null
    scope: Active accounts
    text: 'Active accounts: Your data is retained as long as your account exists.'
  rights:
  - right: Edit
    text: 'Edit: You can update your profile information at any time from your dashboard.'
  - right: Export
    text: 'Export: You can request a copy of your data by contacting us.'
  - right: Email preferences
    text: You can manage email preferences in Settings, including a “Pause All” option.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell, rent, or share your personal data with third parties except as required to operate the platform.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CollabPls
provenance_date: '2026-11-09'
provider_name: CollabPls
provider_slug: collabpls-com
slug: collabpls-com-privacy-policy
source_date: '2026-11-09'
source_filename: collabpls-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://collabpls.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CollabPls\naid: collabpls-com\nurl: https://collabpls.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Display name, X handle, profile picture URL, and bio\n- category: contact\n  text: Email address\n- category: financial\n  text: We store Stripe reference IDs (customer ID, session ID, payment intent ID) to link transactions to your\n    account\n- category: biometric\n  text: Stripe Identity collects a government-issued photo ID and a selfie for biometric face matching\n- category: location\n  text: incident date, time, and\
  \ location (full address)\n- category: communication\n  text: we store the message content, sender, recipient, and timestamp\n- category: health\n  text: STD test date (self-reported date only — we do not collect, store, or request any medical records, test\n    results, or health documentation)\n- category: behavioral\n  text: We track page views, profile views, listing views, and X click events.\npurposes:\n- purpose: Profile creation\n  text: Your X data is used to pre-fill your CollabPls profile so you can get started quickly.\n- purpose: Payments\n  text: Processing ID verification and featured listing payments via Stripe.\n- purpose: Safety & Moderation\n  text: AI-assisted review of user reports and chat messages.\n- purpose: Analytics\n  text: Aggregating anonymized usage data to improve the platform.\nretention:\n- scope: Direct messages\n  period: 30 days\n  text: 'Direct messages: Automatically and permanently deleted 30 days after being sent.'\n- scope: Financial records\n\
  \  period: 7 years\n  text: 'Financial records: Retained for 7 years as required for tax and accounting compliance.'\n- scope: Emergency incident reports\n  period: 7 years\n  text: 'Emergency incident reports: Retained for 7 years (aligns with statute of limitations).'\n- scope: Active accounts\n  period: null\n  text: 'Active accounts: Your data is retained as long as your account exists.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service deletion in Settings > Danger Zone; or contact us\n  text: 'Delete: Self-service account deletion is available in Settings > Danger Zone. This permanently removes\n    your profile, listings, chat messages, and all associated data.'\nrights:\n- right: Edit\n  text: 'Edit: You can update your profile information at any time from your dashboard.'\n- right: Export\n  text: 'Export: You can request a copy of your data by contacting us.'\n- right:\
  \ Email preferences\n  text: You can manage email preferences in Settings, including a “Pause All” option.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell, rent, or share your personal data with third parties except as required to operate the platform.\n"
source_yaml_url: https://artifacts.apis.io/collabpls-com/privacy/collabpls-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from CollabPls's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Creator Economy
- Marketplace
- Collaboration
- Scheduling
- Social Networking
- MCP
- Agents
---
