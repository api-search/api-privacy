---
api_specs:
- filename: notfair-co-health-api-openapi.yml
  format: yaml
  label: notfair-co Health API
  slug: notfair-co-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notfair-co/openapi/notfair-co-health-api-openapi.yml
- filename: notfair-co-mcp-api-openapi.yml
  format: yaml
  label: notfair-co MCP API
  slug: notfair-co-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notfair-co/openapi/notfair-co-mcp-api-openapi.yml
- filename: notfair-co-well-known-api-openapi.yml
  format: yaml
  label: notfair-co .well Known API
  slug: notfair-co-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/notfair-co/openapi/notfair-co-well-known-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Includes your name, email address, workspace membership, and the account or profile identifiers a connected provider returns when you sign in or authorize NotFair.
  - category: behavioral
    text: 'Usage Data: Information about how you access and use the Service, such as your IP address, browser type, and operating system.'
  - category: communication
    text: Lead responses can contain personal information submitted by a lead and are returned only when you request that data through an authorized account.
  deletion:
    route: Email request to tong@notfair.co
    text: To request deletion of stored connection or account data, contact us at tong@notfair.co .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: Provide, operate, and maintain the NotFair service.
  - purpose: Authenticate and connect accounts
    text: Authenticate you and connect the advertising, analytics, Search Console, CRM, and website accounts or properties you choose.
  - purpose: Improve user experience
    text: Monitor and analyze usage and trends to improve user experience.
  - purpose: Communicate with users
    text: Communicate with you about updates, security alerts, and support messages.
  retention:
  - period: null
    scope: Provider connection credentials
    text: We retain provider connection credentials and selected account metadata while the connection remains active
  - period: 100 days
    scope: Tool-call argument payloads
    text: Tool-call argument payloads are removed from operation records after 100 days
  - period: 365 days
    scope: Read-operation records
    text: read-operation records are deleted after 365 days
  - period: seven-day grace period
    scope: Expired OAuth authorization codes
    text: Expired OAuth authorization codes are deleted after a seven-day grace period
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: notfair-co
provenance_date: '2026-11-10'
provider_name: notfair-co
provider_slug: notfair-co
slug: notfair-co-privacy-policy
source_date: '2026-11-10'
source_filename: notfair-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://notfair.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: notfair-co\naid: notfair-co\nurl: https://notfair.co/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Includes your name, email address, workspace membership, and the account or profile identifiers a connected\n    provider returns when you sign in or authorize NotFair.\n- category: behavioral\n  text: 'Usage Data: Information about how you access and use the Service, such as your IP address, browser type,\n    and operating system.'\n- category: communication\n  text: Lead responses can contain personal information submitted by\
  \ a lead and are returned only when you request\n    that data through an authorized account.\npurposes:\n- purpose: Provide and operate the service\n  text: Provide, operate, and maintain the NotFair service.\n- purpose: Authenticate and connect accounts\n  text: Authenticate you and connect the advertising, analytics, Search Console, CRM, and website accounts or properties\n    you choose.\n- purpose: Improve user experience\n  text: Monitor and analyze usage and trends to improve user experience.\n- purpose: Communicate with users\n  text: Communicate with you about updates, security alerts, and support messages.\nretention:\n- scope: Provider connection credentials\n  period: null\n  text: We retain provider connection credentials and selected account metadata while the connection remains active\n- scope: Tool-call argument payloads\n  period: 100 days\n  text: Tool-call argument payloads are removed from operation records after 100 days\n- scope: Read-operation records\n  period:\
  \ 365 days\n  text: read-operation records are deleted after 365 days\n- scope: Expired OAuth authorization codes\n  period: seven-day grace period\n  text: Expired OAuth authorization codes are deleted after a seven-day grace period\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to tong@notfair.co\n  text: To request deletion of stored connection or account data, contact us at tong@notfair.co .\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/notfair-co/privacy/notfair-co-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 13 quoted statements, read from notfair-co's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Artificial Intelligence
- Marketing
- Automation
---
