---
api_specs:
- filename: improvado-accounts-api-openapi.yml
  format: yaml
  label: Improvado Accounts API
  slug: improvado-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-accounts-api-openapi.yml
- filename: improvado-authentication-api-openapi.yml
  format: yaml
  label: Improvado Authentication API
  slug: improvado-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-authentication-api-openapi.yml
- filename: improvado-automated-recipes-api-openapi.yml
  format: yaml
  label: Improvado Automated Recipes API
  slug: improvado-automated-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-automated-recipes-api-openapi.yml
- filename: improvado-data-source-connections-api-openapi.yml
  format: yaml
  label: Improvado Data source connections API
  slug: improvado-data-source-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-data-source-connections-api-openapi.yml
- filename: improvado-data-sources-api-openapi.yml
  format: yaml
  label: Improvado Data sources API
  slug: improvado-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-data-sources-api-openapi.yml
- filename: improvado-data-tables-api-openapi.yml
  format: yaml
  label: Improvado Data tables API
  slug: improvado-data-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-data-tables-api-openapi.yml
- filename: improvado-destination-connections-api-openapi.yml
  format: yaml
  label: Improvado Destination connections API
  slug: improvado-destination-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-destination-connections-api-openapi.yml
- filename: improvado-destinations-api-openapi.yml
  format: yaml
  label: Improvado Destinations API
  slug: improvado-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-destinations-api-openapi.yml
- filename: improvado-extraction-templates-api-openapi.yml
  format: yaml
  label: Improvado Extraction templates API
  slug: improvado-extraction-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-extraction-templates-api-openapi.yml
- filename: improvado-extracts-api-openapi.yml
  format: yaml
  label: Improvado Extracts API
  slug: improvado-extracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-extracts-api-openapi.yml
- filename: improvado-iframe-api-openapi.yml
  format: yaml
  label: Improvado Iframe API
  slug: improvado-iframe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-iframe-api-openapi.yml
- filename: improvado-loads-api-openapi.yml
  format: yaml
  label: Improvado Loads API
  slug: improvado-loads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-loads-api-openapi.yml
- filename: improvado-recipes-api-openapi.yml
  format: yaml
  label: Improvado Recipes API
  slug: improvado-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-recipes-api-openapi.yml
- filename: improvado-roles-api-openapi.yml
  format: yaml
  label: Improvado Roles API
  slug: improvado-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-roles-api-openapi.yml
- filename: improvado-webhooks-api-openapi.yml
  format: yaml
  label: Improvado Webhooks API
  slug: improvado-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-webhooks-api-openapi.yml
- filename: improvado-workspaces-api-openapi.yml
  format: yaml
  label: Improvado Workspaces API
  slug: improvado-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/improvado/openapi/improvado-workspaces-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, phone, company
  - category: contact
    text: Your name, email, phone number, company name, and any other information you choose to share.
  - category: device
    text: Your IP address, browser type, device type, and operating system.
  - category: behavioral
    text: 'Usage Data: Which features you use, which pages you visit, and how you interact with our platform.'
  - category: communication
    text: send you service updates, invoices, and marketing information
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: Data Processing Agreement
    url: null
  purposes:
  - purpose: Run and improve service
    text: We use your data to operate our platform, provide customer support, and develop new features.
  - purpose: Power AI features
    text: With your consent, we process the data described in Section 3.a to provide the AI features you choose to use.
  - purpose: Security and legal reasons
    text: To protect our users and our platform from fraud, and to comply with legal obligations.
  - purpose: Advertising sharing
    text: Some advertising and business-data partners receive information about your visits to our website through cookies and similar tools
  residency:
  - region: United States
    text: We are based in the U.S., and your data may be processed in countries other than your own.
  retention:
  - period: 30 minutes
    scope: Temporary connector-credential records
    text: Encrypted; auto-expire after 30 minutes, deleted earlier on successful use where supported.
  - period: 30 days
    scope: Revoked OAuth tokens
    text: revoked or expired tokens are removed from active systems within 30 days of disconnection
  - period: null
    scope: Chat tool inputs/outputs and workspace content
    text: backup copies age out with backup rotation (default backup retention 180 days per our Backup Policy)
  - period: 3 years
    scope: Support records
    text: Up to 3 years after the case closes, unless contract or law requires otherwise.
  - period: null
    scope: General personal data
    text: We process and store your personal data only for as long as required by the purpose for which it was collected.
  rights:
  - right: Access and correct
    text: 'Access and Correct Your Data: You can review and update your account information at any time.'
  - right: Withdraw consent
    text: 'Withdraw Your Consent: You can withdraw your consent for any data processing, including for AI features and marketing emails, at any time by contacting us or using the opt-out links provided.'
  - right: Delete
    text: 'Delete Your Data ("Right to be Forgotten"): You can request that we delete your personal data.'
  - right: Object or restrict
    text: 'Object to or Restrict Data Use: You can object to our use of your data for certain purposes.'
  - right: Portability
    text: 'Data Portability: You can request a copy of your data in a machine-readable format.'
  - right: Lodge a complaint
    text: 'Lodge a Complaint: You have the right to bring a claim before your local competent data protection authority.'
  - right: Opt out of sale or sharing
    text: Do not sell or share my personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal data for money. Some advertising and business-data partners receive information about your visits to our website through cookies and similar tools, which California law calls "sharing".
  subprocessors:
    text: An updated list of our specific service partners can be provided upon request.
    url: null
  transfers:
  - mechanism: SCC
    text: We use legally-approved mechanisms, like Standard Contractual Clauses, to ensure your data is protected wherever it goes.
  - mechanism: SCC
    text: the transfer is governed by the EU Standard Contractual Clauses (Commission Implementing Decision (EU) 2021/914, Module Two)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Improvado
