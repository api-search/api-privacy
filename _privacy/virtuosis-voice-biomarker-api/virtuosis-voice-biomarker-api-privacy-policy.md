---
api_specs:
- filename: virtuosis-voice-biomarker-api-accounts-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Accounts API
  slug: virtuosis-voice-biomarker-api-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-accounts-api-openapi.yml
- filename: virtuosis-voice-biomarker-api-recordings-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Recordings API
  slug: virtuosis-voice-biomarker-api-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-recordings-api-openapi.yml
- filename: virtuosis-voice-biomarker-api-usage-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Usage API
  slug: virtuosis-voice-biomarker-api-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-usage-api-openapi.yml
- filename: virtuosis-voice-biomarker-api-ping-api-openapi.yml
  format: yaml
  label: Virtuosis Voice Biomarker API Ping API
  slug: virtuosis-voice-biomarker-api-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/openapi/virtuosis-voice-biomarker-api-ping-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: device
    text: IP address, browser, device, language, pages, timestamps, identifiers and logs.
  - category: identifying
    text: name, contact and organization details, user ID, settings, contract, subscription, payment and support records.
  - category: health
    text: health or wellbeing information, inferences, scores, reports and other submitted content.
  - category: biometric
    text: Voice is biometric data only if technically processed to identify or authenticate a person; we do not do this unless expressly agreed.
  deletion:
    route: privacy contact email
    text: Contact privacy[at]virtuosis.ch . We may verify identity.
  dpa:
    available: true
    text: Data Processing Addendum (DPA)
    url: null
  purposes:
  - purpose: provide and support Service
    text: we process data to provide and support the requested Service or contract
  - purpose: train models
    text: We do not use identifiable customer Service data to train models without written authorization and a lawful basis.
  - purpose: marketing and cookies
    text: We use consent for non-essential cookies and marketing where required.
  residency:
  - region: Netherlands
    text: Production Service data is hosted in Azure West Europe (Netherlands).
  - region: EEA
    text: Backups, if enabled, remain in the EEA and within the applicable HDS scope.
  retention:
  - period: null
    scope: raw audio
    text: raw audio is deleted after processing.
  - period: up to 30 days
    scope: export after service ends
    text: After the Service ends, data remains available for export for up to 30 days unless another period is agreed, then is deleted
  - period: without time limit
    scope: anonymized data
    text: Anonymized data may be kept without time limit.
  rights:
  - right: access
    text: you may request access, correction, deletion, restriction, portability or objection, and withdraw consent
  - right: complain to authority
    text: You may complain to the competent authority, including the authority where you live or work, the Swiss FDPIC, or the French CNIL if applicable.
  role:
    text: For our websites, Virtuosis Artificial Intelligence SA is controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Technical providers used to deliver the Services are listed in Section 6 of our DPA.
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers to a destination without adequate protection use applicable standard contractual clauses or another lawful safeguard
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Virtuosis Voice Biomarker API
provenance_date: '2026-11-10'
provider_name: Virtuosis Voice Biomarker API
provider_slug: virtuosis-voice-biomarker-api
slug: virtuosis-voice-biomarker-api-privacy-policy
source_date: '2026-11-10'
source_filename: virtuosis-voice-biomarker-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.virtuosis.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Virtuosis Voice Biomarker API\naid: virtuosis-voice-biomarker-api\nurl: https://www.virtuosis.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For our websites, Virtuosis Artificial Intelligence SA is controller.\ndata_categories:\n- category: device\n  text: IP address, browser, device, language, pages, timestamps, identifiers and logs.\n- category: identifying\n  text: name, contact and organization details, user ID, settings, contract, subscription, payment and support records.\n- category: health\n  text: health or wellbeing information, inferences, scores, reports and other\
  \ submitted content.\n- category: biometric\n  text: Voice is biometric data only if technically processed to identify or authenticate a person; we do not do\n    this unless expressly agreed.\npurposes:\n- purpose: provide and support Service\n  text: we process data to provide and support the requested Service or contract\n- purpose: train models\n  text: We do not use identifiable customer Service data to train models without written authorization and a lawful\n    basis.\n- purpose: marketing and cookies\n  text: We use consent for non-essential cookies and marketing where required.\nretention:\n- scope: raw audio\n  period: null\n  text: raw audio is deleted after processing.\n- scope: export after service ends\n  period: up to 30 days\n  text: After the Service ends, data remains available for export for up to 30 days unless another period is agreed,\n    then is deleted\n- scope: anonymized data\n  period: without time limit\n  text: Anonymized data may be kept without time limit.\n\
  residency:\n- region: Netherlands\n  text: Production Service data is hosted in Azure West Europe (Netherlands).\n- region: EEA\n  text: Backups, if enabled, remain in the EEA and within the applicable HDS scope.\ntransfers:\n- mechanism: SCC\n  text: Transfers to a destination without adequate protection use applicable standard contractual clauses or another\n    lawful safeguard\nsubprocessors:\n  url: null\n  text: Technical providers used to deliver the Services are listed in Section 6 of our DPA.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum (DPA)\ndeletion:\n  route: privacy contact email\n  text: Contact privacy[at]virtuosis.ch . We may verify identity.\nrights:\n- right: access\n  text: you may request access, correction, deletion, restriction, portability or objection, and withdraw consent\n- right: complain to authority\n  text: You may complain to the competent authority, including the authority where you live or work, the Swiss FDPIC,\n    or the French\
  \ CNIL if applicable.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/virtuosis-voice-biomarker-api/privacy/virtuosis-voice-biomarker-api-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Virtuosis Voice Biomarker API's own page on 2026-11-10.
synthetic: false
tags:
- Digital Health
- VoiceBiomarkers
- Speech Analysis
- acoustic analysis
- Medical Devices
- Mental Health
- Wellbeing
- neurodegenerative screening
- Telehealth
- Remote Monitoring
- communication coaching
- Clinical Research
- Health AI
- Clinical Decision Support
---
