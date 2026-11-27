---
api_specs:
- filename: transcriptdock-com-app-api-openapi.yml
  format: yaml
  label: transcriptdock-com App API
  slug: transcriptdock-com-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-app-api-openapi.yml
- filename: transcriptdock-com-batches-api-openapi.yml
  format: yaml
  label: transcriptdock-com Batches API
  slug: transcriptdock-com-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-batches-api-openapi.yml
- filename: transcriptdock-com-capabilities-api-openapi.yml
  format: yaml
  label: transcriptdock-com Capabilities API
  slug: transcriptdock-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-capabilities-api-openapi.yml
- filename: transcriptdock-com-jobs-api-openapi.yml
  format: yaml
  label: transcriptdock-com Jobs API
  slug: transcriptdock-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-jobs-api-openapi.yml
- filename: transcriptdock-com-language-discoveries-api-openapi.yml
  format: yaml
  label: transcriptdock-com Language Discoveries API
  slug: transcriptdock-com-language-discoveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-language-discoveries-api-openapi.yml
- filename: transcriptdock-com-llms-api-openapi.yml
  format: yaml
  label: transcriptdock-com Llms API
  slug: transcriptdock-com-llms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-llms-api-openapi.yml
- filename: transcriptdock-com-llms-full-api-openapi.yml
  format: yaml
  label: transcriptdock-com Llms Full API
  slug: transcriptdock-com-llms-full-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-llms-full-api-openapi.yml
- filename: transcriptdock-com-transcripts-api-openapi.yml
  format: yaml
  label: transcriptdock-com Transcripts API
  slug: transcriptdock-com-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-transcripts-api-openapi.yml
- filename: transcriptdock-com-uploads-api-openapi.yml
  format: yaml
  label: transcriptdock-com Uploads API
  slug: transcriptdock-com-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-uploads-api-openapi.yml
- filename: transcriptdock-com-usage-api-openapi.yml
  format: yaml
  label: transcriptdock-com Usage API
  slug: transcriptdock-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-usage-api-openapi.yml
- filename: transcriptdock-com-video-discoveries-api-openapi.yml
  format: yaml
  label: transcriptdock-com Video Discoveries API
  slug: transcriptdock-com-video-discoveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-video-discoveries-api-openapi.yml
- filename: transcriptdock-com-webhook-endpoints-api-openapi.yml
  format: yaml
  label: transcriptdock-com Webhook Endpoints API
  slug: transcriptdock-com-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-webhook-endpoints-api-openapi.yml
- filename: transcriptdock-com-webhooks-api-openapi.yml
  format: yaml
  label: transcriptdock-com Webhooks API
  slug: transcriptdock-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptdock-com/openapi/transcriptdock-com-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data : email address, password hash (held by Supabase Auth), and the workspace settings you choose.'
  - category: contact
    text: email address
  - category: financial
    text: Stripe holds your card or other payment details; we receive your Stripe customer id, plan, billing period and payment status, never full card numbers.
  - category: device
    text: IP address and user agent for rate limiting and abuse prevention, and error logs.
  - category: behavioral
    text: 'Answers you choose to give : the optional welcome questions (how you heard about us, what you use Transcript Dock for, which platforms and which parts of the product)'
  - category: communication
    text: 'Content you submit : video URLs, uploaded audio, and the transcripts we produce from them.'
  deletion:
    route: dashboard, API, or account settings
    text: You can export or delete your transcripts from the dashboard or the API at any time and delete your whole account from settings
  dpa:
    available: true
    text: A data processing agreement under Article 28 of the GDPR is available on request at transcriptdock@volods.com .
    url: null
  purposes:
  - purpose: run the Service
    text: To run the Service you asked for, to bill you, to keep the Service secure and within its limits, to answer support requests, and to send account emails such as verification, receipts and material changes to terms.
  residency:
  - region: United States
    text: Several of the providers above process data in the United States (the database runs in AWS us-east-1).
  retention:
  - period: 30 or 90 days on paid plans
    scope: transcripts and uploads
    text: Transcripts and uploads are kept for your plan's retention period (7 days on trial, 30 or 90 days on paid plans) unless you delete them sooner.
  - period: null
    scope: account and billing records
    text: Account and billing records are kept while your account exists and for as long as tax law requires afterwards.
  - period: 30 days
    scope: logs
    text: Logs are kept for 30 days.
  rights:
  - right: access
    text: to access your personal data
  - right: correction
    text: to correct it
  - right: erasure
    text: to have it erased
  - right: restriction or objection
    text: to restrict or object to how we use it
  - right: portability
    text: to receive it in a portable format
  - right: withdraw consent
    text: to withdraw consent where we rely on it
  role:
    text: VOLODS LTD, trading as Transcript Dock (the data controller) collects when you use Transcript Dock
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not use your content to train models.
  subprocessors:
    text: Supabase (authentication and database, AWS us-east-1) Vercel (web hosting and API) Oracle Cloud (transcript worker) Google Cloud (uploads storage) Cloudflare (DNS) AssemblyAI (AI transcription of audio from links and uploads; audio is deleted from our storage after processing) Stripe (payments, invoices and receipts) RevenueCat (App Store and Google Play subscriptions bought in the mobile app) Resend (transactional email)
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers rely on the providers' data processing terms, which include the European Commission's Standard Contractual Clauses and the UK International Data Transfer Addendum
  - mechanism: DPF
    text: or on the EU US Data Privacy Framework and its UK Extension where a provider is certified.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: transcriptdock-com
