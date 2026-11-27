---
api_specs:
- filename: nationalize-nationality-api-openapi.yml
  format: yaml
  label: Nationalize.io Nationality API
  slug: nationalize-nationality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nationalize/openapi/nationalize-nationality-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address
  - category: financial
    text: Subscription and billing history Payment data
  - category: contact
    text: Email address
  - category: device
    text: We do not log the IP addresses of API requests.
  - category: other
    text: When you make an API request, you send us a name.
  deletion:
    route: Email info@genderize.io
    text: To exercise any of these rights, email us at info@genderize.io .
  dpa:
    available: true
    text: We offer a Data Processing Agreement for customers who require one.
    url: null
  purposes:
  - purpose: Processing real-time predictions
    text: Processed in real time to generate predictions. Not stored.
  - purpose: Rate limiting, billing, abuse prevention
    text: Rate limiting, billing, abuse prevention.
  - purpose: Account management and service delivery
    text: Account management, service delivery, communication about your subscription.
  - purpose: Payment processing, refunds, tax compliance
    text: Processing payments, issuing refunds, tax compliance.
  residency:
  - region: United States (New York)
    text: Our servers are hosted by DigitalOcean in the United States (New York).
  retention:
  - period: null
    scope: Names submitted via API
    text: Not retained. Processed and discarded immediately.
  - period: about 30 minutes of inactivity
    scope: Spreadsheet upload results
    text: Discarded when you leave the tool, and in all cases within about 30 minutes of inactivity.
  - period: null
    scope: Account data
    text: Retained while your account is active. Deleted upon account closure, except where retention is required by law.
  - period: 5 years
    scope: Billing records
    text: Retained for 5 years after the end of the fiscal year, as required by Danish bookkeeping law.
  rights:
  - right: Access
    text: Access — request a copy of the data we hold about you
  - right: Rectification
    text: Rectification — ask us to correct inaccurate data
  - right: Erasure
    text: Erasure — ask us to delete your data
  - right: Restriction
    text: Restriction — ask us to restrict how we process your data
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format
  - right: Objection
    text: Objection — object to processing based on legitimate interest
  - right: Withdraw consent
    text: Withdraw consent — where processing is based on consent, withdraw it at any time
  role:
    text: If you use our APIs as part of processing personal data in your own systems (for example, enriching a contact database), you are the data controller for that processing.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data. We do not share your data for advertising purposes.
  subprocessors:
    text: 'The Services rely on the following third-party providers, which may process limited data in connection with operating the Services:'
    url: null
  transfers:
  - mechanism: DPF
    text: For transfers of data from the European Economic Area to the United States, we rely on the EU-US Data Privacy Framework
  - mechanism: SCC
    text: Where applicable, Standard Contractual Clauses provide additional safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nationalize.io
provenance_date: '2026-11-10'
provider_name: Nationalize.io
provider_slug: nationalize
slug: nationalize-privacy-policy
source_date: '2026-11-10'
source_filename: nationalize-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nationalize.io/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nationalize.io\naid: nationalize\nurl: https://nationalize.io/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: If you use our APIs as part of processing personal data in your own systems (for example, enriching a contact\n    database), you are the data controller for that processing.\ndata_categories:\n- category: identifying\n  text: Email address\n- category: financial\n  text: Subscription and billing history Payment data\n- category: contact\n  text: Email address\n- category: device\n  text: We do not log the IP addresses of API requests.\n- category: other\n  text: When\
  \ you make an API request, you send us a name.\npurposes:\n- purpose: Processing real-time predictions\n  text: Processed in real time to generate predictions. Not stored.\n- purpose: Rate limiting, billing, abuse prevention\n  text: Rate limiting, billing, abuse prevention.\n- purpose: Account management and service delivery\n  text: Account management, service delivery, communication about your subscription.\n- purpose: Payment processing, refunds, tax compliance\n  text: Processing payments, issuing refunds, tax compliance.\nretention:\n- scope: Names submitted via API\n  period: null\n  text: Not retained. Processed and discarded immediately.\n- scope: Spreadsheet upload results\n  period: about 30 minutes of inactivity\n  text: Discarded when you leave the tool, and in all cases within about 30 minutes of inactivity.\n- scope: Account data\n  period: null\n  text: Retained while your account is active. Deleted upon account closure, except where retention is required\n    by law.\n\
  - scope: Billing records\n  period: 5 years\n  text: Retained for 5 years after the end of the fiscal year, as required by Danish bookkeeping law.\nresidency:\n- region: United States (New York)\n  text: Our servers are hosted by DigitalOcean in the United States (New York).\ntransfers:\n- mechanism: DPF\n  text: For transfers of data from the European Economic Area to the United States, we rely on the EU-US Data Privacy\n    Framework\n- mechanism: SCC\n  text: Where applicable, Standard Contractual Clauses provide additional safeguards.\nsubprocessors:\n  url: null\n  text: 'The Services rely on the following third-party providers, which may process limited data in connection\n    with operating the Services:'\ndpa:\n  available: true\n  url: null\n  text: We offer a Data Processing Agreement for customers who require one.\ndeletion:\n  route: Email info@genderize.io\n  text: To exercise any of these rights, email us at info@genderize.io .\nrights:\n- right: Access\n  text: Access —\
  \ request a copy of the data we hold about you\n- right: Rectification\n  text: Rectification — ask us to correct inaccurate data\n- right: Erasure\n  text: Erasure — ask us to delete your data\n- right: Restriction\n  text: Restriction — ask us to restrict how we process your data\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format\n- right: Objection\n  text: Objection — object to processing based on legitimate interest\n- right: Withdraw consent\n  text: Withdraw consent — where processing is based on consent, withdraw it at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data. We do not share your data for advertising purposes.\n"
source_yaml_url: https://artifacts.apis.io/nationalize/privacy/nationalize-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Nationalize.io's own page on 2026-11-10.
synthetic: false
tags:
- Nationality
- Name Prediction
- Demographics
- Probabilistic Models
- People
---
