---
api_specs:
- filename: asvaai-com-openapi-generated.yml
  format: yaml
  label: Asva AI API
  slug: asvaai-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asvaai-com/openapi/_ae-authored/asvaai-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: work email, name, role, company, password hash.'
  - category: financial
    text: Billing information handled through our payment processor (card tokens, billing address, transaction history).
  - category: communication
    text: Communications you send us (support emails, chat messages, sales inquiries, feedback).
  - category: behavioral
    text: Usage data about how you use the Service (pages visited, tools called, timestamps, error events).
  - category: device
    text: Device and connection data (IP address, browser, operating system, approximate location inferred from IP).
  deletion:
    route: request via privacy email
    text: Delete your personal information, subject to legal retention requirements.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, secure, and improve the Service
    text: Provide, operate, secure, and improve the Service.
  - purpose: Authenticate users
    text: Authenticate users, including through third-party sign-in providers you choose (for example, Google OAuth).
  - purpose: Marketing communications
    text: Send marketing communications you have consented to.
  - purpose: Fraud prevention
    text: Detect, investigate, and prevent fraud, abuse, or violations of our Terms of Service.
  - purpose: Aggregate analytics and benchmarks
    text: Build aggregate analytics, benchmarks, and product usage insights, without identifying any individual or customer.
  residency:
  - region: India
    text: We operate primarily from India and use cloud services hosted in multiple regions, including the United States and the European Union.
  retention:
  - period: up to 24 months
    scope: Account data
    text: 'Account data: while your Account is active, plus up to 24 months after closure unless you request earlier deletion.'
  - period: at least seven years
    scope: Billing records
    text: 'Billing records: at least seven years to meet statutory accounting requirements.'
  - period: up to 13 months
    scope: Audit logs and security records
    text: 'Audit logs and security records: up to 13 months.'
  - period: indefinitely
    scope: Aggregated or de-identified analytics
    text: 'Aggregated or de-identified analytics: indefinitely, in a form that no longer identifies you.'
  rights:
  - right: Access
    text: Access a copy of the personal information we hold about you.
  - right: Correct
    text: Correct inaccurate personal information.
  - right: Delete
    text: Delete your personal information, subject to legal retention requirements.
  - right: Object or restrict
    text: Object to, or restrict, certain processing.
  - right: Withdraw consent
    text: Withdraw consent where we rely on it.
  - right: Portability
    text: Port your personal information to another service in a commonly used format.
  role:
    text: Asva AI acts as a Controller for information we collect directly from you, and as a Processor for Content you submit through the Service on behalf of an enterprise customer.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information for money.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards, such as Standard Contractual Clauses, when transferring personal information outside your region.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Asva AI
provenance_date: '2026-11-09'
provider_name: Asva AI
provider_slug: asvaai-com
slug: asvaai-com-privacy-policy
source_date: '2026-11-09'
source_filename: asvaai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asvaai.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Asva AI\naid: asvaai-com\nurl: https://asvaai.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Asva AI acts as a Controller for information we collect directly from you, and as a Processor for Content\n    you submit through the Service on behalf of an enterprise customer.\ndata_categories:\n- category: identifying\n  text: 'Account information: work email, name, role, company, password hash.'\n- category: financial\n  text: Billing information handled through our payment processor (card tokens, billing address, transaction history).\n- category: communication\n  text: Communications you\
  \ send us (support emails, chat messages, sales inquiries, feedback).\n- category: behavioral\n  text: Usage data about how you use the Service (pages visited, tools called, timestamps, error events).\n- category: device\n  text: Device and connection data (IP address, browser, operating system, approximate location inferred from IP).\npurposes:\n- purpose: Provide, operate, secure, and improve the Service\n  text: Provide, operate, secure, and improve the Service.\n- purpose: Authenticate users\n  text: Authenticate users, including through third-party sign-in providers you choose (for example, Google OAuth).\n- purpose: Marketing communications\n  text: Send marketing communications you have consented to.\n- purpose: Fraud prevention\n  text: Detect, investigate, and prevent fraud, abuse, or violations of our Terms of Service.\n- purpose: Aggregate analytics and benchmarks\n  text: Build aggregate analytics, benchmarks, and product usage insights, without identifying any individual or\n\
  \    customer.\nretention:\n- scope: Account data\n  period: up to 24 months\n  text: 'Account data: while your Account is active, plus up to 24 months after closure unless you request earlier\n    deletion.'\n- scope: Billing records\n  period: at least seven years\n  text: 'Billing records: at least seven years to meet statutory accounting requirements.'\n- scope: Audit logs and security records\n  period: up to 13 months\n  text: 'Audit logs and security records: up to 13 months.'\n- scope: Aggregated or de-identified analytics\n  period: indefinitely\n  text: 'Aggregated or de-identified analytics: indefinitely, in a form that no longer identifies you.'\nresidency:\n- region: India\n  text: We operate primarily from India and use cloud services hosted in multiple regions, including the United\n    States and the European Union.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards, such as Standard Contractual Clauses, when transferring personal information\n   \
  \ outside your region.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request via privacy email\n  text: Delete your personal information, subject to legal retention requirements.\nrights:\n- right: Access\n  text: Access a copy of the personal information we hold about you.\n- right: Correct\n  text: Correct inaccurate personal information.\n- right: Delete\n  text: Delete your personal information, subject to legal retention requirements.\n- right: Object or restrict\n  text: Object to, or restrict, certain processing.\n- right: Withdraw consent\n  text: Withdraw consent where we rely on it.\n- right: Portability\n  text: Port your personal information to another service in a commonly used format.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal information for money.\n"
source_yaml_url: https://artifacts.apis.io/asvaai-com/privacy/asvaai-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Asva AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- SEO
- Brand Monitoring
- Analytics
---
