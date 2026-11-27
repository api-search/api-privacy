---
api_specs:
- filename: firmtape-com-levels-api-openapi.yml
  format: yaml
  label: firmtape-com Levels API
  slug: firmtape-com-levels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmtape-com/openapi/firmtape-com-levels-api-openapi.yml
- filename: firmtape-com-days-api-openapi.yml
  format: yaml
  label: FirmTape Days API
  slug: firmtape-com-days-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmtape-com/openapi/firmtape-com-days-api-openapi.yml
- filename: firmtape-com-session-api-openapi.yml
  format: yaml
  label: FirmTape Session API
  slug: firmtape-com-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmtape-com/openapi/firmtape-com-session-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — to identify your account, send the link that sets your password, and tell you about billing or material changes.
  - category: identifying
    text: Password — stored only as a scrypt hash. We cannot read it.
  - category: financial
    text: Subscription status (plan, whether active, renewal date, and Stripe's customer identifier)
  - category: behavioral
    text: your trading ideas and their test results, kept against your account so they follow you across devices
  - category: device
    text: the push subscriptions of the devices you switch on
  - category: device
    text: records a salted hash of the client IP address (never the address itself)
  deletion:
    route: account page
    text: You can delete your account yourself, from the account page — no email, no waiting, no request to approve.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management
    text: to identify your account, send the link that sets your password, and tell you about billing or material changes
  - purpose: subscription access
    text: to decide whether to unlock the live session
  - purpose: abuse prevention
    text: to blunt password-guessing
  retention:
  - period: for as long as the account exists
    scope: account data
    text: Account data for as long as the account exists.
  - period: 180 days
    scope: ASK conversations
    text: ASK conversations expire 180 days after their last message
  - period: 30 days
    scope: sessions
    text: Sessions expire after 30 days, or immediately when you sign out or delete the account.
  - period: within a few hours
    scope: rate-limit counters
    text: Rate-limit counters expire within a few hours.
  - period: 35 days
    scope: API usage records
    text: Kept for 35 days.
  - period: 60 days
    scope: crawler visit counts
    text: Counts older than 60 days are discarded.
  rights:
  - right: access and portability
    text: a copy of the data we hold, correcting it, a portable export
  - right: objection
    text: objecting to processing based on legitimate interest
  - right: complaint
    text: you may also complain to your national data protection authority
  role:
    text: BrightCode LLC, operating FirmTape, is the data controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we do not sell or share your data
  subprocessors:
    text: Stripe — payments and billing. Upstash — the database holding accounts and sessions. DigitalOcean — hosting. Resend — delivery of the set-password and billing emails.
    url: null
  transfers:
  - mechanism: other
    text: your data may be transferred internationally under the safeguards those providers offer
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FirmTape
provenance_date: '2026-11-09'
provider_name: FirmTape
provider_slug: firmtape-com
slug: firmtape-com-privacy-policy
source_date: '2026-11-09'
source_filename: firmtape-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://firmtape.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FirmTape\naid: firmtape-com\nurl: https://firmtape.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: BrightCode LLC, operating FirmTape, is the data controller.\ndata_categories:\n- category: contact\n  text: Email address — to identify your account, send the link that sets your password, and tell you about billing\n    or material changes.\n- category: identifying\n  text: Password — stored only as a scrypt hash. We cannot read it.\n- category: financial\n  text: Subscription status (plan, whether active, renewal date, and Stripe's customer identifier)\n- category: behavioral\n \
  \ text: your trading ideas and their test results, kept against your account so they follow you across devices\n- category: device\n  text: the push subscriptions of the devices you switch on\n- category: device\n  text: records a salted hash of the client IP address (never the address itself)\npurposes:\n- purpose: account management\n  text: to identify your account, send the link that sets your password, and tell you about billing or material\n    changes\n- purpose: subscription access\n  text: to decide whether to unlock the live session\n- purpose: abuse prevention\n  text: to blunt password-guessing\nretention:\n- scope: account data\n  period: for as long as the account exists\n  text: Account data for as long as the account exists.\n- scope: ASK conversations\n  period: 180 days\n  text: ASK conversations expire 180 days after their last message\n- scope: sessions\n  period: 30 days\n  text: Sessions expire after 30 days, or immediately when you sign out or delete the account.\n\
  - scope: rate-limit counters\n  period: within a few hours\n  text: Rate-limit counters expire within a few hours.\n- scope: API usage records\n  period: 35 days\n  text: Kept for 35 days.\n- scope: crawler visit counts\n  period: 60 days\n  text: Counts older than 60 days are discarded.\nresidency: []\ntransfers:\n- mechanism: other\n  text: your data may be transferred internationally under the safeguards those providers offer\nsubprocessors:\n  url: null\n  text: Stripe — payments and billing. Upstash — the database holding accounts and sessions. DigitalOcean — hosting.\n    Resend — delivery of the set-password and billing emails.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account page\n  text: You can delete your account yourself, from the account page — no email, no waiting, no request to approve.\nrights:\n- right: access and portability\n  text: a copy of the data we hold, correcting it, a portable export\n- right: objection\n  text: objecting to processing\
  \ based on legitimate interest\n- right: complaint\n  text: you may also complain to your national data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell or share your data\n"
source_yaml_url: https://artifacts.apis.io/firmtape-com/privacy/firmtape-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from FirmTape's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Data
- Analytics
- Options
- Gamma
---
