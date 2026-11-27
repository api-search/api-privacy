---
api_specs:
- filename: callnode-io-call-records-api-openapi.yml
  format: yaml
  label: CallNode Call Records API
  slug: callnode-io-call-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-call-records-api-openapi.yml
- filename: callnode-io-email-api-openapi.yml
  format: yaml
  label: CallNode Email API
  slug: callnode-io-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-email-api-openapi.yml
- filename: callnode-io-faxes-api-openapi.yml
  format: yaml
  label: CallNode Faxes API
  slug: callnode-io-faxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-faxes-api-openapi.yml
- filename: callnode-io-messaging-api-openapi.yml
  format: yaml
  label: CallNode Messaging API
  slug: callnode-io-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-messaging-api-openapi.yml
- filename: callnode-io-outbound-calls-api-openapi.yml
  format: yaml
  label: CallNode Outbound Calls API
  slug: callnode-io-outbound-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-outbound-calls-api-openapi.yml
- filename: callnode-io-phone-numbers-api-openapi.yml
  format: yaml
  label: CallNode Phone Numbers API
  slug: callnode-io-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-phone-numbers-api-openapi.yml
- filename: callnode-io-sip-trunks-api-openapi.yml
  format: yaml
  label: CallNode SIP Trunks API
  slug: callnode-io-sip-trunks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-sip-trunks-api-openapi.yml
