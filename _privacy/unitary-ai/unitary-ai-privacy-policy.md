---
api_specs:
- filename: unitary-ai-api-authentication-api-openapi.yml
  format: yaml
  label: Unitary AI API Authentication API
  slug: unitary-ai-api-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unitary-ai/openapi/unitary-ai-api-authentication-api-openapi.yml
- filename: unitary-ai-detoxify-api-openapi.yml
  format: yaml
  label: Unitary AI Detoxify API
  slug: unitary-ai-detoxify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unitary-ai/openapi/unitary-ai-detoxify-api-openapi.yml
- filename: unitary-ai-items-characteristics-api-openapi.yml
  format: yaml
  label: Unitary AI Items & Characteristics API
  slug: unitary-ai-items-characteristics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unitary-ai/openapi/unitary-ai-items-characteristics-api-openapi.yml
- filename: unitary-ai-moderation-api-openapi.yml
  format: yaml
  label: Unitary AI Moderation API
  slug: unitary-ai-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unitary-ai/openapi/unitary-ai-moderation-api-openapi.yml
- filename: unitary-ai-policy-classification-api-openapi.yml
  format: yaml
  label: Unitary AI Policy Classification API
  slug: unitary-ai-policy-classification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unitary-ai/openapi/unitary-ai-policy-classification-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: we will require the name, email address, phone number and job title of our primary contact on the customer side
  - category: professional
    text: job title of our primary contact on the customer side
  - category: identifying
    text: The data may be text, image or video that may contain personal data that could be personally identifiable.
  - category: professional
    text: your name, CV, email address, phone number and interview notes
  - category: device
    text: Cookies are text files placed on your hard drive by a web page server when you visit a website
  deletion:
    route: email to contact@unitary.ai
    text: Please contact us by sending an email to contact@unitary.ai if you wish to make a request under your rights
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: manage contractual relationship
    text: in order to manage our contractual relationship
  - purpose: content classification and moderation
    text: Customers on both products will provide data to Unitary for content classification, moderation or customer operations task completion
  - purpose: machine learning and refinement
    text: our Engineering Team require data for the purpose of machine learning and refinement of our systems
  - purpose: recruitment
    text: to manage your recruitment process
  - purpose: marketing newsletter
    text: to add to a marketing list in order to send a regular newsletter
  residency:
  - region: US
    text: Our primary AWS server is in US where we store most customer data, but upon customer request we may also store data in the EU.
  - region: EU
    text: upon customer request we may also store data in the EU
  - region: UK or EEA
    text: We use applications that store data in the UK or EEA GDPR zone, or countries deemed ‘adequate’ under GDPR.
  retention:
  - period: 6 years after it has ended
    scope: customer account data
    text: We keep customer account data mentioned for the duration of the account with us and for 6 years after it has ended
  - period: 48 hours
    scope: customer media files
    text: Media files provided by our customers and analysed through our platform are usually deleted 48 hours after the safety score report has been created.
  - period: 6 months
    scope: job applicants not hired
    text: Otherwise we will keep your data during your the interview process and remove it after 6 months.
  - period: null
    scope: engineering media files
    text: Media files are pseudonymised and only kept while they are being used for training purposes.
  rights:
  - right: access
    text: The right of access You have the right to ask us for copies of the data we hold about you.
  - right: rectification
    text: The right to rectification You have the right to ask us to rectify the personal information you think is inaccurate
  - right: erasure
    text: The right to erasure You have the right to ask us to erase your personal information, in some circumstances
  - right: restrict processing
    text: The right to restrict processing You have the right to ask us to restrict the processing of your personal information for a period of time in some circumstances
  - right: object
    text: The right to object You have the right to ask us to stop processing your personal information in some circumstances
  - right: data portability
    text: The right to data portability You have the right to ask that we transfer the personal information you gave us to another organisation
  role:
    text: This notice applies wherever we decide why and how we process personal data (and therefore act as a Data Controller under data protection law). It also covers the personal data we process when we act on behalf of our clients (and therefore act as a Data Processor under data protection law).
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We also have subprocessors like OpenAI that may store data in the US.
    url: null
  transfers:
  - mechanism: DPF
    text: Privacy Framework Certification
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) and the UK Addendum where appropriate
  - mechanism: other
    text: the UK International Data Transfer Agreement (IDTA)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Unitary AI
