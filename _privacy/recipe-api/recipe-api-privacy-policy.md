---
api_specs:
- filename: recipe-api-discovery-api-openapi.yml
  format: yaml
  label: Recipe API Discovery API
  slug: recipe-api-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-discovery-api-openapi.yml
- filename: recipe-api-image-generation-api-openapi.yml
  format: yaml
  label: Recipe API Image Generation API
  slug: recipe-api-image-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-image-generation-api-openapi.yml
- filename: recipe-api-ingredients-api-openapi.yml
  format: yaml
  label: Recipe API Ingredients API
  slug: recipe-api-ingredients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-ingredients-api-openapi.yml
- filename: recipe-api-public-api-openapi.yml
  format: yaml
  label: Recipe API Public API
  slug: recipe-api-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-public-api-openapi.yml
- filename: recipe-api-recipes-api-openapi.yml
  format: yaml
  label: Recipe API Recipes API
  slug: recipe-api-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-recipes-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (required)
  - category: contact
    text: Company name (optional)
  - category: financial
    text: Payment processing is handled by Stripe. We do not store your credit card details.
  - category: device
    text: User agent strings (for debugging and analytics)
  - category: behavioral
    text: API request logs (endpoints accessed, timestamps, and for recipe search the filters and search text sent, with how many recipes matched)
  - category: location
    text: Namespace-separated HMAC hashes derived from IP signals for rate limiting, security, and evaluation-abuse review. Raw IP addresses are not retained.
  deletion:
    route: Developer dashboard account deletion; contact email for other removal requests
    text: You can permanently delete your account from the developer dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the API service
    text: Provide and maintain the API service
  - purpose: Authenticate API requests
    text: Authenticate your API requests
  - purpose: Enforce rate limits and prevent abuse
    text: Enforce rate limits and prevent abuse
  - purpose: Process payments and manage subscriptions
    text: Process payments and manage subscriptions
  - purpose: Decide which recipes to add to the catalogue
    text: Decide which recipes to add to the catalogue, from searches that matched none
  - purpose: Marketing communications with consent
    text: Send marketing communications (only with your consent, with easy unsubscribe)
  residency:
  - region: EU/US
    text: Supabase Database hosting (data stored in the EU/US).
  - region: United Kingdom
    text: 'Fly.io API hosting (primary region: London, UK).'
  retention:
  - period: Until you request account deletion
    scope: Account data
    text: 'Account data: Until you request account deletion'
  - period: 90 days
    scope: API usage logs
    text: 'API usage logs: 90 days'
  - period: typically 7 years for tax purposes
    scope: Payment records
    text: 'Payment records: As required by law (typically 7 years for tax purposes)'
  - period: null
    scope: Generated recipes and cooking briefs
    text: 'Generated recipes and cooking briefs: Stored with the catalogue record while that record is retained.'
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you'
  - right: Correction
    text: 'Correction: Request correction of inaccurate personal data'
  - right: Deletion
    text: 'Deletion: Request deletion of your account and personal data'
  - right: Export
    text: 'Export: Request your data in a portable format'
  - right: Withdraw consent
    text: 'Withdraw consent: Unsubscribe from marketing communications at any time'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your data may be processed in countries outside your residence, including the United States and European Union.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Recipe API
provenance_date: '2026-11-10'
provider_name: Recipe API
provider_slug: recipe-api
slug: recipe-api-privacy-policy
source_date: '2026-11-10'
source_filename: recipe-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://recipe-api.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Recipe API\naid: recipe-api\nurl: https://recipe-api.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (required)\n- category: contact\n  text: Company name (optional)\n- category: financial\n  text: Payment processing is handled by Stripe. We do not store your credit card details.\n- category: device\n  text: User agent strings (for debugging and analytics)\n- category: behavioral\n  text: API request logs (endpoints accessed, timestamps, and for recipe search the filters and search text sent,\n    with how many\
  \ recipes matched)\n- category: location\n  text: Namespace-separated HMAC hashes derived from IP signals for rate limiting, security, and evaluation-abuse\n    review. Raw IP addresses are not retained.\npurposes:\n- purpose: Provide and maintain the API service\n  text: Provide and maintain the API service\n- purpose: Authenticate API requests\n  text: Authenticate your API requests\n- purpose: Enforce rate limits and prevent abuse\n  text: Enforce rate limits and prevent abuse\n- purpose: Process payments and manage subscriptions\n  text: Process payments and manage subscriptions\n- purpose: Decide which recipes to add to the catalogue\n  text: Decide which recipes to add to the catalogue, from searches that matched none\n- purpose: Marketing communications with consent\n  text: Send marketing communications (only with your consent, with easy unsubscribe)\nretention:\n- scope: Account data\n  period: Until you request account deletion\n  text: 'Account data: Until you request account\
  \ deletion'\n- scope: API usage logs\n  period: 90 days\n  text: 'API usage logs: 90 days'\n- scope: Payment records\n  period: typically 7 years for tax purposes\n  text: 'Payment records: As required by law (typically 7 years for tax purposes)'\n- scope: Generated recipes and cooking briefs\n  period: null\n  text: 'Generated recipes and cooking briefs: Stored with the catalogue record while that record is retained.'\nresidency:\n- region: EU/US\n  text: Supabase Database hosting (data stored in the EU/US).\n- region: United Kingdom\n  text: 'Fly.io API hosting (primary region: London, UK).'\ntransfers:\n- mechanism: other\n  text: Your data may be processed in countries outside your residence, including the United States and European\n    Union.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Developer dashboard account deletion; contact email for other removal requests\n  text: You can permanently delete your account\
  \ from the developer dashboard.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate personal data'\n- right: Deletion\n  text: 'Deletion: Request deletion of your account and personal data'\n- right: Export\n  text: 'Export: Request your data in a portable format'\n- right: Withdraw consent\n  text: 'Withdraw consent: Unsubscribe from marketing communications at any time'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/recipe-api/privacy/recipe-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 25 quoted statements, read from Recipe API's own page on 2026-11-10.
synthetic: false
tags:
- Recipes
- Food
- Nutrition
- Ingredients
- Data
- Generative AI
- MCP
- Agents
---
