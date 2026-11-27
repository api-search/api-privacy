---
api_specs:
- filename: caleralabs-com-openapi-generated.yml
  format: yaml
  label: Calera Labs API
  slug: caleralabs-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caleralabs-com/openapi/_ae-authored/caleralabs-com-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, organization membership, and authentication tokens managed via Firebase Authentication and enterprise Single Sign-On (SSO).
  - category: other
    text: Text queries, natural-language prompts, documents, financial filing identifiers, and document streams submitted to our APIs or indexed into Infinite Context memory spaces.
  - category: device
    text: Aggregated, anonymized service metrics (HTTP status codes, latency percentiles, error rates, request counts) necessary to maintain uptime, prevent denial-of-service, and enforce subscription rate limits.
  - category: financial
    text: 'Stripe: Payment card processing and recurring subscription billing.'
  deletion:
    route: Universal Dashboard, ICX REST API, or email to support@caleralabs.com
    text: You may delete or flush individual memory spaces or full document collections at any time via the ICX REST API ( DELETE /v1/memory/spaces/{space_id} ) or the Universal Dashboard.
  dpa:
    available: null
    text: For questions, compliance reviews, or Data Processing Agreements (DPAs), contact our privacy team at support@caleralabs.com .
    url: null
  purposes:
  - purpose: Telemetry analytics
    text: Toggling opt-out persists calera_ignore_telemetry locally and suppresses analytics pings.
  - purpose: Training restriction
    text: Calera Labs does not use customer queries, ingested documents, memory spaces, custom ontologies, or API payloads to train public foundation models
  retention:
  - period: 90 days
    scope: Operational logs
    text: Transient operational logs used for infrastructure debugging and DDoS mitigation are automatically purged within 90 days.
  - period: null
    scope: Audit logs
    text: Subscribers can configure their audit log retention window (from 14 days up to enterprise-grade indefinite retention)
  - period: null
    scope: Account records
    text: Basic billing and transactional history are retained for the duration of your account plus standard statutory periods required for financial accounting and tax compliance.
  rights:
  - right: Access and portability
    text: You may export your complete account profile, preferences, and usage records directly from your account settings.
  - right: Rectification and erasure
    text: You may update your profile data or execute a permanent account deletion request with 1 click in the Universal Dashboard or by emailing support@caleralabs.com .
  - right: Non-discrimination
    text: We do not discriminate against any user for exercising their statutory privacy rights.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Google Cloud Platform (GCP): Container hosting (Cloud Run), secure document storage, Cloud KMS encryption, and Firestore metadata storage. Firebase: Authentication, session verification, and static asset distribution. Stripe: Payment card processing and recurring subscription billing.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Calera Labs
provenance_date: '2026-11-09'
provider_name: Calera Labs
provider_slug: caleralabs-com
slug: caleralabs-com-privacy-policy
source_date: '2026-11-09'
source_filename: caleralabs-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://caleralabs.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Calera Labs\naid: caleralabs-com\nurl: https://caleralabs.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, organization membership, and authentication tokens managed via Firebase Authentication\n    and enterprise Single Sign-On (SSO).\n- category: other\n  text: Text queries, natural-language prompts, documents, financial filing identifiers, and document streams submitted\n    to our APIs or indexed into Infinite Context memory spaces.\n- category: device\n  text: Aggregated, anonymized service metrics (HTTP\
  \ status codes, latency percentiles, error rates, request counts)\n    necessary to maintain uptime, prevent denial-of-service, and enforce subscription rate limits.\n- category: financial\n  text: 'Stripe: Payment card processing and recurring subscription billing.'\npurposes:\n- purpose: Telemetry analytics\n  text: Toggling opt-out persists calera_ignore_telemetry locally and suppresses analytics pings.\n- purpose: Training restriction\n  text: Calera Labs does not use customer queries, ingested documents, memory spaces, custom ontologies, or API\n    payloads to train public foundation models\nretention:\n- scope: Operational logs\n  period: 90 days\n  text: Transient operational logs used for infrastructure debugging and DDoS mitigation are automatically purged\n    within 90 days.\n- scope: Audit logs\n  period: null\n  text: Subscribers can configure their audit log retention window (from 14 days up to enterprise-grade indefinite\n    retention)\n- scope: Account records\n  period:\
  \ null\n  text: Basic billing and transactional history are retained for the duration of your account plus standard statutory\n    periods required for financial accounting and tax compliance.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Google Cloud Platform (GCP): Container hosting (Cloud Run), secure document storage, Cloud KMS encryption,\n    and Firestore metadata storage. Firebase: Authentication, session verification, and static asset distribution.\n    Stripe: Payment card processing and recurring subscription billing.'\ndpa:\n  available: null\n  url: null\n  text: For questions, compliance reviews, or Data Processing Agreements (DPAs), contact our privacy team at support@caleralabs.com\n    .\ndeletion:\n  route: Universal Dashboard, ICX REST API, or email to support@caleralabs.com\n  text: You may delete or flush individual memory spaces or full document collections at any time via the ICX REST\n    API ( DELETE /v1/memory/spaces/{space_id} ) or the\
  \ Universal Dashboard.\nrights:\n- right: Access and portability\n  text: You may export your complete account profile, preferences, and usage records directly from your account\n    settings.\n- right: Rectification and erasure\n  text: You may update your profile data or execute a permanent account deletion request with 1 click in the Universal\n    Dashboard or by emailing support@caleralabs.com .\n- right: Non-discrimination\n  text: We do not discriminate against any user for exercising their statutory privacy rights.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caleralabs-com/privacy/caleralabs-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
summary_line: 15 quoted statements, read from Calera Labs's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- LLM
- Infrastructure
- FinanceSec
- PatentSec
- ICX
- Company
---
