---
api_specs:
- filename: m0-order-api-openapi.yml
  format: yaml
  label: M0 Order API
  slug: m0-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/m0/openapi/m0-order-api-openapi.yml
- filename: m0-permit-api-openapi.yml
  format: yaml
  label: M0 Permit API
  slug: m0-permit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/m0/openapi/m0-permit-api-openapi.yml
- filename: m0-quote-api-openapi.yml
  format: yaml
  label: M0 Quote API
  slug: m0-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/m0/openapi/m0-quote-api-openapi.yml
- filename: m0-topology-api-openapi.yml
  format: yaml
  label: M0 Topology API
  slug: m0-topology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/m0/openapi/m0-topology-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, your telephone number, your address or e-mail address
  - category: device
    text: IP address of the requesting device
  - category: behavioral
    text: Pages viewed (date, time, URL, title, time spent)
  - category: location
    text: Approximate location (country and city, if applicable)
  - category: device
    text: the device identifier of mobile devices (e.g. device ID, advertising ID)
  deletion:
    route: contact the controller using the contact details above
    text: To exercise your rights described here, you can contact us at any time using the contact details above.
  dpa:
    available: true
    text: We have concluded a Data Processing Agreement with Google Ireland Limited.
    url: null
  purposes:
  - purpose: website operation and security
    text: to ensure the permanent operability and security of our systems
  - purpose: newsletter delivery
    text: The storage serves the sole purpose of sending you the newsletters and to be able to prove your registration.
  - purpose: analytics
    text: This is used to analyze your usage behavior and improve our website.
  - purpose: advertising
    text: By analyzing and evaluating this data, we are able to display personalized advertising
  residency:
  - region: EEA and other countries
    text: Your data may be processed in the European Economic Area (EEA) and in exceptional circumstances also in countries outside the EEA and around the world
  retention:
  - period: null
    scope: contact requests
    text: The data we collect when you contact us will be deleted after we have fully processed your request
  - period: three years
    scope: contractual data
    text: For evidence purposes, we must retain contractual data in particular for three years from the end of the year in which the business relationship with you ends.
  - period: 2 months
    scope: Google Analytics event data
    text: Event data retention after 2 months
  - period: up to three years
    scope: rights requests
    text: Your requests to exercise data protection rights and our responses to them will be stored for documentation purposes for a period of up to three years
  rights:
  - right: access
    text: Right to access your personal data processed by us (Art. 15 GDPR)
  - right: erasure
    text: Right to erasure of your personal data (Art. 17 GDPR)
  - right: objection
    text: Right to object to the processing of your personal data (Art. 21 GDPR)
  - right: withdraw consent
    text: Right to withdraw your consent (Art. 7 (3) GDPR)
  - right: portability
    text: Right to data portability of your personal data (Art. 20 GDPR)
  role:
    text: 'The contact person and controller acc. to GDPR is the: M0 Foundation c/o Sielva Management SA, Gubelstrasse 11, 6300 Zug Switzerland'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Part of the data processing may be carried out by our service providers. In addition to the service providers mentioned in this privacy policy, this may include, in particular, data centers that store our website and databases (like AWS Amplify)
    url: null
  transfers:
  - mechanism: SCC
    text: Google Ireland Limited and Google LLC have concluded Standard Contractual Clauses (Implementing Decision (EU) 2021/914, Module 3) in accordance with Art. 46 (2)(c) GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: M0
provenance_date: '2026-11-10'
provider_name: M0
provider_slug: m0
slug: m0-privacy-policy
source_date: '2026-11-10'
source_filename: m0-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.m0.org/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: M0\naid: m0\nurl: https://www.m0.org/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The contact person and controller acc. to GDPR is the: M0 Foundation c/o Sielva Management SA, Gubelstrasse\n    11, 6300 Zug Switzerland'\ndata_categories:\n- category: identifying\n  text: your name, your telephone number, your address or e-mail address\n- category: device\n  text: IP address of the requesting device\n- category: behavioral\n  text: Pages viewed (date, time, URL, title, time spent)\n- category: location\n  text: Approximate location (country and city, if applicable)\n- category:\
  \ device\n  text: the device identifier of mobile devices (e.g. device ID, advertising ID)\npurposes:\n- purpose: website operation and security\n  text: to ensure the permanent operability and security of our systems\n- purpose: newsletter delivery\n  text: The storage serves the sole purpose of sending you the newsletters and to be able to prove your registration.\n- purpose: analytics\n  text: This is used to analyze your usage behavior and improve our website.\n- purpose: advertising\n  text: By analyzing and evaluating this data, we are able to display personalized advertising\nretention:\n- scope: contact requests\n  period: null\n  text: The data we collect when you contact us will be deleted after we have fully processed your request\n- scope: contractual data\n  period: three years\n  text: For evidence purposes, we must retain contractual data in particular for three years from the end of the\n    year in which the business relationship with you ends.\n- scope: Google Analytics\
  \ event data\n  period: 2 months\n  text: Event data retention after 2 months\n- scope: rights requests\n  period: up to three years\n  text: Your requests to exercise data protection rights and our responses to them will be stored for documentation\n    purposes for a period of up to three years\nresidency:\n- region: EEA and other countries\n  text: Your data may be processed in the European Economic Area (EEA) and in exceptional circumstances also in\n    countries outside the EEA and around the world\ntransfers:\n- mechanism: SCC\n  text: Google Ireland Limited and Google LLC have concluded Standard Contractual Clauses (Implementing Decision\n    (EU) 2021/914, Module 3) in accordance with Art. 46 (2)(c) GDPR.\nsubprocessors:\n  url: null\n  text: Part of the data processing may be carried out by our service providers. In addition to the service providers\n    mentioned in this privacy policy, this may include, in particular, data centers that store our website and databases\n    (like\
  \ AWS Amplify)\ndpa:\n  available: true\n  url: null\n  text: We have concluded a Data Processing Agreement with Google Ireland Limited.\ndeletion:\n  route: contact the controller using the contact details above\n  text: To exercise your rights described here, you can contact us at any time using the contact details above.\nrights:\n- right: access\n  text: Right to access your personal data processed by us (Art. 15 GDPR)\n- right: erasure\n  text: Right to erasure of your personal data (Art. 17 GDPR)\n- right: objection\n  text: Right to object to the processing of your personal data (Art. 21 GDPR)\n- right: withdraw consent\n  text: Right to withdraw your consent (Art. 7 (3) GDPR)\n- right: portability\n  text: Right to data portability of your personal data (Art. 20 GDPR)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/m0/privacy/m0-privacy-policy.yml
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
summary_line: 24 quoted statements, read from M0's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Stablecoins
- Payments
- Blockchain
- DeFi
- Cross-Chain
- Infrastructure
- Stablecoin Issuance
---
