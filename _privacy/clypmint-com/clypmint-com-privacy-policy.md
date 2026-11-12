---
api_specs:
- filename: clypmint-com-assets-api-openapi.yml
  format: yaml
  label: Clypmint Assets API
  slug: clypmint-com-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-assets-api-openapi.yml
- filename: clypmint-com-content-plans-api-openapi.yml
  format: yaml
  label: Clypmint Content Plans API
  slug: clypmint-com-content-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-content-plans-api-openapi.yml
- filename: clypmint-com-me-api-openapi.yml
  format: yaml
  label: Clypmint Me API
  slug: clypmint-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-me-api-openapi.yml
- filename: clypmint-com-memory-api-openapi.yml
  format: yaml
  label: Clypmint Memory API
  slug: clypmint-com-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-memory-api-openapi.yml
- filename: clypmint-com-openapi-json-api-openapi.yml
  format: yaml
  label: Clypmint Openapi.json API
  slug: clypmint-com-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-openapi-json-api-openapi.yml
- filename: clypmint-com-schedule-api-openapi.yml
  format: yaml
  label: Clypmint Schedule API
  slug: clypmint-com-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-schedule-api-openapi.yml
- filename: clypmint-com-styles-api-openapi.yml
  format: yaml
  label: Clypmint Styles API
  slug: clypmint-com-styles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-styles-api-openapi.yml
- filename: clypmint-com-videos-api-openapi.yml
  format: yaml
  label: Clypmint Videos API
  slug: clypmint-com-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clypmint-com/openapi/clypmint-com-videos-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email address, full name (if provided), authentication tokens via Supabase.'
  - category: financial
    text: we only retain a customer ID, subscription status, and invoice history
  - category: behavioral
    text: 'Usage data: projects created, renders started, style extractions, chat messages, credit ledger entries.'
  - category: device
    text: 'Technical and interaction data: IP address, user agent, device fingerprint (for fraud prevention on signup), timestamps, page visits, clicks, navigation, product events, errors, and performance timing.'
  - category: other
    text: 'Uploaded content: video, image, and audio files you upload, plus any reference URLs you paste.'
  deletion:
    route: Delete account control on Plan & billing page, or email
    text: All data is deleted (some billing records retained per §4).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver video-editing service
    text: Deliver the video-editing service (core functionality).
  - purpose: Prevent abuse
    text: Prevent abuse (rate-limits, fraud scoring at signup).
  - purpose: Legal obligation
    text: Legal obligation (tax records retained 7 years).
  - purpose: Measure ad performance
    text: Measure which of our ads bring customers
  - purpose: Product improvement
    text: Understand acquisition, conversion, feature adoption, reliability, and usability so we can improve the offer, funnel, website, and Studio.
  retention:
  - period: lifetime of your account
    scope: Finished renders, uploaded source material, chat messages
    text: retained for the lifetime of your account
  - period: 7 years
    scope: Billing records
    text: Billing records are retained for 7 years per tax regulations.
  - period: null
    scope: Analytics events and session replays
    text: retained according to our configured analytics retention window
  - period: 90 days
    scope: Meta click ID cookie
    text: we keep it in our own cookie for up to 90 days and send it to Meta with those events
  rights:
  - right: Access
    text: 'Right of access: email us and we''ll provide a copy of your data.'
  - right: Correction
    text: 'Right to correction: edit your profile in-app or email us.'
  - right: Portability
    text: 'Right to portability: we can export your data as JSON + your videos as MP4s.'
  - right: Opt out of sale or sharing
    text: 'Right to opt out of sale or sharing: we do not sell data.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: 'Your data passes through:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clypmint
provenance_date: '2026-11-09'
provider_name: Clypmint
provider_slug: clypmint-com
slug: clypmint-com-privacy-policy
source_date: '2026-11-09'
source_filename: clypmint-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clypmint.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clypmint\naid: clypmint-com\nurl: https://clypmint.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: email address, full name (if provided), authentication tokens via Supabase.'\n- category: financial\n  text: we only retain a customer ID, subscription status, and invoice history\n- category: behavioral\n  text: 'Usage data: projects created, renders started, style extractions, chat messages, credit ledger entries.'\n- category: device\n  text: 'Technical and interaction data: IP address, user agent, device\
  \ fingerprint (for fraud prevention on signup),\n    timestamps, page visits, clicks, navigation, product events, errors, and performance timing.'\n- category: other\n  text: 'Uploaded content: video, image, and audio files you upload, plus any reference URLs you paste.'\npurposes:\n- purpose: Deliver video-editing service\n  text: Deliver the video-editing service (core functionality).\n- purpose: Prevent abuse\n  text: Prevent abuse (rate-limits, fraud scoring at signup).\n- purpose: Legal obligation\n  text: Legal obligation (tax records retained 7 years).\n- purpose: Measure ad performance\n  text: Measure which of our ads bring customers\n- purpose: Product improvement\n  text: Understand acquisition, conversion, feature adoption, reliability, and usability so we can improve the offer,\n    funnel, website, and Studio.\nretention:\n- scope: Finished renders, uploaded source material, chat messages\n  period: lifetime of your account\n  text: retained for the lifetime of your account\n\
  - scope: Billing records\n  period: 7 years\n  text: Billing records are retained for 7 years per tax regulations.\n- scope: Analytics events and session replays\n  period: null\n  text: retained according to our configured analytics retention window\n- scope: Meta click ID cookie\n  period: 90 days\n  text: we keep it in our own cookie for up to 90 days and send it to Meta with those events\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Your data passes through:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account control on Plan & billing page, or email\n  text: All data is deleted (some billing records retained per §4).\nrights:\n- right: Access\n  text: 'Right of access: email us and we''ll provide a copy of your data.'\n- right: Correction\n  text: 'Right to correction: edit your profile in-app or email us.'\n- right: Portability\n  text: 'Right to portability: we can export your data as JSON + your videos as MP4s.'\n- right:\
  \ Opt out of sale or sharing\n  text: 'Right to opt out of sale or sharing: we do not sell data.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/clypmint-com/privacy/clypmint-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Clypmint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video Editing
- Video
- Generative AI
- Content Creation
- MCP
- Creator Tools
- Short-Form Video
---
