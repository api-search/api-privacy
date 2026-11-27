---
api_specs:
- filename: agentready-market-openapi-generated.yml
  format: yaml
  label: AgentReady API
  slug: agentready-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentready-market/openapi/_ae-authored/agentready-market-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — when you submit a scan, capture a report, or subscribe.
  - category: identifying
    text: Store URLs you submit and the resulting scan data (public page data only).
  - category: financial
    text: Payment data — handled directly by our processor Mollie; we do not store card details.
  - category: device
    text: Basic technical data (e.g. IP address) for rate-limiting and abuse prevention.
  - category: behavioral
    text: Visitors are counted via a salted hash that rotates daily and cannot identify you across days.
  deletion:
    route: Signed-in users can delete their account and personal data from the dashboard, or contact hello@agentready.market
    text: Signed-in users can delete their account and personal data directly from their dashboard ("Delete my account & data"); or contact hello@agentready.market
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: To provide the Service (scan, score, recommend, monitor)
  - purpose: Billing
    text: to bill Pro payments
  - purpose: Service emails
    text: to send service emails (e.g. score-drop alerts)
  - purpose: Improve benchmarks
    text: to improve our benchmarks in aggregate
  retention:
  - period: null
    scope: All personal data
    text: We keep data only as long as needed for the Service.
  rights:
  - right: access
    text: you may request access, correction, deletion or export of your personal data
  - right: correction
    text: you may request access, correction, deletion or export of your personal data
  - right: deletion
    text: you may request access, correction, deletion or export of your personal data
  - right: export
    text: you may request access, correction, deletion or export of your personal data
  role:
    text: is the data controller for personal data processed through the Service
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Render — hosting & database. Mollie — payments. Postmark — transactional email.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentReady
provenance_date: '2026-11-09'
provider_name: AgentReady
provider_slug: agentready-market
slug: agentready-market-privacy-policy
source_date: '2026-11-09'
source_filename: agentready-market-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.agentready.market/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentReady\naid: agentready-market\nurl: https://www.agentready.market/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: is the data controller for personal data processed through the Service\ndata_categories:\n- category: contact\n  text: Email address — when you submit a scan, capture a report, or subscribe.\n- category: identifying\n  text: Store URLs you submit and the resulting scan data (public page data only).\n- category: financial\n  text: Payment data — handled directly by our processor Mollie; we do not store card details.\n- category: device\n  text: Basic technical data (e.g.\
  \ IP address) for rate-limiting and abuse prevention.\n- category: behavioral\n  text: Visitors are counted via a salted hash that rotates daily and cannot identify you across days.\npurposes:\n- purpose: Provide the Service\n  text: To provide the Service (scan, score, recommend, monitor)\n- purpose: Billing\n  text: to bill Pro payments\n- purpose: Service emails\n  text: to send service emails (e.g. score-drop alerts)\n- purpose: Improve benchmarks\n  text: to improve our benchmarks in aggregate\nretention:\n- scope: All personal data\n  period: null\n  text: We keep data only as long as needed for the Service.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Render — hosting & database. Mollie — payments. Postmark — transactional email.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Signed-in users can delete their account and personal data from the dashboard, or contact hello@agentready.market\n  text: Signed-in users can delete their account\
  \ and personal data directly from their dashboard (\"Delete my account\n    & data\"); or contact hello@agentready.market\nrights:\n- right: access\n  text: you may request access, correction, deletion or export of your personal data\n- right: correction\n  text: you may request access, correction, deletion or export of your personal data\n- right: deletion\n  text: you may request access, correction, deletion or export of your personal data\n- right: export\n  text: you may request access, correction, deletion or export of your personal data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentready-market/privacy/agentready-market-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from AgentReady's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- E-Commerce
- Audit
- Software-as-a-Service
- Netherlands
---
