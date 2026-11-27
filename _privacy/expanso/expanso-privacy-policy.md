---
api_specs:
- filename: expanso-ops-api-openapi.yml
  format: yaml
  label: Expanso Ops API
  slug: expanso-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/expanso/openapi/expanso-ops-api-openapi.yml
- filename: expanso-orchestrator-api-openapi.yml
  format: yaml
  label: Expanso Orchestrator API
  slug: expanso-orchestrator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/expanso/openapi/expanso-orchestrator-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information, such as your name and email address, and the account you sign in with.
  - category: contact
    text: Our tools send ChatGPT your name, email address and account ID, so it can show which account is connected.
  - category: device
    text: Loading the image sends Scarf your IP address, your browser's user agent, and the URL of the page you are viewing.
  - category: behavioral
    text: Usage and diagnostic information, such as how you use Expanso Cloud, which campaign or website brought you to it, error reports, and feedback you send us.
  - category: other
    text: Data you put into Expanso Cloud, such as your pipelines and nodes, and the metrics, health and logs your nodes send us.
  deletion:
    route: Contact us
    text: To access, correct or delete your personal information, to stop marketing emails, or to remove ChatGPT's access on our side, contact us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Expanso Cloud
    text: 'Provide Expanso Cloud: sign you in, run your pipelines, and show you and your organization what you have access to.'
  - purpose: Customer contact and marketing
    text: Contact you about Expanso's products and services, and learn which campaign or website brought you to Expanso Cloud.
  - purpose: Site analytics
    text: Compile aggregate data about site traffic and interaction to offer better site experiences and tools in the future.
  - purpose: Security and improvement
    text: Keep Expanso Cloud secure, find and fix errors, and improve it.
  retention:
  - period: 90 days
    scope: Server logs
    text: Retain server logs containing the IP address of all requests to this server for no more than 90 days.
  - period: 5 years
    scope: Registered user IP addresses
    text: Retain the IP addresses associated with registered users and their posts for no more than 5 years.
  - period: 30 days
    scope: Account and organization information
    text: Account and organization information for as long as your account exists, and delete it within 30 days after you ask us to.
  - period: 30 days
    scope: Backups
    text: Backups for up to 30 days.
  rights:
  - right: access, correction, deletion
    text: To access, correct or delete your personal information, to stop marketing emails, or to remove ChatGPT's access on our side, contact us at [email protected] .
  - right: opt out of analytics cookies
    text: You can choose whether to allow analytics cookies in the cookie settings.
  role:
    text: Welcome to Expanso Inc. ("Expanso," "we," "us," or "our").
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell, trade, or otherwise transfer your personally identifiable information to outside parties unless required by law or for the operation of our website, conducting our business, or servicing you.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Expanso
provenance_date: '2026-11-09'
provider_name: Expanso
provider_slug: expanso
slug: expanso-privacy-policy
source_date: '2026-11-09'
source_filename: expanso-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://expanso.io/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Expanso\naid: expanso\nurl: https://expanso.io/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Welcome to Expanso Inc. (\"Expanso,\" \"we,\" \"us,\" or \"our\").\ndata_categories:\n- category: identifying\n  text: Account information, such as your name and email address, and the account you sign in with.\n- category: contact\n  text: Our tools send ChatGPT your name, email address and account ID, so it can show which account is connected.\n- category: device\n  text: Loading the image sends Scarf your IP address, your browser's user agent, and the URL of the page you are\n \
  \   viewing.\n- category: behavioral\n  text: Usage and diagnostic information, such as how you use Expanso Cloud, which campaign or website brought you\n    to it, error reports, and feedback you send us.\n- category: other\n  text: Data you put into Expanso Cloud, such as your pipelines and nodes, and the metrics, health and logs your\n    nodes send us.\npurposes:\n- purpose: Provide Expanso Cloud\n  text: 'Provide Expanso Cloud: sign you in, run your pipelines, and show you and your organization what you have\n    access to.'\n- purpose: Customer contact and marketing\n  text: Contact you about Expanso's products and services, and learn which campaign or website brought you to Expanso\n    Cloud.\n- purpose: Site analytics\n  text: Compile aggregate data about site traffic and interaction to offer better site experiences and tools in\n    the future.\n- purpose: Security and improvement\n  text: Keep Expanso Cloud secure, find and fix errors, and improve it.\nretention:\n- scope: Server\
  \ logs\n  period: 90 days\n  text: Retain server logs containing the IP address of all requests to this server for no more than 90 days.\n- scope: Registered user IP addresses\n  period: 5 years\n  text: Retain the IP addresses associated with registered users and their posts for no more than 5 years.\n- scope: Account and organization information\n  period: 30 days\n  text: Account and organization information for as long as your account exists, and delete it within 30 days after\n    you ask us to.\n- scope: Backups\n  period: 30 days\n  text: Backups for up to 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us\n  text: To access, correct or delete your personal information, to stop marketing emails, or to remove ChatGPT's\n    access on our side, contact us at [email protected] .\nrights:\n- right: access, correction, deletion\n  text: To access, correct or delete your\
  \ personal information, to stop marketing emails, or to remove ChatGPT's\n    access on our side, contact us at [email protected] .\n- right: opt out of analytics cookies\n  text: You can choose whether to allow analytics cookies in the cookie settings.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell, trade, or otherwise transfer your personally identifiable information to outside parties\n    unless required by law or for the operation of our website, conducting our business, or servicing you.\n"
source_yaml_url: https://artifacts.apis.io/expanso/privacy/expanso-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Expanso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Distributed Computing
- Edge Computing
- Compute Orchestration
- Data Pipeline
- Data Governance
- Open Source
- Artificial Intelligence
- Job Orchestration
---
