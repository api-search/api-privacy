---
api_specs:
- filename: mobilevalidate-com-account-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Account API
  slug: mobilevalidate-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-account-api-openapi.yml
- filename: mobilevalidate-com-catalog-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Catalog API
  slug: mobilevalidate-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-catalog-api-openapi.yml
- filename: mobilevalidate-com-jobs-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Jobs API
  slug: mobilevalidate-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-jobs-api-openapi.yml
- filename: mobilevalidate-com-keys-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Keys API
  slug: mobilevalidate-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-keys-api-openapi.yml
- filename: mobilevalidate-com-lookup-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Lookup API
  slug: mobilevalidate-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-lookup-api-openapi.yml
- filename: mobilevalidate-com-system-api-openapi.yml
  format: yaml
  label: mobilevalidate-com System API
  slug: mobilevalidate-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-system-api-openapi.yml
- filename: mobilevalidate-com-webhooks-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Webhooks API
  slug: mobilevalidate-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-webhooks-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, work e-mail, company, country, website, a short description of intended use, expected monthly volume, services of interest
  - category: identifying
    text: Name, e-mail, organisation, role, sign-in events, passkey public keys, session records with a truncated IP address and browser type
  - category: financial
    text: Company legal name, country, acceptance of our terms, credit balance, top-ups, charges and invoices.
  - category: behavioral
    text: A random session ID kept in your browser tab, the pages you view, clicks on a few buttons
  - category: communication
    text: Chat messages, the page they were sent from, a keyed hash of your IP address
  deletion:
    route: E-mail support@mobilevalidate.com with "Privacy" in the subject line
    text: 'How to exercise them: e-mail support@mobilevalidate.com with "Privacy" in the subject line, or, if your phone number or e-mail address was checked, use the opt-out form .'
  dpa:
    available: true
    text: The Data Processing Agreement sets out our processor terms with customers.
    url: null
  purposes:
  - purpose: Account and service provision
    text: To provide and secure the service
  - purpose: Billing and fraud prevention
    text: To bill, keep accounts and prevent payment fraud
  - purpose: Sanctions screening
    text: To meet sanctions law and our policy on jurisdictions we do not serve
  - purpose: Checks as processor
    text: To perform the checks, as your processor
  - purpose: Website measurement
    text: To see which pages and sources lead people to try the API (see below)
  residency:
  - region: European Union
    text: Our main servers are in the European Union.
  retention:
  - period: 7 days
    scope: Real-time API lookups
    text: Real-time API lookups (identifiers and results) 7 days
  - period: 90 days
    scope: Website measurement events
    text: Website measurement events 90 days; then only daily totals
  - period: For the life of the account
    scope: Account data
    text: Account data For the life of the account, then deleted, except what we must keep for accounting, tax or legal claims
  - period: 10 years after the end of the financial year concerned
    scope: Billing records
    text: Billing, payment and accounting records (no checked identifiers) 10 years after the end of the financial year concerned
  rights:
  - right: access
    text: access your personal data and get a copy
  - right: correction and deletion
    text: have it corrected or deleted
  - right: restriction and objection
    text: restrict its use or object to it, including at any time to processing based on legitimate interests and to direct marketing
  - right: portability
    text: receive it in a portable format
  - right: withdraw consent
    text: withdraw consent, where we rely on consent
  - right: complain
    text: complain to a data-protection supervisory authority
  role:
    text: Processor for the customer (under US state laws, service provider ). The customer decides why the data is checked and is the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information of customers, account users or website visitors
  subprocessors:
    text: We publish the categories. We give the identities, roles, processing locations and changes of these providers to customers, authorities and other persons where the law or the Data Processing Agreement requires it
    url: null
  transfers:
  - mechanism: SCC
    text: the EU Standard Contractual Clauses adopted by Commission Implementing Decision (EU) 2021/914
  - mechanism: other
    text: for the UK, the International Data Transfer Addendum issued by the Information Commissioner under section 119A of the Data Protection Act 2018
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mobilevalidate-com
provenance_date: '2026-11-10'
provider_name: mobilevalidate-com
provider_slug: mobilevalidate-com
slug: mobilevalidate-com-privacy-policy
source_date: '2026-11-10'
source_filename: mobilevalidate-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mobilevalidate.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mobilevalidate-com\naid: mobilevalidate-com\nurl: https://mobilevalidate.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Processor for the customer (under US state laws, service provider ). The customer decides why the data is\n    checked and is the controller.\ndata_categories:\n- category: contact\n  text: Name, work e-mail, company, country, website, a short description of intended use, expected monthly volume,\n    services of interest\n- category: identifying\n  text: Name, e-mail, organisation, role, sign-in events, passkey public keys, session records with a truncated\n\
  \    IP address and browser type\n- category: financial\n  text: Company legal name, country, acceptance of our terms, credit balance, top-ups, charges and invoices.\n- category: behavioral\n  text: A random session ID kept in your browser tab, the pages you view, clicks on a few buttons\n- category: communication\n  text: Chat messages, the page they were sent from, a keyed hash of your IP address\npurposes:\n- purpose: Account and service provision\n  text: To provide and secure the service\n- purpose: Billing and fraud prevention\n  text: To bill, keep accounts and prevent payment fraud\n- purpose: Sanctions screening\n  text: To meet sanctions law and our policy on jurisdictions we do not serve\n- purpose: Checks as processor\n  text: To perform the checks, as your processor\n- purpose: Website measurement\n  text: To see which pages and sources lead people to try the API (see below)\nretention:\n- scope: Real-time API lookups\n  period: 7 days\n  text: Real-time API lookups (identifiers\
  \ and results) 7 days\n- scope: Website measurement events\n  period: 90 days\n  text: Website measurement events 90 days; then only daily totals\n- scope: Account data\n  period: For the life of the account\n  text: Account data For the life of the account, then deleted, except what we must keep for accounting, tax or\n    legal claims\n- scope: Billing records\n  period: 10 years after the end of the financial year concerned\n  text: Billing, payment and accounting records (no checked identifiers) 10 years after the end of the financial\n    year concerned\nresidency:\n- region: European Union\n  text: Our main servers are in the European Union.\ntransfers:\n- mechanism: SCC\n  text: the EU Standard Contractual Clauses adopted by Commission Implementing Decision (EU) 2021/914\n- mechanism: other\n  text: for the UK, the International Data Transfer Addendum issued by the Information Commissioner under section\n    119A of the Data Protection Act 2018\nsubprocessors:\n  url: null\n  text:\
  \ We publish the categories. We give the identities, roles, processing locations and changes of these providers\n    to customers, authorities and other persons where the law or the Data Processing Agreement requires it\ndpa:\n  available: true\n  url: null\n  text: The Data Processing Agreement sets out our processor terms with customers.\ndeletion:\n  route: E-mail support@mobilevalidate.com with \"Privacy\" in the subject line\n  text: 'How to exercise them: e-mail support@mobilevalidate.com with \"Privacy\" in the subject line, or, if your\n    phone number or e-mail address was checked, use the opt-out form .'\nrights:\n- right: access\n  text: access your personal data and get a copy\n- right: correction and deletion\n  text: have it corrected or deleted\n- right: restriction and objection\n  text: restrict its use or object to it, including at any time to processing based on legitimate interests and\n    to direct marketing\n- right: portability\n  text: receive it in a portable\
  \ format\n- right: withdraw consent\n  text: withdraw consent, where we rely on consent\n- right: complain\n  text: complain to a data-protection supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information of customers, account users or website visitors\n"
source_yaml_url: https://artifacts.apis.io/mobilevalidate-com/privacy/mobilevalidate-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from mobilevalidate-com's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Phone Validation
- Email Verification
- API Service
- Telecommunications
---
