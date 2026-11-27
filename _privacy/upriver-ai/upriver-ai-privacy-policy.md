---
api_specs:
- filename: upriver-ai-account-api-openapi.yml
  format: yaml
  label: upriver-ai Account API
  slug: upriver-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-account-api-openapi.yml
- filename: upriver-ai-audience-api-openapi.yml
  format: yaml
  label: upriver-ai Audience API
  slug: upriver-ai-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-audience-api-openapi.yml
- filename: upriver-ai-brands-api-openapi.yml
  format: yaml
  label: upriver-ai Brands API
  slug: upriver-ai-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-brands-api-openapi.yml
- filename: upriver-ai-breakout-feeds-api-openapi.yml
  format: yaml
  label: upriver-ai Breakout Feeds API
  slug: upriver-ai-breakout-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-breakout-feeds-api-openapi.yml
- filename: upriver-ai-breakout-topics-api-openapi.yml
  format: yaml
  label: upriver-ai Breakout Topics API
  slug: upriver-ai-breakout-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-breakout-topics-api-openapi.yml
- filename: upriver-ai-creators-api-openapi.yml
  format: yaml
  label: upriver-ai Creators API
  slug: upriver-ai-creators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-creators-api-openapi.yml
- filename: upriver-ai-images-api-openapi.yml
  format: yaml
  label: upriver-ai Images API
  slug: upriver-ai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-images-api-openapi.yml
- filename: upriver-ai-products-api-openapi.yml
  format: yaml
  label: upriver-ai Products API
  slug: upriver-ai-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-products-api-openapi.yml
- filename: upriver-ai-sponsorships-api-openapi.yml
  format: yaml
  label: upriver-ai Sponsorships API
  slug: upriver-ai-sponsorships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-sponsorships-api-openapi.yml
- filename: upriver-ai-taxonomy-api-openapi.yml
  format: yaml
  label: upriver-ai Taxonomy API
  slug: upriver-ai-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-taxonomy-api-openapi.yml
- filename: upriver-ai-trends-api-openapi.yml
  format: yaml
  label: upriver-ai Trends API
  slug: upriver-ai-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-trends-api-openapi.yml
- filename: upriver-ai-trends-radar-beta-api-openapi.yml
  format: yaml
  label: upriver-ai Trends Radar (Beta) API
  slug: upriver-ai-trends-radar-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upriver-ai/openapi/upriver-ai-trends-radar-beta-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identifiers: name, email address, IP address, and similar identifiers.'
  - category: professional
    text: 'Professional Information: role, company name, and other business-related details you choose to provide.'
  - category: financial
    text: 'Billing Information: limited billing details necessary to manage subscriptions and payments.'
  - category: communication
    text: 'Support & Communications: information you share when you contact us, including inquiries, feedback, and other communications.'
  - category: behavioral
    text: 'Usage Data: information about how you interact with our API, dashboard, and website—such as request activity, feature usage, performance metrics, and analytics.'
  deletion:
    route: Upon request or account closure, or by email to support@upriver.ai
    text: Upon request or account closure, we will delete or return customer data unless legally required to retain it.
  dpa:
    available: true
    text: A Data Processing Agreement (DPA) consistent with Article 28 of the GDPR is available on request.
    url: null
  purposes:
  - purpose: Provide the services
    text: 'Provide the Services: authenticate users, operate APIs, process payments, manage accounts, and deliver customer support.'
  - purpose: Improve and secure
    text: 'Improve and secure: monitor performance, debug, develop new features, prevent abuse, and maintain logs.'
  residency:
  - region: United States
    text: We’re based in the United States and may use service providers in other countries.
  retention:
  - period: 30 days
    scope: Account closure or deletion request
    text: we delete or anonymize personal data within 30 days
  rights:
  - right: Access, correct, or delete
    text: Access, correct, or delete personal data.
  - right: Restrict or object to processing
    text: Restrict or object to processing.
  - right: Data portability
    text: Request data portability.
  - right: Opt out of sale or sharing
    text: Opt out of sale or sharing (we don’t sell data).
  role:
    text: we act as your data processor
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or share it for third-party advertising.
  subprocessors:
    text: A current list of our sub-processors is available upon request at support@upriver.ai
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on Standard Contractual Clauses (SCCs) or other appropriate safeguards under applicable data-protection laws
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: upriver-ai
provenance_date: '2026-11-10'
provider_name: upriver-ai
provider_slug: upriver-ai
slug: upriver-ai-privacy-policy
source_date: '2026-11-10'
source_filename: upriver-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://upriver.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: upriver-ai\naid: upriver-ai\nurl: https://upriver.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: we act as your data processor\ndata_categories:\n- category: identifying\n  text: 'Identifiers: name, email address, IP address, and similar identifiers.'\n- category: professional\n  text: 'Professional Information: role, company name, and other business-related details you choose to provide.'\n- category: financial\n  text: 'Billing Information: limited billing details necessary to manage subscriptions and payments.'\n- category: communication\n  text: 'Support & Communications: information\
  \ you share when you contact us, including inquiries, feedback, and\n    other communications.'\n- category: behavioral\n  text: 'Usage Data: information about how you interact with our API, dashboard, and website—such as request activity,\n    feature usage, performance metrics, and analytics.'\npurposes:\n- purpose: Provide the services\n  text: 'Provide the Services: authenticate users, operate APIs, process payments, manage accounts, and deliver\n    customer support.'\n- purpose: Improve and secure\n  text: 'Improve and secure: monitor performance, debug, develop new features, prevent abuse, and maintain logs.'\nretention:\n- scope: Account closure or deletion request\n  period: 30 days\n  text: we delete or anonymize personal data within 30 days\nresidency:\n- region: United States\n  text: We’re based in the United States and may use service providers in other countries.\ntransfers:\n- mechanism: SCC\n  text: we rely on Standard Contractual Clauses (SCCs) or other appropriate safeguards\
  \ under applicable data-protection\n    laws\nsubprocessors:\n  url: null\n  text: A current list of our sub-processors is available upon request at support@upriver.ai\ndpa:\n  available: true\n  url: null\n  text: A Data Processing Agreement (DPA) consistent with Article 28 of the GDPR is available on request.\ndeletion:\n  route: Upon request or account closure, or by email to support@upriver.ai\n  text: Upon request or account closure, we will delete or return customer data unless legally required to retain\n    it.\nrights:\n- right: Access, correct, or delete\n  text: Access, correct, or delete personal data.\n- right: Restrict or object to processing\n  text: Restrict or object to processing.\n- right: Data portability\n  text: Request data portability.\n- right: Opt out of sale or sharing\n  text: Opt out of sale or sharing (we don’t sell data).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or share it for third-party advertising.\n"
source_yaml_url: https://artifacts.apis.io/upriver-ai/privacy/upriver-ai-privacy-policy.yml
stated_fields:
- role
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
summary_line: 19 quoted statements, read from upriver-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Data
- Creators
- Brands
- Trends
- Sponsorship
---
