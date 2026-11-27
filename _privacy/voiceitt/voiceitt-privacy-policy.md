---
api_specs:
- filename: voiceitt-websockets-asyncapi.yml
  format: yaml
  label: Voiceitt WebSockets API
  slug: voiceitt-websockets-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/voiceitt/asyncapi/voiceitt-websockets-asyncapi.yml
- filename: voiceitt-auth-api-openapi.yml
  format: yaml
  label: Voiceitt Auth API
  slug: voiceitt-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voiceitt/openapi/voiceitt-auth-api-openapi.yml
- filename: voiceitt-rec-api-openapi.yml
  format: yaml
  label: Voiceitt Rec API
  slug: voiceitt-rec-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voiceitt/openapi/voiceitt-rec-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: This includes your name, date of birth, email address, phone number, account credentials, IP address, and other identifiers
  - category: health
    text: optional health information related to speech (if applicable)
  - category: biometric
    text: Audio Signals
  - category: location
    text: location data (approximate or precise)
  - category: communication
    text: Records of your communications with us, including emails, messages, or other submitted content.
  - category: demographic
    text: gender, country and state of residence
  - category: financial
    text: Details about transactions and orders completed through our Website or Apps.
  deletion:
    route: Request deletion by contacting support@voiceitt.com; deleting requires deleting the entire User account
    text: 'A NOTE ON DELETING YOUR INFORMATION : (i) we must delete your entire User account to remove your Personal Information'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve speech recognition services
    text: Primarily we use your Personal Information, Voice Signals and associated transcripts and annotations to provide you our Services and to operate, maintain, and enhance the quality of our Website, Apps, and Services
  - purpose: Train AI models
    text: Train and refine machine learning and artificial intelligence (AI) models.
  - purpose: Advertising and marketing
    text: To provide you with updates about our products and Services, personalize marketing communications, and measure their effectiveness.
  residency:
  - region: Israel
    text: Technologies of Voice Interface Ltd. is incorporated and registered in Israel under company number 514794486.
  retention:
  - period: null
    scope: Personal Information
    text: We retain your Personal Information only for as long as necessary to fulfill the purposes described in this Privacy Policy or as required by applicable laws.
  - period: indefinitely
    scope: Non-personal or aggregated data
    text: We may indefinitely retain non-personal, aggregated, anonymized, or de-identified information.
  rights:
  - right: Access
    text: Request details on the Personal Information we collect, as well as the sources, purposes, and categories shared.
  - right: Delete or correct
    text: Request deletion or correction of your data, subject to legal and business exceptions.
  - right: Withdraw consent
    text: Revoke previously granted consent at any time.
  - right: Object and restrict
    text: Limit processing or object to processing based on legitimate interests.
  - right: Data portability
    text: Obtain a copy of your data and transfer it to another entity.
  role:
    text: We are the controller in respect of the processing described in this Privacy Notice.
    value: both
  sale_or_sharing:
    stance: conditional
    text: If you do not want Voiceitt to sell or otherwise share your Personal Information for the commercial purposes described in Section 5.2D, “Commercial Transactions,” you can opt out by contacting us at support@voiceitt.com
  subprocessors:
    text: Service Providers. Below is a list of the types of service providers we use, the service each provides, and the types of data shared with each.
    url: null
  transfers:
  - mechanism: SCC
    text: use specific contracts approved by the European Commission, known as the Standard Contractual Clauses, to give your personal data the same protection it has in the EEA.
  - mechanism: adequacy
    text: When we transfer your personal data to Israel or the UK, we rely on the decision by the European Commission that says that those countries are considered to provide an adequate level of data protection.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Voiceitt
provenance_date: '2026-11-10'
provider_name: Voiceitt
provider_slug: voiceitt
slug: voiceitt-privacy-policy
source_date: '2026-11-10'
source_filename: voiceitt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.voiceitt.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Voiceitt\naid: voiceitt\nurl: https://www.voiceitt.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: We are the controller in respect of the processing described in this Privacy Notice.\ndata_categories:\n- category: identifying\n  text: This includes your name, date of birth, email address, phone number, account credentials, IP address, and\n    other identifiers\n- category: health\n  text: optional health information related to speech (if applicable)\n- category: biometric\n  text: Audio Signals\n- category: location\n  text: location data (approximate or precise)\n\
  - category: communication\n  text: Records of your communications with us, including emails, messages, or other submitted content.\n- category: demographic\n  text: gender, country and state of residence\n- category: financial\n  text: Details about transactions and orders completed through our Website or Apps.\npurposes:\n- purpose: Provide and improve speech recognition services\n  text: Primarily we use your Personal Information, Voice Signals and associated transcripts and annotations to\n    provide you our Services and to operate, maintain, and enhance the quality of our Website, Apps, and Services\n- purpose: Train AI models\n  text: Train and refine machine learning and artificial intelligence (AI) models.\n- purpose: Advertising and marketing\n  text: To provide you with updates about our products and Services, personalize marketing communications, and measure\n    their effectiveness.\nretention:\n- scope: Personal Information\n  period: null\n  text: We retain your Personal\
  \ Information only for as long as necessary to fulfill the purposes described in this\n    Privacy Policy or as required by applicable laws.\n- scope: Non-personal or aggregated data\n  period: indefinitely\n  text: We may indefinitely retain non-personal, aggregated, anonymized, or de-identified information.\nresidency:\n- region: Israel\n  text: Technologies of Voice Interface Ltd. is incorporated and registered in Israel under company number 514794486.\ntransfers:\n- mechanism: SCC\n  text: use specific contracts approved by the European Commission, known as the Standard Contractual Clauses, to\n    give your personal data the same protection it has in the EEA.\n- mechanism: adequacy\n  text: When we transfer your personal data to Israel or the UK, we rely on the decision by the European Commission\n    that says that those countries are considered to provide an adequate level of data protection.\nsubprocessors:\n  url: null\n  text: Service Providers. Below is a list of the types of\
  \ service providers we use, the service each provides,\n    and the types of data shared with each.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion by contacting support@voiceitt.com; deleting requires deleting the entire User account\n  text: 'A NOTE ON DELETING YOUR INFORMATION : (i) we must delete your entire User account to remove your Personal\n    Information'\nrights:\n- right: Access\n  text: Request details on the Personal Information we collect, as well as the sources, purposes, and categories\n    shared.\n- right: Delete or correct\n  text: Request deletion or correction of your data, subject to legal and business exceptions.\n- right: Withdraw consent\n  text: Revoke previously granted consent at any time.\n- right: Object and restrict\n  text: Limit processing or object to processing based on legitimate interests.\n- right: Data portability\n  text: Obtain a copy of your data and transfer it to another entity.\nsale_or_sharing:\n\
  \  stance: conditional\n  text: If you do not want Voiceitt to sell or otherwise share your Personal Information for the commercial purposes\n    described in Section 5.2D, “Commercial Transactions,” you can opt out by contacting us at support@voiceitt.com\n"
source_yaml_url: https://artifacts.apis.io/voiceitt/privacy/voiceitt-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Voiceitt's own page on 2026-11-10.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Voice
- Accessibility
- Assistive Technology
- Artificial Intelligence
- Transcription
- Captioning
- Company
- Real-Time
---
