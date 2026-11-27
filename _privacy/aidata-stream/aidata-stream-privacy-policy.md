---
api_specs:
- filename: aidata-stream-openapi-generated.yml
  format: yaml
  label: aidata-stream API
  slug: aidata-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aidata-stream/openapi/_ae-authored/aidata-stream-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name (optional)
  - category: contact
    text: Email address
  - category: financial
    text: Payment information (processed securely by Stripe)
  - category: device
    text: IP addresses (for fraud prevention)
  - category: behavioral
    text: Sessions, traffic sources, conversions, page performance
  deletion:
    route: Deletion request or account deletion
    text: Account deletion - Account and team records are deleted immediately upon request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: Provide and maintain our service
  - purpose: Process transactions
    text: Process your transactions
  - purpose: Send service communications
    text: Send service-related communications
  - purpose: Detect and prevent fraud
    text: Detect and prevent fraud or abuse
  - purpose: Improve service
    text: Improve our service based on usage patterns
  residency:
  - region: European Union
    text: Our servers are located in the European Union.
  retention:
  - period: null
    scope: Active accounts
    text: Active accounts - Data retained while account is active
  - period: 30 days
    scope: Cancelled subscriptions
    text: Cancelled subscriptions - Data retained for 30 days, then deleted
  - period: 7 days
    scope: Account deletion
    text: Associated data files are purged within 7 days.
  rights:
  - right: Access
    text: Access - Request a copy of your personal data
  - right: Correction
    text: Correction - Request correction of inaccurate data
  - right: Deletion
    text: Deletion - Request deletion of your account and data
  - right: Export
    text: Export - Team owners can download a full backup of their team data at any time
  - right: Revoke access
    text: Revoke Access - Disconnect platforms and revoke OAuth permissions anytime
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: aidata-stream
provenance_date: '2026-11-09'
provider_name: aidata-stream
provider_slug: aidata-stream
slug: aidata-stream-privacy-policy
source_date: '2026-11-09'
source_filename: aidata-stream-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aidata.stream/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: aidata-stream\naid: aidata-stream\nurl: https://aidata.stream/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name (optional)\n- category: contact\n  text: Email address\n- category: financial\n  text: Payment information (processed securely by Stripe)\n- category: device\n  text: IP addresses (for fraud prevention)\n- category: behavioral\n  text: Sessions, traffic sources, conversions, page performance\npurposes:\n- purpose: Provide and maintain service\n  text: Provide and maintain our service\n- purpose: Process transactions\n\
  \  text: Process your transactions\n- purpose: Send service communications\n  text: Send service-related communications\n- purpose: Detect and prevent fraud\n  text: Detect and prevent fraud or abuse\n- purpose: Improve service\n  text: Improve our service based on usage patterns\nretention:\n- scope: Active accounts\n  period: null\n  text: Active accounts - Data retained while account is active\n- scope: Cancelled subscriptions\n  period: 30 days\n  text: Cancelled subscriptions - Data retained for 30 days, then deleted\n- scope: Account deletion\n  period: 7 days\n  text: Associated data files are purged within 7 days.\nresidency:\n- region: European Union\n  text: Our servers are located in the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deletion request or account deletion\n  text: Account deletion - Account and team records are deleted immediately upon request.\nrights:\n- right:\
  \ Access\n  text: Access - Request a copy of your personal data\n- right: Correction\n  text: Correction - Request correction of inaccurate data\n- right: Deletion\n  text: Deletion - Request deletion of your account and data\n- right: Export\n  text: Export - Team owners can download a full backup of their team data at any time\n- right: Revoke access\n  text: Revoke Access - Disconnect platforms and revoke OAuth permissions anytime\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your personal information.\n"
source_yaml_url: https://artifacts.apis.io/aidata-stream/privacy/aidata-stream-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from aidata-stream's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Analytics
- SEO
- Marketing
- Data
---
