---
api_specs:
- filename: agent-module-dev-checkout-api-openapi.yml
  format: yaml
  label: Agent Module Checkout API
  slug: agent-module-dev-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-checkout-api-openapi.yml
- filename: agent-module-dev-delta-api-openapi.yml
  format: yaml
  label: Agent Module Delta API
  slug: agent-module-dev-delta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-delta-api-openapi.yml
- filename: agent-module-dev-demo-api-openapi.yml
  format: yaml
  label: Agent Module Demo API
  slug: agent-module-dev-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-demo-api-openapi.yml
- filename: agent-module-dev-interest-api-openapi.yml
  format: yaml
  label: Agent Module Interest API
  slug: agent-module-dev-interest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-interest-api-openapi.yml
- filename: agent-module-dev-keys-api-openapi.yml
  format: yaml
  label: Agent Module Keys API
  slug: agent-module-dev-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-keys-api-openapi.yml
- filename: agent-module-dev-mcp-api-openapi.yml
  format: yaml
  label: Agent Module MCP API
  slug: agent-module-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-mcp-api-openapi.yml
- filename: agent-module-dev-referral-api-openapi.yml
  format: yaml
  label: Agent Module Referral API
  slug: agent-module-dev-referral-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-referral-api-openapi.yml
- filename: agent-module-dev-status-api-openapi.yml
  format: yaml
  label: Agent Module Status API
  slug: agent-module-dev-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-status-api-openapi.yml
- filename: agent-module-dev-telemetry-api-openapi.yml
  format: yaml
  label: Agent Module Telemetry API
  slug: agent-module-dev-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-telemetry-api-openapi.yml
- filename: agent-module-dev-trial-api-openapi.yml
  format: yaml
  label: Agent Module Trial API
  slug: agent-module-dev-trial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-trial-api-openapi.yml
- filename: agent-module-dev-verify-api-openapi.yml
  format: yaml
  label: Agent Module Verify API
  slug: agent-module-dev-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-verify-api-openapi.yml
- filename: agent-module-dev-waitlist-api-openapi.yml
  format: yaml
  label: Agent Module Waitlist API
  slug: agent-module-dev-waitlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-module-dev/openapi/agent-module-dev-waitlist-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: '**Email address** (used for key delivery and account communication)'
  - category: identifying
    text: '**Agent identifier** (`agent_id`) — a string you provide to identify your agent or account'
  - category: financial
    text: Stripe session IDs and subscription status
  - category: behavioral
    text: Request timestamp
  - category: device
    text: Vertical and node accessed
  - category: behavioral
    text: Confidence score you submit
  deletion:
    route: Email admin@agent-module.dev
    text: Request deletion of your account and associated records
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Issuing and managing membership keys
    text: Issuing and managing membership keys | Contract performance
  - purpose: Processing payments
    text: Processing payments | Contract performance
  - purpose: Rate limiting and abuse prevention
    text: Rate limiting and abuse prevention | Legitimate interest
  - purpose: Cohort progression (aggregate PoO scoring)
    text: Cohort progression (aggregate PoO scoring)
  - purpose: Legal compliance
    text: Legal compliance | Legal obligation
  residency:
  - region: United States
    text: All data is stored in **Cloudflare KV** (distributed key-value storage, US regions by default).
  retention:
  - period: Life of membership + 1 year
    scope: Membership key data
    text: Membership key data | Life of membership + 1 year
  - period: 24 hours
    scope: Trial key data
    text: Trial key data | 24 hours (auto-expires in KV)
  - period: 7 years
    scope: Payment records
    text: Payment records | 7 years (tax/legal requirement)
  - period: 2 years or until you request deletion
    scope: PoO/PoV telemetry
    text: PoO/PoV telemetry | 2 years or until you request deletion
  - period: Rolling 30-day window
    scope: API usage counters
    text: API usage counters | Rolling 30-day window
  - period: Until you unsubscribe or request deletion
    scope: Waitlist registrations
    text: Waitlist registrations | Until you unsubscribe or request deletion
  rights:
  - right: Access
    text: '**Access** your data: Contact us at admin@agent-module.dev with your email or agent_id'
  - right: Delete
    text: '**Delete** your data: Request deletion of your account and associated records'
  - right: Correct
    text: '**Correct** your data: Request corrections to inaccurate information'
  - right: Export
    text: '**Export** your data: Receive a copy of data we hold about you'
  - right: Restrict processing (EU/EEA)
    text: You have the additional rights to restrict processing and to lodge a complaint with your national supervisory authority.
  role:
    text: How Agent Module LLC collects, uses, and protects your data
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do **not** sell, rent, or share your data with third parties for marketing purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Module
provenance_date: '2026-11-09'
provider_name: Agent Module
provider_slug: agent-module-dev
slug: agent-module-dev-privacy-policy
source_date: '2026-11-09'
source_filename: agent-module-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agent-module.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Module\naid: agent-module-dev\nurl: https://agent-module.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: How Agent Module LLC collects, uses, and protects your data\ndata_categories:\n- category: contact\n  text: '**Email address** (used for key delivery and account communication)'\n- category: identifying\n  text: '**Agent identifier** (`agent_id`) — a string you provide to identify your agent or account'\n- category: financial\n  text: Stripe session IDs and subscription status\n- category: behavioral\n  text: Request timestamp\n- category: device\n  text: Vertical and node\
  \ accessed\n- category: behavioral\n  text: Confidence score you submit\npurposes:\n- purpose: Issuing and managing membership keys\n  text: Issuing and managing membership keys | Contract performance\n- purpose: Processing payments\n  text: Processing payments | Contract performance\n- purpose: Rate limiting and abuse prevention\n  text: Rate limiting and abuse prevention | Legitimate interest\n- purpose: Cohort progression (aggregate PoO scoring)\n  text: Cohort progression (aggregate PoO scoring)\n- purpose: Legal compliance\n  text: Legal compliance | Legal obligation\nretention:\n- scope: Membership key data\n  period: Life of membership + 1 year\n  text: Membership key data | Life of membership + 1 year\n- scope: Trial key data\n  period: 24 hours\n  text: Trial key data | 24 hours (auto-expires in KV)\n- scope: Payment records\n  period: 7 years\n  text: Payment records | 7 years (tax/legal requirement)\n- scope: PoO/PoV telemetry\n  period: 2 years or until you request deletion\n\
  \  text: PoO/PoV telemetry | 2 years or until you request deletion\n- scope: API usage counters\n  period: Rolling 30-day window\n  text: API usage counters | Rolling 30-day window\n- scope: Waitlist registrations\n  period: Until you unsubscribe or request deletion\n  text: Waitlist registrations | Until you unsubscribe or request deletion\nresidency:\n- region: United States\n  text: All data is stored in **Cloudflare KV** (distributed key-value storage, US regions by default).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email admin@agent-module.dev\n  text: Request deletion of your account and associated records\nrights:\n- right: Access\n  text: '**Access** your data: Contact us at admin@agent-module.dev with your email or agent_id'\n- right: Delete\n  text: '**Delete** your data: Request deletion of your account and associated records'\n- right: Correct\n  text: '**Correct** your data: Request corrections\
  \ to inaccurate information'\n- right: Export\n  text: '**Export** your data: Receive a copy of data we hold about you'\n- right: Restrict processing (EU/EEA)\n  text: You have the additional rights to restrict processing and to lodge a complaint with your national supervisory\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do **not** sell, rent, or share your data with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/agent-module-dev/privacy/agent-module-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Agent Module's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Knowledge Base
- Agents
- Platform
---
