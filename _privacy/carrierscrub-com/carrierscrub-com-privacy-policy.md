---
api_specs:
- filename: carrierscrub-com-authority-history-api-openapi.yml
  format: yaml
  label: CarrierScrub Authority History API
  slug: carrierscrub-com-authority-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-authority-history-api-openapi.yml
- filename: carrierscrub-com-batch-api-openapi.yml
  format: yaml
  label: CarrierScrub Batch API
  slug: carrierscrub-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-batch-api-openapi.yml
- filename: carrierscrub-com-fmcsa-activity-api-openapi.yml
  format: yaml
  label: CarrierScrub Fmcsa Activity API
  slug: carrierscrub-com-fmcsa-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-fmcsa-activity-api-openapi.yml
- filename: carrierscrub-com-lookup-api-openapi.yml
  format: yaml
  label: CarrierScrub Lookup API
  slug: carrierscrub-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carrierscrub-com/openapi/carrierscrub-com-lookup-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in with Google we store the name, email address and profile picture Google returns.
  - category: contact
    text: When you sign in with an emailed link we store your email address
  - category: communication
    text: If you write to us through the contact page, or by email to one of our @carrierscrub.com addresses, we store what you send, including any attachments.
  - category: location
    text: a keyed hash of your IP address that we use only to enforce daily limits.
  - category: behavioral
    text: 'Microsoft Clarity shows how the site is used, as heatmaps and session replays: clicks, scrolling, mouse movement and the text on each page'
  - category: financial
    text: Stripe and Link receive your name, email, billing address and payment details to take the payment
  deletion:
    route: Email privacy@carrierscrub.com from the account address to ask for deletion
    text: you may ask for a copy of your account data, or ask us to delete your account, by writing to privacy@carrierscrub.com from the email address on the account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run requested checks and billing
    text: To run the checks you request, keep your lookup history and watchlist, generate and verify print packets, bill your plan
  - purpose: Measure site use and sales
    text: so we can see which pages and campaigns lead to sales
  retention:
  - period: for as long as your brokerage's account exists
    scope: Lookup history, Shield checks, watchlist, packets and notifications
    text: Lookup history, Shield checks, watchlist, packets and notifications are kept for as long as your brokerage's account exists
  - period: 90 days after their last message
    scope: Public chat conversations
    text: Public chat conversations are deleted 90 days after their last message.
  rights:
  - right: Copy of account data
    text: you may ask for a copy of your account data
  - right: Deletion of account
    text: ask us to delete your account
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell lookup data, we never sell or share the phone numbers you run through Shield
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CarrierScrub
provenance_date: '2026-11-09'
provider_name: CarrierScrub
provider_slug: carrierscrub-com
slug: carrierscrub-com-privacy-policy
source_date: '2026-11-09'
source_filename: carrierscrub-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carrierscrub.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CarrierScrub\naid: carrierscrub-com\nurl: https://carrierscrub.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign in with Google we store the name, email address and profile picture Google returns.\n- category: contact\n  text: When you sign in with an emailed link we store your email address\n- category: communication\n  text: If you write to us through the contact page, or by email to one of our @carrierscrub.com addresses, we store\n    what you send, including any attachments.\n- category: location\n  text: a\
  \ keyed hash of your IP address that we use only to enforce daily limits.\n- category: behavioral\n  text: 'Microsoft Clarity shows how the site is used, as heatmaps and session replays: clicks, scrolling, mouse\n    movement and the text on each page'\n- category: financial\n  text: Stripe and Link receive your name, email, billing address and payment details to take the payment\npurposes:\n- purpose: Run requested checks and billing\n  text: To run the checks you request, keep your lookup history and watchlist, generate and verify print packets,\n    bill your plan\n- purpose: Measure site use and sales\n  text: so we can see which pages and campaigns lead to sales\nretention:\n- scope: Lookup history, Shield checks, watchlist, packets and notifications\n  period: for as long as your brokerage's account exists\n  text: Lookup history, Shield checks, watchlist, packets and notifications are kept for as long as your brokerage's\n    account exists\n- scope: Public chat conversations\n\
  \  period: 90 days after their last message\n  text: Public chat conversations are deleted 90 days after their last message.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@carrierscrub.com from the account address to ask for deletion\n  text: you may ask for a copy of your account data, or ask us to delete your account, by writing to privacy@carrierscrub.com\n    from the email address on the account\nrights:\n- right: Copy of account data\n  text: you may ask for a copy of your account data\n- right: Deletion of account\n  text: ask us to delete your account\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell lookup data, we never sell or share the phone numbers you run through Shield\n"
source_yaml_url: https://artifacts.apis.io/carrierscrub-com/privacy/carrierscrub-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from CarrierScrub's own page on 2026-11-09.
synthetic: false
tags:
- carrier-vetting
- Freight Brokerage
- FMCSA Data
---
