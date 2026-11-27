---
api_specs:
- filename: acuris-geo-com-account-api-openapi.yml
  format: yaml
  label: acuris-geo-com Account API
  slug: acuris-geo-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-account-api-openapi.yml
- filename: acuris-geo-com-billing-api-openapi.yml
  format: yaml
  label: acuris-geo-com Billing API
  slug: acuris-geo-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-billing-api-openapi.yml
- filename: acuris-geo-com-config-api-openapi.yml
  format: yaml
  label: acuris-geo-com Config API
  slug: acuris-geo-com-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-config-api-openapi.yml
- filename: acuris-geo-com-geocoding-api-openapi.yml
  format: yaml
  label: acuris-geo-com Geocoding API
  slug: acuris-geo-com-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-geocoding-api-openapi.yml
- filename: acuris-geo-com-postcode-lookup-api-openapi.yml
  format: yaml
  label: acuris-geo-com Postcode lookup API
  slug: acuris-geo-com-postcode-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-postcode-lookup-api-openapi.yml
- filename: acuris-geo-com-suggest-api-openapi.yml
  format: yaml
  label: acuris-geo-com Suggest API
  slug: acuris-geo-com-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-suggest-api-openapi.yml
- filename: acuris-geo-com-validation-api-openapi.yml
  format: yaml
  label: acuris-geo-com Validation API
  slug: acuris-geo-com-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-validation-api-openapi.yml
- filename: acuris-geo-com-versioned-aliases-v1-api-openapi.yml
  format: yaml
  label: acuris-geo-com Versioned aliases (v1) API
  slug: acuris-geo-com-versioned-aliases-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-versioned-aliases-v1-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: contact
    text: When visitors leave comments on the site we collect the data shown in the comments form
  - category: device
    text: the visitor’s IP address and browser user agent string to help spam detection
  - category: identifying
    text: An anonymized string created from your email address (also called a hash) may be provided to the Gravatar service
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
  retention:
  - period: indefinitely
    scope: comments
    text: If you leave a comment, the comment and its metadata are retained indefinitely.
  - period: one year
    scope: comment cookies
    text: These cookies will last for one year.
  - period: two days
    scope: login cookies
    text: Login cookies last for two days, and screen options cookies last for a year.
  rights:
  - right: access / export
    text: you can request to receive an exported file of the personal data we hold about you
  - right: erasure
    text: You can also request that we erase any personal data we hold about you.
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
name: acuris-geo-com
provenance_date: '2026-11-09'
provider_name: acuris-geo-com
provider_slug: acuris-geo-com
slug: acuris-geo-com-privacy-policy
source_date: '2026-11-09'
source_filename: acuris-geo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.acuris-geo.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: acuris-geo-com\naid: acuris-geo-com\nurl: https://www.acuris-geo.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When visitors leave comments on the site we collect the data shown in the comments form\n- category: device\n  text: the visitor’s IP address and browser user agent string to help spam detection\n- category: identifying\n  text: An anonymized string created from your email address (also called a hash) may be provided to the Gravatar\n    service\npurposes:\n- purpose: spam detection\n  text: the visitor’s IP address\
  \ and browser user agent string to help spam detection\n- purpose: recognize follow-up comments\n  text: This is so we can recognize and approve any follow-up comments automatically instead of holding them in\n    a moderation queue.\nretention:\n- scope: comments\n  period: indefinitely\n  text: If you leave a comment, the comment and its metadata are retained indefinitely.\n- scope: comment cookies\n  period: one year\n  text: These cookies will last for one year.\n- scope: login cookies\n  period: two days\n  text: Login cookies last for two days, and screen options cookies last for a year.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request erasure of personal data\n  text: You can also request that we erase any personal data we hold about you.\nrights:\n- right: access / export\n  text: you can request to receive an exported file of the personal data we hold about you\n- right: erasure\n\
  \  text: You can also request that we erase any personal data we hold about you.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acuris-geo-com/privacy/acuris-geo-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from acuris-geo-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geocoding
- Address Validation
- Location Data
---
