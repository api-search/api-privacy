---
api_specs:
- filename: banzai-events-api-openapi.yml
  format: yaml
  label: Banzai Events API
  slug: banzai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/banzai/openapi/banzai-events-api-openapi.yml
- filename: banzai-intro-api-openapi.yml
  format: yaml
  label: Banzai Intro API
  slug: banzai-intro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/banzai/openapi/banzai-intro-api-openapi.yml
- filename: banzai-reports-api-openapi.yml
  format: yaml
  label: Banzai Reports API
  slug: banzai-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/banzai/openapi/banzai-reports-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Data about you, your account and profile, including first and last name, email address, phone number, company name, job title, profile picture, preferences
  - category: financial
    text: Data about your payments and transactions. For online payments, this includes payment method, including last four digits if you paid by card
  - category: device
    text: Data about the device you use, and analytical data related to your use of our website and Services, including IP address, geographical location, login data, browser ID
  - category: behavioral
    text: 'Marketing data : Data about your marketing preferences, like newsletter subscriptions, attended events and downloads you have made.'
  - category: communication
    text: we process your name, contact details, and other information you choose to send to us (like the content of your message)
  deletion:
    route: Banzai Privacy Request form or contact privacy@banzai.io
    text: You can request to have your information deleted by filling out the Banzai Privacy Request form.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to inquiries and manage business
    text: The purposes are to be able to respond to your inquiries, manage our business efficiently
  - purpose: Fulfil contractual obligations and deliver services
    text: to fulfil our contractual obligations, to deliver the Services you have requested and to process transactions
  - purpose: Conduct research and analytics
    text: We use personal data to identify and analyze how individuals use our Services, and conduct research and analytics on our customer and user base and our Services.
  - purpose: Prevent fraud
    text: We use personal data to prevent, investigate or provide notice of fraud or unlawful or criminal activity.
  - purpose: Interest-based advertising
    text: We participate in interest-based advertising and use third party advertising companies to serve you targeted advertisements based on your browsing history.
  - purpose: Cloud service provider
    source: https://www.banzai.io/legal/subprocessors
    text: Amazon Web Services Cloud Service Provider United States
  - purpose: Marketing platform
    source: https://www.banzai.io/legal/subprocessors
    text: Hubspot, Inc. Marketing Platform United States
  - purpose: Billing / payments
    source: https://www.banzai.io/legal/subprocessors
    text: Stripe Billing / Payments United States
  - purpose: Outbound email service
    source: https://www.banzai.io/legal/subprocessors
    text: Sendgrid Outbound Email Service United States
  residency:
  - region: United States
    source: https://www.banzai.io/legal/subprocessors
    text: ProfitWell Financial Operations Platform United States
  retention:
  - period: null
    scope: Potential customers
    text: We keep your personal data for as long as we believe you are a potential customer, and then for a reasonable time after in case you decide to become a customer
  - period: seven years
    scope: Business records
    text: we are required by national law to store business records (which may include personal data) for seven years for accounting, tax and other business purposes
  - period: three years
    scope: Unsuccessful job applicants
    text: otherwise the information will be deleted within three years after your application was processed
  rights:
  - right: Access and rectification
    text: You can request access to or a copy of the information we process about you and ask us to update any incorrect data.
  - right: Erasure, restriction and objection
    text: In certain circumstances, you may ask us to delete, or restrict or object to our processing of your personal data.
  - right: Data portability
    text: Where processing is based on either your consent or a contract, you may ask us to transmit your personal data in a structured, commonly used and machine-readable format
  - right: Withdraw consent
    text: Where the processing of your personal data is based on your consent, you are entitled to withdraw this consent at any time.
  - right: Complaints
    text: you can lodge a complaint to the competent data protection authority .
  role:
    text: This Policy only applies to the processing of personal data we conduct in our role as a Controller
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: If you would like to know more about our processors and whom we share your personal data with, please contact us using the contact details provided at the top of this Policy.
    url: null
  transfers:
  - mechanism: SCC
    text: Banzai relies on the Standard Contractual Clauses ("SCCs"), as adopted by the European Commission, and the UK Addendum to the EU SCCs, where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Banzai
