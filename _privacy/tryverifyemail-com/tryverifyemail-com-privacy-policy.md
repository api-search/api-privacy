---
api_specs:
- filename: tryverifyemail-com-openapi-generated.yml
  format: yaml
  label: tryverifyemail-com API
  slug: tryverifyemail-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tryverifyemail-com/openapi/_ae-authored/tryverifyemail-com-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data : name, email address, password, and organisation details.'
  - category: financial
    text: 'Billing data : handled by our payment provider Polar; we receive limited confirmation and invoice details, not your full card number.'
  - category: communication
    text: 'Support data : messages and attachments you send us.'
  - category: device
    text: IP address, device and browser type, pages and API endpoints used, timestamps, and similar diagnostics.
  - category: contact
    text: 'Customer Data : the email addresses and related fields you submit for verification.'
  deletion:
    route: user deletes data in account or by request
    text: you can delete them at any time, and deletion is permanent (no soft-delete or hidden copies)
  dpa:
    available: null
    text: That relationship is governed by our Data Processing Agreement and our GDPR page
    url: null
  purposes:
  - purpose: provide and secure the Service
    text: provide, maintain and secure the Service, and verify the addresses you submit
  - purpose: payments and account messages
    text: process payments, manage credits, and send service and account messages
  - purpose: support
    text: provide support and respond to your requests
  - purpose: abuse and fraud prevention
    text: monitor, prevent and investigate abuse, fraud and security incidents
  - purpose: improve the Service
    text: improve the Service and develop new features (using aggregated or de-identified data wherever possible)
  residency:
  - region: India
    text: We operate from India and use providers that may store or process data in other countries
  retention:
  - period: 360 days
    scope: Uploaded lists and verification results
    text: Uploaded lists and verification results are kept for 360 days on every plan, or until you delete them
  - period: deleted within 30 days of account closure
    scope: Account data
    text: Account data is kept while your account is open and deleted within 30 days of account closure.
  - period: as long as the law requires
    scope: Billing and tax records
    text: Billing and tax records are kept for as long as the law requires us to keep them.
  rights:
  - right: access, correct, delete, receive copy
    text: the right to access, correct, delete, or receive a copy of your personal data
  - right: object or restrict processing
    text: to object to or restrict certain processing
  - right: withdraw consent
    text: to withdraw consent
  - right: complain to data-protection authority
    text: you can complain to your local data-protection authority if you are unhappy with our response
  role:
    text: we handle personal data in two distinct roles
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses (and the UK Addendum)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tryverifyemail-com
provenance_date: '2026-11-10'
provider_name: tryverifyemail-com
provider_slug: tryverifyemail-com
slug: tryverifyemail-com-privacy-policy
source_date: '2026-11-10'
source_filename: tryverifyemail-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tryverifyemail.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tryverifyemail-com\naid: tryverifyemail-com\nurl: https://tryverifyemail.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we handle personal data in two distinct roles\ndata_categories:\n- category: identifying\n  text: 'Account data : name, email address, password, and organisation details.'\n- category: financial\n  text: 'Billing data : handled by our payment provider Polar; we receive limited confirmation and invoice details,\n    not your full card number.'\n- category: communication\n  text: 'Support data : messages and attachments you send us.'\n- category: device\n  text:\
  \ IP address, device and browser type, pages and API endpoints used, timestamps, and similar diagnostics.\n- category: contact\n  text: 'Customer Data : the email addresses and related fields you submit for verification.'\npurposes:\n- purpose: provide and secure the Service\n  text: provide, maintain and secure the Service, and verify the addresses you submit\n- purpose: payments and account messages\n  text: process payments, manage credits, and send service and account messages\n- purpose: support\n  text: provide support and respond to your requests\n- purpose: abuse and fraud prevention\n  text: monitor, prevent and investigate abuse, fraud and security incidents\n- purpose: improve the Service\n  text: improve the Service and develop new features (using aggregated or de-identified data wherever possible)\nretention:\n- scope: Uploaded lists and verification results\n  period: 360 days\n  text: Uploaded lists and verification results are kept for 360 days on every plan, or until you\
  \ delete them\n- scope: Account data\n  period: deleted within 30 days of account closure\n  text: Account data is kept while your account is open and deleted within 30 days of account closure.\n- scope: Billing and tax records\n  period: as long as the law requires\n  text: Billing and tax records are kept for as long as the law requires us to keep them.\nresidency:\n- region: India\n  text: We operate from India and use providers that may store or process data in other countries\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses (and the\n    UK Addendum)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: That relationship is governed by our Data Processing Agreement and our GDPR page\ndeletion:\n  route: user deletes data in account or by request\n  text: you can delete them at any time, and deletion is permanent (no soft-delete or hidden copies)\nrights:\n- right:\
  \ access, correct, delete, receive copy\n  text: the right to access, correct, delete, or receive a copy of your personal data\n- right: object or restrict processing\n  text: to object to or restrict certain processing\n- right: withdraw consent\n  text: to withdraw consent\n- right: complain to data-protection authority\n  text: you can complain to your local data-protection authority if you are unhappy with our response\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data\n"
source_yaml_url: https://artifacts.apis.io/tryverifyemail-com/privacy/tryverifyemail-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from tryverifyemail-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email Verification
- Data Validation
- Deliverability
- Bulk
---
