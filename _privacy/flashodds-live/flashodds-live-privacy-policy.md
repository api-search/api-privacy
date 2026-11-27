---
api_specs:
- filename: flashodds-live-api-openapi.json
  format: json
  label: Sorqen API API
  slug: sorqen-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flashodds-live/openapi/_original/flashodds-live-api-openapi.json
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: If you make an account we hold your email address and the things you chose to save.
  - category: identifying
    text: None of them holds a name, an ID, or anything that identifies you, and none is shared with anyone.
  - category: device
    text: Our server keeps ordinary web logs, and holds your IP address briefly in memory for rate limiting so one client cannot scrape the whole board.
  - category: behavioral
    text: A few product events named steps only, see below
  - category: financial
    text: We store only Stripe's identifiers for your customer, subscription and price, which is what lets us know you are on Pro.
  deletion:
    route: Email request to the contact address from the address on the account
    text: Email [email protected] from the address on the account. We delete the account, everything saved on it, and cancel any subscription.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rate limiting
    text: holds your IP address briefly in memory for rate limiting so one client cannot scrape the whole board
  - purpose: aggregate traffic counting
    text: We do set a few small first-party cookies so we can count, in aggregate, what brings people here and whether they come back.
  - purpose: sending sign-in links
    text: Email address to send your sign-in link
  - purpose: product analytics
    text: so we can tell which parts of the product are worth keeping
  - purpose: payments
    text: Stripe processes payments.
  residency:
  - region: Germany
    text: our own server, which is rented from Hetzner and located in Germany
  retention:
  - period: null
    scope: sign-in links
    text: Sign-in links are deleted after they expire.
  - period: null
    scope: sessions
    text: Sessions are deleted when they expire or when you sign out.
  - period: 180 days
    scope: product analytics counts
    text: Counts are kept for 180 days.
  - period: null
    scope: account data
    text: Everything else is kept until you ask us to delete your account, at which point all of it goes.
  rights:
  - right: access
    text: You can also ask for a copy of what we hold
  - right: correction
    text: or ask us to correct it.
  - right: deletion
    text: Everything else is kept until you ask us to delete your account, at which point all of it goes.
  role:
    text: Flash AI Solutions publishes Flash Odds.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, we do not share it for advertising, and no advertising network receives anything from this site.
  subprocessors:
    text: 'Three processors, each doing one job: Stripe for payments, Resend for sending your sign-in link and alert emails, and our own server, which is rented from Hetzner and located in Germany.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: flashodds-live
provenance_date: '2026-11-09'
provider_name: flashodds-live
provider_slug: flashodds-live
slug: flashodds-live-privacy-policy
source_date: '2026-11-09'
source_filename: flashodds-live-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flashodds.live/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: flashodds-live\naid: flashodds-live\nurl: https://flashodds.live/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Flash AI Solutions publishes Flash Odds.\ndata_categories:\n- category: contact\n  text: If you make an account we hold your email address and the things you chose to save.\n- category: identifying\n  text: None of them holds a name, an ID, or anything that identifies you, and none is shared with anyone.\n- category: device\n  text: Our server keeps ordinary web logs, and holds your IP address briefly in memory for rate limiting so one\n    client cannot scrape the whole\
  \ board.\n- category: behavioral\n  text: A few product events named steps only, see below\n- category: financial\n  text: We store only Stripe's identifiers for your customer, subscription and price, which is what lets us know\n    you are on Pro.\npurposes:\n- purpose: rate limiting\n  text: holds your IP address briefly in memory for rate limiting so one client cannot scrape the whole board\n- purpose: aggregate traffic counting\n  text: We do set a few small first-party cookies so we can count, in aggregate, what brings people here and whether\n    they come back.\n- purpose: sending sign-in links\n  text: Email address to send your sign-in link\n- purpose: product analytics\n  text: so we can tell which parts of the product are worth keeping\n- purpose: payments\n  text: Stripe processes payments.\nretention:\n- scope: sign-in links\n  period: null\n  text: Sign-in links are deleted after they expire.\n- scope: sessions\n  period: null\n  text: Sessions are deleted when they expire\
  \ or when you sign out.\n- scope: product analytics counts\n  period: 180 days\n  text: Counts are kept for 180 days.\n- scope: account data\n  period: null\n  text: Everything else is kept until you ask us to delete your account, at which point all of it goes.\nresidency:\n- region: Germany\n  text: our own server, which is rented from Hetzner and located in Germany\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Three processors, each doing one job: Stripe for payments, Resend for sending your sign-in link and alert\n    emails, and our own server, which is rented from Hetzner and located in Germany.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to the contact address from the address on the account\n  text: Email [email protected] from the address on the account. We delete the account, everything saved on it,\n    and cancel any subscription.\nrights:\n- right: access\n  text: You can also ask for a copy of what we hold\n- right: correction\n\
  \  text: or ask us to correct it.\n- right: deletion\n  text: Everything else is kept until you ask us to delete your account, at which point all of it goes.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, we do not share it for advertising, and no advertising network receives\n    anything from this site.\n"
source_yaml_url: https://artifacts.apis.io/flashodds-live/privacy/flashodds-live-privacy-policy.yml
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
summary_line: 22 quoted statements, read from flashodds-live's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- Betting
- Odds
- Real-Time
- Analytics
---
