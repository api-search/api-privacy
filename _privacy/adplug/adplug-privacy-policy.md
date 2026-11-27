---
api_specs:
- filename: adplug-health-api-openapi.yml
  format: yaml
  label: AdPlug Health API
  slug: adplug-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-health-api-openapi.yml
- filename: adplug-mcp-api-openapi.yml
  format: yaml
  label: AdPlug MCP API
  slug: adplug-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-mcp-api-openapi.yml
- filename: adplug-oauth-api-openapi.yml
  format: yaml
  label: AdPlug OAuth API
  slug: adplug-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-oauth-api-openapi.yml
- filename: adplug-oauth-legacy-compat-api-openapi.yml
  format: yaml
  label: AdPlug OAUTH Legacy Compat API
  slug: adplug-oauth-legacy-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-oauth-legacy-compat-api-openapi.yml
- filename: adplug-users-api-openapi.yml
  format: yaml
  label: AdPlug Users API
  slug: adplug-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-users-api-openapi.yml
- filename: adplug-webhooks-api-openapi.yml
  format: yaml
  label: AdPlug Webhooks API
  slug: adplug-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adplug/openapi/adplug-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up, we collect your email address and name.
  - category: contact
    text: If you sign in with Google, we receive your Google profile information (name, email, profile photo).
  - category: financial
    text: We do not store credit card numbers or bank details.
  - category: location
    text: along with your browser, device type and the approximate location of your IP address.
  - category: behavioral
    text: We log each MCP tool call you make (tool name, platform, account ID, success/error status, response time).
  - category: device
    text: along with your browser, device type and the approximate location of your IP address.
  - category: communication
    text: We do not log the content of your AI conversations.
  deletion:
    route: Dashboard disconnect or account deletion; data deletion page for step-by-step instructions
    text: Step-by-step instructions are on our data deletion page .
  dpa:
    available: true
    text: For the full data-protection terms governing these sub-processors, including international transfer mechanisms, see our Data Processing Agreement .
    url: https://adplug.app/dpa
  purposes:
  - purpose: Authenticate and provide MCP endpoint access
    text: To authenticate you and provide access to your MCP endpoint
  - purpose: Execute API calls to connected platforms
    text: To execute API calls to your connected platforms on your behalf when requested by your AI tool
  - purpose: Enforce usage limits
    text: To enforce usage limits based on your subscription tier
  - purpose: Measure own advertising
    text: Where you have allowed it, to understand how AdPlug is used and to measure whether our own advertising works
  residency:
  - region: US-East-2
    text: 'Supabase : Authentication and database hosting. Stores your profile, encrypted credentials, and usage logs. Located in US-East-2.'
  - region: US-East-1
    text: 'Google Cloud (Cloud Run) : Hosts our API server. Processes your MCP requests. Located in US-East-1.'
  - region: US
    text: 'PostHog : product analytics. Receives product events from our servers and, unless you turn analytics cookies off, page views and session replays from your browser. Located in the US.'
  retention:
  - period: Deleted within 30 days of account deletion
    scope: Account data
    text: 'Account data : retained while your account is active. Deleted within 30 days of account deletion.'
  - period: immediately
    scope: OAuth tokens
    text: 'OAuth tokens , and the HubSpot portal details in section 7: deleted immediately when you disconnect a platform, remove a HubSpot portal, or delete your account.'
  - period: a day or two
    scope: Change previews
    text: A daily clean-up deletes each one a day or two after it was made
  - period: 7 days Free, 30 days Pro, 90 days Agency
    scope: Usage logs
    text: 'Usage logs : retained for the duration of your audit log period (7 days Free, 30 days Pro, 90 days Agency).'
  rights:
  - right: Access data
    text: 'Access your data : view your profile, connections, and usage in the dashboard'
  - right: Delete data
    text: 'Delete your data : disconnect platforms or delete your account from the dashboard settings'
  - right: Revoke access
    text: 'Revoke access : disconnect any ad platform at any time; we immediately delete the stored OAuth tokens'
  - right: Export data
    text: 'Export your data : contact us at privacy@adplug.app for a data export'
  - right: GDPR rights
    text: If you are in the EU/EEA, you have additional rights under GDPR including the right to restrict processing and the right to data portability.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: We share data with these services only as needed to provide the product.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AdPlug
