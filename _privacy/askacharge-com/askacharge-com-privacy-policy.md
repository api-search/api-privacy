---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, password (stored hashed with bcrypt, never in clear text)
  - category: contact
    text: Name, email, phone, company, your charging sessions
  - category: financial
    text: if you save a card, the customer and payment method identifiers Stripe returns to us. Card numbers never reach our servers — Stripe captures them directly.
  - category: device
    text: The web server keeps access logs including IP addresses.
  - category: behavioral
    text: Charger, start and end times, energy delivered, meter readings and amount charged.
  - category: communication
    text: Your email and whatever you choose to tell us in the form (how many chargers you have, which brand, what you would control them with and whether they are in different places)
  deletion:
    route: Platform export and delete tools for operators; or written request to info@askacharge.com
    text: the platform gives them tools to export and delete their customers' data, and we help them if needed.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operator account service
    text: If you create an operator account
  - purpose: Receipts and refunds for QR charging
    text: so that a receipt can be issued and a refund handled
  - purpose: Tax filing
    text: Filing of issued invoices where the law requires it. Legal obligation.
  - purpose: Waiting list updates
    text: Only to let you know when Casa opens and, if needed, to ask you something so we design it well. No advertising.
  - purpose: Aggregate site measurement
    text: to measure visits in aggregate
  - purpose: Security and operation
    text: 'Legal basis: legitimate interest in the security and correct operation of the service.'
  residency:
  - region: European Union
    text: On our own servers hosted in the European Union.
  retention:
  - period: null
    scope: Operator account and contents
    text: While the account is active, then for as long as needed to wind the relationship down.
  - period: up to 6 years
    scope: Invoices and tax records
    text: The statutory commercial and tax retention periods (up to 6 years).
  - period: 90 days
    scope: API key activity trail
    text: Writes and rejected attempts made with each API key are recorded with IP, operation and result, and deleted after 90 days.
  - period: null
    scope: Web server access logs
    text: The server's usual rotation, a few weeks.
  rights:
  - right: access
    text: You can ask us for access to your data, its rectification or erasure, restriction of or objection to processing, and portability
  - right: rectification or erasure
    text: its rectification or erasure, restriction of or objection to processing, and portability
  - right: complaint
    text: you can complain to the Spanish Data Protection Agency ( aepd.es )
  role:
    text: when an operator uses askacharge.com to run its chargers, the data of its customers and drivers belongs to that operator, not to us . We process it on their behalf, as a processor. For the operator's own account data we are the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not share it for advertising purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: This involves an international transfer to the United States, covered by the European Commission's standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aska Charge
provenance_date: '2026-11-09'
provider_name: Aska Charge
provider_slug: askacharge-com
slug: askacharge-com-privacy-policy
source_date: '2026-11-09'
source_filename: askacharge-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askacharge.com/askacharge/en/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aska Charge\naid: askacharge-com\nurl: https://askacharge.com/askacharge/en/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: when an operator uses askacharge.com to run its chargers, the data of its customers and drivers belongs\n    to that operator, not to us . We process it on their behalf, as a processor. For the operator's own account\n    data we are the controller.\ndata_categories:\n- category: identifying\n  text: Name, email address, password (stored hashed with bcrypt, never in clear text)\n- category: contact\n  text: Name, email, phone, company, your charging sessions\n-\
  \ category: financial\n  text: if you save a card, the customer and payment method identifiers Stripe returns to us. Card numbers never\n    reach our servers — Stripe captures them directly.\n- category: device\n  text: The web server keeps access logs including IP addresses.\n- category: behavioral\n  text: Charger, start and end times, energy delivered, meter readings and amount charged.\n- category: communication\n  text: Your email and whatever you choose to tell us in the form (how many chargers you have, which brand, what\n    you would control them with and whether they are in different places)\npurposes:\n- purpose: Operator account service\n  text: If you create an operator account\n- purpose: Receipts and refunds for QR charging\n  text: so that a receipt can be issued and a refund handled\n- purpose: Tax filing\n  text: Filing of issued invoices where the law requires it. Legal obligation.\n- purpose: Waiting list updates\n  text: Only to let you know when Casa opens and, if\
  \ needed, to ask you something so we design it well. No advertising.\n- purpose: Aggregate site measurement\n  text: to measure visits in aggregate\n- purpose: Security and operation\n  text: 'Legal basis: legitimate interest in the security and correct operation of the service.'\nretention:\n- scope: Operator account and contents\n  period: null\n  text: While the account is active, then for as long as needed to wind the relationship down.\n- scope: Invoices and tax records\n  period: up to 6 years\n  text: The statutory commercial and tax retention periods (up to 6 years).\n- scope: API key activity trail\n  period: 90 days\n  text: Writes and rejected attempts made with each API key are recorded with IP, operation and result, and deleted\n    after 90 days.\n- scope: Web server access logs\n  period: null\n  text: The server's usual rotation, a few weeks.\nresidency:\n- region: European Union\n  text: On our own servers hosted in the European Union.\ntransfers:\n- mechanism: SCC\n \
  \ text: This involves an international transfer to the United States, covered by the European Commission's standard\n    contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Platform export and delete tools for operators; or written request to info@askacharge.com\n  text: the platform gives them tools to export and delete their customers' data, and we help them if needed.\nrights:\n- right: access\n  text: You can ask us for access to your data, its rectification or erasure, restriction of or objection to processing,\n    and portability\n- right: rectification or erasure\n  text: its rectification or erasure, restriction of or objection to processing, and portability\n- right: complaint\n  text: you can complain to the Spanish Data Protection Agency ( aepd.es )\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not share it for advertising purposes.\n"
source_yaml_url: https://artifacts.apis.io/askacharge-com/privacy/askacharge-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Aska Charge's own page on 2026-11-09.
synthetic: false
tags:
- Electric Vehicles
- Software-as-a-Service
- Charging
- Fleet Management
- Billing
---
