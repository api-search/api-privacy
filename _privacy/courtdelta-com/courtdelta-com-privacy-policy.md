---
api_specs:
- filename: courtdelta-com-attorney-cta-api-openapi.yml
  format: yaml
  label: Court Delta Attorney Cta API
  slug: courtdelta-com-attorney-cta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-attorney-cta-api-openapi.yml
- filename: courtdelta-com-calendar-api-openapi.yml
  format: yaml
  label: Court Delta Calendar API
  slug: courtdelta-com-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-calendar-api-openapi.yml
- filename: courtdelta-com-case-lookup-public-api-openapi.yml
  format: yaml
  label: Court Delta Case Lookup Public API
  slug: courtdelta-com-case-lookup-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-case-lookup-public-api-openapi.yml
- filename: courtdelta-com-case-summary-api-openapi.yml
  format: yaml
  label: Court Delta Case Summary API
  slug: courtdelta-com-case-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-case-summary-api-openapi.yml
- filename: courtdelta-com-citation-check-api-openapi.yml
  format: yaml
  label: Court Delta Citation Check API
  slug: courtdelta-com-citation-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-citation-check-api-openapi.yml
- filename: courtdelta-com-court-date-lookup-api-openapi.yml
  format: yaml
  label: Court Delta Court Date Lookup API
  slug: courtdelta-com-court-date-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-court-date-lookup-api-openapi.yml
- filename: courtdelta-com-courthouse-info-api-openapi.yml
  format: yaml
  label: Court Delta Courthouse Info API
  slug: courtdelta-com-courthouse-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-courthouse-info-api-openapi.yml
- filename: courtdelta-com-expunction-options-api-openapi.yml
  format: yaml
  label: Court Delta Expunction Options API
  slug: courtdelta-com-expunction-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-expunction-options-api-openapi.yml
- filename: courtdelta-com-license-points-api-openapi.yml
  format: yaml
  label: Court Delta License Points API
  slug: courtdelta-com-license-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-license-points-api-openapi.yml
- filename: courtdelta-com-public-api-openapi.yml
  format: yaml
  label: Court Delta Public API
  slug: courtdelta-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-public-api-openapi.yml
- filename: courtdelta-com-settings-api-openapi.yml
  format: yaml
  label: Court Delta Settings API
  slug: courtdelta-com-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-settings-api-openapi.yml
- filename: courtdelta-com-subscribe-api-openapi.yml
  format: yaml
  label: Court Delta Subscribe API
  slug: courtdelta-com-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/courtdelta-com/openapi/courtdelta-com-subscribe-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and phone number
  - category: financial
    text: Payment information (processed by Stripe)
  - category: device
    text: Device and browser information
  - category: location
    text: IP address and location (country/region level)
  - category: behavioral
    text: Usage data and interactions with the Service
  - category: communication
    text: Communications with us
  deletion:
    route: Contact us
    text: You may request access, correction, deletion, or opt-out of certain processing by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing court case lookup, monitoring, and notifications
    text: Providing court case lookup, monitoring, and notifications
  - purpose: Facilitating attorney advertising and lead generation
    text: Facilitating consented attorney advertising and lead generation
  - purpose: Analytics and service optimization
    text: Analytics and service optimization
  - purpose: Detecting fraud and ensuring security
    text: Detecting fraud and ensuring security
  retention:
  - period: while your account is active
    scope: Account data
    text: Account data is retained while your account is active
  - period: for the duration of active monitoring
    scope: Case monitoring data
    text: Case monitoring data is retained for the duration of active monitoring
  - period: up to 90 days
    scope: After account deletion
    text: We may retain data for up to 90 days after account deletion
  rights:
  - right: Access
    text: You may request access, correction, deletion, or opt-out of certain processing by contacting us.
  - right: Opt-out of attorney sharing
    text: You may withdraw this consent at any time using the "Opt out of attorney sharing" link in our emails or by contacting us.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Court Delta
provenance_date: '2026-11-09'
provider_name: Court Delta
provider_slug: courtdelta-com
slug: courtdelta-com-privacy-policy
source_date: '2026-11-09'
source_filename: courtdelta-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.courtdelta.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Court Delta\naid: courtdelta-com\nurl: https://app.courtdelta.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, and phone number\n- category: financial\n  text: Payment information (processed by Stripe)\n- category: device\n  text: Device and browser information\n- category: location\n  text: IP address and location (country/region level)\n- category: behavioral\n  text: Usage data and interactions with the Service\n- category: communication\n  text: Communications with us\npurposes:\n- purpose: Providing\
  \ court case lookup, monitoring, and notifications\n  text: Providing court case lookup, monitoring, and notifications\n- purpose: Facilitating attorney advertising and lead generation\n  text: Facilitating consented attorney advertising and lead generation\n- purpose: Analytics and service optimization\n  text: Analytics and service optimization\n- purpose: Detecting fraud and ensuring security\n  text: Detecting fraud and ensuring security\nretention:\n- scope: Account data\n  period: while your account is active\n  text: Account data is retained while your account is active\n- scope: Case monitoring data\n  period: for the duration of active monitoring\n  text: Case monitoring data is retained for the duration of active monitoring\n- scope: After account deletion\n  period: up to 90 days\n  text: We may retain data for up to 90 days after account deletion\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: Contact us\n  text: You may request access, correction, deletion, or opt-out of certain processing by contacting us.\nrights:\n- right: Access\n  text: You may request access, correction, deletion, or opt-out of certain processing by contacting us.\n- right: Opt-out of attorney sharing\n  text: You may withdraw this consent at any time using the \"Opt out of attorney sharing\" link in our emails or\n    by contacting us.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/courtdelta-com/privacy/courtdelta-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Court Delta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Court Records
- Case Tracking
- Notifications
- North Carolina
- MCP
---
