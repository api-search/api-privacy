---
api_specs:
- filename: buildonto-dev-batch-api-openapi.yml
  format: yaml
  label: Onto Batch API
  slug: buildonto-dev-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildonto-dev/openapi/buildonto-dev-batch-api-openapi.yml
- filename: buildonto-dev-extract-api-openapi.yml
  format: yaml
  label: Onto Extract API
  slug: buildonto-dev-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildonto-dev/openapi/buildonto-dev-extract-api-openapi.yml
- filename: buildonto-dev-map-api-openapi.yml
  format: yaml
  label: Onto Map API
  slug: buildonto-dev-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildonto-dev/openapi/buildonto-dev-map-api-openapi.yml
- filename: buildonto-dev-read-api-openapi.yml
  format: yaml
  label: Onto Read API
  slug: buildonto-dev-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildonto-dev/openapi/buildonto-dev-read-api-openapi.yml
- filename: buildonto-dev-read-score-api-openapi.yml
  format: yaml
  label: Onto Read + Score API
  slug: buildonto-dev-read-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildonto-dev/openapi/buildonto-dev-read-score-api-openapi.yml
- filename: buildonto-dev-score-api-openapi.yml
  format: yaml
  label: Onto Score API
  slug: buildonto-dev-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildonto-dev/openapi/buildonto-dev-score-api-openapi.yml
- filename: buildonto-dev-usage-api-openapi.yml
  format: yaml
  label: Onto Usage API
  slug: buildonto-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildonto-dev/openapi/buildonto-dev-usage-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email, and your name and company if you gave them at signup.
  - category: financial
    text: Your plan, purchases and credit balance.
  - category: device
    text: the visitor's full user-agent
  - category: communication
    text: your message, email and plan when you contact support
  deletion:
    route: Email founder@buildonto.dev
    text: email founder@buildonto.dev with the subject “Delete my Onto account”.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Billing and subscriptions
    text: Billing and subscriptions Your email, plan and purchases. Card details stay with Polar
  - purpose: Email
    text: Email Resend sends the welcome email and your support messages.
  - purpose: Hosting
    text: Hosting, and Vercel KV (run by Upstash) for short-lived data
  residency:
  - region: Service regions
    text: With the services above, in the regions they run. We don't offer a single-region option.
  retention:
  - period: An hour
    scope: Page and Markdown cache
    text: An hour A read's page and Markdown, in the cache
  - period: A month
    scope: Quota counters
    text: A month Quota counters, which reset on the 1st
  - period: 30 days
    scope: MCP refresh token
    text: 30 days An MCP refresh token, unless it's used first
  - period: Until you delete it
    scope: Saved report
    text: Until you delete it
  rights:
  - right: Access, correct, delete
    text: Access, correct, delete.
  - right: See, correct, delete or restrict
    text: Under GDPR, UK GDPR, CCPA or India's DPDP Act you may have the right to see, correct, delete or restrict what we hold about you.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never Sell your data, or anything you send us
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Onto
provenance_date: '2026-11-09'
provider_name: Onto
provider_slug: buildonto-dev
slug: buildonto-dev-privacy-policy
source_date: '2026-11-09'
source_filename: buildonto-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://buildonto.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Onto\naid: buildonto-dev\nurl: https://buildonto.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email, and your name and company if you gave them at signup.\n- category: financial\n  text: Your plan, purchases and credit balance.\n- category: device\n  text: the visitor's full user-agent\n- category: communication\n  text: your message, email and plan when you contact support\npurposes:\n- purpose: Billing and subscriptions\n  text: Billing and subscriptions Your email, plan and purchases. Card details stay with\
  \ Polar\n- purpose: Email\n  text: Email Resend sends the welcome email and your support messages.\n- purpose: Hosting\n  text: Hosting, and Vercel KV (run by Upstash) for short-lived data\nretention:\n- scope: Page and Markdown cache\n  period: An hour\n  text: An hour A read's page and Markdown, in the cache\n- scope: Quota counters\n  period: A month\n  text: A month Quota counters, which reset on the 1st\n- scope: MCP refresh token\n  period: 30 days\n  text: 30 days An MCP refresh token, unless it's used first\n- scope: Saved report\n  period: Until you delete it\n  text: Until you delete it\nresidency:\n- region: Service regions\n  text: With the services above, in the regions they run. We don't offer a single-region option.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email founder@buildonto.dev\n  text: email founder@buildonto.dev with the subject “Delete my Onto account”.\nrights:\n- right: Access,\
  \ correct, delete\n  text: Access, correct, delete.\n- right: See, correct, delete or restrict\n  text: Under GDPR, UK GDPR, CCPA or India's DPDP Act you may have the right to see, correct, delete or restrict\n    what we hold about you.\nsale_or_sharing:\n  stance: prohibited\n  text: We never Sell your data, or anything you send us\n"
source_yaml_url: https://artifacts.apis.io/buildonto-dev/privacy/buildonto-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Onto's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Content
- Markdown
- Read API
- Platform
---
