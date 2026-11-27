---
api_specs:
- filename: 10web-account-api-openapi.yml
  format: yaml
  label: 10Web Account API
  slug: 10web-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-account-api-openapi.yml
- filename: 10web-backup-api-openapi.yml
  format: yaml
  label: 10Web Backup API
  slug: 10web-backup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-backup-api-openapi.yml
- filename: 10web-builder-api-openapi.yml
  format: yaml
  label: 10Web Builder API
  slug: 10web-builder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-builder-api-openapi.yml
- filename: 10web-cache-api-openapi.yml
  format: yaml
  label: 10Web Cache API
  slug: 10web-cache-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-cache-api-openapi.yml
- filename: 10web-certificate-api-openapi.yml
  format: yaml
  label: 10Web Certificate API
  slug: 10web-certificate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-certificate-api-openapi.yml
- filename: 10web-domain-api-openapi.yml
  format: yaml
  label: 10Web Domain API
  slug: 10web-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-domain-api-openapi.yml
- filename: 10web-php-management-api-openapi.yml
  format: yaml
  label: 10Web PHP Management API
  slug: 10web-php-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-php-management-api-openapi.yml
- filename: 10web-section-based-ai-api-openapi.yml
  format: yaml
  label: 10Web Section Based AI API
  slug: 10web-section-based-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-section-based-ai-api-openapi.yml
- filename: 10web-vibe-coding-api-openapi.yml
  format: yaml
  label: 10Web Vibe Coding API
  slug: 10web-vibe-coding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-vibe-coding-api-openapi.yml
- filename: 10web-website-api-openapi.yml
  format: yaml
  label: 10Web Website API
  slug: 10web-website-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-website-api-openapi.yml
- filename: 10web-wp-autologin-api-openapi.yml
  format: yaml
  label: 10Web WP Autologin API
  slug: 10web-wp-autologin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-wp-autologin-api-openapi.yml
- filename: 10web-zone-api-openapi.yml
  format: yaml
  label: 10Web Zone API
  slug: 10web-zone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-zone-api-openapi.yml
- filename: 10web-sub-domain-api-openapi.yml
  format: yaml
  label: 10Web Sub Domain API
  slug: 10web-sub-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-sub-domain-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: First Name Last Name Email Address Password
  - category: financial
    text: Credit Card info. Please note that while you are required to input your Credit Card information, your Credit Card data is not collected by Us and is directly sent to Stripe from your browser.
  - category: location
    text: IP address
  - category: behavioral
    text: Visitor’s behaviour
  deletion:
    route: request via account or email
    text: We have put in place mechanisms and solutions, to delete your personal data we retain, upon your request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: To be able to provide services
  - purpose: Improve platform
    text: To improve our Platform in order to better serve you.
  - purpose: Send emails about orders
    text: To send periodic emails regarding your order or other products and services.
  residency:
  - region: EU and/or adequacy locations
    text: Our servers are in EU and/or in locations subject to Adequacy Decision and/or EU-US privacy Shield
  retention:
  - period: null
    scope: Account and personal data
    text: Personal data is retained until you request us to delete your personal data
  - period: one month
    scope: Deactivation log
    text: Personal data is retained for one month
  - period: one month
    scope: AI co-pilot recordings
    text: Deleted after one month
  - period: 72 hours
    scope: Image Optimizer images
    text: In case of Image Optimizer, images are cached for 72 hours.
  rights:
  - right: access
    text: We honor your right to be informed on and have access to your data that you provided to Us
  - right: deletion
    text: as well as your right to request Us to delete your personal data.
  - right: export
    text: We have put in place mechanisms and solutions, to export and provide you with your personal data we retain, upon your request
  - right: withdraw consent
    text: You can always revoke your consent by contacting us
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or otherwise transfer to outside parties your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 10Web
provenance_date: '2026-11-09'
provider_name: 10Web
provider_slug: 10web
slug: 10web-privacy-policy
source_date: '2026-11-09'
source_filename: 10web-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://10web.io/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 10Web\naid: 10web\nurl: https://10web.io/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: First Name Last Name Email Address Password\n- category: financial\n  text: Credit Card info. Please note that while you are required to input your Credit Card information, your Credit\n    Card data is not collected by Us and is directly sent to Stripe from your browser.\n- category: location\n  text: IP address\n- category: behavioral\n  text: Visitor’s behaviour\npurposes:\n- purpose: Provide services\n  text: To be able to\
  \ provide services\n- purpose: Improve platform\n  text: To improve our Platform in order to better serve you.\n- purpose: Send emails about orders\n  text: To send periodic emails regarding your order or other products and services.\nretention:\n- scope: Account and personal data\n  period: null\n  text: Personal data is retained until you request us to delete your personal data\n- scope: Deactivation log\n  period: one month\n  text: Personal data is retained for one month\n- scope: AI co-pilot recordings\n  period: one month\n  text: Deleted after one month\n- scope: Image Optimizer images\n  period: 72 hours\n  text: In case of Image Optimizer, images are cached for 72 hours.\nresidency:\n- region: EU and/or adequacy locations\n  text: Our servers are in EU and/or in locations subject to Adequacy Decision and/or EU-US privacy Shield\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request via account\
  \ or email\n  text: We have put in place mechanisms and solutions, to delete your personal data we retain, upon your request\nrights:\n- right: access\n  text: We honor your right to be informed on and have access to your data that you provided to Us\n- right: deletion\n  text: as well as your right to request Us to delete your personal data.\n- right: export\n  text: We have put in place mechanisms and solutions, to export and provide you with your personal data we retain,\n    upon your request\n- right: withdraw consent\n  text: You can always revoke your consent by contacting us\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or otherwise transfer to outside parties your personal information.\n"
source_yaml_url: https://artifacts.apis.io/10web/privacy/10web-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from 10Web's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Website Builder
- WordPress
- Hosting
- Website Generation
- No-Code
---
