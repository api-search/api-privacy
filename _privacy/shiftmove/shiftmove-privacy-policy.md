---
api_specs:
- filename: shiftmove-custom-fields-api-openapi.yml
  format: yaml
  label: Shiftmove Custom fields API
  slug: shiftmove-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-custom-fields-api-openapi.yml
- filename: shiftmove-driver-assignments-api-openapi.yml
  format: yaml
  label: Shiftmove Driver assignments API
  slug: shiftmove-driver-assignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-driver-assignments-api-openapi.yml
- filename: shiftmove-drivers-api-openapi.yml
  format: yaml
  label: Shiftmove Drivers API
  slug: shiftmove-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-drivers-api-openapi.yml
- filename: shiftmove-invoices-api-openapi.yml
  format: yaml
  label: Shiftmove Invoices API
  slug: shiftmove-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-invoices-api-openapi.yml
- filename: shiftmove-organizations-api-openapi.yml
  format: yaml
  label: Shiftmove Organizations API
  slug: shiftmove-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-organizations-api-openapi.yml
- filename: shiftmove-vehicle-assignments-api-openapi.yml
  format: yaml
  label: Shiftmove Vehicle assignments API
  slug: shiftmove-vehicle-assignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-vehicle-assignments-api-openapi.yml
- filename: shiftmove-vehicle-financing-api-openapi.yml
  format: yaml
  label: Shiftmove Vehicle financing API
  slug: shiftmove-vehicle-financing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-vehicle-financing-api-openapi.yml
- filename: shiftmove-vehicle-license-plates-api-openapi.yml
  format: yaml
  label: Shiftmove Vehicle license plates API
  slug: shiftmove-vehicle-license-plates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-vehicle-license-plates-api-openapi.yml
- filename: shiftmove-vehicle-usages-api-openapi.yml
  format: yaml
  label: Shiftmove Vehicle usages API
  slug: shiftmove-vehicle-usages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-vehicle-usages-api-openapi.yml
- filename: shiftmove-vehicles-api-openapi.yml
  format: yaml
  label: Shiftmove Vehicles API
  slug: shiftmove-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shiftmove/openapi/shiftmove-vehicles-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name, last name Email address, telephone number, mobile phone number Logbook data Position data during the tour
  - category: location
    text: GPS location data (approx. 20-second interval) with time and date, voltage data for the OBD connector (or box), vehicle identification number (VIN), classification as business or private trip.
  - category: device
    text: Operating system and current IP address (last octet truncated) of the device you use to visit our website
  - category: behavioral
    text: Behavioral and interaction data (e.g., pages visited, clicks, navigation paths)
  - category: communication
    text: Audio recordings of your voice Transcriptions of your spoken request Phone number and connection metadata Information you provide during the call
  - category: financial
    text: Fuel card information (provider, costs, date, product)
  deletion:
    route: Contact privacy@shiftmove.com or the contact details provided; for SaaS data, instruction by controller
    text: To exercise your rights as a data subject, please contact us using the contact details provided at privacy@shiftmove.com .
  dpa:
    available: true
    text: We have concluded a data processing agreement with Zendesk using the EU standard contractual clauses.
    url: null
  purposes:
  - purpose: Provision of the application
    text: 'Shiftmove will regularly process the following data as part of the provision of the application: personal master data, communication data, device data, and IT usage data.'
  - purpose: Product analytics and debugging
    text: The goal is to identify errors, improve user-friendliness, and diagnose technical problems by collecting session and behavior data as well as performance metrics.
  - purpose: Website analytics
    text: We use the web analytics service Plausible Analytics ("Plausible") to continuously optimize our offering, both technically and in terms of content.
  residency:
  - region: EU
    text: Your data is processed in a European data center and anonymized 24 hours after collection.
  - region: EU
    text: All data processed by the AI callbot is stored and processed in data centers within the EU.
  retention:
  - period: 30 days
    scope: Order-processed data after contract termination
    text: Shiftmove will delete the processed data no later than 30 days after termination of the contract or upon instruction by the controller.
  - period: 15 years
    scope: Logbook data and raw data
    text: Please note that logbook data and all raw data required for this purpose will be stored for up to 15 years in accordance with current legal retention requirements.
  - period: 14 months
    scope: Google Analytics data
    text: The personal data processed by Google Analytics is stored for 14 months and then automatically deleted.
  - period: 30 days
    scope: Session recordings (Datadog)
    text: Session recordings are stored for up to 30 days and then automatically deleted.
  - period: 36 months
    scope: Raw personal data (Planhat, Datadog)
    text: The personal raw data will be deleted after 36 months at the latest.
  rights:
  - right: access
    text: You have the right to request confirmation as to whether we process personal data concerning you.
  - right: rectification
    text: the right to rectification (Art. 16 GDPR)
  - right: restriction
    text: the right to restriction of processing (Art. 18 GDPR)
  - right: erasure
    text: the right to erasure (Art. 17 GDPR)
  - right: portability
    text: the right to data portability (Art. 20 GDPR)
  - right: objection
    text: the right to object to processing (Art. 21 GDPR)
  - right: withdraw consent
    text: If the processing is based on your consent, you have the right to withdraw this consent at any time (Art. 7 (3) GDPR)
  - right: complaint
    text: you have the right to lodge a complaint with a competent supervisory authority at any time
  role:
    text: Shiftmove provides products as a processor. A processor is someone who processes data for third-party purposes in accordance with the instructions of the controller.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'The recipients of data processing in the context of providing the Avrios application as processors are listed in full on the following page: https://www.shiftmove.com/legal/legal-overviewsubprocessors .'
    url: https://www.shiftmove.com/legal/legal-overviewsubprocessors
  transfers:
  - mechanism: SCC
    text: We have therefore concluded a data processing agreement with Salesforce in accordance with the EU standard contractual clauses.
  - mechanism: DPF
    text: In addition, Salesforce is certified under the EU-US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Shiftmove
