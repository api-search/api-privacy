---
api_specs:
- filename: cosvoice-com-activity-api-openapi.yml
  format: yaml
  label: CosVoice Activity API
  slug: cosvoice-com-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-activity-api-openapi.yml
- filename: cosvoice-com-calls-api-openapi.yml
  format: yaml
  label: CosVoice Calls API
  slug: cosvoice-com-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-calls-api-openapi.yml
- filename: cosvoice-com-contacts-api-openapi.yml
  format: yaml
  label: CosVoice Contacts API
  slug: cosvoice-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-contacts-api-openapi.yml
- filename: cosvoice-com-emails-api-openapi.yml
  format: yaml
  label: CosVoice Emails API
  slug: cosvoice-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-emails-api-openapi.yml
- filename: cosvoice-com-history-api-openapi.yml
  format: yaml
  label: CosVoice History API
  slug: cosvoice-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-history-api-openapi.yml
- filename: cosvoice-com-line-api-openapi.yml
  format: yaml
  label: CosVoice Line API
  slug: cosvoice-com-line-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-line-api-openapi.yml
- filename: cosvoice-com-messages-api-openapi.yml
  format: yaml
  label: CosVoice Messages API
  slug: cosvoice-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-messages-api-openapi.yml
- filename: cosvoice-com-reservations-api-openapi.yml
  format: yaml
  label: CosVoice Reservations API
  slug: cosvoice-com-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-reservations-api-openapi.yml
- filename: cosvoice-com-settings-api-openapi.yml
  format: yaml
  label: CosVoice Settings API
  slug: cosvoice-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-settings-api-openapi.yml
- filename: cosvoice-com-webhook-api-openapi.yml
  format: yaml
  label: CosVoice Webhook API
  slug: cosvoice-com-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosvoice-com/openapi/cosvoice-com-webhook-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email, name, and optional password (stored hashed).'
  - category: contact
    text: 'Line data: your line''s number, persona settings, contacts you add, and your mobile number if you provide it.'
  - category: communication
    text: 'Call data: call metadata (numbers, times, duration), transcripts, and structured notes produced during calls.'
  - category: financial
    text: 'Payment: Stripe takes your card. We never see or store the card number.'
  - category: device
    text: 'Website visits: which page was opened, the site you came from, and a random number in a cookie that tells one browser from another.'
  - category: communication
    text: 'Messages and email: texts sent to your line and the subject and a short excerpt of emails sent to your line''s address.'
  deletion:
    route: Close your line from Settings or by emailing hello@cosvoice.com
    text: Closing a line releases the number and deletes call content within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the line
    text: 'To run your line: answering and placing calls, producing debriefs, delivering notifications and webhooks you configure, metering minutes, preventing abuse, and supporting you.'
  - purpose: Weekly tip email
    text: We also send a short weekly tip on using your line, which you can stop with one click.
  residency:
  - region: United States
    text: We store your data in the United States.
  retention:
  - period: 30 days
    scope: Call content after line closed
    text: When a line is closed, its call content is deleted within 30 days.
  rights:
  - right: Edit or delete contacts
    text: You can edit or delete contacts, revoke API keys, remove webhooks, and close your line from Settings or by emailing hello@cosvoice.com.
  role:
    text: CosVoice (“we”) provides phone lines and email identities for AI assistants.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not use your call content to train models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CosVoice
provenance_date: '2026-11-09'
provider_name: CosVoice
provider_slug: cosvoice-com
slug: cosvoice-com-privacy-policy
source_date: '2026-11-09'
source_filename: cosvoice-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cosvoice.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CosVoice\naid: cosvoice-com\nurl: https://cosvoice.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CosVoice (“we”) provides phone lines and email identities for AI assistants.\ndata_categories:\n- category: identifying\n  text: 'Account data: your email, name, and optional password (stored hashed).'\n- category: contact\n  text: 'Line data: your line''s number, persona settings, contacts you add, and your mobile number if you provide\n    it.'\n- category: communication\n  text: 'Call data: call metadata (numbers, times, duration), transcripts, and structured notes produced during\n\
  \    calls.'\n- category: financial\n  text: 'Payment: Stripe takes your card. We never see or store the card number.'\n- category: device\n  text: 'Website visits: which page was opened, the site you came from, and a random number in a cookie that tells\n    one browser from another.'\n- category: communication\n  text: 'Messages and email: texts sent to your line and the subject and a short excerpt of emails sent to your\n    line''s address.'\npurposes:\n- purpose: Run the line\n  text: 'To run your line: answering and placing calls, producing debriefs, delivering notifications and webhooks\n    you configure, metering minutes, preventing abuse, and supporting you.'\n- purpose: Weekly tip email\n  text: We also send a short weekly tip on using your line, which you can stop with one click.\nretention:\n- scope: Call content after line closed\n  period: 30 days\n  text: When a line is closed, its call content is deleted within 30 days.\nresidency:\n- region: United States\n  text: We\
  \ store your data in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Close your line from Settings or by emailing hello@cosvoice.com\n  text: Closing a line releases the number and deletes call content within 30 days.\nrights:\n- right: Edit or delete contacts\n  text: You can edit or delete contacts, revoke API keys, remove webhooks, and close your line from Settings or\n    by emailing hello@cosvoice.com.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not use your call content to train models.\n"
source_yaml_url: https://artifacts.apis.io/cosvoice-com/privacy/cosvoice-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from CosVoice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Voice
- Telephony
- Phone Numbers
- AI Receptionist
- Call Transcription
- MCP
- Small Business
---
