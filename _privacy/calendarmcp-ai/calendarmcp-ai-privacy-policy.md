---
api_specs:
- filename: calendarmcp-ai-openapi-generated.yml
  format: yaml
  label: CalendarMCP API
  slug: calendarmcp-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calendarmcp-ai/openapi/_ae-authored/calendarmcp-ai-openapi-generated.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address (from Google OAuth)
  - category: identifying
    text: Your display name (from Google OAuth, if available)
  - category: other
    text: OAuth refresh token for Google Calendar API access
  - category: other
    text: Generated API key for MCP authentication
  deletion:
    route: Disconnect account in dashboard
    text: When you disconnect, all stored information including your email, API key, and OAuth tokens are permanently deleted from our database.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate and authorize access to Google Calendar
    text: Authenticate and authorize access to your Google Calendar
  - purpose: Provide MCP server functionality
    text: Provide MCP server functionality to your connected AI agents
  - purpose: Maintain account and API key
    text: Maintain your account and API key
  retention:
  - period: until you choose to disconnect your account
    scope: Account information
    text: We retain your account information until you choose to disconnect your account.
  rights:
  - right: View stored account information
    text: View your stored account information in the dashboard
  - right: Regenerate API key
    text: Regenerate your API key at any time
  - right: Delete account
    text: Disconnect and delete your account completely
  - right: Revoke Google OAuth permissions
    text: Revoke Google OAuth permissions
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 'We do not share, sell, or disclose your personal information to third parties except:'
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CalendarMCP
provenance_date: '2026-11-09'
provider_name: CalendarMCP
provider_slug: calendarmcp-ai
slug: calendarmcp-ai-privacy-policy
source_date: '2026-11-09'
source_filename: calendarmcp-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://calendarmcp.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CalendarMCP\naid: calendarmcp-ai\nurl: https://calendarmcp.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address (from Google OAuth)\n- category: identifying\n  text: Your display name (from Google OAuth, if available)\n- category: other\n  text: OAuth refresh token for Google Calendar API access\n- category: other\n  text: Generated API key for MCP authentication\npurposes:\n- purpose: Authenticate and authorize access to Google Calendar\n  text: Authenticate and authorize access to your Google Calendar\n- purpose:\
  \ Provide MCP server functionality\n  text: Provide MCP server functionality to your connected AI agents\n- purpose: Maintain account and API key\n  text: Maintain your account and API key\nretention:\n- scope: Account information\n  period: until you choose to disconnect your account\n  text: We retain your account information until you choose to disconnect your account.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Disconnect account in dashboard\n  text: When you disconnect, all stored information including your email, API key, and OAuth tokens are permanently\n    deleted from our database.\nrights:\n- right: View stored account information\n  text: View your stored account information in the dashboard\n- right: Regenerate API key\n  text: Regenerate your API key at any time\n- right: Delete account\n  text: Disconnect and delete your account completely\n- right: Revoke Google OAuth\
  \ permissions\n  text: Revoke Google OAuth permissions\nsale_or_sharing:\n  stance: prohibited\n  text: 'We do not share, sell, or disclose your personal information to third parties except:'\n"
source_yaml_url: https://artifacts.apis.io/calendarmcp-ai/privacy/calendarmcp-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from CalendarMCP's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Artificial Intelligence
- MCP
- Google Calendar
- Integration
---