provenance_date: '2026-11-09'
provider_name: Banzai
provider_slug: banzai
slug: banzai-privacy-policy
source_date: '2026-11-09'
source_filename: banzai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.banzai.io/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Banzai\naid: banzai\nurl: https://www.banzai.io/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.banzai.io/legal/privacy-policy\n  - https://www.banzai.io/legal/subprocessors\nrole:\n  value: both\n  text: This Policy only applies to the processing of personal data we conduct in our role as a Controller\ndata_categories:\n- category: identifying\n  text: Data about you, your account and profile, including first and last name, email address, phone number, company\n    name, job title, profile picture, preferences\n- category: financial\n  text: Data about your payments and transactions.\
  \ For online payments, this includes payment method, including\n    last four digits if you paid by card\n- category: device\n  text: Data about the device you use, and analytical data related to your use of our website and Services, including\n    IP address, geographical location, login data, browser ID\n- category: behavioral\n  text: 'Marketing data : Data about your marketing preferences, like newsletter subscriptions, attended events\n    and downloads you have made.'\n- category: communication\n  text: we process your name, contact details, and other information you choose to send to us (like the content\n    of your message)\npurposes:\n- purpose: Respond to inquiries and manage business\n  text: The purposes are to be able to respond to your inquiries, manage our business efficiently\n- purpose: Fulfil contractual obligations and deliver services\n  text: to fulfil our contractual obligations, to deliver the Services you have requested and to process transactions\n- purpose: Conduct\
  \ research and analytics\n  text: We use personal data to identify and analyze how individuals use our Services, and conduct research and\n    analytics on our customer and user base and our Services.\n- purpose: Prevent fraud\n  text: We use personal data to prevent, investigate or provide notice of fraud or unlawful or criminal activity.\n- purpose: Interest-based advertising\n  text: We participate in interest-based advertising and use third party advertising companies to serve you targeted\n    advertisements based on your browsing history.\n- purpose: Cloud service provider\n  text: Amazon Web Services Cloud Service Provider United States\n  source: https://www.banzai.io/legal/subprocessors\n- purpose: Marketing platform\n  text: Hubspot, Inc. Marketing Platform United States\n  source: https://www.banzai.io/legal/subprocessors\n- purpose: Billing / payments\n  text: Stripe Billing / Payments United States\n  source: https://www.banzai.io/legal/subprocessors\n- purpose: Outbound email\
  \ service\n  text: Sendgrid Outbound Email Service United States\n  source: https://www.banzai.io/legal/subprocessors\nretention:\n- scope: Potential customers\n  period: null\n  text: We keep your personal data for as long as we believe you are a potential customer, and then for a reasonable\n    time after in case you decide to become a customer\n- scope: Business records\n  period: seven years\n  text: we are required by national law to store business records (which may include personal data) for seven years\n    for accounting, tax and other business purposes\n- scope: Unsuccessful job applicants\n  period: three years\n  text: otherwise the information will be deleted within three years after your application was processed\nresidency:\n- region: United States\n  text: ProfitWell Financial Operations Platform United States\n  source: https://www.banzai.io/legal/subprocessors\ntransfers:\n- mechanism: SCC\n  text: Banzai relies on the Standard Contractual Clauses (\"SCCs\"), as adopted\
  \ by the European Commission, and the\n    UK Addendum to the EU SCCs, where applicable.\nsubprocessors:\n  url: null\n  text: If you would like to know more about our processors and whom we share your personal data with, please contact\n    us using the contact details provided at the top of this Policy.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Banzai Privacy Request form or contact privacy@banzai.io\n  text: You can request to have your information deleted by filling out the Banzai Privacy Request form.\nrights:\n- right: Access and rectification\n  text: You can request access to or a copy of the information we process about you and ask us to update any incorrect\n    data.\n- right: Erasure, restriction and objection\n  text: In certain circumstances, you may ask us to delete, or restrict or object to our processing of your personal\n    data.\n- right: Data portability\n  text: Where processing is based on either your consent or a contract, you may\
  \ ask us to transmit your personal\n    data in a structured, commonly used and machine-readable format\n- right: Withdraw consent\n  text: Where the processing of your personal data is based on your consent, you are entitled to withdraw this consent\n    at any time.\n- right: Complaints\n  text: you can lodge a complaint to the competent data protection authority .\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/banzai/privacy/banzai-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Banzai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Marketing Technology
- Event Management
- Webinars
- Video
- Engagement Marketing
- Demand Generation
- Software-as-a-Service
---
