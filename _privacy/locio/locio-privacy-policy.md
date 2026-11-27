---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: An account keeps your email address, the handle you choose, and a hash of your password made with Argon2, never the password itself.
  - category: device
    text: which includes the query, the caller's IP address and the time
  - category: behavioral
    text: For each API key we keep the number of lookups and units used per day, and when the key was last used.
  - category: financial
    text: Stripe takes the card and keeps the invoices; we never see the card.
  - category: communication
    text: The contact form sends us your name, email address and message as an email, together with the IP address it came from
  - category: location
    text: tells us which country a request came from, which decides the country a public key searches. We do not store that country.
  deletion:
    route: self-service at /account/delete
    text: Delete it yourself from /account/delete .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing and plan usage
    text: we count how many lookups each key makes each day, because that is what the plan and the invoice are made of.
  - purpose: abuse prevention
    text: so we can deal with abuse
  - purpose: performance
    text: a lookup that takes too long is logged with its query so we can make it faster.
  residency:
  - region: Australia (Sydney)
    text: DigitalOcean runs our servers and database, in Sydney.
  - region: outside Australia
    text: Some of these process data outside Australia, including in the United States.
  retention:
  - period: 30 days
    scope: server logs
    text: Server logs are kept for at most 30 days and then deleted.
  - period: until you delete the account
    scope: account, keys, usage counts and agent connections
    text: 'Your account, keys, daily usage counts and agent connections: until you delete the account.'
  - period: as long as the law requires
    scope: invoices
    text: 'Invoices: kept by Stripe for as long as the law requires, because they are tax records.'
  - period: as long as it takes to deal with them
    scope: contact form messages
    text: 'Contact form messages: as long as it takes to deal with them.'
  - period: 90 days
    scope: sign-in cookie
    text: locio_session keeps you signed in, for up to 90 days.
  rights:
  - right: access, correction, deletion, stop using
    text: You can ask us for a copy of what we hold about you, to correct it, to delete it, or to stop using it.
  - right: complain to regulator
    text: you can complain to the Office of the Australian Information Commissioner at oaic.gov.au
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we never sell or share what we keep for anyone else's use
  subprocessors:
    text: Cloudflare sits in front of the site and the API, so every request passes through it and it sees your IP address.
    url: null
  transfers:
  - mechanism: other
    text: Some of these process data outside Australia, including in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Locio
provenance_date: '2026-11-09'
provider_name: Locio
provider_slug: locio
slug: locio-privacy-policy
source_date: '2026-11-09'
source_filename: locio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://locio.com.au/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Locio\naid: locio\nurl: https://locio.com.au/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: An account keeps your email address, the handle you choose, and a hash of your password made with Argon2,\n    never the password itself.\n- category: device\n  text: which includes the query, the caller's IP address and the time\n- category: behavioral\n  text: For each API key we keep the number of lookups and units used per day, and when the key was last used.\n- category: financial\n  text: Stripe takes the card and keeps the invoices;\
  \ we never see the card.\n- category: communication\n  text: The contact form sends us your name, email address and message as an email, together with the IP address\n    it came from\n- category: location\n  text: tells us which country a request came from, which decides the country a public key searches. We do not store\n    that country.\npurposes:\n- purpose: billing and plan usage\n  text: we count how many lookups each key makes each day, because that is what the plan and the invoice are made\n    of.\n- purpose: abuse prevention\n  text: so we can deal with abuse\n- purpose: performance\n  text: a lookup that takes too long is logged with its query so we can make it faster.\nretention:\n- scope: server logs\n  period: 30 days\n  text: Server logs are kept for at most 30 days and then deleted.\n- scope: account, keys, usage counts and agent connections\n  period: until you delete the account\n  text: 'Your account, keys, daily usage counts and agent connections: until you delete\
  \ the account.'\n- scope: invoices\n  period: as long as the law requires\n  text: 'Invoices: kept by Stripe for as long as the law requires, because they are tax records.'\n- scope: contact form messages\n  period: as long as it takes to deal with them\n  text: 'Contact form messages: as long as it takes to deal with them.'\n- scope: sign-in cookie\n  period: 90 days\n  text: locio_session keeps you signed in, for up to 90 days.\nresidency:\n- region: Australia (Sydney)\n  text: DigitalOcean runs our servers and database, in Sydney.\n- region: outside Australia\n  text: Some of these process data outside Australia, including in the United States.\ntransfers:\n- mechanism: other\n  text: Some of these process data outside Australia, including in the United States.\nsubprocessors:\n  url: null\n  text: Cloudflare sits in front of the site and the API, so every request passes through it and it sees your IP\n    address.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ self-service at /account/delete\n  text: Delete it yourself from /account/delete .\nrights:\n- right: access, correction, deletion, stop using\n  text: You can ask us for a copy of what we hold about you, to correct it, to delete it, or to stop using it.\n- right: complain to regulator\n  text: you can complain to the Office of the Australian Information Commissioner at oaic.gov.au\nsale_or_sharing:\n  stance: prohibited\n  text: we never sell or share what we keep for anyone else's use\n"
source_yaml_url: https://artifacts.apis.io/locio/privacy/locio-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Locio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Address
- Geocoding
- MCP
---
