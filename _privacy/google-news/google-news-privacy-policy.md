---
api_specs:
- filename: google-news-headlines-api-openapi.yml
  format: yaml
  label: Google News RSS Headlines API
  slug: google-news-headlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-headlines-api-openapi.yml
- filename: google-news-search-api-openapi.yml
  format: yaml
  label: Google News RSS Search API
  slug: google-news-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-search-api-openapi.yml
- filename: google-news-topics-api-openapi.yml
  format: yaml
  label: Google News RSS Topics API
  slug: google-news-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-news/openapi/google-news-topics-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers and similar information such as your name and password, phone number, and address, as well as unique identifiers tied to the browser, application, or device you’re using.
  - category: location
    text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around your device
  - category: health
    text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics (like blood glucose levels)
  - category: biometric
    text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development studies.
  - category: communication
    text: Communications data , such as emails, if you use our services to send and receive messages .
  deletion:
    route: Delete data via account settings, My Activity, or delete specific products or the entire Google Account
    text: Delete your entire Google Account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to deliver our services
  - purpose: Maintain and improve services
    text: we use your information to make improvements to our services
  - purpose: Personalized services and ads
    text: We use the information we collect to tailor our services for you
  - purpose: Measure performance
    text: We use data for analytics and measurement to understand how our services are used.
  - purpose: Protect Google, users and public
    text: We use information to help improve the safety and reliability of our services.
  residency:
  - region: Worldwide servers
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: Advertising data in server logs
    text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in server logs.
  - period: null
    scope: Data kept until account deletion
    text: We keep some data until you delete your Google Account, such as information about how often you use our services.
  rights:
  - right: Access and export
    text: You can export a copy of content in your Google Account if you want to back it up or use it with a service outside of Google.
  - right: Correct, update and delete
    text: to request that Google delete that information.
  - right: Opt out of profiling and targeted advertising
    text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.
  - right: Non-discrimination
    text: They also provide the right to not be discriminated against for exercising these privacy rights.
  role:
    text: This Privacy Policy applies to all of the services offered by Google LLC and its affiliates
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Google does not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We also comply with certain legal frameworks relating to the transfer of data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Google News RSS
provenance_date: '2026-11-09'
provider_name: Google News RSS
provider_slug: google-news
slug: google-news-privacy-policy
source_date: '2026-11-09'
source_filename: google-news-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google News RSS\naid: google-news\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: This Privacy Policy applies to all of the services offered by Google LLC and its affiliates\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: location\n  text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors\
  \ on or around\n    your device\n- category: health\n  text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics\n    (like blood glucose levels)\n- category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\n- category: communication\n  text: Communications data , such as emails, if you use our services to send and receive messages .\npurposes:\n- purpose: Provide services\n  text: We use your information to deliver our services\n- purpose: Maintain and improve services\n  text: we use your information to make improvements to our services\n- purpose: Personalized services and ads\n  text: We use the information we collect to tailor our services for you\n- purpose: Measure performance\n  text: We use data for analytics and measurement to understand how our services are used.\n- purpose: Protect Google, users and public\n  text: We use information\
  \ to help improve the safety and reliability of our services.\nretention:\n- scope: Advertising data in server logs\n  period: null\n  text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\n- scope: Data kept until account deletion\n  period: null\n  text: We keep some data until you delete your Google Account, such as information about how often you use our\n    services.\nresidency:\n- region: Worldwide servers\n  text: We maintain servers around the world and your information may be processed on servers located outside of\n    the country where you live.\ntransfers:\n- mechanism: other\n  text: We also comply with certain legal frameworks relating to the transfer of data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete data via account settings, My Activity, or delete specific products or the entire Google Account\n  text: Delete your\
  \ entire Google Account\nrights:\n- right: Access and export\n  text: You can export a copy of content in your Google Account if you want to back it up or use it with a service\n    outside of Google.\n- right: Correct, update and delete\n  text: to request that Google delete that information.\n- right: Opt out of profiling and targeted advertising\n  text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.\n- right: Non-discrimination\n  text: They also provide the right to not be discriminated against for exercising these privacy rights.\nsale_or_sharing:\n  stance: prohibited\n  text: Google does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/google-news/privacy/google-news-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Google News RSS's own page on 2026-11-09.
synthetic: false
tags:
- Aggregation
- Google News
- Headlines
- Media
- News
- RSS
---
