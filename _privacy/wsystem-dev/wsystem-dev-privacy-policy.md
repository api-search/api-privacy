---
api_specs:
- filename: wsystem-dev-billing-api-openapi.yml
  format: yaml
  label: wsystem-dev Billing API
  slug: wsystem-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-billing-api-openapi.yml
- filename: wsystem-dev-company-api-openapi.yml
  format: yaml
  label: wsystem-dev Company API
  slug: wsystem-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-company-api-openapi.yml
- filename: wsystem-dev-e-invoice-api-openapi.yml
  format: yaml
  label: wsystem-dev E Invoice API
  slug: wsystem-dev-e-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-e-invoice-api-openapi.yml
- filename: wsystem-dev-eori-api-openapi.yml
  format: yaml
  label: wsystem-dev EORI API
  slug: wsystem-dev-eori-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-eori-api-openapi.yml
- filename: wsystem-dev-health-api-openapi.yml
  format: yaml
  label: wsystem-dev Health API
  slug: wsystem-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-health-api-openapi.yml
- filename: wsystem-dev-kyb-api-openapi.yml
  format: yaml
  label: wsystem-dev KYB API
  slug: wsystem-dev-kyb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-kyb-api-openapi.yml
- filename: wsystem-dev-sanctions-api-openapi.yml
  format: yaml
  label: wsystem-dev Sanctions API
  slug: wsystem-dev-sanctions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-sanctions-api-openapi.yml
- filename: wsystem-dev-vat-api-openapi.yml
  format: yaml
  label: wsystem-dev VAT API
  slug: wsystem-dev-vat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wsystem-dev/openapi/wsystem-dev-vat-api-openapi.yml
claim_count: 6
description: ''
doc:
  deletion:
    route: Deletion as set out in the DPA after export window
    text: then delete them as set out in the DPA, unless the law requires W System to keep them.
  dpa:
    available: true
    text: The W System Data Processing Agreement (https://wsystem.dev/legal/dpa, in the version in force) applies and forms part of these terms.
    url: https://wsystem.dev/legal/dpa
  purposes:
  - purpose: Anonymised and aggregated use
    text: The Company allows W System and E-invoice BV to use its data in anonymised and aggregated form to run, secure and improve the service and to produce statistics, never in a way that identifies the Company or any person.
  retention:
  - period: at least 30 days
    scope: Company documents after service ends
    text: keep the Company's documents and transmission records available for export through the API, or in another reasonable format on request, for at least 30 days after the service ends, and then delete them as set out in the DPA, unless the law requires W System to keep them.
  role:
    text: For personal data in the documents the Company is the controller and W System is a processor.
    value: processor
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The Company agrees that W System uses E-invoice BV and its sub-processors as sub-processors.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: wsystem-dev
provenance_date: '2026-11-10'
provider_name: wsystem-dev
provider_slug: wsystem-dev
slug: wsystem-dev-privacy-policy
source_date: '2026-11-10'
source_filename: wsystem-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://wsystem.dev/legal/peppol-mandate-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: wsystem-dev\naid: wsystem-dev\nurl: https://wsystem.dev/legal/peppol-mandate-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: For personal data in the documents the Company is the controller and W System is a processor.\ndata_categories: []\npurposes:\n- purpose: Anonymised and aggregated use\n  text: The Company allows W System and E-invoice BV to use its data in anonymised and aggregated form to run, secure\n    and improve the service and to produce statistics, never in a way that identifies the Company or any person.\nretention:\n- scope: Company documents after service ends\n  period:\
  \ at least 30 days\n  text: keep the Company's documents and transmission records available for export through the API, or in another\n    reasonable format on request, for at least 30 days after the service ends, and then delete them as set out in\n    the DPA, unless the law requires W System to keep them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The Company agrees that W System uses E-invoice BV and its sub-processors as sub-processors.\ndpa:\n  available: true\n  url: https://wsystem.dev/legal/dpa\n  text: The W System Data Processing Agreement (https://wsystem.dev/legal/dpa, in the version in force) applies\n    and forms part of these terms.\ndeletion:\n  route: Deletion as set out in the DPA after export window\n  text: then delete them as set out in the DPA, unless the law requires W System to keep them.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wsystem-dev/privacy/wsystem-dev-privacy-policy.yml
stated_fields:
- role
- purposes
- retention
- subprocessors
- dpa
- deletion
summary_line: 6 quoted statements, read from wsystem-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Invoicing
- European
- Compliance
---
