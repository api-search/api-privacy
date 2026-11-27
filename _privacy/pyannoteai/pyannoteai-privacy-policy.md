---
api_specs:
- filename: pyannoteai-media-api-openapi.yml
  format: yaml
  label: PyannoteAI Media API
  slug: pyannoteai-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-media-api-openapi.yml
- filename: pyannoteai-streaming-api-openapi.yml
  format: yaml
  label: PyannoteAI Streaming API
  slug: pyannoteai-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-streaming-api-openapi.yml
- filename: pyannoteai-jobs-api-openapi.yml
  format: yaml
  label: PyannoteAI Jobs API
  slug: pyannoteai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-jobs-api-openapi.yml
- filename: pyannoteai-operations-api-openapi.yml
  format: yaml
  label: PyannoteAI Operations API
  slug: pyannoteai-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-operations-api-openapi.yml
- filename: pyannoteai-test-api-openapi.yml
  format: yaml
  label: PyannoteAI Test API
  slug: pyannoteai-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pyannoteai/openapi/pyannoteai-test-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identification data (e.g., surname, first name, email address, team name, professional contact details)
  - category: contact
    text: professional contact details
  - category: device
    text: Login data (e.g. logs, IP address)
  - category: behavioral
    text: Usage data (e.g., number, duration, type and status of jobs, models and options used, timestamps)
  - category: financial
    text: Payment and billing data (data related to your credit cards, purchase history, orders, invoices)
  deletion:
    route: Written request to support@pyannote.ai
    text: 'you can send your request to the following address: support@pyannote.ai'
  dpa:
    available: true
    text: Such relationship is governed by the Data Processing Agreement included in the applicable General Terms and Conditions or services agreement.
    url: null
  purposes:
  - purpose: Provide services through account
    text: To provide you with our services available on our Platform through your account
  - purpose: Contract operations and invoicing
    text: To perform operations related to contracts, including invoicing, and customer relationship management
  - purpose: Legal and regulatory compliance
    text: To comply with our legal and regulatory obligations
  - purpose: Recruitment
    text: To process your applications and to manage interview
  - purpose: CV database
    text: To create a CV database
  - purpose: Service analysis and improvement
    text: To analyze your use of the services, understand your expectations and improve the functionalities offered
  residency:
  - region: France
    text: Your personal data is hosted for the duration of the processing on the servers of the company AWS located in France.
  retention:
  - period: 2 years
    scope: Account data
    text: If your account is inactive for a period of 2 years, it will be deleted if you do not respond to our reactivation email.
  - period: 1 year
    scope: Connection logs
    text: Your connection logs are retained for 1 year.
  - period: 10 years
    scope: Invoices
    text: 'Invoices and the related supporting documents, including the usage statements on which they are based: 10 years.'
  - period: 18 months rolling after contract end
    scope: Job input data and metadata for billing
    text: 'Job input data, job metadata and voiceprint usage counts, retained for billing, invoice dispute, audit-trail and fraud-prevention purposes: 18 months rolling after contract end.'
  - period: null
    scope: Credit card data archive
    text: The data relating to your credit cards may be retained in an intermediate archive for a period of thirteen (13) months following the date of debit
  - period: two years
    scope: CV database
    text: Personal data is retained for two years from the last contact with the data subject.
  rights:
  - right: Access
    text: 'Right of access: you have the right to access all your personal data at any time as defined by article 15 of the GDPR.'
  - right: Rectification
    text: 'Right to rectification: you have the right to rectify your inaccurate, incomplete or obsolete personal data at any time'
  - right: Erasure
    text: 'Right to erasure (“right to be forgotten”): you have the right to request that your personal data be deleted'
  - right: Restriction
    text: 'Right to restriction of processing: you have the right to restrict the processing of your personal data in certain cases defined in article 18 of the GDPR.'
  - right: Portability
    text: 'Right to data portability: under specific conditions defined in article 20 of the GDPR'
  - right: Object
    text: 'Right to object: You have the right to object to the processing of your personal data as defined by article 21 of the GDPR.'
  - right: Withdraw consent
    text: Right to withdraw your consent at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Our processors, as listed here: https://trust.pyannote.ai/'
    url: https://trust.pyannote.ai/
  transfers:
  - mechanism: SCC
    text: the execution of Standard Contractual Clauses approved by the European Commission
  - mechanism: BCR
    text: the application of Binding Corporate Rules
  - mechanism: adequacy
    text: personal data are transferred to a country that has been recognized as ensuring an adequate level of protection by a decision of the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PyannoteAI
