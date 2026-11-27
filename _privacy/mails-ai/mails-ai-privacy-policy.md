---
api_specs:
- filename: mails-ai-account-api-openapi.yml
  format: yaml
  label: mails-ai Account API
  slug: mails-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-account-api-openapi.yml
- filename: mails-ai-agents-api-openapi.yml
  format: yaml
  label: mails-ai Agents API
  slug: mails-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-agents-api-openapi.yml
- filename: mails-ai-api-keys-api-openapi.yml
  format: yaml
  label: mails-ai API Keys API
  slug: mails-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-api-keys-api-openapi.yml
- filename: mails-ai-billing-api-openapi.yml
  format: yaml
  label: mails-ai Billing API
  slug: mails-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-billing-api-openapi.yml
- filename: mails-ai-connected-apps-api-openapi.yml
  format: yaml
  label: mails-ai Connected Apps API
  slug: mails-ai-connected-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-connected-apps-api-openapi.yml
- filename: mails-ai-domains-api-openapi.yml
  format: yaml
  label: mails-ai Domains API
  slug: mails-ai-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-domains-api-openapi.yml
- filename: mails-ai-drafts-api-openapi.yml
  format: yaml
  label: mails-ai Drafts API
  slug: mails-ai-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-drafts-api-openapi.yml
- filename: mails-ai-events-api-openapi.yml
  format: yaml
  label: mails-ai Events API
  slug: mails-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-events-api-openapi.yml
- filename: mails-ai-inbound-api-openapi.yml
  format: yaml
  label: mails-ai Inbound API
  slug: mails-ai-inbound-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-inbound-api-openapi.yml
- filename: mails-ai-labels-api-openapi.yml
  format: yaml
  label: mails-ai Labels API
  slug: mails-ai-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-labels-api-openapi.yml
- filename: mails-ai-logs-api-openapi.yml
  format: yaml
  label: mails-ai Logs API
  slug: mails-ai-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-logs-api-openapi.yml
- filename: mails-ai-messages-api-openapi.yml
  format: yaml
  label: mails-ai Messages API
  slug: mails-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-messages-api-openapi.yml
- filename: mails-ai-metrics-api-openapi.yml
  format: yaml
  label: mails-ai Metrics API
  slug: mails-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-metrics-api-openapi.yml
- filename: mails-ai-public-api-openapi.yml
  format: yaml
  label: mails-ai Public API
  slug: mails-ai-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-public-api-openapi.yml
- filename: mails-ai-reputation-api-openapi.yml
  format: yaml
  label: mails-ai Reputation API
  slug: mails-ai-reputation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-reputation-api-openapi.yml
- filename: mails-ai-search-api-openapi.yml
  format: yaml
  label: mails-ai Search API
  slug: mails-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-search-api-openapi.yml
- filename: mails-ai-suppression-api-openapi.yml
  format: yaml
  label: mails-ai Suppression API
  slug: mails-ai-suppression-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-suppression-api-openapi.yml
- filename: mails-ai-threads-api-openapi.yml
  format: yaml
  label: mails-ai Threads API
  slug: mails-ai-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-threads-api-openapi.yml
