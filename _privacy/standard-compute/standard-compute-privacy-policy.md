---
api_specs:
- filename: standard-compute-completions-api-openapi.yml
  format: yaml
  label: Standard Compute Completions API
  slug: standard-compute-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-completions-api-openapi.yml
- filename: standard-compute-healthz-api-openapi.yml
  format: yaml
  label: Standard Compute Healthz API
  slug: standard-compute-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-healthz-api-openapi.yml
- filename: standard-compute-install-ps1-api-openapi.yml
  format: yaml
  label: Standard Compute Install.ps1 API
  slug: standard-compute-install-ps1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-install-ps1-api-openapi.yml
- filename: standard-compute-install-sh-api-openapi.yml
  format: yaml
  label: Standard Compute Install.sh API
  slug: standard-compute-install-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-install-sh-api-openapi.yml
- filename: standard-compute-messages-api-openapi.yml
  format: yaml
  label: Standard Compute Messages API
  slug: standard-compute-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-messages-api-openapi.yml
- filename: standard-compute-models-api-openapi.yml
  format: yaml
  label: Standard Compute Models API
  slug: standard-compute-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-models-api-openapi.yml
- filename: standard-compute-responses-api-openapi.yml
  format: yaml
  label: Standard Compute Responses API
  slug: standard-compute-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-responses-api-openapi.yml
- filename: standard-compute-chat-completions-api-openapi.yml
  format: yaml
  label: Standard Compute Chat Completions API
  slug: standard-compute-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-chat-completions-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: when you sign up we collect your email address and create a secure account
  - category: identifying
    text: 'API keys: when you generate an API key we store an encrypted version of the key, a cryptographic hash for validation, the key prefix and last four characters for display, and timestamps for creation and last use.'
  - category: behavioral
    text: 'Usage data: we record basic usage metadata such as when your API key was last used.'
  - category: device
    text: 'Session data: we use cookies to maintain your login session.'
  - category: financial
    text: Stripe receives your email address and payment method details.
  deletion:
    route: Dashboard account deletion
    text: 'You can delete your account and all associated data at any time from the Dashboard. This action is immediate and irreversible: all API keys are invalidated and all usage data is removed.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: 'Provide and operate the service: authenticate your requests, route them to the appropriate model, and enforce plan limits.'
  - purpose: Improve reliability
    text: 'Improve reliability: monitor aggregate usage patterns to maintain uptime and performance.'
  - purpose: Transactional communication
    text: 'Communicate with you: send transactional emails related to your account, billing, or service changes.'
  residency:
  - region: EU
    text: Your account data and stored records are held in the EU (AWS eu-central-1 via Supabase).
  - region: Inference providers
    text: Inference requests are forwarded to third-party model providers that may process data in various jurisdictions.
  rights:
  - right: access
    text: You have the right to access your data, rectify inaccuracies, request erasure, restrict processing, and receive your data in a portable format.
  - right: response time
    text: We respond to data subject requests within 30 days.
  role:
    text: Standard Compute processes personal data as a data controller under the General Data Protection Regulation (GDPR).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your personal information with third parties for their marketing purposes.
  subprocessors:
    text: We use Supabase for authentication and data storage.
    url: null
  transfers:
  - mechanism: other
    text: we do not represent that prompt content sent to a given provider remains within the EEA or is subject to EEA-equivalent legal safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Standard Compute
provenance_date: '2026-11-10'
provider_name: Standard Compute
provider_slug: standard-compute
slug: standard-compute-privacy-policy
source_date: '2026-11-10'
source_filename: standard-compute-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://standardcompute.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Standard Compute\naid: standard-compute\nurl: https://standardcompute.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Standard Compute processes personal data as a data controller under the General Data Protection Regulation\n    (GDPR).\ndata_categories:\n- category: contact\n  text: when you sign up we collect your email address and create a secure account\n- category: identifying\n  text: 'API keys: when you generate an API key we store an encrypted version of the key, a cryptographic hash for\n    validation, the key prefix and last four characters for display, and timestamps\
  \ for creation and last use.'\n- category: behavioral\n  text: 'Usage data: we record basic usage metadata such as when your API key was last used.'\n- category: device\n  text: 'Session data: we use cookies to maintain your login session.'\n- category: financial\n  text: Stripe receives your email address and payment method details.\npurposes:\n- purpose: Provide and operate the service\n  text: 'Provide and operate the service: authenticate your requests, route them to the appropriate model, and enforce\n    plan limits.'\n- purpose: Improve reliability\n  text: 'Improve reliability: monitor aggregate usage patterns to maintain uptime and performance.'\n- purpose: Transactional communication\n  text: 'Communicate with you: send transactional emails related to your account, billing, or service changes.'\nretention: []\nresidency:\n- region: EU\n  text: Your account data and stored records are held in the EU (AWS eu-central-1 via Supabase).\n- region: Inference providers\n  text: Inference\
  \ requests are forwarded to third-party model providers that may process data in various jurisdictions.\ntransfers:\n- mechanism: other\n  text: we do not represent that prompt content sent to a given provider remains within the EEA or is subject to\n    EEA-equivalent legal safeguards.\nsubprocessors:\n  url: null\n  text: We use Supabase for authentication and data storage.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard account deletion\n  text: 'You can delete your account and all associated data at any time from the Dashboard. This action is immediate\n    and irreversible: all API keys are invalidated and all usage data is removed.'\nrights:\n- right: access\n  text: You have the right to access your data, rectify inaccuracies, request erasure, restrict processing, and\n    receive your data in a portable format.\n- right: response time\n  text: We respond to data subject requests within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text:\
  \ We do not sell, rent, or share your personal information with third parties for their marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/standard-compute/privacy/standard-compute-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Standard Compute's own page on 2026-11-10.
synthetic: false
tags:
- LLM API
- Flat-rate
- Subscription
- AI Agents
- Inference
- Model Routing
- AI Gateway
- Developer Tools
- Coding Agents
- OpenAI-Compatible
---
