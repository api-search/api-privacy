---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: contact
    text: Email you send to support@hanria.ai is read by the company and used to reply to you.
  - category: identifying
    text: the public key and event identifiers described above if you use the Nostr service
  - category: device
    text: standard request metadata, which can include IP addresses, that Cloudflare keeps under its own terms
  - category: communication
    text: any personal data inside text you choose to send to the check (which is evaluated in memory)
  deletion:
    route: email support@hanria.ai
    text: ask us to delete it by writing to support@hanria.ai
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: reply to support email
    text: used to reply to you
  retention:
  - period: null
    scope: hosted check request bodies
    text: The hosted check evaluates request bodies in memory and does not store them.
  - period: 8 days
    scope: Nostr records on HANRIA's machine
    text: It deletes records older than 8 days when it next handles a job.
  rights:
  - right: access
    text: You may ask what email we hold from you
  - right: deletion
    text: ask us to delete it by writing to support@hanria.ai
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: hanria-ai
provenance_date: '2026-11-09'
provider_name: hanria-ai
provider_slug: hanria-ai
slug: hanria-ai-privacy-policy
source_date: '2026-11-09'
source_filename: hanria-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hanria.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: hanria-ai\naid: hanria-ai\nurl: https://hanria.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email you send to support@hanria.ai is read by the company and used to reply to you.\n- category: identifying\n  text: the public key and event identifiers described above if you use the Nostr service\n- category: device\n  text: standard request metadata, which can include IP addresses, that Cloudflare keeps under its own terms\n- category: communication\n  text: any personal data inside text you choose to send to the check (which is\
  \ evaluated in memory)\npurposes:\n- purpose: reply to support email\n  text: used to reply to you\nretention:\n- scope: hosted check request bodies\n  period: null\n  text: The hosted check evaluates request bodies in memory and does not store them.\n- scope: Nostr records on HANRIA's machine\n  period: 8 days\n  text: It deletes records older than 8 days when it next handles a job.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@hanria.ai\n  text: ask us to delete it by writing to support@hanria.ai\nrights:\n- right: access\n  text: You may ask what email we hold from you\n- right: deletion\n  text: ask us to delete it by writing to support@hanria.ai\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/hanria-ai/privacy/hanria-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from hanria-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Identity
- Verification
- Payments
- Compliance
- Company
---
