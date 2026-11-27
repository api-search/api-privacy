---
api_specs:
- filename: bitfinder-air-data-api-openapi.yml
  format: yaml
  label: Bitfinder Air Data API
  slug: bitfinder-air-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitfinder/openapi/bitfinder-air-data-api-openapi.yml
- filename: bitfinder-devices-api-openapi.yml
  format: yaml
  label: Bitfinder Devices API
  slug: bitfinder-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitfinder/openapi/bitfinder-devices-api-openapi.yml
- filename: bitfinder-user-api-openapi.yml
  format: yaml
  label: Bitfinder User API
  slug: bitfinder-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitfinder/openapi/bitfinder-user-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your name, email address or billing information
  - category: location
    text: the physical location of your device will be collected
  - category: behavioral
    text: Your inputs and interactions with the Mobile App and site are recorded as you use and interact with the Mobile App and site.
  - category: device
    text: we record technical information such as your Awair device’s model and serial number or software version
  - category: financial
    text: such as your address and credit card information
  - category: other
    text: current temperature, humidity, VOC level, CO2 level, and dust level in the room
  deletion:
    route: email to privacy@getawair.com or hello@getawair.com
    text: They may request deletion of their account at hello@getawair.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: order processing
    text: In order to process and ship orders, Awair will require the collection of Personal Data
  - purpose: service improvement and troubleshooting
    text: In order to improve your experience over time and help troubleshoot any problem you may encounter with any Awair Services
  - purpose: personalized ads
    text: some sharing of personal information necessary to provide you with personalized ads may be considered a “sale,”
  residency:
  - region: United States and other countries where servers reside
    text: Your personal information may be collected, processed and stored by Awair or its service providers in the United States and other countries where our servers reside.
  retention:
  - period: for as long as you remain a Awair customer
    scope: personal information in account
    text: Awair generally stores your personal information on Awair’s servers until you delete or edit it, or for as long as you remain a Awair customer in order to provide you with Awair Services.
  - period: null
    scope: backup copies
    text: backup copies may linger for some time before they are deleted
  rights:
  - right: access to information collected
    text: They may request information about the specific information collected about them
  - right: deletion
    text: Delete their personal information
  - right: portability
    text: Provide a copy of their personal information in a readily usable format
  - right: opt out of sale
    text: Opt consumers that ask out of sales of their personal information (if any)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: If you provide your consent, then we may also share this data with or sell this data to third parties.
  subprocessors:
    text: We will use sub processors that handle personal data, including our data center partners
    url: null
  transfers:
  - mechanism: other
    text: Where we are transferring data outside of the EU, Awair commits to having the appropriate data transfer mechanisms in place as required by GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bitfinder
provenance_date: '2026-11-09'
provider_name: Bitfinder
provider_slug: bitfinder
slug: bitfinder-privacy-policy
source_date: '2026-11-09'
source_filename: bitfinder-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://getawair.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bitfinder\naid: bitfinder\nurl: https://getawair.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: such as your name, email address or billing information\n- category: location\n  text: the physical location of your device will be collected\n- category: behavioral\n  text: Your inputs and interactions with the Mobile App and site are recorded as you use and interact with the\n    Mobile App and site.\n- category: device\n  text: we record technical information such as your Awair device’s model and serial\
  \ number or software version\n- category: financial\n  text: such as your address and credit card information\n- category: other\n  text: current temperature, humidity, VOC level, CO2 level, and dust level in the room\npurposes:\n- purpose: order processing\n  text: In order to process and ship orders, Awair will require the collection of Personal Data\n- purpose: service improvement and troubleshooting\n  text: In order to improve your experience over time and help troubleshoot any problem you may encounter with any\n    Awair Services\n- purpose: personalized ads\n  text: some sharing of personal information necessary to provide you with personalized ads may be considered a\n    “sale,”\nretention:\n- scope: personal information in account\n  period: for as long as you remain a Awair customer\n  text: Awair generally stores your personal information on Awair’s servers until you delete or edit it, or for\n    as long as you remain a Awair customer in order to provide you with Awair Services.\n\
  - scope: backup copies\n  period: null\n  text: backup copies may linger for some time before they are deleted\nresidency:\n- region: United States and other countries where servers reside\n  text: Your personal information may be collected, processed and stored by Awair or its service providers in the\n    United States and other countries where our servers reside.\ntransfers:\n- mechanism: other\n  text: Where we are transferring data outside of the EU, Awair commits to having the appropriate data transfer\n    mechanisms in place as required by GDPR.\nsubprocessors:\n  url: null\n  text: We will use sub processors that handle personal data, including our data center partners\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to privacy@getawair.com or hello@getawair.com\n  text: They may request deletion of their account at hello@getawair.com.\nrights:\n- right: access to information collected\n  text: They may request information about the specific information\
  \ collected about them\n- right: deletion\n  text: Delete their personal information\n- right: portability\n  text: Provide a copy of their personal information in a readily usable format\n- right: opt out of sale\n  text: Opt consumers that ask out of sales of their personal information (if any)\nsale_or_sharing:\n  stance: conditional\n  text: If you provide your consent, then we may also share this data with or sell this data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/bitfinder/privacy/bitfinder-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Bitfinder's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Air Quality
- IoT
- Environmental Monitoring
- Smart Home
- Sensors
- Health
- Developer API
---
