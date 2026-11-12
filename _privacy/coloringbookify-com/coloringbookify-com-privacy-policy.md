---
api_specs:
- filename: coloringbookify-com-account-api-openapi.yml
  format: yaml
  label: ColoringBookify Account API
  slug: coloringbookify-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-account-api-openapi.yml
- filename: coloringbookify-com-books-api-openapi.yml
  format: yaml
  label: ColoringBookify Books API
  slug: coloringbookify-com-books-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-books-api-openapi.yml
- filename: coloringbookify-com-characters-api-openapi.yml
  format: yaml
  label: ColoringBookify Characters API
  slug: coloringbookify-com-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-characters-api-openapi.yml
- filename: coloringbookify-com-operations-api-openapi.yml
  format: yaml
  label: ColoringBookify Operations API
  slug: coloringbookify-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-operations-api-openapi.yml
- filename: coloringbookify-com-pages-api-openapi.yml
  format: yaml
  label: ColoringBookify Pages API
  slug: coloringbookify-com-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-pages-api-openapi.yml
- filename: coloringbookify-com-planning-api-openapi.yml
  format: yaml
  label: ColoringBookify Planning API
  slug: coloringbookify-com-planning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-planning-api-openapi.yml
- filename: coloringbookify-com-print-api-openapi.yml
  format: yaml
  label: ColoringBookify Print API
  slug: coloringbookify-com-print-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-print-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect the information needed to provide the service, including your name, email address, account and subscription status, prompts, uploaded images, generated pages and books, support messages, and actions you take in the application.
  - category: financial
    text: We receive billing identifiers, plan and payment status, but we do not store your full payment-card number.
  - category: device
    text: We collect technical and usage information such as IP address, browser, device, referring page, session and analytics events to operate, secure, and improve the service.
  deletion:
    route: Email the provider to request account or personal-data deletion
    text: There is currently no self-service account-deletion button. Email us to request account or personal-data deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and secure service
    text: We use information to authenticate accounts, generate and store content, process payments and print orders, provide support, send service messages, prevent misuse, understand product performance, and comply with legal obligations.
  retention:
  - period: null
    scope: Account data and assets
    text: Account data and assets are retained while your account and related records remain active, and longer where reasonably needed for security, dispute resolution, payment and accounting obligations, or legal compliance.
  rights:
  - right: access, correction, deletion
    text: you may request access to, correction of, or deletion of personal information
  - right: object or withdraw consent
    text: may object to or withdraw consent for some uses
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Providers may process information in other countries under their own legal obligations.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ColoringBookify
provenance_date: '2026-11-09'
provider_name: ColoringBookify
provider_slug: coloringbookify-com
slug: coloringbookify-com-privacy-policy
source_date: '2026-11-09'
source_filename: coloringbookify-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coloringbookify.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ColoringBookify\naid: coloringbookify-com\nurl: https://coloringbookify.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect the information needed to provide the service, including your name, email address, account and\n    subscription status, prompts, uploaded images, generated pages and books, support messages, and actions you\n    take in the application.\n- category: financial\n  text: We receive billing identifiers, plan and payment status, but we do not store your full payment-card number.\n- category: device\n\
  \  text: We collect technical and usage information such as IP address, browser, device, referring page, session\n    and analytics events to operate, secure, and improve the service.\npurposes:\n- purpose: Operate and secure service\n  text: We use information to authenticate accounts, generate and store content, process payments and print orders,\n    provide support, send service messages, prevent misuse, understand product performance, and comply with legal\n    obligations.\nretention:\n- scope: Account data and assets\n  period: null\n  text: Account data and assets are retained while your account and related records remain active, and longer where\n    reasonably needed for security, dispute resolution, payment and accounting obligations, or legal compliance.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Providers may process information in other countries under their own legal obligations.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: Email the provider to request account or personal-data deletion\n  text: There is currently no self-service account-deletion button. Email us to request account or personal-data\n    deletion.\nrights:\n- right: access, correction, deletion\n  text: you may request access to, correction of, or deletion of personal information\n- right: object or withdraw consent\n  text: may object to or withdraw consent for some uses\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/coloringbookify-com/privacy/coloringbookify-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from ColoringBookify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Coloring Books
- Image Generation
- PDF Generation
- Printing
- Publishing
- MCP
---
