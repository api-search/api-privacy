---
api_specs:
- filename: ezel-ai-openapi-generated.yml
  format: yaml
  label: Ezel API
  slug: ezel-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ezel-ai/openapi/_ae-authored/ezel-ai-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (used for passwordless authentication via magic links)
  - category: financial
    text: We do not store your full credit card numbers or CVV codes on our servers
  - category: contact
    text: Organization or company name (optional)
  - category: communication
    text: Chat conversations and queries submitted to the AI
  - category: device
    text: IP address (trimmed before being passed to third-party analytics), request metadata, and User-Agent string
  - category: behavioral
    text: Pages viewed, referring URL (where permitted), approximate country-level location, browser and device type, session duration, and interaction events
  deletion:
    route: In-app account deletion from the Settings page, or individual document and chat deletion
    text: You can delete your entire account from the Settings page in your account dashboard
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery and operations
    text: Process your documents and queries through our AI providers (Anthropic, OpenAI)
  - purpose: Billing and payments
    text: Calculate token usage and generate accurate billing
  - purpose: Security and compliance
    text: Detect, prevent, and address fraud, abuse, security incidents, and Terms of Service violations
  - purpose: Product improvement and research
    text: Develop new features and functionality based on user feedback
  residency:
  - region: United States
    text: Customer data is stored on secure servers located in the United States.
  retention:
  - period: the duration of your active account
    scope: Account information
    text: 'Account information: Retained for the duration of your active account'
  - period: Stored indefinitely while your account is active
    scope: Documents and chat history
    text: 'Documents and chat history: Stored indefinitely while your account is active, accessible to you at any time'
  - period: 24 consecutive months
    scope: Inactive accounts
    text: If your account remains inactive (no login or usage) for 24 consecutive months, we will send a notice to your registered email address
  rights:
  - right: Access
    text: 'Right to access: Request a copy of your personal data in a structured, commonly used format'
  - right: Correction
    text: 'Right to correct: Request correction of inaccurate or incomplete personal information'
  - right: Deletion
    text: 'Right to delete (Right to be Forgotten): Request deletion of your personal data, subject to legal obligations'
  - right: Portability
    text: 'Right to data portability: Request a copy of your data in a portable format (feature in development)'
  - right: Objection
    text: 'Right to object: Object to processing based on legitimate interests'
  - right: Restriction
    text: 'Right to restriction: Request that we limit how we process your personal data in certain circumstances'
  role:
    text: Ezel is the data controller responsible for the processing of your personal information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do NOT sell, rent, or trade your personal information. We never have, and we never will.
  subprocessors:
    text: For a complete, up-to-date list of all subprocessors with access to personal data, please see our Subprocessor List.
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): We and our US-based subprocessors (including Anthropic, OpenAI, Stripe, Supabase, Cloudflare, Google, Postmark, and EmailOctopus) have entered into the European Commission''s Standard Contractual Clauses (2021/914)'
  - mechanism: DPF
    text: Where a subprocessor is certified under the EU-US Data Privacy Framework (and the UK Extension / Swiss-US Data Privacy Framework), we may also rely on that certification as a lawful transfer mechanism.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ezel
provenance_date: '2026-11-09'
provider_name: Ezel
provider_slug: ezel-ai
slug: ezel-ai-privacy-policy
source_date: '2026-11-09'
source_filename: ezel-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ezel.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ezel\naid: ezel-ai\nurl: https://ezel.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Ezel is the data controller responsible for the processing of your personal information.\ndata_categories:\n- category: identifying\n  text: Email address (used for passwordless authentication via magic links)\n- category: financial\n  text: We do not store your full credit card numbers or CVV codes on our servers\n- category: contact\n  text: Organization or company name (optional)\n- category: communication\n  text: Chat conversations and queries submitted to the AI\n- category: device\n\
  \  text: IP address (trimmed before being passed to third-party analytics), request metadata, and User-Agent string\n- category: behavioral\n  text: Pages viewed, referring URL (where permitted), approximate country-level location, browser and device type,\n    session duration, and interaction events\npurposes:\n- purpose: Service delivery and operations\n  text: Process your documents and queries through our AI providers (Anthropic, OpenAI)\n- purpose: Billing and payments\n  text: Calculate token usage and generate accurate billing\n- purpose: Security and compliance\n  text: Detect, prevent, and address fraud, abuse, security incidents, and Terms of Service violations\n- purpose: Product improvement and research\n  text: Develop new features and functionality based on user feedback\nretention:\n- scope: Account information\n  period: the duration of your active account\n  text: 'Account information: Retained for the duration of your active account'\n- scope: Documents and chat history\n\
  \  period: Stored indefinitely while your account is active\n  text: 'Documents and chat history: Stored indefinitely while your account is active, accessible to you at any\n    time'\n- scope: Inactive accounts\n  period: 24 consecutive months\n  text: If your account remains inactive (no login or usage) for 24 consecutive months, we will send a notice to\n    your registered email address\nresidency:\n- region: United States\n  text: Customer data is stored on secure servers located in the United States.\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs): We and our US-based subprocessors (including Anthropic, OpenAI, Stripe,\n    Supabase, Cloudflare, Google, Postmark, and EmailOctopus) have entered into the European Commission''s Standard\n    Contractual Clauses (2021/914)'\n- mechanism: DPF\n  text: Where a subprocessor is certified under the EU-US Data Privacy Framework (and the UK Extension / Swiss-US\n    Data Privacy Framework), we may also rely on that\
  \ certification as a lawful transfer mechanism.\nsubprocessors:\n  url: null\n  text: For a complete, up-to-date list of all subprocessors with access to personal data, please see our Subprocessor\n    List.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app account deletion from the Settings page, or individual document and chat deletion\n  text: You can delete your entire account from the Settings page in your account dashboard\nrights:\n- right: Access\n  text: 'Right to access: Request a copy of your personal data in a structured, commonly used format'\n- right: Correction\n  text: 'Right to correct: Request correction of inaccurate or incomplete personal information'\n- right: Deletion\n  text: 'Right to delete (Right to be Forgotten): Request deletion of your personal data, subject to legal obligations'\n- right: Portability\n  text: 'Right to data portability: Request a copy of your data in a portable format (feature in development)'\n- right: Objection\n\
  \  text: 'Right to object: Object to processing based on legitimate interests'\n- right: Restriction\n  text: 'Right to restriction: Request that we limit how we process your personal data in certain circumstances'\nsale_or_sharing:\n  stance: prohibited\n  text: We do NOT sell, rent, or trade your personal information. We never have, and we never will.\n"
source_yaml_url: https://artifacts.apis.io/ezel-ai/privacy/ezel-ai-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Ezel's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Legal Tech
- Software-as-a-Service
- Platform
- Company
---
