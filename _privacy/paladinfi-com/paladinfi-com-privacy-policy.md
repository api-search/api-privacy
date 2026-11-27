---
api_specs:
- filename: paladinfi-com-health-api-openapi.yml
  format: yaml
  label: paladinfi-com Health API
  slug: paladinfi-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paladinfi-com/openapi/paladinfi-com-health-api-openapi.yml
- filename: paladinfi-com-trust-check-api-openapi.yml
  format: yaml
  label: paladinfi-com Trust Check API
  slug: paladinfi-com-trust-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paladinfi-com/openapi/paladinfi-com-trust-check-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP address, taker wallet address, email (if provided)
  - category: contact
    text: Email address , when you contact us at dev@paladinfi.com or subscribe to a paid feature.
  - category: financial
    text: We do receive a payment-processor identifier and subscription metadata.
  - category: device
    text: Server logs. When you make an HTTP request, our infrastructure logs the IP address, user-agent string, timestamp, requested URL, response status, and response time.
  - category: location
    text: Country/region inferred from IP for security and sanctions purposes only; we do not collect precise geolocation
  deletion:
    route: Email dev@paladinfi.com with the subject "CCPA Request"
    text: Email dev@paladinfi.com with the subject "CCPA Request".
  dpa:
    available: null
    text: We are working to maintain a current list of executed DPAs and intend to publish vendor-specific DPA references in a future revision of this Policy.
    url: null
  purposes:
  - purpose: Operate and improve the Service
    text: Operate, maintain, and improve the Service
  - purpose: Security and abuse prevention
    text: Detect and prevent abuse, fraud, and security incidents
  - purpose: Sanctions screening
    text: Perform sanctions screening on taker addresses
  - purpose: Swap quote routing
    text: Generate and return swap quotes and routing data
  - purpose: Support and legal compliance
    text: Respond to support requests and communications
  residency:
  - region: United States
    text: The Service is operated from the United States and is intended for users located outside the European Economic Area, the United Kingdom, and Switzerland.
  retention:
  - period: 30 days
    scope: Server access logs
    text: 'Server access logs: retained up to 30 days in ordinary operation'
  - period: 7 years
    scope: Subscription/payment records
    text: 'Subscription/payment records: retained as required for accounting, tax, audit, and legal-compliance obligations (typically up to 7 years).'
  rights:
  - right: Know
    text: know the categories and specific pieces of personal information we have collected about you over the prior 12 months
  - right: Deletion
    text: request deletion of personal information
  - right: Correction
    text: correct inaccurate personal information
  - right: Opt out of sale or sharing
    text: opt out of any "sale" or "sharing" of personal information
  role:
    text: PaladinFi does not assume the role of a controller under the EU GDPR or UK GDPR by virtue of such access.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information for monetary consideration.
  subprocessors:
    text: As of the date of this policy, these include the providers listed below.
    url: null
  transfers:
  - mechanism: other
    text: we therefore do not undertake EU/UK cross-border transfer mechanisms (such as Standard Contractual Clauses) for outbound transfers from those jurisdictions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: paladinfi-com
provenance_date: '2026-11-10'
provider_name: paladinfi-com
provider_slug: paladinfi-com
slug: paladinfi-com-privacy-policy
source_date: '2026-11-10'
source_filename: paladinfi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://paladinfi.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: paladinfi-com\naid: paladinfi-com\nurl: https://paladinfi.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: PaladinFi does not assume the role of a controller under the EU GDPR or UK GDPR by virtue of such access.\ndata_categories:\n- category: identifying\n  text: IP address, taker wallet address, email (if provided)\n- category: contact\n  text: Email address , when you contact us at dev@paladinfi.com or subscribe to a paid feature.\n- category: financial\n  text: We do receive a payment-processor identifier and subscription metadata.\n- category: device\n  text: Server logs. When\
  \ you make an HTTP request, our infrastructure logs the IP address, user-agent string, timestamp,\n    requested URL, response status, and response time.\n- category: location\n  text: Country/region inferred from IP for security and sanctions purposes only; we do not collect precise geolocation\npurposes:\n- purpose: Operate and improve the Service\n  text: Operate, maintain, and improve the Service\n- purpose: Security and abuse prevention\n  text: Detect and prevent abuse, fraud, and security incidents\n- purpose: Sanctions screening\n  text: Perform sanctions screening on taker addresses\n- purpose: Swap quote routing\n  text: Generate and return swap quotes and routing data\n- purpose: Support and legal compliance\n  text: Respond to support requests and communications\nretention:\n- scope: Server access logs\n  period: 30 days\n  text: 'Server access logs: retained up to 30 days in ordinary operation'\n- scope: Subscription/payment records\n  period: 7 years\n  text: 'Subscription/payment\
  \ records: retained as required for accounting, tax, audit, and legal-compliance obligations\n    (typically up to 7 years).'\nresidency:\n- region: United States\n  text: The Service is operated from the United States and is intended for users located outside the European Economic\n    Area, the United Kingdom, and Switzerland.\ntransfers:\n- mechanism: other\n  text: we therefore do not undertake EU/UK cross-border transfer mechanisms (such as Standard Contractual Clauses)\n    for outbound transfers from those jurisdictions.\nsubprocessors:\n  url: null\n  text: As of the date of this policy, these include the providers listed below.\ndpa:\n  available: null\n  url: null\n  text: We are working to maintain a current list of executed DPAs and intend to publish vendor-specific DPA references\n    in a future revision of this Policy.\ndeletion:\n  route: Email dev@paladinfi.com with the subject \"CCPA Request\"\n  text: Email dev@paladinfi.com with the subject \"CCPA Request\".\nrights:\n\
  - right: Know\n  text: know the categories and specific pieces of personal information we have collected about you over the prior\n    12 months\n- right: Deletion\n  text: request deletion of personal information\n- right: Correction\n  text: correct inaccurate personal information\n- right: Opt out of sale or sharing\n  text: opt out of any \"sale\" or \"sharing\" of personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information for monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/paladinfi-com/privacy/paladinfi-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from paladinfi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DeFi
- Artificial Intelligence
- Infrastructure
- Finance
- Base
---
