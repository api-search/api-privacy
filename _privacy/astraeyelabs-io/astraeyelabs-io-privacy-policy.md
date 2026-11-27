---
api_specs:
- filename: astraeyelabs-io-openapi-generated.yml
  format: yaml
  label: AstraEye Labs API
  slug: astraeyelabs-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraeyelabs-io/openapi/_ae-authored/astraeyelabs-io-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, telephone number, country associated with the telephone number, password hash, multi-factor authentication settings
  - category: financial
    text: Subscription tier, plan and usage state, and payment identifiers.
  - category: financial
    text: Holdings, balances, symbols, quantities, cost basis, and account labels that you enter manually, import by file, or bring in through an account connection you authorize.
  - category: location
    text: IP address, browser or user-agent information, request and route metadata, cookie and session identifiers, logs, audit and security events, error reports, and diagnostic information
  - category: communication
    text: Messages you send to support and our responses.
  - category: behavioral
    text: Research projects, selected templates, analysis types, AI-generated findings, informational research artifacts, feedback, SAGE questions and answers, and usage/metering data.
  deletion:
    route: Email privacy@astraeyelabs.io or account settings
    text: When you close your account, we erase or de-identify your personal information as described in that policy, retaining only what is required for legal or recordkeeping purposes.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, and secure the platform and account
    text: Provide, operate, and secure the platform and your account.
  - purpose: Generate AI-assisted research and SAGE answers
    text: Generate AI-assisted research, analytics, dashboards, and SAGE answers.
  - purpose: Billing and subscriptions
    text: Process subscriptions, credits, usage limits, and billing.
  - purpose: Advertising measurement
    text: Measure how people find AstraEye Labs, and reach people who may be interested in it, as described in Section 11.
  residency:
  - region: United States
    text: Your information is stored and processed in the United States.
  retention:
  - period: up to 30 days
    scope: Authentication sessions
    text: Authentication sessions have an absolute lifetime of up to 30 days.
  - period: up to two years
    scope: Security and administrative audit logs
    text: Security and administrative audit logs are generally retained for up to two years.
  - period: 30 days
    scope: Generated audio objects
    text: generated audio objects are deleted from active storage no later than 30 days after creation.
  - period: five minutes
    scope: Security codes
    text: Security codes become invalid after five minutes;
  rights:
  - right: Right to know / access
    text: Right to know / access the personal information we hold about you and how we use and disclose it (Cal. Civ. Code §§ 1798.100, 1798.110, 1798.115).
  - right: Right to correct
    text: Right to correct inaccurate personal information (Cal. Civ. Code § 1798.106).
  - right: Right to delete
    text: Right to delete your personal information (Cal. Civ. Code § 1798.105).
  - right: Right to data portability
    text: Right to data portability - obtain a copy in a portable format.
  - right: Right to opt out of sale or sharing
    text: Right to opt out of the sale or sharing of personal information and targeted advertising (Cal. Civ. Code § 1798.120).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information for money or other valuable consideration.
  subprocessors:
    text: A current list of material service providers that process personal information on our behalf, and the categories of data and services involved, may be maintained in a separate public subprocessor notice.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AstraEye Labs
provenance_date: '2026-11-09'
provider_name: AstraEye Labs
provider_slug: astraeyelabs-io
slug: astraeyelabs-io-privacy-policy
source_date: '2026-11-09'
source_filename: astraeyelabs-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://astraeyelabs.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AstraEye Labs\naid: astraeyelabs-io\nurl: https://astraeyelabs.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, telephone number, country associated with the telephone number, password hash, multi-factor\n    authentication settings\n- category: financial\n  text: Subscription tier, plan and usage state, and payment identifiers.\n- category: financial\n  text: Holdings, balances, symbols, quantities, cost basis, and account labels that you enter manually, import\n    by file, or bring in through an account connection\
  \ you authorize.\n- category: location\n  text: IP address, browser or user-agent information, request and route metadata, cookie and session identifiers,\n    logs, audit and security events, error reports, and diagnostic information\n- category: communication\n  text: Messages you send to support and our responses.\n- category: behavioral\n  text: Research projects, selected templates, analysis types, AI-generated findings, informational research artifacts,\n    feedback, SAGE questions and answers, and usage/metering data.\npurposes:\n- purpose: Provide, operate, and secure the platform and account\n  text: Provide, operate, and secure the platform and your account.\n- purpose: Generate AI-assisted research and SAGE answers\n  text: Generate AI-assisted research, analytics, dashboards, and SAGE answers.\n- purpose: Billing and subscriptions\n  text: Process subscriptions, credits, usage limits, and billing.\n- purpose: Advertising measurement\n  text: Measure how people find AstraEye\
  \ Labs, and reach people who may be interested in it, as described in Section\n    11.\nretention:\n- scope: Authentication sessions\n  period: up to 30 days\n  text: Authentication sessions have an absolute lifetime of up to 30 days.\n- scope: Security and administrative audit logs\n  period: up to two years\n  text: Security and administrative audit logs are generally retained for up to two years.\n- scope: Generated audio objects\n  period: 30 days\n  text: generated audio objects are deleted from active storage no later than 30 days after creation.\n- scope: Security codes\n  period: five minutes\n  text: Security codes become invalid after five minutes;\nresidency:\n- region: United States\n  text: Your information is stored and processed in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: A current list of material service providers that process personal information on our behalf, and the categories\n    of data and services involved, may be maintained in a\
  \ separate public subprocessor notice.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@astraeyelabs.io or account settings\n  text: When you close your account, we erase or de-identify your personal information as described in that policy,\n    retaining only what is required for legal or recordkeeping purposes.\nrights:\n- right: Right to know / access\n  text: Right to know / access the personal information we hold about you and how we use and disclose it (Cal. Civ.\n    Code §§ 1798.100, 1798.110, 1798.115).\n- right: Right to correct\n  text: Right to correct inaccurate personal information (Cal. Civ. Code § 1798.106).\n- right: Right to delete\n  text: Right to delete your personal information (Cal. Civ. Code § 1798.105).\n- right: Right to data portability\n  text: Right to data portability - obtain a copy in a portable format.\n- right: Right to opt out of sale or sharing\n  text: Right to opt out of the sale or sharing of personal information\
  \ and targeted advertising (Cal. Civ. Code\n    § 1798.120).\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information for money or other valuable consideration.\n"
source_yaml_url: https://artifacts.apis.io/astraeyelabs-io/privacy/astraeyelabs-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from AstraEye Labs's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Cryptocurrency
- Stocks
- Research
---
