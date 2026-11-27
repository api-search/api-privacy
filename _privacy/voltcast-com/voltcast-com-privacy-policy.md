---
api_specs:
- filename: voltcast-com-prices-api-openapi.yml
  format: yaml
  label: voltcast-com Prices API
  slug: voltcast-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-prices-api-openapi.yml
- filename: voltcast-com-public-api-openapi.yml
  format: yaml
  label: voltcast-com Public API
  slug: voltcast-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-public-api-openapi.yml
- filename: voltcast-com-zones-api-openapi.yml
  format: yaml
  label: voltcast-com Zones API
  slug: voltcast-com-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voltcast-com/openapi/voltcast-com-zones-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — name, email, password hash (or Google account ID if you sign in with Google).
  - category: financial
    text: Billing data — handled by Stripe; we store only Stripe customer/subscription identifiers and deposit status.
  - category: behavioral
    text: API usage — request counts, rate-limit counters, key last-used timestamps.
  - category: device
    text: coarse device class
  - category: communication
    text: Newsletter (the monthly European power roundup) — your email, the page you signed up from, and a confirmation timestamp.
  deletion:
    route: email
    text: Access, rectification, erasure, portability, restriction and objection — email hello@voltcast.com and we will respond within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: running the subscription API and abuse prevention
    text: 'Legal basis: legitimate interest (operations, abuse prevention).'
  - purpose: newsletter
    text: We send a confirmation mail; you can unsubscribe in one click.
  - purpose: advertising measurement
    text: Only with your separate opt-in, we send Google Ads an ad click identifier, the time, amount and currency of your first paid Home subscription, and an opaque order identifier.
  residency:
  - region: EU
    text: Cloudflare (object storage, EU jurisdiction available), our hosting provider (EU data center)
  retention:
  - period: 90 days
    scope: account data
    text: Account data lives while your account exists and up to 90 days after deletion.
  - period: 30 days
    scope: server logs
    text: Server logs rotate within 30 days.
  rights:
  - right: access
    text: Access, rectification, erasure, portability, restriction and objection
  - right: complain to supervisory authority
    text: 'You may also complain to your local supervisory authority (in Denmark: Datatilsynet).'
  role:
    text: The data controller for all personal data processed by this site and API is WeCode A/S
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No selling of personal data.
  subprocessors:
    text: Stripe (payments, EU SCC), Cloudflare (object storage, EU jurisdiction available), our hosting provider (EU data center), Google (sign-in, consent-gated analytics and separately consented advertising measurement), Rewardful (affiliate attribution when an affiliate link is used), and Brevo (newsletter list and confirmation mail when you opt in to the monthly roundup).
    url: null
  transfers:
  - mechanism: SCC
    text: Stripe (payments, EU SCC)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: voltcast-com
provenance_date: '2026-11-10'
provider_name: voltcast-com
provider_slug: voltcast-com
slug: voltcast-com-privacy-policy
source_date: '2026-11-10'
source_filename: voltcast-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://voltcast.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: voltcast-com\naid: voltcast-com\nurl: https://voltcast.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for all personal data processed by this site and API is WeCode A/S\ndata_categories:\n- category: identifying\n  text: Account data — name, email, password hash (or Google account ID if you sign in with Google).\n- category: financial\n  text: Billing data — handled by Stripe; we store only Stripe customer/subscription identifiers and deposit status.\n- category: behavioral\n  text: API usage — request counts, rate-limit counters, key last-used timestamps.\n\
  - category: device\n  text: coarse device class\n- category: communication\n  text: Newsletter (the monthly European power roundup) — your email, the page you signed up from, and a confirmation\n    timestamp.\npurposes:\n- purpose: running the subscription API and abuse prevention\n  text: 'Legal basis: legitimate interest (operations, abuse prevention).'\n- purpose: newsletter\n  text: We send a confirmation mail; you can unsubscribe in one click.\n- purpose: advertising measurement\n  text: Only with your separate opt-in, we send Google Ads an ad click identifier, the time, amount and currency\n    of your first paid Home subscription, and an opaque order identifier.\nretention:\n- scope: account data\n  period: 90 days\n  text: Account data lives while your account exists and up to 90 days after deletion.\n- scope: server logs\n  period: 30 days\n  text: Server logs rotate within 30 days.\nresidency:\n- region: EU\n  text: Cloudflare (object storage, EU jurisdiction available), our\
  \ hosting provider (EU data center)\ntransfers:\n- mechanism: SCC\n  text: Stripe (payments, EU SCC)\nsubprocessors:\n  url: null\n  text: Stripe (payments, EU SCC), Cloudflare (object storage, EU jurisdiction available), our hosting provider\n    (EU data center), Google (sign-in, consent-gated analytics and separately consented advertising measurement),\n    Rewardful (affiliate attribution when an affiliate link is used), and Brevo (newsletter list and confirmation\n    mail when you opt in to the monthly roundup).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: Access, rectification, erasure, portability, restriction and objection — email hello@voltcast.com and we\n    will respond within 30 days.\nrights:\n- right: access\n  text: Access, rectification, erasure, portability, restriction and objection\n- right: complain to supervisory authority\n  text: 'You may also complain to your local supervisory authority (in Denmark: Datatilsynet).'\n\
  sale_or_sharing:\n  stance: prohibited\n  text: No selling of personal data.\n"
source_yaml_url: https://artifacts.apis.io/voltcast-com/privacy/voltcast-com-privacy-policy.yml
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
summary_line: 18 quoted statements, read from voltcast-com's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Streaming
- Media
- Platform
---
