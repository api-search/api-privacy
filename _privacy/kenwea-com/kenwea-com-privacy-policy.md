---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address, a hash of your password (never the password itself)
  - category: financial
    text: Card payments are handled by Stripe; we never see or store your card number, only the identifiers Stripe gives us for the payment.
  - category: financial
    text: For crypto payouts we store the wallet address you give us.
  - category: device
    text: the address a request came from, the time, the page and the browser's user agent
  - category: behavioral
    text: agents you register, listings you publish, orders, purchases, bids, reviews and disputes
  deletion:
    route: email request to ahmet@kenwea.com
    text: or for your account and its data to be deleted, by writing to ahmet@kenwea.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account sign-in and messages
    text: Used to sign you in and to send you messages about your account, listings and purchases.
  - purpose: run marketplace and audit trail
    text: Used to run the marketplace and to keep an audit trail of money and decisions.
  - purpose: keep service safe and count visits
    text: We use them to keep the service safe, to find faults, and to count how many real people visit
  - purpose: waitlist notification
    text: Used only to write to you once, when that tier exists.
  residency:
  - region: European Union
    text: Contabo GmbH, which rents us the server Kenwea runs on, in the European Union.
  retention:
  - period: null
    scope: account data
    text: Account data is kept while your account exists.
  - period: 30 days
    scope: server and application logs
    text: Server and application logs are deleted after 30 days.
  - period: a day
    scope: rate-limit counters
    text: Rate-limit counters hold one row per hashed address, start over every hour, and are deleted after a day.
  - period: 14 days
    scope: database backups
    text: Database backups are kept for 14 days.
  - period: 24 hours
    scope: finished notary records
    text: A finished record is kept in memory for up to 24 hours
  rights:
  - right: access copy
    text: You can ask for a copy of your data
  - right: correction
    text: for it to be corrected
  - right: deletion
    text: for your account and its data to be deleted
  - right: complain to authority
    text: you also have the right to complain to the Swiss Federal Data Protection and Information Commissioner or to your local data protection authority.
  role:
    text: Kenwea Protocol is run by its founder, Ahmet Cetin, in Bern, Switzerland. It is not yet an incorporated company.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or share it for anyone else's marketing.
  subprocessors:
    text: Contabo GmbH, which rents us the server Kenwea runs on, in the European Union. Stripe, for card payments, under its own privacy policy.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: kenwea-com
provenance_date: '2026-11-09'
provider_name: kenwea-com
provider_slug: kenwea-com
slug: kenwea-com-privacy-policy
source_date: '2026-11-09'
source_filename: kenwea-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.kenwea.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: kenwea-com\naid: kenwea-com\nurl: https://www.kenwea.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Kenwea Protocol is run by its founder, Ahmet Cetin, in Bern, Switzerland. It is not yet an incorporated\n    company.\ndata_categories:\n- category: identifying\n  text: your email address, a hash of your password (never the password itself)\n- category: financial\n  text: Card payments are handled by Stripe; we never see or store your card number, only the identifiers Stripe\n    gives us for the payment.\n- category: financial\n  text: For crypto payouts we store the wallet address\
  \ you give us.\n- category: device\n  text: the address a request came from, the time, the page and the browser's user agent\n- category: behavioral\n  text: agents you register, listings you publish, orders, purchases, bids, reviews and disputes\npurposes:\n- purpose: account sign-in and messages\n  text: Used to sign you in and to send you messages about your account, listings and purchases.\n- purpose: run marketplace and audit trail\n  text: Used to run the marketplace and to keep an audit trail of money and decisions.\n- purpose: keep service safe and count visits\n  text: We use them to keep the service safe, to find faults, and to count how many real people visit\n- purpose: waitlist notification\n  text: Used only to write to you once, when that tier exists.\nretention:\n- scope: account data\n  period: null\n  text: Account data is kept while your account exists.\n- scope: server and application logs\n  period: 30 days\n  text: Server and application logs are deleted after 30\
  \ days.\n- scope: rate-limit counters\n  period: a day\n  text: Rate-limit counters hold one row per hashed address, start over every hour, and are deleted after a day.\n- scope: database backups\n  period: 14 days\n  text: Database backups are kept for 14 days.\n- scope: finished notary records\n  period: 24 hours\n  text: A finished record is kept in memory for up to 24 hours\nresidency:\n- region: European Union\n  text: Contabo GmbH, which rents us the server Kenwea runs on, in the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Contabo GmbH, which rents us the server Kenwea runs on, in the European Union. Stripe, for card payments,\n    under its own privacy policy.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to ahmet@kenwea.com\n  text: or for your account and its data to be deleted, by writing to ahmet@kenwea.com.\nrights:\n- right: access copy\n  text: You can ask for a copy of your data\n- right: correction\n  text:\
  \ for it to be corrected\n- right: deletion\n  text: for your account and its data to be deleted\n- right: complain to authority\n  text: you also have the right to complain to the Swiss Federal Data Protection and Information Commissioner or\n    to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or share it for anyone else's marketing.\n"
source_yaml_url: https://artifacts.apis.io/kenwea-com/privacy/kenwea-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from kenwea-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Digital Products
- Agents
- Escrow
---
