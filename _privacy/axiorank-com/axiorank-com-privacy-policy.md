---
api_specs:
- filename: axiorank-com-audit-api-openapi.yml
  format: yaml
  label: AxioRank Audit API
  slug: axiorank-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-audit-api-openapi.yml
- filename: axiorank-com-gateway-api-openapi.yml
  format: yaml
  label: AxioRank Gateway API
  slug: axiorank-com-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-gateway-api-openapi.yml
- filename: axiorank-com-health-api-openapi.yml
  format: yaml
  label: AxioRank Health API
  slug: axiorank-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-health-api-openapi.yml
- filename: axiorank-com-mcp-api-openapi.yml
  format: yaml
  label: AxioRank MCP API
  slug: axiorank-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-mcp-api-openapi.yml
- filename: axiorank-com-protocols-api-openapi.yml
  format: yaml
  label: AxioRank Protocols API
  slug: axiorank-com-protocols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-protocols-api-openapi.yml
- filename: axiorank-com-tools-log-api-openapi.yml
  format: yaml
  label: AxioRank Tools Log API
  slug: axiorank-com-tools-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-tools-log-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account and profile data: name, work email address, password or single sign-on identifier, organization or workspace name, job title, and role.'
  - category: financial
    text: 'Billing and transaction data: billing contact, billing address, plan and subscription details, and the last four digits and card type of your payment method.'
  - category: device
    text: 'Device and connection data: IP address, browser type and version, operating system, device identifiers, language preferences, and referring URLs.'
  - category: behavioral
    text: 'Usage and telemetry data: pages and dashboard screens viewed, features used, requests made to our API, timestamps, performance and diagnostic metrics, and error reports.'
  - category: communication
    text: 'Support and communications data: the contents of messages, support requests, survey responses, and other communications you send to us, including any attachments.'
  deletion:
    route: Settings → Privacy & Data
    text: you can also export, correct, or delete your data yourself under Settings → Privacy & Data
  dpa:
    available: true
    text: Our handling of Customer Data is governed by the agreement and Data Processing Addendum (“DPA”) with that customer
    url: null
  purposes:
  - purpose: provide and improve the Service
    text: to provide, operate, maintain, and improve the Service and its features
  - purpose: security and abuse prevention
    text: to monitor, detect, investigate, and prevent security incidents, abuse, and other prohibited or illegal activity
  - purpose: payments and subscriptions
    text: to process payments, manage subscriptions, send invoices, and prevent payment fraud
  - purpose: legal compliance
    text: to comply with legal obligations, enforce our agreements, and establish, exercise, or defend legal claims
  residency:
  - region: United States
    text: We are based in the United States and may process and store information in the United States and other countries where we or our service providers operate.
  retention:
  - period: 90 days
    scope: Inbound request logs
    text: Inbound request logs (which may contain raw IP addresses and user-agent strings) are deleted after 90 days by default
  - period: 365 days
    scope: Audit and forensic logs
    text: Audit and forensic logs (already redacted of secrets and personal data at write time) are deleted after 365 days by default.
  - period: indefinitely
    scope: De-identified aggregate statistics
    text: De-identified, aggregate statistics are retained indefinitely.
  rights:
  - right: access
    text: to access and obtain a copy of the information we hold
  - right: correction
    text: to correct inaccurate or incomplete information
  - right: deletion
    text: to delete your information
  - right: portability
    text: to port your information to another service in a structured, machine-readable format
  - right: objection or restriction
    text: to object to or restrict certain processing, and to withdraw consent where processing is based on consent
  - right: complaint
    text: to lodge a complaint with your local data-protection authority
  role:
    text: As a controller. When we decide why and how personal information is processed
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: A current list of the specific sub-processors we use is published at axiorank.com/subprocessors .
    url: axiorank.com/subprocessors
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as the European Commission’s Standard Contractual Clauses and the UK International Data Transfer Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AxioRank
provenance_date: '2026-11-09'
provider_name: AxioRank
provider_slug: axiorank-com
slug: axiorank-com-privacy-policy
source_date: '2026-11-09'
source_filename: axiorank-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://axiorank.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AxioRank\naid: axiorank-com\nurl: https://axiorank.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: As a controller. When we decide why and how personal information is processed\ndata_categories:\n- category: contact\n  text: 'Account and profile data: name, work email address, password or single sign-on identifier, organization\n    or workspace name, job title, and role.'\n- category: financial\n  text: 'Billing and transaction data: billing contact, billing address, plan and subscription details, and the\n    last four digits and card type of your payment method.'\n- category: device\n\
  \  text: 'Device and connection data: IP address, browser type and version, operating system, device identifiers,\n    language preferences, and referring URLs.'\n- category: behavioral\n  text: 'Usage and telemetry data: pages and dashboard screens viewed, features used, requests made to our API,\n    timestamps, performance and diagnostic metrics, and error reports.'\n- category: communication\n  text: 'Support and communications data: the contents of messages, support requests, survey responses, and other\n    communications you send to us, including any attachments.'\npurposes:\n- purpose: provide and improve the Service\n  text: to provide, operate, maintain, and improve the Service and its features\n- purpose: security and abuse prevention\n  text: to monitor, detect, investigate, and prevent security incidents, abuse, and other prohibited or illegal\n    activity\n- purpose: payments and subscriptions\n  text: to process payments, manage subscriptions, send invoices, and prevent\
  \ payment fraud\n- purpose: legal compliance\n  text: to comply with legal obligations, enforce our agreements, and establish, exercise, or defend legal claims\nretention:\n- scope: Inbound request logs\n  period: 90 days\n  text: Inbound request logs (which may contain raw IP addresses and user-agent strings) are deleted after 90 days\n    by default\n- scope: Audit and forensic logs\n  period: 365 days\n  text: Audit and forensic logs (already redacted of secrets and personal data at write time) are deleted after\n    365 days by default.\n- scope: De-identified aggregate statistics\n  period: indefinitely\n  text: De-identified, aggregate statistics are retained indefinitely.\nresidency:\n- region: United States\n  text: We are based in the United States and may process and store information in the United States and other countries\n    where we or our service providers operate.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as the European Commission’s\
  \ Standard Contractual Clauses and the\n    UK International Data Transfer Addendum\nsubprocessors:\n  url: axiorank.com/subprocessors\n  text: A current list of the specific sub-processors we use is published at axiorank.com/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: Our handling of Customer Data is governed by the agreement and Data Processing Addendum (“DPA”) with that\n    customer\ndeletion:\n  route: Settings → Privacy & Data\n  text: you can also export, correct, or delete your data yourself under Settings → Privacy & Data\nrights:\n- right: access\n  text: to access and obtain a copy of the information we hold\n- right: correction\n  text: to correct inaccurate or incomplete information\n- right: deletion\n  text: to delete your information\n- right: portability\n  text: to port your information to another service in a structured, machine-readable format\n- right: objection or restriction\n  text: to object to or restrict certain processing, and to withdraw\
  \ consent where processing is based on consent\n- right: complaint\n  text: to lodge a complaint with your local data-protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/axiorank-com/privacy/axiorank-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from AxioRank's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Security
- Gateways
- Zero Trust
- Agents
---
