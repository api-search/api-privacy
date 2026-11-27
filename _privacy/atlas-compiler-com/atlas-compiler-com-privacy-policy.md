---
api_specs:
- filename: atlas-compiler-com-api-keys-api-openapi.yml
  format: yaml
  label: Atlas API Keys API
  slug: atlas-compiler-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-api-keys-api-openapi.yml
- filename: atlas-compiler-com-billing-api-openapi.yml
  format: yaml
  label: Atlas Billing API
  slug: atlas-compiler-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-billing-api-openapi.yml
- filename: atlas-compiler-com-execution-api-openapi.yml
  format: yaml
  label: Atlas Execution API
  slug: atlas-compiler-com-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-execution-api-openapi.yml
- filename: atlas-compiler-com-identity-api-openapi.yml
  format: yaml
  label: Atlas Identity API
  slug: atlas-compiler-com-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-identity-api-openapi.yml
- filename: atlas-compiler-com-invitations-api-openapi.yml
  format: yaml
  label: Atlas Invitations API
  slug: atlas-compiler-com-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-invitations-api-openapi.yml
- filename: atlas-compiler-com-jobs-api-openapi.yml
  format: yaml
  label: Atlas Jobs API
  slug: atlas-compiler-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-jobs-api-openapi.yml
- filename: atlas-compiler-com-members-api-openapi.yml
  format: yaml
  label: Atlas Members API
  slug: atlas-compiler-com-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-members-api-openapi.yml
- filename: atlas-compiler-com-projects-api-openapi.yml
  format: yaml
  label: Atlas Projects API
  slug: atlas-compiler-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-projects-api-openapi.yml
- filename: atlas-compiler-com-system-api-openapi.yml
  format: yaml
  label: Atlas System API
  slug: atlas-compiler-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-system-api-openapi.yml
- filename: atlas-compiler-com-usage-api-openapi.yml
  format: yaml
  label: Atlas Usage API
  slug: atlas-compiler-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-usage-api-openapi.yml
- filename: atlas-compiler-com-webhooks-api-openapi.yml
  format: yaml
  label: Atlas Webhooks API
  slug: atlas-compiler-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-webhooks-api-openapi.yml
