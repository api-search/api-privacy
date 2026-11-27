---
api_specs:
- filename: anisongs-jp-check-purity-api-openapi.yml
  format: yaml
  label: Anisongs Check Purity API
  slug: anisongs-jp-check-purity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-check-purity-api-openapi.yml
- filename: anisongs-jp-create-playlist-api-openapi.yml
  format: yaml
  label: Anisongs Create Playlist API
  slug: anisongs-jp-create-playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-create-playlist-api-openapi.yml
- filename: anisongs-jp-get-artist-api-openapi.yml
  format: yaml
  label: Anisongs Get Artist API
  slug: anisongs-jp-get-artist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-get-artist-api-openapi.yml
- filename: anisongs-jp-get-program-api-openapi.yml
  format: yaml
  label: Anisongs Get Program API
  slug: anisongs-jp-get-program-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-get-program-api-openapi.yml
- filename: anisongs-jp-search-tracks-api-openapi.yml
  format: yaml
  label: Anisongs Search Tracks API
  slug: anisongs-jp-search-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anisongs-jp/openapi/anisongs-jp-search-tracks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact form: name, email address, and inquiry content'
  - category: identifying
    text: Anonymous account identifier (a randomly issued token)
  - category: device
    text: Device identifier and device name (e.g., iPhone)
  - category: financial
    text: We never collect or store payment details such as credit card numbers.
  - category: behavioral
    text: Usage events in the app and on the site (operation logs such as screen views and playlist creation/export
  - category: location
    text: Server access logs (IP address, access time, browser type, referrer)
  - category: communication
    text: 'Contact form: name, email address, and inquiry content'
  deletion:
    route: Request via the contact form; verification requires your identifier (token or recovery phrase)
    text: 'Deleting your account (anonymous identifier) and related data : request via the contact form .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and operating the Service
    text: Providing and operating the Service (search, playlist creation/sharing/export, account recovery)
  - purpose: Analytics and improvement
    text: Analyzing usage, improving quality, and developing new features
  - purpose: Security and abuse prevention
    text: Detecting and preventing unauthorized access, misuse, and excessive automated access
  - purpose: Billing
    text: Providing paid plans and managing billing status
  - purpose: Advertising
    text: Ad delivery and ad performance measurement (website only)
  - purpose: Responding to inquiries
    text: Responding to and communicating about inquiries
  - purpose: Legal obligations
    text: Fulfilling legal obligations
  residency:
  - region: Japan
    text: Data is managed on servers located in Japan, with reasonable safeguards against unauthorized access.
  retention:
  - period: until you delete them or we receive a deletion request
    scope: Anonymous accounts and playlists
    text: 'Anonymous accounts, playlists, recovery phrase (hash), reinstall-restore value (hash): until you delete them or we receive a deletion request'
  - period: up to 2 years from collection
    scope: Usage events and click statistics
    text: 'Usage events and click statistics: up to 2 years from collection'
  - period: Usage records are automatically deleted after one year.
    scope: MCP and API tool usage usage records
    text: Usage records are automatically deleted after one year.
  - period: up to 1 year from collection
    scope: Server access logs
    text: 'Server access logs: up to 1 year from collection'
  - period: up to 7 days from collection
    scope: Access-control records (IP addresses)
    text: 'Access-control records for abuse prevention (IP addresses): up to 7 days from collection'
  - period: deleted within 1 year after resolution in principle
    scope: Inquiries
    text: 'Inquiries: deleted within 1 year after resolution in principle'
  rights:
  - right: Deletion of account
    text: 'Deleting your account (anonymous identifier) and related data : request via the contact form .'
  - right: Disclosure, correction, suspension of use
    text: 'Disclosure, correction, suspension of use : for personal information, we respond promptly within a reasonable scope after verifying identity'
  - right: Deleting or unpublishing playlists
    text: 'Deleting or unpublishing playlists : available at any time from within the Service'
  role:
    text: Forfans LLC ("we", "us") establishes this Privacy Policy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anisongs
provenance_date: '2026-11-09'
provider_name: Anisongs
provider_slug: anisongs-jp
slug: anisongs-jp-privacy-policy
source_date: '2026-11-09'
source_filename: anisongs-jp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anisongs.jp/privacy.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anisongs\naid: anisongs-jp\nurl: https://anisongs.jp/privacy.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Forfans LLC (\"we\", \"us\") establishes this Privacy Policy\ndata_categories:\n- category: contact\n  text: 'Contact form: name, email address, and inquiry content'\n- category: identifying\n  text: Anonymous account identifier (a randomly issued token)\n- category: device\n  text: Device identifier and device name (e.g., iPhone)\n- category: financial\n  text: We never collect or store payment details such as credit card numbers.\n- category: behavioral\n  text: Usage events in\
  \ the app and on the site (operation logs such as screen views and playlist creation/export\n- category: location\n  text: Server access logs (IP address, access time, browser type, referrer)\n- category: communication\n  text: 'Contact form: name, email address, and inquiry content'\npurposes:\n- purpose: Providing and operating the Service\n  text: Providing and operating the Service (search, playlist creation/sharing/export, account recovery)\n- purpose: Analytics and improvement\n  text: Analyzing usage, improving quality, and developing new features\n- purpose: Security and abuse prevention\n  text: Detecting and preventing unauthorized access, misuse, and excessive automated access\n- purpose: Billing\n  text: Providing paid plans and managing billing status\n- purpose: Advertising\n  text: Ad delivery and ad performance measurement (website only)\n- purpose: Responding to inquiries\n  text: Responding to and communicating about inquiries\n- purpose: Legal obligations\n  text: Fulfilling\
  \ legal obligations\nretention:\n- scope: Anonymous accounts and playlists\n  period: until you delete them or we receive a deletion request\n  text: 'Anonymous accounts, playlists, recovery phrase (hash), reinstall-restore value (hash): until you delete\n    them or we receive a deletion request'\n- scope: Usage events and click statistics\n  period: up to 2 years from collection\n  text: 'Usage events and click statistics: up to 2 years from collection'\n- scope: MCP and API tool usage usage records\n  period: Usage records are automatically deleted after one year.\n  text: Usage records are automatically deleted after one year.\n- scope: Server access logs\n  period: up to 1 year from collection\n  text: 'Server access logs: up to 1 year from collection'\n- scope: Access-control records (IP addresses)\n  period: up to 7 days from collection\n  text: 'Access-control records for abuse prevention (IP addresses): up to 7 days from collection'\n- scope: Inquiries\n  period: deleted within\
  \ 1 year after resolution in principle\n  text: 'Inquiries: deleted within 1 year after resolution in principle'\nresidency:\n- region: Japan\n  text: Data is managed on servers located in Japan, with reasonable safeguards against unauthorized access.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via the contact form; verification requires your identifier (token or recovery phrase)\n  text: 'Deleting your account (anonymous identifier) and related data : request via the contact form .'\nrights:\n- right: Deletion of account\n  text: 'Deleting your account (anonymous identifier) and related data : request via the contact form .'\n- right: Disclosure, correction, suspension of use\n  text: 'Disclosure, correction, suspension of use : for personal information, we respond promptly within a reasonable\n    scope after verifying identity'\n- right: Deleting or unpublishing playlists\n  text: 'Deleting\
  \ or unpublishing playlists : available at any time from within the Service'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your information.\n"
source_yaml_url: https://artifacts.apis.io/anisongs-jp/privacy/anisongs-jp-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Anisongs's own page on 2026-11-09.
synthetic: false
tags:
- Anime
- Music
- Database
- Japanese
- Entertainment
---
