---
api_specs:
- filename: agentboxd-com-agent-network-api-openapi.yml
  format: yaml
  label: agentboxd-com Agent network API
  slug: agentboxd-com-agent-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-agent-network-api-openapi.yml
- filename: agentboxd-com-agent-self-signup-api-openapi.yml
  format: yaml
  label: agentboxd-com Agent self-signup API
  slug: agentboxd-com-agent-self-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-agent-self-signup-api-openapi.yml
- filename: agentboxd-com-contacts-api-openapi.yml
  format: yaml
  label: agentboxd-com Contacts API
  slug: agentboxd-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-contacts-api-openapi.yml
- filename: agentboxd-com-domains-api-openapi.yml
  format: yaml
  label: agentboxd-com Domains API
  slug: agentboxd-com-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-domains-api-openapi.yml
- filename: agentboxd-com-drafts-api-openapi.yml
  format: yaml
  label: agentboxd-com Drafts API
  slug: agentboxd-com-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-drafts-api-openapi.yml
- filename: agentboxd-com-events-api-openapi.yml
  format: yaml
  label: agentboxd-com Events API
  slug: agentboxd-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-events-api-openapi.yml
- filename: agentboxd-com-inboxes-api-openapi.yml
  format: yaml
  label: agentboxd-com Inboxes API
  slug: agentboxd-com-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-inboxes-api-openapi.yml
- filename: agentboxd-com-knowledge-api-openapi.yml
  format: yaml
  label: agentboxd-com Knowledge API
  slug: agentboxd-com-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-knowledge-api-openapi.yml
- filename: agentboxd-com-lists-api-openapi.yml
  format: yaml
  label: agentboxd-com Lists API
  slug: agentboxd-com-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-lists-api-openapi.yml
- filename: agentboxd-com-messages-api-openapi.yml
  format: yaml
  label: agentboxd-com Messages API
  slug: agentboxd-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-messages-api-openapi.yml
- filename: agentboxd-com-metrics-api-openapi.yml
  format: yaml
  label: agentboxd-com Metrics API
  slug: agentboxd-com-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-metrics-api-openapi.yml
- filename: agentboxd-com-other-api-openapi.yml
  format: yaml
  label: agentboxd-com Other API
  slug: agentboxd-com-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-other-api-openapi.yml
- filename: agentboxd-com-search-api-openapi.yml
  format: yaml
  label: agentboxd-com Search API
  slug: agentboxd-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-search-api-openapi.yml
- filename: agentboxd-com-shakehand-api-openapi.yml
  format: yaml
  label: agentboxd-com Shakehand API
  slug: agentboxd-com-shakehand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-shakehand-api-openapi.yml
- filename: agentboxd-com-threads-api-openapi.yml
  format: yaml
  label: agentboxd-com Threads API
  slug: agentboxd-com-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-threads-api-openapi.yml
- filename: agentboxd-com-trust-api-openapi.yml
  format: yaml
  label: agentboxd-com Trust API
  slug: agentboxd-com-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-trust-api-openapi.yml
