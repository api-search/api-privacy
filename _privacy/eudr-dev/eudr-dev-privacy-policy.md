---
api_specs:
- filename: eudr-dev-a2a-api-openapi.yml
  format: yaml
  label: eudr.dev A2a API
  slug: eudr-dev-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-a2a-api-openapi.yml
- filename: eudr-dev-agent-api-openapi.yml
  format: yaml
  label: eudr.dev Agent API
  slug: eudr-dev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-agent-api-openapi.yml
- filename: eudr-dev-discovery-api-openapi.yml
  format: yaml
  label: eudr.dev Discovery API
  slug: eudr-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-discovery-api-openapi.yml
- filename: eudr-dev-engineer-api-openapi.yml
  format: yaml
  label: eudr.dev Engineer API
  slug: eudr-dev-engineer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-engineer-api-openapi.yml
- filename: eudr-dev-ops-api-openapi.yml
  format: yaml
  label: eudr.dev Ops API
  slug: eudr-dev-ops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-ops-api-openapi.yml
- filename: eudr-dev-public-api-openapi.yml
  format: yaml
  label: eudr.dev Public API
  slug: eudr-dev-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-public-api-openapi.yml
- filename: eudr-dev-reference-api-openapi.yml
  format: yaml
  label: eudr.dev Reference API
  slug: eudr-dev-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eudr-dev/openapi/eudr-dev-reference-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Operator name, address, EORI identifying data (personal when natural-person operator)
  - category: contact
    text: 'Email address identifying data the only credential: sign-in is a one-time link, there is no password'
  - category: location
    text: Plot geolocation (Polygon or Point) location data; may be personal when it identifies a smallholder
  - category: financial
    text: Credit balance and ledger (credits bought, spent, when)
  - category: device
    text: Browser user-agent technical reproducing a bug you report
  - category: communication
    text: Your message whatever you choose to write to answer you
  deletion:
    route: DELETE /app/api/account and DELETE /a2a/tasks/:id; farm and visit deletion in-app
    text: DELETE /app/api/account deletes the user row and revokes all sessions
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: EUDR due diligence
    text: Lawful basis Art. 6(1)(c) GDPR. Legal obligation. The obligation is the EUDR due diligence duty
  - purpose: Charging for statements and answering disputed charges
    text: Credit balance and ledger (credits bought, spent, when) account metadata charging for statements, and answering a disputed charge
  residency:
  - region: EU (Stockholm, Sweden)
    text: AWS EMEA SARL — compute, database, stored files, SES everything held by the service, including farm records and stored files; outbound email recipients eu-north-1 Stockholm, Sweden
  retention:
  - period: 5 years from the statement
    scope: Due diligence statements
    text: Due diligence statements held on eudr.dev (Annex II body, signed receipt) 5 years from the statement, then erased by the hourly sweep.
  - period: 30 days from issue
    scope: OAuth refresh tokens
    text: OAuth refresh tokens 30 days from issue, rotated on each use
  - period: 2 years
    scope: Answered support enquiries
    text: Answered support enquiries 2 years
  - period: 7 days
    scope: Uploads abandoned part-way
    text: Uploads abandoned part-way 7 days
  rights:
  - right: Access (Art. 15)
    text: GET /app/api/account/export returns everything we hold on you as a single JSON file
  - right: Rectification (Art. 16)
    text: Edit your details in the dashboard or re-submit the corrected scenario.
  - right: Erasure (Art. 17)
    text: Deleting a farm or a visit (owner or admin) deletes its records and any stored file nothing else refers to.
  - right: Portability (Art. 20)
    text: 'The Art. 15 export is the portability artifact: a single JSON file in a structured, commonly-used, machine-readable format (RFC 8259 JSON)'
  - right: Object (Art. 21)
    text: The lawful basis is Art. 6(1)(c) (legal obligation), so the absolute Art. 21(1) right to object does not apply.
  - right: Lodge a complaint
    text: With your national supervisory authority.
  role:
    text: 'Processor : Vortx AI Private Limited, operating eudr.dev , acting on the controller''s instructions.'
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The full catalogue with lawful-basis routes and the 30-day change- notice procedure is at /legal/subprocessors .
    url: /legal/subprocessors
  transfers:
  - mechanism: DPF
    text: onward transfer to Google LLC (US) under the EU-US Data Privacy Framework
  - mechanism: other
    text: 'emem.dev is a transfer outside the EEA. Data transferred: plot geometry, HS code, country, quantity.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: eudr.dev
