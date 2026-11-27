---
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register, we store your email address and a hashed password.
  - category: contact
    text: When you register, we store your email address and a hashed password.
  - category: financial
    text: Stripe holds your billing details (name, company name, address, payment method) and invoice history; we keep only the Stripe customer and subscription identifiers, your plan, and the renewal date.
  - category: device
    text: Our servers also keep short-lived request logs — timestamp, request path, response status, duration, IP address, and browser user-agent — so we can debug failures and investigate abuse.
  - category: behavioral
    text: We also record a small number of anonymous product events (for example, that an upload on a tool page finished, or that a Copy button was clicked) to see where people get stuck.
  deletion:
    route: Delete images via the API; delete the entire account by contacting privacy@pixelvault.dev
    text: You can delete any image via the API. To delete your entire account, contact us at privacy@pixelvault.dev .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run account and send product/promotional email
    text: We use your email address to run your account and, unless you opt out, to send occasional product tips and promotional offers.
  - purpose: Debug failures and investigate abuse
    text: so we can debug failures and investigate abuse
  - purpose: Aggregate traffic analytics
    text: We use Cloudflare Web Analytics to understand aggregate traffic.
  residency:
  - region: European Union
    text: Your images and core account data are stored at rest in the European Union
  retention:
  - period: 3 days
    scope: Request logs
    text: These logs are held by Cloudflare on our behalf for a short retention window (currently 3 days) and then deleted automatically.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data.
  subprocessors:
    text: 'We rely on a small set of infrastructure providers, each under a data processing agreement: Cloudflare — image storage (R2, EU), CDN, edge compute, cookieless analytics, and short-lived server request logs. Neon — PostgreSQL database (EU region) for account and image metadata. Plunk — email delivery: transactional messages (e.g. verification, password reset) and occasional product and promotional emails, which you can opt out of at any time. Stripe — payment processing and invoicing for paid plans (card details, billing name and address, invoices).'
    url: null
  transfers:
  - mechanism: SCC
    text: Stripe may process data in the United States under standard contractual clauses.
  - mechanism: other
    text: A couple of subprocessors (below) — transactional email, payments and aggregate analytics — may process limited data outside the EU under standard data-protection safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pixelvault-dev
provenance_date: '2026-11-10'
provider_name: pixelvault-dev
provider_slug: pixelvault-dev
slug: pixelvault-dev-privacy-policy
source_date: '2026-11-10'
source_filename: pixelvault-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pixelvault.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pixelvault-dev\naid: pixelvault-dev\nurl: https://pixelvault.dev/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you register, we store your email address and a hashed password.\n- category: contact\n  text: When you register, we store your email address and a hashed password.\n- category: financial\n  text: Stripe holds your billing details (name, company name, address, payment method) and invoice history; we\n    keep only the Stripe customer and subscription identifiers, your plan, and the renewal date.\n- category: device\n\
  \  text: Our servers also keep short-lived request logs — timestamp, request path, response status, duration, IP\n    address, and browser user-agent — so we can debug failures and investigate abuse.\n- category: behavioral\n  text: We also record a small number of anonymous product events (for example, that an upload on a tool page finished,\n    or that a Copy button was clicked) to see where people get stuck.\npurposes:\n- purpose: Run account and send product/promotional email\n  text: We use your email address to run your account and, unless you opt out, to send occasional product tips and\n    promotional offers.\n- purpose: Debug failures and investigate abuse\n  text: so we can debug failures and investigate abuse\n- purpose: Aggregate traffic analytics\n  text: We use Cloudflare Web Analytics to understand aggregate traffic.\nretention:\n- scope: Request logs\n  period: 3 days\n  text: These logs are held by Cloudflare on our behalf for a short retention window (currently 3 days)\
  \ and then\n    deleted automatically.\nresidency:\n- region: European Union\n  text: Your images and core account data are stored at rest in the European Union\ntransfers:\n- mechanism: SCC\n  text: Stripe may process data in the United States under standard contractual clauses.\n- mechanism: other\n  text: A couple of subprocessors (below) — transactional email, payments and aggregate analytics — may process\n    limited data outside the EU under standard data-protection safeguards.\nsubprocessors:\n  url: null\n  text: 'We rely on a small set of infrastructure providers, each under a data processing agreement: Cloudflare\n    — image storage (R2, EU), CDN, edge compute, cookieless analytics, and short-lived server request logs. Neon\n    — PostgreSQL database (EU region) for account and image metadata. Plunk — email delivery: transactional messages\n    (e.g. verification, password reset) and occasional product and promotional emails, which you can opt out of\n    at any time. Stripe\
  \ — payment processing and invoicing for paid plans (card details, billing name and address,\n    invoices).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete images via the API; delete the entire account by contacting privacy@pixelvault.dev\n  text: You can delete any image via the API. To delete your entire account, contact us at privacy@pixelvault.dev\n    .\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data.\n"
source_yaml_url: https://artifacts.apis.io/pixelvault-dev/privacy/pixelvault-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- sale_or_sharing
summary_line: 15 quoted statements, read from pixelvault-dev's own page on 2026-11-10.
synthetic: false
tags:
- Image Hosting
- CDN
- AI Agents
- Developer Tools
---
