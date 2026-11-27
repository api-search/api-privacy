---
api_specs:
- filename: zephyr-cloud-content-api-openapi.yml
  format: yaml
  label: Zephyr Cloud Content API
  slug: zephyr-cloud-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zephyr-cloud/openapi/zephyr-cloud-content-api-openapi.yml
- filename: zephyr-cloud-discovery-api-openapi.yml
  format: yaml
  label: Zephyr Cloud Discovery API
  slug: zephyr-cloud-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zephyr-cloud/openapi/zephyr-cloud-discovery-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, username, user ID, and sign-in details
  - category: contact
    text: 'Support email: what you write to us, your contact details, and the conversation history, to answer you.'
  - category: financial
    text: Billing and subscription details, to charge for paid plans and keep tax and accounting records.
  - category: location
    text: approximate location, and device and browser details
  - category: behavioral
    text: pages viewed, clicks, referrer
  - category: device
    text: IP address, time, requested URL, response status, and error details
  - category: communication
    text: 'Support email: what you write to us, your contact details, and the conversation history, to answer you.'
  deletion:
    route: email support@zephyr-cloud.io
    text: Depending on where you live, you can ask to access, correct, delete, or receive a copy of your personal information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and platform operation
    text: Your name, email address, username, user ID, and sign-in details, to create your account, authenticate you, and contact you about the services.
  - purpose: deployment authorship and security
    text: To detect stolen or shared credentials and abuse.
  - purpose: website analytics
    text: 'Product analytics on our website through PostHog: pages viewed, clicks, referrer, approximate location, and device and browser details, to understand how the website is used.'
  residency:
  - region: United States
    text: We are based in the United States and our providers operate around the world, so your information may be processed outside your country.
  retention:
  - period: 10 minutes
    scope: sign-in requests and consent screens
    text: 'Sign-in requests and consent screens for connecting an assistant: 10 minutes.'
  - period: up to 1 hour
    scope: assistant access tokens
    text: 'Assistant access tokens: up to 1 hour.'
  - period: up to 30 days
    scope: operational logs
    text: 'Operational logs: up to 30 days.'
  - period: up to 24 months
    scope: website analytics and connector usage events
    text: 'Website analytics and connector usage events: up to 24 months.'
  - period: typically up to 10 years
    scope: billing records
    text: 'Billing records: as long as tax and accounting laws require, typically up to 10 years.'
  rights:
  - right: access, correct, delete, copy
    text: Depending on where you live, you can ask to access, correct, delete, or receive a copy of your personal information, restrict or object to how we use it, and withdraw consent.
  - right: opt out of analytics
    text: Opt out of website analytics with your browser’s cookie or tracking-protection settings.
  role:
    text: For that information we act as your service provider (a “processor”), and your own privacy notice applies to your visitors.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or share it for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we use safeguards the law recognizes, such as the European Commission’s Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zephyr Cloud
provenance_date: '2026-11-10'
provider_name: Zephyr Cloud
provider_slug: zephyr-cloud
slug: zephyr-cloud-privacy-policy
source_date: '2026-11-10'
source_filename: zephyr-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zephyr-cloud.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zephyr Cloud\naid: zephyr-cloud\nurl: https://zephyr-cloud.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For that information we act as your service provider (a “processor”), and your own privacy notice applies\n    to your visitors.\ndata_categories:\n- category: identifying\n  text: Your name, email address, username, user ID, and sign-in details\n- category: contact\n  text: 'Support email: what you write to us, your contact details, and the conversation history, to answer you.'\n- category: financial\n  text: Billing and subscription details, to charge for paid plans and keep tax\
  \ and accounting records.\n- category: location\n  text: approximate location, and device and browser details\n- category: behavioral\n  text: pages viewed, clicks, referrer\n- category: device\n  text: IP address, time, requested URL, response status, and error details\n- category: communication\n  text: 'Support email: what you write to us, your contact details, and the conversation history, to answer you.'\npurposes:\n- purpose: account and platform operation\n  text: Your name, email address, username, user ID, and sign-in details, to create your account, authenticate you,\n    and contact you about the services.\n- purpose: deployment authorship and security\n  text: To detect stolen or shared credentials and abuse.\n- purpose: website analytics\n  text: 'Product analytics on our website through PostHog: pages viewed, clicks, referrer, approximate location,\n    and device and browser details, to understand how the website is used.'\nretention:\n- scope: sign-in requests and consent\
  \ screens\n  period: 10 minutes\n  text: 'Sign-in requests and consent screens for connecting an assistant: 10 minutes.'\n- scope: assistant access tokens\n  period: up to 1 hour\n  text: 'Assistant access tokens: up to 1 hour.'\n- scope: operational logs\n  period: up to 30 days\n  text: 'Operational logs: up to 30 days.'\n- scope: website analytics and connector usage events\n  period: up to 24 months\n  text: 'Website analytics and connector usage events: up to 24 months.'\n- scope: billing records\n  period: typically up to 10 years\n  text: 'Billing records: as long as tax and accounting laws require, typically up to 10 years.'\nresidency:\n- region: United States\n  text: We are based in the United States and our providers operate around the world, so your information may be\n    processed outside your country.\ntransfers:\n- mechanism: SCC\n  text: we use safeguards the law recognizes, such as the European Commission’s Standard Contractual Clauses.\nsubprocessors:\n  url: null\n\
  \  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@zephyr-cloud.io\n  text: Depending on where you live, you can ask to access, correct, delete, or receive a copy of your personal\n    information\nrights:\n- right: access, correct, delete, copy\n  text: Depending on where you live, you can ask to access, correct, delete, or receive a copy of your personal\n    information, restrict or object to how we use it, and withdraw consent.\n- right: opt out of analytics\n  text: Opt out of website analytics with your browser’s cookie or tracking-protection settings.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/zephyr-cloud/privacy/zephyr-cloud-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Zephyr Cloud's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Deployment
- DevOps
- Platform
---
