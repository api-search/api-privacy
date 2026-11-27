---
api_specs:
- filename: buzzmebro-com-applications-api-openapi.yml
  format: yaml
  label: BuzzMeBro Applications API
  slug: buzzmebro-com-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-applications-api-openapi.yml
- filename: buzzmebro-com-check-api-openapi.yml
  format: yaml
  label: BuzzMeBro Check API
  slug: buzzmebro-com-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-check-api-openapi.yml
- filename: buzzmebro-com-info-api-openapi.yml
  format: yaml
  label: BuzzMeBro Info API
  slug: buzzmebro-com-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-info-api-openapi.yml
- filename: buzzmebro-com-me-api-openapi.yml
  format: yaml
  label: BuzzMeBro Me API
  slug: buzzmebro-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-me-api-openapi.yml
- filename: buzzmebro-com-setups-api-openapi.yml
  format: yaml
  label: BuzzMeBro Setups API
  slug: buzzmebro-com-setups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-setups-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your phone number , and the phone number of every person on your resident list.
  - category: identifying
    text: A name, if you give one. It is optional
  - category: location
    text: Where your apartment is — your postal or ZIP code, your unit label as your building lists it, and your building’s address.
  - category: communication
    text: 'A record of each buzz : when it started, what happened (answered, opened, missed), who opened the door, and how long it took.'
  - category: financial
    text: Billing records — your Stripe customer and subscription identifiers, invoice status and referral credits.
  - category: behavioral
    text: Anonymous visit counts We count visits to our public pages and the steps of signing up
  - category: device
    text: whether it was a phone or a computer
  deletion:
    route: Email privacy@buzzmebro.com to ask us to delete your account and its personal information
    text: ask us to delete your account and its personal information, subject to records we are required to keep, and to the append-only buzz log described above
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: We use the information above to provide the service, verify that a phone belongs to the person adding it, buy and operate your number, take payment, prevent fraud and abuse, answer your support requests, and meet legal obligations.
  - purpose: Promotional messages with consent
    text: Promotional messages are sent only with express opt-in under Canada’s anti-spam legislation (CASL)
  - purpose: Advertising measurement via Google Ads
    text: To learn which of them actually lead to sign-ups, Google’s ad tag loads on our public pages
  residency:
  - region: Canada / United States
    text: Supabase Database, authentication and file storage Canada / United States
  - region: United States
    text: Several of the providers above process data in the United States.
  retention:
  - period: while your account is open
    scope: Account and resident list
    text: 'Your account and resident list : while your account is open.'
  - period: 15 days after cancellation
    scope: Buzzer number
    text: 'Your buzzer number : held for 15 days after cancellation so you can change your mind, then released.'
  - period: 30 days
    scope: AI assistant setups
    text: the record is deleted 30 days after the assistant created it.
  - period: null
    scope: Billing records
    text: 'Billing records : kept as long as Canadian tax and accounting law requires.'
  rights:
  - right: Access
    text: ask what personal information we hold about you and get a copy
  - right: Correction
    text: have inaccurate information corrected
  - right: Withdraw consent
    text: withdraw consent, including for promotional messages, at any time
  - right: Deletion
    text: ask us to delete your account and its personal information
  - right: Complain
    text: complain to us, and to the Office of the Privacy Commissioner of Canada
  role:
    text: BuzzMeBro , Toronto, Ontario, Canada
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, license or trade your personal information.
  subprocessors:
    text: Provider What they do for us Where they process Supabase Database, authentication and file storage Canada / United States Twilio Placing and bridging the buzzer calls, sending SMS, and checking whether a number is a mobile line United States
    url: null
  transfers:
  - mechanism: other
    text: We use providers that commit to appropriate contractual protections
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BuzzMeBro
provenance_date: '2026-11-09'
provider_name: BuzzMeBro
provider_slug: buzzmebro-com
slug: buzzmebro-com-privacy-policy
source_date: '2026-11-09'
source_filename: buzzmebro-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://buzzmebro.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BuzzMeBro\naid: buzzmebro-com\nurl: https://buzzmebro.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: BuzzMeBro , Toronto, Ontario, Canada\ndata_categories:\n- category: identifying\n  text: Your phone number , and the phone number of every person on your resident list.\n- category: identifying\n  text: A name, if you give one. It is optional\n- category: location\n  text: Where your apartment is — your postal or ZIP code, your unit label as your building lists it, and your building’s\n    address.\n- category: communication\n  text: 'A record of each buzz : when it started, what\
  \ happened (answered, opened, missed), who opened the door,\n    and how long it took.'\n- category: financial\n  text: Billing records — your Stripe customer and subscription identifiers, invoice status and referral credits.\n- category: behavioral\n  text: Anonymous visit counts We count visits to our public pages and the steps of signing up\n- category: device\n  text: whether it was a phone or a computer\npurposes:\n- purpose: Provide the service\n  text: We use the information above to provide the service, verify that a phone belongs to the person adding it,\n    buy and operate your number, take payment, prevent fraud and abuse, answer your support requests, and meet legal\n    obligations.\n- purpose: Promotional messages with consent\n  text: Promotional messages are sent only with express opt-in under Canada’s anti-spam legislation (CASL)\n- purpose: Advertising measurement via Google Ads\n  text: To learn which of them actually lead to sign-ups, Google’s ad tag loads on our public\
  \ pages\nretention:\n- scope: Account and resident list\n  period: while your account is open\n  text: 'Your account and resident list : while your account is open.'\n- scope: Buzzer number\n  period: 15 days after cancellation\n  text: 'Your buzzer number : held for 15 days after cancellation so you can change your mind, then released.'\n- scope: AI assistant setups\n  period: 30 days\n  text: the record is deleted 30 days after the assistant created it.\n- scope: Billing records\n  period: null\n  text: 'Billing records : kept as long as Canadian tax and accounting law requires.'\nresidency:\n- region: Canada / United States\n  text: Supabase Database, authentication and file storage Canada / United States\n- region: United States\n  text: Several of the providers above process data in the United States.\ntransfers:\n- mechanism: other\n  text: We use providers that commit to appropriate contractual protections\nsubprocessors:\n  url: null\n  text: Provider What they do for us Where\
  \ they process Supabase Database, authentication and file storage Canada\n    / United States Twilio Placing and bridging the buzzer calls, sending SMS, and checking whether a number is\n    a mobile line United States\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@buzzmebro.com to ask us to delete your account and its personal information\n  text: ask us to delete your account and its personal information, subject to records we are required to keep,\n    and to the append-only buzz log described above\nrights:\n- right: Access\n  text: ask what personal information we hold about you and get a copy\n- right: Correction\n  text: have inaccurate information corrected\n- right: Withdraw consent\n  text: withdraw consent, including for promotional messages, at any time\n- right: Deletion\n  text: ask us to delete your account and its personal information\n- right: Complain\n  text: complain to us, and to the Office of the Privacy Commissioner of Canada\n\
  sale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, license or trade your personal information.\n"
source_yaml_url: https://artifacts.apis.io/buzzmebro-com/privacy/buzzmebro-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from BuzzMeBro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Buzzer
- Apartments
- Access
- Subscription
- Toronto
---
