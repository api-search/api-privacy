---
api_specs:
- filename: agentdrive-sh-openapi-generated.yml
  format: yaml
  label: AgentDrive API
  slug: agentdrive-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrive-sh/openapi/_ae-authored/agentdrive-sh-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (when you sign in with a magic-link or OAuth provider), name and avatar provided by Google or GitHub during OAuth, organization name.
  - category: financial
    text: We store a Stripe customer id; Stripe stores the card details. We never see card numbers.
  - category: device
    text: Request logs (IP, user-agent, request id, timestamp, response status), API key usage timestamps.
  - category: other
    text: Files your agents write to AgentDrive (content + metadata), share tokens you create, comments, run logs
  deletion:
    route: Settings
    text: You can delete your account at any time via Settings; deletion is irreversible after 30 days.
  dpa:
    available: true
    text: is maintained in our Data Processing Addendum
    url: null
  purposes:
  - purpose: Operate the Service
    text: Files are stored to be served back to your agents.
  - purpose: Semantic search
    text: The text is not retained by the embedding model.
  - purpose: Email magic-links
    text: Sign-in codes are sent from noreply@agentdrive.sh and expire in 10 minutes.
  - purpose: Improve the Service
    text: Aggregated usage statistics (e.g., total artifacts, embeddings per month) inform capacity planning.
  residency:
  - region: BYO-bucket file content region
    text: On Team and Enterprise, BYO-bucket lets you select the region for file content.
  - region: Whole service
    text: so an EU bucket does not provide EU-only residency for the whole service.
  retention:
  - period: 30 days after deletion request
    scope: Account data
    text: retained while your account is active and for 30 days after deletion request, then purged.
  - period: while your plan is active
    scope: Agent data
    text: 'Agent data: retained while your plan is active.'
  - period: 180 days of inactivity
    scope: Free tier inactive orgs
    text: data is deleted at 180 days of inactivity unless you upgrade or extend.
  - period: 30 days
    scope: Logs
    text: 'Logs: 30 days, then purged.'
  rights:
  - right: Access, correct, delete, port, restrict
    text: You have the right to access, correct, delete, port, or restrict processing of your personal data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your data with any other third party.
  subprocessors:
    text: The current list — including cloud infrastructure, payments, and OAuth identity — is maintained in our Data Processing Addendum
    url: null
  transfers:
  - mechanism: other
    text: Data may be processed in any country where they operate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentDrive
provenance_date: '2026-11-09'
provider_name: AgentDrive
provider_slug: agentdrive-sh
slug: agentdrive-sh-privacy-policy
source_date: '2026-11-09'
source_filename: agentdrive-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentdrive.sh/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentDrive\naid: agentdrive-sh\nurl: https://agentdrive.sh/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (when you sign in with a magic-link or OAuth provider), name and avatar provided by Google\n    or GitHub during OAuth, organization name.\n- category: financial\n  text: We store a Stripe customer id; Stripe stores the card details. We never see card numbers.\n- category: device\n  text: Request logs (IP, user-agent, request id, timestamp, response status), API key usage timestamps.\n- category: other\n\
  \  text: Files your agents write to AgentDrive (content + metadata), share tokens you create, comments, run logs\npurposes:\n- purpose: Operate the Service\n  text: Files are stored to be served back to your agents.\n- purpose: Semantic search\n  text: The text is not retained by the embedding model.\n- purpose: Email magic-links\n  text: Sign-in codes are sent from noreply@agentdrive.sh and expire in 10 minutes.\n- purpose: Improve the Service\n  text: Aggregated usage statistics (e.g., total artifacts, embeddings per month) inform capacity planning.\nretention:\n- scope: Account data\n  period: 30 days after deletion request\n  text: retained while your account is active and for 30 days after deletion request, then purged.\n- scope: Agent data\n  period: while your plan is active\n  text: 'Agent data: retained while your plan is active.'\n- scope: Free tier inactive orgs\n  period: 180 days of inactivity\n  text: data is deleted at 180 days of inactivity unless you upgrade or extend.\n\
  - scope: Logs\n  period: 30 days\n  text: 'Logs: 30 days, then purged.'\nresidency:\n- region: BYO-bucket file content region\n  text: On Team and Enterprise, BYO-bucket lets you select the region for file content.\n- region: Whole service\n  text: so an EU bucket does not provide EU-only residency for the whole service.\ntransfers:\n- mechanism: other\n  text: Data may be processed in any country where they operate.\nsubprocessors:\n  url: null\n  text: The current list — including cloud infrastructure, payments, and OAuth identity — is maintained in our Data\n    Processing Addendum\ndpa:\n  available: true\n  url: null\n  text: is maintained in our Data Processing Addendum\ndeletion:\n  route: Settings\n  text: You can delete your account at any time via Settings; deletion is irreversible after 30 days.\nrights:\n- right: Access, correct, delete, port, restrict\n  text: You have the right to access, correct, delete, port, or restrict processing of your personal data.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell, rent, or share your data with any other third party.\n"
source_yaml_url: https://artifacts.apis.io/agentdrive-sh/privacy/agentdrive-sh-privacy-policy.yml
stated_fields:
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
summary_line: 20 quoted statements, read from AgentDrive's own page on 2026-11-09.
synthetic: false
tags:
- AgentDrive
- Artificial Intelligence
- Multi-Agent
- Workspace
- Memory
- MCP
---
