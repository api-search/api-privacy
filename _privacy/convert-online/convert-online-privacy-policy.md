---
api_specs:
- filename: convert-online-catalogue-api-openapi.yml
  format: yaml
  label: Convert.Online Catalogue API
  slug: convert-online-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convert-online/openapi/convert-online-catalogue-api-openapi.yml
- filename: convert-online-downloads-api-openapi.yml
  format: yaml
  label: Convert.Online Downloads API
  slug: convert-online-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convert-online/openapi/convert-online-downloads-api-openapi.yml
- filename: convert-online-imports-api-openapi.yml
  format: yaml
  label: Convert.Online Imports API
  slug: convert-online-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convert-online/openapi/convert-online-imports-api-openapi.yml
- filename: convert-online-jobs-api-openapi.yml
  format: yaml
  label: Convert.Online Jobs API
  slug: convert-online-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convert-online/openapi/convert-online-jobs-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address
  - category: contact
    text: Full name Billing address Company name (if applicable) VAT ID (if applicable)
  - category: device
    text: IP address HTTP referrer Browser user agent Date and time of access
  - category: financial
    text: Payment method details (e.g., credit card number, expiration date, CVC) – processed securely by Paddle
  - category: behavioral
    text: Platform usage data (e.g., which tools were used, success/error of conversions)
  deletion:
    route: Delete account in user dashboard or contact support email
    text: You may delete your account at any time, which will also delete your files and any personal data associated with payment (as handled by Paddle).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: File conversion and platform functionality
    text: We process your data strictly to deliver the services you request — primarily converting your files to other formats.
  - purpose: Abuse detection
    text: IP addresses are logged to detect abuse (e.g. DoS attacks, bot misuse) and for general location-based analytics (not tied to your personal identity).
  - purpose: Invoicing and fraud protection
    text: When a purchase is made, your billing details are processed exclusively by Paddle, and used for invoicing, tax purposes, and fraud protection.
  residency:
  - region: European Union
    text: your files, account data and logs are processed and stored within the European Union.
  retention:
  - period: immediately after conversion
    scope: Uploaded files
    text: Uploaded files are automatically deleted immediately after conversion.
  - period: 24 hours
    scope: Converted files
    text: Converted files are automatically deleted after 24 hours .
  - period: 30 days
    scope: Log data
    text: Log data (IP address, referrer, user agent) is deleted after 30 days .
  - period: up to 10 years
    scope: Payment data
    text: payment data may be retained for up to 10 years.
  rights:
  - right: Access
    text: Right of access (Art. 15 GDPR)
  - right: Rectification
    text: Right to rectification (Art. 16 GDPR)
  - right: Erasure
    text: Right to erasure (Art. 17 GDPR)
  - right: Restriction
    text: Right to restriction of processing (Art. 18 GDPR)
  - right: Portability
    text: Right to data portability (Art. 20 GDPR)
  - right: Objection
    text: Right to object (Art. 21 GDPR)
  - right: Complaint
    text: Right to lodge a complaint (Art. 77 GDPR)
  role:
    text: As the data controller, Kefalica d.o.o. determines the purposes and means of processing your personal data
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as the EU Standard Contractual Clauses pursuant to Art. 46 (2) (c) GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Convert.Online
provenance_date: '2026-11-09'
provider_name: Convert.Online
provider_slug: convert-online
slug: convert-online-privacy-policy
source_date: '2026-11-09'
source_filename: convert-online-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://convert.online/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Convert.Online\naid: convert-online\nurl: https://convert.online/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: As the data controller, Kefalica d.o.o. determines the purposes and means of processing your personal data\ndata_categories:\n- category: identifying\n  text: Your email address\n- category: contact\n  text: Full name Billing address Company name (if applicable) VAT ID (if applicable)\n- category: device\n  text: IP address HTTP referrer Browser user agent Date and time of access\n- category: financial\n  text: Payment method details (e.g., credit card number, expiration\
  \ date, CVC) – processed securely by Paddle\n- category: behavioral\n  text: Platform usage data (e.g., which tools were used, success/error of conversions)\npurposes:\n- purpose: File conversion and platform functionality\n  text: We process your data strictly to deliver the services you request — primarily converting your files to other\n    formats.\n- purpose: Abuse detection\n  text: IP addresses are logged to detect abuse (e.g. DoS attacks, bot misuse) and for general location-based analytics\n    (not tied to your personal identity).\n- purpose: Invoicing and fraud protection\n  text: When a purchase is made, your billing details are processed exclusively by Paddle, and used for invoicing,\n    tax purposes, and fraud protection.\nretention:\n- scope: Uploaded files\n  period: immediately after conversion\n  text: Uploaded files are automatically deleted immediately after conversion.\n- scope: Converted files\n  period: 24 hours\n  text: Converted files are automatically deleted\
  \ after 24 hours .\n- scope: Log data\n  period: 30 days\n  text: Log data (IP address, referrer, user agent) is deleted after 30 days .\n- scope: Payment data\n  period: up to 10 years\n  text: payment data may be retained for up to 10 years.\nresidency:\n- region: European Union\n  text: your files, account data and logs are processed and stored within the European Union.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as the EU Standard Contractual Clauses pursuant to Art. 46 (2) (c)\n    GDPR.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in user dashboard or contact support email\n  text: You may delete your account at any time, which will also delete your files and any personal data associated\n    with payment (as handled by Paddle).\nrights:\n- right: Access\n  text: Right of access (Art. 15 GDPR)\n- right: Rectification\n  text: Right to rectification (Art. 16 GDPR)\n\
  - right: Erasure\n  text: Right to erasure (Art. 17 GDPR)\n- right: Restriction\n  text: Right to restriction of processing (Art. 18 GDPR)\n- right: Portability\n  text: Right to data portability (Art. 20 GDPR)\n- right: Objection\n  text: Right to object (Art. 21 GDPR)\n- right: Complaint\n  text: Right to lodge a complaint (Art. 77 GDPR)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/convert-online/privacy/convert-online-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 23 quoted statements, read from Convert.Online's own page on 2026-11-09.
synthetic: false
tags:
- Company
- File Conversion
- Document Conversion
- Image Conversion
- Video Conversion
- Audio Conversion
- OCR
- MCP
---
