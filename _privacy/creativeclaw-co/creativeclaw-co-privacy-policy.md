---
api_specs:
- filename: creativeclaw-co-health-api-openapi.yml
  format: yaml
  label: CreativeClaw Health API
  slug: creativeclaw-co-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creativeclaw-co/openapi/creativeclaw-co-health-api-openapi.yml
- filename: creativeclaw-co-mcp-api-openapi.yml
  format: yaml
  label: CreativeClaw MCP API
  slug: creativeclaw-co-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creativeclaw-co/openapi/creativeclaw-co-mcp-api-openapi.yml
- filename: creativeclaw-co-oauth-api-openapi.yml
  format: yaml
  label: CreativeClaw OAuth API
  slug: creativeclaw-co-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/creativeclaw-co/openapi/creativeclaw-co-oauth-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: Email address and name when you sign up or authenticate via Google (Gmail) OAuth.'
  - category: contact
    text: 'Communications: Information you provide when you contact us at [email protected] or send feedback through the product.'
  - category: financial
    text: 'Purchases: When you buy credits or a plan, our payment processor handles your payment details. We receive a record of the purchase, not your full card number.'
  - category: location
    text: 'Assistant context: When you use CreativeClaw through an AI assistant, we receive what the assistant passes to our tools, such as your prompt and settings, along with limited context: your language, country, and time zone'
  - category: device
    text: 'Device information: Browser type, operating system, IP address, and device identifiers.'
  - category: behavioral
    text: 'Usage data: Pages visited, features used, generation requests, and interaction patterns.'
  - category: biometric
    text: Voice recordings can contain personal information; whether voice data is treated as biometric or sensitive data depends on the processing and applicable law.
  deletion:
    route: Contact [email protected] to request deletion of account and associated data; in-product deletion of uploaded and generated media and Characters
    text: You may request deletion of your account and associated data by contacting us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide, maintain, and improve our Services, including processing your media generation requests through third-party AI models (via fal.ai).
  - purpose: Authentication and account management
    text: Authenticate your identity and manage your account.
  - purpose: Analytics
    text: Monitor and analyze usage trends to improve the product experience.
  - purpose: Fraud and security
    text: Detect, prevent, and address fraud, abuse, or technical issues.
  - purpose: Voice cloning
    text: We process them to provide requested voice features and to handle consent, security, support, and legal obligations.
  residency:
  - region: Unspecified
    text: We do not promise a particular data-residency region unless expressly agreed.
  retention:
  - period: null
    scope: Account information and uploaded and generated assets
    text: We retain your account information and your uploaded and generated assets for as long as your account is active, or until you delete them.
  - period: 24 months
    scope: Usage and analytics records
    text: Usage and analytics records are kept for up to 24 months.
  - period: 30 days
    scope: Deletion requests
    text: We will delete your data within 30 days of a verified request, except where retention is required by law.
  rights:
  - right: Access, correct, or delete
    text: Access, correct, or delete your personal information.
  - right: Object or restrict processing
    text: Object to or restrict certain processing of your data.
  - right: Portability
    text: Request a copy of your data in a portable format.
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'Service providers: Including fal.ai and other AI model providers such as Google and OpenAI (media generation), ElevenLabs and Cartesia (voice cloning and speech services), Clerk (sign-in), Cloudflare (storage, hosting, CDN, and analytics routing), PostHog and Google Cloud (analytics), and payment processors.'
    url: null
  transfers:
  - mechanism: other
    text: Our service providers may process information outside your country, including in the United States, where data-protection laws may differ.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CreativeClaw
provenance_date: '2026-11-09'
provider_name: CreativeClaw
provider_slug: creativeclaw-co
slug: creativeclaw-co-privacy-policy
source_date: '2026-11-09'
source_filename: creativeclaw-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://creativeclaw.co/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CreativeClaw\naid: creativeclaw-co\nurl: https://creativeclaw.co/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: Email address and name when you sign up or authenticate via Google (Gmail) OAuth.'\n- category: contact\n  text: 'Communications: Information you provide when you contact us at [email protected] or send feedback through\n    the product.'\n- category: financial\n  text: 'Purchases: When you buy credits or a plan, our payment processor handles your payment details. We receive\n    a record of the\
  \ purchase, not your full card number.'\n- category: location\n  text: 'Assistant context: When you use CreativeClaw through an AI assistant, we receive what the assistant passes\n    to our tools, such as your prompt and settings, along with limited context: your language, country, and time\n    zone'\n- category: device\n  text: 'Device information: Browser type, operating system, IP address, and device identifiers.'\n- category: behavioral\n  text: 'Usage data: Pages visited, features used, generation requests, and interaction patterns.'\n- category: biometric\n  text: Voice recordings can contain personal information; whether voice data is treated as biometric or sensitive\n    data depends on the processing and applicable law.\npurposes:\n- purpose: Provide and improve services\n  text: Provide, maintain, and improve our Services, including processing your media generation requests through\n    third-party AI models (via fal.ai).\n- purpose: Authentication and account management\n\
  \  text: Authenticate your identity and manage your account.\n- purpose: Analytics\n  text: Monitor and analyze usage trends to improve the product experience.\n- purpose: Fraud and security\n  text: Detect, prevent, and address fraud, abuse, or technical issues.\n- purpose: Voice cloning\n  text: We process them to provide requested voice features and to handle consent, security, support, and legal\n    obligations.\nretention:\n- scope: Account information and uploaded and generated assets\n  period: null\n  text: We retain your account information and your uploaded and generated assets for as long as your account is\n    active, or until you delete them.\n- scope: Usage and analytics records\n  period: 24 months\n  text: Usage and analytics records are kept for up to 24 months.\n- scope: Deletion requests\n  period: 30 days\n  text: We will delete your data within 30 days of a verified request, except where retention is required by law.\nresidency:\n- region: Unspecified\n  text: We\
  \ do not promise a particular data-residency region unless expressly agreed.\ntransfers:\n- mechanism: other\n  text: Our service providers may process information outside your country, including in the United States, where\n    data-protection laws may differ.\nsubprocessors:\n  url: null\n  text: 'Service providers: Including fal.ai and other AI model providers such as Google and OpenAI (media generation),\n    ElevenLabs and Cartesia (voice cloning and speech services), Clerk (sign-in), Cloudflare (storage, hosting,\n    CDN, and analytics routing), PostHog and Google Cloud (analytics), and payment processors.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact [email protected] to request deletion of account and associated data; in-product deletion of uploaded\n    and generated media and Characters\n  text: You may request deletion of your account and associated data by contacting us at [email protected] .\nrights:\n- right: Access, correct, or delete\n\
  \  text: Access, correct, or delete your personal information.\n- right: Object or restrict processing\n  text: Object to or restrict certain processing of your data.\n- right: Portability\n  text: Request a copy of your data in a portable format.\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/creativeclaw-co/privacy/creativeclaw-co-privacy-policy.yml
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
summary_line: 24 quoted statements, read from CreativeClaw's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Image Generation
- Video Generation
- Audio
- MCP
- Marketing
---
