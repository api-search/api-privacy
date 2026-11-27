---
api_specs:
- filename: short-io-audit-api-openapi.yml
  format: yaml
  label: Short.io Audit API
  slug: short-io-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-audit-api-openapi.yml
- filename: short-io-domain-dns-api-openapi.yml
  format: yaml
  label: Short.io Domain DNS API
  slug: short-io-domain-dns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-domain-dns-api-openapi.yml
- filename: short-io-domains-api-openapi.yml
  format: yaml
  label: Short.io Domains API
  slug: short-io-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-domains-api-openapi.yml
- filename: short-io-link-bundles-api-openapi.yml
  format: yaml
  label: Short.io Link Bundles API
  slug: short-io-link-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-bundles-api-openapi.yml
- filename: short-io-link-duplication-api-openapi.yml
  format: yaml
  label: Short.io Link Duplication API
  slug: short-io-link-duplication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-duplication-api-openapi.yml
- filename: short-io-link-management-api-openapi.yml
  format: yaml
  label: Short.io Link Management API
  slug: short-io-link-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-management-api-openapi.yml
- filename: short-io-link-queries-api-openapi.yml
  format: yaml
  label: Short.io Link queries API
  slug: short-io-link-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-queries-api-openapi.yml
- filename: short-io-link-targeting-api-openapi.yml
  format: yaml
  label: Short.io Link Targeting API
  slug: short-io-link-targeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-link-targeting-api-openapi.yml
- filename: short-io-organizations-api-openapi.yml
  format: yaml
  label: Short.io Organizations API
  slug: short-io-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-organizations-api-openapi.yml
- filename: short-io-posts-api-openapi.yml
  format: yaml
  label: Short.io Posts API
  slug: short-io-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-posts-api-openapi.yml
- filename: short-io-qr-codes-api-openapi.yml
  format: yaml
  label: Short.io QR Codes API
  slug: short-io-qr-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/short-io/openapi/short-io-qr-codes-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — name, email address, and password when you register.
  - category: behavioral
    text: Usage data — links you create, click statistics, prompts you submit to AI features, and how you interact with the dashboard.
  - category: device
    text: Technical data — IP address, browser type, device information, and cookie identifiers.
  - category: financial
    text: Billing data — payment details processed by our payment provider when you subscribe to a paid plan.
  deletion:
    route: Request deletion via contact email or privacy contact
    text: You can request deletion of your data at any time (see "Your rights" below).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain and improve the service
    text: To provide, maintain, and improve the Short.io service.
  - purpose: Process payments
    text: To process payments and manage your subscription.
  - purpose: AI-assisted features
    text: To power AI-assisted features, such as link and content suggestions and the in-product assistant.
  - purpose: Fraud and security
    text: To detect, prevent, and investigate fraud, abuse, and security threats.
  - purpose: Legal obligations
    text: To comply with legal obligations.
  residency:
  - region: EU
    text: Our EU cluster runs on Amazon Web Services in Frankfurt, Germany.
  - region: US
    text: We are moving Short.io's US cluster from Amazon Web Services in the United States to dedicated bare metal servers in three independent data centers in the Dallas, Texas area
  retention:
  - period: null
    scope: Personal data generally
    text: We retain personal data only for as long as necessary to provide the service and to comply with our legal obligations.
  rights:
  - right: Access
    text: Right to access — Request a copy of your personal data we hold
  - right: Rectification
    text: Right to rectification — Request correction of inaccurate data
  - right: Erasure
    text: Right to erasure — Request deletion of your personal data
  - right: Restrict processing
    text: Right to restrict processing — Limit how we use your data
  - right: Portability
    text: Right to data portability — Receive your data in a portable format
  - right: Object
    text: Right to object — Object to processing based on legitimate interests
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: See the list of subprocessors below.
    url: https://short.io/privacy
  transfers:
  - mechanism: SCC
    text: for transfers from the EU/EEA we use the European Commission's Standard Contractual Clauses
  - mechanism: other
    text: for transfers from the UK we use the UK International Data Transfer Agreement (IDTA) or the UK Addendum to the EU Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Short.io
provenance_date: '2026-11-10'
provider_name: Short.io
provider_slug: short-io
slug: short-io-privacy-policy
source_date: '2026-11-10'
source_filename: short-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://short.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Short.io\naid: short-io\nurl: https://short.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — name, email address, and password when you register.\n- category: behavioral\n  text: Usage data — links you create, click statistics, prompts you submit to AI features, and how you interact\n    with the dashboard.\n- category: device\n  text: Technical data — IP address, browser type, device information, and cookie identifiers.\n- category: financial\n  text: Billing data — payment details processed by our payment provider\
  \ when you subscribe to a paid plan.\npurposes:\n- purpose: Provide, maintain and improve the service\n  text: To provide, maintain, and improve the Short.io service.\n- purpose: Process payments\n  text: To process payments and manage your subscription.\n- purpose: AI-assisted features\n  text: To power AI-assisted features, such as link and content suggestions and the in-product assistant.\n- purpose: Fraud and security\n  text: To detect, prevent, and investigate fraud, abuse, and security threats.\n- purpose: Legal obligations\n  text: To comply with legal obligations.\nretention:\n- scope: Personal data generally\n  period: null\n  text: We retain personal data only for as long as necessary to provide the service and to comply with our legal\n    obligations.\nresidency:\n- region: EU\n  text: Our EU cluster runs on Amazon Web Services in Frankfurt, Germany.\n- region: US\n  text: We are moving Short.io's US cluster from Amazon Web Services in the United States to dedicated bare metal\n\
  \    servers in three independent data centers in the Dallas, Texas area\ntransfers:\n- mechanism: SCC\n  text: for transfers from the EU/EEA we use the European Commission's Standard Contractual Clauses\n- mechanism: other\n  text: for transfers from the UK we use the UK International Data Transfer Agreement (IDTA) or the UK Addendum\n    to the EU Standard Contractual Clauses.\nsubprocessors:\n  url: https://short.io/privacy\n  text: See the list of subprocessors below.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via contact email or privacy contact\n  text: You can request deletion of your data at any time (see \"Your rights\" below).\nrights:\n- right: Access\n  text: Right to access — Request a copy of your personal data we hold\n- right: Rectification\n  text: Right to rectification — Request correction of inaccurate data\n- right: Erasure\n  text: Right to erasure — Request deletion of your personal data\n- right: Restrict processing\n\
  \  text: Right to restrict processing — Limit how we use your data\n- right: Portability\n  text: Right to data portability — Receive your data in a portable format\n- right: Object\n  text: Right to object — Object to processing based on legitimate interests\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/short-io/privacy/short-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Short.io's own page on 2026-11-10.
synthetic: false
tags:
- URL Shortening
- Analytics
- QR Codes
- Enterprise
- Integration
---
