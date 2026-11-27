---
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: your account identifier, email, and name provided by Google sign-in
  - category: contact
    text: Native Apple sign-in requests only your email, including a private relay address if you choose Hide My Email.
  - category: financial
    text: we store your plan, credit balance, and a Stripe customer reference. We never see your card number.
  - category: behavioral
    text: app interactions, device and app information, approximate location derived from IP address, and diagnostic events
  - category: communication
    text: we keep the text prompts you send it and the text of its replies, tied to your account
  - category: other
    text: 'Media: local caches stay on your device; requested AI processing sends relevant media to providers.'
  deletion:
    route: Settings → Delete account in the app, or email support@getklo.com
    text: Use Settings → Delete account in the app to delete your account and cancel Klo web subscriptions, or email support@getklo.com to request deletion of your account and associated cloud data, minus what the law requires us to keep.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: agent editing requests
    text: When you ask the agent for an edit, the pieces needed to fulfill that request are sent to our servers, passed to our AI providers, processed, and returned.
  - purpose: credits and pricing
    text: per-request token counts and costs (so credits and pricing stay honest)
  residency:
  - region: United States
    text: Our current Cloud MCP and account database deployments are in the United States.
  retention:
  - period: null
    scope: account and billing records
    text: Account and billing records are kept while your account exists (and as required for tax and accounting).
  - period: null
    scope: cloud projects and media
    text: Cloud projects and their referenced media have no fixed automatic expiry; unused temporary working files may be cleaned separately.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data and we don't use your content to train models.
  subprocessors:
    text: Supabase hosts our accounts database, sign-in, and API services. Railway hosts Cloud MCP, its project and media storage, and rendering. Vercel hosts our website. PostHog processes product analytics and diagnostics. Stripe processes payments. Anthropic processes agent requests, including the frames the agent captures to see your footage.
    url: null
  transfers:
  - mechanism: other
    text: Providers may process or access data in other countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: getklo-com
provenance_date: '2026-11-09'
provider_name: getklo-com
provider_slug: getklo-com
slug: getklo-com-privacy-policy
source_date: '2026-11-09'
source_filename: getklo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://klo.mov/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: getklo-com\naid: getklo-com\nurl: https://klo.mov/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your account identifier, email, and name provided by Google sign-in\n- category: contact\n  text: Native Apple sign-in requests only your email, including a private relay address if you choose Hide My Email.\n- category: financial\n  text: we store your plan, credit balance, and a Stripe customer reference. We never see your card number.\n- category: behavioral\n  text: app interactions, device and app information, approximate location\
  \ derived from IP address, and diagnostic\n    events\n- category: communication\n  text: we keep the text prompts you send it and the text of its replies, tied to your account\n- category: other\n  text: 'Media: local caches stay on your device; requested AI processing sends relevant media to providers.'\npurposes:\n- purpose: agent editing requests\n  text: When you ask the agent for an edit, the pieces needed to fulfill that request are sent to our servers, passed\n    to our AI providers, processed, and returned.\n- purpose: credits and pricing\n  text: per-request token counts and costs (so credits and pricing stay honest)\nretention:\n- scope: account and billing records\n  period: null\n  text: Account and billing records are kept while your account exists (and as required for tax and accounting).\n- scope: cloud projects and media\n  period: null\n  text: Cloud projects and their referenced media have no fixed automatic expiry; unused temporary working files\n    may be cleaned\
  \ separately.\nresidency:\n- region: United States\n  text: Our current Cloud MCP and account database deployments are in the United States.\ntransfers:\n- mechanism: other\n  text: Providers may process or access data in other countries.\nsubprocessors:\n  url: null\n  text: Supabase hosts our accounts database, sign-in, and API services. Railway hosts Cloud MCP, its project and\n    media storage, and rendering. Vercel hosts our website. PostHog processes product analytics and diagnostics.\n    Stripe processes payments. Anthropic processes agent requests, including the frames the agent captures to see\n    your footage.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Delete account in the app, or email support@getklo.com\n  text: Use Settings → Delete account in the app to delete your account and cancel Klo web subscriptions, or email\n    support@getklo.com to request deletion of your account and associated cloud data, minus what the law requires\n\
  \    us to keep.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data and we don't use your content to train models.\n"
source_yaml_url: https://artifacts.apis.io/getklo-com/privacy/getklo-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- sale_or_sharing
summary_line: 15 quoted statements, read from getklo-com's own page on 2026-11-09.
synthetic: false
tags:
- Video Editing
- Artificial Intelligence
- Cloud Rendering
- Collaboration
- Marketing
---
