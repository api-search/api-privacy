---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email address, handle, and authentication identifiers when an account is created.'
  - category: behavioral
    text: 'Usage data: log files, device/browser info, IP address, and basic analytics events.'
  - category: financial
    text: 'Payment data: handled by Stripe. Calfeed does not store card numbers.'
  - category: other
    text: 'Content: schedules, descriptions, files, and calendar data submitted to generate or edit calendars.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Generate calendars
    text: Generate calendars, hosted feeds, and public calendar pages.
  - purpose: Authentication and abuse prevention
    text: Authenticate accounts and prevent abuse.
  - purpose: Payments and transactional email
    text: Process payments, manage credits, and send transactional email.
  - purpose: Product improvement
    text: Improve the product (aggregate, non-identifying analytics).
  - purpose: Debugging conversion
    text: Debug and improve how schedules are turned into calendars, by reviewing submitted inputs (see retention below).
  retention:
  - period: 90 days
    scope: Submitted inputs (create/edit prompt text)
    text: We retain the raw text you submit (create and edit prompts) for up to 90 days to debug conversion errors and improve quality.
  - period: null
    scope: Account data
    text: 'Account data: kept for the life of the account.'
  - period: 90 days after the last event
    scope: Calendar content
    text: 'Calendar content: retained until deletion or auto-archive (90 days after the last event).'
  - period: 90 days
    scope: Logs
    text: 'Logs: 90 days.'
  rights:
  - right: access, correction, deletion, data portability
    text: Depending on jurisdiction (e.g. GDPR, CCPA), rights may include access, correction, deletion, and data portability.
  role:
    text: Calfeed, LLC , a Delaware limited liability company (“Calfeed,” “we,” “us”), operates calfeed.ai.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: 'Sharing We share information only with service providers needed to run the product: Hosting and database: Vercel, Neon. Email: Resend. Payments: Stripe. AI processing: Anthropic. Analytics: Google Analytics 4.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Calfeed
provenance_date: '2026-11-09'
provider_name: Calfeed
provider_slug: calfeed-ai
slug: calfeed-ai-privacy-policy
source_date: '2026-11-09'
source_filename: calfeed-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://calfeed.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Calfeed\naid: calfeed-ai\nurl: https://calfeed.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Calfeed, LLC , a Delaware limited liability company (“Calfeed,” “we,” “us”), operates calfeed.ai.\ndata_categories:\n- category: identifying\n  text: 'Account data: email address, handle, and authentication identifiers when an account is created.'\n- category: behavioral\n  text: 'Usage data: log files, device/browser info, IP address, and basic analytics events.'\n- category: financial\n  text: 'Payment data: handled by Stripe. Calfeed does not store card numbers.'\n- category: other\n\
  \  text: 'Content: schedules, descriptions, files, and calendar data submitted to generate or edit calendars.'\npurposes:\n- purpose: Generate calendars\n  text: Generate calendars, hosted feeds, and public calendar pages.\n- purpose: Authentication and abuse prevention\n  text: Authenticate accounts and prevent abuse.\n- purpose: Payments and transactional email\n  text: Process payments, manage credits, and send transactional email.\n- purpose: Product improvement\n  text: Improve the product (aggregate, non-identifying analytics).\n- purpose: Debugging conversion\n  text: Debug and improve how schedules are turned into calendars, by reviewing submitted inputs (see retention\n    below).\nretention:\n- scope: Submitted inputs (create/edit prompt text)\n  period: 90 days\n  text: We retain the raw text you submit (create and edit prompts) for up to 90 days to debug conversion errors\n    and improve quality.\n- scope: Account data\n  period: null\n  text: 'Account data: kept for the life\
  \ of the account.'\n- scope: Calendar content\n  period: 90 days after the last event\n  text: 'Calendar content: retained until deletion or auto-archive (90 days after the last event).'\n- scope: Logs\n  period: 90 days\n  text: 'Logs: 90 days.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Sharing We share information only with service providers needed to run the product: Hosting and database:\n    Vercel, Neon. Email: Resend. Payments: Stripe. AI processing: Anthropic. Analytics: Google Analytics 4.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correction, deletion, data portability\n  text: Depending on jurisdiction (e.g. GDPR, CCPA), rights may include access, correction, deletion, and data portability.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/calfeed-ai/privacy/calfeed-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Calfeed's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Productivity
- Scheduling
- Web App
---
