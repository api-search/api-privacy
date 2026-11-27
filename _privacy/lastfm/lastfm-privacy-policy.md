---
api_specs:
- filename: lastfm-album-api-openapi.yml
  format: yaml
  label: Last.fm Album API
  slug: lastfm-album-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-album-api-openapi.yml
- filename: lastfm-artist-api-openapi.yml
  format: yaml
  label: Last.fm Artist API
  slug: lastfm-artist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-artist-api-openapi.yml
- filename: lastfm-auth-api-openapi.yml
  format: yaml
  label: Last.fm Auth API
  slug: lastfm-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-auth-api-openapi.yml
- filename: lastfm-chart-api-openapi.yml
  format: yaml
  label: Last.fm Chart API
  slug: lastfm-chart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-chart-api-openapi.yml
- filename: lastfm-geo-api-openapi.yml
  format: yaml
  label: Last.fm Geo API
  slug: lastfm-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-geo-api-openapi.yml
- filename: lastfm-library-api-openapi.yml
  format: yaml
  label: Last.fm Library API
  slug: lastfm-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-library-api-openapi.yml
- filename: lastfm-tag-api-openapi.yml
  format: yaml
  label: Last.fm Tag API
  slug: lastfm-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-tag-api-openapi.yml
- filename: lastfm-track-api-openapi.yml
  format: yaml
  label: Last.fm Track API
  slug: lastfm-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-track-api-openapi.yml
- filename: lastfm-user-api-openapi.yml
  format: yaml
  label: Last.fm User API
  slug: lastfm-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastfm/openapi/lastfm-user-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: your full name or display name, email address, username, password, date of birth, profile photograph or avatar
  - category: contact
    text: email address
  - category: financial
    text: payment information (such as billing address) is handled by secure third-party processors, such as Stripe or PayPal
  - category: location
    text: your IP address (which may indicate approximate location at city level)
  - category: device
    text: unique device identifiers, cookie ID, media access control (MAC) address and other unique identifiers
  - category: behavioral
    text: online activity data using device-based tracking technologies such as cookies, pixels, tags, beacons, scripts, and similar technologies
  - category: communication
    text: shouts or comments, reviews, connections with other users
  - category: health
    text: Last.fm does not collect sensitive personal information, such as data revealing racial or ethnic origin, political opinions, religious beliefs, health conditions, biometric data, or sexual orientation.
  deletion:
    route: email dp3@last.fm or delete account via account settings
    text: Ask us to delete your account and data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services
    text: We process your personal information to provide you with the Last.fm Services, as part of our agreement with you, or to maintain our relationship with you.
  - purpose: personalised advertising
    text: to personalise advertising and marketing
  - purpose: improve services and train ML
    text: Train machine learning models to improve services, for example, better recommendations
  - purpose: safety and security
    text: to manage safety and security
  residency:
  - region: UK
    text: Last.fm is a UK-based company, but operates globally.
  retention:
  - period: null
    scope: registration information
    text: we retain your registration information for the duration of your relationship with us
  - period: null
    scope: records after relationship ends
    text: Once our relationship ends, we may retain certain records (such as your email address and details about your transactions) for an additional period of time to comply with our legal obligations in certain jurisdictions and to prevent fraud.
  rights:
  - right: access
    text: Access a copy of your personal data.
  - right: correction
    text: Ask us to correct inaccurate or incomplete data.
  - right: deletion
    text: Ask us to delete your account and data
  - right: objection
    text: Object to our use of your data when we rely on legitimate interests.
  - right: restriction
    text: Ask us to restrict how we use your data.
  - right: portability
    text: Receive your data in a structured, machine-readable format.
  - right: withdraw consent
    text: Withdraw consent at any time (this will not affect processing that has already happened).
  - right: opt-out of sale or sharing
    text: Opt-out of the "sale" or "sharing" of your personal information
  role:
    text: Last.fm Limited, ("Last.fm", "we", "us", or "our"), operates the Last.fm website(s)
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we put in place standard contractual clauses approved under data protection laws in the United Kingdom, the EEA, Switzerland to facilitate transfers to the United States of America.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Last.fm
provenance_date: '2026-11-09'
provider_name: Last.fm
provider_slug: lastfm
slug: lastfm-privacy-policy
source_date: '2026-11-09'
source_filename: lastfm-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.last.fm/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Last.fm\naid: lastfm\nurl: https://www.last.fm/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Last.fm Limited, (\"Last.fm\", \"we\", \"us\", or \"our\"), operates the Last.fm website(s)\ndata_categories:\n- category: identifying\n  text: your full name or display name, email address, username, password, date of birth, profile photograph or\n    avatar\n- category: contact\n  text: email address\n- category: financial\n  text: payment information (such as billing address) is handled by secure third-party processors, such as Stripe\n    or PayPal\n- category: location\n  text:\
  \ your IP address (which may indicate approximate location at city level)\n- category: device\n  text: unique device identifiers, cookie ID, media access control (MAC) address and other unique identifiers\n- category: behavioral\n  text: online activity data using device-based tracking technologies such as cookies, pixels, tags, beacons, scripts,\n    and similar technologies\n- category: communication\n  text: shouts or comments, reviews, connections with other users\n- category: health\n  text: Last.fm does not collect sensitive personal information, such as data revealing racial or ethnic origin,\n    political opinions, religious beliefs, health conditions, biometric data, or sexual orientation.\npurposes:\n- purpose: provide services\n  text: We process your personal information to provide you with the Last.fm Services, as part of our agreement\n    with you, or to maintain our relationship with you.\n- purpose: personalised advertising\n  text: to personalise advertising and marketing\n\
  - purpose: improve services and train ML\n  text: Train machine learning models to improve services, for example, better recommendations\n- purpose: safety and security\n  text: to manage safety and security\nretention:\n- scope: registration information\n  period: null\n  text: we retain your registration information for the duration of your relationship with us\n- scope: records after relationship ends\n  period: null\n  text: Once our relationship ends, we may retain certain records (such as your email address and details about\n    your transactions) for an additional period of time to comply with our legal obligations in certain jurisdictions\n    and to prevent fraud.\nresidency:\n- region: UK\n  text: Last.fm is a UK-based company, but operates globally.\ntransfers:\n- mechanism: SCC\n  text: we put in place standard contractual clauses approved under data protection laws in the United Kingdom,\n    the EEA, Switzerland to facilitate transfers to the United States of America.\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email dp3@last.fm or delete account via account settings\n  text: Ask us to delete your account and data\nrights:\n- right: access\n  text: Access a copy of your personal data.\n- right: correction\n  text: Ask us to correct inaccurate or incomplete data.\n- right: deletion\n  text: Ask us to delete your account and data\n- right: objection\n  text: Object to our use of your data when we rely on legitimate interests.\n- right: restriction\n  text: Ask us to restrict how we use your data.\n- right: portability\n  text: Receive your data in a structured, machine-readable format.\n- right: withdraw consent\n  text: Withdraw consent at any time (this will not affect processing that has already happened).\n- right: opt-out of sale or sharing\n  text: Opt-out of the \"sale\" or \"sharing\" of your personal information\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lastfm/privacy/lastfm-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 26 quoted statements, read from Last.fm's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Audio
- Scrobbling
- Recommendations
- Charts
- Public APIs
- AudioScrobbler
---
