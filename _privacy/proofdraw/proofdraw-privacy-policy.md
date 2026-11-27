---
api_specs:
- filename: proofdraw-account-api-openapi.yml
  format: yaml
  label: ProofDraw Account API
  slug: proofdraw-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-account-api-openapi.yml
- filename: proofdraw-auth-api-openapi.yml
  format: yaml
  label: ProofDraw Auth API
  slug: proofdraw-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-auth-api-openapi.yml
- filename: proofdraw-draws-api-openapi.yml
  format: yaml
  label: ProofDraw Draws API
  slug: proofdraw-draws-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-draws-api-openapi.yml
- filename: proofdraw-system-api-openapi.yml
  format: yaml
  label: ProofDraw System API
  slug: proofdraw-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-system-api-openapi.yml
- filename: proofdraw-verification-api-openapi.yml
  format: yaml
  label: ProofDraw Verification API
  slug: proofdraw-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-verification-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data. When you create an account: email address, hashed password, and any name you choose to associate with the account.'
  - category: contact
    text: Communications. Messages you send to hello@proofdraw.com, press@proofdraw.com, security@proofdraw.com, or other support channels.
  - category: financial
    text: Payments are processed by Stripe; we receive a token plus billing metadata (last four digits, brand, country, address) but never your full card number.
  - category: device
    text: 'Server logs. Like every web service, our servers record requests: IP address, user agent, request method and path, response code, response size, and a timestamp.'
  - category: behavioral
    text: Usage telemetry. Aggregate counts of API calls, draws, and entries per account for billing and rate-limit enforcement.
  - category: other
    text: 'Entry data. When you add entries: each entry''s ticket identifier (operator-supplied or auto-generated) and any free-form entry-level metadata JSON you supply.'
  deletion:
    route: Email hello@proofdraw.com
    text: To exercise a right, email hello@proofdraw.com from the address on your account, or from another address along with information sufficient for us to verify your identity.
  dpa:
    available: null
    text: Hosting + email — we use commercial cloud and transactional-email providers under standard data-processing agreements.
    url: null
  purposes:
  - purpose: Operate the Service
    text: 'Operate the Service: create draws, seal lists, fetch drand values, compute winners, render verification pages, deliver webhooks'
  - purpose: Authenticate and rate-limit
    text: Authenticate and rate-limit API requests
  - purpose: Billing
    text: Bill you for paid plans
  - purpose: Security and abuse prevention
    text: Detect, investigate, and prevent abuse, fraud, security incidents, and violations of our Terms
  - purpose: Legal compliance
    text: Comply with legal obligations and respond to lawful requests from authorities
  - purpose: Aggregated improvement
    text: Improve the Service in an aggregated, de-identified manner (e.g., understanding which endpoints are used most).
  residency:
  - region: United States
    text: We are based in the United States. If you access the Service from outside the United States, your information will be transferred to, stored in, and processed in the United States.
  retention:
  - period: up to 90 days
    scope: Account data
    text: Account data — for the life of your account, plus a reasonable wind-down period after closure (typically up to 90 days)
  - period: indefinitely
    scope: Draw data and private metadata
    text: Draw data & private metadata — indefinitely, because draws are referenced by public verification URLs that are part of the cryptographic record.
  - period: up to 90 days
    scope: Server logs
    text: Server logs — up to 90 days for security and operational purposes.
  - period: seven years
    scope: Payment records
    text: Payment records — as required by applicable tax and accounting law, typically seven years.
  rights:
  - right: Access
    text: Access — request a copy of personal information we hold
  - right: Correction
    text: Correction — ask us to correct inaccurate information
  - right: Deletion
    text: Deletion — request deletion of your personal information, subject to the public-sealed-data limitation in Section 6 and to lawful exceptions
  - right: Portability
    text: Portability — receive a copy of your data in a machine-readable format
  - right: Objection / restriction
    text: Objection / restriction — limit how we process your information for certain purposes
  - right: Withdraw consent
    text: Withdraw consent — where processing is based on consent.
  role:
    text: This Privacy Policy applies to information that LeverageIT, LLC, a Michigan limited liability company doing business as "ProofDraw" ("ProofDraw," "we," "us"), collects through the ProofDraw service
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not "share" it for cross-context behavioral advertising as those terms are defined under the California Consumer Privacy Act.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required by law (e.g., for transfers out of the European Economic Area), we rely on Standard Contractual Clauses or other lawful transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ProofDraw
provenance_date: '2026-11-10'
provider_name: ProofDraw
provider_slug: proofdraw
slug: proofdraw-privacy-policy
source_date: '2026-11-10'
source_filename: proofdraw-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://proofdraw.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ProofDraw\naid: proofdraw\nurl: https://proofdraw.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy applies to information that LeverageIT, LLC, a Michigan limited liability company doing\n    business as \"ProofDraw\" (\"ProofDraw,\" \"we,\" \"us\"), collects through the ProofDraw service\ndata_categories:\n- category: identifying\n  text: 'Account data. When you create an account: email address, hashed password, and any name you choose to associate\n    with the account.'\n- category: contact\n  text: Communications. Messages you send to hello@proofdraw.com,\
  \ press@proofdraw.com, security@proofdraw.com, or\n    other support channels.\n- category: financial\n  text: Payments are processed by Stripe; we receive a token plus billing metadata (last four digits, brand, country,\n    address) but never your full card number.\n- category: device\n  text: 'Server logs. Like every web service, our servers record requests: IP address, user agent, request method\n    and path, response code, response size, and a timestamp.'\n- category: behavioral\n  text: Usage telemetry. Aggregate counts of API calls, draws, and entries per account for billing and rate-limit\n    enforcement.\n- category: other\n  text: 'Entry data. When you add entries: each entry''s ticket identifier (operator-supplied or auto-generated)\n    and any free-form entry-level metadata JSON you supply.'\npurposes:\n- purpose: Operate the Service\n  text: 'Operate the Service: create draws, seal lists, fetch drand values, compute winners, render verification\n    pages, deliver webhooks'\n\
  - purpose: Authenticate and rate-limit\n  text: Authenticate and rate-limit API requests\n- purpose: Billing\n  text: Bill you for paid plans\n- purpose: Security and abuse prevention\n  text: Detect, investigate, and prevent abuse, fraud, security incidents, and violations of our Terms\n- purpose: Legal compliance\n  text: Comply with legal obligations and respond to lawful requests from authorities\n- purpose: Aggregated improvement\n  text: Improve the Service in an aggregated, de-identified manner (e.g., understanding which endpoints are used\n    most).\nretention:\n- scope: Account data\n  period: up to 90 days\n  text: Account data — for the life of your account, plus a reasonable wind-down period after closure (typically\n    up to 90 days)\n- scope: Draw data and private metadata\n  period: indefinitely\n  text: Draw data & private metadata — indefinitely, because draws are referenced by public verification URLs that\n    are part of the cryptographic record.\n- scope: Server\
  \ logs\n  period: up to 90 days\n  text: Server logs — up to 90 days for security and operational purposes.\n- scope: Payment records\n  period: seven years\n  text: Payment records — as required by applicable tax and accounting law, typically seven years.\nresidency:\n- region: United States\n  text: We are based in the United States. If you access the Service from outside the United States, your information\n    will be transferred to, stored in, and processed in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required by law (e.g., for transfers out of the European Economic Area), we rely on Standard Contractual\n    Clauses or other lawful transfer mechanisms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Hosting + email — we use commercial cloud and transactional-email providers under standard data-processing\n    agreements.\ndeletion:\n  route: Email hello@proofdraw.com\n  text: To exercise a right, email hello@proofdraw.com\
  \ from the address on your account, or from another address\n    along with information sufficient for us to verify your identity.\nrights:\n- right: Access\n  text: Access — request a copy of personal information we hold\n- right: Correction\n  text: Correction — ask us to correct inaccurate information\n- right: Deletion\n  text: Deletion — request deletion of your personal information, subject to the public-sealed-data limitation in\n    Section 6 and to lawful exceptions\n- right: Portability\n  text: Portability — receive a copy of your data in a machine-readable format\n- right: Objection / restriction\n  text: Objection / restriction — limit how we process your information for certain purposes\n- right: Withdraw consent\n  text: Withdraw consent — where processing is based on consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not \"share\" it for cross-context behavioral advertising\n    as those terms are defined under\
  \ the California Consumer Privacy Act.\n"
source_yaml_url: https://artifacts.apis.io/proofdraw/privacy/proofdraw-privacy-policy.yml
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
summary_line: 28 quoted statements, read from ProofDraw's own page on 2026-11-10.
synthetic: false
tags:
- Randomness
- Provably Fair
- Drand
- Verifiable Randomness
- Cryptography
- raffle
- Giveaways
- Sweepstakes
- Lottery
- Verification
- Webhook
- REST API
---
