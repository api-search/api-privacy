---
api_specs:
- filename: google-play-console-anomalies-api-openapi.yml
  format: yaml
  label: Google Play Console Developer Reporting Play Console Anomalies API
  slug: google-play-console-anomalies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-play-console/openapi/google-play-console-anomalies-api-openapi.yml
- filename: google-play-console-apps-api-openapi.yml
  format: yaml
  label: Google Play Console Developer Reporting Play Console Apps API
  slug: google-play-console-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-play-console/openapi/google-play-console-apps-api-openapi.yml
- filename: google-play-console-vitals-api-openapi.yml
  format: yaml
  label: Google Play Console Developer Reporting Play Console Vitals API
  slug: google-play-console-vitals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-play-console/openapi/google-play-console-vitals-api-openapi.yml
claim_count: 16
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
  deletion:
    route: Privacy controls and My Activity; delete your content, specific items, or entire Google Account
    text: Delete your entire Google Account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to deliver our services
  - purpose: Personalized ads
    text: Depending on your settings, we may also show you personalized ads based on your interests, activity, or personalized content from Google services.
  - purpose: Research and development
    text: Google uses information to improve our services and to develop new products, features and technologies that benefit our users and the public.
  residency:
  - region: Global
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: Activity and data in Google Account
    text: We’ll keep this data in your Google Account until you remove it or choose to have it removed.
  - period: null
    scope: Advertising data in server logs
    text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in server logs.
  rights:
  - right: Access, correct, and delete
    text: they give you the right to access your information, sometimes in a portable format; correct your information; and to request that Google delete that information.
  - right: Opt out of profiling and targeted advertising
    text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.
  - right: Non-discrimination
    text: They also provide the right to not be discriminated against for exercising these privacy rights.
  role:
    text: null
    value: unstated
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
name: Google Play Console Developer Reporting
provenance_date: '2026-11-09'
provider_name: Google Play Console Developer Reporting
provider_slug: google-play-console
slug: google-play-console-privacy-policy
source_date: '2026-11-09'
source_filename: google-play-console-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google Play Console Developer Reporting\naid: google-play-console\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: location\n  text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around\n    your device\n- category: health\n  text:\
  \ Health information if you choose to provide it, such as your medical history, vital signs and health metrics\n    (like blood glucose levels)\n- category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\npurposes:\n- purpose: Provide services\n  text: We use your information to deliver our services\n- purpose: Personalized ads\n  text: Depending on your settings, we may also show you personalized ads based on your interests, activity, or\n    personalized content from Google services.\n- purpose: Research and development\n  text: Google uses information to improve our services and to develop new products, features and technologies that\n    benefit our users and the public.\nretention:\n- scope: Activity and data in Google Account\n  period: null\n  text: We’ll keep this data in your Google Account until you remove it or choose to have it removed.\n- scope: Advertising data in server logs\n  period:\
  \ null\n  text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\nresidency:\n- region: Global\n  text: We maintain servers around the world and your information may be processed on servers located outside of\n    the country where you live.\ntransfers:\n- mechanism: other\n  text: We also comply with certain legal frameworks relating to the transfer of data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy controls and My Activity; delete your content, specific items, or entire Google Account\n  text: Delete your entire Google Account\nrights:\n- right: Access, correct, and delete\n  text: they give you the right to access your information, sometimes in a portable format; correct your information;\n    and to request that Google delete that information.\n- right: Opt out of profiling and targeted advertising\n  text: Many of these laws also\
  \ provide the right to opt out of certain forms of profiling and targeted advertising.\n- right: Non-discrimination\n  text: They also provide the right to not be discriminated against for exercising these privacy rights.\nsale_or_sharing:\n  stance: prohibited\n  text: Google does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/google-play-console/privacy/google-play-console-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Google Play Console Developer Reporting's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Android
- Application
- Google Play Console
- Quality
- Reporting
---
