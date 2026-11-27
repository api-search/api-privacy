---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name Contact information such as email, phone number, or address
  - category: contact
    text: Contact information such as email, phone number, or address
  - category: financial
    text: CrossCheck may also process limited business financial/accounting fields present in the customer's NetSuite data, such as transaction totals, invoice/payment status, credit limits, tax IDs, and accounting classification data.
  - category: device
    text: User activity and analysis such as device information or IP address
  - category: professional
    text: Employment information such as employee ID or compensation
  deletion:
    route: Customer deletes workspaces, environments, snapshots and related records; Provider returns or deletes data at Customer's instruction at DPA expiration
    text: Provider will enable Customer to delete Customer Personal Data in a manner consistent with the functionality of the Services.
  dpa:
    available: true
    text: 'This DPA has 2 parts: (1) the Key Terms on this Cover Page and (2) the Common Paper DPA Standard Terms Version 1.1'
    url: https://vertical.bar/data-processing-agreement
  purposes:
  - purpose: Provide the CrossCheck service
    text: To provide the CrossCheck service, including customer-authorized extraction of NetSuite configurations and selected records
  - purpose: Optional AI-assisted analysis
    text: optional AI-assisted analysis and report generation
  residency:
  - region: United States
    text: 'Country of location: United States'
  retention:
  - period: null
    scope: Database backups and production logs
    text: Production infrastructure evidence shows finite retention for certain system components, including database backups and production log retention windows.
  - period: 3 years after the DPA ends
    scope: Provider compliance records
    text: Provider will maintain records of its compliance with this DPA for 3 years after the DPA ends.
  rights:
  - right: Data portability
    text: CrossCheck supports data portability through customer-facing export and report-generation workflows
  - right: Erasure
    text: The service also supports erasure through deletion of customer workspaces, environments, snapshots, and related records
  - right: Assistance with data subject requests
    text: If a data subject makes a valid request under Applicable Data Protection Laws to delete or opt out of Customer's giving of Customer Personal Data to Provider, Provider will assist Customer in fulfilling the request
  role:
    text: 'Role: Processor'
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: Provider will not sell or share any Personal Data provided by Customer under the Agreement.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Customer and Provider agree that if the GDPR protects the transfer of Customer Personal Data, the transfer is from Customer from within the EEA to Provider outside of the EEA, and the transfer is not governed by an adequacy decision made by the European Commission, then by entering into this DPA, Customer and Provider are deemed to have signed the EEA SCCs
  - mechanism: other
    text: Customer and Provider are deemed to have signed the UK Addendum and their Annexes, which are incorporated by reference.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vertical Bar
provenance_date: '2026-11-10'
provider_name: Vertical Bar
provider_slug: vertical-bar-inc
slug: vertical-bar-inc-privacy-policy
source_date: '2026-11-10'
source_filename: vertical-bar-inc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vertical.bar/data-processing-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vertical Bar\naid: vertical-bar-inc\nurl: https://vertical.bar/data-processing-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: 'Role: Processor'\ndata_categories:\n- category: identifying\n  text: Name Contact information such as email, phone number, or address\n- category: contact\n  text: Contact information such as email, phone number, or address\n- category: financial\n  text: CrossCheck may also process limited business financial/accounting fields present in the customer's NetSuite\n    data, such as transaction totals, invoice/payment status, credit limits, tax IDs, and accounting\
  \ classification\n    data.\n- category: device\n  text: User activity and analysis such as device information or IP address\n- category: professional\n  text: Employment information such as employee ID or compensation\npurposes:\n- purpose: Provide the CrossCheck service\n  text: To provide the CrossCheck service, including customer-authorized extraction of NetSuite configurations and\n    selected records\n- purpose: Optional AI-assisted analysis\n  text: optional AI-assisted analysis and report generation\nretention:\n- scope: Database backups and production logs\n  period: null\n  text: Production infrastructure evidence shows finite retention for certain system components, including database\n    backups and production log retention windows.\n- scope: Provider compliance records\n  period: 3 years after the DPA ends\n  text: Provider will maintain records of its compliance with this DPA for 3 years after the DPA ends.\nresidency:\n- region: United States\n  text: 'Country of location:\
  \ United States'\ntransfers:\n- mechanism: SCC\n  text: Customer and Provider agree that if the GDPR protects the transfer of Customer Personal Data, the transfer\n    is from Customer from within the EEA to Provider outside of the EEA, and the transfer is not governed by an\n    adequacy decision made by the European Commission, then by entering into this DPA, Customer and Provider are\n    deemed to have signed the EEA SCCs\n- mechanism: other\n  text: Customer and Provider are deemed to have signed the UK Addendum and their Annexes, which are incorporated\n    by reference.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://vertical.bar/data-processing-agreement\n  text: 'This DPA has 2 parts: (1) the Key Terms on this Cover Page and (2) the Common Paper DPA Standard Terms\n    Version 1.1'\ndeletion:\n  route: Customer deletes workspaces, environments, snapshots and related records; Provider returns or deletes data\n    at Customer's instruction at\
  \ DPA expiration\n  text: Provider will enable Customer to delete Customer Personal Data in a manner consistent with the functionality\n    of the Services.\nrights:\n- right: Data portability\n  text: CrossCheck supports data portability through customer-facing export and report-generation workflows\n- right: Erasure\n  text: The service also supports erasure through deletion of customer workspaces, environments, snapshots, and\n    related records\n- right: Assistance with data subject requests\n  text: If a data subject makes a valid request under Applicable Data Protection Laws to delete or opt out of Customer's\n    giving of Customer Personal Data to Provider, Provider will assist Customer in fulfilling the request\nsale_or_sharing:\n  stance: prohibited\n  text: Provider will not sell or share any Personal Data provided by Customer under the Agreement.\n"
source_yaml_url: https://artifacts.apis.io/vertical-bar-inc/privacy/vertical-bar-inc-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Vertical Bar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- NetSuite
- DevOps
- ERP
- Change Management
- Process Mining
- Configuration Management
- Manufacturing
---
