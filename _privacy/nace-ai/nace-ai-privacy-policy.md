---
api_specs:
- filename: nace-ai-health-api-openapi.yml
  format: yaml
  label: Nace Ai Health API
  slug: nace-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nace-ai/openapi/nace-ai-health-api-openapi.yml
- filename: nace-ai-public-api-api-openapi.yml
  format: yaml
  label: Nace Ai Public API
  slug: nace-ai-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nace-ai/openapi/nace-ai-public-api-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email address, organization name, role, and team membership.'
  - category: financial
    text: 'Billing information: your payment processor customer identifier, transaction history, and links to receipts and invoices.'
  - category: location
    text: 'Approximate location: derived from your IP address, at the country or city level.'
  - category: device
    text: 'Device and log data: IP address, browser type and version, operating system, device identifiers, referring URLs, and pages viewed in the Console.'
  - category: behavioral
    text: 'API and usage data: API keys used (in partially masked form), endpoints and MCP tools called, request and response metadata'
  - category: other
    text: 'Customer Content: Inputs and Outputs, including any personal information they contain.'
  deletion:
    route: Delete Account in the Console, or email support@nace.ai
    text: 'In the Console: you can update your account name, revoke API keys, and delete your Account, which deletes your Customer Content as described in Section 5.7 of our Terms of Service.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Services
    text: Provide the Services , including creating and managing your Account, authenticating you, issuing API keys, processing Inputs and returning Outputs
  - purpose: Bill and manage account
    text: Bill you and manage your Account , including tracking usage, applying Free Tier limits and credits, processing payments, and preventing fraud.
  - purpose: Security and abuse prevention
    text: Secure the Services and prevent abuse
  - purpose: Model training restriction
    text: We do not use Customer Content to train, fine-tune, evaluate, or improve general-purpose or shared Models, or to create training or evaluation datasets, unless you separately and expressly authorize that use in writing
  - purpose: Marketing
    text: Market our Services , such as product updates, newsletters, and event invitations.
  residency:
  - region: United States
    text: Nace is based in the United States, and we and our service providers process and store personal information in the United States and other countries where our service providers operate.
  retention:
  - period: for as long as your Account is active
    scope: Account information
    text: 'Account information: for as long as your Account is active.'
  - period: 30 days
    scope: Misuse-screening archive
    text: for accounts in Standard mode, the text of Decision model requests (not images) is kept for 30 days in a separate archive
  - period: up to 13 months
    scope: API logs and usage metadata
    text: kept with your user and API-key identifiers for up to 13 months for security, debugging, and billing.
  - period: null
    scope: Billing records
    text: for at least as long as tax and accounting laws require (typically 7 years after the Account is closed).
  - period: up to 35 days
    scope: Backups
    text: Deleted data may persist in backups we control for up to 35 days before being permanently removed
  rights:
  - right: Know and access
    text: Know and access the categories and specific pieces of personal information we collect
  - right: Correct
    text: Correct inaccurate personal information
  - right: Delete
    text: Delete personal information
  - right: Portability
    text: Obtain a copy of your personal information in a portable format
  - right: Opt out of sale or sharing
    text: Opt out of the sale or sharing of personal information, targeted advertising, and certain profiling
  - right: Non-discrimination
    text: Not be discriminated against for exercising these rights.
  role:
    text: Nace decides how this information is used, and this Privacy Notice applies to it in full.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not "share" personal information for cross-context behavioral advertising
  subprocessors:
    text: A current list of our service providers that process Customer Content is available at trust.nace.ai/subprocessors .
    url: trust.nace.ai/subprocessors
  transfers:
  - mechanism: other
    text: If you use the Services from outside the United States, your information will be transferred to, and processed in, the United States
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nace Ai
provenance_date: '2026-11-10'
provider_name: Nace Ai
provider_slug: nace-ai
slug: nace-ai-privacy-policy
source_date: '2026-11-10'
source_filename: nace-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.nace.ai/policies/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nace Ai\naid: nace-ai\nurl: https://www.nace.ai/policies/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Nace decides how this information is used, and this Privacy Notice applies to it in full.\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email address, organization name, role, and team membership.'\n- category: financial\n  text: 'Billing information: your payment processor customer identifier, transaction history, and links to receipts\n    and invoices.'\n- category: location\n  text: 'Approximate location: derived from your IP address, at the\
  \ country or city level.'\n- category: device\n  text: 'Device and log data: IP address, browser type and version, operating system, device identifiers, referring\n    URLs, and pages viewed in the Console.'\n- category: behavioral\n  text: 'API and usage data: API keys used (in partially masked form), endpoints and MCP tools called, request and\n    response metadata'\n- category: other\n  text: 'Customer Content: Inputs and Outputs, including any personal information they contain.'\npurposes:\n- purpose: Provide the Services\n  text: Provide the Services , including creating and managing your Account, authenticating you, issuing API keys,\n    processing Inputs and returning Outputs\n- purpose: Bill and manage account\n  text: Bill you and manage your Account , including tracking usage, applying Free Tier limits and credits, processing\n    payments, and preventing fraud.\n- purpose: Security and abuse prevention\n  text: Secure the Services and prevent abuse\n- purpose: Model training\
  \ restriction\n  text: We do not use Customer Content to train, fine-tune, evaluate, or improve general-purpose or shared Models,\n    or to create training or evaluation datasets, unless you separately and expressly authorize that use in writing\n- purpose: Marketing\n  text: Market our Services , such as product updates, newsletters, and event invitations.\nretention:\n- scope: Account information\n  period: for as long as your Account is active\n  text: 'Account information: for as long as your Account is active.'\n- scope: Misuse-screening archive\n  period: 30 days\n  text: for accounts in Standard mode, the text of Decision model requests (not images) is kept for 30 days in a\n    separate archive\n- scope: API logs and usage metadata\n  period: up to 13 months\n  text: kept with your user and API-key identifiers for up to 13 months for security, debugging, and billing.\n- scope: Billing records\n  period: null\n  text: for at least as long as tax and accounting laws require (typically\
  \ 7 years after the Account is closed).\n- scope: Backups\n  period: up to 35 days\n  text: Deleted data may persist in backups we control for up to 35 days before being permanently removed\nresidency:\n- region: United States\n  text: Nace is based in the United States, and we and our service providers process and store personal information\n    in the United States and other countries where our service providers operate.\ntransfers:\n- mechanism: other\n  text: If you use the Services from outside the United States, your information will be transferred to, and processed\n    in, the United States\nsubprocessors:\n  url: trust.nace.ai/subprocessors\n  text: A current list of our service providers that process Customer Content is available at trust.nace.ai/subprocessors\n    .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete Account in the Console, or email support@nace.ai\n  text: 'In the Console: you can update your account name, revoke API keys, and delete\
  \ your Account, which deletes\n    your Customer Content as described in Section 5.7 of our Terms of Service.'\nrights:\n- right: Know and access\n  text: Know and access the categories and specific pieces of personal information we collect\n- right: Correct\n  text: Correct inaccurate personal information\n- right: Delete\n  text: Delete personal information\n- right: Portability\n  text: Obtain a copy of your personal information in a portable format\n- right: Opt out of sale or sharing\n  text: Opt out of the sale or sharing of personal information, targeted advertising, and certain profiling\n- right: Non-discrimination\n  text: Not be discriminated against for exercising these rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not \"share\" personal information for cross-context behavioral\n    advertising\n"
source_yaml_url: https://artifacts.apis.io/nace-ai/privacy/nace-ai-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Nace Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Intelligence
- Document Processing
- Data Extraction
- OCR
- Machine Learning
- Enterprise Automation
- MCP
---
