---
api_specs:
- filename: dott-discovery-api-openapi.yml
  format: yaml
  label: Dott Discovery API
  slug: dott-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-discovery-api-openapi.yml
- filename: dott-stations-api-openapi.yml
  format: yaml
  label: Dott Stations API
  slug: dott-stations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-stations-api-openapi.yml
- filename: dott-system-api-openapi.yml
  format: yaml
  label: Dott System API
  slug: dott-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-system-api-openapi.yml
- filename: dott-vehicles-api-openapi.yml
  format: yaml
  label: Dott Vehicles API
  slug: dott-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-vehicles-api-openapi.yml
- filename: dott-zones-api-openapi.yml
  format: yaml
  label: Dott Zones API
  slug: dott-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dott/openapi/dott-zones-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: This encompasses your first and last name, username and password, date of birth, and gender (only where required by law)
  - category: contact
    text: we collect your billing and delivery addresses, email addresses, telephone numbers, and other similar identifiers.
  - category: financial
    text: We gather information related to your bank account and payment card details
  - category: location
    text: We collect data on how you use our Vehicles, including ride and geolocation history and telemetry information
  - category: device
    text: This includes the device ID of your mobile device and the details of the pages you visit within the TIER-Dott mobile application.
  - category: behavioral
    text: TIER-Dott collects data about your online activities and information related to your devices.
  - category: biometric
    text: In some jurisdictions, a live selfie may be required.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: These providers are bound by our Data Processing Agreements to handle your information in line with this Privacy Policy and our specific instructions.
    url: null
  purposes:
  - purpose: Customer registration and service delivery
    text: We collect your data to register you as a new customer, deliver our services, and manage payments, fees, and charges.
  - purpose: Data analytics
    text: Your personal data supports our efforts to enhance our Website, App, Vehicles, marketing, and advertising efforts.
  - purpose: Content and advertising personalization
    text: We strive to deliver relevant content and advertisements on our Website and App, including personalized product or service recommendations.
  residency:
  - region: European Union
    text: We consistently store your personal data within the European Union (EU) to ensure its protection under the rigorous standards of the GDPR.
  retention:
  - period: 7 years
    scope: Tax and trip records
    text: Certain types of data, such as trip information or records relevant for tax purposes, are retained for a period of 7 years to comply with legal obligations.
  - period: null
    scope: User accounts
    text: We retain personal data essential for delivering our services for as long as your account remains active.
  rights:
  - right: Access
    text: You are entitled to request an overview of your personal data processed by us, along with a copy of this data
  - right: Rectification
    text: you have the right to request that we correct or update it.
  - right: Object to processing
    text: You may object to the processing of your personal data if you believe our use of it is for our legitimate interests yet unjustifiably impacts you.
  - right: Restrict processing
    text: You can request that we limit the processing of your personal data under specific conditions
  - right: Data portability
    text: This right allows you to obtain your personal data in a structured, commonly used, and machine-readable format
  - right: Erasure
    text: this enables you to request the deletion of your personal data under certain circumstances
  - right: Complain
    text: you have the right to lodge a complaint with the relevant data protection authority
  role:
    text: Tier and Dott will act as joint data controllers pursuant to Article 26 of the GDPR.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 'Applicable Local Laws and Regulations: We evaluate the local legal and regulatory frameworks of the country receiving the data to ensure they provide adequate protection for your personal data.'
  - mechanism: SCC
    text: 'EU Model Clauses: For transfers to countries where the legal framework may not offer equivalent protection, we incorporate EU Model Clauses into our agreements with service providers.'
  - mechanism: adequacy
    text: 'Adequacy Decisions by the European Commission: We also rely on adequacy decisions made by the European Commission'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dott
provenance_date: '2026-11-09'
provider_name: Dott
provider_slug: dott
slug: dott-privacy-policy
source_date: '2026-11-09'
source_filename: dott-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ridedott.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dott\naid: dott\nurl: https://ridedott.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Tier and Dott will act as joint data controllers pursuant to Article 26 of the GDPR.\ndata_categories:\n- category: identifying\n  text: This encompasses your first and last name, username and password, date of birth, and gender (only where\n    required by law)\n- category: contact\n  text: we collect your billing and delivery addresses, email addresses, telephone numbers, and other similar identifiers.\n- category: financial\n  text: We gather information related to your bank account and payment\
  \ card details\n- category: location\n  text: We collect data on how you use our Vehicles, including ride and geolocation history and telemetry information\n- category: device\n  text: This includes the device ID of your mobile device and the details of the pages you visit within the TIER-Dott\n    mobile application.\n- category: behavioral\n  text: TIER-Dott collects data about your online activities and information related to your devices.\n- category: biometric\n  text: In some jurisdictions, a live selfie may be required.\npurposes:\n- purpose: Customer registration and service delivery\n  text: We collect your data to register you as a new customer, deliver our services, and manage payments, fees,\n    and charges.\n- purpose: Data analytics\n  text: Your personal data supports our efforts to enhance our Website, App, Vehicles, marketing, and advertising\n    efforts.\n- purpose: Content and advertising personalization\n  text: We strive to deliver relevant content and advertisements\
  \ on our Website and App, including personalized\n    product or service recommendations.\nretention:\n- scope: Tax and trip records\n  period: 7 years\n  text: Certain types of data, such as trip information or records relevant for tax purposes, are retained for a\n    period of 7 years to comply with legal obligations.\n- scope: User accounts\n  period: null\n  text: We retain personal data essential for delivering our services for as long as your account remains active.\nresidency:\n- region: European Union\n  text: We consistently store your personal data within the European Union (EU) to ensure its protection under the\n    rigorous standards of the GDPR.\ntransfers:\n- mechanism: other\n  text: 'Applicable Local Laws and Regulations: We evaluate the local legal and regulatory frameworks of the country\n    receiving the data to ensure they provide adequate protection for your personal data.'\n- mechanism: SCC\n  text: 'EU Model Clauses: For transfers to countries where the legal\
  \ framework may not offer equivalent protection,\n    we incorporate EU Model Clauses into our agreements with service providers.'\n- mechanism: adequacy\n  text: 'Adequacy Decisions by the European Commission: We also rely on adequacy decisions made by the European\n    Commission'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: These providers are bound by our Data Processing Agreements to handle your information in line with this\n    Privacy Policy and our specific instructions.\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: You are entitled to request an overview of your personal data processed by us, along with a copy of this\n    data\n- right: Rectification\n  text: you have the right to request that we correct or update it.\n- right: Object to processing\n  text: You may object to the processing of your personal data if you believe our use of it is for our legitimate\n    interests yet unjustifiably impacts\
  \ you.\n- right: Restrict processing\n  text: You can request that we limit the processing of your personal data under specific conditions\n- right: Data portability\n  text: This right allows you to obtain your personal data in a structured, commonly used, and machine-readable\n    format\n- right: Erasure\n  text: this enables you to request the deletion of your personal data under certain circumstances\n- right: Complain\n  text: you have the right to lodge a complaint with the relevant data protection authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dott/privacy/dott-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- rights
summary_line: 25 quoted statements, read from Dott's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Micromobility
- Mobility
- E-Scooter
- E-Bikes
- GBFS
- Shared Mobility
- Smart City
- Sustainability
---
