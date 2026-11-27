---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — used as your login identifier (magic-link auth) and for service emails
  - category: financial
    text: Stripe customer record — when you start a paid subscription, Stripe creates a customer record holding your billing email, name, address (collected at Checkout for tax purposes), and payment method
  - category: device
    text: we store the IP address, country, and browser or client identifier (User-Agent) of that request, to prevent abuse of free trials
  - category: communication
    text: Chat messages — visitor and assistant turns, persisted in our database so the subscriber can read transcripts in their studio
  deletion:
    route: contact the website where you used the chatbot, or email support@claraconverts.com
    text: If you are a visitor and want your conversation or lead deleted, the fastest route is to contact the website where you used the chatbot.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service emails and account login
    text: used as your login identifier (magic-link auth) and for service emails
  - purpose: IP rate limiting and abuse prevention
    text: used to enforce rate limits on the marketing site (preview generation, login requests)
  - purpose: Google Calendar appointment booking
    text: Google Calendar data is used solely to check availability and create the appointments a visitor requests, on the connecting subscriber's instruction — never for any other purpose
  residency:
  - region: United States
    text: Some of our processors (notably Stripe and Cloudflare) operate in the United States.
  retention:
  - period: 24 months after cancellation
    scope: subscriber account record
    text: Subscriber account record — kept while the subscription is active, plus 24 months after cancellation for tax and dispute reasons.
  - period: default 90 days
    scope: conversations and leads
    text: Conversations and leads — auto-deleted after the subscriber's retention window (default 90 days) by a daily cleanup job.
  - period: 24 hours
    scope: IP rate-limit counters
    text: IP rate-limit counters — automatically deleted after 24 hours.
  - period: 90 days
    scope: trial creation details
    text: Trial creation details (IP address, country, User-Agent) — automatically deleted 90 days after the trial was created.
  - period: one hour
    scope: preview tenant in KV
    text: We store the preview tenant in KV for one hour, then it's automatically deleted.
  rights:
  - right: access
    text: Access the data we hold about you
  - right: correction
    text: Have it corrected if it's wrong
  - right: restriction
    text: Restrict how we process it
  - right: objection
    text: Object to processing based on legitimate interest
  - right: portability
    text: Receive it in a portable format
  - right: complaint
    text: Lodge a complaint with your local data-protection authority
  role:
    text: For your account , billing, and login data, ClaraConverts is the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your information, and we do not share it with advertisers.
  subprocessors:
    text: We use a small number of processors to run the Service
    url: null
  transfers:
  - mechanism: DPF
    text: Where personal data leaves the EEA, we rely on appropriate safeguards (the EU–US Data Privacy Framework or standard contractual clauses).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClaraConverts
provenance_date: '2026-11-09'
provider_name: ClaraConverts
provider_slug: claraconverts-com
slug: claraconverts-com-privacy-policy
source_date: '2026-11-09'
source_filename: claraconverts-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://claraconverts.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClaraConverts\naid: claraconverts-com\nurl: https://claraconverts.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your account , billing, and login data, ClaraConverts is the controller.\ndata_categories:\n- category: contact\n  text: Email address — used as your login identifier (magic-link auth) and for service emails\n- category: financial\n  text: Stripe customer record — when you start a paid subscription, Stripe creates a customer record holding your\n    billing email, name, address (collected at Checkout for tax purposes), and payment method\n- category: device\n  text: we\
  \ store the IP address, country, and browser or client identifier (User-Agent) of that request, to prevent\n    abuse of free trials\n- category: communication\n  text: Chat messages — visitor and assistant turns, persisted in our database so the subscriber can read transcripts\n    in their studio\npurposes:\n- purpose: service emails and account login\n  text: used as your login identifier (magic-link auth) and for service emails\n- purpose: IP rate limiting and abuse prevention\n  text: used to enforce rate limits on the marketing site (preview generation, login requests)\n- purpose: Google Calendar appointment booking\n  text: Google Calendar data is used solely to check availability and create the appointments a visitor requests,\n    on the connecting subscriber's instruction — never for any other purpose\nretention:\n- scope: subscriber account record\n  period: 24 months after cancellation\n  text: Subscriber account record — kept while the subscription is active, plus 24 months\
  \ after cancellation for\n    tax and dispute reasons.\n- scope: conversations and leads\n  period: default 90 days\n  text: Conversations and leads — auto-deleted after the subscriber's retention window (default 90 days) by a daily\n    cleanup job.\n- scope: IP rate-limit counters\n  period: 24 hours\n  text: IP rate-limit counters — automatically deleted after 24 hours.\n- scope: trial creation details\n  period: 90 days\n  text: Trial creation details (IP address, country, User-Agent) — automatically deleted 90 days after the trial\n    was created.\n- scope: preview tenant in KV\n  period: one hour\n  text: We store the preview tenant in KV for one hour, then it's automatically deleted.\nresidency:\n- region: United States\n  text: Some of our processors (notably Stripe and Cloudflare) operate in the United States.\ntransfers:\n- mechanism: DPF\n  text: Where personal data leaves the EEA, we rely on appropriate safeguards (the EU–US Data Privacy Framework\n    or standard contractual\
  \ clauses).\nsubprocessors:\n  url: null\n  text: We use a small number of processors to run the Service\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact the website where you used the chatbot, or email support@claraconverts.com\n  text: If you are a visitor and want your conversation or lead deleted, the fastest route is to contact the website\n    where you used the chatbot.\nrights:\n- right: access\n  text: Access the data we hold about you\n- right: correction\n  text: Have it corrected if it's wrong\n- right: restriction\n  text: Restrict how we process it\n- right: objection\n  text: Object to processing based on legitimate interest\n- right: portability\n  text: Receive it in a portable format\n- right: complaint\n  text: Lodge a complaint with your local data-protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your information, and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/claraconverts-com/privacy/claraconverts-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from ClaraConverts's own page on 2026-11-09.
synthetic: false
tags:
- AI Chatbot
- Lead Capture
- Appointment Booking
- Ecommerce Checkout
- CRM Integration
- Web agency tools
---
