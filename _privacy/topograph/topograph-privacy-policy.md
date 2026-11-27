---
api_specs:
- filename: topograph-billing-api-openapi.yml
  format: yaml
  label: Topograph Billing API
  slug: topograph-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topograph/openapi/topograph-billing-api-openapi.yml
- filename: topograph-billing-notifications-api-openapi.yml
  format: yaml
  label: Topograph Billing Notifications API
  slug: topograph-billing-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topograph/openapi/topograph-billing-notifications-api-openapi.yml
- filename: topograph-data-api-openapi.yml
  format: yaml
  label: Topograph Data API
  slug: topograph-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topograph/openapi/topograph-data-api-openapi.yml
- filename: topograph-monitors-api-openapi.yml
  format: yaml
  label: Topograph Monitors API
  slug: topograph-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topograph/openapi/topograph-monitors-api-openapi.yml
- filename: topograph-pricing-api-openapi.yml
  format: yaml
  label: Topograph Pricing API
  slug: topograph-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topograph/openapi/topograph-pricing-api-openapi.yml
- filename: topograph-search-api-openapi.yml
  format: yaml
  label: Topograph Search API
  slug: topograph-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topograph/openapi/topograph-search-api-openapi.yml
- filename: topograph-workspaces-api-openapi.yml
  format: yaml
  label: Topograph Workspaces API
  slug: topograph-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/topograph/openapi/topograph-workspaces-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information on your identity;
  - category: professional
    text: Information on your relationship with a company, such as if you are a legal representative;
  - category: other
    text: Information that appears in legal documentation with regard to a company;
  deletion:
    route: Email privacy@topograph.co with a request to exercise the right to erasure
    text: 'You may ask us to delete all or part of the data we have that relates to you, where one at least of the conditions below is met:'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: AML/CFT products for obliged entities and competent authorities
    text: Topograph’s processing of your personal data is justified in that it is necessary to fulfil Topograph’s legitimate interest in developing and providing its AML/CFT products to obliged entities and competent authorities (article 6.1.f) of GDPR)
  - purpose: Proof of compliance
    text: Some of your personal data shall be further processed as a probatory measure for the purpose of proving Topograph’s compliance with applicable laws and regulations.
  retention:
  - period: as long as it appears in official company and ultimate beneficial ownership registers
    scope: Register personal data
    text: We retain your data for as long as it appears in official company and ultimate beneficial ownership registers
  - period: 5 years
    scope: Probatory retention
    text: and for an additional duration of 5 years as a probatory measure.
  rights:
  - right: Access
    text: You have the right to request a copy of all personal data we have that relates to you
  - right: Rectification
    text: You have the right to ask us to rectify, complete or update personal data we have that relates to you
  - right: Object
    text: You have a right to object to the processing activities above on grounds relating to your particular situation.
  - right: Erasure
    text: Right to erasure (right to be forgotten)
  - right: Limitation of processing
    text: Right to limitation of processing
  - right: Post-mortem directives
    text: Right to provide directives regarding your data after your death
  role:
    text: The data controller in the context of this Privacy Policy is Topograph SAS, a French company
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: our service provider or client is self-certified under the Data Privacy Framework
  - mechanism: SCC
    text: the standard contractual clauses adopted by the European Commission on June 4th 2021
  - mechanism: BCR
    text: our service provider or client has implemented binding corporate rules
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Topograph
provenance_date: '2026-11-10'
provider_name: Topograph
provider_slug: topograph
slug: topograph-privacy-policy
source_date: '2026-11-10'
source_filename: topograph-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.topograph.co/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Topograph\naid: topograph\nurl: https://www.topograph.co/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller in the context of this Privacy Policy is Topograph SAS, a French company\ndata_categories:\n- category: identifying\n  text: Information on your identity;\n- category: professional\n  text: Information on your relationship with a company, such as if you are a legal representative;\n- category: other\n  text: Information that appears in legal documentation with regard to a company;\npurposes:\n- purpose: AML/CFT products for obliged entities and competent\
  \ authorities\n  text: Topograph’s processing of your personal data is justified in that it is necessary to fulfil Topograph’s\n    legitimate interest in developing and providing its AML/CFT products to obliged entities and competent authorities\n    (article 6.1.f) of GDPR)\n- purpose: Proof of compliance\n  text: Some of your personal data shall be further processed as a probatory measure for the purpose of proving\n    Topograph’s compliance with applicable laws and regulations.\nretention:\n- scope: Register personal data\n  period: as long as it appears in official company and ultimate beneficial ownership registers\n  text: We retain your data for as long as it appears in official company and ultimate beneficial ownership registers\n- scope: Probatory retention\n  period: 5 years\n  text: and for an additional duration of 5 years as a probatory measure.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: our service provider or client is self-certified under the Data Privacy Framework\n\
  - mechanism: SCC\n  text: the standard contractual clauses adopted by the European Commission on June 4th 2021\n- mechanism: BCR\n  text: our service provider or client has implemented binding corporate rules\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@topograph.co with a request to exercise the right to erasure\n  text: 'You may ask us to delete all or part of the data we have that relates to you, where one at least of the\n    conditions below is met:'\nrights:\n- right: Access\n  text: You have the right to request a copy of all personal data we have that relates to you\n- right: Rectification\n  text: You have the right to ask us to rectify, complete or update personal data we have that relates to you\n- right: Object\n  text: You have a right to object to the processing activities above on grounds relating to your particular situation.\n- right: Erasure\n  text: Right to erasure (right to be forgotten)\n\
  - right: Limitation of processing\n  text: Right to limitation of processing\n- right: Post-mortem directives\n  text: Right to provide directives regarding your data after your death\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/topograph/privacy/topograph-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from Topograph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- KYB
- Company Data
- Business Registers
- Compliance
- Identity Verification
- Beneficial Ownership
- AML
- Due Diligence
- Fintech
---
