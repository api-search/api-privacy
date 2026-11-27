---
api_specs:
- filename: furiosa-health-api-openapi.yml
  format: yaml
  label: FuriosaAI Health API
  slug: furiosa-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/furiosa/openapi/furiosa-health-api-openapi.yml
- filename: furiosa-models-api-openapi.yml
  format: yaml
  label: FuriosaAI Models API
  slug: furiosa-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/furiosa/openapi/furiosa-models-api-openapi.yml
- filename: furiosa-predict-api-api-openapi.yml
  format: yaml
  label: FuriosaAI Predict API
  slug: furiosa-predict-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/furiosa/openapi/furiosa-predict-api-api-openapi.yml
- filename: furiosa-repository-api-openapi.yml
  format: yaml
  label: FuriosaAI Repository API
  slug: furiosa-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/furiosa/openapi/furiosa-repository-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email address, mobile phone number, address
  - category: professional
    text: education, work experience
  - category: communication
    text: details of inquiry
  deletion:
    route: Data subject deletion request
    text: any Personal Data shall be destroyed without delay if the data subject requests deletion
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: recruitment
    text: For the provision of information and notices relating to recruitment, communications relating to recruitment and use of the website, and supporting documents to determine suitability for employment and conduct screenings/interviews
  - purpose: inquiry responses
    text: For responding to inquiries and managing their history
  - purpose: product orders
    text: For communications with customers, shipping products, and managing deliveries and shipping following product orders
  retention:
  - period: By the end of the recruitment process
    scope: recruitment
    text: By the end of the recruitment process
  - period: 3 years from the date of receipt of the inquiry
    scope: website inquiries
    text: 3 years from the date of receipt of the inquiry; provided, however, that any Personal Data shall be destroyed without delay if the data subject requests deletion
  - period: 3 years from the date of placing a product order
    scope: product orders
    text: 3 years from the date of placing a product order; provided, however, that any Personal Data shall be destroyed without delay if the data subject requests deletion
  - period: null
    scope: newsletters
    text: By the time when the subscriber unsubscribes from the newsletter service or the Company terminates the newsletter service
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
  - mechanism: other
    text: The Company shall obtain the separate consent of the Users for transfer of Personal Data to an overseas entity (including the case where the Personal Data is inspected by an overseas entity) or entrustment of the processing and storage with an overseas entity
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FuriosaAI
provenance_date: '2026-11-09'
provider_name: FuriosaAI
provider_slug: furiosa
slug: furiosa-privacy-policy
source_date: '2026-11-09'
source_filename: furiosa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://furiosa.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FuriosaAI\naid: furiosa\nurl: https://furiosa.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, email address, mobile phone number, address\n- category: professional\n  text: education, work experience\n- category: communication\n  text: details of inquiry\npurposes:\n- purpose: recruitment\n  text: For the provision of information and notices relating to recruitment, communications relating to recruitment\n    and use of the website, and supporting documents to determine suitability for employment and conduct screenings/interviews\n\
  - purpose: inquiry responses\n  text: For responding to inquiries and managing their history\n- purpose: product orders\n  text: For communications with customers, shipping products, and managing deliveries and shipping following product\n    orders\nretention:\n- scope: recruitment\n  period: By the end of the recruitment process\n  text: By the end of the recruitment process\n- scope: website inquiries\n  period: 3 years from the date of receipt of the inquiry\n  text: 3 years from the date of receipt of the inquiry; provided, however, that any Personal Data shall be destroyed\n    without delay if the data subject requests deletion\n- scope: product orders\n  period: 3 years from the date of placing a product order\n  text: 3 years from the date of placing a product order; provided, however, that any Personal Data shall be destroyed\n    without delay if the data subject requests deletion\n- scope: newsletters\n  period: null\n  text: By the time when the subscriber unsubscribes from\
  \ the newsletter service or the Company terminates the newsletter\n    service\nresidency: []\ntransfers:\n- mechanism: other\n  text: The Company shall obtain the separate consent of the Users for transfer of Personal Data to an overseas\n    entity (including the case where the Personal Data is inspected by an overseas entity) or entrustment of the\n    processing and storage with an overseas entity\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data subject deletion request\n  text: any Personal Data shall be destroyed without delay if the data subject requests deletion\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/furiosa/privacy/furiosa-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
summary_line: 12 quoted statements, read from FuriosaAI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Inference
- Semiconductors
- NPU
- Hardware
- LLM
- Model Serving
- Kubernetes
- Developer Tools
- Compute
- Infrastructure
---
