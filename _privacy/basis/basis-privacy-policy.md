---
api_specs:
- filename: basis-analytics-api-openapi.yml
  format: yaml
  label: Basis Analytics API
  slug: basis-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basis/openapi/basis-analytics-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'This may include pseudonymous information about Internet users’ browsers and devices, such as: the type of browser and its settings'
  - category: device
    text: information about other identifiers assigned to the device, the IP address from which the device accesses a client’s website or mobile application
  - category: location
    text: information about the geographic location of the device when it accesses a website or mobile application
  - category: behavioral
    text: inferences or information about users’ interests that are created, acquired, bought, sold, or used by our clients
  - category: health
    text: These include standard interest segments that are based on health related information or interests and political information.
  - category: contact
    text: your contact information (e.g., email address, telephone number)
  deletion:
    route: email privacy@basis.com or the Right to Know/Right to Delete form
    text: If your personally identifiable information changes, or if you no longer desire our Service, you may correct, update, delete or deactivate it by emailing us at privacy@basis.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: serve targeted ads
    text: We use the information we collect to serve targeted ads to individuals.
  - purpose: analysis of ad effectiveness
    text: Perform analysis of how effective the ads served are;
  - purpose: fraud detection
    text: Detect fraud; and
  - purpose: marketing
    text: To contact you for marketing purposes.
  retention:
  - period: 60 days
    scope: data collected via browsers and cookies
    text: For data collected via browsers and stored in cookies, Basis DSP stores this data for up to 60 days.
  - period: 180 days
    scope: data collected via mobile advertising IDs
    text: For data collected via mobile application advertising and stored via mobile advertising IDs Basis DSP stores this data for up to 180 days.
  rights:
  - right: access
    text: You have the right to access, update, and correct inaccuracies in certain information in our custody and control
  - right: delete
    text: the right to delete the personal information we have about you, your computer or device (the right to delete)
  - right: opt-out of sale
    text: the right to opt-out of the sale of personal information about you
  - right: complain to supervisory authority
    text: Those rights include the right to complain to EU Supervisory Authorities
  - right: port
    text: the right to access, correct, port to another party and delete certain personal data processed by Basis Technologies
  role:
    text: Where Basis Technologies is a controller of data (e.g., via our Basis DSP), the legal basis will be both legitimate interest and consent
    value: controller
  sale_or_sharing:
    stance: conditional
    text: such transfer may be considered a sale of data in California.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Basis Technologies is responsible for the processing of personal information it receives under the Data Privacy Framework
  - mechanism: other
    text: sharing data of EU and Swiss individuals in response to lawful requests from public authorities
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Basis
provenance_date: '2026-11-09'
provider_name: Basis
provider_slug: basis
slug: basis-privacy-policy
source_date: '2026-11-09'
source_filename: basis-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://privacy.basis.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Basis\naid: basis\nurl: https://privacy.basis.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Where Basis Technologies is a controller of data (e.g., via our Basis DSP), the legal basis will be both\n    legitimate interest and consent\ndata_categories:\n- category: identifying\n  text: 'This may include pseudonymous information about Internet users’ browsers and devices, such as: the type\n    of browser and its settings'\n- category: device\n  text: information about other identifiers assigned to the device, the IP address from which the device accesses\n    a client’s website or mobile\
  \ application\n- category: location\n  text: information about the geographic location of the device when it accesses a website or mobile application\n- category: behavioral\n  text: inferences or information about users’ interests that are created, acquired, bought, sold, or used by our\n    clients\n- category: health\n  text: These include standard interest segments that are based on health related information or interests and political\n    information.\n- category: contact\n  text: your contact information (e.g., email address, telephone number)\npurposes:\n- purpose: serve targeted ads\n  text: We use the information we collect to serve targeted ads to individuals.\n- purpose: analysis of ad effectiveness\n  text: Perform analysis of how effective the ads served are;\n- purpose: fraud detection\n  text: Detect fraud; and\n- purpose: marketing\n  text: To contact you for marketing purposes.\nretention:\n- scope: data collected via browsers and cookies\n  period: 60 days\n  text: For\
  \ data collected via browsers and stored in cookies, Basis DSP stores this data for up to 60 days.\n- scope: data collected via mobile advertising IDs\n  period: 180 days\n  text: For data collected via mobile application advertising and stored via mobile advertising IDs Basis DSP stores\n    this data for up to 180 days.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Basis Technologies is responsible for the processing of personal information it receives under the Data\n    Privacy Framework\n- mechanism: other\n  text: sharing data of EU and Swiss individuals in response to lawful requests from public authorities\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@basis.com or the Right to Know/Right to Delete form\n  text: If your personally identifiable information changes, or if you no longer desire our Service, you may correct,\n    update, delete or deactivate it by emailing us at privacy@basis.com\
  \ .\nrights:\n- right: access\n  text: You have the right to access, update, and correct inaccuracies in certain information in our custody and\n    control\n- right: delete\n  text: the right to delete the personal information we have about you, your computer or device (the right to delete)\n- right: opt-out of sale\n  text: the right to opt-out of the sale of personal information about you\n- right: complain to supervisory authority\n  text: Those rights include the right to complain to EU Supervisory Authorities\n- right: port\n  text: the right to access, correct, port to another party and delete certain personal data processed by Basis\n    Technologies\nsale_or_sharing:\n  stance: conditional\n  text: such transfer may be considered a sale of data in California.\n"
source_yaml_url: https://artifacts.apis.io/basis/privacy/basis-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Basis's own page on 2026-11-09.
synthetic: false
tags:
- Programmatic Advertising
- DSP
- Media Buying
- Campaign Management
- Audience Targeting
- AdTech
---
