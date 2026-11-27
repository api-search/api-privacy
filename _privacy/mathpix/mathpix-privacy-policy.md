---
api_specs:
- filename: mathpix-strokes-api-openapi.yml
  format: yaml
  label: Mathpix Strokes API
  slug: mathpix-strokes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mathpix/openapi/mathpix-strokes-api-openapi.yml
- filename: mathpix-app-tokens-api-openapi.yml
  format: yaml
  label: Mathpix App Tokens API
  slug: mathpix-app-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mathpix/openapi/mathpix-app-tokens-api-openapi.yml
- filename: mathpix-batches-api-openapi.yml
  format: yaml
  label: Mathpix Batches API
  slug: mathpix-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mathpix/openapi/mathpix-batches-api-openapi.yml
- filename: mathpix-conversions-api-openapi.yml
  format: yaml
  label: Mathpix Conversions API
  slug: mathpix-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mathpix/openapi/mathpix-conversions-api-openapi.yml
- filename: mathpix-images-api-openapi.yml
  format: yaml
  label: Mathpix Images API
  slug: mathpix-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mathpix/openapi/mathpix-images-api-openapi.yml
- filename: mathpix-usage-api-openapi.yml
  format: yaml
  label: Mathpix Usage API
  slug: mathpix-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mathpix/openapi/mathpix-usage-api-openapi.yml
- filename: mathpix-documents-api-openapi.yml
  format: yaml
  label: Mathpix Documents API
  slug: mathpix-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mathpix/openapi/mathpix-documents-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address and password
  - category: financial
    text: transaction-related information, such as credit card information, when you make purchases or respond to any offers
  - category: device
    text: the IP address of your mobile or desktop device, your mobile or desktop operating system
  - category: behavioral
    text: technical information about the way you use the Application or the API (such as the features or endpoints used, timestamps, processing durations, and request status)
  - category: contact
    text: information you enter into our system when using the Application, such as contact information
  deletion:
    route: Email support@mathpix.com or delete individual Snips in the Application
    text: If you’d like us to delete User Provided Data that you have provided via the Application, please contact us at support@mathpix.com , and we will respond within a reasonable time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Improve recognition engine and QA
    text: whether or not you allow Mathpix to use your images to improve the Mathpix recognition engine
  - purpose: Service security, abuse prevention, billing
    text: This information is used for service security, abuse prevention, operational monitoring and debugging, and billing.
  - purpose: Marketing contact
    text: We may also use the information you provided us to contact you from time to time to provide you with important information, required notices, and marketing promotions.
  residency:
  - region: United States
    text: Mathpix is a U.S. company and processes data in the United States
  - region: European Union (API EU endpoint)
    text: API customers may additionally choose our EU endpoint ( eu.api.mathpix.com ), on which document content and the results derived from it are processed and stored within the European Union
  retention:
  - period: 30 days
    scope: Automatically collected information
    text: We retain Automatically Collected Information for up to 30 days and may store it in aggregate form thereafter.
  - period: up to 30 days
    scope: Console customer provided and automatically collected data
    text: We will retain Customer Provided and Automatically Collected data for up to 30 days, unless you have opted out of data retention for QA.
  rights:
  - right: Access, amend and delete
    text: If you reside in the EU, UK, or Switzerland, you have the right to request access to your personal data, individuals also have the right to amend and delete that data.
  - right: Opt out of new uses or disclosures
    text: Requests to opt out of such uses or disclosures of personal data should be sent to us as specified in the “How to Contact Us” section below.
  role:
    text: Where an organization uses the Mathpix API to process content on behalf of its own users, Mathpix processes that content as a service provider (processor) acting on the organization’s documented instructions under the applicable services agreement and data processing agreement.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A current list of the service providers we engage to deliver our services is available upon request at support@mathpix.com .
    url: null
  transfers:
  - mechanism: DPF
    text: Mathpix complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mathpix
provenance_date: '2026-11-10'
provider_name: Mathpix
provider_slug: mathpix
slug: mathpix-privacy-policy
source_date: '2026-11-10'
source_filename: mathpix-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mathpix.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mathpix\naid: mathpix\nurl: https://mathpix.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where an organization uses the Mathpix API to process content on behalf of its own users, Mathpix processes\n    that content as a service provider (processor) acting on the organization’s documented instructions under the\n    applicable services agreement and data processing agreement.\ndata_categories:\n- category: identifying\n  text: your email address and password\n- category: financial\n  text: transaction-related information, such as credit card information, when you make purchases or respond\
  \ to\n    any offers\n- category: device\n  text: the IP address of your mobile or desktop device, your mobile or desktop operating system\n- category: behavioral\n  text: technical information about the way you use the Application or the API (such as the features or endpoints\n    used, timestamps, processing durations, and request status)\n- category: contact\n  text: information you enter into our system when using the Application, such as contact information\npurposes:\n- purpose: Improve recognition engine and QA\n  text: whether or not you allow Mathpix to use your images to improve the Mathpix recognition engine\n- purpose: Service security, abuse prevention, billing\n  text: This information is used for service security, abuse prevention, operational monitoring and debugging, and\n    billing.\n- purpose: Marketing contact\n  text: We may also use the information you provided us to contact you from time to time to provide you with important\n    information, required notices, and\
  \ marketing promotions.\nretention:\n- scope: Automatically collected information\n  period: 30 days\n  text: We retain Automatically Collected Information for up to 30 days and may store it in aggregate form thereafter.\n- scope: Console customer provided and automatically collected data\n  period: up to 30 days\n  text: We will retain Customer Provided and Automatically Collected data for up to 30 days, unless you have opted\n    out of data retention for QA.\nresidency:\n- region: United States\n  text: Mathpix is a U.S. company and processes data in the United States\n- region: European Union (API EU endpoint)\n  text: API customers may additionally choose our EU endpoint ( eu.api.mathpix.com ), on which document content\n    and the results derived from it are processed and stored within the European Union\ntransfers:\n- mechanism: DPF\n  text: Mathpix complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data\
  \ Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.\nsubprocessors:\n  url: null\n  text: A current list of the service providers we engage to deliver our services is available upon request at support@mathpix.com\n    .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@mathpix.com or delete individual Snips in the Application\n  text: If you’d like us to delete User Provided Data that you have provided via the Application, please contact\n    us at support@mathpix.com , and we will respond within a reasonable time.\nrights:\n- right: Access, amend and delete\n  text: If you reside in the EU, UK, or Switzerland, you have the right to request access to your personal data,\n    individuals also have the right to amend and delete that data.\n- right: Opt out of new uses or disclosures\n  text: Requests to opt out of such uses or disclosures of personal data should be sent to us as specified in the\n    “How to Contact Us”\
  \ section below.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mathpix/privacy/mathpix-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from Mathpix's own page on 2026-11-10.
synthetic: false
tags:
- OCR
- STEM
- Math
- Chemistry
- Document Conversion
- PDF
- LaTeX
- Handwriting
- Artificial Intelligence
- Machine Learning
---