provenance_date: '2026-11-09'
provider_name: AdPlug
provider_slug: adplug
slug: adplug-privacy-policy
source_date: '2026-11-09'
source_filename: adplug-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adplug.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AdPlug\naid: adplug\nurl: https://adplug.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up, we collect your email address and name.\n- category: contact\n  text: If you sign in with Google, we receive your Google profile information (name, email, profile photo).\n- category: financial\n  text: We do not store credit card numbers or bank details.\n- category: location\n  text: along with your browser, device type and the approximate location of your IP address.\n- category: behavioral\n  text: We log each MCP tool\
  \ call you make (tool name, platform, account ID, success/error status, response time).\n- category: device\n  text: along with your browser, device type and the approximate location of your IP address.\n- category: communication\n  text: We do not log the content of your AI conversations.\npurposes:\n- purpose: Authenticate and provide MCP endpoint access\n  text: To authenticate you and provide access to your MCP endpoint\n- purpose: Execute API calls to connected platforms\n  text: To execute API calls to your connected platforms on your behalf when requested by your AI tool\n- purpose: Enforce usage limits\n  text: To enforce usage limits based on your subscription tier\n- purpose: Measure own advertising\n  text: Where you have allowed it, to understand how AdPlug is used and to measure whether our own advertising works\nretention:\n- scope: Account data\n  period: Deleted within 30 days of account deletion\n  text: 'Account data : retained while your account is active. Deleted within\
  \ 30 days of account deletion.'\n- scope: OAuth tokens\n  period: immediately\n  text: 'OAuth tokens , and the HubSpot portal details in section 7: deleted immediately when you disconnect a platform,\n    remove a HubSpot portal, or delete your account.'\n- scope: Change previews\n  period: a day or two\n  text: A daily clean-up deletes each one a day or two after it was made\n- scope: Usage logs\n  period: 7 days Free, 30 days Pro, 90 days Agency\n  text: 'Usage logs : retained for the duration of your audit log period (7 days Free, 30 days Pro, 90 days Agency).'\nresidency:\n- region: US-East-2\n  text: 'Supabase : Authentication and database hosting. Stores your profile, encrypted credentials, and usage logs.\n    Located in US-East-2.'\n- region: US-East-1\n  text: 'Google Cloud (Cloud Run) : Hosts our API server. Processes your MCP requests. Located in US-East-1.'\n- region: US\n  text: 'PostHog : product analytics. Receives product events from our servers and, unless you turn analytics\
  \ cookies\n    off, page views and session replays from your browser. Located in the US.'\ntransfers: []\nsubprocessors:\n  url: null\n  text: We share data with these services only as needed to provide the product.\ndpa:\n  available: true\n  url: https://adplug.app/dpa\n  text: For the full data-protection terms governing these sub-processors, including international transfer mechanisms,\n    see our Data Processing Agreement .\ndeletion:\n  route: Dashboard disconnect or account deletion; data deletion page for step-by-step instructions\n  text: Step-by-step instructions are on our data deletion page .\nrights:\n- right: Access data\n  text: 'Access your data : view your profile, connections, and usage in the dashboard'\n- right: Delete data\n  text: 'Delete your data : disconnect platforms or delete your account from the dashboard settings'\n- right: Revoke access\n  text: 'Revoke access : disconnect any ad platform at any time; we immediately delete the stored OAuth tokens'\n- right:\
  \ Export data\n  text: 'Export your data : contact us at privacy@adplug.app for a data export'\n- right: GDPR rights\n  text: If you are in the EU/EEA, you have additional rights under GDPR including the right to restrict processing\n    and the right to data portability.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/adplug/privacy/adplug-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from AdPlug's own page on 2026-11-09.
synthetic: false
tags:
- PPC
- AI Integration
- Agency Tools
- Search Console
---
