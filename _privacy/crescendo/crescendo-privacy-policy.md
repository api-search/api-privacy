---
api_specs:
- filename: crescendo-mcp-api-openapi.yml
  format: yaml
  label: Crescendo MCP API
  slug: crescendo-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-mcp-api-openapi.yml
- filename: crescendo-provisioning-api-openapi.yml
  format: yaml
  label: Crescendo Provisioning API
  slug: crescendo-provisioning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-provisioning-api-openapi.yml
- filename: crescendo-reporting-api-openapi.yml
  format: yaml
  label: Crescendo Reporting API
  slug: crescendo-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-reporting-api-openapi.yml
- filename: crescendo-service-api-openapi.yml
  format: yaml
  label: Crescendo Service API
  slug: crescendo-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-service-api-openapi.yml
- filename: crescendo-voc-api-openapi.yml
  format: yaml
  label: Crescendo VOC API
  slug: crescendo-voc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo/openapi/crescendo-voc-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: email address; phone number; first name; last name
  - category: behavioral
    text: clicks; page views; interaction events; user content
  - category: location
    text: latitude (of city); longitude (of city)
  - category: device
    text: device information
  deletion:
    route: Contact the Owner using the contact details in the policy
    text: Any requests to exercise User rights can be directed to the Owner through the contact details provided in this document.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Analytics
    text: Analytics, User database management, Advertising, Contacting the User
  - purpose: Advertising
    text: This type of service allows User Data to be utilized for advertising communication purposes.
  - purpose: Remarketing and behavioral targeting
    text: Remarketing and behavioral targeting
  residency:
  - region: Owner's operating offices and other places of the parties involved
    text: The Data is processed at the Owner's operating offices and in any other places where the parties involved in the processing are located.
  retention:
  - period: as long as required by the purpose they have been collected for
    scope: general
    text: Personal Data shall be processed and stored for as long as required by the purpose they have been collected for
  rights:
  - right: Access their Data
    text: Users have the right to learn if Data is being processed by the Owner, obtain disclosure regarding certain aspects of the processing and obtain a copy of the Data undergoing processing.
  - right: Have their Personal Data deleted
    text: Users have the right to obtain the erasure of their Data from the Owner.
  - right: Object to processing
    text: Users have the right to object to the processing of their Data if the processing is carried out on a legal basis other than consent.
  role:
    text: Owner and Data Controller CrescendoAI Inc
    value: controller
  sale_or_sharing:
    stance: allowed
    text: 'This processing constitutes: a Sale in the United States'
  subprocessors:
    text: The updated list of these parties may be requested from the Owner at any time.
    url: null
  transfers:
  - mechanism: other
    text: Depending on the User's location, data transfers may involve transferring the User's Data to a country other than their own.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Crescendo
provenance_date: '2026-11-09'
provider_name: Crescendo
provider_slug: crescendo
slug: crescendo-privacy-policy
source_date: '2026-11-09'
source_filename: crescendo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.crescendo.ai/policies/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Crescendo\naid: crescendo\nurl: https://www.crescendo.ai/policies/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Owner and Data Controller CrescendoAI Inc\ndata_categories:\n- category: contact\n  text: email address; phone number; first name; last name\n- category: behavioral\n  text: clicks; page views; interaction events; user content\n- category: location\n  text: latitude (of city); longitude (of city)\n- category: device\n  text: device information\npurposes:\n- purpose: Analytics\n  text: Analytics, User database management, Advertising, Contacting the User\n\
  - purpose: Advertising\n  text: This type of service allows User Data to be utilized for advertising communication purposes.\n- purpose: Remarketing and behavioral targeting\n  text: Remarketing and behavioral targeting\nretention:\n- scope: general\n  period: as long as required by the purpose they have been collected for\n  text: Personal Data shall be processed and stored for as long as required by the purpose they have been collected\n    for\nresidency:\n- region: Owner's operating offices and other places of the parties involved\n  text: The Data is processed at the Owner's operating offices and in any other places where the parties involved\n    in the processing are located.\ntransfers:\n- mechanism: other\n  text: Depending on the User's location, data transfers may involve transferring the User's Data to a country other\n    than their own.\nsubprocessors:\n  url: null\n  text: The updated list of these parties may be requested from the Owner at any time.\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Contact the Owner using the contact details in the policy\n  text: Any requests to exercise User rights can be directed to the Owner through the contact details provided in\n    this document.\nrights:\n- right: Access their Data\n  text: Users have the right to learn if Data is being processed by the Owner, obtain disclosure regarding certain\n    aspects of the processing and obtain a copy of the Data undergoing processing.\n- right: Have their Personal Data deleted\n  text: Users have the right to obtain the erasure of their Data from the Owner.\n- right: Object to processing\n  text: Users have the right to object to the processing of their Data if the processing is carried out on a legal\n    basis other than consent.\nsale_or_sharing:\n  stance: allowed\n  text: 'This processing constitutes: a Sale in the United States'\n"
source_yaml_url: https://artifacts.apis.io/crescendo/privacy/crescendo-privacy-policy.yml
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
- sale_or_sharing
summary_line: 17 quoted statements, read from Crescendo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Customer Service
- Artificial Intelligence
- AI Agents
- Contact Center
- Conversational AI
- Voice of Customer
- MCP
- Platform
- Automation
---
