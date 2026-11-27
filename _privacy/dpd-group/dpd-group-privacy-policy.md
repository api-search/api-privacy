---
api_specs:
- filename: dpd-group-countries-api-openapi.yml
  format: yaml
  label: DPD Geo Countries API
  slug: geoapi-countries
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-countries-api-openapi.yml
- filename: dpd-group-customers-api-openapi.yml
  format: yaml
  label: DPD Geo Customers API
  slug: geoapi-customers
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-customers-api-openapi.yml
- filename: dpd-group-me-api-openapi.yml
  format: yaml
  label: DPD Geo Me API
  slug: geoapi-me
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-me-api-openapi.yml
- filename: dpd-group-parcels-api-openapi.yml
  format: yaml
  label: DPD Geo Parcels API
  slug: geoapi-parcels
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-parcels-api-openapi.yml
- filename: dpd-group-pickup-orders-api-openapi.yml
  format: yaml
  label: DPD Geo Pickup Orders API
  slug: geoapi-pickup-orders
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-pickup-orders-api-openapi.yml
- filename: dpd-group-shipments-api-openapi.yml
  format: yaml
  label: DPD Geo Shipments API
  slug: geoapi-shipments
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-shipments-api-openapi.yml
- filename: dpd-group-shipping-services-api-openapi.yml
  format: yaml
  label: DPD Geo Shipping Services API
  slug: geoapi-shipping-services
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-shipping-services-api-openapi.yml
- filename: dpd-group-shipping-api-openapi.yml
  format: yaml
  label: DPD META-API Shipment
  slug: meta-api-shipping
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dpd-group/openapi/dpd-group-shipping-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Sender and receiver data, when is Consumer only: Name, e-mail, address, phone number, parcel number'
  - category: location
    text: Postal address (House number, street name, city, Post code, Country code, Longitude, Latitude) will be kept for 3 years
  - category: location
    text: address (including home GPS coordinates), phone number, parcel number, date of birth
  - category: financial
    text: COD amount, POD
  - category: device
    text: IP address, content of the parcels associated to value of goods
  - category: demographic
    text: login, gender, delivery preferences
  - category: other
    text: Faces License plates
  deletion:
    route: request
    text: Data can also be deleted in advance upon request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Parcel delivery and tracking
    text: Shipment and labeling process - Track and trace by Geopost employees
  - purpose: Customs process
    text: Notification management and payment for duties and taxes - Generation of proofs of payment
  - purpose: Embargo screening
    text: Comparison of personal data against Denied Party Lists (DPLs) published by organizations
  - purpose: Marketing and profiling
    text: Display of advertising, newsletters, personalized campaign
  - purpose: Whistleblowing alerts
    text: Receiving and recording whistleblowing alerts
  residency:
  - region: European Union
    text: Geopost carries out all Personal Data processing activities within the European Union (EU).
  retention:
  - period: 30 days
    scope: Geocheck embargo data
    text: 30 days in live/production database
  - period: 6 months after case closure
    scope: Customer service claims
    text: 6 months after case closure database and 6 months in archive database (not anonymized)
  - period: 2 years
    scope: Authenticated consignee data
    text: 2 years following last connection
  - period: six (6) months
    scope: Chatbot conversations
    text: The data collected in the context of a conversation about the delivery of a package is kept for six (6) months, i.e. the life of a package, after which it is automatically deleted.
  - period: 3 years
    scope: Business prospects
    text: The data are kept for a period of 3 years from the last contact with the data subjects when it comes to prospects.
  - period: 12 months
    scope: Partner barometer
    text: 12 months (until next update)
  rights:
  - right: Access
    text: 'Right of access: you may obtain a copy of your Personal Data being processed by Geopost;'
  - right: Rectification
    text: 'Right to rectification: you may update your Personal Data or ask us to rectify your Personal Data processed by Geopost;'
  - right: Objection
    text: Right to object , in particular to prevent direct marketing
  - right: Erasure
    text: 'Right to erasure: you may ask Geopost to delete your Personal Data;'
  - right: Restriction
    text: 'Right to restrict processing: you may ask Geopost to suspend the processing of your Personal Data;'
  - right: Portability
    text: 'Right to data portability: you may ask Geopost to retrieve your Personal Data for reuse.'
  role:
    text: Geopost determines, jointly with its subsidiaries located on the territory of the European Union or in a country recognised as adequate by the European Commission, the purposes and means of the processing.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: mainly by requiring them to sign the European Commission’s standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DPD Group
