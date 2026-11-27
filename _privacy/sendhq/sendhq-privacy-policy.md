---
api_specs:
- filename: sendhq-account-and-billing-api-openapi.yml
  format: yaml
  label: SendHQ Account and billing API
  slug: sendhq-account-and-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-account-and-billing-api-openapi.yml
- filename: sendhq-deliverability-api-openapi.yml
  format: yaml
  label: SendHQ Deliverability API
  slug: sendhq-deliverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-deliverability-api-openapi.yml
- filename: sendhq-domains-api-openapi.yml
  format: yaml
  label: SendHQ Domains API
  slug: sendhq-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-domains-api-openapi.yml
- filename: sendhq-drafts-and-attachments-api-openapi.yml
  format: yaml
  label: SendHQ Drafts and attachments API
  slug: sendhq-drafts-and-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-drafts-and-attachments-api-openapi.yml
- filename: sendhq-emails-and-threads-api-openapi.yml
  format: yaml
  label: SendHQ Emails and threads API
  slug: sendhq-emails-and-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-emails-and-threads-api-openapi.yml
- filename: sendhq-hosted-templates-api-openapi.yml
  format: yaml
  label: SendHQ Hosted templates API
  slug: sendhq-hosted-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-hosted-templates-api-openapi.yml
- filename: sendhq-inbound-email-api-openapi.yml
  format: yaml
  label: SendHQ Inbound email API
  slug: sendhq-inbound-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhq/openapi/sendhq-inbound-email-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, and password (stored as a salted hash) when you create an account
  - category: contact
    text: the reply email, query, category, and optional attachment you submit through our contact form
  - category: device
    text: your device, operating system, browser (including whether it is an in-app browser such as Facebook's or Instagram's), and preferred language
  - category: location
    text: the approximate location derived from it (country, region, city, time zone and network provider)
  - category: behavioral
    text: we collect page views, button and link clicks, scroll depth, sections viewed, errors, acquisition attribution
  - category: communication
    text: Email metadata — sender, recipient, subject, and status of messages sent and received through the Service.
  deletion:
    route: contact us
    text: You may request deletion of your account and associated data by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and improve the Service
    text: We use the information above to operate and improve the Service, to send and receive email on your behalf, to enforce usage limits, to detect abuse, and to provide support.
  - purpose: advertising measurement
    text: to measure which ads lead to signups and purchases
  retention:
  - period: null
    scope: account and email data
    text: We retain account and email data for as long as your account is active.
  rights:
  - right: access, correct, export, or delete
    text: you may have the right to access, correct, export, or delete your personal data, and to object to or restrict certain processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: We share data with subprocessors strictly to provide and improve the Service — for example, a mail transport provider (such as Amazon SES) to deliver email, infrastructure providers to host the platform, and a product-analytics provider (PostHog)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SendHQ
provenance_date: '2026-11-10'
provider_name: SendHQ
provider_slug: sendhq
slug: sendhq-privacy-policy
source_date: '2026-11-10'
source_filename: sendhq-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sendhq.cc/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SendHQ\naid: sendhq\nurl: https://sendhq.cc/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, email address, and password (stored as a salted hash) when you create an account\n- category: contact\n  text: the reply email, query, category, and optional attachment you submit through our contact form\n- category: device\n  text: your device, operating system, browser (including whether it is an in-app browser such as Facebook's or\n    Instagram's), and preferred language\n- category: location\n  text: the approximate location\
  \ derived from it (country, region, city, time zone and network provider)\n- category: behavioral\n  text: we collect page views, button and link clicks, scroll depth, sections viewed, errors, acquisition attribution\n- category: communication\n  text: Email metadata — sender, recipient, subject, and status of messages sent and received through the Service.\npurposes:\n- purpose: operate and improve the Service\n  text: We use the information above to operate and improve the Service, to send and receive email on your behalf,\n    to enforce usage limits, to detect abuse, and to provide support.\n- purpose: advertising measurement\n  text: to measure which ads lead to signups and purchases\nretention:\n- scope: account and email data\n  period: null\n  text: We retain account and email data for as long as your account is active.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We share data with subprocessors strictly to provide and improve the Service — for example,\
  \ a mail transport\n    provider (such as Amazon SES) to deliver email, infrastructure providers to host the platform, and a product-analytics\n    provider (PostHog)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us\n  text: You may request deletion of your account and associated data by contacting us.\nrights:\n- right: access, correct, export, or delete\n  text: you may have the right to access, correct, export, or delete your personal data, and to object to or restrict\n    certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/sendhq/privacy/sendhq-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from SendHQ's own page on 2026-11-10.
synthetic: false
tags:
- Email API
- Transactional Email
- Inbound Email
- Deliverability
---
