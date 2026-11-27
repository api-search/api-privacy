---
api_specs:
- filename: vigil-wtf-vigil-proxy-api-openapi.yml
  format: yaml
  label: Vigil Proxy
  slug: vigil-wtf-vigil-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigil-wtf/openapi/vigil-wtf-vigil-proxy-api-openapi.yml
- filename: vigil-wtf-feedback-api-openapi.yml
  format: yaml
  label: Vigil Feedback API
  slug: vigil-wtf-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigil-wtf/openapi/vigil-wtf-feedback-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: A Vigil user id (a UUID we generate)
  - category: contact
    text: Email address, and whether it is verified
  - category: financial
    text: Your Stripe customer and subscription ids.
  - category: device
    text: The IP address and browser of each signed-in session
  - category: behavioral
    text: Tells us which marketing actually works.
  - category: communication
    text: The email address you enter when asking to be told about a feature that is not built yet
  - category: other
    text: Latency in milliseconds
  deletion:
    route: Settings → Delete account
    text: It is immediate and irreversible
  dpa:
    available: true
    text: the Article 28 terms for the processor half are in the Data Processing Addendum
    url: null
  purposes:
  - purpose: account creation and authentication
    text: Create and authenticate your account
  - purpose: payment and billing
    text: Take payment and keep billing records
  - purpose: abuse investigation and service protection
    text: Independent investigation of abuse and protection of our service
  - purpose: support
    text: Reply to your support email
  - purpose: marketing attribution
    text: Count a sign-up or a new paid plan in Plausible, with its campaign tags
  residency:
  - region: EU
    text: Our database and authentication run in the EU
  - region: Global edge network
    text: The proxy runs on Cloudflare's edge network, which means your request is processed at whichever location is nearest to the machine making the call.
  retention:
  - period: indefinitely
    scope: call telemetry
    text: today we keep call telemetry indefinitely, on every plan including Free.
  - period: null
    scope: refused-request ledger
    text: it runs daily and deletes refused-request records once they are seven days old.
  - period: 7 years
    scope: billing and accounting records
    text: keep our books, invoices and payment records for 7 years
  rights:
  - right: access
    text: your call and error history is visible in the dashboard and exportable as CSV from Settings
  - right: erasure
    text: Settings → Delete account
  - right: rectification
    text: your settings are editable in the product
  - right: portability
    text: the CSV exports in Settings are machine-readable and yours to take anywhere
  - right: objection
    text: Where we rely on legitimate interests you can object
  - right: withdraw consent
    text: you can withdraw either on its own from Cookie settings in the footer of any public page
  - right: complain to supervisory authority
    text: you can complain to the authority where you habitually live or work
  role:
    text: For the telemetry produced by the AI traffic you route through the proxy, Evolmet B.V. is a processor acting on your instructions, and you are the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: your account, your prompts and your call records are never shared with an advertising network
  subprocessors:
    text: The subprocessor page shows the same list with each company's legal entity
    url: null
  transfers:
  - mechanism: DPF
    text: are listed in the EU-U.S. Data Privacy Framework
  - mechanism: SCC
    text: also carry the Commission's Standard Contractual Clauses (2021/914) in their terms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vigil
provenance_date: '2026-11-10'
provider_name: Vigil
provider_slug: vigil-wtf
slug: vigil-wtf-privacy-policy
source_date: '2026-11-10'
source_filename: vigil-wtf-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.vigil.tools/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vigil\naid: vigil-wtf\nurl: https://www.vigil.tools/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: For the telemetry produced by the AI traffic you route through the proxy, Evolmet B.V. is a processor acting\n    on your instructions, and you are the controller.\ndata_categories:\n- category: identifying\n  text: A Vigil user id (a UUID we generate)\n- category: contact\n  text: Email address, and whether it is verified\n- category: financial\n  text: Your Stripe customer and subscription ids.\n- category: device\n  text: The IP address and browser of each signed-in session\n\
  - category: behavioral\n  text: Tells us which marketing actually works.\n- category: communication\n  text: The email address you enter when asking to be told about a feature that is not built yet\n- category: other\n  text: Latency in milliseconds\npurposes:\n- purpose: account creation and authentication\n  text: Create and authenticate your account\n- purpose: payment and billing\n  text: Take payment and keep billing records\n- purpose: abuse investigation and service protection\n  text: Independent investigation of abuse and protection of our service\n- purpose: support\n  text: Reply to your support email\n- purpose: marketing attribution\n  text: Count a sign-up or a new paid plan in Plausible, with its campaign tags\nretention:\n- scope: call telemetry\n  period: indefinitely\n  text: today we keep call telemetry indefinitely, on every plan including Free.\n- scope: refused-request ledger\n  period: null\n  text: it runs daily and deletes refused-request records once they are\
  \ seven days old.\n- scope: billing and accounting records\n  period: 7 years\n  text: keep our books, invoices and payment records for 7 years\nresidency:\n- region: EU\n  text: Our database and authentication run in the EU\n- region: Global edge network\n  text: The proxy runs on Cloudflare's edge network, which means your request is processed at whichever location\n    is nearest to the machine making the call.\ntransfers:\n- mechanism: DPF\n  text: are listed in the EU-U.S. Data Privacy Framework\n- mechanism: SCC\n  text: also carry the Commission's Standard Contractual Clauses (2021/914) in their terms\nsubprocessors:\n  url: null\n  text: The subprocessor page shows the same list with each company's legal entity\ndpa:\n  available: true\n  url: null\n  text: the Article 28 terms for the processor half are in the Data Processing Addendum\ndeletion:\n  route: Settings → Delete account\n  text: It is immediate and irreversible\nrights:\n- right: access\n  text: your call and error\
  \ history is visible in the dashboard and exportable as CSV from Settings\n- right: erasure\n  text: Settings → Delete account\n- right: rectification\n  text: your settings are editable in the product\n- right: portability\n  text: the CSV exports in Settings are machine-readable and yours to take anywhere\n- right: objection\n  text: Where we rely on legitimate interests you can object\n- right: withdraw consent\n  text: you can withdraw either on its own from Cookie settings in the footer of any public page\n- right: complain to supervisory authority\n  text: you can complain to the authority where you habitually live or work\nsale_or_sharing:\n  stance: prohibited\n  text: your account, your prompts and your call records are never shared with an advertising network\n"
source_yaml_url: https://artifacts.apis.io/vigil-wtf/privacy/vigil-wtf-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Vigil's own page on 2026-11-10.
synthetic: false
tags:
- Monitoring
- AI Middleware
- Security
- Analytics
---
