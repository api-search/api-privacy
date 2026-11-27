---
api_specs:
- filename: justt-chargebacks-api-openapi.yml
  format: yaml
  label: Justt Chargebacks API
  slug: justt-chargebacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-chargebacks-api-openapi.yml
- filename: justt-data-subjects-api-openapi.yml
  format: yaml
  label: Justt Data Subjects API
  slug: justt-data-subjects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-data-subjects-api-openapi.yml
- filename: justt-evidence-api-openapi.yml
  format: yaml
  label: Justt Evidence API
  slug: justt-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-evidence-api-openapi.yml
- filename: justt-files-api-openapi.yml
  format: yaml
  label: Justt Files API
  slug: justt-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-files-api-openapi.yml
- filename: justt-integrations-api-openapi.yml
  format: yaml
  label: Justt Integrations API
  slug: justt-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-integrations-api-openapi.yml
- filename: justt-merchants-api-openapi.yml
  format: yaml
  label: Justt Merchants API
  slug: justt-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-merchants-api-openapi.yml
- filename: justt-pre-chargeback-alerts-api-openapi.yml
  format: yaml
  label: Justt Pre-chargeback Alerts API
  slug: justt-pre-chargeback-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-pre-chargeback-alerts-api-openapi.yml
- filename: justt-sandbox-api-openapi.yml
  format: yaml
  label: Justt Sandbox API
  slug: justt-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-sandbox-api-openapi.yml
- filename: justt-transactions-api-openapi.yml
  format: yaml
  label: Justt Transactions API
  slug: justt-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-transactions-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Full name, email address, phone number and Merchant category code.
  - category: financial
    text: transaction invoices, evidence related to orders/ transactions and cancellations, customer service record, details about customer’s account/profile in your records, online access/download history, billing and shipping address and IP address.
  - category: location
    text: geolocation data (including country and city)
  - category: device
    text: device identifiers, internet service provider, connection speed, search history, type of browser
  - category: behavioral
    text: how you move around different sections of our Services for analytics purposes
  - category: communication
    text: When you send emails or other communications to the Company, we retain those communications
  deletion:
    route: email privacy@justt.ai
    text: 'If you wish to delete all information regarding your use of the Services, please contact us at: privacy@justt.ai'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve Services
    text: We use PII to provide and improve our Services, and to meet our contractual, ethical and legal obligations.
  - purpose: chargeback responses and investigation
    text: for example in submission of chargeback responses or investigation of information related to a chargeback
  - purpose: analytics
    text: The Company uses all of the PII identified in this Section in order to understand the usage trends and preferences of our users
  retention:
  - period: seven years
    scope: customers and business partners
    text: PII associated with our customers and business partners, will be retained for the duration of our engagement, and a period of seven years thereafter.
  - period: indefinitely
    scope: non-personal and statistical information
    text: Non-personal, non-identifiable, metadata and statistical information concerning the use of our Services are retained by Company indefinitely.
  rights:
  - right: access and rectification
    text: We allow data subjects the option to access and obtain a copy of their PII and to rectify such PII if it is not accurate, complete or updated.
  - right: delete or restrict processing
    text: Data subjects have the right to delete their PII or restrict its processing.
  - right: withdraw consent
    text: Data subjects have the right to withdraw their consent to the processing of their PII.
  - right: data portability
    text: Where technically feasible, data subjects have the right to ask to transfer their PII in accordance with their right to data portability, if required pursuant to applicable law.
  - right: lodge complaint
    text: Data subjects also have the right to lodge a complaint with a data protection supervisory authority regarding the processing of their PII.
  role:
    text: Company is a controller of the PII it processes in relation to its customers, vendors, service providers or partners. When Company processes PII on behalf of its customers (e.g. for chargeback responses), Company is a data processor under the GDPR, to the extent applicable.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: seek to rely on appropriate safeguards such as entering into appropriate EC approved standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Justt
provenance_date: '2026-11-09'
provider_name: Justt
provider_slug: justt
slug: justt-privacy-policy
source_date: '2026-11-09'
source_filename: justt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://justt.ai/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Justt\naid: justt\nurl: https://justt.ai/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Company is a controller of the PII it processes in relation to its customers, vendors, service providers\n    or partners. When Company processes PII on behalf of its customers (e.g. for chargeback responses), Company\n    is a data processor under the GDPR, to the extent applicable.\ndata_categories:\n- category: contact\n  text: Full name, email address, phone number and Merchant category code.\n- category: financial\n  text: transaction invoices, evidence related to orders/ transactions and\
  \ cancellations, customer service record,\n    details about customer’s account/profile in your records, online access/download history, billing and shipping\n    address and IP address.\n- category: location\n  text: geolocation data (including country and city)\n- category: device\n  text: device identifiers, internet service provider, connection speed, search history, type of browser\n- category: behavioral\n  text: how you move around different sections of our Services for analytics purposes\n- category: communication\n  text: When you send emails or other communications to the Company, we retain those communications\npurposes:\n- purpose: provide and improve Services\n  text: We use PII to provide and improve our Services, and to meet our contractual, ethical and legal obligations.\n- purpose: chargeback responses and investigation\n  text: for example in submission of chargeback responses or investigation of information related to a chargeback\n- purpose: analytics\n  text: The Company\
  \ uses all of the PII identified in this Section in order to understand the usage trends and preferences\n    of our users\nretention:\n- scope: customers and business partners\n  period: seven years\n  text: PII associated with our customers and business partners, will be retained for the duration of our engagement,\n    and a period of seven years thereafter.\n- scope: non-personal and statistical information\n  period: indefinitely\n  text: Non-personal, non-identifiable, metadata and statistical information concerning the use of our Services\n    are retained by Company indefinitely.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: seek to rely on appropriate safeguards such as entering into appropriate EC approved standard contractual\n    clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@justt.ai\n  text: 'If you wish to delete all information regarding your use of the Services, please contact\
  \ us at: privacy@justt.ai'\nrights:\n- right: access and rectification\n  text: We allow data subjects the option to access and obtain a copy of their PII and to rectify such PII if it\n    is not accurate, complete or updated.\n- right: delete or restrict processing\n  text: Data subjects have the right to delete their PII or restrict its processing.\n- right: withdraw consent\n  text: Data subjects have the right to withdraw their consent to the processing of their PII.\n- right: data portability\n  text: Where technically feasible, data subjects have the right to ask to transfer their PII in accordance with\n    their right to data portability, if required pursuant to applicable law.\n- right: lodge complaint\n  text: Data subjects also have the right to lodge a complaint with a data protection supervisory authority regarding\n    the processing of their PII.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/justt/privacy/justt-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 19 quoted statements, read from Justt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Chargebacks
- Disputes
- Fraud Prevention
- Risk Management
- Financial Services
- E-Commerce
- Artificial Intelligence
- Webhook
---
