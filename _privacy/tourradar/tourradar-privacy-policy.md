---
api_specs:
- filename: tourradar-bookings-api-openapi.yml
  format: yaml
  label: TourRadar Bookings API
  slug: tourradar-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-bookings-api-openapi.yml
- filename: tourradar-bulk-api-openapi.yml
  format: yaml
  label: TourRadar Bulk API
  slug: tourradar-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-bulk-api-openapi.yml
- filename: tourradar-operators-api-openapi.yml
  format: yaml
  label: TourRadar Operators API
  slug: tourradar-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-operators-api-openapi.yml
- filename: tourradar-pricing-availability-api-openapi.yml
  format: yaml
  label: TourRadar Pricing & Availability API
  slug: tourradar-pricing-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-pricing-availability-api-openapi.yml
- filename: tourradar-taxonomy-api-openapi.yml
  format: yaml
  label: TourRadar Taxonomy API
  slug: tourradar-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-taxonomy-api-openapi.yml
- filename: tourradar-tours-api-openapi.yml
  format: yaml
  label: TourRadar Tours API
  slug: tourradar-tours-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourradar/openapi/tourradar-tours-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal data includes your personal details (e.g. name, address, contact details, nationality).
  - category: financial
    text: order / booking data (e.g. payment orders)
  - category: device
    text: Like many platforms, we may also automatically receive general information that is contained in our server log files such as your IP address and cookie information.
  - category: communication
    text: information from your electronic communication with us (e.g. cookies)
  deletion:
    route: Request deletion of user account by contacting us
    text: You may request deletion of your user account by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Order and booking management
    text: The information and data concerning you are necessary for the management of your order / your booking and additional services.
  - purpose: Customer contact and service improvement
    text: We may use Data to customize and improve your user experience on this site and to contact you.
  - purpose: Advertising through third parties
    text: We share personal data with advertising partners, including your email address, as part of the marketing of our services through third parties
  retention:
  - period: null
    scope: Business relationship and legal obligations
    text: TourRadar GmbH processes your personal data for the duration of the entire business relationship (from the initiation, performance until the termination of the contract) and furthermore according to the legal safe-keeping and documentation obligations
  - period: in some cases up to 30 years
    scope: Statutory limitation periods
    text: The statutory limitation periods – in some cases up to 30 years – according to the Austrian General Civil Code (ABGB) must be taken into consideration for the data storage period.
  rights:
  - right: Access, correction, deletion, restriction, objection, portability
    text: you have the right to obtain information regarding your data or to limit its processing or to correct, delete it, the right of objection against processing and the right to data portability
  - right: Withdraw consent
    text: Furthermore you have the right to revoke any consent given at any time with future effect.
  role:
    text: Your data is processed by TourRadar GmbH, Kärntner Ring 5-7 Top 201-203, Vienna 1010, Austria.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We will only share your details with 3rd parties that you expressly consent to being shared with.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your data may therefore be transferred to a party located outside of the EU (a “third country”), if the tour operator you chose resides in a third country and / or the tour takes place in a third country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TourRadar
provenance_date: '2026-11-10'
provider_name: TourRadar
provider_slug: tourradar
slug: tourradar-privacy-policy
source_date: '2026-11-10'
source_filename: tourradar-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tourradar.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TourRadar\naid: tourradar\nurl: https://www.tourradar.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Your data is processed by TourRadar GmbH, Kärntner Ring 5-7 Top 201-203, Vienna 1010, Austria.\ndata_categories:\n- category: identifying\n  text: Personal data includes your personal details (e.g. name, address, contact details, nationality).\n- category: financial\n  text: order / booking data (e.g. payment orders)\n- category: device\n  text: Like many platforms, we may also automatically receive general information that is contained in our server\n    log files such as your\
  \ IP address and cookie information.\n- category: communication\n  text: information from your electronic communication with us (e.g. cookies)\npurposes:\n- purpose: Order and booking management\n  text: The information and data concerning you are necessary for the management of your order / your booking and\n    additional services.\n- purpose: Customer contact and service improvement\n  text: We may use Data to customize and improve your user experience on this site and to contact you.\n- purpose: Advertising through third parties\n  text: We share personal data with advertising partners, including your email address, as part of the marketing\n    of our services through third parties\nretention:\n- scope: Business relationship and legal obligations\n  period: null\n  text: TourRadar GmbH processes your personal data for the duration of the entire business relationship (from the\n    initiation, performance until the termination of the contract) and furthermore according to the legal\
  \ safe-keeping\n    and documentation obligations\n- scope: Statutory limitation periods\n  period: in some cases up to 30 years\n  text: The statutory limitation periods – in some cases up to 30 years – according to the Austrian General Civil\n    Code (ABGB) must be taken into consideration for the data storage period.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your data may therefore be transferred to a party located outside of the EU (a “third country”), if the\n    tour operator you chose resides in a third country and / or the tour takes place in a third country.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of user account by contacting us\n  text: You may request deletion of your user account by contacting us.\nrights:\n- right: Access, correction, deletion, restriction, objection, portability\n  text: you have the right to obtain information regarding your data or to limit its processing\
  \ or to correct, delete\n    it, the right of objection against processing and the right to data portability\n- right: Withdraw consent\n  text: Furthermore you have the right to revoke any consent given at any time with future effect.\nsale_or_sharing:\n  stance: conditional\n  text: We will only share your details with 3rd parties that you expressly consent to being shared with.\n"
source_yaml_url: https://artifacts.apis.io/tourradar/privacy/tourradar-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from TourRadar's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Tours
- Booking
- Marketplace
- Adventure Travel
- Distribution
- Affiliates
---
