---
api_specs:
- filename: freqblog-com-audio-api-openapi.yml
  format: yaml
  label: freqblog-com Audio API
  slug: freqblog-com-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-audio-api-openapi.yml
- filename: freqblog-com-backfill-api-openapi.yml
  format: yaml
  label: freqblog-com Backfill API
  slug: freqblog-com-backfill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-backfill-api-openapi.yml
- filename: freqblog-com-catalog-api-openapi.yml
  format: yaml
  label: freqblog-com Catalog API
  slug: freqblog-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-catalog-api-openapi.yml
- filename: freqblog-com-me-api-openapi.yml
  format: yaml
  label: freqblog-com Me API
  slug: freqblog-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-me-api-openapi.yml
- filename: freqblog-com-request-free-key-api-openapi.yml
  format: yaml
  label: freqblog-com Request Free Key API
  slug: freqblog-com-request-free-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-request-free-key-api-openapi.yml
- filename: freqblog-com-spotify-compat-api-openapi.yml
  format: yaml
  label: freqblog-com Spotify Compat API
  slug: freqblog-com-spotify-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-spotify-compat-api-openapi.yml
- filename: freqblog-com-system-api-openapi.yml
  format: yaml
  label: freqblog-com System API
  slug: freqblog-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-system-api-openapi.yml
- filename: freqblog-com-utility-api-openapi.yml
  format: yaml
  label: freqblog-com Utility API
  slug: freqblog-com-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freqblog-com/openapi/freqblog-com-utility-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address & name Music API account creation; to contact you about your account or service changes; to deliver purchased products
  - category: contact
    text: Contact us at [email protected] for any privacy-related queries.
  - category: financial
    text: Billing information To process subscription and one-off payments. Card details are handled directly by Stripe — we never see or store card numbers.
  - category: location
    text: It is also used to derive an approximate country for fraud review.
  - category: device
    text: Origin IP address One IP address per API key — the address seen at signup, or on the first authenticated call for keys created through checkout — is recorded against that key
  - category: behavioral
    text: Signals derived from the data above — signup and request IP addresses (including the network an IPv6 address belongs to), signup timing, email-address patterns, request patterns such as which tracks or artists are requested, and quota usage
  - category: communication
    text: Email preferences & delivery records Whether you have unsubscribed from tips and usage emails, and the delivery events our email provider reports for messages we send you
  deletion:
    route: Email to privacy contact
    text: To exercise any of these rights, email [email protected] .
  dpa:
    available: true
    text: Hetzner processes data only as necessary to provide hosting services under their Data Processing Agreement .
    url: null
  purposes:
  - purpose: Music API account and service contact
    text: Music API account creation; to contact you about your account or service changes; to deliver purchased products
  - purpose: Abuse detection and rate limiting
    text: Used for rate limiting, abuse detection, answering your support questions, and service monitoring
  - purpose: Subscription and billing
    text: To run your subscription, apply the right quota, and handle renewals and cancellations
  - purpose: Attribution of customer channels
    text: Used only to understand which channels bring us customers
  residency:
  - region: EU (Finland)
    text: Your data is stored on servers located within the EU (Hetzner, Finland).
  retention:
  - period: 60 days rolling
    scope: Request logs
    text: 60 days rolling for request logs; key data held for duration of subscription + 12 months
  - period: 7 years
    scope: Subscription records
    text: As required by UK tax law (7 years)
  - period: Deleted as soon as processing completes
    scope: Uploaded audio files
    text: Deleted as soon as processing completes, before the response is sent
  - period: 14 days
    scope: Web server logs
    text: Web server logs 14 days; API request logs 60 days rolling
  - period: 12 months
    scope: Email delivery events
    text: delivery events 12 months
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you.
  - right: Rectification
    text: Ask us to correct inaccurate or incomplete data.
  - right: Erasure
    text: Request deletion of your data where there is no overriding legal reason to keep it.
  - right: Restriction
    text: Ask us to limit how we use your data while a dispute is resolved.
  - right: Portability
    text: Receive your data in a structured, machine-readable format.
  - right: Objection
    text: Object to processing based on legitimate interests, including profiling.
  - right: Withdraw consent
    text: Where processing is based on consent, withdraw it at any time without affecting prior processing.
  role:
    text: The data controller is Steven Birring trading as Stackbase / FreqBlog.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your personal data with third parties for marketing purposes.
  subprocessors:
    text: Payment processors — when card billing is enabled, payments are handled by Stripe, Inc.
    url: null
  transfers:
  - mechanism: SCC
    text: Some of the processors listed above are US-based and may process data outside the UK/EEA under Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: freqblog-com
