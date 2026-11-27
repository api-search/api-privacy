---
api_specs:
- filename: ibanforge-api-keys-api-openapi.yml
  format: yaml
  label: IBANforge API Keys API
  slug: ibanforge-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-api-keys-api-openapi.yml
- filename: ibanforge-bic-api-openapi.yml
  format: yaml
  label: IBANforge BIC API
  slug: ibanforge-bic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-bic-api-openapi.yml
- filename: ibanforge-compliance-api-openapi.yml
  format: yaml
  label: IBANforge Compliance API
  slug: ibanforge-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-compliance-api-openapi.yml
- filename: ibanforge-credits-api-openapi.yml
  format: yaml
  label: IBANforge Credits API
  slug: ibanforge-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-credits-api-openapi.yml
- filename: ibanforge-free-api-openapi.yml
  format: yaml
  label: IBANforge Free API
  slug: ibanforge-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-free-api-openapi.yml
- filename: ibanforge-iban-api-openapi.yml
  format: yaml
  label: IBANforge IBAN API
  slug: ibanforge-iban-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-iban-api-openapi.yml
- filename: ibanforge-mcp-api-openapi.yml
  format: yaml
  label: IBANforge MCP API
  slug: ibanforge-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-mcp-api-openapi.yml
- filename: ibanforge-swiss-clearing-api-openapi.yml
  format: yaml
  label: IBANforge Swiss Clearing API
  slug: ibanforge-swiss-clearing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-swiss-clearing-api-openapi.yml
