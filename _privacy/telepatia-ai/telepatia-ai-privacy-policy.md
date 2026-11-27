---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: health
    text: data relating to health, sex life and biometric data
  - category: identifying
    text: Any information linked or that may be associated with one or more determined or determinable natural persons.
  - category: contact
    text: the professional, business and/or personal contact data of the Data Subjects
  - category: behavioral
    text: Behavior analysis, profiling and market segmentation, prediction, classification, business intelligence, data mining
  deletion:
    route: Request deletion via PQR channel
    text: The request for deletion of the information and the revocation of the authorization will not proceed when the Data Subject has a legal or contractual duty to remain in the database.
  dpa:
    available: true
    text: such engagement is always preceded by the execution of the same data processing agreements
    url: null
  purposes:
  - purpose: Clinical documentation via AI subprocessors
    text: 'The data sent to these providers is used exclusively to deliver the service contracted by the client health institution: to transcribe the clinical encounter, remove personal identifiers, and generate the draft clinical documentation'
  - purpose: Marketing and advertising
    text: Sending of communications, advertising and/or alerts related to the purposes contained in this Privacy Policy
  - purpose: Profiling and market segmentation
    text: Behavior analysis, profiling and market segmentation, prediction, classification, business intelligence, data mining
  retention:
  - period: null
    scope: Audio of clinical encounter
    text: The audio of the clinical encounter is temporary data, processed in order to generate the transcription and the draft clinical documentation.
  - period: null
    scope: Platform data by default
    text: By default, data processed through the platform is retained
  - period: null
    scope: Databases
    text: The Databases subject to Processing by the Data Controller will remain in force as long as the purposes for which the data were collected subsist and/or for the term established by law.
  rights:
  - right: Know, update and rectify
    text: To know, update and rectify their personal data before the Data Controllers or Data Processors.
  - right: Revoke authorization and request deletion
    text: To revoke the authorization and/or request the deletion of the data when the Processing does not respect constitutional and legal principles, rights and guarantees.
  - right: Request proof of authorization
    text: To request proof of the authorization granted to the Data Controller
  - right: Complain to authority
    text: To file complaints before the Superintendence of Industry and Commerce
  role:
    text: Telepatía S.A.S. acts as Data Controller
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Telepatía S.A.S. does not sell Personal Data and does not share it with third parties other than the subprocessors bound by the agreements described in this section
  subprocessors:
    text: 'GOOGLE (Google Cloud Platform and Google AI models): Provides speech-to-text, de-identification, language-model processing, and secure cloud hosting services.'
    url: null
  transfers:
  - mechanism: other
    text: National and international Transmission and Transfer, and storage and custody of information and/or Personal Data in physical files or on own and/or third-party servers, located within or outside the country
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Telepatia AI
provenance_date: '2026-11-10'
provider_name: Telepatia AI
provider_slug: telepatia-ai
slug: telepatia-ai-privacy-policy
source_date: '2026-11-10'
source_filename: telepatia-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.telepatia.ai/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Telepatia AI\naid: telepatia-ai\nurl: https://www.telepatia.ai/en/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Telepatía S.A.S. acts as Data Controller\ndata_categories:\n- category: health\n  text: data relating to health, sex life and biometric data\n- category: identifying\n  text: Any information linked or that may be associated with one or more determined or determinable natural persons.\n- category: contact\n  text: the professional, business and/or personal contact data of the Data Subjects\n- category: behavioral\n  text: Behavior analysis, profiling and market segmentation,\
  \ prediction, classification, business intelligence,\n    data mining\npurposes:\n- purpose: Clinical documentation via AI subprocessors\n  text: 'The data sent to these providers is used exclusively to deliver the service contracted by the client health\n    institution: to transcribe the clinical encounter, remove personal identifiers, and generate the draft clinical\n    documentation'\n- purpose: Marketing and advertising\n  text: Sending of communications, advertising and/or alerts related to the purposes contained in this Privacy Policy\n- purpose: Profiling and market segmentation\n  text: Behavior analysis, profiling and market segmentation, prediction, classification, business intelligence,\n    data mining\nretention:\n- scope: Audio of clinical encounter\n  period: null\n  text: The audio of the clinical encounter is temporary data, processed in order to generate the transcription\n    and the draft clinical documentation.\n- scope: Platform data by default\n  period: null\n\
  \  text: By default, data processed through the platform is retained\n- scope: Databases\n  period: null\n  text: The Databases subject to Processing by the Data Controller will remain in force as long as the purposes\n    for which the data were collected subsist and/or for the term established by law.\nresidency: []\ntransfers:\n- mechanism: other\n  text: National and international Transmission and Transfer, and storage and custody of information and/or Personal\n    Data in physical files or on own and/or third-party servers, located within or outside the country\nsubprocessors:\n  url: null\n  text: 'GOOGLE (Google Cloud Platform and Google AI models): Provides speech-to-text, de-identification, language-model\n    processing, and secure cloud hosting services.'\ndpa:\n  available: true\n  url: null\n  text: such engagement is always preceded by the execution of the same data processing agreements\ndeletion:\n  route: Request deletion via PQR channel\n  text: The request for deletion\
  \ of the information and the revocation of the authorization will not proceed when\n    the Data Subject has a legal or contractual duty to remain in the database.\nrights:\n- right: Know, update and rectify\n  text: To know, update and rectify their personal data before the Data Controllers or Data Processors.\n- right: Revoke authorization and request deletion\n  text: To revoke the authorization and/or request the deletion of the data when the Processing does not respect\n    constitutional and legal principles, rights and guarantees.\n- right: Request proof of authorization\n  text: To request proof of the authorization granted to the Data Controller\n- right: Complain to authority\n  text: To file complaints before the Superintendence of Industry and Commerce\nsale_or_sharing:\n  stance: prohibited\n  text: Telepatía S.A.S. does not sell Personal Data and does not share it with third parties other than the subprocessors\n    bound by the agreements described in this section\n"
source_yaml_url: https://artifacts.apis.io/telepatia-ai/privacy/telepatia-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Telepatia AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical Documentation
- Medical Scribe
- Electronic Health Records
- Latin America
- Clinical Decision Support
---
