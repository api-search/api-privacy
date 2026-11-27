---
api_specs:
- filename: brightedge-auth-api-openapi.yml
  format: yaml
  label: BrightEdge Auth API
  slug: brightedge-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-auth-api-openapi.yml
- filename: brightedge-authorize-api-openapi.yml
  format: yaml
  label: BrightEdge Authorize API
  slug: brightedge-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-authorize-api-openapi.yml
- filename: brightedge-feedback-api-openapi.yml
  format: yaml
  label: BrightEdge Feedback API
  slug: brightedge-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-feedback-api-openapi.yml
- filename: brightedge-oauth-api-openapi.yml
  format: yaml
  label: BrightEdge OAuth API
  slug: brightedge-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-oauth-api-openapi.yml
- filename: brightedge-ping-api-openapi.yml
  format: yaml
  label: BrightEdge Ping API
  slug: brightedge-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-ping-api-openapi.yml
- filename: brightedge-saml-api-openapi.yml
  format: yaml
  label: BrightEdge SAML API
  slug: brightedge-saml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-saml-api-openapi.yml
- filename: brightedge-sso-api-openapi.yml
  format: yaml
  label: BrightEdge SSO API
  slug: brightedge-sso-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-sso-api-openapi.yml
- filename: brightedge-token-api-openapi.yml
  format: yaml
  label: BrightEdge Token API
  slug: brightedge-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-token-api-openapi.yml
