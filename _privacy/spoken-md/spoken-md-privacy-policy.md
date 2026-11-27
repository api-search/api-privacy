---
api_specs:
- filename: spoken-md-transcripts-api-openapi.yml
  format: yaml
  label: Podcast Transcripts API
  slug: podcast-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spoken-md/openapi/spoken-md-transcripts-api-openapi.yml
- filename: spoken-md-well-known-openapi.json
  format: json
  label: Podcast Transcripts API .well-known API
  slug: podcast-transcripts-api-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spoken-md/openapi/_original/spoken-md-well-known-openapi.json
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address and name — as you enter them at Stripe checkout.
  - category: financial
    text: Credit balance and usage — the credits remaining on your key, and a record of which episodes that key has fetched and when.
  - category: device
    text: Cached transcripts — transcripts are cached to improve response times.
  - category: communication
    text: 'The app sends us only what each request needs: your search text, or the id of the show or episode you asked for.'
  deletion:
    route: Email support@spoken.md
    text: You can request deletion of your personal data at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate API requests and track credit usage
    text: To authenticate API requests and track credit usage
  - purpose: Deliver API key after purchase
    text: To deliver your API key after purchase
  - purpose: Process payments via Stripe
    text: To process payments via Stripe
  - purpose: Send service emails
    text: To send the service emails described below
  - purpose: Site usage analytics
    text: To understand site usage via analytics
  residency:
  - region: Ireland (eu-west-1)
    text: Spoken runs on Amazon Web Services in the Ireland region (eu-west-1).
  retention:
  - period: as long as the key is active
    scope: API key, credit balance and usage record
    text: Your API key, credit balance and usage record are retained as long as the key is active, because they are what the service runs on.
  - period: 90 days without use
    scope: AI app connection
    text: A connection to an AI app is retained until you disconnect it or it has gone 90 days without use, whichever comes first.
  - period: indefinitely
    scope: Cached transcripts
    text: Cached transcripts are retained indefinitely to improve performance
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Export
    text: Export your data in a portable format
  - right: Object
    text: Object to processing
  role:
    text: We are the data controller for the personal data described below.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, share, or rent your data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: spoken-md
provenance_date: '2026-11-10'
provider_name: spoken-md
provider_slug: spoken-md
slug: spoken-md-privacy-policy
source_date: '2026-11-10'
source_filename: spoken-md-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://spoken.md/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: spoken-md\naid: spoken-md\nurl: https://spoken.md/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the personal data described below.\ndata_categories:\n- category: identifying\n  text: Email address and name — as you enter them at Stripe checkout.\n- category: financial\n  text: Credit balance and usage — the credits remaining on your key, and a record of which episodes that key has\n    fetched and when.\n- category: device\n  text: Cached transcripts — transcripts are cached to improve response times.\n- category: communication\n  text: 'The app\
  \ sends us only what each request needs: your search text, or the id of the show or episode you asked\n    for.'\npurposes:\n- purpose: Authenticate API requests and track credit usage\n  text: To authenticate API requests and track credit usage\n- purpose: Deliver API key after purchase\n  text: To deliver your API key after purchase\n- purpose: Process payments via Stripe\n  text: To process payments via Stripe\n- purpose: Send service emails\n  text: To send the service emails described below\n- purpose: Site usage analytics\n  text: To understand site usage via analytics\nretention:\n- scope: API key, credit balance and usage record\n  period: as long as the key is active\n  text: Your API key, credit balance and usage record are retained as long as the key is active, because they are\n    what the service runs on.\n- scope: AI app connection\n  period: 90 days without use\n  text: A connection to an AI app is retained until you disconnect it or it has gone 90 days without use, whichever\n\
  \    comes first.\n- scope: Cached transcripts\n  period: indefinitely\n  text: Cached transcripts are retained indefinitely to improve performance\nresidency:\n- region: Ireland (eu-west-1)\n  text: Spoken runs on Amazon Web Services in the Ireland region (eu-west-1).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@spoken.md\n  text: You can request deletion of your personal data at any time\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Export\n  text: Export your data in a portable format\n- right: Object\n  text: Object to processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, share, or rent your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/spoken-md/privacy/spoken-md-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from spoken-md's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Transcripts
- Markdown
- Artificial Intelligence
---
