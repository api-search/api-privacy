---
api_specs:
- filename: tinyplates-dev-health-api-openapi.yml
  format: yaml
  label: tinyplates-dev Health API
  slug: tinyplates-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-health-api-openapi.yml
- filename: tinyplates-dev-ingredients-api-openapi.yml
  format: yaml
  label: tinyplates-dev Ingredients API
  slug: tinyplates-dev-ingredients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-ingredients-api-openapi.yml
- filename: tinyplates-dev-pantry-api-openapi.yml
  format: yaml
  label: tinyplates-dev Pantry API
  slug: tinyplates-dev-pantry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-pantry-api-openapi.yml
- filename: tinyplates-dev-popular-api-openapi.yml
  format: yaml
  label: tinyplates-dev Popular API
  slug: tinyplates-dev-popular-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-popular-api-openapi.yml
- filename: tinyplates-dev-recipes-api-openapi.yml
  format: yaml
  label: tinyplates-dev Recipes API
  slug: tinyplates-dev-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-recipes-api-openapi.yml
- filename: tinyplates-dev-root-api-openapi.yml
  format: yaml
  label: tinyplates-dev Root API
  slug: tinyplates-dev-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-root-api-openapi.yml
- filename: tinyplates-dev-search-api-openapi.yml
  format: yaml
  label: tinyplates-dev Search API
  slug: tinyplates-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-search-api-openapi.yml
- filename: tinyplates-dev-shoppinglist-api-openapi.yml
  format: yaml
  label: tinyplates-dev Shopping List API
  slug: tinyplates-dev-shoppinglist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-shoppinglist-api-openapi.yml
- filename: tinyplates-dev-status-api-openapi.yml
  format: yaml
  label: tinyplates-dev Status API
  slug: tinyplates-dev-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-status-api-openapi.yml
- filename: tinyplates-dev-substitutions-api-openapi.yml
  format: yaml
  label: tinyplates-dev Substitutions API
  slug: tinyplates-dev-substitutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-substitutions-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, your email address, and a hash of your password.
  - category: behavioral
    text: On the website it also records which pages you moved between
  - category: device
    text: your browser and its language
  - category: location
    text: approximate location information
  - category: communication
    text: the details of any error
  deletion:
    route: Write to chris@pullpanda.io
    text: to have your account and everything attached to it deleted, write to chris@pullpanda.io
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: performance monitoring
    text: We use Guvnor, a monitoring service, to find out which requests are slow and which are failing.
  - purpose: site usage analytics
    text: we use Google Analytics to understand which pages people visit and how they use the site.
  - purpose: rate limiting the markup checker
    text: to limit how often the tool runs
  - purpose: ad performance measurement
    text: so we can see whether our ads lead to sign-ups
  retention:
  - period: as long as you have one
    scope: account
    text: We keep your account for as long as you have one, and usage counts for 30 days.
  - period: 30 days
    scope: usage counts
    text: usage counts for 30 days
  - period: up to two hours
    scope: IP address hash
    text: A hash of your IP address for up to two hours, to limit how often the tool runs.
  rights:
  - right: access a copy of your data
    text: To get a copy of your data
  - right: withdraw analytics consent
    text: You can withdraw consent through the cookie choices below
  - right: revoke API keys
    text: You can revoke any API key yourself from your dashboard
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Nobody buys it and nobody is sold it.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tinyplates-dev
provenance_date: '2026-11-10'
provider_name: tinyplates-dev
provider_slug: tinyplates-dev
slug: tinyplates-dev-privacy-policy
source_date: '2026-11-10'
source_filename: tinyplates-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tinyplates.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tinyplates-dev\naid: tinyplates-dev\nurl: https://www.tinyplates.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name, your email address, and a hash of your password.\n- category: behavioral\n  text: On the website it also records which pages you moved between\n- category: device\n  text: your browser and its language\n- category: location\n  text: approximate location information\n- category: communication\n  text: the details of any error\npurposes:\n- purpose: performance monitoring\n  text: We use Guvnor, a monitoring\
  \ service, to find out which requests are slow and which are failing.\n- purpose: site usage analytics\n  text: we use Google Analytics to understand which pages people visit and how they use the site.\n- purpose: rate limiting the markup checker\n  text: to limit how often the tool runs\n- purpose: ad performance measurement\n  text: so we can see whether our ads lead to sign-ups\nretention:\n- scope: account\n  period: as long as you have one\n  text: We keep your account for as long as you have one, and usage counts for 30 days.\n- scope: usage counts\n  period: 30 days\n  text: usage counts for 30 days\n- scope: IP address hash\n  period: up to two hours\n  text: A hash of your IP address for up to two hours, to limit how often the tool runs.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to chris@pullpanda.io\n  text: to have your account and everything attached to it deleted,\
  \ write to chris@pullpanda.io\nrights:\n- right: access a copy of your data\n  text: To get a copy of your data\n- right: withdraw analytics consent\n  text: You can withdraw consent through the cookie choices below\n- right: revoke API keys\n  text: You can revoke any API key yourself from your dashboard\nsale_or_sharing:\n  stance: prohibited\n  text: Nobody buys it and nobody is sold it.\n"
source_yaml_url: https://artifacts.apis.io/tinyplates-dev/privacy/tinyplates-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from tinyplates-dev's own page on 2026-11-10.
synthetic: false
tags:
- Food
- Recipes
- Search
- Developers
---
