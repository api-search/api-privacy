---
api_specs:
- filename: skilldb-dev-openapi-generated.yml
  format: yaml
  label: skilldb-dev API
  slug: skilldb-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skilldb-dev/openapi/_ae-authored/skilldb-dev-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, display name, and profile picture when you sign in with Google.
  - category: financial
    text: 'Payment Information: Processed securely by Stripe. We do not store credit card numbers.'
  - category: device
    text: API key identifiers, request timestamps, endpoints accessed, and response times for billing and analytics.
  - category: communication
    text: Posts, comments, polls, and messages you submit to the community.
  - category: location
    text: We keep IP-based request counters in memory for rate limiting, using a 60-second window.
  deletion:
    route: Request deletion of account and associated data
    text: Request deletion of your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and improving the platform
    text: Providing and improving the SkillDB platform
  - purpose: Processing payments and subscriptions
    text: Processing payments and managing subscriptions
  - purpose: Billing and rate limiting
    text: Tracking API usage for billing and rate limiting
  - purpose: Service updates and security notices
    text: Communicating service updates and security notices
  - purpose: Usage analysis for recommendations
    text: Analyzing usage patterns to improve skill recommendations
  retention:
  - period: while your account is active
    scope: Account data
    text: Account data is retained while your account is active.
  - period: 90 days
    scope: Authenticated API usage logs
    text: Authenticated API usage logs are retained for 90 days.
  - period: 30 days
    scope: Google Cloud hosting request metadata for anonymous MCP requests
    text: Google Cloud hosting request metadata for anonymous catalog MCP requests, including IP addresses, is retained for 30 days.
  - period: indefinitely unless you request deletion
    scope: Community content
    text: Community content is retained indefinitely unless you request deletion.
  rights:
  - right: Access
    text: Access your personal data
  - right: Deletion
    text: Request deletion of your account and associated data
  - right: Export
    text: Export your data in a machine-readable format
  - right: Opt out of non-essential communications
    text: Opt out of non-essential communications
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: skilldb-dev
provenance_date: '2026-11-10'
provider_name: skilldb-dev
provider_slug: skilldb-dev
slug: skilldb-dev-privacy-policy
source_date: '2026-11-10'
source_filename: skilldb-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://skilldb.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: skilldb-dev\naid: skilldb-dev\nurl: https://skilldb.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, display name, and profile picture when you sign in with Google.\n- category: financial\n  text: 'Payment Information: Processed securely by Stripe. We do not store credit card numbers.'\n- category: device\n  text: API key identifiers, request timestamps, endpoints accessed, and response times for billing and analytics.\n- category: communication\n  text: Posts, comments, polls, and messages you submit to the community.\n\
  - category: location\n  text: We keep IP-based request counters in memory for rate limiting, using a 60-second window.\npurposes:\n- purpose: Providing and improving the platform\n  text: Providing and improving the SkillDB platform\n- purpose: Processing payments and subscriptions\n  text: Processing payments and managing subscriptions\n- purpose: Billing and rate limiting\n  text: Tracking API usage for billing and rate limiting\n- purpose: Service updates and security notices\n  text: Communicating service updates and security notices\n- purpose: Usage analysis for recommendations\n  text: Analyzing usage patterns to improve skill recommendations\nretention:\n- scope: Account data\n  period: while your account is active\n  text: Account data is retained while your account is active.\n- scope: Authenticated API usage logs\n  period: 90 days\n  text: Authenticated API usage logs are retained for 90 days.\n- scope: Google Cloud hosting request metadata for anonymous MCP requests\n  period:\
  \ 30 days\n  text: Google Cloud hosting request metadata for anonymous catalog MCP requests, including IP addresses, is retained\n    for 30 days.\n- scope: Community content\n  period: indefinitely unless you request deletion\n  text: Community content is retained indefinitely unless you request deletion.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of account and associated data\n  text: Request deletion of your account and associated data\nrights:\n- right: Access\n  text: Access your personal data\n- right: Deletion\n  text: Request deletion of your account and associated data\n- right: Export\n  text: Export your data in a machine-readable format\n- right: Opt out of non-essential communications\n  text: Opt out of non-essential communications\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skilldb-dev/privacy/skilldb-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 19 quoted statements, read from skilldb-dev's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Skills
- Catalog
- Developer Tools
- Open Source
---
