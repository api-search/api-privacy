---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register with Google or GitHub, we receive your name, email address, profile image URL, and the identifier of that account from the provider.
  - category: contact
    text: Organization name, the names and emails of teammates you invite
  - category: financial
    text: Payment records. Amount, currency, credits granted, the payment provider's transaction reference, status, and timestamps.
  - category: behavioral
    text: records pages viewed and coarse interaction events
  - category: device
    text: It sets first-party cookies in your browser to identify a session and a returning visitor
  - category: location
    text: It does collect your IP address, which is used to derive country and is not sold.
  - category: communication
    text: anything you write to support
  - category: other
    text: your organization ID, the model and task type, the request parameters and prompt text, any media you upload, the generated result
  deletion:
    route: Email support@hotapi.ai; no self-service account deletion
    text: There is no self-service account deletion. Closing an account goes through support.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate account and authenticate requests
    text: To operate your account and authenticate requests
  - purpose: Meter usage and bill accurately
    text: to meter usage and bill accurately
  - purpose: Detect abuse, fraud, and compromised keys
    text: to detect abuse, fraud, and compromised keys
  - purpose: Analytics
    text: We use analytics to understand which pages and models get attention, which informs what we build.
  residency:
  - region: Germany
    text: Our primary database is in Frankfurt, Germany .
  - region: Singapore, United States, mainland China
    text: Upstream providers process requests in their own regions, which for some video models means Singapore and for others means the United States or mainland China.
  retention:
  - period: 7 days
    scope: Task records
    text: Held for 7 days from creation; after that, result assets are deleted and URLs are cleared.
  - period: 24 hours
    scope: Uploaded input images
    text: Uploaded input images 24 hours, then deleted by a storage lifecycle rule
  - period: 7 days
    scope: Generated output assets
    text: Generated output assets 7 days, then deleted
  - period: null
    scope: Payment transactions
    text: Retained for the statutory accounting period applicable to our entity (generally several years)
  rights:
  - right: Access and correction in dashboard
    text: You can access and correct most of your data directly in the dashboard
  - right: Export usage data
    text: You can export your usage data through the API.
  - right: Deletion, portability, objection, appeal (GDPR/CCPA)
    text: access, correction, deletion, portability, restriction, objecting to processing, or appealing a refusal, including GDPR rights if you are in the EU/UK and CCPA/CPRA rights if you are in California
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share it for cross-context behavioural advertising.
  subprocessors:
    text: Providers we route to include PIAPI, Mulerouter, OrcaRouter, and Volcano Engine/BytePlus ModelArk (Singapore region for video models)
    url: null
  transfers:
  - mechanism: other
    text: That means data can cross borders as part of doing the generation you asked for.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: hotapi-ai
provenance_date: '2026-11-09'
provider_name: hotapi-ai
provider_slug: hotapi-ai
slug: hotapi-ai-privacy-policy
source_date: '2026-11-09'
source_filename: hotapi-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hotapi.ai/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: hotapi-ai\naid: hotapi-ai\nurl: https://hotapi.ai/en/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you register with Google or GitHub, we receive your name, email address, profile image URL, and the\n    identifier of that account from the provider.\n- category: contact\n  text: Organization name, the names and emails of teammates you invite\n- category: financial\n  text: Payment records. Amount, currency, credits granted, the payment provider's transaction reference, status,\n    and timestamps.\n- category: behavioral\n\
  \  text: records pages viewed and coarse interaction events\n- category: device\n  text: It sets first-party cookies in your browser to identify a session and a returning visitor\n- category: location\n  text: It does collect your IP address, which is used to derive country and is not sold.\n- category: communication\n  text: anything you write to support\n- category: other\n  text: your organization ID, the model and task type, the request parameters and prompt text, any media you upload,\n    the generated result\npurposes:\n- purpose: Operate account and authenticate requests\n  text: To operate your account and authenticate requests\n- purpose: Meter usage and bill accurately\n  text: to meter usage and bill accurately\n- purpose: Detect abuse, fraud, and compromised keys\n  text: to detect abuse, fraud, and compromised keys\n- purpose: Analytics\n  text: We use analytics to understand which pages and models get attention, which informs what we build.\nretention:\n- scope: Task records\n\
  \  period: 7 days\n  text: Held for 7 days from creation; after that, result assets are deleted and URLs are cleared.\n- scope: Uploaded input images\n  period: 24 hours\n  text: Uploaded input images 24 hours, then deleted by a storage lifecycle rule\n- scope: Generated output assets\n  period: 7 days\n  text: Generated output assets 7 days, then deleted\n- scope: Payment transactions\n  period: null\n  text: Retained for the statutory accounting period applicable to our entity (generally several years)\nresidency:\n- region: Germany\n  text: Our primary database is in Frankfurt, Germany .\n- region: Singapore, United States, mainland China\n  text: Upstream providers process requests in their own regions, which for some video models means Singapore and\n    for others means the United States or mainland China.\ntransfers:\n- mechanism: other\n  text: That means data can cross borders as part of doing the generation you asked for.\nsubprocessors:\n  url: null\n  text: Providers we route\
  \ to include PIAPI, Mulerouter, OrcaRouter, and Volcano Engine/BytePlus ModelArk (Singapore\n    region for video models)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@hotapi.ai; no self-service account deletion\n  text: There is no self-service account deletion. Closing an account goes through support.\nrights:\n- right: Access and correction in dashboard\n  text: You can access and correct most of your data directly in the dashboard\n- right: Export usage data\n  text: You can export your usage data through the API.\n- right: Deletion, portability, objection, appeal (GDPR/CCPA)\n  text: access, correction, deletion, portability, restriction, objecting to processing, or appealing a refusal,\n    including GDPR rights if you are in the EU/UK and CCPA/CPRA rights if you are in California\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/hotapi-ai/privacy/hotapi-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from hotapi-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- NSFW
- Chat
- Image Generation
- Video Generation
- Voice Generation
---