- filename: agentboxd-com-webhooks-api-openapi.yml
  format: yaml
  label: agentboxd-com Webhooks API
  slug: agentboxd-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentboxd-com/openapi/agentboxd-com-webhooks-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Address, name, the notes and metadata you or your agent add, labels, message counts and dates.
  - category: identifying
    text: Your email address, name, workspace name and membership.
  - category: communication
    text: The original message (MIME), its text, HTML, extracted_text, headers, labels and AI scores.
  - category: location
    text: your country (looked up from your IP address with a database on our own server)
  - category: device
    text: whether you use a phone, tablet or computer
  - category: financial
    text: Controller SynaptrixAI Ltd is the controller of your account and billing data
  deletion:
    route: Delete the inbox or workspace in the dashboard, or write to support@agentboxd.com
    text: To have the stored mail of a deleted inbox removed as well, write to support@agentboxd.com .
  dpa:
    available: true
    text: For a data processing agreement, see DPA or write to hello@agentboxd.com .
    url: DPA
  purposes:
  - purpose: Categorisation by AI processor
    text: Categorisation
  - purpose: Reply drafts and structured extraction
    text: Reply drafts and structured extraction
  - purpose: Website visit counts
    text: We use the counts only to see which pages and posts people find useful
  retention:
  - period: 14 days
    scope: Backups
    text: each one is kept for 14 days
  - period: 400 days
    scope: Website visits
    text: delete them after 400 days
  - period: 7 days
    scope: Unconfirmed sub-processor notice requests
    text: An unconfirmed request is deleted after 7 days.
  - period: 30 days after the season ends
    scope: Game attack emails
    text: kept until 30 days after the season ends, then deleted
  rights:
  - right: Erasure of early-access email
    text: we delete the email when you ask
  role:
    text: For the mail, contacts, knowledge and other data you and your agents process through Agentboxd, you are the controller and SynaptrixAI Ltd acts as your processor, under the DPA .
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The formal list, with change notices, is on Sub-processors .
    url: Sub-processors
  transfers:
  - mechanism: other
    text: JEV (TypeSafe AI, US), once per inbound message
  - mechanism: other
    text: To DeepSeek (China), only when someone asks for a reply draft
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agentboxd-com
provenance_date: '2026-11-09'
provider_name: agentboxd-com
provider_slug: agentboxd-com
slug: agentboxd-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentboxd-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentboxd.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agentboxd-com\naid: agentboxd-com\nurl: https://agentboxd.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For the mail, contacts, knowledge and other data you and your agents process through Agentboxd, you are\n    the controller and SynaptrixAI Ltd acts as your processor, under the DPA .\ndata_categories:\n- category: contact\n  text: Address, name, the notes and metadata you or your agent add, labels, message counts and dates.\n- category: identifying\n  text: Your email address, name, workspace name and membership.\n- category: communication\n  text: The original message (MIME), its\
  \ text, HTML, extracted_text, headers, labels and AI scores.\n- category: location\n  text: your country (looked up from your IP address with a database on our own server)\n- category: device\n  text: whether you use a phone, tablet or computer\n- category: financial\n  text: Controller SynaptrixAI Ltd is the controller of your account and billing data\npurposes:\n- purpose: Categorisation by AI processor\n  text: Categorisation\n- purpose: Reply drafts and structured extraction\n  text: Reply drafts and structured extraction\n- purpose: Website visit counts\n  text: We use the counts only to see which pages and posts people find useful\nretention:\n- scope: Backups\n  period: 14 days\n  text: each one is kept for 14 days\n- scope: Website visits\n  period: 400 days\n  text: delete them after 400 days\n- scope: Unconfirmed sub-processor notice requests\n  period: 7 days\n  text: An unconfirmed request is deleted after 7 days.\n- scope: Game attack emails\n  period: 30 days after the season\
  \ ends\n  text: kept until 30 days after the season ends, then deleted\nresidency: []\ntransfers:\n- mechanism: other\n  text: JEV (TypeSafe AI, US), once per inbound message\n- mechanism: other\n  text: To DeepSeek (China), only when someone asks for a reply draft\nsubprocessors:\n  url: Sub-processors\n  text: The formal list, with change notices, is on Sub-processors .\ndpa:\n  available: true\n  url: DPA\n  text: For a data processing agreement, see DPA or write to hello@agentboxd.com .\ndeletion:\n  route: Delete the inbox or workspace in the dashboard, or write to support@agentboxd.com\n  text: To have the stored mail of a deleted inbox removed as well, write to support@agentboxd.com .\nrights:\n- right: Erasure of early-access email\n  text: we delete the email when you ask\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentboxd-com/privacy/agentboxd-com-privacy-policy.yml
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
summary_line: 20 quoted statements, read from agentboxd-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Email
- Messaging
- Beta
---
