---
api_specs:
- filename: agentcentral-to-openapi-generated.yml
  format: yaml
  label: Agent Central API
  slug: agentcentral-to-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcentral-to/openapi/_ae-authored/agentcentral-to-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: email address, first and last name, and phone number provided when you sign up
  - category: identifying
    text: account identifiers, authentication state, and privacy and versioned Terms acceptance records
  - category: device
    text: IP address, browser or device information, request and response metadata, timestamps, authentication events
  - category: communication
    text: Support communications — messages, diagnostic details, and attachments you send when requesting help or reporting a problem.
  - category: financial
    text: plan and subscription state, invoices and billing events, order measurements used for tiering
  - category: behavioral
    text: Website analytics — cookieless page counts through Vercel Analytics
  - category: other
    text: Amazon OAuth tokens — access and refresh tokens issued by Amazon through its official OAuth flow, encrypted at rest.
  deletion:
    route: dashboard
    text: You can start account deletion from the dashboard; the live tenant dataset, credentials, keys, and mutable account state are then removed through the deletion process.
  dpa:
    available: true
    text: Our Data Processing Agreement forms part of our Terms of Service and applies whenever we process personal data on your behalf.
    url: null
  purposes:
  - purpose: sync and serve Amazon seller data to AI agent
    text: To sync and serve your Amazon seller data to your AI agent.
  - purpose: authenticate account and manage subscription
    text: To authenticate your account and manage your subscription.
  - purpose: advertising delivery
    text: To deliver and measure advertising. We may share limited account information with advertising service providers for this purpose.
  - purpose: product improvement
    text: Product analytics and product improvement use usage data and operational metadata, not your Amazon business data.
  residency:
  - region: United States
    text: Agent Central is operated from the United States.
  retention:
  - period: null
    scope: Amazon data
    text: We retain your Amazon data while your account remains active.
  - period: up to 90 days
    scope: First-party marketing attribution
    text: First-party marketing attribution is kept for up to 90 days unless you withdraw consent sooner.
  - period: 24 hours
    scope: Vercel visit hash
    text: Vercel groups a visit using a hash of the request that it discards after 24 hours.
  rights:
  - right: access
    text: Access a copy of your personal data
  - right: correct
    text: Correct inaccurate data
  - right: delete
    text: Delete your account and associated data, subject to limited lawful retention
  - right: restrict or object
    text: Restrict or object to certain processing
  - right: portability
    text: Data portability (receive your data in a structured format)
  - right: complain
    text: Lodge a complaint with your local data protection authority (EEA/UK residents)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: Subprocessors Provider Purpose Data processed Location Google Cloud Platform Data storage, processing, encryption
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses (SCCs) approved by the European Commission to safeguard these transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Central
provenance_date: '2026-11-09'
provider_name: Agent Central
provider_slug: agentcentral-to
slug: agentcentral-to-privacy-policy
source_date: '2026-11-09'
source_filename: agentcentral-to-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentcentral.to/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Central\naid: agentcentral-to\nurl: https://agentcentral.to/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: email address, first and last name, and phone number provided when you sign up\n- category: identifying\n  text: account identifiers, authentication state, and privacy and versioned Terms acceptance records\n- category: device\n  text: IP address, browser or device information, request and response metadata, timestamps, authentication events\n- category: communication\n  text: Support communications — messages, diagnostic\
  \ details, and attachments you send when requesting help or\n    reporting a problem.\n- category: financial\n  text: plan and subscription state, invoices and billing events, order measurements used for tiering\n- category: behavioral\n  text: Website analytics — cookieless page counts through Vercel Analytics\n- category: other\n  text: Amazon OAuth tokens — access and refresh tokens issued by Amazon through its official OAuth flow, encrypted\n    at rest.\npurposes:\n- purpose: sync and serve Amazon seller data to AI agent\n  text: To sync and serve your Amazon seller data to your AI agent.\n- purpose: authenticate account and manage subscription\n  text: To authenticate your account and manage your subscription.\n- purpose: advertising delivery\n  text: To deliver and measure advertising. We may share limited account information with advertising service providers\n    for this purpose.\n- purpose: product improvement\n  text: Product analytics and product improvement use usage data\
  \ and operational metadata, not your Amazon business\n    data.\nretention:\n- scope: Amazon data\n  period: null\n  text: We retain your Amazon data while your account remains active.\n- scope: First-party marketing attribution\n  period: up to 90 days\n  text: First-party marketing attribution is kept for up to 90 days unless you withdraw consent sooner.\n- scope: Vercel visit hash\n  period: 24 hours\n  text: Vercel groups a visit using a hash of the request that it discards after 24 hours.\nresidency:\n- region: United States\n  text: Agent Central is operated from the United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses (SCCs) approved by the European Commission to safeguard these transfers.\nsubprocessors:\n  url: null\n  text: Subprocessors Provider Purpose Data processed Location Google Cloud Platform Data storage, processing, encryption\ndpa:\n  available: true\n  url: null\n  text: Our Data Processing Agreement forms part of our Terms\
  \ of Service and applies whenever we process personal\n    data on your behalf.\ndeletion:\n  route: dashboard\n  text: You can start account deletion from the dashboard; the live tenant dataset, credentials, keys, and mutable\n    account state are then removed through the deletion process.\nrights:\n- right: access\n  text: Access a copy of your personal data\n- right: correct\n  text: Correct inaccurate data\n- right: delete\n  text: Delete your account and associated data, subject to limited lawful retention\n- right: restrict or object\n  text: Restrict or object to certain processing\n- right: portability\n  text: Data portability (receive your data in a structured format)\n- right: complain\n  text: Lodge a complaint with your local data protection authority (EEA/UK residents)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/agentcentral-to/privacy/agentcentral-to-privacy-policy.yml
stated_fields:
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
summary_line: 26 quoted statements, read from Agent Central's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Artificial Intelligence
- Automation
- Amazon
- Seller Central
---
