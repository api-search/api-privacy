---
api_specs:
- filename: filevine-identity-api-openapi.yml
  format: yaml
  label: Filevine Identity API
  slug: filevine-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-identity-api-openapi.yml
- filename: filevine-projects-api-openapi.yml
  format: yaml
  label: Filevine Projects API
  slug: filevine-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-projects-api-openapi.yml
- filename: filevine-contacts-api-openapi.yml
  format: yaml
  label: Filevine Contacts API
  slug: filevine-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-contacts-api-openapi.yml
- filename: filevine-documents-api-openapi.yml
  format: yaml
  label: Filevine Documents API
  slug: filevine-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-documents-api-openapi.yml
- filename: filevine-notes-api-openapi.yml
  format: yaml
  label: Filevine Notes API
  slug: filevine-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-notes-api-openapi.yml
- filename: filevine-deadlines-api-openapi.yml
  format: yaml
  label: Filevine Deadlines API
  slug: filevine-deadlines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-deadlines-api-openapi.yml
- filename: filevine-tasks-api-openapi.yml
  format: yaml
  label: Filevine Tasks API
  slug: filevine-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-tasks-api-openapi.yml
- filename: filevine-webhooks-api-openapi.yml
  format: yaml
  label: Filevine Webhooks API
  slug: filevine-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-webhooks-api-openapi.yml
- filename: filevine-time-entries-api-openapi.yml
  format: yaml
  label: Filevine Time Entries API
  slug: filevine-time-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filevine/openapi/filevine-time-entries-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account Information . When you register for a Filevine account, we collect your full name, email address, phone number, organization name
  - category: financial
    text: Billing, Payment and Transactional Information . If you are a Subscriber, you will provide your contact information and financial information
  - category: communication
    text: Audio Recordings and Transcripts . When you use our meeting recording features (including LOIS for Meetings), we collect audio recordings of the meetings or conversations you choose to record
  - category: location
    text: Demographic Data . You may include demographic information to your profile on the Services, such as your city, state, country of residence, postal code, and age.
  - category: device
    text: Browser and device data, such as your IP Address, device type, operating system and Internet browser type
  - category: behavioral
    text: Usage data, such as times spent on the Sites and Services, pages visited, links clicked, language preferences
  deletion:
    route: Deletion request via phone, email or webform
    text: Deletion – You may have the right to delete your personal data that we have obtained, subject to certain exceptions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Sites and Services to affiliates
    text: With other Filevine affiliates in order to provide our Sites and Services and for our administrative purposes.
  - purpose: Service providers and AI processing
    text: In particular, audio recordings, transcripts, and related meeting content collected through LOIS for Meetings are processed by AI service providers (including large language model providers) that generate transcripts, summaries, and AI-suggested actions on our behalf.
  - purpose: Legal compliance and harm prevention
    text: To comply with any court order, law, or legal process, including to responding to any government or regulatory request
  retention:
  - period: null
    scope: Personal data generally
    text: We retain your personal data as long as we are providing the Sites and Services to you or our Subscribers (as applicable).
  - period: null
    scope: After account closure
    text: Even after we stop providing Sites and Services directly or indirectly to you, and even if you close your Filevine account, we keep your personal data in order to comply with our legal and reporting obligations.
  rights:
  - right: Access
    text: Access – You may have the right to know what personal data we have collected about you and to access such data.
  - right: Deletion
    text: Deletion – You may have the right to delete your personal data that we have obtained, subject to certain exceptions.
  - right: Correction
    text: Correction – You may have the right to correct inaccuracies in your personal data.
  - right: Data portability
    text: Data portability – You may have the right to receive a copy of your personal data in a portable and readily usable format.
  - right: Opt out of sale or sharing
    text: (ii) opt out of the sale or sharing of your personal data
  role:
    text: 'Where Filevine acts as a controller, we process your personal data: with your consent; where necessary to perform a contract; to comply with our legal obligations'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: These providers act as data subprocessors under contract with Filevine.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required by applicable law, we use the EU Standard Contractual Clauses with a data recipient outside the EEA, UK or Switzerland
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Filevine
provenance_date: '2026-11-09'
provider_name: Filevine
provider_slug: filevine
slug: filevine-privacy-policy
source_date: '2026-11-09'
source_filename: filevine-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.filevine.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Filevine\naid: filevine\nurl: https://www.filevine.com/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Where Filevine acts as a controller, we process your personal data: with your consent; where necessary\n    to perform a contract; to comply with our legal obligations'\ndata_categories:\n- category: identifying\n  text: Account Information . When you register for a Filevine account, we collect your full name, email address,\n    phone number, organization name\n- category: financial\n  text: Billing, Payment and Transactional Information . If you are a Subscriber, you\
  \ will provide your contact\n    information and financial information\n- category: communication\n  text: Audio Recordings and Transcripts . When you use our meeting recording features (including LOIS for Meetings),\n    we collect audio recordings of the meetings or conversations you choose to record\n- category: location\n  text: Demographic Data . You may include demographic information to your profile on the Services, such as your\n    city, state, country of residence, postal code, and age.\n- category: device\n  text: Browser and device data, such as your IP Address, device type, operating system and Internet browser type\n- category: behavioral\n  text: Usage data, such as times spent on the Sites and Services, pages visited, links clicked, language preferences\npurposes:\n- purpose: Provide Sites and Services to affiliates\n  text: With other Filevine affiliates in order to provide our Sites and Services and for our administrative purposes.\n- purpose: Service providers and AI\
  \ processing\n  text: In particular, audio recordings, transcripts, and related meeting content collected through LOIS for Meetings\n    are processed by AI service providers (including large language model providers) that generate transcripts,\n    summaries, and AI-suggested actions on our behalf.\n- purpose: Legal compliance and harm prevention\n  text: To comply with any court order, law, or legal process, including to responding to any government or regulatory\n    request\nretention:\n- scope: Personal data generally\n  period: null\n  text: We retain your personal data as long as we are providing the Sites and Services to you or our Subscribers\n    (as applicable).\n- scope: After account closure\n  period: null\n  text: Even after we stop providing Sites and Services directly or indirectly to you, and even if you close your\n    Filevine account, we keep your personal data in order to comply with our legal and reporting obligations.\nresidency: []\ntransfers:\n- mechanism: SCC\n\
  \  text: Where required by applicable law, we use the EU Standard Contractual Clauses with a data recipient outside\n    the EEA, UK or Switzerland\nsubprocessors:\n  url: null\n  text: These providers act as data subprocessors under contract with Filevine.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deletion request via phone, email or webform\n  text: Deletion – You may have the right to delete your personal data that we have obtained, subject to certain\n    exceptions.\nrights:\n- right: Access\n  text: Access – You may have the right to know what personal data we have collected about you and to access such\n    data.\n- right: Deletion\n  text: Deletion – You may have the right to delete your personal data that we have obtained, subject to certain\n    exceptions.\n- right: Correction\n  text: Correction – You may have the right to correct inaccuracies in your personal data.\n- right: Data portability\n  text: Data portability – You may have the right\
  \ to receive a copy of your personal data in a portable and readily\n    usable format.\n- right: Opt out of sale or sharing\n  text: (ii) opt out of the sale or sharing of your personal data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/filevine/privacy/filevine-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 20 quoted statements, read from Filevine's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Case Management
- Matter
- Intake
- Documents
- LOIS
- Webhook
- Legal AI
- Personal Injury
- Mass Torts
---
