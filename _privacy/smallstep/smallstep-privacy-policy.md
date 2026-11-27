---
api_specs:
- filename: smallstep-authentication-api-openapi.yml
  format: yaml
  label: SmallStep Authentication API
  slug: smallstep-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-authentication-api-openapi.yml
- filename: smallstep-certificates-api-openapi.yml
  format: yaml
  label: SmallStep Certificates API
  slug: smallstep-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-certificates-api-openapi.yml
- filename: smallstep-credentials-api-openapi.yml
  format: yaml
  label: SmallStep Credentials API
  slug: smallstep-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-credentials-api-openapi.yml
- filename: smallstep-device-inventory-api-openapi.yml
  format: yaml
  label: SmallStep Device Inventory API
  slug: smallstep-device-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-device-inventory-api-openapi.yml
- filename: smallstep-pki-architecture-api-openapi.yml
  format: yaml
  label: SmallStep PKI Architecture API
  slug: smallstep-pki-architecture-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-pki-architecture-api-openapi.yml
- filename: smallstep-protect-api-openapi.yml
  format: yaml
  label: SmallStep Protect API
  slug: smallstep-protect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-protect-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may collect Personal Information such as your name, email address, organization, phone number, and third-party account credentials
  - category: device
    text: server logs from your browser or device, which may include your IP address, geolocation data, device identification, “cookie” information
  - category: behavioral
    text: we may collect information about your online activity after you leave our Services
  deletion:
    route: contact privacy@smallstep.com
    text: If you have any questions about viewing or updating information we have on file about you, please contact us at privacy@smallstep.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: personalize, provide, and improve services
    text: we use this Personal Information internally in connection with our Services, including to personalize, provide, and improve our services
  - purpose: analyze how you use the Services
    text: to analyze how you use the Services
  - purpose: customize content
    text: We may use this data to customize content for you that we think you might like, based on your usage patterns.
  retention:
  - period: null
    scope: deleted information
    text: Some information may remain in our records after your deletion of such information from your account.
  rights:
  - right: access
    text: You may access, and, in some cases, edit or delete the following information you’ve provided to us
  - right: opt out of marketing communications
    text: If you do not want to receive communications from us, please indicate your preference by emailing privacy@smallstep.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not rent or sell your Personal Information in personally identifiable form to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SmallStep
provenance_date: '2026-11-10'
provider_name: SmallStep
provider_slug: smallstep
slug: smallstep-privacy-policy
source_date: '2026-11-10'
source_filename: smallstep-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://smallstep.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SmallStep\naid: smallstep\nurl: https://smallstep.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we may collect Personal Information such as your name, email address, organization, phone number, and third-party\n    account credentials\n- category: device\n  text: server logs from your browser or device, which may include your IP address, geolocation data, device identification,\n    “cookie” information\n- category: behavioral\n  text: we may collect information about your online activity after you leave our Services\n\
  purposes:\n- purpose: personalize, provide, and improve services\n  text: we use this Personal Information internally in connection with our Services, including to personalize, provide,\n    and improve our services\n- purpose: analyze how you use the Services\n  text: to analyze how you use the Services\n- purpose: customize content\n  text: We may use this data to customize content for you that we think you might like, based on your usage patterns.\nretention:\n- scope: deleted information\n  period: null\n  text: Some information may remain in our records after your deletion of such information from your account.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact privacy@smallstep.com\n  text: If you have any questions about viewing or updating information we have on file about you, please contact\n    us at privacy@smallstep.com .\nrights:\n- right: access\n  text: You may access,\
  \ and, in some cases, edit or delete the following information you’ve provided to us\n- right: opt out of marketing communications\n  text: If you do not want to receive communications from us, please indicate your preference by emailing privacy@smallstep.com\n    .\nsale_or_sharing:\n  stance: conditional\n  text: We do not rent or sell your Personal Information in personally identifiable form to anyone.\n"
source_yaml_url: https://artifacts.apis.io/smallstep/privacy/smallstep-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from SmallStep's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Certificate Authority
- PKI
- Device Identity
- Zero Trust
- Certificate Management
- mTLS
- ACME
- SSH
- Security
---
