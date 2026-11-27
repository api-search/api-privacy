---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Names Phone numbers Email addresses Mailing addresses Job titles Usernames Passwords
  - category: financial
    text: Debit/credit card numbers
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information our servers automatically collect
  - category: communication
    text: 'Tool call parameters: The specific inputs required to execute each requested action'
  deletion:
    route: Contact privacy@apiant.com or log in to account settings; account deletion upon request
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: Targeted advertising
    text: To deliver targeted advertising to you. We may process your information to develop and display personalized content and advertising tailored to your interests, location, and more.
  - purpose: MCP data operation
    text: 'APIANT, as the platform infrastructure provider, uses data processed through MCP servers solely to: Provide and operate the Platform infrastructure on behalf of the builder'
  retention:
  - period: 90 days
    scope: MCP tool call logs
    text: These logs are purged within 90 days unless a longer retention period is required by law.
  - period: null
    scope: MCP authentication tokens
    text: Authentication tokens are held in memory for the duration of the session and are not persisted after disconnection.
  - period: As long as the user has an account with us
    scope: Account data (CA categories)
    text: 'Category A: As long as the user has an account with us'
  rights:
  - right: Access
    text: Right to access your personal data
  - right: Correction
    text: Right to correct inaccuracies in your personal data
  - right: Deletion
    text: Right to request the deletion of your personal data
  - right: Opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We have not sold or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: 'The third parties we may share personal information with are as follows: Cloud Computing Services: Amazon Web Services (AWS)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: APIANT
provenance_date: '2026-11-09'
provider_name: APIANT
provider_slug: apiant
slug: apiant-privacy-policy
source_date: '2026-11-09'
source_filename: apiant-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apiant.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: APIANT\naid: apiant\nurl: https://apiant.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: Names Phone numbers Email addresses Mailing addresses Job titles Usernames Passwords\n- category: financial\n  text: Debit/credit card numbers\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category: location\n  text: Location\
  \ Data. We collect location data such as information about your device's location, which can be either\n    precise or imprecise.\n- category: behavioral\n  text: Log and Usage Data. Log and usage data is service-related, diagnostic, usage, and performance information\n    our servers automatically collect\n- category: communication\n  text: 'Tool call parameters: The specific inputs required to execute each requested action'\npurposes:\n- purpose: Provide and improve services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: Targeted advertising\n  text: To deliver targeted advertising to you. We may process your information to develop and display personalized\n    content and advertising tailored to your interests, location, and more.\n- purpose: MCP data operation\n  text: 'APIANT, as the platform infrastructure provider, uses data processed through\
  \ MCP servers solely to: Provide\n    and operate the Platform infrastructure on behalf of the builder'\nretention:\n- scope: MCP tool call logs\n  period: 90 days\n  text: These logs are purged within 90 days unless a longer retention period is required by law.\n- scope: MCP authentication tokens\n  period: null\n  text: Authentication tokens are held in memory for the duration of the session and are not persisted after disconnection.\n- scope: Account data (CA categories)\n  period: As long as the user has an account with us\n  text: 'Category A: As long as the user has an account with us'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'The third parties we may share personal information with are as follows: Cloud Computing Services: Amazon\n    Web Services (AWS)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@apiant.com or log in to account settings; account deletion upon request\n  text: Upon your request to terminate\
  \ your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: Access\n  text: Right to access your personal data\n- right: Correction\n  text: Right to correct inaccuracies in your personal data\n- right: Deletion\n  text: Right to request the deletion of your personal data\n- right: Opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California's privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance: conditional\n  text: We have not sold or shared any personal information to third parties for a business or commercial purpose\n    in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/apiant/privacy/apiant-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from APIANT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- Artificial Intelligence
- Automation
- Software-as-a-Service
---
