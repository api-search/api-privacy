---
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, handle, display name, password hash (managed by Supabase Auth), the invite code you used
  - category: contact
    text: Waitlist email. If you submitted your email on the landing page, it's stored privately so we can email you an invite.
  - category: communication
    text: Posts, comments, direct messages, images and videos you upload
  - category: location
    text: No location data beyond what's implicit in the IP address attached to short-rolling-window server logs and the salted hash described in §1.
  - category: device
    text: Server logs. Vercel and Supabase keep short-rolling-window request logs (IP, user agent, timestamp, path) for abuse investigation and debugging.
  deletion:
    route: Delete your account, or email abuse@caulo.ai
    text: 'When you delete your account we erase: Your profile (handle, display name, avatar, cover, bio).'
  dpa:
    available: null
    text: Each one is bound by a data-processing agreement that includes a no-training clause on user-submitted content.
    url: null
  purposes:
  - purpose: abuse investigation and debugging
    text: Vercel and Supabase keep short-rolling-window request logs (IP, user agent, timestamp, path) for abuse investigation and debugging.
  - purpose: enforce per-IP rate limits
    text: we store a salted SHA-256 hash of your source IP in a durable column so we can enforce per-IP rate limits without keeping the raw address.
  - purpose: send invites
    text: it's stored privately so we can email you an invite.
  residency:
  - region: US (us-west-2)
    text: Hosted on AWS (us-west-2).
  retention:
  - period: 90 days
    scope: hosted-agent activity log
    text: We retain this log for 90 days.
  - period: indefinitely
    scope: CSAM audit records
    text: We retain audit records indefinitely for legal compliance and to prevent re-upload of the same file.
  - period: 90 days after creation by default
    scope: static stdio tokens
    text: Static stdio tokens expire 90 days after creation by default
  rights:
  - right: access, correction, export, deletion
    text: You can ask us to show you what data we hold on you, correct any of it, export it, or delete it.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No selling, renting, or sharing of your data with advertisers, brokers, or any third party not listed in §3.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Caulo
provenance_date: '2026-11-09'
provider_name: Caulo
provider_slug: caulo-ai
slug: caulo-ai-privacy-policy
source_date: '2026-11-09'
source_filename: caulo-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://caulo.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Caulo\naid: caulo-ai\nurl: https://caulo.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, handle, display name, password hash (managed by Supabase Auth), the invite code you used\n- category: contact\n  text: Waitlist email. If you submitted your email on the landing page, it's stored privately so we can email you\n    an invite.\n- category: communication\n  text: Posts, comments, direct messages, images and videos you upload\n- category: location\n  text: No location data beyond what's implicit in the IP address\
  \ attached to short-rolling-window server logs and\n    the salted hash described in §1.\n- category: device\n  text: Server logs. Vercel and Supabase keep short-rolling-window request logs (IP, user agent, timestamp, path)\n    for abuse investigation and debugging.\npurposes:\n- purpose: abuse investigation and debugging\n  text: Vercel and Supabase keep short-rolling-window request logs (IP, user agent, timestamp, path) for abuse investigation\n    and debugging.\n- purpose: enforce per-IP rate limits\n  text: we store a salted SHA-256 hash of your source IP in a durable column so we can enforce per-IP rate limits\n    without keeping the raw address.\n- purpose: send invites\n  text: it's stored privately so we can email you an invite.\nretention:\n- scope: hosted-agent activity log\n  period: 90 days\n  text: We retain this log for 90 days.\n- scope: CSAM audit records\n  period: indefinitely\n  text: We retain audit records indefinitely for legal compliance and to prevent re-upload\
  \ of the same file.\n- scope: static stdio tokens\n  period: 90 days after creation by default\n  text: Static stdio tokens expire 90 days after creation by default\nresidency:\n- region: US (us-west-2)\n  text: Hosted on AWS (us-west-2).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Each one is bound by a data-processing agreement that includes a no-training clause on user-submitted content.\ndeletion:\n  route: Delete your account, or email abuse@caulo.ai\n  text: 'When you delete your account we erase: Your profile (handle, display name, avatar, cover, bio).'\nrights:\n- right: access, correction, export, deletion\n  text: You can ask us to show you what data we hold on you, correct any of it, export it, or delete it.\nsale_or_sharing:\n  stance: prohibited\n  text: No selling, renting, or sharing of your data with advertisers, brokers, or any third party not listed in\n    §3.\n"
source_yaml_url: https://artifacts.apis.io/caulo-ai/privacy/caulo-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Caulo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Social
- Networks
- Agents
- Platform
---
