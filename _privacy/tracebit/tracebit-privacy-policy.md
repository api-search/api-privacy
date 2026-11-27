---
api_specs:
- filename: tracebit-alerts-api-openapi.yml
  format: yaml
  label: Tracebit Alerts API
  slug: tracebit-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracebit/openapi/tracebit-alerts-api-openapi.yml
- filename: tracebit-canary-credentials-api-openapi.yml
  format: yaml
  label: Tracebit Canary Credentials API
  slug: tracebit-canary-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracebit/openapi/tracebit-canary-credentials-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: name job title employer name work address work email work phone number
  - category: device
    text: information about the device you are using and its characteristics
  - category: behavioral
    text: the number of page visits and statistically relevant behavior of our visitors on the website
  deletion:
    route: verified request from Data Subjects or their authorized agents, or email privacy@tracebit.com
    text: All personal data that Tracebit controls may be deleted upon verified request from Data Subjects or their authorized agents.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services to prospects and customers
    text: We use this information to provide prospects and customers with services.
  - purpose: website analysis and improvement
    text: We use these tools to collect statistics to improve the experience of our website visitors and to improve our service to our customers.
  residency:
  - region: United States
    text: The personal information Tracebit collects from you is stored in one or more databases hosted by third parties located in the United States.
  retention:
  - period: null
    scope: service data
    text: The Tracebit retains service data for the duration of the customer’s business relationship with the Tracebit and for a period of time thereafter
  - period: null
    scope: prospect data
    text: Tracebit retains prospect data until such time as it no longer has business value and is purged from Tracebit systems.
  rights:
  - right: access
    text: Right of access
  - right: rectification
    text: Right to rectification
  - right: erasure
    text: Right to erasure
  - right: restrict processing
    text: Right to restrict processing
  - right: portability
    text: Right of data portability
  - right: object
    text: Right to object
  - right: automated decision making
    text: Rights related to automated decision making including profiling
  role:
    text: Tracebit Limited (‘Tracebit’) is a security product company.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell this personal information to anyone and only share it with third parties who are facilitating the delivery of our services.
  subprocessors:
    text: 'A list of our third party sub processors can be found here: trust.tracebit.com'
    url: trust.tracebit.com
  transfers:
  - mechanism: DPF
    text: These safeguards may include reliance on the UK Extension to the EU-US Data Privacy Framework (also known as the UK-US Data Bridge)
  - mechanism: SCC
    text: the UK Addendum to the EU Standard Contractual Clauses
  - mechanism: other
    text: the use of the UK International Data Transfer Agreement
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tracebit
provenance_date: '2026-11-10'
provider_name: Tracebit
provider_slug: tracebit
slug: tracebit-privacy-policy
source_date: '2026-11-10'
source_filename: tracebit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tracebit.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tracebit\naid: tracebit\nurl: https://tracebit.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Tracebit Limited (‘Tracebit’) is a security product company.\ndata_categories:\n- category: identifying\n  text: name job title employer name work address work email work phone number\n- category: device\n  text: information about the device you are using and its characteristics\n- category: behavioral\n  text: the number of page visits and statistically relevant behavior of our visitors on the website\npurposes:\n- purpose: provide services to prospects and customers\n  text:\
  \ We use this information to provide prospects and customers with services.\n- purpose: website analysis and improvement\n  text: We use these tools to collect statistics to improve the experience of our website visitors and to improve\n    our service to our customers.\nretention:\n- scope: service data\n  period: null\n  text: The Tracebit retains service data for the duration of the customer’s business relationship with the Tracebit\n    and for a period of time thereafter\n- scope: prospect data\n  period: null\n  text: Tracebit retains prospect data until such time as it no longer has business value and is purged from Tracebit\n    systems.\nresidency:\n- region: United States\n  text: The personal information Tracebit collects from you is stored in one or more databases hosted by third parties\n    located in the United States.\ntransfers:\n- mechanism: DPF\n  text: These safeguards may include reliance on the UK Extension to the EU-US Data Privacy Framework (also known\n    as the\
  \ UK-US Data Bridge)\n- mechanism: SCC\n  text: the UK Addendum to the EU Standard Contractual Clauses\n- mechanism: other\n  text: the use of the UK International Data Transfer Agreement\nsubprocessors:\n  url: trust.tracebit.com\n  text: 'A list of our third party sub processors can be found here: trust.tracebit.com'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: verified request from Data Subjects or their authorized agents, or email privacy@tracebit.com\n  text: All personal data that Tracebit controls may be deleted upon verified request from Data Subjects or their\n    authorized agents.\nrights:\n- right: access\n  text: Right of access\n- right: rectification\n  text: Right to rectification\n- right: erasure\n  text: Right to erasure\n- right: restrict processing\n  text: Right to restrict processing\n- right: portability\n  text: Right of data portability\n- right: object\n  text: Right to object\n- right: automated decision making\n  text: Rights related\
  \ to automated decision making including profiling\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell this personal information to anyone and only share it with third parties who are facilitating\n    the delivery of our services.\n"
source_yaml_url: https://artifacts.apis.io/tracebit/privacy/tracebit-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Tracebit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Security
- Deception
- Canary Tokens
- Threat Detection
- Cloud Security
- Incident Response
---
