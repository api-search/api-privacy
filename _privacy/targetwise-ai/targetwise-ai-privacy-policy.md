---
api_specs:
- filename: targetwise-ai-account-api-openapi.yml
  format: yaml
  label: targetwise-ai Account API
  slug: targetwise-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-account-api-openapi.yml
- filename: targetwise-ai-autocomplete-api-openapi.yml
  format: yaml
  label: targetwise-ai Autocomplete API
  slug: targetwise-ai-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-autocomplete-api-openapi.yml
- filename: targetwise-ai-companies-api-openapi.yml
  format: yaml
  label: targetwise-ai Companies API
  slug: targetwise-ai-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-companies-api-openapi.yml
- filename: targetwise-ai-employees-api-openapi.yml
  format: yaml
  label: targetwise-ai Employees API
  slug: targetwise-ai-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-employees-api-openapi.yml
- filename: targetwise-ai-enrichment-api-openapi.yml
  format: yaml
  label: targetwise-ai Enrichment API
  slug: targetwise-ai-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-enrichment-api-openapi.yml
- filename: targetwise-ai-prospecting-api-openapi.yml
  format: yaml
  label: targetwise-ai Prospecting API
  slug: targetwise-ai-prospecting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-prospecting-api-openapi.yml
- filename: targetwise-ai-resolution-api-openapi.yml
  format: yaml
  label: targetwise-ai Resolution API
  slug: targetwise-ai-resolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/targetwise-ai/openapi/targetwise-ai-resolution-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email, organisation, user and authentication IDs
  - category: financial
    text: Plan, billing contact, invoices, payment and subscription status
  - category: professional
    text: Name, role, employer, professional profile, work email, business phone and company context
  - category: device
    text: IP address, device or browser information and security events
  - category: behavioral
    text: Random browser ID, landing path, referring domain, campaign labels and conversion events
  deletion:
    route: Email office@targetwise.ai with the subject 'Privacy request' and the email address, professional profile URL or other identifier needed to locate the record.
    text: State whether you want access, correction, deletion, suppression, an opt-out or another action.
  dpa:
    available: true
    text: Data Processing Addendum
    url: https://targetwise.ai/legal/dpa
  purposes:
  - purpose: Account setup, service delivery and support
    text: Account setup, service delivery and support
  - purpose: Professional-data matching and supply
    text: Professional-data matching and supply
  - purpose: Fraud prevention, access controls and diagnostics
    text: Fraud prevention, access controls and diagnostics
  - purpose: Optional browser analytics and acquisition reporting
    text: Optional browser analytics and acquisition reporting
  residency:
  - region: UK, EEA and United States
    text: Our hosting and service providers operate internationally, including in the United Kingdom, EEA and United States.
  retention:
  - period: 30 days
    scope: Saved enrichment results
    text: Saved dashboard result retrieval expires after 30 days.
  - period: seven years
    scope: Invoices and contractual records
    text: Generally up to seven years where needed for accounting, tax or legal claims
  - period: 90 days
    scope: Optional acquisition records
    text: Up to 90 days
  rights:
  - right: Object to direct marketing
    text: You can object at any time to processing of your personal data for direct marketing, including related profiling.
  - right: Access, correction, deletion, restriction, portability
    text: you may request access, correction, deletion, restriction or portability, withdraw consent
  - right: Opt-out of sale or sharing
    text: Where applicable US state privacy law provides them, you may also request an opt-out of sale or sharing
  role:
    text: TargetWise is controller for account administration, billing, security, enquiries and its independently determined professional-data activities.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Paid licensing or disclosure of professional contact data can constitute a ‘sale’ under some US state privacy laws.
  subprocessors:
    text: Service providers and subprocessors
    url: https://targetwise.ai/legal/service-providers
  transfers:
  - mechanism: SCC
    text: executed EU Standard Contractual Clauses with the UK Addendum or a UK International Data Transfer Agreement where relevant
  - mechanism: adequacy
    text: an applicable adequacy decision
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: targetwise-ai
provenance_date: '2026-11-10'
provider_name: targetwise-ai
provider_slug: targetwise-ai
slug: targetwise-ai-privacy-policy
source_date: '2026-11-10'
source_filename: targetwise-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://targetwise.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: targetwise-ai\naid: targetwise-ai\nurl: https://targetwise.ai/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: TargetWise is controller for account administration, billing, security, enquiries and its independently\n    determined professional-data activities.\ndata_categories:\n- category: identifying\n  text: Name, work email, organisation, user and authentication IDs\n- category: financial\n  text: Plan, billing contact, invoices, payment and subscription status\n- category: professional\n  text: Name, role, employer, professional profile, work email, business phone and company context\n\
  - category: device\n  text: IP address, device or browser information and security events\n- category: behavioral\n  text: Random browser ID, landing path, referring domain, campaign labels and conversion events\npurposes:\n- purpose: Account setup, service delivery and support\n  text: Account setup, service delivery and support\n- purpose: Professional-data matching and supply\n  text: Professional-data matching and supply\n- purpose: Fraud prevention, access controls and diagnostics\n  text: Fraud prevention, access controls and diagnostics\n- purpose: Optional browser analytics and acquisition reporting\n  text: Optional browser analytics and acquisition reporting\nretention:\n- scope: Saved enrichment results\n  period: 30 days\n  text: Saved dashboard result retrieval expires after 30 days.\n- scope: Invoices and contractual records\n  period: seven years\n  text: Generally up to seven years where needed for accounting, tax or legal claims\n- scope: Optional acquisition records\n\
  \  period: 90 days\n  text: Up to 90 days\nresidency:\n- region: UK, EEA and United States\n  text: Our hosting and service providers operate internationally, including in the United Kingdom, EEA and United\n    States.\ntransfers:\n- mechanism: SCC\n  text: executed EU Standard Contractual Clauses with the UK Addendum or a UK International Data Transfer Agreement\n    where relevant\n- mechanism: adequacy\n  text: an applicable adequacy decision\nsubprocessors:\n  url: https://targetwise.ai/legal/service-providers\n  text: Service providers and subprocessors\ndpa:\n  available: true\n  url: https://targetwise.ai/legal/dpa\n  text: Data Processing Addendum\ndeletion:\n  route: Email office@targetwise.ai with the subject 'Privacy request' and the email address, professional profile\n    URL or other identifier needed to locate the record.\n  text: State whether you want access, correction, deletion, suppression, an opt-out or another action.\nrights:\n- right: Object to direct marketing\n\
  \  text: You can object at any time to processing of your personal data for direct marketing, including related profiling.\n- right: Access, correction, deletion, restriction, portability\n  text: you may request access, correction, deletion, restriction or portability, withdraw consent\n- right: Opt-out of sale or sharing\n  text: Where applicable US state privacy law provides them, you may also request an opt-out of sale or sharing\nsale_or_sharing:\n  stance: conditional\n  text: Paid licensing or disclosure of professional contact data can constitute a ‘sale’ under some US state privacy\n    laws.\n"
source_yaml_url: https://artifacts.apis.io/targetwise-ai/privacy/targetwise-ai-privacy-policy.yml
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
summary_line: 23 quoted statements, read from targetwise-ai's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Data Enrichment
- MCP
- Software-as-a-Service
---
