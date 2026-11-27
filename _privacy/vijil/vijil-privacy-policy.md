---
api_specs:
- filename: vijil-agent-environment-api-openapi.yml
  format: yaml
  label: Vijil Agent Environment API
  slug: vijil-agent-environment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-agent-environment-api-openapi.yml
- filename: vijil-diamond-api-openapi.yml
  format: yaml
  label: Vijil Diamond API
  slug: vijil-diamond-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-diamond-api-openapi.yml
- filename: vijil-dome-api-openapi.yml
  format: yaml
  label: Vijil Dome API
  slug: vijil-dome-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-dome-api-openapi.yml
- filename: vijil-red-team-api-openapi.yml
  format: yaml
  label: Vijil Red Team API
  slug: vijil-red-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-red-team-api-openapi.yml
- filename: vijil-teams-api-openapi.yml
  format: yaml
  label: Vijil Teams API
  slug: vijil-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-teams-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address, password, username, full name
  - category: contact
    text: email address
  - category: financial
    text: credit card information
  - category: location
    text: your session (date, location), your IP address
  - category: device
    text: 'information about your device: type, model, version, operating system, browser'
  - category: behavioral
    text: information about your Use of the Services, your session (date, location), your IP address, information from cookies
  - category: communication
    text: communications between you and the Company, as part of using the Services
  deletion:
    route: written request to privacy@vijil.ai
    text: If you wish to request the erasure of all of your Personal Information that we process, you may do so by sending a written request to privacy@vijil.ai.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver the Services
    text: to deliver the Services, which may include the creation of Your account, the display of Your profile or Your content
  - purpose: improve the Services
    text: performing research and analysis aimed at improving the Services, or other products and technologies of the Company
  - purpose: security
    text: to ensure and maintain security on our Services or Website, which may include detecting, preventing, investigating or otherwise addressing fraud or security issues
  - purpose: legal compliance
    text: to comply with any applicable law, regulation, legal process or governmental requests
  - purpose: advertising measurement
    text: Recording which advertisement brought a visitor here, so that we can stop paying for the ones that do not.
  residency:
  - region: United States
    text: The Company and its servers are located in the United States.
  retention:
  - period: null
    scope: personal information
    text: We retain your Information for as long as necessary to deliver the Services, to comply with any applicable legal requirements, to maintain security and prevent incidents and, in general, to pursue our legitimate interests.
  rights:
  - right: access
    text: You may be entitled under data protection laws to access and review Personal Information the Company holds related to you.
  - right: modify or delete
    text: You may access, modify or delete the Information we collected by editing your profile or controlling the content that you share at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: The Company may disclose Anonymous Information (with or without compensation) to third parties, including advertisers and partners, for purposes including, but not limited to, targeting advertisements.
  subprocessors:
    text: Subprocessor | Description of Subprocessing | Location of Subprocessing. AWS SES | Emails | United States
    url: null
  transfers:
  - mechanism: other
    text: We strive to take appropriate safeguards to ensure that your Personal Information will remain protected in a manner consistent with standard applicable data protection laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vijil
provenance_date: '2026-11-10'
provider_name: Vijil
provider_slug: vijil
slug: vijil-privacy-policy
source_date: '2026-11-10'
source_filename: vijil-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.vijil.ai/policies/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vijil\naid: vijil\nurl: https://www.vijil.ai/policies/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: email address, password, username, full name\n- category: contact\n  text: email address\n- category: financial\n  text: credit card information\n- category: location\n  text: your session (date, location), your IP address\n- category: device\n  text: 'information about your device: type, model, version, operating system, browser'\n- category: behavioral\n  text: information about your Use of the Services, your session (date,\
  \ location), your IP address, information\n    from cookies\n- category: communication\n  text: communications between you and the Company, as part of using the Services\npurposes:\n- purpose: deliver the Services\n  text: to deliver the Services, which may include the creation of Your account, the display of Your profile or\n    Your content\n- purpose: improve the Services\n  text: performing research and analysis aimed at improving the Services, or other products and technologies of\n    the Company\n- purpose: security\n  text: to ensure and maintain security on our Services or Website, which may include detecting, preventing, investigating\n    or otherwise addressing fraud or security issues\n- purpose: legal compliance\n  text: to comply with any applicable law, regulation, legal process or governmental requests\n- purpose: advertising measurement\n  text: Recording which advertisement brought a visitor here, so that we can stop paying for the ones that do not.\nretention:\n- scope:\
  \ personal information\n  period: null\n  text: We retain your Information for as long as necessary to deliver the Services, to comply with any applicable\n    legal requirements, to maintain security and prevent incidents and, in general, to pursue our legitimate interests.\nresidency:\n- region: United States\n  text: The Company and its servers are located in the United States.\ntransfers:\n- mechanism: other\n  text: We strive to take appropriate safeguards to ensure that your Personal Information will remain protected\n    in a manner consistent with standard applicable data protection laws.\nsubprocessors:\n  url: null\n  text: Subprocessor | Description of Subprocessing | Location of Subprocessing. AWS SES | Emails | United States\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: written request to privacy@vijil.ai\n  text: If you wish to request the erasure of all of your Personal Information that we process, you may do so by\n    sending a written request\
  \ to privacy@vijil.ai.\nrights:\n- right: access\n  text: You may be entitled under data protection laws to access and review Personal Information the Company holds\n    related to you.\n- right: modify or delete\n  text: You may access, modify or delete the Information we collected by editing your profile or controlling the\n    content that you share at any time.\nsale_or_sharing:\n  stance: conditional\n  text: The Company may disclose Anonymous Information (with or without compensation) to third parties, including\n    advertisers and partners, for purposes including, but not limited to, targeting advertisements.\n"
source_yaml_url: https://artifacts.apis.io/vijil/privacy/vijil-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Vijil's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Security
- AI Safety
- Trust
- Red Teaming
- Guardrails
- LLM Security
- Evaluation
- Observability
- MCP
---
