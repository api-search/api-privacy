---
api_specs:
- filename: spicyapi-com-agent-tools-api-openapi.yml
  format: yaml
  label: spicyapi-com Agent tools API
  slug: spicyapi-com-agent-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-agent-tools-api-openapi.yml
- filename: spicyapi-com-audio-api-openapi.yml
  format: yaml
  label: spicyapi-com Audio API
  slug: spicyapi-com-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-audio-api-openapi.yml
- filename: spicyapi-com-characters-api-openapi.yml
  format: yaml
  label: spicyapi-com Characters API
  slug: spicyapi-com-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-characters-api-openapi.yml
- filename: spicyapi-com-core-api-openapi.yml
  format: yaml
  label: spicyapi-com Core API
  slug: spicyapi-com-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-core-api-openapi.yml
- filename: spicyapi-com-default-api-openapi.yml
  format: yaml
  label: spicyapi-com Default API
  slug: spicyapi-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-default-api-openapi.yml
- filename: spicyapi-com-embeddings-api-openapi.yml
  format: yaml
  label: spicyapi-com Embeddings API
  slug: spicyapi-com-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-embeddings-api-openapi.yml
- filename: spicyapi-com-guarded-api-openapi.yml
  format: yaml
  label: spicyapi-com Guarded API
  slug: spicyapi-com-guarded-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-guarded-api-openapi.yml
- filename: spicyapi-com-images-api-openapi.yml
  format: yaml
  label: spicyapi-com Images API
  slug: spicyapi-com-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-images-api-openapi.yml
- filename: spicyapi-com-live-calls-api-openapi.yml
  format: yaml
  label: spicyapi-com Live calls API
  slug: spicyapi-com-live-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-live-calls-api-openapi.yml
- filename: spicyapi-com-moderation-api-openapi.yml
  format: yaml
  label: spicyapi-com Moderation API
  slug: spicyapi-com-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-moderation-api-openapi.yml
- filename: spicyapi-com-video-api-openapi.yml
  format: yaml
  label: spicyapi-com Video API
  slug: spicyapi-com-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-video-api-openapi.yml
- filename: spicyapi-com-chat-completions-api-openapi.yml
  format: yaml
  label: spicyapi-com Chat Completions API
  slug: spicyapi-com-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-chat-completions-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: When you register for an account, we collect your email address and account credentials (such as a hashed password).'
  - category: financial
    text: We do not store your full credit card details, but we may receive transaction identifiers and summary information.
  - category: location
    text: When you use the dashboard we also record the country and region your IP address points to, to decide whether the law there requires age verification.
  - category: device
    text: We may collect information about the device and software you use to access our Services, including browser type and version.
  - category: behavioral
    text: PostHog (EU cloud) records page views, product events and session replays of our website and dashboard, with every form input masked, and links them to your account email when you are signed in.
  - category: communication
    text: If you contact us directly, we may receive additional information such as your name, the contents of your message, and any other information you may choose to provide.
  deletion:
    route: Settings, under Security, or contact us
    text: You can delete your account and associated personal data yourself in Settings, under Security, or ask us to by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Services
    text: To operate our API, process your requests, manage your account, and process payments.
  - purpose: Improve and analyze the Services
    text: To understand usage patterns, diagnose technical issues, and improve the performance and safety of our API.
  - purpose: Security and fraud prevention
    text: To monitor for malicious or prohibited activity, to screen imported images and reference images, and to enforce our Terms of Service.
  - purpose: Legal compliance and age verification
    text: To comply with applicable laws, regulations, and legal processes, such as responding to lawful requests from public authorities, and to apply age verification laws
  residency:
  - region: European Union
    text: We are established in the European Union, but some of our service providers process personal data outside the European Economic Area and the United Kingdom
  retention:
  - period: 30 days
    scope: Account data
    text: When your account is deleted, we delete it within 30 days, except the records described in sections 6.3 to 6.6, which we must keep.
  - period: six years
    scope: Request records
    text: They are kept for as long as your account exists and for six years after it is closed.
  - period: 30 days
    scope: Failed API request records
    text: Records of failed API requests are kept for 30 days.
  - period: 12 months
    scope: Hosting server logs
    text: Our hosting providers' server logs are kept for up to 12 months for security analysis and troubleshooting.
  rights:
  - right: access, update, or delete
    text: The right to access , update , or delete the information we have on you.
  - right: rectification
    text: The right of rectification .
  - right: object
    text: The right to object to our processing.
  - right: restriction
    text: The right of restriction .
  - right: portability
    text: The right to data portability .
  - right: withdraw consent
    text: The right to withdraw consent at any time.
  role:
    text: The data controller responsible for your personal information is Wayfinity Ltd, a company incorporated in the Republic of Cyprus (registration number HE 477899), trading as SpicyAPI.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'We use the following service providers, which process personal data on our instructions, only have access to the information they need for their function, and are obliged to protect it: Alibaba Cloud (Singapore) Private Limited, Singapore'
    url: null
  transfers:
  - mechanism: SCC
    text: For every such transfer we rely on the European Commission's Standard Contractual Clauses (with the United Kingdom addendum for UK data) in the provider's data processing terms
  - mechanism: DPF
    text: or on the EU-US Data Privacy Framework where the provider is certified under it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: spicyapi-com
