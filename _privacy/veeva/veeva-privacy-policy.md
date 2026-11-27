---
api_specs:
- filename: veeva-authentication-api-openapi.yml
  format: yaml
  label: veeva Authentication API
  slug: veeva-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-authentication-api-openapi.yml
- filename: veeva-documents-api-openapi.yml
  format: yaml
  label: veeva Documents API
  slug: veeva-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-documents-api-openapi.yml
- filename: veeva-objects-api-openapi.yml
  format: yaml
  label: veeva Objects API
  slug: veeva-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-objects-api-openapi.yml
- filename: veeva-query-api-openapi.yml
  format: yaml
  label: veeva Query API
  slug: veeva-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-query-api-openapi.yml
- filename: veeva-users-api-openapi.yml
  format: yaml
  label: veeva Users API
  slug: veeva-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-users-api-openapi.yml
- filename: veeva-workflows-api-openapi.yml
  format: yaml
  label: veeva Workflows API
  slug: veeva-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veeva/openapi/veeva-workflows-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect information that you provide through that process, such as your name, email address, phone number, username and password, job title and survey responses
  - category: device
    text: we collect device and usage information such as cookie records, browser type, internet service provider (ISP), device IP address, operating systems and versions, device motion data, web beacons and clickstream data
  - category: financial
    text: we will collect information that allows us to collect and process your payment which may include your bank account information or credit or debit card number
  - category: location
    text: We do not collect precise geolocation information.
  - category: professional
    text: We collect information about your professional activity such as your specialty, educational background, references, contributions to events, participation in clinical trials, publications
  - category: demographic
    text: We collect demographic information such as your name, email address, phone number, gender, age, education level and address.
  - category: behavioral
    text: We collect consumer information such as buying activity, media consumption, hobbies and interests, buying channel preferences (e.g., online, in store) and travel preferences.
  deletion:
    route: Privacy requests via the 'click here' link or phone 1 (877) 807-3230
    text: If you wish to exercise your privacy rights, click here or call us, (free of charge) at 1 (877) 807-3230.
  dpa:
    available: true
    text: Where requested, we offer a Data Processing Addendum and Standard Contractual Clauses to enable our customers to comply with data protection laws applicable to our processing of personal information on their behalf.
    url: null
  purposes:
  - purpose: Website operation and analytics
    text: to help us understand how you interact with us, to provide you with relevant information and services, and to help us to ensure our websites are working as designed
  - purpose: Events and marketing
    text: inform you of other events or information we believe you may be interested in; analyze, improve and promote our events, campaigns, products and services
  - purpose: Data products for life sciences customers
    text: to facilitate our life sciences customers’ communication with them
  - purpose: Healthcare marketing measurement
    text: To help our customers measure the impact of their marketing campaigns, we connect pseudonymized media exposure data
  retention:
  - period: two years
    scope: Websites and Apps
    text: We retain your information for two years only (or as otherwise required by law).
  - period: 10 years after you are no longer professionally active
    scope: Our data products
    text: As part of our data products , we keep your information for 10 years after you are no longer professionally active.
  - period: up to 12 months
    scope: Healthcare marketing and analytic products
    text: As part of our healthcare marketing and analytic products , we retain personal information for up to 12 months from the date we last used the information.
  rights:
  - right: know
    text: the right to know what information we hold about you
  - right: correct
    text: the right to correct your inaccurate information
  - right: delete
    text: the right to delete your information
  - right: portability
    text: the right to receive a copy of your information in a portable and readily usable format
  - right: opt-out of sale or targeted advertising
    text: the right to opt-out of the sale of or use of your information for targeted advertising
  - right: limit sensitive information use
    text: the right to limit the use or disclosure of your sensitive information
  role:
    text: You can also write to our data controller, Veeva Systems Inc., or our various local representatives
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not “sell” or “share” sensitive personal information or process sensitive personal information for targeted advertising as such terms are defined under applicable data protection laws.
  subprocessors:
    text: A list of our support locations and of our sub-processors can be found here .
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on transfer mechanisms that lawfully support data transfer to other jurisdictions, such as Standard Contractual Clauses
  - mechanism: adequacy
    text: “adequacy” determinations, obtaining your consent or another recognized transfer mechanism.
  - mechanism: DPF
    text: Veeva Systems Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF (UK Extension), and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Veeva
