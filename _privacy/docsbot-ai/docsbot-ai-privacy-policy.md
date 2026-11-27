---
api_specs:
- filename: docsbot-ai-docsbot-chat-api-api-openapi.yml
  format: yaml
  label: docsbot-ai DocsBot Chat API
  slug: docsbot-ai-docsbot-chat-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsbot-ai/openapi/docsbot-ai-docsbot-chat-api-api-openapi.yml
- filename: docsbot-ai-libraries-api-openapi.yml
  format: yaml
  label: docsbot-ai Libraries API
  slug: docsbot-ai-libraries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsbot-ai/openapi/docsbot-ai-libraries-api-openapi.yml
- filename: docsbot-ai-teams-api-openapi.yml
  format: yaml
  label: docsbot-ai Teams API
  slug: docsbot-ai-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsbot-ai/openapi/docsbot-ai-teams-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: Your Email Address is stored in Google Firebase Authentication and used for account access, security, and service communications, including password setup and reset.
  - category: identifying
    text: Accounts have a random userid assigned to them when they are created.
  - category: communication
    text: Customers that email us, use live chat, or use any of the contact forms on our websites, will have their email address, IP address, and any data provided in the contact form or body of the email stored in G Suite archives and in our help desk third-party service provider, HelpScout.
  - category: financial
    text: To comply with accounting and legal requirements, we keep data on financial transactions in the systems above for up to 10 years.
  - category: behavioral
    text: Emails sent to you may also include standard tracking, including open and click activities.
  - category: device
    text: These services may collect your IP Address, your User Agent, store and retrieve cookies on your browser, embed additional third-party tracking, and monitor your interaction with that embedded content
  deletion:
    route: email human@docsbot.ai or delete uploaded data in Dashboard
    text: You may have a right to request that we delete the personal information we hold about you at any time by emailing human@docsbot.ai .
  dpa:
    available: true
    text: The terms of the Data Processing Agreement (“DPA”) are hereby incorporated by reference and will apply to the extent any Customer Data includes Personal Data.
    url: null
  purposes:
  - purpose: account access and security
    text: used for account access, security, and service communications, including password setup and reset
  - purpose: support and service improvement
    text: We keep all email and chat communication indefinitely to help us provide support and improve our services.
  - purpose: marketing emails
    text: We use email marketing to communicate with customers and potential customers from time to time.
  - purpose: advertising measurement and ads
    text: We use optional advertising tools from Google and Meta to measure campaigns and make ads more relevant.
  residency:
  - region: multiple regions
    text: All web servers and hosting are managed by our team on Vercel, and Google Cloud platforms located in different regions around the world.
  retention:
  - period: two weeks
    scope: login cookies
    text: These cookies will persist for two weeks.
  - period: indefinitely
    scope: registered user profile data
    text: For users that register on one of our sites, we also store the data they provide in their profile indefinitely.
  - period: indefinitely
    scope: email and chat communication
    text: We keep all email and chat communication indefinitely to help us provide support and improve our services.
  - period: up to 10 years
    scope: financial transaction data
    text: we keep data on financial transactions in the systems above for up to 10 years.
  - period: 5 days
    scope: deleted account personal data
    text: If you terminate or delete your account, we will delete your personal information within 5 days of the deletion of your account.
  rights:
  - right: access
    text: If you are a registered user you can request to see or download the data we have about you.
  - right: deletion
    text: You can also request “to be forgotten” and we will erase any personally identifiable data we have about you.
  - right: restrict processing
    text: You have the right to request that we restrict the processing of your personal information
  - right: objection
    text: You have the right to object to processing of your personal information that is based on our legitimate interests or public interest.
  - right: portability
    text: You may have the right to request a copy of the personal information we hold about you.
  - right: opt out of optional advertising
    text: You can turn off optional advertising through Privacy preferences in the footer of docsbot.ai.
  role:
    text: We are a Data Controller with respect to the personal information you provide to us.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information for money. Disclosing website activity or matched customer identifiers to advertising partners for ads across other websites may be considered “sharing” under California law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: standard data protection clauses approved by the European Commission
  - mechanism: BCR
    text: the use of binding corporate rules or other legally accepted means
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: docsbot-ai
provenance_date: '2026-11-09'
provider_name: docsbot-ai
provider_slug: docsbot-ai
slug: docsbot-ai-privacy-policy
source_date: '2026-11-09'
source_filename: docsbot-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docsbot.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: docsbot-ai\naid: docsbot-ai\nurl: https://docsbot.ai/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are a Data Controller with respect to the personal information you provide to us.\ndata_categories:\n- category: contact\n  text: Your Email Address is stored in Google Firebase Authentication and used for account access, security, and\n    service communications, including password setup and reset.\n- category: identifying\n  text: Accounts have a random userid assigned to them when they are created.\n- category: communication\n  text: Customers that email us, use live\
  \ chat, or use any of the contact forms on our websites, will have their\n    email address, IP address, and any data provided in the contact form or body of the email stored in G Suite\n    archives and in our help desk third-party service provider, HelpScout.\n- category: financial\n  text: To comply with accounting and legal requirements, we keep data on financial transactions in the systems\n    above for up to 10 years.\n- category: behavioral\n  text: Emails sent to you may also include standard tracking, including open and click activities.\n- category: device\n  text: These services may collect your IP Address, your User Agent, store and retrieve cookies on your browser,\n    embed additional third-party tracking, and monitor your interaction with that embedded content\npurposes:\n- purpose: account access and security\n  text: used for account access, security, and service communications, including password setup and reset\n- purpose: support and service improvement\n  text: We\
  \ keep all email and chat communication indefinitely to help us provide support and improve our services.\n- purpose: marketing emails\n  text: We use email marketing to communicate with customers and potential customers from time to time.\n- purpose: advertising measurement and ads\n  text: We use optional advertising tools from Google and Meta to measure campaigns and make ads more relevant.\nretention:\n- scope: login cookies\n  period: two weeks\n  text: These cookies will persist for two weeks.\n- scope: registered user profile data\n  period: indefinitely\n  text: For users that register on one of our sites, we also store the data they provide in their profile indefinitely.\n- scope: email and chat communication\n  period: indefinitely\n  text: We keep all email and chat communication indefinitely to help us provide support and improve our services.\n- scope: financial transaction data\n  period: up to 10 years\n  text: we keep data on financial transactions in the systems above\
  \ for up to 10 years.\n- scope: deleted account personal data\n  period: 5 days\n  text: If you terminate or delete your account, we will delete your personal information within 5 days of the deletion\n    of your account.\nresidency:\n- region: multiple regions\n  text: All web servers and hosting are managed by our team on Vercel, and Google Cloud platforms located in different\n    regions around the world.\ntransfers:\n- mechanism: SCC\n  text: standard data protection clauses approved by the European Commission\n- mechanism: BCR\n  text: the use of binding corporate rules or other legally accepted means\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: The terms of the Data Processing Agreement (“DPA”) are hereby incorporated by reference and will apply to\n    the extent any Customer Data includes Personal Data.\ndeletion:\n  route: email human@docsbot.ai or delete uploaded data in Dashboard\n  text: You may have a right to request that we\
  \ delete the personal information we hold about you at any time by\n    emailing human@docsbot.ai .\nrights:\n- right: access\n  text: If you are a registered user you can request to see or download the data we have about you.\n- right: deletion\n  text: You can also request “to be forgotten” and we will erase any personally identifiable data we have about\n    you.\n- right: restrict processing\n  text: You have the right to request that we restrict the processing of your personal information\n- right: objection\n  text: You have the right to object to processing of your personal information that is based on our legitimate\n    interests or public interest.\n- right: portability\n  text: You may have the right to request a copy of the personal information we hold about you.\n- right: opt out of optional advertising\n  text: You can turn off optional advertising through Privacy preferences in the footer of docsbot.ai.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal\
  \ information for money. Disclosing website activity or matched customer identifiers\n    to advertising partners for ads across other websites may be considered “sharing” under California law.\n"
source_yaml_url: https://artifacts.apis.io/docsbot-ai/privacy/docsbot-ai-privacy-policy.yml
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
summary_line: 28 quoted statements, read from docsbot-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Chatbots
- Automation
- Customer Service
---
