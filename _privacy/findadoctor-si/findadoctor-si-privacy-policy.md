---
api_specs:
- filename: findadoctor-si-about-api-openapi.yml
  format: yaml
  label: findadoctor-si About API
  slug: findadoctor-si-about-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-about-api-openapi.yml
- filename: findadoctor-si-doctors-api-openapi.yml
  format: yaml
  label: findadoctor-si Doctors API
  slug: findadoctor-si-doctors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-doctors-api-openapi.yml
- filename: findadoctor-si-gp-practices-api-openapi.yml
  format: yaml
  label: findadoctor-si Gp Practices API
  slug: findadoctor-si-gp-practices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-gp-practices-api-openapi.yml
- filename: findadoctor-si-procedure-volumes-api-openapi.yml
  format: yaml
  label: findadoctor-si Procedure Volumes API
  slug: findadoctor-si-procedure-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-procedure-volumes-api-openapi.yml
- filename: findadoctor-si-procedures-api-openapi.yml
  format: yaml
  label: findadoctor-si Procedures API
  slug: findadoctor-si-procedures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-procedures-api-openapi.yml
- filename: findadoctor-si-search-api-openapi.yml
  format: yaml
  label: findadoctor-si Search API
  slug: findadoctor-si-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-search-api-openapi.yml
- filename: findadoctor-si-specialties-api-openapi.yml
  format: yaml
  label: findadoctor-si Specialties API
  slug: findadoctor-si-specialties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-specialties-api-openapi.yml
- filename: findadoctor-si-terms-api-openapi.yml
  format: yaml
  label: findadoctor-si Terms API
  slug: findadoctor-si-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-terms-api-openapi.yml
- filename: findadoctor-si-waitlist-api-openapi.yml
  format: yaml
  label: findadoctor-si Waitlist API
  slug: findadoctor-si-waitlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-waitlist-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: a short label we use to recognise it (for example the name or email address given when access was requested)
  - category: identifying
    text: We do not ask for, and an agent should not send, a person’s name, date of birth, insurance member ID or anything else that identifies them.
  - category: device
    text: Our server also sees the network address a request comes from, as every web server does.
  - category: behavioral
    text: a search can include a medical condition or procedure, a specialty, a place
  - category: other
    text: Requests that come through ChatGPT may also carry an anonymous user identifier that ChatGPT provides to services for rate limiting
  deletion:
    route: email contact@findadoctor.si
    text: email contact@findadoctor.si and we will delete it, with all its keys and daily totals, within 14 days of confirming the request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer the search request
    text: Search terms are used only to answer that request.
  - purpose: rate limiting and fair sharing
    text: To share the service fairly, the server keeps some information in memory only, never on disk
  - purpose: capacity and pricing planning
    text: are kept for up to 400 days to plan capacity and pricing
  residency:
  - region: United States
    text: The server that answers searches, for every country, is in the United States.
  retention:
  - period: null
    scope: search terms
    text: They are processed in memory and are not written to disk, logged or kept after the answer is sent.
  - period: 14 days
    scope: operational log
    text: It is kept for 14 days.
  - period: 14 days
    scope: web server error log
    text: That log is deleted after 14 days.
  - period: 90 days
    scope: per-account daily totals
    text: keep these for 90 days
  - period: 400 days
    scope: service-wide totals
    text: are kept for up to 400 days to plan capacity and pricing
  - period: null
    scope: accounts
    text: An account is kept until its holder asks us to delete it or we close the service
  rights:
  - right: object (France GDPR)
    text: Doctors in France have rights under the GDPR and the French Data Protection Act (loi n° 78-17), including to object; they can also complain to the CNIL.
  - right: sign out apps / cancel keys
    text: You can also ask us to sign out all your apps or cancel a key at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent any information, and we do not use requests to train AI models.
  subprocessors:
    text: 'Two providers run the service for us: Cloudflare serves these pages and carries requests to our server, and processes network addresses to deliver and protect the service under its own privacy policy; Alibaba Cloud hosts our server in the United States.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: findadoctor-si
provenance_date: '2026-11-09'
provider_name: findadoctor-si
provider_slug: findadoctor-si
slug: findadoctor-si-privacy-policy
source_date: '2026-11-09'
source_filename: findadoctor-si-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://findadoctor.si/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: findadoctor-si\naid: findadoctor-si\nurl: https://findadoctor.si/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: a short label we use to recognise it (for example the name or email address given when access was requested)\n- category: identifying\n  text: We do not ask for, and an agent should not send, a person’s name, date of birth, insurance member ID or\n    anything else that identifies them.\n- category: device\n  text: Our server also sees the network address a request comes from, as every web server does.\n- category: behavioral\n\
  \  text: a search can include a medical condition or procedure, a specialty, a place\n- category: other\n  text: Requests that come through ChatGPT may also carry an anonymous user identifier that ChatGPT provides to\n    services for rate limiting\npurposes:\n- purpose: answer the search request\n  text: Search terms are used only to answer that request.\n- purpose: rate limiting and fair sharing\n  text: To share the service fairly, the server keeps some information in memory only, never on disk\n- purpose: capacity and pricing planning\n  text: are kept for up to 400 days to plan capacity and pricing\nretention:\n- scope: search terms\n  period: null\n  text: They are processed in memory and are not written to disk, logged or kept after the answer is sent.\n- scope: operational log\n  period: 14 days\n  text: It is kept for 14 days.\n- scope: web server error log\n  period: 14 days\n  text: That log is deleted after 14 days.\n- scope: per-account daily totals\n  period: 90 days\n  text:\
  \ keep these for 90 days\n- scope: service-wide totals\n  period: 400 days\n  text: are kept for up to 400 days to plan capacity and pricing\n- scope: accounts\n  period: null\n  text: An account is kept until its holder asks us to delete it or we close the service\nresidency:\n- region: United States\n  text: The server that answers searches, for every country, is in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Two providers run the service for us: Cloudflare serves these pages and carries requests to our server,\n    and processes network addresses to deliver and protect the service under its own privacy policy; Alibaba Cloud\n    hosts our server in the United States.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email contact@findadoctor.si\n  text: email contact@findadoctor.si and we will delete it, with all its keys and daily totals, within 14 days of\n    confirming the request\nrights:\n- right: object (France GDPR)\n  text:\
  \ Doctors in France have rights under the GDPR and the French Data Protection Act (loi n° 78-17), including\n    to object; they can also complain to the CNIL.\n- right: sign out apps / cancel keys\n  text: You can also ask us to sign out all your apps or cancel a key at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent any information, and we do not use requests to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/findadoctor-si/privacy/findadoctor-si-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from findadoctor-si's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Data
- Artificial Intelligence
- Doctor
- International
---
