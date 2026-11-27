---
api_specs:
- filename: botfriendly-xyz-categories-api-openapi.yml
  format: yaml
  label: BotFriendly Categories API
  slug: botfriendly-xyz-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-categories-api-openapi.yml
- filename: botfriendly-xyz-check-api-openapi.yml
  format: yaml
  label: BotFriendly Check API
  slug: botfriendly-xyz-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-check-api-openapi.yml
- filename: botfriendly-xyz-featured-api-openapi.yml
  format: yaml
  label: BotFriendly Featured API
  slug: botfriendly-xyz-featured-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-featured-api-openapi.yml
- filename: botfriendly-xyz-health-api-openapi.yml
  format: yaml
  label: BotFriendly Health API
  slug: botfriendly-xyz-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-health-api-openapi.yml
- filename: botfriendly-xyz-protocols-api-openapi.yml
  format: yaml
  label: BotFriendly Protocols API
  slug: botfriendly-xyz-protocols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-protocols-api-openapi.yml
- filename: botfriendly-xyz-search-api-openapi.yml
  format: yaml
  label: BotFriendly Search API
  slug: botfriendly-xyz-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-search-api-openapi.yml
- filename: botfriendly-xyz-services-api-openapi.yml
  format: yaml
  label: BotFriendly Services API
  slug: botfriendly-xyz-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-services-api-openapi.yml
- filename: botfriendly-xyz-stats-api-openapi.yml
  format: yaml
  label: BotFriendly Stats API
  slug: botfriendly-xyz-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-stats-api-openapi.yml
- filename: botfriendly-xyz-submissions-api-openapi.yml
  format: yaml
  label: BotFriendly Submissions API
  slug: botfriendly-xyz-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-submissions-api-openapi.yml
- filename: botfriendly-xyz-verify-api-openapi.yml
  format: yaml
  label: BotFriendly Verify API
  slug: botfriendly-xyz-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botfriendly-xyz/openapi/botfriendly-xyz-verify-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: contact
    text: We store your email address, display name, and the listings you manage.
  - category: financial
    text: Card details never touch our servers; we keep only the Stripe session reference needed to activate and expire the promotion you bought.
  - category: behavioral
    text: Anonymous usage counters (which endpoints get called) may be tracked in aggregate to plan capacity.
  deletion:
    route: email hi@botfriendly.xyz
    text: Want your account, submission or listing data corrected or deleted? Email hi@botfriendly.xyz from the address on the account and we will handle it within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run account and listings
    text: Creating an account (email-based, via Supabase) is only needed to submit and manage listings or buy ad slots.
  - purpose: rate limiting
    text: IP addresses are used in memory for rate limiting (100 requests a minute; 6 a minute on the site checker)
  - purpose: capacity planning
    text: Anonymous usage counters (which endpoints get called) may be tracked in aggregate to plan capacity.
  retention:
  - period: null
    scope: IP addresses
    text: IP addresses are used in memory for rate limiting (100 requests a minute; 6 a minute on the site checker) and are not written to a database.
  - period: null
    scope: site checker fetched content
    text: We do not store the fetched content or the report after the response is sent, and we never probe private networks.
  rights:
  - right: correction or deletion
    text: Want your account, submission or listing data corrected or deleted?
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell or share account data, and we do not send marketing email.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BotFriendly
provenance_date: '2026-11-09'
provider_name: BotFriendly
provider_slug: botfriendly-xyz
slug: botfriendly-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: botfriendly-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://botfriendly.xyz/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BotFriendly\naid: botfriendly-xyz\nurl: https://botfriendly.xyz/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We store your email address, display name, and the listings you manage.\n- category: financial\n  text: Card details never touch our servers; we keep only the Stripe session reference needed to activate and expire\n    the promotion you bought.\n- category: behavioral\n  text: Anonymous usage counters (which endpoints get called) may be tracked in aggregate to plan capacity.\npurposes:\n- purpose: run account and listings\n\
  \  text: Creating an account (email-based, via Supabase) is only needed to submit and manage listings or buy ad slots.\n- purpose: rate limiting\n  text: IP addresses are used in memory for rate limiting (100 requests a minute; 6 a minute on the site checker)\n- purpose: capacity planning\n  text: Anonymous usage counters (which endpoints get called) may be tracked in aggregate to plan capacity.\nretention:\n- scope: IP addresses\n  period: null\n  text: IP addresses are used in memory for rate limiting (100 requests a minute; 6 a minute on the site checker)\n    and are not written to a database.\n- scope: site checker fetched content\n  period: null\n  text: We do not store the fetched content or the report after the response is sent, and we never probe private\n    networks.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hi@botfriendly.xyz\n  text: Want your account, submission or\
  \ listing data corrected or deleted? Email hi@botfriendly.xyz from the address\n    on the account and we will handle it within 30 days.\nrights:\n- right: correction or deletion\n  text: Want your account, submission or listing data corrected or deleted?\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell or share account data, and we do not send marketing email.\n"
source_yaml_url: https://artifacts.apis.io/botfriendly-xyz/privacy/botfriendly-xyz-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from BotFriendly's own page on 2026-11-09.
synthetic: false
tags:
- BotFriendly
- AI Agents
- Machine-to-Machine
- API Directory
- OpenAPI
---
