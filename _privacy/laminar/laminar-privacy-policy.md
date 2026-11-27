---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address, display name, and profile picture
  - category: contact
    text: the email addresses of people you invite to your workspace
  - category: financial
    text: we do not store your card number
  - category: behavioral
    text: We collect product analytics (pages viewed, features used) tied to your email address
  - category: device
    text: standard technical data such as IP address, browser, and device characteristics
  - category: communication
    text: Emails you exchange with us, feedback, and support requests
  - category: health
    text: If an end user tells a customer's agent about their health, finances, or anything else, that content arrives in the trace
  deletion:
    route: project or workspace deletion in the product
    text: When a customer deletes a project or workspace (or asks us to), the associated Customer Data is deleted from our primary databases.
  dpa:
    available: true
    text: accounts covered by a signed data processing agreement
    url: null
  purposes:
  - purpose: provide the platform
    text: to provide the platform — ingestion, storage, display, search, analytics, evaluations, and alerting
  - purpose: billing and transactional email
    text: To bill for paid plans and send transactional email such as invoices
  - purpose: product improvement
    text: To understand how the product is used and improve it (legitimate interests).
  - purpose: improve Laminar's own models
    text: to improve Laminar's own models, only using Signal Run Data from workspaces where Privacy Mode is off
  retention:
  - period: for as long as your account exists
    scope: account and workspace data
    text: 'Account and workspace data: for as long as your account exists'
  - period: for as long as the customer's project exists
    scope: customer data
    text: Customer Data is retained for as long as the customer's project exists
  - period: within at most 90 days
    scope: search-index copies of customer data
    text: search-index copies within at most 90 days
  rights:
  - right: access, correct, delete, restrict, port
    text: rights to access, correct, delete, restrict, or port your personal data
  - right: opt out of targeted advertising, sale, or profiling
    text: the right to opt out of targeted advertising, sale, or profiling
  - right: withdraw consent
    text: to withdraw consent
  role:
    text: Laminar is a processor acting on the customer's instructions under our data processing agreement
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: the subprocessors we engage are listed in our trust center
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Laminar
provenance_date: '2026-11-09'
provider_name: Laminar
provider_slug: laminar
slug: laminar-privacy-policy
source_date: '2026-11-09'
source_filename: laminar-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://laminar.sh/policies/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Laminar\naid: laminar\nurl: https://laminar.sh/policies/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Laminar is a processor acting on the customer's instructions under our data processing agreement\ndata_categories:\n- category: identifying\n  text: we collect your email address, display name, and profile picture\n- category: contact\n  text: the email addresses of people you invite to your workspace\n- category: financial\n  text: we do not store your card number\n- category: behavioral\n  text: We collect product analytics (pages viewed, features used) tied to your email address\n- category:\
  \ device\n  text: standard technical data such as IP address, browser, and device characteristics\n- category: communication\n  text: Emails you exchange with us, feedback, and support requests\n- category: health\n  text: If an end user tells a customer's agent about their health, finances, or anything else, that content arrives\n    in the trace\npurposes:\n- purpose: provide the platform\n  text: to provide the platform — ingestion, storage, display, search, analytics, evaluations, and alerting\n- purpose: billing and transactional email\n  text: To bill for paid plans and send transactional email such as invoices\n- purpose: product improvement\n  text: To understand how the product is used and improve it (legitimate interests).\n- purpose: improve Laminar's own models\n  text: to improve Laminar's own models, only using Signal Run Data from workspaces where Privacy Mode is off\nretention:\n- scope: account and workspace data\n  period: for as long as your account exists\n  text: 'Account\
  \ and workspace data: for as long as your account exists'\n- scope: customer data\n  period: for as long as the customer's project exists\n  text: Customer Data is retained for as long as the customer's project exists\n- scope: search-index copies of customer data\n  period: within at most 90 days\n  text: search-index copies within at most 90 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: the subprocessors we engage are listed in our trust center\ndpa:\n  available: true\n  url: null\n  text: accounts covered by a signed data processing agreement\ndeletion:\n  route: project or workspace deletion in the product\n  text: When a customer deletes a project or workspace (or asks us to), the associated Customer Data is deleted\n    from our primary databases.\nrights:\n- right: access, correct, delete, restrict, port\n  text: rights to access, correct, delete, restrict, or port your personal data\n- right: opt out of targeted advertising, sale, or profiling\n  text:\
  \ the right to opt out of targeted advertising, sale, or profiling\n- right: withdraw consent\n  text: to withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/laminar/privacy/laminar-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Laminar's own page on 2026-11-09.
synthetic: false
tags:
- Observability
- LLM
- AI Agents
- Tracing
- OpenTelemetry
- Evaluation
- Monitoring
- Developer Tools
- Open Source
---
