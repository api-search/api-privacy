---
api_specs:
- filename: craaft-io-attachments-api-openapi.yml
  format: yaml
  label: craaft Attachments API
  slug: craaft-io-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-attachments-api-openapi.yml
- filename: craaft-io-board-templates-api-openapi.yml
  format: yaml
  label: craaft Board Templates API
  slug: craaft-io-board-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-board-templates-api-openapi.yml
- filename: craaft-io-cards-api-openapi.yml
  format: yaml
  label: craaft Cards API
  slug: craaft-io-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-cards-api-openapi.yml
- filename: craaft-io-checklist-api-openapi.yml
  format: yaml
  label: craaft Checklist API
  slug: craaft-io-checklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-checklist-api-openapi.yml
- filename: craaft-io-columns-api-openapi.yml
  format: yaml
  label: craaft Columns API
  slug: craaft-io-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-columns-api-openapi.yml
- filename: craaft-io-comments-api-openapi.yml
  format: yaml
  label: craaft Comments API
  slug: craaft-io-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-comments-api-openapi.yml
- filename: craaft-io-imports-api-openapi.yml
  format: yaml
  label: craaft Imports API
  slug: craaft-io-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-imports-api-openapi.yml
- filename: craaft-io-invitations-api-openapi.yml
  format: yaml
  label: craaft Invitations API
  slug: craaft-io-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-invitations-api-openapi.yml
- filename: craaft-io-me-api-openapi.yml
  format: yaml
  label: craaft Me API
  slug: craaft-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-me-api-openapi.yml
- filename: craaft-io-members-api-openapi.yml
  format: yaml
  label: craaft Members API
  slug: craaft-io-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-members-api-openapi.yml
- filename: craaft-io-milestones-api-openapi.yml
  format: yaml
  label: craaft Milestones API
  slug: craaft-io-milestones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-milestones-api-openapi.yml
- filename: craaft-io-projects-api-openapi.yml
  format: yaml
  label: craaft Projects API
  slug: craaft-io-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-projects-api-openapi.yml
- filename: craaft-io-public-api-openapi.yml
  format: yaml
  label: craaft Public API
  slug: craaft-io-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-public-api-openapi.yml
- filename: craaft-io-search-api-openapi.yml
  format: yaml
  label: craaft Search API
  slug: craaft-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-search-api-openapi.yml
- filename: craaft-io-users-api-openapi.yml
  format: yaml
  label: craaft Users API
  slug: craaft-io-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-users-api-openapi.yml
- filename: craaft-io-version-api-openapi.yml
  format: yaml
  label: craaft Version API
  slug: craaft-io-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-version-api-openapi.yml
