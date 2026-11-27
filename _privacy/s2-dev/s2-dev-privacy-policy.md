---
api_specs:
- filename: s2-dev-access-tokens-api-openapi.yml
  format: yaml
  label: S2 Dev Access Tokens API
  slug: s2-dev-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-access-tokens-api-openapi.yml
- filename: s2-dev-basins-api-openapi.yml
  format: yaml
  label: S2 Dev Basins API
  slug: s2-dev-basins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-basins-api-openapi.yml
- filename: s2-dev-locations-api-openapi.yml
  format: yaml
  label: S2 Dev Locations API
  slug: s2-dev-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-locations-api-openapi.yml
- filename: s2-dev-metrics-api-openapi.yml
  format: yaml
  label: S2 Dev Metrics API
  slug: s2-dev-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-metrics-api-openapi.yml
- filename: s2-dev-records-api-openapi.yml
  format: yaml
  label: S2 Dev Records API
  slug: s2-dev-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-records-api-openapi.yml
- filename: s2-dev-streams-api-openapi.yml
  format: yaml
  label: S2 Dev Streams API
  slug: s2-dev-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-streams-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Email
  - category: device
    text: Device type
  - category: location
    text: Geo-location data
  - category: financial
    text: Transaction Data
  deletion:
    route: Request deletion or delete account
    text: You may have a right to request that we delete the personal information we hold about you at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: core features and services
    text: to provide you with our platform's core features and services
  - purpose: analytics and business development
    text: for analytics, market research, and business development
  - purpose: advertising and marketing
    text: for advertising and marketing, including to send you promotional information about our products and services
  - purpose: security and fraud prevention
    text: for security and fraud prevention
  residency:
  - region: United Kingdom
    text: The personal information we collect is stored and/or processed in the United Kingdom by us.
  retention:
  - period: duration your account exists on our system
    scope: account data
    text: we may retain this information for the duration your account exists on our system
  - period: 30 days
    scope: account deletion
    text: If you terminate or delete your account, we will delete your personal information within 30 days of the deletion of your account.
  rights:
  - right: Access
    text: You may request details of the personal information that we hold about you.
  - right: Correction
    text: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant, or misleading, please contact us using the details provided in this privacy policy.
  - right: Restrict
    text: You have the right to request that we restrict the processing of your personal information
  - right: Objecting to processing
    text: You have the right to object to processing of your personal information that is based on our legitimate interests or public interest.
  - right: Data portability
    text: You may have the right to request a copy of the personal information we hold about you.
  - right: Deletion
    text: You may have a right to request that we delete the personal information we hold about you at any time
  role:
    text: We, Bandar Systems Inc., located at the address provided in our Contact Us section, are a Data Controller with respect to the personal information you provide to us.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We will not sell personal information, such as email addresses, to unrelated third-parties.
  subprocessors:
    text: 'Third parties we currently use include: Clerk (user authentication)'
    url: null
  transfers:
  - mechanism: SCC
    text: such as standard contractual clauses (“SCCs”) or binding corporate rules.
  - mechanism: BCR
    text: or the use of binding corporate rules or other legally accepted means.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: S2 Dev
provenance_date: '2026-11-10'
provider_name: S2 Dev
provider_slug: s2-dev
slug: s2-dev-privacy-policy
source_date: '2026-11-10'
source_filename: s2-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://s2.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: S2 Dev\naid: s2-dev\nurl: https://s2.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We, Bandar Systems Inc., located at the address provided in our Contact Us section, are a Data Controller\n    with respect to the personal information you provide to us.\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Email\n- category: device\n  text: Device type\n- category: location\n  text: Geo-location data\n- category: financial\n  text: Transaction Data\npurposes:\n- purpose: core features and services\n  text: to provide you with our platform's core\
  \ features and services\n- purpose: analytics and business development\n  text: for analytics, market research, and business development\n- purpose: advertising and marketing\n  text: for advertising and marketing, including to send you promotional information about our products and services\n- purpose: security and fraud prevention\n  text: for security and fraud prevention\nretention:\n- scope: account data\n  period: duration your account exists on our system\n  text: we may retain this information for the duration your account exists on our system\n- scope: account deletion\n  period: 30 days\n  text: If you terminate or delete your account, we will delete your personal information within 30 days of the\n    deletion of your account.\nresidency:\n- region: United Kingdom\n  text: The personal information we collect is stored and/or processed in the United Kingdom by us.\ntransfers:\n- mechanism: SCC\n  text: such as standard contractual clauses (“SCCs”) or binding corporate rules.\n\
  - mechanism: BCR\n  text: or the use of binding corporate rules or other legally accepted means.\nsubprocessors:\n  url: null\n  text: 'Third parties we currently use include: Clerk (user authentication)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion or delete account\n  text: You may have a right to request that we delete the personal information we hold about you at any time\nrights:\n- right: Access\n  text: You may request details of the personal information that we hold about you.\n- right: Correction\n  text: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant,\n    or misleading, please contact us using the details provided in this privacy policy.\n- right: Restrict\n  text: You have the right to request that we restrict the processing of your personal information\n- right: Objecting to processing\n  text: You have the right to object to processing of your personal information that is\
  \ based on our legitimate\n    interests or public interest.\n- right: Data portability\n  text: You may have the right to request a copy of the personal information we hold about you.\n- right: Deletion\n  text: You may have a right to request that we delete the personal information we hold about you at any time\nsale_or_sharing:\n  stance: conditional\n  text: We will not sell personal information, such as email addresses, to unrelated third-parties.\n"
source_yaml_url: https://artifacts.apis.io/s2-dev/privacy/s2-dev-privacy-policy.yml
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
- sale_or_sharing
summary_line: 24 quoted statements, read from S2 Dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Streaming
- Real-Time
- Event Streaming
- Durable Storage
- Message Streaming
- Data Feed
- Observability
- Developer Tools
- Infrastructure
---