provenance_date: '2026-11-09'
provider_name: freqblog-com
provider_slug: freqblog-com
slug: freqblog-com-privacy-policy
source_date: '2026-11-09'
source_filename: freqblog-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://freqblog.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: freqblog-com\naid: freqblog-com\nurl: https://freqblog.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Steven Birring trading as Stackbase / FreqBlog.\ndata_categories:\n- category: identifying\n  text: Email address & name Music API account creation; to contact you about your account or service changes; to\n    deliver purchased products\n- category: contact\n  text: Contact us at [email protected] for any privacy-related queries.\n- category: financial\n  text: Billing information To process subscription and one-off payments. Card details are handled\
  \ directly by Stripe\n    — we never see or store card numbers.\n- category: location\n  text: It is also used to derive an approximate country for fraud review.\n- category: device\n  text: Origin IP address One IP address per API key — the address seen at signup, or on the first authenticated\n    call for keys created through checkout — is recorded against that key\n- category: behavioral\n  text: Signals derived from the data above — signup and request IP addresses (including the network an IPv6 address\n    belongs to), signup timing, email-address patterns, request patterns such as which tracks or artists are requested,\n    and quota usage\n- category: communication\n  text: Email preferences & delivery records Whether you have unsubscribed from tips and usage emails, and the delivery\n    events our email provider reports for messages we send you\npurposes:\n- purpose: Music API account and service contact\n  text: Music API account creation; to contact you about your account or\
  \ service changes; to deliver purchased products\n- purpose: Abuse detection and rate limiting\n  text: Used for rate limiting, abuse detection, answering your support questions, and service monitoring\n- purpose: Subscription and billing\n  text: To run your subscription, apply the right quota, and handle renewals and cancellations\n- purpose: Attribution of customer channels\n  text: Used only to understand which channels bring us customers\nretention:\n- scope: Request logs\n  period: 60 days rolling\n  text: 60 days rolling for request logs; key data held for duration of subscription + 12 months\n- scope: Subscription records\n  period: 7 years\n  text: As required by UK tax law (7 years)\n- scope: Uploaded audio files\n  period: Deleted as soon as processing completes\n  text: Deleted as soon as processing completes, before the response is sent\n- scope: Web server logs\n  period: 14 days\n  text: Web server logs 14 days; API request logs 60 days rolling\n- scope: Email delivery events\n\
  \  period: 12 months\n  text: delivery events 12 months\nresidency:\n- region: EU (Finland)\n  text: Your data is stored on servers located within the EU (Hetzner, Finland).\ntransfers:\n- mechanism: SCC\n  text: Some of the processors listed above are US-based and may process data outside the UK/EEA under Standard\n    Contractual Clauses\nsubprocessors:\n  url: null\n  text: Payment processors — when card billing is enabled, payments are handled by Stripe, Inc.\ndpa:\n  available: true\n  url: null\n  text: Hetzner processes data only as necessary to provide hosting services under their Data Processing Agreement\n    .\ndeletion:\n  route: Email to privacy contact\n  text: To exercise any of these rights, email [email protected] .\nrights:\n- right: Access\n  text: Request a copy of the personal data we hold about you.\n- right: Rectification\n  text: Ask us to correct inaccurate or incomplete data.\n- right: Erasure\n  text: Request deletion of your data where there is no overriding\
  \ legal reason to keep it.\n- right: Restriction\n  text: Ask us to limit how we use your data while a dispute is resolved.\n- right: Portability\n  text: Receive your data in a structured, machine-readable format.\n- right: Objection\n  text: Object to processing based on legitimate interests, including profiling.\n- right: Withdraw consent\n  text: Where processing is based on consent, withdraw it at any time without affecting prior processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share your personal data with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/freqblog-com/privacy/freqblog-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from freqblog-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Audio
- Metadata
---
