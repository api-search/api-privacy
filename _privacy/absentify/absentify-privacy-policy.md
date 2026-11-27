---
api_specs:
- filename: absentify-absences-api-openapi.yml
  format: yaml
  label: Absentify Absences API
  slug: absentify-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-absences-api-openapi.yml
- filename: absentify-departments-api-openapi.yml
  format: yaml
  label: Absentify Departments API
  slug: absentify-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-departments-api-openapi.yml
- filename: absentify-leave-types-api-openapi.yml
  format: yaml
  label: Absentify Leave types API
  slug: absentify-leave-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-leave-types-api-openapi.yml
- filename: absentify-members-api-openapi.yml
  format: yaml
  label: Absentify Members API
  slug: absentify-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-members-api-openapi.yml
- filename: absentify-public-holidays-api-openapi.yml
  format: yaml
  label: Absentify Public holidays API
  slug: absentify-public-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-public-holidays-api-openapi.yml
- filename: absentify-requests-api-openapi.yml
  format: yaml
  label: Absentify Requests API
  slug: absentify-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-requests-api-openapi.yml
- filename: absentify-workspace-api-openapi.yml
  format: yaml
  label: Absentify Workspace API
  slug: absentify-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-workspace-api-openapi.yml
- filename: absentify-allowance-management-api-openapi.yml
  format: yaml
  label: Absentify Allowance Management API
  slug: absentify-allowance-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-allowance-management-api-openapi.yml
- filename: absentify-exports-api-openapi.yml
  format: yaml
  label: Absentify Exports API
  slug: absentify-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-exports-api-openapi.yml
- filename: absentify-out-of-office-api-openapi.yml
  format: yaml
  label: Absentify Out of office API
  slug: absentify-out-of-office-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-out-of-office-api-openapi.yml
