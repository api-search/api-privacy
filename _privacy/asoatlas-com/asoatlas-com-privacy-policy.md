---
api_specs:
- filename: asoatlas-com-openapi-generated.yml
  format: yaml
  label: ASO Atlas API
  slug: asoatlas-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoatlas-com/openapi/_ae-authored/asoatlas-com-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, a hashed password, and the date you confirmed your email.
  - category: financial
    text: Your subscription status, plan, billing period and the customer and subscription identifiers held by our payment processor.
  - category: device
    text: Your IP address, browser user agent, session records, request timestamps and error logs.
  - category: communication
    text: If you contact us, we keep the message and our reply so we can handle the case and any follow-up.
  deletion:
    route: account settings
    text: You can delete your account yourself from account settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and security
    text: We process this to create and secure your account, which is performance of our contract with you (Art. 6(1)(b) GDPR).
  - purpose: Billing
    text: We process billing data to take payment and to meet accounting and tax obligations (Art. 6(1)(b) and 6(1)(c) GDPR).
  - purpose: Security and diagnostics
    text: We use these to keep the Service secure, prevent abuse, enforce rate limits and diagnose failures.
  residency:
  - region: Germany
    text: Hosting, servers and backups Germany
  - region: EU and USA
    text: Payment processing and invoicing EU and USA
  retention:
  - period: while your account exists, then deleted or anonymised within 30 days of closure
    scope: Account and product data
    text: while your account exists, then deleted or anonymised within 30 days of closure.
  - period: 5 years from the end of the accounting year
    scope: Billing records
    text: 5 years from the end of the accounting year, as Polish tax law requires.
  - period: up to 12 months
    scope: Logs and technical data
    text: 'Logs and technical data : up to 12 months.'
  - period: up to 3 years
    scope: Support correspondence
    text: 'Support correspondence : up to 3 years.'
  rights:
  - right: access
    text: give you a copy of the personal data we hold about you (access)
  - right: erasure
    text: delete your data (erasure)
  - right: portability
    text: send your data to you or another provider in a portable format
  - right: withdraw consent
    text: withdraw consent at any time, where processing is based on consent, without affecting what was done before.
  role:
    text: 'The controller of your personal data is:'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'We share the minimum necessary with the following processors:'
    url: null
  transfers:
  - mechanism: SCC
    text: Where a processor is outside the European Economic Area, the transfer is covered by the European Commission's Standard Contractual Clauses or another mechanism permitted under Chapter V GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ASO Atlas
provenance_date: '2026-11-09'
provider_name: ASO Atlas
provider_slug: asoatlas-com
slug: asoatlas-com-privacy-policy
source_date: '2026-11-09'
source_filename: asoatlas-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asoatlas.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ASO Atlas\naid: asoatlas-com\nurl: https://asoatlas.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller of your personal data is:'\ndata_categories:\n- category: identifying\n  text: Your name, email address, a hashed password, and the date you confirmed your email.\n- category: financial\n  text: Your subscription status, plan, billing period and the customer and subscription identifiers held by our\n    payment processor.\n- category: device\n  text: Your IP address, browser user agent, session records, request timestamps and error logs.\n- category: communication\n\
  \  text: If you contact us, we keep the message and our reply so we can handle the case and any follow-up.\npurposes:\n- purpose: Account creation and security\n  text: We process this to create and secure your account, which is performance of our contract with you (Art. 6(1)(b)\n    GDPR).\n- purpose: Billing\n  text: We process billing data to take payment and to meet accounting and tax obligations (Art. 6(1)(b) and 6(1)(c)\n    GDPR).\n- purpose: Security and diagnostics\n  text: We use these to keep the Service secure, prevent abuse, enforce rate limits and diagnose failures.\nretention:\n- scope: Account and product data\n  period: while your account exists, then deleted or anonymised within 30 days of closure\n  text: while your account exists, then deleted or anonymised within 30 days of closure.\n- scope: Billing records\n  period: 5 years from the end of the accounting year\n  text: 5 years from the end of the accounting year, as Polish tax law requires.\n- scope: Logs and technical\
  \ data\n  period: up to 12 months\n  text: 'Logs and technical data : up to 12 months.'\n- scope: Support correspondence\n  period: up to 3 years\n  text: 'Support correspondence : up to 3 years.'\nresidency:\n- region: Germany\n  text: Hosting, servers and backups Germany\n- region: EU and USA\n  text: Payment processing and invoicing EU and USA\ntransfers:\n- mechanism: SCC\n  text: Where a processor is outside the European Economic Area, the transfer is covered by the European Commission's\n    Standard Contractual Clauses or another mechanism permitted under Chapter V GDPR.\nsubprocessors:\n  url: null\n  text: 'We share the minimum necessary with the following processors:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings\n  text: You can delete your account yourself from account settings.\nrights:\n- right: access\n  text: give you a copy of the personal data we hold about you (access)\n- right: erasure\n  text: delete your data (erasure)\n\
  - right: portability\n  text: send your data to you or another provider in a portable format\n- right: withdraw consent\n  text: withdraw consent at any time, where processing is based on consent, without affecting what was done before.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/asoatlas-com/privacy/asoatlas-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from ASO Atlas's own page on 2026-11-09.
synthetic: false
tags:
- ASO
- App Store
- Keyword Research
- Analytics
- Software-as-a-Service
---
