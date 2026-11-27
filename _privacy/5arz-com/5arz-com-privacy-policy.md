---
api_specs:
- filename: 5arz-com-api-openapi.json
  format: json
  label: 5arz Proof-of-Human API API
  slug: 5arz-proof-of-human-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5arz-com/openapi/_original/5arz-com-api-openapi.json
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account basics: name, email address, phone number, country of residence'
  - category: financial
    text: 'Member-supplied debt information: when you choose to enter debt details manually rather than via a connected provider'
  - category: location
    text: country (derived from IP)
  - category: device
    text: Request logs at the Cloudflare edge — IP address, user-agent, request path, response code, country (derived from IP), and correlation ID.
  - category: behavioral
    text: 'Task answers: your answers to verified tasks and the time spent on each question'
  - category: communication
    text: 'Support correspondence: messages you send to info@5arz.com, security@5arz.com, or privacy@5arz.com.'
  - category: biometric
    text: Sensitive identity, banking, and biometric data — Social Security numbers, bank login credentials, full card numbers, government-issued ID documents, live selfies — never touch our servers .
  deletion:
    route: Delete account in the 5arz app (You → Delete account), or email privacy@5arz.com
    text: delete your account at any time in the 5arz app ( You → Delete account ), or ask us to delete information by email, subject to legal-retention exceptions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Services
    text: 'Provide the Services: verify identity, enumerate debts, route payoffs, mint protocol tokens, support recovery flows.'
  - purpose: Operate the platform
    text: 'Operate the platform: authenticate sessions, prevent fraud and abuse, maintain availability, debug issues.'
  - purpose: Communicate with you
    text: 'Communicate with you: respond to support, send transactional notifications about your account, deliver legally required notices.'
  - purpose: Improve and secure the Services
    text: 'Improve and secure the Services: diagnose errors, refine UX, monitor for security incidents, train internal systems on aggregated and de-identified data.'
  retention:
  - period: life of the member account plus 7 years
    scope: Account information
    text: Account information — for the life of the member account plus 7 years to satisfy financial-services recordkeeping obligations.
  - period: 30 days
    scope: Edge request logs
    text: Edge request logs — 30 days at the edge; exported to long-term storage only on incident.
  - period: 3 years from the last interaction
    scope: Support correspondence
    text: Support correspondence — 3 years from the last interaction.
  rights:
  - right: Access
    text: Access — request a copy of the personal information we hold about you.
  - right: Correct
    text: Correct — ask us to fix inaccurate or incomplete information.
  - right: Delete
    text: Delete — delete your account at any time in the 5arz app
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format.
  - right: Restrict or object
    text: Restrict or object — limit how we process your data in certain circumstances.
  - right: Withdraw consent
    text: Withdraw consent — where processing is based on consent, withdraw it at any time.
  - right: Non-discrimination
    text: Non-discrimination — exercise your rights without retaliation or degraded service.
  role:
    text: The data controller is 5arz, Inc. (Delaware C-Corp).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal information.
  subprocessors:
    text: Our current sub-processor list is maintained on this page.
    url: https://5arz.com/privacy
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards, including Standard Contractual Clauses approved by the European Commission, the UK International Data Transfer Addendum, and equivalent mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 5arz
provenance_date: '2026-11-09'
provider_name: 5arz
provider_slug: 5arz-com
slug: 5arz-com-privacy-policy
source_date: '2026-11-09'
source_filename: 5arz-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://5arz.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 5arz\naid: 5arz-com\nurl: https://5arz.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is 5arz, Inc. (Delaware C-Corp).\ndata_categories:\n- category: identifying\n  text: 'Account basics: name, email address, phone number, country of residence'\n- category: financial\n  text: 'Member-supplied debt information: when you choose to enter debt details manually rather than via a connected\n    provider'\n- category: location\n  text: country (derived from IP)\n- category: device\n  text: Request logs at the Cloudflare edge — IP address, user-agent, request path,\
  \ response code, country (derived\n    from IP), and correlation ID.\n- category: behavioral\n  text: 'Task answers: your answers to verified tasks and the time spent on each question'\n- category: communication\n  text: 'Support correspondence: messages you send to info@5arz.com, security@5arz.com, or privacy@5arz.com.'\n- category: biometric\n  text: Sensitive identity, banking, and biometric data — Social Security numbers, bank login credentials, full\n    card numbers, government-issued ID documents, live selfies — never touch our servers .\npurposes:\n- purpose: Provide the Services\n  text: 'Provide the Services: verify identity, enumerate debts, route payoffs, mint protocol tokens, support recovery\n    flows.'\n- purpose: Operate the platform\n  text: 'Operate the platform: authenticate sessions, prevent fraud and abuse, maintain availability, debug issues.'\n- purpose: Communicate with you\n  text: 'Communicate with you: respond to support, send transactional notifications about\
  \ your account, deliver\n    legally required notices.'\n- purpose: Improve and secure the Services\n  text: 'Improve and secure the Services: diagnose errors, refine UX, monitor for security incidents, train internal\n    systems on aggregated and de-identified data.'\nretention:\n- scope: Account information\n  period: life of the member account plus 7 years\n  text: Account information — for the life of the member account plus 7 years to satisfy financial-services recordkeeping\n    obligations.\n- scope: Edge request logs\n  period: 30 days\n  text: Edge request logs — 30 days at the edge; exported to long-term storage only on incident.\n- scope: Support correspondence\n  period: 3 years from the last interaction\n  text: Support correspondence — 3 years from the last interaction.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards, including Standard Contractual Clauses approved by the European Commission,\n    the UK International Data Transfer\
  \ Addendum, and equivalent mechanisms.\nsubprocessors:\n  url: https://5arz.com/privacy\n  text: Our current sub-processor list is maintained on this page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in the 5arz app (You → Delete account), or email privacy@5arz.com\n  text: delete your account at any time in the 5arz app ( You → Delete account ), or ask us to delete information\n    by email, subject to legal-retention exceptions.\nrights:\n- right: Access\n  text: Access — request a copy of the personal information we hold about you.\n- right: Correct\n  text: Correct — ask us to fix inaccurate or incomplete information.\n- right: Delete\n  text: Delete — delete your account at any time in the 5arz app\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format.\n- right: Restrict or object\n  text: Restrict or object — limit how we process your data in certain circumstances.\n- right: Withdraw consent\n\
  \  text: Withdraw consent — where processing is based on consent, withdraw it at any time.\n- right: Non-discrimination\n  text: Non-discrimination — exercise your rights without retaliation or degraded service.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal information.\n"
source_yaml_url: https://artifacts.apis.io/5arz-com/privacy/5arz-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from 5arz's own page on 2026-11-09.
synthetic: false
tags:
- Human Verification
- Artificial Intelligence
- Privacy
- Developer Tools
- Authentication
---