- filename: atlas-compiler-com-workspaces-api-openapi.yml
  format: yaml
  label: Atlas Workspaces API
  slug: atlas-compiler-com-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-compiler-com/openapi/atlas-compiler-com-workspaces-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'User Identifier: An internal immutable ULID assigned to your user record and your corresponding external identity provider identifier (Clerk subject ID).'
  - category: contact
    text: 'Email Address: Your primary email address and email verification status.'
  - category: device
    text: client IP address, HTTP request method, request path, response status code, latency in milliseconds, user-agent string
  - category: financial
    text: Atlas stores your Stripe Customer ID, Stripe Subscription ID, current plan code
  - category: behavioral
    text: 'PostHog Product Analytics & Session Replay: Used to evaluate developer onboarding funnels, identify friction points in the interactive playground, and capture error diagnostics.'
  deletion:
    route: Dashboard or email to privacy address; automated deletion sequence after verified deletion event
    text: You may initiate account deletion directly through the Dashboard or by emailing [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provisioning
    text: Authenticating developers, executing compiler jobs, dispatching webhooks, and routing API calls.
  - purpose: Universal credit accounting
    text: Metering job execution costs, tracking active credit grants, and maintaining immutable financial records.
  - purpose: Security and abuse prevention
    text: Detecting unauthorized API key usage, preventing Server-Side Request Forgery (SSRF) against internal networks, and enforcing edge rate limits.
  - purpose: Transactional communications
    text: Sending essential administrative emails, such as workspace invitation links and critical billing alerts
  residency:
  - region: United States
    text: with core database and authorization storage located in the United States.
  retention:
  - period: active lifetime of your developer account
    scope: Account and workspace records
    text: 'Account & Workspace Records: Retained for the active lifetime of your developer account.'
  - period: null
    scope: Compiled web artifacts (R2/KV)
    text: 'Compiled Web Artifacts (R2/KV): Automatically purged seven (7) days ( 604,800 seconds) after compilation.'
  - period: up to seven (7) years
    scope: Financial and credit ledger
    text: Transactional credit ledger entries and invoices are retained for up to seven (7) years
  rights:
  - right: Access
    text: 'Right of Access: You may request a copy of the personal information we maintain about you.'
  - right: Rectification
    text: 'Right to Rectification: You may correct inaccurate or incomplete account information via your profile settings or by contacting us.'
  - right: Erasure
    text: 'Right to Erasure (Deletion): You may request the permanent erasure of your personal data as described in Section 8.'
  - right: Restriction and objection
    text: 'Right to Restriction & Objection: You may object to or request restrictions on certain processing activities where lawful grounds exist.'
  - right: Portability
    text: 'Right to Data Portability: You may request export of your workspace project data in structured, machine-readable formats.'
  role:
    text: Atlas is an independent developer infrastructure project located in India.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Atlas has never sold, rented, leased, or disclosed customer personal information to third parties for monetary or other valuable consideration, and will not do so.
  subprocessors:
    text: 'We share data only with verified infrastructure subprocessors strictly necessary to operate the Service:'
    url: null
  transfers:
  - mechanism: SCC
    text: including standard contractual clauses (SCCs) executed with our subprocessors.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Atlas
provenance_date: '2026-11-09'
provider_name: Atlas
provider_slug: atlas-compiler-com
slug: atlas-compiler-com-privacy-policy
source_date: '2026-11-09'
source_filename: atlas-compiler-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://atlas-compiler.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Atlas\naid: atlas-compiler-com\nurl: https://atlas-compiler.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Atlas is an independent developer infrastructure project located in India.\ndata_categories:\n- category: identifying\n  text: 'User Identifier: An internal immutable ULID assigned to your user record and your corresponding external\n    identity provider identifier (Clerk subject ID).'\n- category: contact\n  text: 'Email Address: Your primary email address and email verification status.'\n- category: device\n  text: client IP address, HTTP request method, request path,\
  \ response status code, latency in milliseconds, user-agent\n    string\n- category: financial\n  text: Atlas stores your Stripe Customer ID, Stripe Subscription ID, current plan code\n- category: behavioral\n  text: 'PostHog Product Analytics & Session Replay: Used to evaluate developer onboarding funnels, identify friction\n    points in the interactive playground, and capture error diagnostics.'\npurposes:\n- purpose: Service provisioning\n  text: Authenticating developers, executing compiler jobs, dispatching webhooks, and routing API calls.\n- purpose: Universal credit accounting\n  text: Metering job execution costs, tracking active credit grants, and maintaining immutable financial records.\n- purpose: Security and abuse prevention\n  text: Detecting unauthorized API key usage, preventing Server-Side Request Forgery (SSRF) against internal networks,\n    and enforcing edge rate limits.\n- purpose: Transactional communications\n  text: Sending essential administrative emails, such\
  \ as workspace invitation links and critical billing alerts\nretention:\n- scope: Account and workspace records\n  period: active lifetime of your developer account\n  text: 'Account & Workspace Records: Retained for the active lifetime of your developer account.'\n- scope: Compiled web artifacts (R2/KV)\n  period: null\n  text: 'Compiled Web Artifacts (R2/KV): Automatically purged seven (7) days ( 604,800 seconds) after compilation.'\n- scope: Financial and credit ledger\n  period: up to seven (7) years\n  text: Transactional credit ledger entries and invoices are retained for up to seven (7) years\nresidency:\n- region: United States\n  text: with core database and authorization storage located in the United States.\ntransfers:\n- mechanism: SCC\n  text: including standard contractual clauses (SCCs) executed with our subprocessors.\nsubprocessors:\n  url: null\n  text: 'We share data only with verified infrastructure subprocessors strictly necessary to operate the Service:'\ndpa:\n \
  \ available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard or email to privacy address; automated deletion sequence after verified deletion event\n  text: You may initiate account deletion directly through the Dashboard or by emailing [email protected] .\nrights:\n- right: Access\n  text: 'Right of Access: You may request a copy of the personal information we maintain about you.'\n- right: Rectification\n  text: 'Right to Rectification: You may correct inaccurate or incomplete account information via your profile settings\n    or by contacting us.'\n- right: Erasure\n  text: 'Right to Erasure (Deletion): You may request the permanent erasure of your personal data as described in\n    Section 8.'\n- right: Restriction and objection\n  text: 'Right to Restriction & Objection: You may object to or request restrictions on certain processing activities\n    where lawful grounds exist.'\n- right: Portability\n  text: 'Right to Data Portability: You may request export of your\
  \ workspace project data in structured, machine-readable\n    formats.'\nsale_or_sharing:\n  stance: prohibited\n  text: Atlas has never sold, rented, leased, or disclosed customer personal information to third parties for monetary\n    or other valuable consideration, and will not do so.\n"
source_yaml_url: https://artifacts.apis.io/atlas-compiler-com/privacy/atlas-compiler-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Atlas's own page on 2026-11-09.
synthetic: false
tags:
- Web Intelligence
- Data Pipeline
- Automation
- Artificial Intelligence
- Developer Tools
---
