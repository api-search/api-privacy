---
api_specs:
- filename: acuiq-com-checkout-api-openapi.yml
  format: yaml
  label: AcuiQ Checkout API
  slug: acuiq-com-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-checkout-api-openapi.yml
- filename: acuiq-com-corpus-api-openapi.yml
  format: yaml
  label: AcuiQ Corpus API
  slug: acuiq-com-corpus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-corpus-api-openapi.yml
- filename: acuiq-com-llms-txt-api-openapi.yml
  format: yaml
  label: AcuiQ Llms.txt API
  slug: acuiq-com-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-llms-txt-api-openapi.yml
- filename: acuiq-com-mcp-api-openapi.yml
  format: yaml
  label: AcuiQ MCP API
  slug: acuiq-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-mcp-api-openapi.yml
- filename: acuiq-com-meridians-api-openapi.yml
  format: yaml
  label: AcuiQ Meridians API
  slug: acuiq-com-meridians-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-meridians-api-openapi.yml
- filename: acuiq-com-protocols-api-openapi.yml
  format: yaml
  label: AcuiQ Protocols API
  slug: acuiq-com-protocols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-protocols-api-openapi.yml
- filename: acuiq-com-reviews-api-openapi.yml
  format: yaml
  label: AcuiQ Reviews API
  slug: acuiq-com-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-reviews-api-openapi.yml
- filename: acuiq-com-symptoms-api-openapi.yml
  format: yaml
  label: AcuiQ Symptoms API
  slug: acuiq-com-symptoms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-symptoms-api-openapi.yml
- filename: acuiq-com-wiki-api-openapi.yml
  format: yaml
  label: AcuiQ Wiki API
  slug: acuiq-com-wiki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuiq-com/openapi/acuiq-com-wiki-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: behavioral
    text: A symptom tally. Each search adds one row to a count for the symptom it matched, with a timestamp and nothing else.
  - category: location
    text: the page, the site that linked to it, your country, and whether you are on a phone, tablet or computer.
  - category: device
    text: whether you are on a phone, tablet or computer
  - category: financial
    text: A completed order leaves AcuiQ with the product bought, the amount, the page the purchase started from, and a random token that is your download link.
  - category: identifying
    text: a code made by hashing your IP address and browser with a random value
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: ranking symptom suggestions
    text: The count ranks the suggestions on the home page.
  - purpose: extending the index
    text: so the index can be extended
  - purpose: counting unique visitors per day
    text: To count a visitor once a day, AcuiQ keeps a code made by hashing your IP address and browser with a random value.
  - purpose: limiting product ratings to one per order
    text: so each order can rate its product once
  retention:
  - period: 400 days
    scope: page view and action rows
    text: Rows are deleted after 400 days.
  - period: null
    scope: daily visitor code random value
    text: The random value is replaced every day and the old one deleted
  rights:
  - right: access, correction or deletion
    text: Nothing here is linked to you, so there is no record to access, correct or delete.
  - right: contact for review
    text: If you believe otherwise, write to info@acuiq.com and it will be checked.
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
name: AcuiQ
provenance_date: '2026-11-09'
provider_name: AcuiQ
provider_slug: acuiq-com
slug: acuiq-com-privacy-policy
source_date: '2026-11-09'
source_filename: acuiq-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://acuiq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AcuiQ\naid: acuiq-com\nurl: https://acuiq.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: A symptom tally. Each search adds one row to a count for the symptom it matched, with a timestamp and nothing\n    else.\n- category: location\n  text: the page, the site that linked to it, your country, and whether you are on a phone, tablet or computer.\n- category: device\n  text: whether you are on a phone, tablet or computer\n- category: financial\n  text: A completed order leaves AcuiQ with the product bought, the amount, the page\
  \ the purchase started from,\n    and a random token that is your download link.\n- category: identifying\n  text: a code made by hashing your IP address and browser with a random value\npurposes:\n- purpose: ranking symptom suggestions\n  text: The count ranks the suggestions on the home page.\n- purpose: extending the index\n  text: so the index can be extended\n- purpose: counting unique visitors per day\n  text: To count a visitor once a day, AcuiQ keeps a code made by hashing your IP address and browser with a random\n    value.\n- purpose: limiting product ratings to one per order\n  text: so each order can rate its product once\nretention:\n- scope: page view and action rows\n  period: 400 days\n  text: Rows are deleted after 400 days.\n- scope: daily visitor code random value\n  period: null\n  text: The random value is replaced every day and the old one deleted\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text:\
  \ null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correction or deletion\n  text: Nothing here is linked to you, so there is no record to access, correct or delete.\n- right: contact for review\n  text: If you believe otherwise, write to info@acuiq.com and it will be checked.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acuiq-com/privacy/acuiq-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
summary_line: 13 quoted statements, read from AcuiQ's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Acupuncture
- Data
- Research
- Wellness
---
