---
api_specs:
- filename: audiomack-artist-api-openapi.yml
  format: yaml
  label: Audiomack Artist API
  slug: audiomack-artist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-artist-api-openapi.yml
- filename: audiomack-chart-api-openapi.yml
  format: yaml
  label: Audiomack Chart API
  slug: audiomack-chart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-chart-api-openapi.yml
- filename: audiomack-music-api-openapi.yml
  format: yaml
  label: Audiomack Music API
  slug: audiomack-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-music-api-openapi.yml
- filename: audiomack-playlist-api-openapi.yml
  format: yaml
  label: Audiomack Playlist API
  slug: audiomack-playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-playlist-api-openapi.yml
- filename: audiomack-search-api-openapi.yml
  format: yaml
  label: Audiomack Search API
  slug: audiomack-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-search-api-openapi.yml
- filename: audiomack-stats-api-openapi.yml
  format: yaml
  label: Audiomack Stats API
  slug: audiomack-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-stats-api-openapi.yml
- filename: audiomack-user-api-openapi.yml
  format: yaml
  label: Audiomack User API
  slug: audiomack-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-user-api-openapi.yml
- filename: audiomack-oauth-api-openapi.yml
  format: yaml
  label: Audiomack O Auth API
  slug: audiomack-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audiomack/openapi/audiomack-oauth-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: you are required to provide us with a valid email address, name, as well as your age and gender
  - category: identifying
    text: Technical data such as your IP Address, geolocation, cookie data, URLs visited, mobile device ID and information, device attributes, operating system, network connection, browser type, language, and mobile app version.
  - category: location
    text: Device sensor data including lat/long and/or geolocation.
  - category: behavioral
    text: Details of any searches you make using the Audiomack search tools, including the date and time searches were made.
  - category: communication
    text: Details concerning your interaction with any Platform methods of communication specifically including but not limited to emails and push/in-app notifications, such as whether you opened and/or clicked on such messages.
  deletion:
    route: email privacy@audiomack.com or support ticket or user dashboard
    text: You may request account and data deletion at any time, for any reason.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate account and identify user
    text: To operate your Audiomack account, and to identify you when you use the Platform.
  - purpose: advertising
    text: To show you relevant ads on behalf of advertisers and/or sponsors, which may include location data, along with demographic data you make available to us or through connected third party services, recent search history, and behavior with content, ads, or other users on the Platform;
  - purpose: marketing communications
    text: To communicate with you for marketing, support, and/or promotional purposes through email, text message, push, or in-app notifications;
  rights:
  - right: erasure
    text: you shall have the right to obtain from Audiomack the erasure of personal data concerning yourself without undue delay
  - right: access/export
    text: You may use these same methods to request that Audiomack send to you all the data we have stored that is related to your account.
  - right: update
    text: You may update your personal information at any time by visiting your Dashboard page in your user profile.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Audiomack does not sell your personal data to third parties, period.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Please be aware that not all countries have the same data storage and privacy laws as the United States, and by using the Audiomack Platform you consent to the storage, transfer, collection, and transmission of your data to other territories as necessary.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Audiomack
provenance_date: '2026-11-09'
provider_name: Audiomack
provider_slug: audiomack
slug: audiomack-privacy-policy
source_date: '2026-11-09'
source_filename: audiomack-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://audiomack.com/about/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Audiomack\naid: audiomack\nurl: https://audiomack.com/about/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: you are required to provide us with a valid email address, name, as well as your age and gender\n- category: identifying\n  text: Technical data such as your IP Address, geolocation, cookie data, URLs visited, mobile device ID and information,\n    device attributes, operating system, network connection, browser type, language, and mobile app version.\n- category: location\n  text: Device sensor data including lat/long\
  \ and/or geolocation.\n- category: behavioral\n  text: Details of any searches you make using the Audiomack search tools, including the date and time searches\n    were made.\n- category: communication\n  text: Details concerning your interaction with any Platform methods of communication specifically including but\n    not limited to emails and push/in-app notifications, such as whether you opened and/or clicked on such messages.\npurposes:\n- purpose: operate account and identify user\n  text: To operate your Audiomack account, and to identify you when you use the Platform.\n- purpose: advertising\n  text: To show you relevant ads on behalf of advertisers and/or sponsors, which may include location data, along\n    with demographic data you make available to us or through connected third party services, recent search history,\n    and behavior with content, ads, or other users on the Platform;\n- purpose: marketing communications\n  text: To communicate with you for marketing, support,\
  \ and/or promotional purposes through email, text message,\n    push, or in-app notifications;\nretention: []\nresidency: []\ntransfers:\n- mechanism: other\n  text: Please be aware that not all countries have the same data storage and privacy laws as the United States,\n    and by using the Audiomack Platform you consent to the storage, transfer, collection, and transmission of your\n    data to other territories as necessary.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@audiomack.com or support ticket or user dashboard\n  text: You may request account and data deletion at any time, for any reason.\nrights:\n- right: erasure\n  text: you shall have the right to obtain from Audiomack the erasure of personal data concerning yourself without\n    undue delay\n- right: access/export\n  text: You may use these same methods to request that Audiomack send to you all the data we have stored that is\n    related\
  \ to your account.\n- right: update\n  text: You may update your personal information at any time by visiting your Dashboard page in your user profile.\nsale_or_sharing:\n  stance: conditional\n  text: Audiomack does not sell your personal data to third parties, period.\n"
source_yaml_url: https://artifacts.apis.io/audiomack/privacy/audiomack-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Audiomack's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Music Streaming
- Audio
- Podcasts
- Hip-Hop
- Rap
- Afrobeats
- Reggae
- Dancehall
- R&B
- Electronic
- Charts
- Playlists
- Discovery
- Creator Economy
- Independent Artists
---
