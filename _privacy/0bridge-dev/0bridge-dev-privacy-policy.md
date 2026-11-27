---
api_specs:
- filename: 0bridge-dev-openapi-generated.yml
  format: yaml
  label: 0bridge API
  slug: 0bridge-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0bridge-dev/openapi/_ae-authored/0bridge-dev-openapi-generated.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address. If you sign in with Google or GitHub, also your name, profile picture and the account ID the provider shares.
  - category: contact
    text: 'What you send through the contact form , with or without an account: the topic, your email address, the name and company if you give them, and your message'
  - category: financial
    text: 'Billing. If you buy a paid plan: the plan and product, its state and period, and Polar''s customer and subscription IDs.'
  - category: location
    text: the country, until the request expires
  - category: device
    text: IP address, user agent and request metadata that our hosting provider processes to deliver and protect the service.
  - category: communication
    text: 'Mail to Drive. Only if you give a Drive folder an email address: the messages sent to it (sender, recipients, subject, date, the result of our authentication checks, the text and attachments).'
  - category: behavioral
    text: Page views. Cloudflare Web Analytics counts visits to 0bridge.dev pages (the page, the referring site, country, browser and load time).
  deletion:
    route: Delete account in the dashboard (Settings → Delete account)
    text: delete your account in the dashboard (Settings → Delete account)
  dpa:
    available: true
    text: Data Processing Agreement for teams and companies
    url: null
  purposes:
  - purpose: Sign in and keep connections working
    text: To sign you in, keep your connections working and carry out what you ask of the service
  - purpose: Security and abuse protection
    text: protect the service against abuse
  - purpose: Understand usage and improve service
    text: understand how 0 bridge is used so we can improve it
  - purpose: Product update emails
    text: If you turn on product updates, we also email you what's new in 0 bridge, about once a month
  residency:
  - region: Republic of Korea
    text: We are in the Republic of Korea, and our providers process data in the United States and on Cloudflare's global network.
  retention:
  - period: while your account exists
    scope: Account data
    text: Account data is kept while your account exists.
  - period: 90 days
    scope: Audit logs
    text: Audit logs are kept for 90 days.
  - period: 400 days
    scope: Token counts
    text: Token counts are kept 400 days.
  - period: 7 days by default
    scope: Webhook events
    text: Webhook events are kept 7 days by default (up to 30 if you choose).
  - period: 10 minutes
    scope: Clipboard items
    text: Clipboard items go when read or after 10 minutes.
  - period: up to 28 days
    scope: Encrypted backups
    text: Encrypted backups of the service are kept for up to 28 days (weekly ones for 12 weeks)
  rights:
  - right: access
    text: access the personal data we hold about you, and get a copy
  - right: correct
    text: correct it
  - right: delete
    text: delete it
  - right: restrict
    text: restrict how we use it
  - right: port
    text: 'port it: get what you gave us in a common machine-readable format, or have it sent to another service'
  - right: object
    text: object to what we do on the basis of legitimate interests, including the analytics from our server
  - right: withdraw consent
    text: withdraw consent you gave (analytics cookies, product updates) at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, use it for advertising, or use your data to train AI models.
  subprocessors:
    text: The current list, and the Data Processing Agreement for teams and companies, are at Sub-processors and DPA .
    url: null
  transfers:
  - mechanism: adequacy
    text: For data from the EEA, the European Commission has decided that Korea protects personal data adequately (Decision (EU) 2022/254)
  - mechanism: DPF
    text: Our US providers receive it under the EU-U.S. Data Privacy Framework (and its UK Extension) where they are certified (Cloudflare and PostHog)
  - mechanism: SCC
    text: otherwise under the European Commission's Standard Contractual Clauses (Polar)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 0bridge
