---
api_specs:
- filename: temlavo-documents-api-openapi.yml
  format: yaml
  label: Temlavo Documents API
  slug: temlavo-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temlavo/openapi/temlavo-documents-api-openapi.yml
- filename: temlavo-usage-api-openapi.yml
  format: yaml
  label: Temlavo Usage API
  slug: temlavo-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temlavo/openapi/temlavo-usage-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and contact information
  - category: financial
    text: Stripe handles payment-method and payment-processing information.
  - category: location
    text: measures aggregate page views, approximate location, device and browser information
  - category: other
    text: Submitted source files may contain personal information about vendors, customers, employees, sole traders, or other people.
  deletion:
    route: Email privacy@temlavo.com for account closure or deletion requests
    text: To request account closure or return/deletion of retained personal data, contact privacy@temlavo.com
  dpa:
    available: true
    text: For personal data processed on a customer's behalf, the Data Processing Addendum (DPA) sets out processing terms
    url: null
  purposes:
  - purpose: Provide, secure and operate the service
    text: 'We use information only as needed to: provide, secure, and operate the service'
  - purpose: Measure advertising sign-ups with permission
    text: measure with your permission whether our advertising led to sign-ups
  - purpose: No advertising use of invoice content
    text: Temlavo does not use invoice content for advertising
  residency:
  - region: Cyprus
    text: Service operated from Cyprus
  - region: Other countries
    text: uses service providers that may process information in other countries
  retention:
  - period: 24-hour
    scope: Source files and processing intermediates
    text: A 24-hour default expiry applies from each stored object's creation for confirmed source files and processing intermediates.
  - period: Seven days
    scope: Structured document results
    text: Seven days from completion by default.
  - period: seven days
    scope: Idempotency records
    text: Retained for seven days to preserve safe replay behavior.
  - period: approximately 90 days
    scope: Operational records
    text: Generally retained for approximately 90 days where needed for service operation, security, and reliability.
  - period: 365 days
    scope: Source labels
    text: Source labels are kept for up to 365 days from account creation.
  - period: active account lifetime
    scope: Accounting-entity discovery IDs
    text: Raw customer-supplied accounting-entity IDs and their first/last-seen timestamps are retained for the active account lifetime.
  rights:
  - right: Access, correction, deletion, restriction, portability, objection
    text: you may have rights to request access, correction, deletion, restriction, portability, or objection
  - right: Withdraw consent
    text: to withdraw consent where processing depends on consent
  - right: Complain to authority
    text: to complain to a relevant data-protection authority
  role:
    text: Where Temlavo acts as a controller and EU/EEA data-protection law applies
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: For personal data processed on a customer's behalf, the Data Processing Addendum (DPA) sets out processing terms and its contractual subprocessor schedule.
    url: null
  transfers:
  - mechanism: other
    text: For information about provider locations and applicable transfer arrangements, contact privacy@temlavo.com.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Temlavo
provenance_date: '2026-11-10'
provider_name: Temlavo
provider_slug: temlavo
slug: temlavo-privacy-policy
source_date: '2026-11-10'
source_filename: temlavo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://temlavo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Temlavo\naid: temlavo\nurl: https://temlavo.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where Temlavo acts as a controller and EU/EEA data-protection law applies\ndata_categories:\n- category: identifying\n  text: Account and contact information\n- category: financial\n  text: Stripe handles payment-method and payment-processing information.\n- category: location\n  text: measures aggregate page views, approximate location, device and browser information\n- category: other\n  text: Submitted source files may contain personal information about vendors, customers, employees, sole traders,\n\
  \    or other people.\npurposes:\n- purpose: Provide, secure and operate the service\n  text: 'We use information only as needed to: provide, secure, and operate the service'\n- purpose: Measure advertising sign-ups with permission\n  text: measure with your permission whether our advertising led to sign-ups\n- purpose: No advertising use of invoice content\n  text: Temlavo does not use invoice content for advertising\nretention:\n- scope: Source files and processing intermediates\n  period: 24-hour\n  text: A 24-hour default expiry applies from each stored object's creation for confirmed source files and processing\n    intermediates.\n- scope: Structured document results\n  period: Seven days\n  text: Seven days from completion by default.\n- scope: Idempotency records\n  period: seven days\n  text: Retained for seven days to preserve safe replay behavior.\n- scope: Operational records\n  period: approximately 90 days\n  text: Generally retained for approximately 90 days where needed\
  \ for service operation, security, and reliability.\n- scope: Source labels\n  period: 365 days\n  text: Source labels are kept for up to 365 days from account creation.\n- scope: Accounting-entity discovery IDs\n  period: active account lifetime\n  text: Raw customer-supplied accounting-entity IDs and their first/last-seen timestamps are retained for the active\n    account lifetime.\nresidency:\n- region: Cyprus\n  text: Service operated from Cyprus\n- region: Other countries\n  text: uses service providers that may process information in other countries\ntransfers:\n- mechanism: other\n  text: For information about provider locations and applicable transfer arrangements, contact privacy@temlavo.com.\nsubprocessors:\n  url: null\n  text: For personal data processed on a customer's behalf, the Data Processing Addendum (DPA) sets out processing\n    terms and its contractual subprocessor schedule.\ndpa:\n  available: true\n  url: null\n  text: For personal data processed on a customer's\
  \ behalf, the Data Processing Addendum (DPA) sets out processing\n    terms\ndeletion:\n  route: Email privacy@temlavo.com for account closure or deletion requests\n  text: To request account closure or return/deletion of retained personal data, contact privacy@temlavo.com\nrights:\n- right: Access, correction, deletion, restriction, portability, objection\n  text: you may have rights to request access, correction, deletion, restriction, portability, or objection\n- right: Withdraw consent\n  text: to withdraw consent where processing depends on consent\n- right: Complain to authority\n  text: to complain to a relevant data-protection authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/temlavo/privacy/temlavo-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Temlavo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Invoices
- Extraction
- Accounting
---
