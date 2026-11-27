---
api_specs:
- filename: agentrevenuenetwork-com-opportunities-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Opportunities API
  slug: agentrevenuenetwork-com-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-opportunities-api-openapi.yml
- filename: agentrevenuenetwork-com-packages-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Packages API
  slug: agentrevenuenetwork-com-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-packages-api-openapi.yml
- filename: agentrevenuenetwork-com-payment-guide-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Payment Guide API
  slug: agentrevenuenetwork-com-payment-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-payment-guide-api-openapi.yml
- filename: agentrevenuenetwork-com-providers-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Providers API
  slug: agentrevenuenetwork-com-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-providers-api-openapi.yml
- filename: agentrevenuenetwork-com-release-guard-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Release Guard API
  slug: agentrevenuenetwork-com-release-guard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-release-guard-api-openapi.yml
- filename: agentrevenuenetwork-com-repeat-verification-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Repeat Verification API
  slug: agentrevenuenetwork-com-repeat-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-repeat-verification-api-openapi.yml
- filename: agentrevenuenetwork-com-requests-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Requests API
  slug: agentrevenuenetwork-com-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-requests-api-openapi.yml
- filename: agentrevenuenetwork-com-tools-api-openapi.yml
  format: yaml
  label: Agent Revenue Network Tools API
  slug: agentrevenuenetwork-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrevenuenetwork-com/openapi/agentrevenuenetwork-com-tools-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: contact
    text: contact details explicitly submitted for a professional-service request
  - category: financial
    text: payment address, transaction receipt and settlement/accounting metadata
  - category: identifying
    text: ARN stores subscription or x402 settlement identifiers, entitlement state, metered call totals, hashed API keys, hashed payer identity, request hashes and verification outcomes.
  - category: other
    text: hashed rate-limit subject
  deletion:
    route: null
    text: Expired open requests are deleted; contact fields on retained pipeline evidence are redacted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation, abuse prevention, payment reconciliation
    text: Operate requested agent tools, review consented service requests, prevent abuse, reconcile payments and diagnose reliability.
  - purpose: payment processing
    text: Stripe may collect the purchaser billing address for payment processing and tax-jurisdiction assessment.
  retention:
  - period: up to 30 days
    scope: secure audit form requests
    text: The secure audit form stores the supplied email, organization, region, concern and notes in the private owner dashboard for up to 30 days.
  - period: null
    scope: operational and accounting records
    text: Operational and accounting records are retained only for operational, security, accounting or legal purposes; request payloads are not intentionally retained as a product dataset.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Revenue Network
provenance_date: '2026-11-09'
provider_name: Agent Revenue Network
provider_slug: agentrevenuenetwork-com
slug: agentrevenuenetwork-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentrevenuenetwork-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentrevenuenetwork.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Revenue Network\naid: agentrevenuenetwork-com\nurl: https://agentrevenuenetwork.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: contact details explicitly submitted for a professional-service request\n- category: financial\n  text: payment address, transaction receipt and settlement/accounting metadata\n- category: identifying\n  text: ARN stores subscription or x402 settlement identifiers, entitlement state, metered call totals, hashed API\n    keys, hashed payer identity, request hashes and verification outcomes.\n- category:\
  \ other\n  text: hashed rate-limit subject\npurposes:\n- purpose: service operation, abuse prevention, payment reconciliation\n  text: Operate requested agent tools, review consented service requests, prevent abuse, reconcile payments and\n    diagnose reliability.\n- purpose: payment processing\n  text: Stripe may collect the purchaser billing address for payment processing and tax-jurisdiction assessment.\nretention:\n- scope: secure audit form requests\n  period: up to 30 days\n  text: The secure audit form stores the supplied email, organization, region, concern and notes in the private\n    owner dashboard for up to 30 days.\n- scope: operational and accounting records\n  period: null\n  text: Operational and accounting records are retained only for operational, security, accounting or legal purposes;\n    request payloads are not intentionally retained as a product dataset.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: null\n  text: Expired open requests are deleted; contact fields on retained pipeline evidence are redacted.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentrevenuenetwork-com/privacy/agentrevenuenetwork-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 9 quoted statements, read from Agent Revenue Network's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- MCP
- Tools
---
