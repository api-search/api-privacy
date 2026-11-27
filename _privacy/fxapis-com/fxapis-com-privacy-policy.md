---
api_specs:
- filename: fxapis-com-accounts-api-openapi.yml
  format: yaml
  label: fxapis-com Accounts API
  slug: fxapis-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-accounts-api-openapi.yml
- filename: fxapis-com-alerts-api-openapi.yml
  format: yaml
  label: fxapis-com Alerts API
  slug: fxapis-com-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-alerts-api-openapi.yml
- filename: fxapis-com-api-keys-api-openapi.yml
  format: yaml
  label: fxapis-com API keys API
  slug: fxapis-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-api-keys-api-openapi.yml
- filename: fxapis-com-billing-api-openapi.yml
  format: yaml
  label: fxapis-com Billing API
  slug: fxapis-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-billing-api-openapi.yml
- filename: fxapis-com-copy-trading-api-openapi.yml
  format: yaml
  label: fxapis-com Copy trading API
  slug: fxapis-com-copy-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-copy-trading-api-openapi.yml
- filename: fxapis-com-events-api-openapi.yml
  format: yaml
  label: fxapis-com Events API
  slug: fxapis-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-events-api-openapi.yml
- filename: fxapis-com-health-api-openapi.yml
  format: yaml
  label: fxapis-com Health API
  slug: fxapis-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-health-api-openapi.yml
- filename: fxapis-com-history-api-openapi.yml
  format: yaml
  label: fxapis-com History API
  slug: fxapis-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-history-api-openapi.yml
- filename: fxapis-com-instruments-api-openapi.yml
  format: yaml
  label: fxapis-com Instruments API
  slug: fxapis-com-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-instruments-api-openapi.yml
- filename: fxapis-com-lifecycle-api-openapi.yml
  format: yaml
  label: fxapis-com Lifecycle API
  slug: fxapis-com-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-lifecycle-api-openapi.yml
- filename: fxapis-com-market-data-api-openapi.yml
  format: yaml
  label: fxapis-com Market data API
  slug: fxapis-com-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-market-data-api-openapi.yml
- filename: fxapis-com-members-api-openapi.yml
  format: yaml
  label: fxapis-com Members API
  slug: fxapis-com-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-members-api-openapi.yml
- filename: fxapis-com-trading-api-openapi.yml
  format: yaml
  label: fxapis-com Trading API
  slug: fxapis-com-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-trading-api-openapi.yml
- filename: fxapis-com-waves-api-openapi.yml
  format: yaml
  label: fxapis-com Waves API
  slug: fxapis-com-waves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-waves-api-openapi.yml
- filename: fxapis-com-webhooks-api-openapi.yml
  format: yaml
  label: fxapis-com Webhooks API
  slug: fxapis-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-webhooks-api-openapi.yml
