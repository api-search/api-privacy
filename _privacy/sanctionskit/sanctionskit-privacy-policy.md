---
api_specs:
- filename: sanctionskit-batches-and-files-api-openapi.yml
  format: yaml
  label: SanctionsKit Batches and files API
  slug: sanctionskit-batches-and-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-batches-and-files-api-openapi.yml
- filename: sanctionskit-counterparties-api-openapi.yml
  format: yaml
  label: SanctionsKit Counterparties API
  slug: sanctionskit-counterparties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-counterparties-api-openapi.yml
- filename: sanctionskit-monitoring-api-openapi.yml
  format: yaml
  label: SanctionsKit Monitoring API
  slug: sanctionskit-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-monitoring-api-openapi.yml
- filename: sanctionskit-reports-api-openapi.yml
  format: yaml
  label: SanctionsKit Reports API
  slug: sanctionskit-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-reports-api-openapi.yml
- filename: sanctionskit-review-evidence-api-openapi.yml
  format: yaml
  label: SanctionsKit Review evidence API
  slug: sanctionskit-review-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-review-evidence-api-openapi.yml
- filename: sanctionskit-screening-and-evidence-api-openapi.yml
  format: yaml
  label: SanctionsKit Screening and evidence API
  slug: sanctionskit-screening-and-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-screening-and-evidence-api-openapi.yml
- filename: sanctionskit-screening-policies-api-openapi.yml
  format: yaml
  label: SanctionsKit Screening policies API
  slug: sanctionskit-screening-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-screening-policies-api-openapi.yml
- filename: sanctionskit-source-discovery-api-openapi.yml
  format: yaml
  label: SanctionsKit Source discovery API
  slug: sanctionskit-source-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-source-discovery-api-openapi.yml
- filename: sanctionskit-usage-api-openapi.yml
  format: yaml
  label: SanctionsKit Usage API
  slug: sanctionskit-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-usage-api-openapi.yml
- filename: sanctionskit-webhooks-api-openapi.yml
  format: yaml
  label: SanctionsKit Webhooks API
  slug: sanctionskit-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-webhooks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account and business contact information: names, email addresses, organization names, membership and role information, invitations, account identifiers, authentication status, and communications about an account.'
  - category: financial
    text: 'Subscription and transaction information: selected plan, subscription status, billing contacts and details, payment-provider customer and subscription identifiers, invoices, payment events, usage totals, and support correspondence.'
  - category: identifying
    text: 'Customer screening and investigation information: subject names and aliases, person or entity type, country, dates of birth when supplied, document or other identifier values'
  - category: device
    text: 'Technical and operational information: network addresses received by our infrastructure, browser and request information, session and API-key metadata, timestamps, activity and audit records, errors, delivery status, service usage, and short-lived request-protection identifiers.'
  - category: communication
    text: 'Communications: the name, email address, company, topic, message, and attachments or other details you choose to provide to support, together with our responses and delivery information.'
  deletion:
    route: Email support@sanctionskit.com or contact us about deletion beyond the available controls
    text: Contact us or your organization about deletion beyond the available controls.
  dpa:
    available: null
    text: A separately agreed data processing agreement or other binding agreement may provide additional protections for customer information.
    url: null
  purposes:
  - purpose: Account administration and requested services
    text: We use account, membership, and authentication information to create and administer accounts, enforce permissions, and deliver requested features.
  - purpose: Customer screening
    text: We use customer information to perform screening, prepare evidence and summaries, save counterparties, operate monitoring and alerts, support investigations, produce exports, and deliver results to customer-selected destinations.
  - purpose: Billing and accounting
    text: Usage and transaction records support plan limits, invoicing, subscription administration, and accounting.
  - purpose: Abuse prevention and improvement
    text: technical and activity information to prevent abuse, investigate incidents, maintain reliability, and improve the Services
  residency:
  - region: United States and other countries
    text: SanctionsKit and the providers used for a feature may process information in the United States and other countries.
  retention:
  - period: 10 calendar years
    scope: New workspace standard screening evidence
    text: New workspaces default to 10 calendar years of standard screening evidence on every paid plan.
  - period: 24 hours
    scope: Minimal-retention API-key checks
    text: Minimal mode does not store the submitted subject or complete request in the screening record, replaces query values in retained matching evidence, and expires the reduced result after 24 hours.
  - period: 24 hours
    scope: Private batch uploads
    text: Private batch uploads normally expire after 24 hours.
  - period: 30 days
    scope: Transactional email records and bodies
    text: Application records of transactional email recipients and message bodies are cleared after 30 days
  - period: 90 days
    scope: Webhook delivery history
    text: webhook delivery history after 90 days
  - period: 365 days
    scope: Tenant audit events
    text: tenant audit events after 365 days
  - period: 400 days
    scope: Aggregate measurement counts
    text: First-party aggregate website and lifecycle counts are kept for up to 400 days.
  rights:
  - right: access
    text: Depending on applicable law, you may request confirmation of processing, access or a copy, correction, deletion, portability, restriction, objection to processing, withdrawal of consent, or an applicable opt-out.
  - right: objection
    text: You may object to processing based on legitimate interests for reasons relating to your situation, and object at any time to processing for direct marketing.
  - right: complaint
    text: You may complain to a competent supervisory authority, including the authority where you live or work
  role:
    text: We decide how and why to process information needed to operate our business, including website and account administration, billing, communications, service security, and our collection and publication of source records. For these activities, we act as a controller or equivalent responsible business under applicable privacy law.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not use customer screening information or website measurement for targeted or cross-context behavioral advertising
  subprocessors:
    text: Service providers help with hosting, storage, sign-in, payments, email and request protection.
    url: null
  transfers:
  - mechanism: other
    text: Where a cross-border transfer is restricted by applicable law, a lawful transfer basis and any required safeguards must apply. Depending on the relevant parties and destination, that may involve an adequacy decision, approved contractual safeguards and required assessments, or a specific legal exception.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SanctionsKit
