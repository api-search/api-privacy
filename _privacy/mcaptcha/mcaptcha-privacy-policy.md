---
api_specs:
- filename: mcaptcha-openapi.yml
  format: yaml
  label: mCaptcha Guard API
  slug: mcaptcha-guard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcaptcha/openapi/mcaptcha-openapi.yml
claim_count: 5
description: ''
doc:
  data_categories:
  - category: device
    text: Browser . We use this to reproduce browser-specific bugs people see. This is derived from the User-Agent HTTP header.
  - category: behavioral
    text: Page URL . the page URL of each page view on this website.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: debugging
    text: Website activity is logged and stored for a period of one month for debugging purposes.
  retention:
  - period: one month
    scope: website activity logs
    text: Website activity is logged and stored for a period of one month for debugging purposes.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No information is shared with, sent to or sold to third-parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mCaptcha
provenance_date: '2026-11-10'
provider_name: mCaptcha
provider_slug: mcaptcha
slug: mcaptcha-privacy-policy
source_date: '2026-11-10'
source_filename: mcaptcha-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mcaptcha.org/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mCaptcha\naid: mcaptcha\nurl: https://mcaptcha.org/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Browser . We use this to reproduce browser-specific bugs people see. This is derived from the User-Agent\n    HTTP header.\n- category: behavioral\n  text: Page URL . the page URL of each page view on this website.\npurposes:\n- purpose: debugging\n  text: Website activity is logged and stored for a period of one month for debugging purposes.\nretention:\n- scope: website activity logs\n  period: one month\n  text: Website activity\
  \ is logged and stored for a period of one month for debugging purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No information is shared with, sent to or sold to third-parties.\n"
source_yaml_url: https://artifacts.apis.io/mcaptcha/privacy/mcaptcha-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 5 quoted statements, read from mCaptcha's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CAPTCHA
- Privacy
- Open Source
- PoW
- Security
---