- filename: ibanforge-account-api-openapi.yml
  format: yaml
  label: IBANforge Account API
  slug: ibanforge-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ibanforge/openapi/ibanforge-account-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: financial
    text: IBANs submitted for validation
  - category: contact
    text: Email address (free key signup)
  - category: device
    text: Request metadata (path, status, latency, timestamp, pseudonymised IP, user-agent, key prefix)
  - category: financial
    text: Payment data Processing card or USDC payments
  - category: professional
    text: 'For sales and support, IBANforge keeps a lightweight record of business contacts: name, role, professional email address, company'
  deletion:
    route: Email support@ibanforge.com
    text: Write to support@ibanforge.com — we answer within 30 days.
  dpa:
    available: true
    text: this policy and the DPA apply regardless of where you are
    url: null
  purposes:
  - purpose: Validation and enrichment
    text: Validation and enrichment (performance of the service)
  - purpose: Producing annotated file audit report
    text: Producing the annotated report you order (performance of the service)
  - purpose: Key issuance and service messages
    text: Issuing your key, quota notifications, service messages, and at most one note from the founder asking whether the key is useful.
  - purpose: Abuse prevention and capacity planning
    text: Abuse prevention, capacity planning, the public status page
  - purpose: Sales and support contact
    text: For sales and support, IBANforge keeps a lightweight record of business contacts
  residency:
  - region: Amsterdam, Netherlands (EU)
    text: The API and its databases run on Railway infrastructure in the Amsterdam, Netherlands region (EU)
  - region: Switzerland
    text: The website and the dashboard run on a virtual server in Infomaniak's public cloud in Switzerland
  retention:
  - period: null
    scope: IBANs submitted for validation
    text: Processed in memory, never written to storage.
  - period: 2 hours
    scope: File audit annotated report
    text: It is kept 2 hours if unpaid and 24 hours after payment , then automatically deleted.
  - period: 12 months
    scope: Request metadata
    text: Yes, 12 months maximum , then automatically deleted.
  - period: 7 days
    scope: Network edge log of API host
    text: Yes, 7 days , then deleted by Railway.
  - period: 90 days
    scope: Email address backups
    text: backups that still hold it age out within 90 days.
  - period: 30 days
    scope: Account state nightly backups
    text: which keeps 30 days of copies
  - period: ten years
    scope: Invoices
    text: we keep it for ten years, as Swiss accounting law requires.
  - period: duration of the business relationship
    scope: Business contact correspondence
    text: Correspondence is kept for the duration of the business relationship
  rights:
  - right: access, rectification, deletion, restriction, copy, objection
    text: Under the FADP/GDPR you can request access, rectification, deletion, restriction, or a copy of your data, and object to processing.
  - right: complaint to supervisory authority
    text: If you are in the EU/EEA you may lodge a complaint with your supervisory authority; in Switzerland, with the FDPIC.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Section 3 lists the processors and where they operate
    url: null
  transfers:
  - mechanism: DPF
    text: for US processors certified under them, the EU-US and Swiss-US Data Privacy Framework
  - mechanism: SCC
    text: standard contractual clauses maintained by the processor
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IBANforge
provenance_date: '2026-11-09'
provider_name: IBANforge
provider_slug: ibanforge
slug: ibanforge-privacy-policy
source_date: '2026-11-09'
source_filename: ibanforge-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ibanforge.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IBANforge\naid: ibanforge\nurl: https://ibanforge.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: financial\n  text: IBANs submitted for validation\n- category: contact\n  text: Email address (free key signup)\n- category: device\n  text: Request metadata (path, status, latency, timestamp, pseudonymised IP, user-agent, key prefix)\n- category: financial\n  text: Payment data Processing card or USDC payments\n- category: professional\n  text: 'For sales and support, IBANforge keeps a lightweight record of business contacts: name, role, professional\n\
  \    email address, company'\npurposes:\n- purpose: Validation and enrichment\n  text: Validation and enrichment (performance of the service)\n- purpose: Producing annotated file audit report\n  text: Producing the annotated report you order (performance of the service)\n- purpose: Key issuance and service messages\n  text: Issuing your key, quota notifications, service messages, and at most one note from the founder asking whether\n    the key is useful.\n- purpose: Abuse prevention and capacity planning\n  text: Abuse prevention, capacity planning, the public status page\n- purpose: Sales and support contact\n  text: For sales and support, IBANforge keeps a lightweight record of business contacts\nretention:\n- scope: IBANs submitted for validation\n  period: null\n  text: Processed in memory, never written to storage.\n- scope: File audit annotated report\n  period: 2 hours\n  text: It is kept 2 hours if unpaid and 24 hours after payment , then automatically deleted.\n- scope: Request\
  \ metadata\n  period: 12 months\n  text: Yes, 12 months maximum , then automatically deleted.\n- scope: Network edge log of API host\n  period: 7 days\n  text: Yes, 7 days , then deleted by Railway.\n- scope: Email address backups\n  period: 90 days\n  text: backups that still hold it age out within 90 days.\n- scope: Account state nightly backups\n  period: 30 days\n  text: which keeps 30 days of copies\n- scope: Invoices\n  period: ten years\n  text: we keep it for ten years, as Swiss accounting law requires.\n- scope: Business contact correspondence\n  period: duration of the business relationship\n  text: Correspondence is kept for the duration of the business relationship\nresidency:\n- region: Amsterdam, Netherlands (EU)\n  text: The API and its databases run on Railway infrastructure in the Amsterdam, Netherlands region (EU)\n- region: Switzerland\n  text: The website and the dashboard run on a virtual server in Infomaniak's public cloud in Switzerland\ntransfers:\n- mechanism:\
  \ DPF\n  text: for US processors certified under them, the EU-US and Swiss-US Data Privacy Framework\n- mechanism: SCC\n  text: standard contractual clauses maintained by the processor\nsubprocessors:\n  url: null\n  text: Section 3 lists the processors and where they operate\ndpa:\n  available: true\n  url: null\n  text: this policy and the DPA apply regardless of where you are\ndeletion:\n  route: Email support@ibanforge.com\n  text: Write to support@ibanforge.com — we answer within 30 days.\nrights:\n- right: access, rectification, deletion, restriction, copy, objection\n  text: Under the FADP/GDPR you can request access, rectification, deletion, restriction, or a copy of your data,\n    and object to processing.\n- right: complaint to supervisory authority\n  text: If you are in the EU/EEA you may lodge a complaint with your supervisory authority; in Switzerland, with\n    the FDPIC.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ibanforge/privacy/ibanforge-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 27 quoted statements, read from IBANforge's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banking
- Compliance
- MCP
- A2A
---
