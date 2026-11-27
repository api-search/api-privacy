---
api_specs:
- filename: bithuman-ai-account-api-openapi.yml
  format: yaml
  label: bithuman-ai Account API
  slug: bithuman-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-account-api-openapi.yml
- filename: bithuman-ai-agent-context-api-openapi.yml
  format: yaml
  label: bithuman-ai Agent Context API
  slug: bithuman-ai-agent-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-agent-context-api-openapi.yml
- filename: bithuman-ai-agent-generation-api-openapi.yml
  format: yaml
  label: bithuman-ai Agent Generation API
  slug: bithuman-ai-agent-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-agent-generation-api-openapi.yml
- filename: bithuman-ai-agent-management-api-openapi.yml
  format: yaml
  label: bithuman-ai Agent Management API
  slug: bithuman-ai-agent-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-agent-management-api-openapi.yml
- filename: bithuman-ai-api-secrets-api-openapi.yml
  format: yaml
  label: bithuman-ai API secrets API
  slug: bithuman-ai-api-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-api-secrets-api-openapi.yml
- filename: bithuman-ai-authentication-api-openapi.yml
  format: yaml
  label: bithuman-ai Authentication API
  slug: bithuman-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-authentication-api-openapi.yml
- filename: bithuman-ai-billing-api-openapi.yml
  format: yaml
  label: bithuman-ai Billing API
  slug: bithuman-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-billing-api-openapi.yml
- filename: bithuman-ai-dynamics-api-openapi.yml
  format: yaml
  label: bithuman-ai Dynamics API
  slug: bithuman-ai-dynamics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-dynamics-api-openapi.yml
- filename: bithuman-ai-embedding-api-openapi.yml
  format: yaml
  label: bithuman-ai Embedding API
  slug: bithuman-ai-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-embedding-api-openapi.yml
- filename: bithuman-ai-files-api-openapi.yml
  format: yaml
  label: bithuman-ai Files API
  slug: bithuman-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-files-api-openapi.yml
- filename: bithuman-ai-knowledge-api-openapi.yml
  format: yaml
  label: bithuman-ai Knowledge API
  slug: bithuman-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-knowledge-api-openapi.yml
- filename: bithuman-ai-providers-api-openapi.yml
  format: yaml
  label: bithuman-ai Providers API
  slug: bithuman-ai-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-providers-api-openapi.yml
- filename: bithuman-ai-realtime-api-openapi.yml
  format: yaml
  label: bithuman-ai Realtime API
  slug: bithuman-ai-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-realtime-api-openapi.yml
- filename: bithuman-ai-runtime-sessions-api-openapi.yml
  format: yaml
  label: bithuman-ai Runtime sessions API
  slug: bithuman-ai-runtime-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-runtime-sessions-api-openapi.yml
- filename: bithuman-ai-self-hosting-api-openapi.yml
  format: yaml
  label: bithuman-ai Self Hosting API
  slug: bithuman-ai-self-hosting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-self-hosting-api-openapi.yml
- filename: bithuman-ai-status-api-openapi.yml
  format: yaml
  label: bithuman-ai Status API
  slug: bithuman-ai-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-status-api-openapi.yml
- filename: bithuman-ai-video-api-openapi.yml
  format: yaml
  label: bithuman-ai Video API
  slug: bithuman-ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-video-api-openapi.yml
- filename: bithuman-ai-webhooks-api-openapi.yml
  format: yaml
  label: bithuman-ai Webhooks API
  slug: bithuman-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bithuman-ai/openapi/bithuman-ai-webhooks-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, and password when you create an account'
  - category: financial
    text: 'Payment Information: Billing address and payment details (processed by our payment provider)'
  - category: behavioral
    text: 'Usage Data: Information about how you interact with our Services, including API calls, features used, and time spent'
  - category: device
    text: 'Device Information: Device type, operating system, browser type, and IP address'
  - category: communication
    text: 'Communications: Messages you send to us for support or feedback'
  - category: other
    text: 'Content: Images, videos, audio, and text you upload or create using our Services'
  deletion:
    route: account deletion in the app or at bithuman.ai/account/delete
    text: we delete your sign-in, cancel subscriptions you bought on bithuman.ai
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve our Services
    text: Provide, maintain, and improve our Services
  - purpose: Detect and prevent fraud and abuse
    text: Detect, prevent, and address fraud and abuse
  retention:
  - period: while your account is open
    scope: account data
    text: We keep your information while your account is open.
  - period: 180 days
    scope: reported avatar replies
    text: we clear their content 180 days after we resolve them, or one year after you sent them if they're never resolved.
  - period: 30 days
    scope: sign-up IP address and email domain
    text: which we keep for 30 days to detect automated or abusive sign-ups, then delete the IP address
  rights:
  - right: Access
    text: Access and receive a copy of your personal data
  - right: Correction
    text: Correct inaccurate personal data
  - right: Deletion
    text: Request deletion of your personal data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: 'Service Providers: Third parties that help us operate our Services'
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place for such transfers in accordance with applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: bithuman-ai
provenance_date: '2026-11-09'
provider_name: bithuman-ai
provider_slug: bithuman-ai
slug: bithuman-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bithuman-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bithuman.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: bithuman-ai\naid: bithuman-ai\nurl: https://www.bithuman.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, and password when you create an account'\n- category: financial\n  text: 'Payment Information: Billing address and payment details (processed by our payment provider)'\n- category: behavioral\n  text: 'Usage Data: Information about how you interact with our Services, including API calls, features used, and\n    time spent'\n- category: device\n  text: 'Device Information: Device\
  \ type, operating system, browser type, and IP address'\n- category: communication\n  text: 'Communications: Messages you send to us for support or feedback'\n- category: other\n  text: 'Content: Images, videos, audio, and text you upload or create using our Services'\npurposes:\n- purpose: Provide, maintain, and improve our Services\n  text: Provide, maintain, and improve our Services\n- purpose: Detect and prevent fraud and abuse\n  text: Detect, prevent, and address fraud and abuse\nretention:\n- scope: account data\n  period: while your account is open\n  text: We keep your information while your account is open.\n- scope: reported avatar replies\n  period: 180 days\n  text: we clear their content 180 days after we resolve them, or one year after you sent them if they're never\n    resolved.\n- scope: sign-up IP address and email domain\n  period: 30 days\n  text: which we keep for 30 days to detect automated or abusive sign-ups, then delete the IP address\nresidency: []\ntransfers:\n\
  - mechanism: other\n  text: We ensure appropriate safeguards are in place for such transfers in accordance with applicable law.\nsubprocessors:\n  url: null\n  text: 'Service Providers: Third parties that help us operate our Services'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion in the app or at bithuman.ai/account/delete\n  text: we delete your sign-in, cancel subscriptions you bought on bithuman.ai\nrights:\n- right: Access\n  text: Access and receive a copy of your personal data\n- right: Correction\n  text: Correct inaccurate personal data\n- right: Deletion\n  text: Request deletion of your personal data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/bithuman-ai/privacy/bithuman-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from bithuman-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Avatars
- Real-Time
- Platform
---
