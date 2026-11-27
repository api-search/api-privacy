---
api_specs:
- filename: ainsof-io-openapi-generated.yml
  format: yaml
  label: AINSOF API
  slug: ainsof-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ainsof-io/openapi/_ae-authored/ainsof-io-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: each download records which edit it was, your account ID and email
  - category: contact
    text: your name and email, your message, the links, and any screenshot or file you attach
  - category: financial
    text: the amounts charged, and Paddle's transaction, subscription and customer IDs
  - category: device
    text: your browser’s user agent
  - category: behavioral
    text: a record of each track you downloaded
  - category: communication
    text: your message, as it arrives in our mailbox
  deletion:
    route: email request to info@ainsof.io
    text: Email info@ainsof.io and we will tell you what we hold about you, correct it, or delete it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the search and improve matching
    text: To run the search, and to improve matching
  - purpose: rate limiting and request grouping
    text: Rate limiting and request grouping.
  - purpose: accounting and tax
    text: and for our accounting and tax
  residency:
  - region: European Union (Frankfurt)
    text: Request logs and the catalog are held on Supabase infrastructure in the European Union (Frankfurt, eu-central-1 ).
  retention:
  - period: indefinitely
    scope: request logs
    text: Request logs currently have no fixed automatic deletion date and may be retained indefinitely for operating and improving the service, unless deletion is requested.
  - period: 30 days
    scope: analyze_video stills, transcript and reduced-resolution copy
    text: a reduced-resolution copy of the video for 30 days
  - period: seven days
    scope: score_my_video render
    text: The render is scheduled for automated deletion after seven days
  rights:
  - right: access, correction and deletion
    text: Email info@ainsof.io and we will tell you what we hold about you, correct it, or delete it.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data
  subprocessors:
    text: 'These are the only parties who see any part of a request, and each sees it solely to deliver the service you asked for:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AINSOF
provenance_date: '2026-11-09'
provider_name: AINSOF
provider_slug: ainsof-io
slug: ainsof-io-privacy-policy
source_date: '2026-11-09'
source_filename: ainsof-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ainsof.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AINSOF\naid: ainsof-io\nurl: https://ainsof.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: each download records which edit it was, your account ID and email\n- category: contact\n  text: your name and email, your message, the links, and any screenshot or file you attach\n- category: financial\n  text: the amounts charged, and Paddle's transaction, subscription and customer IDs\n- category: device\n  text: your browser’s user agent\n- category: behavioral\n  text: a record of each track you downloaded\n- category: communication\n\
  \  text: your message, as it arrives in our mailbox\npurposes:\n- purpose: run the search and improve matching\n  text: To run the search, and to improve matching\n- purpose: rate limiting and request grouping\n  text: Rate limiting and request grouping.\n- purpose: accounting and tax\n  text: and for our accounting and tax\nretention:\n- scope: request logs\n  period: indefinitely\n  text: Request logs currently have no fixed automatic deletion date and may be retained indefinitely for operating\n    and improving the service, unless deletion is requested.\n- scope: analyze_video stills, transcript and reduced-resolution copy\n  period: 30 days\n  text: a reduced-resolution copy of the video for 30 days\n- scope: score_my_video render\n  period: seven days\n  text: The render is scheduled for automated deletion after seven days\nresidency:\n- region: European Union (Frankfurt)\n  text: Request logs and the catalog are held on Supabase infrastructure in the European Union (Frankfurt, eu-central-1\n\
  \    ).\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'These are the only parties who see any part of a request, and each sees it solely to deliver the service\n    you asked for:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to info@ainsof.io\n  text: Email info@ainsof.io and we will tell you what we hold about you, correct it, or delete it.\nrights:\n- right: access, correction and deletion\n  text: Email info@ainsof.io and we will tell you what we hold about you, correct it, or delete it.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your data\n"
source_yaml_url: https://artifacts.apis.io/ainsof-io/privacy/ainsof-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from AINSOF's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Artificial Intelligence
- Licensing
- Media
---
