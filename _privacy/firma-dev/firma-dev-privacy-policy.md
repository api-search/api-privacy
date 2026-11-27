---
api_specs:
- filename: firma-dev-company-api-openapi.yml
  format: yaml
  label: Firma.dev Company API
  slug: firma-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-company-api-openapi.yml
- filename: firma-dev-custom-fields-api-openapi.yml
  format: yaml
  label: Firma.dev Custom Fields API
  slug: firma-dev-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-custom-fields-api-openapi.yml
- filename: firma-dev-email-domains-api-openapi.yml
  format: yaml
  label: Firma.dev Email Domains API
  slug: firma-dev-email-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-email-domains-api-openapi.yml
- filename: firma-dev-email-templates-api-openapi.yml
  format: yaml
  label: Firma.dev Email Templates API
  slug: firma-dev-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-email-templates-api-openapi.yml
- filename: firma-dev-jwt-management-api-openapi.yml
  format: yaml
  label: Firma.dev JWT Management API
  slug: firma-dev-jwt-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-jwt-management-api-openapi.yml
- filename: firma-dev-organization-seals-api-openapi.yml
  format: yaml
  label: Firma.dev Organization Seals API
  slug: firma-dev-organization-seals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-organization-seals-api-openapi.yml
- filename: firma-dev-signer-terms-api-openapi.yml
  format: yaml
  label: Firma.dev Signer Terms API
  slug: firma-dev-signer-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-signer-terms-api-openapi.yml
- filename: firma-dev-signing-requests-api-openapi.yml
  format: yaml
  label: Firma.dev Signing Requests API
  slug: firma-dev-signing-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-signing-requests-api-openapi.yml
- filename: firma-dev-templates-api-openapi.yml
  format: yaml
  label: Firma.dev Templates API
  slug: firma-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-templates-api-openapi.yml
- filename: firma-dev-webhooks-api-openapi.yml
  format: yaml
  label: Firma.dev Webhooks API
  slug: firma-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-webhooks-api-openapi.yml
- filename: firma-dev-workspace-settings-api-openapi.yml
  format: yaml
  label: Firma.dev Workspace Settings API
  slug: firma-dev-workspace-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-workspace-settings-api-openapi.yml
- filename: firma-dev-workspaces-api-openapi.yml
  format: yaml
  label: Firma.dev Workspaces API
  slug: firma-dev-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-workspaces-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, company, job title API keys, account credentials, and support tickets
  - category: identifying
    text: End-User Signers (processed on your behalf) Name, email, signature data
  - category: financial
    text: Billing & invoicing records
  - category: behavioral
    text: Usage logs (envelope creation, signature events)
  deletion:
    route: Request deletion under GDPR Article 17 by contacting support@firma.dev
    text: You may request deletion of your Personal Data under GDPR Article 17. We will comply within 30 days, except for data we are legally obligated to retain
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the service
    text: Provide & maintain the service (authentication, API calls, webhooks)
  - purpose: Process signature requests
    text: Process signature requests and deliver signed documents
  - purpose: Billing and payments
    text: Billing & payments (invoice creation, tax compliance)
  - purpose: Security and compliance
    text: Security & compliance (fraud prevention, audit logs)
  - purpose: Support and maintenance
    text: Support & maintenance (customer questions, bug fixes)
  retention:
  - period: Until account closure or erasure request
    scope: Personal Data
    text: Personal Data Until account closure or erasure request (see exceptions below)
  - period: Indefinitely
    scope: Signed Documents & Audit Trails
    text: Signed Documents & Audit Trails Indefinitely, to satisfy legal & contractual obligations
  - period: 10 years
    scope: Billing & Invoices
    text: Billing & Invoices 10 years (U.S. tax requirements)
  rights:
  - right: Erasure
    text: You may request deletion of your Personal Data under GDPR Article 17.
  - right: Update, export, or erase (business customers)
    text: 'Business Customers: Contact us directly to update, export, or erase your data.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on appropriate safeguards such as Standard Contractual Clauses for GDPR-compliant transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Firma.dev
provenance_date: '2026-11-09'
provider_name: Firma.dev
provider_slug: firma-dev
slug: firma-dev-privacy-policy
source_date: '2026-11-09'
source_filename: firma-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://firma.dev/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Firma.dev\naid: firma-dev\nurl: https://firma.dev/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email, company, job title API keys, account credentials, and support tickets\n- category: identifying\n  text: End-User Signers (processed on your behalf) Name, email, signature data\n- category: financial\n  text: Billing & invoicing records\n- category: behavioral\n  text: Usage logs (envelope creation, signature events)\npurposes:\n- purpose: Provide and maintain the service\n  text: Provide & maintain the service\
  \ (authentication, API calls, webhooks)\n- purpose: Process signature requests\n  text: Process signature requests and deliver signed documents\n- purpose: Billing and payments\n  text: Billing & payments (invoice creation, tax compliance)\n- purpose: Security and compliance\n  text: Security & compliance (fraud prevention, audit logs)\n- purpose: Support and maintenance\n  text: Support & maintenance (customer questions, bug fixes)\nretention:\n- scope: Personal Data\n  period: Until account closure or erasure request\n  text: Personal Data Until account closure or erasure request (see exceptions below)\n- scope: Signed Documents & Audit Trails\n  period: Indefinitely\n  text: Signed Documents & Audit Trails Indefinitely, to satisfy legal & contractual obligations\n- scope: Billing & Invoices\n  period: 10 years\n  text: Billing & Invoices 10 years (U.S. tax requirements)\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: We rely on appropriate safeguards such as Standard Contractual\
  \ Clauses for GDPR-compliant transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion under GDPR Article 17 by contacting support@firma.dev\n  text: You may request deletion of your Personal Data under GDPR Article 17. We will comply within 30 days, except\n    for data we are legally obligated to retain\nrights:\n- right: Erasure\n  text: You may request deletion of your Personal Data under GDPR Article 17.\n- right: Update, export, or erase (business customers)\n  text: 'Business Customers: Contact us directly to update, export, or erase your data.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firma-dev/privacy/firma-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from Firma.dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Signature
- Developer Tools
- LowCost
---
