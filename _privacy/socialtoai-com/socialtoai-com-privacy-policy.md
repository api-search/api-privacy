---
api_specs:
- filename: socialtoai-com-account-api-openapi.yml
  format: yaml
  label: socialtoai-com Account API
  slug: socialtoai-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-account-api-openapi.yml
- filename: socialtoai-com-call-api-openapi.yml
  format: yaml
  label: socialtoai-com Call API
  slug: socialtoai-com-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-call-api-openapi.yml
- filename: socialtoai-com-capabilities-api-openapi.yml
  format: yaml
  label: socialtoai-com Capabilities API
  slug: socialtoai-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-capabilities-api-openapi.yml
- filename: socialtoai-com-comments-api-openapi.yml
  format: yaml
  label: socialtoai-com Comments API
  slug: socialtoai-com-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-comments-api-openapi.yml
- filename: socialtoai-com-detail-api-openapi.yml
  format: yaml
  label: socialtoai-com Detail API
  slug: socialtoai-com-detail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-detail-api-openapi.yml
- filename: socialtoai-com-find-api-openapi.yml
  format: yaml
  label: socialtoai-com Find API
  slug: socialtoai-com-find-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-find-api-openapi.yml
- filename: socialtoai-com-search-api-openapi.yml
  format: yaml
  label: socialtoai-com Search API
  slug: socialtoai-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-search-api-openapi.yml
- filename: socialtoai-com-trending-api-openapi.yml
  format: yaml
  label: socialtoai-com Trending API
  slug: socialtoai-com-trending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-trending-api-openapi.yml
- filename: socialtoai-com-user-posts-api-openapi.yml
  format: yaml
  label: socialtoai-com User Posts API
  slug: socialtoai-com-user-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-user-posts-api-openapi.yml
- filename: socialtoai-com-user-profile-api-openapi.yml
  format: yaml
  label: socialtoai-com User Profile API
  slug: socialtoai-com-user-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialtoai-com/openapi/socialtoai-com-user-profile-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, to sign you in and to send receipts and service notices.
  - category: identifying
    text: If you sign in with Google, Google also passes on your Google account's name, profile picture and account ID
  - category: financial
    text: Payment records from the payment provider; card numbers never reach us.
  - category: behavioral
    text: 'A record of each call: which interface, when, how many credits, and whether it succeeded.'
  - category: device
    text: Where your first visit came from (the kind of first page, the referring site and campaign tags, never a full address) is kept in your own browser's storage for this site, for up to 90 days
  deletion:
    route: Account settings or email support
    text: You can delete your account from its settings. For anything else about your data, write to support@socialtoai.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the account and sign-in
    text: 'SocialToAI keeps what it needs to run your account: your email, your keys as hashes, and a record of each call with its credits.'
  - purpose: Aggregate analytics
    text: We count page views and a few product events in aggregate
  - purpose: Content analysis for tools
    text: To analyse content when you run a tool, we send the public posts and comments it collected to an AI model provider; nothing that identifies your account is sent.
  retention:
  - period: 24 hours
    scope: Charged call answers
    text: The answer to a call is kept, sealed, for 24 hours so the key that made it can read it again for free; then it is deleted.
  - period: up to 90 days
    scope: First-visit origin in browser
    text: is kept in your own browser's storage for this site, for up to 90 days, and is removed once you sign in.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: and it does not sell your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: socialtoai-com
provenance_date: '2026-11-10'
provider_name: socialtoai-com
provider_slug: socialtoai-com
slug: socialtoai-com-privacy-policy
source_date: '2026-11-10'
source_filename: socialtoai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://socialtoai.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: socialtoai-com\naid: socialtoai-com\nurl: https://socialtoai.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, to sign you in and to send receipts and service notices.\n- category: identifying\n  text: If you sign in with Google, Google also passes on your Google account's name, profile picture and account\n    ID\n- category: financial\n  text: Payment records from the payment provider; card numbers never reach us.\n- category: behavioral\n  text: 'A record of each call: which interface, when, how many credits,\
  \ and whether it succeeded.'\n- category: device\n  text: Where your first visit came from (the kind of first page, the referring site and campaign tags, never a\n    full address) is kept in your own browser's storage for this site, for up to 90 days\npurposes:\n- purpose: Run the account and sign-in\n  text: 'SocialToAI keeps what it needs to run your account: your email, your keys as hashes, and a record of each\n    call with its credits.'\n- purpose: Aggregate analytics\n  text: We count page views and a few product events in aggregate\n- purpose: Content analysis for tools\n  text: To analyse content when you run a tool, we send the public posts and comments it collected to an AI model\n    provider; nothing that identifies your account is sent.\nretention:\n- scope: Charged call answers\n  period: 24 hours\n  text: The answer to a call is kept, sealed, for 24 hours so the key that made it can read it again for free; then\n    it is deleted.\n- scope: First-visit origin in browser\n\
  \  period: up to 90 days\n  text: is kept in your own browser's storage for this site, for up to 90 days, and is removed once you sign in.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or email support\n  text: You can delete your account from its settings. For anything else about your data, write to support@socialtoai.com.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: and it does not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/socialtoai-com/privacy/socialtoai-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 12 quoted statements, read from socialtoai-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- Artificial Intelligence
- Data API
- MCP
- Analytics
---
