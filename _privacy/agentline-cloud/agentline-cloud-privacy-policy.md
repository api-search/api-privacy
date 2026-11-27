---
api_specs:
- filename: agentline-cloud-agent-integration-api-openapi.yml
  format: yaml
  label: AgentLine Agent Integration API
  slug: agentline-cloud-agent-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-agent-integration-api-openapi.yml
- filename: agentline-cloud-agent-recharge-api-openapi.yml
  format: yaml
  label: AgentLine Agent Recharge API
  slug: agentline-cloud-agent-recharge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-agent-recharge-api-openapi.yml
- filename: agentline-cloud-agents-api-openapi.yml
  format: yaml
  label: AgentLine Agents API
  slug: agentline-cloud-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-agents-api-openapi.yml
- filename: agentline-cloud-auth-api-openapi.yml
  format: yaml
  label: AgentLine Auth API
  slug: agentline-cloud-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-auth-api-openapi.yml
- filename: agentline-cloud-billing-api-openapi.yml
  format: yaml
  label: AgentLine Billing API
  slug: agentline-cloud-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-billing-api-openapi.yml
- filename: agentline-cloud-calls-api-openapi.yml
  format: yaml
  label: AgentLine Calls API
  slug: agentline-cloud-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-calls-api-openapi.yml
- filename: agentline-cloud-contacts-api-openapi.yml
  format: yaml
  label: AgentLine Contacts API
  slug: agentline-cloud-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-contacts-api-openapi.yml
- filename: agentline-cloud-events-api-openapi.yml
  format: yaml
  label: AgentLine Events API
  slug: agentline-cloud-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-events-api-openapi.yml
- filename: agentline-cloud-feedback-api-openapi.yml
  format: yaml
  label: AgentLine Feedback API
  slug: agentline-cloud-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-feedback-api-openapi.yml
- filename: agentline-cloud-health-api-openapi.yml
  format: yaml
  label: AgentLine Health API
  slug: agentline-cloud-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-health-api-openapi.yml
- filename: agentline-cloud-messages-api-openapi.yml
  format: yaml
  label: AgentLine Messages API
  slug: agentline-cloud-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-messages-api-openapi.yml
- filename: agentline-cloud-numbers-api-openapi.yml
  format: yaml
  label: AgentLine Numbers API
  slug: agentline-cloud-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-numbers-api-openapi.yml
- filename: agentline-cloud-usage-api-openapi.yml
  format: yaml
  label: AgentLine Usage API
  slug: agentline-cloud-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-usage-api-openapi.yml
- filename: agentline-cloud-voice-api-openapi.yml
  format: yaml
  label: AgentLine Voice API
  slug: agentline-cloud-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-voice-api-openapi.yml
- filename: agentline-cloud-webhooks-api-openapi.yml
  format: yaml
  label: AgentLine Webhooks API
  slug: agentline-cloud-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-webhooks-api-openapi.yml
- filename: agentline-cloud-x402-discovery-api-openapi.yml
  format: yaml
  label: AgentLine x402 Discovery API
  slug: agentline-cloud-x402-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-x402-discovery-api-openapi.yml
