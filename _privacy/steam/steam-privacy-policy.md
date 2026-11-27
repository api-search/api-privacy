---
api_specs:
- filename: steam-iplayerservice-api-openapi.yml
  format: yaml
  label: Steam IPlayerService API
  slug: steam-iplayerservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steam/openapi/steam-iplayerservice-api-openapi.yml
- filename: steam-isteamnews-api-openapi.yml
  format: yaml
  label: Steam ISteamNews API
  slug: steam-isteamnews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steam/openapi/steam-isteamnews-api-openapi.yml
- filename: steam-isteamuser-api-openapi.yml
  format: yaml
  label: Steam ISteamUser API
  slug: steam-isteamuser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steam/openapi/steam-isteamuser-api-openapi.yml
- filename: steam-isteamuserstats-api-openapi.yml
  format: yaml
  label: Steam ISteamUserStats API
  slug: steam-isteamuserstats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steam/openapi/steam-isteamuserstats-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: When setting up an Account, Valve will collect your email address and country of residence.
  - category: financial
    text: If you pay by credit card, you need to provide typical credit card information (name, address, credit card number, expiration date and security code) to Valve
  - category: behavioral
    text: we will track your process across our websites and applications to verify that you are not a bot and to optimize our services.
  - category: device
    text: information about the device you are using, including what operating system you are using, device settings, unique device identifiers, and crash data
  - category: location
    text: our servers log your IP address
  - category: communication
    text: Information sent through chat;
  deletion:
    route: Steam support page account deletion request
    text: You can also request the deletion of your Steam user account via the Steam support page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the gaming service
    text: where it is necessary for the performance of our agreement with you to provide a full-featured gaming service and deliver associated Content and Services
  - purpose: Content recommendations and marketing
    text: We may process information collected under this section 3 so that content, products and services shown on the pages of the Steam store and in update messages displayed when launching the Steam Client can be tailored to meet your needs
  - purpose: Fraud and violation detection
    text: We collect certain data that is required for our detection, investigation and prevention of fraud, cheating and other violations of the SSA and applicable laws
  retention:
  - period: up to ten (10) years
    scope: Transactional data
    text: Valve is required to retain certain transactional data under statutory commercial and tax law for a period of up to ten (10) years.
  - period: 30 (thirty) days
    scope: Deleted account grace period
    text: We allow you to restore your Steam User Account during a grace period of 30 (thirty) days from the moment you request deletion of your Steam User Account.
  rights:
  - right: Access
    text: Right of Access. You have the right to access your Personal Data that we hold about you
  - right: Rectification
    text: Right to Rectification. If we process your Personal Data, we shall endeavor to ensure by implementing suitable measures that your Personal Data is accurate and up-to-date
  - right: Erasure
    text: Right to Erasure. You have the right to obtain deletion of Personal Data concerning you
  - right: Object
    text: Right to Object. When our processing of your Personal Data is based on legitimate interests
  - right: Restriction
    text: Right to restriction of processing of your Personal Data
  - right: Portability
    text: Right to Personal Data portability
  role:
    text: Valve collects and processes Personal Data for the following reasons
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Valve does not sell Personal Data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Valve and its subsidiary TR Technical Inc. comply with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)
  - mechanism: SCC
    text: The use of Standard Contractual Clauses in their version in force and approved by the European Commission and the UK ICO to safeguard transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Steam
provenance_date: '2026-11-10'
provider_name: Steam
provider_slug: steam
slug: steam-privacy-policy
source_date: '2026-11-10'
source_filename: steam-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://store.steampowered.com/privacy_agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Steam\naid: steam\nurl: https://store.steampowered.com/privacy_agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Valve collects and processes Personal Data for the following reasons\ndata_categories:\n- category: contact\n  text: When setting up an Account, Valve will collect your email address and country of residence.\n- category: financial\n  text: If you pay by credit card, you need to provide typical credit card information (name, address, credit card\n    number, expiration date and security code) to Valve\n- category: behavioral\n  text: we will track your process across our\
  \ websites and applications to verify that you are not a bot and to\n    optimize our services.\n- category: device\n  text: information about the device you are using, including what operating system you are using, device settings,\n    unique device identifiers, and crash data\n- category: location\n  text: our servers log your IP address\n- category: communication\n  text: Information sent through chat;\npurposes:\n- purpose: Providing the gaming service\n  text: where it is necessary for the performance of our agreement with you to provide a full-featured gaming service\n    and deliver associated Content and Services\n- purpose: Content recommendations and marketing\n  text: We may process information collected under this section 3 so that content, products and services shown on\n    the pages of the Steam store and in update messages displayed when launching the Steam Client can be tailored\n    to meet your needs\n- purpose: Fraud and violation detection\n  text: We collect certain\
  \ data that is required for our detection, investigation and prevention of fraud, cheating\n    and other violations of the SSA and applicable laws\nretention:\n- scope: Transactional data\n  period: up to ten (10) years\n  text: Valve is required to retain certain transactional data under statutory commercial and tax law for a period\n    of up to ten (10) years.\n- scope: Deleted account grace period\n  period: 30 (thirty) days\n  text: We allow you to restore your Steam User Account during a grace period of 30 (thirty) days from the moment\n    you request deletion of your Steam User Account.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Valve and its subsidiary TR Technical Inc. comply with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)\n- mechanism: SCC\n  text: The use of Standard Contractual Clauses in their version in force and approved by the European Commission\n    and the UK ICO to safeguard transfers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Steam support page account deletion request\n  text: You can also request the deletion of your Steam user account via the Steam support page.\nrights:\n- right: Access\n  text: Right of Access. You have the right to access your Personal Data that we hold about you\n- right: Rectification\n  text: Right to Rectification. If we process your Personal Data, we shall endeavor to ensure by implementing suitable\n    measures that your Personal Data is accurate and up-to-date\n- right: Erasure\n  text: Right to Erasure. You have the right to obtain deletion of Personal Data concerning you\n- right: Object\n  text: Right to Object. When our processing of your Personal Data is based on legitimate interests\n- right: Restriction\n  text: Right to restriction of processing of your Personal Data\n- right: Portability\n  text: Right to Personal Data portability\nsale_or_sharing:\n  stance: prohibited\n  text: Valve does not sell Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/steam/privacy/steam-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Steam's own page on 2026-11-10.
synthetic: false
tags:
- Gaming
- Valve
- Distribution
- Steamworks
- Marketplace
- Web API
- Steam
- Video Games
---