- filename: absentify-overtime-api-openapi.yml
  format: yaml
  label: Absentify Overtime API
  slug: absentify-overtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absentify/openapi/absentify-overtime-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: First Name User identification and display Last Name User identification and display
  - category: contact
    text: Email Address Account identification and communication
  - category: demographic
    text: Birthday (optional) Birthday notifications and HR insights
  - category: location
    text: IP Address Security, fraud prevention, and legal compliance
  - category: behavioral
    text: Referring URLs Marketing analytics
  - category: device
    text: Browser Type and Version Technical support and optimization
  - category: health
    text: Absence information and messages can contain health-related or other sensitive personal data.
  - category: professional
    text: Department Assignments Organizational structure and access control
  deletion:
    route: Email support@absentify.com
    text: Contact support@absentify.com for deletion requests; employees should contact their organization's administrator for requests relating to customer workspace data.
  dpa:
    available: true
    text: 'The DPA is available at: https://absentify.com/dpa'
    url: https://absentify.com/dpa
  purposes:
  - purpose: Providing access to the application
    text: Providing access to the application Art. 6(1)(b) – Performance of contract
  - purpose: Product analytics and improvements
    text: Product analytics and improvements Art. 6(1)(f) – Legitimate interest
  - purpose: Newsletter and marketing
    text: Newsletter and marketing (with consent) Art. 6(1)(a) – Consent
  - purpose: AI assistance using customer workspace data
    text: AI assistance using customer workspace data Customer instructions under the DPA
  residency:
  - region: European Union (Ireland)
    text: Primary application hosting is in the European Union.
  - region: Ireland
    text: Customer Data North Europe (Ireland) EU paired region (geo-redundant)
  retention:
  - period: Until account deletion
    scope: Customer application data
    text: Customer Application Data Until account deletion Deleted immediately upon account deletion
  - period: Maximum 14 days
    scope: Backup data
    text: Backup Data Maximum 14 days Geo-redundant backups, then permanently deleted
  - period: 30 days
    scope: Application logs
    text: Application Logs 30 days Azure Log Analytics
  - period: 365 days
    scope: Security audit logs
    text: Security Audit Logs 365 days Immutable storage for compliance
  - period: 12 months
    scope: Email communications
    text: Email Communications 12 months Unless part of legal/audit matter
  rights:
  - right: Access
    text: Right to Access Obtain confirmation of processing and a copy of your data Art. 15 GDPR
  - right: Erasure
    text: Right to Erasure Request deletion of your data ("right to be forgotten") Art. 17 GDPR
  - right: Portability
    text: Right to Data Portability Receive your data in a structured, machine-readable format Art. 20 GDPR
  - right: Object
    text: Right to Object Object to processing based on legitimate interests Art. 21 GDPR
  - right: Withdraw consent
    text: Right to Withdraw Consent Withdraw consent at any time Art. 7(3) GDPR
  role:
    text: For its own account and contract administration and support activities where it determines the purposes and means of processing, absentify acts as controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: For that data, absentify acts as a service provider or processor where applicable and does not sell it, share it for cross-context behavioral advertising, or use it for targeted advertising.
  subprocessors:
    text: 'The current list of approved subprocessors, including their locations and purposes, is available at: https://absentify.com/subprocessors'
    url: https://absentify.com/subprocessors
  transfers:
  - mechanism: adequacy
    text: The European Commission has adopted an adequacy decision for the United Kingdom
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) as approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Absentify
provenance_date: '2026-11-09'
provider_name: Absentify
provider_slug: absentify
slug: absentify-privacy-policy
source_date: '2026-11-09'
source_filename: absentify-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://absentify.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Absentify\naid: absentify\nurl: https://absentify.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For its own account and contract administration and support activities where it determines the purposes\n    and means of processing, absentify acts as controller.\ndata_categories:\n- category: identifying\n  text: First Name User identification and display Last Name User identification and display\n- category: contact\n  text: Email Address Account identification and communication\n- category: demographic\n  text: Birthday (optional) Birthday notifications and HR insights\n- category:\
  \ location\n  text: IP Address Security, fraud prevention, and legal compliance\n- category: behavioral\n  text: Referring URLs Marketing analytics\n- category: device\n  text: Browser Type and Version Technical support and optimization\n- category: health\n  text: Absence information and messages can contain health-related or other sensitive personal data.\n- category: professional\n  text: Department Assignments Organizational structure and access control\npurposes:\n- purpose: Providing access to the application\n  text: Providing access to the application Art. 6(1)(b) – Performance of contract\n- purpose: Product analytics and improvements\n  text: Product analytics and improvements Art. 6(1)(f) – Legitimate interest\n- purpose: Newsletter and marketing\n  text: Newsletter and marketing (with consent) Art. 6(1)(a) – Consent\n- purpose: AI assistance using customer workspace data\n  text: AI assistance using customer workspace data Customer instructions under the DPA\nretention:\n-\
  \ scope: Customer application data\n  period: Until account deletion\n  text: Customer Application Data Until account deletion Deleted immediately upon account deletion\n- scope: Backup data\n  period: Maximum 14 days\n  text: Backup Data Maximum 14 days Geo-redundant backups, then permanently deleted\n- scope: Application logs\n  period: 30 days\n  text: Application Logs 30 days Azure Log Analytics\n- scope: Security audit logs\n  period: 365 days\n  text: Security Audit Logs 365 days Immutable storage for compliance\n- scope: Email communications\n  period: 12 months\n  text: Email Communications 12 months Unless part of legal/audit matter\nresidency:\n- region: European Union (Ireland)\n  text: Primary application hosting is in the European Union.\n- region: Ireland\n  text: Customer Data North Europe (Ireland) EU paired region (geo-redundant)\ntransfers:\n- mechanism: adequacy\n  text: The European Commission has adopted an adequacy decision for the United Kingdom\n- mechanism: SCC\n\
  \  text: Standard Contractual Clauses (SCCs) as approved by the European Commission\nsubprocessors:\n  url: https://absentify.com/subprocessors\n  text: 'The current list of approved subprocessors, including their locations and purposes, is available at: https://absentify.com/subprocessors'\ndpa:\n  available: true\n  url: https://absentify.com/dpa\n  text: 'The DPA is available at: https://absentify.com/dpa'\ndeletion:\n  route: Email support@absentify.com\n  text: Contact support@absentify.com for deletion requests; employees should contact their organization's administrator\n    for requests relating to customer workspace data.\nrights:\n- right: Access\n  text: Right to Access Obtain confirmation of processing and a copy of your data Art. 15 GDPR\n- right: Erasure\n  text: Right to Erasure Request deletion of your data (\"right to be forgotten\") Art. 17 GDPR\n- right: Portability\n  text: Right to Data Portability Receive your data in a structured, machine-readable format Art. 20\
  \ GDPR\n- right: Object\n  text: Right to Object Object to processing based on legitimate interests Art. 21 GDPR\n- right: Withdraw consent\n  text: Right to Withdraw Consent Withdraw consent at any time Art. 7(3) GDPR\nsale_or_sharing:\n  stance: prohibited\n  text: For that data, absentify acts as a service provider or processor where applicable and does not sell it,\n    share it for cross-context behavioral advertising, or use it for targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/absentify/privacy/absentify-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Absentify's own page on 2026-11-09.
synthetic: false
tags:
- Absence Management
- Human Resources
- Leave Management
- Microsoft Teams
---
