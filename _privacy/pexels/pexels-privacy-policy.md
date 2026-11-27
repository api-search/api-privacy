---
api_specs:
- filename: pexels-collections-api-openapi.yml
  format: yaml
  label: Pexels Collections API
  slug: pexels-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-collections-api-openapi.yml
- filename: pexels-photos-api-openapi.yml
  format: yaml
  label: Pexels Photos API
  slug: pexels-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-photos-api-openapi.yml
- filename: pexels-videos-api-openapi.yml
  format: yaml
  label: Pexels Videos API
  slug: pexels-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-videos-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: your first and last name, date of birth, gender, the city and country you live in
  - category: contact
    text: your first and last name, date of birth, gender, the city and country you live in, information about you, your PayPal address, online profiles, uploaded media and email address
  - category: location
    text: We collect information in order to understand where our users are located for a number of reasons.
  - category: device
    text: we may access, collect and/or monitor one or more “device identifiers,” such as a universally unique identifier (“UUID”)
  - category: behavioral
    text: We will directly collect or generate certain information about your use of the Service (such as user activity data, analytics event data and clickstream data)
  - category: communication
    text: We also collect personal information in any messages you send to us and other users through the Service
  deletion:
    route: Contact us using the contact details provided at the bottom of this page under the “Contact us” heading
    text: request deletion of your data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the Service
    text: We use the information that you directly give us to provide the Service to you.
  - purpose: Machine learning
    text: to train our algorithms, models, products and services using machine learning to develop, improve and provide our Service.
  - purpose: Advertising
    text: to serve, personalize and measure the effectiveness of advertising on the Service and third-party sites and platforms.
  - purpose: Safety and security
    text: to prevent, detect, investigate and address safety, security, fraud and abuse risks
  residency:
  - region: United States, Australia, Singapore, European Union, United Kingdom, Philippines, New Zealand
    text: Your information will be stored and processed in the United States, Australia, Singapore, the European Union, United Kingdom, Philippines and New Zealand
  retention:
  - period: null
    scope: Account data
    text: We will retain your personal information for as long as your account is active or as needed to provide you with the Service
  rights:
  - right: access
    text: You have the right to access the data we process about you
  - right: rectification
    text: obtain rectification of inaccurate data
  - right: deletion
    text: request deletion of your data
  - right: restriction
    text: restrict our processing of your data
  - right: portability
    text: request portability of your data
  - right: objection
    text: object to unreasonable processing
  - right: withdraw consent
    text: If we process your data on the basis of your consent, you have the option to withdraw your consent at any time.
  - right: opt out of marketing
    text: You also have the right to opt-out of marketing communications we send you at any time.
  role:
    text: The data controller responsible for your personal data is Pexels, a Canva Germany GmbH brand.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell or rent the information we collect about you with these third-party ad servers or ad networks for such parties’ own marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: transferring your data to a country that the European Commission or UK authorities (as applicable) have determined provides an adequate level of protection for personal data
  - mechanism: SCC
    text: or by implementing standard contractual clauses with our group companies, service providers and partners.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Pexels
provenance_date: '2026-11-10'
provider_name: Pexels
provider_slug: pexels
slug: pexels-privacy-policy
source_date: '2026-11-10'
source_filename: pexels-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.pexels.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Pexels\naid: pexels\nurl: https://www.pexels.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller responsible for your personal data is Pexels, a Canva Germany GmbH brand.\ndata_categories:\n- category: identifying\n  text: your first and last name, date of birth, gender, the city and country you live in\n- category: contact\n  text: your first and last name, date of birth, gender, the city and country you live in, information about you,\n    your PayPal address, online profiles, uploaded media and email address\n- category: location\n  text: We collect information\
  \ in order to understand where our users are located for a number of reasons.\n- category: device\n  text: we may access, collect and/or monitor one or more “device identifiers,” such as a universally unique identifier\n    (“UUID”)\n- category: behavioral\n  text: We will directly collect or generate certain information about your use of the Service (such as user activity\n    data, analytics event data and clickstream data)\n- category: communication\n  text: We also collect personal information in any messages you send to us and other users through the Service\npurposes:\n- purpose: Providing the Service\n  text: We use the information that you directly give us to provide the Service to you.\n- purpose: Machine learning\n  text: to train our algorithms, models, products and services using machine learning to develop, improve and provide\n    our Service.\n- purpose: Advertising\n  text: to serve, personalize and measure the effectiveness of advertising on the Service and third-party\
  \ sites\n    and platforms.\n- purpose: Safety and security\n  text: to prevent, detect, investigate and address safety, security, fraud and abuse risks\nretention:\n- scope: Account data\n  period: null\n  text: We will retain your personal information for as long as your account is active or as needed to provide you\n    with the Service\nresidency:\n- region: United States, Australia, Singapore, European Union, United Kingdom, Philippines, New Zealand\n  text: Your information will be stored and processed in the United States, Australia, Singapore, the European Union,\n    United Kingdom, Philippines and New Zealand\ntransfers:\n- mechanism: adequacy\n  text: transferring your data to a country that the European Commission or UK authorities (as applicable) have\n    determined provides an adequate level of protection for personal data\n- mechanism: SCC\n  text: or by implementing standard contractual clauses with our group companies, service providers and partners.\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us using the contact details provided at the bottom of this page under the “Contact us” heading\n  text: request deletion of your data\nrights:\n- right: access\n  text: You have the right to access the data we process about you\n- right: rectification\n  text: obtain rectification of inaccurate data\n- right: deletion\n  text: request deletion of your data\n- right: restriction\n  text: restrict our processing of your data\n- right: portability\n  text: request portability of your data\n- right: objection\n  text: object to unreasonable processing\n- right: withdraw consent\n  text: If we process your data on the basis of your consent, you have the option to withdraw your consent at any\n    time.\n- right: opt out of marketing\n  text: You also have the right to opt-out of marketing communications we send you at any time.\nsale_or_sharing:\n  stance: conditional\n  text: We do\
  \ not sell or rent the information we collect about you with these third-party ad servers or ad networks\n    for such parties’ own marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/pexels/privacy/pexels-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Pexels's own page on 2026-11-10.
synthetic: false
tags:
- Photos
- Stock Media
- Video
---
