---
api_specs:
- filename: google-tag-manager-accounts-api-openapi.yml
  format: yaml
  label: Google Tag Manager Accounts API
  slug: google-tag-manager-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-tag-manager/openapi/google-tag-manager-accounts-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers and similar information such as your name and password, phone number, and address, as well as unique identifiers tied to the browser, application, or device you’re using.
  - category: contact
    text: like an email address to communicate with Google or receive updates about our services
  - category: location
    text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around your device
  - category: behavioral
    text: Internet, network, and other activity information such as your search terms; views and interactions with content and ads
  - category: device
    text: browser type and settings, device type and settings, operating system, mobile network information including carrier name and phone number, and application version number
  - category: financial
    text: Commercial information such as your payment information and a history of purchases you make on Google’s services.
  - category: health
    text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics
  - category: biometric
    text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development studies.
  - category: communication
    text: Communications data , such as emails, if you use our services to send and receive messages .
  - category: demographic
    text: Demographic information , such as your age , gender and language .
  deletion:
    route: Privacy Policy deletion tools in Google Account and My Activity
    text: 'To delete your information, you can: Delete your content from specific Google services'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to deliver our services
  - purpose: Personalized content and ads
    text: We use the information we collect to tailor our services for you
  - purpose: Measure performance
    text: We use data for analytics and measurement to understand how our services are used.
  - purpose: Communicate with you
    text: We use information we collect, like your email address, to interact with you directly.
  - purpose: Protect Google, users and public
    text: We use information to help improve the safety and reliability of our services.
  residency:
  - region: Global
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: Activity information in account
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
  - right: Opt out of targeted advertising
    text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.
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
name: Google Tag Manager
provenance_date: '2026-11-09'
provider_name: Google Tag Manager
provider_slug: google-tag-manager
slug: google-tag-manager-privacy-policy
source_date: '2026-11-09'
source_filename: google-tag-manager-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google Tag Manager\naid: google-tag-manager\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: This Privacy Policy applies to all of the services offered by Google LLC and its affiliates\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: contact\n  text: like an email address to communicate with Google or receive updates about our services\n\
  - category: location\n  text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around\n    your device\n- category: behavioral\n  text: Internet, network, and other activity information such as your search terms; views and interactions with\n    content and ads\n- category: device\n  text: browser type and settings, device type and settings, operating system, mobile network information including\n    carrier name and phone number, and application version number\n- category: financial\n  text: Commercial information such as your payment information and a history of purchases you make on Google’s\n    services.\n- category: health\n  text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics\n- category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\n- category: communication\n  text: Communications\
  \ data , such as emails, if you use our services to send and receive messages .\n- category: demographic\n  text: Demographic information , such as your age , gender and language .\npurposes:\n- purpose: Provide services\n  text: We use your information to deliver our services\n- purpose: Personalized content and ads\n  text: We use the information we collect to tailor our services for you\n- purpose: Measure performance\n  text: We use data for analytics and measurement to understand how our services are used.\n- purpose: Communicate with you\n  text: We use information we collect, like your email address, to interact with you directly.\n- purpose: Protect Google, users and public\n  text: We use information to help improve the safety and reliability of our services.\nretention:\n- scope: Activity information in account\n  period: null\n  text: We’ll keep this data in your Google Account until you remove it or choose to have it removed.\n- scope: Advertising data in server logs\n  period:\
  \ null\n  text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\nresidency:\n- region: Global\n  text: We maintain servers around the world and your information may be processed on servers located outside of\n    the country where you live.\ntransfers:\n- mechanism: other\n  text: We also comply with certain legal frameworks relating to the transfer of data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy Policy deletion tools in Google Account and My Activity\n  text: 'To delete your information, you can: Delete your content from specific Google services'\nrights:\n- right: Access and export\n  text: These tools allow you to access, review, update and delete your information, as well as export and download\n    a copy of it.\n- right: Correct\n  text: correct your information\n- right: Delete\n  text: to request that Google delete that\
  \ information.\n- right: Opt out of targeted advertising\n  text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.\nsale_or_sharing:\n  stance: prohibited\n  text: Google does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/google-tag-manager/privacy/google-tag-manager-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Google Tag Manager's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Conversion Tracking
- Marketing
- Tag Management
- Tracking
---
