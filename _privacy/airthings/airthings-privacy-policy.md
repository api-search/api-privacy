---
api_specs:
- filename: airthings-accounts-api-openapi.yml
  format: yaml
  label: Airthings Accounts API
  slug: airthings-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-accounts-api-openapi.yml
- filename: airthings-device-api-openapi.yml
  format: yaml
  label: Airthings Device API
  slug: airthings-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-device-api-openapi.yml
- filename: airthings-devices-api-openapi.yml
  format: yaml
  label: Airthings Devices API
  slug: airthings-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-devices-api-openapi.yml
- filename: airthings-health-api-openapi.yml
  format: yaml
  label: Airthings Health API
  slug: airthings-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-health-api-openapi.yml
- filename: airthings-locations-api-openapi.yml
  format: yaml
  label: Airthings Locations API
  slug: airthings-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-locations-api-openapi.yml
- filename: airthings-organizations-api-openapi.yml
  format: yaml
  label: Airthings Organizations API
  slug: airthings-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-organizations-api-openapi.yml
- filename: airthings-segments-api-openapi.yml
  format: yaml
  label: Airthings Segments API
  slug: airthings-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-segments-api-openapi.yml
- filename: airthings-sensor-api-openapi.yml
  format: yaml
  label: Airthings Sensor API
  slug: airthings-sensor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-sensor-api-openapi.yml
- filename: airthings-spaces-api-openapi.yml
  format: yaml
  label: Airthings Spaces API
  slug: airthings-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-spaces-api-openapi.yml
- filename: airthings-thresholds-api-openapi.yml
  format: yaml
  label: Airthings Thresholds API
  slug: airthings-thresholds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-thresholds-api-openapi.yml
- filename: airthings-webhooks-api-openapi.yml
  format: yaml
  label: Airthings Webhooks API
  slug: airthings-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airthings/openapi/airthings-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, e-mail address, username, and password when you setup an account.
  - category: location
    text: where it is located (e.g., the postal code and/or street address and/or general location if location services are enabled on the mobile device for the App)
  - category: device
    text: the IP address, the general location if location services are enabled on the mobile device for the App, and a unique ID for your mobile device.
  - category: behavioral
    text: User behaviour on how the user interacts with our webpages and the Airthings app related to a user ID.
  - category: contact
    text: Name, telephone number, e-mail address and other personal data collected in connection with support enquiries and Service messages.
  - category: professional
    text: CV, applications references and attestations.
  deletion:
    route: Delete your account, or contact support@airthings.com to withdraw consent
    text: Personal data related to your user account, including location data, is retained until you delete your account
  dpa:
    available: null
    text: Airthings uses data processors to collect, store or in other ways process data on our behalf. In such cases we have concluded data processing agreements to ensure the information security in all segments of the data processing.
    url: null
  purposes:
  - purpose: Administration of user account
    text: Administration of your user account.
  - purpose: Support enquiries and service messages
    text: Responding to incoming enquiries and sending Service updates through our support channel and web application feedback channel.
  - purpose: Marketing
    text: Sending out marketing materials, such as newsletters, email and SMS marketing messages, in-App marketing messaging and information regarding our activities.
  - purpose: Recruitment
    text: The recruitment of employment and consulting vacancies and positions.
  - purpose: Product analytics and personalization
    text: The data will be used to provide customer support, for product analytics purposes, to personalize experiences, to enhance services, and to optimize communications.
  retention:
  - period: five years
    scope: User account data
    text: Personal data related to your user account, including location data, is retained until you delete your account, after such time the data is aggregated and may be stored for up to five years.
  - period: 2 years
    scope: Shipment data
    text: Personal data related to shipment of packages is deleted after 2 years of last shipping date
  rights:
  - right: Access
    text: to request information (i.e., the “right to know”) about the processing of your data free of charge, as well as the receipt of a copy of your personal data.
  - right: Correction
    text: to correct your data.
  - right: Deletion or blocking
    text: to delete or block your data.
  - right: Restriction
    text: to restrict the processing
  - right: Objection
    text: to object the processing of your data
  - right: Withdraw consent
    text: to revoke your consent to the processing of your data in the future
  - right: Complain to supervisory authority
    text: to complain to the competent supervisory authority about inadmissible data processing.
  role:
    text: Airthings, will process your personal data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Transfer to third countries will be protected by appropriate safeguards, namely the use of standard data protection clauses adopted or approved by the European Commission.
  - mechanism: DPF
    text: Airthings complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S. DPF, as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Airthings