provenance_date: '2026-11-10'
provider_name: Unitary AI
provider_slug: unitary-ai
slug: unitary-ai-privacy-policy
source_date: '2026-11-10'
source_filename: unitary-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.unitary.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Unitary AI\naid: unitary-ai\nurl: https://www.unitary.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This notice applies wherever we decide why and how we process personal data (and therefore act as a Data\n    Controller under data protection law). It also covers the personal data we process when we act on behalf of\n    our clients (and therefore act as a Data Processor under data protection law).\ndata_categories:\n- category: contact\n  text: we will require the name, email address, phone number and job title of our primary contact on the customer\n    side\n- category: professional\n\
  \  text: job title of our primary contact on the customer side\n- category: identifying\n  text: The data may be text, image or video that may contain personal data that could be personally identifiable.\n- category: professional\n  text: your name, CV, email address, phone number and interview notes\n- category: device\n  text: Cookies are text files placed on your hard drive by a web page server when you visit a website\npurposes:\n- purpose: manage contractual relationship\n  text: in order to manage our contractual relationship\n- purpose: content classification and moderation\n  text: Customers on both products will provide data to Unitary for content classification, moderation or customer\n    operations task completion\n- purpose: machine learning and refinement\n  text: our Engineering Team require data for the purpose of machine learning and refinement of our systems\n- purpose: recruitment\n  text: to manage your recruitment process\n- purpose: marketing newsletter\n  text: to\
  \ add to a marketing list in order to send a regular newsletter\nretention:\n- scope: customer account data\n  period: 6 years after it has ended\n  text: We keep customer account data mentioned for the duration of the account with us and for 6 years after it\n    has ended\n- scope: customer media files\n  period: 48 hours\n  text: Media files provided by our customers and analysed through our platform are usually deleted 48 hours after\n    the safety score report has been created.\n- scope: job applicants not hired\n  period: 6 months\n  text: Otherwise we will keep your data during your the interview process and remove it after 6 months.\n- scope: engineering media files\n  period: null\n  text: Media files are pseudonymised and only kept while they are being used for training purposes.\nresidency:\n- region: US\n  text: Our primary AWS server is in US where we store most customer data, but upon customer request we may also\n    store data in the EU.\n- region: EU\n  text: upon customer\
  \ request we may also store data in the EU\n- region: UK or EEA\n  text: We use applications that store data in the UK or EEA GDPR zone, or countries deemed ‘adequate’ under GDPR.\ntransfers:\n- mechanism: DPF\n  text: Privacy Framework Certification\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) and the UK Addendum where appropriate\n- mechanism: other\n  text: the UK International Data Transfer Agreement (IDTA)\nsubprocessors:\n  url: null\n  text: We also have subprocessors like OpenAI that may store data in the US.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to contact@unitary.ai\n  text: Please contact us by sending an email to contact@unitary.ai if you wish to make a request under your rights\nrights:\n- right: access\n  text: The right of access You have the right to ask us for copies of the data we hold about you.\n- right: rectification\n  text: The right to rectification You have the right to ask us to rectify the personal information\
  \ you think is\n    inaccurate\n- right: erasure\n  text: The right to erasure You have the right to ask us to erase your personal information, in some circumstances\n- right: restrict processing\n  text: The right to restrict processing You have the right to ask us to restrict the processing of your personal\n    information for a period of time in some circumstances\n- right: object\n  text: The right to object You have the right to ask us to stop processing your personal information in some circumstances\n- right: data portability\n  text: The right to data portability You have the right to ask that we transfer the personal information you gave\n    us to another organisation\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unitary-ai/privacy/unitary-ai-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Unitary AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Content Moderation
- Trust and Safety
- Artificial Intelligence
- Machine Learning
- Computer Vision
- Video
- Virtual Agents
---
