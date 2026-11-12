---
api_specs:
- filename: cliponit-app-account-api-openapi.yml
  format: yaml
  label: ClipOnIt Account API
  slug: cliponit-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-account-api-openapi.yml
- filename: cliponit-app-agents-api-openapi.yml
  format: yaml
  label: ClipOnIt Agents API
  slug: cliponit-app-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-agents-api-openapi.yml
- filename: cliponit-app-auth-api-openapi.yml
  format: yaml
  label: ClipOnIt Auth API
  slug: cliponit-app-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-auth-api-openapi.yml
- filename: cliponit-app-billing-api-openapi.yml
  format: yaml
  label: ClipOnIt Billing API
  slug: cliponit-app-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-billing-api-openapi.yml
- filename: cliponit-app-clips-api-openapi.yml
  format: yaml
  label: ClipOnIt Clips API
  slug: cliponit-app-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-clips-api-openapi.yml
- filename: cliponit-app-enrich-api-openapi.yml
  format: yaml
  label: ClipOnIt Enrich API
  slug: cliponit-app-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-enrich-api-openapi.yml
- filename: cliponit-app-explainer-api-openapi.yml
  format: yaml
  label: ClipOnIt Explainer API
  slug: cliponit-app-explainer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-explainer-api-openapi.yml
- filename: cliponit-app-smart-api-openapi.yml
  format: yaml
  label: ClipOnIt Smart API
  slug: cliponit-app-smart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-smart-api-openapi.yml
- filename: cliponit-app-tiktok-api-openapi.yml
  format: yaml
  label: ClipOnIt Tiktok API
  slug: cliponit-app-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-tiktok-api-openapi.yml
- filename: cliponit-app-videos-api-openapi.yml
  format: yaml
  label: ClipOnIt Videos API
  slug: cliponit-app-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cliponit-app/openapi/cliponit-app-videos-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email address, first or last name, password (stored hashed), and if you sign in with Google: Google identifier, name and avatar.'
  - category: contact
    text: 'Partnerships waitlist (/partenaires page): email address, role (brand or clipper), language, referral code if any and the date of your consent.'
  - category: behavioral
    text: We record page views, clicks, scroll depth, errors and load times, plus the main steps in the app (importing a video, exporting, subscribing).
  - category: device
    text: 'Technical: session cookie, affiliate "ref" cookie (60 days) if you arrive through a referral link, theme and language in your browser''s localStorage, IP address and server logs.'
  - category: communication
    text: 'Content: the videos you upload or import by link, their transcripts, the generated clips and exports, your logo if any.'
  deletion:
    route: Delete a video in the app, or delete the account on request
    text: You can delete a video at any time, which deletes its clips and exports.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the service
    text: Providing the service (transcribing, detecting highlights, reframing, captioning, exporting), managing your account and subscription, answering your requests, preventing abuse (per-IP limits on the free tool), and improving the product from usage statistics and analytics
  residency:
  - region: European Union
    text: 'Hosting and storage: Hetzner, Helsinki (Finland, European Union).'
  retention:
  - period: while the subscription is active
    scope: Paid plan clips and transcripts
    text: on paid plans, clips, exports and transcripts are kept while the subscription is active
  - period: 30 days
    scope: Source video file on paid plans
    text: the source video file is deleted 30 days after it was imported
  - period: 7 days
    scope: Free plan
    text: 'Free plan: 7 days; free tool without an account: 24 hours.'
  - period: 10 years
    scope: Invoices
    text: 'Invoices: 10 years (accounting obligation).'
  - period: 30 days
    scope: Server logs
    text: 'Server logs: 30 days.'
  - period: 13 months at most
    scope: Analytics
    text: 'Analytics (events and "cv_vid" / "cv_ft" cookies): 13 months at most.'
  rights:
  - right: Access, rectification, erasure, portability, restriction and objection
    text: 'Access, rectification, erasure, portability, restriction and objection: write to contact@cliponit.app from your account''s address; we answer within 30 days.'
  - right: Lodge a complaint
    text: You can also lodge a complaint with the CNIL (cnil.fr), the French supervisory authority.
  role:
    text: ClipOnIt (cliponit.app) is published by an independent founder based in Nantes, France, who is the data controller under the GDPR.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: These statistics are not sold, shared or used for advertising, except the three steps described under "Advertising", and only with your consent.
  subprocessors:
    text: 'Hosting and storage: Hetzner, Helsinki (Finland, European Union). Transcription: OpenAI (Whisper). Highlight detection, descriptions and translations: Anthropic (Claude), which receives the transcript, not the video.'
    url: null
  transfers:
  - mechanism: SCC
    text: transfers rely on the European Commission's standard contractual clauses or the Data Privacy Framework
  - mechanism: DPF
    text: transfers rely on the European Commission's standard contractual clauses or the Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClipOnIt
