---
api_specs:
- filename: beancount-io-ledger-api-openapi.yml
  format: yaml
  label: Beancount.io Ledger API
  slug: beancount-io-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beancount-io/openapi/beancount-io-ledger-api-openapi.yml
- filename: beancount-io-mcp-api-openapi.yml
  format: yaml
  label: Beancount.io MCP API
  slug: beancount-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beancount-io/openapi/beancount-io-mcp-api-openapi.yml
- filename: beancount-io-graph-ql-api-openapi.yml
  format: yaml
  label: Beancount.io Graph QL API
  slug: beancount-io-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beancount-io/openapi/beancount-io-graph-ql-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: This information includes personally identifiable information such as your name, username, e-mail address, password, and phone numbers.
  - category: contact
    text: we collect the information you provide in the applicable form
  - category: device
    text: This also includes server log data such as the IP address, device type, or operating system
  - category: behavioral
    text: usage information of the Service, such as information on when, how often and for how long you use the Service
  - category: financial
    text: Ledger file contents (complete accounting records including accounts, transactions, balances)
  - category: financial
    text: We do not store account balances.
  - category: communication
    text: Chat conversation history (all messages in your AI chat sessions)
  - category: health
    text: sensitive personal information
  deletion:
    route: Delete account in account settings; records marked not yet deleted are erased on email request
    text: You can delete your account at any time in your account settings. Deletion is immediate
  dpa:
    available: false
    text: we do not currently have a separate Data Processing Agreement (DPA) with Anthropic.
    url: null
  purposes:
  - purpose: Provide the Service and account features
    text: We will use submitted information for the purposes for which you provided the information, including, for example, to create and maintain a Service account for you
  - purpose: AI features
    text: We use AI services (Claude API from Anthropic) to provide intelligent features including chat assistance, document parsing, and transaction categorization.
  - purpose: Analytics
    text: We may analyze collected information relating to your use of the Service in order to help us improve the Service.
  - purpose: Legal compliance and protection
    text: to investigate, prevent, or take action regarding illegal activities, suspected fraud, or violations of our terms and conditions
  residency:
  - region: United States
    text: Your information will be stored and processed in the United States or other countries where Company has facilities.
  retention:
  - period: null
    scope: AI chat conversations
    text: We do not store your AI chat conversations on our servers
  - period: 30 days
    scope: AI provider API inputs and outputs
    text: API inputs and outputs are retained for up to 30 days for trust and safety monitoring
  - period: 90 days
    scope: Activity (audit) records
    text: These records are kept for 90 days.
  - period: Up to one year
    scope: Sign-in sessions
    text: Up to one year; expired sessions are deleted daily
  - period: Until you delete your account
    scope: Account profile
    text: Until you delete your account
  rights:
  - right: Right to Know
    text: You can request disclosure of the categories and specific pieces of personal information we have collected
  - right: Right to Delete
    text: You can request deletion of your personal information, subject to certain exceptions.
  - right: Right to Correct
    text: You can request correction of inaccurate personal information.
  - right: Right to Opt-Out of Sharing
    text: You can opt out of sharing your personal information with third parties by choosing not to use AI-powered features.
  - right: Right to Non-Discrimination
    text: We will not discriminate against you for exercising your CCPA rights.
  - right: Right to withdraw consent
    text: Right to withdraw consent at any time
  role:
    text: This Privacy Policy (“Policy”) describes how Stargately, Inc. (“Company” or “we” or “our”) treats information collected or provided
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell or distribute your information to third parties for their own purposes, in any form except as provided in this Section.
  subprocessors:
    text: 'We share information only with the following recipients, for the purposes stated: Recipient Purpose Anthropic In-product AI features'
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on Anthropic's Standard Contractual Clauses and security measures to protect your data during international transfers.
  - mechanism: other
    text: By using the Service, you consent to the transfer of information outside of your country, even if your country has more rigorous data protection standards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Beancount.io
