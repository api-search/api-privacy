---
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and contact information, including name, email address, phone number, login metadata, team membership, role, and support communications.
  - category: financial
    text: Payment and billing records, including Corply Pay checkout, payment, receipt-number, billing-cadence, selected-service, renewal-schedule, invoice, refund, dispute, and bank-return records
  - category: location
    text: Founder and company information, including proposed company names, entity details, addresses, founder names, ownership details
  - category: device
    text: Usage, device, and security information, including IP address, browser type, device identifiers, session data, pages viewed, product events, error logs, authentication events, and anti-abuse signals.
  - category: behavioral
    text: AI and automation workflow inputs and outputs, including prompts, extracted facts, summaries, generated drafts, task state, review notes, and operational decisions needed to provide the service.
  - category: communication
    text: 'Corply Mail: mailbox applicant and USPS Form 1583 details, identity-verification status, mailbox permissions, envelope images, scanned correspondence, sender and recipient details'
  deletion:
    route: Email founders@0lumens.com with the subject line Privacy Request
    text: To delete Google user data, email founders@0lumens.com with the subject line Privacy Request; we delete it within 30 days except where a value you confirmed became part of a signed or filed company record we must retain.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate requested services
    text: Provide, operate, and support the services you request or authorize.
  - purpose: Security and fraud prevention
    text: Authenticate users, administer accounts, manage access, prevent fraud and abuse, debug issues, monitor reliability, and protect security.
  - purpose: Product analytics
    text: Analyze product usage and business performance.
  - purpose: Legal compliance
    text: Comply with legal obligations, enforce our Terms of Use, respond to lawful requests, and protect Corply, users, third parties, and the public.
  residency:
  - region: United States
    text: Corply is operated from the United States and is built for U.S.-connected company workflows.
  retention:
  - period: null
    scope: General information
    text: We retain information for as long as needed to provide Corply, maintain company records and audit trails, comply with legal and tax obligations, resolve disputes, enforce agreements, protect security, and operate our business.
  - period: null
    scope: Google user data - unconfirmed profile suggestions
    text: unconfirmed profile suggestions are kept until you confirm, replace, or remove them, or delete your account.
  - period: 30 days
    scope: Google user data - deletion requests
    text: we delete it within 30 days except where a value you confirmed became part of a signed or filed company record we must retain.
  rights:
  - right: access, correct, delete, export, restrict, object
    text: Depending on where you live, you may have rights to access, correct, delete, export, or restrict certain personal information, or to object to certain processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information. We also do not share personal information for cross-context behavioral advertising as those terms are commonly used under U.S. state privacy laws.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Stripe, Finix and Payabli process payment information under their own terms and privacy policies and may process it in the United States and other jurisdictions where they or their providers operate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Corply
provenance_date: '2026-11-09'
provider_name: Corply
provider_slug: corply-dev
slug: corply-dev-privacy-policy
source_date: '2026-11-09'
source_filename: corply-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corply.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Corply\naid: corply-dev\nurl: https://corply.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and contact information, including name, email address, phone number, login metadata, team membership,\n    role, and support communications.\n- category: financial\n  text: Payment and billing records, including Corply Pay checkout, payment, receipt-number, billing-cadence, selected-service,\n    renewal-schedule, invoice, refund, dispute, and bank-return records\n- category: location\n  text: Founder and company information,\
  \ including proposed company names, entity details, addresses, founder names,\n    ownership details\n- category: device\n  text: Usage, device, and security information, including IP address, browser type, device identifiers, session\n    data, pages viewed, product events, error logs, authentication events, and anti-abuse signals.\n- category: behavioral\n  text: AI and automation workflow inputs and outputs, including prompts, extracted facts, summaries, generated\n    drafts, task state, review notes, and operational decisions needed to provide the service.\n- category: communication\n  text: 'Corply Mail: mailbox applicant and USPS Form 1583 details, identity-verification status, mailbox permissions,\n    envelope images, scanned correspondence, sender and recipient details'\npurposes:\n- purpose: Provide and operate requested services\n  text: Provide, operate, and support the services you request or authorize.\n- purpose: Security and fraud prevention\n  text: Authenticate users,\
  \ administer accounts, manage access, prevent fraud and abuse, debug issues, monitor reliability,\n    and protect security.\n- purpose: Product analytics\n  text: Analyze product usage and business performance.\n- purpose: Legal compliance\n  text: Comply with legal obligations, enforce our Terms of Use, respond to lawful requests, and protect Corply,\n    users, third parties, and the public.\nretention:\n- scope: General information\n  period: null\n  text: We retain information for as long as needed to provide Corply, maintain company records and audit trails,\n    comply with legal and tax obligations, resolve disputes, enforce agreements, protect security, and operate our\n    business.\n- scope: Google user data - unconfirmed profile suggestions\n  period: null\n  text: unconfirmed profile suggestions are kept until you confirm, replace, or remove them, or delete your account.\n- scope: Google user data - deletion requests\n  period: 30 days\n  text: we delete it within 30 days\
  \ except where a value you confirmed became part of a signed or filed company\n    record we must retain.\nresidency:\n- region: United States\n  text: Corply is operated from the United States and is built for U.S.-connected company workflows.\ntransfers:\n- mechanism: other\n  text: Stripe, Finix and Payabli process payment information under their own terms and privacy policies and may\n    process it in the United States and other jurisdictions where they or their providers operate.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email founders@0lumens.com with the subject line Privacy Request\n  text: To delete Google user data, email founders@0lumens.com with the subject line Privacy Request; we delete\n    it within 30 days except where a value you confirmed became part of a signed or filed company record we must\n    retain.\nrights:\n- right: access, correct, delete, export, restrict, object\n  text: Depending\
  \ on where you live, you may have rights to access, correct, delete, export, or restrict certain\n    personal information, or to object to certain processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information. We also do not share personal information for cross-context behavioral\n    advertising as those terms are commonly used under U.S. state privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/corply-dev/privacy/corply-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Corply's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Formation
- Incorporation
- Delaware C-Corp
- Legal Tech
- AI Agents
- MCP
- Startups
---
