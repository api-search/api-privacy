---
api_specs:
- filename: misoai-ask-apis-api-openapi.yml
  format: yaml
  label: miso.ai Ask APIs API
  slug: misoai-ask-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-ask-apis-api-openapi.yml
- filename: misoai-bulk-api-api-openapi.yml
  format: yaml
  label: miso.ai Bulk API
  slug: misoai-bulk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-bulk-api-api-openapi.yml
- filename: misoai-experiment-apis-api-openapi.yml
  format: yaml
  label: miso.ai Experiment APIs API
  slug: misoai-experiment-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-experiment-apis-api-openapi.yml
- filename: misoai-interaction-apis-api-openapi.yml
  format: yaml
  label: miso.ai Interaction APIs API
  slug: misoai-interaction-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-interaction-apis-api-openapi.yml
- filename: misoai-product-content-apis-api-openapi.yml
  format: yaml
  label: miso.ai Product / Content APIs API
  slug: misoai-product-content-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-product-content-apis-api-openapi.yml
- filename: misoai-product-recommendations-api-openapi.yml
  format: yaml
  label: miso.ai Product Recommendations API
  slug: misoai-product-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-product-recommendations-api-openapi.yml
- filename: misoai-q-a-apis-api-openapi.yml
  format: yaml
  label: miso.ai Q&A APIs API
  slug: misoai-q-a-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-q-a-apis-api-openapi.yml
- filename: misoai-search-apis-api-openapi.yml
  format: yaml
  label: miso.ai Search APIs API
  slug: misoai-search-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-search-apis-api-openapi.yml
- filename: misoai-user-apis-api-openapi.yml
  format: yaml
  label: miso.ai User APIs API
  slug: misoai-user-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-user-apis-api-openapi.yml
- filename: misoai-user-recommendations-api-openapi.yml
  format: yaml
  label: miso.ai User Recommendations API
  slug: misoai-user-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-user-recommendations-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: This may include personal information such as your name, email address, location, browser or other technical data, and it includes your interaction history with our Customer’s website, application, or services.
  - category: contact
    text: name, phone number, email address, billing information or other information that is given to us by the Customer voluntarily over the course of our business relationship.
  - category: behavioral
    text: we may collect information about your browsing activity so that we can better improve the Services.
  deletion:
    route: contact privacy@askmiso.com
    text: Individuals wishing to exercise any of these rights may contact us via e-mail at privacy@askmiso.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: search result optimization
    text: Miso is an artificial intelligence machine learning engine that is used to drive more efficient search results by learning from the individuals using the Services (You).
  - purpose: service performance auditing
    text: is used in its disaggregated and depersonalized form to audit and review the performance of the Services, including uptime, latency, and lag.
  - purpose: own marketing and internal business
    text: We use this information for our own marketing and internal business purposes, which You can opt out of at any time.
  residency:
  - region: United States
    text: We are located in the United States and we do all processing in the United States.
  retention:
  - period: null
    scope: personal data retained by us
    text: All Personal Data retained by us will be deleted when such Personal Data are no longer necessary for the purposes for which it was processed, unless applicable law requires a longer retention period.
  rights:
  - right: access
    text: To request access to the Personal Data that we hold about You and to request that we rectify or erase it;
  - right: copy
    text: To request a copy of the Personal Data that we hold about You;
  - right: portability
    text: To request a transfer of your Personal Data from us to another data controller; and
  - right: restriction or objection
    text: To request restriction of processing of your Personal Data or object to its processing.
  - right: withdraw consent
    text: You have the right to withdraw that consent at any time.
  role:
    text: At times, we may operate as a data “processor,” processing your personal information at the direction of our Customer who has collected your Personal Data.
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell this data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Miso complies with the EU-U.S. Data Privacy Framework (“ EU-U.S. DPF ”) and the UK Extension to the EU-U.S. DPF as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: miso.ai
provenance_date: '2026-11-10'
provider_name: miso.ai
provider_slug: misoai
slug: misoai-privacy-policy
source_date: '2026-11-10'
source_filename: misoai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://miso.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: miso.ai\naid: misoai\nurl: https://miso.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: At times, we may operate as a data “processor,” processing your personal information at the direction of\n    our Customer who has collected your Personal Data.\ndata_categories:\n- category: identifying\n  text: This may include personal information such as your name, email address, location, browser or other technical\n    data, and it includes your interaction history with our Customer’s website, application, or services.\n- category: contact\n  text: name, phone number, email address, billing\
  \ information or other information that is given to us by the Customer\n    voluntarily over the course of our business relationship.\n- category: behavioral\n  text: we may collect information about your browsing activity so that we can better improve the Services.\npurposes:\n- purpose: search result optimization\n  text: Miso is an artificial intelligence machine learning engine that is used to drive more efficient search results\n    by learning from the individuals using the Services (You).\n- purpose: service performance auditing\n  text: is used in its disaggregated and depersonalized form to audit and review the performance of the Services,\n    including uptime, latency, and lag.\n- purpose: own marketing and internal business\n  text: We use this information for our own marketing and internal business purposes, which You can opt out of at\n    any time.\nretention:\n- scope: personal data retained by us\n  period: null\n  text: All Personal Data retained by us will be deleted\
  \ when such Personal Data are no longer necessary for the\n    purposes for which it was processed, unless applicable law requires a longer retention period.\nresidency:\n- region: United States\n  text: We are located in the United States and we do all processing in the United States.\ntransfers:\n- mechanism: DPF\n  text: Miso complies with the EU-U.S. Data Privacy Framework (“ EU-U.S. DPF ”) and the UK Extension to the EU-U.S.\n    DPF as set forth by the U.S. Department of Commerce.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact privacy@askmiso.com\n  text: Individuals wishing to exercise any of these rights may contact us via e-mail at privacy@askmiso.com .\nrights:\n- right: access\n  text: To request access to the Personal Data that we hold about You and to request that we rectify or erase it;\n- right: copy\n  text: To request a copy of the Personal Data that we hold about You;\n- right: portability\n\
  \  text: To request a transfer of your Personal Data from us to another data controller; and\n- right: restriction or objection\n  text: To request restriction of processing of your Personal Data or object to its processing.\n- right: withdraw consent\n  text: You have the right to withdraw that consent at any time.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell this data.\n"
source_yaml_url: https://artifacts.apis.io/misoai/privacy/misoai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from miso.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Search
- Recommendations
- Personalization
- Semantic Search
- LLM
- Question Answering
- Publishing
- Media
- Retail
- E-Commerce
- Developers
---
