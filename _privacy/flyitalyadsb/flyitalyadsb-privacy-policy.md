---
api_specs:
- filename: flyitalyadsb-live-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Live API
  slug: flyitalyadsb-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-live-api-openapi.yml
- filename: flyitalyadsb-account-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Account API
  slug: flyitalyadsb-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-account-api-openapi.yml
- filename: flyitalyadsb-events-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Events API
  slug: flyitalyadsb-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-events-api-openapi.yml
- filename: flyitalyadsb-flights-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Flights API
  slug: flyitalyadsb-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-flights-api-openapi.yml
- filename: flyitalyadsb-history-api-openapi.yml
  format: yaml
  label: FlyItalyADSB History API
  slug: flyitalyadsb-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-history-api-openapi.yml
- filename: flyitalyadsb-keys-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Keys API
  slug: flyitalyadsb-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-keys-api-openapi.yml
- filename: flyitalyadsb-live-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Live API
  slug: flyitalyadsb-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-live-api-openapi.yml
- filename: flyitalyadsb-watch-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Watch API
  slug: flyitalyadsb-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-watch-api-openapi.yml
- filename: flyitalyadsb-webhooks-api-openapi.yml
  format: yaml
  label: FlyItalyADSB Webhooks API
  slug: flyitalyadsb-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flyitalyadsb/openapi/flyitalyadsb-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address
  - category: financial
    text: the name or company name, billing address, country and VAT number, to issue and keep the invoice
  - category: location
    text: approximate location derived from the IP address
  - category: device
    text: device and browser type
  - category: behavioral
    text: pages visited, clicks, where you came from (referring site and campaign parameters)
  - category: identifying
    text: IP address, date and time, requested path and user agent
  deletion:
    route: delete saved position via My API or the assistant
    text: You can delete the saved position at any time from My API or by asking the assistant.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: no advertising or sale
    text: We do not use your data for advertising and we do not sell it.
  - purpose: providing the service
    text: 'Providing the service you ask for (key, plan, My API , service emails): performance of a contract, GDPR art. 6(1)(b).'
  - purpose: site and service statistics
    text: 'Statistics on the site, the map and the use of the service, including the analytics cookie, visit recordings and linking to your email: legitimate interest in understanding how they are used and improving them, art. 6(1)(f)'
  residency:
  - region: European Union (PostHog)
    text: PostHog Inc. (statistics on the site, the map and the use of the service, and visit recordings, with the data hosted in the European Union)
  retention:
  - period: 15 minutes
    scope: sign-in links and sessions
    text: My API sign-in links are valid for 15 minutes, sessions for 2 hours.
  - period: 90 days
    scope: visit recordings
    text: 'Site and service statistics: visit recordings for 90 days'
  - period: null
    scope: key data
    text: A key's data and usage for as long as the key is active or the subscription runs, and then for as long as needed to handle any disputes and legal obligations.
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: You can ask for access, rectification, erasure, restriction and portability, and object to processing based on legitimate interest
  - right: complaint to authority
    text: You also have the right to lodge a complaint with the Italian data protection authority
  role:
    text: Data controller Nesso Labs S.r.l., Via Carlo Cattaneo 3, 25121 Brescia (BS), Italy, VAT IT04754860981
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not use your data for advertising and we do not sell it.
  subprocessors:
    text: Cloudflare (content delivery, attack protection, cookieless aggregate site statistics)
    url: null
  transfers:
  - mechanism: SCC
    text: Some of these providers also process data outside the European Union, with the safeguards the GDPR requires (standard contractual clauses or an adequacy decision).
  - mechanism: adequacy
    text: Some of these providers also process data outside the European Union, with the safeguards the GDPR requires (standard contractual clauses or an adequacy decision).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FlyItalyADSB
provenance_date: '2026-11-09'
provider_name: FlyItalyADSB
provider_slug: flyitalyadsb
slug: flyitalyadsb-privacy-policy
source_date: '2026-11-09'
source_filename: flyitalyadsb-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flyitalyadsb.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FlyItalyADSB\naid: flyitalyadsb\nurl: https://flyitalyadsb.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data controller Nesso Labs S.r.l., Via Carlo Cattaneo 3, 25121 Brescia (BS), Italy, VAT IT04754860981\ndata_categories:\n- category: contact\n  text: your email address\n- category: financial\n  text: the name or company name, billing address, country and VAT number, to issue and keep the invoice\n- category: location\n  text: approximate location derived from the IP address\n- category: device\n  text: device and browser type\n- category: behavioral\n  text: pages visited,\
  \ clicks, where you came from (referring site and campaign parameters)\n- category: identifying\n  text: IP address, date and time, requested path and user agent\npurposes:\n- purpose: no advertising or sale\n  text: We do not use your data for advertising and we do not sell it.\n- purpose: providing the service\n  text: 'Providing the service you ask for (key, plan, My API , service emails): performance of a contract, GDPR\n    art. 6(1)(b).'\n- purpose: site and service statistics\n  text: 'Statistics on the site, the map and the use of the service, including the analytics cookie, visit recordings\n    and linking to your email: legitimate interest in understanding how they are used and improving them, art. 6(1)(f)'\nretention:\n- scope: sign-in links and sessions\n  period: 15 minutes\n  text: My API sign-in links are valid for 15 minutes, sessions for 2 hours.\n- scope: visit recordings\n  period: 90 days\n  text: 'Site and service statistics: visit recordings for 90 days'\n- scope:\
  \ key data\n  period: null\n  text: A key's data and usage for as long as the key is active or the subscription runs, and then for as long as\n    needed to handle any disputes and legal obligations.\nresidency:\n- region: European Union (PostHog)\n  text: PostHog Inc. (statistics on the site, the map and the use of the service, and visit recordings, with the\n    data hosted in the European Union)\ntransfers:\n- mechanism: SCC\n  text: Some of these providers also process data outside the European Union, with the safeguards the GDPR requires\n    (standard contractual clauses or an adequacy decision).\n- mechanism: adequacy\n  text: Some of these providers also process data outside the European Union, with the safeguards the GDPR requires\n    (standard contractual clauses or an adequacy decision).\nsubprocessors:\n  url: null\n  text: Cloudflare (content delivery, attack protection, cookieless aggregate site statistics)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: delete saved position via My API or the assistant\n  text: You can delete the saved position at any time from My API or by asking the assistant.\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: You can ask for access, rectification, erasure, restriction and portability, and object to processing based\n    on legitimate interest\n- right: complaint to authority\n  text: You also have the right to lodge a complaint with the Italian data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use your data for advertising and we do not sell it.\n"
source_yaml_url: https://artifacts.apis.io/flyitalyadsb/privacy/flyitalyadsb-privacy-policy.yml
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
- sale_or_sharing
summary_line: 21 quoted statements, read from FlyItalyADSB's own page on 2026-11-09.
synthetic: false
tags:
- ADS-B
- MLAT
- Aviation
- Flight Tracking
- Open Data
---
