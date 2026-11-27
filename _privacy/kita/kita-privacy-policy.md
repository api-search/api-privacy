---
api_specs:
- filename: kita-applications-api-openapi.yml
  format: yaml
  label: Kita Applications API
  slug: kita-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-applications-api-openapi.yml
- filename: kita-batch-api-openapi.yml
  format: yaml
  label: Kita Batch API
  slug: kita-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-batch-api-openapi.yml
- filename: kita-conversation-api-openapi.yml
  format: yaml
  label: Kita Conversation API
  slug: kita-conversation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-conversation-api-openapi.yml
- filename: kita-credit-api-openapi.yml
  format: yaml
  label: Kita Credit API
  slug: kita-credit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-credit-api-openapi.yml
- filename: kita-documents-api-openapi.yml
  format: yaml
  label: Kita Documents API
  slug: kita-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-documents-api-openapi.yml
- filename: kita-exports-api-openapi.yml
  format: yaml
  label: Kita Exports API
  slug: kita-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-exports-api-openapi.yml
- filename: kita-folders-api-openapi.yml
  format: yaml
  label: Kita Folders API
  slug: kita-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-folders-api-openapi.yml
- filename: kita-memo-api-openapi.yml
  format: yaml
  label: Kita Memo API
  slug: kita-memo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-memo-api-openapi.yml
- filename: kita-processing-api-openapi.yml
  format: yaml
  label: Kita Processing API
  slug: kita-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-processing-api-openapi.yml
- filename: kita-results-api-openapi.yml
  format: yaml
  label: Kita Results API
  slug: kita-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-results-api-openapi.yml
- filename: kita-schemas-api-openapi.yml
  format: yaml
  label: Kita Schemas API
  slug: kita-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-schemas-api-openapi.yml
- filename: kita-transcripts-api-openapi.yml
  format: yaml
  label: Kita Transcripts API
  slug: kita-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-transcripts-api-openapi.yml
- filename: kita-verification-api-openapi.yml
  format: yaml
  label: Kita Verification API
  slug: kita-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-verification-api-openapi.yml
- filename: kita-webhooks-api-openapi.yml
  format: yaml
  label: Kita Webhooks API
  slug: kita-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-webhooks-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information. If you create an account, we collect information such as your name, email, organization, and password.
  - category: contact
    text: Certain features (such as Contact Us or the Playground) require personal information like your name, company, email, and any message you provide.
  - category: professional
    text: Job applications. When you apply for a role, we collect your name, email, résumé, and any links or additional information you submit.
  - category: device
    text: Web log data. When you use the Services, we automatically receive IP address, pages visited, timestamps, URLs, device attributes, general location, and cookie information.
  - category: behavioral
    text: Cookies. We use cookies to recognize repeat visits and collect usage information.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and communications
    text: We use the information described above to provide the Services; respond to questions; fulfill requests; send operational communications; improve quality; analyze usage
  - purpose: Evaluate job applications
    text: We use this information to evaluate your application and communicate with you about hiring.
  - purpose: Create new products
    text: create new products and services; and manage our business.
  residency:
  - region: United States
    text: Information collected through the Services is transferred to and processed in the United States.
  - region: Mexico, Singapore, Indonesia
    text: Customers using our regional processing options for Mexico, Singapore, or Indonesia may have data residency confined to those regions per agreement.
  retention:
  - period: null
    scope: Personal information generally
    text: We retain personal information only as long as necessary to fulfill the purposes for which it was collected, or as required or permitted by law.
  - period: null
    scope: Customer documents
    text: documents can be purged immediately on processing or held for a contracted timeline.
  rights:
  - right: Access
    text: access, correction, deletion, limitation of sensitive data use, opt-out of sale/sharing or targeted advertising
  - right: Opt-out of automated decision making
    text: opt-out of certain automated decision making
  - right: Appeal
    text: Appeals may be submitted to support@kita.ai with the subject "Appeal of Decision Related to Privacy Rights Request."
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
name: Kita
provenance_date: '2026-11-09'
provider_name: Kita
provider_slug: kita
slug: kita-privacy-policy
source_date: '2026-11-09'
source_filename: kita-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.kita.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Kita\naid: kita\nurl: https://www.kita.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information. If you create an account, we collect information such as your name, email, organization,\n    and password.\n- category: contact\n  text: Certain features (such as Contact Us or the Playground) require personal information like your name, company,\n    email, and any message you provide.\n- category: professional\n  text: Job applications. When you apply for a role, we collect your name, email, résumé, and any links or\
  \ additional\n    information you submit.\n- category: device\n  text: Web log data. When you use the Services, we automatically receive IP address, pages visited, timestamps,\n    URLs, device attributes, general location, and cookie information.\n- category: behavioral\n  text: Cookies. We use cookies to recognize repeat visits and collect usage information.\npurposes:\n- purpose: Provide services and communications\n  text: We use the information described above to provide the Services; respond to questions; fulfill requests;\n    send operational communications; improve quality; analyze usage\n- purpose: Evaluate job applications\n  text: We use this information to evaluate your application and communicate with you about hiring.\n- purpose: Create new products\n  text: create new products and services; and manage our business.\nretention:\n- scope: Personal information generally\n  period: null\n  text: We retain personal information only as long as necessary to fulfill the purposes\
  \ for which it was collected,\n    or as required or permitted by law.\n- scope: Customer documents\n  period: null\n  text: documents can be purged immediately on processing or held for a contracted timeline.\nresidency:\n- region: United States\n  text: Information collected through the Services is transferred to and processed in the United States.\n- region: Mexico, Singapore, Indonesia\n  text: Customers using our regional processing options for Mexico, Singapore, or Indonesia may have data residency\n    confined to those regions per agreement.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: access, correction, deletion, limitation of sensitive data use, opt-out of sale/sharing or targeted advertising\n- right: Opt-out of automated decision making\n  text: opt-out of certain automated decision making\n- right: Appeal\n  text: Appeals may be submitted\
  \ to support@kita.ai with the subject \"Appeal of Decision Related to Privacy Rights\n    Request.\"\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kita/privacy/kita-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- rights
summary_line: 15 quoted statements, read from Kita's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Underwriting
- Credit Scoring
- Document Intelligence
- Document Extraction
- Fraud Prevention
- Artificial Intelligence
- Computer Vision
- Emerging Markets
- Loan Origination
---
