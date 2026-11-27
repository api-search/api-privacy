---
api_specs:
- filename: unprofane-com-api-openapi.json
  format: json
  label: Unprofane API API
  slug: unprofane-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unprofane-com/openapi/_original/unprofane-com-api-openapi.json
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address , to sign you in and to send quota and billing notices
  - category: identifying
    text: Your API keys , as their SHA-256 hashes with the prefix and last four characters.
  - category: location
    text: the visitor's country, as Cloudflare reads it from the address, and the page are kept with the text
  - category: behavioral
    text: which pages a visit opens, what it presses, how fast the pages load, the errors a page hits
  - category: communication
    text: the text of each check on the API's check, batch and MCP routes
  deletion:
    route: dashboard account deletion
    text: Deleting the account from the dashboard removes everything under it, projects, keys, lists, usage rows, corrections and sessions, within 24 hours
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: improve the engine
    text: 'It is used to improve the engine: its word lists, the questions it asks the model, its thresholds, and how often it flags clean text.'
  - purpose: account sign-in and notices
    text: to sign you in and to send quota and billing notices and our answers to your corrections
  - purpose: site analytics
    text: To learn what helps a visitor and what loses them, this site uses PostHog
  retention:
  - period: 90 days
    scope: kept texts
    text: 'For how long: 90 days.'
  - period: while the account exists
    scope: account data
    text: Account data is kept while the account exists.
  - period: 30 days
    scope: database backups
    text: A nightly copy of the database is kept for 30 days for recovery and then deleted
  - period: 30 days
    scope: analytics recordings
    text: PostHog keeps recordings for 30 days.
  rights:
  - right: data export
    text: The dashboard's settings page exports everything we hold about your account as JSON
  - right: change email
    text: changes the email address
  - right: deletion of a check's text
    text: send us the check id and we delete that text
  role:
    text: In data protection law that company is the controller for your account data and your processor for the text you send, and the controller of the copy it keeps to improve the engine.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Nothing is sold, shared for advertising, or sent anywhere else, but for the ad click above, which goes back to Google, whose ad it was.
  subprocessors:
    text: Six companies, each named on the subprocessors page with what it receives
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: unprofane-com
provenance_date: '2026-11-10'
provider_name: unprofane-com
provider_slug: unprofane-com
slug: unprofane-com-privacy-policy
source_date: '2026-11-10'
source_filename: unprofane-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://unprofane.com/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: unprofane-com\naid: unprofane-com\nurl: https://unprofane.com/legal/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In data protection law that company is the controller for your account data and your processor for the text\n    you send, and the controller of the copy it keeps to improve the engine.\ndata_categories:\n- category: contact\n  text: Your email address , to sign you in and to send quota and billing notices\n- category: identifying\n  text: Your API keys , as their SHA-256 hashes with the prefix and last four characters.\n- category: location\n  text: the visitor's country,\
  \ as Cloudflare reads it from the address, and the page are kept with the text\n- category: behavioral\n  text: which pages a visit opens, what it presses, how fast the pages load, the errors a page hits\n- category: communication\n  text: the text of each check on the API's check, batch and MCP routes\npurposes:\n- purpose: improve the engine\n  text: 'It is used to improve the engine: its word lists, the questions it asks the model, its thresholds, and\n    how often it flags clean text.'\n- purpose: account sign-in and notices\n  text: to sign you in and to send quota and billing notices and our answers to your corrections\n- purpose: site analytics\n  text: To learn what helps a visitor and what loses them, this site uses PostHog\nretention:\n- scope: kept texts\n  period: 90 days\n  text: 'For how long: 90 days.'\n- scope: account data\n  period: while the account exists\n  text: Account data is kept while the account exists.\n- scope: database backups\n  period: 30 days\n  text:\
  \ A nightly copy of the database is kept for 30 days for recovery and then deleted\n- scope: analytics recordings\n  period: 30 days\n  text: PostHog keeps recordings for 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Six companies, each named on the subprocessors page with what it receives\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard account deletion\n  text: Deleting the account from the dashboard removes everything under it, projects, keys, lists, usage rows,\n    corrections and sessions, within 24 hours\nrights:\n- right: data export\n  text: The dashboard's settings page exports everything we hold about your account as JSON\n- right: change email\n  text: changes the email address\n- right: deletion of a check's text\n  text: send us the check id and we delete that text\nsale_or_sharing:\n  stance: conditional\n  text: Nothing is sold, shared for advertising, or sent anywhere else, but for the ad click above, which\
  \ goes back\n    to Google, whose ad it was.\n"
source_yaml_url: https://artifacts.apis.io/unprofane-com/privacy/unprofane-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from unprofane-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Profanity Filtering
- Content Moderation
- Machine Learning
- Safety
---
