---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account record: user ID, email, name if you give one, plan and join date.'
  - category: contact
    text: 'Checklist and updates form: sends your address, the boxes you ticked and campaign details (UTM tags, ad click ID, landing page, referrer), never your resume.'
  - category: financial
    text: We store the order, amount, currency, customer ID, billing period and this month's Pro voice calls.
  - category: location
    text: 'DataFast (cookieless): page URLs, referrers, browser, approximate location and a short-lived random ID.'
  - category: device
    text: 'Our own analytics (Trailpost) , from atsprep.com: page, referrer, UTM tags, browser, device, screen width, language and approximate location'
  - category: communication
    text: 'Mail to it comes to us: we read the sender, subject and words to mark a job confirmed or answered'
  deletion:
    route: Account deletion or email to support@atsprep.com
    text: Deleting your account removes synced data, your record and sign-in from our servers at once; browser copies stay until you clear them.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Matching and AI requests
    text: Match and AI requests never include your name, email, phone, address or links.
  - purpose: Account sync
    text: 'Sync: saved versions, your working draft, tracker jobs and Pip call reports with everything typed in them'
  - purpose: Analytics
    text: 'Our own analytics (Trailpost) , from atsprep.com: page, referrer, UTM tags, browser, device, screen width, language and approximate location'
  - purpose: Payments
    text: Polar is our payment processor and merchant of record.
  residency:
  - region: EU (Ireland)
    text: 'Where: Supabase, our processor, in the EU (Ireland).'
  retention:
  - period: null
    scope: Resume files
    text: 'Resume files: never received.'
  - period: up to a day
    scope: Job postings
    text: 'Job postings: up to a day.'
  - period: 13 months
    scope: Raw analytics events
    text: 'Raw analytics events: 13 months.'
  - period: until you delete the account
    scope: Account and synced data
    text: 'Account and synced data: until you delete the account.'
  rights:
  - right: See, correct or delete
    text: You can see, correct or delete your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 'No selling, no training: we never sell your resume or train models on it.'
  subprocessors:
    text: 'Who processes it Cloudflare: hosting, AI and speech ( policy ). Supabase (EU): accounts, sync, match, email records ( policy ). ElevenLabs: Pip''s voice ( policy ). Google: sign-in ( policy ). Resend: email ( policy ). DataFast: analytics ( cookieless mode ). Polar : payments.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ATSPrep
provenance_date: '2026-11-09'
provider_name: ATSPrep
provider_slug: atsprep-com
slug: atsprep-com-privacy-policy
source_date: '2026-11-09'
source_filename: atsprep-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://atsprep.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ATSPrep\naid: atsprep-com\nurl: https://atsprep.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account record: user ID, email, name if you give one, plan and join date.'\n- category: contact\n  text: 'Checklist and updates form: sends your address, the boxes you ticked and campaign details (UTM tags, ad\n    click ID, landing page, referrer), never your resume.'\n- category: financial\n  text: We store the order, amount, currency, customer ID, billing period and this month's Pro voice calls.\n- category: location\n  text:\
  \ 'DataFast (cookieless): page URLs, referrers, browser, approximate location and a short-lived random ID.'\n- category: device\n  text: 'Our own analytics (Trailpost) , from atsprep.com: page, referrer, UTM tags, browser, device, screen width,\n    language and approximate location'\n- category: communication\n  text: 'Mail to it comes to us: we read the sender, subject and words to mark a job confirmed or answered'\npurposes:\n- purpose: Matching and AI requests\n  text: Match and AI requests never include your name, email, phone, address or links.\n- purpose: Account sync\n  text: 'Sync: saved versions, your working draft, tracker jobs and Pip call reports with everything typed in them'\n- purpose: Analytics\n  text: 'Our own analytics (Trailpost) , from atsprep.com: page, referrer, UTM tags, browser, device, screen width,\n    language and approximate location'\n- purpose: Payments\n  text: Polar is our payment processor and merchant of record.\nretention:\n- scope: Resume files\n\
  \  period: null\n  text: 'Resume files: never received.'\n- scope: Job postings\n  period: up to a day\n  text: 'Job postings: up to a day.'\n- scope: Raw analytics events\n  period: 13 months\n  text: 'Raw analytics events: 13 months.'\n- scope: Account and synced data\n  period: until you delete the account\n  text: 'Account and synced data: until you delete the account.'\nresidency:\n- region: EU (Ireland)\n  text: 'Where: Supabase, our processor, in the EU (Ireland).'\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Who processes it Cloudflare: hosting, AI and speech ( policy ). Supabase (EU): accounts, sync, match, email\n    records ( policy ). ElevenLabs: Pip''s voice ( policy ). Google: sign-in ( policy ). Resend: email ( policy\n    ). DataFast: analytics ( cookieless mode ). Polar : payments.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or email to support@atsprep.com\n  text: Deleting your account removes synced data, your record\
  \ and sign-in from our servers at once; browser copies\n    stay until you clear them.\nrights:\n- right: See, correct or delete\n  text: You can see, correct or delete your data.\nsale_or_sharing:\n  stance: prohibited\n  text: 'No selling, no training: we never sell your resume or train models on it.'\n"
source_yaml_url: https://artifacts.apis.io/atsprep-com/privacy/atsprep-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from ATSPrep's own page on 2026-11-09.
synthetic: false
tags:
- Resume Builder
- Job-Tracker
- Careers
- Applicant Tracking
---
