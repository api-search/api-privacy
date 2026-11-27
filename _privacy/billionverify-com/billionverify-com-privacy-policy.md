---
api_specs:
- filename: billionverify-com-account-api-openapi.yml
  format: yaml
  label: BillionVerify Account API
  slug: billionverify-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-account-api-openapi.yml
- filename: billionverify-com-file-processing-api-openapi.yml
  format: yaml
  label: BillionVerify File Processing API
  slug: billionverify-com-file-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-file-processing-api-openapi.yml
- filename: billionverify-com-health-api-openapi.yml
  format: yaml
  label: BillionVerify Health API
  slug: billionverify-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-health-api-openapi.yml
- filename: billionverify-com-verification-api-openapi.yml
  format: yaml
  label: BillionVerify Verification API
  slug: billionverify-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-verification-api-openapi.yml
- filename: billionverify-com-webhooks-api-openapi.yml
  format: yaml
  label: BillionVerify Webhooks API
  slug: billionverify-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, company name, and account identifiers.
  - category: financial
    text: we may receive transaction metadata such as card brand, last four digits, country, billing name, payment status
  - category: device
    text: IP address, browser type, device data, operating system, approximate geolocation, and language preferences.
  - category: behavioral
    text: Usage events, page visits, API request logs, timestamps, credits consumed, session logs, and similar operational data.
  deletion:
    route: email to support
    text: To exercise privacy rights, email support@billionverify.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, secure, maintain, and improve the Service
    text: Provide, secure, maintain, and improve the Service.
  - purpose: Payments, fraud and disputes
    text: Process payments, detect fraud, investigate disputes, and respond to chargebacks or abuse.
  - purpose: Account and support communications
    text: Communicate with you about account activity, billing, support, product changes, and security matters.
  retention:
  - period: 1 day
    scope: Uploaded source or original files
    text: Uploaded source or original files are available for self-service download for 1 day.
  - period: null
    scope: Account and billing records
    text: Account and billing records may be retained while your account is active and for additional periods after closure.
  - period: null
    scope: Shopify app store and customer records
    text: For the Shopify app, store and customer records held by the app, and the verification records the app created for the store's customers, are deleted when Shopify sends the corresponding redaction request.
  rights:
  - right: access, correct, delete, restrict, object, export
    text: Depending on where you live, you may have rights to access, correct, delete, restrict, object to, or export certain personal data, and to withdraw consent for optional processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where required, we rely on recognized transfer mechanisms such as contractual safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BillionVerify
provenance_date: '2026-11-09'
provider_name: BillionVerify
provider_slug: billionverify-com
slug: billionverify-com-privacy-policy
source_date: '2026-11-09'
source_filename: billionverify-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://billionverify.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BillionVerify\naid: billionverify-com\nurl: https://billionverify.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, company name, and account identifiers.\n- category: financial\n  text: we may receive transaction metadata such as card brand, last four digits, country, billing name, payment\n    status\n- category: device\n  text: IP address, browser type, device data, operating system, approximate geolocation, and language preferences.\n- category: behavioral\n  text: Usage events, page visits, API request\
  \ logs, timestamps, credits consumed, session logs, and similar operational\n    data.\npurposes:\n- purpose: Provide, secure, maintain, and improve the Service\n  text: Provide, secure, maintain, and improve the Service.\n- purpose: Payments, fraud and disputes\n  text: Process payments, detect fraud, investigate disputes, and respond to chargebacks or abuse.\n- purpose: Account and support communications\n  text: Communicate with you about account activity, billing, support, product changes, and security matters.\nretention:\n- scope: Uploaded source or original files\n  period: 1 day\n  text: Uploaded source or original files are available for self-service download for 1 day.\n- scope: Account and billing records\n  period: null\n  text: Account and billing records may be retained while your account is active and for additional periods after\n    closure.\n- scope: Shopify app store and customer records\n  period: null\n  text: For the Shopify app, store and customer records held by\
  \ the app, and the verification records the app created\n    for the store's customers, are deleted when Shopify sends the corresponding redaction request.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where required, we rely on recognized transfer mechanisms such as contractual safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to support\n  text: To exercise privacy rights, email support@billionverify.com .\nrights:\n- right: access, correct, delete, restrict, object, export\n  text: Depending on where you live, you may have rights to access, correct, delete, restrict, object to, or export\n    certain personal data, and to withdraw consent for optional processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/billionverify-com/privacy/billionverify-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from BillionVerify's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Software-as-a-Service
- Data Quality
- B2B
---
