---
api_specs:
- filename: seekrit-dev-docs-openapi-generated.yml
  format: yaml
  label: seekrit-dev docs API
  slug: docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seekrit-dev/openapi/_ae-authored/seekrit-dev-docs-openapi-generated.yml
- filename: seekrit-dev-guides-openapi-generated.yml
  format: yaml
  label: seekrit-dev guides API
  slug: guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seekrit-dev/openapi/_ae-authored/seekrit-dev-guides-openapi-generated.yml
- filename: seekrit-dev-reference-openapi-generated.yml
  format: yaml
  label: seekrit-dev reference API
  slug: reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seekrit-dev/openapi/_ae-authored/seekrit-dev-reference-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and identity information. When you sign up, we (through our authentication provider, Stytch) collect your email address, name, and authentication details
  - category: financial
    text: Billing information. If you subscribe to a paid plan, our payment processor, Stripe, collects your payment details directly; we receive your subscription status, plan, and billing metadata, not your full card number.
  - category: device
    text: Device and log data. Standard request metadata our infrastructure provider, Cloudflare, processes to serve traffic and defend against abuse — IP address, user agent, timestamps, and request paths.
  - category: communication
    text: Communications. If you email us (for support, security reports, or otherwise), we keep that correspondence and any information you choose to include in it.
  - category: behavioral
    text: Usage data. Sampled, metered counts of activity such as secret resolves, used to calculate usage and to detect abuse.
  deletion:
    route: dashboard or account closure
    text: You can delete secrets, environments, applications, or your entire organization from the dashboard. Closing your account triggers the retention period described above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and secure the Service
    text: 'We use the information above to: operate and secure the Service'
  - purpose: calculate usage and process billing
    text: calculate usage and process billing
  - purpose: detect and prevent abuse or security incidents
    text: detect, investigate, and prevent abuse or security incidents
  retention:
  - period: as long as your account is active
    scope: account and organization metadata
    text: We retain account and organization metadata for as long as your account is active
  - period: as long as the organization exists (or as required by applicable law)
    scope: audit log entries
    text: audit log entries as an append-only record for as long as the organization exists (or as required by applicable law)
  rights:
  - right: access
    text: Access and export. You can view and export your organization's data — secrets, metadata, and audit history — directly from the dashboard or CLI at any time.
  - right: correct, delete, or receive a copy
    text: Depending on where you live, you may have rights to access, correct, delete, or receive a copy of your personal information, or to object to or restrict certain processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Cloudflare (hosting, database, key-value storage, usage metering, and transactional email delivery), Stytch (authentication), and Stripe (payment processing) each process the data described above solely to provide their part of the Service
    url: null
  transfers:
  - mechanism: other
    text: Where required, we rely on appropriate safeguards (such as standard contractual clauses) for these transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: seekrit-dev
provenance_date: '2026-11-10'
provider_name: seekrit-dev
provider_slug: seekrit-dev
slug: seekrit-dev-privacy-policy
source_date: '2026-11-10'
source_filename: seekrit-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://seekrit.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: seekrit-dev\naid: seekrit-dev\nurl: https://seekrit.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and identity information. When you sign up, we (through our authentication provider, Stytch) collect\n    your email address, name, and authentication details\n- category: financial\n  text: Billing information. If you subscribe to a paid plan, our payment processor, Stripe, collects your payment\n    details directly; we receive your subscription status, plan, and billing metadata, not your full card number.\n- category:\
  \ device\n  text: Device and log data. Standard request metadata our infrastructure provider, Cloudflare, processes to serve\n    traffic and defend against abuse — IP address, user agent, timestamps, and request paths.\n- category: communication\n  text: Communications. If you email us (for support, security reports, or otherwise), we keep that correspondence\n    and any information you choose to include in it.\n- category: behavioral\n  text: Usage data. Sampled, metered counts of activity such as secret resolves, used to calculate usage and to\n    detect abuse.\npurposes:\n- purpose: operate and secure the Service\n  text: 'We use the information above to: operate and secure the Service'\n- purpose: calculate usage and process billing\n  text: calculate usage and process billing\n- purpose: detect and prevent abuse or security incidents\n  text: detect, investigate, and prevent abuse or security incidents\nretention:\n- scope: account and organization metadata\n  period: as long as\
  \ your account is active\n  text: We retain account and organization metadata for as long as your account is active\n- scope: audit log entries\n  period: as long as the organization exists (or as required by applicable law)\n  text: audit log entries as an append-only record for as long as the organization exists (or as required by applicable\n    law)\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where required, we rely on appropriate safeguards (such as standard contractual clauses) for these transfers.\nsubprocessors:\n  url: null\n  text: Cloudflare (hosting, database, key-value storage, usage metering, and transactional email delivery), Stytch\n    (authentication), and Stripe (payment processing) each process the data described above solely to provide their\n    part of the Service\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard or account closure\n  text: You can delete secrets, environments, applications, or your entire organization\
  \ from the dashboard. Closing\n    your account triggers the retention period described above.\nrights:\n- right: access\n  text: Access and export. You can view and export your organization's data — secrets, metadata, and audit history\n    — directly from the dashboard or CLI at any time.\n- right: correct, delete, or receive a copy\n  text: Depending on where you live, you may have rights to access, correct, delete, or receive a copy of your personal\n    information, or to object to or restrict certain processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/seekrit-dev/privacy/seekrit-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from seekrit-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Secrets Management
- Encryption
- Cloudflare
---
