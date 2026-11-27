---
api_specs:
- filename: public
  format: yaml
  label: Yahoo DSP Traffic API
  slug: dsp-traffic-api
  spec_type: Postman
  url: https://www.postman.com/yahoodsp/workspace/public
claim_count: 5
description: ''
doc:
  data_categories:
  - category: identifying
    text: You will be asked to provide a Yahoo ID and an optional alternate email address for contacting you.
  - category: device
    text: Yahoo logs IP addresses for each Web Service during a 24-hour period on a per-IP basis in order to determine the number of API calls made by an IP address during a specific window of time.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contact developer about application problems
    text: Information collected on the Application ID page may be used by Yahoo to contact you if there is a problem with your application.
  - purpose: Rate limiting API access
    text: Access to the Web Services is rate-limited based upon the user's IP address.
  - purpose: Track SDK downloads
    text: Yahoo logs the number of downloads made from the site.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yahoo
provenance_date: '2026-11-10'
provider_name: Yahoo
provider_slug: yahoo
slug: yahoo-privacy-policy
source_date: '2026-11-10'
source_filename: yahoo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://legal.yahoo.com/us/en/yahoo/privacy/products/developer/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yahoo\naid: yahoo\nurl: https://legal.yahoo.com/us/en/yahoo/privacy/products/developer/index.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: You will be asked to provide a Yahoo ID and an optional alternate email address for contacting you.\n- category: device\n  text: Yahoo logs IP addresses for each Web Service during a 24-hour period on a per-IP basis in order to determine\n    the number of API calls made by an IP address during a specific window of time.\npurposes:\n- purpose: Contact developer about application problems\n  text:\
  \ Information collected on the Application ID page may be used by Yahoo to contact you if there is a problem\n    with your application.\n- purpose: Rate limiting API access\n  text: Access to the Web Services is rate-limited based upon the user's IP address.\n- purpose: Track SDK downloads\n  text: Yahoo logs the number of downloads made from the site.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yahoo/privacy/yahoo-privacy-policy.yml
stated_fields:
- data_categories
- purposes
summary_line: 5 quoted statements, read from Yahoo's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Programmatic Advertising
- DSP
- Fantasy Sports
- Sports Data
- Identity
- OpenID Connect
- OAuth
- Audience Data
- Media
- Reporting
- Conversion Tracking
- Authentication
---
