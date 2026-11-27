---
api_specs:
- filename: hivemapper-account-api-openapi.yml
  format: yaml
  label: Hivemapper Account API
  slug: hivemapper-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-account-api-openapi.yml
- filename: hivemapper-ai-events-api-openapi.yml
  format: yaml
  label: Hivemapper AI Events API
  slug: hivemapper-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-ai-events-api-openapi.yml
- filename: hivemapper-bursts-api-openapi.yml
  format: yaml
  label: Hivemapper Bursts API
  slug: hivemapper-bursts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-bursts-api-openapi.yml
- filename: hivemapper-imagery-api-openapi.yml
  format: yaml
  label: Hivemapper Imagery API
  slug: hivemapper-imagery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-imagery-api-openapi.yml
- filename: hivemapper-map-features-api-openapi.yml
  format: yaml
  label: Hivemapper Map Features API
  slug: hivemapper-map-features-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-map-features-api-openapi.yml
- filename: hivemapper-devices-api-openapi.yml
  format: yaml
  label: Hivemapper Devices API
  slug: hivemapper-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-devices-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect account information (such as your wallet address and account identifiers) to enable participation and reward distribution.
  - category: location
    text: Geographic position of the Device.
  - category: other
    text: Street-level images and video frames from the Device's cameras.
  - category: device
    text: We collect metadata about your Device's activity (such as routes driven, hexes covered, Work Orders fulfilled)
  - category: device
    text: we may collect standard usage information (such as IP address, browser type, pages viewed)
  deletion:
    route: Account deletion through the Apps
    text: You may request account deletion through the Apps
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Participation and reward distribution
    text: to enable participation and reward distribution
  - purpose: Network operation and fraud detection
    text: to operate the Network protocol, validate fulfillment, detect fraud, and distribute rewards
  - purpose: Website operation and improvement
    text: to operate, maintain, and improve the site
  residency:
  - region: Global
    text: The Network operates globally.
  rights:
  - right: View and update account information
    text: You can view and update account information in the Apps.
  - right: Removal, restriction or access to Contributor Data
    text: To request removal, restriction, or access for Contributor Data your Device produced and that was delivered to a developer, contact Hivemapper.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Developers receiving data through the Network are responsible for ensuring lawful international transfer under applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hivemapper
provenance_date: '2026-11-09'
provider_name: Hivemapper
provider_slug: hivemapper
slug: hivemapper-privacy-policy
source_date: '2026-11-09'
source_filename: hivemapper-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hivemapper.com/privacy/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hivemapper\naid: hivemapper\nurl: https://hivemapper.com/privacy/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect account information (such as your wallet address and account identifiers) to enable participation\n    and reward distribution.\n- category: location\n  text: Geographic position of the Device.\n- category: other\n  text: Street-level images and video frames from the Device's cameras.\n- category: device\n  text: We collect metadata about your Device's activity (such as routes driven, hexes covered,\
  \ Work Orders fulfilled)\n- category: device\n  text: we may collect standard usage information (such as IP address, browser type, pages viewed)\npurposes:\n- purpose: Participation and reward distribution\n  text: to enable participation and reward distribution\n- purpose: Network operation and fraud detection\n  text: to operate the Network protocol, validate fulfillment, detect fraud, and distribute rewards\n- purpose: Website operation and improvement\n  text: to operate, maintain, and improve the site\nretention: []\nresidency:\n- region: Global\n  text: The Network operates globally.\ntransfers:\n- mechanism: other\n  text: Developers receiving data through the Network are responsible for ensuring lawful international transfer\n    under applicable law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion through the Apps\n  text: You may request account deletion through the Apps\nrights:\n- right: View\
  \ and update account information\n  text: You can view and update account information in the Apps.\n- right: Removal, restriction or access to Contributor Data\n  text: To request removal, restriction, or access for Contributor Data your Device produced and that was delivered\n    to a developer, contact Hivemapper.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hivemapper/privacy/hivemapper-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- transfers
- deletion
- rights
summary_line: 13 quoted statements, read from Hivemapper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Mapping
- Geospatial
- Imagery
- Location
- Street View
- Mobility
- Machine Learning
- Web3
---
