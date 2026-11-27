---
api_specs:
- filename: zapier-accounts-api-openapi.yml
  format: yaml
  label: Zapier Accounts API
  slug: zapier-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-accounts-api-openapi.yml
- filename: zapier-actions-api-openapi.yml
  format: yaml
  label: Zapier Actions API
  slug: zapier-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-actions-api-openapi.yml
- filename: zapier-apps-api-openapi.yml
  format: yaml
  label: Zapier Apps API
  slug: zapier-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-apps-api-openapi.yml
- filename: zapier-authentications-api-openapi.yml
  format: yaml
  label: Zapier Authentications API
  slug: zapier-authentications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-authentications-api-openapi.yml
- filename: zapier-categories-api-openapi.yml
  format: yaml
  label: Zapier Categories API
  slug: zapier-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-categories-api-openapi.yml
- filename: zapier-experimental-api-openapi.yml
  format: yaml
  label: Zapier Experimental API
  slug: zapier-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-experimental-api-openapi.yml
- filename: zapier-inputs-api-openapi.yml
  format: yaml
  label: Zapier Inputs API
  slug: zapier-inputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-inputs-api-openapi.yml
- filename: zapier-outputs-api-openapi.yml
  format: yaml
  label: Zapier Outputs API
  slug: zapier-outputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-outputs-api-openapi.yml
- filename: zapier-zap-templates-api-openapi.yml
  format: yaml
  label: Zapier Zap Templates API
  slug: zapier-zap-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-zap-templates-api-openapi.yml
- filename: zapier-zaps-api-openapi.yml
  format: yaml
  label: Zapier Zaps API
  slug: zapier-zaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zapier/openapi/zapier-zaps-api-openapi.yml
claim_count: 11
description: ''
doc:
  deletion:
    route: Data Retention/Deletion/Export page
    text: Please review our Data Retention/Deletion/Export page for information about Zapier's data retention/deletion practices.
  dpa:
    available: true
    text: You can find Zapier's DPA on our Data Processing Addendum page.
    url: https://zapier.com/legal/data-processing-addendum
  residency:
  - region: United States
    text: Zapier hosts data in AWS servers located in the United States, including customers’ personal data and the data that is processed on behalf of customers.
  - region: EU only storage
    text: Zapier does not support this option.
  retention:
  - period: up to 69 days
    scope: Zap Content and Zap History in customer account
    text: Before Zapier deletes your data on the first Monday of the month, Zapier retains up to 69 days of Zap Content and Zap History in your Zapier account.
  - period: 7 to 30 days
    scope: Company or Enterprise plans
    text: Customers on Company or Enterprise plans can set a custom data retention period of between 7 to 30 days for data held in their Zapier account.
  role:
    text: you, the customer, are considered the “data controller” of that data from a privacy perspective. In turn, Zapier is the “data processor” responsible for safeguarding Customer Content as it flows through Zapier’s systems.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: No, Zapier does not sell or market your data to third parties.
  subprocessors:
    text: Yes, Zapier engages with third-party subprocessors and Zapier affiliates to help provide services to our customers. Please review our Subprocessors page for more information.
    url: https://zapier.com/legal/data-privacy
  transfers:
  - mechanism: DPF
    text: Zapier has certified our compliance with the EU-US Data Privacy Framework (DPF), the UK Extension, and the Swiss-US DPF
  - mechanism: SCC
    text: Zapier’s DPA contains Standard Contractual Clauses (SCCs) for EU data and includes terms specific to how Zapier’s platform works.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zapier
provenance_date: '2026-11-10'
provider_name: Zapier
provider_slug: zapier
slug: zapier-privacy-policy
source_date: '2026-11-10'
source_filename: zapier-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zapier.com/legal/data-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zapier\naid: zapier\nurl: https://zapier.com/legal/data-privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: you, the customer, are considered the “data controller” of that data from a privacy perspective. In turn,\n    Zapier is the “data processor” responsible for safeguarding Customer Content as it flows through Zapier’s systems.\ndata_categories: []\npurposes: []\nretention:\n- scope: Zap Content and Zap History in customer account\n  period: up to 69 days\n  text: Before Zapier deletes your data on the first Monday of the month, Zapier retains up to 69 days of Zap Content\n    and Zap History\
  \ in your Zapier account.\n- scope: Company or Enterprise plans\n  period: 7 to 30 days\n  text: Customers on Company or Enterprise plans can set a custom data retention period of between 7 to 30 days\n    for data held in their Zapier account.\nresidency:\n- region: United States\n  text: Zapier hosts data in AWS servers located in the United States, including customers’ personal data and the\n    data that is processed on behalf of customers.\n- region: EU only storage\n  text: Zapier does not support this option.\ntransfers:\n- mechanism: DPF\n  text: Zapier has certified our compliance with the EU-US Data Privacy Framework (DPF), the UK Extension, and the\n    Swiss-US DPF\n- mechanism: SCC\n  text: Zapier’s DPA contains Standard Contractual Clauses (SCCs) for EU data and includes terms specific to how\n    Zapier’s platform works.\nsubprocessors:\n  url: https://zapier.com/legal/data-privacy\n  text: Yes, Zapier engages with third-party subprocessors and Zapier affiliates to help\
  \ provide services to our\n    customers. Please review our Subprocessors page for more information.\ndpa:\n  available: true\n  url: https://zapier.com/legal/data-processing-addendum\n  text: You can find Zapier's DPA on our Data Processing Addendum page.\ndeletion:\n  route: Data Retention/Deletion/Export page\n  text: Please review our Data Retention/Deletion/Export page for information about Zapier's data retention/deletion\n    practices.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No, Zapier does not sell or market your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/zapier/privacy/zapier-privacy-policy.yml
stated_fields:
- role
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from Zapier's own page on 2026-11-10.
synthetic: false
tags:
- Zapier
- Integration
- iPaaS
- Workflow Automation
- Automation
- No-Code
- App Integration
- AI workflow
- Enterprise Security
- Workflow Orchestration
---