provenance_date: '2026-11-09'
provider_name: Improvado
provider_slug: improvado
slug: improvado-privacy-policy
source_date: '2026-11-09'
source_filename: improvado-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://improvado.io/company-legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Improvado\naid: improvado\nurl: https://improvado.io/company-legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email, phone, company\n- category: contact\n  text: Your name, email, phone number, company name, and any other information you choose to share.\n- category: device\n  text: Your IP address, browser type, device type, and operating system.\n- category: behavioral\n  text: 'Usage Data: Which features you use, which pages you visit, and how you interact with our platform.'\n- category: communication\n  text:\
  \ send you service updates, invoices, and marketing information\npurposes:\n- purpose: Run and improve service\n  text: We use your data to operate our platform, provide customer support, and develop new features.\n- purpose: Power AI features\n  text: With your consent, we process the data described in Section 3.a to provide the AI features you choose to\n    use.\n- purpose: Security and legal reasons\n  text: To protect our users and our platform from fraud, and to comply with legal obligations.\n- purpose: Advertising sharing\n  text: Some advertising and business-data partners receive information about your visits to our website through\n    cookies and similar tools\nretention:\n- scope: Temporary connector-credential records\n  period: 30 minutes\n  text: Encrypted; auto-expire after 30 minutes, deleted earlier on successful use where supported.\n- scope: Revoked OAuth tokens\n  period: 30 days\n  text: revoked or expired tokens are removed from active systems within 30 days of\
  \ disconnection\n- scope: Chat tool inputs/outputs and workspace content\n  period: null\n  text: backup copies age out with backup rotation (default backup retention 180 days per our Backup Policy)\n- scope: Support records\n  period: 3 years\n  text: Up to 3 years after the case closes, unless contract or law requires otherwise.\n- scope: General personal data\n  period: null\n  text: We process and store your personal data only for as long as required by the purpose for which it was collected.\nresidency:\n- region: United States\n  text: We are based in the U.S., and your data may be processed in countries other than your own.\ntransfers:\n- mechanism: SCC\n  text: We use legally-approved mechanisms, like Standard Contractual Clauses, to ensure your data is protected\n    wherever it goes.\n- mechanism: SCC\n  text: the transfer is governed by the EU Standard Contractual Clauses (Commission Implementing Decision (EU) 2021/914,\n    Module Two)\nsubprocessors:\n  url: null\n  text:\
  \ An updated list of our specific service partners can be provided upon request.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access and correct\n  text: 'Access and Correct Your Data: You can review and update your account information at any time.'\n- right: Withdraw consent\n  text: 'Withdraw Your Consent: You can withdraw your consent for any data processing, including for AI features\n    and marketing emails, at any time by contacting us or using the opt-out links provided.'\n- right: Delete\n  text: 'Delete Your Data (\"Right to be Forgotten\"): You can request that we delete your personal data.'\n- right: Object or restrict\n  text: 'Object to or Restrict Data Use: You can object to our use of your data for certain purposes.'\n- right: Portability\n  text: 'Data Portability: You can request a copy of your data in a machine-readable format.'\n- right: Lodge a complaint\n  text: 'Lodge a Complaint:\
  \ You have the right to bring a claim before your local competent data protection authority.'\n- right: Opt out of sale or sharing\n  text: Do not sell or share my personal information\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal data for money. Some advertising and business-data partners receive information\n    about your visits to our website through cookies and similar tools, which California law calls \"sharing\".\n"
source_yaml_url: https://artifacts.apis.io/improvado/privacy/improvado-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Improvado's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Marketing Intelligence
- Marketing Analytics
- Data Pipeline
- ETL
- Advertising Data
- Business Intelligence
- Data Integration
- AI Agents
- MCP
- Agent Readiness
---
