---
api_specs:
- filename: saperly-api-token-registry-api-openapi.yml
  format: yaml
  label: Saperly API Token Registry API
  slug: saperly-api-token-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-api-token-registry-api-openapi.yml
- filename: saperly-assistant-api-openapi.yml
  format: yaml
  label: Saperly Assistant API
  slug: saperly-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-assistant-api-openapi.yml
- filename: saperly-connections-api-openapi.yml
  format: yaml
  label: Saperly Connections API
  slug: saperly-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-connections-api-openapi.yml
- filename: saperly-consent-api-openapi.yml
  format: yaml
  label: Saperly Consent API
  slug: saperly-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-consent-api-openapi.yml
- filename: saperly-customvoices-api-openapi.yml
  format: yaml
  label: Saperly Custom Voices API
  slug: saperly-customvoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-customvoices-api-openapi.yml
- filename: saperly-health-api-openapi.yml
  format: yaml
  label: Saperly Health API
  slug: saperly-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-health-api-openapi.yml
- filename: saperly-keys-api-openapi.yml
  format: yaml
  label: Saperly Keys API
  slug: saperly-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-keys-api-openapi.yml
- filename: saperly-languages-api-openapi.yml
  format: yaml
  label: Saperly Languages API
  slug: saperly-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-languages-api-openapi.yml
- filename: saperly-messaging-api-openapi.yml
  format: yaml
  label: Saperly Messaging API
  slug: saperly-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-messaging-api-openapi.yml
- filename: saperly-numbers-api-openapi.yml
  format: yaml
  label: Saperly Numbers API
  slug: saperly-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-numbers-api-openapi.yml
- filename: saperly-pricing-api-openapi.yml
  format: yaml
  label: Saperly Pricing API
  slug: saperly-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-pricing-api-openapi.yml
- filename: saperly-usage-api-openapi.yml
  format: yaml
  label: Saperly Usage API
  slug: saperly-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-usage-api-openapi.yml
- filename: saperly-voice-api-openapi.yml
  format: yaml
  label: Saperly Voice API
  slug: saperly-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-voice-api-openapi.yml
- filename: saperly-voices-api-openapi.yml
  format: yaml
  label: Saperly Voices API
  slug: saperly-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-voices-api-openapi.yml
- filename: saperly-workspace-api-openapi.yml
  format: yaml
  label: Saperly Workspace API
  slug: saperly-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-workspace-api-openapi.yml
