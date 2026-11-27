---
api_specs:
- filename: cardmind-app-openapi-generated.yml
  format: yaml
  label: CardMind API
  slug: cardmind-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardmind-app/openapi/_ae-authored/cardmind-app-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account email and a link to your sign-in provider (Google, Discord, Apple, or Microsoft).
  - category: behavioral
    text: 'Anonymized usage analytics: page paths, request timing, error rates.'
  - category: other
    text: 'Your collection: card identifiers, quantities, conditions, foiling, and any tags or notes you enter.'
  deletion:
    route: Settings → Account → Delete
    text: Delete your account in Settings → Account → Delete and your data is purged within 30 days.
  dpa:
    available: true
    text: We have data processing addenda on file with each.
    url: /legal/subprocessors
  purposes:
  - purpose: keep service running
    text: Used to keep the service running and figure out what to fix.
  retention:
  - period: null
    scope: account data
    text: Account data is retained while your account is active.
  - period: 30 days
    scope: account deletion
    text: Delete your account in Settings → Account → Delete and your data is purged within 30 days.
  - period: 90 days
    scope: backups
    text: Backups age out within 90 days.
  - period: 30 days
    scope: anonymized analytics rows
    text: individual rows are dropped after 30 days.
  rights:
  - right: access, export, correction, deletion
    text: Access, export, correction, and deletion are self-serve.
  - right: complaint to supervisory authority
    text: EU and UK residents may also lodge a complaint with their supervisory authority.
  - right: opt out of sale
    text: California residents may opt out of any sale of personal information, though we do not sell it in the first place.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell collection data.
  subprocessors:
    text: A current list with versions and DPA links lives at /legal/subprocessors.
    url: /legal/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CardMind
provenance_date: '2026-11-09'
provider_name: CardMind
provider_slug: cardmind-app
slug: cardmind-app-privacy-policy
source_date: '2026-11-09'
source_filename: cardmind-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cardmind.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CardMind\naid: cardmind-app\nurl: https://www.cardmind.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account email and a link to your sign-in provider (Google, Discord, Apple, or Microsoft).\n- category: behavioral\n  text: 'Anonymized usage analytics: page paths, request timing, error rates.'\n- category: other\n  text: 'Your collection: card identifiers, quantities, conditions, foiling, and any tags or notes you enter.'\npurposes:\n- purpose: keep service running\n  text: Used to keep the service running and figure out what\
  \ to fix.\nretention:\n- scope: account data\n  period: null\n  text: Account data is retained while your account is active.\n- scope: account deletion\n  period: 30 days\n  text: Delete your account in Settings → Account → Delete and your data is purged within 30 days.\n- scope: backups\n  period: 90 days\n  text: Backups age out within 90 days.\n- scope: anonymized analytics rows\n  period: 30 days\n  text: individual rows are dropped after 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: /legal/subprocessors\n  text: A current list with versions and DPA links lives at /legal/subprocessors.\ndpa:\n  available: true\n  url: /legal/subprocessors\n  text: We have data processing addenda on file with each.\ndeletion:\n  route: Settings → Account → Delete\n  text: Delete your account in Settings → Account → Delete and your data is purged within 30 days.\nrights:\n- right: access, export, correction, deletion\n  text: Access, export, correction, and deletion are self-serve.\n\
  - right: complaint to supervisory authority\n  text: EU and UK residents may also lodge a complaint with their supervisory authority.\n- right: opt out of sale\n  text: California residents may opt out of any sale of personal information, though we do not sell it in the first\n    place.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell collection data.\n"
source_yaml_url: https://artifacts.apis.io/cardmind-app/privacy/cardmind-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from CardMind's own page on 2026-11-09.
synthetic: false
tags:
- Market Intelligence
- Price Data
- Signals
- Ban Watch
- Deck Intelligence
---
