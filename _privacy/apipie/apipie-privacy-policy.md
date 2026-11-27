---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: This typically includes your email address and name .
  - category: device
    text: Your device's IP address, browser type/version, operating system, and access times.
  - category: behavioral
    text: Details on every API query (as provided by our Usage feature), including the specific model used, token counts, response times, costs, and unique user identifiers or source IPs.
  - category: financial
    text: In case of services requiring payment, we request credit card or other payment account information, which will be used solely for processing payments.
  deletion:
    route: Account settings or contact us
    text: You are able to access, add to, update and delete certain Personal Information about you.
  dpa:
    available: true
    text: Data Processing Addendum (DPA) Official Data Processing Addendum describing how Neuronic AI / APIpie processes, stores, and protects customer data
    url: null
  purposes:
  - purpose: Account and service operation
    text: run and operate our Services
  - purpose: Abuse detection and statistics
    text: Information collected automatically is used only to identify potential cases of abuse and establish statistical information regarding Services usage.
  - purpose: Fulfilling API requests via sub-processors
    text: for the purpose of fulfilling your API requests
  retention:
  - period: null
    scope: Prompt bodies of stateless API calls
    text: we generally implement a strict no-logging policy for prompt bodies . We process the data in memory to route it to the appropriate external model ( Models Route , Preferred Routing ) and then discard the prompt body.
  - period: null
    scope: Stateful services (RAG/Memory) content
    text: retained as long as required by your account settings or until you manually delete it.
  - period: null
    scope: Payment transaction data
    text: Your purchase transaction data is stored only as long as is necessary to complete your purchase transaction. After that is complete, your purchase transaction information is deleted.
  rights:
  - right: Access
    text: Learn if information is being processed by us, obtain disclosure regarding certain aspects of the processing, and obtain a copy of the information undergoing processing;
  - right: Erasure
    text: Obtain the erasure of your Personal Information from us, under certain circumstances;
  - right: Rectification
    text: Verify the accuracy of your information and ask for it to be updated or corrected;
  - right: Restriction
    text: Restrict the processing of your information, under certain circumstances;
  - right: Portability
    text: Receive your information in a structured, commonly used and machine-readable format
  - right: Object
    text: Object to the processing of your information if the processing is carried out on a legal basis other than consent;
  - right: Withdraw consent
    text: Withdraw consent where you have previously given your consent to the processing of your information;
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The full, current list of Sub-processors is detailed in the Data Processing Addendum (DPA).
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on legal transfer mechanisms, such as Standard Contractual Clauses (SCCs), where required for international transfers, as detailed in our DPA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: APIpie
provenance_date: '2026-11-09'
provider_name: APIpie
provider_slug: apipie
slug: apipie-privacy-policy
source_date: '2026-11-09'
source_filename: apipie-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apipie.ai/docs/terms/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: APIpie\naid: apipie\nurl: https://apipie.ai/docs/terms/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: This typically includes your email address and name .\n- category: device\n  text: Your device's IP address, browser type/version, operating system, and access times.\n- category: behavioral\n  text: Details on every API query (as provided by our Usage feature), including the specific model used, token\n    counts, response times, costs, and unique user identifiers or source IPs.\n- category: financial\n  text: In case of services\
  \ requiring payment, we request credit card or other payment account information, which\n    will be used solely for processing payments.\npurposes:\n- purpose: Account and service operation\n  text: run and operate our Services\n- purpose: Abuse detection and statistics\n  text: Information collected automatically is used only to identify potential cases of abuse and establish statistical\n    information regarding Services usage.\n- purpose: Fulfilling API requests via sub-processors\n  text: for the purpose of fulfilling your API requests\nretention:\n- scope: Prompt bodies of stateless API calls\n  period: null\n  text: we generally implement a strict no-logging policy for prompt bodies . We process the data in memory to route\n    it to the appropriate external model ( Models Route , Preferred Routing ) and then discard the prompt body.\n- scope: Stateful services (RAG/Memory) content\n  period: null\n  text: retained as long as required by your account settings or until you manually\
  \ delete it.\n- scope: Payment transaction data\n  period: null\n  text: Your purchase transaction data is stored only as long as is necessary to complete your purchase transaction.\n    After that is complete, your purchase transaction information is deleted.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: We rely on legal transfer mechanisms, such as Standard Contractual Clauses (SCCs), where required for international\n    transfers, as detailed in our DPA.\nsubprocessors:\n  url: null\n  text: The full, current list of Sub-processors is detailed in the Data Processing Addendum (DPA).\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum (DPA) Official Data Processing Addendum describing how Neuronic AI / APIpie processes,\n    stores, and protects customer data\ndeletion:\n  route: Account settings or contact us\n  text: You are able to access, add to, update and delete certain Personal Information about you.\nrights:\n- right: Access\n  text: Learn if information\
  \ is being processed by us, obtain disclosure regarding certain aspects of the processing,\n    and obtain a copy of the information undergoing processing;\n- right: Erasure\n  text: Obtain the erasure of your Personal Information from us, under certain circumstances;\n- right: Rectification\n  text: Verify the accuracy of your information and ask for it to be updated or corrected;\n- right: Restriction\n  text: Restrict the processing of your information, under certain circumstances;\n- right: Portability\n  text: Receive your information in a structured, commonly used and machine-readable format\n- right: Object\n  text: Object to the processing of your information if the processing is carried out on a legal basis other than\n    consent;\n- right: Withdraw consent\n  text: Withdraw consent where you have previously given your consent to the processing of your information;\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apipie/privacy/apipie-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 21 quoted statements, read from APIpie's own page on 2026-11-09.
synthetic: false
tags:
- OpenAI-compatible API
- Redundant routing
---
