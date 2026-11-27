---
api_specs:
- filename: gameye-artifacts-api-openapi.yml
  format: yaml
  label: Gameye Artifacts API
  slug: gameye-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-artifacts-api-openapi.yml
- filename: gameye-available-location-api-openapi.yml
  format: yaml
  label: Gameye Available Location API
  slug: gameye-available-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-available-location-api-openapi.yml
- filename: gameye-logs-api-openapi.yml
  format: yaml
  label: Gameye Logs API
  slug: gameye-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-logs-api-openapi.yml
- filename: gameye-session-api-openapi.yml
  format: yaml
  label: Gameye Session API
  slug: gameye-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-session-api-openapi.yml
- filename: gameye-tag-api-openapi.yml
  format: yaml
  label: Gameye Tag API
  slug: gameye-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-tag-api-openapi.yml
- filename: gameye-application-api-openapi.yml
  format: yaml
  label: Gameye Application API
  slug: gameye-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-application-api-openapi.yml
- filename: gameye-region-api-openapi.yml
  format: yaml
  label: Gameye Region API
  slug: gameye-region-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-region-api-openapi.yml
- filename: gameye-token-api-openapi.yml
  format: yaml
  label: Gameye Token API
  slug: gameye-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameye/openapi/gameye-token-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, business email address, company name
  - category: identifying
    text: IP address, browser type, device type, pages visited, session duration
  - category: financial
    text: Contact name, company name, bank account details (provider's own), invoicing email
  - category: communication
    text: Contact person names, email addresses, Slack/Discord handles, phone numbers (SLA contacts)
  deletion:
    route: Email privacy@gameye.com
    text: Previous versions of this policy are available upon request by contacting privacy@gameye.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Website analytics and performance
    text: Website analytics and performance
  - purpose: Account registration and management
    text: Account registration and management
  - purpose: Service delivery and support
    text: Service delivery and support
  - purpose: Security and abuse prevention
    text: Security and abuse prevention
  retention:
  - period: 13 months
    scope: Website analytics
    text: 13 months, then aggregated
  - period: 30 days
    scope: Developer Trial account data
    text: Developer Trial account data (including API keys, session logs, and configuration) is deleted 30 days after the expiry or termination of the trial period
  - period: 7 years
    scope: Commercial invoicing
    text: 7 years (Dutch tax law)
  - period: 12 months rolling
    scope: Commercial service usage
    text: 12 months rolling
  rights:
  - right: Access
    text: 'Right of access (Art. 15): you may request a copy of the personal data we hold about you.'
  - right: Rectification
    text: 'Right to rectification (Art. 16): you may request correction of inaccurate or incomplete personal data.'
  - right: Erasure
    text: 'Right to erasure (Art. 17): you may request deletion of your personal data where there is no overriding legitimate reason for us to continue processing it.'
  - right: Restriction
    text: 'Right to restriction (Art. 18): you may request that we limit processing of your personal data in certain circumstances.'
  - right: Portability
    text: 'Right to data portability (Art. 20): where processing is based on consent or contract and carried out by automated means, you may request your data in a structured, machine-readable format.'
  - right: Object
    text: 'Right to object (Art. 21): you may object to processing based on legitimate interest.'
  - right: Withdraw consent
    text: 'Right to withdraw consent (Art. 7(3)): where processing is based on your consent, you may withdraw that consent at any time without affecting the lawfulness of prior processing.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Gameye does not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (2021/914/EU) supplemented where necessary by additional technical and organisational measures.
  - mechanism: DPF
    text: EU–US Data Privacy Framework (adequacy decision) and Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Gameye
provenance_date: '2026-11-09'
provider_name: Gameye
provider_slug: gameye
slug: gameye-privacy-policy
source_date: '2026-11-09'
source_filename: gameye-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gameye.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Gameye\naid: gameye\nurl: https://gameye.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, business email address, company name\n- category: identifying\n  text: IP address, browser type, device type, pages visited, session duration\n- category: financial\n  text: Contact name, company name, bank account details (provider's own), invoicing email\n- category: communication\n  text: Contact person names, email addresses, Slack/Discord handles, phone numbers (SLA contacts)\npurposes:\n- purpose: Website analytics and performance\n\
  \  text: Website analytics and performance\n- purpose: Account registration and management\n  text: Account registration and management\n- purpose: Service delivery and support\n  text: Service delivery and support\n- purpose: Security and abuse prevention\n  text: Security and abuse prevention\nretention:\n- scope: Website analytics\n  period: 13 months\n  text: 13 months, then aggregated\n- scope: Developer Trial account data\n  period: 30 days\n  text: Developer Trial account data (including API keys, session logs, and configuration) is deleted 30 days after\n    the expiry or termination of the trial period\n- scope: Commercial invoicing\n  period: 7 years\n  text: 7 years (Dutch tax law)\n- scope: Commercial service usage\n  period: 12 months rolling\n  text: 12 months rolling\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (2021/914/EU) supplemented where necessary by additional technical and organisational\n    measures.\n- mechanism: DPF\n  text:\
  \ EU–US Data Privacy Framework (adequacy decision) and Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@gameye.com\n  text: Previous versions of this policy are available upon request by contacting privacy@gameye.com.\nrights:\n- right: Access\n  text: 'Right of access (Art. 15): you may request a copy of the personal data we hold about you.'\n- right: Rectification\n  text: 'Right to rectification (Art. 16): you may request correction of inaccurate or incomplete personal data.'\n- right: Erasure\n  text: 'Right to erasure (Art. 17): you may request deletion of your personal data where there is no overriding\n    legitimate reason for us to continue processing it.'\n- right: Restriction\n  text: 'Right to restriction (Art. 18): you may request that we limit processing of your personal data in certain\n    circumstances.'\n- right: Portability\n  text: 'Right to data portability\
  \ (Art. 20): where processing is based on consent or contract and carried out by\n    automated means, you may request your data in a structured, machine-readable format.'\n- right: Object\n  text: 'Right to object (Art. 21): you may object to processing based on legitimate interest.'\n- right: Withdraw consent\n  text: 'Right to withdraw consent (Art. 7(3)): where processing is based on your consent, you may withdraw that\n    consent at any time without affecting the lawfulness of prior processing.'\nsale_or_sharing:\n  stance: prohibited\n  text: Gameye does not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/gameye/privacy/gameye-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Gameye's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Game Server Hosting
- Game Server Orchestration
- Multiplayer
- Containers
- Infrastructure
- Gaming
- Edge Computing
- DevOps
---