provenance_date: '2026-11-09'
provider_name: 0bridge
provider_slug: 0bridge-dev
slug: 0bridge-dev-privacy-policy
source_date: '2026-11-09'
source_filename: 0bridge-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://0bridge.dev/policy/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 0bridge\naid: 0bridge-dev\nurl: https://0bridge.dev/policy/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address. If you sign in with Google or GitHub, also your name, profile picture and the account\n    ID the provider shares.\n- category: contact\n  text: 'What you send through the contact form , with or without an account: the topic, your email address, the\n    name and company if you give them, and your message'\n- category: financial\n  text: 'Billing. If you buy a paid plan: the plan and product, its state and\
  \ period, and Polar''s customer and\n    subscription IDs.'\n- category: location\n  text: the country, until the request expires\n- category: device\n  text: IP address, user agent and request metadata that our hosting provider processes to deliver and protect the\n    service.\n- category: communication\n  text: 'Mail to Drive. Only if you give a Drive folder an email address: the messages sent to it (sender, recipients,\n    subject, date, the result of our authentication checks, the text and attachments).'\n- category: behavioral\n  text: Page views. Cloudflare Web Analytics counts visits to 0bridge.dev pages (the page, the referring site, country,\n    browser and load time).\npurposes:\n- purpose: Sign in and keep connections working\n  text: To sign you in, keep your connections working and carry out what you ask of the service\n- purpose: Security and abuse protection\n  text: protect the service against abuse\n- purpose: Understand usage and improve service\n  text: understand\
  \ how 0 bridge is used so we can improve it\n- purpose: Product update emails\n  text: If you turn on product updates, we also email you what's new in 0 bridge, about once a month\nretention:\n- scope: Account data\n  period: while your account exists\n  text: Account data is kept while your account exists.\n- scope: Audit logs\n  period: 90 days\n  text: Audit logs are kept for 90 days.\n- scope: Token counts\n  period: 400 days\n  text: Token counts are kept 400 days.\n- scope: Webhook events\n  period: 7 days by default\n  text: Webhook events are kept 7 days by default (up to 30 if you choose).\n- scope: Clipboard items\n  period: 10 minutes\n  text: Clipboard items go when read or after 10 minutes.\n- scope: Encrypted backups\n  period: up to 28 days\n  text: Encrypted backups of the service are kept for up to 28 days (weekly ones for 12 weeks)\nresidency:\n- region: Republic of Korea\n  text: We are in the Republic of Korea, and our providers process data in the United States and\
  \ on Cloudflare's\n    global network.\ntransfers:\n- mechanism: adequacy\n  text: For data from the EEA, the European Commission has decided that Korea protects personal data adequately\n    (Decision (EU) 2022/254)\n- mechanism: DPF\n  text: Our US providers receive it under the EU-U.S. Data Privacy Framework (and its UK Extension) where they are\n    certified (Cloudflare and PostHog)\n- mechanism: SCC\n  text: otherwise under the European Commission's Standard Contractual Clauses (Polar)\nsubprocessors:\n  url: null\n  text: The current list, and the Data Processing Agreement for teams and companies, are at Sub-processors and DPA\n    .\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement for teams and companies\ndeletion:\n  route: Delete account in the dashboard (Settings → Delete account)\n  text: delete your account in the dashboard (Settings → Delete account)\nrights:\n- right: access\n  text: access the personal data we hold about you, and get a copy\n- right:\
  \ correct\n  text: correct it\n- right: delete\n  text: delete it\n- right: restrict\n  text: restrict how we use it\n- right: port\n  text: 'port it: get what you gave us in a common machine-readable format, or have it sent to another service'\n- right: object\n  text: object to what we do on the basis of legitimate interests, including the analytics from our server\n- right: withdraw consent\n  text: withdraw consent you gave (analytics cookies, product updates) at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, use it for advertising, or use your data to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/0bridge-dev/privacy/0bridge-dev-privacy-policy.yml
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
summary_line: 32 quoted statements, read from 0bridge's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Integration
- Team Collaboration
- Productivity
---
