---
api_specs:
- filename: geoloods-agent-api-openapi.yml
  format: yaml
  label: Geoloods Agent API
  slug: geoloods-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-agent-api-openapi.yml
- filename: geoloods-bbox-api-openapi.yml
  format: yaml
  label: Geoloods Bbox API
  slug: geoloods-bbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-bbox-api-openapi.yml
- filename: geoloods-countries-api-openapi.yml
  format: yaml
  label: Geoloods Countries API
  slug: geoloods-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-countries-api-openapi.yml
- filename: geoloods-geocode-api-openapi.yml
  format: yaml
  label: Geoloods Geocode API
  slug: geoloods-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-geocode-api-openapi.yml
- filename: geoloods-nearby-api-openapi.yml
  format: yaml
  label: Geoloods Nearby API
  slug: geoloods-nearby-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-nearby-api-openapi.yml
- filename: geoloods-search-api-openapi.yml
  format: yaml
  label: Geoloods Search API
  slug: geoloods-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geoloods/openapi/geoloods-search-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Name Company name (optional) Password (encrypted and hashed)
  - category: device
    text: User agent information
  - category: location
    text: IP addresses
  - category: financial
    text: We do not store your full credit card details on our servers. We only retain transaction records and payment status information.
  - category: behavioral
    text: API usage statistics
  deletion:
    route: Contact us using the information provided below
    text: To exercise these rights, please contact us using the information provided below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain geocoding API service
    text: Provide and maintain our geocoding API service
  - purpose: Process transactions and subscriptions
    text: Process your transactions and manage your subscription
  - purpose: Monitor usage and prevent abuse
    text: Monitor API usage and prevent abuse
  - purpose: Improve services
    text: Improve our services and develop new features
  - purpose: Customer support
    text: Respond to your requests and provide customer support
  - purpose: Legal compliance
    text: Comply with legal obligations
  retention:
  - period: Retained until account deletion
    scope: Account data
    text: 'Account data: Retained until account deletion'
  - period: 90 days
    scope: API logs
    text: 'API logs: Retained for 90 days'
  - period: 7 years
    scope: Transaction records
    text: 'Transaction records: Retained for 7 years (legal requirement)'
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Rectification: Correct inaccurate or incomplete data'
  - right: Erasure
    text: 'Erasure: Request deletion of your data'
  - right: Restriction
    text: 'Restriction: Limit how we use your data'
  - right: Portability
    text: 'Portability: Receive your data in a structured format'
  - right: Objection
    text: 'Objection: Object to certain processing activities'
  - right: Withdraw consent
    text: 'Withdraw Consent: Withdraw consent at any time'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal information to third parties.
  subprocessors:
    text: 'Service Providers: Payment processors (Mollie), hosting providers, and email service providers'
    url: null
  transfers:
  - mechanism: other
    text: Your information may be transferred to and maintained on servers located outside of your country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Geoloods
provenance_date: '2026-11-09'
provider_name: Geoloods
provider_slug: geoloods
slug: geoloods-privacy-policy
source_date: '2026-11-09'
source_filename: geoloods-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://geoloods.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Geoloods\naid: geoloods\nurl: https://geoloods.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address Name Company name (optional) Password (encrypted and hashed)\n- category: device\n  text: User agent information\n- category: location\n  text: IP addresses\n- category: financial\n  text: We do not store your full credit card details on our servers. We only retain transaction records and payment\n    status information.\n- category: behavioral\n  text: API usage statistics\npurposes:\n- purpose: Provide and maintain geocoding\
  \ API service\n  text: Provide and maintain our geocoding API service\n- purpose: Process transactions and subscriptions\n  text: Process your transactions and manage your subscription\n- purpose: Monitor usage and prevent abuse\n  text: Monitor API usage and prevent abuse\n- purpose: Improve services\n  text: Improve our services and develop new features\n- purpose: Customer support\n  text: Respond to your requests and provide customer support\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Account data\n  period: Retained until account deletion\n  text: 'Account data: Retained until account deletion'\n- scope: API logs\n  period: 90 days\n  text: 'API logs: Retained for 90 days'\n- scope: Transaction records\n  period: 7 years\n  text: 'Transaction records: Retained for 7 years (legal requirement)'\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may be transferred to and maintained on servers located outside of your\
  \ country.\nsubprocessors:\n  url: null\n  text: 'Service Providers: Payment processors (Mollie), hosting providers, and email service providers'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us using the information provided below\n  text: To exercise these rights, please contact us using the information provided below.\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Rectification\n  text: 'Rectification: Correct inaccurate or incomplete data'\n- right: Erasure\n  text: 'Erasure: Request deletion of your data'\n- right: Restriction\n  text: 'Restriction: Limit how we use your data'\n- right: Portability\n  text: 'Portability: Receive your data in a structured format'\n- right: Objection\n  text: 'Objection: Object to certain processing activities'\n- right: Withdraw consent\n  text: 'Withdraw Consent: Withdraw consent at any time'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent\
  \ your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/geoloods/privacy/geoloods-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Geoloods's own page on 2026-11-09.
synthetic: false
tags:
- Geocoding
- Place Search
- Location
- Coordinates
- Mapping
- Geospatial
- Agents
- OpenAPI
- Llms.txt
---
