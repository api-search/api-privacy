---
api_specs:
- filename: hourtick-account-api-openapi.yml
  format: yaml
  label: Hourtick Account API
  slug: hourtick-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-account-api-openapi.yml
- filename: hourtick-agents-api-openapi.yml
  format: yaml
  label: Hourtick Agents API
  slug: hourtick-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-agents-api-openapi.yml
- filename: hourtick-billing-api-openapi.yml
  format: yaml
  label: Hourtick Billing API
  slug: hourtick-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-billing-api-openapi.yml
- filename: hourtick-catalog-api-openapi.yml
  format: yaml
  label: Hourtick Catalog API
  slug: hourtick-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-catalog-api-openapi.yml
- filename: hourtick-chat-api-openapi.yml
  format: yaml
  label: Hourtick Chat API
  slug: hourtick-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-chat-api-openapi.yml
- filename: hourtick-integrations-api-openapi.yml
  format: yaml
  label: Hourtick Integrations API
  slug: hourtick-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-integrations-api-openapi.yml
- filename: hourtick-invoices-api-openapi.yml
  format: yaml
  label: Hourtick Invoices API
  slug: hourtick-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-invoices-api-openapi.yml
- filename: hourtick-notes-and-files-api-openapi.yml
  format: yaml
  label: Hourtick Notes and files API
  slug: hourtick-notes-and-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-notes-and-files-api-openapi.yml
- filename: hourtick-reports-api-openapi.yml
  format: yaml
  label: Hourtick Reports API
  slug: hourtick-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-reports-api-openapi.yml
- filename: hourtick-tasks-api-openapi.yml
  format: yaml
  label: Hourtick Tasks API
  slug: hourtick-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-tasks-api-openapi.yml
- filename: hourtick-team-api-openapi.yml
  format: yaml
  label: Hourtick Team API
  slug: hourtick-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-team-api-openapi.yml
- filename: hourtick-time-api-openapi.yml
  format: yaml
  label: Hourtick Time API
  slug: hourtick-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hourtick/openapi/hourtick-time-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email address, password hash (never the password itself)'
  - category: contact
    text: 'Communications: messages you send us through the contact form (name, email, topic, message and the page you sent it from).'
  - category: financial
    text: 'Billing data (Pro plan): billing name and email, Stripe customer and subscription identifiers, plan status.'
  - category: location
    text: Hourtick does not take screenshots, record keystrokes, log the apps or websites you use, or track your location.
  - category: behavioral
    text: 'Where you came from: if you allowed analytics on our website (or, outside the EU, the EEA, the UK and Switzerland, didn''t say no), the first page you visited'
  - category: device
    text: 'Technical data: IP address, browser user agent, request timestamps and error logs, needed to operate and secure the service.'
  - category: communication
    text: 'Team chat: channels, direct messages, threads, messages, reactions and shared files, and which conversations you''ve read.'
  deletion:
    route: Settings (web, iPhone or Android app) or hourtick.com/delete-account
    text: You can delete your account yourself in Settings (web, iPhone or Android app).
  dpa:
    available: true
    text: For the time-tracking data your organisation puts into a workspace, your organisation is the controller and we process it on its behalf under our Data Processing Agreement.
    url: https://hourtick.com/dpa
  purposes:
  - purpose: Provide the service
    text: To provide the service you signed up for — performance of a contract (GDPR Art. 6(1)(b)).
  - purpose: Payments and accounting
    text: To process payments and keep accounting records — contract and legal obligation (Art. 6(1)(b) and (c)).
  - purpose: Security and abuse prevention
    text: To secure the service, prevent abuse and fix errors — legitimate interests (Art. 6(1)(f)).
  - purpose: Website analytics
    text: To understand how visitors use our public website (Google Analytics).
  residency:
  - region: EU (Germany)
    text: Hourtick stores its application data and database in the EU, with Akamai Cloud (Linode), Frankfurt, Germany.
  retention:
  - period: null
    scope: Account and workspace data
    text: 'Account and workspace data: for as long as your account or workspace exists.'
  - period: five years
    scope: Billing records
    text: 'Billing records: as long as required by Danish bookkeeping law (currently five years from the end of the financial year).'
  - period: 30 days
    scope: Server logs
    text: 'Server logs: 30 days, unless needed to investigate a specific security incident.'
  - period: 90 days
    scope: Cookies
    text: The cookies on your browser expire after 90 days.
  rights:
  - right: Access, rectify, erase
    text: You have the right to access, rectify and erase your personal data, to restrict or object to processing, and to data portability.
  - right: Data portability / export
    text: You can export your time data as CSV at any time.
  - right: Complaint to supervisory authority
    text: You may lodge a complaint with a supervisory authority.
  role:
    text: For personal data about account holders and website visitors, we are the controller. For the time-tracking data your organisation puts into a workspace, your organisation is the controller and we process it on its behalf under our Data Processing Agreement.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The current list is on our Subprocessors page.
    url: https://hourtick.com/subprocessors
  transfers:
  - mechanism: DPF
    text: Where they do, transfers rely on the EU–US Data Privacy Framework, in which these companies participate, or on the European Commission's Standard Contractual Clauses in their data processing terms.
  - mechanism: SCC
    text: or on the European Commission's Standard Contractual Clauses in their data processing terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hourtick
