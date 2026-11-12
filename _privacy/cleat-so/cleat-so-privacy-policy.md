---
api_specs:
- filename: cleat-so-lines-api-openapi.yml
  format: yaml
  label: Cleat Lines API
  slug: cleat-so-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleat-so/openapi/cleat-so-lines-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your name, email address and password.'
  - category: financial
    text: 'Payments: Stripe handles your card. We keep a Stripe customer reference and each line’s subscription status.'
  - category: communication
    text: 'Texts your lines receive: the sender, the message, when it arrived and any code we detect in it.'
  - category: biometric
    text: 'Identity verification: your ID document and selfie go to our identity verification provider, Stripe or Didit, which checks them.'
  - category: location
    text: your country, state or province, and city, from our hosting provider’s network location (never a street or a precise position)
  - category: device
    text: your device type and your browser and operating system families (never versions or the full browser string)
  deletion:
    route: Delete your account in Settings; or email contact@cleat.so
    text: Delete your account in Settings; it removes the workspaces you own and their texts.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run Cleat
    text: set up lines, show your texts and deliver them where you ask
  - purpose: verify identities and prevent fraud
    text: to verify identities and prevent fraud and abuse
  - purpose: billing
    text: to bill you
  - purpose: understand and test pages
    text: to understand which pages and campaigns bring people to Cleat, and to test versions of our pages
  - purpose: legal obligations
    text: to meet legal obligations
  residency:
  - region: United States
    text: We process data in the United States.
  retention:
  - period: null
    scope: account data, texts and call transcripts
    text: Account data, texts and call transcripts are kept until you delete the workspace or your account.
  - period: two years
    scope: call recordings and transcripts
    text: Call recordings and their transcripts are kept for two years from the call
  - period: 25 months
    scope: visit measurement
    text: page views, sessions and campaign visits are deleted after 25 months
  - period: a year
    scope: email metadata
    text: kept for a year so we can help when one doesn’t arrive
  rights:
  - right: copy, correction or deletion
    text: Ask for a copy of your data, a correction or a deletion by writing to contact@cleat.so .
  - right: further rights by jurisdiction
    text: Depending on where you live, for example California, the EU or the UK, you may have further rights, and we’ll honour them as the law requires.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cleat
provenance_date: '2026-11-09'
provider_name: Cleat
provider_slug: cleat-so
slug: cleat-so-privacy-policy
source_date: '2026-11-09'
source_filename: cleat-so-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cleat.so/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cleat\naid: cleat-so\nurl: https://cleat.so/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account: your name, email address and password.'\n- category: financial\n  text: 'Payments: Stripe handles your card. We keep a Stripe customer reference and each line’s subscription status.'\n- category: communication\n  text: 'Texts your lines receive: the sender, the message, when it arrived and any code we detect in it.'\n- category: biometric\n  text: 'Identity verification: your ID document and selfie go to our identity verification\
  \ provider, Stripe or\n    Didit, which checks them.'\n- category: location\n  text: your country, state or province, and city, from our hosting provider’s network location (never a street\n    or a precise position)\n- category: device\n  text: your device type and your browser and operating system families (never versions or the full browser string)\npurposes:\n- purpose: run Cleat\n  text: set up lines, show your texts and deliver them where you ask\n- purpose: verify identities and prevent fraud\n  text: to verify identities and prevent fraud and abuse\n- purpose: billing\n  text: to bill you\n- purpose: understand and test pages\n  text: to understand which pages and campaigns bring people to Cleat, and to test versions of our pages\n- purpose: legal obligations\n  text: to meet legal obligations\nretention:\n- scope: account data, texts and call transcripts\n  period: null\n  text: Account data, texts and call transcripts are kept until you delete the workspace or your account.\n\
  - scope: call recordings and transcripts\n  period: two years\n  text: Call recordings and their transcripts are kept for two years from the call\n- scope: visit measurement\n  period: 25 months\n  text: page views, sessions and campaign visits are deleted after 25 months\n- scope: email metadata\n  period: a year\n  text: kept for a year so we can help when one doesn’t arrive\nresidency:\n- region: United States\n  text: We process data in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account in Settings; or email contact@cleat.so\n  text: Delete your account in Settings; it removes the workspaces you own and their texts.\nrights:\n- right: copy, correction or deletion\n  text: Ask for a copy of your data, a correction or a deletion by writing to contact@cleat.so .\n- right: further rights by jurisdiction\n  text: Depending on where you live, for example California, the\
  \ EU or the UK, you may have further rights, and\n    we’ll honour them as the law requires.\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell your data.\n"
source_yaml_url: https://artifacts.apis.io/cleat-so/privacy/cleat-so-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Cleat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- Phone Numbers
- Verification Codes
- Two-Factor Authentication
- Webhooks
- Telephony
---
