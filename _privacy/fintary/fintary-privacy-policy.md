---
api_specs:
- filename: fintary-agents-api-openapi.yml
  format: yaml
  label: Fintary Agents API
  slug: fintary-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-agents-api-openapi.yml
- filename: fintary-ams-agents-api-openapi.yml
  format: yaml
  label: Fintary AMS - Agents API
  slug: fintary-ams-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-agents-api-openapi.yml
- filename: fintary-ams-configs-api-openapi.yml
  format: yaml
  label: Fintary AMS - Configs API
  slug: fintary-ams-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-configs-api-openapi.yml
- filename: fintary-ams-customers-api-openapi.yml
  format: yaml
  label: Fintary AMS - Customers API
  slug: fintary-ams-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-customers-api-openapi.yml
- filename: fintary-ams-policies-api-openapi.yml
  format: yaml
  label: Fintary AMS - Policies API
  slug: fintary-ams-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-policies-api-openapi.yml
- filename: fintary-ams-registry-api-openapi.yml
  format: yaml
  label: Fintary AMS - Registry API
  slug: fintary-ams-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-registry-api-openapi.yml
- filename: fintary-ams-tasks-api-openapi.yml
  format: yaml
  label: Fintary AMS - Tasks API
  slug: fintary-ams-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-ams-tasks-api-openapi.yml
- filename: fintary-analytics-api-openapi.yml
  format: yaml
  label: Fintary Analytics API
  slug: fintary-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-analytics-api-openapi.yml
- filename: fintary-commission-reports-api-openapi.yml
  format: yaml
  label: Fintary Commission Reports API
  slug: fintary-commission-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-commission-reports-api-openapi.yml
- filename: fintary-documents-api-openapi.yml
  format: yaml
  label: Fintary Documents API
  slug: fintary-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fintary/openapi/fintary-documents-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information such as your name, mailing or delivery address, email address, telephone number, or similar contact information.
  - category: identifying
    text: Unique identifiers including online identifier, IP address, mobile device identifiers, username, or similar identifier.
  - category: financial
    text: Financial information such as your billing address, credit card information, and other payment-related information.
  - category: behavioral
    text: Internet or other similar network activity including your browsing history, search history, information about your interactions with our websites, applications, or advertisements.
  - category: location
    text: Technical information such as your internet protocol (IP) address, your login data, browser type and version, time zone setting, location, browser plug-in types and versions, operating system and platform, and other technology on the devices you use to access the Service.
  - category: professional
    text: Employment information such as your company or employer/workers, if the information is linked to your identifying information.
  deletion:
    route: Contact us or use account settings
    text: You may view and modify your personal information through your account settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: We use this information to operate, maintain, and provide to you the features of the Service.
  - purpose: Deliver advertising and marketing
    text: Deliver relevant content, advertisements, and messaging to you and to measure or understand the effectiveness of such content, advertisements, and messaging.
  - purpose: Analytics and reporting for Customers
    text: We provide analytics and reporting functionalities to Customers to help manage and analyze workforce capabilities and efficiencies;
  residency:
  - region: United States
    text: Your information collected through the Service may be stored and processed in the United States and in any other country in which Fintary or its subsidiaries, affiliates or service providers maintain facilities.
  retention:
  - period: null
    scope: Account information
    text: We will retain your information for as long as your account is active or as needed to provide you Service.
  rights:
  - right: Right to know/access
    text: 'Right to Know/Access: The right to request certain information about our collection and use of personal information about you as described below:'
  - right: Right to delete
    text: 'Right to Delete: The right to request that we delete certain personal information we have about you.'
  - right: Right to correct
    text: 'Right to Correct: You have the right to request that we correct inaccurate personal information regarding the information you provide us.'
  - right: Right to restrict use of sensitive personal information
    text: 'Right to Restrict the Use of Sensitive Personal Information: You have the right to restrict the use of your sensitive personal information.'
  - right: Marketing opt-out
    text: You may also opt-out of further marketing communications by replying to any promotional email we have sent you or following the opt-out links on that message.
  role:
    text: We handle personal information solely on behalf of our Customers and in accordance with our agreements with our Customers.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: you consent to the transfer of information to the U.S. or any other country in which Fintary or its parent, subsidiaries, affiliates or service providers maintain facilities
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fintary
provenance_date: '2026-11-09'
provider_name: Fintary
provider_slug: fintary
slug: fintary-privacy-policy
source_date: '2026-11-09'
source_filename: fintary-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fintary.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fintary\naid: fintary\nurl: https://www.fintary.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We handle personal information solely on behalf of our Customers and in accordance with our agreements with\n    our Customers.\ndata_categories:\n- category: contact\n  text: Contact information such as your name, mailing or delivery address, email address, telephone number, or\n    similar contact information.\n- category: identifying\n  text: Unique identifiers including online identifier, IP address, mobile device identifiers, username, or similar\n    identifier.\n- category: financial\n\
  \  text: Financial information such as your billing address, credit card information, and other payment-related information.\n- category: behavioral\n  text: Internet or other similar network activity including your browsing history, search history, information\n    about your interactions with our websites, applications, or advertisements.\n- category: location\n  text: Technical information such as your internet protocol (IP) address, your login data, browser type and version,\n    time zone setting, location, browser plug-in types and versions, operating system and platform, and other technology\n    on the devices you use to access the Service.\n- category: professional\n  text: Employment information such as your company or employer/workers, if the information is linked to your identifying\n    information.\npurposes:\n- purpose: Provide and operate the Service\n  text: We use this information to operate, maintain, and provide to you the features of the Service.\n- purpose: Deliver\
  \ advertising and marketing\n  text: Deliver relevant content, advertisements, and messaging to you and to measure or understand the effectiveness\n    of such content, advertisements, and messaging.\n- purpose: Analytics and reporting for Customers\n  text: We provide analytics and reporting functionalities to Customers to help manage and analyze workforce capabilities\n    and efficiencies;\nretention:\n- scope: Account information\n  period: null\n  text: We will retain your information for as long as your account is active or as needed to provide you Service.\nresidency:\n- region: United States\n  text: Your information collected through the Service may be stored and processed in the United States and in any\n    other country in which Fintary or its subsidiaries, affiliates or service providers maintain facilities.\ntransfers:\n- mechanism: other\n  text: you consent to the transfer of information to the U.S. or any other country in which Fintary or its parent,\n    subsidiaries,\
  \ affiliates or service providers maintain facilities\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us or use account settings\n  text: You may view and modify your personal information through your account settings.\nrights:\n- right: Right to know/access\n  text: 'Right to Know/Access: The right to request certain information about our collection and use of personal\n    information about you as described below:'\n- right: Right to delete\n  text: 'Right to Delete: The right to request that we delete certain personal information we have about you.'\n- right: Right to correct\n  text: 'Right to Correct: You have the right to request that we correct inaccurate personal information regarding\n    the information you provide us.'\n- right: Right to restrict use of sensitive personal information\n  text: 'Right to Restrict the Use of Sensitive Personal Information: You have the right to restrict the use of\n   \
  \ your sensitive personal information.'\n- right: Marketing opt-out\n  text: You may also opt-out of further marketing communications by replying to any promotional email we have sent\n    you or following the opt-out links on that message.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fintary/privacy/fintary-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 19 quoted statements, read from Fintary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Insurance
- Insurtech
- Commissions
- Revenue Operations
- Analytics
- Agency Management
- Policy Management
- Payouts
- Reconciliation
- OpenAPI
---
