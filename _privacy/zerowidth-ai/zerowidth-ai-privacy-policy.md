---
api_specs:
- filename: zerowidth-ai-caliper-api-openapi.yml
  format: yaml
  label: zerowidth-ai Caliper API
  slug: zerowidth-ai-caliper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerowidth-ai/openapi/zerowidth-ai-caliper-api-openapi.yml
- filename: zerowidth-ai-flows-api-openapi.yml
  format: yaml
  label: zerowidth-ai Flows API
  slug: zerowidth-ai-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerowidth-ai/openapi/zerowidth-ai-flows-api-openapi.yml
- filename: zerowidth-ai-knowledge-bases-api-openapi.yml
  format: yaml
  label: zerowidth-ai Knowledge Bases API
  slug: zerowidth-ai-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerowidth-ai/openapi/zerowidth-ai-knowledge-bases-api-openapi.yml
- filename: zerowidth-ai-ledger-api-openapi.yml
  format: yaml
  label: zerowidth-ai Ledger API
  slug: zerowidth-ai-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerowidth-ai/openapi/zerowidth-ai-ledger-api-openapi.yml
- filename: zerowidth-ai-shims-api-openapi.yml
  format: yaml
  label: zerowidth-ai Shims API
  slug: zerowidth-ai-shims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerowidth-ai/openapi/zerowidth-ai-shims-api-openapi.yml
- filename: zerowidth-ai-tasks-api-openapi.yml
  format: yaml
  label: zerowidth-ai Tasks API
  slug: zerowidth-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerowidth-ai/openapi/zerowidth-ai-tasks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: your chosen name and profile picture may be visible to other members of workspaces you join
  - category: contact
    text: Creating one requires a working email address
  - category: device
    text: your IP address your preferred language your web browser and operating system the referring website
  - category: communication
    text: we collect your phone number, the messages exchanged, and your opt-in and opt-out status
  - category: behavioral
    text: record what pages and actions you visited and when
  deletion:
    route: Email contact@zerowidth.ai with "Privacy" in the subject
    text: When you delete data, we remove it from our systems promptly thereafter .
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: service operation and account management
    text: register, maintain, and manage your account, and offer the services you signed up for
  - purpose: security and abuse prevention
    text: protect against fraud, unauthorized access, and abuse
  - purpose: product improvement
    text: understand user needs so we can refine and expand the product
  - purpose: processing customer data for tools
    text: When you send data through our API or interface for processing, we use that data only to run the tools you've configured.
  residency:
  - region: United States
    text: We store data in the United States on Google Cloud Platform.
  retention:
  - period: null
    scope: Website and product usage data
    text: Logs of pages visited, technical environment, and similar usage data are retained for a limited operational period .
  - period: null
    scope: Account data
    text: Your account information — email, profile, workspace memberships — is retained as long as your account remains active.
  - period: null
    scope: Customer Content and processed data
    text: Workspace content (pages, datasets, rubrics, flows, agents, run history) is kept as long as the workspace is active.
  rights:
  - right: Access
    text: You have the right to request access to the personal data we hold about you
  - right: Rectification
    text: If the personal data we hold about you is inaccurate or incomplete, you have the right to request its correction.
  - right: Erasure
    text: In certain circumstances you have the right to request the deletion of your personal data.
  - right: Restriction of processing
    text: You have the right to request a restriction on the processing of your personal data
  - right: Data portability
    text: you have the right to receive the personal data we hold about you in a structured, commonly-used, and machine-readable format
  - right: Objection to processing
    text: You have the right to object to the processing of your personal data for direct marketing purposes or when our processing is based on legitimate interests.
  role:
    text: the customer who uploaded or sent the data is the controller; we process it as their processor under the Data Processing Addendum
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, share it with advertisers, or use your private Customer Content to train generative models.
  subprocessors:
    text: We share specific data with a small set of subprocessors who help operate the service.
    url: https://zerowidth.ai/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: Where required, we rely on the EU Standard Contractual Clauses (and UK equivalents) as the transfer mechanism between the EEA / UK / Switzerland and the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: zerowidth-ai
provenance_date: '2026-11-10'
provider_name: zerowidth-ai
provider_slug: zerowidth-ai
slug: zerowidth-ai-privacy-policy
source_date: '2026-11-10'
source_filename: zerowidth-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zerowidth.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: zerowidth-ai\naid: zerowidth-ai\nurl: https://zerowidth.ai/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: the customer who uploaded or sent the data is the controller; we process it as their processor under the\n    Data Processing Addendum\ndata_categories:\n- category: identifying\n  text: your chosen name and profile picture may be visible to other members of workspaces you join\n- category: contact\n  text: Creating one requires a working email address\n- category: device\n  text: your IP address your preferred language your web browser and operating system the referring website\n\
  - category: communication\n  text: we collect your phone number, the messages exchanged, and your opt-in and opt-out status\n- category: behavioral\n  text: record what pages and actions you visited and when\npurposes:\n- purpose: service operation and account management\n  text: register, maintain, and manage your account, and offer the services you signed up for\n- purpose: security and abuse prevention\n  text: protect against fraud, unauthorized access, and abuse\n- purpose: product improvement\n  text: understand user needs so we can refine and expand the product\n- purpose: processing customer data for tools\n  text: When you send data through our API or interface for processing, we use that data only to run the tools you've\n    configured.\nretention:\n- scope: Website and product usage data\n  period: null\n  text: Logs of pages visited, technical environment, and similar usage data are retained for a limited operational\n    period .\n- scope: Account data\n  period: null\n \
  \ text: Your account information — email, profile, workspace memberships — is retained as long as your account remains\n    active.\n- scope: Customer Content and processed data\n  period: null\n  text: Workspace content (pages, datasets, rubrics, flows, agents, run history) is kept as long as the workspace\n    is active.\nresidency:\n- region: United States\n  text: We store data in the United States on Google Cloud Platform.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on the EU Standard Contractual Clauses (and UK equivalents) as the transfer mechanism\n    between the EEA / UK / Switzerland and the United States.\nsubprocessors:\n  url: https://zerowidth.ai/legal/subprocessors\n  text: We share specific data with a small set of subprocessors who help operate the service.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: Email contact@zerowidth.ai with \"Privacy\" in the subject\n  text: When you delete data, we remove it\
  \ from our systems promptly thereafter .\nrights:\n- right: Access\n  text: You have the right to request access to the personal data we hold about you\n- right: Rectification\n  text: If the personal data we hold about you is inaccurate or incomplete, you have the right to request its correction.\n- right: Erasure\n  text: In certain circumstances you have the right to request the deletion of your personal data.\n- right: Restriction of processing\n  text: You have the right to request a restriction on the processing of your personal data\n- right: Data portability\n  text: you have the right to receive the personal data we hold about you in a structured, commonly-used, and machine-readable\n    format\n- right: Objection to processing\n  text: You have the right to object to the processing of your personal data for direct marketing purposes or when\n    our processing is based on legitimate interests.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, share\
  \ it with advertisers, or use your private Customer Content to train generative\n    models.\n"
source_yaml_url: https://artifacts.apis.io/zerowidth-ai/privacy/zerowidth-ai-privacy-policy.yml
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
summary_line: 25 quoted statements, read from zerowidth-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Consulting
- Software-as-a-Service
- Platform
---