provenance_date: '2026-11-10'
provider_name: SanctionsKit
provider_slug: sanctionskit
slug: sanctionskit-privacy-policy
source_date: '2026-11-10'
source_filename: sanctionskit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sanctionskit.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SanctionsKit\naid: sanctionskit\nurl: https://www.sanctionskit.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We decide how and why to process information needed to operate our business, including website and account\n    administration, billing, communications, service security, and our collection and publication of source records.\n    For these activities, we act as a controller or equivalent responsible business under applicable privacy law.\ndata_categories:\n- category: contact\n  text: 'Account and business contact information: names, email addresses, organization names, membership\
  \ and role\n    information, invitations, account identifiers, authentication status, and communications about an account.'\n- category: financial\n  text: 'Subscription and transaction information: selected plan, subscription status, billing contacts and details,\n    payment-provider customer and subscription identifiers, invoices, payment events, usage totals, and support\n    correspondence.'\n- category: identifying\n  text: 'Customer screening and investigation information: subject names and aliases, person or entity type, country,\n    dates of birth when supplied, document or other identifier values'\n- category: device\n  text: 'Technical and operational information: network addresses received by our infrastructure, browser and request\n    information, session and API-key metadata, timestamps, activity and audit records, errors, delivery status,\n    service usage, and short-lived request-protection identifiers.'\n- category: communication\n  text: 'Communications: the name,\
  \ email address, company, topic, message, and attachments or other details you\n    choose to provide to support, together with our responses and delivery information.'\npurposes:\n- purpose: Account administration and requested services\n  text: We use account, membership, and authentication information to create and administer accounts, enforce permissions,\n    and deliver requested features.\n- purpose: Customer screening\n  text: We use customer information to perform screening, prepare evidence and summaries, save counterparties, operate\n    monitoring and alerts, support investigations, produce exports, and deliver results to customer-selected destinations.\n- purpose: Billing and accounting\n  text: Usage and transaction records support plan limits, invoicing, subscription administration, and accounting.\n- purpose: Abuse prevention and improvement\n  text: technical and activity information to prevent abuse, investigate incidents, maintain reliability, and improve\n    the Services\n\
  retention:\n- scope: New workspace standard screening evidence\n  period: 10 calendar years\n  text: New workspaces default to 10 calendar years of standard screening evidence on every paid plan.\n- scope: Minimal-retention API-key checks\n  period: 24 hours\n  text: Minimal mode does not store the submitted subject or complete request in the screening record, replaces\n    query values in retained matching evidence, and expires the reduced result after 24 hours.\n- scope: Private batch uploads\n  period: 24 hours\n  text: Private batch uploads normally expire after 24 hours.\n- scope: Transactional email records and bodies\n  period: 30 days\n  text: Application records of transactional email recipients and message bodies are cleared after 30 days\n- scope: Webhook delivery history\n  period: 90 days\n  text: webhook delivery history after 90 days\n- scope: Tenant audit events\n  period: 365 days\n  text: tenant audit events after 365 days\n- scope: Aggregate measurement counts\n  period:\
  \ 400 days\n  text: First-party aggregate website and lifecycle counts are kept for up to 400 days.\nresidency:\n- region: United States and other countries\n  text: SanctionsKit and the providers used for a feature may process information in the United States and other\n    countries.\ntransfers:\n- mechanism: other\n  text: Where a cross-border transfer is restricted by applicable law, a lawful transfer basis and any required\n    safeguards must apply. Depending on the relevant parties and destination, that may involve an adequacy decision,\n    approved contractual safeguards and required assessments, or a specific legal exception.\nsubprocessors:\n  url: null\n  text: Service providers help with hosting, storage, sign-in, payments, email and request protection.\ndpa:\n  available: null\n  url: null\n  text: A separately agreed data processing agreement or other binding agreement may provide additional protections\n    for customer information.\ndeletion:\n  route: Email support@sanctionskit.com\
  \ or contact us about deletion beyond the available controls\n  text: Contact us or your organization about deletion beyond the available controls.\nrights:\n- right: access\n  text: Depending on applicable law, you may request confirmation of processing, access or a copy, correction, deletion,\n    portability, restriction, objection to processing, withdrawal of consent, or an applicable opt-out.\n- right: objection\n  text: You may object to processing based on legitimate interests for reasons relating to your situation, and object\n    at any time to processing for direct marketing.\n- right: complaint\n  text: You may complain to a competent supervisory authority, including the authority where you live or work\nsale_or_sharing:\n  stance: conditional\n  text: We do not use customer screening information or website measurement for targeted or cross-context behavioral\n    advertising\n"
source_yaml_url: https://artifacts.apis.io/sanctionskit/privacy/sanctionskit-privacy-policy.yml
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
summary_line: 26 quoted statements, read from SanctionsKit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sanctions
- Compliance
- Screening
- Fintech
---