- filename: mails-ai-webhooks-api-openapi.yml
  format: yaml
  label: mails-ai Webhooks API
  slug: mails-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mails-ai/openapi/mails-ai-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: The email address you sign up with, workspace slug + display name, billing identity (handled by Stripe).
  - category: communication
    text: 'Email you send through your agents and email your agents receive: headers, addresses, subject, body content, extracted reply text, attachments metadata.'
  - category: communication
    text: 'Texts your connected phone numbers receive: the sender’s number, the receiving number, the words, and the carrier’s delivery record.'
  - category: behavioral
    text: Classifier output. Typed-event fields derived from inbound messages (intent, entities, urgency, injection_score, sender_reputation).
  - category: device
    text: Audit-log rows for every API call (API-key prefix, action, target, timestamp, IP, user-agent)
  deletion:
    route: Self-serve in Settings → Danger zone, or email support@mails.ai
    text: 'Self-serve: sign in, open Settings → Danger zone, and delete a workspace or your whole account — it is erased at once and you get a deletion receipt.'
  dpa:
    available: true
    text: flag this in your DPA request and we’ll provide our SCC-aligned addendum.
    url: null
  purposes:
  - purpose: Contract performance
    text: Contract performance (GDPR Art. 6(1)(b)). Account, message, and billing data — we can’t send your email or charge you without them.
  - purpose: Security and abuse prevention
    text: Legitimate interest (GDPR Art. 6(1)(f)). Operational logs for security, abuse prevention, deliverability protection.
  - purpose: Classifier inference for your agent
    text: Classifier inference to label inbound for your agent.
  - purpose: Legal obligation
    text: Legal obligation (GDPR Art. 6(1)(c)). Tax records (Stripe), abuse reports, lawful requests from competent authorities.
  residency:
  - region: United States
    text: Many of our sub-processors are in the United States.
  retention:
  - period: null
    scope: Active-account data
    text: Active-account data is retained for as long as the account is active.
  - period: 90 days
    scope: Audit-log rows
    text: target 90 days for Free/Pro, 1 year for Scale
  - period: up to 30 days
    scope: Classifier abuse-monitoring logs at OpenAI
    text: it keeps abuse-monitoring logs, which can include the request, for up to 30 days
  - period: 30 days
    scope: Workspace and message data after closure or erasure
    text: 'On account closure or erasure request: workspace + message data is deleted within 30 days'
  rights:
  - right: Access
    text: Access (Art. 15). A copy of the personal data we hold about you.
  - right: Rectification
    text: Rectification (Art. 16). Correction of inaccurate or incomplete data
  - right: Erasure
    text: Erasure (Art. 17). Deletion of your account and associated data.
  - right: Portability
    text: Portability (Art. 20). Machine-readable export of your messages, events, agents, and audit-log rows.
  - right: Restrict / object
    text: Restrict / object (Art. 18, 21). Email us; we’ll honor the request unless we have an overriding legitimate interest
  role:
    text: For received mail and texts, we act as your processor.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Each vendor’s name, purpose, data category, region (where a source names one) and added-at date are at /sub-processors .
    url: /sub-processors
  transfers:
  - mechanism: SCC
    text: Where required, transfers from the EEA / UK rely on the European Commission’s Standard Contractual Clauses (and the UK IDTA) as the legal mechanism
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mails-ai
provenance_date: '2026-11-10'
provider_name: mails-ai
provider_slug: mails-ai
slug: mails-ai-privacy-policy
source_date: '2026-11-10'
source_filename: mails-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mails.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mails-ai\naid: mails-ai\nurl: https://mails.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For received mail and texts, we act as your processor.\ndata_categories:\n- category: identifying\n  text: The email address you sign up with, workspace slug + display name, billing identity (handled by Stripe).\n- category: communication\n  text: 'Email you send through your agents and email your agents receive: headers, addresses, subject, body content,\n    extracted reply text, attachments metadata.'\n- category: communication\n  text: 'Texts your connected phone numbers receive: the sender’s\
  \ number, the receiving number, the words, and the\n    carrier’s delivery record.'\n- category: behavioral\n  text: Classifier output. Typed-event fields derived from inbound messages (intent, entities, urgency, injection_score,\n    sender_reputation).\n- category: device\n  text: Audit-log rows for every API call (API-key prefix, action, target, timestamp, IP, user-agent)\npurposes:\n- purpose: Contract performance\n  text: Contract performance (GDPR Art. 6(1)(b)). Account, message, and billing data — we can’t send your email\n    or charge you without them.\n- purpose: Security and abuse prevention\n  text: Legitimate interest (GDPR Art. 6(1)(f)). Operational logs for security, abuse prevention, deliverability\n    protection.\n- purpose: Classifier inference for your agent\n  text: Classifier inference to label inbound for your agent.\n- purpose: Legal obligation\n  text: Legal obligation (GDPR Art. 6(1)(c)). Tax records (Stripe), abuse reports, lawful requests from competent\n  \
  \  authorities.\nretention:\n- scope: Active-account data\n  period: null\n  text: Active-account data is retained for as long as the account is active.\n- scope: Audit-log rows\n  period: 90 days\n  text: target 90 days for Free/Pro, 1 year for Scale\n- scope: Classifier abuse-monitoring logs at OpenAI\n  period: up to 30 days\n  text: it keeps abuse-monitoring logs, which can include the request, for up to 30 days\n- scope: Workspace and message data after closure or erasure\n  period: 30 days\n  text: 'On account closure or erasure request: workspace + message data is deleted within 30 days'\nresidency:\n- region: United States\n  text: Many of our sub-processors are in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, transfers from the EEA / UK rely on the European Commission’s Standard Contractual Clauses\n    (and the UK IDTA) as the legal mechanism\nsubprocessors:\n  url: /sub-processors\n  text: Each vendor’s name, purpose, data category, region (where\
  \ a source names one) and added-at date are at /sub-processors\n    .\ndpa:\n  available: true\n  url: null\n  text: flag this in your DPA request and we’ll provide our SCC-aligned addendum.\ndeletion:\n  route: Self-serve in Settings → Danger zone, or email support@mails.ai\n  text: 'Self-serve: sign in, open Settings → Danger zone, and delete a workspace or your whole account — it is\n    erased at once and you get a deletion receipt.'\nrights:\n- right: Access\n  text: Access (Art. 15). A copy of the personal data we hold about you.\n- right: Rectification\n  text: Rectification (Art. 16). Correction of inaccurate or incomplete data\n- right: Erasure\n  text: Erasure (Art. 17). Deletion of your account and associated data.\n- right: Portability\n  text: Portability (Art. 20). Machine-readable export of your messages, events, agents, and audit-log rows.\n- right: Restrict / object\n  text: Restrict / object (Art. 18, 21). Email us; we’ll honor the request unless we have an overriding\
  \ legitimate\n    interest\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mails-ai/privacy/mails-ai-privacy-policy.yml
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
summary_line: 24 quoted statements, read from mails-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Email
- Infrastructure
- Agents
---
