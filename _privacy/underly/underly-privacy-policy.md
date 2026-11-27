---
api_specs:
- filename: underly-analyses-api-openapi.yml
  format: yaml
  label: Underly Analyses API
  slug: underly-analyses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/underly/openapi/underly-analyses-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your name, email address, password if you set one (stored hashed), the organization you belong to and your role in it.'
  - category: financial
    text: 'Billing data: your plan and billing history. Card details are collected and held by Dodo Payments; we never see or store card numbers.'
  - category: financial
    text: 'Customer content: the statements you upload and what Underly reads from them, such as transactions, balances, account details and business names'
  - category: device
    text: 'Usage data: pages visited, browser type, IP address and the time of each visit.'
  deletion:
    route: Delete analysis in app or owner deletes organization from Settings
    text: Deleting an analysis removes its statements, its figures and its stored files.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate Underly
    text: To provide and operate Underly
  - purpose: Read statements and produce analyses
    text: To read statements and produce analyses for your organization
  - purpose: Billing and plan limits
    text: To bill paid plans and apply plan limits
  - purpose: Monitoring and abuse prevention
    text: To monitor performance, fix problems and prevent abuse
  - purpose: Legal compliance
    text: To comply with legal obligations
  retention:
  - period: until you delete them
    scope: Uploaded statements and analyses
    text: Uploaded statements and analyses are kept until you delete them, or until the automatic deletion period that an owner or admin chooses in Settings ends.
  - period: null
    scope: Account and organization data
    text: Account and organization data is kept while the account is active and for a reasonable period afterwards to meet legal and operational obligations.
  rights:
  - right: access, correction, deletion
    text: You may ask to access, correct or delete your personal account information by emailing us.
  - right: CCPA rights
    text: California residents may have additional rights under the CCPA, including the right to know what information we have collected and the right to request deletion.
  role:
    text: LendPipe (“we,” “us” or “our”) operates Underly, software that analyzes business bank statements.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: Service providers that process information for Underly Provider What it does What it handles Supabase Database Account data and analyses
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Underly
provenance_date: '2026-11-10'
provider_name: Underly
provider_slug: underly
slug: underly-privacy-policy
source_date: '2026-11-10'
source_filename: underly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://underly.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Underly\naid: underly\nurl: https://underly.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: LendPipe (“we,” “us” or “our”) operates Underly, software that analyzes business bank statements.\ndata_categories:\n- category: identifying\n  text: 'Account data: your name, email address, password if you set one (stored hashed), the organization you belong\n    to and your role in it.'\n- category: financial\n  text: 'Billing data: your plan and billing history. Card details are collected and held by Dodo Payments; we never\n    see or store card numbers.'\n- category: financial\n  text: 'Customer\
  \ content: the statements you upload and what Underly reads from them, such as transactions, balances,\n    account details and business names'\n- category: device\n  text: 'Usage data: pages visited, browser type, IP address and the time of each visit.'\npurposes:\n- purpose: Provide and operate Underly\n  text: To provide and operate Underly\n- purpose: Read statements and produce analyses\n  text: To read statements and produce analyses for your organization\n- purpose: Billing and plan limits\n  text: To bill paid plans and apply plan limits\n- purpose: Monitoring and abuse prevention\n  text: To monitor performance, fix problems and prevent abuse\n- purpose: Legal compliance\n  text: To comply with legal obligations\nretention:\n- scope: Uploaded statements and analyses\n  period: until you delete them\n  text: Uploaded statements and analyses are kept until you delete them, or until the automatic deletion period\n    that an owner or admin chooses in Settings ends.\n- scope: Account\
  \ and organization data\n  period: null\n  text: Account and organization data is kept while the account is active and for a reasonable period afterwards\n    to meet legal and operational obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service providers that process information for Underly Provider What it does What it handles Supabase Database\n    Account data and analyses\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete analysis in app or owner deletes organization from Settings\n  text: Deleting an analysis removes its statements, its figures and its stored files.\nrights:\n- right: access, correction, deletion\n  text: You may ask to access, correct or delete your personal account information by emailing us.\n- right: CCPA rights\n  text: California residents may have additional rights under the CCPA, including the right to know what information\n    we have collected and the right to request deletion.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/underly/privacy/underly-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Underly's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Banking
- Data Analysis
- Lending
- Accounting
---