provenance_date: '2026-11-10'
provider_name: spicyapi-com
provider_slug: spicyapi-com
slug: spicyapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: spicyapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.spicyapi.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: spicyapi-com\naid: spicyapi-com\nurl: https://www.spicyapi.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller responsible for your personal information is Wayfinity Ltd, a company incorporated in\n    the Republic of Cyprus (registration number HE 477899), trading as SpicyAPI.\ndata_categories:\n- category: identifying\n  text: 'Account Information: When you register for an account, we collect your email address and account credentials\n    (such as a hashed password).'\n- category: financial\n  text: We do not store your full credit card details, but we\
  \ may receive transaction identifiers and summary information.\n- category: location\n  text: When you use the dashboard we also record the country and region your IP address points to, to decide whether\n    the law there requires age verification.\n- category: device\n  text: We may collect information about the device and software you use to access our Services, including browser\n    type and version.\n- category: behavioral\n  text: PostHog (EU cloud) records page views, product events and session replays of our website and dashboard,\n    with every form input masked, and links them to your account email when you are signed in.\n- category: communication\n  text: If you contact us directly, we may receive additional information such as your name, the contents of your\n    message, and any other information you may choose to provide.\npurposes:\n- purpose: Provide and maintain the Services\n  text: To operate our API, process your requests, manage your account, and process payments.\n\
  - purpose: Improve and analyze the Services\n  text: To understand usage patterns, diagnose technical issues, and improve the performance and safety of our API.\n- purpose: Security and fraud prevention\n  text: To monitor for malicious or prohibited activity, to screen imported images and reference images, and to\n    enforce our Terms of Service.\n- purpose: Legal compliance and age verification\n  text: To comply with applicable laws, regulations, and legal processes, such as responding to lawful requests\n    from public authorities, and to apply age verification laws\nretention:\n- scope: Account data\n  period: 30 days\n  text: When your account is deleted, we delete it within 30 days, except the records described in sections 6.3\n    to 6.6, which we must keep.\n- scope: Request records\n  period: six years\n  text: They are kept for as long as your account exists and for six years after it is closed.\n- scope: Failed API request records\n  period: 30 days\n  text: Records of failed\
  \ API requests are kept for 30 days.\n- scope: Hosting server logs\n  period: 12 months\n  text: Our hosting providers' server logs are kept for up to 12 months for security analysis and troubleshooting.\nresidency:\n- region: European Union\n  text: We are established in the European Union, but some of our service providers process personal data outside\n    the European Economic Area and the United Kingdom\ntransfers:\n- mechanism: SCC\n  text: For every such transfer we rely on the European Commission's Standard Contractual Clauses (with the United\n    Kingdom addendum for UK data) in the provider's data processing terms\n- mechanism: DPF\n  text: or on the EU-US Data Privacy Framework where the provider is certified under it.\nsubprocessors:\n  url: null\n  text: 'We use the following service providers, which process personal data on our instructions, only have access\n    to the information they need for their function, and are obliged to protect it: Alibaba Cloud (Singapore) Private\n\
  \    Limited, Singapore'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings, under Security, or contact us\n  text: You can delete your account and associated personal data yourself in Settings, under Security, or ask us\n    to by contacting us.\nrights:\n- right: access, update, or delete\n  text: The right to access , update , or delete the information we have on you.\n- right: rectification\n  text: The right of rectification .\n- right: object\n  text: The right to object to our processing.\n- right: restriction\n  text: The right of restriction .\n- right: portability\n  text: The right to data portability .\n- right: withdraw consent\n  text: The right to withdraw consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/spicyapi-com/privacy/spicyapi-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from spicyapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Adult
- Image Generation
- Video Generation
- Voice
---
