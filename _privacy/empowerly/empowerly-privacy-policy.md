---
api_specs:
- filename: empowerly-status-api-openapi.yml
  format: yaml
  label: Empowerly Status API
  slug: empowerly-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-status-api-openapi.yml
- filename: empowerly-components-api-openapi.yml
  format: yaml
  label: Empowerly Components API
  slug: empowerly-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-components-api-openapi.yml
- filename: empowerly-incidents-api-openapi.yml
  format: yaml
  label: Empowerly Incidents API
  slug: empowerly-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-incidents-api-openapi.yml
- filename: empowerly-maintenance-api-openapi.yml
  format: yaml
  label: Empowerly Maintenance API
  slug: empowerly-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empowerly/openapi/empowerly-maintenance-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up for an account, we ask you for your name, email address, phone number, and username.
  - category: demographic
    text: such as your or your parents’ or guardians’ name, address, email address, phone number, age, gender, GPA, test scores, academic interests and activities, household income
  - category: location
    text: For example, we infer your location information by using your IP address.
  - category: device
    text: including IP address, device name and type, device identifiers, operating system, web browser type and version
  - category: behavioral
    text: like the pages or other content you view, referrer information (the website you visited before coming to our Services), the dates and times of your visits
  - category: communication
    text: the contents of a message or attachments that you may send to us
  - category: financial
    text: your payment-related information, such as bank account, routing number, credit card or other financial information, is collected by our third-party payment processor on our behalf
  - category: professional
    text: your contact information, employment-related information, and your resume online
  deletion:
    route: Contact support to close account or have information removed
    text: You can update your account and profile information or close your account by contacting us at support@empowerly.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and customer support
    text: Provide Empowerly Services and customer support you request
  - purpose: Process transactions and payments
    text: Process transactions, payments, and send notices about your transactions
  - purpose: Marketing and advertising
    text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials that may be relevant, valuable, or otherwise of interest to you
  - purpose: Fraud and abuse prevention
    text: To find and prevent fraud and abuse, and respond to trust and safety issues that may arise
  - purpose: Text messages and reminders
    text: send you counseling session and meeting reminders / account notifications / application deadline reminders / promotional offers
  residency:
  - region: United States
    text: Our Services are hosted in the United States and intended for visitors located within the United States.
  retention:
  - period: '[five] years after you opt out'
    scope: SMS opt-in data
    text: for [five] years after you opt out, consistent with our record-keeping obligations
  rights:
  - right: Update or close account
    text: You can update your account and profile information or close your account by contacting us at support@empowerly.com .
  - right: Unsubscribe from promotional email
    text: You can unsubscribe from our promotional emails via the link provided in the emails.
  - right: Opt out of promotional SMS
    text: You can opt out from our promotional SMS messages by replying “STOP” to our message.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: your information may be transferred to, stored and processed in the United States where our servers are located and our databases are operated
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Empowerly
provenance_date: '2026-11-09'
provider_name: Empowerly
provider_slug: empowerly
slug: empowerly-privacy-policy
source_date: '2026-11-09'
source_filename: empowerly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://empowerly.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Empowerly\naid: empowerly\nurl: https://empowerly.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up for an account, we ask you for your name, email address, phone number, and username.\n- category: demographic\n  text: such as your or your parents’ or guardians’ name, address, email address, phone number, age, gender, GPA,\n    test scores, academic interests and activities, household income\n- category: location\n  text: For example, we infer your location information by using your IP address.\n- category:\
  \ device\n  text: including IP address, device name and type, device identifiers, operating system, web browser type and version\n- category: behavioral\n  text: like the pages or other content you view, referrer information (the website you visited before coming to\n    our Services), the dates and times of your visits\n- category: communication\n  text: the contents of a message or attachments that you may send to us\n- category: financial\n  text: your payment-related information, such as bank account, routing number, credit card or other financial information,\n    is collected by our third-party payment processor on our behalf\n- category: professional\n  text: your contact information, employment-related information, and your resume online\npurposes:\n- purpose: Provide services and customer support\n  text: Provide Empowerly Services and customer support you request\n- purpose: Process transactions and payments\n  text: Process transactions, payments, and send notices about your\
  \ transactions\n- purpose: Marketing and advertising\n  text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials\n    that may be relevant, valuable, or otherwise of interest to you\n- purpose: Fraud and abuse prevention\n  text: To find and prevent fraud and abuse, and respond to trust and safety issues that may arise\n- purpose: Text messages and reminders\n  text: send you counseling session and meeting reminders / account notifications / application deadline reminders\n    / promotional offers\nretention:\n- scope: SMS opt-in data\n  period: '[five] years after you opt out'\n  text: for [five] years after you opt out, consistent with our record-keeping obligations\nresidency:\n- region: United States\n  text: Our Services are hosted in the United States and intended for visitors located within the United States.\ntransfers:\n- mechanism: other\n  text: your information may be transferred to, stored and processed in the United\
  \ States where our servers are\n    located and our databases are operated\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support to close account or have information removed\n  text: You can update your account and profile information or close your account by contacting us at support@empowerly.com\n    .\nrights:\n- right: Update or close account\n  text: You can update your account and profile information or close your account by contacting us at support@empowerly.com\n    .\n- right: Unsubscribe from promotional email\n  text: You can unsubscribe from our promotional emails via the link provided in the emails.\n- right: Opt out of promotional SMS\n  text: You can opt out from our promotional SMS messages by replying “STOP” to our message.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/empowerly/privacy/empowerly-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Empowerly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- College Admissions
- Counseling
- Students
- Career Services
- Consumer Services
- Status Pages
---
