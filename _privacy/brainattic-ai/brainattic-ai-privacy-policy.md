---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email, organisation, a securely hashed password where you set one
  - category: contact
    text: an email address, a Slack member ID, or a mobile phone number
  - category: device
    text: basic device/browser metadata in operational and security logs
  - category: identifying
    text: IP address, timestamps, endpoint/request and status, correlation identifier
  - category: behavioral
    text: Document-search logs contain the query text, up to 500 characters, the searching account's identifier
  deletion:
    route: Authorised immediate-deletion request executed by FSS, or customer-initiated closure with a cancellable 14-day window
    text: An authorised immediate-deletion request, executed by FSS, removes live data without creating a recovery archive.
  dpa:
    available: true
    text: This processing is governed by our Data Processing Agreement .
    url: null
  purposes:
  - purpose: Provide Customer Content functions, search, retrieval, exports, and reminders
    text: Provide Customer Content functions, search, retrieval, exports, and reminders
  - purpose: Create and operate accounts, authenticate users
    text: Create and operate accounts, authenticate users, administer access, and keep contract-acceptance evidence
  - purpose: Secure the website and Service, prevent abuse
    text: Secure the website and Service, prevent abuse, and keep operational logs, including reCAPTCHA where enabled
  residency:
  - region: Bulgaria (EU)
    text: FSS stores core Service data on infrastructure in Bulgaria, European Union .
  retention:
  - period: While the workspace is active
    scope: Customer Content and live tenant data
    text: Customer Content and live tenant data While the workspace is active.
  - period: 90 days
    scope: MCP access events
    text: MCP access events 90 days by default; your organisation's administrators may set between 1 and 730 days.
  - period: 90 days
    scope: Search log
    text: Search log 90 days by default; FSS may set a different period for your workspace on request.
  - period: 30 days
    scope: Application and security logs
    text: Application and security logs 30 days .
  rights:
  - right: access, rectification, erasure, restriction, data portability, objection
    text: Subject to the GDPR, you may have rights of access , rectification , erasure , restriction , and data portability , and the right to object to processing based on legitimate interests.
  - right: complain to supervisory authority
    text: You may complain to the Commission for Personal Data Protection (CPDP) , www.cpdp.bg , or another competent EU supervisory authority.
  role:
    text: Here FSS is the controller because FSS determines why and how that data is used to operate, secure, administer, and support the Service.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, use Customer Content for advertising, build behavioural advertising profiles inside brainattic, or make automated eligibility decisions.
  subprocessors:
    text: 'The following external parties may be involved:'
    url: null
  transfers:
  - mechanism: SCC
    text: For the LinkedIn relevant products described above, restricted EU transfers use Module 1 controller-to-controller Standard Contractual Clauses under the LinkedIn Independent Controller Addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: brainattic
provenance_date: '2026-11-09'
provider_name: brainattic
provider_slug: brainattic-ai
slug: brainattic-ai-privacy-policy
source_date: '2026-11-09'
source_filename: brainattic-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://brainattic.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: brainattic\naid: brainattic-ai\nurl: https://brainattic.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Here FSS is the controller because FSS determines why and how that data is used to operate, secure, administer,\n    and support the Service.\ndata_categories:\n- category: identifying\n  text: Name, work email, organisation, a securely hashed password where you set one\n- category: contact\n  text: an email address, a Slack member ID, or a mobile phone number\n- category: device\n  text: basic device/browser metadata in operational and security logs\n- category: identifying\n  text:\
  \ IP address, timestamps, endpoint/request and status, correlation identifier\n- category: behavioral\n  text: Document-search logs contain the query text, up to 500 characters, the searching account's identifier\npurposes:\n- purpose: Provide Customer Content functions, search, retrieval, exports, and reminders\n  text: Provide Customer Content functions, search, retrieval, exports, and reminders\n- purpose: Create and operate accounts, authenticate users\n  text: Create and operate accounts, authenticate users, administer access, and keep contract-acceptance evidence\n- purpose: Secure the website and Service, prevent abuse\n  text: Secure the website and Service, prevent abuse, and keep operational logs, including reCAPTCHA where enabled\nretention:\n- scope: Customer Content and live tenant data\n  period: While the workspace is active\n  text: Customer Content and live tenant data While the workspace is active.\n- scope: MCP access events\n  period: 90 days\n  text: MCP access events\
  \ 90 days by default; your organisation's administrators may set between 1 and 730 days.\n- scope: Search log\n  period: 90 days\n  text: Search log 90 days by default; FSS may set a different period for your workspace on request.\n- scope: Application and security logs\n  period: 30 days\n  text: Application and security logs 30 days .\nresidency:\n- region: Bulgaria (EU)\n  text: FSS stores core Service data on infrastructure in Bulgaria, European Union .\ntransfers:\n- mechanism: SCC\n  text: For the LinkedIn relevant products described above, restricted EU transfers use Module 1 controller-to-controller\n    Standard Contractual Clauses under the LinkedIn Independent Controller Addendum.\nsubprocessors:\n  url: null\n  text: 'The following external parties may be involved:'\ndpa:\n  available: true\n  url: null\n  text: This processing is governed by our Data Processing Agreement .\ndeletion:\n  route: Authorised immediate-deletion request executed by FSS, or customer-initiated closure\
  \ with a cancellable\n    14-day window\n  text: An authorised immediate-deletion request, executed by FSS, removes live data without creating a recovery\n    archive.\nrights:\n- right: access, rectification, erasure, restriction, data portability, objection\n  text: Subject to the GDPR, you may have rights of access , rectification , erasure , restriction , and data portability\n    , and the right to object to processing based on legitimate interests.\n- right: complain to supervisory authority\n  text: You may complain to the Commission for Personal Data Protection (CPDP) , www.cpdp.bg , or another competent\n    EU supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, use Customer Content for advertising, build behavioural advertising profiles\n    inside brainattic, or make automated eligibility decisions.\n"
source_yaml_url: https://artifacts.apis.io/brainattic-ai/privacy/brainattic-ai-privacy-policy.yml
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
summary_line: 21 quoted statements, read from brainattic's own page on 2026-11-09.
synthetic: false
tags:
- Knowledge Base
- Artificial Intelligence
- Enterprise
- Governance
- MCP
- Company
---
