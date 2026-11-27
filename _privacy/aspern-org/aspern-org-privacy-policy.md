---
api_specs:
- filename: aspern-org-account-api-openapi.yml
  format: yaml
  label: ASPERN Account API
  slug: aspern-org-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-account-api-openapi.yml
- filename: aspern-org-agents-api-openapi.yml
  format: yaml
  label: ASPERN Agents API
  slug: aspern-org-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-agents-api-openapi.yml
- filename: aspern-org-alerts-api-openapi.yml
  format: yaml
  label: ASPERN Alerts API
  slug: aspern-org-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-alerts-api-openapi.yml
- filename: aspern-org-attestation-api-openapi.yml
  format: yaml
  label: ASPERN Attestation API
  slug: aspern-org-attestation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-attestation-api-openapi.yml
- filename: aspern-org-capital-api-openapi.yml
  format: yaml
  label: ASPERN Capital API
  slug: aspern-org-capital-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-capital-api-openapi.yml
- filename: aspern-org-commerce-api-openapi.yml
  format: yaml
  label: ASPERN Commerce API
  slug: aspern-org-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-commerce-api-openapi.yml
- filename: aspern-org-crowding-api-openapi.yml
  format: yaml
  label: ASPERN Crowding API
  slug: aspern-org-crowding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-crowding-api-openapi.yml
- filename: aspern-org-history-api-openapi.yml
  format: yaml
  label: ASPERN History API
  slug: aspern-org-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-history-api-openapi.yml
- filename: aspern-org-judgement-api-openapi.yml
  format: yaml
  label: ASPERN Judgement API
  slug: aspern-org-judgement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-judgement-api-openapi.yml
- filename: aspern-org-market-api-openapi.yml
  format: yaml
  label: ASPERN Market API
  slug: aspern-org-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-market-api-openapi.yml
- filename: aspern-org-ratings-api-openapi.yml
  format: yaml
  label: ASPERN Ratings API
  slug: aspern-org-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-ratings-api-openapi.yml
- filename: aspern-org-record-api-openapi.yml
  format: yaml
  label: ASPERN Record API
  slug: aspern-org-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-record-api-openapi.yml
- filename: aspern-org-reference-api-openapi.yml
  format: yaml
  label: ASPERN Reference API
  slug: aspern-org-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-reference-api-openapi.yml
- filename: aspern-org-risk-api-openapi.yml
  format: yaml
  label: ASPERN Risk API
  slug: aspern-org-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aspern-org/openapi/aspern-org-risk-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: a name and an email address if you open an account
  - category: financial
    text: a record of what you paid
  - category: device
    text: Four cookies exist on this site and every one of them is a step of the sign-in you asked for.
  - category: behavioral
    text: Which pages were read, and for how long
  - category: financial
    text: A blockchain address, where you chose to pay that way
  deletion:
    route: Write to hello@aspern.org
    text: Delete it ( erasure ) The account and everything on it. Payment records survive this, because the tax rules require them and we are not free to drop them at will.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and sign-in
    text: To have an account at all, to sign you in, and to write to you about what you bought
  - purpose: Tax and accounting records
    text: To know what you are owed, and because the tax authority requires it
  - purpose: Recognise payments
    text: To recognise your payment when it arrives
  - purpose: Site readership
    text: To know which work is worth continuing
  - purpose: Metering API use
    text: To meter the allowance you bought and to keep the service up
  retention:
  - period: Until you close the account
    scope: Account data
    text: Until you close the account
  - period: Ten years
    scope: Payment records
    text: Ten years, which is the accounting rule and not our choice
  - period: Aggregated
    scope: Read-page data
    text: Aggregated; the daily visitor hash cannot be joined across days
  rights:
  - right: Access
    text: See it ( access ) A copy of everything held about you.
  - right: Rectification
    text: Correct it ( rectification ) A wrong name or address, fixed.
  - right: Erasure
    text: Delete it ( erasure ) The account and everything on it.
  - right: Portability
    text: Take it elsewhere ( data portability ) The same copy in a machine-readable file.
  - right: Objection
    text: Object to the audience count ( objection ) Say so and this browser stops being counted.
  - right: Complaint
    text: Complain about us ( lodge a complaint with a supervisory authority ) To the data protection authority where you live, without asking us first.
  role:
    text: They decide what is collected here and why, which is what the law calls the controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Nothing is sold, nothing is shared for advertising, and there is no fifth.
  subprocessors:
    text: Four, and each does one job. Nothing is sold, nothing is shared for advertising, and there is no fifth.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ASPERN
provenance_date: '2026-11-09'
provider_name: ASPERN
provider_slug: aspern-org
slug: aspern-org-privacy-policy
source_date: '2026-11-09'
source_filename: aspern-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aspern.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ASPERN\naid: aspern-org\nurl: https://aspern.org/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: They decide what is collected here and why, which is what the law calls the controller.\ndata_categories:\n- category: identifying\n  text: a name and an email address if you open an account\n- category: financial\n  text: a record of what you paid\n- category: device\n  text: Four cookies exist on this site and every one of them is a step of the sign-in you asked for.\n- category: behavioral\n  text: Which pages were read, and for how long\n- category: financial\n  text: A blockchain address,\
  \ where you chose to pay that way\npurposes:\n- purpose: Account and sign-in\n  text: To have an account at all, to sign you in, and to write to you about what you bought\n- purpose: Tax and accounting records\n  text: To know what you are owed, and because the tax authority requires it\n- purpose: Recognise payments\n  text: To recognise your payment when it arrives\n- purpose: Site readership\n  text: To know which work is worth continuing\n- purpose: Metering API use\n  text: To meter the allowance you bought and to keep the service up\nretention:\n- scope: Account data\n  period: Until you close the account\n  text: Until you close the account\n- scope: Payment records\n  period: Ten years\n  text: Ten years, which is the accounting rule and not our choice\n- scope: Read-page data\n  period: Aggregated\n  text: Aggregated; the daily visitor hash cannot be joined across days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Four, and each does one job. Nothing is sold,\
  \ nothing is shared for advertising, and there is no fifth.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hello@aspern.org\n  text: Delete it ( erasure ) The account and everything on it. Payment records survive this, because the tax rules\n    require them and we are not free to drop them at will.\nrights:\n- right: Access\n  text: See it ( access ) A copy of everything held about you.\n- right: Rectification\n  text: Correct it ( rectification ) A wrong name or address, fixed.\n- right: Erasure\n  text: Delete it ( erasure ) The account and everything on it.\n- right: Portability\n  text: Take it elsewhere ( data portability ) The same copy in a machine-readable file.\n- right: Objection\n  text: Object to the audience count ( objection ) Say so and this browser stops being counted.\n- right: Complaint\n  text: Complain about us ( lodge a complaint with a supervisory authority ) To the data protection authority where\n    you live, without asking us\
  \ first.\nsale_or_sharing:\n  stance: prohibited\n  text: Nothing is sold, nothing is shared for advertising, and there is no fifth.\n"
source_yaml_url: https://artifacts.apis.io/aspern-org/privacy/aspern-org-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from ASPERN's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Blockchain
- Artificial Intelligence
- Data
- Intelligence
---
