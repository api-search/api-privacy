---
api_specs:
- filename: cdisc-adam-api-openapi.yml
  format: yaml
  label: cdisc ADaM API
  slug: cdisc-adam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-adam-api-openapi.yml
- filename: cdisc-biomedical-concepts-api-openapi.yml
  format: yaml
  label: cdisc Biomedical Concepts API
  slug: cdisc-biomedical-concepts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-biomedical-concepts-api-openapi.yml
- filename: cdisc-cdash-api-openapi.yml
  format: yaml
  label: cdisc CDASH API
  slug: cdisc-cdash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-cdash-api-openapi.yml
- filename: cdisc-products-api-openapi.yml
  format: yaml
  label: cdisc Products API
  slug: cdisc-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-products-api-openapi.yml
- filename: cdisc-sdtm-api-openapi.yml
  format: yaml
  label: cdisc SDTM API
  slug: cdisc-sdtm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-sdtm-api-openapi.yml
- filename: cdisc-terminology-api-openapi.yml
  format: yaml
  label: cdisc Terminology API
  slug: cdisc-terminology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-terminology-api-openapi.yml
- filename: cdisc-about-api-openapi.yml
  format: yaml
  label: Cdisc About API
  slug: cdisc-about-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-about-api-openapi.yml
- filename: cdisc-analysis-results-standards-ars-api-openapi.yml
  format: yaml
  label: Cdisc Analysis Results Standards (ARS) API
  slug: cdisc-analysis-results-standards-ars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-analysis-results-standards-ars-api-openapi.yml
- filename: cdisc-production-api-openapi.yml
  format: yaml
  label: Cdisc Production API
  slug: cdisc-production-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-production-api-openapi.yml
- filename: cdisc-studies-api-openapi.yml
  format: yaml
  label: Cdisc Studies API
  slug: cdisc-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdisc/openapi/cdisc-studies-api-openapi.yml
claim_count: 8
description: ''
doc:
  data_categories:
  - category: identifying
    text: Users may be asked for, as appropriate, name, email address, mailing address, phone number.
  - category: device
    text: Non-personal identification information may include the browser name, the type of computer and technical information about Users means of connection to our Site
  - category: behavioral
    text: User’s web browser places cookies on their hard drive for record-keeping purposes and sometimes to track information about them.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run and operate the Site
    text: To run and operate our Site - We may need your information display content on the Site correctly.
  - purpose: Improve the Site
    text: To improve our Site - We may use feedback you provide to improve our products and services.
  - purpose: Send periodic emails
    text: To send periodic emails - We may use the email address to respond to their inquiries, questions, and/or other requests.
  role:
    text: CDISC has the discretion to update this privacy policy at any time.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell, trade, or rent Users personal identification information to others. We may share generic aggregated demographic information not linked to any personal identification information regarding visitors and users with our business partners, trusted affiliates and advertisers for the purposes outlined above.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cdisc
provenance_date: '2026-11-09'
provider_name: Cdisc
provider_slug: cdisc
slug: cdisc-privacy-policy
source_date: '2026-11-09'
source_filename: cdisc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cdisc.org/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cdisc\naid: cdisc\nurl: https://www.cdisc.org/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CDISC has the discretion to update this privacy policy at any time.\ndata_categories:\n- category: identifying\n  text: Users may be asked for, as appropriate, name, email address, mailing address, phone number.\n- category: device\n  text: Non-personal identification information may include the browser name, the type of computer and technical\n    information about Users means of connection to our Site\n- category: behavioral\n  text: User’s web browser places cookies on their hard\
  \ drive for record-keeping purposes and sometimes to track\n    information about them.\npurposes:\n- purpose: Run and operate the Site\n  text: To run and operate our Site - We may need your information display content on the Site correctly.\n- purpose: Improve the Site\n  text: To improve our Site - We may use feedback you provide to improve our products and services.\n- purpose: Send periodic emails\n  text: To send periodic emails - We may use the email address to respond to their inquiries, questions, and/or\n    other requests.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell, trade, or rent Users personal identification information to others. We may share generic\n    aggregated demographic information not linked to any personal identification information regarding visitors\n\
  \    and users with our business partners, trusted affiliates and advertisers for the purposes outlined above.\n"
source_yaml_url: https://artifacts.apis.io/cdisc/privacy/cdisc-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- sale_or_sharing
summary_line: 8 quoted statements, read from Cdisc's own page on 2026-11-09.
synthetic: false
tags:
- Clinical Trials
- Standards
- Life Sciences
- Pharma
- Healthcare
- Metadata
- Controlled Terminology
- Data Exchange
- Non-Profit
- Clinical Research
---
