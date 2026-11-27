---
api_specs:
- filename: bidprowl-com-comps-api-openapi.yml
  format: yaml
  label: BidProwl Comps API
  slug: bidprowl-com-comps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-comps-api-openapi.yml
- filename: bidprowl-com-export-api-openapi.yml
  format: yaml
  label: BidProwl Export API
  slug: bidprowl-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-export-api-openapi.yml
- filename: bidprowl-com-flip-score-api-openapi.yml
  format: yaml
  label: BidProwl Flip Score API
  slug: bidprowl-com-flip-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-flip-score-api-openapi.yml
- filename: bidprowl-com-listings-api-openapi.yml
  format: yaml
  label: BidProwl Listings API
  slug: bidprowl-com-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-listings-api-openapi.yml
- filename: bidprowl-com-sold-api-openapi.yml
  format: yaml
  label: BidProwl Sold API
  slug: bidprowl-com-sold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-sold-api-openapi.yml
- filename: bidprowl-com-sources-api-openapi.yml
  format: yaml
  label: BidProwl Sources API
  slug: bidprowl-com-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-sources-api-openapi.yml
- filename: bidprowl-com-usage-api-openapi.yml
  format: yaml
  label: BidProwl Usage API
  slug: bidprowl-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-usage-api-openapi.yml
- filename: bidprowl-com-webhooks-api-openapi.yml
  format: yaml
  label: BidProwl Webhooks API
  slug: bidprowl-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidprowl-com/openapi/bidprowl-com-webhooks-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, and your name if you sign in with Google.
  - category: financial
    text: If you buy Pro, Stripe handles your card. We never see or store card numbers; we keep only your subscription status.
  - category: behavioral
    text: Google Analytics measures page views, device type, country and which pages lead to signups.
  - category: device
    text: Google Analytics measures page views, device type, country and which pages lead to signups.
  deletion:
    route: Email request
    text: To delete your account and data, email [email protected] and we will do it within 7 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sign in and send requested emails
    text: Used to sign you in and send the emails you ask for.
  - purpose: Send alerts for matching lots
    text: Your alerts, saved searches and watchlist, so we can email you when a matching lot is listed or about to close.
  - purpose: Advertising measurement and remarketing
    text: Google Ads and Google Analytics use cookies to tell us which ads led to a visit or signup, and may use your visit to show you BidProwl ads on other sites (remarketing).
  residency:
  - region: Germany
    text: Your account data and our auction data are stored in a PostgreSQL database on our own server in Germany (Hetzner).
  rights:
  - right: Opt out of marketing emails
    text: You can turn off any email from your account settings or the link in every email.
  - right: Turn off personalized Google ads
    text: You can turn off personalized ads from Google at adssettings.google.com
  - right: Opt out of Google Analytics
    text: opt out of Google Analytics with the browser add-on
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your email or personal data
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BidProwl
provenance_date: '2026-11-09'
provider_name: BidProwl
provider_slug: bidprowl-com
slug: bidprowl-com-privacy-policy
source_date: '2026-11-09'
source_filename: bidprowl-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bidprowl.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BidProwl\naid: bidprowl-com\nurl: https://bidprowl.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, and your name if you sign in with Google.\n- category: financial\n  text: If you buy Pro, Stripe handles your card. We never see or store card numbers; we keep only your subscription\n    status.\n- category: behavioral\n  text: Google Analytics measures page views, device type, country and which pages lead to signups.\n- category: device\n  text: Google Analytics measures page views, device type, country and\
  \ which pages lead to signups.\npurposes:\n- purpose: Sign in and send requested emails\n  text: Used to sign you in and send the emails you ask for.\n- purpose: Send alerts for matching lots\n  text: Your alerts, saved searches and watchlist, so we can email you when a matching lot is listed or about to\n    close.\n- purpose: Advertising measurement and remarketing\n  text: Google Ads and Google Analytics use cookies to tell us which ads led to a visit or signup, and may use your\n    visit to show you BidProwl ads on other sites (remarketing).\nretention: []\nresidency:\n- region: Germany\n  text: Your account data and our auction data are stored in a PostgreSQL database on our own server in Germany\n    (Hetzner).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request\n  text: To delete your account and data, email [email protected] and we will do it within 7 days.\nrights:\n- right: Opt out of\
  \ marketing emails\n  text: You can turn off any email from your account settings or the link in every email.\n- right: Turn off personalized Google ads\n  text: You can turn off personalized ads from Google at adssettings.google.com\n- right: Opt out of Google Analytics\n  text: opt out of Google Analytics with the browser add-on\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your email or personal data\n"
source_yaml_url: https://artifacts.apis.io/bidprowl-com/privacy/bidprowl-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from BidProwl's own page on 2026-11-09.
synthetic: false
tags:
- Government
- Auctions
- Marketplace
- Data
- Search
---
