---
api_specs:
- filename: scope-bid-carrier-feed-api-openapi.yml
  format: yaml
  label: scope-bid Carrier Feed API
  slug: scope-bid-carrier-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-carrier-feed-api-openapi.yml
- filename: scope-bid-deliverables-api-openapi.yml
  format: yaml
  label: scope-bid Deliverables API
  slug: scope-bid-deliverables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-deliverables-api-openapi.yml
- filename: scope-bid-dispatches-api-openapi.yml
  format: yaml
  label: scope-bid Dispatches API
  slug: scope-bid-dispatches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-dispatches-api-openapi.yml
- filename: scope-bid-exports-api-openapi.yml
  format: yaml
  label: scope-bid Exports API
  slug: scope-bid-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-exports-api-openapi.yml
- filename: scope-bid-insights-api-openapi.yml
  format: yaml
  label: scope-bid Insights API
  slug: scope-bid-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-insights-api-openapi.yml
- filename: scope-bid-matters-api-openapi.yml
  format: yaml
  label: scope-bid Matters API
  slug: scope-bid-matters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-matters-api-openapi.yml
- filename: scope-bid-partner-authorizations-api-openapi.yml
  format: yaml
  label: scope-bid Partner Authorizations API
  slug: scope-bid-partner-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-partner-authorizations-api-openapi.yml
- filename: scope-bid-scopes-api-openapi.yml
  format: yaml
  label: scope-bid Scopes API
  slug: scope-bid-scopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-scopes-api-openapi.yml
- filename: scope-bid-vendors-api-openapi.yml
  format: yaml
  label: scope-bid Vendors API
  slug: scope-bid-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-vendors-api-openapi.yml
- filename: scope-bid-webhooks-api-openapi.yml
  format: yaml
  label: scope-bid Webhooks API
  slug: scope-bid-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scope-bid/openapi/scope-bid-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Account information. Email address, name, organization name, role, password, two-factor authentication setup.
  - category: financial
    text: Payment information. Payment instruments are processed by Stripe; Scope receives transaction metadata (amounts, currency, statuses) but does not store payment-card numbers or bank account details.
  - category: behavioral
    text: Usage data. Pages visited, actions taken, time stamps, IP addresses, browser type, device information.
  - category: communication
    text: Communication content. Messages exchanged through Scope's platform, notification preferences (email opt-in, SMS opt-in), inbound replies to dispatch notifications.
  - category: professional
    text: Firm and Vendor profile information. Business name, business address, business phone, business email, website, professional licenses and credentials, service categories, geographic coverage, capacity calendars.
  deletion:
    route: Contact privacy@scope.bid; requests honored per Section 8, subject to retention periods and legal holds
    text: Deletion requests are honored per Section 8, subject to the retention periods and legal holds described above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate platform
    text: Operate the Scope platform (route Matters, process bids, execute payments)
  - purpose: Verify identity and prevent fraud
    text: Verify user identity and prevent fraud
  - purpose: Improve platform
    text: Improve Scope's platform and develop new features
  residency:
  - region: United States
    text: Scope is headquartered in the United States. Personal information you provide is transferred to and processed in the United States.
  retention:
  - period: three (3) years after closure
    scope: Account data
    text: Retained for the duration of the account plus three (3) years after closure, to support audit, dispute, and tax-reporting obligations.
  - period: seven (7) years after Matter completion
    scope: Matter data
    text: Retained for seven (7) years after Matter completion, consistent with typical litigation-hold standards.
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correct
    text: Correct inaccurate personal information
  - right: Delete
    text: Delete your personal information (subject to legal retention requirements)
  - right: Restrict or object
    text: Restrict or object to processing of your personal information
  - right: Portability
    text: Portability of your personal information in a structured, machine-readable format
  role:
    text: 'Scope''s data practices reflect this two-sided role: we receive data from both Firms and Vendors to facilitate Matter routing, payment, and reputation tracking.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: A current sub-processor list is available on request and will be maintained at scope.bid/trust.
    url: scope.bid/trust
  transfers:
  - mechanism: SCC
    text: For users in the EU, UK, or EEA, we rely on appropriate transfer mechanisms (Standard Contractual Clauses, adequacy decisions where applicable)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: scope-bid
provenance_date: '2026-11-10'
provider_name: scope-bid
provider_slug: scope-bid
slug: scope-bid-privacy-policy
source_date: '2026-11-10'
source_filename: scope-bid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scope.bid/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: scope-bid\naid: scope-bid\nurl: https://scope.bid/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Scope''s data practices reflect this two-sided role: we receive data from both Firms and Vendors to facilitate\n    Matter routing, payment, and reputation tracking.'\ndata_categories:\n- category: contact\n  text: Account information. Email address, name, organization name, role, password, two-factor authentication setup.\n- category: financial\n  text: Payment information. Payment instruments are processed by Stripe; Scope receives transaction metadata (amounts,\n    currency, statuses)\
  \ but does not store payment-card numbers or bank account details.\n- category: behavioral\n  text: Usage data. Pages visited, actions taken, time stamps, IP addresses, browser type, device information.\n- category: communication\n  text: Communication content. Messages exchanged through Scope's platform, notification preferences (email opt-in,\n    SMS opt-in), inbound replies to dispatch notifications.\n- category: professional\n  text: Firm and Vendor profile information. Business name, business address, business phone, business email, website,\n    professional licenses and credentials, service categories, geographic coverage, capacity calendars.\npurposes:\n- purpose: Operate platform\n  text: Operate the Scope platform (route Matters, process bids, execute payments)\n- purpose: Verify identity and prevent fraud\n  text: Verify user identity and prevent fraud\n- purpose: Improve platform\n  text: Improve Scope's platform and develop new features\nretention:\n- scope: Account data\n\
  \  period: three (3) years after closure\n  text: Retained for the duration of the account plus three (3) years after closure, to support audit, dispute,\n    and tax-reporting obligations.\n- scope: Matter data\n  period: seven (7) years after Matter completion\n  text: Retained for seven (7) years after Matter completion, consistent with typical litigation-hold standards.\nresidency:\n- region: United States\n  text: Scope is headquartered in the United States. Personal information you provide is transferred to and processed\n    in the United States.\ntransfers:\n- mechanism: SCC\n  text: For users in the EU, UK, or EEA, we rely on appropriate transfer mechanisms (Standard Contractual Clauses,\n    adequacy decisions where applicable)\nsubprocessors:\n  url: scope.bid/trust\n  text: A current sub-processor list is available on request and will be maintained at scope.bid/trust.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@scope.bid; requests\
  \ honored per Section 8, subject to retention periods and legal holds\n  text: Deletion requests are honored per Section 8, subject to the retention periods and legal holds described\n    above.\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correct\n  text: Correct inaccurate personal information\n- right: Delete\n  text: Delete your personal information (subject to legal retention requirements)\n- right: Restrict or object\n  text: Restrict or object to processing of your personal information\n- right: Portability\n  text: Portability of your personal information in a structured, machine-readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/scope-bid/privacy/scope-bid-privacy-policy.yml
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
summary_line: 21 quoted statements, read from scope-bid's own page on 2026-11-10.
synthetic: false
tags:
- Construction
- Bidding
- Software-as-a-Service
- Collaboration
- Analytics
---
