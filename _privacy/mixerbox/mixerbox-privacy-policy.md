---
api_specs:
- filename: mixerbox-gpt-api-openapi.yml
  format: yaml
  label: MixerBox Gpt API
  slug: mixerbox-gpt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixerbox/openapi/mixerbox-gpt-api-openapi.yml
- filename: mixerbox-gpt-plugins-api-openapi.yml
  format: yaml
  label: MixerBox Gpt Plugins API
  slug: mixerbox-gpt-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixerbox/openapi/mixerbox-gpt-plugins-api-openapi.yml
- filename: mixerbox-services-api-openapi.yml
  format: yaml
  label: MixerBox Services API
  slug: mixerbox-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mixerbox/openapi/mixerbox-services-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: the End-User’s full name
  - category: contact
    text: the End-User’s mailing address
  - category: contact
    text: the End-User’s e-mail address
  - category: demographic
    text: the End-User’s date of birth
  - category: device
    text: (b) device identifier
  - category: behavioral
    text: (h) the actions taken while utilizing the App
  deletion:
    route: email request
    text: 'You may do so by e-mailing us at: [email protected] .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: performance of the EULA and provision of the Service
    text: performance of the EULA for the provision of the Service, including, but not limited to, contents provision, identity verification, and product delivery
  - purpose: marketing and advertising
    text: marketing and advertising, including, but not limited to, development of new services and provision of customized services
  - purpose: promotional messages
    text: We will also use your personal information to send you promotional messages regarding various MixerBox™ products and/or services
  residency:
  - region: Republic of Korea
    text: a data center located in the Republic of Korea on AWS (Amazon Web Services)
  retention:
  - period: until the Member’s membership for the Service is withdrawn
    scope: personally identifiable information
    text: MixerBox™ may keep your personally identifiable information until the Member’s membership for the Service is withdrawn or MixerBox™’s purpose of processing the personally identifiable information is achieved
  rights:
  - right: access
    text: inform you of what personal information we have on file for you
  - right: correction
    text: amend the personal information that we have on file for you
  - right: deletion
    text: remove personal information that you have provided to us, or that we have collected
  - right: opt-out of marketing
    text: To opt-out of receiving e-mail communications or other marketing messages from us
  - right: California opt-out of marketing disclosure
    text: would like to opt-out from the disclosure of your personal information to any third-party for marketing purposes
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: allowed
    text: you agree that we may share, sell, rent, lease or otherwise provide that personal information to/with any third-party for any purposes permitted by law
  subprocessors:
    text: MixerBox™ may entrusts the processing of personally identifiable information to Amazon Web Services
    url: null
  transfers:
  - mechanism: other
    text: The users may refuse cross-border transfer of his/her personal data by contacting MixerBox’s Privacy Protection Officer or the relevant department.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MixerBox
provenance_date: '2026-11-10'
provider_name: MixerBox
provider_slug: mixerbox
slug: mixerbox-privacy-policy
source_date: '2026-11-10'
source_filename: mixerbox-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mbplayer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MixerBox\naid: mixerbox\nurl: https://www.mbplayer.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: the End-User’s full name\n- category: contact\n  text: the End-User’s mailing address\n- category: contact\n  text: the End-User’s e-mail address\n- category: demographic\n  text: the End-User’s date of birth\n- category: device\n  text: (b) device identifier\n- category: behavioral\n  text: (h) the actions taken while utilizing the App\npurposes:\n- purpose: performance of the EULA and provision of the Service\n\
  \  text: performance of the EULA for the provision of the Service, including, but not limited to, contents provision,\n    identity verification, and product delivery\n- purpose: marketing and advertising\n  text: marketing and advertising, including, but not limited to, development of new services and provision of customized\n    services\n- purpose: promotional messages\n  text: We will also use your personal information to send you promotional messages regarding various MixerBox™\n    products and/or services\nretention:\n- scope: personally identifiable information\n  period: until the Member’s membership for the Service is withdrawn\n  text: MixerBox™ may keep your personally identifiable information until the Member’s membership for the Service\n    is withdrawn or MixerBox™’s purpose of processing the personally identifiable information is achieved\nresidency:\n- region: Republic of Korea\n  text: a data center located in the Republic of Korea on AWS (Amazon Web Services)\ntransfers:\n\
  - mechanism: other\n  text: The users may refuse cross-border transfer of his/her personal data by contacting MixerBox’s Privacy Protection\n    Officer or the relevant department.\nsubprocessors:\n  url: null\n  text: MixerBox™ may entrusts the processing of personally identifiable information to Amazon Web Services\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: 'You may do so by e-mailing us at: [email protected] .'\nrights:\n- right: access\n  text: inform you of what personal information we have on file for you\n- right: correction\n  text: amend the personal information that we have on file for you\n- right: deletion\n  text: remove personal information that you have provided to us, or that we have collected\n- right: opt-out of marketing\n  text: To opt-out of receiving e-mail communications or other marketing messages from us\n- right: California opt-out of marketing disclosure\n  text: would like to opt-out from the disclosure of\
  \ your personal information to any third-party for marketing\n    purposes\nsale_or_sharing:\n  stance: allowed\n  text: you agree that we may share, sell, rent, lease or otherwise provide that personal information to/with any\n    third-party for any purposes permitted by law\n"
source_yaml_url: https://artifacts.apis.io/mixerbox/privacy/mixerbox-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from MixerBox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Artificial Intelligence
- ChatGPT Plugins
- GPT Actions
- Music
- Weather
- Translation
- Productivity
---
