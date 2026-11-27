---
api_specs:
- filename: chadwin-companies-api-openapi.yml
  format: yaml
  label: Chadwin Companies API
  slug: chadwin-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-companies-api-openapi.yml
- filename: chadwin-company-kpis-api-openapi.yml
  format: yaml
  label: Chadwin Company KPIs API
  slug: chadwin-company-kpis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-company-kpis-api-openapi.yml
- filename: chadwin-company-reports-api-openapi.yml
  format: yaml
  label: Chadwin Company reports API
  slug: chadwin-company-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-company-reports-api-openapi.yml
- filename: chadwin-current-reports-api-openapi.yml
  format: yaml
  label: Chadwin Current reports API
  slug: chadwin-current-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-current-reports-api-openapi.yml
- filename: chadwin-insider-activity-api-openapi.yml
  format: yaml
  label: Chadwin Insider activity API
  slug: chadwin-insider-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-insider-activity-api-openapi.yml
- filename: chadwin-institutional-holdings-api-openapi.yml
  format: yaml
  label: Chadwin Institutional holdings API
  slug: chadwin-institutional-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-institutional-holdings-api-openapi.yml
- filename: chadwin-normalized-financial-statements-api-openapi.yml
  format: yaml
  label: Chadwin Normalized financial statements API
  slug: chadwin-normalized-financial-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chadwin/openapi/chadwin-normalized-financial-statements-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process your email address, email-verification state, session tokens and expiry, and security information such as IP address and user agent.
  - category: identifying
    text: If you choose Google sign-in, we receive your Google account identifier, email address and verification state, name, profile picture, and authentication tokens.
  - category: financial
    text: We process Stripe customer, checkout, subscription, product, and price identifiers; subscription status and billing periods; and limited webhook and checkout-attempt records.
  - category: device
    text: We store an API key name, prefix, cryptographic digest, creation and revocation state, your plan entitlement, the request count for the current billing period, and the time of the latest request.
  - category: communication
    text: We process your email address and message content when we send authentication or service emails or when you contact support.
  - category: behavioral
    text: PostHog records page views, page leaves, and session replays to help us understand how the product is used.
  deletion:
    route: Contact support@chadwin.co to exercise a right
    text: Contact support@chadwin.co to exercise a right or ask a privacy question.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and security
    text: We use this data to create and secure your account and provide the service under our contract with you.
  - purpose: subscription administration
    text: We use this data to start and administer your subscription, provide paid access, handle billing questions, and meet accounting, tax, and legal obligations.
  - purpose: API operation and quotas
    text: We use these records to authenticate requests, enforce plan quotas, operate the API, and resolve account or usage disputes.
  - purpose: optional product analytics
    text: After you grant measurement consent, Cloudflare Web Analytics measures aggregate traffic and performance without cookies, and PostHog records page views, page leaves, and session replays to help us understand how the product is used.
  retention:
  - period: 10 minutes
    scope: one-time sign-in codes
    text: One-time sign-in codes expire after 10 minutes
  - period: seven days
    scope: Cloudflare Worker logs
    text: Cloudflare Worker logs are retained for seven days
  - period: while your account exists
    scope: account, session, API-key and service state
    text: Account, session, API-key, and service state is kept while your account exists, with limited security records retained longer where needed to prevent abuse or resolve claims
  - period: null
    scope: support correspondence
    text: Support correspondence is kept while needed to resolve the request and any related legal claim
  rights:
  - right: access
    text: you may ask us to give you access to your personal data, correct it, erase it, restrict its use, or provide it in a portable format.
  - right: objection
    text: You may object to processing based on legitimate interests and withdraw consent at any time without affecting processing that was lawful before withdrawal.
  - right: complaint to authority
    text: You may also lodge a complaint with Sweden's data protection authority, Integritetsskyddsmyndigheten (IMY)
  role:
    text: Chadwin AB, organization number 559525-6438, is the data controller.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We use the following providers to operate Chadwin: Cloudflare processes application traffic, Worker logs and traces, and consented Web Analytics Supabase hosts account and application data in Postgres Stripe Managed Payments and Sold through Link provide checkout, billing, fraud prevention, merchant-of-record, subscription management, and transaction-support services.'
    url: null
  transfers:
  - mechanism: adequacy
    text: Where a recipient processes personal data outside the EEA, the transfer is protected by an applicable adequacy decision, the EU-US Data Privacy Framework, or contractual safeguards such as the European Commission's Standard Contractual Clauses.
  - mechanism: DPF
    text: Where a recipient processes personal data outside the EEA, the transfer is protected by an applicable adequacy decision, the EU-US Data Privacy Framework, or contractual safeguards such as the European Commission's Standard Contractual Clauses.
  - mechanism: SCC
    text: Where a recipient processes personal data outside the EEA, the transfer is protected by an applicable adequacy decision, the EU-US Data Privacy Framework, or contractual safeguards such as the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chadwin