provenance_date: '2026-11-10'
provider_name: transcriptdock-com
provider_slug: transcriptdock-com
slug: transcriptdock-com-privacy-policy
source_date: '2026-11-10'
source_filename: transcriptdock-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.transcriptdock.com/docs/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: transcriptdock-com\naid: transcriptdock-com\nurl: https://www.transcriptdock.com/docs/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: VOLODS LTD, trading as Transcript Dock (the data controller) collects when you use Transcript Dock\ndata_categories:\n- category: identifying\n  text: 'Account data : email address, password hash (held by Supabase Auth), and the workspace settings you choose.'\n- category: contact\n  text: email address\n- category: financial\n  text: Stripe holds your card or other payment details; we receive your Stripe customer id, plan, billing period\n    and payment status,\
  \ never full card numbers.\n- category: device\n  text: IP address and user agent for rate limiting and abuse prevention, and error logs.\n- category: behavioral\n  text: 'Answers you choose to give : the optional welcome questions (how you heard about us, what you use Transcript\n    Dock for, which platforms and which parts of the product)'\n- category: communication\n  text: 'Content you submit : video URLs, uploaded audio, and the transcripts we produce from them.'\npurposes:\n- purpose: run the Service\n  text: To run the Service you asked for, to bill you, to keep the Service secure and within its limits, to answer\n    support requests, and to send account emails such as verification, receipts and material changes to terms.\nretention:\n- scope: transcripts and uploads\n  period: 30 or 90 days on paid plans\n  text: Transcripts and uploads are kept for your plan's retention period (7 days on trial, 30 or 90 days on paid\n    plans) unless you delete them sooner.\n- scope: account\
  \ and billing records\n  period: null\n  text: Account and billing records are kept while your account exists and for as long as tax law requires afterwards.\n- scope: logs\n  period: 30 days\n  text: Logs are kept for 30 days.\nresidency:\n- region: United States\n  text: Several of the providers above process data in the United States (the database runs in AWS us-east-1).\ntransfers:\n- mechanism: SCC\n  text: These transfers rely on the providers' data processing terms, which include the European Commission's Standard\n    Contractual Clauses and the UK International Data Transfer Addendum\n- mechanism: DPF\n  text: or on the EU US Data Privacy Framework and its UK Extension where a provider is certified.\nsubprocessors:\n  url: null\n  text: Supabase (authentication and database, AWS us-east-1) Vercel (web hosting and API) Oracle Cloud (transcript\n    worker) Google Cloud (uploads storage) Cloudflare (DNS) AssemblyAI (AI transcription of audio from links and\n    uploads; audio is\
  \ deleted from our storage after processing) Stripe (payments, invoices and receipts) RevenueCat\n    (App Store and Google Play subscriptions bought in the mobile app) Resend (transactional email)\ndpa:\n  available: true\n  url: null\n  text: A data processing agreement under Article 28 of the GDPR is available on request at transcriptdock@volods.com\n    .\ndeletion:\n  route: dashboard, API, or account settings\n  text: You can export or delete your transcripts from the dashboard or the API at any time and delete your whole\n    account from settings\nrights:\n- right: access\n  text: to access your personal data\n- right: correction\n  text: to correct it\n- right: erasure\n  text: to have it erased\n- right: restriction or objection\n  text: to restrict or object to how we use it\n- right: portability\n  text: to receive it in a portable format\n- right: withdraw consent\n  text: to withdraw consent where we rely on it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell\
  \ personal data and do not use your content to train models.\n"
source_yaml_url: https://artifacts.apis.io/transcriptdock-com/privacy/transcriptdock-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from transcriptdock-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Transcript
- YouTube
- TikTok
---
