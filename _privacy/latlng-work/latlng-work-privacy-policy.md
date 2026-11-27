---
api_specs:
- filename: latlng-work-geocoding-api-openapi.yml
  format: yaml
  label: latlng-work Geocoding API
  slug: latlng-work-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latlng-work/openapi/latlng-work-geocoding-api-openapi.yml
- filename: latlng-work-places-api-openapi.yml
  format: yaml
  label: latlng-work Places API
  slug: latlng-work-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latlng-work/openapi/latlng-work-places-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name (optional)
  - category: contact
    text: Email address
  - category: financial
    text: Payment information (for paid plans, processed by our payment provider)
  - category: device
    text: IP addresses (for rate limiting purposes only)
  - category: behavioral
    text: API request counts and timestamps
  deletion:
    route: Request deletion of account and associated data
    text: You may request deletion of your account and associated data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Provide and maintain the Service
  - purpose: Process payments and manage subscription
    text: Process payments and manage your subscription
  - purpose: Enforce rate limits and prevent abuse
    text: Enforce rate limits and prevent abuse
  - purpose: Send service updates and announcements
    text: Send important service updates and announcements
  - purpose: Respond to support requests
    text: Respond to your support requests
  - purpose: Improve and optimize the Service
    text: Improve and optimize our Service
  retention:
  - period: as long as your account is active
    scope: Account information
    text: We retain your account information for as long as your account is active.
  - period: 90 days
    scope: API usage statistics
    text: API usage statistics are retained for 90 days for billing and analytics purposes.
  rights:
  - right: Access personal data
    text: Access your personal data
  - right: Correct inaccurate data
    text: Correct inaccurate data
  - right: Delete data
    text: Delete your data
  - right: Export data
    text: Export your data
  - right: Object to processing
    text: Object to processing
  - right: Withdraw consent
    text: Withdraw consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Share your query data with third parties
  subprocessors:
    text: '6. Third-Party Services We use the following third-party services: Clerk: For authentication (see Clerk Privacy Policy ) Cloudflare: For hosting and CDN'
    url: null
  transfers:
  - mechanism: other
    text: Your data may be processed in countries outside your jurisdiction. We ensure appropriate safeguards are in place for such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: latlng-work
provenance_date: '2026-11-09'
provider_name: latlng-work
provider_slug: latlng-work
slug: latlng-work-privacy-policy
source_date: '2026-11-09'
source_filename: latlng-work-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.latlng.work/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: latlng-work\naid: latlng-work\nurl: https://www.latlng.work/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name (optional)\n- category: contact\n  text: Email address\n- category: financial\n  text: Payment information (for paid plans, processed by our payment provider)\n- category: device\n  text: IP addresses (for rate limiting purposes only)\n- category: behavioral\n  text: API request counts and timestamps\npurposes:\n- purpose: Provide and maintain the Service\n  text: Provide and maintain the Service\n- purpose: Process payments\
  \ and manage subscription\n  text: Process payments and manage your subscription\n- purpose: Enforce rate limits and prevent abuse\n  text: Enforce rate limits and prevent abuse\n- purpose: Send service updates and announcements\n  text: Send important service updates and announcements\n- purpose: Respond to support requests\n  text: Respond to your support requests\n- purpose: Improve and optimize the Service\n  text: Improve and optimize our Service\nretention:\n- scope: Account information\n  period: as long as your account is active\n  text: We retain your account information for as long as your account is active.\n- scope: API usage statistics\n  period: 90 days\n  text: API usage statistics are retained for 90 days for billing and analytics purposes.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your data may be processed in countries outside your jurisdiction. We ensure appropriate safeguards are\n    in place for such transfers.\nsubprocessors:\n  url: null\n  text: '6.\
  \ Third-Party Services We use the following third-party services: Clerk: For authentication (see Clerk\n    Privacy Policy ) Cloudflare: For hosting and CDN'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of account and associated data\n  text: You may request deletion of your account and associated data at any time.\nrights:\n- right: Access personal data\n  text: Access your personal data\n- right: Correct inaccurate data\n  text: Correct inaccurate data\n- right: Delete data\n  text: Delete your data\n- right: Export data\n  text: Export your data\n- right: Object to processing\n  text: Object to processing\n- right: Withdraw consent\n  text: Withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: Share your query data with third parties\n"
source_yaml_url: https://artifacts.apis.io/latlng-work/privacy/latlng-work-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from latlng-work's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geocoding
- Mapping
- Location
---
