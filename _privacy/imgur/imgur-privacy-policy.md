---
api_specs:
- filename: imgur-account-api-openapi.yml
  format: yaml
  label: Imgur Account API
  slug: imgur-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-account-api-openapi.yml
- filename: imgur-album-api-openapi.yml
  format: yaml
  label: Imgur Album API
  slug: imgur-album-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-album-api-openapi.yml
- filename: imgur-auth-api-openapi.yml
  format: yaml
  label: Imgur Auth API
  slug: imgur-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-auth-api-openapi.yml
- filename: imgur-comment-api-openapi.yml
  format: yaml
  label: Imgur Comment API
  slug: imgur-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-comment-api-openapi.yml
- filename: imgur-gallery-api-openapi.yml
  format: yaml
  label: Imgur Gallery API
  slug: imgur-gallery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-gallery-api-openapi.yml
- filename: imgur-image-api-openapi.yml
  format: yaml
  label: Imgur Image API
  slug: imgur-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-image-api-openapi.yml
- filename: imgur-memegen-api-openapi.yml
  format: yaml
  label: Imgur Memegen API
  slug: imgur-memegen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-memegen-api-openapi.yml
- filename: imgur-notification-api-openapi.yml
  format: yaml
  label: Imgur Notification API
  slug: imgur-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-notification-api-openapi.yml
- filename: imgur-tags-api-openapi.yml
  format: yaml
  label: Imgur Tags API
  slug: imgur-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-tags-api-openapi.yml
- filename: imgur-topic-api-openapi.yml
  format: yaml
  label: Imgur Topic API
  slug: imgur-topic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-topic-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect whatever personal data about you that you choose to give us, such as a contact email address (which we do not make public) and profile information.
  - category: device
    text: device characteristics (including device ID for mobile devices), operating system, browser type, IP address, username from stored cookies if present
  - category: contact
    text: we collect real names and contact information – so if you win a contest, we’ll ask for that information
  - category: behavioral
    text: page and image viewing statistics, and incoming and outgoing links
  deletion:
    route: log in and delete your account
    text: If you have a username, you may log in and access your data, correct whatever information you deem to be incorrect, opt out of information sharing with our advertisers, or delete your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: analytics and site optimization
    text: We use this automatically collected anonymous data to analyze how our site and app are used so as to keep them optimized
  - purpose: interest-based advertising
    text: We also provide automatically collected anonymous data to third party advertisers and analytics companies to supplement the tracking information described below
  - purpose: contest prizes
    text: to enable us to award prizes to the winners as well as to comply with the applicable laws, we collect real names and contact information
  - purpose: legal compliance
    text: We also use such data to enable us to comply with copyright law, with 18 USC §2258A (illegal content), and to respond to lawful requests by public authorities
  retention:
  - period: null
    scope: backup and archival copies
    text: For legal reasons we may retain backup and/or archival copies of information prior to your corrections, amendments, or deletions.
  - period: null
    scope: phone number
    text: we won’t save your number, share it, sell it, or even show it to anyone
  rights:
  - right: access and correction
    text: If you have a username, you may log in and access your data, correct whatever information you deem to be incorrect
  - right: opt out of sharing with advertisers
    text: opt out of information sharing with our advertisers
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
name: Imgur
provenance_date: '2026-11-09'
provider_name: Imgur
provider_slug: imgur
slug: imgur-privacy-policy
source_date: '2026-11-09'
source_filename: imgur-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://imgur.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Imgur\naid: imgur\nurl: https://imgur.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect whatever personal data about you that you choose to give us, such as a contact email address\n    (which we do not make public) and profile information.\n- category: device\n  text: device characteristics (including device ID for mobile devices), operating system, browser type, IP address,\n    username from stored cookies if present\n- category: contact\n  text: we collect real names and contact information – so if you win a contest,\
  \ we’ll ask for that information\n- category: behavioral\n  text: page and image viewing statistics, and incoming and outgoing links\npurposes:\n- purpose: analytics and site optimization\n  text: We use this automatically collected anonymous data to analyze how our site and app are used so as to keep\n    them optimized\n- purpose: interest-based advertising\n  text: We also provide automatically collected anonymous data to third party advertisers and analytics companies\n    to supplement the tracking information described below\n- purpose: contest prizes\n  text: to enable us to award prizes to the winners as well as to comply with the applicable laws, we collect real\n    names and contact information\n- purpose: legal compliance\n  text: We also use such data to enable us to comply with copyright law, with 18 USC §2258A (illegal content), and\n    to respond to lawful requests by public authorities\nretention:\n- scope: backup and archival copies\n  period: null\n  text: For legal\
  \ reasons we may retain backup and/or archival copies of information prior to your corrections,\n    amendments, or deletions.\n- scope: phone number\n  period: null\n  text: we won’t save your number, share it, sell it, or even show it to anyone\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: log in and delete your account\n  text: If you have a username, you may log in and access your data, correct whatever information you deem to be\n    incorrect, opt out of information sharing with our advertisers, or delete your account.\nrights:\n- right: access and correction\n  text: If you have a username, you may log in and access your data, correct whatever information you deem to be\n    incorrect\n- right: opt out of sharing with advertisers\n  text: opt out of information sharing with our advertisers\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imgur/privacy/imgur-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from Imgur's own page on 2026-11-09.
synthetic: false
tags:
- Photography
- Image
- Image Hosting
- Albums
- Gallery
- Social
- Memes
- Content Sharing
- Public APIs
---
