---
api_specs:
- filename: arpi-ai-authentication-api-openapi.yml
  format: yaml
  label: ARPI Inc. Authentication API
  slug: arpi-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arpi-ai/openapi/arpi-ai-authentication-api-openapi.yml
- filename: arpi-ai-diag-api-openapi.yml
  format: yaml
  label: ARPI Inc. Diag API
  slug: arpi-ai-diag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arpi-ai/openapi/arpi-ai-diag-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: '[Required] Email address, password'
  - category: professional
    text: '[Required] Affiliated institution, type of institution, position, department'
  - category: health
    text: '[Required] ECG data'
  - category: financial
    text: '[Required] Subscription info: plan type, payment status, etc. / Payment info: order number, payment amount, etc.'
  - category: contact
    text: '[Required] Email address, name, region, hospital/company/affiliation name, phone number, inquiry content'
  deletion:
    route: Email to the Chief Privacy Officer or written/email request
    text: Rights may be exercised in writing, by email, and so on, and the Company will act on them without delay.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision of ECG analysis service
    text: Provision of goods or services
  - purpose: Customer inquiry handling
    text: Customer inquiry handling
  - purpose: Marketing and advertising (optional, consent)
    text: New product launch notices, promotional information, and other marketing uses
  retention:
  - period: Until membership withdrawal
    scope: Membership information
    text: Until membership withdrawal
  - period: 6 hours after analysis is complete
    scope: ECG data
    text: 6 hours after analysis is complete
  - period: 3 years
    scope: Customer inquiries
    text: 3 years
  - period: Until consent is withdrawn or membership is terminated
    scope: Marketing email
    text: Until consent is withdrawn or membership is terminated
  rights:
  - right: Access
    text: 'Right to request access: you may request access to your own personal information being processed by the Company.'
  - right: Correction
    text: 'Right to request correction of errors: if there are errors in your personal information, you may request that they be corrected.'
  - right: Deletion
    text: 'Right to request deletion: in certain cases, you may request deletion of your personal information.'
  - right: Suspension of processing
    text: 'Right to request suspension of processing: in certain cases, you may request suspension of the processing of your personal information.'
  role:
    text: ARPI Inc. ("the Company") lawfully processes and securely manages personal information in compliance with the Republic of Korea’s Personal Information Protection Act ("PIPA")
    value: controller
  sale_or_sharing:
    stance: conditional
    text: If personal information is sold to or shared with a third party, the Company notifies users in advance and provides a choice through a "Do Not Sell/Share (Opt-Out)" link.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'USA (Twilio, RevenueCat, HubSpot, AWS, etc.): the EU Standard Contractual Clauses (SCCs) included in each provider’s Data Processing Addendum (DPA), or the EU-US Data Privacy Framework (DPF), applies'
  - mechanism: DPF
    text: or the EU-US Data Privacy Framework (DPF), applies
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ARPI Inc.
provenance_date: '2026-11-09'
provider_name: ARPI Inc.
provider_slug: arpi-ai
slug: arpi-ai-privacy-policy
source_date: '2026-11-09'
source_filename: arpi-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.arpi.ai/en/terms/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ARPI Inc.\naid: arpi-ai\nurl: https://www.arpi.ai/en/terms/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: ARPI Inc. (\"the Company\") lawfully processes and securely manages personal information in compliance with\n    the Republic of Korea’s Personal Information Protection Act (\"PIPA\")\ndata_categories:\n- category: identifying\n  text: '[Required] Email address, password'\n- category: professional\n  text: '[Required] Affiliated institution, type of institution, position, department'\n- category: health\n  text: '[Required] ECG data'\n- category: financial\n\
  \  text: '[Required] Subscription info: plan type, payment status, etc. / Payment info: order number, payment amount,\n    etc.'\n- category: contact\n  text: '[Required] Email address, name, region, hospital/company/affiliation name, phone number, inquiry content'\npurposes:\n- purpose: Provision of ECG analysis service\n  text: Provision of goods or services\n- purpose: Customer inquiry handling\n  text: Customer inquiry handling\n- purpose: Marketing and advertising (optional, consent)\n  text: New product launch notices, promotional information, and other marketing uses\nretention:\n- scope: Membership information\n  period: Until membership withdrawal\n  text: Until membership withdrawal\n- scope: ECG data\n  period: 6 hours after analysis is complete\n  text: 6 hours after analysis is complete\n- scope: Customer inquiries\n  period: 3 years\n  text: 3 years\n- scope: Marketing email\n  period: Until consent is withdrawn or membership is terminated\n  text: Until consent is withdrawn\
  \ or membership is terminated\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: 'USA (Twilio, RevenueCat, HubSpot, AWS, etc.): the EU Standard Contractual Clauses (SCCs) included in each\n    provider’s Data Processing Addendum (DPA), or the EU-US Data Privacy Framework (DPF), applies'\n- mechanism: DPF\n  text: or the EU-US Data Privacy Framework (DPF), applies\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email to the Chief Privacy Officer or written/email request\n  text: Rights may be exercised in writing, by email, and so on, and the Company will act on them without delay.\nrights:\n- right: Access\n  text: 'Right to request access: you may request access to your own personal information being processed by the\n    Company.'\n- right: Correction\n  text: 'Right to request correction of errors: if there are errors in your personal information, you may request\n    that they be corrected.'\n- right: Deletion\n\
  \  text: 'Right to request deletion: in certain cases, you may request deletion of your personal information.'\n- right: Suspension of processing\n  text: 'Right to request suspension of processing: in certain cases, you may request suspension of the processing\n    of your personal information.'\nsale_or_sharing:\n  stance: conditional\n  text: If personal information is sold to or shared with a third party, the Company notifies users in advance and\n    provides a choice through a \"Do Not Sell/Share (Opt-Out)\" link.\n"
source_yaml_url: https://artifacts.apis.io/arpi-ai/privacy/arpi-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from ARPI Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Medical AI
- Healthcare
- ECG
- Diagnostics
- Artificial Intelligence
---
