---
api_specs:
- filename: scryfall-bulk-data-api-openapi.yml
  format: yaml
  label: Scryfall Bulk Data API
  slug: scryfall-bulk-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-bulk-data-api-openapi.yml
- filename: scryfall-cards-api-openapi.yml
  format: yaml
  label: Scryfall Cards API
  slug: scryfall-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-cards-api-openapi.yml
- filename: scryfall-catalogs-api-openapi.yml
  format: yaml
  label: Scryfall Catalogs API
  slug: scryfall-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-catalogs-api-openapi.yml
- filename: scryfall-migrations-api-openapi.yml
  format: yaml
  label: Scryfall Migrations API
  slug: scryfall-migrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-migrations-api-openapi.yml
- filename: scryfall-rulings-api-openapi.yml
  format: yaml
  label: Scryfall Rulings API
  slug: scryfall-rulings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-rulings-api-openapi.yml
- filename: scryfall-sets-api-openapi.yml
  format: yaml
  label: Scryfall Sets API
  slug: scryfall-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-sets-api-openapi.yml
- filename: scryfall-symbology-api-openapi.yml
  format: yaml
  label: Scryfall Symbology API
  slug: scryfall-symbology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scryfall/openapi/scryfall-symbology-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: device
    text: Your browser version (Safari, Firefox, Chrome, etc)
  - category: device
    text: Your operating system (macOS, Windows, iPhone, etc)
  - category: location
    text: Your country
  - category: behavioral
    text: we keep track of which buttons and links people click to get around on the site and how often they come back
  - category: identifying
    text: a username and email address
  - category: contact
    text: Your email address is private; we will never share your account email with anyone.
  - category: financial
    text: such as debit or credit card details
  deletion:
    route: account deletion via settings link
    text: You can delete your Scryfall account at any time. If you do, Scryfall will remove all information we have about you, including your account details, your settings, your comments, and your decks.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate Scryfall and provide paid services
    text: Any information we do collect is only used to operate Scryfall, provide paid services, and make informed decisions about how to improve our products.
  - purpose: account services
    text: Scryfall uses this information to provide you with account services and communicate changes made to your account.
  - purpose: troubleshooting bot issues
    text: In order to troubleshoot bot issues, Scryfall administrators are able to see messages sent to our bots for a period of less than 24 hours.
  residency:
  - region: United States
    text: we store account and system data in the United States, using Heroku Postgres
  retention:
  - period: less than 24 hours
    scope: bot messages
    text: Scryfall administrators are able to see messages sent to our bots for a period of less than 24 hours. After this time, Scryfall discards this data and does not permanently store bot messages.
  - period: null
    scope: deleted accounts
    text: once you delete an account, all of that information will be unrecoverable, even by Scryfall administrators.
  rights:
  - right: data export
    text: You can download an archive of your account data at any time in your Scryfall settings.
  - right: account deletion
    text: You can delete your Scryfall account at any time.
  - right: opt-out of Google Analytics
    text: You have the option to opt-out of Google Analytics using their browser extension or any of the available content blocking plugins for your platform.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell or trade this information to any other company.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Scryfall
provenance_date: '2026-11-10'
provider_name: Scryfall
provider_slug: scryfall
slug: scryfall-privacy-policy
source_date: '2026-11-10'
source_filename: scryfall-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scryfall.com/docs/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Scryfall\naid: scryfall\nurl: https://scryfall.com/docs/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Your browser version (Safari, Firefox, Chrome, etc)\n- category: device\n  text: Your operating system (macOS, Windows, iPhone, etc)\n- category: location\n  text: Your country\n- category: behavioral\n  text: we keep track of which buttons and links people click to get around on the site and how often they come\n    back\n- category: identifying\n  text: a username and email address\n- category: contact\n  text: Your email address\
  \ is private; we will never share your account email with anyone.\n- category: financial\n  text: such as debit or credit card details\npurposes:\n- purpose: operate Scryfall and provide paid services\n  text: Any information we do collect is only used to operate Scryfall, provide paid services, and make informed\n    decisions about how to improve our products.\n- purpose: account services\n  text: Scryfall uses this information to provide you with account services and communicate changes made to your\n    account.\n- purpose: troubleshooting bot issues\n  text: In order to troubleshoot bot issues, Scryfall administrators are able to see messages sent to our bots for\n    a period of less than 24 hours.\nretention:\n- scope: bot messages\n  period: less than 24 hours\n  text: Scryfall administrators are able to see messages sent to our bots for a period of less than 24 hours. After\n    this time, Scryfall discards this data and does not permanently store bot messages.\n- scope: deleted\
  \ accounts\n  period: null\n  text: once you delete an account, all of that information will be unrecoverable, even by Scryfall administrators.\nresidency:\n- region: United States\n  text: we store account and system data in the United States, using Heroku Postgres\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion via settings link\n  text: You can delete your Scryfall account at any time. If you do, Scryfall will remove all information we have\n    about you, including your account details, your settings, your comments, and your decks.\nrights:\n- right: data export\n  text: You can download an archive of your account data at any time in your Scryfall settings.\n- right: account deletion\n  text: You can delete your Scryfall account at any time.\n- right: opt-out of Google Analytics\n  text: You have the option to opt-out of Google Analytics using their browser extension or any of the available\n\
  \    content blocking plugins for your platform.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell or trade this information to any other company.\n"
source_yaml_url: https://artifacts.apis.io/scryfall/privacy/scryfall-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Scryfall's own page on 2026-11-10.
synthetic: false
tags:
- Magic The Gathering
- Card Data
- Open Data
- Free
- Community Funded
- Public APIs
- Gaming
- Card Games
---
