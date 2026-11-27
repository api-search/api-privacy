---
api_specs:
- filename: call4-me-balance-api-openapi.yml
  format: yaml
  label: call4me Balance API
  slug: call4-me-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-balance-api-openapi.yml
- filename: call4-me-call4me-api-api-openapi.yml
  format: yaml
  label: call4me Call4me API
  slug: call4-me-call4me-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-call4me-api-api-openapi.yml
- filename: call4-me-calls-api-openapi.yml
  format: yaml
  label: call4me Calls API
  slug: call4-me-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-calls-api-openapi.yml
- filename: call4-me-numbers-api-openapi.yml
  format: yaml
  label: call4me Numbers API
  slug: call4-me-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-numbers-api-openapi.yml
- filename: call4-me-profile-api-openapi.yml
  format: yaml
  label: call4me Profile API
  slug: call4-me-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-profile-api-openapi.yml
- filename: call4-me-requirements-api-openapi.yml
  format: yaml
  label: call4me Requirements API
  slug: call4-me-requirements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-requirements-api-openapi.yml
- filename: call4-me-scheduled-calls-api-openapi.yml
  format: yaml
  label: call4me Scheduled Calls API
  slug: call4-me-scheduled-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-scheduled-calls-api-openapi.yml
- filename: call4-me-x402-api-openapi.yml
  format: yaml
  label: call4me X402 API
  slug: call4-me-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/call4-me/openapi/call4-me-x402-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store your email, account identifier, and information supplied by your sign-in provider, such as your name and profile image.
  - category: contact
    text: If you join a call or receive a callback, we also process your phone number and your part of the conversation.
  - category: financial
    text: We store your balance, purchases, charges, and payment-provider references for billing and reconciliation.
  - category: behavioral
    text: We process browser and device information, IP addresses, referring sites, landing pages, campaign and click identifiers, cookie identifiers, and account-linked usage events for site analytics and advertising measurement.
  - category: communication
    text: Call requests and history. We store the destination number, business and task details you or your agent provide, scheduling information, answers you give during a call, call status, timing and charges, outcomes, text transcripts, and recording references.
  - category: health
    text: Some integrations outside the ChatGPT plugin also support health or dental insurance fields.
  deletion:
    route: Email me@call4.me for deletion requests; account and call-history deletion is handled by support.
    text: Account and call-history deletion is handled by support, not by a plugin tool.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Make and manage requested calls
    text: We use this information to make and manage the requested calls, return results, maintain your history, resolve problems, and prevent abuse.
  - purpose: Site analytics and advertising measurement
    text: We process browser and device information, IP addresses, referring sites, landing pages, campaign and click identifiers, cookie identifiers, and account-linked usage events for site analytics and advertising measurement.
  - purpose: Billing and reconciliation
    text: We store your balance, purchases, charges, and payment-provider references for billing and reconciliation.
  retention:
  - period: null
    scope: Account records and call history
    text: there is currently no automatic age-based deletion.
  - period: one year
    scope: Call recordings (Telnyx)
    text: Its published recording policy currently states that recordings are stored for one year unless deleted earlier, and that this maximum may change.
  - period: 400 days
    scope: Sign-in sessions
    text: our browser sessions are configured for up to 400 days and renew with active use.
  - period: seven days
    scope: OAuth access tokens
    text: OAuth access tokens last seven days; refresh tokens can last ten years and rotate when used.
  - period: 365 days
    scope: First-visit attribution cookies
    text: first-visit attribution lasts up to 365 days
  rights:
  - right: Access, correction and deletion
    text: 'Access, deletion, and other privacy requests: email me@call4.me from the address associated with your account.'
  - right: View and correct saved profile
    text: 'View and correct: use my account or the connected tools to review your calls and available recordings.'
  - right: Withdraw SMS consent
    text: You can withdraw consent at text alert preferences or, once messages are available, by replying STOP.
  - right: Object to measurement
    text: Contact us about objecting to measurement or requesting removal of associated data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Mobile information, SMS consent, and SMS subscription records are not sold or shared with third parties or affiliates for marketing or promotional purposes.
  subprocessors:
    text: Cloudflare hosts our application, databases, call-session state, and operational logs. Telnyx carries calls and processes phone numbers, call metadata, and recorded audio. OpenAI processes call instructions, relevant calling details, live audio, transcripts, and generated responses for the voice agent, its supporting reasoning, and call summaries.
    url: null
  transfers:
  - mechanism: other
    text: Our service providers may process information outside your country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: call4me
