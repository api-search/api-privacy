---
api_specs:
- filename: holvi-account-information-api-openapi.yml
  format: yaml
  label: Holvi Account Information API
  slug: holvi-account-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-account-information-api-openapi.yml
- filename: holvi-consent-api-openapi.yml
  format: yaml
  label: Holvi Consent API
  slug: holvi-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-consent-api-openapi.yml
- filename: holvi-payment-initiation-api-openapi.yml
  format: yaml
  label: Holvi Payment Initiation API
  slug: holvi-payment-initiation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-payment-initiation-api-openapi.yml
- filename: holvi-third-party-provider-api-openapi.yml
  format: yaml
  label: Holvi Third Party Provider API
  slug: holvi-third-party-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/holvi/openapi/holvi-third-party-provider-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal details like your name, email address, date and place of birth
  - category: contact
    text: Contact details like your email address, physical address, and phone number
  - category: financial
    text: Credit information like repayment history and details, including where relevant information derived from Open Banking data
  - category: location
    text: Information about your identity like your passport or national identity card
  - category: behavioral
    text: Analytics information about how you interact with Holvi products and services
  - category: device
    text: technical details like your IP address and device information
  - category: biometric
    text: Identity verification media like video selfies or images of you
  - category: communication
    text: Correspondence records between you and Holvi, including for example email, chat, and phone call recordings
  deletion:
    route: Contact the Holvi Privacy Team or use the online privacy request form
    text: You may use all of your rights e.g. through Holvi's dedicated data privacy platform by filling in and submitting an online form here .
  dpa:
    available: true
    text: The obligations of Holvi as a data processor are set forth in the Holvi Data Processing Agreement.
    url: null
  purposes:
  - purpose: Providing payment services and products
    text: Holvi processes your personal data mainly for the purpose of providing better payment services to you.
  - purpose: Regulatory and anti-money laundering compliance
    text: Comply with regulatory requirements, such as payment institution and anti-money laundering legislation
  - purpose: Fraud prevention
    text: Manage risk, or to detect, prevent, and/or remediate fraud or other potentially illegal or prohibited activities
  - purpose: Marketing with consent
    text: In cases where Holvi provides targeted marketing and advertising, communicates service updates, and delivers promotional offers, Holvi will ask for your consent as required by law.
  retention:
  - period: ten years
    scope: Customer data and customer support data
    text: Customer data and customer support data are usually retained for ten years after the end of the customer relationship
  - period: ten years
    scope: Payment data of customers
    text: Payment data of Holvi customers are retained for ten years after the end of customer relationship.
  - period: three years
    scope: Survey responses
    text: Survey responses are retained for three years from submission, or until you close your account, whichever is earlier.
  - period: up to one month
    scope: Incomplete account creation
    text: If a user creating a Holvi account stops the account creation process, personal data entered by the user are retained for up to one month
  - period: six months
    scope: Job application data of successful candidates
    text: Job application data of successful candidates are retained for six months after the application period
  rights:
  - right: Access
    text: The right to access (Art. 15 GDPR) You can access your personal data stored in Holvi's systems through your account or by requesting a copy from the Holvi Privacy Team.
  - right: Portability
    text: The right to data portability (Art. 20 GDPR)
  - right: Rectification
    text: The right to rectification (Art. 16 GDPR)
  - right: Erasure
    text: The right to be forgotten / the right to erasure (Art. 17 GDPR)
  - right: Restriction
    text: The right to restrict processing (Art. 18 GDPR)
  - right: Object
    text: The right to object processing (Art. 21 GDPR)
  - right: Automated decision-making
    text: Rights related to automated decision making including profiling (Art. 22 GDPR)
  - right: Complaint
    text: You also have a right to lodge a complaint with a supervisory authority.
  role:
    text: Holvi acts as a data controller for the processing of personal data as described in this Privacy Notice. Holvi acts as a data processor to the extent it processes personal data on your behalf when making available certain related value added services such as invoicing, reporting, and the online store platform.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses from the European Commission
  - mechanism: adequacy
    text: Adequacy decisions by the European Commission
  - mechanism: DPF
    text: EU-US Data Privacy Framework (DPF), UK Extension to the EU-US DPF, and Swiss-US DPF
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Holvi
provenance_date: '2026-11-09'
provider_name: Holvi
provider_slug: holvi
slug: holvi-privacy-policy
source_date: '2026-11-09'
source_filename: holvi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://support.holvi.com/hc/en-gb/articles/29831985498258-Privacy-Notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Holvi\naid: holvi\nurl: https://support.holvi.com/hc/en-gb/articles/29831985498258-Privacy-Notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Holvi acts as a data controller for the processing of personal data as described in this Privacy Notice.\n    Holvi acts as a data processor to the extent it processes personal data on your behalf when making available\n    certain related value added services such as invoicing, reporting, and the online store platform.\ndata_categories:\n- category: identifying\n  text: Personal details like your name, email address, date and place of birth\n- category:\
  \ contact\n  text: Contact details like your email address, physical address, and phone number\n- category: financial\n  text: Credit information like repayment history and details, including where relevant information derived from\n    Open Banking data\n- category: location\n  text: Information about your identity like your passport or national identity card\n- category: behavioral\n  text: Analytics information about how you interact with Holvi products and services\n- category: device\n  text: technical details like your IP address and device information\n- category: biometric\n  text: Identity verification media like video selfies or images of you\n- category: communication\n  text: Correspondence records between you and Holvi, including for example email, chat, and phone call recordings\npurposes:\n- purpose: Providing payment services and products\n  text: Holvi processes your personal data mainly for the purpose of providing better payment services to you.\n- purpose: Regulatory\
  \ and anti-money laundering compliance\n  text: Comply with regulatory requirements, such as payment institution and anti-money laundering legislation\n- purpose: Fraud prevention\n  text: Manage risk, or to detect, prevent, and/or remediate fraud or other potentially illegal or prohibited activities\n- purpose: Marketing with consent\n  text: In cases where Holvi provides targeted marketing and advertising, communicates service updates, and delivers\n    promotional offers, Holvi will ask for your consent as required by law.\nretention:\n- scope: Customer data and customer support data\n  period: ten years\n  text: Customer data and customer support data are usually retained for ten years after the end of the customer\n    relationship\n- scope: Payment data of customers\n  period: ten years\n  text: Payment data of Holvi customers are retained for ten years after the end of customer relationship.\n- scope: Survey responses\n  period: three years\n  text: Survey responses are retained\
  \ for three years from submission, or until you close your account, whichever\n    is earlier.\n- scope: Incomplete account creation\n  period: up to one month\n  text: If a user creating a Holvi account stops the account creation process, personal data entered by the user\n    are retained for up to one month\n- scope: Job application data of successful candidates\n  period: six months\n  text: Job application data of successful candidates are retained for six months after the application period\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses from the European Commission\n- mechanism: adequacy\n  text: Adequacy decisions by the European Commission\n- mechanism: DPF\n  text: EU-US Data Privacy Framework (DPF), UK Extension to the EU-US DPF, and Swiss-US DPF\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: The obligations of Holvi as a data processor are set forth in the Holvi Data Processing Agreement.\ndeletion:\n\
  \  route: Contact the Holvi Privacy Team or use the online privacy request form\n  text: You may use all of your rights e.g. through Holvi's dedicated data privacy platform by filling in and submitting\n    an online form here .\nrights:\n- right: Access\n  text: The right to access (Art. 15 GDPR) You can access your personal data stored in Holvi's systems through your\n    account or by requesting a copy from the Holvi Privacy Team.\n- right: Portability\n  text: The right to data portability (Art. 20 GDPR)\n- right: Rectification\n  text: The right to rectification (Art. 16 GDPR)\n- right: Erasure\n  text: The right to be forgotten / the right to erasure (Art. 17 GDPR)\n- right: Restriction\n  text: The right to restrict processing (Art. 18 GDPR)\n- right: Object\n  text: The right to object processing (Art. 21 GDPR)\n- right: Automated decision-making\n  text: Rights related to automated decision making including profiling (Art. 22 GDPR)\n- right: Complaint\n  text: You also have a\
  \ right to lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/holvi/privacy/holvi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 31 quoted statements, read from Holvi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Fintech
- Payments
- Business Banking
- PSD2
- Open Banking
- SEPA
- Finland
---
