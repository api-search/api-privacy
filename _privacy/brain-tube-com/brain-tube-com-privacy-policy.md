---
api_specs:
- filename: brain-tube-com-api-openapi.json
  format: json
  label: BrainTube REST API API
  slug: braintube-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brain-tube-com/openapi/_original/brain-tube-com-api-openapi.json
claim_count: 20
description: ''
doc:
  data_categories:
  - category: behavioral
    text: we store the URLs, titles, and content summaries of pages you explicitly save
  - category: communication
    text: For YouTube videos, we also store transcripts and AI-generated summaries.
  - category: identifying
    text: the connected account's name and email
  - category: behavioral
    text: we measure how the product is used so we can find and fix what isn't working
  deletion:
    route: Email privacy@brain-tube.com to delete entire account; delete individual items in app
    text: To delete your entire account and all associated data, email privacy@brain-tube.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Search, AI chat and metadata enrichment
    text: Synced content is stored in BrainTube's database and processed for search, AI chat, and metadata enrichment.
  - purpose: Show and import YouTube playlists
    text: only to show you your playlists and to import the videos you pick into your own BrainTube library
  - purpose: Product analytics
    text: to record product-analytics events such as page views and feature usage
  - purpose: Advertising measurement and remarketing
    text: to measure which of our ads bring visitors and sign-ups, and to show BrainTube ads to people who have visited our sites before
  residency:
  - region: EU
    text: PostHog, hosted in the EU, to record product-analytics events such as page views and feature usage.
  retention:
  - period: within 30 days
    scope: YouTube data on account deletion
    text: Deleting your account (email privacy@brain-tube.com ) deletes all YouTube data we hold within 30 days.
  - period: 12 months
    scope: bt_acq cookie
    text: a first-party cookie named bt_acq for 12 months
  - period: 90 days
    scope: bt_partner_ref cookie
    text: a bt_partner_ref cookie stores that partner code for 90 days
  - period: 30 days
    scope: bt_signed_in cookie
    text: we set a first-party cookie named bt_signed_in on brain-tube.com for 30 days
  - period: while your account exists
    scope: Retrieval and tool-call logs
    text: The retrieval log and the tool-call log are kept while your account exists, and all of this is deleted with your account.
  rights:
  - right: Object to product analytics
    text: You can object at any time by emailing privacy@brain-tube.com, and we will stop sending events for your account.
  - right: Withdraw consent for cookies
    text: can change your mind at any time from Cookie settings in the footer
  - right: Revoke YouTube access
    text: You can also revoke BrainTube's access at any time on your Google Account permissions page
  role:
    text: VR EXPRESS OOD is the controller of the personal data processed through BrainTube.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data, and we do not show ads inside BrainTube.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BrainTube
provenance_date: '2026-11-09'
provider_name: BrainTube
provider_slug: brain-tube-com
slug: brain-tube-com-privacy-policy
source_date: '2026-11-09'
source_filename: brain-tube-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://brain-tube.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BrainTube\naid: brain-tube-com\nurl: https://brain-tube.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: VR EXPRESS OOD is the controller of the personal data processed through BrainTube.\ndata_categories:\n- category: behavioral\n  text: we store the URLs, titles, and content summaries of pages you explicitly save\n- category: communication\n  text: For YouTube videos, we also store transcripts and AI-generated summaries.\n- category: identifying\n  text: the connected account's name and email\n- category: behavioral\n  text: we measure how the product is used so we can find and\
  \ fix what isn't working\npurposes:\n- purpose: Search, AI chat and metadata enrichment\n  text: Synced content is stored in BrainTube's database and processed for search, AI chat, and metadata enrichment.\n- purpose: Show and import YouTube playlists\n  text: only to show you your playlists and to import the videos you pick into your own BrainTube library\n- purpose: Product analytics\n  text: to record product-analytics events such as page views and feature usage\n- purpose: Advertising measurement and remarketing\n  text: to measure which of our ads bring visitors and sign-ups, and to show BrainTube ads to people who have visited\n    our sites before\nretention:\n- scope: YouTube data on account deletion\n  period: within 30 days\n  text: Deleting your account (email privacy@brain-tube.com ) deletes all YouTube data we hold within 30 days.\n- scope: bt_acq cookie\n  period: 12 months\n  text: a first-party cookie named bt_acq for 12 months\n- scope: bt_partner_ref cookie\n  period:\
  \ 90 days\n  text: a bt_partner_ref cookie stores that partner code for 90 days\n- scope: bt_signed_in cookie\n  period: 30 days\n  text: we set a first-party cookie named bt_signed_in on brain-tube.com for 30 days\n- scope: Retrieval and tool-call logs\n  period: while your account exists\n  text: The retrieval log and the tool-call log are kept while your account exists, and all of this is deleted with\n    your account.\nresidency:\n- region: EU\n  text: PostHog, hosted in the EU, to record product-analytics events such as page views and feature usage.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@brain-tube.com to delete entire account; delete individual items in app\n  text: To delete your entire account and all associated data, email privacy@brain-tube.com .\nrights:\n- right: Object to product analytics\n  text: You can object at any time by emailing privacy@brain-tube.com, and we\
  \ will stop sending events for your\n    account.\n- right: Withdraw consent for cookies\n  text: can change your mind at any time from Cookie settings in the footer\n- right: Revoke YouTube access\n  text: You can also revoke BrainTube's access at any time on your Google Account permissions page\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your data, and we do not show ads inside BrainTube.\n"
source_yaml_url: https://artifacts.apis.io/brain-tube-com/privacy/brain-tube-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from BrainTube's own page on 2026-11-09.
synthetic: false
tags:
- AI Integration
- MCP
---
