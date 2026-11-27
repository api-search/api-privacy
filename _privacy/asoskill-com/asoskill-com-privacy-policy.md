---
api_specs:
- filename: asoskill-com-authentication-api-openapi.yml
  format: yaml
  label: asoskill-com Authentication API
  slug: asoskill-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-authentication-api-openapi.yml
- filename: asoskill-com-billing-api-openapi.yml
  format: yaml
  label: asoskill-com Billing API
  slug: asoskill-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-billing-api-openapi.yml
- filename: asoskill-com-credits-api-openapi.yml
  format: yaml
  label: asoskill-com Credits API
  slug: asoskill-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-credits-api-openapi.yml
- filename: asoskill-com-data-api-openapi.yml
  format: yaml
  label: asoskill-com Data API
  slug: asoskill-com-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-data-api-openapi.yml
- filename: asoskill-com-mcp-api-openapi.yml
  format: yaml
  label: asoskill-com MCP API
  slug: asoskill-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-mcp-api-openapi.yml
- filename: asoskill-com-operations-api-openapi.yml
  format: yaml
  label: asoskill-com Operations API
  slug: asoskill-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asoskill-com/openapi/asoskill-com-operations-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process your email address, account identifier, authentication status, account creation and update times, and security-related account events.
  - category: behavioral
    text: PostHog stores a persistent anonymous analytics identifier in first-party cookies and local storage so we can recognize repeat visits
  - category: device
    text: browser and device information, IP address and user agent, coarse location derived from network information
  - category: financial
    text: purchase amount, currency, tax, credits purchased, payment status, receipt or invoice references, and refund information
  - category: communication
    text: If you contact us or exercise a legal right, we process your message, contact details, order reference, and our response.
  deletion:
    route: Email viktor@asosuite.com
    text: You may request account deletion at viktor@asosuite.com . We will remove or anonymize information that is no longer required, revoke active API keys, and explain any information we must retain.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide accounts, API access and support
    text: Create accounts, authenticate users, provide API access, meter credits, supply output, and provide support
  - purpose: Payments and accounting
    text: Take payment, provide invoices, process refunds, and maintain accounting and consumer records
  - purpose: Security and abuse prevention
    text: Protect accounts, prevent abuse, enforce rate limits, troubleshoot, monitor reliability, and defend legal claims
  - purpose: Analytics and advertising measurement
    text: Understand acquisition, website use, account activation, checkout, purchases, and refunds; measure advertising; build advertising audiences; and improve the Service
  residency:
  - region: Sweden
    text: The primary API region is Stockholm, Sweden.
  - region: Germany
    text: PostHog Cloud EU for website, product, funnel, and conversion analytics hosted in Frankfurt, Germany.
  retention:
  - period: while the account is open
    scope: Account profiles and active API keys
    text: Account profiles and active API-key records while the account is open.
  - period: up to seven days
    scope: Meta checkout matching context
    text: Meta checkout matching context in our core database for up to seven days, after which DynamoDB expires it automatically.
  - period: for the period required by applicable law
    scope: Payment, invoice, tax and refund records
    text: Payment, invoice, tax, refund, and accounting records for the period required by applicable law.
  - period: null
    scope: PostHog analytics events
    text: PostHog analytics events according to the configured PostHog retention period and only while useful for product and commercial analysis.
  rights:
  - right: Access, correction, deletion, restriction, portability, objection
    text: GDPR gives you rights to information, access, correction, deletion, restriction, data portability, and objection.
  - right: Withdraw consent
    text: Where processing is based on consent, you may withdraw consent without affecting earlier lawful processing.
  - right: Complaint to supervisory authority
    text: You may lodge a complaint with the Swedish Authority for Privacy Protection (Integritetsskyddsmyndigheten, IMY) at imy.se
  role:
    text: Hesselbom Tech AB , organization number 559450-0372 , of Berguven 8, 436 53 Hovås, Sweden , is the controller for the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: such as an adequacy decision, the EU–US Data Privacy Framework where applicable, or the European Commission’s standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: asoskill-com
provenance_date: '2026-11-09'
provider_name: asoskill-com
provider_slug: asoskill-com
slug: asoskill-com-privacy-policy
source_date: '2026-11-09'
source_filename: asoskill-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.asoskill.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: asoskill-com\naid: asoskill-com\nurl: https://www.asoskill.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Hesselbom Tech AB , organization number 559450-0372 , of Berguven 8, 436 53 Hovås, Sweden , is the controller\n    for the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: We process your email address, account identifier, authentication status, account creation and update times,\n    and security-related account events.\n- category: behavioral\n  text: PostHog stores a persistent anonymous analytics identifier in first-party cookies\
  \ and local storage so we\n    can recognize repeat visits\n- category: device\n  text: browser and device information, IP address and user agent, coarse location derived from network information\n- category: financial\n  text: purchase amount, currency, tax, credits purchased, payment status, receipt or invoice references, and refund\n    information\n- category: communication\n  text: If you contact us or exercise a legal right, we process your message, contact details, order reference,\n    and our response.\npurposes:\n- purpose: Provide accounts, API access and support\n  text: Create accounts, authenticate users, provide API access, meter credits, supply output, and provide support\n- purpose: Payments and accounting\n  text: Take payment, provide invoices, process refunds, and maintain accounting and consumer records\n- purpose: Security and abuse prevention\n  text: Protect accounts, prevent abuse, enforce rate limits, troubleshoot, monitor reliability, and defend legal\n    claims\n\
  - purpose: Analytics and advertising measurement\n  text: Understand acquisition, website use, account activation, checkout, purchases, and refunds; measure advertising;\n    build advertising audiences; and improve the Service\nretention:\n- scope: Account profiles and active API keys\n  period: while the account is open\n  text: Account profiles and active API-key records while the account is open.\n- scope: Meta checkout matching context\n  period: up to seven days\n  text: Meta checkout matching context in our core database for up to seven days, after which DynamoDB expires it\n    automatically.\n- scope: Payment, invoice, tax and refund records\n  period: for the period required by applicable law\n  text: Payment, invoice, tax, refund, and accounting records for the period required by applicable law.\n- scope: PostHog analytics events\n  period: null\n  text: PostHog analytics events according to the configured PostHog retention period and only while useful for\n    product and commercial\
  \ analysis.\nresidency:\n- region: Sweden\n  text: The primary API region is Stockholm, Sweden.\n- region: Germany\n  text: PostHog Cloud EU for website, product, funnel, and conversion analytics hosted in Frankfurt, Germany.\ntransfers:\n- mechanism: adequacy\n  text: such as an adequacy decision, the EU–US Data Privacy Framework where applicable, or the European Commission’s\n    standard contractual clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email viktor@asosuite.com\n  text: You may request account deletion at viktor@asosuite.com . We will remove or anonymize information that is\n    no longer required, revoke active API keys, and explain any information we must retain.\nrights:\n- right: Access, correction, deletion, restriction, portability, objection\n  text: GDPR gives you rights to information, access, correction, deletion, restriction, data portability, and objection.\n- right: Withdraw consent\n\
  \  text: Where processing is based on consent, you may withdraw consent without affecting earlier lawful processing.\n- right: Complaint to supervisory authority\n  text: You may lodge a complaint with the Swedish Authority for Privacy Protection (Integritetsskyddsmyndigheten,\n    IMY) at imy.se\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asoskill-com/privacy/asoskill-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from asoskill-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ASO
- App Store
- Data
---
