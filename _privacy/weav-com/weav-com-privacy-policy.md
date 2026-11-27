---
api_specs:
- filename: weav-com-openapi-generated.yml
  format: yaml
  label: weav-com API
  slug: weav-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weav-com/openapi/_ae-authored/weav-com-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, profile/avatar, and (where applicable) identity information provided through our authentication provider (e.g., WorkOS).
  - category: contact
    text: Name, email address, phone number (if provided), and other identifiers you or the workspace associate with you.
  - category: financial
    text: Billing address, payment method details (processed by our payment providers), and information needed for invoicing.
  - category: device
    text: IP address, browser type, device information, and how you use the Sites and application (e.g., pages visited, features used).
  - category: communication
    text: Message content, attachments, channel (e.g., chat, email), and related metadata (e.g., timestamps, assignee).
  - category: behavioral
    text: Analytics cookies (e.g., Fathom Analytics) and advertising-related technologies (e.g., Google Ads) to improve our Sites and for marketing.
  deletion:
    route: Contact privacy@weav.com
    text: To exercise these rights, contact us at privacy@weav.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Weav platform
    text: Provide the Weav platform – Account and workspace management, authentication, AI and inbox features, and support.
  - purpose: Process payments and billing
    text: Process payments and billing – Usage-based billing, invoicing, and payment processing (via our billing and payment providers).
  - purpose: Communicate with you
    text: Communicate with you – Service-related and security messages; with your consent or where permitted, marketing.
  - purpose: Improve and secure services
    text: Improve and secure our services – Analytics, troubleshooting, security, fraud prevention, and compliance with law.
  residency:
  - region: United States
    text: Our systems and subprocessors store and process data in the United States, including in AWS data centers (e.g., us-east-1 and us-east-2).
  retention:
  - period: 90 days
    scope: User Data after subscription end
    text: We retain User Data for 90 days following cancellation or termination of the subscription, regardless of payment status, except where retention is required by law or for legitimate business purposes.
  - period: null
    scope: Workspace data
    text: We retain personal data for as long as the relevant workspace exists and as needed to provide the service, comply with law, resolve disputes, and enforce our agreements.
  rights:
  - right: Access and correction
    text: 'Access and correction: You may request access to or correction of your personal data by contacting us.'
  - right: Erase and restrict/object (GDPR)
    text: Access, rectify, or erase your personal data Restrict or object to certain processing Data portability Withdraw consent where processing is based on consent
  - right: Delete (CCPA)
    text: Delete your personal information
  - right: Opt out of marketing
    text: 'Marketing: You may opt out of marketing emails via the link in our emails or by contacting us.'
  role:
    text: The workspace owner is the data controller for Customer data; we process it as a service provider to deliver and operate the platform.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information for monetary compensation.
  subprocessors:
    text: 'We may share data with the following service providers (subprocessors): WorkOS – Authentication and organization management'
    url: null
  transfers:
  - mechanism: SCC
    text: standard contractual clauses, adequacy decisions, or other approved mechanisms where required by applicable law
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: weav-com
provenance_date: '2026-11-10'
provider_name: weav-com
provider_slug: weav-com
slug: weav-com-privacy-policy
source_date: '2026-11-10'
source_filename: weav-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://weav.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: weav-com\naid: weav-com\nurl: https://weav.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The workspace owner is the data controller for Customer data; we process it as a service provider to deliver\n    and operate the platform.\ndata_categories:\n- category: identifying\n  text: Name, email address, profile/avatar, and (where applicable) identity information provided through our authentication\n    provider (e.g., WorkOS).\n- category: contact\n  text: Name, email address, phone number (if provided), and other identifiers you or the workspace associate with\n    you.\n- category: financial\n\
  \  text: Billing address, payment method details (processed by our payment providers), and information needed for\n    invoicing.\n- category: device\n  text: IP address, browser type, device information, and how you use the Sites and application (e.g., pages visited,\n    features used).\n- category: communication\n  text: Message content, attachments, channel (e.g., chat, email), and related metadata (e.g., timestamps, assignee).\n- category: behavioral\n  text: Analytics cookies (e.g., Fathom Analytics) and advertising-related technologies (e.g., Google Ads) to improve\n    our Sites and for marketing.\npurposes:\n- purpose: Provide the Weav platform\n  text: Provide the Weav platform – Account and workspace management, authentication, AI and inbox features, and\n    support.\n- purpose: Process payments and billing\n  text: Process payments and billing – Usage-based billing, invoicing, and payment processing (via our billing and\n    payment providers).\n- purpose: Communicate with\
  \ you\n  text: Communicate with you – Service-related and security messages; with your consent or where permitted, marketing.\n- purpose: Improve and secure services\n  text: Improve and secure our services – Analytics, troubleshooting, security, fraud prevention, and compliance\n    with law.\nretention:\n- scope: User Data after subscription end\n  period: 90 days\n  text: We retain User Data for 90 days following cancellation or termination of the subscription, regardless of\n    payment status, except where retention is required by law or for legitimate business purposes.\n- scope: Workspace data\n  period: null\n  text: We retain personal data for as long as the relevant workspace exists and as needed to provide the service,\n    comply with law, resolve disputes, and enforce our agreements.\nresidency:\n- region: United States\n  text: Our systems and subprocessors store and process data in the United States, including in AWS data centers\n    (e.g., us-east-1 and us-east-2).\ntransfers:\n\
  - mechanism: SCC\n  text: standard contractual clauses, adequacy decisions, or other approved mechanisms where required by applicable\n    law\nsubprocessors:\n  url: null\n  text: 'We may share data with the following service providers (subprocessors): WorkOS – Authentication and organization\n    management'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@weav.com\n  text: To exercise these rights, contact us at privacy@weav.com.\nrights:\n- right: Access and correction\n  text: 'Access and correction: You may request access to or correction of your personal data by contacting us.'\n- right: Erase and restrict/object (GDPR)\n  text: Access, rectify, or erase your personal data Restrict or object to certain processing Data portability Withdraw\n    consent where processing is based on consent\n- right: Delete (CCPA)\n  text: Delete your personal information\n- right: Opt out of marketing\n  text: 'Marketing: You may opt out of marketing emails\
  \ via the link in our emails or by contacting us.'\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal information for monetary compensation.\n"
source_yaml_url: https://artifacts.apis.io/weav-com/privacy/weav-com-privacy-policy.yml
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
summary_line: 22 quoted statements, read from weav-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Customer Service
- Automation
- Software-as-a-Service
- Chatbots
---
