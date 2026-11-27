---
api_specs:
- filename: casemagic-ai-cases-api-openapi.yml
  format: yaml
  label: CaseMagic Cases API
  slug: casemagic-ai-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casemagic-ai/openapi/casemagic-ai-cases-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your email address and a hash of your password. Never the password itself.'
  - category: financial
    text: 'Billing: your subscription status and plan. Card details are handled by Stripe and never reach CaseMagic.'
  - category: behavioral
    text: 'Usage: which pages were viewed, which lookups were run, and which assistant a request came from'
  - category: communication
    text: 'CaseMail: messages sent to a case address, their headers, their senders and recipients, their timestamps and their attachments.'
  - category: device
    text: with a one-way hash of your IP address rather than the address itself
  deletion:
    route: Ask us to delete it
    text: Ask us to delete it and it is deleted, other than records we are required to keep for tax and payment purposes.
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: null
    scope: Account and case data
    text: Account and case data are kept while the account exists.
  rights:
  - right: Removal of name from public case page
    text: you can ask us to show your name as initials and to tell search engines not to index the page, using the privacy request form
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Your case data is not sold, and is not shared with advertisers.
  subprocessors:
    text: The hosting provider that runs the application. The database provider that stores it. Stripe, for payments. The email provider that delivers and receives CaseMail. CourtListener, which is where public docket data is read from.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CaseMagic
provenance_date: '2026-11-09'
provider_name: CaseMagic
provider_slug: casemagic-ai
slug: casemagic-ai-privacy-policy
source_date: '2026-11-09'
source_filename: casemagic-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://casemagic.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CaseMagic\naid: casemagic-ai\nurl: https://casemagic.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account: your email address and a hash of your password. Never the password itself.'\n- category: financial\n  text: 'Billing: your subscription status and plan. Card details are handled by Stripe and never reach CaseMagic.'\n- category: behavioral\n  text: 'Usage: which pages were viewed, which lookups were run, and which assistant a request came from'\n- category: communication\n  text: 'CaseMail: messages sent to a case address,\
  \ their headers, their senders and recipients, their timestamps\n    and their attachments.'\n- category: device\n  text: with a one-way hash of your IP address rather than the address itself\npurposes: []\nretention:\n- scope: Account and case data\n  period: null\n  text: Account and case data are kept while the account exists.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The hosting provider that runs the application. The database provider that stores it. Stripe, for payments.\n    The email provider that delivers and receives CaseMail. CourtListener, which is where public docket data is\n    read from.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask us to delete it\n  text: Ask us to delete it and it is deleted, other than records we are required to keep for tax and payment purposes.\nrights:\n- right: Removal of name from public case page\n  text: you can ask us to show your name as initials and to tell search engines not to index\
  \ the page, using the\n    privacy request form\nsale_or_sharing:\n  stance: prohibited\n  text: Your case data is not sold, and is not shared with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/casemagic-ai/privacy/casemagic-ai-privacy-policy.yml
stated_fields:
- data_categories
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from CaseMagic's own page on 2026-11-09.
synthetic: false
tags:
- Legal Tech
- Court Data
- Alerts
- Free
---
