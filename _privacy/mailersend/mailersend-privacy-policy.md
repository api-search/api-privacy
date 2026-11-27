---
api_specs:
- filename: mailersend-bulk-email-api-openapi.yml
  format: yaml
  label: MailerSend Bulk Email API
  slug: mailersend-bulk-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailersend/openapi/mailersend-bulk-email-api-openapi.yml
- filename: mailersend-domains-api-openapi.yml
  format: yaml
  label: MailerSend Domains API
  slug: mailersend-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailersend/openapi/mailersend-domains-api-openapi.yml
- filename: mailersend-email-api-openapi.yml
  format: yaml
  label: MailerSend Email API
  slug: mailersend-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailersend/openapi/mailersend-email-api-openapi.yml
- filename: mailersend-messages-api-openapi.yml
  format: yaml
  label: MailerSend Messages API
  slug: mailersend-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailersend/openapi/mailersend-messages-api-openapi.yml
- filename: mailersend-sender-identities-api-openapi.yml
  format: yaml
  label: MailerSend Sender Identities API
  slug: mailersend-sender-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailersend/openapi/mailersend-sender-identities-api-openapi.yml
- filename: mailersend-templates-api-openapi.yml
  format: yaml
  label: MailerSend Templates API
  slug: mailersend-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailersend/openapi/mailersend-templates-api-openapi.yml
