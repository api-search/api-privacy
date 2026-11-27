---
api_specs:
- filename: factory-automations-api-openapi.yml
  format: yaml
  label: Factory Automations API
  slug: factory-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-automations-api-openapi.yml
- filename: factory-computers-api-openapi.yml
  format: yaml
  label: Factory Computers API
  slug: factory-computers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-computers-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, business email address, company name, role, login credentials, and communication preferences.
  - category: communication
    text: Messages, feedback, inquiries, and bug reports submitted to our customer support or security teams.
  - category: device
    text: IP address, device type, browser specifications, operating system, diagnostic logs, performance metrics, and feature-interaction data collected automatically.
  - category: behavioral
    text: Analyzing usage patterns, monitoring application performance, debugging issues, and improving core agent functionality and developer experience.
  - category: other
    text: Inputs, prompts, code repositories, branch references, file contents, terminal or command inputs, session history, and outputs generated during your use of the Services.
  - category: other
    text: OAuth tokens, authentication credentials, and user-provided API keys (e.g., Bring Your Own Key / BYOK configurations).
  deletion:
    route: Email privacy@factory.com; enterprise deletion requests go to the organization's administrator.
    text: To exercise these rights, email us at privacy@factory.com .
  dpa:
    available: true
    text: Your organization is the Data Controller (or "Business"), and Factory acts strictly as a Data Processor (or "Service Provider") governed by your organization's Master Services Agreement (MSA) and Data Processing Addendum (DPA) or other agreements with Factory.
    url: null
  purposes:
  - purpose: Providing the Services
    text: Authenticating users, routing model requests, executing requested tasks, maintaining platform operations, and facilitating payments.
  - purpose: Service improvement and analytics
    text: Analyzing usage patterns, monitoring application performance, debugging issues, and improving core agent functionality and developer experience.
  - purpose: Customer support and communications
    text: Responding to technical questions, sending system alerts, notifying you of updates, and resolving customer issues.
  - purpose: Safety and security
    text: Preventing fraud, detecting malicious or unauthorized activity, enforcing our terms, and securing our infrastructure.
  - purpose: Legal compliance
    text: Meeting regulatory obligations, responding to lawful government or legal requests, and enforcing our agreements.
  - purpose: Marketing
    text: Sending newsletters or promotional updates regarding new features. You may opt out at any time.
  residency:
  - region: United States
    text: We operate and process data primarily in the United States.
  retention:
  - period: null
    scope: Enterprise workspace data
    text: For enterprise organizations, session retention and storage policies are configurable by workspace administrators.
  - period: active life of your account
    scope: Standard account information
    text: For standard accounts, account information is retained for the active life of your account.
  rights:
  - right: Access and portability
    text: 'Access & Portability: Request a copy of the personal information we maintain about you in a structured format.'
  - right: Correction
    text: 'Correction: Request corrections to inaccurate or incomplete information.'
  - right: Deletion
    text: 'Deletion: Request that we delete your personal information, subject to legal and operational exceptions.'
  - right: Opt-out of marketing
    text: 'Opt-Out of Marketing: Opt out of promotional communications at any time using the "unsubscribe" link in our emails or by contacting us.'
  - right: Object or restrict processing
    text: 'Object or Restrict Processing: Object to or request limitations on certain types of data processing based on legitimate interests.'
  role:
    text: Your organization is the Data Controller (or "Business"), and Factory acts strictly as a Data Processor (or "Service Provider")
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data, and we do not share your personal data for cross-context behavioral or targeted advertising.
  subprocessors:
    text: For a complete, up-to-date list of our specific third-party subprocessors, the data they process, and their geographic locations, please visit our Trust Center at trust.factory.com .
    url: https://trust.factory.com
  transfers:
  - mechanism: SCC
    text: We rely on legally recognized transfer mechanisms, including the European Commission’s Standard Contractual Clauses (SCCs), to protect cross-border data transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Factory
