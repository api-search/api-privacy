---
api_specs:
- filename: agenttoolworks-com-openapi-generated.yml
  format: yaml
  label: agenttoolworks-com API
  slug: agenttoolworks-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenttoolworks-com/openapi/_ae-authored/agenttoolworks-com-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address , to create your account, send sign-in links and tell you about your key, a payment or a security issue.
  - category: identifying
    text: Your API keys , stored only as a one-way hash.
  - category: behavioral
    text: 'A usage record per call : which tool, when, how many credits, and whether it succeeded.'
  - category: financial
    text: 'Your credit balance and purchases : amounts, dates and the Stripe reference of each payment.'
  - category: device
    text: Your IP address , used transiently to rate-limit signups and sign-in requests and to stop abuse.
  - category: behavioral
    text: 'Where your visit came from , recorded once when you sign up and never updated: the referring site'
  deletion:
    route: Email support@agenttoolworks.com from the address on the account
    text: You can ask for a copy of your data, its correction, or the deletion of your account by writing to support@agenttoolworks.com from the address on the account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and sign-in
    text: to create your account, send sign-in links and tell you about your key, a payment or a security issue
  - purpose: Accounting and billing
    text: 'Legal basis: contract, and keeping accurate accounts.'
  - purpose: Rate-limiting and abuse prevention
    text: used transiently to rate-limit signups and sign-in requests and to stop abuse
  - purpose: Channel attribution
    text: our legitimate interest in knowing which channels bring us users, so we spend on the ones that work
  retention:
  - period: null
    scope: Account data
    text: Account data is kept while your account exists.
  - period: 90 days
    scope: Detailed usage records
    text: Detailed usage records stay in the live database for 90 days and are then moved to archive storage, kept for accounting.
  - period: null
    scope: Payment records
    text: Payment records are kept as long as accounting law requires.
  - period: 15 minutes
    scope: Sign-in links
    text: Sign-in links expire after 15 minutes and sessions after 30 days.
  rights:
  - right: Access
    text: You can ask for a copy of your data
  - right: Correction
    text: its correction
  - right: Deletion
    text: the deletion of your account
  - right: Restrict or object to processing (EU/UK)
    text: If you are in the European Union or the United Kingdom you also have the rights to restrict or object to processing
  - right: Data portability (EU/UK)
    text: to data portability
  - right: Complain to data protection authority (EU/UK)
    text: and to complain to your data protection authority
  role:
    text: The controller is ECOM FR LLC , which operates AgentToolWorks
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data to anyone.
  subprocessors:
    text: 'Cloudflare : hosting, database and the Turnstile check. Postmark (ActiveCampaign): sending sign-in and account emails. Stripe : taking card payments.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agenttoolworks-com
provenance_date: '2026-11-09'
provider_name: agenttoolworks-com
provider_slug: agenttoolworks-com
slug: agenttoolworks-com-privacy-policy
source_date: '2026-11-09'
source_filename: agenttoolworks-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenttoolworks.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agenttoolworks-com\naid: agenttoolworks-com\nurl: https://agenttoolworks.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is ECOM FR LLC , which operates AgentToolWorks\ndata_categories:\n- category: contact\n  text: Your email address , to create your account, send sign-in links and tell you about your key, a payment or\n    a security issue.\n- category: identifying\n  text: Your API keys , stored only as a one-way hash.\n- category: behavioral\n  text: 'A usage record per call : which tool, when, how many credits, and whether it succeeded.'\n- category: financial\n\
  \  text: 'Your credit balance and purchases : amounts, dates and the Stripe reference of each payment.'\n- category: device\n  text: Your IP address , used transiently to rate-limit signups and sign-in requests and to stop abuse.\n- category: behavioral\n  text: 'Where your visit came from , recorded once when you sign up and never updated: the referring site'\npurposes:\n- purpose: Account creation and sign-in\n  text: to create your account, send sign-in links and tell you about your key, a payment or a security issue\n- purpose: Accounting and billing\n  text: 'Legal basis: contract, and keeping accurate accounts.'\n- purpose: Rate-limiting and abuse prevention\n  text: used transiently to rate-limit signups and sign-in requests and to stop abuse\n- purpose: Channel attribution\n  text: our legitimate interest in knowing which channels bring us users, so we spend on the ones that work\nretention:\n- scope: Account data\n  period: null\n  text: Account data is kept while your account\
  \ exists.\n- scope: Detailed usage records\n  period: 90 days\n  text: Detailed usage records stay in the live database for 90 days and are then moved to archive storage, kept\n    for accounting.\n- scope: Payment records\n  period: null\n  text: Payment records are kept as long as accounting law requires.\n- scope: Sign-in links\n  period: 15 minutes\n  text: Sign-in links expire after 15 minutes and sessions after 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Cloudflare : hosting, database and the Turnstile check. Postmark (ActiveCampaign): sending sign-in and\n    account emails. Stripe : taking card payments.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@agenttoolworks.com from the address on the account\n  text: You can ask for a copy of your data, its correction, or the deletion of your account by writing to support@agenttoolworks.com\n    from the address on the account.\nrights:\n- right: Access\n  text:\
  \ You can ask for a copy of your data\n- right: Correction\n  text: its correction\n- right: Deletion\n  text: the deletion of your account\n- right: Restrict or object to processing (EU/UK)\n  text: If you are in the European Union or the United Kingdom you also have the rights to restrict or object to\n    processing\n- right: Data portability (EU/UK)\n  text: to data portability\n- right: Complain to data protection authority (EU/UK)\n  text: and to complain to your data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data to anyone.\n"
source_yaml_url: https://artifacts.apis.io/agenttoolworks-com/privacy/agenttoolworks-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from agenttoolworks-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Verification
- Data Tools
- Web Scraping
---
