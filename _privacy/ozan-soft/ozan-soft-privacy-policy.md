---
api_specs:
- filename: ozan-soft-gender-inference-api-openapi.yml
  format: yaml
  label: Ozan Soft Gender inference API
  slug: ozan-soft-gender-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozan-soft/openapi/ozan-soft-gender-inference-api-openapi.yml
- filename: ozan-soft-phone-api-openapi.yml
  format: yaml
  label: Ozan Soft Phone API
  slug: ozan-soft-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozan-soft/openapi/ozan-soft-phone-api-openapi.yml
- filename: ozan-soft-quota-api-openapi.yml
  format: yaml
  label: Ozan Soft Quota API
  slug: ozan-soft-quota-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ozan-soft/openapi/ozan-soft-quota-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Users may be asked for, as appropriate, a name, email address, mailing address, phone number and limited billing information.
  - category: device
    text: This may include browser name, computer type, operating system, Internet service provider and similar technical information about a User’s means of connection to our Site.
  - category: financial
    text: Complete payment-card credentials are collected and processed by the payment provider rather than stored by GenderAPI.
  - category: identifying
    source: https://www.genderapi.io/subprocessors
    text: Customer data processed through the Service, account data and technical logs
  - category: financial
    source: https://www.genderapi.io/subprocessors
    text: Customer, order, transaction, device and payment information
  - category: contact
    source: https://www.genderapi.io/subprocessors
    text: Recipient email address, message content and delivery metadata
  - category: communication
    source: https://www.genderapi.io/subprocessors
    text: Contact details, support-message content, attachments and message metadata
  deletion:
    route: Deletion request, or request for earlier removal of uploaded files from the active workspace
    text: After exporting results, the User may request earlier removal from the active workspace.
  dpa:
    available: true
    text: Customers that submit personal data for processing can review our Data Processing Agreement
    url: https://www.genderapi.io/dpa
  purposes:
  - purpose: Customer service
    text: 'Customer service: to respond to support requests and needs.'
  - purpose: Transactional emails
    text: 'Transactional and support emails: to send registration, verification, password-recovery, order and service messages, and to respond to inquiries.'
  - purpose: Site improvement
    text: 'Site improvement: to use feedback to improve products and services.'
  - purpose: Network delivery, traffic security and bot protection
    source: https://www.genderapi.io/subprocessors
    text: Network delivery, traffic security and bot protection
  - purpose: Application, database and file-processing hosting
    source: https://www.genderapi.io/subprocessors
    text: Application, database and file-processing hosting
  - purpose: Card-payment processing
    source: https://www.genderapi.io/subprocessors
    text: Card-payment processing
  - purpose: Transactional email
    source: https://www.genderapi.io/subprocessors
    text: Transactional registration, verification and password-recovery email
  - purpose: Manual customer support
    source: https://www.genderapi.io/subprocessors
    text: Manual customer support
  residency:
  - region: United States
    text: 'DigitalOcean: primary application, database and file-processing infrastructure in the United States'
  - region: Global, including the United States
    source: https://www.genderapi.io/subprocessors
    text: Global, including the United States
  - region: United States
    source: https://www.genderapi.io/subprocessors
    text: United States
  - region: Türkiye
    source: https://www.genderapi.io/subprocessors
    text: Türkiye and provider-authorized locations
  retention:
  - period: 30 days
    scope: Account information
    text: Following account closure or an approved deletion request, information that is not subject to a legal exception is deleted or irreversibly anonymized within 30 days.
  - period: up to seven years
    scope: Billing and transaction records
    text: Invoices, transaction records and the limited billing information needed for accounting, tax, chargeback and fraud-prevention obligations may be retained for up to seven years from the transaction date.
  - period: up to 24 months
    scope: Support communications
    text: Support requests and related correspondence may be retained for up to 24 months after the request is closed
  - period: up to 90 days
    scope: Security and technical logs
    text: Server, authentication and security-event logs may be retained for up to 90 days
  - period: five days
    scope: Excel and CSV uploads
    text: The published policy schedules uploaded Excel and CSV files for removal from active systems within five days.
  rights:
  - right: access, objection and deletion
    text: Applicable access, objection and deletion rights are described in our GDPR privacy information.
  - right: withdraw analytics consent
    text: Users may change their choice at any time through “Cookie preferences” in the footer.
  - right: Objection
    source: https://www.genderapi.io/subprocessors
    text: A customer may submit a reasonable, documented data-protection objection during the notice period under the procedure in the Data Processing Agreement
  role:
    text: 'Data controller · Tax identification number: 7140188422'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: GenderAPI does not sell or rent personal information.
  subprocessors:
    text: Customers that submit personal data for processing can review our Data Processing Agreement and current Subprocessors register .
    url: https://www.genderapi.io/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ozan Soft
