---
api_specs:
- filename: postman.yaml
  format: yaml
  label: Qover Embedded Insurance API
  slug: qover-embedded-insurance-api
  spec_type: Postman
  url: https://docs.qover.com/
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: National Identiﬁcation Number (NIN), National Register Number, such as CPR
  - category: financial
    text: IBAN/BIC, account number ,sort code, payment method, payment status and amount.
  - category: health
    text: Health data , including health status, such as sickness, disability, physical, mental and medical condition, bodily injuries, medical history and procedures, causes of death
  - category: location
    text: 'Only for bike insurance: location data, namely the last location of your bike when it was stolen that you provide us for'
  - category: behavioral
    text: information collected through cookie or other tracking technologies, which may include log-in credentials, IP addresses, domain names, browser versions and operating system, trafﬁc data
  - category: communication
    text: We store recordings of telephone conversations, emails, chats, SMS, for training purposes
  deletion:
    route: Written request to privacy@qover.com for consent withdrawal
    text: we will delete your Personal Data from our repository.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Execution and administration of your insurance contract
    text: Execution and administration of your insurance contract
  - purpose: Detection and prevention of fraud and money laundering
    text: Detection, prevention and investigation of crime, including fraud and money laundering, and analysis and management of other commercial risks
  - purpose: Marketing communications with consent
    text: If you have agreed to receive product updates and offers from us, we will process your email address, and potentially, information included in your account, based on your corresponding consent
  - purpose: Data analysis and statistical evaluation
    text: Data analysis and statistical evaluation and compilation
  retention:
  - period: null
    scope: General personal data
    text: Qover does not store your Persona Data for longer than needed for the respective purposes of processing.
  rights:
  - right: Access
    text: Right of access (article 15 EU/UK GDPR)
  - right: Rectification
    text: You can always ask us to rectify and complete your Personal Data that is inaccurate or incomplete.
  - right: Restriction of processing
    text: Right to restriction of processing (article 18 EU/UK GDPR)
  - right: Portability
    text: Right to data portability (article 20 EU/UK GDPR)
  - right: Object
    text: Right to object (article 21 EU/UK GDPR)
  - right: Withdraw consent
    text: Right to withdraw your consent (article 7 (3) EU/UK GDPR)
  - right: Lodge a complaint
    text: Right to lodge a complaint (article 77 EU/UK GDPR)
  role:
    text: Within this framework, Qover as a Data Controller processes your Personal Data for providing you with the Services.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, lease, trade or otherwise proﬁt from your Personal Data for purposes other than our main business.
  subprocessors:
    text: Service providers instructed by us (including the sub-processors of these service providers)
    url: null
  transfers:
  - mechanism: other
    text: Such transfers are subject to appropriate safeguards, including adequacy decision by the appropriate supervisory authority, the use of approved binding corporate rules or standard contractual clauses, or your consent.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Qover
provenance_date: '2026-11-10'
provider_name: Qover
provider_slug: qover
slug: qover-privacy-policy
source_date: '2026-11-10'
source_filename: qover-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://storage.googleapis.com/qover-assets/documents/policies/Privacy%20Policy_EN_v.04_2026.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Qover\naid: qover\nurl: https://storage.googleapis.com/qover-assets/documents/policies/Privacy%20Policy_EN_v.04_2026.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Within this framework, Qover as a Data Controller processes your Personal Data for providing you with the\n    Services.\ndata_categories:\n- category: identifying\n  text: National Identiﬁcation Number (NIN), National Register Number, such as CPR\n- category: financial\n  text: IBAN/BIC, account number ,sort code, payment method, payment status and amount.\n- category: health\n  text: Health data , including health status,\
  \ such as sickness, disability, physical, mental and medical condition,\n    bodily injuries, medical history and procedures, causes of death\n- category: location\n  text: 'Only for bike insurance: location data, namely the last location of your bike when it was stolen that you\n    provide us for'\n- category: behavioral\n  text: information collected through cookie or other tracking technologies, which may include log-in credentials,\n    IP addresses, domain names, browser versions and operating system, trafﬁc data\n- category: communication\n  text: We store recordings of telephone conversations, emails, chats, SMS, for training purposes\npurposes:\n- purpose: Execution and administration of your insurance contract\n  text: Execution and administration of your insurance contract\n- purpose: Detection and prevention of fraud and money laundering\n  text: Detection, prevention and investigation of crime, including fraud and money laundering, and analysis and\n    management of other\
  \ commercial risks\n- purpose: Marketing communications with consent\n  text: If you have agreed to receive product updates and offers from us, we will process your email address, and\n    potentially, information included in your account, based on your corresponding consent\n- purpose: Data analysis and statistical evaluation\n  text: Data analysis and statistical evaluation and compilation\nretention:\n- scope: General personal data\n  period: null\n  text: Qover does not store your Persona Data for longer than needed for the respective purposes of processing.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Such transfers are subject to appropriate safeguards, including adequacy decision by the appropriate supervisory\n    authority, the use of approved binding corporate rules or standard contractual clauses, or your consent.\nsubprocessors:\n  url: null\n  text: Service providers instructed by us (including the sub-processors of these service providers)\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: Written request to privacy@qover.com for consent withdrawal\n  text: we will delete your Personal Data from our repository.\nrights:\n- right: Access\n  text: Right of access (article 15 EU/UK GDPR)\n- right: Rectification\n  text: You can always ask us to rectify and complete your Personal Data that is inaccurate or incomplete.\n- right: Restriction of processing\n  text: Right to restriction of processing (article 18 EU/UK GDPR)\n- right: Portability\n  text: Right to data portability (article 20 EU/UK GDPR)\n- right: Object\n  text: Right to object (article 21 EU/UK GDPR)\n- right: Withdraw consent\n  text: Right to withdraw your consent (article 7 (3) EU/UK GDPR)\n- right: Lodge a complaint\n  text: Right to lodge a complaint (article 77 EU/UK GDPR)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, lease, trade or otherwise proﬁt from your Personal Data for purposes other than our main\n    business.\n"
source_yaml_url: https://artifacts.apis.io/qover/privacy/qover-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Qover's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Embedded Insurance
- Claims
- Policy
- Fintech
- Belgium
---