provenance_date: '2026-11-09'
provider_name: Beancount.io
provider_slug: beancount-io
slug: beancount-io-privacy-policy
source_date: '2026-11-09'
source_filename: beancount-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://beancount.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Beancount.io\naid: beancount-io\nurl: https://beancount.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy (“Policy”) describes how Stargately, Inc. (“Company” or “we” or “our”) treats information\n    collected or provided\ndata_categories:\n- category: identifying\n  text: This information includes personally identifiable information such as your name, username, e-mail address,\n    password, and phone numbers.\n- category: contact\n  text: we collect the information you provide in the applicable form\n- category: device\n  text: This also includes server\
  \ log data such as the IP address, device type, or operating system\n- category: behavioral\n  text: usage information of the Service, such as information on when, how often and for how long you use the Service\n- category: financial\n  text: Ledger file contents (complete accounting records including accounts, transactions, balances)\n- category: financial\n  text: We do not store account balances.\n- category: communication\n  text: Chat conversation history (all messages in your AI chat sessions)\n- category: health\n  text: sensitive personal information\npurposes:\n- purpose: Provide the Service and account features\n  text: We will use submitted information for the purposes for which you provided the information, including, for\n    example, to create and maintain a Service account for you\n- purpose: AI features\n  text: We use AI services (Claude API from Anthropic) to provide intelligent features including chat assistance,\n    document parsing, and transaction categorization.\n\
  - purpose: Analytics\n  text: We may analyze collected information relating to your use of the Service in order to help us improve the\n    Service.\n- purpose: Legal compliance and protection\n  text: to investigate, prevent, or take action regarding illegal activities, suspected fraud, or violations of\n    our terms and conditions\nretention:\n- scope: AI chat conversations\n  period: null\n  text: We do not store your AI chat conversations on our servers\n- scope: AI provider API inputs and outputs\n  period: 30 days\n  text: API inputs and outputs are retained for up to 30 days for trust and safety monitoring\n- scope: Activity (audit) records\n  period: 90 days\n  text: These records are kept for 90 days.\n- scope: Sign-in sessions\n  period: Up to one year\n  text: Up to one year; expired sessions are deleted daily\n- scope: Account profile\n  period: Until you delete your account\n  text: Until you delete your account\nresidency:\n- region: United States\n  text: Your information\
  \ will be stored and processed in the United States or other countries where Company has\n    facilities.\ntransfers:\n- mechanism: SCC\n  text: We rely on Anthropic's Standard Contractual Clauses and security measures to protect your data during international\n    transfers.\n- mechanism: other\n  text: By using the Service, you consent to the transfer of information outside of your country, even if your country\n    has more rigorous data protection standards.\nsubprocessors:\n  url: null\n  text: 'We share information only with the following recipients, for the purposes stated: Recipient Purpose Anthropic\n    In-product AI features'\ndpa:\n  available: false\n  url: null\n  text: we do not currently have a separate Data Processing Agreement (DPA) with Anthropic.\ndeletion:\n  route: Delete account in account settings; records marked not yet deleted are erased on email request\n  text: You can delete your account at any time in your account settings. Deletion is immediate\nrights:\n\
  - right: Right to Know\n  text: You can request disclosure of the categories and specific pieces of personal information we have collected\n- right: Right to Delete\n  text: You can request deletion of your personal information, subject to certain exceptions.\n- right: Right to Correct\n  text: You can request correction of inaccurate personal information.\n- right: Right to Opt-Out of Sharing\n  text: You can opt out of sharing your personal information with third parties by choosing not to use AI-powered\n    features.\n- right: Right to Non-Discrimination\n  text: We will not discriminate against you for exercising your CCPA rights.\n- right: Right to withdraw consent\n  text: Right to withdraw consent at any time\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell or distribute your information to third parties for their own purposes, in any form except\n    as provided in this Section.\n"
source_yaml_url: https://artifacts.apis.io/beancount-io/privacy/beancount-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from Beancount.io's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Finance
- Software-as-a-Service
- Open Source
- Collaboration
---