provenance_date: '2026-11-10'
provider_name: Ozan Soft
provider_slug: ozan-soft
slug: ozan-soft-privacy-policy
source_date: '2026-11-10'
source_filename: ozan-soft-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.genderapi.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ozan Soft\naid: ozan-soft\nurl: https://www.genderapi.io/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.genderapi.io/privacy-policy\n  - https://www.genderapi.io/subprocessors\nrole:\n  value: both\n  text: 'Data controller · Tax identification number: 7140188422'\ndata_categories:\n- category: identifying\n  text: Users may be asked for, as appropriate, a name, email address, mailing address, phone number and limited\n    billing information.\n- category: device\n  text: This may include browser name, computer type, operating system, Internet service provider and similar technical\n\
  \    information about a User’s means of connection to our Site.\n- category: financial\n  text: Complete payment-card credentials are collected and processed by the payment provider rather than stored\n    by GenderAPI.\n- category: identifying\n  text: Customer data processed through the Service, account data and technical logs\n  source: https://www.genderapi.io/subprocessors\n- category: financial\n  text: Customer, order, transaction, device and payment information\n  source: https://www.genderapi.io/subprocessors\n- category: contact\n  text: Recipient email address, message content and delivery metadata\n  source: https://www.genderapi.io/subprocessors\n- category: communication\n  text: Contact details, support-message content, attachments and message metadata\n  source: https://www.genderapi.io/subprocessors\npurposes:\n- purpose: Customer service\n  text: 'Customer service: to respond to support requests and needs.'\n- purpose: Transactional emails\n  text: 'Transactional and\
  \ support emails: to send registration, verification, password-recovery, order and service\n    messages, and to respond to inquiries.'\n- purpose: Site improvement\n  text: 'Site improvement: to use feedback to improve products and services.'\n- purpose: Network delivery, traffic security and bot protection\n  text: Network delivery, traffic security and bot protection\n  source: https://www.genderapi.io/subprocessors\n- purpose: Application, database and file-processing hosting\n  text: Application, database and file-processing hosting\n  source: https://www.genderapi.io/subprocessors\n- purpose: Card-payment processing\n  text: Card-payment processing\n  source: https://www.genderapi.io/subprocessors\n- purpose: Transactional email\n  text: Transactional registration, verification and password-recovery email\n  source: https://www.genderapi.io/subprocessors\n- purpose: Manual customer support\n  text: Manual customer support\n  source: https://www.genderapi.io/subprocessors\nretention:\n\
  - scope: Account information\n  period: 30 days\n  text: Following account closure or an approved deletion request, information that is not subject to a legal exception\n    is deleted or irreversibly anonymized within 30 days.\n- scope: Billing and transaction records\n  period: up to seven years\n  text: Invoices, transaction records and the limited billing information needed for accounting, tax, chargeback\n    and fraud-prevention obligations may be retained for up to seven years from the transaction date.\n- scope: Support communications\n  period: up to 24 months\n  text: Support requests and related correspondence may be retained for up to 24 months after the request is closed\n- scope: Security and technical logs\n  period: up to 90 days\n  text: Server, authentication and security-event logs may be retained for up to 90 days\n- scope: Excel and CSV uploads\n  period: five days\n  text: The published policy schedules uploaded Excel and CSV files for removal from active systems\
  \ within five\n    days.\nresidency:\n- region: United States\n  text: 'DigitalOcean: primary application, database and file-processing infrastructure in the United States'\n- region: Global, including the United States\n  text: Global, including the United States\n  source: https://www.genderapi.io/subprocessors\n- region: United States\n  text: United States\n  source: https://www.genderapi.io/subprocessors\n- region: Türkiye\n  text: Türkiye and provider-authorized locations\n  source: https://www.genderapi.io/subprocessors\ntransfers: []\nsubprocessors:\n  url: https://www.genderapi.io/subprocessors\n  text: Customers that submit personal data for processing can review our Data Processing Agreement and current\n    Subprocessors register .\ndpa:\n  available: true\n  url: https://www.genderapi.io/dpa\n  text: Customers that submit personal data for processing can review our Data Processing Agreement\ndeletion:\n  route: Deletion request, or request for earlier removal of uploaded files\
  \ from the active workspace\n  text: After exporting results, the User may request earlier removal from the active workspace.\nrights:\n- right: access, objection and deletion\n  text: Applicable access, objection and deletion rights are described in our GDPR privacy information.\n- right: withdraw analytics consent\n  text: Users may change their choice at any time through “Cookie preferences” in the footer.\n- right: Objection\n  text: A customer may submit a reasonable, documented data-protection objection during the notice period under\n    the procedure in the Data Processing Agreement\n  source: https://www.genderapi.io/subprocessors\nsale_or_sharing:\n  stance: prohibited\n  text: GenderAPI does not sell or rent personal information.\n"
source_yaml_url: https://artifacts.apis.io/ozan-soft/privacy/ozan-soft-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from Ozan Soft's own page on 2026-11-10.
synthetic: false
tags:
- Data Enrichment
- Gender Detection
- Name Analysis
- Demographics
- Identity
- Marketing Data
- Developer API
- Phone Validation
---
