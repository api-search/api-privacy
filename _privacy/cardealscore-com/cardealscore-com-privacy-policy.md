---
api_specs:
- filename: cardealscore-com-explain-api-openapi.yml
  format: yaml
  label: DealScore Explain API
  slug: cardealscore-com-explain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardealscore-com/openapi/cardealscore-com-explain-api-openapi.yml
- filename: cardealscore-com-health-api-openapi.yml
  format: yaml
  label: DealScore Health API
  slug: cardealscore-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardealscore-com/openapi/cardealscore-com-health-api-openapi.yml
- filename: cardealscore-com-quote-check-api-openapi.yml
  format: yaml
  label: DealScore Quote Check API
  slug: cardealscore-com-quote-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardealscore-com/openapi/cardealscore-com-quote-check-api-openapi.yml
- filename: cardealscore-com-score-api-openapi.yml
  format: yaml
  label: DealScore Score API
  slug: cardealscore-com-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cardealscore-com/openapi/cardealscore-com-score-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: Email for magic-link sign-in.
  - category: location
    text: A signed-out first score on /try sets the ds_anon_look cookie and stores the request IP address as received (not hashed), the UTC date, and a count of signed-out scores from that address on that date, so that one look is not repeated.
  - category: device
    text: When an AI client registers for OAuth, we store its name, its redirect addresses, the user agent it registered with, and the two-letter country Vercel reports for that request.
  - category: financial
    text: Stripe ids (customer id and subscription id) and your plan name, so paid access can be turned on and off.
  - category: behavioral
    text: Vercel Web Analytics records basic page views.
  - category: other
    text: Score requests include the vehicle attributes you send (year, make, model, trim, VIN, asking price, mileage, and an optional ZIP, or a listing URL or listing text if one is sent).
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: compute grade and meter counting
    text: Those fields are used to compute the grade and to decide whether the request counts on the meter.
  - purpose: account identification
    text: The address is the account id for keys, OAuth consent, and billing.
  retention:
  - period: 30 days
    scope: ds_session cookie
    text: 'ds_session : keeps you signed in. 30 days.'
  - period: 400 days
    scope: ds_anon_look cookie
    text: 'ds_anon_look : marks that the signed-out free score was used. 400 days.'
  - period: 400 days
    scope: ds_attr cookie
    text: 'ds_attr : holds campaign tags and the referring site until you sign up. 400 days.'
  - period: 1 hour
    scope: /try draft in browser local storage
    text: The /try form keeps a draft of what you enter in your browser's local storage for up to 1 hour.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DealScore
provenance_date: '2026-11-09'
provider_name: DealScore
provider_slug: cardealscore-com
slug: cardealscore-com-privacy-policy
source_date: '2026-11-09'
source_filename: cardealscore-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cardealscore.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DealScore\naid: cardealscore-com\nurl: https://cardealscore.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email for magic-link sign-in.\n- category: location\n  text: A signed-out first score on /try sets the ds_anon_look cookie and stores the request IP address as received\n    (not hashed), the UTC date, and a count of signed-out scores from that address on that date, so that one look\n    is not repeated.\n- category: device\n  text: When an AI client registers for OAuth, we store its name, its redirect addresses, the user\
  \ agent it registered\n    with, and the two-letter country Vercel reports for that request.\n- category: financial\n  text: Stripe ids (customer id and subscription id) and your plan name, so paid access can be turned on and off.\n- category: behavioral\n  text: Vercel Web Analytics records basic page views.\n- category: other\n  text: Score requests include the vehicle attributes you send (year, make, model, trim, VIN, asking price, mileage,\n    and an optional ZIP, or a listing URL or listing text if one is sent).\npurposes:\n- purpose: compute grade and meter counting\n  text: Those fields are used to compute the grade and to decide whether the request counts on the meter.\n- purpose: account identification\n  text: The address is the account id for keys, OAuth consent, and billing.\nretention:\n- scope: ds_session cookie\n  period: 30 days\n  text: 'ds_session : keeps you signed in. 30 days.'\n- scope: ds_anon_look cookie\n  period: 400 days\n  text: 'ds_anon_look : marks that the\
  \ signed-out free score was used. 400 days.'\n- scope: ds_attr cookie\n  period: 400 days\n  text: 'ds_attr : holds campaign tags and the referring site until you sign up. 400 days.'\n- scope: /try draft in browser local storage\n  period: 1 hour\n  text: The /try form keeps a draft of what you enter in your browser's local storage for up to 1 hour.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/cardealscore-com/privacy/cardealscore-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 13 quoted statements, read from DealScore's own page on 2026-11-09.
synthetic: false
tags:
- Company
- UsedCar
- Artificial Intelligence
- Pricing
- MCP
---
