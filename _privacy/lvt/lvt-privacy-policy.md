---
api_specs:
- filename: lvt-cameras-api-openapi.yml
  format: yaml
  label: LVT Cameras API
  slug: lvt-cameras-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-cameras-api-openapi.yml
- filename: lvt-events-api-openapi.yml
  format: yaml
  label: LVT Events API
  slug: lvt-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-events-api-openapi.yml
- filename: lvt-liveunits-api-openapi.yml
  format: yaml
  label: LVT Live Units API
  slug: lvt-liveunits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-liveunits-api-openapi.yml
- filename: lvt-locations-api-openapi.yml
  format: yaml
  label: LVT Locations API
  slug: lvt-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-locations-api-openapi.yml
- filename: lvt-media-api-openapi.yml
  format: yaml
  label: LVT Media API
  slug: lvt-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-media-api-openapi.yml
- filename: lvt-streams-api-openapi.yml
  format: yaml
  label: LVT Streams API
  slug: lvt-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-streams-api-openapi.yml
- filename: lvt-talkdown-api-openapi.yml
  format: yaml
  label: LVT Talkdown API
  slug: lvt-talkdown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-talkdown-api-openapi.yml
- filename: lvt-webhooks-api-openapi.yml
  format: yaml
  label: LVT Webhooks API
  slug: lvt-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-webhooks-api-openapi.yml
- filename: lvt-public-keys-api-openapi.yml
  format: yaml
  label: LVT Public Keys API
  slug: lvt-public-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-public-keys-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may ask you for your name, organization name, email, address, and phone number
  - category: financial
    text: such as credit card or other financial information
  - category: location
    text: we infer your location information by using your IP address
  - category: device
    text: device type, device identifiers
  - category: behavioral
    text: the searches you conduct
  - category: communication
    text: the contents of a message or attachments that you may send to us
  deletion:
    route: account settings or email to privacy@lvt.com
    text: You may delete or deactivate your account through account settings or by emailing us at privacy@lvt.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, maintain, improve and enhance services
    text: To provide, maintain, improve, and enhance our services
  - purpose: marketing and advertising
    text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials
  - purpose: fraud prevention
    text: To find and prevent fraud and abuse, and respond to trust and safety issues that may arise
  residency:
  - region: United States
    text: Our services are hosted in the United States
  retention:
  - period: null
    scope: personal information
    text: We take measures to delete your information or keep it in a form that does not permit identifying you when this information is no longer necessary for the purposes for which we process it
  rights:
  - right: opt out of use for listed purposes
    text: You may also opt out from our use of your information for the purposes listed in
  - right: unsubscribe from promotional emails
    text: You can unsubscribe from our promotional emails via the link provided in the emails.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may also transfer your data from the U.S. to other countries or regions in connection with storage and processing of data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LVT
provenance_date: '2026-11-10'
provider_name: LVT
provider_slug: lvt
slug: lvt-privacy-policy
source_date: '2026-11-10'
source_filename: lvt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lvt.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LVT\naid: lvt\nurl: https://www.lvt.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we may ask you for your name, organization name, email, address, and phone number\n- category: financial\n  text: such as credit card or other financial information\n- category: location\n  text: we infer your location information by using your IP address\n- category: device\n  text: device type, device identifiers\n- category: behavioral\n  text: the searches you conduct\n- category: communication\n  text: the contents\
  \ of a message or attachments that you may send to us\npurposes:\n- purpose: provide, maintain, improve and enhance services\n  text: To provide, maintain, improve, and enhance our services\n- purpose: marketing and advertising\n  text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials\n- purpose: fraud prevention\n  text: To find and prevent fraud and abuse, and respond to trust and safety issues that may arise\nretention:\n- scope: personal information\n  period: null\n  text: We take measures to delete your information or keep it in a form that does not permit identifying you when\n    this information is no longer necessary for the purposes for which we process it\nresidency:\n- region: United States\n  text: Our services are hosted in the United States\ntransfers:\n- mechanism: other\n  text: We may also transfer your data from the U.S. to other countries or regions in connection with storage and\n    processing of data\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings or email to privacy@lvt.com\n  text: You may delete or deactivate your account through account settings or by emailing us at privacy@lvt.com\nrights:\n- right: opt out of use for listed purposes\n  text: You may also opt out from our use of your information for the purposes listed in\n- right: unsubscribe from promotional emails\n  text: You can unsubscribe from our promotional emails via the link provided in the emails.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lvt/privacy/lvt-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 15 quoted statements, read from LVT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Physical Security
- Video Surveillance
- Camera
- Video Streaming
- WebRTC
- RTSP
- ONVIF
- IoT
- Alerts
- Webhook
- Public Safety
- Retail
- Critical Infrastructure
---
