---
api_specs:
- filename: adsbiq-com-aircraft-api-openapi.yml
  format: yaml
  label: adsbiq-com Aircraft API
  slug: adsbiq-com-aircraft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-aircraft-api-openapi.yml
- filename: adsbiq-com-airports-api-openapi.yml
  format: yaml
  label: adsbiq-com Airports API
  slug: adsbiq-com-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-airports-api-openapi.yml
- filename: adsbiq-com-flights-api-openapi.yml
  format: yaml
  label: adsbiq-com Flights API
  slug: adsbiq-com-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-flights-api-openapi.yml
- filename: adsbiq-com-geographic-api-openapi.yml
  format: yaml
  label: adsbiq-com Geographic API
  slug: adsbiq-com-geographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-geographic-api-openapi.yml
- filename: adsbiq-com-network-api-openapi.yml
  format: yaml
  label: adsbiq-com Network API
  slug: adsbiq-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsbiq-com/openapi/adsbiq-com-network-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name or alias (optional; defaults to your device hostname if not provided)
  - category: identifying
    text: IP addresses (IPv4 and/or IPv6, recorded at registration and updated via periodic heartbeat signals)
  - category: contact
    text: Email address (optional; used for account communication only — we do not require email for any functionality)
  - category: location
    text: Receiver location (latitude, longitude, altitude) for MLAT calculations and coverage mapping
  - category: behavioral
    text: Connection metadata (last seen timestamp, message rates, aircraft counts, positions contributed)
  deletion:
    route: Delete My Data button on feeder dashboard, or email request
    text: Use the "Delete My Data" button on your feeder dashboard to instantly and permanently erase your feeder registration, personal data, watchlist, and alert history.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate network
    text: Aggregate ADS-B data from feeders, perform MLAT calculations, serve data via API and live map.
  - purpose: security
    text: Detect abuse, enforce rate limits, and protect the network from unauthorized access.
  - purpose: feeder communication
    text: Send setup instructions, service updates, or respond to support requests (only if you provided an email).
  residency:
  - region: United States
    text: Our servers are located in the United States.
  retention:
  - period: 90 days
    scope: feeder accounts
    text: Retained while your feeder is active and for 90 days after disconnection.
  - period: 90 days
    scope: feeder statistics
    text: are kept in our live database for 90 days
  - period: no more than 90 days
    scope: server logs
    text: Logs are retained for no more than 90 days.
  - period: indefinitely
    scope: historical ADS-B position archives
    text: Historical position archives are retained in Parquet format indefinitely for research and analysis.
  rights:
  - right: access
    text: You may request a copy of the personal data we hold about you by contacting [email protected] .
  - right: correction
    text: You may request corrections to inaccurate personal data.
  - right: portability and complaint (EU/EEA)
    text: 'For EU/EEA residents: You have additional rights under the GDPR, including the right to data portability and the right to lodge a complaint with your local data protection authority.'
  role:
    text: Sky Power Services LLC , a Florida limited liability company (the "Data Controller").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: We use standard hosting infrastructure (AWS, Cloudflare) which may process data on our behalf under their respective privacy policies.
    url: null
  transfers:
  - mechanism: other
    text: By running the feeder install script and registering your receiver, you explicitly consent to the transfer of your data to the United States
  - mechanism: DPF
    text: We rely on adequacy decisions and data transfer frameworks adopted by the European Commission, including the EU-US Data Privacy Framework, where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: adsbiq-com
provenance_date: '2026-11-09'
provider_name: adsbiq-com
provider_slug: adsbiq-com
slug: adsbiq-com-privacy-policy
source_date: '2026-11-09'
source_filename: adsbiq-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adsbiq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: adsbiq-com\naid: adsbiq-com\nurl: https://adsbiq.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Sky Power Services LLC , a Florida limited liability company (the \"Data Controller\").\ndata_categories:\n- category: identifying\n  text: Name or alias (optional; defaults to your device hostname if not provided)\n- category: identifying\n  text: IP addresses (IPv4 and/or IPv6, recorded at registration and updated via periodic heartbeat signals)\n- category: contact\n  text: Email address (optional; used for account communication only — we do not require email for any functionality)\n\
  - category: location\n  text: Receiver location (latitude, longitude, altitude) for MLAT calculations and coverage mapping\n- category: behavioral\n  text: Connection metadata (last seen timestamp, message rates, aircraft counts, positions contributed)\npurposes:\n- purpose: operate network\n  text: Aggregate ADS-B data from feeders, perform MLAT calculations, serve data via API and live map.\n- purpose: security\n  text: Detect abuse, enforce rate limits, and protect the network from unauthorized access.\n- purpose: feeder communication\n  text: Send setup instructions, service updates, or respond to support requests (only if you provided an email).\nretention:\n- scope: feeder accounts\n  period: 90 days\n  text: Retained while your feeder is active and for 90 days after disconnection.\n- scope: feeder statistics\n  period: 90 days\n  text: are kept in our live database for 90 days\n- scope: server logs\n  period: no more than 90 days\n  text: Logs are retained for no more than 90 days.\n\
  - scope: historical ADS-B position archives\n  period: indefinitely\n  text: Historical position archives are retained in Parquet format indefinitely for research and analysis.\nresidency:\n- region: United States\n  text: Our servers are located in the United States.\ntransfers:\n- mechanism: other\n  text: By running the feeder install script and registering your receiver, you explicitly consent to the transfer\n    of your data to the United States\n- mechanism: DPF\n  text: We rely on adequacy decisions and data transfer frameworks adopted by the European Commission, including\n    the EU-US Data Privacy Framework, where applicable.\nsubprocessors:\n  url: null\n  text: We use standard hosting infrastructure (AWS, Cloudflare) which may process data on our behalf under their\n    respective privacy policies.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete My Data button on feeder dashboard, or email request\n  text: Use the \"Delete My Data\" button on\
  \ your feeder dashboard to instantly and permanently erase your feeder\n    registration, personal data, watchlist, and alert history.\nrights:\n- right: access\n  text: You may request a copy of the personal data we hold about you by contacting [email protected] .\n- right: correction\n  text: You may request corrections to inaccurate personal data.\n- right: portability and complaint (EU/EEA)\n  text: 'For EU/EEA residents: You have additional rights under the GDPR, including the right to data portability\n    and the right to lodge a complaint with your local data protection authority.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/adsbiq-com/privacy/adsbiq-com-privacy-policy.yml
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
summary_line: 22 quoted statements, read from adsbiq-com's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Data Analytics
- Marketing Technology
- Company
---