provenance_date: '2026-11-09'
provider_name: call4me
provider_slug: call4-me
slug: call4-me-privacy-policy
source_date: '2026-11-09'
source_filename: call4-me-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://call4.me/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: call4me\naid: call4-me\nurl: https://call4.me/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store your email, account identifier, and information supplied by your sign-in provider, such as your\n    name and profile image.\n- category: contact\n  text: If you join a call or receive a callback, we also process your phone number and your part of the conversation.\n- category: financial\n  text: We store your balance, purchases, charges, and payment-provider references for billing and reconciliation.\n- category: behavioral\n\
  \  text: We process browser and device information, IP addresses, referring sites, landing pages, campaign and click\n    identifiers, cookie identifiers, and account-linked usage events for site analytics and advertising measurement.\n- category: communication\n  text: Call requests and history. We store the destination number, business and task details you or your agent\n    provide, scheduling information, answers you give during a call, call status, timing and charges, outcomes,\n    text transcripts, and recording references.\n- category: health\n  text: Some integrations outside the ChatGPT plugin also support health or dental insurance fields.\npurposes:\n- purpose: Make and manage requested calls\n  text: We use this information to make and manage the requested calls, return results, maintain your history, resolve\n    problems, and prevent abuse.\n- purpose: Site analytics and advertising measurement\n  text: We process browser and device information, IP addresses, referring sites,\
  \ landing pages, campaign and click\n    identifiers, cookie identifiers, and account-linked usage events for site analytics and advertising measurement.\n- purpose: Billing and reconciliation\n  text: We store your balance, purchases, charges, and payment-provider references for billing and reconciliation.\nretention:\n- scope: Account records and call history\n  period: null\n  text: there is currently no automatic age-based deletion.\n- scope: Call recordings (Telnyx)\n  period: one year\n  text: Its published recording policy currently states that recordings are stored for one year unless deleted earlier,\n    and that this maximum may change.\n- scope: Sign-in sessions\n  period: 400 days\n  text: our browser sessions are configured for up to 400 days and renew with active use.\n- scope: OAuth access tokens\n  period: seven days\n  text: OAuth access tokens last seven days; refresh tokens can last ten years and rotate when used.\n- scope: First-visit attribution cookies\n  period:\
  \ 365 days\n  text: first-visit attribution lasts up to 365 days\nresidency: []\ntransfers:\n- mechanism: other\n  text: Our service providers may process information outside your country.\nsubprocessors:\n  url: null\n  text: Cloudflare hosts our application, databases, call-session state, and operational logs. Telnyx carries calls\n    and processes phone numbers, call metadata, and recorded audio. OpenAI processes call instructions, relevant\n    calling details, live audio, transcripts, and generated responses for the voice agent, its supporting reasoning,\n    and call summaries.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email me@call4.me for deletion requests; account and call-history deletion is handled by support.\n  text: Account and call-history deletion is handled by support, not by a plugin tool.\nrights:\n- right: Access, correction and deletion\n  text: 'Access, deletion, and other privacy requests: email me@call4.me from the address associated\
  \ with your account.'\n- right: View and correct saved profile\n  text: 'View and correct: use my account or the connected tools to review your calls and available recordings.'\n- right: Withdraw SMS consent\n  text: You can withdraw consent at text alert preferences or, once messages are available, by replying STOP.\n- right: Object to measurement\n  text: Contact us about objecting to measurement or requesting removal of associated data\nsale_or_sharing:\n  stance: prohibited\n  text: Mobile information, SMS consent, and SMS subscription records are not sold or shared with third parties\n    or affiliates for marketing or promotional purposes.\n"
source_yaml_url: https://artifacts.apis.io/call4-me/privacy/call4-me-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from call4me's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Telephony
- Automation
- Software-as-a-Service
- Call4me
---