provenance_date: '2026-11-09'
provider_name: eudr.dev
provider_slug: eudr-dev
slug: eudr-dev-privacy-policy
source_date: '2026-11-09'
source_filename: eudr-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eudr.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: eudr.dev\naid: eudr-dev\nurl: https://eudr.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Processor : Vortx AI Private Limited, operating eudr.dev , acting on the controller''s instructions.'\ndata_categories:\n- category: identifying\n  text: Operator name, address, EORI identifying data (personal when natural-person operator)\n- category: contact\n  text: 'Email address identifying data the only credential: sign-in is a one-time link, there is no password'\n- category: location\n  text: Plot geolocation (Polygon or Point) location data; may be personal when it identifies a smallholder\n\
  - category: financial\n  text: Credit balance and ledger (credits bought, spent, when)\n- category: device\n  text: Browser user-agent technical reproducing a bug you report\n- category: communication\n  text: Your message whatever you choose to write to answer you\npurposes:\n- purpose: EUDR due diligence\n  text: Lawful basis Art. 6(1)(c) GDPR. Legal obligation. The obligation is the EUDR due diligence duty\n- purpose: Charging for statements and answering disputed charges\n  text: Credit balance and ledger (credits bought, spent, when) account metadata charging for statements, and answering\n    a disputed charge\nretention:\n- scope: Due diligence statements\n  period: 5 years from the statement\n  text: Due diligence statements held on eudr.dev (Annex II body, signed receipt) 5 years from the statement, then\n    erased by the hourly sweep.\n- scope: OAuth refresh tokens\n  period: 30 days from issue\n  text: OAuth refresh tokens 30 days from issue, rotated on each use\n- scope: Answered\
  \ support enquiries\n  period: 2 years\n  text: Answered support enquiries 2 years\n- scope: Uploads abandoned part-way\n  period: 7 days\n  text: Uploads abandoned part-way 7 days\nresidency:\n- region: EU (Stockholm, Sweden)\n  text: AWS EMEA SARL — compute, database, stored files, SES everything held by the service, including farm records\n    and stored files; outbound email recipients eu-north-1 Stockholm, Sweden\ntransfers:\n- mechanism: DPF\n  text: onward transfer to Google LLC (US) under the EU-US Data Privacy Framework\n- mechanism: other\n  text: 'emem.dev is a transfer outside the EEA. Data transferred: plot geometry, HS code, country, quantity.'\nsubprocessors:\n  url: /legal/subprocessors\n  text: The full catalogue with lawful-basis routes and the 30-day change- notice procedure is at /legal/subprocessors\n    .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: DELETE /app/api/account and DELETE /a2a/tasks/:id; farm and visit deletion in-app\n  text:\
  \ DELETE /app/api/account deletes the user row and revokes all sessions\nrights:\n- right: Access (Art. 15)\n  text: GET /app/api/account/export returns everything we hold on you as a single JSON file\n- right: Rectification (Art. 16)\n  text: Edit your details in the dashboard or re-submit the corrected scenario.\n- right: Erasure (Art. 17)\n  text: Deleting a farm or a visit (owner or admin) deletes its records and any stored file nothing else refers\n    to.\n- right: Portability (Art. 20)\n  text: 'The Art. 15 export is the portability artifact: a single JSON file in a structured, commonly-used, machine-readable\n    format (RFC 8259 JSON)'\n- right: Object (Art. 21)\n  text: The lawful basis is Art. 6(1)(c) (legal obligation), so the absolute Art. 21(1) right to object does not\n    apply.\n- right: Lodge a complaint\n  text: With your national supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eudr-dev/privacy/eudr-dev-privacy-policy.yml
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
summary_line: 24 quoted statements, read from eudr.dev's own page on 2026-11-09.
synthetic: false
tags:
- EU Deforestation
- Compliance
- Agriculture
- AI
- Environmental
---
