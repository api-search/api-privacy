---
api_specs:
- filename: google-analytics-accounts-api-openapi.yml
  format: yaml
  label: Google Analytics Accounts API
  slug: google-analytics-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-analytics/openapi/google-analytics-accounts-api-openapi.yml
- filename: google-analytics-accountsummaries-api-openapi.yml
  format: yaml
  label: Google Analytics Account Summaries API
  slug: google-analytics-accountsummaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-analytics/openapi/google-analytics-accountsummaries-api-openapi.yml
- filename: google-analytics-properties-api-openapi.yml
  format: yaml
  label: Google Analytics Properties API
  slug: google-analytics-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-analytics/openapi/google-analytics-properties-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers and similar information such as your name and password, phone number, and address, as well as unique identifiers tied to the browser, application, or device you’re using.
  - category: behavioral
    text: Internet, network, and other activity information such as your search terms; views and interactions with content and ads
  - category: location
    text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around your device
  - category: health
    text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics (like blood glucose levels)
  - category: biometric
    text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development studies.
  - category: demographic
    text: Demographic information
  - category: financial
    text: Commercial information such as your payment information and a history of purchases you make on Google’s services.
  deletion:
    route: Delete content, specific products, or the entire Google Account
    text: You can export a copy of your information or delete it from your Google Account at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Measure performance
    text: We use data for analytics and measurement to understand how our services are used.
  - purpose: Personalized services and ads
    text: We use the information we collect to tailor our services for you, including providing customized and personalized experiences and recommendations
  - purpose: Advertising
    text: Google processes information to provide advertising, including online identifiers, browsing and search activity, and information about your location and interactions with advertisements.
  - purpose: Research and development
    text: Google uses information to improve our services and to develop new products, features and technologies that benefit our users and the public.
  residency:
  - region: servers around the world
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: advertising data in server logs
    text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in server logs.
  - period: until you delete your Google Account
    scope: some data
    text: We keep some data until you delete your Google Account, such as information about how often you use our services.
  rights:
  - right: access, correct, and delete
    text: they give you the right to access your information, sometimes in a portable format; correct your information; and to request that Google delete that information.
  - right: opt out of profiling and targeted advertising
    text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Google does not sell your personal information.
  subprocessors:
    text: We provide personal information to our affiliates and other trusted businesses or persons to process it for us, based on our instructions
    url: null
  transfers:
  - mechanism: other
    text: We also comply with certain legal frameworks relating to the transfer of data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Google Analytics 4
provenance_date: '2026-11-09'
provider_name: Google Analytics
provider_slug: google-analytics
slug: google-analytics-privacy-policy
source_date: '2026-11-09'
source_filename: google-analytics-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google Analytics 4\naid: google-analytics-4\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: behavioral\n  text: Internet, network, and other activity information such as your search terms; views and interactions with\n    content and ads\n- category: location\n  text: Geolocation\
  \ data , such as may be determined by GPS, IP address, and other data from sensors on or around\n    your device\n- category: health\n  text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics\n    (like blood glucose levels)\n- category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\n- category: demographic\n  text: Demographic information\n- category: financial\n  text: Commercial information such as your payment information and a history of purchases you make on Google’s\n    services.\npurposes:\n- purpose: Measure performance\n  text: We use data for analytics and measurement to understand how our services are used.\n- purpose: Personalized services and ads\n  text: We use the information we collect to tailor our services for you, including providing customized and personalized\n    experiences and recommendations\n- purpose: Advertising\n\
  \  text: Google processes information to provide advertising, including online identifiers, browsing and search activity,\n    and information about your location and interactions with advertisements.\n- purpose: Research and development\n  text: Google uses information to improve our services and to develop new products, features and technologies that\n    benefit our users and the public.\nretention:\n- scope: advertising data in server logs\n  period: null\n  text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\n- scope: some data\n  period: until you delete your Google Account\n  text: We keep some data until you delete your Google Account, such as information about how often you use our\n    services.\nresidency:\n- region: servers around the world\n  text: We maintain servers around the world and your information may be processed on servers located outside of\n    the country where you live.\ntransfers:\n\
  - mechanism: other\n  text: We also comply with certain legal frameworks relating to the transfer of data.\nsubprocessors:\n  url: null\n  text: We provide personal information to our affiliates and other trusted businesses or persons to process it\n    for us, based on our instructions\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete content, specific products, or the entire Google Account\n  text: You can export a copy of your information or delete it from your Google Account at any time\nrights:\n- right: access, correct, and delete\n  text: they give you the right to access your information, sometimes in a portable format; correct your information;\n    and to request that Google delete that information.\n- right: opt out of profiling and targeted advertising\n  text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.\nsale_or_sharing:\n  stance: prohibited\n  text: Google does not sell your personal\
  \ information.\n"
source_yaml_url: https://artifacts.apis.io/google-analytics/privacy/google-analytics-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Google Analytics 4's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Data
- Google
- Metrics
- Reporting
- Web Analytics
- Machine Learning
- Attribution
---
