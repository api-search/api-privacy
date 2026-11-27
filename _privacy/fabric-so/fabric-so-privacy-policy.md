---
api_specs:
- filename: fabric-so-openapi-generated.yml
  format: yaml
  label: Fabric API
  slug: fabric-so-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabric-so/openapi/_ae-authored/fabric-so-openapi-generated.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up for Fabric, we typically ask for identifying information such as your name and email address.
  - category: financial
    text: We store a record of the payment transaction, including the last 4 digits of the credit card number and your as-of billing address
  - category: device
    text: your browser automatically shares certain information such as which operating system and browser version you are using.
  - category: behavioral
    text: along with the pages you are visiting, page load timing, and which website referred you, for statistical purposes like conversion rates, and to test new designs.
  deletion:
    route: delete account or data in account
    text: At any point, you can delete your account and/or the data within it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account personalization and invoices
    text: We access your name and email so we can personalize your new account and send you invoices, updates or other essential information.
  - purpose: charging and tax
    text: That's so we can charge you for our service, calculate taxes due and send you invoices.
  - purpose: fraud detection
    text: to detect fraudulent credit card transactions
  - purpose: product improvement
    text: We may use anonymized, aggregated data to improve our services.
  retention:
  - period: 30 days
    scope: deleted account data
    text: Upon deletion, it will be purged from our systems within 30 days, after which point it will be entirely unrecoverable.
  rights:
  - right: data export
    text: at any point, you can export all the data held in your Fabric account, and will automatically receive it as a .ZIP file.
  - right: opt out of anonymized data use
    text: You can opt out at any time in your settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We’ll never sell your personal info to third parties
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fabric
provenance_date: '2026-11-09'
provider_name: Fabric
provider_slug: fabric-so
slug: fabric-so-privacy-policy
source_date: '2026-11-09'
source_filename: fabric-so-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fabric.so/info/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fabric\naid: fabric-so\nurl: https://fabric.so/info/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up for Fabric, we typically ask for identifying information such as your name and email address.\n- category: financial\n  text: We store a record of the payment transaction, including the last 4 digits of the credit card number and\n    your as-of billing address\n- category: device\n  text: your browser automatically shares certain information such as which operating system and browser version\n    you are using.\n\
  - category: behavioral\n  text: along with the pages you are visiting, page load timing, and which website referred you, for statistical\n    purposes like conversion rates, and to test new designs.\npurposes:\n- purpose: account personalization and invoices\n  text: We access your name and email so we can personalize your new account and send you invoices, updates or other\n    essential information.\n- purpose: charging and tax\n  text: That's so we can charge you for our service, calculate taxes due and send you invoices.\n- purpose: fraud detection\n  text: to detect fraudulent credit card transactions\n- purpose: product improvement\n  text: We may use anonymized, aggregated data to improve our services.\nretention:\n- scope: deleted account data\n  period: 30 days\n  text: Upon deletion, it will be purged from our systems within 30 days, after which point it will be entirely\n    unrecoverable.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: delete account or data in account\n  text: At any point, you can delete your account and/or the data within it.\nrights:\n- right: data export\n  text: at any point, you can export all the data held in your Fabric account, and will automatically receive it\n    as a .ZIP file.\n- right: opt out of anonymized data use\n  text: You can opt out at any time in your settings.\nsale_or_sharing:\n  stance: prohibited\n  text: We’ll never sell your personal info to third parties\n"
source_yaml_url: https://artifacts.apis.io/fabric-so/privacy/fabric-so-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Fabric's own page on 2026-11-09.
synthetic: false
tags:
- AI Workspace
- File Storage
- Integration
---
