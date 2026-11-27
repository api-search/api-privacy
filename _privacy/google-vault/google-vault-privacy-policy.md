---
api_specs:
- filename: google-vault-matters-api-openapi.yml
  format: yaml
  label: Google Vault Matters API
  slug: google-vault-matters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-vault/openapi/google-vault-matters-api-openapi.yml
- filename: google-vault-operations-api-openapi.yml
  format: yaml
  label: Google Vault Operations API
  slug: google-vault-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-vault/openapi/google-vault-operations-api-openapi.yml
claim_count: 18
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
    route: Delete content, activity, products, or entire Google Account
    text: 'To delete your information, you can: Delete your content from specific Google services'
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
  - purpose: Communicate with you
    text: We use information we collect, like your email address, to interact with you directly.
  residency:
  - region: Global servers
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: Activity information in account
    text: You can also delete activity information saved in your account, or choose to have it deleted automatically after a set period of time.
  - period: null
    scope: Other data
    text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in server logs.
  rights:
  - right: Access, review, update and delete
    text: These tools allow you to access, review, update and delete your information, as well as export and download a copy of it.
  - right: Export
    text: You can export a copy of content in your Google Account if you want to back it up or use it with a service outside of Google.
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
name: Google Vault
provenance_date: '2026-11-09'
provider_name: Google Vault
provider_slug: google-vault
slug: google-vault-privacy-policy
source_date: '2026-11-09'
source_filename: google-vault-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google Vault\naid: google-vault\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: location\n  text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around\n    your device\n- category: health\n  text: Health information if you choose\
  \ to provide it, such as your medical history, vital signs and health metrics\n    (like blood glucose levels)\n- category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\npurposes:\n- purpose: Provide services\n  text: We use your information to deliver our services\n- purpose: Maintain and improve services\n  text: we use your information to make improvements to our services\n- purpose: Personalized services and ads\n  text: We use the information we collect to tailor our services for you\n- purpose: Communicate with you\n  text: We use information we collect, like your email address, to interact with you directly.\nretention:\n- scope: Activity information in account\n  period: null\n  text: You can also delete activity information saved in your account, or choose to have it deleted automatically\n    after a set period of time.\n- scope: Other data\n  period: null\n  text: Other data is deleted\
  \ or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\nresidency:\n- region: Global servers\n  text: We maintain servers around the world and your information may be processed on servers located outside of\n    the country where you live.\ntransfers:\n- mechanism: other\n  text: We also comply with certain legal frameworks relating to the transfer of data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete content, activity, products, or entire Google Account\n  text: 'To delete your information, you can: Delete your content from specific Google services'\nrights:\n- right: Access, review, update and delete\n  text: These tools allow you to access, review, update and delete your information, as well as export and download\n    a copy of it.\n- right: Export\n  text: You can export a copy of content in your Google Account if you want to back it up or use it with a service\n\
  \    outside of Google.\n- right: Opt out of profiling and targeted advertising\n  text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.\n- right: Non-discrimination\n  text: They also provide the right to not be discriminated against for exercising these privacy rights.\nsale_or_sharing:\n  stance: prohibited\n  text: Google does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/google-vault/privacy/google-vault-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Google Vault's own page on 2026-11-09.
synthetic: false
tags:
- eDiscovery
- Legal Hold
- Information Governance
- Compliance
- Archiving
- Retention
- Google Workspace
- Audit
---
