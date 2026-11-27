---
api_specs:
- filename: vulk-dev-models-api-openapi.yml
  format: yaml
  label: vulk-dev Models API
  slug: vulk-dev-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-models-api-openapi.yml
- filename: vulk-dev-operations-api-openapi.yml
  format: yaml
  label: vulk-dev Operations API
  slug: vulk-dev-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-operations-api-openapi.yml
- filename: vulk-dev-pay-as-you-go-previous-vulk-api-openapi.yml
  format: yaml
  label: vulk-dev Pay-as-you-go (previous VULK) API
  slug: vulk-dev-pay-as-you-go-previous-vulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-pay-as-you-go-previous-vulk-api-openapi.yml
- filename: vulk-dev-projects-api-openapi.yml
  format: yaml
  label: vulk-dev Projects API
  slug: vulk-dev-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-projects-api-openapi.yml
- filename: vulk-dev-usage-api-openapi.yml
  format: yaml
  label: vulk-dev Usage API
  slug: vulk-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vulk-dev/openapi/vulk-dev-usage-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, billing address, payment details (processed securely via Stripe)
  - category: device
    text: information about your web browser, IP address, time zone, and cookies installed on your device
  - category: behavioral
    text: we collect information about the individual pages you view, what websites or search terms referred you to the Site, and how you interact with the Site
  - category: other
    text: we store the prompts you submit, the generated source files, deployment metadata, and billing usage
  deletion:
    route: account deletion; contact form with topic "Privacy / DPO"
    text: Right to erasure ("right to be forgotten") — request deletion
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: process orders and payments
    text: Process your orders, payments, and generate invoices
  - purpose: fraud screening
    text: Screen for potential fraud or risks
  - purpose: improve Site experience
    text: Improve and optimize the Site experience
  - purpose: AI generation
    text: we forward the prompt and any attached images, files, or context you choose to share to a third-party large language model
  residency:
  - region: EU
    text: Your account and project database stays in the EU (AWS Frankfurt).
  - region: Outside EU
    text: AI models run outside the EU, mostly in the United States
  retention:
  - period: 90 days
    scope: account activity records
    text: Deleted automatically after 90 days and when you delete your account.
  - period: 7 years
    scope: billing records after account deletion
    text: After account deletion, billing records are kept for 7 years to comply with Portuguese tax law
  - period: 30 days
    scope: everything else after account deletion
    text: everything else is purged within 30 days
  rights:
  - right: access
    text: Right of access — request a copy of the data we hold about you
  - right: rectification
    text: Right to rectification — correct inaccurate or incomplete data
  - right: erasure
    text: Right to erasure ("right to be forgotten") — request deletion
  - right: restrict processing
    text: Right to restrict processing — limit how we use your data
  - right: portability
    text: Right to data portability — export your data in a machine-readable format
  - right: object
    text: Right to object — opt out of marketing or profiling
  - right: complaint
    text: 'Right to lodge a complaint — with your national data-protection authority (in Portugal: CNPD )'
  role:
    text: Code Ahead Establishes and documents the transfer mechanism
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information.
  subprocessors:
    text: The subprocessors page lists each supplier and country.
    url: null
  transfers:
  - mechanism: SCC
    text: an adequacy decision or Standard Contractual Clauses (SCCs) approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: vulk-dev
provenance_date: '2026-11-10'
provider_name: vulk-dev
provider_slug: vulk-dev
slug: vulk-dev-privacy-policy
source_date: '2026-11-10'
source_filename: vulk-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vulk.dev/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: vulk-dev\naid: vulk-dev\nurl: https://vulk.dev/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Code Ahead Establishes and documents the transfer mechanism\ndata_categories:\n- category: identifying\n  text: your name, email address, billing address, payment details (processed securely via Stripe)\n- category: device\n  text: information about your web browser, IP address, time zone, and cookies installed on your device\n- category: behavioral\n  text: we collect information about the individual pages you view, what websites or search terms referred you to\n    the Site, and how\
  \ you interact with the Site\n- category: other\n  text: we store the prompts you submit, the generated source files, deployment metadata, and billing usage\npurposes:\n- purpose: process orders and payments\n  text: Process your orders, payments, and generate invoices\n- purpose: fraud screening\n  text: Screen for potential fraud or risks\n- purpose: improve Site experience\n  text: Improve and optimize the Site experience\n- purpose: AI generation\n  text: we forward the prompt and any attached images, files, or context you choose to share to a third-party large\n    language model\nretention:\n- scope: account activity records\n  period: 90 days\n  text: Deleted automatically after 90 days and when you delete your account.\n- scope: billing records after account deletion\n  period: 7 years\n  text: After account deletion, billing records are kept for 7 years to comply with Portuguese tax law\n- scope: everything else after account deletion\n  period: 30 days\n  text: everything else\
  \ is purged within 30 days\nresidency:\n- region: EU\n  text: Your account and project database stays in the EU (AWS Frankfurt).\n- region: Outside EU\n  text: AI models run outside the EU, mostly in the United States\ntransfers:\n- mechanism: SCC\n  text: an adequacy decision or Standard Contractual Clauses (SCCs) approved by the European Commission\nsubprocessors:\n  url: null\n  text: The subprocessors page lists each supplier and country.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion; contact form with topic \"Privacy / DPO\"\n  text: Right to erasure (\"right to be forgotten\") — request deletion\nrights:\n- right: access\n  text: Right of access — request a copy of the data we hold about you\n- right: rectification\n  text: Right to rectification — correct inaccurate or incomplete data\n- right: erasure\n  text: Right to erasure (\"right to be forgotten\") — request deletion\n- right: restrict processing\n  text: Right to restrict processing\
  \ — limit how we use your data\n- right: portability\n  text: Right to data portability — export your data in a machine-readable format\n- right: object\n  text: Right to object — opt out of marketing or profiling\n- right: complaint\n  text: 'Right to lodge a complaint — with your national data-protection authority (in Portugal: CNPD )'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information.\n"
source_yaml_url: https://artifacts.apis.io/vulk-dev/privacy/vulk-dev-privacy-policy.yml
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
summary_line: 25 quoted statements, read from vulk-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- App Builder
- No-Code
- 3D
---
