---
api_specs:
- filename: imgauth-api-di-attestazione-opere-digitali-agent-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Agent API
  slug: imgauth-api-di-attestazione-opere-digitali-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-agent-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-badge-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Badge API
  slug: imgauth-api-di-attestazione-opere-digitali-badge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-badge-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-c-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali C API
  slug: imgauth-api-di-attestazione-opere-digitali-c-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-c-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-cert-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Cert API
  slug: imgauth-api-di-attestazione-opere-digitali-cert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-cert-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-cert-pdf-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Cert Pdf API
  slug: imgauth-api-di-attestazione-opere-digitali-cert-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-cert-pdf-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-hash-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Hash API
  slug: imgauth-api-di-attestazione-opere-digitali-hash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-hash-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-health-log-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Health Log API
  slug: imgauth-api-di-attestazione-opere-digitali-health-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-health-log-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-integrations-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Integrations API
  slug: imgauth-api-di-attestazione-opere-digitali-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-integrations-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-integrazioni-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Integrazioni API
  slug: imgauth-api-di-attestazione-opere-digitali-integrazioni-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-integrazioni-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-ots-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Ots API
  slug: imgauth-api-di-attestazione-opere-digitali-ots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-ots-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-ping-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Ping API
  slug: imgauth-api-di-attestazione-opere-digitali-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-ping-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-status-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Status API
  slug: imgauth-api-di-attestazione-opere-digitali-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-status-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-status-history-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Status History API
  slug: imgauth-api-di-attestazione-opere-digitali-status-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-status-history-api-openapi.yml
