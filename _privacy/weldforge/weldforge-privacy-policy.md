---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Intake form submissions: email, build description, optional voice recording.'
  - category: communication
    text: 'Chatbot conversations: messages typed into the support chatbot widget; forwarded to Anthropic for response generation.'
  - category: device
    text: 'Server logs: standard request metadata (IP, user agent, timestamp, path) retained by Vercel for ~30 days.'
  - category: communication
    text: 'Email correspondence: messages to support@weldforge.ai, max@weldforge.ai, etc.'
  deletion:
    route: Email max@weldforge.ai with subject line “Privacy Request.”
    text: Email max@weldforge.ai with subject line “Privacy Request.”
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to intake submissions
    text: Respond to intake submissions with a scope and pricing proposal
  - purpose: Operate support chatbot
    text: Operate the support chatbot via Anthropic Claude
  - purpose: Run integrations
    text: Run the integrations we build on your behalf in our cloud
  - purpose: Operational notifications
    text: Send proactive overage alerts and operational notifications
  - purpose: Security and debugging
    text: Debug the platform, prevent abuse, meet hosting security obligations
  retention:
  - period: disposition + 7 years
    scope: Intake submissions
    text: 'Intake submissions: retained in email until disposition + 7 years (tax / business records retention).'
  - period: typically 30 days
    scope: Chatbot messages
    text: 'Chatbot messages: ephemeral; Anthropic API default logging applies (typically 30 days).'
  - period: ~30 days
    scope: Server logs
    text: 'Server logs: ~30 days at the hosting layer.'
  - period: null
    scope: Integration data in flight
    text: 'Integration data in flight: not persisted by Weldforge beyond what your specific integration requires for its operation; configured per Subscription Agreement.'
  rights:
  - right: access
    text: California, EU, and UK residents have the right to access, delete, correct, and object to processing of their personal information.
  - right: delete
    text: California, EU, and UK residents have the right to access, delete, correct, and object to processing of their personal information.
  - right: correct
    text: California, EU, and UK residents have the right to access, delete, correct, and object to processing of their personal information.
  - right: object
    text: California, EU, and UK residents have the right to access, delete, correct, and object to processing of their personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it with third parties for advertising.
  subprocessors:
    text: 4. Subprocessors Vercel (web hosting / edge) - vercel.com/legal/privacy-policy AWS (integration runtime hosting) - aws.amazon.com/privacy Anthropic (chatbot + AI-augmented build) - anthropic.com/legal/privacy Google Workspace (email at weldforge.ai inboxes) - policies.google.com/privacy Slack (customer support channels) - slack.com/trust/privacy
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Green Dolphin Software
provenance_date: '2026-11-10'
provider_name: Green Dolphin Software
provider_slug: weldforge
slug: weldforge-privacy-policy
source_date: '2026-11-10'
source_filename: weldforge-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://weldforge.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Green Dolphin Software\naid: weldforge\nurl: https://weldforge.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Intake form submissions: email, build description, optional voice recording.'\n- category: communication\n  text: 'Chatbot conversations: messages typed into the support chatbot widget; forwarded to Anthropic for response\n    generation.'\n- category: device\n  text: 'Server logs: standard request metadata (IP, user agent, timestamp, path) retained by Vercel for ~30 days.'\n- category: communication\n  text: 'Email correspondence:\
  \ messages to support@weldforge.ai, max@weldforge.ai, etc.'\npurposes:\n- purpose: Respond to intake submissions\n  text: Respond to intake submissions with a scope and pricing proposal\n- purpose: Operate support chatbot\n  text: Operate the support chatbot via Anthropic Claude\n- purpose: Run integrations\n  text: Run the integrations we build on your behalf in our cloud\n- purpose: Operational notifications\n  text: Send proactive overage alerts and operational notifications\n- purpose: Security and debugging\n  text: Debug the platform, prevent abuse, meet hosting security obligations\nretention:\n- scope: Intake submissions\n  period: disposition + 7 years\n  text: 'Intake submissions: retained in email until disposition + 7 years (tax / business records retention).'\n- scope: Chatbot messages\n  period: typically 30 days\n  text: 'Chatbot messages: ephemeral; Anthropic API default logging applies (typically 30 days).'\n- scope: Server logs\n  period: ~30 days\n  text: 'Server logs:\
  \ ~30 days at the hosting layer.'\n- scope: Integration data in flight\n  period: null\n  text: 'Integration data in flight: not persisted by Weldforge beyond what your specific integration requires for\n    its operation; configured per Subscription Agreement.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 4. Subprocessors Vercel (web hosting / edge) - vercel.com/legal/privacy-policy AWS (integration runtime\n    hosting) - aws.amazon.com/privacy Anthropic (chatbot + AI-augmented build) - anthropic.com/legal/privacy Google\n    Workspace (email at weldforge.ai inboxes) - policies.google.com/privacy Slack (customer support channels) -\n    slack.com/trust/privacy\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email max@weldforge.ai with subject line “Privacy Request.”\n  text: Email max@weldforge.ai with subject line “Privacy Request.”\nrights:\n- right: access\n  text: California, EU, and UK residents have the right to access, delete, correct,\
  \ and object to processing of\n    their personal information.\n- right: delete\n  text: California, EU, and UK residents have the right to access, delete, correct, and object to processing of\n    their personal information.\n- right: correct\n  text: California, EU, and UK residents have the right to access, delete, correct, and object to processing of\n    their personal information.\n- right: object\n  text: California, EU, and UK residents have the right to access, delete, correct, and object to processing of\n    their personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it with third parties for advertising.\n"
source_yaml_url: https://artifacts.apis.io/weldforge/privacy/weldforge-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Green Dolphin Software's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- No-Code
- Software-as-a-Service
- Automation
- Platform
---
