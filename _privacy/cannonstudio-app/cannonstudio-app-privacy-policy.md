---
api_specs:
- filename: cannonstudio-app-openapi-generated.yml
  format: yaml
  label: Cannon Studio API
  slug: cannonstudio-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cannonstudio-app/openapi/_ae-authored/cannonstudio-app-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and profile information, such as your email address, display name, authentication identifiers, account settings, verification status, and creator-program profile details
  - category: financial
    text: Billing and commercial information, such as Stripe customer IDs, App Store and Google Play purchase metadata, subscription status, billing events, invoices, purchase history, credits granted or consumed, refund or dispute metadata, and support records related to purchases
  - category: behavioral
    text: User content and media, including prompts, scripts, images, videos, audio, narration text, uploaded references, composer timelines, project data, generated outputs, and submission metadata for public or shared features
  - category: biometric
    text: voice samples may be treated as biometric-related data under some laws
  - category: device
    text: browser or device details, mobile app platform, app version, approximate location inferred from IP, IP-address-linked request logs, crash and error information, and security events
  - category: location
    text: approximate location inferred from IP
  - category: communication
    text: Marketing, referral, and attribution data, such as creator referral codes, UTM parameters, ad-click or campaign attribution data, lifecycle email state, and communication preferences
  deletion:
    route: Account Settings deletion request, or email chase@cannonstudio.app
    text: You can start an account deletion request from Account Settings, or contact us at chase@cannonstudio.app for privacy-related rights requests, marketing opt-outs, or deletion requests.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate users and manage accounts
    text: Authenticate users and manage accounts
  - purpose: Process payments and billing
    text: Process payments, subscriptions, credit purchases, and billing support
  - purpose: Route prompts to AI or infrastructure providers
    text: Route prompts, media, and settings to AI or infrastructure providers needed to fulfill requested features
  - purpose: Fraud and abuse prevention
    text: Track credits, enforce feature limits, detect abuse, and prevent fraud
  - purpose: Measure advertising and campaign performance
    text: Measure referral, advertising, and campaign performance, including signup and conversion attribution
  residency:
  - region: United States and other countries
    text: Cannon Studio and its providers may process and store information in the United States and other countries.
  retention:
  - period: null
    scope: account information, billing records, generation history
    text: We retain account information, billing records, and generation history for as long as reasonably necessary to provide the service
  rights:
  - right: access
    text: you may have rights to access, correct, delete, or request a copy of certain personal information
  - right: opt out of marketing
    text: and to opt out of certain marketing communications
  - right: portability
    text: or to opt out of certain sales, sharing, or targeted advertising uses
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: We do not sell personal information for money.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cannon Studio
provenance_date: '2026-11-09'
provider_name: Cannon Studio
provider_slug: cannonstudio-app
slug: cannonstudio-app-privacy-policy
source_date: '2026-11-09'
source_filename: cannonstudio-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cannonstudio.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cannon Studio\naid: cannonstudio-app\nurl: https://www.cannonstudio.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and profile information, such as your email address, display name, authentication identifiers, account\n    settings, verification status, and creator-program profile details\n- category: financial\n  text: Billing and commercial information, such as Stripe customer IDs, App Store and Google Play purchase metadata,\n    subscription status, billing events, invoices, purchase history, credits granted or\
  \ consumed, refund or dispute\n    metadata, and support records related to purchases\n- category: behavioral\n  text: User content and media, including prompts, scripts, images, videos, audio, narration text, uploaded references,\n    composer timelines, project data, generated outputs, and submission metadata for public or shared features\n- category: biometric\n  text: voice samples may be treated as biometric-related data under some laws\n- category: device\n  text: browser or device details, mobile app platform, app version, approximate location inferred from IP, IP-address-linked\n    request logs, crash and error information, and security events\n- category: location\n  text: approximate location inferred from IP\n- category: communication\n  text: Marketing, referral, and attribution data, such as creator referral codes, UTM parameters, ad-click or campaign\n    attribution data, lifecycle email state, and communication preferences\npurposes:\n- purpose: Authenticate users and\
  \ manage accounts\n  text: Authenticate users and manage accounts\n- purpose: Process payments and billing\n  text: Process payments, subscriptions, credit purchases, and billing support\n- purpose: Route prompts to AI or infrastructure providers\n  text: Route prompts, media, and settings to AI or infrastructure providers needed to fulfill requested features\n- purpose: Fraud and abuse prevention\n  text: Track credits, enforce feature limits, detect abuse, and prevent fraud\n- purpose: Measure advertising and campaign performance\n  text: Measure referral, advertising, and campaign performance, including signup and conversion attribution\nretention:\n- scope: account information, billing records, generation history\n  period: null\n  text: We retain account information, billing records, and generation history for as long as reasonably necessary\n    to provide the service\nresidency:\n- region: United States and other countries\n  text: Cannon Studio and its providers may process and\
  \ store information in the United States and other countries.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account Settings deletion request, or email chase@cannonstudio.app\n  text: You can start an account deletion request from Account Settings, or contact us at chase@cannonstudio.app\n    for privacy-related rights requests, marketing opt-outs, or deletion requests.\nrights:\n- right: access\n  text: you may have rights to access, correct, delete, or request a copy of certain personal information\n- right: opt out of marketing\n  text: and to opt out of certain marketing communications\n- right: portability\n  text: or to opt out of certain sales, sharing, or targeted advertising uses\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell personal information for money.\n"
source_yaml_url: https://artifacts.apis.io/cannonstudio-app/privacy/cannonstudio-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 18 quoted statements, read from Cannon Studio's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Production
- Advertising
- Content Creation
- Multimedia
---
