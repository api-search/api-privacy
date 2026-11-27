---
api_specs:
- filename: deepdub-dubbing-api-openapi.yml
  format: yaml
  label: Deepdub Dubbing API
  slug: deepdub-dubbing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-dubbing-api-openapi.yml
- filename: deepdub-gender-detection-api-openapi.yml
  format: yaml
  label: Deepdub Gender Detection API
  slug: deepdub-gender-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-gender-detection-api-openapi.yml
- filename: deepdub-infrastructure-api-openapi.yml
  format: yaml
  label: Deepdub Infrastructure API
  slug: deepdub-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-infrastructure-api-openapi.yml
- filename: deepdub-issues-api-openapi.yml
  format: yaml
  label: Deepdub Issues API
  slug: deepdub-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-issues-api-openapi.yml
- filename: deepdub-tts-api-openapi.yml
  format: yaml
  label: Deepdub TTS API
  slug: deepdub-tts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-tts-api-openapi.yml
- filename: deepdub-usage-api-openapi.yml
  format: yaml
  label: Deepdub Usage API
  slug: deepdub-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-usage-api-openapi.yml
- filename: deepdub-voice-api-openapi.yml
  format: yaml
  label: Deepdub Voice API
  slug: deepdub-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-voice-api-openapi.yml
- filename: deepdub-provenance-api-openapi.yml
  format: yaml
  label: Deepdub Provenance API
  slug: deepdub-provenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdub/openapi/deepdub-provenance-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address, full name, company/employer name and job title
  - category: device
    text: your IP address, internet service provider, search history, cookie information, type of browser
  - category: behavioral
    text: which pages of the Services you viewed, exit and entrance pages and your use time of the Services
  - category: communication
    text: When you request a demo, send an email or other communication to the Company, we may retain those communications
  deletion:
    route: email
    text: You may exercise the above rights by sending a request to privacy@deepdub.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, operate, maintain and improve Services
    text: In order to provide, operate, maintain and improve our Services
  - purpose: marketing and customer relations
    text: for marketing and customer relations purposes
  - purpose: targeted advertising
    text: provide targeted advertisements or interest based advertisements
  - purpose: improve models and Services
    text: We also use Personal Data provided to us through the Services to improve our models and the Services we provide.
  retention:
  - period: null
    scope: Personal Data
    text: We retain your Personal Data only for as long as reasonably necessary for the purposes for which it was collected or to comply with any applicable legal or ethical reporting or document retention requirements.
  rights:
  - right: access and rectification
    text: We allow our users the option to access and obtain a copy of their Personal Data and to rectify such Personal Data if it is not accurate, complete or updated.
  - right: delete or restrict processing
    text: You have the right to delete your Personal Data or restrict its processing.
  - right: withdraw consent
    text: You have the right to withdraw your consent to the processing of your Personal Data.
  - right: data portability
    text: Where technically feasible, you have the right to ask to transfer your Personal Data in accordance with your right to data portability.
  - right: lodge a complaint
    text: You also have the right to lodge a complaint with a data protection supervisory authority regarding the processing of your Personal Data.
  role:
    text: 'Personal Data We Collect and How We Use It. Summary: We collect Personal Data about our clients and their representatives and users of our Services.'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Transfers to Israel are made based on an adequacy ruling by the EU Commission.
  - mechanism: SCC
    text: Transfers to the USA are made based on the Standard Contractual Clauses published by the EU Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Deepdub
provenance_date: '2026-11-09'
provider_name: Deepdub
provider_slug: deepdub
slug: deepdub-privacy-policy
source_date: '2026-11-09'
source_filename: deepdub-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://deepdub.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Deepdub\naid: deepdub\nurl: https://deepdub.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Personal Data We Collect and How We Use It. Summary: We collect Personal Data about our clients and their\n    representatives and users of our Services.'\ndata_categories:\n- category: identifying\n  text: email address, full name, company/employer name and job title\n- category: device\n  text: your IP address, internet service provider, search history, cookie information, type of browser\n- category: behavioral\n  text: which pages of the Services you viewed, exit and entrance pages\
  \ and your use time of the Services\n- category: communication\n  text: When you request a demo, send an email or other communication to the Company, we may retain those communications\npurposes:\n- purpose: provide, operate, maintain and improve Services\n  text: In order to provide, operate, maintain and improve our Services\n- purpose: marketing and customer relations\n  text: for marketing and customer relations purposes\n- purpose: targeted advertising\n  text: provide targeted advertisements or interest based advertisements\n- purpose: improve models and Services\n  text: We also use Personal Data provided to us through the Services to improve our models and the Services we\n    provide.\nretention:\n- scope: Personal Data\n  period: null\n  text: We retain your Personal Data only for as long as reasonably necessary for the purposes for which it was\n    collected or to comply with any applicable legal or ethical reporting or document retention requirements.\nresidency: []\ntransfers:\n\
  - mechanism: adequacy\n  text: Transfers to Israel are made based on an adequacy ruling by the EU Commission.\n- mechanism: SCC\n  text: Transfers to the USA are made based on the Standard Contractual Clauses published by the EU Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: You may exercise the above rights by sending a request to privacy@deepdub.ai .\nrights:\n- right: access and rectification\n  text: We allow our users the option to access and obtain a copy of their Personal Data and to rectify such Personal\n    Data if it is not accurate, complete or updated.\n- right: delete or restrict processing\n  text: You have the right to delete your Personal Data or restrict its processing.\n- right: withdraw consent\n  text: You have the right to withdraw your consent to the processing of your Personal Data.\n- right: data portability\n  text: Where technically feasible, you have the right to\
  \ ask to transfer your Personal Data in accordance with\n    your right to data portability.\n- right: lodge a complaint\n  text: You also have the right to lodge a complaint with a data protection supervisory authority regarding the\n    processing of your Personal Data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deepdub/privacy/deepdub-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from Deepdub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice
- Text-to-Speech
- Dubbing
- Localization
- Speech Synthesis
- Voice Cloning
- Media
- Artificial Intelligence
- Audio
---
