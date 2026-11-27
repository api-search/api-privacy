---
api_specs:
- filename: nexbid-dev-agent-api-openapi.yml
  format: yaml
  label: nexbid-dev Agent API
  slug: nexbid-dev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexbid-dev/openapi/nexbid-dev-agent-api-openapi.yml
- filename: nexbid-dev-attribution-api-openapi.yml
  format: yaml
  label: nexbid-dev Attribution API
  slug: nexbid-dev-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexbid-dev/openapi/nexbid-dev-attribution-api-openapi.yml
- filename: nexbid-dev-discovery-api-openapi.yml
  format: yaml
  label: nexbid-dev Discovery API
  slug: nexbid-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexbid-dev/openapi/nexbid-dev-discovery-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Name (if provided) Authentication tokens and session data
  - category: device
    text: IP address of the accessing device Date and time of access Name and URL of the requested file Browser type and version Operating system used
  - category: contact
    text: we collect your email address and optionally your role (Publisher, Advertiser, Ad-Tech Developer)
  - category: behavioral
    text: Search queries (product search, categories, product details)
  deletion:
    route: Direct requests to welcome@digital-opua.ch
    text: Direct requests to welcome@digital-opua.ch. We will respond to your request within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and operating the Service
    text: Providing and operating the Service
  - purpose: User authentication and account management
    text: User authentication and account management
  - purpose: Communicating with interested parties (waitlist)
    text: Communicating with interested parties (waitlist)
  - purpose: Error resolution and security
    text: Error resolution and security
  - purpose: Product development
    text: Product development
  residency:
  - region: EU (Frankfurt)
    text: All infrastructure data is processed in the EU (Frankfurt).
  retention:
  - period: Maximum 30 days
    scope: Server logs
    text: 'Server logs: Maximum 30 days'
  - period: Until the beta phase concludes, unless an ongoing business relationship exists
    scope: Waitlist data
    text: 'Waitlist data: Until the beta phase concludes, unless an ongoing business relationship exists'
  - period: Until account deletion by the user
    scope: User account data
    text: 'User account data: Until account deletion by the user'
  - period: Maximum 90 days
    scope: API usage data
    text: 'API usage data: Maximum 90 days'
  rights:
  - right: Access
    text: Right to access your stored data
  - right: Rectification
    text: Right to rectify inaccurate data
  - right: Deletion
    text: Right to delete your data
  - right: Portability
    text: Right to data portability
  - right: Withdraw consent
    text: Right to withdraw consent
  - right: Restriction
    text: Right to restrict processing
  role:
    text: 'The data controller for this website is: digital opua GmbH'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: No data is shared for advertising purposes.
  subprocessors:
    text: 'We only share personal data where necessary for service delivery. The following data processors are used: Vercel Inc. (USA)'
    url: null
  transfers:
  - mechanism: DPF
    text: Adequate data protection under Swiss-U.S. Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: nexbid-dev
provenance_date: '2026-11-10'
provider_name: nexbid-dev
provider_slug: nexbid-dev
slug: nexbid-dev-privacy-policy
source_date: '2026-11-10'
source_filename: nexbid-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nexbid.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: nexbid-dev\naid: nexbid-dev\nurl: https://nexbid.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The data controller for this website is: digital opua GmbH'\ndata_categories:\n- category: identifying\n  text: Email address Name (if provided) Authentication tokens and session data\n- category: device\n  text: IP address of the accessing device Date and time of access Name and URL of the requested file Browser type\n    and version Operating system used\n- category: contact\n  text: we collect your email address and optionally your role (Publisher, Advertiser, Ad-Tech Developer)\n\
  - category: behavioral\n  text: Search queries (product search, categories, product details)\npurposes:\n- purpose: Providing and operating the Service\n  text: Providing and operating the Service\n- purpose: User authentication and account management\n  text: User authentication and account management\n- purpose: Communicating with interested parties (waitlist)\n  text: Communicating with interested parties (waitlist)\n- purpose: Error resolution and security\n  text: Error resolution and security\n- purpose: Product development\n  text: Product development\nretention:\n- scope: Server logs\n  period: Maximum 30 days\n  text: 'Server logs: Maximum 30 days'\n- scope: Waitlist data\n  period: Until the beta phase concludes, unless an ongoing business relationship exists\n  text: 'Waitlist data: Until the beta phase concludes, unless an ongoing business relationship exists'\n- scope: User account data\n  period: Until account deletion by the user\n  text: 'User account data: Until account\
  \ deletion by the user'\n- scope: API usage data\n  period: Maximum 90 days\n  text: 'API usage data: Maximum 90 days'\nresidency:\n- region: EU (Frankfurt)\n  text: All infrastructure data is processed in the EU (Frankfurt).\ntransfers:\n- mechanism: DPF\n  text: Adequate data protection under Swiss-U.S. Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: 'We only share personal data where necessary for service delivery. The following data processors are used:\n    Vercel Inc. (USA)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Direct requests to welcome@digital-opua.ch\n  text: Direct requests to welcome@digital-opua.ch. We will respond to your request within 30 days.\nrights:\n- right: Access\n  text: Right to access your stored data\n- right: Rectification\n  text: Right to rectify inaccurate data\n- right: Deletion\n  text: Right to delete your data\n- right: Portability\n  text: Right to data portability\n- right: Withdraw consent\n  text: Right\
  \ to withdraw consent\n- right: Restriction\n  text: Right to restrict processing\nsale_or_sharing:\n  stance: unstated\n  text: No data is shared for advertising purposes.\n"
source_yaml_url: https://artifacts.apis.io/nexbid-dev/privacy/nexbid-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 24 quoted statements, read from nexbid-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Commerce
- Advertising
- Switzerland
- Open Source
---
