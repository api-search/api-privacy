---
api_specs:
- filename: flightaware-airports-api-openapi.yml
  format: yaml
  label: FlightAware Airports API
  slug: flightaware-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-airports-api-openapi.yml
- filename: flightaware-alerts-api-openapi.yml
  format: yaml
  label: FlightAware Alerts API
  slug: flightaware-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-alerts-api-openapi.yml
- filename: flightaware-flights-api-openapi.yml
  format: yaml
  label: FlightAware Flights API
  slug: flightaware-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-flights-api-openapi.yml
- filename: flightaware-foresight-api-openapi.yml
  format: yaml
  label: FlightAware Foresight API
  slug: flightaware-foresight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-foresight-api-openapi.yml
- filename: flightaware-history-api-openapi.yml
  format: yaml
  label: FlightAware History API
  slug: flightaware-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-history-api-openapi.yml
- filename: flightaware-miscellaneous-api-openapi.yml
  format: yaml
  label: FlightAware Miscellaneous API
  slug: flightaware-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-miscellaneous-api-openapi.yml
- filename: flightaware-operators-api-openapi.yml
  format: yaml
  label: FlightAware Operators API
  slug: flightaware-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-operators-api-openapi.yml
- filename: flightaware-account-api-openapi.yml
  format: yaml
  label: FlightAware Account API
  slug: flightaware-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightaware/openapi/flightaware-account-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: names, e-mail addresses, e-mail preferences, account passwords, mailing addresses, and billing addresses
  - category: device
    text: information about the device(s) that you use to access our products and services
  - category: behavioral
    text: we keep track of certain information about you when you visit and interact with any of our products and services
  - category: location
    text: We use your IP address and/or country preference to approximate your location
  - category: financial
    text: We collect payment and associated billing information when you register for paid products or services
  deletion:
    route: Request deletion via contact
    text: You may request deletion of your account or Personal Information by us
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: basic business operations and customer communications
    text: To conduct basic business operations, such as to communicate with you and for business planning.
  - purpose: improve products and services
    text: To improve our products and services, and our website.
  - purpose: advertising
    text: For relevant advertisements
  residency:
  - region: United States
    text: Your Personal Information may be processed in countries (including the United States) where Data Protection Laws may be different or less stringent than in your home jurisdiction.
  retention:
  - period: null
    scope: personal information
    text: After such time, we will either delete or anonymize your information
  rights:
  - right: access
    text: The right to access, modify, and correct Personal Information about you
  - right: deletion
    text: You may request deletion of your account or Personal Information by us
  - right: opt-out of communications
    text: The right to opt-out of our communications to you using "unsubscribe features"
  - right: withdraw consent
    text: Where processing of Personal Information about you is based on consent, the right to withdraw your consent to such processing
  - right: complaint to supervisory authority
    text: The right to lodge a complaint with a supervisory authority.
  role:
    text: FlightAware LLC is responsible for this website, including its mobile versions
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: BCR
    text: Through RTX, FlightAware has adopted Binding Corporate Rules (BCRs) as a mechanism to authorize the sharing of Personal Information between its businesses inside the European Union (EU)
  - mechanism: SCC
    text: To the extent that FlightAware relies on the standard contractual clauses (also called the model clauses) or Binding Corporate Rules to authorize transfer
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FlightAware
provenance_date: '2026-11-09'
provider_name: FlightAware
provider_slug: flightaware
slug: flightaware-privacy-policy
source_date: '2026-11-09'
source_filename: flightaware-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.flightaware.com/about/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FlightAware\naid: flightaware\nurl: https://www.flightaware.com/about/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: FlightAware LLC is responsible for this website, including its mobile versions\ndata_categories:\n- category: identifying\n  text: names, e-mail addresses, e-mail preferences, account passwords, mailing addresses, and billing addresses\n- category: device\n  text: information about the device(s) that you use to access our products and services\n- category: behavioral\n  text: we keep track of certain information about you when you visit and interact with any of our products\
  \ and\n    services\n- category: location\n  text: We use your IP address and/or country preference to approximate your location\n- category: financial\n  text: We collect payment and associated billing information when you register for paid products or services\npurposes:\n- purpose: basic business operations and customer communications\n  text: To conduct basic business operations, such as to communicate with you and for business planning.\n- purpose: improve products and services\n  text: To improve our products and services, and our website.\n- purpose: advertising\n  text: For relevant advertisements\nretention:\n- scope: personal information\n  period: null\n  text: After such time, we will either delete or anonymize your information\nresidency:\n- region: United States\n  text: Your Personal Information may be processed in countries (including the United States) where Data Protection\n    Laws may be different or less stringent than in your home jurisdiction.\ntransfers:\n- mechanism:\
  \ BCR\n  text: Through RTX, FlightAware has adopted Binding Corporate Rules (BCRs) as a mechanism to authorize the sharing\n    of Personal Information between its businesses inside the European Union (EU)\n- mechanism: SCC\n  text: To the extent that FlightAware relies on the standard contractual clauses (also called the model clauses)\n    or Binding Corporate Rules to authorize transfer\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via contact\n  text: You may request deletion of your account or Personal Information by us\nrights:\n- right: access\n  text: The right to access, modify, and correct Personal Information about you\n- right: deletion\n  text: You may request deletion of your account or Personal Information by us\n- right: opt-out of communications\n  text: The right to opt-out of our communications to you using \"unsubscribe features\"\n- right: withdraw consent\n  text: Where processing\
  \ of Personal Information about you is based on consent, the right to withdraw your consent\n    to such processing\n- right: complaint to supervisory authority\n  text: The right to lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flightaware/privacy/flightaware-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 19 quoted statements, read from FlightAware's own page on 2026-11-09.
synthetic: false
tags:
- Aviation
- Flights
- Flight Tracking
- Mapping
- Radar
- Satellite
- Traffic Control
---
