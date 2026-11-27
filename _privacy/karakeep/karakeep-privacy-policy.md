---
api_specs:
- filename: karakeep-openapi-generated.yml
  format: yaml
  label: Karakeep API
  slug: karakeep-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karakeep/openapi/_ae-authored/karakeep-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information : email address, name, profile image, authentication identifiers.'
  - category: other
    text: 'Content you provide : links, notes, uploads, and other data you choose to save in the Service.'
  - category: financial
    text: 'Billing and subscription data : plan status, billing events, and limited payment metadata from payment providers.'
  - category: device
    text: 'Technical and usage data : logs, device/browser details, IP address, and service events needed to run, secure, and troubleshoot Karakeep.'
  - category: communication
    text: 'Support communications : information you send when contacting support.'
  deletion:
    route: Delete your account
    text: When you delete your account, we delete your data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run and improve Karakeep Cloud
    text: 'We use your data to run and improve Karakeep Cloud, including to: create and manage your account; store and present your content; manage subscriptions and payments; detect abuse, fraud, and security incidents; monitor reliability and fix issues; comply with legal obligations.'
  - purpose: AI features
    text: We may process this content, including via third-party artificial intelligence providers, to provide features such as full-text search, automatic tagging, and AI-powered summaries.
  residency:
  - region: Europe
    text: Karakeep Cloud stores primary data in Europe.
  retention:
  - period: 90 days
    scope: Encrypted backups
    text: Residual copies may remain in encrypted backups for up to 90 days before being purged.
  - period: null
    scope: Personal data
    text: We keep personal data only as long as needed to run the Service and meet legal obligations.
  rights:
  - right: Access
    text: 'Access : request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction : ask us to correct inaccurate or incomplete data.'
  - right: Erasure
    text: 'Erasure : ask us to delete your personal data.'
  - right: Restriction
    text: 'Restriction : ask us to restrict certain processing of your data.'
  - right: Portability
    text: 'Portability : receive your data in a structured, commonly used format.'
  - right: Objection
    text: 'Objection : object to processing based on legitimate interests.'
  role:
    text: Localhost Labs Ltd is the data controller for personal data processed under this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'Current key providers include: Hetzner (hosting and infrastructure, with primary data storage in Europe). Stripe (payments and billing events). OpenAI (content processing for features such as automatic tagging and summaries).'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on recognised safeguards for cross-border transfers, such as Standard Contractual Clauses (SCCs) or adequacy decisions.
  - mechanism: adequacy
    text: Where required, we rely on recognised safeguards for cross-border transfers, such as Standard Contractual Clauses (SCCs) or adequacy decisions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Karakeep
provenance_date: '2026-11-09'
provider_name: Karakeep
provider_slug: karakeep
slug: karakeep-privacy-policy
source_date: '2026-11-09'
source_filename: karakeep-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://karakeep.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Karakeep\naid: karakeep\nurl: https://karakeep.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Localhost Labs Ltd is the data controller for personal data processed under this policy.\ndata_categories:\n- category: identifying\n  text: 'Account information : email address, name, profile image, authentication identifiers.'\n- category: other\n  text: 'Content you provide : links, notes, uploads, and other data you choose to save in the Service.'\n- category: financial\n  text: 'Billing and subscription data : plan status, billing events, and limited payment metadata from payment\n\
  \    providers.'\n- category: device\n  text: 'Technical and usage data : logs, device/browser details, IP address, and service events needed to run,\n    secure, and troubleshoot Karakeep.'\n- category: communication\n  text: 'Support communications : information you send when contacting support.'\npurposes:\n- purpose: Run and improve Karakeep Cloud\n  text: 'We use your data to run and improve Karakeep Cloud, including to: create and manage your account; store\n    and present your content; manage subscriptions and payments; detect abuse, fraud, and security incidents; monitor\n    reliability and fix issues; comply with legal obligations.'\n- purpose: AI features\n  text: We may process this content, including via third-party artificial intelligence providers, to provide features\n    such as full-text search, automatic tagging, and AI-powered summaries.\nretention:\n- scope: Encrypted backups\n  period: 90 days\n  text: Residual copies may remain in encrypted backups for up to 90\
  \ days before being purged.\n- scope: Personal data\n  period: null\n  text: We keep personal data only as long as needed to run the Service and meet legal obligations.\nresidency:\n- region: Europe\n  text: Karakeep Cloud stores primary data in Europe.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on recognised safeguards for cross-border transfers, such as Standard Contractual\n    Clauses (SCCs) or adequacy decisions.\n- mechanism: adequacy\n  text: Where required, we rely on recognised safeguards for cross-border transfers, such as Standard Contractual\n    Clauses (SCCs) or adequacy decisions.\nsubprocessors:\n  url: null\n  text: 'Current key providers include: Hetzner (hosting and infrastructure, with primary data storage in Europe).\n    Stripe (payments and billing events). OpenAI (content processing for features such as automatic tagging and\n    summaries).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account\n  text:\
  \ When you delete your account, we delete your data.\nrights:\n- right: Access\n  text: 'Access : request a copy of the personal data we hold about you.'\n- right: Correction\n  text: 'Correction : ask us to correct inaccurate or incomplete data.'\n- right: Erasure\n  text: 'Erasure : ask us to delete your personal data.'\n- right: Restriction\n  text: 'Restriction : ask us to restrict certain processing of your data.'\n- right: Portability\n  text: 'Portability : receive your data in a structured, commonly used format.'\n- right: Objection\n  text: 'Objection : object to processing based on legitimate interests.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/karakeep/privacy/karakeep-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Karakeep's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Bookmarking
- Artificial Intelligence
- Collaboration
- Open Source
---
