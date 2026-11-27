---
api_specs:
- filename: google-gmail-domains-api-openapi.yml
  format: yaml
  label: Google Gmail Domains API
  slug: google-gmail-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gmail/openapi/google-gmail-domains-api-openapi.yml
- filename: google-gmail-domainstats-api-openapi.yml
  format: yaml
  label: Google Gmail Domain Stats API
  slug: google-gmail-domainstats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gmail/openapi/google-gmail-domainstats-api-openapi.yml
- filename: google-gmail-users-api-openapi.yml
  format: yaml
  label: Google Gmail Users API
  slug: google-gmail-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-gmail/openapi/google-gmail-users-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers and similar information such as your name and password, phone number, and address, as well as unique identifiers tied to the browser, application, or device you’re using.
  - category: location
    text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around your device
  - category: communication
    text: Communications data , such as emails, if you use our services to send and receive messages .
  - category: financial
    text: Commercial information such as your payment information and a history of purchases you make on Google’s services.
  - category: health
    text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics (like blood glucose levels)
  - category: biometric
    text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development studies.
  deletion:
    route: Delete your information from your Google Account, or delete specific content or products
    text: 'To delete your information, you can: Delete your content from specific Google services'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to deliver our services
  - purpose: Maintain and improve services
    text: We also use your information to ensure our services are working as intended
  - purpose: Personalized services and ads
    text: We use the information we collect to tailor our services for you
  - purpose: Measure performance
    text: We use data for analytics and measurement to understand how our services are used.
  - purpose: Protect Google, users and public
    text: We use information to help improve the safety and reliability of our services.
  residency:
  - region: Global
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: Data in Google Account
    text: We’ll keep this data in your Google Account until you remove it or choose to have it removed.
  - period: null
    scope: Advertising data in server logs
    text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in server logs.
  rights:
  - right: Access and export
    text: These tools allow you to access, review, update and delete your information, as well as export and download a copy of it.
  - right: Correct
    text: correct your information
  - right: Delete
    text: to request that Google delete that information.
  - right: Opt out of profiling and targeted advertising
    text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Google does not sell your personal information. Google also does not “share” your personal information as that term is defined in the California Consumer Privacy Act (CCPA).
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
name: Google Gmail
provenance_date: '2026-11-09'
provider_name: Google Gmail
provider_slug: google-gmail
slug: google-gmail-privacy-policy
source_date: '2026-11-09'
source_filename: google-gmail-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google Gmail\naid: google-gmail\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: location\n  text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around\n    your device\n- category: communication\n  text: Communications data , such\
  \ as emails, if you use our services to send and receive messages .\n- category: financial\n  text: Commercial information such as your payment information and a history of purchases you make on Google’s\n    services.\n- category: health\n  text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics\n    (like blood glucose levels)\n- category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\npurposes:\n- purpose: Provide services\n  text: We use your information to deliver our services\n- purpose: Maintain and improve services\n  text: We also use your information to ensure our services are working as intended\n- purpose: Personalized services and ads\n  text: We use the information we collect to tailor our services for you\n- purpose: Measure performance\n  text: We use data for analytics and measurement to understand how our services are used.\n\
  - purpose: Protect Google, users and public\n  text: We use information to help improve the safety and reliability of our services.\nretention:\n- scope: Data in Google Account\n  period: null\n  text: We’ll keep this data in your Google Account until you remove it or choose to have it removed.\n- scope: Advertising data in server logs\n  period: null\n  text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\nresidency:\n- region: Global\n  text: We maintain servers around the world and your information may be processed on servers located outside of\n    the country where you live.\ntransfers:\n- mechanism: other\n  text: We also comply with certain legal frameworks relating to the transfer of data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your information from your Google Account, or delete specific content or products\n  text: 'To\
  \ delete your information, you can: Delete your content from specific Google services'\nrights:\n- right: Access and export\n  text: These tools allow you to access, review, update and delete your information, as well as export and download\n    a copy of it.\n- right: Correct\n  text: correct your information\n- right: Delete\n  text: to request that Google delete that information.\n- right: Opt out of profiling and targeted advertising\n  text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.\nsale_or_sharing:\n  stance: prohibited\n  text: Google does not sell your personal information. Google also does not “share” your personal information as\n    that term is defined in the California Consumer Privacy Act (CCPA).\n"
source_yaml_url: https://artifacts.apis.io/google-gmail/privacy/google-gmail-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Google Gmail's own page on 2026-11-09.
synthetic: false
tags:
- Drafts
- Email
- Gmail
- Google
- Google Workspace
- Labels
- Messaging
- Threads
---
