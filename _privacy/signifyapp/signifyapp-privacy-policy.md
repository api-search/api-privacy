---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identifiers : Name, surname, identification number, E-mail, Mobile Number'
  - category: financial
    text: 'Commercial /transactional Data: billing information, purchased products or Services, bank card data and bank account details'
  - category: biometric
    text: 'Biometric Data of the signatory: photo/video recording of the face of the signatory recorded through the mobile app or camera'
  - category: location
    text: geolocation, physical location and other characteristics such as operative system and browser
  - category: device
    text: unique device identifiers
  deletion:
    route: Account deletion request or erasure request by Customer; Signify erases within 10 calendar days
    text: Signify shall destroy/erase the Data associated with the Customer within 10 (ten) calendar days upon such deletion
  dpa:
    available: true
    text: 'the matters related to the processing of the Data by Signify as the Data Processor, are governed under the Data Protection Agreement available at: https://signifyapp.com/en/policies/privacy-policy/#dpa'
    url: https://signifyapp.com/en/policies/privacy-policy/#dpa
  purposes:
  - purpose: Providing the Platform and Services
    text: Provides the Customer the Services/products in relation to the Platform (electronic signature, sharing the Document and etc.).
  - purpose: Direct marketing
    text: Markets the preferences, products or special measures via e-mail or phone, provides the Customer with marketing information.
  - purpose: Fraud prevention and security
    text: Prevents, examines and reacts to the matters such as fraud, Non-authorized Use of the Services, breach of the Terms of Use or other illegal activities.
  - purpose: Legal compliance
    text: Complies with the requirements of law, including but not limited to the Anti-Money Laundering normative acts.
  residency:
  - region: Sweden (AWS Stockholm)
    text: Signify uses the Amazon Web Services (AWS) data center located in Stockholm for storing the data.
  retention:
  - period: null
    scope: Customer data while account active
    text: Signify processes the Customer Data at least for the period wherein the Customer’s Account is active
  - period: 2 (two) year term
    scope: Inactive accounts
    text: In the event there is no activity by the Customer on the Platform, Signify may delete the full information/Data, Documents, templates, configurations, sub-users and etc. upon expiry of the 2 (two) year term from the latest activity of the Customer on the Platform.
  - period: ten (10) years from the expiry date
    scope: Financial management data
    text: During the contractual relationship, plus ten (10) years from the expiry date
  - period: Three (3) years
    scope: Managing account cancellation lists
    text: Managing account cancellation lists Three (3) years from the account cancellation request
  rights:
  - right: Obtain information
    text: Right to O btain I nformation - obtain information on the Data being processed
  - right: Correct, update, block, remove or destroy
    text: Right to C orrect, U pdate, C omplete, A dd, B lock, R emove and/or D estroy the Data
  - right: Refuse processing for marketing
    text: Right to R efuse P rocessing of the Data for M arketing P urposes - object to the processing of the Data for direct marketing purposes.
  - right: Withdraw consent
    text: Right to W ithdraw the C onsent - withdraw his/her/its consent on the processing of the Data at any time
  role:
    text: Signify acting in its capacity as the Data Processor set forth under the Law of Georgia “on the Personal Data Protection” receives and processes
    value: processor
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'The list of the service providers and sub-contractors of Signify is available at: https://signifyapp.com/en/policies/privacy-policy/#sub-subprocessors'
    url: https://signifyapp.com/en/policies/privacy-policy/#subprocessors
  transfers:
  - mechanism: other
    text: Data Transmission in other Countries of Insufficient Data Protection Guarantees. In the event the data is transmitted in a state which fails to provide sufficient degree of protection of the data and the rights of the data subject, Signify ensures to conclude a respective Data Processing Agreement in accordance with the requirements of the law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Signify
