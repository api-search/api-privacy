---
api_specs:
- filename: facesign-ai-avatars-api-openapi.yml
  format: yaml
  label: FaceSign Avatars API
  slug: facesign-ai-avatars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facesign-ai/openapi/facesign-ai-avatars-api-openapi.yml
- filename: facesign-ai-langs-api-openapi.yml
  format: yaml
  label: FaceSign Langs API
  slug: facesign-ai-langs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facesign-ai/openapi/facesign-ai-langs-api-openapi.yml
- filename: facesign-ai-sessions-api-openapi.yml
  format: yaml
  label: FaceSign Sessions API
  slug: facesign-ai-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facesign-ai/openapi/facesign-ai-sessions-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Facial biometric data, voice patterns, and behavioral signals collected during verification sessions.
  - category: device
    text: Device type, operating system, browser information, IP address, and geolocation.
  - category: behavioral
    text: Pages visited, referral source, and similar usage data collected when you browse our websites.
  - category: communication
    text: conversation transcripts, interaction patterns, and verification outcomes.
  - category: contact
    text: Information provided by Customers to facilitate verification (e.g., name, email, account identifiers)
  deletion:
    route: Contact FaceSign by email to request deletion of demonstration sessions; deletion of verification data on request or via Customer.
    text: You can ask us to delete your demonstration session at any time by contacting [email protected] , and we will do so.
  dpa:
    available: true
    text: for enterprise customers, any executed Data Processing Agreement (DPA).
    url: null
  purposes:
  - purpose: Providing verification services
    text: Providing identity verification and trust-decisioning services as instructed by our Customers.
  - purpose: Fraud detection
    text: Detecting and preventing fraud, including deepfakes, synthetic identities, and coercion.
  - purpose: Improving accuracy
    text: Improving the accuracy and reliability of our verification technology, using de-identified, aggregated data that does not include biometric data.
  - purpose: Account management
    text: Managing Customer accounts, billing, and support.
  residency:
  - region: United States
    text: FaceSign currently processes and stores verification data in the United States.
  retention:
  - period: approximately 24 hours
    scope: Customer verification media
    text: By default, captured media is automatically deleted within approximately 24 hours.
  - period: up to 24 months
    scope: FaceSign demonstration sessions
    text: We retain demonstration session media and the associated session record for up to 24 months
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate personal data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data, subject to legal retention requirements.'
  - right: Portability
    text: 'Portability: Request your data in a structured, machine-readable format.'
  - right: Objection & restriction
    text: 'Objection & restriction: Object to or restrict certain processing of your personal data.'
  - right: Consent withdrawal
    text: 'Consent withdrawal: Withdraw consent to biometric processing at any time, without affecting processing already performed.'
  role:
    text: For verification data, the Customer is the data controller and FaceSign acts as a data processor on the Customer's behalf and instructions.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: A current subprocessor list is available on request to [email protected] .
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses and the UK International Data Transfer Addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FaceSign
provenance_date: '2026-11-09'
provider_name: FaceSign
provider_slug: facesign-ai
slug: facesign-ai-privacy-policy
source_date: '2026-11-09'
source_filename: facesign-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.facesign.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FaceSign\naid: facesign-ai\nurl: https://www.facesign.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For verification data, the Customer is the data controller and FaceSign acts as a data processor on the\n    Customer's behalf and instructions.\ndata_categories:\n- category: identifying\n  text: Facial biometric data, voice patterns, and behavioral signals collected during verification sessions.\n- category: device\n  text: Device type, operating system, browser information, IP address, and geolocation.\n- category: behavioral\n  text: Pages visited, referral source, and similar usage\
  \ data collected when you browse our websites.\n- category: communication\n  text: conversation transcripts, interaction patterns, and verification outcomes.\n- category: contact\n  text: Information provided by Customers to facilitate verification (e.g., name, email, account identifiers)\npurposes:\n- purpose: Providing verification services\n  text: Providing identity verification and trust-decisioning services as instructed by our Customers.\n- purpose: Fraud detection\n  text: Detecting and preventing fraud, including deepfakes, synthetic identities, and coercion.\n- purpose: Improving accuracy\n  text: Improving the accuracy and reliability of our verification technology, using de-identified, aggregated data\n    that does not include biometric data.\n- purpose: Account management\n  text: Managing Customer accounts, billing, and support.\nretention:\n- scope: Customer verification media\n  period: approximately 24 hours\n  text: By default, captured media is automatically deleted\
  \ within approximately 24 hours.\n- scope: FaceSign demonstration sessions\n  period: up to 24 months\n  text: We retain demonstration session media and the associated session record for up to 24 months\nresidency:\n- region: United States\n  text: FaceSign currently processes and stores verification data in the United States.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses and the\n    UK International Data Transfer Addendum.\nsubprocessors:\n  url: null\n  text: A current subprocessor list is available on request to [email protected] .\ndpa:\n  available: true\n  url: null\n  text: for enterprise customers, any executed Data Processing Agreement (DPA).\ndeletion:\n  route: Contact FaceSign by email to request deletion of demonstration sessions; deletion of verification data\n    on request or via Customer.\n  text: You can ask us to delete your demonstration session at any time by contacting [email\
  \ protected] , and we\n    will do so.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate personal data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data, subject to legal retention requirements.'\n- right: Portability\n  text: 'Portability: Request your data in a structured, machine-readable format.'\n- right: Objection & restriction\n  text: 'Objection & restriction: Object to or restrict certain processing of your personal data.'\n- right: Consent withdrawal\n  text: 'Consent withdrawal: Withdraw consent to biometric processing at any time, without affecting processing\n    already performed.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/facesign-ai/privacy/facesign-ai-privacy-policy.yml
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
- sale_or_sharing
summary_line: 24 quoted statements, read from FaceSign's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Identity Verification
- Deepfake Detection
- Liveness Detection
- Biometrics
---