provenance_date: '2026-11-10'
provider_name: Shiftmove
provider_slug: shiftmove
slug: shiftmove-privacy-policy
source_date: '2026-11-10'
source_filename: shiftmove-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.shiftmove.com/legal/datenschutzerklarung
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Shiftmove\naid: shiftmove\nurl: https://www.shiftmove.com/legal/datenschutzerklarung\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: Shiftmove provides products as a processor. A processor is someone who processes data for third-party purposes\n    in accordance with the instructions of the controller.\ndata_categories:\n- category: identifying\n  text: First name, last name Email address, telephone number, mobile phone number Logbook data Position data during\n    the tour\n- category: location\n  text: GPS location data (approx. 20-second interval) with time and date, voltage\
  \ data for the OBD connector (or\n    box), vehicle identification number (VIN), classification as business or private trip.\n- category: device\n  text: Operating system and current IP address (last octet truncated) of the device you use to visit our website\n- category: behavioral\n  text: Behavioral and interaction data (e.g., pages visited, clicks, navigation paths)\n- category: communication\n  text: Audio recordings of your voice Transcriptions of your spoken request Phone number and connection metadata\n    Information you provide during the call\n- category: financial\n  text: Fuel card information (provider, costs, date, product)\npurposes:\n- purpose: Provision of the application\n  text: 'Shiftmove will regularly process the following data as part of the provision of the application: personal\n    master data, communication data, device data, and IT usage data.'\n- purpose: Product analytics and debugging\n  text: The goal is to identify errors, improve user-friendliness, and\
  \ diagnose technical problems by collecting\n    session and behavior data as well as performance metrics.\n- purpose: Website analytics\n  text: We use the web analytics service Plausible Analytics (\"Plausible\") to continuously optimize our offering,\n    both technically and in terms of content.\nretention:\n- scope: Order-processed data after contract termination\n  period: 30 days\n  text: Shiftmove will delete the processed data no later than 30 days after termination of the contract or upon\n    instruction by the controller.\n- scope: Logbook data and raw data\n  period: 15 years\n  text: Please note that logbook data and all raw data required for this purpose will be stored for up to 15 years\n    in accordance with current legal retention requirements.\n- scope: Google Analytics data\n  period: 14 months\n  text: The personal data processed by Google Analytics is stored for 14 months and then automatically deleted.\n- scope: Session recordings (Datadog)\n  period: 30 days\n\
  \  text: Session recordings are stored for up to 30 days and then automatically deleted.\n- scope: Raw personal data (Planhat, Datadog)\n  period: 36 months\n  text: The personal raw data will be deleted after 36 months at the latest.\nresidency:\n- region: EU\n  text: Your data is processed in a European data center and anonymized 24 hours after collection.\n- region: EU\n  text: All data processed by the AI callbot is stored and processed in data centers within the EU.\ntransfers:\n- mechanism: SCC\n  text: We have therefore concluded a data processing agreement with Salesforce in accordance with the EU standard\n    contractual clauses.\n- mechanism: DPF\n  text: In addition, Salesforce is certified under the EU-US Data Privacy Framework.\nsubprocessors:\n  url: https://www.shiftmove.com/legal/legal-overviewsubprocessors\n  text: 'The recipients of data processing in the context of providing the Avrios application as processors are\n    listed in full on the following page: https://www.shiftmove.com/legal/legal-overviewsubprocessors\
  \ .'\ndpa:\n  available: true\n  url: null\n  text: We have concluded a data processing agreement with Zendesk using the EU standard contractual clauses.\ndeletion:\n  route: Contact privacy@shiftmove.com or the contact details provided; for SaaS data, instruction by controller\n  text: To exercise your rights as a data subject, please contact us using the contact details provided at privacy@shiftmove.com\n    .\nrights:\n- right: access\n  text: You have the right to request confirmation as to whether we process personal data concerning you.\n- right: rectification\n  text: the right to rectification (Art. 16 GDPR)\n- right: restriction\n  text: the right to restriction of processing (Art. 18 GDPR)\n- right: erasure\n  text: the right to erasure (Art. 17 GDPR)\n- right: portability\n  text: the right to data portability (Art. 20 GDPR)\n- right: objection\n  text: the right to object to processing (Art. 21 GDPR)\n- right: withdraw consent\n  text: If the processing is based on your consent,\
  \ you have the right to withdraw this consent at any time (Art.\n    7 (3) GDPR)\n- right: complaint\n  text: you have the right to lodge a complaint with a competent supervisory authority at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shiftmove/privacy/shiftmove-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 30 quoted statements, read from Shiftmove's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fleet Management
- Mobility
- Automotive
- Telematics
- Vehicles
- Fleet API
- Software-as-a-Service
---
