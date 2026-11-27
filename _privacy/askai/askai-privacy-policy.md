---
api_specs:
- filename: askai-openapi-generated.yml
  format: yaml
  label: AskAI API
  slug: askai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askai/openapi/_ae-authored/askai-openapi-generated.yml
- filename: askai-gptfy-api-api-openapi.yml
  format: yaml
  label: GPTfy GPTfy API
  slug: askai-gptfy-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askai/openapi/askai-gptfy-api-api-openapi.yml
- filename: askai-chat-completions-api-openapi.yml
  format: yaml
  label: GPTfy Chat Completions API
  slug: askai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askai/openapi/askai-chat-completions-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Optional Account Information: If you choose to create an account (email, username)'
  - category: contact
    text: 'Contact Information: When you contact our support team'
  - category: device
    text: 'Device Information: Browser type, operating system, IP address'
  - category: behavioral
    text: 'Usage Data: How you interact with our service (pages visited, features used)'
  - category: other
    text: 'Images and Media You Upload: Photos, images, GIFs, and videos you upload to our AI image, face swap and age-guesser tools'
  - category: communication
    text: 'Chat Messages: The questions and messages you send to our AI assistants'
  deletion:
    route: Account deletion or contact the privacy team
    text: If you create an account, we retain your account information until you delete your account or request deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision
    text: Process and respond to your AI chat requests
  - purpose: Service improvement
    text: Analyze usage patterns to improve user experience
  - purpose: Legal and security
    text: Protect against fraud, abuse, and security threats
  - purpose: Advertising
    text: Playwire LLC may collect and use certain aggregated and anonymized data for advertising purposes.
  retention:
  - period: 24 hours
    scope: Chats and images for free and anonymous users
    text: For anonymous visitors and free accounts, your chats and any images or videos you generate are automatically and permanently deleted after 24 hours.
  - period: up to 24 months
    scope: Usage analytics
    text: Anonymous usage analytics may be retained for up to 24 months to help improve our service.
  - period: up to 30 days
    scope: How Old Do I Look uploads
    text: uploads to the How Old Do I Look age guesser and source-and-result review copies from the AI Hairstyle Changer are retained privately for up to 30 days
  - period: null
    scope: Account information
    text: If you create an account, we retain your account information until you delete your account or request deletion.
  rights:
  - right: Access
    text: 'Access: Request access to your personal information'
  - right: Correction
    text: 'Correction: Request correction of inaccurate information'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal information'
  - right: Portability
    text: 'Portability: Request a copy of your data in a portable format'
  - right: Objection
    text: 'Objection: Object to certain uses of your information'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal data or chat conversations to advertisers or data brokers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your information may be transferred to and processed in countries other than your country of residence.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GPTfy
provenance_date: '2026-11-09'
provider_name: GPTfy
provider_slug: askai
slug: askai-privacy-policy
source_date: '2026-11-09'
source_filename: askai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askai.free/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GPTfy\naid: askai\nurl: https://askai.free/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Optional Account Information: If you choose to create an account (email, username)'\n- category: contact\n  text: 'Contact Information: When you contact our support team'\n- category: device\n  text: 'Device Information: Browser type, operating system, IP address'\n- category: behavioral\n  text: 'Usage Data: How you interact with our service (pages visited, features used)'\n- category: other\n  text: 'Images and Media You Upload:\
  \ Photos, images, GIFs, and videos you upload to our AI image, face swap and\n    age-guesser tools'\n- category: communication\n  text: 'Chat Messages: The questions and messages you send to our AI assistants'\npurposes:\n- purpose: Service provision\n  text: Process and respond to your AI chat requests\n- purpose: Service improvement\n  text: Analyze usage patterns to improve user experience\n- purpose: Legal and security\n  text: Protect against fraud, abuse, and security threats\n- purpose: Advertising\n  text: Playwire LLC may collect and use certain aggregated and anonymized data for advertising purposes.\nretention:\n- scope: Chats and images for free and anonymous users\n  period: 24 hours\n  text: For anonymous visitors and free accounts, your chats and any images or videos you generate are automatically\n    and permanently deleted after 24 hours.\n- scope: Usage analytics\n  period: up to 24 months\n  text: Anonymous usage analytics may be retained for up to 24 months to help\
  \ improve our service.\n- scope: How Old Do I Look uploads\n  period: up to 30 days\n  text: uploads to the How Old Do I Look age guesser and source-and-result review copies from the AI Hairstyle Changer\n    are retained privately for up to 30 days\n- scope: Account information\n  period: null\n  text: If you create an account, we retain your account information until you delete your account or request deletion.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may be transferred to and processed in countries other than your country of residence.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or contact the privacy team\n  text: If you create an account, we retain your account information until you delete your account or request deletion.\nrights:\n- right: Access\n  text: 'Access: Request access to your personal information'\n- right: Correction\n  text: 'Correction: Request correction\
  \ of inaccurate information'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal information'\n- right: Portability\n  text: 'Portability: Request a copy of your data in a portable format'\n- right: Objection\n  text: 'Objection: Object to certain uses of your information'\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal data or chat conversations to advertisers or data brokers.\n"
source_yaml_url: https://artifacts.apis.io/askai/privacy/askai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from GPTfy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Language-Model
- Platform
---
