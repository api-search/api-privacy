---
api_specs:
- filename: languagetool-check-api-openapi.yml
  format: yaml
  label: LanguageTool Check API
  slug: languagetool-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/languagetool/openapi/languagetool-check-api-openapi.yml
- filename: languagetool-languages-api-openapi.yml
  format: yaml
  label: LanguageTool Languages API
  slug: languagetool-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/languagetool/openapi/languagetool-languages-api-openapi.yml
- filename: languagetool-words-api-openapi.yml
  format: yaml
  label: LanguageTool Words API
  slug: languagetool-words-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/languagetool/openapi/languagetool-words-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and last name, email and/or physical address, and phone number
  - category: financial
    text: we will collect your payment information including card holder name, billing city, state, postal code and country, card type, the first 6 or last 4 digits of payment card, and card expiration date
  - category: location
    text: General Location Information including your approximated city, state and/or country based on your IP address.
  - category: device
    text: Device and Connection Data such as your internet protocol (IP) address, Internet service provider, operating system, computer model, language settings and CPU details, and web browser type.
  - category: behavioral
    text: Usage or Activity Data including activity and events that are logged when you use our Services
  - category: communication
    text: When you communicate with us in written, email, or in-product for any reason
  - category: biometric
    text: Some of our Services may also request your image and an image of your ID to perform biometric identification verification.
  deletion:
    route: Privacy Request Webform
    text: You may submit a request to exercise any of your individual privacy rights under applicable law by using our Privacy Request Webform .
  dpa:
    available: true
    text: When you register for LanguageTool’s premium services with a Team Plan, we process any personal data we collect as described in the LanguageTool Business Data Processing Agreement available at https://languagetool.org/legal/dpa
    url: https://languagetool.org/legal/dpa
  purposes:
  - purpose: Providing services
    text: Providing any of our Services to you, including operating and maintaining any of our Services, creating and managing user accounts for the Services
  - purpose: Improving services
    text: We perform internal analytics and applied machine learning on data about your engagement with our Services to help develop and improve our Services.
  - purpose: Advertising
    text: Showing you advertisements, including interest-based or online behavioral advertising (with your consent or otherwise in accordance with applicable law).
  - purpose: Safety and fraud prevention
    text: Protecting the rights, property or safety of you, Learneo, or another party, by preventing, detecting, investigating and responding to safety, security, fraud and abuse risks.
  residency:
  - region: Offices
    text: Learneo has offices located in the United States, India, The Netherlands, Germany, and Canada
  retention:
  - period: null
    scope: Account data
    text: we retain personal data about you for as long as you have an open account with us, and for a commercially reasonable period needed to fulfill the purposes described in this Privacy Policy.
  rights:
  - right: access, deletion, correction, restriction
    text: including the right to know details about our privacy practices, to access , delete or correct, or restrict your personal data
  - right: objection / opt-out
    text: or to object or opt-out of certain processing activities, and to revoke consent (as applicable)
  - right: opt out of sale or sharing (US)
    text: If you are in the US, this includes the right to opt-out of the sale or sharing of your personal data
  role:
    text: Learneo, Inc. is the data controller responsible for your personal data.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: If you are in the US, this includes the right to opt-out of the sale or sharing of your personal data, which may include us sharing your information with third party advertising partners as described in this Privacy Policy.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: we are certified and comply with the EU-U.S. and Swiss-U.S. Data Privacy Frameworks (“DPF”)
  - mechanism: SCC
    text: Transfers to countries that don't have an adequacy decision typically take place on the basis of the European Commission-approved standard contractual data protection clauses
  - mechanism: adequacy
    text: we rely on the European Commission's adequacy decision for Israel and the UK.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LanguageTool
provenance_date: '2026-11-09'
provider_name: LanguageTool
provider_slug: languagetool
slug: languagetool-privacy-policy
source_date: '2026-11-09'
source_filename: languagetool-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://languagetool.org/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LanguageTool\naid: languagetool\nurl: https://languagetool.org/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Learneo, Inc. is the data controller responsible for your personal data.\ndata_categories:\n- category: identifying\n  text: first and last name, email and/or physical address, and phone number\n- category: financial\n  text: we will collect your payment information including card holder name, billing city, state, postal code and\n    country, card type, the first 6 or last 4 digits of payment card, and card expiration date\n- category: location\n  text: General Location\
  \ Information including your approximated city, state and/or country based on your IP address.\n- category: device\n  text: Device and Connection Data such as your internet protocol (IP) address, Internet service provider, operating\n    system, computer model, language settings and CPU details, and web browser type.\n- category: behavioral\n  text: Usage or Activity Data including activity and events that are logged when you use our Services\n- category: communication\n  text: When you communicate with us in written, email, or in-product for any reason\n- category: biometric\n  text: Some of our Services may also request your image and an image of your ID to perform biometric identification\n    verification.\npurposes:\n- purpose: Providing services\n  text: Providing any of our Services to you, including operating and maintaining any of our Services, creating\n    and managing user accounts for the Services\n- purpose: Improving services\n  text: We perform internal analytics and applied\
  \ machine learning on data about your engagement with our Services\n    to help develop and improve our Services.\n- purpose: Advertising\n  text: Showing you advertisements, including interest-based or online behavioral advertising (with your consent\n    or otherwise in accordance with applicable law).\n- purpose: Safety and fraud prevention\n  text: Protecting the rights, property or safety of you, Learneo, or another party, by preventing, detecting, investigating\n    and responding to safety, security, fraud and abuse risks.\nretention:\n- scope: Account data\n  period: null\n  text: we retain personal data about you for as long as you have an open account with us, and for a commercially\n    reasonable period needed to fulfill the purposes described in this Privacy Policy.\nresidency:\n- region: Offices\n  text: Learneo has offices located in the United States, India, The Netherlands, Germany, and Canada\ntransfers:\n- mechanism: DPF\n  text: we are certified and comply with the\
  \ EU-U.S. and Swiss-U.S. Data Privacy Frameworks (“DPF”)\n- mechanism: SCC\n  text: Transfers to countries that don't have an adequacy decision typically take place on the basis of the European\n    Commission-approved standard contractual data protection clauses\n- mechanism: adequacy\n  text: we rely on the European Commission's adequacy decision for Israel and the UK.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://languagetool.org/legal/dpa\n  text: When you register for LanguageTool’s premium services with a Team Plan, we process any personal data we\n    collect as described in the LanguageTool Business Data Processing Agreement available at https://languagetool.org/legal/dpa\ndeletion:\n  route: Privacy Request Webform\n  text: You may submit a request to exercise any of your individual privacy rights under applicable law by using\n    our Privacy Request Webform .\nrights:\n- right: access, deletion, correction, restriction\n  text: including\
  \ the right to know details about our privacy practices, to access , delete or correct, or restrict\n    your personal data\n- right: objection / opt-out\n  text: or to object or opt-out of certain processing activities, and to revoke consent (as applicable)\n- right: opt out of sale or sharing (US)\n  text: If you are in the US, this includes the right to opt-out of the sale or sharing of your personal data\nsale_or_sharing:\n  stance: conditional\n  text: If you are in the US, this includes the right to opt-out of the sale or sharing of your personal data, which\n    may include us sharing your information with third party advertising partners as described in this Privacy Policy.\n"
source_yaml_url: https://artifacts.apis.io/languagetool/privacy/languagetool-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from LanguageTool's own page on 2026-11-09.
synthetic: false
tags:
- Grammar
- Language
- Proofreading
- Spell Check
- Style Check
- Text Analysis
---
