---
api_specs:
- filename: gaipagents-com-agent-observatory-api-openapi.yml
  format: yaml
  label: gaipagents-com Agent Observatory API
  slug: gaipagents-com-agent-observatory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-agent-observatory-api-openapi.yml
- filename: gaipagents-com-delivery-assurance-api-openapi.yml
  format: yaml
  label: gaipagents-com Delivery Assurance API
  slug: gaipagents-com-delivery-assurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-delivery-assurance-api-openapi.yml
- filename: gaipagents-com-discovery-api-openapi.yml
  format: yaml
  label: gaipagents-com Discovery API
  slug: gaipagents-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-discovery-api-openapi.yml
- filename: gaipagents-com-evidence-ledger-api-openapi.yml
  format: yaml
  label: gaipagents-com Evidence Ledger API
  slug: gaipagents-com-evidence-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-evidence-ledger-api-openapi.yml
- filename: gaipagents-com-platform-api-openapi.yml
  format: yaml
  label: gaipagents-com Platform API
  slug: gaipagents-com-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-platform-api-openapi.yml
- filename: gaipagents-com-supplier-reliability-api-openapi.yml
  format: yaml
  label: gaipagents-com Supplier Reliability API
  slug: gaipagents-com-supplier-reliability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-supplier-reliability-api-openapi.yml
- filename: gaipagents-com-the-record-api-openapi.yml
  format: yaml
  label: gaipagents-com The record API
  slug: gaipagents-com-the-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gaipagents-com/openapi/gaipagents-com-the-record-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: A shop's name, web address and any contact details it publishes can identify a person, for example where the shop is run by a sole trader, so GAIP treats them as personal data.
  - category: device
    text: The User-Agent header is reduced to a coarse category (for example "directory or monitor"); the header itself is not kept.
  - category: contact
    text: GAIP has no accounts and asks for public or non-personal data only.
  deletion:
    route: corrections and opt-out
    text: A shop owner can opt out of observation, ask for its stored history to be deleted, or correct a record through corrections and opt-out
  dpa:
    available: true
    text: GAIP signed Railway's Data Processing Agreement on 7 October 2026 (Railway's agreement binds only once signed).
    url: https://railway.com/legal/dpa
  purposes:
  - purpose: rate limiting
    text: To apply the public rate limits, GAIP turns your request's source address into a salted one-way hash combined with the date (UTC)
  - purpose: measuring use and keeping bot traffic out of figures
    text: 'Lawful basis: legitimate interests (measuring whether GAIP is used and keeping bot traffic out of its figures).'
  - purpose: keeping verifiable receipts and improving the service
    text: To provide the free checks you request, keep the service secure and within fair-use limits, keep verifiable receipts and improve the service.
  residency:
  - region: Vercel functions
    text: GAIP's functions run in Vercel's Washington, D.C., USA region (iad1)
  - region: Railway
    text: GAIP's service runs in Railway's EU West region, Amsterdam, the Netherlands.
  - region: Neon database
    text: GAIP's database is in Neon's AWS Europe (London) region (aws-eu-west-2).
  retention:
  - period: 6 years
    scope: Receipts (inputs and submitted content)
    text: what you supplied inside a receipt (inputs, terms, evidence, addresses, identifiers and any text) is kept for 6 years from the receipt date
  - period: null
    scope: Network address for rate limiting
    text: The address itself is not stored.
  - period: 1,095 days
    scope: Free shop check rows
    text: the check results and the evidence behind them (hashes and excerpts of at most 300 characters, never page copies), for 1,095 days.
  - period: 730 days
    scope: Correction and opt-out requests
    text: The content of a correction, right-of-reply or opt-out request is kept for 730 days so the correction stays linked to what it corrects.
  rights:
  - right: access, rectification, erasure, restriction, objection, portability
    text: You may ask for access, rectification, erasure, restriction, objection or portability where UK GDPR gives you those rights.
  - right: complain to GAIP
    text: You can complain to GAIP about how it uses personal data through the same route; GAIP acknowledges a data protection complaint within 30 days and tells you the outcome
  - right: complain to regulator
    text: You can also complain to the regulator, the Information Commission (formerly the Information Commissioner, still known as the ICO; ico.org.uk).
  role:
    text: The controller is Toby Graham, a sole trader trading as GAIP.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: GAIP does not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 'Safeguard: for transfers from the UK, the UK International Data Transfer Agreement, which Vercel''s addendum treats as entered into'
  - mechanism: DPF
    text: 'Safeguard: for transfers from the UK, the UK Extension to the EU-U.S. Data Privacy Framework (the UK-US data bridge) or the EU Standard Contractual Clauses with the UK Addendum, both named in Railway''s agreement'
  - mechanism: SCC
    text: 'Safeguard: for any transfer from the UK, the EU Standard Contractual Clauses with the UK Addendum, as that addendum sets out'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: gaipagents-com
