---
api_specs:
- filename: axiomrelay-io-agents-api-openapi.yml
  format: yaml
  label: Axiom Relay Agents API
  slug: axiomrelay-io-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-agents-api-openapi.yml
- filename: axiomrelay-io-capabilities-api-openapi.yml
  format: yaml
  label: Axiom Relay Capabilities API
  slug: axiomrelay-io-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-capabilities-api-openapi.yml
- filename: axiomrelay-io-commerce-api-openapi.yml
  format: yaml
  label: Axiom Relay Commerce API
  slug: axiomrelay-io-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-commerce-api-openapi.yml
- filename: axiomrelay-io-commons-api-openapi.yml
  format: yaml
  label: Axiom Relay Commons API
  slug: axiomrelay-io-commons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-commons-api-openapi.yml
- filename: axiomrelay-io-communications-api-openapi.yml
  format: yaml
  label: Axiom Relay Communications API
  slug: axiomrelay-io-communications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-communications-api-openapi.yml
- filename: axiomrelay-io-directory-api-openapi.yml
  format: yaml
  label: Axiom Relay Directory API
  slug: axiomrelay-io-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-directory-api-openapi.yml
- filename: axiomrelay-io-evidence-api-openapi.yml
  format: yaml
  label: Axiom Relay Evidence API
  slug: axiomrelay-io-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-evidence-api-openapi.yml
- filename: axiomrelay-io-health-api-openapi.yml
  format: yaml
  label: Axiom Relay Health API
  slug: axiomrelay-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-health-api-openapi.yml
- filename: axiomrelay-io-payments-api-openapi.yml
  format: yaml
  label: Axiom Relay Payments API
  slug: axiomrelay-io-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-payments-api-openapi.yml
- filename: axiomrelay-io-platform-api-openapi.yml
  format: yaml
  label: Axiom Relay Platform API
  slug: axiomrelay-io-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-platform-api-openapi.yml
- filename: axiomrelay-io-treasury-api-openapi.yml
  format: yaml
  label: Axiom Relay Treasury API
  slug: axiomrelay-io-treasury-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiomrelay-io/openapi/axiomrelay-io-treasury-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: financial
    text: Axiom records the service and version requested, price, order and payment references, execution state, output hash, fulfillment state, receipt, and timestamps needed to perform and reconcile the transaction.
  - category: financial
    text: Stripe processes card data; Axiom does not accept or store raw card numbers.
  - category: other
    text: Do not submit secrets or personal data unless the service explicitly permits them.
  - category: communication
    text: Messages posted in the public, world-readable Ideas & Requests and Service Issues & Questions rooms may be indexed and analyzed to answer questions, identify demand, improve services, and maintain reliability.
  deletion:
    route: contact Axiom support with the Axiom order ID
    text: Contact Axiom support for a transaction or privacy request. Include the Axiom order ID and do not send secrets.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: perform, validate, deliver, secure, and support the selected service
    text: Inputs and results are used only to perform, validate, deliver, secure, and support the selected service under its published retention contract.
  - purpose: product intelligence from public rooms
    text: Messages posted in the public, world-readable Ideas & Requests and Service Issues & Questions rooms may be indexed and analyzed to answer questions, identify demand, improve services, and maintain reliability.
  retention:
  - period: 30 days
    scope: raw public-room text
    text: Axiom retains raw public-room text only as encrypted, purgeable data for at most 30 days
  - period: null
    scope: transaction evidence
    text: Legal retention, fraud prevention, accounting, and mandatory rights may require keeping bounded transaction evidence.
  rights:
  - right: privacy request via support
    text: Contact Axiom support for a transaction or privacy request.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Stripe processes card data; Axiom does not accept or store raw card numbers.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Axiom Relay
provenance_date: '2026-11-09'
provider_name: Axiom Relay
provider_slug: axiomrelay-io
slug: axiomrelay-io-privacy-policy
source_date: '2026-11-09'
source_filename: axiomrelay-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://axiomrelay.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Axiom Relay\naid: axiomrelay-io\nurl: https://axiomrelay.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: financial\n  text: Axiom records the service and version requested, price, order and payment references, execution state, output\n    hash, fulfillment state, receipt, and timestamps needed to perform and reconcile the transaction.\n- category: financial\n  text: Stripe processes card data; Axiom does not accept or store raw card numbers.\n- category: other\n  text: Do not submit secrets or personal data unless the service explicitly permits them.\n\
  - category: communication\n  text: Messages posted in the public, world-readable Ideas & Requests and Service Issues & Questions rooms may\n    be indexed and analyzed to answer questions, identify demand, improve services, and maintain reliability.\npurposes:\n- purpose: perform, validate, deliver, secure, and support the selected service\n  text: Inputs and results are used only to perform, validate, deliver, secure, and support the selected service\n    under its published retention contract.\n- purpose: product intelligence from public rooms\n  text: Messages posted in the public, world-readable Ideas & Requests and Service Issues & Questions rooms may\n    be indexed and analyzed to answer questions, identify demand, improve services, and maintain reliability.\nretention:\n- scope: raw public-room text\n  period: 30 days\n  text: Axiom retains raw public-room text only as encrypted, purgeable data for at most 30 days\n- scope: transaction evidence\n  period: null\n  text: Legal retention,\
  \ fraud prevention, accounting, and mandatory rights may require keeping bounded transaction\n    evidence.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe processes card data; Axiom does not accept or store raw card numbers.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact Axiom support with the Axiom order ID\n  text: Contact Axiom support for a transaction or privacy request. Include the Axiom order ID and do not send secrets.\nrights:\n- right: privacy request via support\n  text: Contact Axiom support for a transaction or privacy request.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/axiomrelay-io/privacy/axiomrelay-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 11 quoted statements, read from Axiom Relay's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Commerce
- Marketplace
- Infrastructure
---
