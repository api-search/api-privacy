---
api_specs:
- filename: descript-api-endpoints-api-openapi.yml
  format: yaml
  label: Descript API Endpoints API
  slug: descript-api-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-api-endpoints-api-openapi.yml
- filename: descript-edit-in-descript-api-openapi.yml
  format: yaml
  label: Descript Edit in Descript API
  slug: descript-edit-in-descript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-edit-in-descript-api-openapi.yml
- filename: descript-export-from-descript-api-openapi.yml
  format: yaml
  label: Descript Export from Descript API
  slug: descript-export-from-descript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/descript/openapi/descript-export-from-descript-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: The types of information we collect may include your name, email address, postal address, password
  - category: financial
    text: we work with a third-party payment processor to collect and process your payment information
  - category: behavioral
    text: 'Log Information: We log information about your use of the Descript Service'
  - category: device
    text: 'Device Information: We collect information about the computer or mobile device you use to access the Descript Service'
  - category: biometric
    text: Generate voiceprints, which may be considered biometric data in some jurisdictions
  - category: biometric
    text: Generate face scans or facial geometry data (through our vendors) as needed to create your Descript avatar
  - category: communication
    text: content like video, voice, or audio recordings and images
  - category: professional
    text: This includes name, contact information, professional credentials and skills, educational and work history
  deletion:
    route: Account settings, or email support@descript.com
    text: If you wish to delete or deactivate your account, you can delete your Descript account in your account settings
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the service
    text: Provide, maintain, analyze, test, and improve the Descript Service and our technology
  - purpose: AI model training
    text: Personalize and improve the Descript Service and for research and development purposes including training our artificial intelligence models
  - purpose: Targeted advertising
    text: Target advertisements to you on third-party properties as described below
  - purpose: Voice authentication and fraud prevention
    text: Generate voiceprints, which may be considered biometric data in some jurisdictions, and use those voiceprints to authenticate you and prevent fraud
  - purpose: Security and fraud
    text: Detect, investigate and prevent security incidents, fraudulent transactions, and other illegal activities
  residency:
  - region: United States
    text: Descript is based in the United States and we process and store information in the U.S.
  retention:
  - period: up to three years after you last accessed your account, whichever occurs first
    scope: Voiceprints
    text: We will retain those voiceprints until the purpose of collection has been satisfied or for up to three years after you last accessed your account, whichever occurs first.
  - period: up to three years after you last accessed your account, whichever occurs first
    scope: Avatar facial geometry data (vendors)
    text: Our vendors will retain facial geometry data until the purpose of collection has been satisfied or for up to three years after you last accessed your account, whichever occurs first.
  - period: null
    scope: Personal data generally
    text: We store personal data for as long as necessary to carry out the purposes for which we originally collected it and for other legitimate business purposes
  rights:
  - right: Access, correction, and deletion
    text: You have the right to (1) request to know more about and access your personal information, (2) request deletion of your personal information, and (3) request correction of inaccurate personal information.
  - right: Object to or restrict processing
    text: You may also have the right to object to, or request that we restrict, certain processing.
  - right: Opt out of promotional emails
    text: You may opt out of receiving promotional emails from us by following the instructions in those emails.
  - right: Non-discrimination
    text: We will not treat you differently for exercising your privacy rights.
  - right: Lodge a complaint
    text: you have the right to lodge a complaint with the data privacy authority where you reside
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: allowed
    text: These activities may result in us selling or sharing identifiers, internet or other electronic network activity information, and inferences with our advertising partners
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We will take steps to ensure that your personal data receives an adequate level of protection in the jurisdictions in which we process it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Descript
provenance_date: '2026-11-09'
provider_name: Descript
provider_slug: descript
slug: descript-privacy-policy
source_date: '2026-11-09'
source_filename: descript-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.descript.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Descript\naid: descript\nurl: https://www.descript.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: The types of information we collect may include your name, email address, postal address, password\n- category: financial\n  text: we work with a third-party payment processor to collect and process your payment information\n- category: behavioral\n  text: 'Log Information: We log information about your use of the Descript Service'\n- category: device\n  text: 'Device Information: We collect information about the computer or mobile\
  \ device you use to access the Descript\n    Service'\n- category: biometric\n  text: Generate voiceprints, which may be considered biometric data in some jurisdictions\n- category: biometric\n  text: Generate face scans or facial geometry data (through our vendors) as needed to create your Descript avatar\n- category: communication\n  text: content like video, voice, or audio recordings and images\n- category: professional\n  text: This includes name, contact information, professional credentials and skills, educational and work history\npurposes:\n- purpose: Provide and improve the service\n  text: Provide, maintain, analyze, test, and improve the Descript Service and our technology\n- purpose: AI model training\n  text: Personalize and improve the Descript Service and for research and development purposes including training\n    our artificial intelligence models\n- purpose: Targeted advertising\n  text: Target advertisements to you on third-party properties as described below\n- purpose:\
  \ Voice authentication and fraud prevention\n  text: Generate voiceprints, which may be considered biometric data in some jurisdictions, and use those voiceprints\n    to authenticate you and prevent fraud\n- purpose: Security and fraud\n  text: Detect, investigate and prevent security incidents, fraudulent transactions, and other illegal activities\nretention:\n- scope: Voiceprints\n  period: up to three years after you last accessed your account, whichever occurs first\n  text: We will retain those voiceprints until the purpose of collection has been satisfied or for up to three years\n    after you last accessed your account, whichever occurs first.\n- scope: Avatar facial geometry data (vendors)\n  period: up to three years after you last accessed your account, whichever occurs first\n  text: Our vendors will retain facial geometry data until the purpose of collection has been satisfied or for up\n    to three years after you last accessed your account, whichever occurs first.\n- scope:\
  \ Personal data generally\n  period: null\n  text: We store personal data for as long as necessary to carry out the purposes for which we originally collected\n    it and for other legitimate business purposes\nresidency:\n- region: United States\n  text: Descript is based in the United States and we process and store information in the U.S.\ntransfers:\n- mechanism: other\n  text: We will take steps to ensure that your personal data receives an adequate level of protection in the jurisdictions\n    in which we process it.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings, or email support@descript.com\n  text: If you wish to delete or deactivate your account, you can delete your Descript account in your account settings\nrights:\n- right: Access, correction, and deletion\n  text: You have the right to (1) request to know more about and access your personal information, (2) request deletion\n    of your\
  \ personal information, and (3) request correction of inaccurate personal information.\n- right: Object to or restrict processing\n  text: You may also have the right to object to, or request that we restrict, certain processing.\n- right: Opt out of promotional emails\n  text: You may opt out of receiving promotional emails from us by following the instructions in those emails.\n- right: Non-discrimination\n  text: We will not treat you differently for exercising your privacy rights.\n- right: Lodge a complaint\n  text: you have the right to lodge a complaint with the data privacy authority where you reside\nsale_or_sharing:\n  stance: allowed\n  text: These activities may result in us selling or sharing identifiers, internet or other electronic network activity\n    information, and inferences with our advertising partners\n"
source_yaml_url: https://artifacts.apis.io/descript/privacy/descript-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Descript's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Audio Editing
- Captions
- Media
- Podcasts
- Transcription
- Video Editing
- Audio
---
