---
api_specs:
- filename: bloq-auth-api-openapi.yml
  format: yaml
  label: Bloq Auth API
  slug: bloq-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-auth-api-openapi.yml
- filename: bloq-bloq-api-api-openapi.yml
  format: yaml
  label: Bloq Bloq API
  slug: bloq-bloq-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-bloq-api-api-openapi.yml
- filename: bloq-chains-api-openapi.yml
  format: yaml
  label: Bloq Chains API
  slug: bloq-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-chains-api-openapi.yml
- filename: bloq-logs-api-openapi.yml
  format: yaml
  label: Bloq Logs API
  slug: bloq-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-logs-api-openapi.yml
- filename: bloq-staking-api-openapi.yml
  format: yaml
  label: Bloq Staking API
  slug: bloq-staking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-staking-api-openapi.yml
- filename: bloq-status-api-openapi.yml
  format: yaml
  label: Bloq Status API
  slug: bloq-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-status-api-openapi.yml
- filename: bloq-users-api-openapi.yml
  format: yaml
  label: Bloq Users API
  slug: bloq-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-users-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: device
    text: the visitor’s IP address and browser user agent string to help spam detection
  - category: identifying
    text: An anonymized string created from your email address (also called a hash) may be provided to the Gravatar service
  - category: identifying
    text: we collect the data shown in the comments form
  deletion:
    route: request erasure of personal data
    text: You can also request that we erase any personal data we hold about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: spam detection
    text: the visitor’s IP address and browser user agent string to help spam detection
  - purpose: recognize follow-up comments
    text: This is so we can recognize and approve any follow-up comments automatically instead of holding them in a moderation queue.
  - purpose: login and display preferences
    text: When you log in, we will also set up several cookies to save your login information and your screen display choices.
  retention:
  - period: indefinitely
    scope: comments and metadata
    text: If you leave a comment, the comment and its metadata are retained indefinitely.
  - period: one year
    scope: comment name, email and website cookies
    text: These cookies will last for one year.
  - period: two days
    scope: login cookies
    text: Login cookies last for two days, and screen options cookies last for a year.
  - period: 1 day
    scope: post edit cookie
    text: It expires after 1 day.
  rights:
  - right: access / data export
    text: you can request to receive an exported file of the personal data we hold about you
  - right: erasure
    text: You can also request that we erase any personal data we hold about you.
  - right: view, edit or delete profile data
    text: All users can see, edit, or delete their personal information at any time (except they cannot change their username).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bloq
provenance_date: '2026-11-09'
provider_name: Bloq
provider_slug: bloq
slug: bloq-privacy-policy
source_date: '2026-11-09'
source_filename: bloq-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bloq.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bloq\naid: bloq\nurl: https://bloq.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: the visitor’s IP address and browser user agent string to help spam detection\n- category: identifying\n  text: An anonymized string created from your email address (also called a hash) may be provided to the Gravatar\n    service\n- category: identifying\n  text: we collect the data shown in the comments form\npurposes:\n- purpose: spam detection\n  text: the visitor’s IP address and browser user agent string to help spam detection\n- purpose:\
  \ recognize follow-up comments\n  text: This is so we can recognize and approve any follow-up comments automatically instead of holding them in\n    a moderation queue.\n- purpose: login and display preferences\n  text: When you log in, we will also set up several cookies to save your login information and your screen display\n    choices.\nretention:\n- scope: comments and metadata\n  period: indefinitely\n  text: If you leave a comment, the comment and its metadata are retained indefinitely.\n- scope: comment name, email and website cookies\n  period: one year\n  text: These cookies will last for one year.\n- scope: login cookies\n  period: two days\n  text: Login cookies last for two days, and screen options cookies last for a year.\n- scope: post edit cookie\n  period: 1 day\n  text: It expires after 1 day.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request erasure of personal data\n\
  \  text: You can also request that we erase any personal data we hold about you.\nrights:\n- right: access / data export\n  text: you can request to receive an exported file of the personal data we hold about you\n- right: erasure\n  text: You can also request that we erase any personal data we hold about you.\n- right: view, edit or delete profile data\n  text: All users can see, edit, or delete their personal information at any time (except they cannot change their\n    username).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bloq/privacy/bloq-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from Bloq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- Infrastructure
- DeFi
- Blockchain
---