- filename: callnode-io-wholesale-api-openapi.yml
  format: yaml
  label: CallNode Wholesale API
  slug: callnode-io-wholesale-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callnode-io/openapi/callnode-io-wholesale-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, company name
  - category: financial
    text: Payment information (processed securely via Stripe)
  - category: communication
    text: Call records (date, time, duration, participants)
  - category: communication
    text: Message content (SMS/MMS text and media)
  - category: communication
    text: Call transcripts and voice recordings (when a feature you enable produces them; see Section 6)
  - category: device
    text: IP addresses and device information
  - category: behavioral
    text: API requests and usage patterns
  - category: location
    text: an approximate location (city and country) derived from your IP address
  deletion:
    route: Email request to the privacy contact address; response within 30 days
    text: You can request deletion of your data by emailing [email protected] (or [email protected] ). We respond within 30 days.
  dpa:
    available: true
    text: If you route traffic involving individuals in the EEA, the United Kingdom or Switzerland and need a Data Processing Addendum, contact [email protected] and we will put one in place with you.
    url: null
  purposes:
  - purpose: Service delivery
    text: Process calls and messages, route communications
  - purpose: Billing
    text: Calculate charges, process payments, maintain transaction records
  - purpose: Support
    text: Troubleshoot issues, respond to inquiries
  - purpose: Compliance
    text: Meet legal obligations, prevent fraud and abuse
  - purpose: Improvement
    text: Analyze usage patterns, enhance service quality
  residency:
  - region: Canada (Quebec)
    text: Our servers run in data centers in Canada (Quebec)
  - region: United States (AWS us-east-1)
    text: stored media, recordings and files are kept in the United States (AWS, us-east-1)
  retention:
  - period: a minimum of two years
    scope: Call detail records
    text: Retained for a minimum of two years .
  - period: 90 days
    scope: Call transcripts
    text: Retained for 90 days, then removed by a daily purge.
  - period: 90 days
    scope: Voicemail
    text: Audio and its transcript retained for 90 days, then removed by a daily purge.
  - period: 90 days
    scope: Messages
    text: Message text and MMS media retained for 90 days, then removed by a daily purge
  - period: while account is active
    scope: Account data
    text: 'Account Data: Retained while account is active'
  - period: 7 years
    scope: Payment records
    text: 'Payment Records: Retained for 7 years per tax requirements'
  - period: indefinitely
    scope: Suppression / Do-Not-Call entries
    text: 'Suppression / Do-Not-Call entries: Retained indefinitely.'
  rights:
  - right: Access
    text: 'Access: Request copies of your personal data'
  - right: Correction
    text: 'Correction: Update inaccurate information'
  - right: Deletion
    text: 'Deletion: Request deletion of your data'
  - right: Portability
    text: 'Portability: Receive your data in machine-readable format'
  - right: Opt-out
    text: 'Opt-Out: Unsubscribe from onboarding and marketing emails with the link in any such email, or by writing to us'
  role:
    text: In the language of the GDPR and UK GDPR, you are the controller and CallNode is the processor for that data. For your own account information — your name, email address, company, billing details, and your use of our website and dashboard — CallNode is the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal information to third parties.
  subprocessors:
    text: Our current subprocessors, the purpose of each, and the categories of vendor we do not name publicly are listed on the Security & Compliance page.
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers from the EEA, the United Kingdom or Switzerland are made under the EU Standard Contractual Clauses (with the UK Addendum) incorporated in a Data Processing Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CallNode
provenance_date: '2026-11-09'
provider_name: CallNode
provider_slug: callnode-io
slug: callnode-io-privacy-policy
source_date: '2026-11-09'
source_filename: callnode-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://callnode.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CallNode\naid: callnode-io\nurl: https://callnode.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In the language of the GDPR and UK GDPR, you are the controller and CallNode is the processor for that data.\n    For your own account information — your name, email address, company, billing details, and your use of our website\n    and dashboard — CallNode is the controller.\ndata_categories:\n- category: identifying\n  text: Name, email address, company name\n- category: financial\n  text: Payment information (processed securely via Stripe)\n- category: communication\n  text: Call records\
  \ (date, time, duration, participants)\n- category: communication\n  text: Message content (SMS/MMS text and media)\n- category: communication\n  text: Call transcripts and voice recordings (when a feature you enable produces them; see Section 6)\n- category: device\n  text: IP addresses and device information\n- category: behavioral\n  text: API requests and usage patterns\n- category: location\n  text: an approximate location (city and country) derived from your IP address\npurposes:\n- purpose: Service delivery\n  text: Process calls and messages, route communications\n- purpose: Billing\n  text: Calculate charges, process payments, maintain transaction records\n- purpose: Support\n  text: Troubleshoot issues, respond to inquiries\n- purpose: Compliance\n  text: Meet legal obligations, prevent fraud and abuse\n- purpose: Improvement\n  text: Analyze usage patterns, enhance service quality\nretention:\n- scope: Call detail records\n  period: a minimum of two years\n  text: Retained for\
  \ a minimum of two years .\n- scope: Call transcripts\n  period: 90 days\n  text: Retained for 90 days, then removed by a daily purge.\n- scope: Voicemail\n  period: 90 days\n  text: Audio and its transcript retained for 90 days, then removed by a daily purge.\n- scope: Messages\n  period: 90 days\n  text: Message text and MMS media retained for 90 days, then removed by a daily purge\n- scope: Account data\n  period: while account is active\n  text: 'Account Data: Retained while account is active'\n- scope: Payment records\n  period: 7 years\n  text: 'Payment Records: Retained for 7 years per tax requirements'\n- scope: Suppression / Do-Not-Call entries\n  period: indefinitely\n  text: 'Suppression / Do-Not-Call entries: Retained indefinitely.'\nresidency:\n- region: Canada (Quebec)\n  text: Our servers run in data centers in Canada (Quebec)\n- region: United States (AWS us-east-1)\n  text: stored media, recordings and files are kept in the United States (AWS, us-east-1)\ntransfers:\n\
  - mechanism: SCC\n  text: Transfers from the EEA, the United Kingdom or Switzerland are made under the EU Standard Contractual Clauses\n    (with the UK Addendum) incorporated in a Data Processing Addendum\nsubprocessors:\n  url: null\n  text: Our current subprocessors, the purpose of each, and the categories of vendor we do not name publicly are\n    listed on the Security & Compliance page.\ndpa:\n  available: true\n  url: null\n  text: If you route traffic involving individuals in the EEA, the United Kingdom or Switzerland and need a Data\n    Processing Addendum, contact [email protected] and we will put one in place with you.\ndeletion:\n  route: Email request to the privacy contact address; response within 30 days\n  text: You can request deletion of your data by emailing [email protected] (or [email protected] ). We respond\n    within 30 days.\nrights:\n- right: Access\n  text: 'Access: Request copies of your personal data'\n- right: Correction\n  text: 'Correction: Update inaccurate\
  \ information'\n- right: Deletion\n  text: 'Deletion: Request deletion of your data'\n- right: Portability\n  text: 'Portability: Receive your data in machine-readable format'\n- right: Opt-out\n  text: 'Opt-Out: Unsubscribe from onboarding and marketing emails with the link in any such email, or by writing\n    to us'\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/callnode-io/privacy/callnode-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 33 quoted statements, read from CallNode's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Telephony
- Phone Numbers
- SMS
- Webhook
- SIP Trunking
- AI Agents
- Communications
---
