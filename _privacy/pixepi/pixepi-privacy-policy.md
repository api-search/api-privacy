---
api_specs:
- filename: pixepi-apps-api-openapi.yml
  format: yaml
  label: Pixepi Apps API
  slug: pixepi-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixepi/openapi/pixepi-apps-api-openapi.yml
- filename: pixepi-jobs-api-openapi.yml
  format: yaml
  label: Pixepi Jobs API
  slug: pixepi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixepi/openapi/pixepi-jobs-api-openapi.yml
- filename: pixepi-usage-api-openapi.yml
  format: yaml
  label: Pixepi Usage API
  slug: pixepi-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixepi/openapi/pixepi-usage-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: if you create an account, your email address and optionally your name are stored
  - category: device
    text: 'Technical records: limited records such as IP address and browser information may be kept to prevent abuse and unauthorised access.'
  - category: behavioral
    text: 'Job records: the tool name, job time, file name and size, and the result status are kept; file contents are never written to these records.'
  - category: other
    text: 'Files you upload: the file you choose is processed temporarily, only to carry out the job you asked for.'
  deletion:
    route: delete files yourself or close account
    text: If you start the deletion yourself, the file is deleted immediately .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the service
    text: Pixepi processes only the data needed to run the service.
  - purpose: prevent abuse and unauthorised access
    text: limited records such as IP address and browser information may be kept to prevent abuse and unauthorised access.
  - purpose: hosting and traffic security
    text: Only the infrastructure provider needed to run the service and Cloudflare as a security and speed layer process data for hosting and traffic security.
  residency:
  - region: own servers
    text: Files and technical records are processed on our own servers ; files are not stored in third-party cloud storage.
  retention:
  - period: within 24 hours of the job finishing
    scope: guest uploaded files
    text: Files you upload as a guest are deleted automatically within 24 hours of the job finishing.
  - period: 15 days
    scope: member outputs
    text: Member outputs are kept for 15 days ; you can delete them whenever you like.
  - period: 7 days
    scope: member input files
    text: Input files you upload as a member are deleted within 7 days ; outputs live longer than that.
  - period: within 30 days
    scope: account record after closure
    text: your account record is anonymised within 30 days .
  rights:
  - right: information
    text: 'Information: you can learn whether your data is processed and how.'
  - right: access
    text: 'Access: you can request a copy of the data processed about you.'
  - right: correction
    text: 'Correction: you can ask for incomplete or incorrect data to be corrected.'
  - right: deletion
    text: 'Deletion: you can request that your files and records be deleted.'
  - right: objection and portability
    text: 'Objection and portability: you can object to processing and request your data in a portable format.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Your data is never sold, rented or transferred to third parties for marketing.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Pixepi
provenance_date: '2026-11-10'
provider_name: Pixepi
provider_slug: pixepi
slug: pixepi-privacy-policy
source_date: '2026-11-10'
source_filename: pixepi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pixepi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Pixepi\naid: pixepi\nurl: https://pixepi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: if you create an account, your email address and optionally your name are stored\n- category: device\n  text: 'Technical records: limited records such as IP address and browser information may be kept to prevent abuse\n    and unauthorised access.'\n- category: behavioral\n  text: 'Job records: the tool name, job time, file name and size, and the result status are kept; file contents\n    are never written to these records.'\n- category:\
  \ other\n  text: 'Files you upload: the file you choose is processed temporarily, only to carry out the job you asked for.'\npurposes:\n- purpose: run the service\n  text: Pixepi processes only the data needed to run the service.\n- purpose: prevent abuse and unauthorised access\n  text: limited records such as IP address and browser information may be kept to prevent abuse and unauthorised\n    access.\n- purpose: hosting and traffic security\n  text: Only the infrastructure provider needed to run the service and Cloudflare as a security and speed layer\n    process data for hosting and traffic security.\nretention:\n- scope: guest uploaded files\n  period: within 24 hours of the job finishing\n  text: Files you upload as a guest are deleted automatically within 24 hours of the job finishing.\n- scope: member outputs\n  period: 15 days\n  text: Member outputs are kept for 15 days ; you can delete them whenever you like.\n- scope: member input files\n  period: 7 days\n  text: Input files\
  \ you upload as a member are deleted within 7 days ; outputs live longer than that.\n- scope: account record after closure\n  period: within 30 days\n  text: your account record is anonymised within 30 days .\nresidency:\n- region: own servers\n  text: Files and technical records are processed on our own servers ; files are not stored in third-party cloud\n    storage.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete files yourself or close account\n  text: If you start the deletion yourself, the file is deleted immediately .\nrights:\n- right: information\n  text: 'Information: you can learn whether your data is processed and how.'\n- right: access\n  text: 'Access: you can request a copy of the data processed about you.'\n- right: correction\n  text: 'Correction: you can ask for incomplete or incorrect data to be corrected.'\n- right: deletion\n  text: 'Deletion: you can request that your files and\
  \ records be deleted.'\n- right: objection and portability\n  text: 'Objection and portability: you can object to processing and request your data in a portable format.'\nsale_or_sharing:\n  stance: prohibited\n  text: Your data is never sold, rented or transferred to third parties for marketing.\n"
source_yaml_url: https://artifacts.apis.io/pixepi/privacy/pixepi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Pixepi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tools
- PDF
- Image
---
