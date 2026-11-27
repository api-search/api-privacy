---
api_specs:
- filename: parseforme-webhooks-api-openapi.yml
  format: yaml
  label: ParseForMe Webhooks API
  slug: parseforme-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-webhooks-api-openapi.yml
- filename: parseforme-document-types-api-openapi.yml
  format: yaml
  label: ParseForMe Document Types API
  slug: parseforme-document-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-document-types-api-openapi.yml
- filename: parseforme-documents-api-openapi.yml
  format: yaml
  label: ParseForMe Documents API
  slug: parseforme-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-documents-api-openapi.yml
- filename: parseforme-me-api-openapi.yml
  format: yaml
  label: ParseForMe Me API
  slug: parseforme-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-me-api-openapi.yml
- filename: parseforme-meta-api-openapi.yml
  format: yaml
  label: ParseForMe Meta API
  slug: parseforme-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseforme/openapi/parseforme-meta-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your name and email address from the sign-in provider you choose, and the workspace you create.'
  - category: contact
    text: 'Account data: your name and email address from the sign-in provider you choose'
  - category: financial
    text: the record of your token purchases (payment card details are handled by Paddle, not by us)
  - category: location
    text: an approximate location (country, region and city) derived from your IP address
  - category: behavioral
    text: we record page views and similar interactions in our own first-party analytics
  - category: device
    text: your device type, referrer, any campaign parameters in the link you followed
  - category: other
    text: 'Documents and extracted data: the files you upload for parsing and the structured data we extract from them.'
  deletion:
    route: in-app workspace deletion or contacting us
    text: You can delete your workspace and all of its data at any time from your account, or by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service
    text: 'We use your data only to provide the Service: to parse your documents, let you review and export the result, meter and bill token usage, provide support, and keep the Service secure.'
  - purpose: website analytics and advertising measurement
    text: We use website analytics to understand how the site is used and to measure our advertising.
  - purpose: conversion measurement with consent
    text: With your consent we also share a limited set of conversion events (such as a sign-up or purchase) with Meta and Google so we can measure and improve those campaigns.
  residency:
  - region: EU
    text: The Service and your documents are hosted in the EU (Hetzner, Germany), and document parsing (Mistral) is performed in the EU.
  retention:
  - period: null
    scope: raw uploads
    text: Raw uploads are deleted immediately after a document is ingested
  - period: 90 days
    scope: extracted data and exports
    text: Extracted data and exports are kept in your workspace and are automatically deleted after 90 days.
  rights:
  - right: access, correct, delete, port
    text: If you are in the EEA or UK, you have the right to access, correct, delete, and port your personal data
  - right: object or restrict processing
    text: and to object to or restrict certain processing.
  - right: complain to data protection authority
    text: You may also complain to your local data protection authority.
  role:
    text: Because that access is by us as the controller rather than a disclosure to a separate recipient
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not use the contents of your documents to train models.
  subprocessors:
    text: Mistral AI — optical character recognition and document parsing.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ParseForMe
provenance_date: '2026-11-10'
provider_name: ParseForMe
provider_slug: parseforme
slug: parseforme-privacy-policy
source_date: '2026-11-10'
source_filename: parseforme-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://parseforme.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ParseForMe\naid: parseforme\nurl: https://parseforme.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Because that access is by us as the controller rather than a disclosure to a separate recipient\ndata_categories:\n- category: identifying\n  text: 'Account data: your name and email address from the sign-in provider you choose, and the workspace you create.'\n- category: contact\n  text: 'Account data: your name and email address from the sign-in provider you choose'\n- category: financial\n  text: the record of your token purchases (payment card details are handled by Paddle,\
  \ not by us)\n- category: location\n  text: an approximate location (country, region and city) derived from your IP address\n- category: behavioral\n  text: we record page views and similar interactions in our own first-party analytics\n- category: device\n  text: your device type, referrer, any campaign parameters in the link you followed\n- category: other\n  text: 'Documents and extracted data: the files you upload for parsing and the structured data we extract from\n    them.'\npurposes:\n- purpose: provide the Service\n  text: 'We use your data only to provide the Service: to parse your documents, let you review and export the result,\n    meter and bill token usage, provide support, and keep the Service secure.'\n- purpose: website analytics and advertising measurement\n  text: We use website analytics to understand how the site is used and to measure our advertising.\n- purpose: conversion measurement with consent\n  text: With your consent we also share a limited set of conversion\
  \ events (such as a sign-up or purchase) with\n    Meta and Google so we can measure and improve those campaigns.\nretention:\n- scope: raw uploads\n  period: null\n  text: Raw uploads are deleted immediately after a document is ingested\n- scope: extracted data and exports\n  period: 90 days\n  text: Extracted data and exports are kept in your workspace and are automatically deleted after 90 days.\nresidency:\n- region: EU\n  text: The Service and your documents are hosted in the EU (Hetzner, Germany), and document parsing (Mistral) is\n    performed in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Mistral AI — optical character recognition and document parsing.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app workspace deletion or contacting us\n  text: You can delete your workspace and all of its data at any time from your account, or by contacting us.\nrights:\n- right: access, correct, delete, port\n  text: If you are in the EEA or UK,\
  \ you have the right to access, correct, delete, and port your personal data\n- right: object or restrict processing\n  text: and to object to or restrict certain processing.\n- right: complain to data protection authority\n  text: You may also complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we do not use the contents of your documents to train models.\n"
source_yaml_url: https://artifacts.apis.io/parseforme/privacy/parseforme-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from ParseForMe's own page on 2026-11-10.
synthetic: false
tags:
- Document Parsing
- OCR
- Data Extraction
- Document AI
- Intelligent Document Processing
- Invoices
- Bank Statements
- Receipts
- Resume
- PDF
- Webhook
- REST
---
