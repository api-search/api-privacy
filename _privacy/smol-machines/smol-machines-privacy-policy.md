---
api_specs:
- filename: smol-machines-apps-api-openapi.yml
  format: yaml
  label: Smol Machines Apps API
  slug: smol-machines-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-apps-api-openapi.yml
- filename: smol-machines-billing-api-openapi.yml
  format: yaml
  label: Smol Machines Billing API
  slug: smol-machines-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-billing-api-openapi.yml
- filename: smol-machines-containers-api-openapi.yml
  format: yaml
  label: Smol Machines Containers API
  slug: smol-machines-containers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-containers-api-openapi.yml
- filename: smol-machines-execution-api-openapi.yml
  format: yaml
  label: Smol Machines Execution API
  slug: smol-machines-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-execution-api-openapi.yml
- filename: smol-machines-health-api-openapi.yml
  format: yaml
  label: Smol Machines Health API
  slug: smol-machines-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-health-api-openapi.yml
- filename: smol-machines-images-api-openapi.yml
  format: yaml
  label: Smol Machines Images API
  slug: smol-machines-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-images-api-openapi.yml
- filename: smol-machines-logs-api-openapi.yml
  format: yaml
  label: Smol Machines Logs API
  slug: smol-machines-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-logs-api-openapi.yml
- filename: smol-machines-machines-api-openapi.yml
  format: yaml
  label: Smol Machines API
  slug: smol-machines-machines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-machines-api-openapi.yml
- filename: smol-machines-microvms-api-openapi.yml
  format: yaml
  label: Smol Machines MicroVMs API
  slug: smol-machines-microvms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-microvms-api-openapi.yml
- filename: smol-machines-nodes-api-openapi.yml
  format: yaml
  label: Smol Machines Nodes API
  slug: smol-machines-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-nodes-api-openapi.yml
- filename: smol-machines-operations-api-openapi.yml
  format: yaml
  label: Smol Machines Operations API
  slug: smol-machines-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-operations-api-openapi.yml
- filename: smol-machines-plans-api-openapi.yml
  format: yaml
  label: Smol Machines Plans API
  slug: smol-machines-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-plans-api-openapi.yml
- filename: smol-machines-pools-api-openapi.yml
  format: yaml
  label: Smol Machines Pools API
  slug: smol-machines-pools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-pools-api-openapi.yml
- filename: smol-machines-sandboxes-api-openapi.yml
  format: yaml
  label: Smol Machines Sandboxes API
  slug: smol-machines-sandboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-sandboxes-api-openapi.yml
- filename: smol-machines-tenants-api-openapi.yml
  format: yaml
  label: Smol Machines Tenants API
  slug: smol-machines-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-tenants-api-openapi.yml
- filename: smol-machines-tokens-api-openapi.yml
  format: yaml
  label: Smol Machines Tokens API
  slug: smol-machines-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-tokens-api-openapi.yml
- filename: smol-machines-usage-api-openapi.yml
  format: yaml
  label: Smol Machines Usage API
  slug: smol-machines-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-usage-api-openapi.yml
- filename: smol-machines-volumes-api-openapi.yml
  format: yaml
  label: Smol Machines Volumes API
  slug: smol-machines-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-volumes-api-openapi.yml
