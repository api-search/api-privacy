---
api_specs:
- filename: thirdtrail-life-ephemerides-api-openapi.yml
  format: yaml
  label: thirdtrail-life Ephemerides API
  slug: thirdtrail-life-ephemerides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-ephemerides-api-openapi.yml
- filename: thirdtrail-life-mcp-api-openapi.yml
  format: yaml
  label: thirdtrail-life MCP API
  slug: thirdtrail-life-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-mcp-api-openapi.yml
- filename: thirdtrail-life-solar-api-openapi.yml
  format: yaml
  label: thirdtrail-life Solar API
  slug: thirdtrail-life-solar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-solar-api-openapi.yml
- filename: thirdtrail-life-tides-api-openapi.yml
  format: yaml
  label: thirdtrail-life Tides API
  slug: thirdtrail-life-tides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-tides-api-openapi.yml
- filename: thirdtrail-life-utility-api-openapi.yml
  format: yaml
  label: thirdtrail-life Utility API
  slug: thirdtrail-life-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-utility-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address, username, first name, last name (if you choose to provide them)
  - category: financial
    text: We do not hold your card details, bank details, or any payment instrument data.
  - category: behavioral
    text: pages viewed, referring page, approximate location (country/region, derived from your IP address), device and browser type, and session timing
  - category: device
    text: request IPs, user-agent strings, error traces (retention limited)
  - category: communication
    text: email correspondence with support; emails we send you about your account (reactivation keys, billing)
  deletion:
    route: request deletion from your account page
    text: 'Right to erasure / "right to be forgotten" (Art. 17): request deletion from your account page (30-day grace period; permanent thereafter).'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Performance of contract
    text: 'Performance of a contract (Art. 6(1)(b) GDPR): identity, account metadata, authentication, subscription/billing, API credentials.'
  - purpose: Legal obligation
    text: 'Legal obligation (Art. 6(1)(c)): retention of billing-related data for tax and accounting purposes per applicable law.'
  - purpose: Legitimate interests
    text: 'Legitimate interests (Art. 6(1)(f)): API usage logs (for billing reconciliation, fraud prevention and capacity planning); diagnostic / security logs (for service security and reliability).'
  - purpose: Website analytics with consent
    text: 'Consent (Art. 6(1)(a), and Reg. 5 of S.I. 336/2011): website analytics.'
  residency:
  - region: EEA
    text: All primary processing occurs within the EEA.
  retention:
  - period: for the lifetime of your account
    scope: Account data
    text: 'Account data : for the lifetime of your account.'
  - period: 30 days
    scope: Deletion-pending data
    text: 'Deletion-pending data : 30 days after you request deletion, then permanently deleted'
  - period: 24 months
    scope: API usage events
    text: 'API usage events : 24 months, then aggregated and the per-event rows deleted.'
  - period: 7 years
    scope: Billing-related data
    text: 'Billing-related data (invoices, subscription history) : 7 years after the relevant transaction'
  - period: 90 days
    scope: Diagnostic / security logs
    text: 'Diagnostic / security logs : 90 days.'
  - period: 24 months
    scope: Email correspondence with support
    text: 'Email correspondence with support : 24 months.'
  - period: 14 months
    scope: Google Analytics event and user data
    text: our property is configured to delete both event-level and user-level data after 14 months
  rights:
  - right: Access
    text: 'Right of access (Art. 15): download a copy of all personal data we hold on you via /account/data.json (logged-in users) or by emailing the DPO.'
  - right: Portability
    text: 'Right to data portability (Art. 20): your data is provided in machine-readable JSON and CSV'
  - right: Rectification
    text: 'Right to rectification (Art. 16): edit your details at any time from your account page .'
  - right: Erasure
    text: 'Right to erasure / "right to be forgotten" (Art. 17): request deletion from your account page'
  - right: Restrict processing
    text: 'Right to restrict processing (Art. 18): deactivate your account from your account page .'
  - right: Object
    text: 'Right to object (Art. 21): contact dpo (at) thirdtrail.life .'
  - right: Withdraw consent
    text: 'Right to withdraw consent : where processing is based on consent, you can withdraw it without affecting the lawfulness of past processing.'
  - right: Complain
    text: Right to lodge a complaint with your supervisory authority.
  role:
    text: The data controller is Third Trail Limited , a private company limited by shares registered in Ireland under company number 819504
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Sub-processor Purpose Location / transfer mechanism Stripe Payments Europe Ltd Subscription billing, card processing, customer records Ireland (EEA).
    url: null
  transfers:
  - mechanism: SCC
    text: Any transfer outside the EEA (Stripe US support functions, and Google Analytics data reaching Google LLC in the United States if you have accepted analytics cookies) is governed by EU Standard Contractual Clauses (SCCs)
  - mechanism: DPF
    text: the EU-US Data Privacy Framework, to which Google LLC is certified
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: thirdtrail-life
provenance_date: '2026-11-10'
provider_name: thirdtrail-life
provider_slug: thirdtrail-life
slug: thirdtrail-life-privacy-policy
source_date: '2026-11-10'
source_filename: thirdtrail-life-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thirdtrail.life/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: thirdtrail-life\naid: thirdtrail-life\nurl: https://thirdtrail.life/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Third Trail Limited , a private company limited by shares registered in Ireland under\n    company number 819504\ndata_categories:\n- category: identifying\n  text: email address, username, first name, last name (if you choose to provide them)\n- category: financial\n  text: We do not hold your card details, bank details, or any payment instrument data.\n- category: behavioral\n  text: pages viewed, referring page, approximate location (country/region,\
  \ derived from your IP address), device\n    and browser type, and session timing\n- category: device\n  text: request IPs, user-agent strings, error traces (retention limited)\n- category: communication\n  text: email correspondence with support; emails we send you about your account (reactivation keys, billing)\npurposes:\n- purpose: Performance of contract\n  text: 'Performance of a contract (Art. 6(1)(b) GDPR): identity, account metadata, authentication, subscription/billing,\n    API credentials.'\n- purpose: Legal obligation\n  text: 'Legal obligation (Art. 6(1)(c)): retention of billing-related data for tax and accounting purposes per\n    applicable law.'\n- purpose: Legitimate interests\n  text: 'Legitimate interests (Art. 6(1)(f)): API usage logs (for billing reconciliation, fraud prevention and capacity\n    planning); diagnostic / security logs (for service security and reliability).'\n- purpose: Website analytics with consent\n  text: 'Consent (Art. 6(1)(a), and Reg. 5 of\
  \ S.I. 336/2011): website analytics.'\nretention:\n- scope: Account data\n  period: for the lifetime of your account\n  text: 'Account data : for the lifetime of your account.'\n- scope: Deletion-pending data\n  period: 30 days\n  text: 'Deletion-pending data : 30 days after you request deletion, then permanently deleted'\n- scope: API usage events\n  period: 24 months\n  text: 'API usage events : 24 months, then aggregated and the per-event rows deleted.'\n- scope: Billing-related data\n  period: 7 years\n  text: 'Billing-related data (invoices, subscription history) : 7 years after the relevant transaction'\n- scope: Diagnostic / security logs\n  period: 90 days\n  text: 'Diagnostic / security logs : 90 days.'\n- scope: Email correspondence with support\n  period: 24 months\n  text: 'Email correspondence with support : 24 months.'\n- scope: Google Analytics event and user data\n  period: 14 months\n  text: our property is configured to delete both event-level and user-level data after\
  \ 14 months\nresidency:\n- region: EEA\n  text: All primary processing occurs within the EEA.\ntransfers:\n- mechanism: SCC\n  text: Any transfer outside the EEA (Stripe US support functions, and Google Analytics data reaching Google LLC\n    in the United States if you have accepted analytics cookies) is governed by EU Standard Contractual Clauses\n    (SCCs)\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework, to which Google LLC is certified\nsubprocessors:\n  url: null\n  text: Sub-processor Purpose Location / transfer mechanism Stripe Payments Europe Ltd Subscription billing, card\n    processing, customer records Ireland (EEA).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request deletion from your account page\n  text: 'Right to erasure / \"right to be forgotten\" (Art. 17): request deletion from your account page (30-day grace\n    period; permanent thereafter).'\nrights:\n- right: Access\n  text: 'Right of access (Art. 15): download a copy of\
  \ all personal data we hold on you via /account/data.json (logged-in\n    users) or by emailing the DPO.'\n- right: Portability\n  text: 'Right to data portability (Art. 20): your data is provided in machine-readable JSON and CSV'\n- right: Rectification\n  text: 'Right to rectification (Art. 16): edit your details at any time from your account page .'\n- right: Erasure\n  text: 'Right to erasure / \"right to be forgotten\" (Art. 17): request deletion from your account page'\n- right: Restrict processing\n  text: 'Right to restrict processing (Art. 18): deactivate your account from your account page .'\n- right: Object\n  text: 'Right to object (Art. 21): contact dpo (at) thirdtrail.life .'\n- right: Withdraw consent\n  text: 'Right to withdraw consent : where processing is based on consent, you can withdraw it without affecting\n    the lawfulness of past processing.'\n- right: Complain\n  text: Right to lodge a complaint with your supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/thirdtrail-life/privacy/thirdtrail-life-privacy-policy.yml
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
summary_line: 31 quoted statements, read from thirdtrail-life's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Astronomy
- Tides
- Solar
---
