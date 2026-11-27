---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you join the waitlist we collect your name, email address, and phone number (with country code).
  - category: identifying
    text: Creating a Waqi account collects your email address and password
  - category: financial
    text: Stripe Subscription billing (once Waqi billing launches) Payment details directly — we never see or store card numbers
  - category: communication
    text: If you provide a phone number for briefings, we may contact you on WhatsApp.
  - category: other
    text: the response is scanned for sensitive data (card numbers, emails, phone numbers, government IDs, and similar categories), that data is redacted
  deletion:
    route: Dashboard deletion of connectors or whole account, or email info@bilazann.com
    text: For Waqi account data you can also delete individual connectors or your whole account directly from the dashboard.
  dpa:
    available: true
    text: A separate Data Processing Agreement sets out our obligations to you as processor in more detail
    url: null
  purposes:
  - purpose: Waitlist launch contact
    text: to contact you about Bilazann's launch and early access
  - purpose: Waqi redaction of sensitive fields
    text: We process that data solely to detect and redact sensitive fields before it reaches your AI client, we do not use it for any other purpose
  - purpose: Connector credential use
    text: specifically so Waqi can make the calls needed to serve your requests
  residency:
  - region: outside UAE
    text: Some sub-processors store data outside the UAE.
  retention:
  - period: 12 months
    scope: Waitlist data
    text: no longer than 12 months after collection without renewed contact
  - period: null
    scope: Waqi account data and connector credentials
    text: kept for as long as your account is active, and deleted within 30 days of account closure
  - period: null
    scope: Waqi business data returned by connected tools
    text: we do not retain it once a call completes
  rights:
  - right: access
    text: You may request access to, correction of, or deletion of your personal data, withdraw consent, or object to processing.
  - right: deletion
    text: Write to info@bilazann.com ; we respond within 30 days.
  role:
    text: 'Waqi: our role is data processor, yours is data controller'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Sub-processor Purpose What it touches Vercel Website & app hosting All traffic in transit; nothing at rest Supabase Database, authentication Account data, encrypted connector credentials, redacted audit log Resend Transactional email (signup confirmation, alerts) Email address only Twilio / Meta WhatsApp briefing delivery Phone number, message content Stripe Subscription billing
    url: null
  transfers:
  - mechanism: other
    text: Where personal data leaves the UAE we rely on the PDPL's transfer provisions and contractual safeguards with each provider.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bilazann
provenance_date: '2026-11-09'
provider_name: Bilazann
provider_slug: bilazann-com
slug: bilazann-com-privacy-policy
source_date: '2026-11-09'
source_filename: bilazann-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bilazann.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bilazann\naid: bilazann-com\nurl: https://www.bilazann.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Waqi: our role is data processor, yours is data controller'\ndata_categories:\n- category: identifying\n  text: When you join the waitlist we collect your name, email address, and phone number (with country code).\n- category: identifying\n  text: Creating a Waqi account collects your email address and password\n- category: financial\n  text: Stripe Subscription billing (once Waqi billing launches) Payment details directly — we never see or store\n    card numbers\n- category: communication\n\
  \  text: If you provide a phone number for briefings, we may contact you on WhatsApp.\n- category: other\n  text: the response is scanned for sensitive data (card numbers, emails, phone numbers, government IDs, and similar\n    categories), that data is redacted\npurposes:\n- purpose: Waitlist launch contact\n  text: to contact you about Bilazann's launch and early access\n- purpose: Waqi redaction of sensitive fields\n  text: We process that data solely to detect and redact sensitive fields before it reaches your AI client, we do\n    not use it for any other purpose\n- purpose: Connector credential use\n  text: specifically so Waqi can make the calls needed to serve your requests\nretention:\n- scope: Waitlist data\n  period: 12 months\n  text: no longer than 12 months after collection without renewed contact\n- scope: Waqi account data and connector credentials\n  period: null\n  text: kept for as long as your account is active, and deleted within 30 days of account closure\n- scope:\
  \ Waqi business data returned by connected tools\n  period: null\n  text: we do not retain it once a call completes\nresidency:\n- region: outside UAE\n  text: Some sub-processors store data outside the UAE.\ntransfers:\n- mechanism: other\n  text: Where personal data leaves the UAE we rely on the PDPL's transfer provisions and contractual safeguards\n    with each provider.\nsubprocessors:\n  url: null\n  text: Sub-processor Purpose What it touches Vercel Website & app hosting All traffic in transit; nothing at rest\n    Supabase Database, authentication Account data, encrypted connector credentials, redacted audit log Resend Transactional\n    email (signup confirmation, alerts) Email address only Twilio / Meta WhatsApp briefing delivery Phone number,\n    message content Stripe Subscription billing\ndpa:\n  available: true\n  url: null\n  text: A separate Data Processing Agreement sets out our obligations to you as processor in more detail\ndeletion:\n  route: Dashboard deletion of\
  \ connectors or whole account, or email info@bilazann.com\n  text: For Waqi account data you can also delete individual connectors or your whole account directly from the\n    dashboard.\nrights:\n- right: access\n  text: You may request access to, correction of, or deletion of your personal data, withdraw consent, or object\n    to processing.\n- right: deletion\n  text: Write to info@bilazann.com ; we respond within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/bilazann-com/privacy/bilazann-com-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Bilazann's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data
- Privacy
- Business
---
