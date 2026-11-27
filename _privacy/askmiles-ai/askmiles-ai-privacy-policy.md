---
api_specs:
- filename: askmiles-ai-openapi-generated.yml
  format: yaml
  label: AskMiles AI API
  slug: askmiles-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askmiles-ai/openapi/_ae-authored/askmiles-ai-openapi-generated.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: contact
    text: When you create an account, I collect your email address.
  - category: identifying
    text: You can give Miles a first name to call you by. That is optional, and it is the only name Miles asks for.
  - category: communication
    text: I store every message you send to Miles and every response it gives you.
  - category: behavioral
    text: Memory and Profile Data Miles keeps notes from your conversations so it can remember what you tell it.
  - category: device
    text: 'The server logs basic technical information: your IP address, browser version, and usage data.'
  - category: financial
    text: 'Credit card preferences : Types of cards you''re interested in, annual fee tolerance'
  - category: location
    text: 'Personal context : Family size, location, travel frequency'
  deletion:
    route: Settings page 'Delete Account' button, or email support@askmiles.ai
    text: You can delete your account at any time through your Settings page, or by contacting me at support@askmiles.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide AI responses
    text: Process your questions through AI services
  - purpose: Account management
    text: Manage your account, send account-related emails
  - purpose: Improve personalization
    text: Use conversation history and memory data to provide better recommendations
  - purpose: Process payments
    text: Handle support payments and billing
  - purpose: Improve the service
    text: Analyze usage patterns and service performance
  - purpose: Legal compliance
    text: Meet legal obligations and protect my legal rights
  residency:
  - region: United States
    text: Your information may be processed, stored, and used outside your country of residence, including in the United States.
  retention:
  - period: null
    scope: Active accounts
    text: All data is kept while your account is active
  - period: 30 days
    scope: Deleted accounts
    text: It is kept for 30 days to protect free offers from repeat sign-ups.
  - period: 30 days
    scope: Server logs
    text: These logs are used to keep Miles running and secure, and are deleted automatically after 30 days.
  - period: 90 days
    scope: Audit logs
    text: These records are kept for 90 days.
  - period: 400 days
    scope: Session analytics
    text: are kept for up to 400 days.
  - period: 7 days
    scope: Backups
    text: The backup files themselves expire from Cloudflare R2 after 7 days.
  rights:
  - right: Access
    text: Access your personal data
  - right: Rectify
    text: Rectify inaccurate data
  - right: Erase
    text: Erase your data (“right to be forgotten”)
  - right: Restrict processing
    text: Restrict processing
  - right: Data portability
    text: Data portability
  - right: Object to processing
    text: Object to processing
  - right: Know what personal information is collected
    text: Know what personal information is collected
  - right: Opt out of sale
    text: Opt out of sale (I don't sell data)
  role:
    text: This policy says “I” because there is no company.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: I do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your information may be processed, stored, and used outside your country of residence, including in the United States. By using the service, you consent to these transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AskMiles AI
provenance_date: '2026-11-09'
provider_name: AskMiles AI
provider_slug: askmiles-ai
slug: askmiles-ai-privacy-policy
source_date: '2026-11-09'
source_filename: askmiles-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askmiles.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AskMiles AI\naid: askmiles-ai\nurl: https://askmiles.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This policy says “I” because there is no company.\ndata_categories:\n- category: contact\n  text: When you create an account, I collect your email address.\n- category: identifying\n  text: You can give Miles a first name to call you by. That is optional, and it is the only name Miles asks for.\n- category: communication\n  text: I store every message you send to Miles and every response it gives you.\n- category: behavioral\n  text: Memory and Profile Data Miles keeps notes from\
  \ your conversations so it can remember what you tell it.\n- category: device\n  text: 'The server logs basic technical information: your IP address, browser version, and usage data.'\n- category: financial\n  text: 'Credit card preferences : Types of cards you''re interested in, annual fee tolerance'\n- category: location\n  text: 'Personal context : Family size, location, travel frequency'\npurposes:\n- purpose: Provide AI responses\n  text: Process your questions through AI services\n- purpose: Account management\n  text: Manage your account, send account-related emails\n- purpose: Improve personalization\n  text: Use conversation history and memory data to provide better recommendations\n- purpose: Process payments\n  text: Handle support payments and billing\n- purpose: Improve the service\n  text: Analyze usage patterns and service performance\n- purpose: Legal compliance\n  text: Meet legal obligations and protect my legal rights\nretention:\n- scope: Active accounts\n  period:\
  \ null\n  text: All data is kept while your account is active\n- scope: Deleted accounts\n  period: 30 days\n  text: It is kept for 30 days to protect free offers from repeat sign-ups.\n- scope: Server logs\n  period: 30 days\n  text: These logs are used to keep Miles running and secure, and are deleted automatically after 30 days.\n- scope: Audit logs\n  period: 90 days\n  text: These records are kept for 90 days.\n- scope: Session analytics\n  period: 400 days\n  text: are kept for up to 400 days.\n- scope: Backups\n  period: 7 days\n  text: The backup files themselves expire from Cloudflare R2 after 7 days.\nresidency:\n- region: United States\n  text: Your information may be processed, stored, and used outside your country of residence, including in the\n    United States.\ntransfers:\n- mechanism: other\n  text: Your information may be processed, stored, and used outside your country of residence, including in the\n    United States. By using the service, you consent to these transfers.\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings page 'Delete Account' button, or email support@askmiles.ai\n  text: You can delete your account at any time through your Settings page, or by contacting me at support@askmiles.ai\n    .\nrights:\n- right: Access\n  text: Access your personal data\n- right: Rectify\n  text: Rectify inaccurate data\n- right: Erase\n  text: Erase your data (“right to be forgotten”)\n- right: Restrict processing\n  text: Restrict processing\n- right: Data portability\n  text: Data portability\n- right: Object to processing\n  text: Object to processing\n- right: Know what personal information is collected\n  text: Know what personal information is collected\n- right: Opt out of sale\n  text: Opt out of sale (I don't sell data)\nsale_or_sharing:\n  stance: prohibited\n  text: I do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/askmiles-ai/privacy/askmiles-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from AskMiles AI's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Credit Cards
- Rewards
- Personal Finance
- Artificial Intelligence
---
