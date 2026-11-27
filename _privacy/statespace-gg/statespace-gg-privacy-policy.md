---
api_specs:
- filename: statespace-gg-openapi-generated.yml
  format: yaml
  label: Statespace API
  slug: statespace-gg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statespace-gg/openapi/_ae-authored/statespace-gg-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Sign-in provider, provider identity, login name, internal account identifier, plan, and account configuration.
  - category: contact
    text: The name, email address, and message you submit through the contact form, plus later correspondence.
  - category: device
    text: Technical request information. Our service and hosting providers may process network addresses, requested URLs, response status, and other request metadata to deliver and protect the service.
  - category: behavioral
    text: 'for each subject of an arm, a one-way hash of the subject identifier with counts: requests, 4xx and 5xx responses, response times in fixed ranges, and matched events.'
  - category: communication
    text: Access and activity records. Session and credential records, credential metadata, account actions, timestamps, and audit records.
  deletion:
    route: Contact us to request account closure, deletion, or details about retention for a specific record type.
    text: Contact us to request account closure, deletion, or details about retention for a specific record type.
  dpa:
    available: null
    text: any applicable data processing agreement also govern the processing
    url: null
  purposes:
  - purpose: authenticate users and operate accounts
    text: We use information to authenticate users, operate accounts, store experiment builds and counts, show evidence and usage reports, enforce account limits, and maintain audit records.
  - purpose: respond to messages
    text: We also use it to respond to messages, investigate errors and abuse, protect the service, and meet legal obligations.
  residency:
  - region: United States
    text: Our infrastructure includes services in the United States.
  retention:
  - period: null
    scope: subject counts in running experiment versions
    text: Statespace keeps the counts of each subject only while their experiment version runs.
  - period: null
    scope: final results of each arm
    text: When the version stops, it keeps only the final results of each arm.
  - period: null
    scope: audit record of an erasure
    text: The audit record of an erasure keeps the hash of the subject, not the subject identifier.
  rights:
  - right: access, correct, delete, or obtain a copy
    text: Depending on applicable law, you may have rights to access, correct, delete, or obtain a copy of personal information, or to object to or restrict its processing.
  - right: withdraw consent
    text: You may also have a right to withdraw consent or complain to a supervisory authority.
  role:
    text: Statespace Technologies, Inc. (“Statespace,” “we,” “us”) operates the service.
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The implementation uses Amazon Web Services for website delivery, artifact storage, and contact email delivery.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Statespace
provenance_date: '2026-11-10'
provider_name: Statespace
provider_slug: statespace-gg
slug: statespace-gg-privacy-policy
source_date: '2026-11-10'
source_filename: statespace-gg-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://statespace.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Statespace\naid: statespace-gg\nurl: https://statespace.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: Statespace Technologies, Inc. (“Statespace,” “we,” “us”) operates the service.\ndata_categories:\n- category: identifying\n  text: Sign-in provider, provider identity, login name, internal account identifier, plan, and account configuration.\n- category: contact\n  text: The name, email address, and message you submit through the contact form, plus later correspondence.\n- category: device\n  text: Technical request information. Our service and hosting providers may process network\
  \ addresses, requested\n    URLs, response status, and other request metadata to deliver and protect the service.\n- category: behavioral\n  text: 'for each subject of an arm, a one-way hash of the subject identifier with counts: requests, 4xx and 5xx\n    responses, response times in fixed ranges, and matched events.'\n- category: communication\n  text: Access and activity records. Session and credential records, credential metadata, account actions, timestamps,\n    and audit records.\npurposes:\n- purpose: authenticate users and operate accounts\n  text: We use information to authenticate users, operate accounts, store experiment builds and counts, show evidence\n    and usage reports, enforce account limits, and maintain audit records.\n- purpose: respond to messages\n  text: We also use it to respond to messages, investigate errors and abuse, protect the service, and meet legal\n    obligations.\nretention:\n- scope: subject counts in running experiment versions\n  period: null\n\
  \  text: Statespace keeps the counts of each subject only while their experiment version runs.\n- scope: final results of each arm\n  period: null\n  text: When the version stops, it keeps only the final results of each arm.\n- scope: audit record of an erasure\n  period: null\n  text: The audit record of an erasure keeps the hash of the subject, not the subject identifier.\nresidency:\n- region: United States\n  text: Our infrastructure includes services in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: The implementation uses Amazon Web Services for website delivery, artifact storage, and contact email delivery.\ndpa:\n  available: null\n  url: null\n  text: any applicable data processing agreement also govern the processing\ndeletion:\n  route: Contact us to request account closure, deletion, or details about retention for a specific record type.\n  text: Contact us to request account closure, deletion, or details about retention for a specific record type.\n\
  rights:\n- right: access, correct, delete, or obtain a copy\n  text: Depending on applicable law, you may have rights to access, correct, delete, or obtain a copy of personal\n    information, or to object to or restrict its processing.\n- right: withdraw consent\n  text: You may also have a right to withdraw consent or complain to a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/statespace-gg/privacy/statespace-gg-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 17 quoted statements, read from Statespace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Simulation
- Analytics
- Cloud
- Engineering
---
