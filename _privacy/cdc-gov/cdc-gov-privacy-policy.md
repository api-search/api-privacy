---
api_specs:
- filename: cdc-gov-app-notifications-api-openapi.yml
  format: yaml
  label: CDC App Notifications API
  slug: cdc-gov-app-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-app-notifications-api-openapi.yml
- filename: cdc-gov-code-systems-api-openapi.yml
  format: yaml
  label: CDC Code Systems API
  slug: cdc-gov-code-systems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-code-systems-api-openapi.yml
- filename: cdc-gov-conditions-api-openapi.yml
  format: yaml
  label: CDC Conditions API
  slug: cdc-gov-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-conditions-api-openapi.yml
- filename: cdc-gov-configurations-api-openapi.yml
  format: yaml
  label: CDC Configurations API
  slug: cdc-gov-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-configurations-api-openapi.yml
- filename: cdc-gov-events-api-openapi.yml
  format: yaml
  label: CDC Events API
  slug: cdc-gov-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-events-api-openapi.yml
- filename: cdc-gov-query-api-openapi.yml
  format: yaml
  label: CDC Query API
  slug: cdc-gov-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-query-api-openapi.yml
- filename: cdc-gov-query-connector-api-openapi-3-0-api-openapi.yml
  format: yaml
  label: CDC Query Connector API OpenAPI 3.0 API
  slug: cdc-gov-query-connector-api-openapi-3-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-query-connector-api-openapi-3-0-api-openapi.yml
- filename: cdc-gov-releases-api-openapi.yml
  format: yaml
  label: CDC Releases API
  slug: cdc-gov-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-releases-api-openapi.yml
- filename: cdc-gov-simulator-api-openapi.yml
  format: yaml
  label: CDC Simulator API
  slug: cdc-gov-simulator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-simulator-api-openapi.yml
- filename: cdc-gov-user-api-openapi.yml
  format: yaml
  label: CDC User API
  slug: cdc-gov-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdc-gov/openapi/cdc-gov-user-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: contact
    text: Submitting personal information (name, address, telephone number, email address, etc.) is voluntary and is not required to access information on our website.
  - category: behavioral
    text: Non-PII information related to your visit to our websites may be automatically collected and temporarily stored.
  deletion:
    route: contact CDC Privacy Office
    text: please contact the CDC Privacy Office (see Contact information here).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: respond to user requests
    text: we may use that information to respond to your message and/or help us get you the information or services you requested.
  - purpose: statistical analysis and site improvement
    text: We may use data you provide and automatically generated data for statistical analysis to assess, for example, what information is of interest to users, technical design specifications, and system performance.
  retention:
  - period: as long as necessary
    scope: information submitted by users
    text: We retain the information only for as long as necessary to respond to your question or request.
  - period: immediately upon completion of its intended purpose
    scope: children's personal information
    text: Personal information about your child will be destroyed immediately upon completion of its intended purpose.
  rights:
  - right: opt out of geofenced messaging
    text: CDC requires that individuals always have the option to opt-out of messaging
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not use or share your information for commercial purposes and, except as described above, we do not exchange or otherwise disclose this information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CDC
provenance_date: '2026-11-09'
provider_name: CDC
provider_slug: cdc-gov
slug: cdc-gov-privacy-policy
source_date: '2026-11-09'
source_filename: cdc-gov-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cdc.gov/other/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CDC\naid: cdc-gov\nurl: https://www.cdc.gov/other/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Submitting personal information (name, address, telephone number, email address, etc.) is voluntary and\n    is not required to access information on our website.\n- category: behavioral\n  text: Non-PII information related to your visit to our websites may be automatically collected and temporarily\n    stored.\npurposes:\n- purpose: respond to user requests\n  text: we may use that information to respond to your message and/or help\
  \ us get you the information or services\n    you requested.\n- purpose: statistical analysis and site improvement\n  text: We may use data you provide and automatically generated data for statistical analysis to assess, for example,\n    what information is of interest to users, technical design specifications, and system performance.\nretention:\n- scope: information submitted by users\n  period: as long as necessary\n  text: We retain the information only for as long as necessary to respond to your question or request.\n- scope: children's personal information\n  period: immediately upon completion of its intended purpose\n  text: Personal information about your child will be destroyed immediately upon completion of its intended purpose.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact CDC Privacy Office\n  text: please contact the CDC Privacy Office (see Contact information here).\n\
  rights:\n- right: opt out of geofenced messaging\n  text: CDC requires that individuals always have the option to opt-out of messaging\nsale_or_sharing:\n  stance: conditional\n  text: We do not use or share your information for commercial purposes and, except as described above, we do not\n    exchange or otherwise disclose this information.\n"
source_yaml_url: https://artifacts.apis.io/cdc-gov/privacy/cdc-gov-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 9 quoted statements, read from CDC's own page on 2026-11-09.
synthetic: false
tags:
- Public Health
- Disease Surveillance
- Vaccination
- Health Statistics
- Government
- Open Data
- Environmental Health
- Mortality
- CDC WONDER
- Epidemiology
- Federal Government
- Healthcare
- Socrata
- WONDER
---
