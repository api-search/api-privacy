---
api_specs:
- filename: postalform-com-api-keys-api-openapi.yml
  format: yaml
  label: PostalForm Api Keys API
  slug: postalform-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-api-keys-api-openapi.yml
- filename: postalform-com-credits-api-openapi.yml
  format: yaml
  label: PostalForm Credits API
  slug: postalform-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-credits-api-openapi.yml
- filename: postalform-com-documents-api-openapi.yml
  format: yaml
  label: PostalForm Documents API
  slug: postalform-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-documents-api-openapi.yml
- filename: postalform-com-letters-api-openapi.yml
  format: yaml
  label: PostalForm Letters API
  slug: postalform-com-letters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-letters-api-openapi.yml
- filename: postalform-com-machine-api-openapi.yml
  format: yaml
  label: PostalForm Machine API
  slug: postalform-com-machine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-machine-api-openapi.yml
- filename: postalform-com-postcards-api-openapi.yml
  format: yaml
  label: PostalForm Postcards API
  slug: postalform-com-postcards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-postcards-api-openapi.yml
- filename: postalform-com-return-receipts-api-openapi.yml
  format: yaml
  label: PostalForm Return Receipts API
  slug: postalform-com-return-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-return-receipts-api-openapi.yml
- filename: postalform-com-webhook-endpoints-api-openapi.yml
  format: yaml
  label: PostalForm Webhook Endpoints API
  slug: postalform-com-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-webhook-endpoints-api-openapi.yml
- filename: postalform-com-webhook-events-api-openapi.yml
  format: yaml
  label: PostalForm Webhook Events API
  slug: postalform-com-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postalform-com/openapi/postalform-com-webhook-events-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact info: name and email.'
  - category: identifying
    text: 'Order and fulfillment info: recipient name/address, return address (if provided), order metadata, and payment status.'
  - category: financial
    text: We do not receive or store full payment card numbers.
  - category: device
    text: 'Technical data: IP address, device/browser information, timestamps, and log data associated with your use of the Service.'
  - category: other
    text: 'Document content: the files or content you submit for printing/mailing (which may include personal information depending on what you upload).'
  deletion:
    route: contact support
    text: You can contact us to request access, correction, or deletion of certain information, subject to legal limits.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: process, print and deliver orders
    text: To process, print, and deliver orders.
  - purpose: customer support
    text: To provide customer support and communicate about your order.
  - purpose: security and fraud prevention
    text: To maintain security, prevent fraud/abuse, and enforce our Terms, Acceptable Use Policy, and Content Policy.
  - purpose: legal compliance
    text: To comply with legal obligations and respond to lawful requests.
  retention:
  - period: null
    scope: document content
    text: we may retain submitted documents for a limited period to provide support and handle reprints, then delete them on a schedule determined by our operations.
  - period: null
    scope: order records
    text: 'Order records: may be retained longer for accounting, fraud prevention, and legal compliance.'
  - period: 30 days
    scope: draft capability
    text: A draft capability expires after 30 days.
  rights:
  - right: access
    text: You can contact us to request access, correction, or deletion of certain information, subject to legal limits.
  - right: correction
    text: You can contact us to request access, correction, or deletion of certain information, subject to legal limits.
  - right: opt out of non-transactional emails
    text: You can opt out of non-transactional emails where applicable.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PostalForm
provenance_date: '2026-11-10'
provider_name: PostalForm
provider_slug: postalform-com
slug: postalform-com-privacy-policy
source_date: '2026-11-10'
source_filename: postalform-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://postalform.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PostalForm\naid: postalform-com\nurl: https://postalform.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Contact info: name and email.'\n- category: identifying\n  text: 'Order and fulfillment info: recipient name/address, return address (if provided), order metadata, and payment\n    status.'\n- category: financial\n  text: We do not receive or store full payment card numbers.\n- category: device\n  text: 'Technical data: IP address, device/browser information, timestamps, and log data associated with your use\n    of the Service.'\n\
  - category: other\n  text: 'Document content: the files or content you submit for printing/mailing (which may include personal information\n    depending on what you upload).'\npurposes:\n- purpose: process, print and deliver orders\n  text: To process, print, and deliver orders.\n- purpose: customer support\n  text: To provide customer support and communicate about your order.\n- purpose: security and fraud prevention\n  text: To maintain security, prevent fraud/abuse, and enforce our Terms, Acceptable Use Policy, and Content Policy.\n- purpose: legal compliance\n  text: To comply with legal obligations and respond to lawful requests.\nretention:\n- scope: document content\n  period: null\n  text: we may retain submitted documents for a limited period to provide support and handle reprints, then delete\n    them on a schedule determined by our operations.\n- scope: order records\n  period: null\n  text: 'Order records: may be retained longer for accounting, fraud prevention, and legal\
  \ compliance.'\n- scope: draft capability\n  period: 30 days\n  text: A draft capability expires after 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact support\n  text: You can contact us to request access, correction, or deletion of certain information, subject to legal limits.\nrights:\n- right: access\n  text: You can contact us to request access, correction, or deletion of certain information, subject to legal limits.\n- right: correction\n  text: You can contact us to request access, correction, or deletion of certain information, subject to legal limits.\n- right: opt out of non-transactional emails\n  text: You can opt out of non-transactional emails where applicable.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/postalform-com/privacy/postalform-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from PostalForm's own page on 2026-11-10.
synthetic: false
tags:
- Physical Mail
- Print & Mail
- Postal Mail
- Certified Mail
- Documents
- Agents
- Agentic Commerce
- MCP
- A2A
- x402
- Machine Payments
- Webhook
- Agent-Native
- United States
---
