---
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: The URL you ask us to test. It is the input to the service, so it is processed and appears in operational logs.
  - category: financial
    text: Payment details. A transaction hash and amount on Base.
  - category: device
    text: Request metadata. Including IP address and user agent, used for rate limiting and abuse prevention.
  deletion:
    route: contact the provider with the URL and approximate test time
    text: If you need a specific request's logs removed, contact us with the URL and roughly when it was tested and we will remove it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: debugging and abuse prevention
    text: The 20 signals and the Markdown, kept briefly for debugging and abuse prevention.
  - purpose: rate limiting and abuse prevention
    text: Including IP address and user agent, used for rate limiting and abuse prevention.
  retention:
  - period: a short operational window
    scope: parsed content and results
    text: Parsed content and results are retained for a short operational window for debugging and abuse review, then discarded.
  - period: longer
    scope: aggregate counters
    text: Aggregate counters — request counts, error rates, spend — are kept longer because they contain no page content.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No sale of data. Not to anyone, for any purpose.
  subprocessors:
    text: Who else is involved Cloudflare — hosting and request handling for the service. The x402 facilitator — verifies and settles the USDC payment on Base.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: NanoParse
provenance_date: '2026-11-10'
provider_name: NanoParse
provider_slug: nanoparse
slug: nanoparse-privacy-policy
source_date: '2026-11-10'
source_filename: nanoparse-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nanoparse.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: NanoParse\naid: nanoparse\nurl: https://nanoparse.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: The URL you ask us to test. It is the input to the service, so it is processed and appears in operational\n    logs.\n- category: financial\n  text: Payment details. A transaction hash and amount on Base.\n- category: device\n  text: Request metadata. Including IP address and user agent, used for rate limiting and abuse prevention.\npurposes:\n- purpose: debugging and abuse prevention\n  text: The 20 signals and the Markdown, kept\
  \ briefly for debugging and abuse prevention.\n- purpose: rate limiting and abuse prevention\n  text: Including IP address and user agent, used for rate limiting and abuse prevention.\nretention:\n- scope: parsed content and results\n  period: a short operational window\n  text: Parsed content and results are retained for a short operational window for debugging and abuse review, then\n    discarded.\n- scope: aggregate counters\n  period: longer\n  text: Aggregate counters — request counts, error rates, spend — are kept longer because they contain no page content.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who else is involved Cloudflare — hosting and request handling for the service. The x402 facilitator — verifies\n    and settles the USDC payment on Base.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact the provider with the URL and approximate test time\n  text: If you need a specific request's logs removed, contact us with\
  \ the URL and roughly when it was tested and\n    we will remove it.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No sale of data. Not to anyone, for any purpose.\n"
source_yaml_url: https://artifacts.apis.io/nanoparse/privacy/nanoparse-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 10 quoted statements, read from NanoParse's own page on 2026-11-10.
synthetic: false
tags:
- Web Parsing
- AI Agents
- Markdown Conversion
- Litmus Scoring
- Crypto Payments
---
