---
api_specs:
- filename: stratalize-com-x402-api-openapi.yml
  format: yaml
  label: stratalize-com X402 API
  slug: stratalize-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stratalize-com/openapi/stratalize-com-x402-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and password (via Supabase Auth)
  - category: contact
    text: Organization name, industry, and location
  - category: professional
    text: Department, job title, and role within your organization
  - category: financial
    text: Billing information processed by our payment processor, Stripe
  - category: device
    text: Session timestamps, IP addresses, and browser/device metadata
  - category: behavioral
    text: Features accessed, reports generated, and queries submitted
  - category: location
    text: Organization name, industry, and location
  - category: biometric
    text: Face and fingerprint data stay on your phone and are never sent to us.
  deletion:
    route: Email privacy@stratalize.com or delete account in the app or on the web
    text: You may request deletion of your data at any time by contacting privacy@stratalize.com.
  dpa:
    available: true
    text: Organizations in the EU/EEA may request a Data Processing Agreement (DPA) incorporating appropriate transfer safeguards by contacting privacy@stratalize.com.
    url: null
  purposes:
  - purpose: Provide and improve platform
    text: Provide, operate, and improve the Stratalize platform
  - purpose: Generate AI syntheses
    text: Generate AI intelligence syntheses on your behalf
  - purpose: Billing
    text: Process billing and subscription management (via Stripe)
  - purpose: Security and fraud prevention
    text: Detect, investigate, and prevent security incidents and fraud
  - purpose: Product analytics
    text: Analyze platform usage to improve features and performance
  residency:
  - region: United States
    text: Stratalize is operated from the United States.
  retention:
  - period: Duration of subscription + 90 days
    scope: Account and profile data
    text: Account and profile data Duration of subscription + 90 days
  - period: 7 years
    scope: Governance audit logs
    text: Governance audit logs 7 years (regulatory requirement)
  - period: Seconds to minutes
    scope: Raw staging payloads
    text: Raw staging payloads Seconds to minutes (deleted post-synthesis)
  - period: 12 months
    scope: Analytics events (PostHog)
    text: Analytics events (PostHog) 12 months
  - period: 90 days
    scope: Error logs (Sentry)
    text: Error logs (Sentry) 90 days
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correct
    text: Correct inaccurate or incomplete personal data
  - right: Delete
    text: Request deletion of your personal data
  - right: Restrict or object
    text: Restrict or object to processing
  - right: Portability
    text: Request data portability in a machine-readable format
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent
  - right: Complain
    text: Lodge a complaint with your local data protection authority
  role:
    text: We process data on behalf of your organization as a data processor under your organization's direction.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Supabase Database, authentication All platform data including Personal Data US / EU (configurable)
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on Standard Contractual Clauses (SCCs) approved by the European Commission, or other appropriate transfer mechanisms, with relevant sub-processors.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: stratalize-com
provenance_date: '2026-11-10'
provider_name: stratalize-com
provider_slug: stratalize-com
slug: stratalize-com-privacy-policy
source_date: '2026-11-10'
source_filename: stratalize-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.stratalize.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: stratalize-com\naid: stratalize-com\nurl: https://www.stratalize.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We process data on behalf of your organization as a data processor under your organization's direction.\ndata_categories:\n- category: identifying\n  text: Name, email address, and password (via Supabase Auth)\n- category: contact\n  text: Organization name, industry, and location\n- category: professional\n  text: Department, job title, and role within your organization\n- category: financial\n  text: Billing information processed by our payment processor, Stripe\n\
  - category: device\n  text: Session timestamps, IP addresses, and browser/device metadata\n- category: behavioral\n  text: Features accessed, reports generated, and queries submitted\n- category: location\n  text: Organization name, industry, and location\n- category: biometric\n  text: Face and fingerprint data stay on your phone and are never sent to us.\npurposes:\n- purpose: Provide and improve platform\n  text: Provide, operate, and improve the Stratalize platform\n- purpose: Generate AI syntheses\n  text: Generate AI intelligence syntheses on your behalf\n- purpose: Billing\n  text: Process billing and subscription management (via Stripe)\n- purpose: Security and fraud prevention\n  text: Detect, investigate, and prevent security incidents and fraud\n- purpose: Product analytics\n  text: Analyze platform usage to improve features and performance\nretention:\n- scope: Account and profile data\n  period: Duration of subscription + 90 days\n  text: Account and profile data Duration\
  \ of subscription + 90 days\n- scope: Governance audit logs\n  period: 7 years\n  text: Governance audit logs 7 years (regulatory requirement)\n- scope: Raw staging payloads\n  period: Seconds to minutes\n  text: Raw staging payloads Seconds to minutes (deleted post-synthesis)\n- scope: Analytics events (PostHog)\n  period: 12 months\n  text: Analytics events (PostHog) 12 months\n- scope: Error logs (Sentry)\n  period: 90 days\n  text: Error logs (Sentry) 90 days\nresidency:\n- region: United States\n  text: Stratalize is operated from the United States.\ntransfers:\n- mechanism: SCC\n  text: we rely on Standard Contractual Clauses (SCCs) approved by the European Commission, or other appropriate\n    transfer mechanisms, with relevant sub-processors.\nsubprocessors:\n  url: null\n  text: Supabase Database, authentication All platform data including Personal Data US / EU (configurable)\ndpa:\n  available: true\n  url: null\n  text: Organizations in the EU/EEA may request a Data Processing\
  \ Agreement (DPA) incorporating appropriate transfer\n    safeguards by contacting privacy@stratalize.com.\ndeletion:\n  route: Email privacy@stratalize.com or delete account in the app or on the web\n  text: You may request deletion of your data at any time by contacting privacy@stratalize.com.\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correct\n  text: Correct inaccurate or incomplete personal data\n- right: Delete\n  text: Request deletion of your personal data\n- right: Restrict or object\n  text: Restrict or object to processing\n- right: Portability\n  text: Request data portability in a machine-readable format\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent\n- right: Complain\n  text: Lodge a complaint with your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/stratalize-com/privacy/stratalize-com-privacy-policy.yml
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
summary_line: 32 quoted statements, read from stratalize-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Project Controls
- Schedule Management
- Artificial Intelligence
- Compliance
---
