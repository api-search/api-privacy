---
api_specs:
- filename: mailbridgeapi-activity-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Activity API
  slug: mailbridgeapi-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-activity-api-openapi.yml
- filename: mailbridgeapi-compliance-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Compliance API
  slug: mailbridgeapi-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-compliance-api-openapi.yml
- filename: mailbridgeapi-mailbox-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Mailbox API
  slug: mailbridgeapi-mailbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-mailbox-api-openapi.yml
- filename: mailbridgeapi-receiving-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Receiving API
  slug: mailbridgeapi-receiving-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-receiving-api-openapi.yml
- filename: mailbridgeapi-sending-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Sending API
  slug: mailbridgeapi-sending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-sending-api-openapi.yml
- filename: mailbridgeapi-service-api-openapi.yml
  format: yaml
  label: MailBridgeAPI Service API
  slug: mailbridgeapi-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailbridgeapi/openapi/mailbridgeapi-service-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact requests include your name, email address, subject, message, language, page, timestamps, browser information and a pseudonymized network identifier.
  - category: behavioral
    text: 'Usage Data: Information on how the website is accessed and used (e.g., page views, site navigation patterns).'
  - category: communication
    text: Your messages, recent conversation context and selected public documentation are sent to OpenAI to generate replies
  deletion:
    route: Account deletion page or email to info@mailbridgeapi.com
    text: Account and data deletion requests can be made from the account deletion page or by contacting info@mailbridgeapi.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: Personal information is used to provide and maintain our service, including to monitor the usage of our service.
  - purpose: Communication and marketing
    text: To contact users with newsletters, marketing or promotional materials, and other information.
  - purpose: Improvements
    text: To improve and personalize the user experience.
  residency:
  - region: outside user jurisdiction
    text: Personal information may be transferred to — and maintained on — computers located outside of your state, province, country, or other governmental jurisdiction.
  retention:
  - period: null
    scope: Contact requests
    text: They are retained until removed by the operator and are not published in the knowledge base or sent to OpenAI by the contact form.
  - period: null
    scope: AI chat conversations
    text: Conversations are retained on the service server until removed by the operator; they are not added to the public knowledge base.
  - period: 30 days
    scope: OpenAI abuse-monitoring logs
    text: OpenAI may retain abuse-monitoring logs for up to 30 days under its API data controls.
  rights:
  - right: Access, update, delete
    text: Users can access, update, or delete their personal information.
  - right: Withdraw consent
    text: Users have the right to withdraw consent at any time where we rely on consent to process personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MailBridgeAPI
provenance_date: '2026-11-10'
provider_name: MailBridgeAPI
provider_slug: mailbridgeapi
slug: mailbridgeapi-privacy-policy
source_date: '2026-11-10'
source_filename: mailbridgeapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mailbridgeapi.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MailBridgeAPI\naid: mailbridgeapi\nurl: https://mailbridgeapi.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Contact requests include your name, email address, subject, message, language, page, timestamps, browser\n    information and a pseudonymized network identifier.\n- category: behavioral\n  text: 'Usage Data: Information on how the website is accessed and used (e.g., page views, site navigation patterns).'\n- category: communication\n  text: Your messages, recent conversation context and selected public documentation\
  \ are sent to OpenAI to generate\n    replies\npurposes:\n- purpose: Provide and maintain service\n  text: Personal information is used to provide and maintain our service, including to monitor the usage of our\n    service.\n- purpose: Communication and marketing\n  text: To contact users with newsletters, marketing or promotional materials, and other information.\n- purpose: Improvements\n  text: To improve and personalize the user experience.\nretention:\n- scope: Contact requests\n  period: null\n  text: They are retained until removed by the operator and are not published in the knowledge base or sent to OpenAI\n    by the contact form.\n- scope: AI chat conversations\n  period: null\n  text: Conversations are retained on the service server until removed by the operator; they are not added to the\n    public knowledge base.\n- scope: OpenAI abuse-monitoring logs\n  period: 30 days\n  text: OpenAI may retain abuse-monitoring logs for up to 30 days under its API data controls.\nresidency:\n\
  - region: outside user jurisdiction\n  text: Personal information may be transferred to — and maintained on — computers located outside of your state,\n    province, country, or other governmental jurisdiction.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion page or email to info@mailbridgeapi.com\n  text: Account and data deletion requests can be made from the account deletion page or by contacting info@mailbridgeapi.com.\nrights:\n- right: Access, update, delete\n  text: Users can access, update, or delete their personal information.\n- right: Withdraw consent\n  text: Users have the right to withdraw consent at any time where we rely on consent to process personal information.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailbridgeapi/privacy/mailbridgeapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 13 quoted statements, read from MailBridgeAPI's own page on 2026-11-10.
synthetic: false
tags:
- Email API
- SMTP
- IMAP
- mailbox integration
- Developer Tools
- mailbox monitoring
---
