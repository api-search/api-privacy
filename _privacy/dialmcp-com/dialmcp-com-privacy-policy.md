---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your phone number, verified by SMS code — it is your identity and your caller ID.
  - category: identifying
    text: You also provide a display name at signup, which the assistant uses to introduce itself
  - category: communication
    text: a full turn-by-turn transcript , and an audio recording of the call.
  - category: location
    text: the destination number and callee name
  - category: behavioral
    text: signups, logins, calls placed and their outcomes, and page interactions.
  - category: device
    text: IP addresses are used transiently to rate-limit signups and the public opt-out page; we do not store them in our database.
  deletion:
    route: Email support@dialmcp.com to delete your account and its calls, transcripts, and recordings.
    text: 'Delete : email support@dialmcp.com to delete your account and its calls, transcripts, and recordings.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service : place calls, stream the conversation, and return transcripts, recordings, and results to your AI client.'
  - purpose: Safety and compliance
    text: 'Safety and compliance : screening objectives before dialing, enforcing rate limits and calling hours, honoring the do-not-call list, and maintaining the per-call compliance log.'
  - purpose: Operations
    text: 'Operations : aggregate metrics (call counts, latency, cost) and structured logs to run and improve the service.'
  - purpose: Product analytics and fraud detection
    text: to understand how the service is used and to detect fraud and abuse
  residency:
  - region: United States
    text: Your data is stored on Cloudflare infrastructure (database, recording storage, hosting) in the United States.
  retention:
  - period: 90 days after the call
    scope: Recordings
    text: 'Recordings : deleted automatically 90 days after the call.'
  - period: up to 5 years after a call
    scope: Compliance logs
    text: compliance logs may be retained up to 5 years after a call, consistent with TCPA consent-record norms, even after account deletion
  - period: indefinitely
    scope: Do-not-call entries
    text: 'Do-not-call entries : retained indefinitely — deletion would defeat their purpose.'
  - period: null
    scope: Transcripts and call metadata
    text: 'Transcripts, results, call metadata, compliance logs : retained while your account exists'
  rights:
  - right: Access
    text: 'Access : your AI client can retrieve all of your calls, transcripts, and recordings at any time via the connector.'
  - right: Delete
    text: 'Delete : email support@dialmcp.com to delete your account and its calls, transcripts, and recordings.'
  - right: Correct and non-discrimination (where applicable)
    text: you may have additional rights to access, delete, or correct personal information, and to non-discrimination for exercising them.
  - right: Revoke connector access
    text: 'Revoke : disconnecting the connector from your AI client revokes its token immediately.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, do not use call content for advertising, and do not use your call content to train AI models.
  subprocessors:
    text: 'To operate each call, data is shared with: Processor What they receive Purpose Telnyx'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DialMCP
provenance_date: '2026-11-09'
provider_name: DialMCP
provider_slug: dialmcp-com
slug: dialmcp-com-privacy-policy
source_date: '2026-11-09'
source_filename: dialmcp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dialmcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DialMCP\naid: dialmcp-com\nurl: https://dialmcp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your phone number, verified by SMS code — it is your identity and your caller ID.\n- category: identifying\n  text: You also provide a display name at signup, which the assistant uses to introduce itself\n- category: communication\n  text: a full turn-by-turn transcript , and an audio recording of the call.\n- category: location\n  text: the destination number and callee name\n- category: behavioral\n  text: signups, logins, calls\
  \ placed and their outcomes, and page interactions.\n- category: device\n  text: IP addresses are used transiently to rate-limit signups and the public opt-out page; we do not store them\n    in our database.\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service : place calls, stream the conversation, and return transcripts, recordings, and\n    results to your AI client.'\n- purpose: Safety and compliance\n  text: 'Safety and compliance : screening objectives before dialing, enforcing rate limits and calling hours, honoring\n    the do-not-call list, and maintaining the per-call compliance log.'\n- purpose: Operations\n  text: 'Operations : aggregate metrics (call counts, latency, cost) and structured logs to run and improve the\n    service.'\n- purpose: Product analytics and fraud detection\n  text: to understand how the service is used and to detect fraud and abuse\nretention:\n- scope: Recordings\n  period: 90 days after the call\n  text: 'Recordings : deleted\
  \ automatically 90 days after the call.'\n- scope: Compliance logs\n  period: up to 5 years after a call\n  text: compliance logs may be retained up to 5 years after a call, consistent with TCPA consent-record norms, even\n    after account deletion\n- scope: Do-not-call entries\n  period: indefinitely\n  text: 'Do-not-call entries : retained indefinitely — deletion would defeat their purpose.'\n- scope: Transcripts and call metadata\n  period: null\n  text: 'Transcripts, results, call metadata, compliance logs : retained while your account exists'\nresidency:\n- region: United States\n  text: Your data is stored on Cloudflare infrastructure (database, recording storage, hosting) in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'To operate each call, data is shared with: Processor What they receive Purpose Telnyx'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@dialmcp.com to delete your account and its calls, transcripts,\
  \ and recordings.\n  text: 'Delete : email support@dialmcp.com to delete your account and its calls, transcripts, and recordings.'\nrights:\n- right: Access\n  text: 'Access : your AI client can retrieve all of your calls, transcripts, and recordings at any time via the\n    connector.'\n- right: Delete\n  text: 'Delete : email support@dialmcp.com to delete your account and its calls, transcripts, and recordings.'\n- right: Correct and non-discrimination (where applicable)\n  text: you may have additional rights to access, delete, or correct personal information, and to non-discrimination\n    for exercising them.\n- right: Revoke connector access\n  text: 'Revoke : disconnecting the connector from your AI client revokes its token immediately.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, do not use call content for advertising, and do not use your call content\n    to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/dialmcp-com/privacy/dialmcp-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from DialMCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Phone Calls
- Voice AI
- Telephony
---
