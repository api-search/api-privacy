---
api_specs:
- filename: aicertificates-study-content-api-openapi.yml
  format: yaml
  label: AI Certificates Content API
  slug: aicertificates-study-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicertificates-study/openapi/aicertificates-study-content-api-openapi.yml
- filename: aicertificates-study-readiness-api-openapi.yml
  format: yaml
  label: AI Certificates Readiness API
  slug: aicertificates-study-readiness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicertificates-study/openapi/aicertificates-study-readiness-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Sign-in is handled by Clerk, which holds your email address and, if you sign in with Google, the identifier Google gives it.
  - category: contact
    text: If you ask for your score by email, the address is used to send it and is passed to Resend
  - category: behavioral
    text: which question, which exam domain, what you picked, and whether it was right
  - category: device
    text: Within one visit, a link you click to another page here carries a random visit tag, so the pages of that visit can be counted together.
  - category: financial
    text: What comes back to us is that a payment succeeded, an identifier for it so a later refund can be matched to it, and the country used to work out tax.
  deletion:
    route: Contact page request, or unsubscribe link for emails
    text: If you have an account, write to the same address to get a copy of what is held or to have it deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Show progress and track missed questions
    text: That is what lets your progress be shown back to you on any device
  - purpose: Percentile comparison for readiness check
    text: the point of it is a percentile against other people
  - purpose: Product analytics
    text: Page views and interactions are recorded with PostHog to see which pages are useful and where people give up.
  - purpose: Score delivery and prep series
    text: is used to send it and is passed to Resend, which delivers the mail and keeps the address on a list so a short prep series can follow
  - purpose: Diagnose broken flows
    text: Session recordings are captured on the public site to diagnose broken flows.
  retention:
  - period: null
    scope: Readiness check rows
    text: those entries are purged once their month closes
  - period: null
    scope: Payment record
    text: we keep the record of the payment itself for as long as tax and accounting rules require
  rights:
  - right: Access copy of held data
    text: If you have an account, write to the same address to get a copy of what is held or to have it deleted.
  - right: Deletion of account and answer history
    text: Ask on the contact page to have that history deleted
  - right: Unsubscribe from emails
    text: To remove an email address, use the unsubscribe link in any message
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Nothing is sold, and nothing is shared with advertisers, because there are none.
  subprocessors:
    text: Processors Vercel — hosting and content delivery. Neon — the database holding readiness check rows. PostHog — product analytics and session recording. Resend — sending score emails and the one Developer – Professional launch email, where you asked for them. Clerk — sign-in, for accounts created by a purchase. Stripe — payment, tax, and receipts, as merchant of record
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Certificates
provenance_date: '2026-11-09'
provider_name: AI Certificates
provider_slug: aicertificates-study
slug: aicertificates-study-privacy-policy
source_date: '2026-11-09'
source_filename: aicertificates-study-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aicertificates.study/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Certificates\naid: aicertificates-study\nurl: https://aicertificates.study/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Sign-in is handled by Clerk, which holds your email address and, if you sign in with Google, the identifier\n    Google gives it.\n- category: contact\n  text: If you ask for your score by email, the address is used to send it and is passed to Resend\n- category: behavioral\n  text: which question, which exam domain, what you picked, and whether it was right\n- category: device\n  text: Within one visit,\
  \ a link you click to another page here carries a random visit tag, so the pages of that\n    visit can be counted together.\n- category: financial\n  text: What comes back to us is that a payment succeeded, an identifier for it so a later refund can be matched\n    to it, and the country used to work out tax.\npurposes:\n- purpose: Show progress and track missed questions\n  text: That is what lets your progress be shown back to you on any device\n- purpose: Percentile comparison for readiness check\n  text: the point of it is a percentile against other people\n- purpose: Product analytics\n  text: Page views and interactions are recorded with PostHog to see which pages are useful and where people give\n    up.\n- purpose: Score delivery and prep series\n  text: is used to send it and is passed to Resend, which delivers the mail and keeps the address on a list so a\n    short prep series can follow\n- purpose: Diagnose broken flows\n  text: Session recordings are captured on the public\
  \ site to diagnose broken flows.\nretention:\n- scope: Readiness check rows\n  period: null\n  text: those entries are purged once their month closes\n- scope: Payment record\n  period: null\n  text: we keep the record of the payment itself for as long as tax and accounting rules require\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Processors Vercel — hosting and content delivery. Neon — the database holding readiness check rows. PostHog\n    — product analytics and session recording. Resend — sending score emails and the one Developer – Professional\n    launch email, where you asked for them. Clerk — sign-in, for accounts created by a purchase. Stripe — payment,\n    tax, and receipts, as merchant of record\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact page request, or unsubscribe link for emails\n  text: If you have an account, write to the same address to get a copy of what is held or to have it deleted.\nrights:\n- right: Access\
  \ copy of held data\n  text: If you have an account, write to the same address to get a copy of what is held or to have it deleted.\n- right: Deletion of account and answer history\n  text: Ask on the contact page to have that history deleted\n- right: Unsubscribe from emails\n  text: To remove an email address, use the unsubscribe link in any message\nsale_or_sharing:\n  stance: conditional\n  text: Nothing is sold, and nothing is shared with advertisers, because there are none.\n"
source_yaml_url: https://artifacts.apis.io/aicertificates-study/privacy/aicertificates-study-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from AI Certificates's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Artificial Intelligence
- Certification
- Practice Exams
- Anthropic
---
