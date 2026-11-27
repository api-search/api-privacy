---
api_specs:
- filename: agentage-io-openapi-generated.yml
  format: yaml
  label: agentage-io API
  slug: agentage-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentage-io/openapi/_ae-authored/agentage-io-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: Waitlist - your email address and, optionally, which AI tools you use.
  - category: device
    text: your IP address, browser and device (user-agent), the page that referred you, and any campaign tags (UTM)
  - category: identifying
    text: the identifier from your chosen sign-in (GitHub, Google, or Microsoft) and basic profile details that provider returns
  - category: other
    text: Your memory content - the notes your AI tools read and write through the MCP endpoint.
  - category: other
    text: Operational logs - minimal request and error logs needed to run and secure the service.
  deletion:
    route: Delete a memory or your account in the service
    text: Delete a memory or your account and the corresponding data is removed from our store; you keep your local files.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: 'To operate the service: store and sync your memory, return search results, authenticate you, send service messages, and keep the system secure and reliable.'
  - purpose: gauge demand and prevent abuse
    text: to gauge demand and prevent abuse, not to profile you
  residency:
  - region: EU (Germany)
    text: Your canonical store and our index run on EU-based cloud infrastructure (Germany)
  retention:
  - period: null
    scope: account data
    text: We keep your data while your account is active.
  rights:
  - right: access
    text: Under the GDPR you can access, correct, export, or delete your personal data, and object to or restrict certain processing.
  - right: export
    text: You can export your full memory as plain files at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not use your memory content to train models.
  subprocessors:
    text: 'We rely on a small set of providers, each handling a specific function: EU cloud infrastructure (Germany) - compute and storage.'
    url: null
  transfers:
  - mechanism: other
    text: Anthropic (US) - LLM tool-calling pass-through; not used to train models.
  - mechanism: other
    text: Google (US) - Google Analytics, to measure marketing-site usage.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agentage-io
provenance_date: '2026-11-09'
provider_name: agentage-io
provider_slug: agentage-io
slug: agentage-io-privacy-policy
source_date: '2026-11-09'
source_filename: agentage-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentage.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agentage-io\naid: agentage-io\nurl: https://agentage.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Waitlist - your email address and, optionally, which AI tools you use.\n- category: device\n  text: your IP address, browser and device (user-agent), the page that referred you, and any campaign tags (UTM)\n- category: identifying\n  text: the identifier from your chosen sign-in (GitHub, Google, or Microsoft) and basic profile details that provider\n    returns\n- category: other\n  text: Your memory content - the notes your AI tools\
  \ read and write through the MCP endpoint.\n- category: other\n  text: Operational logs - minimal request and error logs needed to run and secure the service.\npurposes:\n- purpose: operate the service\n  text: 'To operate the service: store and sync your memory, return search results, authenticate you, send service\n    messages, and keep the system secure and reliable.'\n- purpose: gauge demand and prevent abuse\n  text: to gauge demand and prevent abuse, not to profile you\nretention:\n- scope: account data\n  period: null\n  text: We keep your data while your account is active.\nresidency:\n- region: EU (Germany)\n  text: Your canonical store and our index run on EU-based cloud infrastructure (Germany)\ntransfers:\n- mechanism: other\n  text: Anthropic (US) - LLM tool-calling pass-through; not used to train models.\n- mechanism: other\n  text: Google (US) - Google Analytics, to measure marketing-site usage.\nsubprocessors:\n  url: null\n  text: 'We rely on a small set of providers,\
  \ each handling a specific function: EU cloud infrastructure (Germany)\n    - compute and storage.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a memory or your account in the service\n  text: Delete a memory or your account and the corresponding data is removed from our store; you keep your local\n    files.\nrights:\n- right: access\n  text: Under the GDPR you can access, correct, export, or delete your personal data, and object to or restrict\n    certain processing.\n- right: export\n  text: You can export your full memory as plain files at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we do not use your memory content to train models.\n"
source_yaml_url: https://artifacts.apis.io/agentage-io/privacy/agentage-io-privacy-policy.yml
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
summary_line: 16 quoted statements, read from agentage-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Collaboration
- Privacy
- EU-hosted
---
