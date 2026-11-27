---
api_specs:
- filename: tohuman-humanizations-api-openapi.yml
  format: yaml
  label: ToHuman Humanizations API
  slug: tohuman-humanizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-humanizations-api-openapi.yml
- filename: tohuman-humanize-api-openapi.yml
  format: yaml
  label: ToHuman Humanize API
  slug: tohuman-humanize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-humanize-api-openapi.yml
- filename: tohuman-submit-api-openapi.yml
  format: yaml
  label: ToHuman Submit API
  slug: tohuman-submit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tohuman/openapi/tohuman-submit-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: identifying
    text: Name (optional)
  - category: identifying
    text: Password (hashed, never stored in plain text)
  - category: device
    text: Browser/device information (via standard HTTP headers)
  - category: identifying
    text: IP addresses (for rate limiting and security)
  - category: behavioral
    text: API request metadata (timestamps, intensity settings, word counts, processing times)
  - category: other
    text: Input and output text is stored in your account as document history so you can access it later.
  deletion:
    route: Delete documents or account from dashboard
    text: Delete individual documents or your entire account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the Service — processing your text and returning humanized output
  - purpose: Maintain account
    text: To maintain your account — authentication, document history, API token management
  - purpose: Enforce rate limits
    text: To enforce rate limits — fair usage across all users
  - purpose: Transactional emails
    text: To send transactional emails — account confirmation, password resets, important service updates
  - purpose: Improve the service
    text: To improve the Service — aggregate, anonymized usage statistics (never individual content)
  residency:
  - region: United States
    text: Your data is stored on servers within the United States.
  retention:
  - period: while your account is active
    scope: Account data
    text: Account data — retained while your account is active
  - period: until you delete them or close your account
    scope: Documents and humanizations
    text: Documents & humanizations — retained until you delete them or close your account
  - period: 90 days
    scope: API logs
    text: API logs — retained for 90 days for debugging and abuse prevention
  - period: within minutes
    scope: Rate limit data
    text: Rate limit data — temporary, automatically expires within minutes
  rights:
  - right: Access
    text: Access your data through your dashboard and API
  - right: Delete
    text: Delete individual documents or your entire account
  - right: Export
    text: Export your data by contacting us
  - right: Revoke API tokens
    text: Revoke API tokens at any time from your dashboard
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your data with advertisers
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ToHuman
provenance_date: '2026-11-10'
provider_name: ToHuman
provider_slug: tohuman
slug: tohuman-privacy-policy
source_date: '2026-11-10'
source_filename: tohuman-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tohuman.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ToHuman\naid: tohuman\nurl: https://tohuman.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address\n- category: identifying\n  text: Name (optional)\n- category: identifying\n  text: Password (hashed, never stored in plain text)\n- category: device\n  text: Browser/device information (via standard HTTP headers)\n- category: identifying\n  text: IP addresses (for rate limiting and security)\n- category: behavioral\n  text: API request metadata (timestamps, intensity settings, word counts, processing times)\n- category: other\n\
  \  text: Input and output text is stored in your account as document history so you can access it later.\npurposes:\n- purpose: Provide the service\n  text: To provide the Service — processing your text and returning humanized output\n- purpose: Maintain account\n  text: To maintain your account — authentication, document history, API token management\n- purpose: Enforce rate limits\n  text: To enforce rate limits — fair usage across all users\n- purpose: Transactional emails\n  text: To send transactional emails — account confirmation, password resets, important service updates\n- purpose: Improve the service\n  text: To improve the Service — aggregate, anonymized usage statistics (never individual content)\nretention:\n- scope: Account data\n  period: while your account is active\n  text: Account data — retained while your account is active\n- scope: Documents and humanizations\n  period: until you delete them or close your account\n  text: Documents & humanizations — retained until\
  \ you delete them or close your account\n- scope: API logs\n  period: 90 days\n  text: API logs — retained for 90 days for debugging and abuse prevention\n- scope: Rate limit data\n  period: within minutes\n  text: Rate limit data — temporary, automatically expires within minutes\nresidency:\n- region: United States\n  text: Your data is stored on servers within the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete documents or account from dashboard\n  text: Delete individual documents or your entire account\nrights:\n- right: Access\n  text: Access your data through your dashboard and API\n- right: Delete\n  text: Delete individual documents or your entire account\n- right: Export\n  text: Export your data by contacting us\n- right: Revoke API tokens\n  text: Revoke API tokens at any time from your dashboard\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your\
  \ data with advertisers\n"
source_yaml_url: https://artifacts.apis.io/tohuman/privacy/tohuman-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from ToHuman's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Text-Humanization
- Content Generation
- Marketing
- Software-as-a-Service
---
