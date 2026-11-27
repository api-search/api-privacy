---
api_specs:
- filename: autoderm-ai-dermatology-api-device-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API Device API
  slug: autoderm-ai-dermatology-api-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-device-api-openapi.yml
- filename: autoderm-ai-dermatology-api-inference-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API Inference API
  slug: autoderm-ai-dermatology-api-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-inference-api-openapi.yml
- filename: autoderm-ai-dermatology-api-system-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API System API
  slug: autoderm-ai-dermatology-api-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-system-api-openapi.yml
- filename: autoderm-ai-dermatology-api-utils-api-openapi.yml
  format: yaml
  label: Autoderm – AI Dermatology API Utils API
  slug: autoderm-ai-dermatology-api-utils-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoderm-ai-dermatology-api/openapi/autoderm-ai-dermatology-api-utils-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect identification and contact data such as your name, email address, and company details
  - category: financial
    text: Where you submit payment details to subscribe to our services, payment processing is handled by our provider Stripe.
  - category: health
    text: skin images submitted via the Autoderm API may be retained by us following the inference and used to improve and retrain our AI models
  - category: other
    text: We also collect aggregated, non-identifiable usage statistics linked to your API key
  deletion:
    route: email to support@autoderm.ai
    text: Consent may be withdrawn at any time by contacting support@autoderm.ai .
  dpa:
    available: true
    text: All processors are bound by data processing agreements.
    url: null
  purposes:
  - purpose: account management and contracted services
    text: We use this information to manage your account and provide the services you have contracted.
  - purpose: post-market surveillance
    text: for the purpose of post-market surveillance of the Autoderm medical device
  - purpose: improve and retrain AI models
    text: used to improve and retrain our AI models
  residency:
  - region: EU
    text: 'Google Cloud (EU): hosting, storage and data processing'
  retention:
  - period: for up to five additional years thereafter
    scope: contract and account data
    text: We retain this data for the duration of the contract and for up to five additional years thereafter to meet fiscal and liability obligations.
  - period: duration of the device lifecycle
    scope: post-market surveillance usage statistics
    text: This data is retained for the duration of the device lifecycle.
  rights:
  - right: GDPR rights (Articles 15-21)
    text: You maintain full control over your personal data in accordance with GDPR Articles 15–21 during the initial submission and analysis phases.
  - right: lodge a complaint
    text: You also have the right to lodge a complaint to your relevant privacy protection authority
  role:
    text: 'Controller: Autoderm'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not collect or sell personal data.
  subprocessors:
    text: 'Hetzner Online GmbH (Germany): hosting, storage and data processing'
    url: null
  transfers:
  - mechanism: SCC
    text: All third parties have signed with us the corresponding standard contractual clauses based on European requirements.
  - mechanism: other
    text: No transfers outside the EEA are made in connection with the processing described above.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Autoderm – AI Dermatology API
provenance_date: '2026-11-09'
provider_name: Autoderm – AI Dermatology API
provider_slug: autoderm-ai-dermatology-api
slug: autoderm-ai-dermatology-api-privacy-policy
source_date: '2026-11-09'
source_filename: autoderm-ai-dermatology-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://autoderm.ai/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Autoderm – AI Dermatology API\naid: autoderm-ai-dermatology-api\nurl: https://autoderm.ai/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller: Autoderm'\ndata_categories:\n- category: contact\n  text: we collect identification and contact data such as your name, email address, and company details\n- category: financial\n  text: Where you submit payment details to subscribe to our services, payment processing is handled by our provider\n    Stripe.\n- category: health\n  text: skin images submitted via the Autoderm API may be retained by us following the inference and\
  \ used to improve\n    and retrain our AI models\n- category: other\n  text: We also collect aggregated, non-identifiable usage statistics linked to your API key\npurposes:\n- purpose: account management and contracted services\n  text: We use this information to manage your account and provide the services you have contracted.\n- purpose: post-market surveillance\n  text: for the purpose of post-market surveillance of the Autoderm medical device\n- purpose: improve and retrain AI models\n  text: used to improve and retrain our AI models\nretention:\n- scope: contract and account data\n  period: for up to five additional years thereafter\n  text: We retain this data for the duration of the contract and for up to five additional years thereafter to meet\n    fiscal and liability obligations.\n- scope: post-market surveillance usage statistics\n  period: duration of the device lifecycle\n  text: This data is retained for the duration of the device lifecycle.\nresidency:\n- region: EU\n \
  \ text: 'Google Cloud (EU): hosting, storage and data processing'\ntransfers:\n- mechanism: SCC\n  text: All third parties have signed with us the corresponding standard contractual clauses based on European requirements.\n- mechanism: other\n  text: No transfers outside the EEA are made in connection with the processing described above.\nsubprocessors:\n  url: null\n  text: 'Hetzner Online GmbH (Germany): hosting, storage and data processing'\ndpa:\n  available: true\n  url: null\n  text: All processors are bound by data processing agreements.\ndeletion:\n  route: email to support@autoderm.ai\n  text: Consent may be withdrawn at any time by contacting support@autoderm.ai .\nrights:\n- right: GDPR rights (Articles 15-21)\n  text: You maintain full control over your personal data in accordance with GDPR Articles 15–21 during the initial\n    submission and analysis phases.\n- right: lodge a complaint\n  text: You also have the right to lodge a complaint to your relevant privacy protection\
  \ authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not collect or sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/autoderm-ai-dermatology-api/privacy/autoderm-ai-dermatology-api-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Autoderm – AI Dermatology API's own page on 2026-11-09.
synthetic: false
tags:
- dermatology-api
- ai-dermatology
- Medical Imaging
- Telehealth
- skin-analysis
- REST API
- OpenAPI
- Llms.txt
- ce-marked
- White Label
- Healthcare
- Medical AI
- Computer Vision
- Medical Devices
- ICD-10
- image-classification
- Clinical Decision Support
- triage
---