provenance_date: '2026-11-09'
provider_name: Hourtick
provider_slug: hourtick
slug: hourtick-privacy-policy
source_date: '2026-11-09'
source_filename: hourtick-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hourtick.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hourtick\naid: hourtick\nurl: https://hourtick.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For personal data about account holders and website visitors, we are the controller. For the time-tracking\n    data your organisation puts into a workspace, your organisation is the controller and we process it on its behalf\n    under our Data Processing Agreement.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email address, password hash (never the password itself)'\n- category: contact\n  text: 'Communications: messages you send us through the contact form (name,\
  \ email, topic, message and the page\n    you sent it from).'\n- category: financial\n  text: 'Billing data (Pro plan): billing name and email, Stripe customer and subscription identifiers, plan status.'\n- category: location\n  text: Hourtick does not take screenshots, record keystrokes, log the apps or websites you use, or track your location.\n- category: behavioral\n  text: 'Where you came from: if you allowed analytics on our website (or, outside the EU, the EEA, the UK and Switzerland,\n    didn''t say no), the first page you visited'\n- category: device\n  text: 'Technical data: IP address, browser user agent, request timestamps and error logs, needed to operate and\n    secure the service.'\n- category: communication\n  text: 'Team chat: channels, direct messages, threads, messages, reactions and shared files, and which conversations\n    you''ve read.'\npurposes:\n- purpose: Provide the service\n  text: To provide the service you signed up for — performance of a contract (GDPR\
  \ Art. 6(1)(b)).\n- purpose: Payments and accounting\n  text: To process payments and keep accounting records — contract and legal obligation (Art. 6(1)(b) and (c)).\n- purpose: Security and abuse prevention\n  text: To secure the service, prevent abuse and fix errors — legitimate interests (Art. 6(1)(f)).\n- purpose: Website analytics\n  text: To understand how visitors use our public website (Google Analytics).\nretention:\n- scope: Account and workspace data\n  period: null\n  text: 'Account and workspace data: for as long as your account or workspace exists.'\n- scope: Billing records\n  period: five years\n  text: 'Billing records: as long as required by Danish bookkeeping law (currently five years from the end of the\n    financial year).'\n- scope: Server logs\n  period: 30 days\n  text: 'Server logs: 30 days, unless needed to investigate a specific security incident.'\n- scope: Cookies\n  period: 90 days\n  text: The cookies on your browser expire after 90 days.\nresidency:\n-\
  \ region: EU (Germany)\n  text: Hourtick stores its application data and database in the EU, with Akamai Cloud (Linode), Frankfurt, Germany.\ntransfers:\n- mechanism: DPF\n  text: Where they do, transfers rely on the EU–US Data Privacy Framework, in which these companies participate,\n    or on the European Commission's Standard Contractual Clauses in their data processing terms.\n- mechanism: SCC\n  text: or on the European Commission's Standard Contractual Clauses in their data processing terms.\nsubprocessors:\n  url: https://hourtick.com/subprocessors\n  text: The current list is on our Subprocessors page.\ndpa:\n  available: true\n  url: https://hourtick.com/dpa\n  text: For the time-tracking data your organisation puts into a workspace, your organisation is the controller\n    and we process it on its behalf under our Data Processing Agreement.\ndeletion:\n  route: Settings (web, iPhone or Android app) or hourtick.com/delete-account\n  text: You can delete your account yourself in\
  \ Settings (web, iPhone or Android app).\nrights:\n- right: Access, rectify, erase\n  text: You have the right to access, rectify and erase your personal data, to restrict or object to processing,\n    and to data portability.\n- right: Data portability / export\n  text: You can export your time data as CSV at any time.\n- right: Complaint to supervisory authority\n  text: You may lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hourtick/privacy/hourtick-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Hourtick's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collaboration
- Artificial Intelligence
- Time Tracking
- Project Management
---
