---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account identifiers: email address, Firebase UID, and the display name you provide when you sign in.'
  - category: financial
    text: 'Billing data: we use Stripe and Shopify Managed Pricing for payments. Stripe receives payment-method data directly from you; we receive only a customer ID and billing status.'
  - category: behavioral
    text: 'Request metadata for analytics: timestamp, HTTP method, tool name (e.g. check_stock ), user-agent string (e.g. ChatGPT-User ), and an anonymised IP prefix (IPv4 /24 or IPv6 /48).'
  - category: location
    text: 'Country/region: inferred from Cloud Run’s edge headers, not from cookies or fingerprinting.'
  - category: device
    text: 'Session discriminator: a SHA-256 hash of (anonymised IP + user-agent + a rotating salt), truncated to 12 hexadecimal characters.'
  deletion:
    route: Email privacy@agenticshelf.ai or uninstall the app
    text: You can also email privacy@agenticshelf.ai to request immediate deletion.
  dpa:
    available: true
    text: Merchants subject to GDPR, UK-GDPR, or comparable regimes can execute a Data Processing Agreement (DPA) with us.
    url: https://www.agenticshelf.ai/privacy
  purposes:
  - purpose: Run audits and MCP tool calls
    text: To run the citation audits, product-selection workflows, and MCP tool calls you configure.
  - purpose: Aggregate analytics
    text: To show you aggregate analytics (agent traffic by country, per-LLM citation trends, Query Library trends).
  - purpose: Operate and secure the service
    text: To operate, secure, and improve the service — debugging, fraud prevention, and performance monitoring.
  - purpose: Account communications
    text: To communicate with you about account, billing, and material product changes.
  residency:
  - region: United States (us-central1)
    text: 'Primary infrastructure: Google Cloud Platform, region us-central1 .'
  retention:
  - period: 30 days
    scope: Merchant account data
    text: Deleted within 30 days of uninstall, account closure, or receipt of Shopify’s shop/redact webhook.
  - period: 90-day rolling window
    scope: Agent traffic logs
    text: 'Agent traffic logs: 90-day rolling window, then aggregated to daily totals without raw logs.'
  - period: 35 days
    scope: Backups
    text: 'Backups: Firestore point-in-time backups roll off within 35 days.'
  rights:
  - right: access, correction, deletion
    text: You can request access to, correction of, or deletion of your personal data by emailing privacy@agenticshelf.ai .
  - right: restrict, port, object, withdraw consent
    text: including the right to access, rectify, erase, restrict processing of, port, or object to processing of your personal data, and the right to withdraw consent.
  - right: opt out of sale or sharing (California)
    text: California residents have the right to opt out of the “sale” or “sharing” of personal information; we don’t sell or share data, so the opt-out is automatic.
  role:
    text: We are the data controller for merchant account data and the data processor for any data we handle on behalf of merchants on their shoppers’ behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: We rely on a small number of subprocessors to operate the service. Each is listed below with the data category they handle and a link to their own privacy policy.
    url: https://www.agenticshelf.ai/privacy
  transfers:
  - mechanism: SCC
    text: We rely on the Standard Contractual Clauses (2021/914 module 2) and, where applicable, the UK International Data Transfer Addendum to authorise those transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agenticshelf-ai
provenance_date: '2026-11-09'
provider_name: agenticshelf-ai
provider_slug: agenticshelf-ai
slug: agenticshelf-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agenticshelf-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.agenticshelf.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agenticshelf-ai\naid: agenticshelf-ai\nurl: https://www.agenticshelf.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the data controller for merchant account data and the data processor for any data we handle on behalf\n    of merchants on their shoppers’ behalf.\ndata_categories:\n- category: identifying\n  text: 'Account identifiers: email address, Firebase UID, and the display name you provide when you sign in.'\n- category: financial\n  text: 'Billing data: we use Stripe and Shopify Managed Pricing for payments. Stripe receives payment-method data\n    directly from you; we\
  \ receive only a customer ID and billing status.'\n- category: behavioral\n  text: 'Request metadata for analytics: timestamp, HTTP method, tool name (e.g. check_stock ), user-agent string\n    (e.g. ChatGPT-User ), and an anonymised IP prefix (IPv4 /24 or IPv6 /48).'\n- category: location\n  text: 'Country/region: inferred from Cloud Run’s edge headers, not from cookies or fingerprinting.'\n- category: device\n  text: 'Session discriminator: a SHA-256 hash of (anonymised IP + user-agent + a rotating salt), truncated to 12\n    hexadecimal characters.'\npurposes:\n- purpose: Run audits and MCP tool calls\n  text: To run the citation audits, product-selection workflows, and MCP tool calls you configure.\n- purpose: Aggregate analytics\n  text: To show you aggregate analytics (agent traffic by country, per-LLM citation trends, Query Library trends).\n- purpose: Operate and secure the service\n  text: To operate, secure, and improve the service — debugging, fraud prevention, and performance\
  \ monitoring.\n- purpose: Account communications\n  text: To communicate with you about account, billing, and material product changes.\nretention:\n- scope: Merchant account data\n  period: 30 days\n  text: Deleted within 30 days of uninstall, account closure, or receipt of Shopify’s shop/redact webhook.\n- scope: Agent traffic logs\n  period: 90-day rolling window\n  text: 'Agent traffic logs: 90-day rolling window, then aggregated to daily totals without raw logs.'\n- scope: Backups\n  period: 35 days\n  text: 'Backups: Firestore point-in-time backups roll off within 35 days.'\nresidency:\n- region: United States (us-central1)\n  text: 'Primary infrastructure: Google Cloud Platform, region us-central1 .'\ntransfers:\n- mechanism: SCC\n  text: We rely on the Standard Contractual Clauses (2021/914 module 2) and, where applicable, the UK International\n    Data Transfer Addendum to authorise those transfers.\nsubprocessors:\n  url: https://www.agenticshelf.ai/privacy\n  text: We rely on\
  \ a small number of subprocessors to operate the service. Each is listed below with the data category\n    they handle and a link to their own privacy policy.\ndpa:\n  available: true\n  url: https://www.agenticshelf.ai/privacy\n  text: Merchants subject to GDPR, UK-GDPR, or comparable regimes can execute a Data Processing Agreement (DPA)\n    with us.\ndeletion:\n  route: Email privacy@agenticshelf.ai or uninstall the app\n  text: You can also email privacy@agenticshelf.ai to request immediate deletion.\nrights:\n- right: access, correction, deletion\n  text: You can request access to, correction of, or deletion of your personal data by emailing privacy@agenticshelf.ai\n    .\n- right: restrict, port, object, withdraw consent\n  text: including the right to access, rectify, erase, restrict processing of, port, or object to processing of\n    your personal data, and the right to withdraw consent.\n- right: opt out of sale or sharing (California)\n  text: California residents have the right\
  \ to opt out of the “sale” or “sharing” of personal information; we don’t\n    sell or share data, so the opt-out is automatic.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/agenticshelf-ai/privacy/agenticshelf-ai-privacy-policy.yml
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
summary_line: 22 quoted statements, read from agenticshelf-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Commerce
- MCP
- Auditing
---
