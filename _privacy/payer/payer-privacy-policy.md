---
api_specs:
- filename: payer-openapi-generated.yml
  format: yaml
  label: Payer API
  slug: payer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/_ae-authored/payer-openapi-generated.yml
- filename: payer-all-api-openapi.yml
  format: yaml
  label: Payer All API
  slug: payer-all-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-all-api-openapi.yml
- filename: payer-audit-api-openapi.yml
  format: yaml
  label: Payer Audit API
  slug: payer-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-audit-api-openapi.yml
- filename: payer-changelog-api-openapi.yml
  format: yaml
  label: Payer Changelog API
  slug: payer-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-changelog-api-openapi.yml
- filename: payer-documentation-api-openapi.yml
  format: yaml
  label: Payer Documentation API
  slug: payer-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-documentation-api-openapi.yml
- filename: payer-events-api-openapi.yml
  format: yaml
  label: Payer Events API
  slug: payer-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-events-api-openapi.yml
- filename: payer-export-api-openapi.yml
  format: yaml
  label: Payer Export API
  slug: payer-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-export-api-openapi.yml
- filename: payer-invoices-api-openapi.yml
  format: yaml
  label: Payer Invoices API
  slug: payer-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-invoices-api-openapi.yml
- filename: payer-oauth2-api-openapi.yml
  format: yaml
  label: Payer Oauth2 API
  slug: payer-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-oauth2-api-openapi.yml
- filename: payer-orders-api-openapi.yml
  format: yaml
  label: Payer Orders API
  slug: payer-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-orders-api-openapi.yml
- filename: payer-page-api-openapi.yml
  format: yaml
  label: Payer Page API
  slug: payer-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-page-api-openapi.yml
- filename: payer-payer-api-api-openapi.yml
  format: yaml
  label: Payer Payer API
  slug: payer-payer-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-payer-api-api-openapi.yml
- filename: payer-reader-access-api-openapi.yml
  format: yaml
  label: Payer Reader Access API
  slug: payer-reader-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-reader-access-api-openapi.yml
- filename: payer-reference-api-openapi.yml
  format: yaml
  label: Payer Reference API
  slug: payer-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-reference-api-openapi.yml
- filename: payer-search-api-openapi.yml
  format: yaml
  label: Payer Search API
  slug: payer-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-search-api-openapi.yml
- filename: payer-users-api-openapi.yml
  format: yaml
  label: Payer Users API
  slug: payer-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-users-api-openapi.yml
- filename: payer-version-api-openapi.yml
  format: yaml
  label: Payer Version API
  slug: payer-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payer/openapi/payer-version-api-openapi.yml
claim_count: 6
description: ''
doc:
  data_categories:
  - category: contact
    text: When visitors leave comments on the site we collect the data shown in the comments form, and also the visitor’s IP address and browser user agent string to help spam detection.
  deletion:
    route: user profile
    text: All users can see, edit, or delete their personal information at any time (except they cannot change their username).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: spam detection
    text: also the visitor’s IP address and browser user agent string to help spam detection.
  retention:
  - period: indefinitely
    scope: comments
    text: If you leave a comment, the comment and its metadata are retained indefinitely.
  rights:
  - right: access/export
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
name: Payer
provenance_date: '2026-11-10'
provider_name: Payer
provider_slug: payer
slug: payer-privacy-policy
source_date: '2026-11-10'
source_filename: payer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://payer.eu/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Payer\naid: payer\nurl: https://payer.eu/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When visitors leave comments on the site we collect the data shown in the comments form, and also the visitor’s\n    IP address and browser user agent string to help spam detection.\npurposes:\n- purpose: spam detection\n  text: also the visitor’s IP address and browser user agent string to help spam detection.\nretention:\n- scope: comments\n  period: indefinitely\n  text: If you leave a comment, the comment and its metadata are retained\
  \ indefinitely.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: user profile\n  text: All users can see, edit, or delete their personal information at any time (except they cannot change their\n    username).\nrights:\n- right: access/export\n  text: you can request to receive an exported file of the personal data we hold about you\n- right: erasure\n  text: You can also request that we erase any personal data we hold about you.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/payer/privacy/payer-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 6 quoted statements, read from Payer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- B2B
- Fintech
- Automation
---
