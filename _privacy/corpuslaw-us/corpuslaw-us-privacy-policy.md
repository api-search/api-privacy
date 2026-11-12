---
api_specs:
- filename: corpuslaw-us-account-api-openapi.yml
  format: yaml
  label: Corpus Account API
  slug: corpuslaw-us-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-account-api-openapi.yml
- filename: corpuslaw-us-browse-api-openapi.yml
  format: yaml
  label: Corpus Browse API
  slug: corpuslaw-us-browse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-browse-api-openapi.yml
- filename: corpuslaw-us-coverage-api-openapi.yml
  format: yaml
  label: Corpus Coverage API
  slug: corpuslaw-us-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-coverage-api-openapi.yml
- filename: corpuslaw-us-formation-api-openapi.yml
  format: yaml
  label: Corpus Formation API
  slug: corpuslaw-us-formation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-formation-api-openapi.yml
- filename: corpuslaw-us-general-api-openapi.yml
  format: yaml
  label: Corpus General API
  slug: corpuslaw-us-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-general-api-openapi.yml
- filename: corpuslaw-us-gis-api-openapi.yml
  format: yaml
  label: Corpus GIS API
  slug: corpuslaw-us-gis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-gis-api-openapi.yml
- filename: corpuslaw-us-search-api-openapi.yml
  format: yaml
  label: Corpus Search API
  slug: corpuslaw-us-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpuslaw-us/openapi/corpuslaw-us-search-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: the names, roles, and addresses of the members, managers, officers, directors, organizers, and incorporators, along with contact details
  - category: identifying
    text: the responsible party’s Social Security Number
  - category: financial
    text: Card payments are processed by Stripe.
  - category: financial
    text: records the recipient, mint, cluster, transaction signature, amount, and settlement state needed to reconcile it
  - category: contact
    text: we collect your email address (and, with Google, your name)
  - category: behavioral
    text: record how you interact with our public pages
  - category: location
    text: approximate location from IP
  - category: device
    text: browser type
  - category: communication
    text: We store the messages you exchange with the Belisarius assistant
  deletion:
    route: email support@corpuslaw.us
    text: To make a request, email support@corpuslaw.us
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide formation services
    text: running the intake, preparing and submitting filings after human review
  - purpose: process payments
    text: to process payments
  - purpose: secure, debug, and improve the platform
    text: to secure, debug, and improve the platform
  - purpose: legal, tax, and accounting obligations
    text: to meet our legal, tax, and accounting obligations
  - purpose: product analytics
    text: product analytics (PostHog and Vercel Analytics) to understand how the site is used
  residency:
  - region: United States
    text: Corpus is operated from the United States and stores data in the United States.
  retention:
  - period: 7 days
    scope: responsible party SSN
    text: never retained longer than 7 days regardless
  - period: null
    scope: order and account data
    text: We keep order and account data for as long as needed to provide the services and to meet legal, tax, and accounting obligations, then delete or de-identify it.
  - period: seven days
    scope: email plan snapshot
    text: storing a plan snapshot and step statuses for seven days
  rights:
  - right: access
    text: You may request access to, correction of, or deletion of your personal information
  - right: deletion
    text: the right to deletion, which you may exercise without discriminatory treatment
  - right: opt out of non-essential communications
    text: you may opt out of non-essential communications at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information , and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: 'We share your information only as needed to run the service, with these categories of providers (subprocessors): Filing partner and government.'
    url: null
  transfers:
  - mechanism: other
    text: These providers process the data to return a result to us; some may process it outside the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Corpus
provenance_date: '2026-11-09'
provider_name: Corpus
provider_slug: corpuslaw-us
slug: corpuslaw-us-privacy-policy
source_date: '2026-11-09'
source_filename: corpuslaw-us-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corpuslaw.us/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Corpus\naid: corpuslaw-us\nurl: https://corpuslaw.us/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: the names, roles, and addresses of the members, managers, officers, directors, organizers, and incorporators,\n    along with contact details\n- category: identifying\n  text: the responsible party’s Social Security Number\n- category: financial\n  text: Card payments are processed by Stripe.\n- category: financial\n  text: records the recipient, mint, cluster, transaction signature, amount, and settlement state needed to reconcile\n\
  \    it\n- category: contact\n  text: we collect your email address (and, with Google, your name)\n- category: behavioral\n  text: record how you interact with our public pages\n- category: location\n  text: approximate location from IP\n- category: device\n  text: browser type\n- category: communication\n  text: We store the messages you exchange with the Belisarius assistant\npurposes:\n- purpose: provide formation services\n  text: running the intake, preparing and submitting filings after human review\n- purpose: process payments\n  text: to process payments\n- purpose: secure, debug, and improve the platform\n  text: to secure, debug, and improve the platform\n- purpose: legal, tax, and accounting obligations\n  text: to meet our legal, tax, and accounting obligations\n- purpose: product analytics\n  text: product analytics (PostHog and Vercel Analytics) to understand how the site is used\nretention:\n- scope: responsible party SSN\n  period: 7 days\n  text: never retained longer\
  \ than 7 days regardless\n- scope: order and account data\n  period: null\n  text: We keep order and account data for as long as needed to provide the services and to meet legal, tax, and\n    accounting obligations, then delete or de-identify it.\n- scope: email plan snapshot\n  period: seven days\n  text: storing a plan snapshot and step statuses for seven days\nresidency:\n- region: United States\n  text: Corpus is operated from the United States and stores data in the United States.\ntransfers:\n- mechanism: other\n  text: These providers process the data to return a result to us; some may process it outside the United States.\nsubprocessors:\n  url: null\n  text: 'We share your information only as needed to run the service, with these categories of providers (subprocessors):\n    Filing partner and government.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@corpuslaw.us\n  text: To make a request, email support@corpuslaw.us\nrights:\n- right:\
  \ access\n  text: You may request access to, correction of, or deletion of your personal information\n- right: deletion\n  text: the right to deletion, which you may exercise without discriminatory treatment\n- right: opt out of non-essential communications\n  text: you may opt out of non-essential communications at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information , and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/corpuslaw-us/privacy/corpuslaw-us-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Corpus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Law
- Business Formation
- LLC
- Compliance
- MCP
- AI Agents
---
