---
api_specs:
- filename: bitly-bsds-api-openapi.yml
  format: yaml
  label: Bitly BSDs API
  slug: bitly-bsds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-bsds-api-openapi.yml
- filename: bitly-bitlinks-api-openapi.yml
  format: yaml
  label: Bitly Bitlinks API
  slug: bitly-bitlinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-bitlinks-api-openapi.yml
- filename: bitly-campaigns-api-openapi.yml
  format: yaml
  label: Bitly Campaigns API
  slug: bitly-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-campaigns-api-openapi.yml
- filename: bitly-custom-bitlinks-api-openapi.yml
  format: yaml
  label: Bitly Custom Bitlinks API
  slug: bitly-custom-bitlinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-custom-bitlinks-api-openapi.yml
- filename: bitly-groups-api-openapi.yml
  format: yaml
  label: Bitly Groups API
  slug: bitly-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-groups-api-openapi.yml
- filename: bitly-organizations-api-openapi.yml
  format: yaml
  label: Bitly Organizations API
  slug: bitly-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-organizations-api-openapi.yml
- filename: bitly-qr-codes-api-openapi.yml
  format: yaml
  label: Bitly QR Codes API
  slug: bitly-qr-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-qr-codes-api-openapi.yml
- filename: bitly-user-api-openapi.yml
  format: yaml
  label: Bitly User API
  slug: bitly-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-user-api-openapi.yml
- filename: bitly-webhooks-api-openapi.yml
  format: yaml
  label: Bitly Webhooks API
  slug: bitly-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-webhooks-api-openapi.yml
- filename: bitly-apps-api-openapi.yml
  format: yaml
  label: Bitly Apps API
  slug: bitly-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitly/openapi/bitly-apps-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, phone number, company name, industry, job title, company size, email address and sign-in information
  - category: location
    text: your geolocation data (which we derive from your IP address)
  - category: device
    text: device settings, such as browser type, operating system, and language
  - category: behavioral
    text: internet or other electronic network activity information like the referring websites or services
  - category: communication
    text: Communications with the customer, IP address, Social media profile information, interactions, contents and other user generated information
  deletion:
    route: Account settings or email to privacy@bit.ly
    text: You can delete your Account at any time through your Account settings page.
  dpa:
    available: null
    text: Bitly Inc. and Bitly Europe GmbH have concluded a joint controller agreement in accordance with the GDPR
    url: null
  purposes:
  - purpose: Customer support and communications
    text: We process your data to provide customer support, customer communications, to optimize and improve our service and the user experience, and to process and manage payments
  - purpose: Marketing
    text: The personal data above is used to generate leads, target marketing activities to the contacts representing potential and current customers
  - purpose: Security and fraud prevention
    text: detect, deter and prevent malicious, fraudulent or unlawful activity
  retention:
  - period: three (3) years
    scope: Subscription, product usage and similar data
    text: Subscription data, product usage data and similar data based on actions of the users is anonymized or erased after three (3) years have passed from the account deactivation or last contact.
  - period: up to 12 months
    scope: Tracking pixel data
    text: The tracking pixel data is stored on the users’ device for up to 12 months.
  rights:
  - right: Access
    text: access to a copy of such personal data (Art. 15 GDPR)
  - right: Correction
    text: If the personal data that is being processed is incorrect or inaccurate, you are entitled to demand for the data to be corrected (Art. 16 GDPR).
  - right: Deletion, restriction and objection
    text: you may demand for the deletion or limitation of the processing and have the right to object to the processing altogether (Art. 17, 18, and 21 GDPR).
  - right: Data portability
    text: you may be entitled to data transferability (Article 20 GDPR)
  - right: Withdraw consent
    text: you may revoke your consent at any time.
  role:
    text: for which either of us act as the data controller, or for which we act as joint controllers
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: To protect your personal data, we have concluded so-called standard contractual clauses (“SCCs”).
  - mechanism: adequacy
    text: Where applicable, we base data transfers also on adequacy decisions issued by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bitly
provenance_date: '2026-11-09'
provider_name: Bitly
provider_slug: bitly
slug: bitly-privacy-policy
source_date: '2026-11-09'
source_filename: bitly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bitly.com/pages/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bitly\naid: bitly\nurl: https://bitly.com/pages/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: for which either of us act as the data controller, or for which we act as joint controllers\ndata_categories:\n- category: identifying\n  text: your name, phone number, company name, industry, job title, company size, email address and sign-in information\n- category: location\n  text: your geolocation data (which we derive from your IP address)\n- category: device\n  text: device settings, such as browser type, operating system, and language\n- category: behavioral\n  text:\
  \ internet or other electronic network activity information like the referring websites or services\n- category: communication\n  text: Communications with the customer, IP address, Social media profile information, interactions, contents and\n    other user generated information\npurposes:\n- purpose: Customer support and communications\n  text: We process your data to provide customer support, customer communications, to optimize and improve our service\n    and the user experience, and to process and manage payments\n- purpose: Marketing\n  text: The personal data above is used to generate leads, target marketing activities to the contacts representing\n    potential and current customers\n- purpose: Security and fraud prevention\n  text: detect, deter and prevent malicious, fraudulent or unlawful activity\nretention:\n- scope: Subscription, product usage and similar data\n  period: three (3) years\n  text: Subscription data, product usage data and similar data based on actions of the\
  \ users is anonymized or erased\n    after three (3) years have passed from the account deactivation or last contact.\n- scope: Tracking pixel data\n  period: up to 12 months\n  text: The tracking pixel data is stored on the users’ device for up to 12 months.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: To protect your personal data, we have concluded so-called standard contractual clauses (“SCCs”).\n- mechanism: adequacy\n  text: Where applicable, we base data transfers also on adequacy decisions issued by the European Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Bitly Inc. and Bitly Europe GmbH have concluded a joint controller agreement in accordance with the GDPR\ndeletion:\n  route: Account settings or email to privacy@bit.ly\n  text: You can delete your Account at any time through your Account settings page.\nrights:\n- right: Access\n  text: access to a copy of such personal data (Art. 15 GDPR)\n- right: Correction\n\
  \  text: If the personal data that is being processed is incorrect or inaccurate, you are entitled to demand for\n    the data to be corrected (Art. 16 GDPR).\n- right: Deletion, restriction and objection\n  text: you may demand for the deletion or limitation of the processing and have the right to object to the processing\n    altogether (Art. 17, 18, and 21 GDPR).\n- right: Data portability\n  text: you may be entitled to data transferability (Article 20 GDPR)\n- right: Withdraw consent\n  text: you may revoke your consent at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bitly/privacy/bitly-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 20 quoted statements, read from Bitly's own page on 2026-11-09.
synthetic: false
tags:
- Links
- URL Shorteners
- QR Codes
- Analytics
- Marketing
- Link Management
- Webhook
- Attribution
- Agents
- MCP
---
