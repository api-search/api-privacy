---
api_specs:
- filename: choruskeepsake-com-openapi.yml
  format: yaml
  label: Chorus API
  slug: chorus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/choruskeepsake-com/openapi/choruskeepsake-com-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: you give an email address, your name and a password
  - category: contact
    text: If you order a printed book you give a postal address
  - category: financial
    text: Payment is taken by Stripe, and your card details never reach us.
  - category: communication
    text: a voice recording or a written message
  - category: behavioral
    text: PostHog counts visits and the steps people take on the website.
  - category: device
    text: the address the call came from
  deletion:
    route: Account in the app
    text: The organiser can remove any single recording, or delete the account and everything in it, from Account in the app.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Measure site visits and ad performance
    text: so we can see which posts, ads and searches bring people to Chorus
  - purpose: Provide service through providers
    text: Each of them handles your information only to do that job for us.
  retention:
  - period: Until you say otherwise
    scope: Book and recordings
    text: Until you say otherwise
  - period: for a day
    scope: Chat note in browser
    text: If you close the bubble with its X, it remembers that for a day.
  rights:
  - right: Access
    text: You can ask to see what we hold about you
  - right: Correction
    text: have it corrected
  - right: Deletion
    text: have it deleted
  - right: Portability
    text: or take it with you
  - right: Complaint to supervisory authority
    text: If you are in the EU you can also complain to the Data Protection Commission in Ireland.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell anything about you, and nobody outside the providers named below ever sees it.
  subprocessors:
    text: Supabase hosts the database and the files.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chorus Keepsake
provenance_date: '2026-11-09'
provider_name: Chorus Keepsake
provider_slug: choruskeepsake-com
slug: choruskeepsake-com-privacy-policy
source_date: '2026-11-09'
source_filename: choruskeepsake-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://choruskeepsake.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chorus Keepsake\naid: choruskeepsake-com\nurl: https://choruskeepsake.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: you give an email address, your name and a password\n- category: contact\n  text: If you order a printed book you give a postal address\n- category: financial\n  text: Payment is taken by Stripe, and your card details never reach us.\n- category: communication\n  text: a voice recording or a written message\n- category: behavioral\n  text: PostHog counts visits and the steps people take on the website.\n- category:\
  \ device\n  text: the address the call came from\npurposes:\n- purpose: Measure site visits and ad performance\n  text: so we can see which posts, ads and searches bring people to Chorus\n- purpose: Provide service through providers\n  text: Each of them handles your information only to do that job for us.\nretention:\n- scope: Book and recordings\n  period: Until you say otherwise\n  text: Until you say otherwise\n- scope: Chat note in browser\n  period: for a day\n  text: If you close the bubble with its X, it remembers that for a day.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Supabase hosts the database and the files.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account in the app\n  text: The organiser can remove any single recording, or delete the account and everything in it, from Account\n    in the app.\nrights:\n- right: Access\n  text: You can ask to see what we hold about you\n- right: Correction\n  text: have it corrected\n\
  - right: Deletion\n  text: have it deleted\n- right: Portability\n  text: or take it with you\n- right: Complaint to supervisory authority\n  text: If you are in the EU you can also complain to the Data Protection Commission in Ireland.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell anything about you, and nobody outside the providers named below ever sees it.\n"
source_yaml_url: https://artifacts.apis.io/choruskeepsake-com/privacy/choruskeepsake-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Chorus Keepsake's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Memories
- Gifts
- PhotoBook
- Voice
- Video
---
