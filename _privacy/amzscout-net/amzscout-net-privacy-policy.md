---
api_specs:
- filename: amzscout-net-discovery-api-openapi.yml
  format: yaml
  label: AMZScout Discovery API
  slug: amzscout-net-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amzscout-net/openapi/amzscout-net-discovery-api-openapi.yml
- filename: amzscout-net-dispatch-api-openapi.yml
  format: yaml
  label: AMZScout Dispatch API
  slug: amzscout-net-dispatch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amzscout-net/openapi/amzscout-net-dispatch-api-openapi.yml
- filename: amzscout-net-tools-api-openapi.yml
  format: yaml
  label: AMZScout Tools API
  slug: amzscout-net-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amzscout-net/openapi/amzscout-net-tools-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, address, email address, and/or phone number.
  - category: device
    text: your internet protocol (IP) address, device ID, browser type and version, and time zone setting
  - category: location
    text: geolocation data to determine what country you are accessing our App and/or Site from
  - category: behavioral
    text: Information regarding your use of our App and/or Site, and which website(s) you came to our Site from.
  - category: communication
    text: copies of your communications with us
  deletion:
    route: Email support@amzscout.net for connector logs
    text: you may request deletion of your connector logs before their automatic 30-day expiry by contacting us at support@amzscout.net.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Communicating with you
    text: We use personal and contact information provided by you, copies of your communications with us and, in some circumstances, transaction details, to manage our relationship with you.
  - purpose: Analytics
    text: to optimize our services and to improve our Site, services, direct marketing, behavior profiling, and experiences.
  - purpose: Fraud prevention
    text: in order to undertake analysis for the purposes of identifying and dealing with any fraud or fraudulent activity.
  - purpose: Marketing communications
    text: We send you marketing communications through a number of different channels.
  - purpose: AI assistant usage analytics
    text: We use this data for usage analytics and to detect and prevent abuse of the connector; we do not use it to train AI models.
  residency:
  - region: United States
    text: We process your personal information in the United States.
  retention:
  - period: 30 days
    scope: Connector tool-usage and assistant logs
    text: We retain these logs for up to 30 days from the date they are created, after which they are automatically deleted.
  - period: null
    scope: Personal data generally
    text: We will only keep your personal data for as long as necessary to fulfil the purposes we collected it for, including for the purposes of satisfying any legal, accounting, or reporting requirements.
  rights:
  - right: Opt out of marketing
    text: to ask us not to use your personal data for marketing;
  - right: Access
    text: to request from us access to personal information held about you
  - right: Rectification
    text: to ask for the information that we retain about you to be rectified if it is inaccurate or incomplete;
  - right: Erasure
    text: to ask, in certain circumstances, to delete any of your personal data that we retain;
  - right: Restriction
    text: to ask, in certain circumstances, for the processing of that information to be restricted;
  - right: Portability
    text: and to ask, in certain circumstances, for data portability;
  - right: Withdraw consent
    text: to ask that we stop any consent-based processing of your personal data after you withdraw that consent;
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: AMZScout does not sell User Information to third parties. However, we may share User Information with our staff, business partners, and third party service providers, for marketing, advertising or product/service offering purposes.
  subprocessors:
    text: 'Requests made through the amzscout-agent tool are the exception: to generate a response, your request text and the AMZScout data retrieved for it are sent to OpenAI and Anthropic, which act as subprocessors for this feature only.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AMZScout
provenance_date: '2026-11-09'
provider_name: AMZScout
provider_slug: amzscout-net
slug: amzscout-net-privacy-policy
source_date: '2026-11-09'
source_filename: amzscout-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://amzscout.net/privacy-policy/?r=footer
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AMZScout\naid: amzscout-net\nurl: https://amzscout.net/privacy-policy/?r=footer\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name, address, email address, and/or phone number.\n- category: device\n  text: your internet protocol (IP) address, device ID, browser type and version, and time zone setting\n- category: location\n  text: geolocation data to determine what country you are accessing our App and/or Site from\n- category: behavioral\n  text: Information regarding your use of our App and/or Site, and which website(s) you came\
  \ to our Site from.\n- category: communication\n  text: copies of your communications with us\npurposes:\n- purpose: Communicating with you\n  text: We use personal and contact information provided by you, copies of your communications with us and, in some\n    circumstances, transaction details, to manage our relationship with you.\n- purpose: Analytics\n  text: to optimize our services and to improve our Site, services, direct marketing, behavior profiling, and experiences.\n- purpose: Fraud prevention\n  text: in order to undertake analysis for the purposes of identifying and dealing with any fraud or fraudulent\n    activity.\n- purpose: Marketing communications\n  text: We send you marketing communications through a number of different channels.\n- purpose: AI assistant usage analytics\n  text: We use this data for usage analytics and to detect and prevent abuse of the connector; we do not use it\n    to train AI models.\nretention:\n- scope: Connector tool-usage and assistant logs\n\
  \  period: 30 days\n  text: We retain these logs for up to 30 days from the date they are created, after which they are automatically\n    deleted.\n- scope: Personal data generally\n  period: null\n  text: We will only keep your personal data for as long as necessary to fulfil the purposes we collected it for,\n    including for the purposes of satisfying any legal, accounting, or reporting requirements.\nresidency:\n- region: United States\n  text: We process your personal information in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Requests made through the amzscout-agent tool are the exception: to generate a response, your request text\n    and the AMZScout data retrieved for it are sent to OpenAI and Anthropic, which act as subprocessors for this\n    feature only.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@amzscout.net for connector logs\n  text: you may request deletion of your connector logs before their automatic\
  \ 30-day expiry by contacting us at\n    support@amzscout.net.\nrights:\n- right: Opt out of marketing\n  text: to ask us not to use your personal data for marketing;\n- right: Access\n  text: to request from us access to personal information held about you\n- right: Rectification\n  text: to ask for the information that we retain about you to be rectified if it is inaccurate or incomplete;\n- right: Erasure\n  text: to ask, in certain circumstances, to delete any of your personal data that we retain;\n- right: Restriction\n  text: to ask, in certain circumstances, for the processing of that information to be restricted;\n- right: Portability\n  text: and to ask, in certain circumstances, for data portability;\n- right: Withdraw consent\n  text: to ask that we stop any consent-based processing of your personal data after you withdraw that consent;\nsale_or_sharing:\n  stance: conditional\n  text: AMZScout does not sell User Information to third parties. However, we may share User Information\
  \ with our\n    staff, business partners, and third party service providers, for marketing, advertising or product/service offering\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/amzscout-net/privacy/amzscout-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from AMZScout's own page on 2026-11-09.
synthetic: false
tags:
- Amazon
- FBA
- Product Research
- Software-as-a-Service
- E-Commerce
- Company
---
