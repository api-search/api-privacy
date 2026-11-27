---
api_specs:
- filename: fastino-labs-anthropic-compat-api-openapi.yml
  format: yaml
  label: Fastino Labs Anthropic Compat API
  slug: fastino-labs-anthropic-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-anthropic-compat-api-openapi.yml
- filename: fastino-labs-inference-api-openapi.yml
  format: yaml
  label: Fastino Labs Inference API
  slug: fastino-labs-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-inference-api-openapi.yml
- filename: fastino-labs-inference-history-api-openapi.yml
  format: yaml
  label: Fastino Labs Inference History API
  slug: fastino-labs-inference-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-inference-history-api-openapi.yml
- filename: fastino-labs-openai-compat-api-openapi.yml
  format: yaml
  label: Fastino Labs Openai Compat API
  slug: fastino-labs-openai-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastino-labs/openapi/fastino-labs-openai-compat-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email address, company name, and authentication credentials when you sign up or join the waitlist.
  - category: behavioral
    text: Information about how you interact with our platform, including pages visited, features used, and actions taken.
  - category: device
    text: Browser type, operating system, IP address, device information, and cookies.
  - category: other
    text: Datasets, models, and other content you upload or create on the platform.
  deletion:
    route: Delete Account option in account settings, or email support@fastino.ai
    text: You can delete your account and associated data at any time using the Delete Account option in your account settings, or by contacting us at support@fastino.ai.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve the platform
    text: Provide, maintain, and improve the Fastino platform.
  - purpose: Account and waitlist management
    text: Process and manage your account registration and waitlist status.
  - purpose: Communications
    text: Communicate with you about updates, features, and support.
  - purpose: Security and fraud prevention
    text: Ensure security and prevent fraud or abuse.
  retention:
  - period: null
    scope: Account information
    text: Account information is retained while your account is active and for a limited period afterward as needed for legal, tax, and security purposes.
  - period: null
    scope: Inference data
    text: Inference data (the prompts you send and the completions you receive) is retained in your history to provide the service and is deleted when you delete your account.
  - period: null
    scope: Uploaded datasets and models
    text: Uploaded datasets and models are retained while your account is active or until you delete them, whichever comes first.
  - period: null
    scope: Technical and usage logs
    text: Technical and usage logs are retained for a limited period for security, abuse prevention, and billing, then deleted or aggregated.
  - period: null
    scope: GLiNER-2 async job result
    text: A result you never fetch is deleted 24 hours after the job finishes.
  rights:
  - right: Access, correct, or delete
    text: Access, correct, or delete your personal data.
  - right: Object to or restrict processing
    text: Object to or restrict processing of your data.
  - right: Data portability
    text: Data portability.
  - right: Withdraw consent
    text: Withdraw consent at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not share it with third parties for their own advertising or marketing.
  subprocessors:
    text: A current list of our subprocessors is available at docs.fastino.ai/trust-safety.
    url: docs.fastino.ai/trust-safety
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fastino Labs
provenance_date: '2026-11-09'
provider_name: Fastino Labs
provider_slug: fastino-labs
slug: fastino-labs-privacy-policy
source_date: '2026-11-09'
source_filename: fastino-labs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agent.fastino.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fastino Labs\naid: fastino-labs\nurl: https://agent.fastino.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, email address, company name, and authentication credentials when you sign up or join the waitlist.\n- category: behavioral\n  text: Information about how you interact with our platform, including pages visited, features used, and actions\n    taken.\n- category: device\n  text: Browser type, operating system, IP address, device information, and cookies.\n- category: other\n  text: Datasets, models, and other content you\
  \ upload or create on the platform.\npurposes:\n- purpose: Provide, maintain, and improve the platform\n  text: Provide, maintain, and improve the Fastino platform.\n- purpose: Account and waitlist management\n  text: Process and manage your account registration and waitlist status.\n- purpose: Communications\n  text: Communicate with you about updates, features, and support.\n- purpose: Security and fraud prevention\n  text: Ensure security and prevent fraud or abuse.\nretention:\n- scope: Account information\n  period: null\n  text: Account information is retained while your account is active and for a limited period afterward as needed\n    for legal, tax, and security purposes.\n- scope: Inference data\n  period: null\n  text: Inference data (the prompts you send and the completions you receive) is retained in your history to provide\n    the service and is deleted when you delete your account.\n- scope: Uploaded datasets and models\n  period: null\n  text: Uploaded datasets and models\
  \ are retained while your account is active or until you delete them, whichever\n    comes first.\n- scope: Technical and usage logs\n  period: null\n  text: Technical and usage logs are retained for a limited period for security, abuse prevention, and billing,\n    then deleted or aggregated.\n- scope: GLiNER-2 async job result\n  period: null\n  text: A result you never fetch is deleted 24 hours after the job finishes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: docs.fastino.ai/trust-safety\n  text: A current list of our subprocessors is available at docs.fastino.ai/trust-safety.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete Account option in account settings, or email support@fastino.ai\n  text: You can delete your account and associated data at any time using the Delete Account option in your account\n    settings, or by contacting us at support@fastino.ai.\nrights:\n- right: Access, correct, or delete\n  text: Access, correct, or delete\
  \ your personal data.\n- right: Object to or restrict processing\n  text: Object to or restrict processing of your data.\n- right: Data portability\n  text: Data portability.\n- right: Withdraw consent\n  text: Withdraw consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not share it with third parties for their own advertising\n    or marketing.\n"
source_yaml_url: https://artifacts.apis.io/fastino-labs/privacy/fastino-labs-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Fastino Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Small Language Models
- Fine-Tuning
- Inference
- Named Entity Recognition
- Information Extraction
- LLM
- Agents
- PII Detection
- Model Training
- Foundation Models
---