- filename: brightedge-well-known-api-openapi.yml
  format: yaml
  label: BrightEdge .well Known API
  slug: brightedge-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brightedge/openapi/brightedge-well-known-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your username, first and last name, email and/or postal address, telephone number or other information that can be used to identify you that you provide when you create an account or fill out a form on the Site
  - category: device
    text: Usage, viewing and technical data automatically collected from your computer or device through cookies and other technologies (described below), such as your device identifier or IP address, browser type, internet service provider (ISP), referring/exit pages, operating system, date/time stamp, and clickstream data
  - category: communication
    text: Comments or other information you post on the Site or otherwise communicate to us (e.g., when you contact customer support, submit inquiries or requests, etc.)
  - category: location
    text: Location information when you visit the Site, including location information provided by a computer or device interacting with the Site
  - category: professional
    text: Such information may include contact information from business information database providers
  deletion:
    route: Email privacy@brightedge.com or webform
    text: 'California residents may exercise their CCPA rights through the following methods: Sending email to privacy@brightedge.com. Filling out our webform here .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain and improve the Site and products and services
    text: To provide, maintain and improve the Site and our products and services, including operating certain features and functionality of the Site
  - purpose: Analytics and business modeling
    text: To analyze trends, administer or optimize the Site, monitor usage or traffic patterns
  - purpose: Marketing communications
    text: To communicate directly with you, including sending you newsletters, promotions and special offers or information about new products and services.
  - purpose: Security and fraud prevention
    text: To control unauthorized use or abuse of the Site and our products and services, or otherwise detect, investigate or prevent activities that may violate our policies or be illegal
  retention:
  - period: null
    scope: Account information
    text: We hold your Personal Information in a combination of hard copy and electronic files for the period necessary to support the Site, comply with our legal obligations, resolve disputes, or otherwise fulfill the purposes outlined in this Privacy Policy.
  - period: null
    scope: Backup account information
    text: We may also retain backup information related to your account on our servers for some time after cancelation for fraud detection or to comply with applicable law or our internal security policies.
  rights:
  - right: Access
    text: Access . To confirm whether we are processing their personal information and to obtain a copy of their personal information in a portable and, to the extent technically feasible, readily usable format.
  - right: Deletion
    text: Deletion . To delete their personal information provided to or obtained by us.
  - right: Correction
    text: Correction . The right to correct inaccuracies in their personal information, taking into account the nature and purposes of the processing of the personal information.
  - right: Opt-out of sale, targeted advertising
    text: to opt out of the “sale” of their personal information; to opt out of targeted advertising by us
  - right: Withdraw consent
    text: Right to withdraw consent at any time (Article 7(3)) . Where we rely on consent, you may withdraw it at any time.
  - right: Object
    text: Right to object (Article 21). You may object to processing based on legitimate interests.
  role:
    text: BrightEdge acts as a ‘processor’ of such data and will only process it on behalf of the relevant customer (the ‘controller’)
    value: both
  sale_or_sharing:
    stance: allowed
    text: 'We may “sell” the following categories of personal information: identifiers, Internet and network activity information, and commercial information.'
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: BrightEdge participates in and has certified its compliance with the EU-U.S. Data Privacy Framework (the “ EU DPF ”)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BrightEdge
provenance_date: '2026-11-09'
provider_name: BrightEdge
provider_slug: brightedge
slug: brightedge-privacy-policy
source_date: '2026-11-09'
source_filename: brightedge-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.brightedge.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BrightEdge\naid: brightedge\nurl: https://www.brightedge.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: BrightEdge acts as a ‘processor’ of such data and will only process it on behalf of the relevant customer\n    (the ‘controller’)\ndata_categories:\n- category: identifying\n  text: Your username, first and last name, email and/or postal address, telephone number or other information that\n    can be used to identify you that you provide when you create an account or fill out a form on the Site\n- category: device\n  text: Usage, viewing and technical data automatically collected from\
  \ your computer or device through cookies and\n    other technologies (described below), such as your device identifier or IP address, browser type, internet service\n    provider (ISP), referring/exit pages, operating system, date/time stamp, and clickstream data\n- category: communication\n  text: Comments or other information you post on the Site or otherwise communicate to us (e.g., when you contact\n    customer support, submit inquiries or requests, etc.)\n- category: location\n  text: Location information when you visit the Site, including location information provided by a computer or device\n    interacting with the Site\n- category: professional\n  text: Such information may include contact information from business information database providers\npurposes:\n- purpose: Provide, maintain and improve the Site and products and services\n  text: To provide, maintain and improve the Site and our products and services, including operating certain features\n    and functionality of\
  \ the Site\n- purpose: Analytics and business modeling\n  text: To analyze trends, administer or optimize the Site, monitor usage or traffic patterns\n- purpose: Marketing communications\n  text: To communicate directly with you, including sending you newsletters, promotions and special offers or information\n    about new products and services.\n- purpose: Security and fraud prevention\n  text: To control unauthorized use or abuse of the Site and our products and services, or otherwise detect, investigate\n    or prevent activities that may violate our policies or be illegal\nretention:\n- scope: Account information\n  period: null\n  text: We hold your Personal Information in a combination of hard copy and electronic files for the period necessary\n    to support the Site, comply with our legal obligations, resolve disputes, or otherwise fulfill the purposes\n    outlined in this Privacy Policy.\n- scope: Backup account information\n  period: null\n  text: We may also retain backup information\
  \ related to your account on our servers for some time after cancelation\n    for fraud detection or to comply with applicable law or our internal security policies.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: BrightEdge participates in and has certified its compliance with the EU-U.S. Data Privacy Framework (the\n    “ EU DPF ”)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@brightedge.com or webform\n  text: 'California residents may exercise their CCPA rights through the following methods: Sending email to privacy@brightedge.com.\n    Filling out our webform here .'\nrights:\n- right: Access\n  text: Access . To confirm whether we are processing their personal information and to obtain a copy of their personal\n    information in a portable and, to the extent technically feasible, readily usable format.\n- right: Deletion\n  text: Deletion . To delete their personal information provided to or\
  \ obtained by us.\n- right: Correction\n  text: Correction . The right to correct inaccuracies in their personal information, taking into account the nature\n    and purposes of the processing of the personal information.\n- right: Opt-out of sale, targeted advertising\n  text: to opt out of the “sale” of their personal information; to opt out of targeted advertising by us\n- right: Withdraw consent\n  text: Right to withdraw consent at any time (Article 7(3)) . Where we rely on consent, you may withdraw it at\n    any time.\n- right: Object\n  text: Right to object (Article 21). You may object to processing based on legitimate interests.\nsale_or_sharing:\n  stance: allowed\n  text: 'We may “sell” the following categories of personal information: identifiers, Internet and network activity\n    information, and commercial information.'\n"
source_yaml_url: https://artifacts.apis.io/brightedge/privacy/brightedge-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from BrightEdge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- Search
- Content
- Marketing
- Analytics
- Keywords
- Enterprise
- AI Search
---
