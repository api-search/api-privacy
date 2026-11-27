---
api_specs:
- filename: raute-io-drivers-api-openapi.yml
  format: yaml
  label: raute-io Drivers API
  slug: raute-io-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raute-io/openapi/raute-io-drivers-api-openapi.yml
- filename: raute-io-orders-api-openapi.yml
  format: yaml
  label: raute-io Orders API
  slug: raute-io-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raute-io/openapi/raute-io-orders-api-openapi.yml
- filename: raute-io-tracking-api-openapi.yml
  format: yaml
  label: raute-io Tracking API
  slug: raute-io-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raute-io/openapi/raute-io-tracking-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Data: Name, email address, phone number, company name, and role information provided during registration and account management.'
  - category: financial
    text: 'Payment Information: Billing details processed securely through Stripe.'
  - category: location
    text: Real-time GPS location data is collected from driver accounts while the driver is online in the app
  - category: device
    text: 'Device Information: Device type, operating system, browser type, app version, and unique device identifiers.'
  - category: behavioral
    text: 'Usage Data: Information about how you interact with our platform, including features used, pages visited, actions taken, and timestamps.'
  - category: communication
    text: 'Communications: Messages, support requests, feedback, and other correspondence you send to us.'
  deletion:
    route: Delete account at raute.io/delete-account or email support@raute.io
    text: To exercise any of these rights, you may delete your account at raute.io/delete-account or email us at support@raute.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the platform
    text: Provide, operate, and maintain the Raute.io platform and its features.
  - purpose: Billing
    text: Process transactions and manage your subscription billing.
  - purpose: Security and fraud prevention
    text: Protect the security and integrity of the platform and prevent fraud or unauthorized activity.
  - purpose: Analytics and improvement
    text: Conduct analytics and research to improve our products and services.
  - purpose: Advertising measurement
    text: so we can tell which ads work
  residency:
  - region: United States
    text: Your information is processed and stored in the United States.
  retention:
  - period: 30 calendar days
    scope: Account termination or deletion
    text: Upon account termination or deletion, we will remove your personal data within 30 calendar days, except where retention is required by law or for legitimate business purposes.
  - period: indefinitely
    scope: Anonymized and aggregated data
    text: Anonymized and aggregated data that cannot be used to identify you may be retained indefinitely for analytics and service improvement purposes.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete personal data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data.'
  - right: Portability
    text: 'Portability: Request a copy of your data in a structured, commonly used, machine-readable format.'
  - right: Opt-Out
    text: 'Opt-Out: Opt out of marketing communications and non-essential data processing.'
  - right: Restriction
    text: 'Restriction: Request restriction of processing of your personal data under certain conditions.'
  - right: Objection
    text: 'Objection: Object to processing of your personal data based on legitimate interests.'
  role:
    text: Howl Dating LLC, DBA Raute.io
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required by applicable law, we use Standard Contractual Clauses (SCCs) approved by the European Commission or other legally approved transfer mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: raute-io
provenance_date: '2026-11-10'
provider_name: raute-io
provider_slug: raute-io
slug: raute-io-privacy-policy
source_date: '2026-11-10'
source_filename: raute-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.raute.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: raute-io\naid: raute-io\nurl: https://www.raute.io/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Howl Dating LLC, DBA Raute.io\ndata_categories:\n- category: identifying\n  text: 'Account Data: Name, email address, phone number, company name, and role information provided during registration\n    and account management.'\n- category: financial\n  text: 'Payment Information: Billing details processed securely through Stripe.'\n- category: location\n  text: Real-time GPS location data is collected from driver accounts while the driver is online in the app\n- category: device\n  text:\
  \ 'Device Information: Device type, operating system, browser type, app version, and unique device identifiers.'\n- category: behavioral\n  text: 'Usage Data: Information about how you interact with our platform, including features used, pages visited,\n    actions taken, and timestamps.'\n- category: communication\n  text: 'Communications: Messages, support requests, feedback, and other correspondence you send to us.'\npurposes:\n- purpose: Provide and operate the platform\n  text: Provide, operate, and maintain the Raute.io platform and its features.\n- purpose: Billing\n  text: Process transactions and manage your subscription billing.\n- purpose: Security and fraud prevention\n  text: Protect the security and integrity of the platform and prevent fraud or unauthorized activity.\n- purpose: Analytics and improvement\n  text: Conduct analytics and research to improve our products and services.\n- purpose: Advertising measurement\n  text: so we can tell which ads work\nretention:\n- scope:\
  \ Account termination or deletion\n  period: 30 calendar days\n  text: Upon account termination or deletion, we will remove your personal data within 30 calendar days, except\n    where retention is required by law or for legitimate business purposes.\n- scope: Anonymized and aggregated data\n  period: indefinitely\n  text: Anonymized and aggregated data that cannot be used to identify you may be retained indefinitely for analytics\n    and service improvement purposes.\nresidency:\n- region: United States\n  text: Your information is processed and stored in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required by applicable law, we use Standard Contractual Clauses (SCCs) approved by the European Commission\n    or other legally approved transfer mechanisms\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account at raute.io/delete-account or email support@raute.io\n  text: To exercise any of these\
  \ rights, you may delete your account at raute.io/delete-account or email us at support@raute.io\n    .\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate or incomplete personal data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data.'\n- right: Portability\n  text: 'Portability: Request a copy of your data in a structured, commonly used, machine-readable format.'\n- right: Opt-Out\n  text: 'Opt-Out: Opt out of marketing communications and non-essential data processing.'\n- right: Restriction\n  text: 'Restriction: Request restriction of processing of your personal data under certain conditions.'\n- right: Objection\n  text: 'Objection: Object to processing of your personal data based on legitimate interests.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/raute-io/privacy/raute-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from raute-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Delivery
- Route Planning
- Artificial Intelligence
- Fleet Management
---
