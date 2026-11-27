---
api_specs:
- filename: busymate-dev-core-openapi-generated.yml
  format: yaml
  label: Busymate DevTools core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busymate-dev/openapi/_ae-authored/busymate-dev-core-openapi-generated.yml
- filename: busymate-dev-federation-openapi-generated.yml
  format: yaml
  label: Busymate DevTools federation API
  slug: federation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busymate-dev/openapi/_ae-authored/busymate-dev-federation-openapi-generated.yml
- filename: busymate-dev-mcp-openapi-generated.yml
  format: yaml
  label: Busymate DevTools mcp API
  slug: mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busymate-dev/openapi/_ae-authored/busymate-dev-mcp-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address (or Apple's private relay address, if you choose to hide your email).
  - category: location
    text: The app collects your device's public (egress) IP address and an approximate, country-level location derived from it.
  - category: device
    text: a per-device UUID generated locally at first launch
  - category: behavioral
    text: Request URLs, HTTP method, status code, request and response headers, and timing for every connection your device makes through the tunnel.
  - category: communication
    text: Response bodies, but only for the HTTPS domains you explicitly add to the SSL-proxy list inside the app.
  deletion:
    route: Delete account in app, Clear feed, device Unpair, or email support@busymate.net
    text: We will purge all entries, device records, and account data within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Network inspection
    text: lets you inspect the HTTP and HTTPS traffic of apps and devices you own
  - purpose: Account authentication
    text: This identity data is used solely to authenticate you and identify your account.
  - purpose: Push notifications
    text: so we can deliver notifications you've asked for (for example, capture alerts)
  - purpose: Product reliability
    text: Their sole purpose is to monitor and improve the reliability and usability of the app and its capture engine.
  retention:
  - period: 10 days
    scope: captured entries
    text: The platform enforces a single global retention window of 10 days for captured entries, applied uniformly across every workspace.
  rights:
  - right: access, correct, export, delete
    text: you have the right under GDPR (or equivalent national law) to access, correct, export, or delete your data
  - right: lodge complaint
    text: and to lodge a complaint with your national data protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not share it with advertisers or analytics networks.
  subprocessors:
    text: A small number of features involve additional, named sub-processors — Sign in with Apple and the IP-to-country lookup.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Busymate DevTools
provenance_date: '2026-11-09'
provider_name: Busymate DevTools
provider_slug: busymate-dev
slug: busymate-dev-privacy-policy
source_date: '2026-11-09'
source_filename: busymate-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://busymate.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Busymate DevTools\naid: busymate-dev\nurl: https://busymate.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address (or Apple's private relay address, if you choose to hide your email).\n- category: location\n  text: The app collects your device's public (egress) IP address and an approximate, country-level location derived\n    from it.\n- category: device\n  text: a per-device UUID generated locally at first launch\n- category: behavioral\n  text: Request URLs, HTTP method, status code, request and response headers,\
  \ and timing for every connection your\n    device makes through the tunnel.\n- category: communication\n  text: Response bodies, but only for the HTTPS domains you explicitly add to the SSL-proxy list inside the app.\npurposes:\n- purpose: Network inspection\n  text: lets you inspect the HTTP and HTTPS traffic of apps and devices you own\n- purpose: Account authentication\n  text: This identity data is used solely to authenticate you and identify your account.\n- purpose: Push notifications\n  text: so we can deliver notifications you've asked for (for example, capture alerts)\n- purpose: Product reliability\n  text: Their sole purpose is to monitor and improve the reliability and usability of the app and its capture engine.\nretention:\n- scope: captured entries\n  period: 10 days\n  text: The platform enforces a single global retention window of 10 days for captured entries, applied uniformly\n    across every workspace.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n \
  \ text: A small number of features involve additional, named sub-processors — Sign in with Apple and the IP-to-country\n    lookup.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in app, Clear feed, device Unpair, or email support@busymate.net\n  text: We will purge all entries, device records, and account data within 30 days.\nrights:\n- right: access, correct, export, delete\n  text: you have the right under GDPR (or equivalent national law) to access, correct, export, or delete your data\n- right: lodge complaint\n  text: and to lodge a complaint with your national data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we do not share it with advertisers or analytics networks.\n"
source_yaml_url: https://artifacts.apis.io/busymate-dev/privacy/busymate-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Busymate DevTools's own page on 2026-11-09.
synthetic: false
tags:
- Developer Tools
- Network Monitoring
- HTTPS Debugging
- AI Assistance
- Mobile Development
---