provenance_date: '2026-11-09'
provider_name: Factory
provider_slug: factory
slug: factory-privacy-policy
source_date: '2026-11-09'
source_filename: factory-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://factory.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Factory\naid: factory\nurl: https://factory.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Your organization is the Data Controller (or \"Business\"), and Factory acts strictly as a Data Processor\n    (or \"Service Provider\")\ndata_categories:\n- category: contact\n  text: Name, business email address, company name, role, login credentials, and communication preferences.\n- category: communication\n  text: Messages, feedback, inquiries, and bug reports submitted to our customer support or security teams.\n- category: device\n  text: IP address, device type, browser specifications,\
  \ operating system, diagnostic logs, performance metrics,\n    and feature-interaction data collected automatically.\n- category: behavioral\n  text: Analyzing usage patterns, monitoring application performance, debugging issues, and improving core agent\n    functionality and developer experience.\n- category: other\n  text: Inputs, prompts, code repositories, branch references, file contents, terminal or command inputs, session\n    history, and outputs generated during your use of the Services.\n- category: other\n  text: OAuth tokens, authentication credentials, and user-provided API keys (e.g., Bring Your Own Key / BYOK configurations).\npurposes:\n- purpose: Providing the Services\n  text: Authenticating users, routing model requests, executing requested tasks, maintaining platform operations,\n    and facilitating payments.\n- purpose: Service improvement and analytics\n  text: Analyzing usage patterns, monitoring application performance, debugging issues, and improving core agent\n\
  \    functionality and developer experience.\n- purpose: Customer support and communications\n  text: Responding to technical questions, sending system alerts, notifying you of updates, and resolving customer\n    issues.\n- purpose: Safety and security\n  text: Preventing fraud, detecting malicious or unauthorized activity, enforcing our terms, and securing our infrastructure.\n- purpose: Legal compliance\n  text: Meeting regulatory obligations, responding to lawful government or legal requests, and enforcing our agreements.\n- purpose: Marketing\n  text: Sending newsletters or promotional updates regarding new features. You may opt out at any time.\nretention:\n- scope: Enterprise workspace data\n  period: null\n  text: For enterprise organizations, session retention and storage policies are configurable by workspace administrators.\n- scope: Standard account information\n  period: active life of your account\n  text: For standard accounts, account information is retained for the active\
  \ life of your account.\nresidency:\n- region: United States\n  text: We operate and process data primarily in the United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on legally recognized transfer mechanisms, including the European Commission’s Standard Contractual\n    Clauses (SCCs), to protect cross-border data transfers.\nsubprocessors:\n  url: https://trust.factory.com\n  text: For a complete, up-to-date list of our specific third-party subprocessors, the data they process, and their\n    geographic locations, please visit our Trust Center at trust.factory.com .\ndpa:\n  available: true\n  url: null\n  text: Your organization is the Data Controller (or \"Business\"), and Factory acts strictly as a Data Processor\n    (or \"Service Provider\") governed by your organization's Master Services Agreement (MSA) and Data Processing\n    Addendum (DPA) or other agreements with Factory.\ndeletion:\n  route: Email privacy@factory.com; enterprise deletion requests go to the organization's\
  \ administrator.\n  text: To exercise these rights, email us at privacy@factory.com .\nrights:\n- right: Access and portability\n  text: 'Access & Portability: Request a copy of the personal information we maintain about you in a structured\n    format.'\n- right: Correction\n  text: 'Correction: Request corrections to inaccurate or incomplete information.'\n- right: Deletion\n  text: 'Deletion: Request that we delete your personal information, subject to legal and operational exceptions.'\n- right: Opt-out of marketing\n  text: 'Opt-Out of Marketing: Opt out of promotional communications at any time using the \"unsubscribe\" link in\n    our emails or by contacting us.'\n- right: Object or restrict processing\n  text: 'Object or Restrict Processing: Object to or request limitations on certain types of data processing based\n    on legitimate interests.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data, and we do not share your personal data for cross-context\
  \ behavioral or\n    targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/factory/privacy/factory-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Factory's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Software-as-a-Service
- Cloud
- Automation
- Supply Chain
- Company
---
