---
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, password, phone number (optional)'
  - category: contact
    text: Email addresses and phone numbers
  - category: financial
    text: 'Payment Information: Billing address, payment method (processed by Stripe)'
  - category: device
    text: 'Device Information: Device type, operating system, browser type'
  - category: location
    text: 'IP Address: Your internet protocol address (used for security and audit trails)'
  - category: behavioral
    text: 'Usage Data: Pages visited, features used, time spent, click patterns'
  - category: communication
    text: 'Communications: Messages you send us via email or support channels'
  - category: professional
    text: 'Profile Information: Company name, job title (optional)'
  deletion:
    route: Settings > Delete Account or email support@addsign.io
    text: You can delete your account through your account settings (Settings > Delete Account) or by contacting us at support@addsign.io.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Process payments and prevent fraud
    text: Process payments and prevent fraud
  - purpose: Transactional emails
    text: Send transactional emails (signature requests, confirmations, reminders)
  - purpose: Analytics to improve user experience
    text: Analyze usage patterns to improve user experience
  - purpose: Legal obligations
    text: Comply with legal obligations
  retention:
  - period: 30 days
    scope: Account data
    text: 'Account Data: Retained while your account is active and for 30 days after deletion'
  - period: 7 years
    scope: Signed documents
    text: 'Signed Documents: Retained for a minimum of 7 years for legal compliance'
  - period: 7 years
    scope: Audit logs
    text: 'Audit Logs: Retained for 7 years (required for electronic signature validity)'
  - period: 30 days
    scope: Deleted documents
    text: 'Deleted Documents: Moved to trash for 30 days, then permanently deleted'
  - period: 90 days
    scope: Assistant conversations
    text: 'Assistant Conversations: Questions you ask the in-app assistant, and its replies, are retained for 90 days and deleted with your account'
  - period: 90 days
    scope: Server logs
    text: 'Server Logs: Retained for 90 days'
  rights:
  - right: Access and portability
    text: You can access your documents and account information through the Service.
  - right: Correction
    text: You can update your account information through your profile settings.
  - right: Deletion
    text: You can delete your account through your account settings (Settings > Delete Account) or by contacting us at support@addsign.io.
  - right: Marketing opt-out
    text: You can unsubscribe from marketing emails using the link in any marketing email.
  - right: California (CCPA) rights
    text: California residents have additional rights under the California Consumer Privacy Act, including the right to know what personal information we collect and the right to non-discrimination for exercising privacy rights.
  - right: GDPR rights
    text: If you are in the European Economic Area, you have additional rights under GDPR, including the right to lodge a complaint with a supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do NOT sell your personal information.
  subprocessors:
    text: 'Supabase: Database, authentication, and file storage (data encrypted at rest)'
    url: null
  transfers:
  - mechanism: other
    text: Your information may be transferred to and processed in countries other than your own. We ensure appropriate safeguards are in place to protect your information in accordance with applicable data protection laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AddSign
provenance_date: '2026-11-09'
provider_name: AddSign
provider_slug: addsign-io
slug: addsign-io-privacy-policy
source_date: '2026-11-09'
source_filename: addsign-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://addsign.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AddSign\naid: addsign-io\nurl: https://addsign.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, password, phone number (optional)'\n- category: contact\n  text: Email addresses and phone numbers\n- category: financial\n  text: 'Payment Information: Billing address, payment method (processed by Stripe)'\n- category: device\n  text: 'Device Information: Device type, operating system, browser type'\n- category: location\n  text: 'IP Address: Your internet protocol address (used for security\
  \ and audit trails)'\n- category: behavioral\n  text: 'Usage Data: Pages visited, features used, time spent, click patterns'\n- category: communication\n  text: 'Communications: Messages you send us via email or support channels'\n- category: professional\n  text: 'Profile Information: Company name, job title (optional)'\npurposes:\n- purpose: Provide and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Process payments and prevent fraud\n  text: Process payments and prevent fraud\n- purpose: Transactional emails\n  text: Send transactional emails (signature requests, confirmations, reminders)\n- purpose: Analytics to improve user experience\n  text: Analyze usage patterns to improve user experience\n- purpose: Legal obligations\n  text: Comply with legal obligations\nretention:\n- scope: Account data\n  period: 30 days\n  text: 'Account Data: Retained while your account is active and for 30 days after deletion'\n- scope: Signed documents\n  period: 7\
  \ years\n  text: 'Signed Documents: Retained for a minimum of 7 years for legal compliance'\n- scope: Audit logs\n  period: 7 years\n  text: 'Audit Logs: Retained for 7 years (required for electronic signature validity)'\n- scope: Deleted documents\n  period: 30 days\n  text: 'Deleted Documents: Moved to trash for 30 days, then permanently deleted'\n- scope: Assistant conversations\n  period: 90 days\n  text: 'Assistant Conversations: Questions you ask the in-app assistant, and its replies, are retained for 90 days\n    and deleted with your account'\n- scope: Server logs\n  period: 90 days\n  text: 'Server Logs: Retained for 90 days'\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may be transferred to and processed in countries other than your own. We ensure appropriate\n    safeguards are in place to protect your information in accordance with applicable data protection laws.\nsubprocessors:\n  url: null\n  text: 'Supabase: Database, authentication, and file\
  \ storage (data encrypted at rest)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings > Delete Account or email support@addsign.io\n  text: You can delete your account through your account settings (Settings > Delete Account) or by contacting us\n    at support@addsign.io.\nrights:\n- right: Access and portability\n  text: You can access your documents and account information through the Service.\n- right: Correction\n  text: You can update your account information through your profile settings.\n- right: Deletion\n  text: You can delete your account through your account settings (Settings > Delete Account) or by contacting us\n    at support@addsign.io.\n- right: Marketing opt-out\n  text: You can unsubscribe from marketing emails using the link in any marketing email.\n- right: California (CCPA) rights\n  text: California residents have additional rights under the California Consumer Privacy Act, including the right\n    to know what personal information\
  \ we collect and the right to non-discrimination for exercising privacy rights.\n- right: GDPR rights\n  text: If you are in the European Economic Area, you have additional rights under GDPR, including the right to\n    lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do NOT sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/addsign-io/privacy/addsign-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from AddSign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Small Business
- AI Document Analysis
- DocuSign Alternative
- Free Plan
---
