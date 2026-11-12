---
api_specs:
- filename: corebee-ai-auth-api-openapi.yml
  format: yaml
  label: Corebee Auth API
  slug: corebee-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-auth-api-openapi.yml
- filename: corebee-ai-contacts-api-openapi.yml
  format: yaml
  label: Corebee Contacts API
  slug: corebee-ai-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-contacts-api-openapi.yml
- filename: corebee-ai-conversations-api-openapi.yml
  format: yaml
  label: Corebee Conversations API
  slug: corebee-ai-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-conversations-api-openapi.yml
- filename: corebee-ai-labels-api-openapi.yml
  format: yaml
  label: Corebee Labels API
  slug: corebee-ai-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-labels-api-openapi.yml
- filename: corebee-ai-voice-api-openapi.yml
  format: yaml
  label: Corebee Voice API
  slug: corebee-ai-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-voice-api-openapi.yml
- filename: corebee-ai-webhooks-api-openapi.yml
  format: yaml
  label: Corebee Webhooks API
  slug: corebee-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corebee-ai/openapi/corebee-ai-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email address, company name, and password when you register'
  - category: financial
    text: 'Payment information: processed securely through our payment provider (Polar/Stripe), or Shopify, if you subscribe through the Shopify App Store.'
  - category: communication
    text: 'Communications: messages you send to us via email, chat, or other channels'
  - category: device
    text: 'Device data: browser type, operating system, device type, screen resolution, and language preferences'
  - category: behavioral
    text: 'Usage data: pages visited, features used, session duration, click patterns, and referral sources'
  - category: location
    text: 'Network data: IP address (anonymized for EU/EEA visitors in analytics), approximate geographic location'
  deletion:
    route: Contact support@corebee.ai; closing account requires email from an owner's address
    text: You can request deletion of your data at any time by contacting us.
  dpa:
    available: true
    text: our Data Processing Agreement
    url: null
  purposes:
  - purpose: Managing relationship and operating business
    text: We process this data for the purposes of managing our relationship with you, operating our business, and complying with legal obligations.
  - purpose: Fraud prevention and security
    text: Detect, investigate, and prevent fraudulent, unauthorized, or illegal activity
  residency:
  - region: India (application and primary database)
    text: The Corebee application runs on infrastructure physically located in Mumbai, India
  - region: Germany (product analytics)
    text: 'Product analytics (PostHog): EU Cloud (Frankfurt, Germany).'
  - region: United States (voice servers)
    text: 'Voice servers (Fly.io): United States (Ashburn, Virginia).'
  retention:
  - period: 30 days
    scope: Account and Customer Data
    text: After an account ends, you have 30 days to export your Customer Data.
  - period: 7 years
    scope: Payment records
    text: 'Payment records: 7 years (as required by tax law)'
  - period: 14 months
    scope: Analytics data (GA4)
    text: We have configured a data retention period of 14 months.
  - period: 30 days
    scope: PostHog session replay
    text: Retained 30 days.
  rights:
  - right: Access
    text: Access your personal data (Article 15)
  - right: Delete
    text: Delete your data ("right to be forgotten") (Article 17)
  - right: Portability
    text: 'Data portability : receive your data in a structured, commonly used, machine-readable format (Article 20)'
  - right: Object
    text: Object to processing of your data, including for direct marketing (Article 21)
  - right: Opt out of sale or sharing (California)
    text: 'Right to opt out: of the sale or sharing of personal information'
  role:
    text: Corebee as Data Controller Corebee is the data controller for personal data collected through our website, marketing activities, and account management.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We have executed the Standard Contractual Clauses approved by the European Commission (Implementing Decision 2021/914) with our Indian and US sub-processors as the primary transfer mechanism for personal data leaving the EEA.
  - mechanism: DPF
    text: Where a US sub-processor (e.g. Sentry, Resend, OpenAI, Anthropic, Stripe, Google, Meta) is self-certified under the EU-US Data Privacy Framework
  - mechanism: other
    text: UK Addendum to the EU SCCs issued by the UK Information Commissioner (ICO)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Corebee
provenance_date: '2026-11-09'
provider_name: Corebee
provider_slug: corebee-ai
slug: corebee-ai-privacy-policy
source_date: '2026-11-09'
source_filename: corebee-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corebee.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Corebee\naid: corebee-ai\nurl: https://corebee.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Corebee as Data Controller Corebee is the data controller for personal data collected through our website,\n    marketing activities, and account management.\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email address, company name, and password when you register'\n- category: financial\n  text: 'Payment information: processed securely through our payment provider (Polar/Stripe), or Shopify, if you\n    subscribe through the Shopify App Store.'\n- category: communication\n\
  \  text: 'Communications: messages you send to us via email, chat, or other channels'\n- category: device\n  text: 'Device data: browser type, operating system, device type, screen resolution, and language preferences'\n- category: behavioral\n  text: 'Usage data: pages visited, features used, session duration, click patterns, and referral sources'\n- category: location\n  text: 'Network data: IP address (anonymized for EU/EEA visitors in analytics), approximate geographic location'\npurposes:\n- purpose: Managing relationship and operating business\n  text: We process this data for the purposes of managing our relationship with you, operating our business, and\n    complying with legal obligations.\n- purpose: Fraud prevention and security\n  text: Detect, investigate, and prevent fraudulent, unauthorized, or illegal activity\nretention:\n- scope: Account and Customer Data\n  period: 30 days\n  text: After an account ends, you have 30 days to export your Customer Data.\n- scope: Payment\
  \ records\n  period: 7 years\n  text: 'Payment records: 7 years (as required by tax law)'\n- scope: Analytics data (GA4)\n  period: 14 months\n  text: We have configured a data retention period of 14 months.\n- scope: PostHog session replay\n  period: 30 days\n  text: Retained 30 days.\nresidency:\n- region: India (application and primary database)\n  text: The Corebee application runs on infrastructure physically located in Mumbai, India\n- region: Germany (product analytics)\n  text: 'Product analytics (PostHog): EU Cloud (Frankfurt, Germany).'\n- region: United States (voice servers)\n  text: 'Voice servers (Fly.io): United States (Ashburn, Virginia).'\ntransfers:\n- mechanism: SCC\n  text: We have executed the Standard Contractual Clauses approved by the European Commission (Implementing Decision\n    2021/914) with our Indian and US sub-processors as the primary transfer mechanism for personal data leaving\n    the EEA.\n- mechanism: DPF\n  text: Where a US sub-processor (e.g. Sentry,\
  \ Resend, OpenAI, Anthropic, Stripe, Google, Meta) is self-certified\n    under the EU-US Data Privacy Framework\n- mechanism: other\n  text: UK Addendum to the EU SCCs issued by the UK Information Commissioner (ICO)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: our Data Processing Agreement\ndeletion:\n  route: Contact support@corebee.ai; closing account requires email from an owner's address\n  text: You can request deletion of your data at any time by contacting us.\nrights:\n- right: Access\n  text: Access your personal data (Article 15)\n- right: Delete\n  text: Delete your data (\"right to be forgotten\") (Article 17)\n- right: Portability\n  text: 'Data portability : receive your data in a structured, commonly used, machine-readable format (Article 20)'\n- right: Object\n  text: Object to processing of your data, including for direct marketing (Article 21)\n- right: Opt out of sale or sharing (California)\n  text: 'Right to opt out: of\
  \ the sale or sharing of personal information'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/corebee-ai/privacy/corebee-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Corebee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Support
- Artificial Intelligence
- Chatbots
- Help Desk
- Omnichannel Messaging
- Voice Agents
- MCP
---
