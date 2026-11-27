---
api_specs:
- filename: testerarmy-groups-api-openapi.yml
  format: yaml
  label: Testerarmy Groups API
  slug: testerarmy-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-groups-api-openapi.yml
- filename: testerarmy-projects-api-openapi.yml
  format: yaml
  label: Testerarmy Projects API
  slug: testerarmy-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-projects-api-openapi.yml
- filename: testerarmy-test-runs-api-openapi.yml
  format: yaml
  label: Testerarmy Test Runs API
  slug: testerarmy-test-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-test-runs-api-openapi.yml
- filename: testerarmy-tests-api-openapi.yml
  format: yaml
  label: Testerarmy Tests API
  slug: testerarmy-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-tests-api-openapi.yml
- filename: testerarmy-webhooks-api-openapi.yml
  format: yaml
  label: Testerarmy Webhooks API
  slug: testerarmy-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-webhooks-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name (as provided by your OAuth provider)
  - category: contact
    text: Email address
  - category: identifying
    text: OAuth provider account identifiers
  - category: financial
    text: We store only Stripe customer IDs, subscription IDs, plan names, and subscription status for account management.
  - category: behavioral
    text: Feature usage events (pages visited, actions taken, test runs executed)
  - category: device
    text: IP address, browser type, device information
  - category: communication
    text: Chat conversation history
  - category: other
    text: Website credentials (username/password) - stored encrypted with AES-256-GCM
  - category: other
    text: Screenshots captured during test execution
  deletion:
    route: Account deletion
    text: Account deletion is permanent and immediate. All associated personal data is deleted at the time of deletion, except where retention is required by law (e.g., billing records).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Process payments and subscriptions
    text: Process payments and manage subscriptions through Stripe
  - purpose: Marketing communications
    text: Send product updates, feature announcements, and marketing communications via Loops (you may unsubscribe at any time)
  - purpose: Product analytics
    text: Analyze product usage patterns to improve features, reliability, and user experience
  - purpose: Security and error monitoring
    text: Monitor and fix errors, bugs, and security issues
  residency:
  - region: United States, European Union, and other countries
    text: Your data may be processed in the United States, European Union, and other countries where our service providers operate
  retention:
  - period: for the lifetime of your account
    scope: Account data
    text: Account data - retained for the lifetime of your account
  - period: indefinitely while your account is active
    scope: Chat and message history
    text: Chat and message history - retained indefinitely while your account is active
  - period: default 90 days
    scope: API keys
    text: API keys - configurable expiration (default 90 days) or non-expiring
  - period: 1 hour
    scope: Magic link tokens
    text: Magic link tokens - expire after 1 hour
  - period: 7 days
    scope: Team invitations and join links
    text: Team invitations and join links - expire after 7 days
  - period: 24 hours
    scope: Stream data (Redis)
    text: Stream data (Redis) - automatically deleted after 24 hours
  rights:
  - right: Access
    text: Access your personal data we hold
  - right: Rectify
    text: Rectify inaccurate or incomplete data
  - right: Erase
    text: Erase your personal data
  - right: Port
    text: Port your data to another service in a machine-readable format
  - right: Object
    text: Object to processing based on legitimate interests
  - right: Restrict
    text: Restrict processing in certain circumstances
  - right: Withdraw consent
    text: Withdraw consent at any time where processing is based on consent
  - right: Delete (California)
    text: Delete your personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'We use the following third-party services to operate the platform:'
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses and other lawful transfer mechanisms where required by applicable data protection laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Testerarmy
provenance_date: '2026-11-10'
provider_name: Testerarmy
provider_slug: testerarmy
slug: testerarmy-privacy-policy
source_date: '2026-11-10'
source_filename: testerarmy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tester.army/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Testerarmy\naid: testerarmy\nurl: https://tester.army/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name (as provided by your OAuth provider)\n- category: contact\n  text: Email address\n- category: identifying\n  text: OAuth provider account identifiers\n- category: financial\n  text: We store only Stripe customer IDs, subscription IDs, plan names, and subscription status for account management.\n- category: behavioral\n  text: Feature usage events (pages visited, actions taken, test runs executed)\n- category: device\n  text:\
  \ IP address, browser type, device information\n- category: communication\n  text: Chat conversation history\n- category: other\n  text: Website credentials (username/password) - stored encrypted with AES-256-GCM\n- category: other\n  text: Screenshots captured during test execution\npurposes:\n- purpose: Provide, maintain, and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Process payments and subscriptions\n  text: Process payments and manage subscriptions through Stripe\n- purpose: Marketing communications\n  text: Send product updates, feature announcements, and marketing communications via Loops (you may unsubscribe\n    at any time)\n- purpose: Product analytics\n  text: Analyze product usage patterns to improve features, reliability, and user experience\n- purpose: Security and error monitoring\n  text: Monitor and fix errors, bugs, and security issues\nretention:\n- scope: Account data\n  period: for the lifetime of your account\n  text: Account\
  \ data - retained for the lifetime of your account\n- scope: Chat and message history\n  period: indefinitely while your account is active\n  text: Chat and message history - retained indefinitely while your account is active\n- scope: API keys\n  period: default 90 days\n  text: API keys - configurable expiration (default 90 days) or non-expiring\n- scope: Magic link tokens\n  period: 1 hour\n  text: Magic link tokens - expire after 1 hour\n- scope: Team invitations and join links\n  period: 7 days\n  text: Team invitations and join links - expire after 7 days\n- scope: Stream data (Redis)\n  period: 24 hours\n  text: Stream data (Redis) - automatically deleted after 24 hours\nresidency:\n- region: United States, European Union, and other countries\n  text: Your data may be processed in the United States, European Union, and other countries where our service providers\n    operate\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses and other lawful transfer\
  \ mechanisms where required by applicable\n    data protection laws.\nsubprocessors:\n  url: null\n  text: 'We use the following third-party services to operate the platform:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion\n  text: Account deletion is permanent and immediate. All associated personal data is deleted at the time of deletion,\n    except where retention is required by law (e.g., billing records).\nrights:\n- right: Access\n  text: Access your personal data we hold\n- right: Rectify\n  text: Rectify inaccurate or incomplete data\n- right: Erase\n  text: Erase your personal data\n- right: Port\n  text: Port your data to another service in a machine-readable format\n- right: Object\n  text: Object to processing based on legitimate interests\n- right: Restrict\n  text: Restrict processing in certain circumstances\n- right: Withdraw consent\n  text: Withdraw consent at any time where processing is based on consent\n- right: Delete (California)\n\
  \  text: Delete your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/testerarmy/privacy/testerarmy-privacy-policy.yml
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
summary_line: 33 quoted statements, read from Testerarmy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- QA
- Software Testing
- Browser Automation
- AI Agents
- Developer Tools
- CI/CD
- End-to-End Testing
- Mobile Testing
---