provenance_date: '2026-11-09'
provider_name: Airthings
provider_slug: airthings
slug: airthings-privacy-policy
source_date: '2026-11-09'
source_filename: airthings-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.airthings.com/legal/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Airthings\naid: airthings\nurl: https://www.airthings.com/legal/privacy-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Airthings, will process your personal data.\ndata_categories:\n- category: identifying\n  text: Your name, e-mail address, username, and password when you setup an account.\n- category: location\n  text: where it is located (e.g., the postal code and/or street address and/or general location if location services\n    are enabled on the mobile device for the App)\n- category: device\n  text: the IP address, the general location if location services are enabled on the\
  \ mobile device for the App,\n    and a unique ID for your mobile device.\n- category: behavioral\n  text: User behaviour on how the user interacts with our webpages and the Airthings app related to a user ID.\n- category: contact\n  text: Name, telephone number, e-mail address and other personal data collected in connection with support enquiries\n    and Service messages.\n- category: professional\n  text: CV, applications references and attestations.\npurposes:\n- purpose: Administration of user account\n  text: Administration of your user account.\n- purpose: Support enquiries and service messages\n  text: Responding to incoming enquiries and sending Service updates through our support channel and web application\n    feedback channel.\n- purpose: Marketing\n  text: Sending out marketing materials, such as newsletters, email and SMS marketing messages, in-App marketing\n    messaging and information regarding our activities.\n- purpose: Recruitment\n  text: The recruitment of employment\
  \ and consulting vacancies and positions.\n- purpose: Product analytics and personalization\n  text: The data will be used to provide customer support, for product analytics purposes, to personalize experiences,\n    to enhance services, and to optimize communications.\nretention:\n- scope: User account data\n  period: five years\n  text: Personal data related to your user account, including location data, is retained until you delete your account,\n    after such time the data is aggregated and may be stored for up to five years.\n- scope: Shipment data\n  period: 2 years\n  text: Personal data related to shipment of packages is deleted after 2 years of last shipping date\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Transfer to third countries will be protected by appropriate safeguards, namely the use of standard data\n    protection clauses adopted or approved by the European Commission.\n- mechanism: DPF\n  text: Airthings complies with the EU-U.S. Data Privacy Framework (EU-U.S.\
  \ DPF) and the UK Extension to the EU-U.S.\n    DPF, as set forth by the U.S. Department of Commerce.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Airthings uses data processors to collect, store or in other ways process data on our behalf. In such cases\n    we have concluded data processing agreements to ensure the information security in all segments of the data\n    processing.\ndeletion:\n  route: Delete your account, or contact support@airthings.com to withdraw consent\n  text: Personal data related to your user account, including location data, is retained until you delete your account\nrights:\n- right: Access\n  text: to request information (i.e., the “right to know”) about the processing of your data free of charge, as\n    well as the receipt of a copy of your personal data.\n- right: Correction\n  text: to correct your data.\n- right: Deletion or blocking\n  text: to delete or block your data.\n- right: Restriction\n  text: to restrict\
  \ the processing\n- right: Objection\n  text: to object the processing of your data\n- right: Withdraw consent\n  text: to revoke your consent to the processing of your data in the future\n- right: Complain to supervisory authority\n  text: to complain to the competent supervisory authority about inadmissible data processing.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airthings/privacy/airthings-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 25 quoted statements, read from Airthings's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Air Quality
- Radon
- Sensors
- IoT
---
