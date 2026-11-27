---
api_specs:
- filename: cite42-dev-openapi-generated.yml
  format: yaml
  label: cite42-dev API
  slug: cite42-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cite42-dev/openapi/_ae-authored/cite42-dev-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address, authentication identifiers and (if you choose to provide them) your name, organization, and country
  - category: financial
    text: When you add funds we collect billing email, country, and a Stripe customer ID.
  - category: device
    text: the IP address and User-Agent of the request
  - category: other
    text: we receive and process the request body, for example, the brand name, prompt set, URL, keyword, location, language, trend query, or competitor list you submit
  deletion:
    route: email support@cite42.dev
    text: To exercise any of these rights, email support@cite42.dev
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the Service
    text: Authenticating you, accepting API requests, routing them to the appropriate model providers and search/SEO data providers, returning structured results, charging your balance
  - purpose: Billing and fraud prevention
    text: detecting payment fraud, credit-card testing, abusive account creation, and API-key compromise
  - purpose: Rate limiting and abuse detection
    text: Counting requests per key, per IP, and per account
  - purpose: Communication
    text: Sending account-related notifications (e.g. low account balance, key compromise, security alerts, material changes to these policies).
  residency:
  - region: European Economic Area
    text: stored primarily in the European Economic Area
  retention:
  - period: while your account is active and for up to 90 days after deletion
    scope: Account data
    text: 'Account data: while your account is active and for up to 90 days after deletion'
  - period: 180 days
    scope: API request and response logs
    text: 'API request and response logs: 180 days, after which they are deleted or aggregated into non-identifying statistics.'
  - period: currently six years from the end of the relevant tax year
    scope: Billing ledger and invoices
    text: currently six years from the end of the relevant tax year
  - period: up to 12 months
    scope: Security and abuse-detection logs
    text: 'Security and abuse-detection logs: up to 12 months.'
  - period: maximum 35-day cycle
    scope: Backups
    text: 'Backups: rolling, encrypted, with a maximum 35-day cycle.'
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Erase
    text: Erase your data (the "right to be forgotten"), subject to legal retention obligations.
  - right: Object
    text: Object to processing carried out on the basis of legitimate interests.
  - right: Port
    text: Port data you have provided to us in a structured, machine-readable format.
  role:
    text: 'Controller: Flynk AI LTD, registered in England and Wales.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: The following service providers help us run the Service and process limited categories of your personal data on our behalf
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses (SCCs)
  - mechanism: other
    text: the UK International Data Transfer Agreement (IDTA)
  - mechanism: other
    text: the UK Addendum to the EU SCCs
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cite42-dev
provenance_date: '2026-11-09'
provider_name: cite42-dev
provider_slug: cite42-dev
slug: cite42-dev-privacy-policy
source_date: '2026-11-09'
source_filename: cite42-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cite42.dev/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cite42-dev\naid: cite42-dev\nurl: https://www.cite42.dev/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller: Flynk AI LTD, registered in England and Wales.'\ndata_categories:\n- category: identifying\n  text: we collect your email address, authentication identifiers and (if you choose to provide them) your name,\n    organization, and country\n- category: financial\n  text: When you add funds we collect billing email, country, and a Stripe customer ID.\n- category: device\n  text: the IP address and User-Agent of the request\n- category: other\n  text: we receive and\
  \ process the request body, for example, the brand name, prompt set, URL, keyword, location,\n    language, trend query, or competitor list you submit\npurposes:\n- purpose: Providing the Service\n  text: Authenticating you, accepting API requests, routing them to the appropriate model providers and search/SEO\n    data providers, returning structured results, charging your balance\n- purpose: Billing and fraud prevention\n  text: detecting payment fraud, credit-card testing, abusive account creation, and API-key compromise\n- purpose: Rate limiting and abuse detection\n  text: Counting requests per key, per IP, and per account\n- purpose: Communication\n  text: Sending account-related notifications (e.g. low account balance, key compromise, security alerts, material\n    changes to these policies).\nretention:\n- scope: Account data\n  period: while your account is active and for up to 90 days after deletion\n  text: 'Account data: while your account is active and for up to 90 days after\
  \ deletion'\n- scope: API request and response logs\n  period: 180 days\n  text: 'API request and response logs: 180 days, after which they are deleted or aggregated into non-identifying\n    statistics.'\n- scope: Billing ledger and invoices\n  period: currently six years from the end of the relevant tax year\n  text: currently six years from the end of the relevant tax year\n- scope: Security and abuse-detection logs\n  period: up to 12 months\n  text: 'Security and abuse-detection logs: up to 12 months.'\n- scope: Backups\n  period: maximum 35-day cycle\n  text: 'Backups: rolling, encrypted, with a maximum 35-day cycle.'\nresidency:\n- region: European Economic Area\n  text: stored primarily in the European Economic Area\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses (SCCs)\n- mechanism: other\n  text: the UK International Data Transfer Agreement (IDTA)\n- mechanism: other\n  text: the UK Addendum to the EU SCCs\nsubprocessors:\n\
  \  url: null\n  text: The following service providers help us run the Service and process limited categories of your personal\n    data on our behalf\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@cite42.dev\n  text: To exercise any of these rights, email support@cite42.dev\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Erase\n  text: Erase your data (the \"right to be forgotten\"), subject to legal retention obligations.\n- right: Object\n  text: Object to processing carried out on the basis of legitimate interests.\n- right: Port\n  text: Port data you have provided to us in a structured, machine-readable format.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/cite42-dev/privacy/cite42-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from cite42-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- SEO
- MCP
- Data
- Visibility
---
