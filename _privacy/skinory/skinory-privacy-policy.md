---
api_specs:
- filename: skinory-inventories-api-openapi.yml
  format: yaml
  label: Skinory (submitted as g2push) Inventories API
  slug: skinory-inventories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skinory/openapi/skinory-inventories-api-openapi.yml
- filename: skinory-inventory-api-openapi.yml
  format: yaml
  label: Skinory (submitted as g2push) Inventory API
  slug: skinory-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skinory/openapi/skinory-inventory-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'We store: SteamID64, nickname, avatar, registration and last login dates'
  - category: contact
    text: We do not request or store email, phone or payment data.
  - category: behavioral
    text: plus your favourites, price-tracking settings and, if you add one, your CS2 chicken census report (the breed and colour of your chicken)
  - category: location
    text: We save your chosen site language and the latest approximate IP country supplied by Cloudflare at sign-in or during account activity, with update dates.
  - category: device
    text: A local database lookup can also save the ASN, network operator, ISP or network type when known
  deletion:
    route: email info@skinory.io; removed within 7 days
    text: To delete your account and all related data, email info@skinory.io — we will remove it within 7 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account features
    text: Account data supports your profile, favourites, price tracking and notifications.
  - purpose: usage and diagnostics
    text: Usage and diagnostic data help us understand which pages are used and investigate errors.
  - purpose: notification audiences
    text: Language and country help select notification audiences.
  retention:
  - period: 400 days
    scope: Steam value snapshots
    text: Value snapshots live 400 days
  - period: 30 days
    scope: per-item history
    text: per-item history is deleted 30 days after tracking is switched off
  - period: 180 days
    scope: leaderboard rows without tracking or public page
    text: leaderboard rows without tracking or a public page are cleaned after 180 days
  rights:
  - right: download data export
    text: In your profile you can download a JSON copy of your account data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Skinory (submitted as g2push)
provenance_date: '2026-11-10'
provider_name: Skinory (submitted as g2push)
provider_slug: skinory
slug: skinory-privacy-policy
source_date: '2026-11-10'
source_filename: skinory-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://skinory.io/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Skinory (submitted as g2push)\naid: skinory\nurl: https://skinory.io/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'We store: SteamID64, nickname, avatar, registration and last login dates'\n- category: contact\n  text: We do not request or store email, phone or payment data.\n- category: behavioral\n  text: plus your favourites, price-tracking settings and, if you add one, your CS2 chicken census report (the breed\n    and colour of your chicken)\n- category: location\n  text: We save your chosen site language and the latest\
  \ approximate IP country supplied by Cloudflare at sign-in\n    or during account activity, with update dates.\n- category: device\n  text: A local database lookup can also save the ASN, network operator, ISP or network type when known\npurposes:\n- purpose: account features\n  text: Account data supports your profile, favourites, price tracking and notifications.\n- purpose: usage and diagnostics\n  text: Usage and diagnostic data help us understand which pages are used and investigate errors.\n- purpose: notification audiences\n  text: Language and country help select notification audiences.\nretention:\n- scope: Steam value snapshots\n  period: 400 days\n  text: Value snapshots live 400 days\n- scope: per-item history\n  period: 30 days\n  text: per-item history is deleted 30 days after tracking is switched off\n- scope: leaderboard rows without tracking or public page\n  period: 180 days\n  text: leaderboard rows without tracking or a public page are cleaned after 180 days\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email info@skinory.io; removed within 7 days\n  text: To delete your account and all related data, email info@skinory.io — we will remove it within 7 days.\nrights:\n- right: download data export\n  text: In your profile you can download a JSON copy of your account data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skinory/privacy/skinory-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from Skinory (submitted as g2push)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Skins
- CS2
- CS:GO
---
