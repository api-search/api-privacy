---
api_specs:
- filename: octri-dev-openapi-generated.yml
  format: yaml
  label: Octri API
  slug: octri-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octri-dev/openapi/_ae-authored/octri-dev-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address and profile picture URL.
  - category: contact
    text: Records of transactional emails we sent you, so we can tell whether a password reset or an invite actually arrived.
  - category: financial
    text: Credit balances, usage counters and AI token totals used for metering and billing.
  - category: behavioral
    text: 'Page views: which page, and when.'
  - category: device
    text: the IP address and browser user agent, and whether it succeeded.
  - category: communication
    text: 'Ask-the-docs conversations: the question, our answer, the pages cited, and a random visitor id kept in the reader’s browser so a conversation holds together.'
  deletion:
    route: Delete a project or the whole organisation from its settings; or email support to erase everything held
    text: Closing an organisation, or asking us to erase everything we hold for you, is completed within 30 days, and monitoring data is removed on the same request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'To run the service: authenticate you, enforce permissions, generate docs and SDKs, host your documentation, and meter what you use.'
  - purpose: Billing
    text: 'To bill you: apply plan limits, charge subscriptions and credit packs through Paddle, and issue receipts.'
  - purpose: Security
    text: 'To keep the platform secure: audit logging, rate limiting, fraud and abuse detection.'
  - purpose: Product improvement
    text: 'To improve the product: aggregate usage figures showing which features get used.'
  - purpose: Marketing
    text: 'To market to you: product news and the newsletter, only where you opted in or where a soft opt-in applies to existing customers.'
  residency:
  - region: United States
    text: Octri is operated from the United States and our subprocessors operate in the United States and the European Economic Area.
  retention:
  - period: While the account exists
    scope: Account and organisation records
    text: Account and organisation records While the account exists Erased within 30 days of closing the organisation or asking us to.
  - period: 365 days
    scope: Security audit log
    text: Security audit log 365 days Sign-ins, permission changes, billing events. Deleted automatically.
  - period: 7 days
    scope: Ask-the-docs chat sessions
    text: Ask-the-docs chat sessions 7 days Questions, answers and the anonymous visitor id, then deleted.
  - period: 730 days
    scope: Free Spec Audit runs
    text: Free Spec Audit runs 730 days The audited spec's own info block, the score, a hashed IP and any email you asked us to send the report to.
  rights:
  - right: Access, correction, deletion, restriction, portability, withdraw consent
    text: Depending on where you live you may have the right to access your data, correct it, delete it, restrict or object to how we use it, receive a portable copy, and withdraw consent.
  - right: Non-discrimination (California)
    text: which also gives you a right not to be discriminated against for exercising them.
  role:
    text: We are the controller for data about our own customers
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, we do not share it for cross-context behavioural advertising
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission’s Standard Contractual Clauses and the UK Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Octri
provenance_date: '2026-11-10'
provider_name: Octri
provider_slug: octri-dev
slug: octri-dev-privacy-policy
source_date: '2026-11-10'
source_filename: octri-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://octri.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Octri\naid: octri-dev\nurl: https://octri.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for data about our own customers\ndata_categories:\n- category: identifying\n  text: Your name, email address and profile picture URL.\n- category: contact\n  text: Records of transactional emails we sent you, so we can tell whether a password reset or an invite actually\n    arrived.\n- category: financial\n  text: Credit balances, usage counters and AI token totals used for metering and billing.\n- category: behavioral\n  text: 'Page views: which page, and when.'\n- category:\
  \ device\n  text: the IP address and browser user agent, and whether it succeeded.\n- category: communication\n  text: 'Ask-the-docs conversations: the question, our answer, the pages cited, and a random visitor id kept in\n    the reader’s browser so a conversation holds together.'\npurposes:\n- purpose: Run the service\n  text: 'To run the service: authenticate you, enforce permissions, generate docs and SDKs, host your documentation,\n    and meter what you use.'\n- purpose: Billing\n  text: 'To bill you: apply plan limits, charge subscriptions and credit packs through Paddle, and issue receipts.'\n- purpose: Security\n  text: 'To keep the platform secure: audit logging, rate limiting, fraud and abuse detection.'\n- purpose: Product improvement\n  text: 'To improve the product: aggregate usage figures showing which features get used.'\n- purpose: Marketing\n  text: 'To market to you: product news and the newsletter, only where you opted in or where a soft opt-in applies\n    to existing\
  \ customers.'\nretention:\n- scope: Account and organisation records\n  period: While the account exists\n  text: Account and organisation records While the account exists Erased within 30 days of closing the organisation\n    or asking us to.\n- scope: Security audit log\n  period: 365 days\n  text: Security audit log 365 days Sign-ins, permission changes, billing events. Deleted automatically.\n- scope: Ask-the-docs chat sessions\n  period: 7 days\n  text: Ask-the-docs chat sessions 7 days Questions, answers and the anonymous visitor id, then deleted.\n- scope: Free Spec Audit runs\n  period: 730 days\n  text: Free Spec Audit runs 730 days The audited spec's own info block, the score, a hashed IP and any email you\n    asked us to send the report to.\nresidency:\n- region: United States\n  text: Octri is operated from the United States and our subprocessors operate in the United States and the European\n    Economic Area.\ntransfers:\n- mechanism: SCC\n  text: we rely on the European\
  \ Commission’s Standard Contractual Clauses and the UK Addendum\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a project or the whole organisation from its settings; or email support to erase everything held\n  text: Closing an organisation, or asking us to erase everything we hold for you, is completed within 30 days,\n    and monitoring data is removed on the same request.\nrights:\n- right: Access, correction, deletion, restriction, portability, withdraw consent\n  text: Depending on where you live you may have the right to access your data, correct it, delete it, restrict\n    or object to how we use it, receive a portable copy, and withdraw consent.\n- right: Non-discrimination (California)\n  text: which also gives you a right not to be discriminated against for exercising them.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, we do not share it for cross-context behavioural\
  \ advertising\n"
source_yaml_url: https://artifacts.apis.io/octri-dev/privacy/octri-dev-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Octri's own page on 2026-11-10.
synthetic: false
tags:
- Company
- OpenAPI
- Documentation
- SDK
- Monitoring
- MCP
- API Tooling
- API Documentation
- SDK Generation
- API Monitoring
- SDK Monitoring
---