- filename: fxapis-com-workspace-api-openapi.yml
  format: yaml
  label: fxapis-com Workspace API
  slug: fxapis-com-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-workspace-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, password (stored only as a one-way hash), role in your workspace, whether your email is verified, the workspace name.
  - category: contact
    text: Enterprise enquiries Name, work email, company, role, website, phone, what you are building, your message, time zone, the country your request came from
  - category: financial
    text: Plan, invoices, amounts, payment status, the payment provider's references and the last digits and brand of a card if the provider returns them.
  - category: device
    text: the device model, operating system version and browser your browser reports, and a hash of its settings (screen, time zone, languages, graphics)
  - category: location
    text: IP address, request path and method, response status, timing, request identifier, and error details
  - category: behavioral
    text: Orders and their outcomes, deals, positions, multi-account orders, broker return codes, and the timestamps of each.
  - category: communication
    text: Emails you send us and our replies.
  deletion:
    route: Email to the privacy contact
    text: You can ask to see, correct, export or delete your data at [email protected] .
  dpa:
    available: null
    text: Data management terms
    url: null
  purposes:
  - purpose: Providing the Service
    text: 'Providing the Service: accounts, sign-in, connecting MT5 accounts, transmitting orders, recording outcomes'
  - purpose: Billing and financial records
    text: Billing, invoicing and collecting payment; keeping financial records
  - purpose: Security
    text: 'Security: preventing fraud, abuse and unauthorised access; investigating incidents; rate limiting'
  - purpose: Improving the Service
    text: Improving the Service using aggregated, de-identified usage information
  residency:
  - region: European Union
    text: Our servers and databases are hosted in the European Union.
  retention:
  - period: within 30 days of closure
    scope: Account and workspace data
    text: Account and workspace data — while your account is open, then deleted within 30 days of closure, except as below.
  - period: until you disconnect the account or close your workspace
    scope: Broker passwords
    text: Broker passwords — until you disconnect the account or close your workspace, when they are erased immediately.
  - period: up to seven days from sign-in
    scope: Sign-in sessions
    text: Sign-in sessions — up to seven days from sign-in, ending sooner after a day unused, or until you sign out.
  - period: typically up to 10 years
    scope: Invoices and payment records
    text: Invoices and payment records — as long as tax and accounting law requires, typically up to 10 years.
  - period: up to 24 months after our last contact
    scope: Enterprise enquiries
    text: Enterprise enquiries — up to 24 months after our last contact, unless they lead to a contract.
  - period: up to 30 days
    scope: Technical logs
    text: Technical logs — up to 30 days, longer only when needed to investigate a specific incident.
  rights:
  - right: access
    text: access the personal data we hold about you and receive a copy
  - right: correction
    text: have inaccurate data corrected
  - right: deletion
    text: have your data deleted, where we have no overriding legal reason to keep it
  - right: restriction or objection
    text: restrict or object to our use of it, including where we rely on legitimate interests
  - right: portability
    text: receive data you gave us in a portable, machine-readable form
  - right: withdraw consent
    text: withdraw consent, where we rely on consent, without affecting what was done before
  role:
    text: For your own account, billing and our websites, we decide how and why data is used — we are the controller .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data, or share it for cross-context behavioural advertising.
  subprocessors:
    text: The current list of providers is kept in our Data management terms .
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses (and the UK addendum) or another lawful transfer mechanism
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fxapis-com
provenance_date: '2026-11-09'
provider_name: fxapis-com
provider_slug: fxapis-com
slug: fxapis-com-privacy-policy
source_date: '2026-11-09'
source_filename: fxapis-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fxapis.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fxapis-com\naid: fxapis-com\nurl: https://fxapis.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your own account, billing and our websites, we decide how and why data is used — we are the controller\n    .\ndata_categories:\n- category: identifying\n  text: Name, email address, password (stored only as a one-way hash), role in your workspace, whether your email\n    is verified, the workspace name.\n- category: contact\n  text: Enterprise enquiries Name, work email, company, role, website, phone, what you are building, your message,\n    time zone, the country your request\
  \ came from\n- category: financial\n  text: Plan, invoices, amounts, payment status, the payment provider's references and the last digits and brand\n    of a card if the provider returns them.\n- category: device\n  text: the device model, operating system version and browser your browser reports, and a hash of its settings\n    (screen, time zone, languages, graphics)\n- category: location\n  text: IP address, request path and method, response status, timing, request identifier, and error details\n- category: behavioral\n  text: Orders and their outcomes, deals, positions, multi-account orders, broker return codes, and the timestamps\n    of each.\n- category: communication\n  text: Emails you send us and our replies.\npurposes:\n- purpose: Providing the Service\n  text: 'Providing the Service: accounts, sign-in, connecting MT5 accounts, transmitting orders, recording outcomes'\n- purpose: Billing and financial records\n  text: Billing, invoicing and collecting payment; keeping financial\
  \ records\n- purpose: Security\n  text: 'Security: preventing fraud, abuse and unauthorised access; investigating incidents; rate limiting'\n- purpose: Improving the Service\n  text: Improving the Service using aggregated, de-identified usage information\nretention:\n- scope: Account and workspace data\n  period: within 30 days of closure\n  text: Account and workspace data — while your account is open, then deleted within 30 days of closure, except\n    as below.\n- scope: Broker passwords\n  period: until you disconnect the account or close your workspace\n  text: Broker passwords — until you disconnect the account or close your workspace, when they are erased immediately.\n- scope: Sign-in sessions\n  period: up to seven days from sign-in\n  text: Sign-in sessions — up to seven days from sign-in, ending sooner after a day unused, or until you sign out.\n- scope: Invoices and payment records\n  period: typically up to 10 years\n  text: Invoices and payment records — as long as tax and\
  \ accounting law requires, typically up to 10 years.\n- scope: Enterprise enquiries\n  period: up to 24 months after our last contact\n  text: Enterprise enquiries — up to 24 months after our last contact, unless they lead to a contract.\n- scope: Technical logs\n  period: up to 30 days\n  text: Technical logs — up to 30 days, longer only when needed to investigate a specific incident.\nresidency:\n- region: European Union\n  text: Our servers and databases are hosted in the European Union.\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses (and the UK addendum) or another lawful\n    transfer mechanism\nsubprocessors:\n  url: null\n  text: The current list of providers is kept in our Data management terms .\ndpa:\n  available: null\n  url: null\n  text: Data management terms\ndeletion:\n  route: Email to the privacy contact\n  text: You can ask to see, correct, export or delete your data at [email protected] .\nrights:\n- right: access\n\
  \  text: access the personal data we hold about you and receive a copy\n- right: correction\n  text: have inaccurate data corrected\n- right: deletion\n  text: have your data deleted, where we have no overriding legal reason to keep it\n- right: restriction or objection\n  text: restrict or object to our use of it, including where we rely on legitimate interests\n- right: portability\n  text: receive data you gave us in a portable, machine-readable form\n- right: withdraw consent\n  text: withdraw consent, where we rely on consent, without affecting what was done before\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data, or share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/fxapis-com/privacy/fxapis-com-privacy-policy.yml
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
summary_line: 30 quoted statements, read from fxapis-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Trading
- MT5
- Cloud
---
