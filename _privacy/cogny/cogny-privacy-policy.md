---
api_specs:
- filename: cogny-reports-api-openapi.yml
  format: yaml
  label: Cogny Reports API
  slug: cogny-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-reports-api-openapi.yml
- filename: cogny-tickets-api-openapi.yml
  format: yaml
  label: Cogny Tickets API
  slug: cogny-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-tickets-api-openapi.yml
- filename: cogny-warehouses-api-openapi.yml
  format: yaml
  label: Cogny Warehouses API
  slug: cogny-warehouses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-warehouses-api-openapi.yml
- filename: cogny-webhooks-api-openapi.yml
  format: yaml
  label: Cogny Webhooks API
  slug: cogny-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogny/openapi/cogny-webhooks-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address First name and last name
  - category: device
    text: Internet Protocol (IP) address Browser type and version
  - category: behavioral
    text: Pages visited on our Website Date and time of your visit Time spent on pages
  - category: device
    text: Device identifiers
  - category: communication
    text: We may store a text transcript of the conversation
  deletion:
    route: Disconnect integration in app settings or uninstall Shopify app
    text: When you uninstall, we automatically delete your OAuth credentials and disable the connection.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and maintain services
    text: To maintain and provide our services
  - purpose: analytics and improvement
    text: To analyze usage patterns and improve our services
  - purpose: customer support
    text: To offer customer care and support
  - purpose: security
    text: detect and address technical issues
  residency:
  - region: Sweden
    text: Your data, including Personal Data, may be transferred and stored outside your jurisdiction, including in Sweden.
  retention:
  - period: null
    scope: Google OAuth refresh tokens
    text: OAuth refresh tokens are stored encrypted in our database (Supabase Vault).
  - period: null
    scope: Google cached data
    text: Cached or temporary data used during report generation is retained only for the duration needed to complete the request.
  - period: null
    scope: MCP server
    text: The MCP server does not store or cache query results.
  - period: null
    scope: Voice assistant transcripts
    text: retained no longer than necessary
  rights:
  - right: withdraw consent
    text: you can withdraw consent at any time via the cookie settings
  - right: disconnect integrations
    text: You can disconnect any Google service at any time from Settings > API Connections in the Cogny app.
  role:
    text: operated by Cogny AB
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Google data is not sold, shared with third parties for advertising, or used for any purpose unrelated to providing the Cogny platform services to the authenticated user.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cogny
provenance_date: '2026-11-09'
provider_name: Cogny
provider_slug: cogny
slug: cogny-privacy-policy
source_date: '2026-11-09'
source_filename: cogny-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cogny.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cogny\naid: cogny\nurl: https://cogny.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: operated by Cogny AB\ndata_categories:\n- category: identifying\n  text: Email address First name and last name\n- category: device\n  text: Internet Protocol (IP) address Browser type and version\n- category: behavioral\n  text: Pages visited on our Website Date and time of your visit Time spent on pages\n- category: device\n  text: Device identifiers\n- category: communication\n  text: We may store a text transcript of the conversation\npurposes:\n- purpose: provide and maintain services\n  text:\
  \ To maintain and provide our services\n- purpose: analytics and improvement\n  text: To analyze usage patterns and improve our services\n- purpose: customer support\n  text: To offer customer care and support\n- purpose: security\n  text: detect and address technical issues\nretention:\n- scope: Google OAuth refresh tokens\n  period: null\n  text: OAuth refresh tokens are stored encrypted in our database (Supabase Vault).\n- scope: Google cached data\n  period: null\n  text: Cached or temporary data used during report generation is retained only for the duration needed to complete\n    the request.\n- scope: MCP server\n  period: null\n  text: The MCP server does not store or cache query results.\n- scope: Voice assistant transcripts\n  period: null\n  text: retained no longer than necessary\nresidency:\n- region: Sweden\n  text: Your data, including Personal Data, may be transferred and stored outside your jurisdiction, including in\n    Sweden.\ntransfers: []\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Disconnect integration in app settings or uninstall Shopify app\n  text: When you uninstall, we automatically delete your OAuth credentials and disable the connection.\nrights:\n- right: withdraw consent\n  text: you can withdraw consent at any time via the cookie settings\n- right: disconnect integrations\n  text: You can disconnect any Google service at any time from Settings > API Connections in the Cogny app.\nsale_or_sharing:\n  stance: conditional\n  text: Google data is not sold, shared with third parties for advertising, or used for any purpose unrelated to\n    providing the Cogny platform services to the authenticated user.\n"
source_yaml_url: https://artifacts.apis.io/cogny/privacy/cogny-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Cogny's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Marketing
- Marketing Analytics
- Marketing Automation
- MCP
- Agents
- Data Warehouse
- Advertising
---
