---
api_specs:
- filename: flightpowers-com-account-api-openapi.yml
  format: yaml
  label: flightpowers-com Account API
  slug: flightpowers-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-account-api-openapi.yml
- filename: flightpowers-com-flights-api-openapi.yml
  format: yaml
  label: flightpowers-com Flights API
  slug: flightpowers-com-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-flights-api-openapi.yml
- filename: flightpowers-com-hotels-api-openapi.yml
  format: yaml
  label: flightpowers-com Hotels API
  slug: flightpowers-com-hotels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-hotels-api-openapi.yml
- filename: flightpowers-com-verify-api-openapi.yml
  format: yaml
  label: flightpowers-com Verify API
  slug: flightpowers-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flightpowers-com/openapi/flightpowers-com-verify-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: If you sign in with Google, we keep your name, email address, profile picture, and when you signed up and last visited.
  - category: behavioral
    text: To learn which pages and tools are actually useful, the site records interaction events
  - category: device
    text: PostHog's script also sends its standard details
  - category: location
    text: PostHog receives your IP address, which it can use to estimate your location.
  deletion:
    route: contact the site owner by email or the contact page
    text: To have yours deleted, ask us (see Questions).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: analytics
    text: To learn which pages and tools are actually useful, the site records interaction events
  - purpose: campaign attribution
    text: so we can tell whether a post we wrote actually sent anyone here
  - purpose: debugging failed searches
    text: so we can find and fix the problem
  residency:
  - region: EU
    text: The demo uses PostHog (EU servers) for analytics
  retention:
  - period: until we delete them
    scope: failed flight search inputs
    text: 'There is no automatic deletion yet: they are kept until we delete them.'
  - period: about a day
    scope: flights API backend logs
    text: Our flights API backend's logs include the search itself and are kept for about a day.
  - period: 3 hours
    scope: demo conversation and results cache
    text: The conversation and its results are kept in a cache for 3 hours
  rights:
  - right: deletion
    text: or want your data deleted, ask directly
  - right: objection to statistics
    text: write to app@flightpowers.com to object
  - right: opt out of emails
    text: Opting out takes effect immediately and needs no reason.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: flightpowers-com
provenance_date: '2026-11-09'
provider_name: flightpowers-com
provider_slug: flightpowers-com
slug: flightpowers-com-privacy-policy
source_date: '2026-11-09'
source_filename: flightpowers-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flightpowers.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: flightpowers-com\naid: flightpowers-com\nurl: https://flightpowers.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: If you sign in with Google, we keep your name, email address, profile picture, and when you signed up and\n    last visited.\n- category: behavioral\n  text: To learn which pages and tools are actually useful, the site records interaction events\n- category: device\n  text: PostHog's script also sends its standard details\n- category: location\n  text: PostHog receives your IP address, which it can use to estimate\
  \ your location.\npurposes:\n- purpose: analytics\n  text: To learn which pages and tools are actually useful, the site records interaction events\n- purpose: campaign attribution\n  text: so we can tell whether a post we wrote actually sent anyone here\n- purpose: debugging failed searches\n  text: so we can find and fix the problem\nretention:\n- scope: failed flight search inputs\n  period: until we delete them\n  text: 'There is no automatic deletion yet: they are kept until we delete them.'\n- scope: flights API backend logs\n  period: about a day\n  text: Our flights API backend's logs include the search itself and are kept for about a day.\n- scope: demo conversation and results cache\n  period: 3 hours\n  text: The conversation and its results are kept in a cache for 3 hours\nresidency:\n- region: EU\n  text: The demo uses PostHog (EU servers) for analytics\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: contact the site owner by email or the contact page\n  text: To have yours deleted, ask us (see Questions).\nrights:\n- right: deletion\n  text: or want your data deleted, ask directly\n- right: objection to statistics\n  text: write to app@flightpowers.com to object\n- right: opt out of emails\n  text: Opting out takes effect immediately and needs no reason.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/flightpowers-com/privacy/flightpowers-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from flightpowers-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Data
- Flights
- Hotels
---