- filename: mailersend-webhooks-api-openapi.yml
  format: yaml
  label: MailerSend Webhooks API
  slug: mailersend-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailersend/openapi/mailersend-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: identification and contact data (legal name, contact details (email), name of the representative
  - category: financial
    text: billing information (billing address, PayPal account details, payment information)
  - category: device
    text: IT information (IP addresses, usage data, cookies data, online navigation data, location data, browser data)
  - category: behavioral
    text: location and online behavioral data (such as information about your use of social media websites, page view information and search results and links)
  - category: communication
    text: 'Data Subject information: email address, IP, location data, phone number, device data'
  deletion:
    route: Email request to info@mailersend.com or account settings
    text: If you are not able to exercise these rights through your MailerSend account, please contact us via email at info@mailersend.com.
  dpa:
    available: true
    text: We created our Data Processing Addendum to cover the GDPR requirements as they relate to cloud-based transactional communications software services
    url: null
  purposes:
  - purpose: operate and improve the Services
    text: MailerSend uses collected information to operate and improve the Services, maintain quality, analyze usage, provide statistics and customer support, verify identity and send relevant information.
  - purpose: marketing communications
    text: 'we may send customized informational or promotional content to our Customers: Based on your marketing preferences, where you have provided consent.'
  - purpose: product analytics and A/B testing
    text: MailerSend utilizes PostHog to analyze product usage and perform A/B testing.
  residency:
  - region: European Union
    text: Our data storage centers are in the European Union and have an information storage security certificate (ISO 27001)
  retention:
  - period: 30 days
    scope: Personal Data after deletion request
    text: In case you request the deletion of your Personal Data, it will be effective within the next 30 days
  - period: 2 years or more
    scope: Inactive accounts
    text: If your account is inactive for 2 years or more, MailerSend reserves the right to permanently delete your account with all its data
  - period: 6 months
    scope: Unapproved or rejected accounts
    text: If your account was never approved, or was suspended or rejected, and you did not sign in to your account or send emails within the last 6 months, your account will be fully deleted.
  rights:
  - right: Access
    text: Right to Access . You have the right to request disclosure of the specific pieces of your Personal Data we have collected about you in a portable and, where technically feasible, readily usable format.
  - right: Deletion
    text: Right to Deletion. You may request the deletion of your Personal Data in accordance with Clause 11 of this Privacy Policy.
  - right: Correction
    text: Right to correct your Personal Data. You have the right to update inaccurate information that we process about you by amending it in your MailerSend account.
  - right: Object to processing
    text: Right to object to the processing of your Personal Data, including profiling.
  - right: Opt-out of sharing
    text: Right to Opt-Out. You have the right to opt-out of sharing your Personal Data for cross-context behavioral advertising to third parties.
  - right: Non-discrimination
    text: Right to exercise rights without discrimination. You have the right not to receive discriminatory treatment if you exercise the rights conferred to you by applicable privacy law.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never sell, rent, or lease your Personal Data to a third party
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: MailerSend, Inc. operates in accordance with the EU-U.S. and Swiss-U.S. Data Privacy Frameworks (DPF), as well as the UK Extension to the EU-U.S. DPF
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MailerSend
provenance_date: '2026-11-10'
provider_name: MailerSend
provider_slug: mailersend
slug: mailersend-privacy-policy
source_date: '2026-11-10'
source_filename: mailersend-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mailersend.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MailerSend\naid: mailersend\nurl: https://www.mailersend.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: identification and contact data (legal name, contact details (email), name of the representative\n- category: financial\n  text: billing information (billing address, PayPal account details, payment information)\n- category: device\n  text: IT information (IP addresses, usage data, cookies data, online navigation data, location data, browser data)\n- category: behavioral\n  text: location and online behavioral\
  \ data (such as information about your use of social media websites, page view\n    information and search results and links)\n- category: communication\n  text: 'Data Subject information: email address, IP, location data, phone number, device data'\npurposes:\n- purpose: operate and improve the Services\n  text: MailerSend uses collected information to operate and improve the Services, maintain quality, analyze usage,\n    provide statistics and customer support, verify identity and send relevant information.\n- purpose: marketing communications\n  text: 'we may send customized informational or promotional content to our Customers: Based on your marketing preferences,\n    where you have provided consent.'\n- purpose: product analytics and A/B testing\n  text: MailerSend utilizes PostHog to analyze product usage and perform A/B testing.\nretention:\n- scope: Personal Data after deletion request\n  period: 30 days\n  text: In case you request the deletion of your Personal Data, it will\
  \ be effective within the next 30 days\n- scope: Inactive accounts\n  period: 2 years or more\n  text: If your account is inactive for 2 years or more, MailerSend reserves the right to permanently delete your\n    account with all its data\n- scope: Unapproved or rejected accounts\n  period: 6 months\n  text: If your account was never approved, or was suspended or rejected, and you did not sign in to your account\n    or send emails within the last 6 months, your account will be fully deleted.\nresidency:\n- region: European Union\n  text: Our data storage centers are in the European Union and have an information storage security certificate\n    (ISO 27001)\ntransfers:\n- mechanism: DPF\n  text: MailerSend, Inc. operates in accordance with the EU-U.S. and Swiss-U.S. Data Privacy Frameworks (DPF), as\n    well as the UK Extension to the EU-U.S. DPF\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We created our Data Processing Addendum to cover\
  \ the GDPR requirements as they relate to cloud-based transactional\n    communications software services\ndeletion:\n  route: Email request to info@mailersend.com or account settings\n  text: If you are not able to exercise these rights through your MailerSend account, please contact us via email\n    at info@mailersend.com.\nrights:\n- right: Access\n  text: Right to Access . You have the right to request disclosure of the specific pieces of your Personal Data\n    we have collected about you in a portable and, where technically feasible, readily usable format.\n- right: Deletion\n  text: Right to Deletion. You may request the deletion of your Personal Data in accordance with Clause 11 of this\n    Privacy Policy.\n- right: Correction\n  text: Right to correct your Personal Data. You have the right to update inaccurate information that we process\n    about you by amending it in your MailerSend account.\n- right: Object to processing\n  text: Right to object to the processing of your\
  \ Personal Data, including profiling.\n- right: Opt-out of sharing\n  text: Right to Opt-Out. You have the right to opt-out of sharing your Personal Data for cross-context behavioral\n    advertising to third parties.\n- right: Non-discrimination\n  text: Right to exercise rights without discrimination. You have the right not to receive discriminatory treatment\n    if you exercise the rights conferred to you by applicable privacy law.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell, rent, or lease your Personal Data to a third party\n"
source_yaml_url: https://artifacts.apis.io/mailersend/privacy/mailersend-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from MailerSend's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Transactional Email
- SMTP
- Marketing
- Communications
- SMS
- Messaging
- Templates
- Webhook
- Email Verification
- Deliverability
- Analytics
- MCP
---
