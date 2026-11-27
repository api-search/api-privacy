---
api_specs:
- filename: sourcebot-enterprise-ee-api-openapi.yml
  format: yaml
  label: Sourcebot Enterprise (EE) API
  slug: sourcebot-enterprise-ee-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-enterprise-ee-api-openapi.yml
- filename: sourcebot-git-api-openapi.yml
  format: yaml
  label: Sourcebot Git API
  slug: sourcebot-git-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-git-api-openapi.yml
- filename: sourcebot-repositories-api-openapi.yml
  format: yaml
  label: Sourcebot Repositories API
  slug: sourcebot-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-repositories-api-openapi.yml
- filename: sourcebot-search-navigation-api-openapi.yml
  format: yaml
  label: Sourcebot Search & Navigation API
  slug: sourcebot-search-navigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-search-navigation-api-openapi.yml
- filename: sourcebot-system-api-openapi.yml
  format: yaml
  label: Sourcebot System API
  slug: sourcebot-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-system-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information you submit in forms (name, email, company, message)
  - category: contact
    text: 'Account information: Email address, name, and any other profile information you provide.'
  - category: financial
    text: For paid subscriptions, your payment information, which is collected and processed directly by Stripe, our payment processor.
  - category: location
    text: approximate location from IP
  - category: behavioral
    text: Session recordings via PostHog, which capture how you interact with the site (clicks, navigation, scrolls).
  - category: device
    text: browser type
  - category: communication
    text: 'Usage content: Search queries you run, inputs you provide to AI features, and outputs the AI returns to you.'
  deletion:
    route: Delete account in app or email legal@sourcebot.dev
    text: You can delete your account at any time; we will delete your personal data within 30 days, except where retention is required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, and improve Sourcebot
    text: Provide, operate, and improve Sourcebot
  - purpose: Detect and prevent abuse, fraud, and security incidents
    text: Detect and prevent abuse, fraud, and security incidents
  - purpose: Comply with legal obligations
    text: Comply with our legal obligations
  residency:
  - region: United States
    text: We are based in the United States, and the information we collect is processed there.
  retention:
  - period: 12 months
    scope: Self-hosted product telemetry
    text: identifiable session-level events deleted within 12 months
  - period: lifetime of the deployment plus 24 months
    scope: Service Ping data
    text: Retained for the lifetime of the deployment plus 24 months
  - period: 30 days
    scope: Cloud accounts
    text: we will delete your personal data within 30 days, except where retention is required by law
  - period: 24 months
    scope: Website analytics
    text: Retained for up to 24 months.
  rights:
  - right: access
    text: you may have rights to access, correct, delete, export, or restrict our processing of your personal data
  - right: object or withdraw consent
    text: to object to processing or withdraw consent
  role:
    text: Taqla Inc. (“Sourcebot”, “we”, “us”) builds Sourcebot
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your personal information.
  subprocessors:
    text: 'We share personal information only with service providers who help us run our business, under contractual confidentiality and data protection obligations. These currently include: Stripe: payment processing'
    url: null
  transfers:
  - mechanism: other
    text: If you access Sourcebot from outside the US, you consent to your information being transferred to and processed in the US, subject to appropriate safeguards where required.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sourcebot
provenance_date: '2026-11-10'
provider_name: Sourcebot
provider_slug: sourcebot
slug: sourcebot-privacy-policy
source_date: '2026-11-10'
source_filename: sourcebot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sourcebot.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sourcebot\naid: sourcebot\nurl: https://www.sourcebot.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Taqla Inc. (“Sourcebot”, “we”, “us”) builds Sourcebot\ndata_categories:\n- category: identifying\n  text: Information you submit in forms (name, email, company, message)\n- category: contact\n  text: 'Account information: Email address, name, and any other profile information you provide.'\n- category: financial\n  text: For paid subscriptions, your payment information, which is collected and processed directly by Stripe, our\n    payment processor.\n- category: location\n  text:\
  \ approximate location from IP\n- category: behavioral\n  text: Session recordings via PostHog, which capture how you interact with the site (clicks, navigation, scrolls).\n- category: device\n  text: browser type\n- category: communication\n  text: 'Usage content: Search queries you run, inputs you provide to AI features, and outputs the AI returns to\n    you.'\npurposes:\n- purpose: Provide, operate, and improve Sourcebot\n  text: Provide, operate, and improve Sourcebot\n- purpose: Detect and prevent abuse, fraud, and security incidents\n  text: Detect and prevent abuse, fraud, and security incidents\n- purpose: Comply with legal obligations\n  text: Comply with our legal obligations\nretention:\n- scope: Self-hosted product telemetry\n  period: 12 months\n  text: identifiable session-level events deleted within 12 months\n- scope: Service Ping data\n  period: lifetime of the deployment plus 24 months\n  text: Retained for the lifetime of the deployment plus 24 months\n- scope: Cloud\
  \ accounts\n  period: 30 days\n  text: we will delete your personal data within 30 days, except where retention is required by law\n- scope: Website analytics\n  period: 24 months\n  text: Retained for up to 24 months.\nresidency:\n- region: United States\n  text: We are based in the United States, and the information we collect is processed there.\ntransfers:\n- mechanism: other\n  text: If you access Sourcebot from outside the US, you consent to your information being transferred to and processed\n    in the US, subject to appropriate safeguards where required.\nsubprocessors:\n  url: null\n  text: 'We share personal information only with service providers who help us run our business, under contractual\n    confidentiality and data protection obligations. These currently include: Stripe: payment processing'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in app or email legal@sourcebot.dev\n  text: You can delete your account at any time; we will\
  \ delete your personal data within 30 days, except where\n    retention is required by law.\nrights:\n- right: access\n  text: you may have rights to access, correct, delete, export, or restrict our processing of your personal data\n- right: object or withdraw consent\n  text: to object to processing or withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/sourcebot/privacy/sourcebot-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Sourcebot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code Search
- Code Intelligence
- Developer Tools
- Source Code
- Version Control
- MCP
- AI Coding Agents
- Enterprise Search
- Self-Hosted
---
