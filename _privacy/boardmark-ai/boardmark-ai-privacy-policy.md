---
api_specs:
- filename: boardmark-ai-openapi-generated.yml
  format: yaml
  label: BoardMark API
  slug: boardmark-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boardmark-ai/openapi/_ae-authored/boardmark-ai-openapi-generated.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email address, password (stored only as an irreversible hash), email verification status and language.'
  - category: contact
    text: 'Correspondence and support cases: messages and emails you send us'
  - category: financial
    text: 'Payment data: invoice and payment history, payment references and coupon redemptions'
  - category: device
    text: 'Device notification (web push) data (when you turn it on): the endpoint address and encryption keys your browser issues, a device name (such as the browser and operating system)'
  - category: behavioral
    text: 'Usage and technical data: IP address, browser and device type (user agent), access times, sessions and signed-in devices, sign-in history (including the sign-in method) and failed sign-in attempts'
  - category: communication
    text: 'LINE data (when you link a LINE account in your settings): your LINE user ID, LINE display name'
  deletion:
    route: Account deletion option in account settings or by contacting the Company under section 12
    text: 'Requests to delete data under section 9: once we have verified the request, we delete the data from live systems without undue delay, except data we must keep by law as set out in this section.'
  dpa:
    available: true
    text: A customer company that needs a signed data processing agreement can ask us as described in section 12.
    url: null
  purposes:
  - purpose: Account and service provision
    text: To create and maintain your account, authenticate you, provide the Service you request and send the emails it needs
  - purpose: Security
    text: 'To keep the Service secure, prevent unauthorised access, fraud and spam, limit request rates, investigate anomalies and keep evidence of actions: legitimate interests (section 24(5)).'
  - purpose: Billing
    text: To calculate fees, issue invoices, tax invoices and receipts, collect payment and follow up on payment
  - purpose: Service improvement
    text: 'To operate, troubleshoot and improve the Service and to answer your questions: legitimate interests (section 24(5)).'
  residency:
  - region: Thailand
    text: 'We store and process the Service''s data in Thailand, on Amazon Web Services (AWS) in the Asia Pacific (Thailand) region, Bangkok: the database, files and attachments, and backups.'
  retention:
  - period: 1 year
    scope: Account data and Customer Content
    text: when you delete your account you choose either to keep your data for 1 year so that you can come back (the default), or to delete it permanently now
  - period: 30 days
    scope: Delivery records and notification bell entries
    text: 'Delivery records of emails, LINE messages, Telegram messages, device notifications and webhooks (including the webhook delivery history administrators see) and entries in the notification bell: 30 days.'
  - period: at least 5 years
    scope: Invoices and accounting records
    text: 'Invoices, tax invoices, receipts and supporting accounting and tax records: kept for at least 5 years from the date of issue, or longer where the law requires'
  - period: null
    scope: Support cases
    text: 'Support cases (messages, attachments, diagnostic context and the IP address hash): kept while the customer company that owns the case exists, and no longer than 2 years after the case is closed.'
  - period: 30 days
    scope: Remembered browser
    text: A remembered browser ("remember this device") lasts 30 days.
  rights:
  - right: access
    text: access your personal data and obtain a copy
  - right: portability
    text: receive your data, or have it sent or transferred, in a machine-readable format
  - right: objection
    text: object to the collection, use or disclosure of your data
  - right: erasure
    text: have your data erased, destroyed or anonymised
  - right: restriction
    text: have the use of your data restricted
  - right: correction
    text: have your data corrected so that it is accurate, up to date, complete and not misleading
  - right: withdraw consent
    text: withdraw consent where we rely on consent
  - right: complaint
    text: lodge a complaint with the Office of the Personal Data Protection Committee
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data
  subprocessors:
    text: service providers processing data on our behalf — server and storage hosting, backup storage, email delivery and payment processing (Omise, through the Company's payment gateway)
    url: null
  transfers:
  - mechanism: SCC
    text: We protect transfers of personal data from the EEA to Thailand with the Standard Contractual Clauses adopted by the European Commission (Implementing Decision (EU) 2021/914)
  - mechanism: other
    text: transfers from the United Kingdom with the UK International Data Transfer Addendum to those clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BoardMark
provenance_date: '2026-11-09'
provider_name: BoardMark
provider_slug: boardmark-ai
slug: boardmark-ai-privacy-policy
source_date: '2026-11-09'
source_filename: boardmark-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.boardmark.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BoardMark\naid: boardmark-ai\nurl: https://www.boardmark.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email address, password (stored only as an irreversible hash), email verification status\n    and language.'\n- category: contact\n  text: 'Correspondence and support cases: messages and emails you send us'\n- category: financial\n  text: 'Payment data: invoice and payment history, payment references and coupon redemptions'\n- category: device\n  text: 'Device notification (web push) data (when you\
  \ turn it on): the endpoint address and encryption keys your\n    browser issues, a device name (such as the browser and operating system)'\n- category: behavioral\n  text: 'Usage and technical data: IP address, browser and device type (user agent), access times, sessions and\n    signed-in devices, sign-in history (including the sign-in method) and failed sign-in attempts'\n- category: communication\n  text: 'LINE data (when you link a LINE account in your settings): your LINE user ID, LINE display name'\npurposes:\n- purpose: Account and service provision\n  text: To create and maintain your account, authenticate you, provide the Service you request and send the emails\n    it needs\n- purpose: Security\n  text: 'To keep the Service secure, prevent unauthorised access, fraud and spam, limit request rates, investigate\n    anomalies and keep evidence of actions: legitimate interests (section 24(5)).'\n- purpose: Billing\n  text: To calculate fees, issue invoices, tax invoices and receipts,\
  \ collect payment and follow up on payment\n- purpose: Service improvement\n  text: 'To operate, troubleshoot and improve the Service and to answer your questions: legitimate interests (section\n    24(5)).'\nretention:\n- scope: Account data and Customer Content\n  period: 1 year\n  text: when you delete your account you choose either to keep your data for 1 year so that you can come back (the\n    default), or to delete it permanently now\n- scope: Delivery records and notification bell entries\n  period: 30 days\n  text: 'Delivery records of emails, LINE messages, Telegram messages, device notifications and webhooks (including\n    the webhook delivery history administrators see) and entries in the notification bell: 30 days.'\n- scope: Invoices and accounting records\n  period: at least 5 years\n  text: 'Invoices, tax invoices, receipts and supporting accounting and tax records: kept for at least 5 years from\n    the date of issue, or longer where the law requires'\n- scope: Support\
  \ cases\n  period: null\n  text: 'Support cases (messages, attachments, diagnostic context and the IP address hash): kept while the customer\n    company that owns the case exists, and no longer than 2 years after the case is closed.'\n- scope: Remembered browser\n  period: 30 days\n  text: A remembered browser (\"remember this device\") lasts 30 days.\nresidency:\n- region: Thailand\n  text: 'We store and process the Service''s data in Thailand, on Amazon Web Services (AWS) in the Asia Pacific\n    (Thailand) region, Bangkok: the database, files and attachments, and backups.'\ntransfers:\n- mechanism: SCC\n  text: We protect transfers of personal data from the EEA to Thailand with the Standard Contractual Clauses adopted\n    by the European Commission (Implementing Decision (EU) 2021/914)\n- mechanism: other\n  text: transfers from the United Kingdom with the UK International Data Transfer Addendum to those clauses.\nsubprocessors:\n  url: null\n  text: service providers processing data\
  \ on our behalf — server and storage hosting, backup storage, email delivery\n    and payment processing (Omise, through the Company's payment gateway)\ndpa:\n  available: true\n  url: null\n  text: A customer company that needs a signed data processing agreement can ask us as described in section 12.\ndeletion:\n  route: Account deletion option in account settings or by contacting the Company under section 12\n  text: 'Requests to delete data under section 9: once we have verified the request, we delete the data from live\n    systems without undue delay, except data we must keep by law as set out in this section.'\nrights:\n- right: access\n  text: access your personal data and obtain a copy\n- right: portability\n  text: receive your data, or have it sent or transferred, in a machine-readable format\n- right: objection\n  text: object to the collection, use or disclosure of your data\n- right: erasure\n  text: have your data erased, destroyed or anonymised\n- right: restriction\n  text:\
  \ have the use of your data restricted\n- right: correction\n  text: have your data corrected so that it is accurate, up to date, complete and not misleading\n- right: withdraw consent\n  text: withdraw consent where we rely on consent\n- right: complaint\n  text: lodge a complaint with the Office of the Personal Data Protection Committee\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data\n"
source_yaml_url: https://artifacts.apis.io/boardmark-ai/privacy/boardmark-ai-privacy-policy.yml
stated_fields:
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
summary_line: 30 quoted statements, read from BoardMark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Project Management
- Artificial Intelligence
- Collaboration
---
