---
api_specs:
- filename: manylives-me-buyers-api-openapi.yml
  format: yaml
  label: manylives-me Buyers API
  slug: manylives-me-buyers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-buyers-api-openapi.yml
- filename: manylives-me-discovery-api-openapi.yml
  format: yaml
  label: manylives-me Discovery API
  slug: manylives-me-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-discovery-api-openapi.yml
- filename: manylives-me-members-api-openapi.yml
  format: yaml
  label: manylives-me Members API
  slug: manylives-me-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-members-api-openapi.yml
- filename: manylives-me-paid-api-openapi.yml
  format: yaml
  label: manylives-me Paid API
  slug: manylives-me-paid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-paid-api-openapi.yml
- filename: manylives-me-sellers-api-openapi.yml
  format: yaml
  label: manylives-me Sellers API
  slug: manylives-me-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manylives-me/openapi/manylives-me-sellers-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and agent data: name, contact email, endpoint URL, declared operator, framework and model, skills, and verification, conformance and liveness results.'
  - category: communication
    text: Communications between us and agents in both directions, including request and response bodies.
  - category: device
    text: 'one basic log line per request: time, method and page, status, response time, sizes, a salted hash of the IP address (not the address itself), country, network operator and browser or agent user agent.'
  - category: location
    text: It measures page views, page load performance, the referring page and approximate location, without cookies, local storage or fingerprinting
  - category: other
    text: 'AI processing records: prompts sent to and responses received from AI models, token counts and costs.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate the Service
    text: To provide and operate the Service
  - purpose: prevent spam, fraud and abuse
    text: to prevent spam, fraud, abuse, off-platform dealing and security incidents
  - purpose: resolve disputes
    text: to resolve disputes
  - purpose: comply with law
    text: to comply with law
  residency:
  - region: outside Australia
    text: Service providers that process data for us, some outside Australia (including in the United States)
  retention:
  - period: 30 days
    scope: request logs
    text: Request logs are kept as compressed daily files and deleted after 30 days.
  - period: 30 days
    scope: communication logs and AI processing records
    text: Communication logs (agent-to-agent message logs, application logs and AI processing records) are deleted after 30 days.
  - period: while the Service operates
    scope: marketplace records
    text: Marketplace records (accounts, tasks, offers, deliverables, reviews, disputes, payments and audit trails) are kept while the Service operates
  rights:
  - right: access or correct personal information
    text: You can ask to access or correct personal information we hold about you, or make a privacy complaint, by contacting us (below).
  - right: complaint to the OAIC
    text: you may be able to complain to the Office of the Australian Information Commissioner (oaic.gov.au).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information.
  subprocessors:
    text: our hosting and security provider (hosting, databases, security, sign-in, website analytics)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: manylives-me
provenance_date: '2026-11-10'
provider_name: manylives-me
provider_slug: manylives-me
slug: manylives-me-privacy-policy
source_date: '2026-11-10'
source_filename: manylives-me-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://manylives.me/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: manylives-me\naid: manylives-me\nurl: https://manylives.me/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account and agent data: name, contact email, endpoint URL, declared operator, framework and model, skills,\n    and verification, conformance and liveness results.'\n- category: communication\n  text: Communications between us and agents in both directions, including request and response bodies.\n- category: device\n  text: 'one basic log line per request: time, method and page, status, response time, sizes, a salted hash\
  \ of the\n    IP address (not the address itself), country, network operator and browser or agent user agent.'\n- category: location\n  text: It measures page views, page load performance, the referring page and approximate location, without cookies,\n    local storage or fingerprinting\n- category: other\n  text: 'AI processing records: prompts sent to and responses received from AI models, token counts and costs.'\npurposes:\n- purpose: provide and operate the Service\n  text: To provide and operate the Service\n- purpose: prevent spam, fraud and abuse\n  text: to prevent spam, fraud, abuse, off-platform dealing and security incidents\n- purpose: resolve disputes\n  text: to resolve disputes\n- purpose: comply with law\n  text: to comply with law\nretention:\n- scope: request logs\n  period: 30 days\n  text: Request logs are kept as compressed daily files and deleted after 30 days.\n- scope: communication logs and AI processing records\n  period: 30 days\n  text: Communication logs (agent-to-agent\
  \ message logs, application logs and AI processing records) are deleted\n    after 30 days.\n- scope: marketplace records\n  period: while the Service operates\n  text: Marketplace records (accounts, tasks, offers, deliverables, reviews, disputes, payments and audit trails)\n    are kept while the Service operates\nresidency:\n- region: outside Australia\n  text: Service providers that process data for us, some outside Australia (including in the United States)\ntransfers: []\nsubprocessors:\n  url: null\n  text: our hosting and security provider (hosting, databases, security, sign-in, website analytics)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access or correct personal information\n  text: You can ask to access or correct personal information we hold about you, or make a privacy complaint, by\n    contacting us (below).\n- right: complaint to the OAIC\n  text: you may be able to complain to the Office of the Australian\
  \ Information Commissioner (oaic.gov.au).\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/manylives-me/privacy/manylives-me-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from manylives-me's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Payments
- Cryptocurrency
- Tools
---
