---
api_specs:
- filename: blvigil-com-agent-api-openapi.yml
  format: yaml
  label: Vigil Agent API
  slug: blvigil-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvigil-com/openapi/blvigil-com-agent-api-openapi.yml
- filename: blvigil-com-mcp-api-openapi.yml
  format: yaml
  label: Vigil MCP API
  slug: blvigil-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvigil-com/openapi/blvigil-com-mcp-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: A Vigil account can include email address, authentication method, account creation and recent sign-in or activity timestamps, preferences, subscription or entitlement status, and download access.
  - category: location
    text: Residents, home configuration, device state, activity and alert history, geofence settings, relay configuration, and derived sensing results are stored in Vigil's application-support database on your Mac.
  - category: device
    text: Like an ordinary web request, that exposes request time, requested path, IP address, and user-agent information to our hosting and security provider.
  - category: financial
    text: Black Label receives the information needed to deliver and support your order, including email, product, price, currency, payment or subscription status, and transaction identifiers.
  - category: behavioral
    text: Vigil pages load PostHog, which measures page views and may record clicks and other page interactions, session replays of page layout, scrolling and clicks, heatmaps, clicks that had no effect, and browser errors.
  - category: communication
    text: If you email support, our email service and Black Label process the message, contact details, and related account or order information needed to respond.
  deletion:
    route: Email support@blvigil.com or use Vigil support; verified request deletes account record and preferences
    text: A verified request can delete your Vigil account record and preferences.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver and support orders
    text: Black Label receives the information needed to deliver and support your order
  - purpose: Operational analytics
    text: Vigil pages load PostHog, which measures page views and may record clicks and other page interactions
  - purpose: Website security
    text: Cloudflare serves and protects this website and therefore processes ordinary request and security data such as IP address, user agent, URL, time, cookies, and bot or abuse signals.
  retention:
  - period: null
    scope: Account and order information
    text: We keep account and order information for as long as needed to provide access, fulfill orders, prevent fraud, keep financial records, resolve disputes, and meet legal obligations.
  - period: up to 30 days
    scope: Signed-in browser session
    text: A signed-in browser session lasts up to 30 days.
  - period: about 15 minutes
    scope: Abuse-prevention records
    text: Short-lived abuse-prevention records derived from email and IP information can be kept for about 15 minutes.
  rights:
  - right: access
    text: To request access, correction, or deletion, email support@blvigil.com from the address on the account, or use Vigil support .
  - right: correction
    text: To request access, correction, or deletion, email support@blvigil.com from the address on the account, or use Vigil support .
  - right: deletion
    text: To request access, correction, or deletion, email support@blvigil.com from the address on the account, or use Vigil support .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use it for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vigil
provenance_date: '2026-11-09'
provider_name: Vigil
provider_slug: blvigil-com
slug: blvigil-com-privacy-policy
source_date: '2026-11-09'
source_filename: blvigil-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blvigil.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vigil\naid: blvigil-com\nurl: https://blvigil.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: A Vigil account can include email address, authentication method, account creation and recent sign-in or\n    activity timestamps, preferences, subscription or entitlement status, and download access.\n- category: location\n  text: Residents, home configuration, device state, activity and alert history, geofence settings, relay configuration,\n    and derived sensing results are stored in Vigil's application-support database on your\
  \ Mac.\n- category: device\n  text: Like an ordinary web request, that exposes request time, requested path, IP address, and user-agent information\n    to our hosting and security provider.\n- category: financial\n  text: Black Label receives the information needed to deliver and support your order, including email, product,\n    price, currency, payment or subscription status, and transaction identifiers.\n- category: behavioral\n  text: Vigil pages load PostHog, which measures page views and may record clicks and other page interactions, session\n    replays of page layout, scrolling and clicks, heatmaps, clicks that had no effect, and browser errors.\n- category: communication\n  text: If you email support, our email service and Black Label process the message, contact details, and related\n    account or order information needed to respond.\npurposes:\n- purpose: Deliver and support orders\n  text: Black Label receives the information needed to deliver and support your order\n- purpose:\
  \ Operational analytics\n  text: Vigil pages load PostHog, which measures page views and may record clicks and other page interactions\n- purpose: Website security\n  text: Cloudflare serves and protects this website and therefore processes ordinary request and security data such\n    as IP address, user agent, URL, time, cookies, and bot or abuse signals.\nretention:\n- scope: Account and order information\n  period: null\n  text: We keep account and order information for as long as needed to provide access, fulfill orders, prevent fraud,\n    keep financial records, resolve disputes, and meet legal obligations.\n- scope: Signed-in browser session\n  period: up to 30 days\n  text: A signed-in browser session lasts up to 30 days.\n- scope: Abuse-prevention records\n  period: about 15 minutes\n  text: Short-lived abuse-prevention records derived from email and IP information can be kept for about 15 minutes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@blvigil.com or use Vigil support; verified request deletes account record and preferences\n  text: A verified request can delete your Vigil account record and preferences.\nrights:\n- right: access\n  text: To request access, correction, or deletion, email support@blvigil.com from the address on the account, or\n    use Vigil support .\n- right: correction\n  text: To request access, correction, or deletion, email support@blvigil.com from the address on the account, or\n    use Vigil support .\n- right: deletion\n  text: To request access, correction, or deletion, email support@blvigil.com from the address on the account, or\n    use Vigil support .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/blvigil-com/privacy/blvigil-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Vigil's own page on 2026-11-09.
synthetic: false
tags:
- Home Automation
- Security
- Smart Home
- Software
- Mac
- Windows
---
