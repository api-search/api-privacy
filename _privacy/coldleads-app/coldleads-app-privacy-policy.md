---
api_specs:
- filename: coldleads-app-activity-api-openapi.yml
  format: yaml
  label: Cold Leads Activity API
  slug: coldleads-app-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-activity-api-openapi.yml
- filename: coldleads-app-credits-api-openapi.yml
  format: yaml
  label: Cold Leads Credits API
  slug: coldleads-app-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-credits-api-openapi.yml
- filename: coldleads-app-find-api-openapi.yml
  format: yaml
  label: Cold Leads Find API
  slug: coldleads-app-find-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-find-api-openapi.yml
- filename: coldleads-app-follow-ups-api-openapi.yml
  format: yaml
  label: Cold Leads Follow Ups API
  slug: coldleads-app-follow-ups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-follow-ups-api-openapi.yml
- filename: coldleads-app-leads-api-openapi.yml
  format: yaml
  label: Cold Leads Leads API
  slug: coldleads-app-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-leads-api-openapi.yml
- filename: coldleads-app-next-actions-api-openapi.yml
  format: yaml
  label: Cold Leads Next Actions API
  slug: coldleads-app-next-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-next-actions-api-openapi.yml
- filename: coldleads-app-social-api-openapi.yml
  format: yaml
  label: Cold Leads Social API
  slug: coldleads-app-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-social-api-openapi.yml
- filename: coldleads-app-verify-api-openapi.yml
  format: yaml
  label: Cold Leads Verify API
  slug: coldleads-app-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldleads-app/openapi/coldleads-app-verify-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your name, e-mail address and authentication identifier received from the sign-in method you choose'
  - category: contact
    text: 'Contact data you add: names, e-mail addresses, phone numbers, companies, social profile links, tags, notes and interaction history of your business contacts.'
  - category: device
    text: 'Technical data: a session cookie required for sign-in and basic server logs (IP address, time) for security and rate limiting.'
  - category: financial
    text: we store only payment and subscription identifiers, never card numbers.
  - category: communication
    text: Messages you type in the chat are sent to OpenAI to generate the reply
  deletion:
    route: E-mail to support@coldleads.app or via Help → Send a report
    text: You may request access, correction, export or deletion of your data at any time by e-mail to the address above or via Help → Send a report; we respond within 30 days.
  dpa:
    available: true
    text: For your contacts' data we act as your processor under the Data Processing Agreement (coldleads.app/terms/dpa).
    url: coldleads.app/terms/dpa
  purposes:
  - purpose: Provide the Service
    text: 'Solely to provide the Service: authenticating you, storing your CRM data, sending the e-mail campaigns you explicitly launch, and generating drafts with AI.'
  - purpose: Advertising
    text: We do not sell personal data and do not use it for advertising.
  residency:
  - region: European Union
    text: Supabase (the PostgreSQL database, stored in the EU — Paris, France)
  retention:
  - period: null
    scope: Account data
    text: Data is kept while your account is active.
  - period: 30 days
    scope: Session cookie
    text: The session cookie expires after 30 days.
  - period: 90 days
    scope: AI tool audit log
    text: For each call we keep an audit log entry (time, tool name, result status and duration; never arguments, e-mail addresses or message text) for 90 days
  - period: null
    scope: Chat transcripts
    text: We do not store chat transcripts in the app database.
  rights:
  - right: Access, correction, export, deletion
    text: You may request access, correction, export or deletion of your data at any time
  - right: Complaint
    text: You may lodge a complaint with the Czech Office for Personal Data Protection (uoou.cz).
  role:
    text: the data controller for account data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data, use it for advertising or use it to train AI models.
  subprocessors:
    text: 'We rely on: Vercel (hosting), Supabase (the PostgreSQL database, stored in the EU — Paris, France), Google Firebase (authentication; Firebase Analytics for anonymous usage statistics and error reports after you accept the cookie notice), Microsoft Clarity (anonymised session replays and heatmaps to improve usability; typed text is masked, cookies only after you accept the cookie notice), Google Ads (conversion measurement — whether a subscription followed an ad click; cookies only after you accept the cookie notice), Stripe (Stripe Payments Europe, Ltd.; payments), Resend (e-mail delivery), OpenAI (the website AI assistant and ChatGPT integration; the data needed for these features is described in sections 7 and 8), unavatar.io (public avatars).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cold Leads
