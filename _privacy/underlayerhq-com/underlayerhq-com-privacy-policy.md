---
api_specs:
- filename: underlayerhq-com-openapi-generated.yml
  format: yaml
  label: underlayerhq-com API
  slug: underlayerhq-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/underlayerhq-com/openapi/_ae-authored/underlayerhq-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email address, and password (or SSO identifier) when you create an account.
  - category: contact
    text: Company or workspace name, billing address, and VAT/tax registration number where applicable.
  - category: financial
    text: such as the last four digits of a card, billing address, and transaction status.
  - category: device
    text: IP address, browser and device type, and pages visited on underlayerhq.com, collected via standard server logs and privacy-respecting analytics.
  - category: behavioral
    text: Progress, quiz answers, scores, view events, and completion events recorded as a Learner interacts with an embedded course.
  - category: identifying
    text: Identifiers a Customer provisions through the Identities API (typically a Customer-assigned user ID, and optionally a name or email address the Customer chooses to pass to us).
  deletion:
    route: Account closure or support/API export
    text: If a Customer closes its workspace, we delete or anonymize Personal Data within 90 days, except where retention is required by law.
  dpa:
    available: true
    text: Our processing obligations to Customers are set out in our Data Processing Addendum ("DPA"), available on request
    url: null
  purposes:
  - purpose: Operating and securing the Services
    text: Operating, maintaining, and securing the Services, including authenticating API requests and enforcing usage limits.
  - purpose: Generating and delivering courses
    text: Generating, storing, and delivering courses on a Customer's instructions.
  - purpose: Learner progress reporting
    text: Recording and reporting Learner progress and completions back to the Customer via the Tracking API and webhooks.
  - purpose: Payments and tax
    text: Processing payments, issuing invoices, and complying with UAE tax and accounting obligations, including VAT record-keeping under Federal Decree-Law No. 8 of 2017.
  - purpose: Fraud and abuse prevention
    text: Detecting, investigating, and preventing fraud, abuse, or violations of our Terms of Service.
  retention:
  - period: 90 days
    scope: Closed workspace
    text: If a Customer closes its workspace, we delete or anonymize Personal Data within 90 days, except where retention is required by law.
  - period: at least five years
    scope: Financial records
    text: UAE tax and accounting record-keeping, which generally requires financial records to be retained for at least five years
  rights:
  - right: access
    text: the right to request access to, correction of, or erasure of your Personal Data
  - right: objection and restriction
    text: to object to or restrict certain processing
  - right: portability
    text: to request that we transfer your data to another provider (data portability)
  - right: withdraw consent
    text: to withdraw consent at any time where processing is based on consent
  - right: deletion (CCPA)
    text: to request its deletion, and to opt out of any "sale" or "sharing" of Personal Data
  role:
    text: Underlayer wears two hats, and which one applies depends on whose data is involved.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell Personal Data, and we do not share it with third parties for their own independent marketing purposes.
  subprocessors:
    text: The current list is published in full at underlayerhq.com/sub-processors, naming each one and what it receives
    url: underlayerhq.com/sub-processors
  transfers:
  - mechanism: adequacy
    text: we do so only where the destination country is recognized by the UAE Data Office as providing an adequate level of protection
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses or an equivalent UK mechanism as an additional safeguard.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: underlayerhq-com
provenance_date: '2026-11-10'
provider_name: underlayerhq-com
provider_slug: underlayerhq-com
slug: underlayerhq-com-privacy-policy
source_date: '2026-11-10'
source_filename: underlayerhq-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://underlayerhq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: underlayerhq-com\naid: underlayerhq-com\nurl: https://underlayerhq.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Underlayer wears two hats, and which one applies depends on whose data is involved.\ndata_categories:\n- category: identifying\n  text: Name, work email address, and password (or SSO identifier) when you create an account.\n- category: contact\n  text: Company or workspace name, billing address, and VAT/tax registration number where applicable.\n- category: financial\n  text: such as the last four digits of a card, billing address, and transaction status.\n- category: device\n\
  \  text: IP address, browser and device type, and pages visited on underlayerhq.com, collected via standard server\n    logs and privacy-respecting analytics.\n- category: behavioral\n  text: Progress, quiz answers, scores, view events, and completion events recorded as a Learner interacts with\n    an embedded course.\n- category: identifying\n  text: Identifiers a Customer provisions through the Identities API (typically a Customer-assigned user ID, and\n    optionally a name or email address the Customer chooses to pass to us).\npurposes:\n- purpose: Operating and securing the Services\n  text: Operating, maintaining, and securing the Services, including authenticating API requests and enforcing usage\n    limits.\n- purpose: Generating and delivering courses\n  text: Generating, storing, and delivering courses on a Customer's instructions.\n- purpose: Learner progress reporting\n  text: Recording and reporting Learner progress and completions back to the Customer via the Tracking API\
  \ and webhooks.\n- purpose: Payments and tax\n  text: Processing payments, issuing invoices, and complying with UAE tax and accounting obligations, including\n    VAT record-keeping under Federal Decree-Law No. 8 of 2017.\n- purpose: Fraud and abuse prevention\n  text: Detecting, investigating, and preventing fraud, abuse, or violations of our Terms of Service.\nretention:\n- scope: Closed workspace\n  period: 90 days\n  text: If a Customer closes its workspace, we delete or anonymize Personal Data within 90 days, except where retention\n    is required by law.\n- scope: Financial records\n  period: at least five years\n  text: UAE tax and accounting record-keeping, which generally requires financial records to be retained for at\n    least five years\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: we do so only where the destination country is recognized by the UAE Data Office as providing an adequate\n    level of protection\n- mechanism: SCC\n  text: we rely on the European\
  \ Commission's Standard Contractual Clauses or an equivalent UK mechanism as an additional\n    safeguard.\nsubprocessors:\n  url: underlayerhq.com/sub-processors\n  text: The current list is published in full at underlayerhq.com/sub-processors, naming each one and what it receives\ndpa:\n  available: true\n  url: null\n  text: Our processing obligations to Customers are set out in our Data Processing Addendum (\"DPA\"), available on\n    request\ndeletion:\n  route: Account closure or support/API export\n  text: If a Customer closes its workspace, we delete or anonymize Personal Data within 90 days, except where retention\n    is required by law.\nrights:\n- right: access\n  text: the right to request access to, correction of, or erasure of your Personal Data\n- right: objection and restriction\n  text: to object to or restrict certain processing\n- right: portability\n  text: to request that we transfer your data to another provider (data portability)\n- right: withdraw consent\n  text:\
  \ to withdraw consent at any time where processing is based on consent\n- right: deletion (CCPA)\n  text: to request its deletion, and to opt out of any \"sale\" or \"sharing\" of Personal Data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell Personal Data, and we do not share it with third parties for their own independent marketing\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/underlayerhq-com/privacy/underlayerhq-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from underlayerhq-com's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Software-as-a-Service
- Training
- LMS
- Embeddings
---
