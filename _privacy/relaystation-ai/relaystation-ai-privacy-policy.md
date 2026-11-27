---
api_specs:
- filename: relaystation-ai-api-openapi.json
  format: json
  label: Relaystation Api API
  slug: relaystation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relaystation-ai/openapi/_original/relaystation-ai-api-openapi.json
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: If you sign in with Google or GitHub, we receive your name, email address, and account identifier from that provider.
  - category: financial
    text: we receive transaction confirmations, billing metadata, and your ledger history, but we do not store full card numbers
  - category: location
    text: IP address, timestamps, error data, and similar diagnostic information
  - category: biometric
    text: we collect and process government-ID images, biometric liveness/face-match data, and name/identity information submitted for sanctions and PEP screening
  - category: communication
    text: we process the message content and the destination contact information (Telegram handle, email address, or phone number)
  - category: behavioral
    text: we automatically collect API request logs, tool-call metadata
  deletion:
    route: dashboard or contact email
    text: You can exercise most of these rights directly for account data via the dashboard at app.relaystation.ai, or by contacting us at the address below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and provide the Service
    text: We use the information described above to operate and provide the Service (executing the specific tool called and returning a result)
  - purpose: fraud and abuse security
    text: secure the Service against fraud, abuse, and unauthorized access
  - purpose: identity verification and screening
    text: complete identity verification and sanctions/PEP screening where you request those tools
  residency:
  - region: United States
    text: The Service may process and store data in jurisdictions other than your own, including the United States.
  retention:
  - period: null
    scope: Batons
    text: Batons follow the lifecycle you configure (time, size, or read-count limits).
  - period: null
    scope: Identity verification and screening records
    text: are retained for the period required by applicable KYC/AML-adjacent obligations in the relevant jurisdiction
  - period: null
    scope: Account and authentication data
    text: retained for as long as your account is active, and deleted or anonymized within a reasonable period after account closure
  rights:
  - right: access, correct, delete, or export
    text: you may have the right to access, correct, delete, or export personal information we hold about you
  - right: object or restrict processing
    text: and to object to or restrict certain processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell personal information.
  subprocessors:
    text: 'Named sub-processors who help us operate the Service: Stripe (payment processing) and Amazon Web Services (cloud storage and compute infrastructure).'
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards (such as standard contractual clauses) for cross-border transfers of personal data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: relaystation-ai
provenance_date: '2026-11-10'
provider_name: relaystation-ai
provider_slug: relaystation-ai
slug: relaystation-ai-privacy-policy
source_date: '2026-11-10'
source_filename: relaystation-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://relaystation.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: relaystation-ai\naid: relaystation-ai\nurl: https://relaystation.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: If you sign in with Google or GitHub, we receive your name, email address, and account identifier from that\n    provider.\n- category: financial\n  text: we receive transaction confirmations, billing metadata, and your ledger history, but we do not store full\n    card numbers\n- category: location\n  text: IP address, timestamps, error data, and similar diagnostic information\n- category: biometric\n  text: we collect\
  \ and process government-ID images, biometric liveness/face-match data, and name/identity information\n    submitted for sanctions and PEP screening\n- category: communication\n  text: we process the message content and the destination contact information (Telegram handle, email address,\n    or phone number)\n- category: behavioral\n  text: we automatically collect API request logs, tool-call metadata\npurposes:\n- purpose: operate and provide the Service\n  text: We use the information described above to operate and provide the Service (executing the specific tool called\n    and returning a result)\n- purpose: fraud and abuse security\n  text: secure the Service against fraud, abuse, and unauthorized access\n- purpose: identity verification and screening\n  text: complete identity verification and sanctions/PEP screening where you request those tools\nretention:\n- scope: Batons\n  period: null\n  text: Batons follow the lifecycle you configure (time, size, or read-count limits).\n\
  - scope: Identity verification and screening records\n  period: null\n  text: are retained for the period required by applicable KYC/AML-adjacent obligations in the relevant jurisdiction\n- scope: Account and authentication data\n  period: null\n  text: retained for as long as your account is active, and deleted or anonymized within a reasonable period after\n    account closure\nresidency:\n- region: United States\n  text: The Service may process and store data in jurisdictions other than your own, including the United States.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards (such as standard contractual clauses) for cross-border transfers of personal\n    data\nsubprocessors:\n  url: null\n  text: 'Named sub-processors who help us operate the Service: Stripe (payment processing) and Amazon Web Services\n    (cloud storage and compute infrastructure).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard or contact email\n  text: You\
  \ can exercise most of these rights directly for account data via the dashboard at app.relaystation.ai,\n    or by contacting us at the address below.\nrights:\n- right: access, correct, delete, or export\n  text: you may have the right to access, correct, delete, or export personal information we hold about you\n- right: object or restrict processing\n  text: and to object to or restrict certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/relaystation-ai/privacy/relaystation-ai-privacy-policy.yml
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
summary_line: 19 quoted statements, read from relaystation-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data-Relay
- Real-Time
- Cloud
---
