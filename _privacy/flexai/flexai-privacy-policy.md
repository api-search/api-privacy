---
api_specs:
- filename: flexai-completions-api-openapi.yml
  format: yaml
  label: FlexAI Completions API
  slug: flexai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-completions-api-openapi.yml
- filename: flexai-embeddings-api-openapi.yml
  format: yaml
  label: FlexAI Embeddings API
  slug: flexai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-embeddings-api-openapi.yml
- filename: flexai-models-api-openapi.yml
  format: yaml
  label: FlexAI Models API
  slug: flexai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-models-api-openapi.yml
- filename: flexai-usage-api-openapi.yml
  format: yaml
  label: FlexAI Usage API
  slug: flexai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-usage-api-openapi.yml
- filename: flexai-chat-completions-api-openapi.yml
  format: yaml
  label: FlexAI Chat Completions API
  slug: flexai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-chat-completions-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: including company name, your name, email address, phone number, and payment/billing information such as address and payment method
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Your general location may be derived from your IP address.
  - category: behavioral
    text: information about how and when you use our Services, and other technical information
  deletion:
    route: Email legal@flex.ai to request removal or deletion
    text: To request to review, update, or delete your personal information, please email us at legal@flex.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver and improve Services
    text: We process your End User information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with the law.
  - purpose: Marketing and advertising measurement
    text: We measure which of our ads lead to sign-ups and purchases, as described in Section 1, but we do not use this to make decisions about you.
  residency:
  - region: EU workspaces metadata
    text: For EU workspaces, this metadata is stored within the European Union.
  retention:
  - period: 90 days
    scope: Usage metadata
    text: Usage metadata is deleted from live systems after 90 days and archived for 2 years.
  - period: 13 months
    scope: Client IP addresses
    text: Client IP addresses are retained for 13 months for security and abuse prevention.
  rights:
  - right: Access
    text: Upon request, we will provide you with access to the personal information that we hold about you.
  - right: Correction
    text: You may also correct, amend, or delete the personal information we hold about you.
  - right: Erasure
    text: (ii) to request rectification or erasure;
  - right: Restrict processing
    text: (iii) to restrict the processing of your personal information;
  - right: Data portability
    text: (iv) if applicable, to data portability;
  - right: Withdraw consent
    text: You have the right to withdraw your consent for our processing of your information at any time.
  - right: Opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: With respect to your Client Data (workloads, etc.) as defined in our Terms, we are a Data Processor acting on your behalf.
    value: both
  sale_or_sharing:
    stance: conditional
    text: 'We have shared the following categories of personal information to third parties in the preceding twelve (12) months: Inferences drawn from collected personal information Identifiers (online identifiers and hashed email addresses), shared with advertising networks'
  subprocessors:
    text: A list of our subprocessors will be made available on demand.
    url: null
  transfers:
  - mechanism: other
    text: BY SIGNING UP FOR AND USING OUR SERVICES, YOU UNDERSTAND AND CONSENT TO TRANSFER OF YOUR PERSONAL DATA TO OUR OFFICES IN THE UNITED STATES.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FlexAI
provenance_date: '2026-11-09'
provider_name: FlexAI
provider_slug: flexai
slug: flexai-privacy-policy
source_date: '2026-11-09'
source_filename: flexai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flex.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FlexAI\naid: flexai\nurl: https://flex.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: With respect to your Client Data (workloads, etc.) as defined in our Terms, we are a Data Processor acting\n    on your behalf.\ndata_categories:\n- category: identifying\n  text: including company name, your name, email address, phone number, and payment/billing information such as\n    address and payment method\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category:\
  \ location\n  text: Your general location may be derived from your IP address.\n- category: behavioral\n  text: information about how and when you use our Services, and other technical information\npurposes:\n- purpose: Deliver and improve Services\n  text: We process your End User information to provide, improve, and administer our Services, communicate with\n    you, for security and fraud prevention, and to comply with the law.\n- purpose: Marketing and advertising measurement\n  text: We measure which of our ads lead to sign-ups and purchases, as described in Section 1, but we do not use\n    this to make decisions about you.\nretention:\n- scope: Usage metadata\n  period: 90 days\n  text: Usage metadata is deleted from live systems after 90 days and archived for 2 years.\n- scope: Client IP addresses\n  period: 13 months\n  text: Client IP addresses are retained for 13 months for security and abuse prevention.\nresidency:\n- region: EU workspaces metadata\n  text: For EU workspaces,\
  \ this metadata is stored within the European Union.\ntransfers:\n- mechanism: other\n  text: BY SIGNING UP FOR AND USING OUR SERVICES, YOU UNDERSTAND AND CONSENT TO TRANSFER OF YOUR PERSONAL DATA TO\n    OUR OFFICES IN THE UNITED STATES.\nsubprocessors:\n  url: null\n  text: A list of our subprocessors will be made available on demand.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email legal@flex.ai to request removal or deletion\n  text: To request to review, update, or delete your personal information, please email us at legal@flex.ai .\nrights:\n- right: Access\n  text: Upon request, we will provide you with access to the personal information that we hold about you.\n- right: Correction\n  text: You may also correct, amend, or delete the personal information we hold about you.\n- right: Erasure\n  text: (ii) to request rectification or erasure;\n- right: Restrict processing\n  text: (iii) to restrict the processing of your personal information;\n- right:\
  \ Data portability\n  text: (iv) if applicable, to data portability;\n- right: Withdraw consent\n  text: You have the right to withdraw your consent for our processing of your information at any time.\n- right: Opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance: conditional\n  text: 'We have shared the following categories of personal information to third parties in the preceding twelve\n    (12) months: Inferences drawn from collected personal information Identifiers (online identifiers and hashed\n    email addresses), shared with advertising networks'\n"
source_yaml_url: https://artifacts.apis.io/flexai/privacy/flexai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from FlexAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- LLM
- OpenAI-Compatible
- GPU Compute
- Embeddings
- Fine-Tuning
- Agents
---
