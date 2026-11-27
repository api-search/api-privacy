---
api_specs:
- filename: 4dayweek-io-4dayweek-io-public-api-api-openapi.yml
  format: yaml
  label: 4dayweek-io 4dayweek.io Public API
  slug: 4dayweek-io-4dayweek-io-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/4dayweek-io/openapi/4dayweek-io-4dayweek-io-public-api-api-openapi.yml
- filename: 4dayweek-io-jobs-api-openapi.yml
  format: yaml
  label: 4dayweek-io Jobs API
  slug: 4dayweek-io-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/4dayweek-io/openapi/4dayweek-io-jobs-api-openapi.yml
- filename: 4dayweek-io-mcp-api-openapi.yml
  format: yaml
  label: 4dayweek-io MCP API
  slug: 4dayweek-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/4dayweek-io/openapi/4dayweek-io-mcp-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name and email address
  - category: contact
    text: Email address
  - category: financial
    text: Stripe customer identifier for billing purposes (we do not store credit card numbers or full payment details - these are held by Stripe)
  - category: biometric
    text: the selfies you uploaded (biometric data under UK GDPR Article 9, which we processed on your explicit consent)
  - category: device
    text: IP address - hashed using SHA-256 with a cryptographic salt before storage
  deletion:
    route: Account settings in dashboard, or email phil@4dayweek.io
    text: You can permanently delete your account and all associated data through the account settings in your dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: Necessary to provide the service you have requested, including creating your account, authenticating your identity, and maintaining your session.
  - purpose: Job applications
    text: You have requested that we transmit your application to the employer.
  - purpose: Analytics (hashed IP)
    text: Privacy-preserving usage analysis using irreversibly hashed IP addresses.
  - purpose: Billing
    text: Processing subscription and one-time purchase payments through Stripe
  residency:
  - region: United States (New York)
    text: Our primary infrastructure is hosted on DigitalOcean servers located in the United States (New York region).
  retention:
  - period: While account is active
    scope: Active accounts
    text: While account is active
  - period: 2 years of inactivity
    scope: Inactive accounts
    text: 2 years of inactivity
  - period: 2 years from submission
    scope: Job applications
    text: 2 years from submission
  - period: 6 years from end of tax year
    scope: Billing records
    text: 6 years from end of tax year
  - period: Account deletion, or 90 days of account inactivity
    scope: Resumes
    text: Account deletion, or 90 days of account inactivity
  - period: null
    scope: AI response cache (resume/profile data)
    text: about a week (at most 8 days)
  rights:
  - right: Access
    text: 'Right of access (Article 15): You have the right to request a copy of the personal data we hold about you'
  - right: Rectification
    text: Right to rectification (Article 16)
  - right: Erasure
    text: Right to erasure (Article 17)
  - right: Restriction
    text: Right to restrict processing (Article 18)
  - right: Portability
    text: Right to data portability (Article 20)
  - right: Object
    text: Right to object (Article 21)
  - right: Withdraw consent
    text: Right to withdraw consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal data. We never have and we never will.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: These transfers are safeguarded by the UK International Data Transfer Agreement (UK IDTA) or the UK Addendum to the EU Standard Contractual Clauses (SCCs), as appropriate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 4dayweek-io
provenance_date: '2026-11-09'
provider_name: 4dayweek-io
provider_slug: 4dayweek-io
slug: 4dayweek-io-privacy-policy
source_date: '2026-11-09'
source_filename: 4dayweek-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://4dayweek.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 4dayweek-io\naid: 4dayweek-io\nurl: https://4dayweek.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Full name and email address\n- category: contact\n  text: Email address\n- category: financial\n  text: Stripe customer identifier for billing purposes (we do not store credit card numbers or full payment details\n    - these are held by Stripe)\n- category: biometric\n  text: the selfies you uploaded (biometric data under UK GDPR Article 9, which we processed on your explicit consent)\n- category: device\n  text: IP address -\
  \ hashed using SHA-256 with a cryptographic salt before storage\npurposes:\n- purpose: Account creation and authentication\n  text: Necessary to provide the service you have requested, including creating your account, authenticating your\n    identity, and maintaining your session.\n- purpose: Job applications\n  text: You have requested that we transmit your application to the employer.\n- purpose: Analytics (hashed IP)\n  text: Privacy-preserving usage analysis using irreversibly hashed IP addresses.\n- purpose: Billing\n  text: Processing subscription and one-time purchase payments through Stripe\nretention:\n- scope: Active accounts\n  period: While account is active\n  text: While account is active\n- scope: Inactive accounts\n  period: 2 years of inactivity\n  text: 2 years of inactivity\n- scope: Job applications\n  period: 2 years from submission\n  text: 2 years from submission\n- scope: Billing records\n  period: 6 years from end of tax year\n  text: 6 years from end of tax year\n\
  - scope: Resumes\n  period: Account deletion, or 90 days of account inactivity\n  text: Account deletion, or 90 days of account inactivity\n- scope: AI response cache (resume/profile data)\n  period: null\n  text: about a week (at most 8 days)\nresidency:\n- region: United States (New York)\n  text: Our primary infrastructure is hosted on DigitalOcean servers located in the United States (New York region).\ntransfers:\n- mechanism: other\n  text: These transfers are safeguarded by the UK International Data Transfer Agreement (UK IDTA) or the UK Addendum\n    to the EU Standard Contractual Clauses (SCCs), as appropriate.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings in dashboard, or email phil@4dayweek.io\n  text: You can permanently delete your account and all associated data through the account settings in your dashboard.\nrights:\n- right: Access\n  text: 'Right of access (Article 15): You have the\
  \ right to request a copy of the personal data we hold about you'\n- right: Rectification\n  text: Right to rectification (Article 16)\n- right: Erasure\n  text: Right to erasure (Article 17)\n- right: Restriction\n  text: Right to restrict processing (Article 18)\n- right: Portability\n  text: Right to data portability (Article 20)\n- right: Object\n  text: Right to object (Article 21)\n- right: Withdraw consent\n  text: Right to withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal data. We never have and we never will.\n"
source_yaml_url: https://artifacts.apis.io/4dayweek-io/privacy/4dayweek-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from 4dayweek-io's own page on 2026-11-09.
synthetic: false
tags:
- Remote Jobs
- Flexible Schedule
- Work-Life Balance
- Recruiting
---
