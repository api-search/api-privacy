---
api_specs:
- filename: eventship-com-attendees-api-openapi.yml
  format: yaml
  label: Eventship Attendees API
  slug: eventship-com-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-attendees-api-openapi.yml
- filename: eventship-com-broadcast-api-openapi.yml
  format: yaml
  label: Eventship Broadcast API
  slug: eventship-com-broadcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-broadcast-api-openapi.yml
- filename: eventship-com-events-api-openapi.yml
  format: yaml
  label: Eventship Events API
  slug: eventship-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-events-api-openapi.yml
- filename: eventship-com-hubs-api-openapi.yml
  format: yaml
  label: Eventship Hubs API
  slug: eventship-com-hubs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-hubs-api-openapi.yml
- filename: eventship-com-questions-api-openapi.yml
  format: yaml
  label: Eventship Questions API
  slug: eventship-com-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-questions-api-openapi.yml
- filename: eventship-com-registration-api-openapi.yml
  format: yaml
  label: Eventship Registration API
  slug: eventship-com-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-registration-api-openapi.yml
- filename: eventship-com-speakers-api-openapi.yml
  format: yaml
  label: Eventship Speakers API
  slug: eventship-com-speakers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-speakers-api-openapi.yml
- filename: eventship-com-ticket-types-api-openapi.yml
  format: yaml
  label: Eventship Ticket Types API
  slug: eventship-com-ticket-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventship-com/openapi/eventship-com-ticket-types-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, company affiliation, interests, and location data
  - category: contact
    text: your phone number is stored securely and is only used to deliver SMS notifications
  - category: financial
    text: We store only the necessary references (such as the last four digits, expiration date, and subscription status)
  - category: location
    text: We may collect and use your IP address to infer your approximate location.
  - category: communication
    text: Messages sent between users are stored on our servers
  - category: device
    text: browser type, browser version, the pages of our Service that you visit, the time and date of your visit
  - category: behavioral
    text: we may track anonymous engagement metrics such as ad impressions and verified ad clicks
  deletion:
    route: Email support[at]eventship.com from the email address associated with your account
    text: If you would like to delete your account or personal data, email us at support[at]eventship.com from the email address associated with your account.
  dpa:
    available: true
    text: Terms of Use and Data Processing Agreement
    url: https://eventship.com/dpa
  purposes:
  - purpose: provide, improve and personalize the Service
    text: We use your Personal Information to provide, improve, and personalize the Service
  - purpose: product analytics and fixing problems
    text: We use PostHog to understand how the Service is used and to find and fix problems.
  - purpose: advertising measurement
    text: We use the Meta (Facebook) Pixel on certain pages of our platform to measure ad performance, track conversions
  - purpose: SMS notifications
    text: we may send you SMS (text) messages related to events you are registered for or hosts you follow.
  retention:
  - period: 30 days
    scope: session replays
    text: these are kept for 30 days
  - period: a minimum of 7 years
    scope: paid transaction history
    text: we retain transaction history for a minimum of 7 years to comply with tax and accounting laws
  - period: 60 days
    scope: revenue from sponsor campaigns
    text: After 60 days following an event, revenue from any ongoing sponsor campaigns is retained solely by Eventship.
  rights:
  - right: opt out of SMS notifications
    text: You can opt out of SMS notifications at any time by replying STOP to any message
  - right: opt out of AI-assisted features
    text: If you would like to opt out of AI-assisted features where technically feasible, please contact us at support[at]eventship.com .
  - right: opt out of Digital Sponsor tracking
    text: You can opt out of Digital Sponsor tracking by adjusting your browser settings
  - right: account and data deletion
    text: Deletion of your entire account, or Removal of specific personal data where technically feasible.
  role:
    text: Eventship, Inc. ("Eventship", "us", "we", or "our") operates eventship.com (the "Service").
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not share your phone number or SMS consent with event hosts, sponsors, affiliates, or other third parties for marketing purposes.
  subprocessors:
    text: A complete list of our sub-processors, including the data they process and their locations, is available on our Sub-processors page
    url: https://eventship.com/sub-processors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Eventship
provenance_date: '2026-11-09'
provider_name: Eventship
provider_slug: eventship-com
slug: eventship-com-privacy-policy
source_date: '2026-11-09'
source_filename: eventship-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eventship.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Eventship\naid: eventship-com\nurl: https://eventship.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Eventship, Inc. (\"Eventship\", \"us\", \"we\", or \"our\") operates eventship.com (the \"Service\").\ndata_categories:\n- category: identifying\n  text: your name, email address, company affiliation, interests, and location data\n- category: contact\n  text: your phone number is stored securely and is only used to deliver SMS notifications\n- category: financial\n  text: We store only the necessary references (such as the last four digits, expiration date, and subscription\n  \
  \  status)\n- category: location\n  text: We may collect and use your IP address to infer your approximate location.\n- category: communication\n  text: Messages sent between users are stored on our servers\n- category: device\n  text: browser type, browser version, the pages of our Service that you visit, the time and date of your visit\n- category: behavioral\n  text: we may track anonymous engagement metrics such as ad impressions and verified ad clicks\npurposes:\n- purpose: provide, improve and personalize the Service\n  text: We use your Personal Information to provide, improve, and personalize the Service\n- purpose: product analytics and fixing problems\n  text: We use PostHog to understand how the Service is used and to find and fix problems.\n- purpose: advertising measurement\n  text: We use the Meta (Facebook) Pixel on certain pages of our platform to measure ad performance, track conversions\n- purpose: SMS notifications\n  text: we may send you SMS (text) messages related\
  \ to events you are registered for or hosts you follow.\nretention:\n- scope: session replays\n  period: 30 days\n  text: these are kept for 30 days\n- scope: paid transaction history\n  period: a minimum of 7 years\n  text: we retain transaction history for a minimum of 7 years to comply with tax and accounting laws\n- scope: revenue from sponsor campaigns\n  period: 60 days\n  text: After 60 days following an event, revenue from any ongoing sponsor campaigns is retained solely by Eventship.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: https://eventship.com/sub-processors\n  text: A complete list of our sub-processors, including the data they process and their locations, is available\n    on our Sub-processors page\ndpa:\n  available: true\n  url: https://eventship.com/dpa\n  text: Terms of Use and Data Processing Agreement\ndeletion:\n  route: Email support[at]eventship.com from the email address associated with your account\n  text: If you would like to delete your account\
  \ or personal data, email us at support[at]eventship.com from the\n    email address associated with your account.\nrights:\n- right: opt out of SMS notifications\n  text: You can opt out of SMS notifications at any time by replying STOP to any message\n- right: opt out of AI-assisted features\n  text: If you would like to opt out of AI-assisted features where technically feasible, please contact us at support[at]eventship.com\n    .\n- right: opt out of Digital Sponsor tracking\n  text: You can opt out of Digital Sponsor tracking by adjusting your browser settings\n- right: account and data deletion\n  text: Deletion of your entire account, or Removal of specific personal data where technically feasible.\nsale_or_sharing:\n  stance: conditional\n  text: We do not share your phone number or SMS consent with event hosts, sponsors, affiliates, or other third\n    parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/eventship-com/privacy/eventship-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Eventship's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Attendees
- Ticketing
- Event Management
---
