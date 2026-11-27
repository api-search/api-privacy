---
api_specs:
- filename: agentic-news-ai-agents-api-openapi.yml
  format: yaml
  label: Agentic News Agents API
  slug: agentic-news-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-news-ai/openapi/agentic-news-ai-agents-api-openapi.yml
- filename: agentic-news-ai-api-keys-api-openapi.yml
  format: yaml
  label: Agentic News API Keys API
  slug: agentic-news-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-news-ai/openapi/agentic-news-ai-api-keys-api-openapi.yml
- filename: agentic-news-ai-briefing-api-openapi.yml
  format: yaml
  label: Agentic News Briefing API
  slug: agentic-news-ai-briefing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-news-ai/openapi/agentic-news-ai-briefing-api-openapi.yml
- filename: agentic-news-ai-feed-api-openapi.yml
  format: yaml
  label: Agentic News Feed API
  slug: agentic-news-ai-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-news-ai/openapi/agentic-news-ai-feed-api-openapi.yml
- filename: agentic-news-ai-search-api-openapi.yml
  format: yaml
  label: Agentic News Search API
  slug: agentic-news-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-news-ai/openapi/agentic-news-ai-search-api-openapi.yml
- filename: agentic-news-ai-stories-api-openapi.yml
  format: yaml
  label: Agentic News Stories API
  slug: agentic-news-ai-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-news-ai/openapi/agentic-news-ai-stories-api-openapi.yml
- filename: agentic-news-ai-trending-api-openapi.yml
  format: yaml
  label: Agentic News Trending API
  slug: agentic-news-ai-trending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-news-ai/openapi/agentic-news-ai-trending-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, and your name when Google or Apple sign-in provides it
  - category: contact
    text: Your LinkedIn profile, if you choose to import it during setup
  - category: financial
    text: Billing identifiers (Stripe customer ID, subscription status; we do not store full payment card numbers)
  - category: location
    text: Your approximate location (city and country) during setup, looked up from your IP address by ipapi.co
  - category: behavioral
    text: Whether you open our emails (time and browser) and which links you click (time, IP address, and browser)
  - category: communication
    text: Chat history with the AI about your news collections
  deletion:
    route: Delete account in settings
    text: Deletion immediately removes your account, agents, Lenses, collections, feedback, and email history from our database and from our sign-in provider.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the Service
    text: Account creation, authentication, matching Watches to clusters, generating Lenses, delivering alerts and digests.
  - purpose: Personalizing and improving relevance
    text: Using your feedback and preferences (e.g., thumbs up/down).
  - purpose: Measuring usage and reliability
    text: Enforcing limits (token accounting), preventing abuse, and debugging.
  - purpose: Billing and payments
    text: Processing via Stripe; fraud prevention.
  - purpose: Communications
    text: Transactional messages about the Service, and where permitted, product updates and marketing (you can opt out).
  retention:
  - period: while your account is active
    scope: Account data and preferences
    text: Retained while your account is active.
  - period: null
    scope: News metadata and cached content
    text: Retained for archival search.
  - period: until you delete your account
    scope: Email opens and link clicks
    text: Records of email opens and link clicks are kept until you delete your account.
  rights:
  - right: Delete account
    text: Delete your account yourself, in settings
  - right: Access, correction, or copy
    text: Request access to, correction of, or a copy of your personal data, by email
  - right: Object or restrict processing
    text: Object to or restrict certain processing
  - right: Withdraw consent
    text: Withdraw consent (where processing relies on consent)
  - right: Opt out of marketing
    text: Opt out of marketing communications
  role:
    text: We act as a data controller for user account data and related usage data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses for EEA/UK transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentic News
provenance_date: '2026-11-09'
provider_name: Agentic News
provider_slug: agentic-news-ai
slug: agentic-news-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agentic-news-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentic-news.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentic News\naid: agentic-news-ai\nurl: https://agentic-news.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We act as a data controller for user account data and related usage data.\ndata_categories:\n- category: identifying\n  text: Email address, and your name when Google or Apple sign-in provides it\n- category: contact\n  text: Your LinkedIn profile, if you choose to import it during setup\n- category: financial\n  text: Billing identifiers (Stripe customer ID, subscription status; we do not store full payment card numbers)\n- category: location\n  text: Your approximate location\
  \ (city and country) during setup, looked up from your IP address by ipapi.co\n- category: behavioral\n  text: Whether you open our emails (time and browser) and which links you click (time, IP address, and browser)\n- category: communication\n  text: Chat history with the AI about your news collections\npurposes:\n- purpose: Providing the Service\n  text: Account creation, authentication, matching Watches to clusters, generating Lenses, delivering alerts and\n    digests.\n- purpose: Personalizing and improving relevance\n  text: Using your feedback and preferences (e.g., thumbs up/down).\n- purpose: Measuring usage and reliability\n  text: Enforcing limits (token accounting), preventing abuse, and debugging.\n- purpose: Billing and payments\n  text: Processing via Stripe; fraud prevention.\n- purpose: Communications\n  text: Transactional messages about the Service, and where permitted, product updates and marketing (you can opt\n    out).\nretention:\n- scope: Account data and preferences\n\
  \  period: while your account is active\n  text: Retained while your account is active.\n- scope: News metadata and cached content\n  period: null\n  text: Retained for archival search.\n- scope: Email opens and link clicks\n  period: until you delete your account\n  text: Records of email opens and link clicks are kept until you delete your account.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses for EEA/UK transfers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in settings\n  text: Deletion immediately removes your account, agents, Lenses, collections, feedback, and email history from\n    our database and from our sign-in provider.\nrights:\n- right: Delete account\n  text: Delete your account yourself, in settings\n- right: Access, correction, or copy\n  text: Request access to, correction of, or a copy of your personal data, by email\n- right: Object or restrict\
  \ processing\n  text: Object to or restrict certain processing\n- right: Withdraw consent\n  text: Withdraw consent (where processing relies on consent)\n- right: Opt out of marketing\n  text: Opt out of marketing communications\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentic-news-ai/privacy/agentic-news-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from Agentic News's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- News
- Aggregation
- DailyBriefings
- AI Agents
---
