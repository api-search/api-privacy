---
api_specs:
- filename: flatin-pt-public-api-openapi.yml
  format: yaml
  label: flatin.pt Public API
  slug: flatin-pt-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flatin-pt/openapi/flatin-pt-public-api-openapi.yml
- filename: flatin-pt-actions-api-openapi.yml
  format: yaml
  label: flatin.pt Actions API
  slug: flatin-pt-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flatin-pt/openapi/flatin-pt-actions-api-openapi.yml
- filename: flatin-pt-places-api-openapi.yml
  format: yaml
  label: flatin.pt Places API
  slug: flatin-pt-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flatin-pt/openapi/flatin-pt-places-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: Name and contact — what you entered in the form.
  - category: other
    text: 'What you are looking for: type of home, area, budget, timing.'
  - category: device
    text: 'Technical data about the request: IP address, time, page, browser.'
  - category: communication
    text: your email or your Telegram chat number
  deletion:
    route: deletion at end of retention period
    text: Once the period is over, the data is deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Handling requests
    text: take the request, work out what you are looking for, choose who on the team follows it and know which site or link brought it
  - purpose: Saved-search alerts
    text: email those who subscribed and confirmed their address
  - purpose: Technical logs and abuse protection
    text: keeping the site working, investigating incidents, rate limiting
  residency:
  - region: EU
    text: the data stays in the EU
  retention:
  - period: null
    scope: Requests
    text: A request stays 3 years after it is closed
  - period: 7 days
    scope: Unconfirmed alert subscriptions
    text: unconfirmed subscription — 7 days
  rights:
  - right: access, rectification, erasure, restriction, portability, objection, withdraw consent
    text: You have the rights of access, rectification, erasure, restriction, portability and objection, and you can withdraw consent at any time.
  - right: complaint to supervisory authority
    text: 'you may complain to the supervisory authority: CNPD (Portugal)'
  role:
    text: The controller is HOLY CHAOS, UNIPESSOAL LDA (NIF 519403908, Porto, Portugal), a real-estate mediation company holding AMI licence no. 28163.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data and do not share it for third-party advertising.
  subprocessors:
    text: Besides the team, only the suppliers in this table handle the data, for technical reasons, each for the purpose shown
    url: null
  transfers:
  - mechanism: SCC
    text: Cloudflare, Inc. protecting the site and delivering pages US yes EU standard contractual clauses
  - mechanism: other
    text: there is no processing agreement; that is why the message carries neither your name nor your contact, only the request number
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: flatin.pt
provenance_date: '2026-11-09'
provider_name: flatin.pt
provider_slug: flatin-pt
slug: flatin-pt-privacy-policy
source_date: '2026-11-09'
source_filename: flatin-pt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flatin.pt/en/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: flatin.pt\naid: flatin-pt\nurl: https://flatin.pt/en/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is HOLY CHAOS, UNIPESSOAL LDA (NIF 519403908, Porto, Portugal), a real-estate mediation company\n    holding AMI licence no. 28163.\ndata_categories:\n- category: contact\n  text: Name and contact — what you entered in the form.\n- category: other\n  text: 'What you are looking for: type of home, area, budget, timing.'\n- category: device\n  text: 'Technical data about the request: IP address, time, page, browser.'\n- category: communication\n  text: your email\
  \ or your Telegram chat number\npurposes:\n- purpose: Handling requests\n  text: take the request, work out what you are looking for, choose who on the team follows it and know which site\n    or link brought it\n- purpose: Saved-search alerts\n  text: email those who subscribed and confirmed their address\n- purpose: Technical logs and abuse protection\n  text: keeping the site working, investigating incidents, rate limiting\nretention:\n- scope: Requests\n  period: null\n  text: A request stays 3 years after it is closed\n- scope: Unconfirmed alert subscriptions\n  period: 7 days\n  text: unconfirmed subscription — 7 days\nresidency:\n- region: EU\n  text: the data stays in the EU\ntransfers:\n- mechanism: SCC\n  text: Cloudflare, Inc. protecting the site and delivering pages US yes EU standard contractual clauses\n- mechanism: other\n  text: there is no processing agreement; that is why the message carries neither your name nor your contact, only\n    the request number\nsubprocessors:\n\
  \  url: null\n  text: Besides the team, only the suppliers in this table handle the data, for technical reasons, each for the\n    purpose shown\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: deletion at end of retention period\n  text: Once the period is over, the data is deleted.\nrights:\n- right: access, rectification, erasure, restriction, portability, objection, withdraw consent\n  text: You have the rights of access, rectification, erasure, restriction, portability and objection, and you can\n    withdraw consent at any time.\n- right: complaint to supervisory authority\n  text: 'you may complain to the supervisory authority: CNPD (Portugal)'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data and do not share it for third-party advertising.\n"
source_yaml_url: https://artifacts.apis.io/flatin-pt/privacy/flatin-pt-privacy-policy.yml
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
summary_line: 18 quoted statements, read from flatin.pt's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Property Tax
- Tax
- IMI
- IMT
- Stamp Duty
- Portugal
- Open Data
- Government Data
- Fiscal Data
- MCP
- AI Agents
---
