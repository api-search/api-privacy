---
api_specs:
- filename: salad-transcription-api-default-api-openapi.yml
  format: yaml
  label: Salad Transcription API Default API
  slug: salad-transcription-api-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salad-transcription-api/openapi/salad-transcription-api-default-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact details and messages you send us
  - category: financial
    text: billing details processed by Stripe (we do not store full card numbers)
  - category: device
    text: a persistent machine identifier and your computer's CPU, GPU, RAM, storage, operating system, and driver details
  - category: location
    text: your public IP address and the country and region derived from it
  - category: communication
    text: support and sales communications
  - category: other
    text: transcription media and transcripts
  deletion:
    route: email privacy request
    text: Email [email protected] from your account email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account operation and authentication
    text: To run accounts and authenticate users
  - purpose: billing and payouts
    text: to pay Chefs and bill customers
  - purpose: support
    text: to provide support
  - purpose: service improvement
    text: to understand how our products are used so we can improve them
  - purpose: workload data processing
    text: We process it only to provide the service, keep the platform secure, enforce our Terms, and comply with law.
  residency:
  - region: United States
    text: Salad is based in the United States, and we and our providers process information there and in other countries
  - region: worldwide
    text: Chef machines are located worldwide
  retention:
  - period: Up to 95 days
    scope: Container logs and metrics
    text: Up to 95 days
  - period: as needed to complete and return your job
    scope: Transcription API media and transcripts
    text: Media and transcripts kept as needed to complete and return your job
  - period: null
    scope: Account, billing, earning and redemption information
    text: We keep account, billing, earning, and redemption information for as long as your account exists
  - period: null
    scope: AI Gateway content
    text: Content not stored
  rights:
  - right: access, correction, deletion, portability
    text: you may have the right to access, correct, delete, or receive a copy of your personal information
  - right: object or restrict processing
    text: to object to or restrict certain processing
  - right: withdraw consent
    text: and to withdraw consent
  role:
    text: Where Workload Data includes personal information about a customer's users, the customer is the controller and we are the processor.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: A list of our infrastructure subprocessors is available through the Trust Center
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on standard contractual clauses for transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Salad Transcription API
provenance_date: '2026-11-10'
provider_name: Salad Transcription API
provider_slug: salad-transcription-api
slug: salad-transcription-api-privacy-policy
source_date: '2026-11-10'
source_filename: salad-transcription-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://salad.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Salad Transcription API\naid: salad-transcription-api\nurl: https://salad.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Where Workload Data includes personal information about a customer's users, the customer is the controller\n    and we are the processor.\ndata_categories:\n- category: contact\n  text: Contact details and messages you send us\n- category: financial\n  text: billing details processed by Stripe (we do not store full card numbers)\n- category: device\n  text: a persistent machine identifier and your computer's CPU, GPU, RAM, storage, operating system, and driver\n\
  \    details\n- category: location\n  text: your public IP address and the country and region derived from it\n- category: communication\n  text: support and sales communications\n- category: other\n  text: transcription media and transcripts\npurposes:\n- purpose: account operation and authentication\n  text: To run accounts and authenticate users\n- purpose: billing and payouts\n  text: to pay Chefs and bill customers\n- purpose: support\n  text: to provide support\n- purpose: service improvement\n  text: to understand how our products are used so we can improve them\n- purpose: workload data processing\n  text: We process it only to provide the service, keep the platform secure, enforce our Terms, and comply with\n    law.\nretention:\n- scope: Container logs and metrics\n  period: Up to 95 days\n  text: Up to 95 days\n- scope: Transcription API media and transcripts\n  period: as needed to complete and return your job\n  text: Media and transcripts kept as needed to complete and return\
  \ your job\n- scope: Account, billing, earning and redemption information\n  period: null\n  text: We keep account, billing, earning, and redemption information for as long as your account exists\n- scope: AI Gateway content\n  period: null\n  text: Content not stored\nresidency:\n- region: United States\n  text: Salad is based in the United States, and we and our providers process information there and in other countries\n- region: worldwide\n  text: Chef machines are located worldwide\ntransfers:\n- mechanism: SCC\n  text: we rely on standard contractual clauses for transfers\nsubprocessors:\n  url: null\n  text: A list of our infrastructure subprocessors is available through the Trust Center\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy request\n  text: Email [email protected] from your account email.\nrights:\n- right: access, correction, deletion, portability\n  text: you may have the right to access, correct, delete, or receive a copy of your\
  \ personal information\n- right: object or restrict processing\n  text: to object to or restrict certain processing\n- right: withdraw consent\n  text: and to withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/salad-transcription-api/privacy/salad-transcription-api-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Salad Transcription API's own page on 2026-11-10.
synthetic: false
tags:
- Audio Transcription
- Captions
- Diarization
- GPU
- Speech Recognition
- Transcription
- Video Processing
---