provenance_date: '2026-11-10'
provider_name: PyannoteAI
provider_slug: pyannoteai
slug: pyannoteai-privacy-policy
source_date: '2026-11-10'
source_filename: pyannoteai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.pyannote.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PyannoteAI\naid: pyannoteai\nurl: https://www.pyannote.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identification data (e.g., surname, first name, email address, team name, professional contact details)\n- category: contact\n  text: professional contact details\n- category: device\n  text: Login data (e.g. logs, IP address)\n- category: behavioral\n  text: Usage data (e.g., number, duration, type and status of jobs, models and options used, timestamps)\n- category: financial\n  text: Payment and billing data (data\
  \ related to your credit cards, purchase history, orders, invoices)\npurposes:\n- purpose: Provide services through account\n  text: To provide you with our services available on our Platform through your account\n- purpose: Contract operations and invoicing\n  text: To perform operations related to contracts, including invoicing, and customer relationship management\n- purpose: Legal and regulatory compliance\n  text: To comply with our legal and regulatory obligations\n- purpose: Recruitment\n  text: To process your applications and to manage interview\n- purpose: CV database\n  text: To create a CV database\n- purpose: Service analysis and improvement\n  text: To analyze your use of the services, understand your expectations and improve the functionalities offered\nretention:\n- scope: Account data\n  period: 2 years\n  text: If your account is inactive for a period of 2 years, it will be deleted if you do not respond to our reactivation\n    email.\n- scope: Connection logs\n  period:\
  \ 1 year\n  text: Your connection logs are retained for 1 year.\n- scope: Invoices\n  period: 10 years\n  text: 'Invoices and the related supporting documents, including the usage statements on which they are based:\n    10 years.'\n- scope: Job input data and metadata for billing\n  period: 18 months rolling after contract end\n  text: 'Job input data, job metadata and voiceprint usage counts, retained for billing, invoice dispute, audit-trail\n    and fraud-prevention purposes: 18 months rolling after contract end.'\n- scope: Credit card data archive\n  period: null\n  text: The data relating to your credit cards may be retained in an intermediate archive for a period of thirteen\n    (13) months following the date of debit\n- scope: CV database\n  period: two years\n  text: Personal data is retained for two years from the last contact with the data subject.\nresidency:\n- region: France\n  text: Your personal data is hosted for the duration of the processing on the servers of the company\
  \ AWS located\n    in France.\ntransfers:\n- mechanism: SCC\n  text: the execution of Standard Contractual Clauses approved by the European Commission\n- mechanism: BCR\n  text: the application of Binding Corporate Rules\n- mechanism: adequacy\n  text: personal data are transferred to a country that has been recognized as ensuring an adequate level of protection\n    by a decision of the European Commission\nsubprocessors:\n  url: https://trust.pyannote.ai/\n  text: 'Our processors, as listed here: https://trust.pyannote.ai/'\ndpa:\n  available: true\n  url: null\n  text: Such relationship is governed by the Data Processing Agreement included in the applicable General Terms\n    and Conditions or services agreement.\ndeletion:\n  route: Written request to support@pyannote.ai\n  text: 'you can send your request to the following address: support@pyannote.ai'\nrights:\n- right: Access\n  text: 'Right of access: you have the right to access all your personal data at any time as defined by\
  \ article\n    15 of the GDPR.'\n- right: Rectification\n  text: 'Right to rectification: you have the right to rectify your inaccurate, incomplete or obsolete personal\n    data at any time'\n- right: Erasure\n  text: 'Right to erasure (“right to be forgotten”): you have the right to request that your personal data be deleted'\n- right: Restriction\n  text: 'Right to restriction of processing: you have the right to restrict the processing of your personal data\n    in certain cases defined in article 18 of the GDPR.'\n- right: Portability\n  text: 'Right to data portability: under specific conditions defined in article 20 of the GDPR'\n- right: Object\n  text: 'Right to object: You have the right to object to the processing of your personal data as defined by article\n    21 of the GDPR.'\n- right: Withdraw consent\n  text: Right to withdraw your consent at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pyannoteai/privacy/pyannoteai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 31 quoted statements, read from PyannoteAI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Data
- Speech Recognition
- Speaker Diarization
- Audio
- Voice AI
- Machine Learning
- Transcription
- Streaming
- Webhook
- Real-Time
- A2A
---
