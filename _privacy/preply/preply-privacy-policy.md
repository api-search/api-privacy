---
api_specs:
- filename: preply-chatgpt-openapi-api-openapi.yml
  format: yaml
  label: Preply Chatgpt Openapi API
  slug: preply-chatgpt-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/preply/openapi/preply-chatgpt-openapi-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: first name, last name, email, phone number, Skype ID, or social network ID
  - category: biometric
    text: We process your facial biometrics (we have engaged a third-party online verification provider for this purpose) and your ID to verify your identity and identify fraud.
  - category: financial
    text: We process the details of transactions you carry out through the Preply Platform (such as ID, date and time of transaction).
  - category: location
    text: your location, type of the device you used during your visit
  - category: communication
    text: We may analyze your microphone activity and measure the volume of the sound.
  deletion:
    route: Email support@preply.com or delete the account at https://preply.com/settings
    text: Contact us by email at support@preply.com. We will respond to your request to delete your information within 30 days and notify you of the outcome.
  dpa:
    available: true
    text: strictly under data processing agreements (DPA) or Standard Contractual Clauses (SCCs)
    url: null
  purposes:
  - purpose: Provision of services
    text: Primarily, we process your personal data to authorize access to our Services and to fulfill our obligations under the Terms of Service for Services provision.
  - purpose: Analytics and development
    text: For the purposes of analytics, we monitor and analyze the personal data you provide us with
  - purpose: AI data training
    text: Preply stores your personal data processed by AI-powered tools for AI data training purposes for 2 years in the EU and longer for non-EU jurisdictions.
  residency:
  - region: Ireland, Germany, United States
    text: Preply uses only secure places of storage, such as those provided by AWS (Amazon, the USA), with servers located in Ireland, Germany and the United States.
  retention:
  - period: null
    scope: Active account
    text: Generally, Preply retains your personal data as long as your account is active.
  - period: 90 days
    scope: Expired account
    text: If your last activity on Preply was more than 2 years ago, your account will be considered expired. In this case, we undertake to remove your personal data from our active systems and servers within 90 days or earlier.
  - period: 2 years
    scope: AI data training
    text: Preply stores your personal data processed by AI-powered tools for AI data training purposes for 2 years in the EU and longer for non-EU jurisdictions.
  - period: 30 days
    scope: Sweepstakes participant lists
    text: Lists of participants of the sweepstakes including those who entered the sweepstakes via the alternative method of entry (mail-in) will be deleted in 30 days after the close of the sweepstakes.
  rights:
  - right: Access
    text: You can access your personal data processed by Preply.
  - right: Rectification
    text: You can ask Preply to have incomplete personal data requiring corrections completed.
  - right: Erasure
    text: You can request Preply to erase personal data.
  - right: Portability
    text: You can have your personal data transmitted directly from one controller to another where technically feasible
  - right: Objection
    text: You can object to our processing of your personal data when the processing is related to the performance of our task carried out in the public interest or the exercise of official authority vested in us.
  - right: Withdraw consent
    text: Right to Withdraw Consent at any Time by Contacting Us
  - right: California Right to Know, Correction, Deletion, Opt-Out
    text: know about the categories and specific pieces of personal data that we have collected about you and access a copy of your personal data (“ Right to Know ”)
  role:
    text: 'Data Controller: Preply, Inc., address: 1309 Beacon Street, Suite 300, Brookline, MA 02446'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data and the personal data of any minors under 16 years of age.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: signing data processing agreements for the protection of personal data with contractors and partners (including the Standard Contractual Clauses adopted by the European Commission and compliant with the EU data protection laws)
  - mechanism: DPF
    text: Preply, Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Preply
provenance_date: '2026-11-10'
provider_name: Preply
provider_slug: preply
slug: preply-privacy-policy
source_date: '2026-11-10'
source_filename: preply-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://termsofuse.preply.com/terms_of_use/en_PrivacyPolicy.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Preply\naid: preply\nurl: https://termsofuse.preply.com/terms_of_use/en_PrivacyPolicy.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: 'Data Controller: Preply, Inc., address: 1309 Beacon Street, Suite 300, Brookline, MA 02446'\ndata_categories:\n- category: identifying\n  text: first name, last name, email, phone number, Skype ID, or social network ID\n- category: biometric\n  text: We process your facial biometrics (we have engaged a third-party online verification provider for this purpose)\n    and your ID to verify your identity and identify fraud.\n- category: financial\n\
  \  text: We process the details of transactions you carry out through the Preply Platform (such as ID, date and time\n    of transaction).\n- category: location\n  text: your location, type of the device you used during your visit\n- category: communication\n  text: We may analyze your microphone activity and measure the volume of the sound.\npurposes:\n- purpose: Provision of services\n  text: Primarily, we process your personal data to authorize access to our Services and to fulfill our obligations\n    under the Terms of Service for Services provision.\n- purpose: Analytics and development\n  text: For the purposes of analytics, we monitor and analyze the personal data you provide us with\n- purpose: AI data training\n  text: Preply stores your personal data processed by AI-powered tools for AI data training purposes for 2 years\n    in the EU and longer for non-EU jurisdictions.\nretention:\n- scope: Active account\n  period: null\n  text: Generally, Preply retains your personal data\
  \ as long as your account is active.\n- scope: Expired account\n  period: 90 days\n  text: If your last activity on Preply was more than 2 years ago, your account will be considered expired. In this\n    case, we undertake to remove your personal data from our active systems and servers within 90 days or earlier.\n- scope: AI data training\n  period: 2 years\n  text: Preply stores your personal data processed by AI-powered tools for AI data training purposes for 2 years\n    in the EU and longer for non-EU jurisdictions.\n- scope: Sweepstakes participant lists\n  period: 30 days\n  text: Lists of participants of the sweepstakes including those who entered the sweepstakes via the alternative\n    method of entry (mail-in) will be deleted in 30 days after the close of the sweepstakes.\nresidency:\n- region: Ireland, Germany, United States\n  text: Preply uses only secure places of storage, such as those provided by AWS (Amazon, the USA), with servers\n    located in Ireland, Germany and\
  \ the United States.\ntransfers:\n- mechanism: SCC\n  text: signing data processing agreements for the protection of personal data with contractors and partners (including\n    the Standard Contractual Clauses adopted by the European Commission and compliant with the EU data protection\n    laws)\n- mechanism: DPF\n  text: Preply, Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: strictly under data processing agreements (DPA) or Standard Contractual Clauses (SCCs)\ndeletion:\n  route: Email support@preply.com or delete the account at https://preply.com/settings\n  text: Contact us by email at support@preply.com. We will respond to your request to delete your information within\n    30 days and notify you of the outcome.\nrights:\n- right: Access\n  text: You can access your personal\
  \ data processed by Preply.\n- right: Rectification\n  text: You can ask Preply to have incomplete personal data requiring corrections completed.\n- right: Erasure\n  text: You can request Preply to erase personal data.\n- right: Portability\n  text: You can have your personal data transmitted directly from one controller to another where technically feasible\n- right: Objection\n  text: You can object to our processing of your personal data when the processing is related to the performance\n    of our task carried out in the public interest or the exercise of official authority vested in us.\n- right: Withdraw consent\n  text: Right to Withdraw Consent at any Time by Contacting Us\n- right: California Right to Know, Correction, Deletion, Opt-Out\n  text: know about the categories and specific pieces of personal data that we have collected about you and access\n    a copy of your personal data (“ Right to Know ”)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal\
  \ data and the personal data of any minors under 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/preply/privacy/preply-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Preply's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- Language Learning
- Tutoring
- Marketplace
- EdTech
- Search
---
