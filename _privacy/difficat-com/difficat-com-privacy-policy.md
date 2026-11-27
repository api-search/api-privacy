---
api_specs:
- filename: difficat-com-balance-api-openapi.yml
  format: yaml
  label: DiffiCat Balance API
  slug: difficat-com-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/difficat-com/openapi/difficat-com-balance-api-openapi.yml
- filename: difficat-com-compares-api-openapi.yml
  format: yaml
  label: DiffiCat Compares API
  slug: difficat-com-compares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/difficat-com/openapi/difficat-com-compares-api-openapi.yml
- filename: difficat-com-discover-api-openapi.yml
  format: yaml
  label: DiffiCat Discover API
  slug: difficat-com-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/difficat-com/openapi/difficat-com-discover-api-openapi.yml
- filename: difficat-com-feedback-api-openapi.yml
  format: yaml
  label: DiffiCat Feedback API
  slug: difficat-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/difficat-com/openapi/difficat-com-feedback-api-openapi.yml
- filename: difficat-com-jobs-api-openapi.yml
  format: yaml
  label: DiffiCat Jobs API
  slug: difficat-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/difficat-com/openapi/difficat-com-jobs-api-openapi.yml
- filename: difficat-com-screenshots-api-openapi.yml
  format: yaml
  label: DiffiCat Screenshots API
  slug: difficat-com-screenshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/difficat-com/openapi/difficat-com-screenshots-api-openapi.yml
- filename: difficat-com-snapshots-api-openapi.yml
  format: yaml
  label: DiffiCat Snapshots API
  slug: difficat-com-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/difficat-com/openapi/difficat-com-snapshots-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: behavioral
    text: It measures how the pages are used — page views, browser and device characteristics, and which features are used
  - category: device
    text: browser and device characteristics
  - category: identifying
    text: Through a provider we receive that account's basic profile (name, email address and, where the provider gives one, picture) solely to identify your session
  - category: contact
    text: For an email-code account we keep only the email address
  - category: financial
    text: the Stripe customer and subscription identifiers and a hash of the account's API key
  deletion:
    route: Account page deletion; forever-delete from Archive
    text: An account stays until its owner deletes it from the account page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Understand product usage
    text: We use this to understand which parts of the product people find and use; we do not sell or share this data.
  - purpose: Run requested comparisons
    text: The URLs you submit are used only to run the comparison you asked for.
  - purpose: Identify user session
    text: solely to identify your session
  - purpose: Subscription payments
    text: Subscription payments are processed by Stripe ; the app stores no card data.
  residency:
  - region: EU (Frankfurt)
    text: Both difficat.com and app.difficat.com load PostHog analytics, hosted in the EU (Frankfurt).
  retention:
  - period: 30 days
    scope: Unsaved comparison reports
    text: for every other account they are kept for 30 days (at most 5)
  - period: null
    scope: Pro comparisons
    text: Comparisons of a Pro account are saved until you delete them forever
  - period: null
    scope: Agent API job records
    text: the record expires 24 hours after its last update
  - period: 30 days
    scope: Agent API job report data and screenshots
    text: The job's report data and screenshots are deleted 30 days after they are written.
  - period: 30 days
    scope: Service logs
    text: are deleted after 30 days
  - period: ten years
    scope: Accounting ledger
    text: kept for the ten years Swiss accounting law requires (Code of Obligations art. 958f)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell or share this data
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DiffiCat
provenance_date: '2026-11-09'
provider_name: DiffiCat
provider_slug: difficat-com
slug: difficat-com-privacy-policy
source_date: '2026-11-09'
source_filename: difficat-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://difficat.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DiffiCat\naid: difficat-com\nurl: https://difficat.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: It measures how the pages are used — page views, browser and device characteristics, and which features\n    are used\n- category: device\n  text: browser and device characteristics\n- category: identifying\n  text: Through a provider we receive that account's basic profile (name, email address and, where the provider\n    gives one, picture) solely to identify your session\n- category: contact\n  text: For an email-code account\
  \ we keep only the email address\n- category: financial\n  text: the Stripe customer and subscription identifiers and a hash of the account's API key\npurposes:\n- purpose: Understand product usage\n  text: We use this to understand which parts of the product people find and use; we do not sell or share this data.\n- purpose: Run requested comparisons\n  text: The URLs you submit are used only to run the comparison you asked for.\n- purpose: Identify user session\n  text: solely to identify your session\n- purpose: Subscription payments\n  text: Subscription payments are processed by Stripe ; the app stores no card data.\nretention:\n- scope: Unsaved comparison reports\n  period: 30 days\n  text: for every other account they are kept for 30 days (at most 5)\n- scope: Pro comparisons\n  period: null\n  text: Comparisons of a Pro account are saved until you delete them forever\n- scope: Agent API job records\n  period: null\n  text: the record expires 24 hours after its last update\n- scope:\
  \ Agent API job report data and screenshots\n  period: 30 days\n  text: The job's report data and screenshots are deleted 30 days after they are written.\n- scope: Service logs\n  period: 30 days\n  text: are deleted after 30 days\n- scope: Accounting ledger\n  period: ten years\n  text: kept for the ten years Swiss accounting law requires (Code of Obligations art. 958f)\nresidency:\n- region: EU (Frankfurt)\n  text: Both difficat.com and app.difficat.com load PostHog analytics, hosted in the EU (Frankfurt).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page deletion; forever-delete from Archive\n  text: An account stays until its owner deletes it from the account page.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell or share this data\n"
source_yaml_url: https://artifacts.apis.io/difficat-com/privacy/difficat-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- sale_or_sharing
summary_line: 18 quoted statements, read from DiffiCat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Website Migration
- Visual Regression
- Testing
- QA
- SEO
- MCP
- AI Agents
- x402
---