provenance_date: '2026-11-10'
provider_name: Veeva
provider_slug: veeva
slug: veeva-privacy-policy
source_date: '2026-11-10'
source_filename: veeva-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.veeva.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Veeva\naid: veeva\nurl: https://www.veeva.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: You can also write to our data controller, Veeva Systems Inc., or our various local representatives\ndata_categories:\n- category: identifying\n  text: we collect information that you provide through that process, such as your name, email address, phone number,\n    username and password, job title and survey responses\n- category: device\n  text: we collect device and usage information such as cookie records, browser type, internet service provider\n    (ISP), device IP address, operating\
  \ systems and versions, device motion data, web beacons and clickstream data\n- category: financial\n  text: we will collect information that allows us to collect and process your payment which may include your bank\n    account information or credit or debit card number\n- category: location\n  text: We do not collect precise geolocation information.\n- category: professional\n  text: We collect information about your professional activity such as your specialty, educational background,\n    references, contributions to events, participation in clinical trials, publications\n- category: demographic\n  text: We collect demographic information such as your name, email address, phone number, gender, age, education\n    level and address.\n- category: behavioral\n  text: We collect consumer information such as buying activity, media consumption, hobbies and interests, buying\n    channel preferences (e.g., online, in store) and travel preferences.\npurposes:\n- purpose: Website operation\
  \ and analytics\n  text: to help us understand how you interact with us, to provide you with relevant information and services, and\n    to help us to ensure our websites are working as designed\n- purpose: Events and marketing\n  text: inform you of other events or information we believe you may be interested in; analyze, improve and promote\n    our events, campaigns, products and services\n- purpose: Data products for life sciences customers\n  text: to facilitate our life sciences customers’ communication with them\n- purpose: Healthcare marketing measurement\n  text: To help our customers measure the impact of their marketing campaigns, we connect pseudonymized media exposure\n    data\nretention:\n- scope: Websites and Apps\n  period: two years\n  text: We retain your information for two years only (or as otherwise required by law).\n- scope: Our data products\n  period: 10 years after you are no longer professionally active\n  text: As part of our data products , we keep your information\
  \ for 10 years after you are no longer professionally\n    active.\n- scope: Healthcare marketing and analytic products\n  period: up to 12 months\n  text: As part of our healthcare marketing and analytic products , we retain personal information for up to 12\n    months from the date we last used the information.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on transfer mechanisms that lawfully support data transfer to other jurisdictions,\n    such as Standard Contractual Clauses\n- mechanism: adequacy\n  text: “adequacy” determinations, obtaining your consent or another recognized transfer mechanism.\n- mechanism: DPF\n  text: Veeva Systems Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the\n    EU-U.S. DPF (UK Extension), and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S.\n    Department of Commerce.\nsubprocessors:\n  url: null\n  text: A list of our support locations and of\
  \ our sub-processors can be found here .\ndpa:\n  available: true\n  url: null\n  text: Where requested, we offer a Data Processing Addendum and Standard Contractual Clauses to enable our customers\n    to comply with data protection laws applicable to our processing of personal information on their behalf.\ndeletion:\n  route: Privacy requests via the 'click here' link or phone 1 (877) 807-3230\n  text: If you wish to exercise your privacy rights, click here or call us, (free of charge) at 1 (877) 807-3230.\nrights:\n- right: know\n  text: the right to know what information we hold about you\n- right: correct\n  text: the right to correct your inaccurate information\n- right: delete\n  text: the right to delete your information\n- right: portability\n  text: the right to receive a copy of your information in a portable and readily usable format\n- right: opt-out of sale or targeted advertising\n  text: the right to opt-out of the sale of or use of your information for targeted advertising\n\
  - right: limit sensitive information use\n  text: the right to limit the use or disclosure of your sensitive information\nsale_or_sharing:\n  stance: conditional\n  text: We do not “sell” or “share” sensitive personal information or process sensitive personal information for\n    targeted advertising as such terms are defined under applicable data protection laws.\n"
source_yaml_url: https://artifacts.apis.io/veeva/privacy/veeva-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Veeva's own page on 2026-11-10.
synthetic: false
tags:
- Life Sciences
- Pharmaceuticals
- Clinical Trials
- Regulatory
- Quality Management
- Document Management
- Content Management
- Healthcare
- Software-as-a-Service
- Enterprise
- MCP
- Agents
- Clinical Research
---