provenance_date: '2026-11-09'
provider_name: gaipagents-com
provider_slug: gaipagents-com
slug: gaipagents-com-privacy-policy
source_date: '2026-11-09'
source_filename: gaipagents-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gaipagents.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: gaipagents-com\naid: gaipagents-com\nurl: https://gaipagents.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is Toby Graham, a sole trader trading as GAIP.\ndata_categories:\n- category: identifying\n  text: A shop's name, web address and any contact details it publishes can identify a person, for example where\n    the shop is run by a sole trader, so GAIP treats them as personal data.\n- category: device\n  text: The User-Agent header is reduced to a coarse category (for example \"directory or monitor\"); the header itself\n    is not kept.\n- category: contact\n\
  \  text: GAIP has no accounts and asks for public or non-personal data only.\npurposes:\n- purpose: rate limiting\n  text: To apply the public rate limits, GAIP turns your request's source address into a salted one-way hash combined\n    with the date (UTC)\n- purpose: measuring use and keeping bot traffic out of figures\n  text: 'Lawful basis: legitimate interests (measuring whether GAIP is used and keeping bot traffic out of its figures).'\n- purpose: keeping verifiable receipts and improving the service\n  text: To provide the free checks you request, keep the service secure and within fair-use limits, keep verifiable\n    receipts and improve the service.\nretention:\n- scope: Receipts (inputs and submitted content)\n  period: 6 years\n  text: what you supplied inside a receipt (inputs, terms, evidence, addresses, identifiers and any text) is kept\n    for 6 years from the receipt date\n- scope: Network address for rate limiting\n  period: null\n  text: The address itself is not stored.\n\
  - scope: Free shop check rows\n  period: 1,095 days\n  text: the check results and the evidence behind them (hashes and excerpts of at most 300 characters, never page\n    copies), for 1,095 days.\n- scope: Correction and opt-out requests\n  period: 730 days\n  text: The content of a correction, right-of-reply or opt-out request is kept for 730 days so the correction stays\n    linked to what it corrects.\nresidency:\n- region: Vercel functions\n  text: GAIP's functions run in Vercel's Washington, D.C., USA region (iad1)\n- region: Railway\n  text: GAIP's service runs in Railway's EU West region, Amsterdam, the Netherlands.\n- region: Neon database\n  text: GAIP's database is in Neon's AWS Europe (London) region (aws-eu-west-2).\ntransfers:\n- mechanism: other\n  text: 'Safeguard: for transfers from the UK, the UK International Data Transfer Agreement, which Vercel''s addendum\n    treats as entered into'\n- mechanism: DPF\n  text: 'Safeguard: for transfers from the UK, the UK Extension\
  \ to the EU-U.S. Data Privacy Framework (the UK-US\n    data bridge) or the EU Standard Contractual Clauses with the UK Addendum, both named in Railway''s agreement'\n- mechanism: SCC\n  text: 'Safeguard: for any transfer from the UK, the EU Standard Contractual Clauses with the UK Addendum, as that\n    addendum sets out'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://railway.com/legal/dpa\n  text: GAIP signed Railway's Data Processing Agreement on 7 October 2026 (Railway's agreement binds only once signed).\ndeletion:\n  route: corrections and opt-out\n  text: A shop owner can opt out of observation, ask for its stored history to be deleted, or correct a record through\n    corrections and opt-out\nrights:\n- right: access, rectification, erasure, restriction, objection, portability\n  text: You may ask for access, rectification, erasure, restriction, objection or portability where UK GDPR gives\n    you those rights.\n- right: complain to GAIP\n\
  \  text: You can complain to GAIP about how it uses personal data through the same route; GAIP acknowledges a data\n    protection complaint within 30 days and tells you the outcome\n- right: complain to regulator\n  text: You can also complain to the regulator, the Information Commission (formerly the Information Commissioner,\n    still known as the ICO; ico.org.uk).\nsale_or_sharing:\n  stance: prohibited\n  text: GAIP does not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/gaipagents-com/privacy/gaipagents-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from gaipagents-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- MCP
- A2A
- OpenAPI
---
