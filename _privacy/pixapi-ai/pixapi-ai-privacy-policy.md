---
api_specs:
- filename: pixapi-ai-openapi-generated.yml
  format: yaml
  label: pixapi-ai API
  slug: pixapi-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixapi-ai/openapi/_ae-authored/pixapi-ai-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, name, profile image, user ID, email verification status, password authentication data, and password reset activity.
  - category: contact
    text: Email address, name, profile image, user ID, email verification status, password authentication data, and password reset activity.
  - category: financial
    text: We store credit balance records, credit grants and consumption records, reward claims, order records, subscription records, checkout session identifiers, provider names, transaction metadata, plan names, product names, currency, amounts, and related accounting fields.
  - category: location
    text: Session, security, locale, IP, referral, and campaign metadata when available in the active database schema.
  - category: behavioral
    text: Usage records associated with your account or API key so you can review consumption and so Pixapi can maintain billing and abuse-prevention records.
  - category: device
    text: We may collect IP address, user agent, browser and device data, request logs, rate-limit signals, error logs, performance data, cookies, local storage, and analytics events.
  - category: communication
    text: If you open a support ticket, we store the ticket title, message content, attachments, status, replies, timestamps, and the account associated with the ticket.
  - category: other
    text: API endpoint, model ID, request parameters, prompts, messages, input asset URLs, files, or other payload fields that you intentionally submit to a supported model.
  deletion:
    route: Email privacy@pixapi.ai to request deletion
    text: To request access, correction, deletion, or other privacy assistance, contact us at privacy@pixapi.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and secure accounts and sessions
    text: Provide, authenticate, secure, and maintain Pixapi accounts and sessions.
  - purpose: Route API requests to upstream model providers
    text: Route API requests to supported upstream model providers and return normalized responses.
  - purpose: Usage tracking and billing
    text: Track model usage, calculate credit consumption, maintain usage history, and enforce plan limits or rate limits.
  - purpose: Fraud and abuse prevention
    text: Prevent fraud, abuse, spam, unauthorized access, credit bypass, service misuse, and security incidents.
  - purpose: Product improvement and analytics
    text: Debug errors, improve reliability, measure product usage, and understand aggregate product performance.
  retention:
  - period: null
    scope: Account records
    text: Account records are generally retained while your account remains active.
  - period: null
    scope: Credit, order, subscription, reward, and payment records
    text: Credit, order, subscription, reward, and payment records may be retained for accounting, fraud prevention, tax, and compliance purposes.
  - period: null
    scope: Security logs, rate-limit data, and diagnostic logs
    text: Security logs, rate-limit data, and diagnostic logs are retained for a period appropriate to protect and operate the Service.
  rights:
  - right: access
    text: Depending on your location, you may have rights to access, correct, export, restrict, object to, or delete personal information.
  - right: correction
    text: Depending on your location, you may have rights to access, correct, export, restrict, object to, or delete personal information.
  - right: deletion
    text: Depending on your location, you may have rights to access, correct, export, restrict, object to, or delete personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pixapi-ai
provenance_date: '2026-11-10'
provider_name: pixapi-ai
provider_slug: pixapi-ai
slug: pixapi-ai-privacy-policy
source_date: '2026-11-10'
source_filename: pixapi-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pixapi.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pixapi-ai\naid: pixapi-ai\nurl: https://pixapi.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, name, profile image, user ID, email verification status, password authentication data, and\n    password reset activity.\n- category: contact\n  text: Email address, name, profile image, user ID, email verification status, password authentication data, and\n    password reset activity.\n- category: financial\n  text: We store credit balance records, credit grants and consumption records, reward claims, order records,\
  \ subscription\n    records, checkout session identifiers, provider names, transaction metadata, plan names, product names, currency,\n    amounts, and related accounting fields.\n- category: location\n  text: Session, security, locale, IP, referral, and campaign metadata when available in the active database schema.\n- category: behavioral\n  text: Usage records associated with your account or API key so you can review consumption and so Pixapi can maintain\n    billing and abuse-prevention records.\n- category: device\n  text: We may collect IP address, user agent, browser and device data, request logs, rate-limit signals, error\n    logs, performance data, cookies, local storage, and analytics events.\n- category: communication\n  text: If you open a support ticket, we store the ticket title, message content, attachments, status, replies,\n    timestamps, and the account associated with the ticket.\n- category: other\n  text: API endpoint, model ID, request parameters, prompts, messages,\
  \ input asset URLs, files, or other payload\n    fields that you intentionally submit to a supported model.\npurposes:\n- purpose: Provide and secure accounts and sessions\n  text: Provide, authenticate, secure, and maintain Pixapi accounts and sessions.\n- purpose: Route API requests to upstream model providers\n  text: Route API requests to supported upstream model providers and return normalized responses.\n- purpose: Usage tracking and billing\n  text: Track model usage, calculate credit consumption, maintain usage history, and enforce plan limits or rate\n    limits.\n- purpose: Fraud and abuse prevention\n  text: Prevent fraud, abuse, spam, unauthorized access, credit bypass, service misuse, and security incidents.\n- purpose: Product improvement and analytics\n  text: Debug errors, improve reliability, measure product usage, and understand aggregate product performance.\nretention:\n- scope: Account records\n  period: null\n  text: Account records are generally retained while your\
  \ account remains active.\n- scope: Credit, order, subscription, reward, and payment records\n  period: null\n  text: Credit, order, subscription, reward, and payment records may be retained for accounting, fraud prevention,\n    tax, and compliance purposes.\n- scope: Security logs, rate-limit data, and diagnostic logs\n  period: null\n  text: Security logs, rate-limit data, and diagnostic logs are retained for a period appropriate to protect and\n    operate the Service.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@pixapi.ai to request deletion\n  text: To request access, correction, deletion, or other privacy assistance, contact us at privacy@pixapi.ai .\nrights:\n- right: access\n  text: Depending on your location, you may have rights to access, correct, export, restrict, object to, or delete\n    personal information.\n- right: correction\n  text: Depending on your location,\
  \ you may have rights to access, correct, export, restrict, object to, or delete\n    personal information.\n- right: deletion\n  text: Depending on your location, you may have rights to access, correct, export, restrict, object to, or delete\n    personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/pixapi-ai/privacy/pixapi-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from pixapi-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Machine Learning
---