provenance_date: '2026-11-09'
provider_name: Chadwin
provider_slug: chadwin
slug: chadwin-privacy-policy
source_date: '2026-11-09'
source_filename: chadwin-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.chadwin.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chadwin\naid: chadwin\nurl: https://www.chadwin.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Chadwin AB, organization number 559525-6438, is the data controller.\ndata_categories:\n- category: identifying\n  text: We process your email address, email-verification state, session tokens and expiry, and security information\n    such as IP address and user agent.\n- category: identifying\n  text: If you choose Google sign-in, we receive your Google account identifier, email address and verification\n    state, name, profile picture, and authentication tokens.\n- category: financial\n\
  \  text: We process Stripe customer, checkout, subscription, product, and price identifiers; subscription status\n    and billing periods; and limited webhook and checkout-attempt records.\n- category: device\n  text: We store an API key name, prefix, cryptographic digest, creation and revocation state, your plan entitlement,\n    the request count for the current billing period, and the time of the latest request.\n- category: communication\n  text: We process your email address and message content when we send authentication or service emails or when\n    you contact support.\n- category: behavioral\n  text: PostHog records page views, page leaves, and session replays to help us understand how the product is used.\npurposes:\n- purpose: account creation and security\n  text: We use this data to create and secure your account and provide the service under our contract with you.\n- purpose: subscription administration\n  text: We use this data to start and administer your subscription,\
  \ provide paid access, handle billing questions,\n    and meet accounting, tax, and legal obligations.\n- purpose: API operation and quotas\n  text: We use these records to authenticate requests, enforce plan quotas, operate the API, and resolve account\n    or usage disputes.\n- purpose: optional product analytics\n  text: After you grant measurement consent, Cloudflare Web Analytics measures aggregate traffic and performance\n    without cookies, and PostHog records page views, page leaves, and session replays to help us understand how\n    the product is used.\nretention:\n- scope: one-time sign-in codes\n  period: 10 minutes\n  text: One-time sign-in codes expire after 10 minutes\n- scope: Cloudflare Worker logs\n  period: seven days\n  text: Cloudflare Worker logs are retained for seven days\n- scope: account, session, API-key and service state\n  period: while your account exists\n  text: Account, session, API-key, and service state is kept while your account exists, with limited\
  \ security records\n    retained longer where needed to prevent abuse or resolve claims\n- scope: support correspondence\n  period: null\n  text: Support correspondence is kept while needed to resolve the request and any related legal claim\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where a recipient processes personal data outside the EEA, the transfer is protected by an applicable adequacy\n    decision, the EU-US Data Privacy Framework, or contractual safeguards such as the European Commission's Standard\n    Contractual Clauses.\n- mechanism: DPF\n  text: Where a recipient processes personal data outside the EEA, the transfer is protected by an applicable adequacy\n    decision, the EU-US Data Privacy Framework, or contractual safeguards such as the European Commission's Standard\n    Contractual Clauses.\n- mechanism: SCC\n  text: Where a recipient processes personal data outside the EEA, the transfer is protected by an applicable adequacy\n    decision, the EU-US\
  \ Data Privacy Framework, or contractual safeguards such as the European Commission's Standard\n    Contractual Clauses.\nsubprocessors:\n  url: null\n  text: 'We use the following providers to operate Chadwin: Cloudflare processes application traffic, Worker logs\n    and traces, and consented Web Analytics Supabase hosts account and application data in Postgres Stripe Managed\n    Payments and Sold through Link provide checkout, billing, fraud prevention, merchant-of-record, subscription\n    management, and transaction-support services.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support@chadwin.co to exercise a right\n  text: Contact support@chadwin.co to exercise a right or ask a privacy question.\nrights:\n- right: access\n  text: you may ask us to give you access to your personal data, correct it, erase it, restrict its use, or provide\n    it in a portable format.\n- right: objection\n  text: You may object to processing based on legitimate\
  \ interests and withdraw consent at any time without affecting\n    processing that was lawful before withdrawal.\n- right: complaint to authority\n  text: You may also lodge a complaint with Sweden's data protection authority, Integritetsskyddsmyndigheten (IMY)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chadwin/privacy/chadwin-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 23 quoted statements, read from Chadwin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Analytics
- Integration
- Enterprise
---
