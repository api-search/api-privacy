---
api_specs:
- filename: namegender-account-api-openapi.yml
  format: yaml
  label: NameGender Account API
  slug: namegender-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-account-api-openapi.yml
- filename: namegender-batches-api-openapi.yml
  format: yaml
  label: NameGender Batches API
  slug: namegender-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-batches-api-openapi.yml
- filename: namegender-gender-api-openapi.yml
  format: yaml
  label: NameGender Gender API
  slug: namegender-gender-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-gender-api-openapi.yml
- filename: namegender-webhooks-api-openapi.yml
  format: yaml
  label: NameGender Webhooks API
  slug: namegender-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: name, email address, password hash, optional company and country details, account preferences and verification status.'
  - category: identifying
    text: 'Authentication and security data: API key hashes and prefixes, permitted IP addresses or origins, session information, IP address, user agent and security events.'
  - category: financial
    text: 'Billing data: package, amount, asset, network, payment address, transaction reference, confirmation state and invoice details.'
  - category: communication
    text: 'Support and communication data: messages, attachments and information you choose to provide.'
  - category: behavioral
    text: 'Sign-up source: when you create an account, the first page you opened on the site during that visit, the domain of the website that referred you (not the full address) and any campaign tags in the link (utm_source, utm_medium, utm_campaign).'
  deletion:
    route: Request through support or dashboard
    text: You can request account or personal-data deletion through support.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Name classification and API access
    text: Provide name classification, API access, batch processing, account features and support.
  - purpose: Security and fraud prevention
    text: Authenticate requests, enforce quotas, prevent fraud and investigate misuse.
  - purpose: Billing and payments
    text: Calculate credits, confirm payments, create records and maintain transaction history.
  - purpose: Analytics
    text: Measure public website visits with Google Analytics only after you grant analytics consent.
  - purpose: Legal compliance
    text: Comply with legal obligations and establish, exercise or defend legal claims.
  retention:
  - period: 7 days
    scope: Raw small-request API logs
    text: 'Raw small-request logs: 7 days.'
  - period: 7 days after processing
    scope: Uploaded and generated batch files
    text: 'Uploaded and generated batch files: 7 days after processing.'
  - period: while the account is active and longer where accounting, fraud prevention or legal obligations require it
    scope: Account, credit, invoice and transaction records
    text: 'Account, credit, invoice and transaction records: while the account is active and longer where accounting, fraud prevention or legal obligations require it.'
  - period: up to 2 years
    scope: Google Analytics cookies
    text: Google Analytics cookies can remain for up to 2 years unless you withdraw consent or delete them sooner.
  rights:
  - right: Access, correction, deletion, restriction, objection
    text: Depending on where you live, you may have rights to access, correct, delete, restrict or object to processing, receive a portable copy, withdraw consent and complain to a supervisory authority.
  - right: Revoke API keys and remove jobs
    text: You can revoke API keys and remove uploaded jobs from the dashboard.
  - right: Block non-essential browser storage
    text: You can block non-essential browser storage, although essential login and security cookies are required for the account area.
  role:
    text: The service operator shown at the end of this page is responsible for this processing unless a separate agreement says otherwise. When a customer submits data about other people, that customer decides why the data is processed and NameGender acts as a service provider or processor for the requested operation.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Infrastructure and service providers may process data outside your country. Where required, we use recognised transfer safeguards and limit transfers to what is needed for the service.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: NameGender
provenance_date: '2026-11-10'
provider_name: NameGender
provider_slug: namegender
slug: namegender-privacy-policy
source_date: '2026-11-10'
source_filename: namegender-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://namegender.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: NameGender\naid: namegender\nurl: https://namegender.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The service operator shown at the end of this page is responsible for this processing unless a separate\n    agreement says otherwise. When a customer submits data about other people, that customer decides why the data\n    is processed and NameGender acts as a service provider or processor for the requested operation.\ndata_categories:\n- category: contact\n  text: 'Account data: name, email address, password hash, optional company and country details, account preferences\n   \
  \ and verification status.'\n- category: identifying\n  text: 'Authentication and security data: API key hashes and prefixes, permitted IP addresses or origins, session\n    information, IP address, user agent and security events.'\n- category: financial\n  text: 'Billing data: package, amount, asset, network, payment address, transaction reference, confirmation state\n    and invoice details.'\n- category: communication\n  text: 'Support and communication data: messages, attachments and information you choose to provide.'\n- category: behavioral\n  text: 'Sign-up source: when you create an account, the first page you opened on the site during that visit, the\n    domain of the website that referred you (not the full address) and any campaign tags in the link (utm_source,\n    utm_medium, utm_campaign).'\npurposes:\n- purpose: Name classification and API access\n  text: Provide name classification, API access, batch processing, account features and support.\n- purpose: Security and fraud\
  \ prevention\n  text: Authenticate requests, enforce quotas, prevent fraud and investigate misuse.\n- purpose: Billing and payments\n  text: Calculate credits, confirm payments, create records and maintain transaction history.\n- purpose: Analytics\n  text: Measure public website visits with Google Analytics only after you grant analytics consent.\n- purpose: Legal compliance\n  text: Comply with legal obligations and establish, exercise or defend legal claims.\nretention:\n- scope: Raw small-request API logs\n  period: 7 days\n  text: 'Raw small-request logs: 7 days.'\n- scope: Uploaded and generated batch files\n  period: 7 days after processing\n  text: 'Uploaded and generated batch files: 7 days after processing.'\n- scope: Account, credit, invoice and transaction records\n  period: while the account is active and longer where accounting, fraud prevention or legal obligations require\n    it\n  text: 'Account, credit, invoice and transaction records: while the account is active and\
  \ longer where accounting,\n    fraud prevention or legal obligations require it.'\n- scope: Google Analytics cookies\n  period: up to 2 years\n  text: Google Analytics cookies can remain for up to 2 years unless you withdraw consent or delete them sooner.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Infrastructure and service providers may process data outside your country. Where required, we use recognised\n    transfer safeguards and limit transfers to what is needed for the service.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request through support or dashboard\n  text: You can request account or personal-data deletion through support.\nrights:\n- right: Access, correction, deletion, restriction, objection\n  text: Depending on where you live, you may have rights to access, correct, delete, restrict or object to processing,\n    receive a portable copy, withdraw consent and complain to a supervisory\
  \ authority.\n- right: Revoke API keys and remove jobs\n  text: You can revoke API keys and remove uploaded jobs from the dashboard.\n- right: Block non-essential browser storage\n  text: You can block non-essential browser storage, although essential login and security cookies are required\n    for the account area.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/namegender/privacy/namegender-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from NameGender's own page on 2026-11-10.
synthetic: false
tags:
- Gender
- Name
- Data Enrichment
- Demographics
- Bulk
---
