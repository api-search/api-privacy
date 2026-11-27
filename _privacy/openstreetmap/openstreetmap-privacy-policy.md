---
api_specs:
- filename: openstreetmap-capabilities-api-openapi.yml
  format: yaml
  label: OpenStreetMap Capabilities API
  slug: openstreetmap-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-capabilities-api-openapi.yml
- filename: openstreetmap-changesets-api-openapi.yml
  format: yaml
  label: OpenStreetMap Changesets API
  slug: openstreetmap-changesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-changesets-api-openapi.yml
- filename: openstreetmap-map-data-api-openapi.yml
  format: yaml
  label: OpenStreetMap Map Data API
  slug: openstreetmap-map-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-map-data-api-openapi.yml
- filename: openstreetmap-nodes-api-openapi.yml
  format: yaml
  label: OpenStreetMap Nodes API
  slug: openstreetmap-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-nodes-api-openapi.yml
- filename: openstreetmap-notes-api-openapi.yml
  format: yaml
  label: OpenStreetMap Notes API
  slug: openstreetmap-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-notes-api-openapi.yml
- filename: openstreetmap-relations-api-openapi.yml
  format: yaml
  label: OpenStreetMap Relations API
  slug: openstreetmap-relations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-relations-api-openapi.yml
- filename: openstreetmap-users-api-openapi.yml
  format: yaml
  label: OpenStreetMap Users API
  slug: openstreetmap-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-users-api-openapi.yml
- filename: openstreetmap-ways-api-openapi.yml
  format: yaml
  label: OpenStreetMap Ways API
  slug: openstreetmap-ways-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-ways-api-openapi.yml
- filename: openstreetmap-geocoding-api-openapi.yml
  format: yaml
  label: OpenStreetMap Geocoding API
  slug: openstreetmap-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-geocoding-api-openapi.yml
- filename: openstreetmap-status-api-openapi.yml
  format: yaml
  label: OpenStreetMap Status API
  slug: openstreetmap-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openstreetmap/openapi/openstreetmap-status-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: user id and login name of the author of every change to an object
  - category: contact
    text: the e-mail address associated with your account
  - category: location
    text: network access data (example IP addresses) for the systems and services operated by the OSMF
  - category: device
    text: collect information about your browser or application and your interaction with our website, including (a) IP address, (b) browser and device type, (c) operating system
  - category: behavioral
    text: the pages accessed on our websites
  - category: financial
    text: Payment details for both classes of members are retained for accounting purposes as long as required by law.
  deletion:
    route: request account removal via account or OSMF contact
    text: You can request your account to be removed and we will honor such requests as far as possible.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: open data project operation and spam/vandalism prevention
    text: detecting, removing and correcting spam accounts, vandalism, and violations of the rights of third parties
  - purpose: operational support and security
    text: in support of the operation of the services from a technical, security and planning point of view.
  - purpose: legal obligation for membership register
    text: The processing of this data is necessary for compliance with a legal obligation (see GDPR article 6.1c ).
  residency:
  - region: United Kingdom and Netherlands
    text: Personal data other than any associated with a tile request (for instance, IP addresses and request details) is stored in the United Kingdom and the Netherlands.
  - region: EU
    text: Backups are stored in the EU.
  retention:
  - period: 180 days
    scope: automatically collected usage records (Piwik)
    text: detailed usage information is retained for 180 days
  - period: as long as required by law
    scope: OSMF membership payment details
    text: Payment details for both classes of members are retained for accounting purposes as long as required by law.
  rights:
  - right: object to processing
    text: You have a right to object against processing based on legitimate interests of the data controller.
  - right: correct, amend or delete inaccurate information
    text: If you believe that we hold information that would allow us to correct, amend, or delete inaccurate information about you
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Like us, they will never barter, trade, or sell access to your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OpenStreetMap
provenance_date: '2026-11-10'
provider_name: OpenStreetMap
provider_slug: openstreetmap
slug: openstreetmap-privacy-policy
source_date: '2026-11-10'
source_filename: openstreetmap-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://osmfoundation.org/wiki/Privacy_Policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OpenStreetMap\naid: openstreetmap\nurl: https://osmfoundation.org/wiki/Privacy_Policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: user id and login name of the author of every change to an object\n- category: contact\n  text: the e-mail address associated with your account\n- category: location\n  text: network access data (example IP addresses) for the systems and services operated by the OSMF\n- category: device\n  text: collect information about your browser or application and your interaction with our website, including (a)\n  \
  \  IP address, (b) browser and device type, (c) operating system\n- category: behavioral\n  text: the pages accessed on our websites\n- category: financial\n  text: Payment details for both classes of members are retained for accounting purposes as long as required by\n    law.\npurposes:\n- purpose: open data project operation and spam/vandalism prevention\n  text: detecting, removing and correcting spam accounts, vandalism, and violations of the rights of third parties\n- purpose: operational support and security\n  text: in support of the operation of the services from a technical, security and planning point of view.\n- purpose: legal obligation for membership register\n  text: The processing of this data is necessary for compliance with a legal obligation (see GDPR article 6.1c ).\nretention:\n- scope: automatically collected usage records (Piwik)\n  period: 180 days\n  text: detailed usage information is retained for 180 days\n- scope: OSMF membership payment details\n  period: as\
  \ long as required by law\n  text: Payment details for both classes of members are retained for accounting purposes as long as required by\n    law.\nresidency:\n- region: United Kingdom and Netherlands\n  text: Personal data other than any associated with a tile request (for instance, IP addresses and request details)\n    is stored in the United Kingdom and the Netherlands.\n- region: EU\n  text: Backups are stored in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request account removal via account or OSMF contact\n  text: You can request your account to be removed and we will honor such requests as far as possible.\nrights:\n- right: object to processing\n  text: You have a right to object against processing based on legitimate interests of the data controller.\n- right: correct, amend or delete inaccurate information\n  text: If you believe that we hold information that would allow us to correct,\
  \ amend, or delete inaccurate information\n    about you\nsale_or_sharing:\n  stance: prohibited\n  text: Like us, they will never barter, trade, or sell access to your personal data.\n"
source_yaml_url: https://artifacts.apis.io/openstreetmap/privacy/openstreetmap-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from OpenStreetMap's own page on 2026-11-10.
synthetic: false
tags:
- Geospatial
- Mapping
- Open Data
- Geocoding
- Editing
- OpenStreetMap
---