- filename: smol-machines-api-keys-api-openapi.yml
  format: yaml
  label: Smol Machines API Keys API
  slug: smol-machines-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smol-machines/openapi/smol-machines-api-keys-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address and name, received from your sign-in provider (Google or email login via Auth0)
  - category: financial
    text: payment card details are collected and stored by Stripe, our payment processor; we never see full card numbers.
  - category: behavioral
    text: metered consumption (CPU, memory, disk, egress)
  - category: device
    text: API request logs (timestamps, endpoints, status codes, IP addresses)
  deletion:
    route: Email request or account closure
    text: You can access, correct, export, or delete your personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating, metering, and billing
    text: Operating, metering, and billing the service.
  - purpose: Transactional email
    text: Transactional email — welcome, waitlist, activation, receipts, and low-balance warnings via Resend.
  - purpose: Security and abuse prevention
    text: Security, abuse prevention (including detection of prohibited workloads like cryptomining), and legal compliance.
  - purpose: Aggregated statistics
    text: Aggregated, non-identifying statistics about platform usage.
  residency:
  - region: United States
    text: Data is processed in the United States; by using the service you consent to that transfer.
  retention:
  - period: 30 days
    scope: Account closure
    text: When you close your account, we delete your machines and personal data within 30 days, except records we must keep for billing, tax, or legal reasons
  - period: null
    scope: Operational logs
    text: Operational logs are retained on a rolling basis and then discarded.
  rights:
  - right: access
    text: You can access, correct, export, or delete your personal data.
  - right: correct, export, delete
    text: You can access, correct, export, or delete your personal data.
  - right: statutory rights (EEA/UK GDPR, California CCPA)
    text: Depending on where you live (including the EEA/UK under GDPR and California under CCPA), you may have specific statutory rights to the same effect.
  role:
    text: smol machines, inc. is the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share it with advertisers.
  subprocessors:
    text: 'We share data only with the processors that run the service: Google Cloud — compute infrastructure, databases, and logs (US regions). Cloudflare — artifact/registry storage and networking. Auth0 (Okta) — authentication. Stripe — payments. Resend — transactional email delivery. Fly.io — website hosting.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Smol Machines
provenance_date: '2026-11-10'
provider_name: Smol Machines
provider_slug: smol-machines
slug: smol-machines-privacy-policy
source_date: '2026-11-10'
source_filename: smol-machines-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://smolmachines.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Smol Machines\naid: smol-machines\nurl: https://smolmachines.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: smol machines, inc. is the data controller for the personal data described here.\ndata_categories:\n- category: contact\n  text: your email address and name, received from your sign-in provider (Google or email login via Auth0)\n- category: financial\n  text: payment card details are collected and stored by Stripe, our payment processor; we never see full card numbers.\n- category: behavioral\n  text: metered consumption (CPU, memory, disk, egress)\n- category: device\n\
  \  text: API request logs (timestamps, endpoints, status codes, IP addresses)\npurposes:\n- purpose: Operating, metering, and billing\n  text: Operating, metering, and billing the service.\n- purpose: Transactional email\n  text: Transactional email — welcome, waitlist, activation, receipts, and low-balance warnings via Resend.\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention (including detection of prohibited workloads like cryptomining), and legal compliance.\n- purpose: Aggregated statistics\n  text: Aggregated, non-identifying statistics about platform usage.\nretention:\n- scope: Account closure\n  period: 30 days\n  text: When you close your account, we delete your machines and personal data within 30 days, except records we\n    must keep for billing, tax, or legal reasons\n- scope: Operational logs\n  period: null\n  text: Operational logs are retained on a rolling basis and then discarded.\nresidency:\n- region: United States\n  text: Data is processed\
  \ in the United States; by using the service you consent to that transfer.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data only with the processors that run the service: Google Cloud — compute infrastructure, databases,\n    and logs (US regions). Cloudflare — artifact/registry storage and networking. Auth0 (Okta) — authentication.\n    Stripe — payments. Resend — transactional email delivery. Fly.io — website hosting.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request or account closure\n  text: You can access, correct, export, or delete your personal data.\nrights:\n- right: access\n  text: You can access, correct, export, or delete your personal data.\n- right: correct, export, delete\n  text: You can access, correct, export, or delete your personal data.\n- right: statutory rights (EEA/UK GDPR, California CCPA)\n  text: Depending on where you live (including the EEA/UK under GDPR and California under CCPA), you may have specific\n\
  \    statutory rights to the same effect.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/smol-machines/privacy/smol-machines-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Smol Machines's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MicroVM
- Sandbox
- Virtualization
- Developer Tools
- Infrastructure
- AI Agents
- Code Execution
- Containers
- Cloud
---
