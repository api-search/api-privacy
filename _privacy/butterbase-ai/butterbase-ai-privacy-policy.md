---
api_specs:
- filename: butterbase-ai-openapi-generated.yml
  format: yaml
  label: Butterbase API
  slug: butterbase-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterbase-ai/openapi/_ae-authored/butterbase-ai-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up, we collect your name, email address, and a securely hashed password.
  - category: financial
    text: We store your Stripe customer identifier, current plan, and billing history.
  - category: device
    text: We collect server logs including IP addresses, request timestamps, and error messages for debugging and security.
  - category: communication
    text: If you contact us for support, we retain your contact information and the contents of that correspondence.
  - category: behavioral
    text: We count API calls, storage used, and AI tokens consumed to enforce plan limits and power your usage dashboard.
  deletion:
    route: Through the Butterbase dashboard
    text: You may request to access, correct, export, or delete your personal information at any time through the Butterbase dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate platform
    text: Provide and operate the Butterbase platform
  - purpose: Account authentication and security
    text: Authenticate your account and keep it secure
  - purpose: Billing
    text: Process billing via Stripe
  - purpose: Product improvement
    text: Improve the platform using aggregated, anonymised usage patterns
  retention:
  - period: Until account deletion
    scope: Account information
    text: Account information Until account deletion
  - period: Until app deletion, or 30 days after account deletion
    scope: App data
    text: App data (databases, files) Until app deletion, or 30 days after account deletion
  - period: 7 years
    scope: Payment records
    text: Payment records 7 years
  - period: 30 days
    scope: Logs
    text: Logs are retained for 30 days.
  rights:
  - right: access
    text: You may request to access, correct, export, or delete your personal information at any time through the Butterbase dashboard.
  - right: export
    text: Your app's database can be exported in standard PostgreSQL format at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'We share personal information only with the following service providers, who are bound by confidentiality obligations: Provider Purpose Amazon Web Services Cloud infrastructure and file storage Stripe, Inc. Payment processing Cloudflare, Inc. Frontend deployment OpenRouter AI model routing'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Butterbase
provenance_date: '2026-11-09'
provider_name: Butterbase
provider_slug: butterbase-ai
slug: butterbase-ai-privacy-policy
source_date: '2026-11-09'
source_filename: butterbase-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://butterbase.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Butterbase\naid: butterbase-ai\nurl: https://butterbase.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up, we collect your name, email address, and a securely hashed password.\n- category: financial\n  text: We store your Stripe customer identifier, current plan, and billing history.\n- category: device\n  text: We collect server logs including IP addresses, request timestamps, and error messages for debugging and\n    security.\n- category: communication\n  text: If you contact us for support, we retain\
  \ your contact information and the contents of that correspondence.\n- category: behavioral\n  text: We count API calls, storage used, and AI tokens consumed to enforce plan limits and power your usage dashboard.\npurposes:\n- purpose: Provide and operate platform\n  text: Provide and operate the Butterbase platform\n- purpose: Account authentication and security\n  text: Authenticate your account and keep it secure\n- purpose: Billing\n  text: Process billing via Stripe\n- purpose: Product improvement\n  text: Improve the platform using aggregated, anonymised usage patterns\nretention:\n- scope: Account information\n  period: Until account deletion\n  text: Account information Until account deletion\n- scope: App data\n  period: Until app deletion, or 30 days after account deletion\n  text: App data (databases, files) Until app deletion, or 30 days after account deletion\n- scope: Payment records\n  period: 7 years\n  text: Payment records 7 years\n- scope: Logs\n  period: 30 days\n \
  \ text: Logs are retained for 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share personal information only with the following service providers, who are bound by confidentiality\n    obligations: Provider Purpose Amazon Web Services Cloud infrastructure and file storage Stripe, Inc. Payment\n    processing Cloudflare, Inc. Frontend deployment OpenRouter AI model routing'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Through the Butterbase dashboard\n  text: You may request to access, correct, export, or delete your personal information at any time through the\n    Butterbase dashboard.\nrights:\n- right: access\n  text: You may request to access, correct, export, or delete your personal information at any time through the\n    Butterbase dashboard.\n- right: export\n  text: Your app's database can be exported in standard PostgreSQL format at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal\
  \ information.\n"
source_yaml_url: https://artifacts.apis.io/butterbase-ai/privacy/butterbase-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Butterbase's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Backend
- Business
- Agent-Native
- Platform
---
