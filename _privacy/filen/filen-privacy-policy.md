---
api_specs:
- filename: filen-health-api-openapi.yml
  format: yaml
  label: Filen Health API
  slug: filen-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-health-api-openapi.yml
- filename: filen-items-api-openapi.yml
  format: yaml
  label: Filen Items API
  slug: filen-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-items-api-openapi.yml
- filename: filen-shared-api-openapi.yml
  format: yaml
  label: Filen Shared API
  slug: filen-shared-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-shared-api-openapi.yml
- filename: filen-user-api-openapi.yml
  format: yaml
  label: Filen User API
  slug: filen-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-user-api-openapi.yml
- filename: filen-auth-api-openapi.yml
  format: yaml
  label: Filen Auth API
  slug: filen-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-auth-api-openapi.yml
- filename: filen-chat-api-openapi.yml
  format: yaml
  label: Filen Chat API
  slug: filen-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-chat-api-openapi.yml
- filename: filen-contacts-api-openapi.yml
  format: yaml
  label: Filen Contacts API
  slug: filen-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-contacts-api-openapi.yml
- filename: filen-dir-api-openapi.yml
  format: yaml
  label: Filen Dir API
  slug: filen-dir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-dir-api-openapi.yml
- filename: filen-directories-api-openapi.yml
  format: yaml
  label: Filen Directories API
  slug: filen-directories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-directories-api-openapi.yml
- filename: filen-file-api-openapi.yml
  format: yaml
  label: Filen File API
  slug: filen-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-file-api-openapi.yml
- filename: filen-file-transfers-api-openapi.yml
  format: yaml
  label: Filen File Transfers API
  slug: filen-file-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-file-transfers-api-openapi.yml
- filename: filen-internal-api-openapi.yml
  format: yaml
  label: Filen (internal) API
  slug: filen-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-internal-api-openapi.yml
- filename: filen-item-api-openapi.yml
  format: yaml
  label: Filen Item API
  slug: filen-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-item-api-openapi.yml
- filename: filen-misc-api-openapi.yml
  format: yaml
  label: Filen Misc API
  slug: filen-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-misc-api-openapi.yml
- filename: filen-mobile-api-openapi.yml
  format: yaml
  label: Filen Mobile API
  slug: filen-mobile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-mobile-api-openapi.yml
- filename: filen-notes-api-openapi.yml
  format: yaml
  label: Filen Notes API
  slug: filen-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filen/openapi/filen-notes-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you upload a file, it is already encrypted on your device, so we do not know if it belongs to you or another person
  - category: contact
    text: 'User Data: When you submit a suggestion, personal data such as your name, email address (if provided), and IP address may be processed.'
  - category: device
    text: 'Usage Data: We collect technical data such as access times, browser type, and operating system to ensure the security and functionality of the tool.'
  deletion:
    route: Contact support or delete files in the account; files are marked for deletion and removed at the next file cleanup
    text: Upon account deletion, all of your files will be marked for deletion and removed at the next appropriate file cleanup
  dpa:
    available: true
    text: The data processing addendum corresponding to the standard contractual clauses can be found at https://sentry.io/legal/dpa/ .
    url: https://sentry.io/legal/dpa/
  purposes:
  - purpose: provide encrypted cloud storage
    text: We collect your files because we need them to provide our encrypted cloud storage and collaboration services
  - purpose: website analytics
    text: We use the self hosted web analytics service “Plausible Analytics“ to continuously optimize our offer, both technically and in terms of content.
  - purpose: bot protection
    text: The processing is carried out for the purpose of ensuring the security and functionality of our website and preventing misuse.
  residency:
  - region: Germany
    text: We secure all data on servers hosted in Germany.
  retention:
  - period: null
    scope: files while subscribed
    text: We will retain your files for as long as you are subscribed to our Services
  - period: two months
    scope: job applications rejected
    text: If an application is rejected, we automatically delete the data provided to us two months after notification of the rejection.
  rights:
  - right: access
    text: Right of access according to Art. 15 GDPR
  - right: deletion
    text: Deletion according to Art. 17 GDPR
  - right: correction
    text: Correction according to Art. 16 GDPR
  - right: restriction of processing
    text: Restriction of processing according to Art. 18 GDPR
  - right: objection
    text: Objection according to Art. 21 GDPR
  - right: complaint to supervisory authority
    text: right to lodge a complaint with a competent supervisory authority
  role:
    text: Filen Cloud Dienste UG (haftungsbeschränkt) Breite Str. 27 45657 Recklinghausen Germany
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your files, account data or usage data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: As a basis for data processing at recipients located in third countries (outside the European Union, Iceland, Liechtenstein, Norway, thus especially in the USA) or a data transfer there, PayPal uses so-called standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Filen
provenance_date: '2026-11-09'
provider_name: Filen
provider_slug: filen
slug: filen-privacy-policy
source_date: '2026-11-09'
source_filename: filen-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://filen.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Filen\naid: filen\nurl: https://filen.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Filen Cloud Dienste UG (haftungsbeschränkt) Breite Str. 27 45657 Recklinghausen Germany\ndata_categories:\n- category: identifying\n  text: When you upload a file, it is already encrypted on your device, so we do not know if it belongs to you or\n    another person\n- category: contact\n  text: 'User Data: When you submit a suggestion, personal data such as your name, email address (if provided),\n    and IP address may be processed.'\n- category: device\n  text: 'Usage Data: We collect technical\
  \ data such as access times, browser type, and operating system to ensure\n    the security and functionality of the tool.'\npurposes:\n- purpose: provide encrypted cloud storage\n  text: We collect your files because we need them to provide our encrypted cloud storage and collaboration services\n- purpose: website analytics\n  text: We use the self hosted web analytics service “Plausible Analytics“ to continuously optimize our offer, both\n    technically and in terms of content.\n- purpose: bot protection\n  text: The processing is carried out for the purpose of ensuring the security and functionality of our website\n    and preventing misuse.\nretention:\n- scope: files while subscribed\n  period: null\n  text: We will retain your files for as long as you are subscribed to our Services\n- scope: job applications rejected\n  period: two months\n  text: If an application is rejected, we automatically delete the data provided to us two months after notification\n    of the rejection.\n\
  residency:\n- region: Germany\n  text: We secure all data on servers hosted in Germany.\ntransfers:\n- mechanism: SCC\n  text: As a basis for data processing at recipients located in third countries (outside the European Union, Iceland,\n    Liechtenstein, Norway, thus especially in the USA) or a data transfer there, PayPal uses so-called standard\n    contractual clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://sentry.io/legal/dpa/\n  text: The data processing addendum corresponding to the standard contractual clauses can be found at https://sentry.io/legal/dpa/\n    .\ndeletion:\n  route: Contact support or delete files in the account; files are marked for deletion and removed at the next file\n    cleanup\n  text: Upon account deletion, all of your files will be marked for deletion and removed at the next appropriate\n    file cleanup\nrights:\n- right: access\n  text: Right of access according to Art. 15 GDPR\n- right: deletion\n  text: Deletion\
  \ according to Art. 17 GDPR\n- right: correction\n  text: Correction according to Art. 16 GDPR\n- right: restriction of processing\n  text: Restriction of processing according to Art. 18 GDPR\n- right: objection\n  text: Objection according to Art. 21 GDPR\n- right: complaint to supervisory authority\n  text: right to lodge a complaint with a competent supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your files, account data or usage data.\n"
source_yaml_url: https://artifacts.apis.io/filen/privacy/filen-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Filen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Storage
- Encryption
- Zero Knowledge
- File Sync
---
