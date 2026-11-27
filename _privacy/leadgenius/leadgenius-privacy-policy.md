---
api_specs:
- filename: leadgenius-campaigns-api-openapi.yml
  format: yaml
  label: LeadGenius Campaigns API
  slug: leadgenius-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-campaigns-api-openapi.yml
- filename: leadgenius-exclusion-api-openapi.yml
  format: yaml
  label: LeadGenius Exclusion API
  slug: leadgenius-exclusion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-exclusion-api-openapi.yml
- filename: leadgenius-rapid-enrichment-api-openapi.yml
  format: yaml
  label: LeadGenius Rapid Enrichment API
  slug: leadgenius-rapid-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-rapid-enrichment-api-openapi.yml
- filename: leadgenius-records-api-openapi.yml
  format: yaml
  label: LeadGenius Records API
  slug: leadgenius-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-records-api-openapi.yml
- filename: leadgenius-usage-api-openapi.yml
  format: yaml
  label: LeadGenius Usage API
  slug: leadgenius-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-usage-api-openapi.yml
- filename: leadgenius-leadgenius-enrichment-api-api-openapi.yml
  format: yaml
  label: LeadGenius Enrichment API
  slug: leadgenius-leadgenius-enrichment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadgenius/openapi/leadgenius-leadgenius-enrichment-api-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Contact information: name, email address, phone number, mailing address.'
  - category: identifying
    text: 'Online identifiers: IP address, device ID, and similar identifiers.'
  - category: financial
    text: Financial and transaction details (handled by a third-party processor).
  - category: behavioral
    text: Website activity, device information, access times, navigation history.
  - category: professional
    text: Company name, job title, company location.
  - category: communication
    text: Customer service call or chat recordings.
  - category: other
    text: Profiles reflecting preferences, characteristics, behavior.
  deletion:
    route: Account settings or email to privacy@leadgenius.com
    text: Access, Modify, Delete Account Information via your account or by emailing privacy@leadgenius.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: Provide and operate the Services.
  - purpose: Improve and develop services
    text: Improve and develop our Services.
  - purpose: Research and analytics
    text: Conduct research and analytics.
  - purpose: Direct marketing
    text: Send direct marketing communications (opt-out available).
  - purpose: Interest-based advertising
    text: Deliver interest-based advertising.
  - purpose: Legal compliance
    text: Comply with laws and legal processes.
  - purpose: Fraud prevention and safety
    text: Prevent fraud, ensure safety, and enforce policies.
  residency:
  - region: United States
    text: LeadGenius is headquartered in the United States.
  - region: Other countries
    text: Your information may be stored and processed in other countries.
  rights:
  - right: Access
    text: Right to Know / Access
  - right: Delete
    text: Right to Delete
  - right: Correct
    text: Right to Correct
  - right: Opt out of sale or sharing
    text: Right to Opt Out of Sale or Sharing
  - right: Nondiscrimination
    text: Right to Nondiscrimination
  - right: Port
    text: Access, correct, delete, port, restrict, or object to processing.
  - right: Object and restrict
    text: Access, correct, delete, port, restrict, or object to processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LeadGenius
provenance_date: '2026-11-09'
provider_name: LeadGenius
provider_slug: leadgenius
slug: leadgenius-privacy-policy
source_date: '2026-11-09'
source_filename: leadgenius-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.leadgenius.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LeadGenius\naid: leadgenius\nurl: https://www.leadgenius.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Contact information: name, email address, phone number, mailing address.'\n- category: identifying\n  text: 'Online identifiers: IP address, device ID, and similar identifiers.'\n- category: financial\n  text: Financial and transaction details (handled by a third-party processor).\n- category: behavioral\n  text: Website activity, device information, access times, navigation history.\n- category: professional\n  text:\
  \ Company name, job title, company location.\n- category: communication\n  text: Customer service call or chat recordings.\n- category: other\n  text: Profiles reflecting preferences, characteristics, behavior.\npurposes:\n- purpose: Provide and operate the Services\n  text: Provide and operate the Services.\n- purpose: Improve and develop services\n  text: Improve and develop our Services.\n- purpose: Research and analytics\n  text: Conduct research and analytics.\n- purpose: Direct marketing\n  text: Send direct marketing communications (opt-out available).\n- purpose: Interest-based advertising\n  text: Deliver interest-based advertising.\n- purpose: Legal compliance\n  text: Comply with laws and legal processes.\n- purpose: Fraud prevention and safety\n  text: Prevent fraud, ensure safety, and enforce policies.\nretention: []\nresidency:\n- region: United States\n  text: LeadGenius is headquartered in the United States.\n- region: Other countries\n  text: Your information may be stored\
  \ and processed in other countries.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or email to privacy@leadgenius.com\n  text: Access, Modify, Delete Account Information via your account or by emailing privacy@leadgenius.com .\nrights:\n- right: Access\n  text: Right to Know / Access\n- right: Delete\n  text: Right to Delete\n- right: Correct\n  text: Right to Correct\n- right: Opt out of sale or sharing\n  text: Right to Opt Out of Sale or Sharing\n- right: Nondiscrimination\n  text: Right to Nondiscrimination\n- right: Port\n  text: Access, correct, delete, port, restrict, or object to processing.\n- right: Object and restrict\n  text: Access, correct, delete, port, restrict, or object to processing.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/leadgenius/privacy/leadgenius-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- deletion
- rights
summary_line: 24 quoted statements, read from LeadGenius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Enrichment
- Lead Generation
- Sales
- Marketing
- B2B Data
- Contact Data
- Firmographics
- Go-To-Market
- Account Based Marketing
---
