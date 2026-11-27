---
api_specs:
- filename: callchatsyn-com-answer-api-openapi.yml
  format: yaml
  label: CallChatSyn Answer API
  slug: callchatsyn-com-answer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callchatsyn-com/openapi/callchatsyn-com-answer-api-openapi.yml
- filename: callchatsyn-com-bookings-api-openapi.yml
  format: yaml
  label: CallChatSyn Bookings API
  slug: callchatsyn-com-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callchatsyn-com/openapi/callchatsyn-com-bookings-api-openapi.yml
- filename: callchatsyn-com-slots-api-openapi.yml
  format: yaml
  label: CallChatSyn Slots API
  slug: callchatsyn-com-slots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callchatsyn-com/openapi/callchatsyn-com-slots-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect your email address, a password (stored as a salted hash, never in plain text), and your business name
  - category: contact
    text: we collect their phone number, their name if they give one, and a transcript of the conversation
  - category: financial
    text: Stripe passes us only what we need to run your subscription (plan, status, and a customer reference ID)
  - category: behavioral
    text: we log feature usage inside the product (e.g. sign-ups, FAQs created, appointments booked)
  - category: device
    text: general device/browser info
  deletion:
    route: Delete account data from dashboard or by contacting us; customers must contact the business
    text: You can access, correct, or delete your account data at any time from your dashboard, or by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the bot
    text: 'To operate the bot: routing your customers'' messages and calls, answering FAQs, checking order status, and booking appointments.'
  - purpose: dashboard and analytics
    text: 'To run your dashboard: analytics, call/message transcripts, and the customer roster built from your own data.'
  - purpose: payments
    text: To process payments and manage your subscription through Stripe.
  - purpose: product improvement
    text: To maintain and improve the product, including diagnosing bugs and understanding feature usage.
  retention:
  - period: as long as your account is active
    scope: account and business data
    text: We keep account and business data for as long as your account is active.
  - period: within a reasonable period
    scope: organization data after account closure
    text: If you close your account, we delete your organization's data (including your customers' conversation history) within a reasonable period, except where we're required to keep records for legal, tax, or billing purposes.
  rights:
  - right: access, correct, delete
    text: You can access, correct, or delete your account data at any time from your dashboard, or by contacting us.
  - right: unsubscribe from marketing
    text: Marketing emails include an unsubscribe link.
  role:
    text: This policy explains what information CallChatSyn (“CallChatSyn,” “we,” “us”) collects through callchatsyn.com and the CallChatSyn apps
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not use your customers' conversation data to train models outside of answering that conversation.
  subprocessors:
    text: 'We use the following service providers to run CallChatSyn. Each only receives the data it needs to do its job: Supabase — database, authentication, and file storage.'
    url: null
  transfers:
  - mechanism: other
    text: Our service providers operate infrastructure in multiple countries, which may mean your data is processed outside the country where you or your customers are located.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CallChatSyn
provenance_date: '2026-11-09'
provider_name: CallChatSyn
provider_slug: callchatsyn-com
slug: callchatsyn-com-privacy-policy
source_date: '2026-11-09'
source_filename: callchatsyn-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://callchatsyn.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CallChatSyn\naid: callchatsyn-com\nurl: https://callchatsyn.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This policy explains what information CallChatSyn (“CallChatSyn,” “we,” “us”) collects through callchatsyn.com\n    and the CallChatSyn apps\ndata_categories:\n- category: contact\n  text: we collect your email address, a password (stored as a salted hash, never in plain text), and your business\n    name\n- category: contact\n  text: we collect their phone number, their name if they give one, and a transcript of the conversation\n- category: financial\n  text: Stripe passes us\
  \ only what we need to run your subscription (plan, status, and a customer reference ID)\n- category: behavioral\n  text: we log feature usage inside the product (e.g. sign-ups, FAQs created, appointments booked)\n- category: device\n  text: general device/browser info\npurposes:\n- purpose: operate the bot\n  text: 'To operate the bot: routing your customers'' messages and calls, answering FAQs, checking order status,\n    and booking appointments.'\n- purpose: dashboard and analytics\n  text: 'To run your dashboard: analytics, call/message transcripts, and the customer roster built from your own\n    data.'\n- purpose: payments\n  text: To process payments and manage your subscription through Stripe.\n- purpose: product improvement\n  text: To maintain and improve the product, including diagnosing bugs and understanding feature usage.\nretention:\n- scope: account and business data\n  period: as long as your account is active\n  text: We keep account and business data for as long as\
  \ your account is active.\n- scope: organization data after account closure\n  period: within a reasonable period\n  text: If you close your account, we delete your organization's data (including your customers' conversation history)\n    within a reasonable period, except where we're required to keep records for legal, tax, or billing purposes.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Our service providers operate infrastructure in multiple countries, which may mean your data is processed\n    outside the country where you or your customers are located.\nsubprocessors:\n  url: null\n  text: 'We use the following service providers to run CallChatSyn. Each only receives the data it needs to do its\n    job: Supabase — database, authentication, and file storage.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account data from dashboard or by contacting us; customers must contact the business\n  text: You can access, correct, or delete your\
  \ account data at any time from your dashboard, or by contacting us.\nrights:\n- right: access, correct, delete\n  text: You can access, correct, or delete your account data at any time from your dashboard, or by contacting us.\n- right: unsubscribe from marketing\n  text: Marketing emails include an unsubscribe link.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not use your customers' conversation data to train models\n    outside of answering that conversation.\n"
source_yaml_url: https://artifacts.apis.io/callchatsyn-com/privacy/callchatsyn-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from CallChatSyn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Receptionist
- Answering Service
- Voice AI
- Appointment Booking
- Chatbots
- WhatsApp
- Small Business
- MCP
---
