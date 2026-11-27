---
api_specs:
- filename: mintlify-agent-api-openapi.yml
  format: yaml
  label: Mintlify Agent API
  slug: mintlify-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-agent-api-openapi.yml
- filename: mintlify-analytics-api-openapi.yml
  format: yaml
  label: Mintlify Analytics API
  slug: mintlify-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-analytics-api-openapi.yml
- filename: mintlify-assistant-api-openapi.yml
  format: yaml
  label: Mintlify Assistant API
  slug: mintlify-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-assistant-api-openapi.yml
- filename: mintlify-update-api-openapi.yml
  format: yaml
  label: Mintlify Update API
  slug: mintlify-update-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mintlify/openapi/mintlify-update-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: names email addresses
  - category: contact
    text: Contact details, such as real name, alias, postal address, telephone or mobile contact number, unique personal identifier, online identifier, Internet Protocol address, email address, and account name
  - category: financial
    text: Payment Data. We may collect data necessary to process your payment if you make purchases, such as your payment instrument number, and the security code associated with your payment instrument.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information our servers automatically collect when you access or use our Services
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: communication
    text: Messages sent to the bot may be passed to third-party LLM providers (such as Anthropic and OpenAI) for inference only
  deletion:
    route: Request via email or data subject access request form
    text: To request to review, update, or delete your personal information, please fill out and submit a data subject access request .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, improve, and administer Services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: Identify usage trends
    text: To identify usage trends. We may process information about how you use our Services to better understand how they are being used so we can improve them.
  - purpose: Marketing communications to existing customers
    text: Send marketing communications to existing customers and business contacts about products and services that may be of interest to them, subject to your right to opt out at any time
  - purpose: Cookie-based analytics and marketing
    text: Marketing / advertising Help us understand the effectiveness of our marketing, attribute visits and conversions, identify the organizations and visitors interested in Mintlify, and deliver and measure relevant advertising.
  residency:
  - region: United States
    text: Because we and some of our service providers are based in the United States, your information may be transferred internationally
  retention:
  - period: null
    scope: Account data
    text: 'We have collected the following categories of personal information in the past twelve (12) months: Category Examples Collected A. Identifiers'
  - period: null
    scope: Personal information generally
    text: No purpose in this notice will require us keeping your personal information for longer than the period of time in which users have an account with us.
  - period: up to 30 days
    scope: Slack transient logs
    text: Transient logs that may include excerpts are retained for up to 30 days for debugging and then purged.
  - period: up to 30 days
    scope: Teams transient logs
    text: Transient logs that may include excerpts are retained for up to 30 days for debugging and then purged.
  rights:
  - right: Access
    text: (i) to request access and obtain a copy of your personal information
  - right: Rectification or erasure
    text: (ii) to request rectification or erasure;
  - right: Restrict processing
    text: (iii) to restrict the processing of your personal information;
  - right: Data portability
    text: (iv) if applicable, to data portability.
  - right: Object
    text: In certain circumstances, you may also have the right to object to the processing of your personal information.
  - right: Opt out of sale or sharing (CCPA)
    text: You may request to opt out from future selling or sharing of your personal information to third parties.
  - right: Non-discrimination
    text: We will not discriminate against you if you exercise your privacy rights.
  role:
    text: This privacy notice for Mintlify, Inc. (doing business as Mintlify) ( Mintlify , we , us , or our ), describes how and why we might collect, store, use, and/or share ( process ) your information when you use our services
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Mintlify, Inc. will not sell or share personal information in the future belonging to website visitors, users, and other consumers.
  subprocessors:
    text: Information about our approved third party service providers can be found in our trust center page.
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses (SCCs)
  - mechanism: DPF
    text: the EU–US Data Privacy Framework (and its UK and Swiss extensions) when required, and where the recipient is certified
  - mechanism: other
    text: the UK International Data Transfer Addendum (IDTA) to the SCCs
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mintlify
provenance_date: '2026-11-10'
provider_name: Mintlify
provider_slug: mintlify
slug: mintlify-privacy-policy
source_date: '2026-11-10'
source_filename: mintlify-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mintlify.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mintlify\naid: mintlify\nurl: https://www.mintlify.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This privacy notice for Mintlify, Inc. (doing business as Mintlify) ( Mintlify , we , us , or our ), describes\n    how and why we might collect, store, use, and/or share ( process ) your information when you use our services\ndata_categories:\n- category: identifying\n  text: names email addresses\n- category: contact\n  text: Contact details, such as real name, alias, postal address, telephone or mobile contact number, unique personal\n    identifier, online identifier, Internet\
  \ Protocol address, email address, and account name\n- category: financial\n  text: Payment Data. We may collect data necessary to process your payment if you make purchases, such as your\n    payment instrument number, and the security code associated with your payment instrument.\n- category: location\n  text: Location Data. We collect location data such as information about your device's location, which can be either\n    precise or imprecise.\n- category: behavioral\n  text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information\n    our servers automatically collect when you access or use our Services\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category: communication\n  text: Messages sent to the bot may be passed to third-party LLM providers (such as Anthropic and OpenAI) for inference\n    only\n\
  purposes:\n- purpose: Provide, improve, and administer Services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: Identify usage trends\n  text: To identify usage trends. We may process information about how you use our Services to better understand\n    how they are being used so we can improve them.\n- purpose: Marketing communications to existing customers\n  text: Send marketing communications to existing customers and business contacts about products and services that\n    may be of interest to them, subject to your right to opt out at any time\n- purpose: Cookie-based analytics and marketing\n  text: Marketing / advertising Help us understand the effectiveness of our marketing, attribute visits and conversions,\n    identify the organizations and visitors interested in Mintlify, and deliver and measure relevant advertising.\nretention:\n- scope: Account\
  \ data\n  period: null\n  text: 'We have collected the following categories of personal information in the past twelve (12) months: Category\n    Examples Collected A. Identifiers'\n- scope: Personal information generally\n  period: null\n  text: No purpose in this notice will require us keeping your personal information for longer than the period of\n    time in which users have an account with us.\n- scope: Slack transient logs\n  period: up to 30 days\n  text: Transient logs that may include excerpts are retained for up to 30 days for debugging and then purged.\n- scope: Teams transient logs\n  period: up to 30 days\n  text: Transient logs that may include excerpts are retained for up to 30 days for debugging and then purged.\nresidency:\n- region: United States\n  text: Because we and some of our service providers are based in the United States, your information may be transferred\n    internationally\ntransfers:\n- mechanism: SCC\n  text: the European Commission's Standard Contractual\
  \ Clauses (SCCs)\n- mechanism: DPF\n  text: the EU–US Data Privacy Framework (and its UK and Swiss extensions) when required, and where the recipient\n    is certified\n- mechanism: other\n  text: the UK International Data Transfer Addendum (IDTA) to the SCCs\nsubprocessors:\n  url: null\n  text: Information about our approved third party service providers can be found in our trust center page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via email or data subject access request form\n  text: To request to review, update, or delete your personal information, please fill out and submit a data subject\n    access request .\nrights:\n- right: Access\n  text: (i) to request access and obtain a copy of your personal information\n- right: Rectification or erasure\n  text: (ii) to request rectification or erasure;\n- right: Restrict processing\n  text: (iii) to restrict the processing of your personal information;\n- right: Data portability\n  text: (iv) if\
  \ applicable, to data portability.\n- right: Object\n  text: In certain circumstances, you may also have the right to object to the processing of your personal information.\n- right: Opt out of sale or sharing (CCPA)\n  text: You may request to opt out from future selling or sharing of your personal information to third parties.\n- right: Non-discrimination\n  text: We will not discriminate against you if you exercise your privacy rights.\nsale_or_sharing:\n  stance: prohibited\n  text: Mintlify, Inc. will not sell or share personal information in the future belonging to website visitors,\n    users, and other consumers.\n"
source_yaml_url: https://artifacts.apis.io/mintlify/privacy/mintlify-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Mintlify's own page on 2026-11-10.
synthetic: false
tags:
- Documentation
- API Documentation
- Developer Portal
- MCP
- AI Assistant
- Docs as Code
---
