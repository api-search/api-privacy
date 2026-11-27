---
api_specs:
- filename: agoria-studio-search-api-openapi.yml
  format: yaml
  label: Agoria Search API
  slug: agoria-studio-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agoria-studio/openapi/agoria-studio-search-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, contact details (email or phone), the content of the request, and appointment or order details
  - category: contact
    text: Business email address, and sign-in state.
  - category: communication
    text: the sender, recipients, subject, date, thread and text of the messages in the mailbox, and the mailbox's own address
  - category: behavioral
    text: We log the search queries sent to our discovery endpoints, which tools were called, and which AI source a request appears to come from
  - category: financial
    text: Where a payment is held in escrow, we retain the transaction record (amount, parties, status) but not the payment instrument.
  deletion:
    route: Email hello@agoria.studio
    text: Messages already synced stay on the business's records until they are deleted — email hello@agoria.studio and we will delete them within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Publish agent-callable interface
    text: To publish a business's agent-callable interface and answer AI assistants accurately about it.
  - purpose: Carry out bookings and payments
    text: To carry out the bookings, orders, quotes, payments and messages requested through the platform.
  - purpose: Operate and improve service
    text: To operate, secure, debug and improve the service.
  residency:
  - region: Australia/global
    text: Microsoft Azure — hosting, database and email delivery (Australia/global regions).
  retention:
  - period: 5,000 per business
    scope: Synced mailbox messages
    text: up to the most recent 5,000 per business, for as long as the owner's retention setting says (indefinitely unless they set a limit)
  - period: 7 years
    scope: Escrow and payment records
    text: escrow and payment records are kept for 7 years, as Australian tax and financial-record rules require
  - period: 15 minutes
    scope: Sign-in links
    text: Sign-in links — single-use, and expire in 15 minutes.
  rights:
  - right: access
    text: You can ask us to access , correct , or delete the personal information we hold about you, or to stop processing it.
  - right: complaint to OAIC
    text: Under the Australian Privacy Act you may also complain to the Office of the Australian Information Commissioner.
  - right: GDPR rights including portability and objection
    text: If you are in the EEA or UK, GDPR rights including portability and objection apply
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not use customer contact details for our own marketing.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agoria
provenance_date: '2026-11-09'
provider_name: Agoria
provider_slug: agoria-studio
slug: agoria-studio-privacy-policy
source_date: '2026-11-09'
source_filename: agoria-studio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agoria.studio/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agoria\naid: agoria-studio\nurl: https://agoria.studio/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name, contact details (email or phone), the content of the request, and appointment or order details\n- category: contact\n  text: Business email address, and sign-in state.\n- category: communication\n  text: the sender, recipients, subject, date, thread and text of the messages in the mailbox, and the mailbox's\n    own address\n- category: behavioral\n  text: We log the search queries sent to our discovery endpoints, which tools\
  \ were called, and which AI source\n    a request appears to come from\n- category: financial\n  text: Where a payment is held in escrow, we retain the transaction record (amount, parties, status) but not the\n    payment instrument.\npurposes:\n- purpose: Publish agent-callable interface\n  text: To publish a business's agent-callable interface and answer AI assistants accurately about it.\n- purpose: Carry out bookings and payments\n  text: To carry out the bookings, orders, quotes, payments and messages requested through the platform.\n- purpose: Operate and improve service\n  text: To operate, secure, debug and improve the service.\nretention:\n- scope: Synced mailbox messages\n  period: 5,000 per business\n  text: up to the most recent 5,000 per business, for as long as the owner's retention setting says (indefinitely\n    unless they set a limit)\n- scope: Escrow and payment records\n  period: 7 years\n  text: escrow and payment records are kept for 7 years, as Australian tax and\
  \ financial-record rules require\n- scope: Sign-in links\n  period: 15 minutes\n  text: Sign-in links — single-use, and expire in 15 minutes.\nresidency:\n- region: Australia/global\n  text: Microsoft Azure — hosting, database and email delivery (Australia/global regions).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@agoria.studio\n  text: Messages already synced stay on the business's records until they are deleted — email hello@agoria.studio\n    and we will delete them within 30 days.\nrights:\n- right: access\n  text: You can ask us to access , correct , or delete the personal information we hold about you, or to stop processing\n    it.\n- right: complaint to OAIC\n  text: Under the Australian Privacy Act you may also complain to the Office of the Australian Information Commissioner.\n- right: GDPR rights including portability and objection\n  text: If you are in the EEA or UK, GDPR rights\
  \ including portability and objection apply\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not use customer contact details for our own marketing.\n"
source_yaml_url: https://artifacts.apis.io/agoria-studio/privacy/agoria-studio-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Agoria's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Business
- Platform
- Commerce
- Automation
---
