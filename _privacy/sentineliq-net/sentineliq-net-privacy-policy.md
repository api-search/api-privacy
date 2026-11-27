---
api_specs:
- filename: sentineliq-net-agent-api-api-openapi.yml
  format: yaml
  label: sentineliq-net Agent API
  slug: sentineliq-net-agent-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-agent-api-api-openapi.yml
- filename: sentineliq-net-mcp-api-openapi.yml
  format: yaml
  label: sentineliq-net MCP API
  slug: sentineliq-net-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-mcp-api-openapi.yml
- filename: sentineliq-net-property-research-api-openapi.yml
  format: yaml
  label: sentineliq-net Property Research API
  slug: sentineliq-net-property-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-property-research-api-openapi.yml
- filename: sentineliq-net-public-api-openapi.yml
  format: yaml
  label: sentineliq-net Public API
  slug: sentineliq-net-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-public-api-openapi.yml
- filename: sentineliq-net-seller-workflows-api-openapi.yml
  format: yaml
  label: sentineliq-net Seller Workflows API
  slug: sentineliq-net-seller-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentineliq-net/openapi/sentineliq-net-seller-workflows-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account credentials — email address and a hashed password (we never see your raw password; authentication is handled by Supabase).
  - category: contact
    text: Optional contact data — if you use our Sphere of Influence tools, any contacts you add (name, phone, notes).
  - category: financial
    text: Optional deal data — if you use our deal tracking, transaction details you provide.
  - category: professional
    text: Agent profile — name, brokerage, specialty, and farm ZIP codes you provide during onboarding.
  - category: communication
    text: Chat content — messages you send in-app and the responses we generate.
  - category: behavioral
    text: Usage analytics — which features you use, response latency, error rates. Aggregated and scoped to your account.
  - category: device
    text: One free trial per person — when a free-trial account signs in to the developer console or connects an assistant, the page computes a browser identifier with the open-source FingerprintJS library, inside your browser, from browser and device signals.
  deletion:
    route: Email the privacy-request address
    text: You can request deletion of your data at any time by emailing [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver chat answers and calculations
    text: Answer your chat queries with property data, market stats, and coaching.
  - purpose: Improve service and troubleshoot
    text: Improve service quality and troubleshoot issues.
  - purpose: Trial and signup follow-up
    text: Continue a requested trial, Founding Agent Lab, or office-pilot signup and respond to that request.
  - purpose: Free trial abuse prevention
    text: This lets us give the free trial once per person rather than once per new email address, and we do not give trials to temporary inboxes.
  retention:
  - period: null
    scope: Account data
    text: Account data is retained while your account is active.
  - period: 30 days
    scope: Account deletion requests
    text: We will delete your profile, contacts, deals, and chat history within 30 days of a verified request, except as required by law (e.g., records of payments subject to tax retention rules).
  - period: 24 hours
    scope: Browser campaign receipt
    text: The browser campaign receipt used for account attribution expires after 24 hours.
  - period: 30 days
    scope: Browser toolkit credentials
    text: The toolkit treats them as expired after 30 days and removes expired entries on the next toolkit visit
  rights:
  - right: Know what personal information we hold
    text: Know what personal information we hold about you.
  - right: Correction
    text: Request correction of inaccurate information.
  - right: Deletion
    text: Request deletion of your information.
  - right: Portability
    text: Export your data in a portable format.
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
name: sentineliq-net
provenance_date: '2026-11-10'
provider_name: sentineliq-net
provider_slug: sentineliq-net
slug: sentineliq-net-privacy-policy
source_date: '2026-11-10'
source_filename: sentineliq-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sentineliq.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: sentineliq-net\naid: sentineliq-net\nurl: https://sentineliq.net/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account credentials — email address and a hashed password (we never see your raw password; authentication\n    is handled by Supabase).\n- category: contact\n  text: Optional contact data — if you use our Sphere of Influence tools, any contacts you add (name, phone, notes).\n- category: financial\n  text: Optional deal data — if you use our deal tracking, transaction details you provide.\n- category: professional\n  text:\
  \ Agent profile — name, brokerage, specialty, and farm ZIP codes you provide during onboarding.\n- category: communication\n  text: Chat content — messages you send in-app and the responses we generate.\n- category: behavioral\n  text: Usage analytics — which features you use, response latency, error rates. Aggregated and scoped to your account.\n- category: device\n  text: One free trial per person — when a free-trial account signs in to the developer console or connects an assistant,\n    the page computes a browser identifier with the open-source FingerprintJS library, inside your browser, from\n    browser and device signals.\npurposes:\n- purpose: Deliver chat answers and calculations\n  text: Answer your chat queries with property data, market stats, and coaching.\n- purpose: Improve service and troubleshoot\n  text: Improve service quality and troubleshoot issues.\n- purpose: Trial and signup follow-up\n  text: Continue a requested trial, Founding Agent Lab, or office-pilot signup\
  \ and respond to that request.\n- purpose: Free trial abuse prevention\n  text: This lets us give the free trial once per person rather than once per new email address, and we do not give\n    trials to temporary inboxes.\nretention:\n- scope: Account data\n  period: null\n  text: Account data is retained while your account is active.\n- scope: Account deletion requests\n  period: 30 days\n  text: We will delete your profile, contacts, deals, and chat history within 30 days of a verified request, except\n    as required by law (e.g., records of payments subject to tax retention rules).\n- scope: Browser campaign receipt\n  period: 24 hours\n  text: The browser campaign receipt used for account attribution expires after 24 hours.\n- scope: Browser toolkit credentials\n  period: 30 days\n  text: The toolkit treats them as expired after 30 days and removes expired entries on the next toolkit visit\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Email the privacy-request address\n  text: You can request deletion of your data at any time by emailing [email protected] .\nrights:\n- right: Know what personal information we hold\n  text: Know what personal information we hold about you.\n- right: Correction\n  text: Request correction of inaccurate information.\n- right: Deletion\n  text: Request deletion of your information.\n- right: Portability\n  text: Export your data in a portable format.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/sentineliq-net/privacy/sentineliq-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from sentineliq-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data API
- Washington
- AI Integration
---
