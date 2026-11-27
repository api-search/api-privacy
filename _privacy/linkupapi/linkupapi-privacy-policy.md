---
api_specs:
- filename: linkupapi-openapi-generated.yml
  format: yaml
  label: LinkupAPI API
  slug: linkupapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkupapi/openapi/_ae-authored/linkupapi-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, password (stored hashed), company information.
  - category: financial
    text: Billing details and payment history.
  - category: device
    text: API request logs (endpoint called, timestamps, status, credits consumed, IP address, user agent).
  - category: communication
    text: 'Message data: the content of messages sent through the API, and messages read from the connected inbox'
  deletion:
    route: Delete account from the dashboard or by writing to privacy@linkupapi.com
    text: delete your LinkupAPI account from the dashboard or by writing to privacy@linkupapi.com, which deletes the personal data associated with the account except where retention is legally required. Deletion requests are honored within 30 days.
  dpa:
    available: null
    text: 'We share personal data only with processors that help us run the service, under data processing agreements:'
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: provide, operate, and secure the LinkupAPI service;
  - purpose: Authenticate to third-party providers
    text: authenticate to third-party providers on the connected account's behalf and perform the actions our customer requests through the API;
  - purpose: Billing and fraud prevention
    text: meter usage, bill our customers, and prevent fraud and abuse;
  - purpose: Customer support
    text: provide customer support;
  residency:
  - region: European Union
    text: Our infrastructure is hosted in the European Union.
  retention:
  - period: up to 10 years for invoices
    scope: Account and billing data
    text: for the life of the customer account, then as required by French accounting and tax law (up to 10 years for invoices).
  - period: up to 12 months
    scope: API logs
    text: 'API logs: up to 12 months, then deleted or anonymized.'
  - period: until the connection is removed by the user or customer, the account is deleted, or the token is revoked or expires
    scope: Connected account tokens and credentials
    text: 'Connected account tokens and credentials: until the connection is removed by the user or customer, the account is deleted, or the token is revoked or expires.'
  rights:
  - right: access, rectify, erase
    text: you have the right to access, rectify, and erase your personal data, restrict or object to its processing, receive it in a portable format, and withdraw consent at any time
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with the French supervisory authority (CNIL, www.cnil.fr) or your local authority.
  role:
    text: LINKUPAPI SAS is the data controller for the personal data described in this policy.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do NOT sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where a processor is located outside the European Economic Area, we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LinkupAPI
provenance_date: '2026-11-09'
provider_name: LinkupAPI
provider_slug: linkupapi
slug: linkupapi-privacy-policy
source_date: '2026-11-09'
source_filename: linkupapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://linkupapi.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LinkupAPI\naid: linkupapi\nurl: https://linkupapi.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: LINKUPAPI SAS is the data controller for the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: Name, email address, password (stored hashed), company information.\n- category: financial\n  text: Billing details and payment history.\n- category: device\n  text: API request logs (endpoint called, timestamps, status, credits consumed, IP address, user agent).\n- category: communication\n  text: 'Message data: the content of messages sent\
  \ through the API, and messages read from the connected inbox'\npurposes:\n- purpose: Provide and operate the service\n  text: provide, operate, and secure the LinkupAPI service;\n- purpose: Authenticate to third-party providers\n  text: authenticate to third-party providers on the connected account's behalf and perform the actions our customer\n    requests through the API;\n- purpose: Billing and fraud prevention\n  text: meter usage, bill our customers, and prevent fraud and abuse;\n- purpose: Customer support\n  text: provide customer support;\nretention:\n- scope: Account and billing data\n  period: up to 10 years for invoices\n  text: for the life of the customer account, then as required by French accounting and tax law (up to 10 years\n    for invoices).\n- scope: API logs\n  period: up to 12 months\n  text: 'API logs: up to 12 months, then deleted or anonymized.'\n- scope: Connected account tokens and credentials\n  period: until the connection is removed by the user or customer,\
  \ the account is deleted, or the token is revoked\n    or expires\n  text: 'Connected account tokens and credentials: until the connection is removed by the user or customer, the\n    account is deleted, or the token is revoked or expires.'\nresidency:\n- region: European Union\n  text: Our infrastructure is hosted in the European Union.\ntransfers:\n- mechanism: SCC\n  text: Where a processor is located outside the European Economic Area, we rely on appropriate safeguards such\n    as the European Commission's Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: 'We share personal data only with processors that help us run the service, under data processing agreements:'\ndeletion:\n  route: Delete account from the dashboard or by writing to privacy@linkupapi.com\n  text: delete your LinkupAPI account from the dashboard or by writing to privacy@linkupapi.com, which deletes the\n    personal data associated with the account\
  \ except where retention is legally required. Deletion requests are\n    honored within 30 days.\nrights:\n- right: access, rectify, erase\n  text: you have the right to access, rectify, and erase your personal data, restrict or object to its processing,\n    receive it in a portable format, and withdraw consent at any time\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with the French supervisory authority (CNIL, www.cnil.fr) or\n    your local authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do NOT sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/linkupapi/privacy/linkupapi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from LinkupAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Outreach
- Artificial Intelligence
- Automation
---