- filename: craaft-io-webhooks-api-openapi.yml
  format: yaml
  label: craaft Webhooks API
  slug: craaft-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craaft-io/openapi/craaft-io-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: your name, email address, and a hashed password.'
  - category: communication
    text: 'Email delivery data: when we send transactional email (mention notifications, invitations, password reset), the recipient address, subject and message are processed by Resend on our behalf.'
  - category: financial
    text: 'Billing data: handled by Paddle, our Merchant of Record. We receive your subscription status, plan, and an opaque customer identifier.'
  - category: device
    text: 'Usage data: minimal server logs (request paths, timing, status codes, anonymised IP) used to operate and debug the Service.'
  - category: behavioral
    text: Our public website pages (not the app) use Plausible, a cookieless analytics service, to count visits, the pages and referring sites they come from, and clicks through to sign up.
  deletion:
    route: Delete your account; or email support@craaft.io to exercise rights
    text: When you delete your account, we remove personal data from primary storage within 30 days and from backups within 90 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: sign you in, render your boards, deliver notifications you''ve opted into.'
  - purpose: Billing
    text: Bill you for the plan you've chosen.
  - purpose: Diagnostics and reliability
    text: Diagnose problems and improve reliability.
  - purpose: Account communications
    text: Communicate with you about your account and material changes to the Service.
  residency:
  - region: Region chosen by customer
    text: Our infrastructure runs on Google Cloud Platform in the region we've chosen for the workspace.
  retention:
  - period: null
    scope: Account and content data
    text: Account and content data are kept for as long as your account is active.
  - period: 30 days
    scope: Deleted account data in primary storage
    text: When you delete your account, we remove personal data from primary storage within 30 days and from backups within 90 days.
  - period: 90 days
    scope: Deleted account data in backups
    text: When you delete your account, we remove personal data from primary storage within 30 days and from backups within 90 days.
  - period: 7 years
    scope: Invoices and tax records
    text: 'Some records are kept longer when required by law: invoices and tax records for up to 7 years; security logs for 90 days.'
  - period: 90 days
    scope: Security logs
    text: 'Some records are kept longer when required by law: invoices and tax records for up to 7 years; security logs for 90 days.'
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correct
    text: Correct inaccurate data.
  - right: Export
    text: Export your data in a portable format (JSON or CSV, from each board's settings).
  - right: Delete
    text: Delete your account and your data.
  - right: Object or restrict
    text: Object to or restrict certain processing.
  - right: Withdraw consent
    text: Withdraw consent where we relied on it.
  - right: Complain
    text: Lodge a complaint with your local data-protection authority.
  role:
    text: Machine Republic (Pty) Ltd (“we”, “us”) operates the Service.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data, and we don't share it with advertisers.
  subprocessors:
    text: 'Paddle (paddle.com): payment processing, tax compliance, subscription management.'
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the Standard Contractual Clauses or equivalent transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: craaft
provenance_date: '2026-11-09'
provider_name: craaft
provider_slug: craaft-io
slug: craaft-io-privacy-policy
source_date: '2026-11-09'
source_filename: craaft-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://craaft.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: craaft\naid: craaft-io\nurl: https://craaft.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Machine Republic (Pty) Ltd (“we”, “us”) operates the Service.\ndata_categories:\n- category: identifying\n  text: 'Account information: your name, email address, and a hashed password.'\n- category: communication\n  text: 'Email delivery data: when we send transactional email (mention notifications, invitations, password reset),\n    the recipient address, subject and message are processed by Resend on our behalf.'\n- category: financial\n  text: 'Billing data: handled by Paddle, our Merchant\
  \ of Record. We receive your subscription status, plan, and\n    an opaque customer identifier.'\n- category: device\n  text: 'Usage data: minimal server logs (request paths, timing, status codes, anonymised IP) used to operate and\n    debug the Service.'\n- category: behavioral\n  text: Our public website pages (not the app) use Plausible, a cookieless analytics service, to count visits, the\n    pages and referring sites they come from, and clicks through to sign up.\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service: sign you in, render your boards, deliver notifications you''ve opted into.'\n- purpose: Billing\n  text: Bill you for the plan you've chosen.\n- purpose: Diagnostics and reliability\n  text: Diagnose problems and improve reliability.\n- purpose: Account communications\n  text: Communicate with you about your account and material changes to the Service.\nretention:\n- scope: Account and content data\n  period: null\n  text: Account and content data\
  \ are kept for as long as your account is active.\n- scope: Deleted account data in primary storage\n  period: 30 days\n  text: When you delete your account, we remove personal data from primary storage within 30 days and from backups\n    within 90 days.\n- scope: Deleted account data in backups\n  period: 90 days\n  text: When you delete your account, we remove personal data from primary storage within 30 days and from backups\n    within 90 days.\n- scope: Invoices and tax records\n  period: 7 years\n  text: 'Some records are kept longer when required by law: invoices and tax records for up to 7 years; security\n    logs for 90 days.'\n- scope: Security logs\n  period: 90 days\n  text: 'Some records are kept longer when required by law: invoices and tax records for up to 7 years; security\n    logs for 90 days.'\nresidency:\n- region: Region chosen by customer\n  text: Our infrastructure runs on Google Cloud Platform in the region we've chosen for the workspace.\ntransfers:\n- mechanism:\
  \ SCC\n  text: we rely on the Standard Contractual Clauses or equivalent transfer mechanisms.\nsubprocessors:\n  url: null\n  text: 'Paddle (paddle.com): payment processing, tax compliance, subscription management.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account; or email support@craaft.io to exercise rights\n  text: When you delete your account, we remove personal data from primary storage within 30 days and from backups\n    within 90 days.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correct\n  text: Correct inaccurate data.\n- right: Export\n  text: Export your data in a portable format (JSON or CSV, from each board's settings).\n- right: Delete\n  text: Delete your account and your data.\n- right: Object or restrict\n  text: Object to or restrict certain processing.\n- right: Withdraw consent\n  text: Withdraw consent where we relied on it.\n- right: Complain\n  text: Lodge a complaint with your\
  \ local data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data, and we don't share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/craaft-io/privacy/craaft-io-privacy-policy.yml
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
summary_line: 27 quoted statements, read from craaft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Task Management
- Kanban
- Project Management
- Productivity
- AI Agents
- MCP
- REST API
- Collaboration
---
