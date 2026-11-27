---
api_specs:
- filename: arena-predictions-com-api-keys-api-openapi.yml
  format: yaml
  label: Arena API keys API
  slug: arena-predictions-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-api-keys-api-openapi.yml
- filename: arena-predictions-com-identity-api-openapi.yml
  format: yaml
  label: Arena Identity API
  slug: arena-predictions-com-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-identity-api-openapi.yml
- filename: arena-predictions-com-markets-api-openapi.yml
  format: yaml
  label: Arena Markets API
  slug: arena-predictions-com-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-markets-api-openapi.yml
- filename: arena-predictions-com-portfolio-api-openapi.yml
  format: yaml
  label: Arena Portfolio API
  slug: arena-predictions-com-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-portfolio-api-openapi.yml
- filename: arena-predictions-com-records-api-openapi.yml
  format: yaml
  label: Arena Records API
  slug: arena-predictions-com-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-records-api-openapi.yml
- filename: arena-predictions-com-status-api-openapi.yml
  format: yaml
  label: Arena Status API
  slug: arena-predictions-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-status-api-openapi.yml
- filename: arena-predictions-com-trading-api-openapi.yml
  format: yaml
  label: Arena Trading API
  slug: arena-predictions-com-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-trading-api-openapi.yml
- filename: arena-predictions-com-usage-api-openapi.yml
  format: yaml
  label: Arena Usage API
  slug: arena-predictions-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arena-predictions-com/openapi/arena-predictions-com-usage-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your display name, email address, and (optionally) a profile photo and the leagues you follow.
  - category: financial
    text: Whether you have an active Arena Basic subscription (listed as “Arena Pro” on the App Store), and the related purchase and entitlement identifiers.
  - category: device
    text: Standard technical data such as IP address, device or browser type, app version, and interaction and diagnostic events
  deletion:
    route: in-app deletion or email request
    text: You can delete your account at any time from within the iOS app, or request deletion from any platform by emailing support@zbgcllc.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate and operate the app
    text: We use your information to authenticate you; operate the app
  - purpose: service messages and push notifications
    text: send you service messages and, if you enable them, push notifications when your picks settle
  - purpose: security and debugging
    text: keep the service secure and debug problems
  - purpose: advertising measurement
    text: measure our advertising (see “Advertising measurement” below)
  residency:
  - region: United States
    text: Arena is operated from the United States, and your information is processed and stored there.
  retention:
  - period: null
    scope: account data
    text: We keep your information while your account is active and as needed to provide the service.
  - period: 180 days
    scope: onboarding and funnel analytics events
    text: onboarding and funnel analytics events (deleted after 180 days)
  rights:
  - right: access, correction, deletion, copy
    text: You may request access to, correction of, deletion of, or a copy of your personal data
  - right: opt out of sale or sharing (California)
    text: to opt out of sale or sharing
  - right: lodge complaint with supervisory authority
    text: the right to lodge a complaint with a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Under some state laws, including California’s, this may count as “sharing” personal information for advertising.
  subprocessors:
    text: We share limited data with the providers below, and only as needed.
    url: null
  transfers:
  - mechanism: other
    text: we take steps to ensure appropriate safeguards for such transfers where required
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Arena
provenance_date: '2026-11-09'
provider_name: Arena
provider_slug: arena-predictions-com
slug: arena-predictions-com-privacy-policy
source_date: '2026-11-09'
source_filename: arena-predictions-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://arena-predictions.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Arena\naid: arena-predictions-com\nurl: https://arena-predictions.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your display name, email address, and (optionally) a profile photo and the leagues you follow.\n- category: financial\n  text: Whether you have an active Arena Basic subscription (listed as “Arena Pro” on the App Store), and the related\n    purchase and entitlement identifiers.\n- category: device\n  text: Standard technical data such as IP address, device or browser type, app version, and interaction and diagnostic\n\
  \    events\npurposes:\n- purpose: authenticate and operate the app\n  text: We use your information to authenticate you; operate the app\n- purpose: service messages and push notifications\n  text: send you service messages and, if you enable them, push notifications when your picks settle\n- purpose: security and debugging\n  text: keep the service secure and debug problems\n- purpose: advertising measurement\n  text: measure our advertising (see “Advertising measurement” below)\nretention:\n- scope: account data\n  period: null\n  text: We keep your information while your account is active and as needed to provide the service.\n- scope: onboarding and funnel analytics events\n  period: 180 days\n  text: onboarding and funnel analytics events (deleted after 180 days)\nresidency:\n- region: United States\n  text: Arena is operated from the United States, and your information is processed and stored there.\ntransfers:\n- mechanism: other\n  text: we take steps to ensure appropriate safeguards\
  \ for such transfers where required\nsubprocessors:\n  url: null\n  text: We share limited data with the providers below, and only as needed.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app deletion or email request\n  text: You can delete your account at any time from within the iOS app, or request deletion from any platform by\n    emailing support@zbgcllc.com\nrights:\n- right: access, correction, deletion, copy\n  text: You may request access to, correction of, deletion of, or a copy of your personal data\n- right: opt out of sale or sharing (California)\n  text: to opt out of sale or sharing\n- right: lodge complaint with supervisory authority\n  text: the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: conditional\n  text: Under some state laws, including California’s, this may count as “sharing” personal information for advertising.\n"
source_yaml_url: https://artifacts.apis.io/arena-predictions-com/privacy/arena-predictions-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Arena's own page on 2026-11-09.
synthetic: false
tags:
- Prediction Markets
- Paper Trading
- Sandbox
- CLI
---
