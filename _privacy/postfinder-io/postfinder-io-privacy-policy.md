---
api_specs:
- filename: postfinder-io-nearby-api-openapi.yml
  format: yaml
  label: Postfinder Nearby API
  slug: postfinder-io-nearby-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-nearby-api-openapi.yml
- filename: postfinder-io-places-api-openapi.yml
  format: yaml
  label: Postfinder Places API
  slug: postfinder-io-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-places-api-openapi.yml
- filename: postfinder-io-postcodes-api-openapi.yml
  format: yaml
  label: Postfinder Postcodes API
  slug: postfinder-io-postcodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-postcodes-api-openapi.yml
- filename: postfinder-io-reference-api-openapi.yml
  format: yaml
  label: Postfinder Reference API
  slug: postfinder-io-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-reference-api-openapi.yml
- filename: postfinder-io-search-api-openapi.yml
  format: yaml
  label: Postfinder Search API
  slug: postfinder-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postfinder-io/openapi/postfinder-io-search-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: your IP address, the page you asked for including anything in its address such as a search or a postcode, your browser's user agent and the time
  - category: contact
    text: The contact form asks for your name, email address and message.
  - category: identifying
    text: An account keeps your email address, the handle you choose, and a hash of your password made with Argon2, never the password itself.
  - category: location
    text: The position is rounded to about 100 metres before it leaves your device, and is only used to find what is nearby.
  - category: device
    text: A reviewer cookie, pf_reviewer , holds a random token for one year, so your next review carries the same name
  deletion:
    route: Delete it yourself from /account/delete
    text: Delete it yourself from /account/delete . That deletes your email address, password, passkeys, photos and every session straight away.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: keep the site running and deal with abuse
    text: We use them to keep the site running and to deal with abuse, and for nothing else.
  - purpose: find nearby places
    text: is only used to find what is nearby
  - purpose: prevent repeated reviews from one address
    text: To stop one address sending hundreds of reviews, we keep a hash of your IP address rather than the address itself
  - purpose: verify a person is submitting a form
    text: Turnstile, the check that a person rather than a script is sending a form
  residency:
  - region: Australia
    text: DigitalOcean runs our servers, database and photo storage, in Sydney.
  - region: outside Australia
    text: Some of these process data outside Australia, including in the United States.
  retention:
  - period: at most 30 days
    scope: server logs
    text: These go into server logs, which are kept for at most 30 days and then deleted.
  - period: until you delete the account
    scope: account and photos
    text: 'Your account and photos: until you delete the account.'
  - period: for as long as the place's page exists
    scope: reviews and daily hash
    text: 'Reviews, and the daily hash kept with them: for as long as the place''s page exists.'
  - period: until it is decided
    scope: fix or new place email
    text: 'An email given with a fix or a new place: until it is decided.'
  - period: null
    scope: contact form messages
    text: 'Contact form messages: as long as it takes to deal with them.'
  rights:
  - right: copy of data
    text: you can ask us for a copy of what we hold about you
  - right: correction
    text: to correct it
  - right: deletion
    text: to delete it
  - right: stop using / object
    text: to stop using it, and object to how we use it
  - right: complain to data protection authority
    text: If you are in the United Kingdom or the European Union, you can also complain to your data protection authority.
  role:
    text: PostFinder (postfinder.io) is a directory of post offices, parcel lockers and post boxes.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell or share what we keep for anyone else's use.
  subprocessors:
    text: 'Who else is involved These services handle data for the site, each for one job:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Postfinder
provenance_date: '2026-11-10'
provider_name: Postfinder
provider_slug: postfinder-io
slug: postfinder-io-privacy-policy
source_date: '2026-11-10'
source_filename: postfinder-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://postfinder.io/en/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Postfinder\naid: postfinder-io\nurl: https://postfinder.io/en/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: PostFinder (postfinder.io) is a directory of post offices, parcel lockers and post boxes.\ndata_categories:\n- category: identifying\n  text: your IP address, the page you asked for including anything in its address such as a search or a postcode,\n    your browser's user agent and the time\n- category: contact\n  text: The contact form asks for your name, email address and message.\n- category: identifying\n  text: An account keeps your email address, the handle you choose,\
  \ and a hash of your password made with Argon2,\n    never the password itself.\n- category: location\n  text: The position is rounded to about 100 metres before it leaves your device, and is only used to find what\n    is nearby.\n- category: device\n  text: A reviewer cookie, pf_reviewer , holds a random token for one year, so your next review carries the same\n    name\npurposes:\n- purpose: keep the site running and deal with abuse\n  text: We use them to keep the site running and to deal with abuse, and for nothing else.\n- purpose: find nearby places\n  text: is only used to find what is nearby\n- purpose: prevent repeated reviews from one address\n  text: To stop one address sending hundreds of reviews, we keep a hash of your IP address rather than the address\n    itself\n- purpose: verify a person is submitting a form\n  text: Turnstile, the check that a person rather than a script is sending a form\nretention:\n- scope: server logs\n  period: at most 30 days\n  text: These go\
  \ into server logs, which are kept for at most 30 days and then deleted.\n- scope: account and photos\n  period: until you delete the account\n  text: 'Your account and photos: until you delete the account.'\n- scope: reviews and daily hash\n  period: for as long as the place's page exists\n  text: 'Reviews, and the daily hash kept with them: for as long as the place''s page exists.'\n- scope: fix or new place email\n  period: until it is decided\n  text: 'An email given with a fix or a new place: until it is decided.'\n- scope: contact form messages\n  period: null\n  text: 'Contact form messages: as long as it takes to deal with them.'\nresidency:\n- region: Australia\n  text: DigitalOcean runs our servers, database and photo storage, in Sydney.\n- region: outside Australia\n  text: Some of these process data outside Australia, including in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Who else is involved These services handle data for the site, each for one\
  \ job:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete it yourself from /account/delete\n  text: Delete it yourself from /account/delete . That deletes your email address, password, passkeys, photos and\n    every session straight away.\nrights:\n- right: copy of data\n  text: you can ask us for a copy of what we hold about you\n- right: correction\n  text: to correct it\n- right: deletion\n  text: to delete it\n- right: stop using / object\n  text: to stop using it, and object to how we use it\n- right: complain to data protection authority\n  text: If you are in the United Kingdom or the European Union, you can also complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell or share what we keep for anyone else's use.\n"
source_yaml_url: https://artifacts.apis.io/postfinder-io/privacy/postfinder-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Postfinder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Address
- Autocomplete
- Logistics
- Australia
---
