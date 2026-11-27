---
api_specs:
- filename: isgenai-checks-api-openapi.yml
  format: yaml
  label: isGenAI Checks API
  slug: isgenai-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isgenai/openapi/isgenai-checks-api-openapi.yml
- filename: isgenai-content-credentials-api-openapi.yml
  format: yaml
  label: isGenAI Content Credentials API
  slug: isgenai-content-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isgenai/openapi/isgenai-content-credentials-api-openapi.yml
- filename: isgenai-health-api-openapi.yml
  format: yaml
  label: isGenAI Health API
  slug: isgenai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isgenai/openapi/isgenai-health-api-openapi.yml
- filename: isgenai-mcp-api-openapi.yml
  format: yaml
  label: isGenAI MCP API
  slug: isgenai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isgenai/openapi/isgenai-mcp-api-openapi.yml
- filename: isgenai-prompts-api-openapi.yml
  format: yaml
  label: isGenAI Prompts API
  slug: isgenai-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isgenai/openapi/isgenai-prompts-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store your login email, a salted password hash, a hashed recovery code and essential session cookies.
  - category: financial
    text: we store Stripe customer and subscription identifiers, payment event identifiers and usage records. We never store full card numbers.
  - category: behavioral
    text: we also keep our own first-party record of the pages you view, how long each stays visible and which features and plan offers you use
  - category: device
    text: Google’s analytics tag loads only after you accept. It uses first-party cookies to distinguish visits and may process browser, device and network information, including an IP address during transmission.
  - category: communication
    text: Feedback on results When you send feedback, we save your selected answers, the check ID, result category and content type, plus a task description only if you choose to add one.
  deletion:
    route: Contact us to request account deletion
    text: Contact us to request account deletion; required billing records may be retained separately.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run, secure and support the service
    text: so we can run, secure and support the service
  - purpose: improve the service
    text: We use it to see where people get stuck and to improve the service.
  - purpose: prioritize improvements
    text: Feedback helps us understand tasks and prioritize improvements.
  retention:
  - period: 180 days
    scope: sign-in and check records
    text: These records never include your files, text, links or prompts, and are kept for 180 days.
  - period: 30 days
    scope: feedback reports
    text: We keep reports in a private review queue and remove reports older than 30 days during cleanup.
  - period: up to ten minutes
    scope: in-memory prompt results
    text: Results may be held in server memory for up to ten minutes to avoid repeat calls.
  - period: 180 days
    scope: analytics choice
    text: Your accept or reject choice is stored in your browser for 180 days.
  rights:
  - right: withdraw analytics consent
    text: Rejecting removes the visitor ID and stops this record.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: isGenAI
provenance_date: '2026-11-09'
provider_name: isGenAI
provider_slug: isgenai
slug: isgenai-privacy-policy
source_date: '2026-11-09'
source_filename: isgenai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://isgenai.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: isGenAI\naid: isgenai\nurl: https://isgenai.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store your login email, a salted password hash, a hashed recovery code and essential session cookies.\n- category: financial\n  text: we store Stripe customer and subscription identifiers, payment event identifiers and usage records. We never\n    store full card numbers.\n- category: behavioral\n  text: we also keep our own first-party record of the pages you view, how long each stays visible and which features\n    and plan offers\
  \ you use\n- category: device\n  text: Google’s analytics tag loads only after you accept. It uses first-party cookies to distinguish visits and\n    may process browser, device and network information, including an IP address during transmission.\n- category: communication\n  text: Feedback on results When you send feedback, we save your selected answers, the check ID, result category\n    and content type, plus a task description only if you choose to add one.\npurposes:\n- purpose: run, secure and support the service\n  text: so we can run, secure and support the service\n- purpose: improve the service\n  text: We use it to see where people get stuck and to improve the service.\n- purpose: prioritize improvements\n  text: Feedback helps us understand tasks and prioritize improvements.\nretention:\n- scope: sign-in and check records\n  period: 180 days\n  text: These records never include your files, text, links or prompts, and are kept for 180 days.\n- scope: feedback reports\n  period:\
  \ 30 days\n  text: We keep reports in a private review queue and remove reports older than 30 days during cleanup.\n- scope: in-memory prompt results\n  period: up to ten minutes\n  text: Results may be held in server memory for up to ten minutes to avoid repeat calls.\n- scope: analytics choice\n  period: 180 days\n  text: Your accept or reject choice is stored in your browser for 180 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us to request account deletion\n  text: Contact us to request account deletion; required billing records may be retained separately.\nrights:\n- right: withdraw analytics consent\n  text: Rejecting removes the visitor ID and stops this record.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/isgenai/privacy/isgenai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from isGenAI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Detector
- Image
- Text
- Code
- Free
- Privacy
---
