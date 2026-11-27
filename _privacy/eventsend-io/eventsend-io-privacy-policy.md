---
api_specs:
- filename: eventsend-io-openapi-generated.yml
  format: yaml
  label: EventSend API
  slug: eventsend-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventsend-io/openapi/_ae-authored/eventsend-io-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, and time zone.
  - category: contact
    text: the contact and invoicing email addresses you give us
  - category: financial
    text: a customer reference from our payment processor
  - category: communication
    text: 'The events your applications and connected services submit: an event name, a severity, a message, and any structured data you choose to include'
  - category: device
    text: the network address a request came from, the time, the pages or endpoints requested, and diagnostic information when something fails
  deletion:
    route: Automatic deletion at end of retention window; account closure deletes configuration and content
    text: Deletion is automatic — you do not need to ask.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service: accepting your events, applying your routing rules, and delivering them.'
  - purpose: Operate accounts
    text: 'To operate your account: signing you in, showing your history, and letting your team collaborate.'
  - purpose: Billing and legal records
    text: To bill you and keep the records we are legally required to keep.
  - purpose: Security
    text: 'To secure the service: preventing abuse, enforcing limits, investigating incidents.'
  - purpose: Support and service messages
    text: To support you when you ask, and to send you service messages about your account, your destinations, or your billing.
  residency:
  - region: United States
    text: The service is operated from the United States , and your information is processed there.
  retention:
  - period: 7 days to 90 days
    scope: Events and delivery records
    text: it currently ranges from 7 days to 90 days depending on plan
  - period: one year
    scope: Records of significant account actions
    text: Records of significant account actions — for example who changed a setting, and when — are kept for one year after an organization is closed
  - period: null
    scope: Financial records
    text: Financial records are kept for as long as tax and accounting law requires.
  rights:
  - right: access
    text: the right to access the information we hold about you
  - right: correct
    text: to correct it
  - right: delete
    text: to delete it
  - right: portability
    text: to receive a copy in a portable form
  - right: object or restrict
    text: to object to or restrict certain processing
  - right: withdraw consent
    text: to withdraw consent where we relied on it
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your information.
  subprocessors:
    text: A current list of these providers is available on request at [email protected] .
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards, including standard contractual clauses with our providers, for that transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EventSend
provenance_date: '2026-11-09'
provider_name: EventSend
provider_slug: eventsend-io
slug: eventsend-io-privacy-policy
source_date: '2026-11-09'
source_filename: eventsend-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eventsend.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EventSend\naid: eventsend-io\nurl: https://eventsend.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name, email address, and time zone.\n- category: contact\n  text: the contact and invoicing email addresses you give us\n- category: financial\n  text: a customer reference from our payment processor\n- category: communication\n  text: 'The events your applications and connected services submit: an event name, a severity, a message, and any\n    structured data you choose to include'\n- category: device\n  text: the network\
  \ address a request came from, the time, the pages or endpoints requested, and diagnostic information\n    when something fails\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service: accepting your events, applying your routing rules, and delivering them.'\n- purpose: Operate accounts\n  text: 'To operate your account: signing you in, showing your history, and letting your team collaborate.'\n- purpose: Billing and legal records\n  text: To bill you and keep the records we are legally required to keep.\n- purpose: Security\n  text: 'To secure the service: preventing abuse, enforcing limits, investigating incidents.'\n- purpose: Support and service messages\n  text: To support you when you ask, and to send you service messages about your account, your destinations, or\n    your billing.\nretention:\n- scope: Events and delivery records\n  period: 7 days to 90 days\n  text: it currently ranges from 7 days to 90 days depending on plan\n- scope: Records of significant\
  \ account actions\n  period: one year\n  text: Records of significant account actions — for example who changed a setting, and when — are kept for one\n    year after an organization is closed\n- scope: Financial records\n  period: null\n  text: Financial records are kept for as long as tax and accounting law requires.\nresidency:\n- region: United States\n  text: The service is operated from the United States , and your information is processed there.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards, including standard contractual clauses with our providers, for that transfer.\nsubprocessors:\n  url: null\n  text: A current list of these providers is available on request at [email protected] .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Automatic deletion at end of retention window; account closure deletes configuration and content\n  text: Deletion is automatic — you do not need to ask.\nrights:\n- right: access\n  text: the right\
  \ to access the information we hold about you\n- right: correct\n  text: to correct it\n- right: delete\n  text: to delete it\n- right: portability\n  text: to receive a copy in a portable form\n- right: object or restrict\n  text: to object to or restrict certain processing\n- right: withdraw consent\n  text: to withdraw consent where we relied on it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your information.\n"
source_yaml_url: https://artifacts.apis.io/eventsend-io/privacy/eventsend-io-privacy-policy.yml
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
summary_line: 24 quoted statements, read from EventSend's own page on 2026-11-09.
synthetic: false
tags:
- Event Tracking
- Analytics
- Webhook
- Integration
- Product Teams
---