provenance_date: '2026-11-09'
provider_name: Cold Leads
provider_slug: coldleads-app
slug: coldleads-app-privacy-policy
source_date: '2026-11-09'
source_filename: coldleads-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coldleads.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cold Leads\naid: coldleads-app\nurl: https://coldleads.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the data controller for account data.\ndata_categories:\n- category: identifying\n  text: 'Account data: your name, e-mail address and authentication identifier received from the sign-in method\n    you choose'\n- category: contact\n  text: 'Contact data you add: names, e-mail addresses, phone numbers, companies, social profile links, tags, notes\n    and interaction history of your business contacts.'\n- category: device\n  text: 'Technical data: a session cookie required for\
  \ sign-in and basic server logs (IP address, time) for security\n    and rate limiting.'\n- category: financial\n  text: we store only payment and subscription identifiers, never card numbers.\n- category: communication\n  text: Messages you type in the chat are sent to OpenAI to generate the reply\npurposes:\n- purpose: Provide the Service\n  text: 'Solely to provide the Service: authenticating you, storing your CRM data, sending the e-mail campaigns\n    you explicitly launch, and generating drafts with AI.'\n- purpose: Advertising\n  text: We do not sell personal data and do not use it for advertising.\nretention:\n- scope: Account data\n  period: null\n  text: Data is kept while your account is active.\n- scope: Session cookie\n  period: 30 days\n  text: The session cookie expires after 30 days.\n- scope: AI tool audit log\n  period: 90 days\n  text: For each call we keep an audit log entry (time, tool name, result status and duration; never arguments,\n    e-mail addresses or message\
  \ text) for 90 days\n- scope: Chat transcripts\n  period: null\n  text: We do not store chat transcripts in the app database.\nresidency:\n- region: European Union\n  text: Supabase (the PostgreSQL database, stored in the EU — Paris, France)\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We rely on: Vercel (hosting), Supabase (the PostgreSQL database, stored in the EU — Paris, France), Google\n    Firebase (authentication; Firebase Analytics for anonymous usage statistics and error reports after you accept\n    the cookie notice), Microsoft Clarity (anonymised session replays and heatmaps to improve usability; typed text\n    is masked, cookies only after you accept the cookie notice), Google Ads (conversion measurement — whether a\n    subscription followed an ad click; cookies only after you accept the cookie notice), Stripe (Stripe Payments\n    Europe, Ltd.; payments), Resend (e-mail delivery), OpenAI (the website AI assistant and ChatGPT integration;\n    the data needed for\
  \ these features is described in sections 7 and 8), unavatar.io (public avatars).'\ndpa:\n  available: true\n  url: coldleads.app/terms/dpa\n  text: For your contacts' data we act as your processor under the Data Processing Agreement (coldleads.app/terms/dpa).\ndeletion:\n  route: E-mail to support@coldleads.app or via Help → Send a report\n  text: You may request access, correction, export or deletion of your data at any time by e-mail to the address\n    above or via Help → Send a report; we respond within 30 days.\nrights:\n- right: Access, correction, export, deletion\n  text: You may request access, correction, export or deletion of your data at any time\n- right: Complaint\n  text: You may lodge a complaint with the Czech Office for Personal Data Protection (uoou.cz).\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data, use it for advertising or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/coldleads-app/privacy/coldleads-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Cold Leads's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Software-as-a-Service
- Small Business
- Lead Management
- Cold Leads
---
