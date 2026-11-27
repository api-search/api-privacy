---
api_specs:
- filename: lyft-concierge-rides-api-openapi.yml
  format: yaml
  label: lyft Concierge Rides API
  slug: lyft-concierge-rides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-concierge-rides-api-openapi.yml
- filename: lyft-cost-estimates-api-openapi.yml
  format: yaml
  label: lyft Cost Estimates API
  slug: lyft-cost-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-cost-estimates-api-openapi.yml
- filename: lyft-drivers-api-openapi.yml
  format: yaml
  label: lyft Drivers API
  slug: lyft-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-drivers-api-openapi.yml
- filename: lyft-eta-api-openapi.yml
  format: yaml
  label: lyft ETA API
  slug: lyft-eta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-eta-api-openapi.yml
- filename: lyft-profile-api-openapi.yml
  format: yaml
  label: lyft Profile API
  slug: lyft-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-profile-api-openapi.yml
- filename: lyft-ride-types-api-openapi.yml
  format: yaml
  label: lyft Ride Types API
  slug: lyft-ride-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-ride-types-api-openapi.yml
- filename: lyft-rides-api-openapi.yml
  format: yaml
  label: lyft Rides API
  slug: lyft-rides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lyft/openapi/lyft-rides-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect the information you provide us, such as your name, email address, phone number, birth date, profile photo, and payment information
  - category: identifying
    text: government identification number (such as social security number), driver's license information (including gender)
  - category: location
    text: This includes approximate and precise location through GPS and WiFi data, IP address, Bluetooth data, and any other location information you choose to share with us.
  - category: behavioral
    text: Cookies, Analytics, and Third-Party Technologies. We collect and use information through the use of "cookies," tracking pixels, data analytics tools like Google Analytics
  - category: financial
    text: We collect the payment information you provide us, including your bank routing numbers and tax information.
  - category: communication
    text: the contents of SMS and chat messages
  - category: device
    text: device model, IP address, type of browser, version of operating system, identity of carrier and manufacturer
  deletion:
    route: Account deletion via the Lyft privacy page link
    text: If you would like to delete your Lyft account, please visit here .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Lyft Platform
    text: Provide the Lyft Platform;
  - purpose: Security and safety
    text: Maintain the security and safety of the Lyft Platform and its users;
  - purpose: Marketing and advertising
    text: Provide marketing and advertising.
  - purpose: Improve the Lyft Platform
    text: Improve the Lyft Platform;
  retention:
  - period: as long as you maintain an account
    scope: Profile information
    text: This means we keep your profile information for as long as you maintain an account.
  - period: at least seven years
    scope: Transactional information
    text: We retain transactional information such as rides and payments for at least seven years
  rights:
  - right: Access personal information
    text: Lyft provides ways for you to access and delete your personal information
  - right: Email unsubscribe
    text: You can always unsubscribe from our commercial or promotional emails by clicking unsubscribe in those messages.
  - right: Opt out of push notifications
    text: You can opt out of receiving push notifications through your device settings.
  - right: Jurisdiction-specific rights
    text: Some states, such as California, Colorado, Connecticut, Delaware, Indiana, Iowa, Kentucky, Maryland, Minnesota, Montana, Nebraska, New Hampshire, New Jersey, Oregon, Rhode Island, Tennessee, Texas, Utah, and Virginia provide specific rights to residents of the state regarding personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information to third parties for money
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lyft
provenance_date: '2026-11-10'
provider_name: Lyft
provider_slug: lyft
slug: lyft-privacy-policy
source_date: '2026-11-10'
source_filename: lyft-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lyft.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lyft\naid: lyft\nurl: https://www.lyft.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect the information you provide us, such as your name, email address, phone number, birth date, profile\n    photo, and payment information\n- category: identifying\n  text: government identification number (such as social security number), driver's license information (including\n    gender)\n- category: location\n  text: This includes approximate and precise location through GPS and WiFi data, IP address, Bluetooth data, and\n   \
  \ any other location information you choose to share with us.\n- category: behavioral\n  text: Cookies, Analytics, and Third-Party Technologies. We collect and use information through the use of \"cookies,\"\n    tracking pixels, data analytics tools like Google Analytics\n- category: financial\n  text: We collect the payment information you provide us, including your bank routing numbers and tax information.\n- category: communication\n  text: the contents of SMS and chat messages\n- category: device\n  text: device model, IP address, type of browser, version of operating system, identity of carrier and manufacturer\npurposes:\n- purpose: Provide the Lyft Platform\n  text: Provide the Lyft Platform;\n- purpose: Security and safety\n  text: Maintain the security and safety of the Lyft Platform and its users;\n- purpose: Marketing and advertising\n  text: Provide marketing and advertising.\n- purpose: Improve the Lyft Platform\n  text: Improve the Lyft Platform;\nretention:\n- scope: Profile\
  \ information\n  period: as long as you maintain an account\n  text: This means we keep your profile information for as long as you maintain an account.\n- scope: Transactional information\n  period: at least seven years\n  text: We retain transactional information such as rides and payments for at least seven years\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion via the Lyft privacy page link\n  text: If you would like to delete your Lyft account, please visit here .\nrights:\n- right: Access personal information\n  text: Lyft provides ways for you to access and delete your personal information\n- right: Email unsubscribe\n  text: You can always unsubscribe from our commercial or promotional emails by clicking unsubscribe in those messages.\n- right: Opt out of push notifications\n  text: You can opt out of receiving push notifications through your device settings.\n- right:\
  \ Jurisdiction-specific rights\n  text: Some states, such as California, Colorado, Connecticut, Delaware, Indiana, Iowa, Kentucky, Maryland, Minnesota,\n    Montana, Nebraska, New Hampshire, New Jersey, Oregon, Rhode Island, Tennessee, Texas, Utah, and Virginia provide\n    specific rights to residents of the state regarding personal information.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information to third parties for money\n"
source_yaml_url: https://artifacts.apis.io/lyft/privacy/lyft-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Lyft's own page on 2026-11-10.
synthetic: false
tags:
- Transportation
- Mobility
- Ride Hailing
- Micromobility
- Bike Share
- Scooters
- GBFS
- Logistics
- Travel
---
