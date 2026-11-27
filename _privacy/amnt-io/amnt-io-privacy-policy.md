---
api_specs:
- filename: amnt-io-account-api-openapi.yml
  format: yaml
  label: AMNT Account API
  slug: amnt-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-account-api-openapi.yml
- filename: amnt-io-agents-api-openapi.yml
  format: yaml
  label: AMNT Agents API
  slug: amnt-io-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-agents-api-openapi.yml
- filename: amnt-io-runs-api-openapi.yml
  format: yaml
  label: AMNT Runs API
  slug: amnt-io-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-runs-api-openapi.yml
- filename: amnt-io-svg-api-openapi.yml
  format: yaml
  label: AMNT SVG API
  slug: amnt-io-svg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amnt-io/openapi/amnt-io-svg-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details , such as your email address and sign-in details
  - category: contact
    text: Communications , such as the messages and feedback you send us.
  - category: financial
    text: Payment information , such as your billing details and purchase history.
  - category: behavioral
    text: Device and usage information , such as your IP address, browser and device type, the pages you view, the features you use
  - category: device
    text: the dates and times of your visits, and error reports.
  - category: other
    text: Content , such as the text, prompts, images and files you submit, and what you create with the Services.
  deletion:
    route: email support@amnt.io
    text: To use any of these rights, email support@amnt.io.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Services
    text: to create and manage your account, carry out your requests, deliver what you create and give you support
  - purpose: take payments
    text: to bill you, process payments and keep financial records
  - purpose: keep the Services safe
    text: to prevent fraud, abuse and security incidents, and to enforce our Terms
  - purpose: improve the Services
    text: including improving our models with content created on the Services (our legitimate interests)
  - purpose: analytics
    text: To measure use with analytics cookies (your consent).
  retention:
  - period: null
    scope: account information and content
    text: Account information and content is kept while your account is open, then deleted or anonymised within a reasonable period, unless you delete it sooner.
  - period: up to six years
    scope: payment and transaction records
    text: Payment and transaction records are kept for up to six years after the transaction, to meet tax and accounting rules.
  - period: null
    scope: device and usage information
    text: Device and usage information is kept for a limited period, then deleted or combined so that it no longer identifies you.
  rights:
  - right: access
    text: access the personal information we hold about you
  - right: correction
    text: have inaccurate information corrected
  - right: deletion
    text: have your information deleted
  - right: restrict or object
    text: restrict or object to our use of your information, including for direct marketing
  - right: portability
    text: receive your information in a portable format
  - right: withdraw consent
    text: withdraw your consent at any time, where we rely on it
  role:
    text: AMNT.IO LTD is the controller of your personal information under UK data protection law, including the UK GDPR.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not share it with advertisers.
  subprocessors:
    text: Our main service providers are Amazon Web Services, Amazon Cognito, Resend, Stripe, OpenAI, Azure OpenAI, Anthropic, Replicate, Fal, OpenSea, SentX and Pinata.
    url: null
  transfers:
  - mechanism: adequacy
    text: relying on UK adequacy regulations
  - mechanism: other
    text: using the UK International Data Transfer Agreement or the UK Addendum to the EU Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AMNT
provenance_date: '2026-11-09'
provider_name: AMNT
provider_slug: amnt-io
slug: amnt-io-privacy-policy
source_date: '2026-11-09'
source_filename: amnt-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://amnt.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AMNT\naid: amnt-io\nurl: https://amnt.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AMNT.IO LTD is the controller of your personal information under UK data protection law, including the UK\n    GDPR.\ndata_categories:\n- category: identifying\n  text: Account details , such as your email address and sign-in details\n- category: contact\n  text: Communications , such as the messages and feedback you send us.\n- category: financial\n  text: Payment information , such as your billing details and purchase history.\n- category: behavioral\n  text: Device and usage information , such\
  \ as your IP address, browser and device type, the pages you view, the\n    features you use\n- category: device\n  text: the dates and times of your visits, and error reports.\n- category: other\n  text: Content , such as the text, prompts, images and files you submit, and what you create with the Services.\npurposes:\n- purpose: provide the Services\n  text: to create and manage your account, carry out your requests, deliver what you create and give you support\n- purpose: take payments\n  text: to bill you, process payments and keep financial records\n- purpose: keep the Services safe\n  text: to prevent fraud, abuse and security incidents, and to enforce our Terms\n- purpose: improve the Services\n  text: including improving our models with content created on the Services (our legitimate interests)\n- purpose: analytics\n  text: To measure use with analytics cookies (your consent).\nretention:\n- scope: account information and content\n  period: null\n  text: Account information and\
  \ content is kept while your account is open, then deleted or anonymised within a\n    reasonable period, unless you delete it sooner.\n- scope: payment and transaction records\n  period: up to six years\n  text: Payment and transaction records are kept for up to six years after the transaction, to meet tax and accounting\n    rules.\n- scope: device and usage information\n  period: null\n  text: Device and usage information is kept for a limited period, then deleted or combined so that it no longer\n    identifies you.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: relying on UK adequacy regulations\n- mechanism: other\n  text: using the UK International Data Transfer Agreement or the UK Addendum to the EU Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: Our main service providers are Amazon Web Services, Amazon Cognito, Resend, Stripe, OpenAI, Azure OpenAI,\n    Anthropic, Replicate, Fal, OpenSea, SentX and Pinata.\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: email support@amnt.io\n  text: To use any of these rights, email support@amnt.io.\nrights:\n- right: access\n  text: access the personal information we hold about you\n- right: correction\n  text: have inaccurate information corrected\n- right: deletion\n  text: have your information deleted\n- right: restrict or object\n  text: restrict or object to our use of your information, including for direct marketing\n- right: portability\n  text: receive your information in a portable format\n- right: withdraw consent\n  text: withdraw your consent at any time, where we rely on it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/amnt-io/privacy/amnt-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from AMNT's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Tools
- Creators
- Developers
- Agents
---