- filename: saperly-workspace-invitations-api-openapi.yml
  format: yaml
  label: Saperly Workspace Invitations API
  slug: saperly-workspace-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/saperly/openapi/saperly-workspace-invitations-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up we store your email, business name, billing address (collected by our payment processor), and the API keys you generate.
  - category: communication
    text: 'For every call or SMS sent or received on a Saperly number we record metadata: the originating number, the destination number, timestamps, duration, delivery status, segment count, and routing zone.'
  - category: behavioral
    text: We log API key activity, billing transactions, balance changes, and webhook delivery attempts so you can audit your own usage
  - category: professional
    text: we keep your message and the details you include — such as your name, work email, company, and what you’re building.
  - category: location
    text: geolocation (zone-level routing)
  deletion:
    route: email hello@saperly.com
    text: To exercise any right, email hello@saperly.com from the address tied to your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: We use personal data to operate the service, transmit your communications, bill you, prevent fraud and abuse, comply with legal obligations
  - purpose: support and product quality
    text: answer support tickets, and improve product quality through aggregated, de-identified metrics.
  residency:
  - region: United States
    text: Saperly is based in the United States and our sub-processors are all U.S.-headquartered.
  retention:
  - period: 30 days
    scope: Call recordings
    text: Call recordings — 30 days from the call end time, then deleted.
  - period: 90 days
    scope: Transcripts
    text: Transcripts — 90 days from the call end time, then deleted.
  - period: life of the line plus 7 years
    scope: Communications metadata
    text: Communications metadata — life of the line plus 7 years for billing and tax recordkeeping.
  - period: 4 years
    scope: Consent records (TCPA)
    text: Consent records (TCPA) — 4 years from creation (TCPA statute of limitations).
  - period: null
    scope: Account data
    text: Account data — for the lifetime of your account, then 30 days post-termination as a recovery window, then deleted.
  rights:
  - right: Access
    text: Access — request a copy of the personal data we hold about you.
  - right: Erasure
    text: Erasure — ask us to delete your data, subject to the legal retention exceptions in Section 8.
  - right: Portability
    text: Portability — receive your data in a structured, commonly used, machine-readable format.
  - right: Objection
    text: Objection — object to processing based on our legitimate interests.
  - right: Correct inaccurate personal information
    text: Correct inaccurate personal information.
  role:
    text: For the purposes of GDPR and UK GDPR, Saperly is the controller of account, billing, and correspondence data, and a processor of the communications content (call audio, SMS bodies, transcripts) that flows over your phone numbers.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, share it for cross-context behavioural advertising, rent it, or use it to train any third-party advertising profile.
  subprocessors:
    text: We rely on the following sub-processors to deliver Saperly.
    url: https://saperly.com/privacy
  transfers:
  - mechanism: SCC
    text: We rely on the European Commission’s Standard Contractual Clauses (and the UK Addendum) as the transfer mechanism for personal data moving to the United States
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Saperly
provenance_date: '2026-11-10'
provider_name: Saperly
provider_slug: saperly
slug: saperly-privacy-policy
source_date: '2026-11-10'
source_filename: saperly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://saperly.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Saperly\naid: saperly\nurl: https://saperly.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For the purposes of GDPR and UK GDPR, Saperly is the controller of account, billing, and correspondence\n    data, and a processor of the communications content (call audio, SMS bodies, transcripts) that flows over your\n    phone numbers.\ndata_categories:\n- category: identifying\n  text: When you sign up we store your email, business name, billing address (collected by our payment processor),\n    and the API keys you generate.\n- category: communication\n  text: 'For every call or SMS sent\
  \ or received on a Saperly number we record metadata: the originating number,\n    the destination number, timestamps, duration, delivery status, segment count, and routing zone.'\n- category: behavioral\n  text: We log API key activity, billing transactions, balance changes, and webhook delivery attempts so you can\n    audit your own usage\n- category: professional\n  text: we keep your message and the details you include — such as your name, work email, company, and what you’re\n    building.\n- category: location\n  text: geolocation (zone-level routing)\npurposes:\n- purpose: operate the service\n  text: We use personal data to operate the service, transmit your communications, bill you, prevent fraud and abuse,\n    comply with legal obligations\n- purpose: support and product quality\n  text: answer support tickets, and improve product quality through aggregated, de-identified metrics.\nretention:\n- scope: Call recordings\n  period: 30 days\n  text: Call recordings — 30 days from\
  \ the call end time, then deleted.\n- scope: Transcripts\n  period: 90 days\n  text: Transcripts — 90 days from the call end time, then deleted.\n- scope: Communications metadata\n  period: life of the line plus 7 years\n  text: Communications metadata — life of the line plus 7 years for billing and tax recordkeeping.\n- scope: Consent records (TCPA)\n  period: 4 years\n  text: Consent records (TCPA) — 4 years from creation (TCPA statute of limitations).\n- scope: Account data\n  period: null\n  text: Account data — for the lifetime of your account, then 30 days post-termination as a recovery window, then\n    deleted.\nresidency:\n- region: United States\n  text: Saperly is based in the United States and our sub-processors are all U.S.-headquartered.\ntransfers:\n- mechanism: SCC\n  text: We rely on the European Commission’s Standard Contractual Clauses (and the UK Addendum) as the transfer\n    mechanism for personal data moving to the United States\nsubprocessors:\n  url: https://saperly.com/privacy\n\
  \  text: We rely on the following sub-processors to deliver Saperly.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@saperly.com\n  text: To exercise any right, email hello@saperly.com from the address tied to your account.\nrights:\n- right: Access\n  text: Access — request a copy of the personal data we hold about you.\n- right: Erasure\n  text: Erasure — ask us to delete your data, subject to the legal retention exceptions in Section 8.\n- right: Portability\n  text: Portability — receive your data in a structured, commonly used, machine-readable format.\n- right: Objection\n  text: Objection — object to processing based on our legitimate interests.\n- right: Correct inaccurate personal information\n  text: Correct inaccurate personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, share it for cross-context behavioural advertising, rent it, or use\n    it to train any third-party advertising profile.\n"
source_yaml_url: https://artifacts.apis.io/saperly/privacy/saperly-privacy-policy.yml
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
- sale_or_sharing
summary_line: 23 quoted statements, read from Saperly's own page on 2026-11-10.
synthetic: false
tags:
- Telephony
- Voice
- SMS
- Phone Numbers
- AI Agents
- Consent
- Compliance
- MCP
- Messaging
- Communications
---
