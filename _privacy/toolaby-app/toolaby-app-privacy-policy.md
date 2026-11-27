---
api_specs:
- filename: toolaby-app-analytics-api-openapi.yml
  format: yaml
  label: toolaby-app Analytics API
  slug: toolaby-app-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-analytics-api-openapi.yml
- filename: toolaby-app-customers-api-openapi.yml
  format: yaml
  label: toolaby-app Customers API
  slug: toolaby-app-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-customers-api-openapi.yml
- filename: toolaby-app-grants-api-openapi.yml
  format: yaml
  label: toolaby-app Grants API
  slug: toolaby-app-grants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-grants-api-openapi.yml
- filename: toolaby-app-uses-api-openapi.yml
  format: yaml
  label: toolaby-app Uses API
  slug: toolaby-app-uses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolaby-app/openapi/toolaby-app-uses-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and, if you give it, your name.
  - category: contact
    text: Its name, website and support address (shown to your buyers)
  - category: financial
    text: Stripe's references for what you bought (customer, checkout session, payment), the licence or subscription state
  - category: device
    text: 'For each extension you connect: a random install id, the public half of a key the extension made on your device'
  - category: behavioral
    text: the days it ran, its version, how often the paywall opened and what opened it
  - category: location
    text: The address and browser each sign-in came from, for as long as the session lasts.
  deletion:
    route: Write to hello@toolaby.app to request deletion
    text: When you ask us to delete your data, we do so within thirty days, keeping only what the law requires
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'To run the service: sign you in, know what you are entitled to, unlock the tool on your devices, send the emails the account needs'
  - purpose: Developer buyer support
    text: 'To let developers see and support their buyers: who bought what, on how many devices, what needs attention.'
  - purpose: Extension usage counts
    text: 'To show developers how their extensions are used and what sells, as counts: active devices, the way from a new device to a purchase, what opened the paywall, each version, and why people remove an extension.'
  - purpose: Security and fairness
    text: 'To keep the service secure and fair: rate limits, replay protection, abuse detection, revoking a licence that is refunded or shared beyond its limit.'
  residency:
  - region: European Union (Frankfurt and Stockholm)
    text: In the European Union — Frankfurt and Stockholm, as listed above — except mail you send us, which is kept in our mailbox at Google and may be stored outside the EU.
  retention:
  - period: for as long as the account or the purchase exists
    scope: Account, purchase, licence and device records
    text: 'Account, purchase, licence and device records: for as long as the account or the purchase exists, then as long as the developer''s legal obligations require'
  - period: thirteen months
    scope: Analytics daily counts
    text: 'Analytics: each day''s counts, and the answers given when an extension is removed, for thirteen months'
  - period: no longer than twelve months
    scope: Security and abuse records
    text: 'Security and abuse records: no longer than twelve months.'
  - period: null
    scope: Access requests
    text: 'Access requests While Toolaby is invite-only, the address you ask with and when you asked: until we answer, and for 90 days after.'
  rights:
  - right: access
    text: You can ask to see the data we hold about you, to correct it, to have it deleted, to receive a copy
  - right: object or restrict
    text: and to object to or restrict its processing.
  - right: complain to authority
    text: You can also complain to the data protection authority where you live.
  role:
    text: 'If you are a developer with a workspace, Toolaby decides why and how your data is processed: we are the controller.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Not to advertise, not to profile, not to sell.
  subprocessors:
    text: 'The providers that run Toolaby , processing on our instructions and nothing else: Vercel Hosting and the code that answers every request'
    url: null
  transfers:
  - mechanism: SCC
    text: The providers are companies that also operate outside the EU and are bound to us by data processing terms with the European Commission's standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: toolaby-app
provenance_date: '2026-11-10'
provider_name: toolaby-app
provider_slug: toolaby-app
slug: toolaby-app-privacy-policy
source_date: '2026-11-10'
source_filename: toolaby-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://toolaby.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: toolaby-app\naid: toolaby-app\nurl: https://toolaby.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'If you are a developer with a workspace, Toolaby decides why and how your data is processed: we are the\n    controller.'\ndata_categories:\n- category: identifying\n  text: Your email address and, if you give it, your name.\n- category: contact\n  text: Its name, website and support address (shown to your buyers)\n- category: financial\n  text: Stripe's references for what you bought (customer, checkout session, payment), the licence or subscription\n    state\n- category: device\n  text:\
  \ 'For each extension you connect: a random install id, the public half of a key the extension made on your\n    device'\n- category: behavioral\n  text: the days it ran, its version, how often the paywall opened and what opened it\n- category: location\n  text: The address and browser each sign-in came from, for as long as the session lasts.\npurposes:\n- purpose: Run the service\n  text: 'To run the service: sign you in, know what you are entitled to, unlock the tool on your devices, send the\n    emails the account needs'\n- purpose: Developer buyer support\n  text: 'To let developers see and support their buyers: who bought what, on how many devices, what needs attention.'\n- purpose: Extension usage counts\n  text: 'To show developers how their extensions are used and what sells, as counts: active devices, the way from\n    a new device to a purchase, what opened the paywall, each version, and why people remove an extension.'\n- purpose: Security and fairness\n  text: 'To keep the\
  \ service secure and fair: rate limits, replay protection, abuse detection, revoking a licence\n    that is refunded or shared beyond its limit.'\nretention:\n- scope: Account, purchase, licence and device records\n  period: for as long as the account or the purchase exists\n  text: 'Account, purchase, licence and device records: for as long as the account or the purchase exists, then\n    as long as the developer''s legal obligations require'\n- scope: Analytics daily counts\n  period: thirteen months\n  text: 'Analytics: each day''s counts, and the answers given when an extension is removed, for thirteen months'\n- scope: Security and abuse records\n  period: no longer than twelve months\n  text: 'Security and abuse records: no longer than twelve months.'\n- scope: Access requests\n  period: null\n  text: 'Access requests While Toolaby is invite-only, the address you ask with and when you asked: until we answer,\n    and for 90 days after.'\nresidency:\n- region: European Union (Frankfurt\
  \ and Stockholm)\n  text: In the European Union — Frankfurt and Stockholm, as listed above — except mail you send us, which is kept\n    in our mailbox at Google and may be stored outside the EU.\ntransfers:\n- mechanism: SCC\n  text: The providers are companies that also operate outside the EU and are bound to us by data processing terms\n    with the European Commission's standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'The providers that run Toolaby , processing on our instructions and nothing else: Vercel Hosting and the\n    code that answers every request'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hello@toolaby.app to request deletion\n  text: When you ask us to delete your data, we do so within thirty days, keeping only what the law requires\nrights:\n- right: access\n  text: You can ask to see the data we hold about you, to correct it, to have it deleted, to receive a copy\n- right: object or restrict\n  text: and to object\
  \ to or restrict its processing.\n- right: complain to authority\n  text: You can also complain to the data protection authority where you live.\nsale_or_sharing:\n  stance: prohibited\n  text: Not to advertise, not to profile, not to sell.\n"
source_yaml_url: https://artifacts.apis.io/toolaby-app/privacy/toolaby-app-privacy-policy.yml
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
summary_line: 23 quoted statements, read from toolaby-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Chrome Extension
- Stripe
- Licensing
---
