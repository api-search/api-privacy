---
api_specs:
- filename: agilehero-io-account-api-openapi.yml
  format: yaml
  label: AgileHero Account API
  slug: agilehero-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-account-api-openapi.yml
- filename: agilehero-io-cards-api-openapi.yml
  format: yaml
  label: AgileHero Cards API
  slug: agilehero-io-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-cards-api-openapi.yml
- filename: agilehero-io-discovery-api-openapi.yml
  format: yaml
  label: AgileHero Discovery API
  slug: agilehero-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-discovery-api-openapi.yml
- filename: agilehero-io-projects-api-openapi.yml
  format: yaml
  label: AgileHero Projects API
  slug: agilehero-io-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-projects-api-openapi.yml
- filename: agilehero-io-webhooks-api-openapi.yml
  format: yaml
  label: AgileHero Webhooks API
  slug: agilehero-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-webhooks-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and last name, e-mail address, phone number, if it is provided or required for a given functionality, Account identifier, IP address
  - category: device
    text: IP address, technical identifiers, device data, browser data, connection-related technical data, system logs
  - category: financial
    text: payment status, details necessary to issue an invoice if such is requested by the User
  - category: behavioral
    text: the User’s activity
  - category: communication
    text: content of the report
  deletion:
    route: Account or Workspace deletion; data deleted from active systems after the 30-day period
    text: Upon the lapse of that period, the data is deleted from the Service Provider’s active systems unless the provisions of the Privacy Policy state otherwise.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing access to the Application
    text: providing access to AgileHero
  - purpose: account creation and maintenance
    text: enabling the User to create an Account, maintaining the User Account, and using the Services
  - purpose: payment processing
    text: processing payments through the Payment Operator
  - purpose: AI-assisted functionalities
    text: providing AI-assisted functionalities of the Application
  - purpose: security and diagnostics
    text: detecting errors, debugging, ensuring security, preventing abuses, and improving the performance of the Application
  - purpose: website statistics
    text: statistics and audience measurement of the AgileHero website
  residency:
  - region: European Union
    text: The data processed by this tool is hosted exclusively within the European Union and is not transferred to a third country.
  - region: European Union
    text: The AI models are run in that provider’s data centres located in the European Union
  retention:
  - period: 6 months
    scope: technical logs
    text: technical logs are retained for the period necessary to ensure the security, diagnostics, and stability of the Application, for no longer than 6 months
  - period: 90 days
    scope: backup copies
    text: Backup copies are retained for no longer than 90 days.
  - period: 30 days
    scope: data after account or workspace termination
    text: data will be stored by an additional, maximum period of 30 days to enable the User to revoke the deletion order
  - period: null
    scope: website statistics
    text: personal data is not retained — the data is anonymised and aggregated immediately upon collection
  - period: 30 days
    scope: AI provider retention
    text: the provider may retain them for no longer than 30 days, exclusively for automated abuse detection, in the data centre located in the European Union
  rights:
  - right: erasure
    text: request that the collected personal data referring to him/her is removed from the Service Provider’s systems, in particular, from AgileHero
  - right: restriction
    text: restrict the processing of his/her personal data
  - right: portability
    text: portability of the personal data collected by the Service Provider, including the right to receive them in a structured form
  - right: access and rectification
    text: request the Service Provider to provide access to his/her personal data and rectify them
  - right: objection
    text: raise an objection against personal data processing
  - right: withdraw consent
    text: revoke the consent to the personal data processing at any time
  - right: complaint
    text: file a complaint against the Service Provider to the supervisory authority
  role:
    text: The Controller of personal data is the Service Provider, i.e. AgileHero spółka z ograniczoną odpowiedzialnością
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: All the transfers will be based on standard contractual clauses (SCC) or Data Privacy Framework.
  - mechanism: DPF
    text: All the transfers will be based on standard contractual clauses (SCC) or Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgileHero
provenance_date: '2026-11-09'
provider_name: AgileHero
provider_slug: agilehero-io
slug: agilehero-io-privacy-policy
source_date: '2026-11-09'
source_filename: agilehero-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agilehero.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgileHero\naid: agilehero-io\nurl: https://agilehero.io/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Controller of personal data is the Service Provider, i.e. AgileHero spółka z ograniczoną odpowiedzialnością\ndata_categories:\n- category: identifying\n  text: first and last name, e-mail address, phone number, if it is provided or required for a given functionality,\n    Account identifier, IP address\n- category: device\n  text: IP address, technical identifiers, device data, browser data, connection-related technical data, system\n    logs\n- category: financial\n  text: payment\
  \ status, details necessary to issue an invoice if such is requested by the User\n- category: behavioral\n  text: the User’s activity\n- category: communication\n  text: content of the report\npurposes:\n- purpose: providing access to the Application\n  text: providing access to AgileHero\n- purpose: account creation and maintenance\n  text: enabling the User to create an Account, maintaining the User Account, and using the Services\n- purpose: payment processing\n  text: processing payments through the Payment Operator\n- purpose: AI-assisted functionalities\n  text: providing AI-assisted functionalities of the Application\n- purpose: security and diagnostics\n  text: detecting errors, debugging, ensuring security, preventing abuses, and improving the performance of the\n    Application\n- purpose: website statistics\n  text: statistics and audience measurement of the AgileHero website\nretention:\n- scope: technical logs\n  period: 6 months\n  text: technical logs are retained for the\
  \ period necessary to ensure the security, diagnostics, and stability\n    of the Application, for no longer than 6 months\n- scope: backup copies\n  period: 90 days\n  text: Backup copies are retained for no longer than 90 days.\n- scope: data after account or workspace termination\n  period: 30 days\n  text: data will be stored by an additional, maximum period of 30 days to enable the User to revoke the deletion\n    order\n- scope: website statistics\n  period: null\n  text: personal data is not retained — the data is anonymised and aggregated immediately upon collection\n- scope: AI provider retention\n  period: 30 days\n  text: the provider may retain them for no longer than 30 days, exclusively for automated abuse detection, in the\n    data centre located in the European Union\nresidency:\n- region: European Union\n  text: The data processed by this tool is hosted exclusively within the European Union and is not transferred to\n    a third country.\n- region: European Union\n  text:\
  \ The AI models are run in that provider’s data centres located in the European Union\ntransfers:\n- mechanism: SCC\n  text: All the transfers will be based on standard contractual clauses (SCC) or Data Privacy Framework.\n- mechanism: DPF\n  text: All the transfers will be based on standard contractual clauses (SCC) or Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account or Workspace deletion; data deleted from active systems after the 30-day period\n  text: Upon the lapse of that period, the data is deleted from the Service Provider’s active systems unless the\n    provisions of the Privacy Policy state otherwise.\nrights:\n- right: erasure\n  text: request that the collected personal data referring to him/her is removed from the Service Provider’s systems,\n    in particular, from AgileHero\n- right: restriction\n  text: restrict the processing of his/her personal data\n- right: portability\n\
  \  text: portability of the personal data collected by the Service Provider, including the right to receive them\n    in a structured form\n- right: access and rectification\n  text: request the Service Provider to provide access to his/her personal data and rectify them\n- right: objection\n  text: raise an objection against personal data processing\n- right: withdraw consent\n  text: revoke the consent to the personal data processing at any time\n- right: complaint\n  text: file a complaint against the Service Provider to the supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agilehero-io/privacy/agilehero-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 29 quoted statements, read from AgileHero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Project Management
- Agile
- AI Integration
- Collaboration
---
