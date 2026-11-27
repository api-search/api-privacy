---
api_specs:
- filename: clearpolicy-app-api-openapi.json
  format: json
  label: ClearPolicy API API
  slug: clearpolicy-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearpolicy-app/openapi/_original/clearpolicy-app-api-openapi.json
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Phone number (if provided)
  - category: device
    text: Browser and device information
  - category: behavioral
    text: Usage and analytics information collected through our analytics tools
  - category: financial
    text: Billing and subscription information, including subscription status
  - category: communication
    text: Recipient message content included by the sending organization, if any
  deletion:
    route: Request via provider contact
    text: You may also request export or deletion of specific personal data at any time by contacting
  dpa:
    available: true
    text: Our Data Processing Agreement covers that processing relationship in detail
    url: null
  purposes:
  - purpose: Deliver policy acknowledgment requests
    text: Deliver policy acknowledgment requests
  - purpose: Improve the service
    text: Improve the service
  - purpose: Advertising measurement
    text: Measure our advertising and show relevant ClearPolicy ads
  residency:
  - region: United States
    text: Customer data is stored primarily in the United States.
  retention:
  - period: 30 days
    scope: Unused trial accounts
    text: we may delete the account and organization 30 days after you sign up (no organization)
  - period: null
    scope: Completed signature and acknowledgment records
    text: Completed signature and acknowledgment records are retained to preserve legal audit trails and are not subject to a scheduled purge date
  - period: null
    scope: Google Drive authentication tokens
    text: Authentication tokens are retained until you disconnect the relevant Google connection or access scope.
  rights:
  - right: Access
    text: Access to your personal data
  - right: Correction
    text: Correction of inaccurate data
  - right: Deletion
    text: Deletion of your data
  - right: Export
    text: Export of your data
  role:
    text: ClearPolicy acts as your data processor for that information.
    value: processor
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal data for money. Advertising-related disclosures may be considered a "sale" or "sharing" under some privacy laws.
  subprocessors:
    text: See our Data Processing Agreement for hosting and sub-processor details.
    url: null
  transfers:
  - mechanism: other
    text: Some providers may process limited technical metadata in other locations as part of normal service delivery.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClearPolicy
provenance_date: '2026-11-09'
provider_name: ClearPolicy
provider_slug: clearpolicy-app
slug: clearpolicy-app-privacy-policy
source_date: '2026-11-09'
source_filename: clearpolicy-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clearpolicy.app/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClearPolicy\naid: clearpolicy-app\nurl: https://www.clearpolicy.app/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: ClearPolicy acts as your data processor for that information.\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Phone number (if provided)\n- category: device\n  text: Browser and device information\n- category: behavioral\n  text: Usage and analytics information collected through our analytics tools\n- category: financial\n  text: Billing and subscription information, including subscription status\n- category: communication\n\
  \  text: Recipient message content included by the sending organization, if any\npurposes:\n- purpose: Deliver policy acknowledgment requests\n  text: Deliver policy acknowledgment requests\n- purpose: Improve the service\n  text: Improve the service\n- purpose: Advertising measurement\n  text: Measure our advertising and show relevant ClearPolicy ads\nretention:\n- scope: Unused trial accounts\n  period: 30 days\n  text: we may delete the account and organization 30 days after you sign up (no organization)\n- scope: Completed signature and acknowledgment records\n  period: null\n  text: Completed signature and acknowledgment records are retained to preserve legal audit trails and are not subject\n    to a scheduled purge date\n- scope: Google Drive authentication tokens\n  period: null\n  text: Authentication tokens are retained until you disconnect the relevant Google connection or access scope.\nresidency:\n- region: United States\n  text: Customer data is stored primarily in the United\
  \ States.\ntransfers:\n- mechanism: other\n  text: Some providers may process limited technical metadata in other locations as part of normal service delivery.\nsubprocessors:\n  url: null\n  text: See our Data Processing Agreement for hosting and sub-processor details.\ndpa:\n  available: true\n  url: null\n  text: Our Data Processing Agreement covers that processing relationship in detail\ndeletion:\n  route: Request via provider contact\n  text: You may also request export or deletion of specific personal data at any time by contacting\nrights:\n- right: Access\n  text: Access to your personal data\n- right: Correction\n  text: Correction of inaccurate data\n- right: Deletion\n  text: Deletion of your data\n- right: Export\n  text: Export of your data\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal data for money. Advertising-related disclosures may be considered a \"sale\" or \"sharing\"\n    under some privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/clearpolicy-app/privacy/clearpolicy-app-privacy-policy.yml
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
summary_line: 23 quoted statements, read from ClearPolicy's own page on 2026-11-09.
synthetic: false
tags:
- Policy
- E-Signature
- Software-as-a-Service
- Small Business
- Non-Profit
---
