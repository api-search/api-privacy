---
api_specs:
- filename: lacuna-lacuna-music-api-api-openapi.yml
  format: yaml
  label: Lacuna Music API Events
  slug: lacuna-lacuna-music-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lacuna/openapi/lacuna-lacuna-music-api-api-openapi.yml
- filename: lacuna-music-api-openapi.yml
  format: yaml
  label: Lacuna Music API
  slug: lacuna-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lacuna/openapi/lacuna-music-api-openapi.yml
- filename: lacuna-account-api-openapi.yml
  format: yaml
  label: Lacuna Account API
  slug: lacuna-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lacuna/openapi/lacuna-account-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: OAuth profile information (display name, email address, and profile picture) provided by Your third-party authentication provider (Google or Apple)
  - category: financial
    text: 'Billing information (when You make a purchase): phone number, billing address, company name, and tax ID'
  - category: device
    text: Usage Data is collected automatically when using the Service.
  - category: location
    text: We collect Your IP address and may derive approximate location information (country, region, city) from it.
  - category: communication
    text: Account, consent, subscription, and transaction records are generally retained while Your Account is active.
  deletion:
    route: Account deletion control in the Website or App, or email support@lacuna.fm to request erasure
    text: To request erasure of retained Personal Data, including Google profile information and sign-in records, email support@lacuna.fm .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: To provide and maintain our Service , including to monitor the usage of our Service.
  - purpose: Manage account
    text: 'To manage Your Account: to manage Your registration as a user of the Service.'
  - purpose: AI feature processing
    text: When You use Our AI music or lyrics features, the audio, text prompts, lyrics, reference materials, and generation settings You provide are sent to third-party AI service providers solely to process Your request.
  - purpose: Private voice model training
    text: When You explicitly request a personal singing voice, We use the recording You provide to train Your private voice model.
  residency:
  - region: United Kingdom
    text: 'Country refers to: United Kingdom'
  retention:
  - period: null
    scope: Account, consent, subscription and transaction records
    text: Account, consent, subscription, and transaction records are generally retained while Your Account is active.
  - period: null
    scope: Private voices
    text: Private voices remain stored for reuse until You delete them; We do not currently apply an automatic expiry period for saved voices.
  - period: 24 hours
    scope: Unfinished uploads
    text: Unfinished uploads are scheduled for cleanup after 24 hours.
  - period: null
    scope: Usage Data
    text: Usage Data is generally retained for a shorter period of time, except when this data is used to strengthen the security or to improve the functionality of Our Service
  rights:
  - right: access, correction, erasure (Google sign-in information)
    text: You can email support@lacuna.fm to request access to, correction of, or erasure of stored Google profile and sign-in information.
  - right: withdraw AI data-sharing consent
    text: You can withdraw that consent at any time in the App under Account > Data & AI .
  role:
    text: Company (referred to as either "the Company", "We", "Us" or "Our" in this Agreement) refers to JOYLINK LTD, a company registered in England and Wales.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We do not sell Your Google sign-in information or use it to train general-purpose AI or machine-learning models.
  subprocessors:
    text: Our RVC service runs personal voice training and conversion on Modal or RunPod according to the configured provider. Where a recording needs vocal separation, Replicate processes the relevant audio through the separation model.
    url: null
  transfers:
  - mechanism: other
    text: The Company will take all steps reasonably necessary to ensure that Your data is treated securely and in accordance with this Privacy Policy and no transfer of Your Personal Data will take place to an organization or a country unless there are adequate controls in place
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lacuna
provenance_date: '2026-11-09'
provider_name: Lacuna
provider_slug: lacuna
slug: lacuna-privacy-policy
source_date: '2026-11-09'
source_filename: lacuna-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lacuna.fm/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lacuna\naid: lacuna\nurl: https://www.lacuna.fm/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Company (referred to as either \"the Company\", \"We\", \"Us\" or \"Our\" in this Agreement) refers to JOYLINK LTD,\n    a company registered in England and Wales.\ndata_categories:\n- category: identifying\n  text: OAuth profile information (display name, email address, and profile picture) provided by Your third-party\n    authentication provider (Google or Apple)\n- category: financial\n  text: 'Billing information (when You make a purchase): phone number, billing address, company name,\
  \ and tax ID'\n- category: device\n  text: Usage Data is collected automatically when using the Service.\n- category: location\n  text: We collect Your IP address and may derive approximate location information (country, region, city) from\n    it.\n- category: communication\n  text: Account, consent, subscription, and transaction records are generally retained while Your Account is active.\npurposes:\n- purpose: Provide and maintain the Service\n  text: To provide and maintain our Service , including to monitor the usage of our Service.\n- purpose: Manage account\n  text: 'To manage Your Account: to manage Your registration as a user of the Service.'\n- purpose: AI feature processing\n  text: When You use Our AI music or lyrics features, the audio, text prompts, lyrics, reference materials, and\n    generation settings You provide are sent to third-party AI service providers solely to process Your request.\n- purpose: Private voice model training\n  text: When You explicitly request a\
  \ personal singing voice, We use the recording You provide to train Your private\n    voice model.\nretention:\n- scope: Account, consent, subscription and transaction records\n  period: null\n  text: Account, consent, subscription, and transaction records are generally retained while Your Account is active.\n- scope: Private voices\n  period: null\n  text: Private voices remain stored for reuse until You delete them; We do not currently apply an automatic expiry\n    period for saved voices.\n- scope: Unfinished uploads\n  period: 24 hours\n  text: Unfinished uploads are scheduled for cleanup after 24 hours.\n- scope: Usage Data\n  period: null\n  text: Usage Data is generally retained for a shorter period of time, except when this data is used to strengthen\n    the security or to improve the functionality of Our Service\nresidency:\n- region: United Kingdom\n  text: 'Country refers to: United Kingdom'\ntransfers:\n- mechanism: other\n  text: The Company will take all steps reasonably\
  \ necessary to ensure that Your data is treated securely and in\n    accordance with this Privacy Policy and no transfer of Your Personal Data will take place to an organization\n    or a country unless there are adequate controls in place\nsubprocessors:\n  url: null\n  text: Our RVC service runs personal voice training and conversion on Modal or RunPod according to the configured\n    provider. Where a recording needs vocal separation, Replicate processes the relevant audio through the separation\n    model.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion control in the Website or App, or email support@lacuna.fm to request erasure\n  text: To request erasure of retained Personal Data, including Google profile information and sign-in records,\n    email support@lacuna.fm .\nrights:\n- right: access, correction, erasure (Google sign-in information)\n  text: You can email support@lacuna.fm to request access to, correction of, or erasure of stored\
  \ Google profile\n    and sign-in information.\n- right: withdraw AI data-sharing consent\n  text: You can withdraw that consent at any time in the App under Account > Data & AI .\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell Your Google sign-in information or use it to train general-purpose AI or machine-learning\n    models.\n"
source_yaml_url: https://artifacts.apis.io/lacuna/privacy/lacuna-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Lacuna's own page on 2026-11-09.
synthetic: false
tags:
- AI Music
- Music Generation
- AI Song Generator
- AI Lyrics Generator
- Audio
- MIDI
- Songwriting
- Generative AI
- MCP Server
- Agent Skills
- A2A
- Developer Tools
- Account
- OAuth
- Authentication
---
