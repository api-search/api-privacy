---
api_specs:
- filename: openrouter-completions-api-openapi.yml
  format: yaml
  label: OpenRouter Completions API
  slug: openrouter-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-completions-api-openapi.yml
- filename: openrouter-credits-api-openapi.yml
  format: yaml
  label: OpenRouter Credits API
  slug: openrouter-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-credits-api-openapi.yml
- filename: openrouter-generation-api-openapi.yml
  format: yaml
  label: OpenRouter Generation API
  slug: openrouter-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-generation-api-openapi.yml
- filename: openrouter-keys-api-openapi.yml
  format: yaml
  label: OpenRouter Keys API
  slug: openrouter-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-keys-api-openapi.yml
- filename: openrouter-models-api-openapi.yml
  format: yaml
  label: OpenRouter Models API
  slug: openrouter-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-models-api-openapi.yml
- filename: openrouter-providers-api-openapi.yml
  format: yaml
  label: OpenRouter Providers API
  slug: openrouter-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-providers-api-openapi.yml
- filename: openrouter-chat-completions-api-openapi.yml
  format: yaml
  label: OpenRouter Chat Completions API
  slug: openrouter-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-chat-completions-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, mailing address, email address, and telephone number.
  - category: contact
    text: Records and copies of your correspondence (including email addresses), if you contact us.
  - category: financial
    text: Details of transactions you carry out through our Site and of the fulfillment of Credits purchases.
  - category: location
    text: Geolocation data, such as the general area from which your device accesses our Service based on information like its IP address, or precise location information you choose to provide
  - category: biometric
    text: Image, audio, video, and "biometric information".
  - category: behavioral
    text: Your search queries on the Site.
  - category: device
    text: Information about your computer and internet connection, including your IP address, operating system and browser type
  deletion:
    route: Email to [email protected]
    text: You may request deletion of your data by contacting us at [email protected] .
  dpa:
    available: null
    text: If you have a Data Processing Agreement with us, the terms of that agreement and our separate agreements with Model Providers govern how your data is handled by each Model Provider
    url: null
  purposes:
  - purpose: Providing the Service
    text: Transmitting your Inputs to third-party Model Providers for inference, and depending on the Model selected, for model training and improvement purposes.
  - purpose: Delivering interest-based ads
    text: Delivering interest-based ads (also known as personalized ads or targeted ads).
  - purpose: Keeping you secure and safe
    text: Keeping you secure and safe while using our Site, which requires us to process your personal data to combat spam, malware, malicious activities or security risks.
  residency:
  - region: US and other countries outside EEA and UK
    text: your personal data may be transferred to our servers in the US, or to other countries outside the European Economic Area (" EEA ") and the UK.
  retention:
  - period: null
    scope: Personal data generally
    text: We are subject to applicable laws on the retention of information and will retain your information for as long as is reasonably necessary to comply with our business and legal obligations and to meet regulatory and compliance requirements.
  - period: until you delete them or close your account
    scope: Uploaded Files (Files API)
    text: We retain Uploaded Files until you delete them or close your account.
  - period: null
    scope: Image, audio and video Inputs
    text: We do not persist image, audio or video files beyond the duration necessary to route the request, except as required for abuse detection, security, billing, or legal compliance.
  rights:
  - right: Right to know
    text: You have the right to know what personal data OpenRouter processes about you
  - right: Access and data portability
    text: You have the right to request a copy of the personal data we process about you, subject to certain exceptions and conditions.
  - right: Deletion
    text: You have the right to request that we delete personal data we have collected from you when you use our Service, subject to certain exceptions.
  - right: Correction
    text: You have the right to request that we correct inaccurate personal data we have retained about you, subject to certain exceptions.
  - right: Objection
    text: You have the right to object to processing of your personal data, subject to certain exceptions.
  - right: Restriction
    text: You have the right to restrict our processing of personal data in certain circumstances.
  - right: Withdrawal of consent
    text: Where our processing of your personal data is based on your consent, you have the right to withdraw consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: You can opt out of sharing your personal data for targeted advertising by following the directions in this section.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: adequacy decisions from the European Commission under Article 45 of the European Union's General Data Protection Regulation (GDPR)
  - mechanism: SCC
    text: standard contractual clauses approved by the European Commission under Article 46 of the GDPR
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OpenRouter
provenance_date: '2026-11-10'
provider_name: OpenRouter
provider_slug: openrouter
slug: openrouter-privacy-policy
source_date: '2026-11-10'
source_filename: openrouter-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://openrouter.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OpenRouter\naid: openrouter\nurl: https://openrouter.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, mailing address, email address, and telephone number.\n- category: contact\n  text: Records and copies of your correspondence (including email addresses), if you contact us.\n- category: financial\n  text: Details of transactions you carry out through our Site and of the fulfillment of Credits purchases.\n- category: location\n  text: Geolocation data, such as the general area from which your device accesses our Service\
  \ based on information\n    like its IP address, or precise location information you choose to provide\n- category: biometric\n  text: Image, audio, video, and \"biometric information\".\n- category: behavioral\n  text: Your search queries on the Site.\n- category: device\n  text: Information about your computer and internet connection, including your IP address, operating system and\n    browser type\npurposes:\n- purpose: Providing the Service\n  text: Transmitting your Inputs to third-party Model Providers for inference, and depending on the Model selected,\n    for model training and improvement purposes.\n- purpose: Delivering interest-based ads\n  text: Delivering interest-based ads (also known as personalized ads or targeted ads).\n- purpose: Keeping you secure and safe\n  text: Keeping you secure and safe while using our Site, which requires us to process your personal data to combat\n    spam, malware, malicious activities or security risks.\nretention:\n- scope: Personal data\
  \ generally\n  period: null\n  text: We are subject to applicable laws on the retention of information and will retain your information for as\n    long as is reasonably necessary to comply with our business and legal obligations and to meet regulatory and\n    compliance requirements.\n- scope: Uploaded Files (Files API)\n  period: until you delete them or close your account\n  text: We retain Uploaded Files until you delete them or close your account.\n- scope: Image, audio and video Inputs\n  period: null\n  text: We do not persist image, audio or video files beyond the duration necessary to route the request, except\n    as required for abuse detection, security, billing, or legal compliance.\nresidency:\n- region: US and other countries outside EEA and UK\n  text: your personal data may be transferred to our servers in the US, or to other countries outside the European\n    Economic Area (\" EEA \") and the UK.\ntransfers:\n- mechanism: adequacy\n  text: adequacy decisions from the\
  \ European Commission under Article 45 of the European Union's General Data Protection\n    Regulation (GDPR)\n- mechanism: SCC\n  text: standard contractual clauses approved by the European Commission under Article 46 of the GDPR\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: If you have a Data Processing Agreement with us, the terms of that agreement and our separate agreements\n    with Model Providers govern how your data is handled by each Model Provider\ndeletion:\n  route: Email to [email protected]\n  text: You may request deletion of your data by contacting us at [email protected] .\nrights:\n- right: Right to know\n  text: You have the right to know what personal data OpenRouter processes about you\n- right: Access and data portability\n  text: You have the right to request a copy of the personal data we process about you, subject to certain exceptions\n    and conditions.\n- right: Deletion\n  text: You have the right to request that\
  \ we delete personal data we have collected from you when you use our Service,\n    subject to certain exceptions.\n- right: Correction\n  text: You have the right to request that we correct inaccurate personal data we have retained about you, subject\n    to certain exceptions.\n- right: Objection\n  text: You have the right to object to processing of your personal data, subject to certain exceptions.\n- right: Restriction\n  text: You have the right to restrict our processing of personal data in certain circumstances.\n- right: Withdrawal of consent\n  text: Where our processing of your personal data is based on your consent, you have the right to withdraw consent\nsale_or_sharing:\n  stance: conditional\n  text: You can opt out of sharing your personal data for targeted advertising by following the directions in this\n    section.\n"
source_yaml_url: https://artifacts.apis.io/openrouter/privacy/openrouter-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from OpenRouter's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Gateways
- LLM
- Router
---
