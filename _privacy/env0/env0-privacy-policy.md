---
api_specs:
- filename: env0-agents-api-openapi.yml
  format: yaml
  label: Env0 Agents API
  slug: env0-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-agents-api-openapi.yml
- filename: env0-configuration-api-openapi.yml
  format: yaml
  label: Env0 Configuration API
  slug: env0-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-configuration-api-openapi.yml
- filename: env0-deployments-api-openapi.yml
  format: yaml
  label: Env0 Deployments API
  slug: env0-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-deployments-api-openapi.yml
- filename: env0-environments-api-openapi.yml
  format: yaml
  label: Env0 Environments API
  slug: env0-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-environments-api-openapi.yml
- filename: env0-modules-api-openapi.yml
  format: yaml
  label: Env0 Modules API
  slug: env0-modules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-modules-api-openapi.yml
- filename: env0-organizations-api-openapi.yml
  format: yaml
  label: Env0 Organizations API
  slug: env0-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-organizations-api-openapi.yml
- filename: env0-projects-api-openapi.yml
  format: yaml
  label: Env0 Projects API
  slug: env0-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-projects-api-openapi.yml
- filename: env0-templates-api-openapi.yml
  format: yaml
  label: Env0 Templates API
  slug: env0-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-templates-api-openapi.yml
- filename: env0-users-api-openapi.yml
  format: yaml
  label: Env0 Users API
  slug: env0-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-users-api-openapi.yml
- filename: env0-webhooks-api-openapi.yml
  format: yaml
  label: Env0 Webhooks API
  slug: env0-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-webhooks-api-openapi.yml
- filename: env0-approval-policies-api-openapi.yml
  format: yaml
  label: Env0 Approval Policies API
  slug: env0-approval-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/env0/openapi/env0-approval-policies-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, account username, email address, language preference, profile picture, company affiliation, logo URL, company description, links to your projects
  - category: contact
    text: Name, account username, email address, company affiliation, position, phone number, country, and content of inquiry or feedback
  - category: financial
    text: Basic billing and payment information from the payment processors including your name and your billing address.
  - category: location
    text: IP address and location data based on it, pages visited, Website and App functions used, fields completed in forms, screen captures or recordings
  - category: behavioral
    text: pages visited, Website and App functions used, fields completed in forms
  - category: device
    text: This information may include device and browser information, IP address, and browsing activity
  - category: communication
    text: email communications
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide App functionality
    text: Provide App users with the functionality of the App
  - purpose: Collect user payments
    text: Collect user payments
  - purpose: Customer support and relationship
    text: Provide technical support to App users
  - purpose: Marketing
    text: Promoting and marketing EnvZero’s products and services
  - purpose: Analytics and personalized ads
    text: Inform and serve personalized ads more relevant to user interests
  retention:
  - period: null
    scope: General personal information
    text: We retain your information for the duration we need it to operate the App, the Websites, and our business, and interact with Website and App users, and thereafter as needed for record-keeping matters.
  rights:
  - right: Access
    text: Right to Access and receive a copy of your personal information that we process.
  - right: Rectify
    text: Right to Rectify inaccurate personal information we have concerning you
  - right: Withdraw consent
    text: Right to easily and at any time withdraw your consent
  - right: Data portability
    text: Right to Data Portability
  - right: Object
    text: Right to Object to our processing of your candidate personal information based on our legitimate interest.
  - right: Restrict processing
    text: Right to Restrict us from processing your candidate personal information
  - right: Erasure
    text: Right to be Forgotten .
  - right: Complain to authority
    text: you have the right to lodge a complaint with your local data protection authority.
  role:
    text: EnvZero Inc. is the controller of the personal data described in this Notice.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: These companies are authorized to use your personal information in this context only as necessary to provide these services to us and not for their own promotional purposes.
    url: null
  transfers:
  - mechanism: other
    text: we will transfer your information to countries such as the United States and Israel.
  - mechanism: SCC
    text: We do so under the terms of a data transfer agreement which contain standard data protection contract clauses with adequate safeguards determined by the EU Commission and UK Information Commissioner’s Office.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Env0
provenance_date: '2026-11-09'
provider_name: Env0
provider_slug: env0
slug: env0-privacy-policy
source_date: '2026-11-09'
source_filename: env0-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.envzero.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Env0\naid: env0\nurl: https://www.envzero.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: EnvZero Inc. is the controller of the personal data described in this Notice.\ndata_categories:\n- category: identifying\n  text: Name, account username, email address, language preference, profile picture, company affiliation, logo URL,\n    company description, links to your projects\n- category: contact\n  text: Name, account username, email address, company affiliation, position, phone number, country, and content\n    of inquiry or feedback\n- category: financial\n  text: Basic\
  \ billing and payment information from the payment processors including your name and your billing address.\n- category: location\n  text: IP address and location data based on it, pages visited, Website and App functions used, fields completed\n    in forms, screen captures or recordings\n- category: behavioral\n  text: pages visited, Website and App functions used, fields completed in forms\n- category: device\n  text: This information may include device and browser information, IP address, and browsing activity\n- category: communication\n  text: email communications\npurposes:\n- purpose: Provide App functionality\n  text: Provide App users with the functionality of the App\n- purpose: Collect user payments\n  text: Collect user payments\n- purpose: Customer support and relationship\n  text: Provide technical support to App users\n- purpose: Marketing\n  text: Promoting and marketing EnvZero’s products and services\n- purpose: Analytics and personalized ads\n  text: Inform and serve\
  \ personalized ads more relevant to user interests\nretention:\n- scope: General personal information\n  period: null\n  text: We retain your information for the duration we need it to operate the App, the Websites, and our business,\n    and interact with Website and App users, and thereafter as needed for record-keeping matters.\nresidency: []\ntransfers:\n- mechanism: other\n  text: we will transfer your information to countries such as the United States and Israel.\n- mechanism: SCC\n  text: We do so under the terms of a data transfer agreement which contain standard data protection contract clauses\n    with adequate safeguards determined by the EU Commission and UK Information Commissioner’s Office.\nsubprocessors:\n  url: null\n  text: These companies are authorized to use your personal information in this context only as necessary to provide\n    these services to us and not for their own promotional purposes.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ null\n  text: null\nrights:\n- right: Access\n  text: Right to Access and receive a copy of your personal information that we process.\n- right: Rectify\n  text: Right to Rectify inaccurate personal information we have concerning you\n- right: Withdraw consent\n  text: Right to easily and at any time withdraw your consent\n- right: Data portability\n  text: Right to Data Portability\n- right: Object\n  text: Right to Object to our processing of your candidate personal information based on our legitimate interest.\n- right: Restrict processing\n  text: Right to Restrict us from processing your candidate personal information\n- right: Erasure\n  text: Right to be Forgotten .\n- right: Complain to authority\n  text: you have the right to lodge a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/env0/privacy/env0-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Env0's own page on 2026-11-09.
synthetic: false
tags:
- FinOps
- Infrastructure as Code
- DevOps
- Cloud
- Terraform
- OpenTofu
- Platform Engineering
- Cloud Governance
- Drift Detection
- A2A
---
