---
api_specs:
- filename: buildervet-au-api-openapi.yml
  format: yaml
  label: BuilderVet API API
  slug: buildervet-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildervet-au/openapi/_original/buildervet-au-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: location
    text: I record roughly where you are (country, region and city, worked out from your IP address)
  - category: identifying
    text: your account email, authentication records, purchased rights, monitored builders, delivery preferences, and notification history
  - category: device
    text: I also store your device type and browser user agent.
  - category: behavioral
    text: how far you scroll and page-speed timings
  - category: financial
    text: BuilderVet keeps payment references, purchase or subscription state, and access dates so it can provide the service.
  deletion:
    route: contact us
    text: To request account-data access, correction, or deletion, contact us .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: understand which channels bring signups
    text: This is only used to understand which channels work.
  - purpose: provide the service
    text: BuilderVet keeps payment references, purchase or subscription state, and access dates so it can provide the service.
  - purpose: deliver sign-in links and alerts
    text: Email services receive the address and message needed to deliver sign-in links and enabled alerts.
  retention:
  - period: 35 days
    scope: raw page and click analytics events
    text: Raw page and click events are deleted after 35 days;
  - period: 400 days
    scope: visit summaries
    text: visit summaries (the hashed daily key, country, device, campaign tags, pages, time and scroll) are deleted after 400 days.
  - period: 90 days
    scope: ad and campaign source in browser local storage
    text: in local storage for up to 90 days.
  rights:
  - right: access
    text: To request account-data access, correction, or deletion, contact us .
  - right: correction
    text: To request account-data access, correction, or deletion, contact us .
  - right: deletion
    text: To request account-data access, correction, or deletion, contact us .
  - right: reject optional analytics
    text: You can reject them at any time with the Analytics settings link in the footer of every public page.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: It is not sold and not shared with ad networks.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BuilderVet
provenance_date: '2026-11-09'
provider_name: BuilderVet
provider_slug: buildervet-au
slug: buildervet-au-privacy-policy
source_date: '2026-11-09'
source_filename: buildervet-au-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://buildervet.au/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BuilderVet\naid: buildervet-au\nurl: https://buildervet.au/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: location\n  text: I record roughly where you are (country, region and city, worked out from your IP address)\n- category: identifying\n  text: your account email, authentication records, purchased rights, monitored builders, delivery preferences,\n    and notification history\n- category: device\n  text: I also store your device type and browser user agent.\n- category: behavioral\n  text: how far you scroll and page-speed timings\n- category:\
  \ financial\n  text: BuilderVet keeps payment references, purchase or subscription state, and access dates so it can provide\n    the service.\npurposes:\n- purpose: understand which channels bring signups\n  text: This is only used to understand which channels work.\n- purpose: provide the service\n  text: BuilderVet keeps payment references, purchase or subscription state, and access dates so it can provide\n    the service.\n- purpose: deliver sign-in links and alerts\n  text: Email services receive the address and message needed to deliver sign-in links and enabled alerts.\nretention:\n- scope: raw page and click analytics events\n  period: 35 days\n  text: Raw page and click events are deleted after 35 days;\n- scope: visit summaries\n  period: 400 days\n  text: visit summaries (the hashed daily key, country, device, campaign tags, pages, time and scroll) are deleted\n    after 400 days.\n- scope: ad and campaign source in browser local storage\n  period: 90 days\n  text: in local\
  \ storage for up to 90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us\n  text: To request account-data access, correction, or deletion, contact us .\nrights:\n- right: access\n  text: To request account-data access, correction, or deletion, contact us .\n- right: correction\n  text: To request account-data access, correction, or deletion, contact us .\n- right: deletion\n  text: To request account-data access, correction, or deletion, contact us .\n- right: reject optional analytics\n  text: You can reject them at any time with the Analytics settings link in the footer of every public page.\nsale_or_sharing:\n  stance: prohibited\n  text: It is not sold and not shared with ad networks.\n"
source_yaml_url: https://artifacts.apis.io/buildervet-au/privacy/buildervet-au-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from BuilderVet's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
