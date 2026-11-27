---
api_specs:
- filename: deploy-social-account-api-openapi.yml
  format: yaml
  label: deploy.social Account API
  slug: deploy-social-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-account-api-openapi.yml
- filename: deploy-social-destinations-api-openapi.yml
  format: yaml
  label: deploy.social Destinations API
  slug: deploy-social-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-destinations-api-openapi.yml
- filename: deploy-social-media-api-openapi.yml
  format: yaml
  label: deploy.social Media API
  slug: deploy-social-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-media-api-openapi.yml
- filename: deploy-social-posts-api-openapi.yml
  format: yaml
  label: deploy.social Posts API
  slug: deploy-social-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-posts-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, display name, and — if you use password sign-in — a hashed password (we can’t read it).
  - category: contact
    text: Email address, display name, and — if you use password sign-in — a hashed password (we can’t read it).
  - category: behavioral
    text: Pages visited, buttons clicked, and recordings of sessions, collected with PostHog so we can see where people get stuck.
  - category: device
    text: When you sign in, on the web or in the app, we keep a rough note of the device and network it came from, so you can spot a sign-in that wasn’t you.
  - category: financial
    text: If you’re on a paid plan, your payment details are collected and processed by Stripe, Inc. — card numbers never reach our servers.
  - category: communication
    text: Whether you want emails when a deployment finishes or fails, plus in-app notification history.
  deletion:
    route: Delete account from Profile in account settings, or email hello@deploy.social
    text: 'Your whole account: delete it yourself, any time, from Profile in your account settings — account, media, credentials, API keys and connected apps, gone immediately.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Log in and reach you
    text: This is how you log in and how we reach you.
  - purpose: Publishing content
    text: We store them so we can convert your videos and photos into each platform’s required format and publish your posts where you tell us to.
  - purpose: Advertising conversion measurement
    text: we advertise deploy.social on Google and in ChatGPT, with Google and OpenAI measuring which ads lead to sign-ups.
  residency:
  - region: USA
    text: PostHog stores this in the USA, and it’s used only by us, to improve the product.
  retention:
  - period: within 7 days
    scope: Post statistics after disconnecting account
    text: They're deleted when the post is removed, and within 7 days of you disconnecting the account.
  - period: at most 3 hours
    scope: Pre-signup video, cover and caption
    text: The video, cover frame and caption are kept for at most 3 hours.
  - period: within 30 days
    scope: Account deletion requests by email
    text: Prefer email? Write to hello@deploy.social and we’ll do it for you within 30 days.
  - period: null
    scope: Product analytics
    text: We keep it after an account is deleted, so we can learn what got in someone’s way and fix it.
  rights:
  - right: Access, correction and deletion
    text: you have the right to know what personal information we hold about you, to get a copy of it, to have it corrected or deleted, and to opt out of its sale or sharing.
  - right: Opt out of sharing
    text: 'You can opt out of that sharing two ways: Global Privacy Control. We honor it.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell personal information, and we never have.
  subprocessors:
    text: We run on a small set of service providers (“subprocessors”).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: deploy.social
provenance_date: '2026-11-09'
provider_name: deploy.social
provider_slug: deploy-social
slug: deploy-social-privacy-policy
source_date: '2026-11-09'
source_filename: deploy-social-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://deploy.social/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: deploy.social\naid: deploy-social\nurl: https://deploy.social/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, display name, and — if you use password sign-in — a hashed password (we can’t read it).\n- category: contact\n  text: Email address, display name, and — if you use password sign-in — a hashed password (we can’t read it).\n- category: behavioral\n  text: Pages visited, buttons clicked, and recordings of sessions, collected with PostHog so we can see where people\n    get stuck.\n- category: device\n  text:\
  \ When you sign in, on the web or in the app, we keep a rough note of the device and network it came from,\n    so you can spot a sign-in that wasn’t you.\n- category: financial\n  text: If you’re on a paid plan, your payment details are collected and processed by Stripe, Inc. — card numbers\n    never reach our servers.\n- category: communication\n  text: Whether you want emails when a deployment finishes or fails, plus in-app notification history.\npurposes:\n- purpose: Log in and reach you\n  text: This is how you log in and how we reach you.\n- purpose: Publishing content\n  text: We store them so we can convert your videos and photos into each platform’s required format and publish\n    your posts where you tell us to.\n- purpose: Advertising conversion measurement\n  text: we advertise deploy.social on Google and in ChatGPT, with Google and OpenAI measuring which ads lead to\n    sign-ups.\nretention:\n- scope: Post statistics after disconnecting account\n  period: within 7 days\n\
  \  text: They're deleted when the post is removed, and within 7 days of you disconnecting the account.\n- scope: Pre-signup video, cover and caption\n  period: at most 3 hours\n  text: The video, cover frame and caption are kept for at most 3 hours.\n- scope: Account deletion requests by email\n  period: within 30 days\n  text: Prefer email? Write to hello@deploy.social and we’ll do it for you within 30 days.\n- scope: Product analytics\n  period: null\n  text: We keep it after an account is deleted, so we can learn what got in someone’s way and fix it.\nresidency:\n- region: USA\n  text: PostHog stores this in the USA, and it’s used only by us, to improve the product.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We run on a small set of service providers (“subprocessors”).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account from Profile in account settings, or email hello@deploy.social\n  text: 'Your whole account: delete it yourself, any time,\
  \ from Profile in your account settings — account, media,\n    credentials, API keys and connected apps, gone immediately.'\nrights:\n- right: Access, correction and deletion\n  text: you have the right to know what personal information we hold about you, to get a copy of it, to have it\n    corrected or deleted, and to opt out of its sale or sharing.\n- right: Opt out of sharing\n  text: 'You can opt out of that sharing two ways: Global Privacy Control. We honor it.'\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell personal information, and we never have.\n"
source_yaml_url: https://artifacts.apis.io/deploy-social/privacy/deploy-social-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from deploy.social's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Video
- Short-Form Video
- Cross-Posting
- Scheduling
- Content Publishing
- MCP
---
