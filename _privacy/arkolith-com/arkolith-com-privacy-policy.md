---
api_specs:
- filename: arkolith-com-funds-api-openapi.yml
  format: yaml
  label: Arkolith Funds API
  slug: arkolith-com-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arkolith-com/openapi/arkolith-com-funds-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: we process your name, email address, organization details if provided, API-key metadata, billing records
  - category: behavioral
    text: usage logs such as calls made, endpoints, timestamps, IP-derived security data, and error events
  - category: other
    text: The Service includes factual data about identified natural persons obtained from public official registers.
  - category: other
    text: Categories include name, role or position, issuer or entity concerned, reported transaction type, date, and amount range as disclosed in the public filing.
  deletion:
    route: privacy [at] arkolith.com
    text: To exercise rights, contact privacy [at] arkolith.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, secure, meter, bill, debug and improve the Service
    text: We use this data to provide, secure, meter, bill, debug, and improve the Service
  - purpose: financial-market transparency
    text: 'Purposes: financial-market transparency, accountability of mandatory public disclosures, and market-data infrastructure for customers.'
  - purpose: advertising measurement
    text: to measure whether our ads bring visitors and signups
  - purpose: product analytics and session replay
    text: PostHog (PostHog Inc., EU-hosted) for product analytics and session replay
  residency:
  - region: EEA
    text: The Service is hosted in the EEA, including Google Cloud in europe-west1.
  retention:
  - period: life of the account
    scope: account and billing data
    text: Account and billing data is retained for the life of the account and as required by Swedish bookkeeping, tax, and legal obligations after that.
  - period: a limited period
    scope: usage logs
    text: Usage logs are retained for a limited period for security, abuse prevention, debugging, and billing.
  - period: null
    scope: public-record data
    text: Public-record data is retained as historical financial record data consistent with the transparency and point-in-time archive purpose.
  rights:
  - right: access, rectification, erasure, restriction, objection, portability
    text: You have the rights of access, rectification, erasure, restriction, objection, and data portability under the GDPR.
  - right: lodge complaint with supervisory authority
    text: You also have the right to lodge a complaint with the Swedish supervisory authority, Integritetsskyddsmyndigheten (IMY), at imy.se.
  role:
    text: is the controller for personal data processed through the Arkolith API, MCP server, and website.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell account-holder personal data such as names, emails, account details, or billing data for marketing or advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where a sub-processor or upstream source is outside the EEA, transfers are protected by an adequacy decision, EU Standard Contractual Clauses, or another lawful transfer mechanism.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Arkolith
provenance_date: '2026-11-09'
provider_name: Arkolith
provider_slug: arkolith-com
slug: arkolith-com-privacy-policy
source_date: '2026-11-09'
source_filename: arkolith-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://arkolith.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Arkolith\naid: arkolith-com\nurl: https://arkolith.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: is the controller for personal data processed through the Arkolith API, MCP server, and website.\ndata_categories:\n- category: identifying\n  text: we process your name, email address, organization details if provided, API-key metadata, billing records\n- category: behavioral\n  text: usage logs such as calls made, endpoints, timestamps, IP-derived security data, and error events\n- category: other\n  text: The Service includes factual data about identified natural persons obtained\
  \ from public official registers.\n- category: other\n  text: Categories include name, role or position, issuer or entity concerned, reported transaction type, date,\n    and amount range as disclosed in the public filing.\npurposes:\n- purpose: provide, secure, meter, bill, debug and improve the Service\n  text: We use this data to provide, secure, meter, bill, debug, and improve the Service\n- purpose: financial-market transparency\n  text: 'Purposes: financial-market transparency, accountability of mandatory public disclosures, and market-data\n    infrastructure for customers.'\n- purpose: advertising measurement\n  text: to measure whether our ads bring visitors and signups\n- purpose: product analytics and session replay\n  text: PostHog (PostHog Inc., EU-hosted) for product analytics and session replay\nretention:\n- scope: account and billing data\n  period: life of the account\n  text: Account and billing data is retained for the life of the account and as required by Swedish\
  \ bookkeeping,\n    tax, and legal obligations after that.\n- scope: usage logs\n  period: a limited period\n  text: Usage logs are retained for a limited period for security, abuse prevention, debugging, and billing.\n- scope: public-record data\n  period: null\n  text: Public-record data is retained as historical financial record data consistent with the transparency and\n    point-in-time archive purpose.\nresidency:\n- region: EEA\n  text: The Service is hosted in the EEA, including Google Cloud in europe-west1.\ntransfers:\n- mechanism: other\n  text: Where a sub-processor or upstream source is outside the EEA, transfers are protected by an adequacy decision,\n    EU Standard Contractual Clauses, or another lawful transfer mechanism.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacy [at] arkolith.com\n  text: To exercise rights, contact privacy [at] arkolith.com\nrights:\n- right: access, rectification, erasure,\
  \ restriction, objection, portability\n  text: You have the rights of access, rectification, erasure, restriction, objection, and data portability under\n    the GDPR.\n- right: lodge complaint with supervisory authority\n  text: You also have the right to lodge a complaint with the Swedish supervisory authority, Integritetsskyddsmyndigheten\n    (IMY), at imy.se.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell account-holder personal data such as names, emails, account details, or billing data for\n    marketing or advertising.\n"
source_yaml_url: https://artifacts.apis.io/arkolith-com/privacy/arkolith-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Arkolith's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- SEC
- MCP
---