provenance_date: '2026-11-09'
provider_name: ClipOnIt
provider_slug: cliponit-app
slug: cliponit-app-privacy-policy
source_date: '2026-11-09'
source_filename: cliponit-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cliponit.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClipOnIt\naid: cliponit-app\nurl: https://cliponit.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ClipOnIt (cliponit.app) is published by an independent founder based in Nantes, France, who is the data\n    controller under the GDPR.\ndata_categories:\n- category: identifying\n  text: 'Account: email address, first or last name, password (stored hashed), and if you sign in with Google: Google\n    identifier, name and avatar.'\n- category: contact\n  text: 'Partnerships waitlist (/partenaires page): email address, role (brand or clipper), language, referral code\n    if any and\
  \ the date of your consent.'\n- category: behavioral\n  text: We record page views, clicks, scroll depth, errors and load times, plus the main steps in the app (importing\n    a video, exporting, subscribing).\n- category: device\n  text: 'Technical: session cookie, affiliate \"ref\" cookie (60 days) if you arrive through a referral link, theme\n    and language in your browser''s localStorage, IP address and server logs.'\n- category: communication\n  text: 'Content: the videos you upload or import by link, their transcripts, the generated clips and exports, your\n    logo if any.'\npurposes:\n- purpose: Providing the service\n  text: Providing the service (transcribing, detecting highlights, reframing, captioning, exporting), managing your\n    account and subscription, answering your requests, preventing abuse (per-IP limits on the free tool), and improving\n    the product from usage statistics and analytics\nretention:\n- scope: Paid plan clips and transcripts\n  period: while the\
  \ subscription is active\n  text: on paid plans, clips, exports and transcripts are kept while the subscription is active\n- scope: Source video file on paid plans\n  period: 30 days\n  text: the source video file is deleted 30 days after it was imported\n- scope: Free plan\n  period: 7 days\n  text: 'Free plan: 7 days; free tool without an account: 24 hours.'\n- scope: Invoices\n  period: 10 years\n  text: 'Invoices: 10 years (accounting obligation).'\n- scope: Server logs\n  period: 30 days\n  text: 'Server logs: 30 days.'\n- scope: Analytics\n  period: 13 months at most\n  text: 'Analytics (events and \"cv_vid\" / \"cv_ft\" cookies): 13 months at most.'\nresidency:\n- region: European Union\n  text: 'Hosting and storage: Hetzner, Helsinki (Finland, European Union).'\ntransfers:\n- mechanism: SCC\n  text: transfers rely on the European Commission's standard contractual clauses or the Data Privacy Framework\n- mechanism: DPF\n  text: transfers rely on the European Commission's standard\
  \ contractual clauses or the Data Privacy Framework\nsubprocessors:\n  url: null\n  text: 'Hosting and storage: Hetzner, Helsinki (Finland, European Union). Transcription: OpenAI (Whisper). Highlight\n    detection, descriptions and translations: Anthropic (Claude), which receives the transcript, not the video.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a video in the app, or delete the account on request\n  text: You can delete a video at any time, which deletes its clips and exports.\nrights:\n- right: Access, rectification, erasure, portability, restriction and objection\n  text: 'Access, rectification, erasure, portability, restriction and objection: write to contact@cliponit.app from\n    your account''s address; we answer within 30 days.'\n- right: Lodge a complaint\n  text: You can also lodge a complaint with the CNIL (cnil.fr), the French supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: These statistics are not sold,\
  \ shared or used for advertising, except the three steps described under \"Advertising\",\n    and only with your consent.\n"
source_yaml_url: https://artifacts.apis.io/cliponit-app/privacy/cliponit-app-privacy-policy.yml
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
summary_line: 21 quoted statements, read from ClipOnIt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Artificial Intelligence
- Short-Form Video
- Video Editing
- MCP
- Content Creation
- Social Media
---
