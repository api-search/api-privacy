---
api_specs:
- filename: api.json
  format: json
  label: Vocenya API
  slug: vocenya-api
  spec_type: OpenAPI
  url: https://vocenya.com/docs/api.json
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account details: name, email address, phone number, password (stored hashed), business name, website, industry, business hours and team members.'
  - category: financial
    text: Billing information, collected and stored by our payment processor, Stripe. We do not store full card numbers.
  - category: communication
    text: Call audio, recordings and transcripts , where the business has recording or transcripts enabled for its plan.
  - category: device
    text: Device and usage information such as IP address, browser type, pages viewed and referring pages, collected through server logs and similar technologies.
  - category: biometric
    text: 'Voice samples, if you choose to give your receptionist your own voice: we send the recording to ElevenLabs to create a cloned voice'
  deletion:
    route: Account owners delete recordings, transcripts, chats and leads in the portal or app; others email info@gh-businesssolutions.com
    text: You can ask us to delete the information Vocenya holds about you, including data received through WhatsApp, text messages and calls
  dpa:
    available: true
    text: DPA
    url: null
  purposes:
  - purpose: Provide the Services
    text: 'To provide the Services: answering and routing calls, texts and chats, booking appointments, sending summaries, handing conversations to people, and placing outbound calls a customer has set up.'
  - purpose: Improve reliability and quality
    text: To improve reliability and quality of the Services.
  - purpose: Billing and security
    text: To operate accounts, billing, security, fraud prevention and customer support.
  residency:
  - region: United States
    text: We are based in the United States and store data primarily in the United States.
  retention:
  - period: null
    scope: Active accounts and general data
    text: We keep information for as long as an account is active and as needed to provide the Services, then delete or de-identify it within a reasonable period
  - period: 30 days
    scope: WhatsApp messages, call records and leads deleted on request
    text: We will delete your messages, call records and lead details (or have the business do so) within 30 days
  - period: 30, 90 or 365 days
    scope: Automatic deletion of recordings and transcripts
    text: set call recordings and transcripts to be deleted automatically after a period you choose (30, 90 or 365 days)
  rights:
  - right: access, correct, delete or obtain a copy
    text: you may have the right to access, correct, delete or obtain a copy of your personal information, and to opt out of certain processing.
  - right: opt out of marketing emails
    text: You can opt out of marketing emails at any time.
  role:
    text: the business is the controller (or "covered entity" or "business") and we act as its processor or service provider.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for cross-context behavioral advertising.
  subprocessors:
    text: The full list, with what each receives and which are never used for HIPAA-mode accounts, is on our sub-processors page .
    url: https://vocenya.com/sub-processors
  transfers:
  - mechanism: other
    text: Some support and live-agent work is performed from other countries, including the Philippines, with safeguards to protect the information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: vocenya-com
provenance_date: '2026-11-10'
provider_name: vocenya-com
provider_slug: vocenya-com
slug: vocenya-com-privacy-policy
source_date: '2026-11-10'
source_filename: vocenya-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vocenya.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: vocenya-com\naid: vocenya-com\nurl: https://vocenya.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: the business is the controller (or \"covered entity\" or \"business\") and we act as its processor or service\n    provider.\ndata_categories:\n- category: contact\n  text: 'Account details: name, email address, phone number, password (stored hashed), business name, website, industry,\n    business hours and team members.'\n- category: financial\n  text: Billing information, collected and stored by our payment processor, Stripe. We do not store full card numbers.\n- category: communication\n\
  \  text: Call audio, recordings and transcripts , where the business has recording or transcripts enabled for its\n    plan.\n- category: device\n  text: Device and usage information such as IP address, browser type, pages viewed and referring pages, collected\n    through server logs and similar technologies.\n- category: biometric\n  text: 'Voice samples, if you choose to give your receptionist your own voice: we send the recording to ElevenLabs\n    to create a cloned voice'\npurposes:\n- purpose: Provide the Services\n  text: 'To provide the Services: answering and routing calls, texts and chats, booking appointments, sending summaries,\n    handing conversations to people, and placing outbound calls a customer has set up.'\n- purpose: Improve reliability and quality\n  text: To improve reliability and quality of the Services.\n- purpose: Billing and security\n  text: To operate accounts, billing, security, fraud prevention and customer support.\nretention:\n- scope: Active accounts\
  \ and general data\n  period: null\n  text: We keep information for as long as an account is active and as needed to provide the Services, then delete\n    or de-identify it within a reasonable period\n- scope: WhatsApp messages, call records and leads deleted on request\n  period: 30 days\n  text: We will delete your messages, call records and lead details (or have the business do so) within 30 days\n- scope: Automatic deletion of recordings and transcripts\n  period: 30, 90 or 365 days\n  text: set call recordings and transcripts to be deleted automatically after a period you choose (30, 90 or 365\n    days)\nresidency:\n- region: United States\n  text: We are based in the United States and store data primarily in the United States.\ntransfers:\n- mechanism: other\n  text: Some support and live-agent work is performed from other countries, including the Philippines, with safeguards\n    to protect the information.\nsubprocessors:\n  url: https://vocenya.com/sub-processors\n  text: The\
  \ full list, with what each receives and which are never used for HIPAA-mode accounts, is on our sub-processors\n    page .\ndpa:\n  available: true\n  url: null\n  text: DPA\ndeletion:\n  route: Account owners delete recordings, transcripts, chats and leads in the portal or app; others email info@gh-businesssolutions.com\n  text: You can ask us to delete the information Vocenya holds about you, including data received through WhatsApp,\n    text messages and calls\nrights:\n- right: access, correct, delete or obtain a copy\n  text: you may have the right to access, correct, delete or obtain a copy of your personal information, and to\n    opt out of certain processing.\n- right: opt out of marketing emails\n  text: You can opt out of marketing emails at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/vocenya-com/privacy/vocenya-com-privacy-policy.yml
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
summary_line: 20 quoted statements, read from vocenya-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Communications
- Customer Service
- Automation
- Voice
---
