---
api_specs:
- filename: openapi.json
  format: json
  label: Bankstatemently API
  slug: bankstatemently-api
  spec_type: OpenAPI
  url: https://api.bankstatemently.com/v1/openapi.json
- filename: bankstatemently-com-v1-openapi.json
  format: json
  label: Bankstatemently API V1 API
  slug: bankstatemently-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankstatemently-com/openapi/_original/bankstatemently-com-v1-openapi.json
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Basic account details (e.g. name, email, payment info) when you sign up
  - category: financial
    text: Uploaded files (e.g. bank statements) to provide our conversion services
  - category: device
    text: Technical data (e.g. IP address, browser type, usage patterns) for improving the Service
  - category: behavioral
    text: 'Ratings and feedback you choose to give: a 1–5 star rating of a conversion or of the Service'
  deletion:
    route: Contact us or delete document/account in service
    text: you can delete a document, or your whole account, at any time (see Your Choices below)
  dpa:
    available: true
    text: If you are processing personal data on behalf of your organization and require a Data Processing Agreement (DPA), please contact us to request one.
    url: null
  purposes:
  - purpose: Process and convert files
    text: To process and convert uploaded files into structured data formats
  - purpose: Improve parsing accuracy
    text: To improve parsing accuracy and extraction quality across statements
  - purpose: Customer support and billing
    text: To provide customer support and billing
  - purpose: Debugging and reliability
    text: To debug issues and ensure Service reliability
  retention:
  - period: 24 hours
    scope: No account or free plan
    text: 'No account, or free plan: files and results are deleted automatically once they are 24 hours old'
  - period: up to 90 days
    scope: Backups
    text: 'Backups: deleted data can remain in our database backups for up to 90 days before they expire'
  - period: null
    scope: Ratings, feedback and transfer decisions
    text: 'Ratings, feedback and transfer decisions: we keep them to improve the Service; ask us and we''ll delete them'
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Rectify
    text: Rectify inaccurate or incomplete data
  - right: Erase
    text: Erase your data ("right to be forgotten")
  - right: Restrict or object
    text: Restrict or object to processing
  - right: Data portability
    text: Data portability — receive your data in a structured, machine-readable format
  role:
    text: This Privacy Policy explains how Uncommon Goods Lab Pte. Ltd. ("we", "us", or "our") collects, uses, and protects information when you use Bankstatemently
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: 'Third-party service providers: We use third-party service providers to operate and improve the Service:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bankstatemently
provenance_date: '2026-11-09'
provider_name: Bankstatemently
provider_slug: bankstatemently-com
slug: bankstatemently-com-privacy-policy
source_date: '2026-11-09'
source_filename: bankstatemently-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bankstatemently.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bankstatemently\naid: bankstatemently-com\nurl: https://bankstatemently.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy explains how Uncommon Goods Lab Pte. Ltd. (\"we\", \"us\", or \"our\") collects, uses, and\n    protects information when you use Bankstatemently\ndata_categories:\n- category: identifying\n  text: Basic account details (e.g. name, email, payment info) when you sign up\n- category: financial\n  text: Uploaded files (e.g. bank statements) to provide our conversion services\n- category: device\n  text: Technical data (e.g. IP address, browser\
  \ type, usage patterns) for improving the Service\n- category: behavioral\n  text: 'Ratings and feedback you choose to give: a 1–5 star rating of a conversion or of the Service'\npurposes:\n- purpose: Process and convert files\n  text: To process and convert uploaded files into structured data formats\n- purpose: Improve parsing accuracy\n  text: To improve parsing accuracy and extraction quality across statements\n- purpose: Customer support and billing\n  text: To provide customer support and billing\n- purpose: Debugging and reliability\n  text: To debug issues and ensure Service reliability\nretention:\n- scope: No account or free plan\n  period: 24 hours\n  text: 'No account, or free plan: files and results are deleted automatically once they are 24 hours old'\n- scope: Backups\n  period: up to 90 days\n  text: 'Backups: deleted data can remain in our database backups for up to 90 days before they expire'\n- scope: Ratings, feedback and transfer decisions\n  period: null\n  text:\
  \ 'Ratings, feedback and transfer decisions: we keep them to improve the Service; ask us and we''ll delete\n    them'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Third-party service providers: We use third-party service providers to operate and improve the Service:'\ndpa:\n  available: true\n  url: null\n  text: If you are processing personal data on behalf of your organization and require a Data Processing Agreement\n    (DPA), please contact us to request one.\ndeletion:\n  route: Contact us or delete document/account in service\n  text: you can delete a document, or your whole account, at any time (see Your Choices below)\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Rectify\n  text: Rectify inaccurate or incomplete data\n- right: Erase\n  text: Erase your data (\"right to be forgotten\")\n- right: Restrict or object\n  text: Restrict or object to processing\n- right: Data portability\n  text: Data portability — receive\
  \ your data in a structured, machine-readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/bankstatemently-com/privacy/bankstatemently-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Bankstatemently's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banking
- Data Conversion
- Software-as-a-Service
---
