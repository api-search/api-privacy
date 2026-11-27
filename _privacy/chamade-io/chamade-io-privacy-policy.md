---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email address, hashed password.'
  - category: contact
    text: 'SIP data: phone numbers (DID), caller IDs, call metadata for SIP calls.'
  - category: financial
    text: 'Payment data: processed entirely by Stripe. We store your Stripe customer ID and subscription status, but never your card details.'
  - category: communication
    text: 'Voice data: during a call, meeting audio is streamed in real-time through the meeting bridge (Maquisard)'
  - category: device
    text: 'Call metadata: call ID, platform, meeting URL, timestamps, state.'
  deletion:
    route: Delete your account from the dashboard or account settings
    text: Delete your account and associated data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the service
    text: processing your account data, OAuth tokens, and call data is necessary to provide the service.
  - purpose: Debugging call metadata
    text: 'Legitimate interest (Art. 6(1)(f) GDPR): call metadata for debugging, usage tracking for billing.'
  - purpose: Billing
    text: 'Call metadata: call ID, platform, meeting URL, timestamps, state. Retained for billing and debugging.'
  residency:
  - region: EU
    text: Hetzner Online GmbH (Germany) — server hosting. Data processed within the EU.
  retention:
  - period: Deleted within 30 days of account deletion
    scope: Account data
    text: 'Account data: retained as long as your account is active. Deleted within 30 days of account deletion.'
  - period: up to 12 months
    scope: Call data
    text: 'Call data: metadata retained for up to 12 months for billing purposes, then deleted.'
  - period: not persisted
    scope: Audio and transcriptions
    text: 'Audio and transcriptions: not persisted. Processed in real-time only.'
  rights:
  - right: Access
    text: Access your personal data.
  - right: Rectify
    text: Rectify inaccurate data.
  - right: Delete
    text: Delete your account and associated data.
  - right: Portability
    text: Port your data in a machine-readable format.
  - right: Object
    text: Object to processing based on legitimate interest.
  - right: Complain
    text: 'Lodge a complaint with the Belgian Data Protection Authority (APD/GBA): www.dataprotectionauthority.be.'
  role:
    text: The data controller is Nafis SRL, Belgium (BCE 0656.477.588).
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Chamade relies on the following third-party services to operate the gateway itself: Hetzner Online GmbH (Germany) — server hosting.'
    url: null
  transfers:
  - mechanism: SCC
    text: Transfer to the US is covered by Standard Contractual Clauses (SCCs).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chamade
provenance_date: '2026-11-09'
provider_name: Chamade
provider_slug: chamade-io
slug: chamade-io-privacy-policy
source_date: '2026-11-09'
source_filename: chamade-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chamade.io/legal#privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chamade\naid: chamade-io\nurl: https://chamade.io/legal#privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Nafis SRL, Belgium (BCE 0656.477.588).\ndata_categories:\n- category: identifying\n  text: 'Account data: email address, hashed password.'\n- category: contact\n  text: 'SIP data: phone numbers (DID), caller IDs, call metadata for SIP calls.'\n- category: financial\n  text: 'Payment data: processed entirely by Stripe. We store your Stripe customer ID and subscription status, but\n    never your card details.'\n- category: communication\n  text: 'Voice data:\
  \ during a call, meeting audio is streamed in real-time through the meeting bridge (Maquisard)'\n- category: device\n  text: 'Call metadata: call ID, platform, meeting URL, timestamps, state.'\npurposes:\n- purpose: Providing the service\n  text: processing your account data, OAuth tokens, and call data is necessary to provide the service.\n- purpose: Debugging call metadata\n  text: 'Legitimate interest (Art. 6(1)(f) GDPR): call metadata for debugging, usage tracking for billing.'\n- purpose: Billing\n  text: 'Call metadata: call ID, platform, meeting URL, timestamps, state. Retained for billing and debugging.'\nretention:\n- scope: Account data\n  period: Deleted within 30 days of account deletion\n  text: 'Account data: retained as long as your account is active. Deleted within 30 days of account deletion.'\n- scope: Call data\n  period: up to 12 months\n  text: 'Call data: metadata retained for up to 12 months for billing purposes, then deleted.'\n- scope: Audio and transcriptions\n\
  \  period: not persisted\n  text: 'Audio and transcriptions: not persisted. Processed in real-time only.'\nresidency:\n- region: EU\n  text: Hetzner Online GmbH (Germany) — server hosting. Data processed within the EU.\ntransfers:\n- mechanism: SCC\n  text: Transfer to the US is covered by Standard Contractual Clauses (SCCs).\nsubprocessors:\n  url: null\n  text: 'Chamade relies on the following third-party services to operate the gateway itself: Hetzner Online GmbH\n    (Germany) — server hosting.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account from the dashboard or account settings\n  text: Delete your account and associated data.\nrights:\n- right: Access\n  text: Access your personal data.\n- right: Rectify\n  text: Rectify inaccurate data.\n- right: Delete\n  text: Delete your account and associated data.\n- right: Portability\n  text: Port your data in a machine-readable format.\n- right: Object\n  text: Object to processing based on\
  \ legitimate interest.\n- right: Complain\n  text: 'Lodge a complaint with the Belgian Data Protection Authority (APD/GBA): www.dataprotectionauthority.be.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chamade-io/privacy/chamade-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 22 quoted statements, read from Chamade's own page on 2026-11-09.
synthetic: false
tags:
- Voice gateway
- Chat gateway
- AI Agents
- SIP
- Speech API
---
