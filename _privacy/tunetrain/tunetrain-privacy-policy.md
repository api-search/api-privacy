---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Data: Email address, username, account preferences'
  - category: financial
    text: 'Payment Data: Billing information, payment method details (processed securely via Stripe)'
  - category: behavioral
    text: 'Usage Data: Service usage patterns, feature interactions, training history, model performance metrics'
  - category: device
    text: 'Technical Data: IP address, browser type, device information, session data'
  - category: other
    text: 'Training Data: Datasets uploaded for model fine-tuning (processed according to your instructions)'
  - category: communication
    text: 'Communication Data: Support requests, feedback, correspondence'
  deletion:
    route: Contact privacy@tunetrain.ai to exercise rights, including erasure
    text: 'Right to Erasure (Art. 17): Request deletion of your personal data'
  dpa:
    available: true
    text: All third-party processors are bound by data processing agreements (DPAs)
    url: null
  purposes:
  - purpose: Contract performance
    text: 'Contract Performance (Art. 6(1)(b) GDPR): To provide our AI model fine-tuning services'
  - purpose: Service improvement, fraud prevention, analytics
    text: 'Legitimate Interest (Art. 6(1)(f) GDPR): For service improvement, fraud prevention, and analytics'
  - purpose: Marketing communications
    text: 'Consent (Art. 6(1)(a) GDPR): For marketing communications and optional features'
  - purpose: Tax and accounting
    text: 'Legal Obligation (Art. 6(1)(c) GDPR): For tax and accounting requirements'
  retention:
  - period: 3 years
    scope: Account data
    text: 'Account Data: Retained for the duration of your account plus 3 years for legal obligations'
  - period: 30 days
    scope: Training data
    text: 'Training Data: Retained only during active training and for 30 days after completion, then securely deleted'
  - period: 10 years
    scope: Payment data
    text: 'Payment Data: Retained for 10 years for tax and accounting purposes'
  - period: 12 months
    scope: Technical logs
    text: 'Technical Logs: Retained for 12 months for security and performance monitoring'
  rights:
  - right: Access
    text: 'Right of Access (Art. 15): Request information about your personal data'
  - right: Rectification
    text: 'Right to Rectification (Art. 16): Correct inaccurate personal data'
  - right: Erasure
    text: 'Right to Erasure (Art. 17): Request deletion of your personal data'
  - right: Restrict processing
    text: 'Right to Restrict Processing (Art. 18): Limit how we process your data'
  - right: Portability
    text: 'Right to Data Portability (Art. 20): Receive your data in a portable format'
  - right: Object
    text: 'Right to Object (Art. 21): Object to processing based on legitimate interest'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: Withdraw consent for consent-based processing'
  role:
    text: Responsible Entity SunsetPicnic UG (haftungsbeschränkt) TuneTrain.ai Platform c/o Pawel Sawicki Plantage 17 13597 Berlin, Germany
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Stripe: Payment processing (PCI DSS compliant) Clerk: Authentication and user management services Cloud Infrastructure: Secure compute and storage for model training Vercel: Hosting and content delivery Communication Services: Transactional email delivery'
    url: null
  transfers:
  - mechanism: adequacy
    text: European Commission adequacy decisions
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs)
  - mechanism: BCR
    text: Binding Corporate Rules where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TuneTrain.ai
provenance_date: '2026-11-10'
provider_name: TuneTrain.ai
provider_slug: tunetrain
slug: tunetrain-privacy-policy
source_date: '2026-11-10'
source_filename: tunetrain-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tunetrain.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TuneTrain.ai\naid: tunetrain\nurl: https://www.tunetrain.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Responsible Entity SunsetPicnic UG (haftungsbeschränkt) TuneTrain.ai Platform c/o Pawel Sawicki Plantage\n    17 13597 Berlin, Germany\ndata_categories:\n- category: identifying\n  text: 'Account Data: Email address, username, account preferences'\n- category: financial\n  text: 'Payment Data: Billing information, payment method details (processed securely via Stripe)'\n- category: behavioral\n  text: 'Usage Data: Service usage patterns, feature interactions, training history,\
  \ model performance metrics'\n- category: device\n  text: 'Technical Data: IP address, browser type, device information, session data'\n- category: other\n  text: 'Training Data: Datasets uploaded for model fine-tuning (processed according to your instructions)'\n- category: communication\n  text: 'Communication Data: Support requests, feedback, correspondence'\npurposes:\n- purpose: Contract performance\n  text: 'Contract Performance (Art. 6(1)(b) GDPR): To provide our AI model fine-tuning services'\n- purpose: Service improvement, fraud prevention, analytics\n  text: 'Legitimate Interest (Art. 6(1)(f) GDPR): For service improvement, fraud prevention, and analytics'\n- purpose: Marketing communications\n  text: 'Consent (Art. 6(1)(a) GDPR): For marketing communications and optional features'\n- purpose: Tax and accounting\n  text: 'Legal Obligation (Art. 6(1)(c) GDPR): For tax and accounting requirements'\nretention:\n- scope: Account data\n  period: 3 years\n  text: 'Account Data: Retained\
  \ for the duration of your account plus 3 years for legal obligations'\n- scope: Training data\n  period: 30 days\n  text: 'Training Data: Retained only during active training and for 30 days after completion, then securely deleted'\n- scope: Payment data\n  period: 10 years\n  text: 'Payment Data: Retained for 10 years for tax and accounting purposes'\n- scope: Technical logs\n  period: 12 months\n  text: 'Technical Logs: Retained for 12 months for security and performance monitoring'\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: European Commission adequacy decisions\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs)\n- mechanism: BCR\n  text: Binding Corporate Rules where applicable\nsubprocessors:\n  url: null\n  text: 'Stripe: Payment processing (PCI DSS compliant) Clerk: Authentication and user management services Cloud\n    Infrastructure: Secure compute and storage for model training Vercel: Hosting and content delivery Communication\n    Services: Transactional\
  \ email delivery'\ndpa:\n  available: true\n  url: null\n  text: All third-party processors are bound by data processing agreements (DPAs)\ndeletion:\n  route: Contact privacy@tunetrain.ai to exercise rights, including erasure\n  text: 'Right to Erasure (Art. 17): Request deletion of your personal data'\nrights:\n- right: Access\n  text: 'Right of Access (Art. 15): Request information about your personal data'\n- right: Rectification\n  text: 'Right to Rectification (Art. 16): Correct inaccurate personal data'\n- right: Erasure\n  text: 'Right to Erasure (Art. 17): Request deletion of your personal data'\n- right: Restrict processing\n  text: 'Right to Restrict Processing (Art. 18): Limit how we process your data'\n- right: Portability\n  text: 'Right to Data Portability (Art. 20): Receive your data in a portable format'\n- right: Object\n  text: 'Right to Object (Art. 21): Object to processing based on legitimate interest'\n- right: Withdraw consent\n  text: 'Right to Withdraw Consent:\
  \ Withdraw consent for consent-based processing'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tunetrain/privacy/tunetrain-privacy-policy.yml
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
summary_line: 28 quoted statements, read from TuneTrain.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Software-as-a-Service
- Machine Learning
- Fine-Tuning
---
