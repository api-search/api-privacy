---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: We do not store your IP address. It is replaced, before anything is written, by a short salted SHA-256 hash
  - category: contact
    text: we store your email address, a normalised form of it used to allow one key per mailbox
  - category: financial
    text: We record the paying wallet address, amount, transaction hash and time in a payment ledger
  - category: location
    text: an approximate location (country, region and city, looked up from your IP address, which is not stored)
  - category: device
    text: the browser, operating system and device type
  - category: behavioral
    text: Clicks on the free-key button and free-key sign-ups are counted the same way.
  - category: communication
    text: We store your message, the email address if you choose to give one, the hashed caller identifier and the user agent
  deletion:
    route: email request to privacy address
    text: You may ask for access to, correction of, or deletion of personal data we hold about you, or object to its processing. Email [email protected] and we will respond within two business days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse prevention and rate limits
    text: enough to count distinct callers and to apply rate limits and abuse blocks, not enough to recover the address
  - purpose: accounting
    text: We keep this for accounting.
  - purpose: issuing API keys
    text: so we can issue your API key
  - purpose: change alerts
    text: If you register a webhook we store its URL, the series or documents it watches, the signing secret and delivery state, until you remove it or it is deactivated.
  retention:
  - period: about nine weeks
    scope: request logs
    text: at present it reaches back about nine weeks
  - period: about five weeks
    scope: system log copy
    text: A copy in the system log is kept for about five weeks.
  - period: 90 days
    scope: full visitor statistics records
    text: Full records are kept for 90 days.
  - period: null
    scope: visitor code salt
    text: a salt that changes every day and is deleted at midnight (SAST)
  - period: as long as tax and accounting law requires
    scope: purchase records
    text: These purchase records are kept for as long as tax and accounting law requires.
  rights:
  - right: access
    text: You may ask for access to, correction of, or deletion of personal data we hold about you
  - right: correction
    text: You may ask for access to, correction of, or deletion of personal data we hold about you
  - right: deletion
    text: You may ask for access to, correction of, or deletion of personal data we hold about you
  - right: objection
    text: or object to its processing
  - right: complaint to regulator
    text: you may also complain to the Information Regulator of South Africa
  role:
    text: This notice explains what 3L Group Consulting (PTY) LTD collects when you use afriref or any of its six sister services, why, and for how long.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent data and do not build profiles of callers.
  subprocessors:
    text: Cloudflare sits in front of all seven services for delivery and protection, and therefore sees each connection, including your IP address, under its own terms.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: afriref
provenance_date: '2026-11-09'
provider_name: afriref
provider_slug: afriref-dev
slug: afriref-dev-privacy-policy
source_date: '2026-11-09'
source_filename: afriref-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://afriref.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: afriref\naid: afriref-dev\nurl: https://afriref.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This notice explains what 3L Group Consulting (PTY) LTD collects when you use afriref or any of its six\n    sister services, why, and for how long.\ndata_categories:\n- category: identifying\n  text: We do not store your IP address. It is replaced, before anything is written, by a short salted SHA-256 hash\n- category: contact\n  text: we store your email address, a normalised form of it used to allow one key per mailbox\n- category: financial\n  text: We record the paying wallet address,\
  \ amount, transaction hash and time in a payment ledger\n- category: location\n  text: an approximate location (country, region and city, looked up from your IP address, which is not stored)\n- category: device\n  text: the browser, operating system and device type\n- category: behavioral\n  text: Clicks on the free-key button and free-key sign-ups are counted the same way.\n- category: communication\n  text: We store your message, the email address if you choose to give one, the hashed caller identifier and the\n    user agent\npurposes:\n- purpose: abuse prevention and rate limits\n  text: enough to count distinct callers and to apply rate limits and abuse blocks, not enough to recover the address\n- purpose: accounting\n  text: We keep this for accounting.\n- purpose: issuing API keys\n  text: so we can issue your API key\n- purpose: change alerts\n  text: If you register a webhook we store its URL, the series or documents it watches, the signing secret and delivery\n    state, until\
  \ you remove it or it is deactivated.\nretention:\n- scope: request logs\n  period: about nine weeks\n  text: at present it reaches back about nine weeks\n- scope: system log copy\n  period: about five weeks\n  text: A copy in the system log is kept for about five weeks.\n- scope: full visitor statistics records\n  period: 90 days\n  text: Full records are kept for 90 days.\n- scope: visitor code salt\n  period: null\n  text: a salt that changes every day and is deleted at midnight (SAST)\n- scope: purchase records\n  period: as long as tax and accounting law requires\n  text: These purchase records are kept for as long as tax and accounting law requires.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare sits in front of all seven services for delivery and protection, and therefore sees each connection,\n    including your IP address, under its own terms.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to privacy address\n\
  \  text: You may ask for access to, correction of, or deletion of personal data we hold about you, or object to its\n    processing. Email [email protected] and we will respond within two business days.\nrights:\n- right: access\n  text: You may ask for access to, correction of, or deletion of personal data we hold about you\n- right: correction\n  text: You may ask for access to, correction of, or deletion of personal data we hold about you\n- right: deletion\n  text: You may ask for access to, correction of, or deletion of personal data we hold about you\n- right: objection\n  text: or object to its processing\n- right: complaint to regulator\n  text: you may also complain to the Information Regulator of South Africa\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent data and do not build profiles of callers.\n"
source_yaml_url: https://artifacts.apis.io/afriref-dev/privacy/afriref-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from afriref's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Government
- Africa
- Reference
---
