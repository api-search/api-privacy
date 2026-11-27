---
api_specs:
- filename: agentaos-ai-bank-accounts-api-openapi.yml
  format: yaml
  label: AgentaOS Bank Accounts API
  slug: agentaos-ai-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-bank-accounts-api-openapi.yml
- filename: agentaos-ai-businesses-api-openapi.yml
  format: yaml
  label: AgentaOS Businesses API
  slug: agentaos-ai-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-businesses-api-openapi.yml
- filename: agentaos-ai-checkouts-api-openapi.yml
  format: yaml
  label: AgentaOS Checkouts API
  slug: agentaos-ai-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-checkouts-api-openapi.yml
- filename: agentaos-ai-customers-api-openapi.yml
  format: yaml
  label: AgentaOS Customers API
  slug: agentaos-ai-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-customers-api-openapi.yml
- filename: agentaos-ai-discount-codes-api-openapi.yml
  format: yaml
  label: AgentaOS Discount Codes API
  slug: agentaos-ai-discount-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-discount-codes-api-openapi.yml
- filename: agentaos-ai-invoices-api-openapi.yml
  format: yaml
  label: AgentaOS Invoices API
  slug: agentaos-ai-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-invoices-api-openapi.yml
- filename: agentaos-ai-payment-links-api-openapi.yml
  format: yaml
  label: AgentaOS Payment Links API
  slug: agentaos-ai-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-payment-links-api-openapi.yml
- filename: agentaos-ai-subscriptions-api-openapi.yml
  format: yaml
  label: AgentaOS Subscriptions API
  slug: agentaos-ai-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-subscriptions-api-openapi.yml
- filename: agentaos-ai-transactions-api-openapi.yml
  format: yaml
  label: AgentaOS Transactions API
  slug: agentaos-ai-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentaos-ai/openapi/agentaos-ai-transactions-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, business details, login credentials, and identity or business-verification (KYC/KYB) documents where required by law.
  - category: financial
    text: Orders, amounts, taxes, refunds, chargebacks, and payout records.
  - category: device
    text: Log data, IP address, device and browser information, and product-analytics events.
  - category: communication
    text: Messages you send us for support or sales, and our replies.
  deletion:
    route: null
    text: We keep personal data only as long as needed for the purpose we collected it, then delete or anonymise it.
  dpa:
    available: true
    text: That processing is governed by our Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide the Service and checkout
    text: Provide the Service; operate the checkout, sales, payouts, tax, and invoicing.
  - purpose: Identity verification and fraud prevention
    text: Verify identity; prevent fraud, money laundering, and abuse; meet tax, accounting, and sanctions obligations.
  - purpose: Product analytics
    text: With your consent, we use PostHog , a product-analytics tool, to understand and improve how the Service is used.
  - purpose: Marketing
    text: Send product or marketing updates. Consent or legitimate interests; you can opt out at any time.
  residency:
  - region: European Union
    text: we have configured it to store and process this data on European Union infrastructure
  retention:
  - period: up to 7 years
    scope: Transaction, tax, invoicing, and accounting records
    text: kept for the period required by tax and accounting law (generally up to 7 years)
  - period: up to 5 years
    scope: KYC/KYB and anti-money-laundering records
    text: kept for the period required by AML law (generally up to 5 years after the end of the relationship)
  - period: null
    scope: Account and merchant data
    text: kept for the life of your account and a reasonable period afterwards
  rights:
  - right: access
    text: you may request access to, rectification , erasure , restriction , or portability of your personal data
  - right: objection
    text: you may object to certain processing or withdraw consent where we rely on it
  - right: complaint
    text: You may also lodge a complaint with your local supervisory authority
  role:
    text: We are the controller for personal data of website visitors and merchants, and for Buyer data we handle as the seller of record
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses, with any supplementary measures required
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentaOS
provenance_date: '2026-11-09'
provider_name: AgentaOS
provider_slug: agentaos-ai
slug: agentaos-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agentaos-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentaos.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentaOS\naid: agentaos-ai\nurl: https://agentaos.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for personal data of website visitors and merchants, and for Buyer data we handle\n    as the seller of record\ndata_categories:\n- category: identifying\n  text: Name, email, business details, login credentials, and identity or business-verification (KYC/KYB) documents\n    where required by law.\n- category: financial\n  text: Orders, amounts, taxes, refunds, chargebacks, and payout records.\n- category: device\n  text: Log data, IP address, device and browser information,\
  \ and product-analytics events.\n- category: communication\n  text: Messages you send us for support or sales, and our replies.\npurposes:\n- purpose: Provide the Service and checkout\n  text: Provide the Service; operate the checkout, sales, payouts, tax, and invoicing.\n- purpose: Identity verification and fraud prevention\n  text: Verify identity; prevent fraud, money laundering, and abuse; meet tax, accounting, and sanctions obligations.\n- purpose: Product analytics\n  text: With your consent, we use PostHog , a product-analytics tool, to understand and improve how the Service\n    is used.\n- purpose: Marketing\n  text: Send product or marketing updates. Consent or legitimate interests; you can opt out at any time.\nretention:\n- scope: Transaction, tax, invoicing, and accounting records\n  period: up to 7 years\n  text: kept for the period required by tax and accounting law (generally up to 7 years)\n- scope: KYC/KYB and anti-money-laundering records\n  period: up to 5 years\n \
  \ text: kept for the period required by AML law (generally up to 5 years after the end of the relationship)\n- scope: Account and merchant data\n  period: null\n  text: kept for the life of your account and a reasonable period afterwards\nresidency:\n- region: European Union\n  text: we have configured it to store and process this data on European Union infrastructure\ntransfers:\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses, with any supplementary measures required\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: That processing is governed by our Data Processing Agreement\ndeletion:\n  route: null\n  text: We keep personal data only as long as needed for the purpose we collected it, then delete or anonymise it.\nrights:\n- right: access\n  text: you may request access to, rectification , erasure , restriction , or portability of your personal data\n- right: objection\n  text: you may object to certain processing\
  \ or withdraw consent where we rely on it\n- right: complaint\n  text: You may also lodge a complaint with your local supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/agentaos-ai/privacy/agentaos-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from AgentaOS's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Billing
- Software-as-a-Service
- Freelancers
- Artificial Intelligence
---
