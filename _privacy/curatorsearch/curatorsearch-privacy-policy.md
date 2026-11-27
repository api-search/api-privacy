---
api_specs:
- filename: curatorsearch-data-api-openapi.yml
  format: yaml
  label: CuratorSearch Data API
  slug: curatorsearch-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curatorsearch/openapi/curatorsearch-data-api-openapi.yml
- filename: curatorsearch-jobs-api-openapi.yml
  format: yaml
  label: CuratorSearch Jobs API
  slug: curatorsearch-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curatorsearch/openapi/curatorsearch-jobs-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address, your name if you give one, and a one-way hash of your password
  - category: financial
    text: a customer reference and subscription status from Stripe, our payment processor
  - category: professional
    text: the listing content you submit, linked to your account
  - category: device
    text: ordinary server request logs, which include IP addresses
  deletion:
    route: Delete account in the app
    text: You can delete your account at any time, which removes your account record and any job postings attached to it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing account and subscription
    text: Providing your account and subscription is processing necessary to perform our contract with you.
  - purpose: Security
    text: Security measures such as rate limiting and breached-password checks rest on our legitimate interest in protecting accounts.
  - purpose: Operating job board
    text: Aggregating publicly advertised vacancies rests on our legitimate interest in operating a job board.
  - purpose: Traffic analytics
    text: We use Google Analytics to see aggregate traffic and which pages get used
  residency:
  - region: EEA
    text: Railway — hosts the application and the database, both in Railway's EU-West (Amsterdam) region, so account and subscription records are stored inside the EEA.
  retention:
  - period: ten years afterwards
    scope: Account and subscription records
    text: Account and subscription records are kept while your account exists and for ten years afterwards where needed for tax and accounting.
  - period: 30 days
    scope: Server logs
    text: Server logs are kept for 30 days.
  - period: within an hour
    scope: Rate-limiting counters
    text: Rate-limiting counters are held in memory only and expire within an hour.
  rights:
  - right: access
    text: You have the right to access your data, correct it, delete it, restrict or object to processing, and receive a portable copy.
  - right: complain to supervisory authority
    text: If you are in the UK you may complain to the Information Commissioner's Office; in the EU, to your national supervisory authority.
  role:
    text: The data controller is Nadim Samman, Urbanstraße 176, 10961 Berlin, Germany, acting as a sole trader.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal data with third parties for marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Both self-certify under the EU-US Data Privacy Framework, and both also offer the European Commission's Standard Contractual Clauses.
  - mechanism: SCC
    text: where it is not, we rely on the European Commission's Standard Contractual Clauses.
  - mechanism: adequacy
    text: The breached-password check runs against Have I Been Pwned in the UK, which the European Commission has found to provide an adequate level of protection.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CuratorSearch
provenance_date: '2026-11-09'
provider_name: CuratorSearch
provider_slug: curatorsearch
slug: curatorsearch-privacy-policy
source_date: '2026-11-09'
source_filename: curatorsearch-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://curatorsearch.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CuratorSearch\naid: curatorsearch\nurl: https://curatorsearch.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Nadim Samman, Urbanstraße 176, 10961 Berlin, Germany, acting as a sole trader.\ndata_categories:\n- category: identifying\n  text: your email address, your name if you give one, and a one-way hash of your password\n- category: financial\n  text: a customer reference and subscription status from Stripe, our payment processor\n- category: professional\n  text: the listing content you submit, linked to your account\n- category: device\n  text: ordinary\
  \ server request logs, which include IP addresses\npurposes:\n- purpose: Providing account and subscription\n  text: Providing your account and subscription is processing necessary to perform our contract with you.\n- purpose: Security\n  text: Security measures such as rate limiting and breached-password checks rest on our legitimate interest in\n    protecting accounts.\n- purpose: Operating job board\n  text: Aggregating publicly advertised vacancies rests on our legitimate interest in operating a job board.\n- purpose: Traffic analytics\n  text: We use Google Analytics to see aggregate traffic and which pages get used\nretention:\n- scope: Account and subscription records\n  period: ten years afterwards\n  text: Account and subscription records are kept while your account exists and for ten years afterwards where needed\n    for tax and accounting.\n- scope: Server logs\n  period: 30 days\n  text: Server logs are kept for 30 days.\n- scope: Rate-limiting counters\n  period: within\
  \ an hour\n  text: Rate-limiting counters are held in memory only and expire within an hour.\nresidency:\n- region: EEA\n  text: Railway — hosts the application and the database, both in Railway's EU-West (Amsterdam) region, so account\n    and subscription records are stored inside the EEA.\ntransfers:\n- mechanism: DPF\n  text: Both self-certify under the EU-US Data Privacy Framework, and both also offer the European Commission's\n    Standard Contractual Clauses.\n- mechanism: SCC\n  text: where it is not, we rely on the European Commission's Standard Contractual Clauses.\n- mechanism: adequacy\n  text: The breached-password check runs against Have I Been Pwned in the UK, which the European Commission has\n    found to provide an adequate level of protection.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in the app\n  text: You can delete your account at any time, which removes your account record and\
  \ any job postings attached\n    to it.\nrights:\n- right: access\n  text: You have the right to access your data, correct it, delete it, restrict or object to processing, and receive\n    a portable copy.\n- right: complain to supervisory authority\n  text: If you are in the UK you may complain to the Information Commissioner's Office; in the EU, to your national\n    supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal data with third parties for marketing.\n"
source_yaml_url: https://artifacts.apis.io/curatorsearch/privacy/curatorsearch-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from CuratorSearch's own page on 2026-11-09.
synthetic: false
tags:
- Agent-Native
- MCP
- OpenAPI
- Llms.txt
- Open Data
- Job
- Cultural Heritage
- Museums
- curatorial
- salary-transparency
- glam
- museum jobs
- Job Board
- Salaries
- Pay Transparency
- Datasets
- RSS
---
