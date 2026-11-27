---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: If you contact us at legal@freetts.org, we'll have your email from that exchange.
  - category: identifying
    text: 'Like every website, our server logs basic connection info: IP address, page requested, browser type, and visit time.'
  - category: behavioral
    text: The FreeTTS website uses Google Analytics to understand aggregate, largely anonymized usage (which pages are visited, broad device and region)
  - category: financial
    text: we receive the purchase and the plan, never card details.
  - category: communication
    text: Email us directly. A real person responds within 24 hours.
  deletion:
    route: automatic deletion by background task; email legal@freetts.org for requests
    text: Background task deletes all files older than 1 hour. Automatically. No exceptions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: generate audio from submitted text
    text: Process your text to generate audio (then drop it, unless you turn history on)
  - purpose: apply plan limits and stop abuse
    text: Keep a usage record of each generation (voice, length, time) to apply your plan limits and stop abuse
  - purpose: security logging
    text: Log basic server traffic for security (IP, page, time)
  - purpose: improve the product via analytics
    text: so we can improve the product
  residency:
  - region: Germany
    text: Our own servers are in the EU.
  - region: Singapore
    text: Supabase (accounts, usage records, saved projects, and history text if you switch it on) — Singapore .
  retention:
  - period: within one hour
    scope: submitted text (free tool)
    text: automatically deleted within one hour.
  - period: about an hour
    scope: generated audio (free and guest)
    text: Audio for free and guest generations is deleted about an hour after it is made.
  - period: null
    scope: optional history
    text: The toggle is OFF by default.
  - period: null
    scope: server logs
    text: These are standard security logs, rotated regularly, not analyzed to identify individual users.
  rights:
  - right: know
    text: Right to Know What data do we collect about you?
  - right: delete
    text: Right to Delete Can you request deletion of your data?
  - right: opt out of sale
    text: Right to Opt Out of Sale Can you stop us from selling your data?
  - right: portability
    text: Right to Portability Can you export your data?
  - right: non-discrimination
    text: Right to Non-Discrimination Will we treat you differently if you exercise rights?
  role:
    text: Each processes the text solely to return audio
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: FreeTTS does not sell your personal information.
  subprocessors:
    text: Cloudflare (delivery and abuse protection) — a global edge network
    url: null
  transfers:
  - mechanism: SCC
    text: Where processing happens outside the EU or EEA, it is covered by the standard contractual clauses each provider publishes.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FreeTTS
provenance_date: '2026-11-09'
provider_name: FreeTTS
provider_slug: freetts
slug: freetts-privacy-policy
source_date: '2026-11-09'
source_filename: freetts-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://freetts.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FreeTTS\naid: freetts\nurl: https://freetts.org/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Each processes the text solely to return audio\ndata_categories:\n- category: contact\n  text: If you contact us at legal@freetts.org, we'll have your email from that exchange.\n- category: identifying\n  text: 'Like every website, our server logs basic connection info: IP address, page requested, browser type, and\n    visit time.'\n- category: behavioral\n  text: The FreeTTS website uses Google Analytics to understand aggregate, largely anonymized usage (which pages\n    are visited, broad\
  \ device and region)\n- category: financial\n  text: we receive the purchase and the plan, never card details.\n- category: communication\n  text: Email us directly. A real person responds within 24 hours.\npurposes:\n- purpose: generate audio from submitted text\n  text: Process your text to generate audio (then drop it, unless you turn history on)\n- purpose: apply plan limits and stop abuse\n  text: Keep a usage record of each generation (voice, length, time) to apply your plan limits and stop abuse\n- purpose: security logging\n  text: Log basic server traffic for security (IP, page, time)\n- purpose: improve the product via analytics\n  text: so we can improve the product\nretention:\n- scope: submitted text (free tool)\n  period: within one hour\n  text: automatically deleted within one hour.\n- scope: generated audio (free and guest)\n  period: about an hour\n  text: Audio for free and guest generations is deleted about an hour after it is made.\n- scope: optional history\n  period:\
  \ null\n  text: The toggle is OFF by default.\n- scope: server logs\n  period: null\n  text: These are standard security logs, rotated regularly, not analyzed to identify individual users.\nresidency:\n- region: Germany\n  text: Our own servers are in the EU.\n- region: Singapore\n  text: Supabase (accounts, usage records, saved projects, and history text if you switch it on) — Singapore .\ntransfers:\n- mechanism: SCC\n  text: Where processing happens outside the EU or EEA, it is covered by the standard contractual clauses each provider\n    publishes.\nsubprocessors:\n  url: null\n  text: Cloudflare (delivery and abuse protection) — a global edge network\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: automatic deletion by background task; email legal@freetts.org for requests\n  text: Background task deletes all files older than 1 hour. Automatically. No exceptions.\nrights:\n- right: know\n  text: Right to Know What data do we collect about you?\n- right: delete\n\
  \  text: Right to Delete Can you request deletion of your data?\n- right: opt out of sale\n  text: Right to Opt Out of Sale Can you stop us from selling your data?\n- right: portability\n  text: Right to Portability Can you export your data?\n- right: non-discrimination\n  text: Right to Non-Discrimination Will we treat you differently if you exercise rights?\nsale_or_sharing:\n  stance: prohibited\n  text: FreeTTS does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/freetts/privacy/freetts-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from FreeTTS's own page on 2026-11-09.
synthetic: false
tags:
- Text-to-Speech
- Speech Synthesis
- AI-voice
- Audio
- Media
- Accessibility
- Speech-to-Text
- Content Creation
- Developer Tools
---
