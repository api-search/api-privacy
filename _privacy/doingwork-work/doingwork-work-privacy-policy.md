---
api_specs:
- filename: doingwork-work-status-api-openapi.yml
  format: yaml
  label: doingwork-work Status API
  slug: doingwork-work-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doingwork-work/openapi/doingwork-work-status-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and workers: names, work emails, phone numbers you give us, shop name and contact details, roles and what each worker can see or do.'
  - category: location
    text: 'Photos: we keep each photo as the shop uploaded it, including the data the camera saved with it: when it was taken, the GPS location and altitude, the compass direction, and the camera and lens.'
  - category: device
    text: 'Sign-in and security: one-time sign-in links, session records and times, your IP address for rate limits'
  - category: communication
    text: 'Texts and calls (only for shops that connect their own phone number): the phone numbers, the texts sent and received, call records (time, length, direction, outcome), voicemail links and length'
  - category: financial
    text: 'Payments: Stripe handles card and bank details. We never see full card or bank account numbers. We keep payment amounts, status, fees, refunds and disputes.'
  - category: behavioral
    text: 'Email: what we sent, to whom, whether it was delivered, and unsubscribe choices.'
  deletion:
    route: Email contact@doingwork.work from your account email; owners can export and close shops; shops can delete customers one by one
    text: To correct or delete your own information, email contact@doingwork.work from your account email. We may need to confirm who you are.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run Doing Work for each shop
    text: To run Doing Work for each shop, sign people in, take our fees, send the emails a shop asks us to send, keep the service secure, prevent fraud and abuse, answer support requests and meet legal duties.
  - purpose: Service delivery to shops
    text: We don't sell personal information, and we don't use a shop's customer list to market to those customers.
  residency:
  - region: United States
    text: Fly.io, our cloud hosting provider, which runs the app, its PostgreSQL database and photo storage in the United States.
  retention:
  - period: 90 days
    scope: Homeowner requests not booked
    text: Photos and details from a homeowner request that was not booked are deleted 90 days after it was sent.
  - period: 90 days
    scope: Closed shop working data
    text: 'After 90 days, we delete the shop''s working data: photos and photo files, photo shares and tags, notes, scheduled messages, templates, saved reports, request forms, the price book, approval rules, schedules and hours, time off, invites, webhooks, agent tasks and saved cards.'
  - period: 30 days
    scope: Agent A2A tasks
    text: Each task is deleted 30 days after its last update
  - period: null
    scope: Unclaimed agents
    text: an agent that was never claimed is deleted one day after its claim expires
  rights:
  - right: Know, correct or delete
    text: Some state laws give residents rights to know, correct or delete personal information. We honor those requests where they apply, and we won't treat you differently for using them.
  - right: Export
    text: The owner can export the shop's data in Doing Work at any time.
  role:
    text: For a shop's own account, its workers and its use of Doing Work, we decide how data is used, and this policy applies directly. For the customer information a shop puts into Doing Work, the shop decides how it is used. We handle it as the shop's service provider, only to run Doing Work for that shop.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information, and we don't use a shop's customer list to market to those customers.
  subprocessors:
    text: The current list, with what each one handles, is at doingwork.work/subprocessors/.
    url: doingwork.work/subprocessors/
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: doingwork-work
provenance_date: '2026-11-09'
provider_name: doingwork-work
provider_slug: doingwork-work
slug: doingwork-work-privacy-policy
source_date: '2026-11-09'
source_filename: doingwork-work-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://doingwork.work/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: doingwork-work\naid: doingwork-work\nurl: https://doingwork.work/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For a shop's own account, its workers and its use of Doing Work, we decide how data is used, and this policy\n    applies directly. For the customer information a shop puts into Doing Work, the shop decides how it is used.\n    We handle it as the shop's service provider, only to run Doing Work for that shop.\ndata_categories:\n- category: identifying\n  text: 'Account and workers: names, work emails, phone numbers you give us, shop name and contact details, roles\n    and what\
  \ each worker can see or do.'\n- category: location\n  text: 'Photos: we keep each photo as the shop uploaded it, including the data the camera saved with it: when it\n    was taken, the GPS location and altitude, the compass direction, and the camera and lens.'\n- category: device\n  text: 'Sign-in and security: one-time sign-in links, session records and times, your IP address for rate limits'\n- category: communication\n  text: 'Texts and calls (only for shops that connect their own phone number): the phone numbers, the texts sent\n    and received, call records (time, length, direction, outcome), voicemail links and length'\n- category: financial\n  text: 'Payments: Stripe handles card and bank details. We never see full card or bank account numbers. We keep\n    payment amounts, status, fees, refunds and disputes.'\n- category: behavioral\n  text: 'Email: what we sent, to whom, whether it was delivered, and unsubscribe choices.'\npurposes:\n- purpose: Run Doing Work for each shop\n\
  \  text: To run Doing Work for each shop, sign people in, take our fees, send the emails a shop asks us to send,\n    keep the service secure, prevent fraud and abuse, answer support requests and meet legal duties.\n- purpose: Service delivery to shops\n  text: We don't sell personal information, and we don't use a shop's customer list to market to those customers.\nretention:\n- scope: Homeowner requests not booked\n  period: 90 days\n  text: Photos and details from a homeowner request that was not booked are deleted 90 days after it was sent.\n- scope: Closed shop working data\n  period: 90 days\n  text: 'After 90 days, we delete the shop''s working data: photos and photo files, photo shares and tags, notes,\n    scheduled messages, templates, saved reports, request forms, the price book, approval rules, schedules and hours,\n    time off, invites, webhooks, agent tasks and saved cards.'\n- scope: Agent A2A tasks\n  period: 30 days\n  text: Each task is deleted 30 days after its last\
  \ update\n- scope: Unclaimed agents\n  period: null\n  text: an agent that was never claimed is deleted one day after its claim expires\nresidency:\n- region: United States\n  text: Fly.io, our cloud hosting provider, which runs the app, its PostgreSQL database and photo storage in the\n    United States.\ntransfers: []\nsubprocessors:\n  url: doingwork.work/subprocessors/\n  text: The current list, with what each one handles, is at doingwork.work/subprocessors/.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@doingwork.work from your account email; owners can export and close shops; shops can delete\n    customers one by one\n  text: To correct or delete your own information, email contact@doingwork.work from your account email. We may\n    need to confirm who you are.\nrights:\n- right: Know, correct or delete\n  text: Some state laws give residents rights to know, correct or delete personal information. We honor those requests\n    where they apply,\
  \ and we won't treat you differently for using them.\n- right: Export\n  text: The owner can export the shop's data in Doing Work at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information, and we don't use a shop's customer list to market to those customers.\n"
source_yaml_url: https://artifacts.apis.io/doingwork-work/privacy/doingwork-work-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from doingwork-work's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Field Service Management
- Invoicing
- Mobile
---
