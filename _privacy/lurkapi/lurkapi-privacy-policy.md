---
api_specs:
- filename: lurkapi-account-api-openapi.yml
  format: yaml
  label: LurkAPI Account API
  slug: lurkapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-account-api-openapi.yml
- filename: lurkapi-bluesky-api-openapi.yml
  format: yaml
  label: LurkAPI Bluesky API
  slug: lurkapi-bluesky-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-bluesky-api-openapi.yml
- filename: lurkapi-ebay-api-openapi.yml
  format: yaml
  label: LurkAPI eBay API
  slug: lurkapi-ebay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-ebay-api-openapi.yml
- filename: lurkapi-facebook-api-openapi.yml
  format: yaml
  label: LurkAPI Facebook API
  slug: lurkapi-facebook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-facebook-api-openapi.yml
- filename: lurkapi-google-api-openapi.yml
  format: yaml
  label: LurkAPI Google API
  slug: lurkapi-google-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-google-api-openapi.yml
- filename: lurkapi-instagram-api-openapi.yml
  format: yaml
  label: LurkAPI Instagram API
  slug: lurkapi-instagram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-instagram-api-openapi.yml
- filename: lurkapi-link-in-bio-api-openapi.yml
  format: yaml
  label: LurkAPI Link In Bio API
  slug: lurkapi-link-in-bio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-link-in-bio-api-openapi.yml
- filename: lurkapi-reddit-api-openapi.yml
  format: yaml
  label: LurkAPI Reddit API
  slug: lurkapi-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-reddit-api-openapi.yml
- filename: lurkapi-snapchat-api-openapi.yml
  format: yaml
  label: LurkAPI Snapchat API
  slug: lurkapi-snapchat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-snapchat-api-openapi.yml
- filename: lurkapi-telegram-api-openapi.yml
  format: yaml
  label: LurkAPI Telegram API
  slug: lurkapi-telegram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-telegram-api-openapi.yml
- filename: lurkapi-threads-api-openapi.yml
  format: yaml
  label: LurkAPI Threads API
  slug: lurkapi-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-threads-api-openapi.yml
- filename: lurkapi-tiktok-api-openapi.yml
  format: yaml
  label: LurkAPI Tik Tok API
  slug: lurkapi-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-tiktok-api-openapi.yml
- filename: lurkapi-web-api-openapi.yml
  format: yaml
  label: LurkAPI Web API
  slug: lurkapi-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-web-api-openapi.yml
- filename: lurkapi-x-twitter-api-openapi.yml
  format: yaml
  label: LurkAPI X (Twitter) API
  slug: lurkapi-x-twitter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-x-twitter-api-openapi.yml
- filename: lurkapi-youtube-api-openapi.yml
  format: yaml
  label: LurkAPI YouTube API
  slug: lurkapi-youtube-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-youtube-api-openapi.yml
- filename: lurkapi-linked-in-api-openapi.yml
  format: yaml
  label: LurkAPI Linked In API
  slug: lurkapi-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-linked-in-api-openapi.yml