- filename: agentline-cloud-x402-keyless-api-openapi.yml
  format: yaml
  label: AgentLine x402 Keyless API
  slug: agentline-cloud-x402-keyless-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentline-cloud/openapi/agentline-cloud-x402-keyless-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information includes login identifiers, email, account links, API-key hashes and prefixes, permissions, connected-app grants and support requests.
  - category: communication
    text: Telephony information includes assigned numbers, caller and recipient numbers, timestamps, status, duration, transcripts, per-call instructions and greetings, voice settings, inbound SMS/MMS content and media references, relay context and event payloads.
  - category: financial
    text: Billing records include balances, charges, credit purchases and payment-provider references.
  - category: behavioral
    text: PostHog provides product analytics, error tracking, session replay and server logs across the website and dashboard.
  deletion:
    route: dashboard at agentline.cloud/dashboard/privacy, or email support from the account email; support for account closure and other requests
    text: Signed-in owners can delete history earlier at agentline.cloud/dashboard/privacy, or by emailing support from the account email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate and operate service
    text: We use minimum necessary data to authenticate accounts, route and process communications, fulfill requested connector actions, operate and secure the service, calculate charges, prevent abuse, investigate failures, provide support and meet legal obligations.
  - purpose: no sale or unrelated advertising
    text: We do not sell connector data, use it for unrelated advertising, build unrelated profiles, infer sensitive characteristics for unrelated purposes, or train our own models on it.
  residency:
  - region: United States and other countries
    text: AgentLine is operated from India, and our providers may process information in the United States and other countries.
  retention:
  - period: 90 days
    scope: communication content
    text: Communication content is kept for 90 days so you can review history and transcripts, then cleared automatically.
  - period: null
    scope: call routing and billing metadata
    text: Call routing and billing metadata (numbers, timestamps, duration, status and charges) is kept while your account is active and afterwards for as long as tax, accounting or legal obligations require.
  rights:
  - right: access, correction, deletion, restriction, objection, portability, consent withdrawal, complaint
    text: Depending on your jurisdiction, you may have rights of access, correction, deletion, restriction, objection, portability, consent withdrawal or complaint to a competent authority.
  role:
    text: We are responsible for the processing described here; customers and connected services can have separate responsibilities for their own use.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell connector data, use it for unrelated advertising, build unrelated profiles, infer sensitive characteristics for unrelated purposes, or train our own models on it.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentLine
provenance_date: '2026-11-09'
provider_name: AgentLine
provider_slug: agentline-cloud
slug: agentline-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: agentline-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentline.cloud/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentLine\naid: agentline-cloud\nurl: https://agentline.cloud/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for the processing described here; customers and connected services can have separate\n    responsibilities for their own use.\ndata_categories:\n- category: identifying\n  text: Account information includes login identifiers, email, account links, API-key hashes and prefixes, permissions,\n    connected-app grants and support requests.\n- category: communication\n  text: Telephony information includes assigned numbers, caller and recipient numbers, timestamps,\
  \ status, duration,\n    transcripts, per-call instructions and greetings, voice settings, inbound SMS/MMS content and media references,\n    relay context and event payloads.\n- category: financial\n  text: Billing records include balances, charges, credit purchases and payment-provider references.\n- category: behavioral\n  text: PostHog provides product analytics, error tracking, session replay and server logs across the website and\n    dashboard.\npurposes:\n- purpose: authenticate and operate service\n  text: We use minimum necessary data to authenticate accounts, route and process communications, fulfill requested\n    connector actions, operate and secure the service, calculate charges, prevent abuse, investigate failures, provide\n    support and meet legal obligations.\n- purpose: no sale or unrelated advertising\n  text: We do not sell connector data, use it for unrelated advertising, build unrelated profiles, infer sensitive\n    characteristics for unrelated purposes, or train\
  \ our own models on it.\nretention:\n- scope: communication content\n  period: 90 days\n  text: Communication content is kept for 90 days so you can review history and transcripts, then cleared automatically.\n- scope: call routing and billing metadata\n  period: null\n  text: Call routing and billing metadata (numbers, timestamps, duration, status and charges) is kept while your\n    account is active and afterwards for as long as tax, accounting or legal obligations require.\nresidency:\n- region: United States and other countries\n  text: AgentLine is operated from India, and our providers may process information in the United States and other\n    countries.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard at agentline.cloud/dashboard/privacy, or email support from the account email; support for account\n    closure and other requests\n  text: Signed-in owners can delete history earlier at agentline.cloud/dashboard/privacy,\
  \ or by emailing support\n    from the account email.\nrights:\n- right: access, correction, deletion, restriction, objection, portability, consent withdrawal, complaint\n  text: Depending on your jurisdiction, you may have rights of access, correction, deletion, restriction, objection,\n    portability, consent withdrawal or complaint to a competent authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell connector data, use it for unrelated advertising, build unrelated profiles, infer sensitive\n    characteristics for unrelated purposes, or train our own models on it.\n"
source_yaml_url: https://artifacts.apis.io/agentline-cloud/privacy/agentline-cloud-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from AgentLine's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Telephony
- Voice
- SMS
- Agents
---
