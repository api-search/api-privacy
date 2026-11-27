---
api_specs:
- filename: paubox-analytics-api-openapi.yml
  format: yaml
  label: Paubox Analytics API
  slug: paubox-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-analytics-api-openapi.yml
- filename: paubox-campaign-mailings-api-openapi.yml
  format: yaml
  label: Paubox Campaign Mailings API
  slug: paubox-campaign-mailings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-campaign-mailings-api-openapi.yml
- filename: paubox-drip-campaigns-api-openapi.yml
  format: yaml
  label: Paubox Drip Campaigns API
  slug: paubox-drip-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-drip-campaigns-api-openapi.yml
- filename: paubox-dynamic-templates-api-openapi.yml
  format: yaml
  label: Paubox Dynamic Templates API
  slug: paubox-dynamic-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-dynamic-templates-api-openapi.yml
- filename: paubox-form-management-api-openapi.yml
  format: yaml
  label: Paubox Form management API
  slug: paubox-form-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-form-management-api-openapi.yml
- filename: paubox-forms-api-openapi.yml
  format: yaml
  label: Paubox Forms API
  slug: paubox-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-forms-api-openapi.yml
- filename: paubox-messages-api-openapi.yml
  format: yaml
  label: Paubox Messages API
  slug: paubox-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-messages-api-openapi.yml
- filename: paubox-submissions-api-openapi.yml
  format: yaml
  label: Paubox Submissions API
  slug: paubox-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-submissions-api-openapi.yml
- filename: paubox-subscribers-api-openapi.yml
  format: yaml
  label: Paubox Subscribers API
  slug: paubox-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscribers-api-openapi.yml
- filename: paubox-subscription-lists-api-openapi.yml
  format: yaml
  label: Paubox Subscription Lists API
  slug: paubox-subscription-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscription-lists-api-openapi.yml
- filename: paubox-subscriptions-api-openapi.yml
  format: yaml
  label: Paubox Subscriptions API
  slug: paubox-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscriptions-api-openapi.yml
- filename: paubox-tracking-links-api-openapi.yml
  format: yaml
  label: Paubox Tracking Links API
  slug: paubox-tracking-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-tracking-links-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect your first and last name, email address, postal address, phone number, job title, and other similar contact data.
  - category: identifying
    text: We collect passwords, password hints, and similar security information used for authentication and account access.
  - category: financial
    text: We collect data necessary to process your payment if you make purchases, such as your payment instrument number (such as a credit card number)
  - category: device
    text: may include device and usage information, such as your IP address, browser and device characteristics, operating system
  - category: behavioral
    text: information about how and when you use our Sites and other technical information
  deletion:
    route: Account termination request to support@paubox.com
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and logon
    text: To facilitate account creation and logon process with your Consent.
  - purpose: Order fulfilment
    text: Fulfill and manage your orders for Contractual reasons.
  - purpose: Targeted advertising
    text: Deliver targeted advertising to you for our Business Purposes and/or with your Consent.
  - purpose: Site security
    text: To protect our Sites for Business Purposes and/or for Legal Reasons.
  residency:
  - region: United States
    text: Our servers are located in the United States.
  retention:
  - period: 90 days
    scope: After account termination
    text: No purpose in this policy will require us keeping your personal information for longer than 90 days past the termination of the user’s account.
  rights:
  - right: Access
    text: (i) to request access and obtain a copy of your personal information
  - right: Rectification or erasure
    text: (ii) to request rectification or erasure
  - right: Restriction of processing
    text: (iii) to restrict the processing of your personal information
  - right: Data portability
    text: (iv) if applicable, to data portability
  - right: Objection
    text: you may also have the right to object to the processing of your personal information
  - right: Withdraw consent
    text: If we are relying on your consent to process your personal information, you have the right to withdraw your consent at any time.
  role:
    text: Depending on the context of the personal information you provide, Paubox may be the data controller (“Controller”) or data processor (“Processor”) of your personal information under this policy.
    value: both
  sale_or_sharing:
    stance: conditional
    text: we do not share, sell, rent or trade any of your information with third parties for their promotional purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Paubox
provenance_date: '2026-11-10'
provider_name: Paubox
provider_slug: paubox
slug: paubox-privacy-policy
source_date: '2026-11-10'
source_filename: paubox-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.paubox.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Paubox\naid: paubox\nurl: https://www.paubox.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Depending on the context of the personal information you provide, Paubox may be the data controller (“Controller”)\n    or data processor (“Processor”) of your personal information under this policy.\ndata_categories:\n- category: contact\n  text: We collect your first and last name, email address, postal address, phone number, job title, and other similar\n    contact data.\n- category: identifying\n  text: We collect passwords, password hints, and similar security information used for\
  \ authentication and account\n    access.\n- category: financial\n  text: We collect data necessary to process your payment if you make purchases, such as your payment instrument\n    number (such as a credit card number)\n- category: device\n  text: may include device and usage information, such as your IP address, browser and device characteristics, operating\n    system\n- category: behavioral\n  text: information about how and when you use our Sites and other technical information\npurposes:\n- purpose: Account creation and logon\n  text: To facilitate account creation and logon process with your Consent.\n- purpose: Order fulfilment\n  text: Fulfill and manage your orders for Contractual reasons.\n- purpose: Targeted advertising\n  text: Deliver targeted advertising to you for our Business Purposes and/or with your Consent.\n- purpose: Site security\n  text: To protect our Sites for Business Purposes and/or for Legal Reasons.\nretention:\n- scope: After account termination\n  period:\
  \ 90 days\n  text: No purpose in this policy will require us keeping your personal information for longer than 90 days past\n    the termination of the user’s account.\nresidency:\n- region: United States\n  text: Our servers are located in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account termination request to support@paubox.com\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: Access\n  text: (i) to request access and obtain a copy of your personal information\n- right: Rectification or erasure\n  text: (ii) to request rectification or erasure\n- right: Restriction of processing\n  text: (iii) to restrict the processing of your personal information\n- right: Data portability\n  text: (iv) if applicable, to data portability\n- right: Objection\n  text: you may also have\
  \ the right to object to the processing of your personal information\n- right: Withdraw consent\n  text: If we are relying on your consent to process your personal information, you have the right to withdraw your\n    consent at any time.\nsale_or_sharing:\n  stance: conditional\n  text: we do not share, sell, rent or trade any of your information with third parties for their promotional purposes.\n"
source_yaml_url: https://artifacts.apis.io/paubox/privacy/paubox-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Paubox's own page on 2026-11-10.
synthetic: false
tags:
- Email
- HIPAA
- Healthcare
- Compliance
- Transactional Email
- Email Marketing
- Forms
- Security
- Encryption
- Messaging
- A2A
---
