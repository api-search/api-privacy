---
api_specs:
- filename: oruk-ai-affect-api-openapi.yml
  format: yaml
  label: oruk-ai Affect API
  slug: oruk-ai-affect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-affect-api-openapi.yml
- filename: oruk-ai-audio-api-openapi.yml
  format: yaml
  label: oruk-ai Audio API
  slug: oruk-ai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-audio-api-openapi.yml
- filename: oruk-ai-client-token-api-openapi.yml
  format: yaml
  label: oruk-ai Client Token API
  slug: oruk-ai-client-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-client-token-api-openapi.yml
- filename: oruk-ai-livez-api-openapi.yml
  format: yaml
  label: oruk-ai Livez API
  slug: oruk-ai-livez-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-livez-api-openapi.yml
- filename: oruk-ai-models-api-openapi.yml
  format: yaml
  label: oruk-ai Models API
  slug: oruk-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-models-api-openapi.yml
- filename: oruk-ai-orukzero-api-openapi.yml
  format: yaml
  label: oruk-ai Oruk Zero API
  slug: oruk-ai-orukzero-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-orukzero-api-openapi.yml
- filename: oruk-ai-pricing-api-openapi.yml
  format: yaml
  label: oruk-ai Pricing API
  slug: oruk-ai-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-pricing-api-openapi.yml
- filename: oruk-ai-readyz-api-openapi.yml
  format: yaml
  label: oruk-ai Readyz API
  slug: oruk-ai-readyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oruk-ai/openapi/oruk-ai-readyz-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: When you create an account, we collect your name and email address, your authentication details, and any optional company, role, or use-case information you provide.
  - category: financial
    text: Card details, billing addresses, and tax information are collected through secure hosted checkout.
  - category: device
    text: Operational logs may include IP address, browser user agent, request path, timestamp, and status for security and reliability.
  - category: communication
    text: Batch audio testing uses a short-lived, essential cookie to keep temporary uploads private to your browser session.
  deletion:
    route: email access@oruk.ai
    text: You can request access, correction, or deletion of your personal data by emailing access@oruk.ai
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing, abuse prevention, audit, and support
    text: Retained for billing, abuse prevention, audit, and support.
  - purpose: operate accounts and billing
    text: Data is disclosed only as necessary to deliver the selected service, operate accounts and billing, perform measurement you have permitted, protect the service, or comply with law.
  residency:
  - region: North America, Europe, Asia
    text: Spectra-2 processes audio in North America, Europe, or Asia, routing each request by proximity, service health, and available capacity.
  - region: United States
    text: Other standard speech inference remains in the United States.
  retention:
  - period: after processing
    scope: API audio
    text: Oruk’s own inference services discard request audio after processing.
  - period: up to 48 hours
    scope: Optional speaker diarization audio
    text: Optional speaker diarization uses task processors that temporarily retain uploaded audio for up to 48 hours.
  - period: 24 hours
    scope: Resonance 2 result replay records
    text: Replay is available for 24 hours; this is not a physical-deletion deadline.
  - period: 10 minutes
    scope: Demo and playground uploads
    text: Upload handles expire after 10 minutes.
  - period: null
    scope: Account details
    text: Retained while your account is active.
  - period: up to 90 days
    scope: Consented attribution identifiers
    text: Eligible for measurement for up to 90 days after the most recent consented capture; cleared on withdrawal or by scheduled cleanup after expiry.
  rights:
  - right: access
    text: You can request access, correction, or deletion of your personal data by emailing access@oruk.ai
  - right: correction
    text: You can request access, correction, or deletion of your personal data by emailing access@oruk.ai
  - right: deletion
    text: You can request access, correction, or deletion of your personal data by emailing access@oruk.ai
  - right: withdraw cookie consent
    text: Use Cookie preferences in the footer to withdraw consent.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or customer content.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Optional task processing may occur outside the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: oruk-ai
provenance_date: '2026-11-10'
provider_name: Oruk
provider_slug: oruk-ai
slug: oruk-ai-privacy-policy
source_date: '2026-11-10'
source_filename: oruk-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://oruk.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: oruk-ai\naid: oruk-ai\nurl: https://oruk.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you create an account, we collect your name and email address, your authentication details, and any\n    optional company, role, or use-case information you provide.\n- category: financial\n  text: Card details, billing addresses, and tax information are collected through secure hosted checkout.\n- category: device\n  text: Operational logs may include IP address, browser user agent, request path, timestamp, and status for security\n   \
  \ and reliability.\n- category: communication\n  text: Batch audio testing uses a short-lived, essential cookie to keep temporary uploads private to your browser\n    session.\npurposes:\n- purpose: billing, abuse prevention, audit, and support\n  text: Retained for billing, abuse prevention, audit, and support.\n- purpose: operate accounts and billing\n  text: Data is disclosed only as necessary to deliver the selected service, operate accounts and billing, perform\n    measurement you have permitted, protect the service, or comply with law.\nretention:\n- scope: API audio\n  period: after processing\n  text: Oruk’s own inference services discard request audio after processing.\n- scope: Optional speaker diarization audio\n  period: up to 48 hours\n  text: Optional speaker diarization uses task processors that temporarily retain uploaded audio for up to 48 hours.\n- scope: Resonance 2 result replay records\n  period: 24 hours\n  text: Replay is available for 24 hours; this is not a physical-deletion\
  \ deadline.\n- scope: Demo and playground uploads\n  period: 10 minutes\n  text: Upload handles expire after 10 minutes.\n- scope: Account details\n  period: null\n  text: Retained while your account is active.\n- scope: Consented attribution identifiers\n  period: up to 90 days\n  text: Eligible for measurement for up to 90 days after the most recent consented capture; cleared on withdrawal\n    or by scheduled cleanup after expiry.\nresidency:\n- region: North America, Europe, Asia\n  text: Spectra-2 processes audio in North America, Europe, or Asia, routing each request by proximity, service\n    health, and available capacity.\n- region: United States\n  text: Other standard speech inference remains in the United States.\ntransfers:\n- mechanism: other\n  text: Optional task processing may occur outside the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email access@oruk.ai\n  text: You can request\
  \ access, correction, or deletion of your personal data by emailing access@oruk.ai\nrights:\n- right: access\n  text: You can request access, correction, or deletion of your personal data by emailing access@oruk.ai\n- right: correction\n  text: You can request access, correction, or deletion of your personal data by emailing access@oruk.ai\n- right: deletion\n  text: You can request access, correction, or deletion of your personal data by emailing access@oruk.ai\n- right: withdraw cookie consent\n  text: Use Cookie preferences in the footer to withdraw consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or customer content.\n"
source_yaml_url: https://artifacts.apis.io/oruk-ai/privacy/oruk-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from oruk-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Speech
- Artificial Intelligence
- Transcription
- Voice
---
