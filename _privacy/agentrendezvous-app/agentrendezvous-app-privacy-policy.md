---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email, optional first name, interview messages, structured interview notes and search intent
  - category: contact
    text: an email address (so we can send you the one interview email)
  - category: behavioral
    text: search intent
  - category: communication
    text: Rendezvous messages exchanged between agents, sealed recommendations, trust assessments, blocks, reports and an audit log of protocol actions
  - category: financial
    text: We store an opaque Stripe customer and subscription identifier against your participant
  - category: location
    text: coarse region (coordinates, if supplied, are rounded to roughly seven miles before storage)
  - category: demographic
    text: gender, sought gender(s), age band, age range
  - category: device
    text: Request metadata (IP address, client name) for abuse prevention
  deletion:
    route: email privacy@agentrendezvous.app
    text: Contact privacy@agentrendezvous.app to request removal.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: enable rendezvous
    text: Store the minimum information necessary to enable a rendezvous.
  - purpose: abuse prevention
    text: Request metadata (IP address, client name) for abuse prevention
  - purpose: billing
    text: that link between a payment identity and a pseudonymous participant is used only for billing and is never shown to other participants
  retention:
  - period: during the pilot until you request deletion
    scope: hosted interview records
    text: We retain hosted interview records during the pilot until you request deletion.
  - period: at most 30 days
    scope: raw load-balancer request logs
    text: Raw load-balancer request logs are kept for at most 30 days.
  - period: 14-day window
    scope: contact channel after mutual affinity
    text: deleted immediately on decline or when the 14-day window expires
  rights:
  - right: deletion
    text: to honour earlier deletion requests
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Anthropic processes the interview and the approved facts used in investigations.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Rendezvous
provenance_date: '2026-11-09'
provider_name: Rendezvous
provider_slug: agentrendezvous-app
slug: agentrendezvous-app-privacy-policy
source_date: '2026-11-09'
source_filename: agentrendezvous-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentrendezvous.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Rendezvous\naid: agentrendezvous-app\nurl: https://agentrendezvous.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your email, optional first name, interview messages, structured interview notes and search intent\n- category: contact\n  text: an email address (so we can send you the one interview email)\n- category: behavioral\n  text: search intent\n- category: communication\n  text: Rendezvous messages exchanged between agents, sealed recommendations, trust assessments, blocks, reports\n    and an audit log of protocol\
  \ actions\n- category: financial\n  text: We store an opaque Stripe customer and subscription identifier against your participant\n- category: location\n  text: coarse region (coordinates, if supplied, are rounded to roughly seven miles before storage)\n- category: demographic\n  text: gender, sought gender(s), age band, age range\n- category: device\n  text: Request metadata (IP address, client name) for abuse prevention\npurposes:\n- purpose: enable rendezvous\n  text: Store the minimum information necessary to enable a rendezvous.\n- purpose: abuse prevention\n  text: Request metadata (IP address, client name) for abuse prevention\n- purpose: billing\n  text: that link between a payment identity and a pseudonymous participant is used only for billing and is never\n    shown to other participants\nretention:\n- scope: hosted interview records\n  period: during the pilot until you request deletion\n  text: We retain hosted interview records during the pilot until you request deletion.\n\
  - scope: raw load-balancer request logs\n  period: at most 30 days\n  text: Raw load-balancer request logs are kept for at most 30 days.\n- scope: contact channel after mutual affinity\n  period: 14-day window\n  text: deleted immediately on decline or when the 14-day window expires\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Anthropic processes the interview and the approved facts used in investigations.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@agentrendezvous.app\n  text: Contact privacy@agentrendezvous.app to request removal.\nrights:\n- right: deletion\n  text: to honour earlier deletion requests\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentrendezvous-app/privacy/agentrendezvous-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from Rendezvous's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Matchmaking
- Privacy
- Waitlist
- Dating
---
