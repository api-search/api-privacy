---
api_specs:
- filename: unipile-com-accounts-api-openapi.yml
  format: yaml
  label: unipile-com Accounts API
  slug: unipile-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-accounts-api-openapi.yml
- filename: unipile-com-calendars-api-openapi.yml
  format: yaml
  label: unipile-com Calendars API
  slug: unipile-com-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-calendars-api-openapi.yml
- filename: unipile-com-emails-api-openapi.yml
  format: yaml
  label: unipile-com Emails API
  slug: unipile-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-emails-api-openapi.yml
- filename: unipile-com-linkedin-specific-api-openapi.yml
  format: yaml
  label: unipile-com LinkedIn Specific API
  slug: unipile-com-linkedin-specific-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-linkedin-specific-api-openapi.yml
- filename: unipile-com-messaging-api-openapi.yml
  format: yaml
  label: unipile-com Messaging API
  slug: unipile-com-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-messaging-api-openapi.yml
- filename: unipile-com-posts-api-openapi.yml
  format: yaml
  label: unipile-com Posts API
  slug: unipile-com-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-posts-api-openapi.yml
- filename: unipile-com-users-api-openapi.yml
  format: yaml
  label: unipile-com Users API
  slug: unipile-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-users-api-openapi.yml
- filename: unipile-com-webhooks-api-openapi.yml
  format: yaml
  label: unipile-com Webhooks API
  slug: unipile-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-webhooks-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and last name, professional email address, company name, job title and contact details provided when creating an account or contacting us
  - category: financial
    text: 'Billing data : billing address, information required to issue invoices, and limited payment-related information.'
  - category: device
    text: IP address, browser type and version, operating system, device identifier, language, pages visited, date and time of access, connection data
  - category: communication
    text: Text messages, attachments, images, documents and voice notes
  - category: communication
    text: Headers, sender and recipient addresses, plain-text or HTML body, and attachments
  - category: behavioral
    text: 'Aggregated usage data : statistics relating to the use of the website and the API services selected'
  deletion:
    route: Customer choice on agreement end; controller data via dpo@unipile.com or start@unipile.com
    text: When the agreement ends, Unipile will, at the customer’s choice, return or delete the personal data received in connection with the service, including copies held in its systems
  dpa:
    available: true
    text: the Data Processing Agreement (“DPA”) entered into with that customer
    url: null
  purposes:
  - purpose: Account and service provision
    text: Creating and administering customer accounts, providing the services and managing subscriptions
  - purpose: Billing and accounting
    text: Managing billing, payments and accounting
  - purpose: Security
    text: Securing the website, preventing misuse and investigating incidents
  - purpose: Marketing
    text: Sending marketing communications
  - purpose: Customer API processing
    text: Unipile does not use data processed on behalf of its customers for its own purposes.
  residency:
  - region: United States / EU
    text: INTERCOM R&D UNLIMITED COMPANY Customer support platform (V2) Ireland United States / EU (Dublin)
  retention:
  - period: 30 days
    scope: Account registration data (controller)
    text: account registration data is retained for the duration of the contractual relationship and for 30 days after account deletion
  - period: 30 days
    scope: Technical and browsing information (controller)
    text: technical and browsing information is retained for 30 days from collection
  - period: 7 days
    scope: Payment information after anomaly
    text: limited payment information retained in the event of a payment anomaly is kept for no more than 7 days
  - period: one hour
    scope: Calendar data V2
    text: 'V2: cached for one hour by default; the user may configure this period.'
  rights:
  - right: access
    text: access to your personal data
  - right: correction
    text: correction of inaccurate or incomplete data
  - right: deletion
    text: deletion of your data
  - right: restriction
    text: restriction of processing
  - right: objection
    text: objection to processing based on legitimate interests
  - right: portability
    text: portability of data you provided to us where processing is based on consent or a contract and is carried out by automated means
  - right: withdraw consent
    text: withdrawal of your consent at any time
  role:
    text: 'Unipile acts as a data controller when it determines the purposes and means of processing related in particular to: browsing the unipile.com website'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Unipile does not sell personal data.
  subprocessors:
    text: Unipile uses the following sub-processors in connection with its API services.
    url: null
  transfers:
  - mechanism: adequacy
    text: an adequacy decision adopted by the European Commission
  - mechanism: SCC
    text: the European Commission’s Standard Contractual Clauses, supplemented where necessary by a transfer impact assessment and additional safeguards
  - mechanism: DPF
    text: valid certification under the EU-U.S. Data Privacy Framework where that mechanism applies
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: unipile-com
provenance_date: '2026-11-10'
provider_name: unipile-com
provider_slug: unipile-com
slug: unipile-com-privacy-policy
source_date: '2026-11-10'
source_filename: unipile-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.unipile.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: unipile-com\naid: unipile-com\nurl: https://www.unipile.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Unipile acts as a data controller when it determines the purposes and means of processing related in particular\n    to: browsing the unipile.com website'\ndata_categories:\n- category: identifying\n  text: first and last name, professional email address, company name, job title and contact details provided when\n    creating an account or contacting us\n- category: financial\n  text: 'Billing data : billing address, information required to issue invoices, and limited payment-related\
  \ information.'\n- category: device\n  text: IP address, browser type and version, operating system, device identifier, language, pages visited, date\n    and time of access, connection data\n- category: communication\n  text: Text messages, attachments, images, documents and voice notes\n- category: communication\n  text: Headers, sender and recipient addresses, plain-text or HTML body, and attachments\n- category: behavioral\n  text: 'Aggregated usage data : statistics relating to the use of the website and the API services selected'\npurposes:\n- purpose: Account and service provision\n  text: Creating and administering customer accounts, providing the services and managing subscriptions\n- purpose: Billing and accounting\n  text: Managing billing, payments and accounting\n- purpose: Security\n  text: Securing the website, preventing misuse and investigating incidents\n- purpose: Marketing\n  text: Sending marketing communications\n- purpose: Customer API processing\n  text: Unipile\
  \ does not use data processed on behalf of its customers for its own purposes.\nretention:\n- scope: Account registration data (controller)\n  period: 30 days\n  text: account registration data is retained for the duration of the contractual relationship and for 30 days after\n    account deletion\n- scope: Technical and browsing information (controller)\n  period: 30 days\n  text: technical and browsing information is retained for 30 days from collection\n- scope: Payment information after anomaly\n  period: 7 days\n  text: limited payment information retained in the event of a payment anomaly is kept for no more than 7 days\n- scope: Calendar data V2\n  period: one hour\n  text: 'V2: cached for one hour by default; the user may configure this period.'\nresidency:\n- region: United States / EU\n  text: INTERCOM R&D UNLIMITED COMPANY Customer support platform (V2) Ireland United States / EU (Dublin)\ntransfers:\n- mechanism: adequacy\n  text: an adequacy decision adopted by the European\
  \ Commission\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses, supplemented where necessary by a transfer impact\n    assessment and additional safeguards\n- mechanism: DPF\n  text: valid certification under the EU-U.S. Data Privacy Framework where that mechanism applies\nsubprocessors:\n  url: null\n  text: Unipile uses the following sub-processors in connection with its API services.\ndpa:\n  available: true\n  url: null\n  text: the Data Processing Agreement (“DPA”) entered into with that customer\ndeletion:\n  route: Customer choice on agreement end; controller data via dpo@unipile.com or start@unipile.com\n  text: When the agreement ends, Unipile will, at the customer’s choice, return or delete the personal data received\n    in connection with the service, including copies held in its systems\nrights:\n- right: access\n  text: access to your personal data\n- right: correction\n  text: correction of inaccurate or incomplete data\n- right: deletion\n\
  \  text: deletion of your data\n- right: restriction\n  text: restriction of processing\n- right: objection\n  text: objection to processing based on legitimate interests\n- right: portability\n  text: portability of data you provided to us where processing is based on consent or a contract and is carried\n    out by automated means\n- right: withdraw consent\n  text: withdrawal of your consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: Unipile does not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/unipile-com/privacy/unipile-com-privacy-policy.yml
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
summary_line: 31 quoted statements, read from unipile-com's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Integration
- Multi-Channel
- Communications
---
