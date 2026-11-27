---
api_specs:
- filename: amass-tech-cores-biomedcore-api-openapi.yml
  format: yaml
  label: Amass Cores/biomedcore API
  slug: amass-tech-cores-biomedcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-biomedcore-api-openapi.yml
- filename: amass-tech-cores-drugcore-api-openapi.yml
  format: yaml
  label: Amass Cores/drugcore API
  slug: amass-tech-cores-drugcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-drugcore-api-openapi.yml
- filename: amass-tech-cores-genecore-api-openapi.yml
  format: yaml
  label: Amass Cores/genecore API
  slug: amass-tech-cores-genecore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-genecore-api-openapi.yml
- filename: amass-tech-cores-patentcore-api-openapi.yml
  format: yaml
  label: Amass Cores/patentcore API
  slug: amass-tech-cores-patentcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-patentcore-api-openapi.yml
- filename: amass-tech-cores-regulatorycore-api-openapi.yml
  format: yaml
  label: Amass Cores/regulatorycore API
  slug: amass-tech-cores-regulatorycore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-regulatorycore-api-openapi.yml
- filename: amass-tech-cores-trialcore-api-openapi.yml
  format: yaml
  label: Amass Cores/trialcore API
  slug: amass-tech-cores-trialcore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-cores-trialcore-api-openapi.yml
- filename: amass-tech-credits-api-openapi.yml
  format: yaml
  label: Amass Credits API
  slug: amass-tech-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amass-tech/openapi/amass-tech-credits-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name Email address Role (for example, user or administrator) Organization
  - category: contact
    text: Email address
  - category: financial
    text: Name associated with payment method Last four digits of payment card Card type and expiry date Payment status Transaction and billing metadata
  - category: device
    text: IP address Device, browser, and session identifiers
  - category: behavioral
    text: Navigation and feature usage data
  - category: communication
    text: Messages, support requests, and related correspondence
  - category: other
    text: Customer-Submitted Content Where users of the subscription platform upload or submit documents, files, notes, metadata, prompts, or other content, such content may include personal data provided by or on behalf of the customer.
  deletion:
    route: null
    text: deleted within thirty (30) days following termination
  dpa:
    available: null
    text: in accordance with the applicable Data Processing Agreement ("DPA"), where relevant
    url: null
  purposes:
  - purpose: Provide and secure services
    text: provide, operate, maintain, and secure our website and subscription platform
  - purpose: Billing and payments
    text: process billing and payments
  - purpose: Monitoring and improvement
    text: improve the functionality, usability, and user experience of the website and subscription platform
  - purpose: Customer content processing
    text: For the subscription platform, customer-submitted content is processed only to provide, maintain, secure, support, and improve the subscription services in accordance with the applicable contract and documented customer instructions.
  residency:
  - region: European Union
    text: Primary customer content for the subscription platform is hosted in the European Union.
  retention:
  - period: thirty (30) days
    scope: Customer-submitted data in subscription platform
    text: Customer-submitted data in the subscription platform is generally retained for the duration of the applicable contract and deleted within thirty (30) days following termination
  - period: null
    scope: Account data
    text: for as long as an account remains active
  rights:
  - right: access
    text: access your personal data
  - right: rectification
    text: rectify inaccurate or incomplete personal data
  - right: erasure
    text: request erasure of personal data
  - right: restriction
    text: request restriction of processing
  - right: objection
    text: object to processing
  - right: portability
    text: request data portability
  - right: complaint
    text: lodge a complaint with a competent supervisory authority
  role:
    text: 'Amass acts as: Data Controller for personal data processed for website operations, account administration, billing, service analytics, security logging, communications, and our own business operations.'
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: adequacy decisions adopted by the European Commission
  - mechanism: SCC
    text: Standard Contractual Clauses ("SCCs") approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Amass
provenance_date: '2026-11-09'
provider_name: Amass
provider_slug: amass-tech
slug: amass-tech-privacy-policy
source_date: '2026-11-09'
source_filename: amass-tech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://amass.tech/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Amass\naid: amass-tech\nurl: https://amass.tech/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Amass acts as: Data Controller for personal data processed for website operations, account administration,\n    billing, service analytics, security logging, communications, and our own business operations.'\ndata_categories:\n- category: identifying\n  text: Full name Email address Role (for example, user or administrator) Organization\n- category: contact\n  text: Email address\n- category: financial\n  text: Name associated with payment method Last four digits of payment card Card\
  \ type and expiry date Payment status\n    Transaction and billing metadata\n- category: device\n  text: IP address Device, browser, and session identifiers\n- category: behavioral\n  text: Navigation and feature usage data\n- category: communication\n  text: Messages, support requests, and related correspondence\n- category: other\n  text: Customer-Submitted Content Where users of the subscription platform upload or submit documents, files, notes,\n    metadata, prompts, or other content, such content may include personal data provided by or on behalf of the\n    customer.\npurposes:\n- purpose: Provide and secure services\n  text: provide, operate, maintain, and secure our website and subscription platform\n- purpose: Billing and payments\n  text: process billing and payments\n- purpose: Monitoring and improvement\n  text: improve the functionality, usability, and user experience of the website and subscription platform\n- purpose: Customer content processing\n  text: For the subscription\
  \ platform, customer-submitted content is processed only to provide, maintain, secure,\n    support, and improve the subscription services in accordance with the applicable contract and documented customer\n    instructions.\nretention:\n- scope: Customer-submitted data in subscription platform\n  period: thirty (30) days\n  text: Customer-submitted data in the subscription platform is generally retained for the duration of the applicable\n    contract and deleted within thirty (30) days following termination\n- scope: Account data\n  period: null\n  text: for as long as an account remains active\nresidency:\n- region: European Union\n  text: Primary customer content for the subscription platform is hosted in the European Union.\ntransfers:\n- mechanism: adequacy\n  text: adequacy decisions adopted by the European Commission\n- mechanism: SCC\n  text: Standard Contractual Clauses (\"SCCs\") approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: in accordance with the applicable Data Processing Agreement (\"DPA\"), where relevant\ndeletion:\n  route: null\n  text: deleted within thirty (30) days following termination\nrights:\n- right: access\n  text: access your personal data\n- right: rectification\n  text: rectify inaccurate or incomplete personal data\n- right: erasure\n  text: request erasure of personal data\n- right: restriction\n  text: request restriction of processing\n- right: objection\n  text: object to processing\n- right: portability\n  text: request data portability\n- right: complaint\n  text: lodge a complaint with a competent supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amass-tech/privacy/amass-tech-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 26 quoted statements, read from Amass's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Data Intelligence
- MCP
---
