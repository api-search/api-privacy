---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'A fingerprint, not the address itself: an HMAC-SHA-256 hash made with a secret key that is kept only on our server.'
  - category: contact
    text: 'Account: email address, name, interface language, and a password stored as a bcrypt hash'
  - category: device
    text: Browser (user agent) A fingerprint made with the same key, for the same purpose.
  - category: location
    text: Country A two-letter code, only if our hosting supplies it with the request. At present it does not, and this field is empty.
  - category: behavioral
    text: After a click Whether the reader arrived at the destination site, how long they stayed and, if that site also runs our block, how many pages they viewed and whether they scrolled.
  deletion:
    route: email
    text: write to ax5165@gmail.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: count impressions and prevent fraud
    text: We use this data to count real impressions, to refuse fake ones and to compute each site’s quality score
  residency:
  - region: Uzbekistan
    text: Our servers are located in Uzbekistan.
  retention:
  - period: 52 days
    scope: server logs
    text: 'Server logs: 52 days.'
  - period: 3 days
    scope: database backups
    text: 'Database backups: 3 days.'
  - period: no automatic time limit
    scope: impression and click records
    text: Impression and click records, with the hashes above, are kept with no automatic time limit at present
  - period: while the account exists
    scope: account data
    text: Account data is kept while the account exists.
  rights:
  - right: access, correction, deletion, objection
    text: You can ask us what we hold about you, ask us to correct it, to delete it, or object to its use
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not store the page address, build reader profiles, set cookies, use local storage, sell data or hand it to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BarterBanner
provenance_date: '2026-11-09'
provider_name: BarterBanner
provider_slug: barterbanner-com
slug: barterbanner-com-privacy-policy
source_date: '2026-11-09'
source_filename: barterbanner-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://barterbanner.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BarterBanner\naid: barterbanner-com\nurl: https://barterbanner.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'A fingerprint, not the address itself: an HMAC-SHA-256 hash made with a secret key that is kept only on\n    our server.'\n- category: contact\n  text: 'Account: email address, name, interface language, and a password stored as a bcrypt hash'\n- category: device\n  text: Browser (user agent) A fingerprint made with the same key, for the same purpose.\n- category: location\n  text: Country A two-letter code, only if\
  \ our hosting supplies it with the request. At present it does not, and\n    this field is empty.\n- category: behavioral\n  text: After a click Whether the reader arrived at the destination site, how long they stayed and, if that site\n    also runs our block, how many pages they viewed and whether they scrolled.\npurposes:\n- purpose: count impressions and prevent fraud\n  text: We use this data to count real impressions, to refuse fake ones and to compute each site’s quality score\nretention:\n- scope: server logs\n  period: 52 days\n  text: 'Server logs: 52 days.'\n- scope: database backups\n  period: 3 days\n  text: 'Database backups: 3 days.'\n- scope: impression and click records\n  period: no automatic time limit\n  text: Impression and click records, with the hashes above, are kept with no automatic time limit at present\n- scope: account data\n  period: while the account exists\n  text: Account data is kept while the account exists.\nresidency:\n- region: Uzbekistan\n  text:\
  \ Our servers are located in Uzbekistan.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: write to ax5165@gmail.com\nrights:\n- right: access, correction, deletion, objection\n  text: You can ask us what we hold about you, ask us to correct it, to delete it, or object to its use\nsale_or_sharing:\n  stance: prohibited\n  text: We do not store the page address, build reader profiles, set cookies, use local storage, sell data or hand\n    it to anyone.\n"
source_yaml_url: https://artifacts.apis.io/barterbanner-com/privacy/barterbanner-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from BarterBanner's own page on 2026-11-09.
synthetic: false
tags:
- Networks
- Publishing
- ContentExchange
- Multi-language
---