provenance_date: '2026-11-09'
provider_name: DPD Group
provider_slug: dpd-group
slug: dpd-group-privacy-policy
source_date: '2026-11-09'
source_filename: dpd-group-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.geopost.com/en/data-privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DPD Group\naid: dpd-group\nurl: https://www.geopost.com/en/data-privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Geopost determines, jointly with its subsidiaries located on the territory of the European Union or in a\n    country recognised as adequate by the European Commission, the purposes and means of the processing.\ndata_categories:\n- category: contact\n  text: 'Sender and receiver data, when is Consumer only: Name, e-mail, address, phone number, parcel number'\n- category: location\n  text: Postal address (House number, street name, city, Post code, Country code, Longitude,\
  \ Latitude) will be kept\n    for 3 years\n- category: location\n  text: address (including home GPS coordinates), phone number, parcel number, date of birth\n- category: financial\n  text: COD amount, POD\n- category: device\n  text: IP address, content of the parcels associated to value of goods\n- category: demographic\n  text: login, gender, delivery preferences\n- category: other\n  text: Faces License plates\npurposes:\n- purpose: Parcel delivery and tracking\n  text: Shipment and labeling process - Track and trace by Geopost employees\n- purpose: Customs process\n  text: Notification management and payment for duties and taxes - Generation of proofs of payment\n- purpose: Embargo screening\n  text: Comparison of personal data against Denied Party Lists (DPLs) published by organizations\n- purpose: Marketing and profiling\n  text: Display of advertising, newsletters, personalized campaign\n- purpose: Whistleblowing alerts\n  text: Receiving and recording whistleblowing alerts\nretention:\n\
  - scope: Geocheck embargo data\n  period: 30 days\n  text: 30 days in live/production database\n- scope: Customer service claims\n  period: 6 months after case closure\n  text: 6 months after case closure database and 6 months in archive database (not anonymized)\n- scope: Authenticated consignee data\n  period: 2 years\n  text: 2 years following last connection\n- scope: Chatbot conversations\n  period: six (6) months\n  text: The data collected in the context of a conversation about the delivery of a package is kept for six (6)\n    months, i.e. the life of a package, after which it is automatically deleted.\n- scope: Business prospects\n  period: 3 years\n  text: The data are kept for a period of 3 years from the last contact with the data subjects when it comes to\n    prospects.\n- scope: Partner barometer\n  period: 12 months\n  text: 12 months (until next update)\nresidency:\n- region: European Union\n  text: Geopost carries out all Personal Data processing activities within the\
  \ European Union (EU).\ntransfers:\n- mechanism: SCC\n  text: mainly by requiring them to sign the European Commission’s standard contractual clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request\n  text: Data can also be deleted in advance upon request.\nrights:\n- right: Access\n  text: 'Right of access: you may obtain a copy of your Personal Data being processed by Geopost;'\n- right: Rectification\n  text: 'Right to rectification: you may update your Personal Data or ask us to rectify your Personal Data processed\n    by Geopost;'\n- right: Objection\n  text: Right to object , in particular to prevent direct marketing\n- right: Erasure\n  text: 'Right to erasure: you may ask Geopost to delete your Personal Data;'\n- right: Restriction\n  text: 'Right to restrict processing: you may ask Geopost to suspend the processing of your Personal Data;'\n- right: Portability\n  text: 'Right to data portability: you\
  \ may ask Geopost to retrieve your Personal Data for reuse.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dpd-group/privacy/dpd-group-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 28 quoted statements, read from DPD Group's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- Parcel
- Shipping
- Tracking
- Carrier
---
