---
api_specs:
- filename: wetransform-openapi-generated.yml
  format: yaml
  label: WeTransform API
  slug: wetransform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wetransform/openapi/_ae-authored/wetransform-openapi-generated.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: When visitors leave comments on the site we collect the data shown in the comments form, and also the visitor's IP address and browser user agent string to help spam detection.
  - category: identifying
    text: If you leave a comment on our site you may opt-in to saving your name, email address and website in cookies.
  deletion:
    route: request erasure
    text: You can also request that we erase any personal data we hold about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: spam detection
    text: also the visitor's IP address and browser user agent string to help spam detection
  - purpose: comment convenience
    text: These are for your convenience so that you do not have to fill in your details again when you leave another comment.
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
  - right: access/export
    text: you can request to receive an exported file of the personal data we hold about you, including any data you have provided to us.
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
name: WeTransform
provenance_date: '2026-11-10'
provider_name: WeTransform
provider_slug: wetransform
slug: wetransform-privacy-policy
source_date: '2026-11-10'
source_filename: wetransform-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://wetransform.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WeTransform\naid: wetransform\nurl: https://wetransform.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When visitors leave comments on the site we collect the data shown in the comments form, and also the visitor's\n    IP address and browser user agent string to help spam detection.\n- category: identifying\n  text: If you leave a comment on our site you may opt-in to saving your name, email address and website in cookies.\npurposes:\n- purpose: spam detection\n  text: also the visitor's IP address and browser user agent string\
  \ to help spam detection\n- purpose: comment convenience\n  text: These are for your convenience so that you do not have to fill in your details again when you leave another\n    comment.\nretention:\n- scope: comments\n  period: indefinitely\n  text: If you leave a comment, the comment and its metadata are retained indefinitely.\n- scope: comment cookies\n  period: one year\n  text: These cookies will last for one year.\n- scope: login cookies\n  period: two days\n  text: Login cookies last for two days, and screen options cookies last for a year.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request erasure\n  text: You can also request that we erase any personal data we hold about you.\nrights:\n- right: access/export\n  text: you can request to receive an exported file of the personal data we hold about you, including any data you\n    have provided to us.\n- right: erasure\n  text:\
  \ You can also request that we erase any personal data we hold about you.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wetransform/privacy/wetransform-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 10 quoted statements, read from WeTransform's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- B2B SaaS
- No-Code
- Artificial Intelligence
- Embedded Import
---
