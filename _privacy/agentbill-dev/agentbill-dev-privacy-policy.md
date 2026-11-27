---
api_specs:
- filename: agentbill-dev-openapi-generated.yml
  format: yaml
  label: AgentBill API
  slug: agentbill-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbill-dev/openapi/_ae-authored/agentbill-dev-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address, and, if you give them, a name, a use case and a stack
  - category: identifying
    text: the account id that provider gives us for you and the verified address it returns
  - category: device
    text: the address it was last used from, and each network it has been used from (for IPv6 the /64, for IPv4 the address itself)
  - category: behavioral
    text: which way in you picked, whether you named a client, and which of its samples or your key's lines you pressed Copy on
  - category: communication
    text: ours logs each request with the IP address it came from, the path (never the query string, and never a sign-in or recovery token) and the time
  deletion:
    route: email hello@agentbill.dev
    text: Email hello@agentbill.dev from the address on the account and we delete the account and everything stored under it
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run account and sign-in
    text: Used to run your account, sign you in and email you (section 5).
  - purpose: measure ads
    text: to measure our ads (page views and sign-ups)
  - purpose: service operation
    text: 'This is the service itself: the ceilings, the console and your usage.'
  retention:
  - period: 90 days
    scope: revoked or expired API keys
    text: deleted 90 days after the day it was revoked or expired
  - period: 180 days
    scope: preflight refusals and snapshots
    text: deleted 180 days after the refusal
  - period: 400 days
    scope: usage record metadata
    text: cleared 400 days after the record
  - period: 180 days
    scope: marketing page events
    text: deleted 180 days after the event
  - period: null
    scope: account data
    text: Kept while your account exists, and deleted with it
  rights:
  - right: copy of data
    text: You can also ask for a copy of your data or to correct it, the same way.
  - right: correction
    text: You can also ask for a copy of your data or to correct it, the same way.
  - right: GDPR rights for EU/EEA or UK
    text: If you are in the EU/EEA or UK, these rights are backed by the GDPR.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Fly.io hosts the service and keeps its request log. Supabase hosts the database. Resend sends the emails in section 5, and receives mail sent to hello@agentbill.dev
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentBill
provenance_date: '2026-11-09'
provider_name: AgentBill
provider_slug: agentbill-dev
slug: agentbill-dev-privacy-policy
source_date: '2026-11-09'
source_filename: agentbill-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentbill.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentBill\naid: agentbill-dev\nurl: https://agentbill.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your email address, and, if you give them, a name, a use case and a stack\n- category: identifying\n  text: the account id that provider gives us for you and the verified address it returns\n- category: device\n  text: the address it was last used from, and each network it has been used from (for IPv6 the /64, for IPv4 the\n    address itself)\n- category: behavioral\n  text: which way in you picked, whether you named a client,\
  \ and which of its samples or your key's lines you pressed\n    Copy on\n- category: communication\n  text: ours logs each request with the IP address it came from, the path (never the query string, and never a sign-in\n    or recovery token) and the time\npurposes:\n- purpose: run account and sign-in\n  text: Used to run your account, sign you in and email you (section 5).\n- purpose: measure ads\n  text: to measure our ads (page views and sign-ups)\n- purpose: service operation\n  text: 'This is the service itself: the ceilings, the console and your usage.'\nretention:\n- scope: revoked or expired API keys\n  period: 90 days\n  text: deleted 90 days after the day it was revoked or expired\n- scope: preflight refusals and snapshots\n  period: 180 days\n  text: deleted 180 days after the refusal\n- scope: usage record metadata\n  period: 400 days\n  text: cleared 400 days after the record\n- scope: marketing page events\n  period: 180 days\n  text: deleted 180 days after the event\n- scope:\
  \ account data\n  period: null\n  text: Kept while your account exists, and deleted with it\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Fly.io hosts the service and keeps its request log. Supabase hosts the database. Resend sends the emails\n    in section 5, and receives mail sent to hello@agentbill.dev\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@agentbill.dev\n  text: Email hello@agentbill.dev from the address on the account and we delete the account and everything stored\n    under it\nrights:\n- right: copy of data\n  text: You can also ask for a copy of your data or to correct it, the same way.\n- right: correction\n  text: You can also ask for a copy of your data or to correct it, the same way.\n- right: GDPR rights for EU/EEA or UK\n  text: If you are in the EU/EEA or UK, these rights are backed by the GDPR.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentbill-dev/privacy/agentbill-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from AgentBill's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