- filename: lurkapi-truthsocial-api-openapi.yml
  format: yaml
  label: LurkAPI Truthsocial API
  slug: lurkapi-truthsocial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lurkapi/openapi/lurkapi-truthsocial-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, and your name if you sign in with Google.
  - category: identifying
    text: API keys. A one-way hash of each key and its first few characters
  - category: behavioral
    text: 'Usage counts. For each account, per day and per endpoint: how many requests, how many credits and how many errors.'
  - category: communication
    text: 'Request log. For each call: when, which endpoint, its parameters (never your key)'
  - category: location
    text: The request log records each try with its IP address, but not what it returned.
  - category: financial
    text: We receive a record of each purchase (amount, credits, date), never your card number.
  - category: device
    text: 'Google Analytics and Microsoft Clarity show us how the site is used: pages viewed, clicks and scrolls, device and rough location.'
  deletion:
    route: Email support@lurkapi.com to get a copy of your data, correct it or delete your account.
    text: Email support@lurkapi.com to get a copy of your data, correct it or delete your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: sign in and account email
    text: We use them to sign you in and to email you about your account.
  - purpose: billing, limits and dashboard
    text: They power billing, limits and your dashboard.
  - purpose: support and abuse prevention
    text: We keep it for 14 days to answer support questions and stop abuse, then delete it.
  - purpose: measuring site use
    text: Google Analytics and Microsoft Clarity show us how the site is used
  - purpose: ad conversion measurement
    text: Google Ads learns when a visit from one of our ads leads to a sign-up or a purchase (with its amount), so we can tell which ads work.
  retention:
  - period: 14 days
    scope: request log
    text: We keep it for 14 days to answer support questions and stop abuse, then delete it.
  - period: until you delete your account
    scope: account data, keys and usage counts
    text: Account data, keys and usage counts stay until you delete your account.
  - period: null
    scope: purchase records
    text: Purchase records are kept as long as tax and accounting rules require.
  - period: 90 days
    scope: email send records
    text: our record of the emails we sent you (address, type, whether it went out) after 90 days
  rights:
  - right: access
    text: Email support@lurkapi.com to get a copy of your data
  - right: correction
    text: correct it
  - right: deletion
    text: delete your account
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell or rent your data, and beyond measuring our own ads we don’t use it for advertising.
  subprocessors:
    text: Cloudflare hosts the site, the API, the database and the saved responses, sends our emails and processes request logs (such as IP addresses) to run and protect the service. Stripe processes payments.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LurkAPI
provenance_date: '2026-11-10'
provider_name: LurkAPI
provider_slug: lurkapi
slug: lurkapi-privacy-policy
source_date: '2026-11-10'
source_filename: lurkapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://lurkapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LurkAPI\naid: lurkapi\nurl: https://lurkapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your email address, and your name if you sign in with Google.\n- category: identifying\n  text: API keys. A one-way hash of each key and its first few characters\n- category: behavioral\n  text: 'Usage counts. For each account, per day and per endpoint: how many requests, how many credits and how many\n    errors.'\n- category: communication\n  text: 'Request log. For each call: when, which endpoint, its parameters (never your key)'\n- category:\
  \ location\n  text: The request log records each try with its IP address, but not what it returned.\n- category: financial\n  text: We receive a record of each purchase (amount, credits, date), never your card number.\n- category: device\n  text: 'Google Analytics and Microsoft Clarity show us how the site is used: pages viewed, clicks and scrolls,\n    device and rough location.'\npurposes:\n- purpose: sign in and account email\n  text: We use them to sign you in and to email you about your account.\n- purpose: billing, limits and dashboard\n  text: They power billing, limits and your dashboard.\n- purpose: support and abuse prevention\n  text: We keep it for 14 days to answer support questions and stop abuse, then delete it.\n- purpose: measuring site use\n  text: Google Analytics and Microsoft Clarity show us how the site is used\n- purpose: ad conversion measurement\n  text: Google Ads learns when a visit from one of our ads leads to a sign-up or a purchase (with its amount), so\n\
  \    we can tell which ads work.\nretention:\n- scope: request log\n  period: 14 days\n  text: We keep it for 14 days to answer support questions and stop abuse, then delete it.\n- scope: account data, keys and usage counts\n  period: until you delete your account\n  text: Account data, keys and usage counts stay until you delete your account.\n- scope: purchase records\n  period: null\n  text: Purchase records are kept as long as tax and accounting rules require.\n- scope: email send records\n  period: 90 days\n  text: our record of the emails we sent you (address, type, whether it went out) after 90 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare hosts the site, the API, the database and the saved responses, sends our emails and processes\n    request logs (such as IP addresses) to run and protect the service. Stripe processes payments.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@lurkapi.com to get a copy\
  \ of your data, correct it or delete your account.\n  text: Email support@lurkapi.com to get a copy of your data, correct it or delete your account.\nrights:\n- right: access\n  text: Email support@lurkapi.com to get a copy of your data\n- right: correction\n  text: correct it\n- right: deletion\n  text: delete your account\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell or rent your data, and beyond measuring our own ads we don’t use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/lurkapi/privacy/lurkapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from LurkAPI's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Data API
- AI Integration
- Advertising
- Analytics
---
