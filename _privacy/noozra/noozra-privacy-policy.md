---
api_specs:
- filename: noozra-building-permits-api-openapi.yml
  format: yaml
  label: Noozra Building permits API
  slug: noozra-building-permits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-building-permits-api-openapi.yml
- filename: noozra-communities-api-openapi.yml
  format: yaml
  label: Noozra Communities API
  slug: noozra-communities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-communities-api-openapi.yml
- filename: noozra-datasets-api-openapi.yml
  format: yaml
  label: Noozra Datasets API
  slug: noozra-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-datasets-api-openapi.yml
- filename: noozra-federal-register-api-openapi.yml
  format: yaml
  label: Noozra Federal Register API
  slug: noozra-federal-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-federal-register-api-openapi.yml
- filename: noozra-government-contracts-api-openapi.yml
  format: yaml
  label: Noozra Government contracts API
  slug: noozra-government-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-government-contracts-api-openapi.yml
- filename: noozra-jobs-api-openapi.yml
  format: yaml
  label: Noozra Jobs API
  slug: noozra-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-jobs-api-openapi.yml
- filename: noozra-new-businesses-api-openapi.yml
  format: yaml
  label: Noozra New businesses API
  slug: noozra-new-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-new-businesses-api-openapi.yml
- filename: noozra-news-api-openapi.yml
  format: yaml
  label: Noozra News API
  slug: noozra-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-news-api-openapi.yml
- filename: noozra-product-recalls-api-openapi.yml
  format: yaml
  label: Noozra Product recalls API
  slug: noozra-product-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noozra/openapi/noozra-product-recalls-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: If you create one we store your email address and sign-in timestamps.
  - category: contact
    text: If you create one we store your email address and sign-in timestamps.
  - category: financial
    text: we keep PayPal’s token for it with the card’s brand, last four digits, expiry and any billing address you gave
  - category: behavioral
    text: When you read a feed or a post, your browser tells us, for each post, how long its card was on your screen
  - category: device
    text: the sites, countries, device types (phone, tablet, desktop), browsers and operating systems they came from
  - category: location
    text: When you create an account we note your country, unless your browser sends Global Privacy Control.
  deletion:
    route: account settings or email removals@noozra.com
    text: which you can do any time from your account settings (it removes your profile and everything tied to it), or by emailing removals@noozra.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run accounts and count member use
    text: We use this only to run your account and to count how members use the site
  - purpose: stop multiple free API accounts
    text: Both are used only to stop one person making many free accounts.
  - purpose: rank posts
    text: We add that to the post's own totals, which help rank Hot
  - purpose: newsletter
    text: The newsletter is strictly opt-in.
  - purpose: analytics
    text: We use Google Analytics to understand traffic — page views, referrers, and approximate location.
  retention:
  - period: until you delete your account
    scope: account data
    text: We keep this data until you delete your account
  - period: 30 days
    scope: API key network code
    text: we keep a one-way code made from your internet connection’s address (never the address itself) for 30 days
  - period: 90 days
    scope: search totals
    text: search totals are deleted after 90 days
  - period: 90 days
    scope: sponsor card raw records
    text: Raw records are deleted after 90 days; only daily totals per advert are kept.
  rights:
  - right: access
    text: You can access, correct, export, or delete your personal data at any time
  - right: correction
    text: You can access, correct, export, or delete your personal data at any time
  - right: export
    text: The data download in account settings includes all of it.
  - right: deletion
    text: anyone can email removals@noozra.com to request access or deletion
  - right: newsletter unsubscribe
    text: unsubscribing takes effect immediately
  role:
    text: We do not sell personal information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we never sell your data
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Noozra
provenance_date: '2026-11-10'
provider_name: Noozra
provider_slug: noozra
slug: noozra-privacy-policy
source_date: '2026-11-10'
source_filename: noozra-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://noozra.com/about
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Noozra\naid: noozra\nurl: https://noozra.com/about\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We do not sell personal information.\ndata_categories:\n- category: identifying\n  text: If you create one we store your email address and sign-in timestamps.\n- category: contact\n  text: If you create one we store your email address and sign-in timestamps.\n- category: financial\n  text: we keep PayPal’s token for it with the card’s brand, last four digits, expiry and any billing address you\n    gave\n- category: behavioral\n  text: When you read a feed or a post, your browser tells us, for\
  \ each post, how long its card was on your screen\n- category: device\n  text: the sites, countries, device types (phone, tablet, desktop), browsers and operating systems they came from\n- category: location\n  text: When you create an account we note your country, unless your browser sends Global Privacy Control.\npurposes:\n- purpose: run accounts and count member use\n  text: We use this only to run your account and to count how members use the site\n- purpose: stop multiple free API accounts\n  text: Both are used only to stop one person making many free accounts.\n- purpose: rank posts\n  text: We add that to the post's own totals, which help rank Hot\n- purpose: newsletter\n  text: The newsletter is strictly opt-in.\n- purpose: analytics\n  text: We use Google Analytics to understand traffic — page views, referrers, and approximate location.\nretention:\n- scope: account data\n  period: until you delete your account\n  text: We keep this data until you delete your account\n- scope:\
  \ API key network code\n  period: 30 days\n  text: we keep a one-way code made from your internet connection’s address (never the address itself) for 30 days\n- scope: search totals\n  period: 90 days\n  text: search totals are deleted after 90 days\n- scope: sponsor card raw records\n  period: 90 days\n  text: Raw records are deleted after 90 days; only daily totals per advert are kept.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings or email removals@noozra.com\n  text: which you can do any time from your account settings (it removes your profile and everything tied to it),\n    or by emailing removals@noozra.com\nrights:\n- right: access\n  text: You can access, correct, export, or delete your personal data at any time\n- right: correction\n  text: You can access, correct, export, or delete your personal data at any time\n- right: export\n  text: The data download in account\
  \ settings includes all of it.\n- right: deletion\n  text: anyone can email removals@noozra.com to request access or deletion\n- right: newsletter unsubscribe\n  text: unsubscribing takes effect immediately\nsale_or_sharing:\n  stance: prohibited\n  text: we never sell your data\n"
source_yaml_url: https://artifacts.apis.io/noozra/privacy/noozra-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Noozra's own page on 2026-11-10.
synthetic: false
tags:
- News
- Free
- Community
- Artificial Intelligence
---
