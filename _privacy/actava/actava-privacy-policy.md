---
api_specs:
- filename: actava-models-api-openapi.yml
  format: yaml
  label: Actava.ai Models API
  slug: actava-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actava/openapi/actava-models-api-openapi.yml
- filename: actava-chat-completions-api-openapi.yml
  format: yaml
  label: Actava.ai Chat Completions API
  slug: actava-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actava/openapi/actava-chat-completions-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, phone number, company name, job title, and billing details.'
  - category: behavioral
    text: 'Usage Data: Features accessed, actions taken, timestamps, frequency of use, and performance metrics.'
  - category: device
    text: 'Device & Technical Data: IP address, browser type, operating system, device identifiers, and referring URLs.'
  - category: health
    text: This may include health information, precise geolocation, and account credentials.
  - category: communication
    text: 'Communications: Messages you send to us via support channels, email, feedback forms, and recorded support calls or screen-shares'
  deletion:
    route: Request deletion via compliance@actava.ai
    text: You may request deletion of your data at any time (see Section 9).
  dpa:
    available: true
    text: Enterprise customers receive this no-training commitment contractually through our Master Services Agreement and Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide and operate Services
    text: Provide, operate, and maintain our Services.
  - purpose: Improve and develop features
    text: Improve, personalize, and develop new features (using aggregated or de-identified data; see Section 3.1).
  - purpose: Fraud and security
    text: Monitor for fraud, abuse, and security threats.
  retention:
  - period: up to 90 days after deletion
    scope: Account Data
    text: Retained for the duration of your account and for up to 90 days after deletion, unless a longer period is required by law.
  - period: null
    scope: User Content
    text: Following termination, customer tenant data is available for export for 30 days, then deleted within 60 days, unless retention is required by law or specified differently in the customer agreement.
  - period: Zero retention
    scope: CURA API Inputs & Outputs
    text: 'CURA API Inputs & Outputs: Zero retention. Prompt and completion bodies are processed transiently to generate a response and are not persisted to storage.'
  - period: up to 24 months
    scope: Usage & Log Data
    text: 'Usage & Log Data: Retained for up to 24 months for security and analytics purposes.'
  - period: up to 30 days
    scope: Backups
    text: Encrypted backups may persist for up to 30 days after data deletion before being overwritten.
  rights:
  - right: Access
    text: Access the personal information we hold about you.
  - right: Correct
    text: Correct inaccurate or incomplete information.
  - right: Delete
    text: Delete your personal information (subject to legal retention requirements).
  - right: Export
    text: Export your data in a portable format.
  - right: Opt out
    text: Opt out of non-essential cookies, profiling, targeted advertising, and the sale or sharing of personal information
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  role:
    text: In most enterprise deployments, Actava.ai acts as a data processor (or, under HIPAA, a Business Associate ) on behalf of our customers, who serve as the data controller (or Covered Entity).
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A current list of subprocessors is maintained at trust.actava.ai/subprocessors.
    url: trust.actava.ai/subprocessors
  transfers:
  - mechanism: DPF
    text: Where we participate in a recognized data transfer framework (such as the EU-US Data Privacy Framework, UK Extension, and Swiss-US Data Privacy Framework), we will identify our certification on our website.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Actava.ai
provenance_date: '2026-11-09'
provider_name: Actava.ai
provider_slug: actava
slug: actava-privacy-policy
source_date: '2026-11-09'
source_filename: actava-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.actava.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Actava.ai\naid: actava\nurl: https://www.actava.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In most enterprise deployments, Actava.ai acts as a data processor (or, under HIPAA, a Business Associate\n    ) on behalf of our customers, who serve as the data controller (or Covered Entity).\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, phone number, company name, job title, and billing details.'\n- category: behavioral\n  text: 'Usage Data: Features accessed, actions taken, timestamps, frequency of use, and performance metrics.'\n- category:\
  \ device\n  text: 'Device & Technical Data: IP address, browser type, operating system, device identifiers, and referring\n    URLs.'\n- category: health\n  text: This may include health information, precise geolocation, and account credentials.\n- category: communication\n  text: 'Communications: Messages you send to us via support channels, email, feedback forms, and recorded support\n    calls or screen-shares'\npurposes:\n- purpose: Provide and operate Services\n  text: Provide, operate, and maintain our Services.\n- purpose: Improve and develop features\n  text: Improve, personalize, and develop new features (using aggregated or de-identified data; see Section 3.1).\n- purpose: Fraud and security\n  text: Monitor for fraud, abuse, and security threats.\nretention:\n- scope: Account Data\n  period: up to 90 days after deletion\n  text: Retained for the duration of your account and for up to 90 days after deletion, unless a longer period is\n    required by law.\n- scope: User Content\n\
  \  period: null\n  text: Following termination, customer tenant data is available for export for 30 days, then deleted within 60\n    days, unless retention is required by law or specified differently in the customer agreement.\n- scope: CURA API Inputs & Outputs\n  period: Zero retention\n  text: 'CURA API Inputs & Outputs: Zero retention. Prompt and completion bodies are processed transiently to generate\n    a response and are not persisted to storage.'\n- scope: Usage & Log Data\n  period: up to 24 months\n  text: 'Usage & Log Data: Retained for up to 24 months for security and analytics purposes.'\n- scope: Backups\n  period: up to 30 days\n  text: Encrypted backups may persist for up to 30 days after data deletion before being overwritten.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Where we participate in a recognized data transfer framework (such as the EU-US Data Privacy Framework,\n    UK Extension, and Swiss-US Data Privacy Framework), we will identify our certification\
  \ on our website.\nsubprocessors:\n  url: trust.actava.ai/subprocessors\n  text: A current list of subprocessors is maintained at trust.actava.ai/subprocessors.\ndpa:\n  available: true\n  url: null\n  text: Enterprise customers receive this no-training commitment contractually through our Master Services Agreement\n    and Data Processing Addendum\ndeletion:\n  route: Request deletion via compliance@actava.ai\n  text: You may request deletion of your data at any time (see Section 9).\nrights:\n- right: Access\n  text: Access the personal information we hold about you.\n- right: Correct\n  text: Correct inaccurate or incomplete information.\n- right: Delete\n  text: Delete your personal information (subject to legal retention requirements).\n- right: Export\n  text: Export your data in a portable format.\n- right: Opt out\n  text: Opt out of non-essential cookies, profiling, targeted advertising, and the sale or sharing of personal information\n- right: Withdraw consent\n  text: Withdraw\
  \ consent where processing is based on consent.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/actava/privacy/actava-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 24 quoted statements, read from Actava.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Machine Learning
- Platform
---
