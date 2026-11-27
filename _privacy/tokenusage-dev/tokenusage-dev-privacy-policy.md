---
api_specs:
- filename: tokenusage-dev-nerfwatch-api-openapi.yml
  format: yaml
  label: tokenusage-dev Nerfwatch API
  slug: tokenusage-dev-nerfwatch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tokenusage-dev/openapi/tokenusage-dev-nerfwatch-api-openapi.yml
- filename: tokenusage-dev-resets-api-openapi.yml
  format: yaml
  label: tokenusage-dev Resets API
  slug: tokenusage-dev-resets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tokenusage-dev/openapi/tokenusage-dev-resets-api-openapi.yml
- filename: tokenusage-dev-resets-atom-api-openapi.yml
  format: yaml
  label: tokenusage-dev Resets.atom API
  slug: tokenusage-dev-resets-atom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tokenusage-dev/openapi/tokenusage-dev-resets-atom-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: your phone number, email address and optional name are not published
  - category: identifying
    text: the phone number itself is also stored because the site needs it to send texts
  - category: device
    text: browser, device and approximate location information
  - category: communication
    text: Welcome, alert and correction messages include your optional name.
  deletion:
    route: email support@tokenusage.dev or run share.py --delete --yes from the plugin directory
    text: To request deletion of your stored contact details, email support@tokenusage.dev .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: verification and messaging for reset alerts
    text: The site uses Twilio for verification, messaging and opt-out processing, and Google Cloud to host the site and store subscription data.
  - purpose: analytics
    text: we use Google Analytics 4 to count visits and understand how the site is used
  - purpose: Nerf Watch evidence link delivery
    text: It sends you the link you asked for and nothing else
  retention:
  - period: thirty days
    scope: delivery records
    text: They expire after thirty days; database cleanup can happen later.
  - period: indefinitely
    scope: Nerf Watch evidence records
    text: It keeps this indefinitely.
  - period: 390 days
    scope: analytics cookies
    text: 'We request host-only analytics cookies with an expiry of 33,696,000 seconds: 390 days, about 13 months'
  rights:
  - right: deletion of contact details
    text: To request deletion of your stored contact details, email support@tokenusage.dev .
  role:
    text: tokenusage.dev is operated by Pistachio Technology Inc.
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Mobile phone numbers, SMS opt-in data and consent are never sold to or shared with third parties or affiliates for marketing or promotional purposes.
  subprocessors:
    text: The site uses Twilio for verification, messaging and opt-out processing, and Google Cloud to host the site and store subscription data.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tokenusage-dev
provenance_date: '2026-11-10'
provider_name: tokenusage-dev
provider_slug: tokenusage-dev
slug: tokenusage-dev-privacy-policy
source_date: '2026-11-10'
source_filename: tokenusage-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tokenusage.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tokenusage-dev\naid: tokenusage-dev\nurl: https://tokenusage.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: tokenusage.dev is operated by Pistachio Technology Inc.\ndata_categories:\n- category: contact\n  text: your phone number, email address and optional name are not published\n- category: identifying\n  text: the phone number itself is also stored because the site needs it to send texts\n- category: device\n  text: browser, device and approximate location information\n- category: communication\n  text: Welcome, alert and correction messages include your optional name.\npurposes:\n\
  - purpose: verification and messaging for reset alerts\n  text: The site uses Twilio for verification, messaging and opt-out processing, and Google Cloud to host the site\n    and store subscription data.\n- purpose: analytics\n  text: we use Google Analytics 4 to count visits and understand how the site is used\n- purpose: Nerf Watch evidence link delivery\n  text: It sends you the link you asked for and nothing else\nretention:\n- scope: delivery records\n  period: thirty days\n  text: They expire after thirty days; database cleanup can happen later.\n- scope: Nerf Watch evidence records\n  period: indefinitely\n  text: It keeps this indefinitely.\n- scope: analytics cookies\n  period: 390 days\n  text: 'We request host-only analytics cookies with an expiry of 33,696,000 seconds: 390 days, about 13 months'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The site uses Twilio for verification, messaging and opt-out processing, and Google Cloud to host the site\n   \
  \ and store subscription data.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@tokenusage.dev or run share.py --delete --yes from the plugin directory\n  text: To request deletion of your stored contact details, email support@tokenusage.dev .\nrights:\n- right: deletion of contact details\n  text: To request deletion of your stored contact details, email support@tokenusage.dev .\nsale_or_sharing:\n  stance: prohibited\n  text: Mobile phone numbers, SMS opt-in data and consent are never sold to or shared with third parties or affiliates\n    for marketing or promotional purposes.\n"
source_yaml_url: https://artifacts.apis.io/tokenusage-dev/privacy/tokenusage-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from tokenusage-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Token Usage
- Artificial Intelligence
- Analytics
- OpenAI
- Anthropic
---
