---
api_specs:
- filename: deepinquiry-facts-api-openapi.yml
  format: yaml
  label: DeepInquiry Verified Facts API (Machine Accountability Corp) Facts API
  slug: deepinquiry-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepinquiry/openapi/deepinquiry-facts-api-openapi.yml
- filename: deepinquiry-search-api-openapi.yml
  format: yaml
  label: DeepInquiry Verified Facts API (Machine Accountability Corp) Search API
  slug: deepinquiry-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepinquiry/openapi/deepinquiry-search-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, plan and subscription status, hashed API key
  - category: financial
    text: Stripe customer ID, subscription ID, billing status, current-period timestamps
  - category: device
    text: IP address, browser type and version, referring URL, request path, response code
  - category: behavioral
    text: Endpoint requested, timestamp, fact ID returned, HTTP status, IP address (short-lived), user agent
  - category: communication
    text: The content of emails or support tickets you send us and our replies
  deletion:
    route: email api@deepinquiry.ai
    text: To exercise any of these rights, email api@deepinquiry.ai from the address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the Service
    text: Operate the Service — authenticate your API key, enforce quotas and rate limits, bill you through Stripe
  - purpose: Secure the Service
    text: Secure the Service — detect and prevent abuse, fraud, unauthorized access, and attacks; investigate incidents.
  - purpose: Improve the Service
    text: Improve the Service — produce aggregated analytics on endpoint usage, error rates, and latency.
  - purpose: Comply with law
    text: Comply with law — respond to lawful requests from regulators, courts, or law enforcement; meet tax and accounting obligations.
  residency:
  - region: United States
    text: Our servers and most of our subprocessors are located in the United States.
  retention:
  - period: While your account is active, plus up to 24 months after deletion
    scope: Account records
    text: While your account is active, plus up to 24 months after deletion
  - period: Up to 13 months
    scope: API usage rows
    text: Up to 13 months, then aggregated and row-level data deleted
  - period: Typically 30 days
    scope: Server request logs
    text: Typically 30 days
  - period: At least 7 years
    scope: Billing records
    text: At least 7 years
  - period: Up to 3 years after the last exchange
    scope: Support and communications
    text: Up to 3 years after the last exchange
  rights:
  - right: Access
    text: Ask for a copy of the personal information we hold about you.
  - right: Correction
    text: Ask us to fix inaccurate personal information.
  - right: Deletion
    text: Ask us to delete your account and associated personal information.
  - right: Portability
    text: Receive your data in a machine-readable format.
  role:
    text: Machine Accountability Corporation is the “controller” of personal information under the EU and UK General Data Protection Regulations
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: The current, dated list of our subprocessors — including the purpose, data categories, and processing location for each — is maintained at /subprocessors
    url: /subprocessors
  transfers:
  - mechanism: SCC
    text: Where required, we rely on the European Commission’s Standard Contractual Clauses
  - mechanism: DPF
    text: on the EU–U.S. Data Privacy Framework where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DeepInquiry Verified Facts API (Machine Accountability Corp)
provenance_date: '2026-11-09'
provider_name: DeepInquiry Verified Facts API (Machine Accountability Corp)
provider_slug: deepinquiry
slug: deepinquiry-privacy-policy
source_date: '2026-11-09'
source_filename: deepinquiry-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.deepinquiry.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DeepInquiry Verified Facts API (Machine Accountability Corp)\naid: deepinquiry\nurl: https://www.deepinquiry.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Machine Accountability Corporation is the “controller” of personal information under the EU and UK General\n    Data Protection Regulations\ndata_categories:\n- category: contact\n  text: Email address, plan and subscription status, hashed API key\n- category: financial\n  text: Stripe customer ID, subscription ID, billing status, current-period timestamps\n- category: device\n  text: IP address, browser type and version, referring\
  \ URL, request path, response code\n- category: behavioral\n  text: Endpoint requested, timestamp, fact ID returned, HTTP status, IP address (short-lived), user agent\n- category: communication\n  text: The content of emails or support tickets you send us and our replies\npurposes:\n- purpose: Operate the Service\n  text: Operate the Service — authenticate your API key, enforce quotas and rate limits, bill you through Stripe\n- purpose: Secure the Service\n  text: Secure the Service — detect and prevent abuse, fraud, unauthorized access, and attacks; investigate incidents.\n- purpose: Improve the Service\n  text: Improve the Service — produce aggregated analytics on endpoint usage, error rates, and latency.\n- purpose: Comply with law\n  text: Comply with law — respond to lawful requests from regulators, courts, or law enforcement; meet tax and accounting\n    obligations.\nretention:\n- scope: Account records\n  period: While your account is active, plus up to 24 months after deletion\n\
  \  text: While your account is active, plus up to 24 months after deletion\n- scope: API usage rows\n  period: Up to 13 months\n  text: Up to 13 months, then aggregated and row-level data deleted\n- scope: Server request logs\n  period: Typically 30 days\n  text: Typically 30 days\n- scope: Billing records\n  period: At least 7 years\n  text: At least 7 years\n- scope: Support and communications\n  period: Up to 3 years after the last exchange\n  text: Up to 3 years after the last exchange\nresidency:\n- region: United States\n  text: Our servers and most of our subprocessors are located in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on the European Commission’s Standard Contractual Clauses\n- mechanism: DPF\n  text: on the EU–U.S. Data Privacy Framework where applicable\nsubprocessors:\n  url: /subprocessors\n  text: The current, dated list of our subprocessors — including the purpose, data categories, and processing location\n    for each — is maintained\
  \ at /subprocessors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email api@deepinquiry.ai\n  text: To exercise any of these rights, email api@deepinquiry.ai from the address on your account.\nrights:\n- right: Access\n  text: Ask for a copy of the personal information we hold about you.\n- right: Correction\n  text: Ask us to fix inaccurate personal information.\n- right: Deletion\n  text: Ask us to delete your account and associated personal information.\n- right: Portability\n  text: Receive your data in a machine-readable format.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/deepinquiry/privacy/deepinquiry-privacy-policy.yml
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
summary_line: 25 quoted statements, read from DeepInquiry Verified Facts API (Machine Accountability Corp)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Facts
- Verification
- Data
---