- filename: imgauth-api-di-attestazione-opere-digitali-verify-api-openapi.yml
  format: yaml
  label: imgauth — API di attestazione opere digitali Verify API
  slug: imgauth-api-di-attestazione-opere-digitali-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/openapi/imgauth-api-di-attestazione-opere-digitali-verify-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: We process your email address, the chosen provider and the date of the request
  - category: identifying
    text: We process your Telegram user id
  - category: device
    text: The IP address is processed for rate-limiting (abuse prevention) and for the Cloudflare Turnstile anti-bot check when the attestation is issued.
  - category: behavioral
    text: daily usage counters (how many attestations/verifications you have requested)
  - category: financial
    text: subscription references (Stripe identifier, status, expiry date, amount)
  - category: professional
    text: your sector and your region (Professional profiling)
  deletion:
    route: written request to the privacy contact address
    text: To exercise them, write to [email protected]
  dpa:
    available: true
    text: covered by a Data Processing Agreement
    url: null
  purposes:
  - purpose: quotas and abuse prevention
    text: in order to apply quotas and prevent abuse
  - purpose: visit statistics
    text: It collects aggregate statistics only, which are not shared with third parties for commercial purposes.
  - purpose: subscription performance
    text: 'Legal basis: performance of the subscription contract (art. 6.1.b)'
  residency:
  - region: EU
    text: the certificate archive resides on Cloudflare R2 storage in the European Union jurisdiction (data residency in the EU)
  - region: unspecified
    text: stored on Cloudflare D1 (the engine's database), which is separate from the R2 certificate archive and without R2's explicit EU jurisdiction constraint
  retention:
  - period: 180 days
    scope: Developer email
    text: then 180 days from revocation (anti-abuse record)
  - period: 90 days
    scope: Telegram usage counters
    text: usage counters are deleted automatically after 90 days
  - period: 13 months
    scope: Matomo statistics
    text: 'Retention: 13 months.'
  - period: Retained indefinitely unless erasure is requested
    scope: PDF certificate archive
    text: Retained indefinitely unless erasure is requested (see §7).
  - period: at least 5 years
    scope: Subscription references and attestation log
    text: the attestation log and the subscription references are kept for at least 5 years from the production of each certificate
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: You have the right of access, rectification, erasure, restriction, portability, objection to processing based on legitimate interest
  - right: complaint to supervisory authority
    text: You may lodge a complaint with the Garante per la protezione dei dati personali
  role:
    text: Data controller Spazio Genesi ETS
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Data are neither transferred nor sold.
  subprocessors:
    text: Cloudflare, Inc. Engine (Workers), archive (R2 — EU), anti-bot (Turnstile) Fingerprint, certificate, IP address
    url: null
  transfers:
  - mechanism: SCC
    text: Any transfers take place in compliance with GDPR safeguards (standard contractual clauses / adequacy decisions).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: imgauth — API di attestazione opere digitali
provenance_date: '2026-11-09'
provider_name: imgauth — API di attestazione opere digitali
provider_slug: imgauth-api-di-attestazione-opere-digitali
slug: imgauth-api-di-attestazione-opere-digitali-privacy-policy
source_date: '2026-11-09'
source_filename: imgauth-api-di-attestazione-opere-digitali-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://attestazione.spaziogenesi.org/en/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: imgauth — API di attestazione opere digitali\naid: imgauth-api-di-attestazione-opere-digitali\nurl: https://attestazione.spaziogenesi.org/en/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data controller Spazio Genesi ETS\ndata_categories:\n- category: contact\n  text: We process your email address, the chosen provider and the date of the request\n- category: identifying\n  text: We process your Telegram user id\n- category: device\n  text: The IP address is processed for rate-limiting (abuse prevention) and for the Cloudflare Turnstile anti-bot\n    check when the attestation\
  \ is issued.\n- category: behavioral\n  text: daily usage counters (how many attestations/verifications you have requested)\n- category: financial\n  text: subscription references (Stripe identifier, status, expiry date, amount)\n- category: professional\n  text: your sector and your region (Professional profiling)\npurposes:\n- purpose: quotas and abuse prevention\n  text: in order to apply quotas and prevent abuse\n- purpose: visit statistics\n  text: It collects aggregate statistics only, which are not shared with third parties for commercial purposes.\n- purpose: subscription performance\n  text: 'Legal basis: performance of the subscription contract (art. 6.1.b)'\nretention:\n- scope: Developer email\n  period: 180 days\n  text: then 180 days from revocation (anti-abuse record)\n- scope: Telegram usage counters\n  period: 90 days\n  text: usage counters are deleted automatically after 90 days\n- scope: Matomo statistics\n  period: 13 months\n  text: 'Retention: 13 months.'\n- scope:\
  \ PDF certificate archive\n  period: Retained indefinitely unless erasure is requested\n  text: Retained indefinitely unless erasure is requested (see §7).\n- scope: Subscription references and attestation log\n  period: at least 5 years\n  text: the attestation log and the subscription references are kept for at least 5 years from the production of\n    each certificate\nresidency:\n- region: EU\n  text: the certificate archive resides on Cloudflare R2 storage in the European Union jurisdiction (data residency\n    in the EU)\n- region: unspecified\n  text: stored on Cloudflare D1 (the engine's database), which is separate from the R2 certificate archive and without\n    R2's explicit EU jurisdiction constraint\ntransfers:\n- mechanism: SCC\n  text: Any transfers take place in compliance with GDPR safeguards (standard contractual clauses / adequacy decisions).\nsubprocessors:\n  url: null\n  text: Cloudflare, Inc. Engine (Workers), archive (R2 — EU), anti-bot (Turnstile) Fingerprint,\
  \ certificate, IP\n    address\ndpa:\n  available: true\n  url: null\n  text: covered by a Data Processing Agreement\ndeletion:\n  route: written request to the privacy contact address\n  text: To exercise them, write to [email protected]\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: You have the right of access, rectification, erasure, restriction, portability, objection to processing\n    based on legitimate interest\n- right: complaint to supervisory authority\n  text: You may lodge a complaint with the Garante per la protezione dei dati personali\nsale_or_sharing:\n  stance: prohibited\n  text: Data are neither transferred nor sold.\n"
source_yaml_url: https://artifacts.apis.io/imgauth-api-di-attestazione-opere-digitali/privacy/imgauth-api-di-attestazione-opere-digitali-privacy-policy.yml
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
summary_line: 24 quoted statements, read from imgauth — API di attestazione opere digitali's own page on 2026-11-09.
synthetic: false
tags:
- digital notarization
- Timestamping
- proof-of-existence
- Content Authenticity
- Provenance
- Copyright
- IP protection
- Blockchain
- Bitcoin
- OpenTimestamps
- Security
- Documents
- E-Signature
- MCP
---