provenance_date: '2026-11-10'
provider_name: Signify
provider_slug: signifyapp
slug: signifyapp-privacy-policy
source_date: '2026-11-10'
source_filename: signifyapp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://signifyapp.com/en/policies/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Signify\naid: signifyapp\nurl: https://signifyapp.com/en/policies/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Signify acting in its capacity as the Data Processor set forth under the Law of Georgia “on the Personal\n    Data Protection” receives and processes\ndata_categories:\n- category: identifying\n  text: 'Identifiers : Name, surname, identification number, E-mail, Mobile Number'\n- category: financial\n  text: 'Commercial /transactional Data: billing information, purchased products or Services, bank card data and\n    bank account details'\n- category: biometric\n  text:\
  \ 'Biometric Data of the signatory: photo/video recording of the face of the signatory recorded through the\n    mobile app or camera'\n- category: location\n  text: geolocation, physical location and other characteristics such as operative system and browser\n- category: device\n  text: unique device identifiers\npurposes:\n- purpose: Providing the Platform and Services\n  text: Provides the Customer the Services/products in relation to the Platform (electronic signature, sharing the\n    Document and etc.).\n- purpose: Direct marketing\n  text: Markets the preferences, products or special measures via e-mail or phone, provides the Customer with marketing\n    information.\n- purpose: Fraud prevention and security\n  text: Prevents, examines and reacts to the matters such as fraud, Non-authorized Use of the Services, breach of\n    the Terms of Use or other illegal activities.\n- purpose: Legal compliance\n  text: Complies with the requirements of law, including but not limited to the\
  \ Anti-Money Laundering normative\n    acts.\nretention:\n- scope: Customer data while account active\n  period: null\n  text: Signify processes the Customer Data at least for the period wherein the Customer’s Account is active\n- scope: Inactive accounts\n  period: 2 (two) year term\n  text: In the event there is no activity by the Customer on the Platform, Signify may delete the full information/Data,\n    Documents, templates, configurations, sub-users and etc. upon expiry of the 2 (two) year term from the latest\n    activity of the Customer on the Platform.\n- scope: Financial management data\n  period: ten (10) years from the expiry date\n  text: During the contractual relationship, plus ten (10) years from the expiry date\n- scope: Managing account cancellation lists\n  period: Three (3) years\n  text: Managing account cancellation lists Three (3) years from the account cancellation request\nresidency:\n- region: Sweden (AWS Stockholm)\n  text: Signify uses the Amazon Web Services\
  \ (AWS) data center located in Stockholm for storing the data.\ntransfers:\n- mechanism: other\n  text: Data Transmission in other Countries of Insufficient Data Protection Guarantees. In the event the data is\n    transmitted in a state which fails to provide sufficient degree of protection of the data and the rights of\n    the data subject, Signify ensures to conclude a respective Data Processing Agreement in accordance with the\n    requirements of the law.\nsubprocessors:\n  url: https://signifyapp.com/en/policies/privacy-policy/#subprocessors\n  text: 'The list of the service providers and sub-contractors of Signify is available at: https://signifyapp.com/en/policies/privacy-policy/#sub-subprocessors'\ndpa:\n  available: true\n  url: https://signifyapp.com/en/policies/privacy-policy/#dpa\n  text: 'the matters related to the processing of the Data by Signify as the Data Processor, are governed under\n    the Data Protection Agreement available at: https://signifyapp.com/en/policies/privacy-policy/#dpa'\n\
  deletion:\n  route: Account deletion request or erasure request by Customer; Signify erases within 10 calendar days\n  text: Signify shall destroy/erase the Data associated with the Customer within 10 (ten) calendar days upon such\n    deletion\nrights:\n- right: Obtain information\n  text: Right to O btain I nformation - obtain information on the Data being processed\n- right: Correct, update, block, remove or destroy\n  text: Right to C orrect, U pdate, C omplete, A dd, B lock, R emove and/or D estroy the Data\n- right: Refuse processing for marketing\n  text: Right to R efuse P rocessing of the Data for M arketing P urposes - object to the processing of the Data\n    for direct marketing purposes.\n- right: Withdraw consent\n  text: Right to W ithdraw the C onsent - withdraw his/her/its consent on the processing of the Data at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/signifyapp/privacy/signifyapp-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 23 quoted statements, read from Signify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Contract Management
- Digital Signature
- Enterprise Software
- Software-as-a-Service
---
