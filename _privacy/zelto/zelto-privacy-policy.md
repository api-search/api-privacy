---
api_specs:
- filename: zelto-action-checks-api-openapi.yml
  format: yaml
  label: Zelto Action checks API
  slug: zelto-action-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-action-checks-api-openapi.yml
- filename: zelto-agents-api-openapi.yml
  format: yaml
  label: Zelto Agents API
  slug: zelto-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-agents-api-openapi.yml
- filename: zelto-buckets-api-openapi.yml
  format: yaml
  label: Zelto Buckets API
  slug: zelto-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-buckets-api-openapi.yml
- filename: zelto-companies-api-openapi.yml
  format: yaml
  label: Zelto Companies API
  slug: zelto-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-companies-api-openapi.yml
- filename: zelto-conversations-api-openapi.yml
  format: yaml
  label: Zelto Conversations API
  slug: zelto-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-conversations-api-openapi.yml
- filename: zelto-customer-metrics-api-openapi.yml
  format: yaml
  label: Zelto Customer Metrics API
  slug: zelto-customer-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-customer-metrics-api-openapi.yml
- filename: zelto-experiments-api-openapi.yml
  format: yaml
  label: Zelto Experiments API
  slug: zelto-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-experiments-api-openapi.yml
- filename: zelto-findings-api-openapi.yml
  format: yaml
  label: Zelto Findings API
  slug: zelto-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-findings-api-openapi.yml
- filename: zelto-organizations-api-openapi.yml
  format: yaml
  label: Zelto Organizations API
  slug: zelto-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-organizations-api-openapi.yml
- filename: zelto-reports-api-openapi.yml
  format: yaml
  label: Zelto Reports API
  slug: zelto-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-reports-api-openapi.yml
- filename: zelto-reviews-api-openapi.yml
  format: yaml
  label: Zelto Reviews API
  slug: zelto-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zelto/openapi/zelto-reviews-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email, organization name, role, password (stored only as a hash), and authentication identifiers
  - category: communication
    text: Call recordings and audio, transcripts, agent system prompts and configuration, call metadata (timestamps, phone numbers, provider identifiers, durations)
  - category: device
    text: Log data, device and browser information, IP address, pages viewed, feature usage, and diagnostic and performance data.
  - category: financial
    text: Plan, usage counts, and billing contact details. Card payments are processed by our payment provider; we do not store full card numbers.
  deletion:
    route: Email privacy@zelto.ai with a deletion request
    text: When an account is closed, or on a valid deletion request, we delete or de-identify personal information within a commercially reasonable period
  dpa:
    available: true
    text: Our handling of customer content is governed by our agreement with the customer (including any Data Processing Addendum).
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: Provide, operate, and secure the Services, including analyzing calls and generating findings.
  - purpose: Account authentication
    text: Authenticate users, manage accounts, and enforce access controls.
  - purpose: Billing
    text: Process transactions and manage billing.
  - purpose: Product improvement
    text: Monitor, debug, and improve the Services, and develop new features.
  - purpose: Fraud and security
    text: Detect, prevent, and respond to fraud, abuse, and security incidents.
  residency:
  - region: United States
    text: We host and operate the Services in the United States (AWS us-east-1 ).
  retention:
  - period: null
    scope: Account information
    text: We keep account information for as long as your account is active and as needed to provide the Services.
  - period: rolling schedule
    scope: Backups
    text: Backups are purged on a rolling schedule.
  rights:
  - right: access
    text: Depending on where you live, you may have rights to access, correct, delete, port, or restrict the processing of your personal information
  - right: object
    text: to object to certain processing, and to withdraw consent.
  role:
    text: For account and website data (the information you give us to sign up and use Zelto), Zelto is the controller .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information and do not share it for cross-context behavioral advertising.
  subprocessors:
    text: A current, complete list of sub-processors is available on request at privacy@zelto.ai .
    url: null
  transfers:
  - mechanism: SCC
    text: Where we transfer personal data from the EEA, UK, or Switzerland, we rely on appropriate safeguards such as the Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zelto
provenance_date: '2026-11-10'
provider_name: Zelto
provider_slug: zelto
slug: zelto-privacy-policy
source_date: '2026-11-10'
source_filename: zelto-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zelto.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zelto\naid: zelto\nurl: https://zelto.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account and website data (the information you give us to sign up and use Zelto), Zelto is the controller\n    .\ndata_categories:\n- category: identifying\n  text: Name, work email, organization name, role, password (stored only as a hash), and authentication identifiers\n- category: communication\n  text: Call recordings and audio, transcripts, agent system prompts and configuration, call metadata (timestamps,\n    phone numbers, provider identifiers, durations)\n- category: device\n  text: Log data,\
  \ device and browser information, IP address, pages viewed, feature usage, and diagnostic and performance\n    data.\n- category: financial\n  text: Plan, usage counts, and billing contact details. Card payments are processed by our payment provider; we\n    do not store full card numbers.\npurposes:\n- purpose: Provide and operate the Services\n  text: Provide, operate, and secure the Services, including analyzing calls and generating findings.\n- purpose: Account authentication\n  text: Authenticate users, manage accounts, and enforce access controls.\n- purpose: Billing\n  text: Process transactions and manage billing.\n- purpose: Product improvement\n  text: Monitor, debug, and improve the Services, and develop new features.\n- purpose: Fraud and security\n  text: Detect, prevent, and respond to fraud, abuse, and security incidents.\nretention:\n- scope: Account information\n  period: null\n  text: We keep account information for as long as your account is active and as needed to provide\
  \ the Services.\n- scope: Backups\n  period: rolling schedule\n  text: Backups are purged on a rolling schedule.\nresidency:\n- region: United States\n  text: We host and operate the Services in the United States (AWS us-east-1 ).\ntransfers:\n- mechanism: SCC\n  text: Where we transfer personal data from the EEA, UK, or Switzerland, we rely on appropriate safeguards such\n    as the Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: A current, complete list of sub-processors is available on request at privacy@zelto.ai .\ndpa:\n  available: true\n  url: null\n  text: Our handling of customer content is governed by our agreement with the customer (including any Data Processing\n    Addendum).\ndeletion:\n  route: Email privacy@zelto.ai with a deletion request\n  text: When an account is closed, or on a valid deletion request, we delete or de-identify personal information\n    within a commercially reasonable period\nrights:\n- right: access\n  text: Depending on where you\
  \ live, you may have rights to access, correct, delete, port, or restrict the processing\n    of your personal information\n- right: object\n  text: to object to certain processing, and to withdraw consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information and do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/zelto/privacy/zelto-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Zelto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Voice AI
- QA
- Production
- Analytics
- Monitoring
---
