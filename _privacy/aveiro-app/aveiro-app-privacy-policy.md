---
api_specs:
- filename: aveiro-app-openapi-generated.yml
  format: yaml
  label: Aveiro API
  slug: aveiro-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aveiro-app/openapi/_ae-authored/aveiro-app-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: display name, username, bio and profile photo
  - category: contact
    text: email address and password (or sign-in with Google or GitHub)
  - category: financial
    text: we store your Stripe customer ID and subscription status, never your full card number.
  - category: location
    text: an optional country derived from the IP at the time of the event
  - category: behavioral
    text: From these events we may compute per-subscriber engagement
  - category: device
    text: browser, operating system and device type (from the user agent)
  - category: communication
    text: we process recipient email addresses and message content to deliver mail
  - category: other
    text: server logs, request metadata and rate-limiting data, including IP addresses
  deletion:
    route: Settings → Security → Delete account
    text: 'Delete: Settings → Security → Delete account.'
  dpa:
    available: true
    text: They process personal data only on our instructions, under a data processing agreement.
    url: null
  purposes:
  - purpose: account and service provision
    text: to create your account, provide the service you signed up for, take payment and support you
  - purpose: AI features
    text: we send your prompts and the context you include (such as page content or attachments) to AI model providers through the Vercel AI Gateway so the model can respond.
  - purpose: aggregate usage statistics
    text: aggregate usage statistics for the site owner
  - purpose: newsletter sending
    text: 'Aveiro (a Dopler service): sending the newsletters you subscribe to.'
  residency:
  - region: outside the EEA, mostly United States
    text: Some providers process data outside the European Economic Area, mostly in the United States.
  retention:
  - period: while your account is open
    scope: account data
    text: 'Account data: while your account is open.'
  - period: eight years
    scope: invoices and payment records
    text: 'Invoices and payment records: eight years, as the Hungarian Accounting Act requires (Act C of 2000, section 169).'
  - period: up to 90 days
    scope: request logs and error reports
    text: 'Request logs and error reports: up to 90 days.'
  - period: a rolling window of up to 30 days
    scope: backups
    text: 'Backups: a rolling window of up to 30 days, after which deleted data is gone from them too.'
  rights:
  - right: access
    text: give you a copy of the personal data we hold about you (access)
  - right: erasure
    text: delete it (erasure)
  - right: portability
    text: give it to you, or to another provider, in a portable format (portability)
  - right: objection
    text: stop processing it on the basis of our legitimate interest (objection)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, rent it out or trade it.
  subprocessors:
    text: 'Upstash: rate limiting.'
    url: null
  transfers:
  - mechanism: DPF
    text: the transfer relies on the EU-US Data Privacy Framework for providers certified under it
  - mechanism: SCC
    text: or on the European Commission's standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aveiro
provenance_date: '2026-11-09'
provider_name: Aveiro
provider_slug: aveiro-app
slug: aveiro-app-privacy-policy
source_date: '2026-11-09'
source_filename: aveiro-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aveiro.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aveiro\naid: aveiro-app\nurl: https://www.aveiro.app/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: display name, username, bio and profile photo\n- category: contact\n  text: email address and password (or sign-in with Google or GitHub)\n- category: financial\n  text: we store your Stripe customer ID and subscription status, never your full card number.\n- category: location\n  text: an optional country derived from the IP at the time of the event\n- category: behavioral\n  text: From these events we may compute per-subscriber\
  \ engagement\n- category: device\n  text: browser, operating system and device type (from the user agent)\n- category: communication\n  text: we process recipient email addresses and message content to deliver mail\n- category: other\n  text: server logs, request metadata and rate-limiting data, including IP addresses\npurposes:\n- purpose: account and service provision\n  text: to create your account, provide the service you signed up for, take payment and support you\n- purpose: AI features\n  text: we send your prompts and the context you include (such as page content or attachments) to AI model providers\n    through the Vercel AI Gateway so the model can respond.\n- purpose: aggregate usage statistics\n  text: aggregate usage statistics for the site owner\n- purpose: newsletter sending\n  text: 'Aveiro (a Dopler service): sending the newsletters you subscribe to.'\nretention:\n- scope: account data\n  period: while your account is open\n  text: 'Account data: while your account is\
  \ open.'\n- scope: invoices and payment records\n  period: eight years\n  text: 'Invoices and payment records: eight years, as the Hungarian Accounting Act requires (Act C of 2000, section\n    169).'\n- scope: request logs and error reports\n  period: up to 90 days\n  text: 'Request logs and error reports: up to 90 days.'\n- scope: backups\n  period: a rolling window of up to 30 days\n  text: 'Backups: a rolling window of up to 30 days, after which deleted data is gone from them too.'\nresidency:\n- region: outside the EEA, mostly United States\n  text: Some providers process data outside the European Economic Area, mostly in the United States.\ntransfers:\n- mechanism: DPF\n  text: the transfer relies on the EU-US Data Privacy Framework for providers certified under it\n- mechanism: SCC\n  text: or on the European Commission's standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'Upstash: rate limiting.'\ndpa:\n  available: true\n  url: null\n  text: They process personal\
  \ data only on our instructions, under a data processing agreement.\ndeletion:\n  route: Settings → Security → Delete account\n  text: 'Delete: Settings → Security → Delete account.'\nrights:\n- right: access\n  text: give you a copy of the personal data we hold about you (access)\n- right: erasure\n  text: delete it (erasure)\n- right: portability\n  text: give it to you, or to another provider, in a portable format (portability)\n- right: objection\n  text: stop processing it on the basis of our legitimate interest (objection)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, rent it out or trade it.\n"
source_yaml_url: https://artifacts.apis.io/aveiro-app/privacy/aveiro-app-privacy-policy.yml
stated_fields:
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
summary_line: 27 quoted statements, read from Aveiro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- Publishing
- Templates
- Artificial Intelligence
---
