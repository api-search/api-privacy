---
api_specs:
- filename: outcrawl-scrape-api-openapi.yml
  format: yaml
  label: Outcrawl Scrape API
  slug: outcrawl-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outcrawl/openapi/outcrawl-scrape-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in with Google or GitHub we receive the name, email address and avatar your account there makes available
  - category: financial
    text: our payment processor collects your card or bank details directly and passes us back only what we need to keep your account current, not the full card number
  - category: location
    text: your browser, device and approximate location (worked out from your IP address)
  - category: behavioral
    text: the pages you visit and the page that sent you, what you click
  - category: communication
    text: Anything you send us by email or through the console when you ask for help.
  deletion:
    route: Write to hello@outcrawl.ai
    text: Write to hello@outcrawl.ai and we will act on a request within the time the law where you live requires
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: 'To operate the service: authenticate you, route and meter your requests, run the browser sessions your tasks need, and show you the console and your usage.'
  - purpose: billing
    text: To bill you and keep the ledger on your billing page accurate.
  - purpose: security
    text: To keep the service secure, including detecting the kind of misuse our terms describe.
  - purpose: improve service
    text: To learn which pages and features help people get started, and to find and fix what breaks.
  residency:
  - region: United States
    text: Outcrawl is a United States company, and the providers above run infrastructure mainly in the United States
  retention:
  - period: null
    scope: account information
    text: We keep account information for as long as your account is active, and for a limited period afterwards to meet accounting and legal obligations and to restore an account closed by mistake.
  - period: the period your plan sets
    scope: session recordings
    text: A session recording is kept for the period your plan sets, shown with its expiry date against that recording in your console, and is deleted automatically once it expires.
  - period: 30 days
    scope: PostHog recordings
    text: PostHog deletes a recording of how you used the site after 30 days.
  - period: null
    scope: secrets
    text: A secret you store stays until you delete it.
  rights:
  - right: access
    text: you may have the right to ask for a copy of the personal data we hold about you
  - right: correction
    text: to have it corrected
  - right: deletion
    text: to have it deleted
  - right: objection or restriction
    text: to object to or restrict some of what we do with it
  - right: portability
    text: to receive it in a portable format
  - right: complain to authority
    text: you also have the right to complain to your local data protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: Google Sign-in, if you choose it, and reCAPTCHA on the sign-in page GitHub Sign-in, if you choose it Vercel Hosts the application you are using Supabase Runs the database behind your account, usage and billing records
    url: null
  transfers:
  - mechanism: other
    text: Where the law where you live requires a specific safeguard for that transfer, we put it in place before the transfer happens.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Outcrawl
provenance_date: '2026-11-10'
provider_name: Outcrawl
provider_slug: outcrawl
slug: outcrawl-privacy-policy
source_date: '2026-11-10'
source_filename: outcrawl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://outcrawl.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Outcrawl\naid: outcrawl\nurl: https://outcrawl.ai/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign in with Google or GitHub we receive the name, email address and avatar your account there\n    makes available\n- category: financial\n  text: our payment processor collects your card or bank details directly and passes us back only what we need to\n    keep your account current, not the full card number\n- category: location\n  text: your browser, device and approximate location (worked out from your IP address)\n\
  - category: behavioral\n  text: the pages you visit and the page that sent you, what you click\n- category: communication\n  text: Anything you send us by email or through the console when you ask for help.\npurposes:\n- purpose: operate the service\n  text: 'To operate the service: authenticate you, route and meter your requests, run the browser sessions your\n    tasks need, and show you the console and your usage.'\n- purpose: billing\n  text: To bill you and keep the ledger on your billing page accurate.\n- purpose: security\n  text: To keep the service secure, including detecting the kind of misuse our terms describe.\n- purpose: improve service\n  text: To learn which pages and features help people get started, and to find and fix what breaks.\nretention:\n- scope: account information\n  period: null\n  text: We keep account information for as long as your account is active, and for a limited period afterwards to\n    meet accounting and legal obligations and to restore an account\
  \ closed by mistake.\n- scope: session recordings\n  period: the period your plan sets\n  text: A session recording is kept for the period your plan sets, shown with its expiry date against that recording\n    in your console, and is deleted automatically once it expires.\n- scope: PostHog recordings\n  period: 30 days\n  text: PostHog deletes a recording of how you used the site after 30 days.\n- scope: secrets\n  period: null\n  text: A secret you store stays until you delete it.\nresidency:\n- region: United States\n  text: Outcrawl is a United States company, and the providers above run infrastructure mainly in the United States\ntransfers:\n- mechanism: other\n  text: Where the law where you live requires a specific safeguard for that transfer, we put it in place before\n    the transfer happens.\nsubprocessors:\n  url: null\n  text: Google Sign-in, if you choose it, and reCAPTCHA on the sign-in page GitHub Sign-in, if you choose it Vercel\n    Hosts the application you are using\
  \ Supabase Runs the database behind your account, usage and billing records\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hello@outcrawl.ai\n  text: Write to hello@outcrawl.ai and we will act on a request within the time the law where you live requires\nrights:\n- right: access\n  text: you may have the right to ask for a copy of the personal data we hold about you\n- right: correction\n  text: to have it corrected\n- right: deletion\n  text: to have it deleted\n- right: objection or restriction\n  text: to object to or restrict some of what we do with it\n- right: portability\n  text: to receive it in a portable format\n- right: complain to authority\n  text: you also have the right to complain to your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/outcrawl/privacy/outcrawl-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Outcrawl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Web Infrastructure
- Data Extraction
- Automation
---
