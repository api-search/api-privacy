---
api_specs:
- filename: kugelaudio-dictionaries-api-openapi.yml
  format: yaml
  label: KugelAudio Dictionaries API
  slug: kugelaudio-dictionaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-dictionaries-api-openapi.yml
- filename: kugelaudio-models-api-openapi.yml
  format: yaml
  label: KugelAudio Models API
  slug: kugelaudio-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-models-api-openapi.yml
- filename: kugelaudio-voices-api-openapi.yml
  format: yaml
  label: KugelAudio Voices API
  slug: kugelaudio-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-voices-api-openapi.yml
- filename: kugelaudio-elevenlabs-compatible-api-openapi.yml
  format: yaml
  label: KugelAudio ElevenLabs compatible API
  slug: kugelaudio-elevenlabs-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-elevenlabs-compatible-api-openapi.yml
- filename: kugelaudio-projects-api-openapi.yml
  format: yaml
  label: KugelAudio Projects API
  slug: kugelaudio-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-projects-api-openapi.yml
- filename: kugelaudio-text-to-speech-api-openapi.yml
  format: yaml
  label: KugelAudio Text to Speech API
  slug: kugelaudio-text-to-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-text-to-speech-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: behavioral
    text: IP address device information browser information page views clicks browsing history
  - category: contact
    text: email address, first name, last name, payment details
  - category: financial
    text: payment details
  - category: communication
    text: 'Personal Data processed : email address, message content'
  - category: other
    text: reference recordings, derived voice features, avatar images
  - category: professional
    text: name, email address, company
  deletion:
    route: Account deletion in account settings with a 14 day grace period
    text: Users can delete their account themselves in the account settings. Deletion is carried out after a grace period of 14 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: analytics
    text: The services contained in this section enable the Owner to monitor and analyse web traffic and can be used to keep track of User behaviour.
  - purpose: handling payments
    text: Unless otherwise specified, this Application processes any payments by credit card, bank transfer or other means via external payment service providers.
  - purpose: voice cloning and voice avatars
    text: We store the recording, its transcript and voice features derived from it in order to generate speech in that voice
  residency:
  - region: France (Paris)
    text: 'Place of processing : France (Paris)'
  - region: Germany (Falkenstein)
    text: 'Place of processing : Germany (Falkenstein)'
  - region: United States (Oregon)
    text: 'Place of processing : United States (Oregon)'
  - region: Finland (Helsinki)
    text: 'Place of processing : Finland (Helsinki)'
  retention:
  - period: until you delete the voice
    scope: voice recordings
    text: The data stays stored until you delete the voice.
  - period: 30 days
    scope: earlier voice file versions
    text: Earlier versions of the files are removed 30 days after deletion
  - period: 6 months
    scope: job applications
    text: deleted 6 months after the decision if the applicant is not hired
  - period: 365 days
    scope: Leadfeeder cookies
    text: stored for up to 365 days
  rights:
  - right: Withdraw consent
    text: Withdraw their consent at any time.
  - right: Object to processing
    text: Object to processing of their Data.
  - right: Access
    text: Access their Data.
  - right: Rectification
    text: Verify and seek rectification.
  - right: Restriction
    text: Restrict the processing of their Data.
  - right: Erasure
    text: Have their Personal Data deleted or otherwise removed.
  - right: Portability
    text: Receive their Data and have it transferred to another controller.
  - right: Complaint
    text: Lodge a complaint.
  role:
    text: Owner and Data Controller KugelAudio GmbH Rosenthaler Str. 36, 10178 Berlin
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Trusted third parties help us to process it
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: KugelAudio
provenance_date: '2026-11-09'
provider_name: KugelAudio
provider_slug: kugelaudio
slug: kugelaudio-privacy-policy
source_date: '2026-11-09'
source_filename: kugelaudio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.kugelaudio.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: KugelAudio\naid: kugelaudio\nurl: https://www.kugelaudio.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Owner and Data Controller KugelAudio GmbH Rosenthaler Str. 36, 10178 Berlin\ndata_categories:\n- category: behavioral\n  text: IP address device information browser information page views clicks browsing history\n- category: contact\n  text: email address, first name, last name, payment details\n- category: financial\n  text: payment details\n- category: communication\n  text: 'Personal Data processed : email address, message content'\n- category: other\n  text: reference\
  \ recordings, derived voice features, avatar images\n- category: professional\n  text: name, email address, company\npurposes:\n- purpose: analytics\n  text: The services contained in this section enable the Owner to monitor and analyse web traffic and can be used\n    to keep track of User behaviour.\n- purpose: handling payments\n  text: Unless otherwise specified, this Application processes any payments by credit card, bank transfer or other\n    means via external payment service providers.\n- purpose: voice cloning and voice avatars\n  text: We store the recording, its transcript and voice features derived from it in order to generate speech in\n    that voice\nretention:\n- scope: voice recordings\n  period: until you delete the voice\n  text: The data stays stored until you delete the voice.\n- scope: earlier voice file versions\n  period: 30 days\n  text: Earlier versions of the files are removed 30 days after deletion\n- scope: job applications\n  period: 6 months\n  text: deleted\
  \ 6 months after the decision if the applicant is not hired\n- scope: Leadfeeder cookies\n  period: 365 days\n  text: stored for up to 365 days\nresidency:\n- region: France (Paris)\n  text: 'Place of processing : France (Paris)'\n- region: Germany (Falkenstein)\n  text: 'Place of processing : Germany (Falkenstein)'\n- region: United States (Oregon)\n  text: 'Place of processing : United States (Oregon)'\n- region: Finland (Helsinki)\n  text: 'Place of processing : Finland (Helsinki)'\ntransfers: []\nsubprocessors:\n  url: null\n  text: Trusted third parties help us to process it\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion in account settings with a 14 day grace period\n  text: Users can delete their account themselves in the account settings. Deletion is carried out after a grace\n    period of 14 days\nrights:\n- right: Withdraw consent\n  text: Withdraw their consent at any time.\n- right: Object to processing\n  text: Object to processing\
  \ of their Data.\n- right: Access\n  text: Access their Data.\n- right: Rectification\n  text: Verify and seek rectification.\n- right: Restriction\n  text: Restrict the processing of their Data.\n- right: Erasure\n  text: Have their Personal Data deleted or otherwise removed.\n- right: Portability\n  text: Receive their Data and have it transferred to another controller.\n- right: Complaint\n  text: Lodge a complaint.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kugelaudio/privacy/kugelaudio-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 28 quoted statements, read from KugelAudio's own page on 2026-11-09.
synthetic: false
tags:
- Voice
- Text-to-Speech
- Speech Synthesis
- Voice AI
- Voice Cloning
- Audio
- Artificial Intelligence
- Machine Learning
- Streaming
- Real-Time
- Conversational AI
- Europe
- Data Sovereignty
- GDPR
- Company
---
