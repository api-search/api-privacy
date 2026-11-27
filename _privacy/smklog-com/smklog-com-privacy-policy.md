---
api_specs:
- filename: smklog-com-operations-api-openapi.yml
  format: yaml
  label: SMKlog Operations API
  slug: smklog-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-operations-api-openapi.yml
- filename: smklog-com-dimensional-weight-api-openapi.yml
  format: yaml
  label: SMKlog Dimensional Weight API
  slug: smklog-com-dimensional-weight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-dimensional-weight-api-openapi.yml
- filename: smklog-com-holiday-shipping-api-openapi.yml
  format: yaml
  label: SMKlog Holiday Shipping API
  slug: smklog-com-holiday-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-holiday-shipping-api-openapi.yml
- filename: smklog-com-payments-api-openapi.yml
  format: yaml
  label: SMKlog Payments API
  slug: smklog-com-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-payments-api-openapi.yml
- filename: smklog-com-price-index-api-openapi.yml
  format: yaml
  label: SMKlog Price Index API
  slug: smklog-com-price-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-price-index-api-openapi.yml
- filename: smklog-com-refunds-api-openapi.yml
  format: yaml
  label: SMKlog Refunds API
  slug: smklog-com-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-refunds-api-openapi.yml
- filename: smklog-com-shipping-rates-api-openapi.yml
  format: yaml
  label: SMKlog Shipping Rates API
  slug: smklog-com-shipping-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-shipping-rates-api-openapi.yml
- filename: smklog-com-shipping-restrictions-api-openapi.yml
  format: yaml
  label: SMKlog Shipping Restrictions API
  slug: smklog-com-shipping-restrictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-shipping-restrictions-api-openapi.yml
- filename: smklog-com-tracking-api-openapi.yml
  format: yaml
  label: SMKlog Tracking API
  slug: smklog-com-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-tracking-api-openapi.yml
- filename: smklog-com-webhooks-api-openapi.yml
  format: yaml
  label: SMKlog Webhooks API
  slug: smklog-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Business identity details such as name, company, role, and business contact information
  - category: financial
    text: Payment, billing, and checkout metadata needed to process secure quote and label workflows through payment and carrier-service providers
  - category: location
    text: Package and label details such as dimensions, weight, contents, address information, selected carrier service, tracking, and label status
  - category: behavioral
    text: Google Analytics (GA4), which counts visits and shows which pages lead to a quote
  - category: contact
    source: https://smklog.com/trust/subprocessors
    text: Sender and recipient names, addresses, phone numbers, email addresses, parcel contents and dimensions
  - category: financial
    source: https://smklog.com/trust/subprocessors
    text: Payer email, order amount and description
  - category: behavioral
    source: https://smklog.com/trust/subprocessors
    text: Site usage analytics; item descriptions (never names or addresses)
  deletion:
    route: Email request to privacy@smklog.com
    text: You may request access, correction, or deletion of your personal data by contacting privacy@smklog.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Answer shipping quote, label, and support requests
    text: To answer shipping quote, label, and support requests
  - purpose: Check parcel eligibility
    text: To check whether a parcel can be sold online and clarify its details
  - purpose: Service improvement and reporting
    text: To improve service quality, intake accuracy, and operational reporting
  - purpose: Fraud prevention and auditability
    text: Submission metadata and source information needed for service review, fraud prevention, and auditability
  - purpose: hosting and database
    source: https://smklog.com/trust/subprocessors
    text: Hosting (Workers, Pages), database (D1), DNS, edge cache, bot management, operator access control
  - purpose: payment checkout
    source: https://smklog.com/trust/subprocessors
    text: Hosted checkout, receipts, refunds, carrier-adjustment invoices
  - purpose: packaging estimate
    source: https://smklog.com/trust/subprocessors
    text: Packaging estimate and the pre-payment packaging check from item descriptions
  residency:
  - region: United States
    source: https://smklog.com/trust/subprocessors
    text: United States (data in the ENAM region, see data residency)
  retention:
  - period: null
    scope: Business inquiry and request data
    text: We retain business inquiry and request data only as long as needed for service delivery, legal compliance, fraud prevention, and audit purposes.
  - period: 30 days
    scope: API and assistant request records
    text: kept for 30 days to tell real use from automated directory scans
  - period: until the client is revoked
    scope: OAuth API client registrations
    text: kept until the client is revoked
  - period: two days
    scope: Hash of registering IP address
    text: erased after two days
  rights:
  - right: Access, correction, deletion
    text: You may request access, correction, or deletion of your personal data by contacting privacy@smklog.com
  - right: Portability
    text: Where applicable, you may also request portability or object to certain processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    source: https://smklog.com/trust/subprocessors
    text: The complete list of third parties that process customer data on SMKlog’s behalf
    url: https://smklog.com/trust/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SMKlog
