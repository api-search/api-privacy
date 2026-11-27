---
api_specs:
- filename: socially-run-attributions-api-openapi.yml
  format: yaml
  label: socially-run Attributions API
  slug: socially-run-attributions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-attributions-api-openapi.yml
- filename: socially-run-dossiers-api-openapi.yml
  format: yaml
  label: socially-run Dossiers API
  slug: socially-run-dossiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-dossiers-api-openapi.yml
- filename: socially-run-emails-api-openapi.yml
  format: yaml
  label: socially-run Emails API
  slug: socially-run-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-emails-api-openapi.yml
- filename: socially-run-jobs-api-openapi.yml
  format: yaml
  label: socially-run Jobs API
  slug: socially-run-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-jobs-api-openapi.yml
- filename: socially-run-platforms-api-openapi.yml
  format: yaml
  label: socially-run Platforms API
  slug: socially-run-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-platforms-api-openapi.yml
- filename: socially-run-posts-api-openapi.yml
  format: yaml
  label: socially-run Posts API
  slug: socially-run-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-posts-api-openapi.yml
- filename: socially-run-profiles-api-openapi.yml
  format: yaml
  label: socially-run Profiles API
  slug: socially-run-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-profiles-api-openapi.yml
- filename: socially-run-resolve-api-openapi.yml
  format: yaml
  label: socially-run Resolve API
  slug: socially-run-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-resolve-api-openapi.yml
- filename: socially-run-search-api-openapi.yml
  format: yaml
  label: socially-run Search API
  slug: socially-run-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-search-api-openapi.yml
- filename: socially-run-trending-api-openapi.yml
  format: yaml
  label: socially-run Trending API
  slug: socially-run-trending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-trending-api-openapi.yml
- filename: socially-run-usage-api-openapi.yml
  format: yaml
  label: socially-run Usage API
  slug: socially-run-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-usage-api-openapi.yml
- filename: socially-run-usernames-api-openapi.yml
  format: yaml
  label: socially-run Usernames API
  slug: socially-run-usernames-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-usernames-api-openapi.yml
- filename: socially-run-web-api-openapi.yml
  format: yaml
  label: socially-run Web API
  slug: socially-run-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-web-api-openapi.yml
- filename: socially-run-webhooks-api-openapi.yml
  format: yaml
  label: socially-run Webhooks API
  slug: socially-run-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socially-run/openapi/socially-run-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account : email address, display name, the sign-in provider (email, Google or GitHub)'
  - category: financial
    text: 'Billing : your plan, your credit balance, and the Stripe customer and payment references.'
  - category: device
    text: 'Technical : the IP address and user agent of each request, in the request logs.'
  - category: behavioral
    text: 'Usage : the kind, target platform, credits charged or refunded, cache status, request id and timestamp of every request'
  - category: identifying
    text: 'Whatever the public page showed at the moment we read it: display name, handle, bio, avatar URL, follower and post counts, recent public posts, links.'
  deletion:
    route: console, under Account
    text: Customers can also delete their account there.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation, metering, billing, security and support
    text: We use it to run the service, meter it, bill it, keep it secure and support you.
  - purpose: legitimate interest in public information
    text: We rely on legitimate interest in public information (LGPD art. 7, IX; GDPR art. 6(1)(f))
  residency:
  - region: Brazil
    text: Our servers are in São Paulo, Brazil.
  - region: United States
    text: It runs in AWS's us-east-1 region, in the United States.
  retention:
  - period: indefinitely
    scope: public profile, post, web and search results
    text: we keep the public data we read and its earlier versions indefinitely in our database for cached and fallback answers
  - period: 180 days
    scope: request logs
    text: 'Request logs : 180 days.'
  - period: 7 days
    scope: webhook delivery logs
    text: Webhook delivery logs are kept 7 days.
  - period: 7 days
    scope: backups on our servers
    text: 'Backups run every night: they stay 7 days on our servers and 30 days in encrypted offsite storage.'
  - period: 14 days
    scope: deleted account before final deletion
    text: hold the account for 14 days so you can undo it
  - period: life of the account
    scope: lookup history
    text: 'Lookup history (what you called, never the page content): kept for the life of the account.'
  rights:
  - right: access, correction, deletion, anonymization
    text: you can ask us to confirm whether we hold data about you, to show it to you, to correct it, to delete or anonymize it
  - right: portability
    text: to hand it over in a portable form
  - right: withdraw consent
    text: You can withdraw a consent you gave us at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell it, and we do not train models on it.
  subprocessors:
    text: 'Stripe : payments. Card data never reaches us.'
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers outside Brazil and the EEA rely on the processors' standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: socially-run
provenance_date: '2026-11-10'
provider_name: socially-run
provider_slug: socially-run
slug: socially-run-privacy-policy
source_date: '2026-11-10'
source_filename: socially-run-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://socially.run/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: socially-run\naid: socially-run\nurl: https://socially.run/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Account : email address, display name, the sign-in provider (email, Google or GitHub)'\n- category: financial\n  text: 'Billing : your plan, your credit balance, and the Stripe customer and payment references.'\n- category: device\n  text: 'Technical : the IP address and user agent of each request, in the request logs.'\n- category: behavioral\n  text: 'Usage : the kind, target platform, credits charged or refunded, cache status,\
  \ request id and timestamp\n    of every request'\n- category: identifying\n  text: 'Whatever the public page showed at the moment we read it: display name, handle, bio, avatar URL, follower\n    and post counts, recent public posts, links.'\npurposes:\n- purpose: service operation, metering, billing, security and support\n  text: We use it to run the service, meter it, bill it, keep it secure and support you.\n- purpose: legitimate interest in public information\n  text: We rely on legitimate interest in public information (LGPD art. 7, IX; GDPR art. 6(1)(f))\nretention:\n- scope: public profile, post, web and search results\n  period: indefinitely\n  text: we keep the public data we read and its earlier versions indefinitely in our database for cached and fallback\n    answers\n- scope: request logs\n  period: 180 days\n  text: 'Request logs : 180 days.'\n- scope: webhook delivery logs\n  period: 7 days\n  text: Webhook delivery logs are kept 7 days.\n- scope: backups on our servers\n\
  \  period: 7 days\n  text: 'Backups run every night: they stay 7 days on our servers and 30 days in encrypted offsite storage.'\n- scope: deleted account before final deletion\n  period: 14 days\n  text: hold the account for 14 days so you can undo it\n- scope: lookup history\n  period: life of the account\n  text: 'Lookup history (what you called, never the page content): kept for the life of the account.'\nresidency:\n- region: Brazil\n  text: Our servers are in São Paulo, Brazil.\n- region: United States\n  text: It runs in AWS's us-east-1 region, in the United States.\ntransfers:\n- mechanism: SCC\n  text: Transfers outside Brazil and the EEA rely on the processors' standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'Stripe : payments. Card data never reaches us.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: console, under Account\n  text: Customers can also delete their account there.\nrights:\n- right: access, correction, deletion, anonymization\n\
  \  text: you can ask us to confirm whether we hold data about you, to show it to you, to correct it, to delete or\n    anonymize it\n- right: portability\n  text: to hand it over in a portable form\n- right: withdraw consent\n  text: You can withdraw a consent you gave us at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell it, and we do not train models on it.\n"
source_yaml_url: https://artifacts.apis.io/socially-run/privacy/socially-run-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from socially-run's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Data API
- JSON
- MCP
- AI Agents
---
