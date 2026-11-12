---
api_specs:
- filename: coordigent-com-agents-api-openapi.yml
  format: yaml
  label: Coordigent Agents API
  slug: coordigent-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-agents-api-openapi.yml
- filename: coordigent-com-events-api-openapi.yml
  format: yaml
  label: Coordigent Events API
  slug: coordigent-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-events-api-openapi.yml
- filename: coordigent-com-items-api-openapi.yml
  format: yaml
  label: Coordigent Items API
  slug: coordigent-com-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-items-api-openapi.yml
- filename: coordigent-com-me-api-openapi.yml
  format: yaml
  label: Coordigent Me API
  slug: coordigent-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-me-api-openapi.yml
- filename: coordigent-com-projects-api-openapi.yml
  format: yaml
  label: Coordigent Projects API
  slug: coordigent-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-projects-api-openapi.yml
- filename: coordigent-com-stream-api-openapi.yml
  format: yaml
  label: Coordigent Stream API
  slug: coordigent-com-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-stream-api-openapi.yml
- filename: coordigent-com-threads-api-openapi.yml
  format: yaml
  label: Coordigent Threads API
  slug: coordigent-com-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-threads-api-openapi.yml
- filename: coordigent-com-webhooks-api-openapi.yml
  format: yaml
  label: Coordigent Webhooks API
  slug: coordigent-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-webhooks-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: your name, your email address, and the authentication provider you signed in with.'
  - category: device
    text: the machine name your agent reports
  - category: behavioral
    text: 'Prompts: the full text you send your agent, up to 100 KB each.'
  - category: professional
    text: 'File activity: the paths your agent read, edited or created, relative to the repository, and diffs of its edits up to 20 KB each.'
  - category: financial
    text: Card details never reach our servers. Payment is handled entirely by Stripe's hosted pages.
  deletion:
    route: email hi@coordigent.com for manual account deletion; project owners can delete a repository with coord repo remove --delete-history
    text: There is not yet a self-serve way to delete your account. If you want your account or any of your data removed, email hi@coordigent.com and we will do it by hand.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: coordinating coding agents on the same repository
    text: Coordigent coordinates AI coding agents working on the same repository. To do that it records what those agents did.
  - purpose: sign-in emails
    text: Resend — sign-in emails, and messages sent through our contact form.
  - purpose: payments
    text: Stripe — payments. Receives your email address, your project's name and billing details; we never see your card.
  residency:
  - region: United States
    text: Production data is stored in the United States, in the Central US region.
  retention:
  - period: 90 days
    scope: messages between agents including pull request feedback
    text: Messages between agents, including pull request feedback, are deleted 90 days after they were sent.
  - period: 90 days
    scope: handoff summaries, session history and work summaries
    text: Handoff summaries, the session history built from them and work summaries are deleted 90 days after they were written.
  - period: 365 days
    scope: memories split from session history
    text: Memories split from that session history (a decision, a finished change, a finding or a loose end, one line each) are kept for 365 days.
  - period: null
    scope: session records, file activity and prompts
    text: Coordigent does not delete session records, file activity or prompts on a schedule.
  rights:
  - right: access, correct, export or delete
    text: you may have the right to access, correct, export or delete the personal data we hold about you, and to object to how we process it.
  role:
    text: Coordigent is operated by Coordigent, Inc., a Delaware corporation, which is responsible for the data described here.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Coordigent uses these services. Each receives only what it needs to do its job, and processes it under its own API or service terms.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coordigent
provenance_date: '2026-11-09'
provider_name: Coordigent
provider_slug: coordigent-com
slug: coordigent-com-privacy-policy
source_date: '2026-11-09'
source_filename: coordigent-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coordigent.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coordigent\naid: coordigent-com\nurl: https://coordigent.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Coordigent is operated by Coordigent, Inc., a Delaware corporation, which is responsible for the data described\n    here.\ndata_categories:\n- category: identifying\n  text: 'Account details: your name, your email address, and the authentication provider you signed in with.'\n- category: device\n  text: the machine name your agent reports\n- category: behavioral\n  text: 'Prompts: the full text you send your agent, up to 100 KB each.'\n- category: professional\n  text: 'File\
  \ activity: the paths your agent read, edited or created, relative to the repository, and diffs of its\n    edits up to 20 KB each.'\n- category: financial\n  text: Card details never reach our servers. Payment is handled entirely by Stripe's hosted pages.\npurposes:\n- purpose: coordinating coding agents on the same repository\n  text: Coordigent coordinates AI coding agents working on the same repository. To do that it records what those\n    agents did.\n- purpose: sign-in emails\n  text: Resend — sign-in emails, and messages sent through our contact form.\n- purpose: payments\n  text: Stripe — payments. Receives your email address, your project's name and billing details; we never see your\n    card.\nretention:\n- scope: messages between agents including pull request feedback\n  period: 90 days\n  text: Messages between agents, including pull request feedback, are deleted 90 days after they were sent.\n- scope: handoff summaries, session history and work summaries\n  period: 90 days\n\
  \  text: Handoff summaries, the session history built from them and work summaries are deleted 90 days after they\n    were written.\n- scope: memories split from session history\n  period: 365 days\n  text: Memories split from that session history (a decision, a finished change, a finding or a loose end, one line\n    each) are kept for 365 days.\n- scope: session records, file activity and prompts\n  period: null\n  text: Coordigent does not delete session records, file activity or prompts on a schedule.\nresidency:\n- region: United States\n  text: Production data is stored in the United States, in the Central US region.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Coordigent uses these services. Each receives only what it needs to do its job, and processes it under its\n    own API or service terms.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hi@coordigent.com for manual account deletion; project owners can delete a repository with coord\n\
  \    repo remove --delete-history\n  text: There is not yet a self-serve way to delete your account. If you want your account or any of your data removed,\n    email hi@coordigent.com and we will do it by hand.\nrights:\n- right: access, correct, export or delete\n  text: you may have the right to access, correct, export or delete the personal data we hold about you, and to\n    object to how we process it.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coordigent-com/privacy/coordigent-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from Coordigent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Coding Agents
- MCP
- Developer Tools
- Agent Coordination
- CLI
---
