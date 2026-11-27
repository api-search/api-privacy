---
api_specs:
- filename: mailerlite-webhook-api-openapi.yml
  format: yaml
  label: MailerLite Webhook API
  slug: mailerlite-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailerlite/openapi/mailerlite-webhook-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: identification and contact data (name, contact details, username)
  - category: financial
    text: billing information (billing and mailing addresses, payment information)
  - category: device
    text: 'The browser and device information: location, device type, model, number, type of browser or operating system'
  - category: behavioral
    text: online behavioral data (such as information about your use of social media websites, page view information and search results and links)
  - category: contact
    text: 'Subscribers'' information: email address and any other additional information that Customer provides to MailerLite.'
  deletion:
    route: Account deletion via account settings, 'Forget Me' feature, or contacting MailerLite
    text: Unless you specifically request that we delete your account by deleting an account yourself, using the ‘Forget Me’ feature or by contacting us
  dpa:
    available: true
    text: We created our Data Processing Addendum to cover the GDPR requirements as they relate to email marketing and we encourage all our Customers to review it here .
    url: null
  purposes:
  - purpose: operate and improve the Services
    text: MailerLite uses collected information to operate and improve the Services, maintain quality, analyze usage, provide statistics and customer support, verify identity and send relevant information.
  - purpose: process payments
    text: process payments, and understand user demographics and preferences.
  - purpose: marketing communications
    text: Based on your marketing preferences, where you have provided consent.
  residency:
  - region: European Union
    text: Our data storage center is in the European Union and has information storage security certificate (ISO 27001)
  retention:
  - period: 30 days
    scope: Account deletion requested
    text: your data will be fully deleted or anonymized within 30 days from receiving an eligible request.
  - period: 3 years
    scope: Inactive or terminated accounts
    text: If your account is terminated or remains inactive for 3 years or more, MailerLite reserves the right to permanently delete the account and all its data
  - period: 7 years
    scope: Legally required billing and transaction records
    text: This information will be retained for 7 years, calculated from the time the account was terminated, suspended, disapproved, or otherwise ceased using the Services
  rights:
  - right: Access
    text: Right to Access . You have the right to request disclosure of the specific pieces of your Personal Data we have collected about you in a portable and, where technically feasible, readily usable format.
  - right: Deletion
    text: Right to Deletion. You may request the deletion of your Personal Data in accordance with Clause 11 of this Privacy Policy.
  - right: Correct
    text: Right to correct your Personal Data. You have the right to update inaccurate information that we process about you by amending it in your MailerLite account.
  - right: Object
    text: Right to object to the processing of your Personal Data. You have the right to object to the processing of your personal data, including profiling.
  - right: Opt-out of sharing
    text: Right to Opt-Out. You have the right to opt-out of sharing your Personal Data for cross-context behavioral advertising to third parties.
  role:
    text: We process Personal Data as a Processor on behalf of the Customer.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will never sell, rent, or lease your Personal Data to a third party
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: MailerLite, Inc. has certified to the Department of Commerce that it adheres to the Data Privacy Framework Principles.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MailerLite
provenance_date: '2026-11-10'
provider_name: MailerLite
provider_slug: mailerlite
slug: mailerlite-privacy-policy
source_date: '2026-11-10'
source_filename: mailerlite-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mailerlite.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MailerLite\naid: mailerlite\nurl: https://www.mailerlite.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We process Personal Data as a Processor on behalf of the Customer.\ndata_categories:\n- category: identifying\n  text: identification and contact data (name, contact details, username)\n- category: financial\n  text: billing information (billing and mailing addresses, payment information)\n- category: device\n  text: 'The browser and device information: location, device type, model, number, type of browser or operating\n    system'\n- category: behavioral\n  text: online\
  \ behavioral data (such as information about your use of social media websites, page view information\n    and search results and links)\n- category: contact\n  text: 'Subscribers'' information: email address and any other additional information that Customer provides to\n    MailerLite.'\npurposes:\n- purpose: operate and improve the Services\n  text: MailerLite uses collected information to operate and improve the Services, maintain quality, analyze usage,\n    provide statistics and customer support, verify identity and send relevant information.\n- purpose: process payments\n  text: process payments, and understand user demographics and preferences.\n- purpose: marketing communications\n  text: Based on your marketing preferences, where you have provided consent.\nretention:\n- scope: Account deletion requested\n  period: 30 days\n  text: your data will be fully deleted or anonymized within 30 days from receiving an eligible request.\n- scope: Inactive or terminated accounts\n  period:\
  \ 3 years\n  text: If your account is terminated or remains inactive for 3 years or more, MailerLite reserves the right to\n    permanently delete the account and all its data\n- scope: Legally required billing and transaction records\n  period: 7 years\n  text: This information will be retained for 7 years, calculated from the time the account was terminated, suspended,\n    disapproved, or otherwise ceased using the Services\nresidency:\n- region: European Union\n  text: Our data storage center is in the European Union and has information storage security certificate (ISO 27001)\ntransfers:\n- mechanism: DPF\n  text: MailerLite, Inc. has certified to the Department of Commerce that it adheres to the Data Privacy Framework\n    Principles.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We created our Data Processing Addendum to cover the GDPR requirements as they relate to email marketing\n    and we encourage all our Customers to review it here\
  \ .\ndeletion:\n  route: Account deletion via account settings, 'Forget Me' feature, or contacting MailerLite\n  text: Unless you specifically request that we delete your account by deleting an account yourself, using the ‘Forget\n    Me’ feature or by contacting us\nrights:\n- right: Access\n  text: Right to Access . You have the right to request disclosure of the specific pieces of your Personal Data\n    we have collected about you in a portable and, where technically feasible, readily usable format.\n- right: Deletion\n  text: Right to Deletion. You may request the deletion of your Personal Data in accordance with Clause 11 of this\n    Privacy Policy.\n- right: Correct\n  text: Right to correct your Personal Data. You have the right to update inaccurate information that we process\n    about you by amending it in your MailerLite account.\n- right: Object\n  text: Right to object to the processing of your Personal Data. You have the right to object to the processing\n    of your personal\
  \ data, including profiling.\n- right: Opt-out of sharing\n  text: Right to Opt-Out. You have the right to opt-out of sharing your Personal Data for cross-context behavioral\n    advertising to third parties.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell, rent, or lease your Personal Data to a third party\n"
source_yaml_url: https://artifacts.apis.io/mailerlite/privacy/mailerlite-privacy-policy.yml
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
summary_line: 22 quoted statements, read from MailerLite's own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- Automation
- Newsletters
- Subscribers
- Campaigns
- Webhook
- E-Commerce
- Segmentation
- Transactional Email
- MCP
- Email
---
