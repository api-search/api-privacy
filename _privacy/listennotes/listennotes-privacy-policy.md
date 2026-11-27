---
api_specs:
- filename: listennotes-insights-api-api-openapi.yml
  format: yaml
  label: Listen Notes Insights API
  slug: insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-insights-api-api-openapi.yml
- filename: listennotes-playlist-api-api-openapi.yml
  format: yaml
  label: Listen Notes Playlist API
  slug: playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-playlist-api-api-openapi.yml
- filename: listennotes-podcaster-api-api-openapi.yml
  format: yaml
  label: Listen Notes Podcaster API
  slug: listennotes-podcaster-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-podcaster-api-api-openapi.yml
- filename: listennotes-search-api-api-openapi.yml
  format: yaml
  label: Listen Notes Search API
  slug: listennotes-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-search-api-api-openapi.yml
- filename: listennotes-directory-api-api-openapi.yml
  format: yaml
  label: Listen Notes Directory API
  slug: listennotes-directory-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listennotes/openapi/listennotes-directory-api-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: like your name, email address, telephone number or credit card to store with your account
  - category: device
    text: We collect device-specific information (such as your hardware model, operating system version, unique device identifiers, and mobile network information including phone number).
  - category: location
    text: When you use Listen Notes services, we may collect and process information about your actual location.
  - category: behavioral
    text: details of how you used our service, such as your search queries.
  - category: communication
    text: We log API request information, including the requested operation and parameters such as search queries, account and app identifiers, request times, usage, and success or failure.
  deletion:
    route: Delete account via Settings page ACCOUNT tab or contact hello@listennotes.com
    text: When you delete your account, we permanently delete information you have provided and things you have created, such as your email address and your podcast playlists, and you won't be able to recover the data later.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, maintain, protect and improve services
    text: We use the information we collect from all of our services to provide, maintain, protect and improve them, to develop new ones, and to protect Listen Notes and our users.
  - purpose: tailored content and ads
    text: We also use this information to offer you tailored content – like giving you more relevant search results and ads.
  - purpose: analytics
    text: We may use third party analytics services, such as Google Analytics, to grow our business, to improve and develop our Services
  retention:
  - period: null
    scope: Podcast API request logs
    text: Podcast API request logs are retained unless the Listen Notes account that owns the API account is deleted.
  - period: up to ten minutes
    scope: MCP results and card data cache
    text: MCP results and card data are cached for up to ten minutes after the request
  rights:
  - right: access, rectify, port and erase
    text: We provide you with the ability to access, rectify, port and erase your data.
  - right: revoke MCP access
    text: You can revoke access from the MCP connections page.
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
name: Listen Notes
provenance_date: '2026-11-09'
provider_name: Listen Notes
provider_slug: listennotes
slug: listennotes-privacy-policy
source_date: '2026-11-09'
source_filename: listennotes-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.listennotes.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Listen Notes\naid: listennotes\nurl: https://www.listennotes.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: like your name, email address, telephone number or credit card to store with your account\n- category: device\n  text: We collect device-specific information (such as your hardware model, operating system version, unique device\n    identifiers, and mobile network information including phone number).\n- category: location\n  text: When you use Listen Notes services, we may collect and process information about your actual\
  \ location.\n- category: behavioral\n  text: details of how you used our service, such as your search queries.\n- category: communication\n  text: We log API request information, including the requested operation and parameters such as search queries,\n    account and app identifiers, request times, usage, and success or failure.\npurposes:\n- purpose: provide, maintain, protect and improve services\n  text: We use the information we collect from all of our services to provide, maintain, protect and improve them,\n    to develop new ones, and to protect Listen Notes and our users.\n- purpose: tailored content and ads\n  text: We also use this information to offer you tailored content – like giving you more relevant search results\n    and ads.\n- purpose: analytics\n  text: We may use third party analytics services, such as Google Analytics, to grow our business, to improve and\n    develop our Services\nretention:\n- scope: Podcast API request logs\n  period: null\n  text: Podcast API\
  \ request logs are retained unless the Listen Notes account that owns the API account is deleted.\n- scope: MCP results and card data cache\n  period: up to ten minutes\n  text: MCP results and card data are cached for up to ten minutes after the request\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account via Settings page ACCOUNT tab or contact hello@listennotes.com\n  text: When you delete your account, we permanently delete information you have provided and things you have created,\n    such as your email address and your podcast playlists, and you won't be able to recover the data later.\nrights:\n- right: access, rectify, port and erase\n  text: We provide you with the ability to access, rectify, port and erase your data.\n- right: revoke MCP access\n  text: You can revoke access from the MCP connections page.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/listennotes/privacy/listennotes-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from Listen Notes's own page on 2026-11-09.
synthetic: false
tags:
- Podcasts
- Podcast Search
- Podcast Directory
- Search
- Audio
- Media
- Podcast Insights
---
