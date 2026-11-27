---
api_specs:
- filename: cloudidr-external-api-openapi.yml
  format: yaml
  label: Cloudidr External API
  slug: cloudidr-external-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudidr/openapi/cloudidr-external-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, phone number'
  - category: contact
    text: Billing address
  - category: financial
    text: Credit card details (processed by third-party payment processors)
  - category: device
    text: IP addresses
  - category: behavioral
    text: Service interaction patterns
  - category: professional
    text: Job title and role
  - category: communication
    text: Support requests and correspondence
  deletion:
    route: Self-service account deletion via portal or email request to privacy@cloudidr.com
    text: 'Delete Account: Self-service account deletion via portal Email request: privacy@cloudidr.com'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision
    text: Provisioning and managing compute resources
  - purpose: Service improvement
    text: Developing new features and capabilities
  - purpose: Marketing communications
    text: Product announcements
  - purpose: Legal obligations
    text: Law enforcement when required by valid legal process
  residency:
  - region: United States
    text: 'Primary: United States (AWS US regions)'
  retention:
  - period: 90 days
    scope: Account data
    text: Retained for 90 days after account closure (for billing/legal purposes)
  - period: 7 years
    scope: Billing records
    text: Retained for 7 years (legal and tax requirements)
  - period: 90 days
    scope: Service usage logs
    text: Retained for 90 days (operational purposes)
  - period: 30 days
    scope: LLM Ops metadata
    text: Permanently deleted within 30 days of account deletion
  - period: 30 days
    scope: Customer content
    text: Deleted within 30 days of account closure or service termination
  rights:
  - right: Access
    text: Request copy of your personal data
  - right: Portability
    text: Export data in machine-readable formats (JSON, CSV)
  - right: Deletion
    text: All personal data deleted within 30 days
  - right: Object
    text: Object to processing for marketing purposes (honored immediately)
  - right: Restrict processing
    text: Limit how we use your data
  - right: Withdraw consent
    text: Withdraw consent anytime
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We Do Not Sell Personal Information
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may transfer data internationally as necessary to provide Services
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cloudidr
provenance_date: '2026-11-09'
provider_name: Cloudidr
provider_slug: cloudidr
slug: cloudidr-privacy-policy
source_date: '2026-11-09'
source_filename: cloudidr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cloudidr.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cloudidr\naid: cloudidr\nurl: https://www.cloudidr.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, phone number'\n- category: contact\n  text: Billing address\n- category: financial\n  text: Credit card details (processed by third-party payment processors)\n- category: device\n  text: IP addresses\n- category: behavioral\n  text: Service interaction patterns\n- category: professional\n  text: Job title and role\n- category: communication\n  text: Support requests and correspondence\n\
  purposes:\n- purpose: Service provision\n  text: Provisioning and managing compute resources\n- purpose: Service improvement\n  text: Developing new features and capabilities\n- purpose: Marketing communications\n  text: Product announcements\n- purpose: Legal obligations\n  text: Law enforcement when required by valid legal process\nretention:\n- scope: Account data\n  period: 90 days\n  text: Retained for 90 days after account closure (for billing/legal purposes)\n- scope: Billing records\n  period: 7 years\n  text: Retained for 7 years (legal and tax requirements)\n- scope: Service usage logs\n  period: 90 days\n  text: Retained for 90 days (operational purposes)\n- scope: LLM Ops metadata\n  period: 30 days\n  text: Permanently deleted within 30 days of account deletion\n- scope: Customer content\n  period: 30 days\n  text: Deleted within 30 days of account closure or service termination\nresidency:\n- region: United States\n  text: 'Primary: United States (AWS US regions)'\ntransfers:\n\
  - mechanism: other\n  text: We may transfer data internationally as necessary to provide Services\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service account deletion via portal or email request to privacy@cloudidr.com\n  text: 'Delete Account: Self-service account deletion via portal Email request: privacy@cloudidr.com'\nrights:\n- right: Access\n  text: Request copy of your personal data\n- right: Portability\n  text: Export data in machine-readable formats (JSON, CSV)\n- right: Deletion\n  text: All personal data deleted within 30 days\n- right: Object\n  text: Object to processing for marketing purposes (honored immediately)\n- right: Restrict processing\n  text: Limit how we use your data\n- right: Withdraw consent\n  text: Withdraw consent anytime\nsale_or_sharing:\n  stance: prohibited\n  text: We Do Not Sell Personal Information\n"
source_yaml_url: https://artifacts.apis.io/cloudidr/privacy/cloudidr-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Cloudidr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity and Access Management
- Cloud
- Security
- Artificial Intelligence
- FinOps
---
