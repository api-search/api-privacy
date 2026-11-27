---
api_specs:
- filename: sofar-ocean-devices-api-openapi.yml
  format: yaml
  label: Sofar Ocean Devices API
  slug: sofar-ocean-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofar-ocean/openapi/sofar-ocean-devices-api-openapi.yml
- filename: sofar-ocean-smart-mooring-api-openapi.yml
  format: yaml
  label: Sofar Ocean Smart Mooring API
  slug: sofar-ocean-smart-mooring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofar-ocean/openapi/sofar-ocean-smart-mooring-api-openapi.yml
- filename: sofar-ocean-spotter-data-api-openapi.yml
  format: yaml
  label: Sofar Ocean Spotter Data API
  slug: sofar-ocean-spotter-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofar-ocean/openapi/sofar-ocean-spotter-data-api-openapi.yml
- filename: sofar-ocean-wave-spectra-api-openapi.yml
  format: yaml
  label: Sofar Ocean Wave Spectra API
  slug: sofar-ocean-wave-spectra-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofar-ocean/openapi/sofar-ocean-wave-spectra-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Basic user information , such as your name, email address, mobile phone number and organization.
  - category: location
    text: Location information , when you access or use our mobile application(s), website(s), hardware device(s), or otherwise consent to our collection of this information.
  - category: financial
    text: Purchase information, such as your shipping address and point of contact.
  - category: device
    text: 'Device Information: We collect device-specific information when you access our Services, including your hardware model, operating system and version, unique device identifiers, mobile network information'
  - category: behavioral
    text: 'Log Information: We collect log information about how you access or use our Services, including your access times, time zone, browser type and language.'
  - category: communication
    text: Other information that you provide to us directly or through your interaction with our services , such as pictures, messages, or other information and content.
  deletion:
    route: Email request to support@sofarocean.com to remove account
    text: To remove your account, send us a request support@sofarocean.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and improve services
    text: Operate and improve our Services;
  - purpose: Create other products or services
    text: Create other products or services;
  - purpose: Customer service
    text: Respond to your comments, questions and requests and provide customer service;
  - purpose: Analytics of usage
    text: Monitor and analyze trends, usage and activities in connection with ourServices;
  retention:
  - period: null
    scope: Account removal
    text: Please note that even after you remove your account, we may retain certain information as required by law, for legitimate business purposes and to protect member safety.
  rights:
  - right: Update or correct information
    text: You may update or correct information about you at any time by logging into your account and editing your profile.
  - right: Withdraw location consent
    text: You have the ability to turn of location-based services by adjusting the settings on your web browser or mobile devices, or powering off your hardware devices.
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
    text: By accessing or using the Services, you consent to the processing and transfer of information in and to the United States and other countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sofar Ocean
provenance_date: '2026-11-10'
provider_name: Sofar Ocean
provider_slug: sofar-ocean
slug: sofar-ocean-privacy-policy
source_date: '2026-11-10'
source_filename: sofar-ocean-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sofarocean.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sofar Ocean\naid: sofar-ocean\nurl: https://www.sofarocean.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Basic user information , such as your name, email address, mobile phone number and organization.\n- category: location\n  text: Location information , when you access or use our mobile application(s), website(s), hardware device(s),\n    or otherwise consent to our collection of this information.\n- category: financial\n  text: Purchase information, such as your shipping address and point of contact.\n- category:\
  \ device\n  text: 'Device Information: We collect device-specific information when you access our Services, including your\n    hardware model, operating system and version, unique device identifiers, mobile network information'\n- category: behavioral\n  text: 'Log Information: We collect log information about how you access or use our Services, including your access\n    times, time zone, browser type and language.'\n- category: communication\n  text: Other information that you provide to us directly or through your interaction with our services , such as\n    pictures, messages, or other information and content.\npurposes:\n- purpose: Operate and improve services\n  text: Operate and improve our Services;\n- purpose: Create other products or services\n  text: Create other products or services;\n- purpose: Customer service\n  text: Respond to your comments, questions and requests and provide customer service;\n- purpose: Analytics of usage\n  text: Monitor and analyze trends, usage and\
  \ activities in connection with ourServices;\nretention:\n- scope: Account removal\n  period: null\n  text: Please note that even after you remove your account, we may retain certain information as required by law,\n    for legitimate business purposes and to protect member safety.\nresidency: []\ntransfers:\n- mechanism: other\n  text: By accessing or using the Services, you consent to the processing and transfer of information in and to\n    the United States and other countries.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to support@sofarocean.com to remove account\n  text: To remove your account, send us a request support@sofarocean.com.\nrights:\n- right: Update or correct information\n  text: You may update or correct information about you at any time by logging into your account and editing your\n    profile.\n- right: Withdraw location consent\n  text: You have the ability to turn of location-based\
  \ services by adjusting the settings on your web browser or\n    mobile devices, or powering off your hardware devices.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sofar-ocean/privacy/sofar-ocean-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 15 quoted statements, read from Sofar Ocean's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Climate
- Ocean Data
- Weather
- Maritime
- Sensors
- IoT
- Environmental Data
- Wave Data
- Buoys
---
