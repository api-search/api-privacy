---
api_specs:
- filename: faable-com-openapi-generated.yml
  format: yaml
  label: Faable API
  slug: faable-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/faable-com/openapi/_ae-authored/faable-com-openapi-generated.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, name, profile picture, identifiers from the identity provider you signed in with (e.g. GitHub, Google)
  - category: contact
    text: Billing name, billing address, VAT/tax ID, plan, invoices, payment status
  - category: financial
    text: Billing data Billing name, billing address, VAT/tax ID, plan, invoices, payment status
  - category: device
    text: Security data Authentication events, session data, IP address, user agent, rate-limit and abuse signals
  - category: behavioral
    text: Product analytics Pages viewed, features used, pseudonymous device/session identifier
  - category: communication
    text: Support data Emails, ticket contents, and anything you choose to send us
  deletion:
    route: Write to privacy@faable.com or delete via account; customer content deleted within 30 days of account closure or on request
    text: Customer content (apps, deployments, artifacts, Auth users) Deleted within 30 days of account closure or on your request
  dpa:
    available: true
    text: The commitments above form our DPA and are incorporated into the Terms of Service . If your organisation requires a countersigned DPA, request one at privacy@faable.com .
    url: null
  purposes:
  - purpose: Create and authenticate accounts
    text: Create and authenticate your account, associate you with a team
  - purpose: Charge and invoice
    text: Charge for the Services, issue invoices, comply with tax and accounting law
  - purpose: Security and abuse prevention
    text: Detect and prevent fraud, abuse, credential stuffing, and platform misuse
  - purpose: Product analytics with consent
    text: Understand which parts of the product and documentation work
  residency:
  - region: European Union
    text: Application workloads and identity data run on infrastructure located in the European Union .
  retention:
  - period: 30 days
    scope: Account and team data
    text: deleted or anonymised within 30 days of account closure
  - period: 6 years
    scope: Invoices and accounting records
    text: 6 years , as required by Spanish commercial and tax law
  - period: Up to 90 days
    scope: Build and deployment logs
    text: Up to 90 days
  - period: Up to 12 months
    scope: Platform and security logs
    text: Up to 12 months where needed to investigate abuse and security incidents
  - period: 30 days rolling
    scope: Backups
    text: 30 days rolling, after which they expire automatically
  - period: 3 years
    scope: Support correspondence
    text: 3 years from the last message
  - period: Up to 12 months
    scope: Analytics data
    text: Up to 12 months at event level
  rights:
  - right: Access
    text: Access the personal data we hold about you and get a copy of it.
  - right: Rectify
    text: Rectify data that is inaccurate or incomplete.
  - right: Erase
    text: Erase your data (“right to be forgotten”), where no legal obligation requires us to keep it.
  - right: Restrict or object
    text: Restrict or object to processing based on our legitimate interests.
  - right: Portability
    text: Port your data to another provider in a structured, machine-readable format.
  - right: Withdraw consent
    text: Withdraw consent at any time, without affecting processing already carried out.
  role:
    text: We are the controller of your relationship with us.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: We use a small set of specialised providers. Each is bound by a data processing agreement holding them to the same obligations we accept towards you.
    url: null
  transfers:
  - mechanism: adequacy
    text: Where a transfer to a third country happens, it is covered by an adequacy decision, by the EU Standard Contractual Clauses, or by both
  - mechanism: SCC
    text: Where a transfer to a third country happens, it is covered by an adequacy decision, by the EU Standard Contractual Clauses, or by both
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Faable
provenance_date: '2026-11-09'
provider_name: Faable
provider_slug: faable-com
slug: faable-com-privacy-policy
source_date: '2026-11-09'
source_filename: faable-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://faable.com/docs/platform/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Faable\naid: faable-com\nurl: https://faable.com/docs/platform/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of your relationship with us.\ndata_categories:\n- category: identifying\n  text: Email address, name, profile picture, identifiers from the identity provider you signed in with (e.g. GitHub,\n    Google)\n- category: contact\n  text: Billing name, billing address, VAT/tax ID, plan, invoices, payment status\n- category: financial\n  text: Billing data Billing name, billing address, VAT/tax ID, plan, invoices, payment status\n- category: device\n  text:\
  \ Security data Authentication events, session data, IP address, user agent, rate-limit and abuse signals\n- category: behavioral\n  text: Product analytics Pages viewed, features used, pseudonymous device/session identifier\n- category: communication\n  text: Support data Emails, ticket contents, and anything you choose to send us\npurposes:\n- purpose: Create and authenticate accounts\n  text: Create and authenticate your account, associate you with a team\n- purpose: Charge and invoice\n  text: Charge for the Services, issue invoices, comply with tax and accounting law\n- purpose: Security and abuse prevention\n  text: Detect and prevent fraud, abuse, credential stuffing, and platform misuse\n- purpose: Product analytics with consent\n  text: Understand which parts of the product and documentation work\nretention:\n- scope: Account and team data\n  period: 30 days\n  text: deleted or anonymised within 30 days of account closure\n- scope: Invoices and accounting records\n  period: 6\
  \ years\n  text: 6 years , as required by Spanish commercial and tax law\n- scope: Build and deployment logs\n  period: Up to 90 days\n  text: Up to 90 days\n- scope: Platform and security logs\n  period: Up to 12 months\n  text: Up to 12 months where needed to investigate abuse and security incidents\n- scope: Backups\n  period: 30 days rolling\n  text: 30 days rolling, after which they expire automatically\n- scope: Support correspondence\n  period: 3 years\n  text: 3 years from the last message\n- scope: Analytics data\n  period: Up to 12 months\n  text: Up to 12 months at event level\nresidency:\n- region: European Union\n  text: Application workloads and identity data run on infrastructure located in the European Union .\ntransfers:\n- mechanism: adequacy\n  text: Where a transfer to a third country happens, it is covered by an adequacy decision, by the EU Standard Contractual\n    Clauses, or by both\n- mechanism: SCC\n  text: Where a transfer to a third country happens, it is covered\
  \ by an adequacy decision, by the EU Standard Contractual\n    Clauses, or by both\nsubprocessors:\n  url: null\n  text: We use a small set of specialised providers. Each is bound by a data processing agreement holding them to\n    the same obligations we accept towards you.\ndpa:\n  available: true\n  url: null\n  text: The commitments above form our DPA and are incorporated into the Terms of Service . If your organisation\n    requires a countersigned DPA, request one at privacy@faable.com .\ndeletion:\n  route: Write to privacy@faable.com or delete via account; customer content deleted within 30 days of account closure\n    or on request\n  text: Customer content (apps, deployments, artifacts, Auth users) Deleted within 30 days of account closure or\n    on your request\nrights:\n- right: Access\n  text: Access the personal data we hold about you and get a copy of it.\n- right: Rectify\n  text: Rectify data that is inaccurate or incomplete.\n- right: Erase\n  text: Erase your data (“right\
  \ to be forgotten”), where no legal obligation requires us to keep it.\n- right: Restrict or object\n  text: Restrict or object to processing based on our legitimate interests.\n- right: Portability\n  text: Port your data to another provider in a structured, machine-readable format.\n- right: Withdraw consent\n  text: Withdraw consent at any time, without affecting processing already carried out.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/faable-com/privacy/faable-com-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Faable's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- ZeroOps
- Hosting
- Identity
- GDPR
- Software-as-a-Service
---
