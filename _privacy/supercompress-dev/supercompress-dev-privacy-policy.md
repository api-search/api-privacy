---
api_specs:
- filename: supercompress-dev-openapi-generated.yml
  format: yaml
  label: supercompress-dev API
  slug: supercompress-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supercompress-dev/openapi/_ae-authored/supercompress-dev-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, display name, and authentication identifiers (for example Firebase Auth UID)
  - category: financial
    text: Stripe customer identifiers, subscription/credit status, invoices, and payment event metadata
  - category: location
    text: approximate location derived from IP
  - category: device
    text: IP address, user agent, approximate location derived from IP, request timestamps, and diagnostic logs
  - category: communication
    text: Emails you send us, and transactional product emails we send you
  - category: behavioral
    text: 'Usage metrics: tokens in/out/saved, request counts, timestamps, rate-limit counters'
  - category: other
    text: 'Request content you submit: context, query, and related parameters needed to compress.'
  deletion:
    route: email privacy@supercompress.dev
    text: To exercise rights, email privacy@supercompress.dev
  dpa:
    available: true
    text: If you need a data processing agreement (DPA) for enterprise use of the hosted API, contact us at the same address.
    url: null
  purposes:
  - purpose: provide, operate, secure, and improve the Services
    text: provide, operate, secure, and improve the Services
  - purpose: metering, billing and fraud prevention
    text: meter usage, bill credits, prevent double-billing, and detect fraud/abuse
  - purpose: no model training on customer content
    text: We do not use Customer Content (prompts, context dumps, or compressed outputs) to train or fine-tune the hosted Neural Keep model or any third-party foundation model.
  residency:
  - region: United States
    text: We are based in the United States.
  retention:
  - period: for the life of the account
    scope: Account data
    text: for the life of the account
  - period: on the order of about 48 hours
    scope: Replayable compressed responses
    text: on the order of about 48 hours
  - period: 48 hours
    scope: CCR originals
    text: Those originals are retained for 48 hours
  rights:
  - right: access, correct, or delete
    text: access, correct, or delete personal information
  - right: portability
    text: portability of certain data
  - right: object or restrict
    text: object to or restrict certain processing
  - right: withdraw consent
    text: withdraw consent where processing is consent-based
  - right: appeal or complain
    text: appeal or lodge a complaint with a supervisory authority
  role:
    text: 'the controller (or equivalent) is: Arjun Shah d/b/a SuperCompress'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Vercel (hosting/compute), Google Firebase / Google Cloud (auth, datastore), Fly.io (hosted Neural Keep inference)
    url: null
  transfers:
  - mechanism: SCC
    text: such as Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: supercompress-dev
provenance_date: '2026-11-10'
provider_name: supercompress-dev
provider_slug: supercompress-dev
slug: supercompress-dev-privacy-policy
source_date: '2026-11-10'
source_filename: supercompress-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.supercompress.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: supercompress-dev\naid: supercompress-dev\nurl: https://www.supercompress.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'the controller (or equivalent) is: Arjun Shah d/b/a SuperCompress'\ndata_categories:\n- category: identifying\n  text: Email address, display name, and authentication identifiers (for example Firebase Auth UID)\n- category: financial\n  text: Stripe customer identifiers, subscription/credit status, invoices, and payment event metadata\n- category: location\n  text: approximate location derived from IP\n- category: device\n  text: IP address, user agent, approximate\
  \ location derived from IP, request timestamps, and diagnostic logs\n- category: communication\n  text: Emails you send us, and transactional product emails we send you\n- category: behavioral\n  text: 'Usage metrics: tokens in/out/saved, request counts, timestamps, rate-limit counters'\n- category: other\n  text: 'Request content you submit: context, query, and related parameters needed to compress.'\npurposes:\n- purpose: provide, operate, secure, and improve the Services\n  text: provide, operate, secure, and improve the Services\n- purpose: metering, billing and fraud prevention\n  text: meter usage, bill credits, prevent double-billing, and detect fraud/abuse\n- purpose: no model training on customer content\n  text: We do not use Customer Content (prompts, context dumps, or compressed outputs) to train or fine-tune the\n    hosted Neural Keep model or any third-party foundation model.\nretention:\n- scope: Account data\n  period: for the life of the account\n  text: for the life\
  \ of the account\n- scope: Replayable compressed responses\n  period: on the order of about 48 hours\n  text: on the order of about 48 hours\n- scope: CCR originals\n  period: 48 hours\n  text: Those originals are retained for 48 hours\nresidency:\n- region: United States\n  text: We are based in the United States.\ntransfers:\n- mechanism: SCC\n  text: such as Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: Vercel (hosting/compute), Google Firebase / Google Cloud (auth, datastore), Fly.io (hosted Neural Keep inference)\ndpa:\n  available: true\n  url: null\n  text: If you need a data processing agreement (DPA) for enterprise use of the hosted API, contact us at the same\n    address.\ndeletion:\n  route: email privacy@supercompress.dev\n  text: To exercise rights, email privacy@supercompress.dev\nrights:\n- right: access, correct, or delete\n  text: access, correct, or delete personal information\n- right: portability\n  text: portability of certain data\n- right: object\
  \ or restrict\n  text: object to or restrict certain processing\n- right: withdraw consent\n  text: withdraw consent where processing is consent-based\n- right: appeal or complain\n  text: appeal or lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/supercompress-dev/privacy/supercompress-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from supercompress-dev's own page on 2026-11-10.
synthetic: false
tags:
- LLM
- Compression
- Cost-Reduction
- Artificial Intelligence
- Developer Tools
---
