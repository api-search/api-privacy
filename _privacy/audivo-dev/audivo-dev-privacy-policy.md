---
api_specs:
- filename: audivo-dev-account-api-openapi.yml
  format: yaml
  label: audivo-dev Account API
  slug: audivo-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-account-api-openapi.yml
- filename: audivo-dev-api-keys-api-openapi.yml
  format: yaml
  label: audivo-dev API Keys API
  slug: audivo-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-api-keys-api-openapi.yml
- filename: audivo-dev-billing-api-openapi.yml
  format: yaml
  label: audivo-dev Billing API
  slug: audivo-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-billing-api-openapi.yml
- filename: audivo-dev-catalog-api-openapi.yml
  format: yaml
  label: audivo-dev Catalog API
  slug: audivo-dev-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-catalog-api-openapi.yml
- filename: audivo-dev-connected-apps-api-openapi.yml
  format: yaml
  label: audivo-dev Connected Apps API
  slug: audivo-dev-connected-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-connected-apps-api-openapi.yml
- filename: audivo-dev-data-api-openapi.yml
  format: yaml
  label: audivo-dev Data API
  slug: audivo-dev-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-data-api-openapi.yml
- filename: audivo-dev-groups-api-openapi.yml
  format: yaml
  label: audivo-dev Groups API
  slug: audivo-dev-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-groups-api-openapi.yml
- filename: audivo-dev-quotes-api-openapi.yml
  format: yaml
  label: audivo-dev Quotes API
  slug: audivo-dev-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-quotes-api-openapi.yml
- filename: audivo-dev-session-api-openapi.yml
  format: yaml
  label: audivo-dev Session API
  slug: audivo-dev-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-session-api-openapi.yml
- filename: audivo-dev-transcripts-api-openapi.yml
  format: yaml
  label: audivo-dev Transcripts API
  slug: audivo-dev-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-transcripts-api-openapi.yml
- filename: audivo-dev-uploads-api-openapi.yml
  format: yaml
  label: audivo-dev Uploads API
  slug: audivo-dev-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audivo-dev/openapi/audivo-dev-uploads-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, sign-in identity, account identifiers, API key records, and account settings.
  - category: financial
    text: Your billing details, subscription, credit balance, purchases, and payment references.
  - category: behavioral
    text: Requests, episode selections, job status, credits charged, timestamps, and diagnostic records.
  - category: device
    text: Our hosting providers may process IP addresses, browser information, and request metadata to deliver and secure the service.
  - category: other
    text: Podcast content. Public feed metadata, audio, publisher transcripts, and generated transcripts.
  - category: communication
    text: Information you provide when contacting us about your account, a payment, a privacy request, or a content concern.
  deletion:
    route: Dashboard export and account deletion; or contact by email for uploaded transcripts
    text: You can export your account data and request account deletion from the dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and secure the service
    text: We use account, billing, and request information to provide the service, authenticate you, process payments, deliver transcripts, and respond to requests.
  - purpose: Legitimate interests
    text: We also process information for our legitimate interests in securing the service, preventing abuse and duplicate free-credit claims, diagnosing failures, and operating a public podcast transcript service
  retention:
  - period: 30 days
    scope: Request logs
    text: 'Request logs: 30 days.'
  - period: one year
    scope: Website analytics cookies
    text: visitor identifier up to one year; session identifier 30 minutes.
  - period: 30 days
    scope: Dashboard session
    text: 'Dashboard session: up to 30 days.'
  - period: within a day
    scope: Podcast audio downloaded to transcribe
    text: 'Podcast audio we download to transcribe: deleted within a day.'
  - period: seven days
    scope: Uploaded audio
    text: 'Audio you upload: deleted after seven days.'
  - period: null
    scope: Account information
    text: 'Account information: while your account is open.'
  rights:
  - right: access
    text: you may have rights to access, correct, erase, or receive a portable copy of your personal information
  - right: restrict processing
    text: restrict processing, object to processing based on legitimate interests, and withdraw consent
  - right: complain to authority
    text: You may also complain to your local data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Vercel for website and dashboard hosting. Amazon Web Services for authentication, processing, storage, and operational logs. Stripe for checkout, subscriptions, and payment processing. DeepInfra for speech-to-text processing of podcast audio. Google for authentication when you choose Google sign-in. DataFast for page analytics on audivo.dev.
    url: null
  transfers:
  - mechanism: other
    text: Our providers may process information outside your country, where data protection laws may differ.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: audivo-dev
provenance_date: '2026-11-09'
provider_name: audivo-dev
provider_slug: audivo-dev
slug: audivo-dev-privacy-policy
source_date: '2026-11-09'
source_filename: audivo-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://audivo.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: audivo-dev\naid: audivo-dev\nurl: https://audivo.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, sign-in identity, account identifiers, API key records, and account settings.\n- category: financial\n  text: Your billing details, subscription, credit balance, purchases, and payment references.\n- category: behavioral\n  text: Requests, episode selections, job status, credits charged, timestamps, and diagnostic records.\n- category: device\n  text: Our hosting providers may process IP addresses, browser information,\
  \ and request metadata to deliver and\n    secure the service.\n- category: other\n  text: Podcast content. Public feed metadata, audio, publisher transcripts, and generated transcripts.\n- category: communication\n  text: Information you provide when contacting us about your account, a payment, a privacy request, or a content\n    concern.\npurposes:\n- purpose: Provide and secure the service\n  text: We use account, billing, and request information to provide the service, authenticate you, process payments,\n    deliver transcripts, and respond to requests.\n- purpose: Legitimate interests\n  text: We also process information for our legitimate interests in securing the service, preventing abuse and duplicate\n    free-credit claims, diagnosing failures, and operating a public podcast transcript service\nretention:\n- scope: Request logs\n  period: 30 days\n  text: 'Request logs: 30 days.'\n- scope: Website analytics cookies\n  period: one year\n  text: visitor identifier up to one year;\
  \ session identifier 30 minutes.\n- scope: Dashboard session\n  period: 30 days\n  text: 'Dashboard session: up to 30 days.'\n- scope: Podcast audio downloaded to transcribe\n  period: within a day\n  text: 'Podcast audio we download to transcribe: deleted within a day.'\n- scope: Uploaded audio\n  period: seven days\n  text: 'Audio you upload: deleted after seven days.'\n- scope: Account information\n  period: null\n  text: 'Account information: while your account is open.'\nresidency: []\ntransfers:\n- mechanism: other\n  text: Our providers may process information outside your country, where data protection laws may differ.\nsubprocessors:\n  url: null\n  text: Vercel for website and dashboard hosting. Amazon Web Services for authentication, processing, storage, and\n    operational logs. Stripe for checkout, subscriptions, and payment processing. DeepInfra for speech-to-text processing\n    of podcast audio. Google for authentication when you choose Google sign-in. DataFast for page\
  \ analytics on audivo.dev.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard export and account deletion; or contact by email for uploaded transcripts\n  text: You can export your account data and request account deletion from the dashboard.\nrights:\n- right: access\n  text: you may have rights to access, correct, erase, or receive a portable copy of your personal information\n- right: restrict processing\n  text: restrict processing, object to processing based on legitimate interests, and withdraw consent\n- right: complain to authority\n  text: You may also complain to your local data protection authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/audivo-dev/privacy/audivo-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 20 quoted statements, read from audivo-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Podcasts
- Transcripts
- Audio
---