provenance_date: '2026-11-10'
provider_name: SMKlog
provider_slug: smklog-com
slug: smklog-com-privacy-policy
source_date: '2026-11-10'
source_filename: smklog-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://smklog.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SMKlog\naid: smklog-com\nurl: https://smklog.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://smklog.com/privacy\n  - https://smklog.com/trust/subprocessors\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Business identity details such as name, company, role, and business contact information\n- category: financial\n  text: Payment, billing, and checkout metadata needed to process secure quote and label workflows through payment\n    and carrier-service providers\n- category: location\n  text: Package and label details such as dimensions, weight, contents,\
  \ address information, selected carrier service,\n    tracking, and label status\n- category: behavioral\n  text: Google Analytics (GA4), which counts visits and shows which pages lead to a quote\n- category: contact\n  text: Sender and recipient names, addresses, phone numbers, email addresses, parcel contents and dimensions\n  source: https://smklog.com/trust/subprocessors\n- category: financial\n  text: Payer email, order amount and description\n  source: https://smklog.com/trust/subprocessors\n- category: behavioral\n  text: Site usage analytics; item descriptions (never names or addresses)\n  source: https://smklog.com/trust/subprocessors\npurposes:\n- purpose: Answer shipping quote, label, and support requests\n  text: To answer shipping quote, label, and support requests\n- purpose: Check parcel eligibility\n  text: To check whether a parcel can be sold online and clarify its details\n- purpose: Service improvement and reporting\n  text: To improve service quality, intake accuracy,\
  \ and operational reporting\n- purpose: Fraud prevention and auditability\n  text: Submission metadata and source information needed for service review, fraud prevention, and auditability\n- purpose: hosting and database\n  text: Hosting (Workers, Pages), database (D1), DNS, edge cache, bot management, operator access control\n  source: https://smklog.com/trust/subprocessors\n- purpose: payment checkout\n  text: Hosted checkout, receipts, refunds, carrier-adjustment invoices\n  source: https://smklog.com/trust/subprocessors\n- purpose: packaging estimate\n  text: Packaging estimate and the pre-payment packaging check from item descriptions\n  source: https://smklog.com/trust/subprocessors\nretention:\n- scope: Business inquiry and request data\n  period: null\n  text: We retain business inquiry and request data only as long as needed for service delivery, legal compliance,\n    fraud prevention, and audit purposes.\n- scope: API and assistant request records\n  period: 30 days\n  text:\
  \ kept for 30 days to tell real use from automated directory scans\n- scope: OAuth API client registrations\n  period: until the client is revoked\n  text: kept until the client is revoked\n- scope: Hash of registering IP address\n  period: two days\n  text: erased after two days\nresidency:\n- region: United States\n  text: United States (data in the ENAM region, see data residency)\n  source: https://smklog.com/trust/subprocessors\ntransfers: []\nsubprocessors:\n  url: https://smklog.com/trust/subprocessors\n  text: The complete list of third parties that process customer data on SMKlog’s behalf\n  source: https://smklog.com/trust/subprocessors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to privacy@smklog.com\n  text: You may request access, correction, or deletion of your personal data by contacting privacy@smklog.com\nrights:\n- right: Access, correction, deletion\n  text: You may request access, correction, or deletion of your personal data\
  \ by contacting privacy@smklog.com\n- right: Portability\n  text: Where applicable, you may also request portability or object to certain processing.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smklog-com/privacy/smklog-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 23 quoted statements, read from SMKlog's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Shipping
- Logistics
- Parcel Shipping
- shipping-rates
- Shipping Labels
- E-Commerce
- Agents
- MCP
- A2A
---
