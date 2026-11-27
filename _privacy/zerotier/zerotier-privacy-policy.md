---
api_specs:
- filename: zerotier-controller-api-openapi.yml
  format: yaml
  label: ZeroTier Controller API
  slug: zerotier-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-controller-api-openapi.yml
- filename: zerotier-network-api-openapi.yml
  format: yaml
  label: ZeroTier Network API
  slug: zerotier-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-network-api-openapi.yml
- filename: zerotier-network-member-api-openapi.yml
  format: yaml
  label: ZeroTier Network Member API
  slug: zerotier-network-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-network-member-api-openapi.yml
- filename: zerotier-organizations-api-openapi.yml
  format: yaml
  label: ZeroTier Organizations API
  slug: zerotier-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-organizations-api-openapi.yml
- filename: zerotier-peer-api-openapi.yml
  format: yaml
  label: ZeroTier Peer API
  slug: zerotier-peer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-peer-api-openapi.yml
- filename: zerotier-status-api-openapi.yml
  format: yaml
  label: ZeroTier Status API
  slug: zerotier-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-status-api-openapi.yml
- filename: zerotier-user-api-openapi.yml
  format: yaml
  label: ZeroTier User API
  slug: zerotier-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-user-api-openapi.yml
- filename: zerotier-util-api-openapi.yml
  format: yaml
  label: ZeroTier Util API
  slug: zerotier-util-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-util-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal data, including your name, address, email address, language and resume.
  - category: location
    text: Approximate geolocation (derived from IP address); ZeroTier does not collect precise GPS or continuous location data.
  - category: device
    text: Device information, including IP address and operating systems.
  - category: behavioral
    text: Usage Data, including browsing and search history, page views, data communicated while using the service.
  - category: financial
    text: Payment info
  deletion:
    route: contact details provided in this document
    text: Any requests to exercise User rights can be directed to the Owner through the contact details provided in this document.
  dpa:
    available: true
    text: With each third party service provider processing Personal Data the Owner has executed a Data Processing Agreement
    url: null
  purposes:
  - purpose: Analytics
    text: This type of service enables the Owner to monitor and analyze web traffic and can be used to keep track of User behavior.
  - purpose: Handling payments
    text: Unless otherwise specified, this Application processes any payments by credit card, bank transfer or other means via external payment service providers.
  - purpose: Remarketing and behavioral targeting
    text: This type of service allows this Application and its partners to inform, optimize and serve advertising based on past use of this Application by the User.
  residency:
  - region: operating offices and other places where parties are located
    text: The Data is processed at the Owner’s operating offices and in any other places where the parties involved in the processing are located.
  retention:
  - period: for as long as required by the purpose they have been collected for
    scope: general
    text: Unless specified otherwise in this document, Personal Data shall be processed and stored for as long as required by the purpose they have been collected for
  rights:
  - right: access
    text: Users have the right to learn if Data is being processed by the Owner
  - right: erasure
    text: Users have the right to obtain the erasure of their Data from the Owner.
  - right: object
    text: Users have the right to object to the processing of their Data if the processing is carried out on a legal basis other than consent.
  - right: opt out of sale
    text: the right to opt out from the Sale of your Personal Information
  role:
    text: Data Controller for data it processes itself
    value: controller
  sale_or_sharing:
    stance: allowed
    text: 'Shared: Yes'
  subprocessors:
    text: You can find more information on the third party service providers we use
    url: trust.zerotier.com
  transfers:
  - mechanism: other
    text: Depending on the User’s location, data transfers may involve transferring the User’s Data to a country other than their own.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ZeroTier
provenance_date: '2026-11-10'
provider_name: ZeroTier
provider_slug: zerotier
slug: zerotier-privacy-policy
source_date: '2026-11-10'
source_filename: zerotier-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zerotier.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ZeroTier\naid: zerotier\nurl: https://www.zerotier.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data Controller for data it processes itself\ndata_categories:\n- category: identifying\n  text: Personal data, including your name, address, email address, language and resume.\n- category: location\n  text: Approximate geolocation (derived from IP address); ZeroTier does not collect precise GPS or continuous location\n    data.\n- category: device\n  text: Device information, including IP address and operating systems.\n- category: behavioral\n  text: Usage Data, including\
  \ browsing and search history, page views, data communicated while using the service.\n- category: financial\n  text: Payment info\npurposes:\n- purpose: Analytics\n  text: This type of service enables the Owner to monitor and analyze web traffic and can be used to keep track\n    of User behavior.\n- purpose: Handling payments\n  text: Unless otherwise specified, this Application processes any payments by credit card, bank transfer or other\n    means via external payment service providers.\n- purpose: Remarketing and behavioral targeting\n  text: This type of service allows this Application and its partners to inform, optimize and serve advertising\n    based on past use of this Application by the User.\nretention:\n- scope: general\n  period: for as long as required by the purpose they have been collected for\n  text: Unless specified otherwise in this document, Personal Data shall be processed and stored for as long as\n    required by the purpose they have been collected for\nresidency:\n\
  - region: operating offices and other places where parties are located\n  text: The Data is processed at the Owner’s operating offices and in any other places where the parties involved\n    in the processing are located.\ntransfers:\n- mechanism: other\n  text: Depending on the User’s location, data transfers may involve transferring the User’s Data to a country other\n    than their own.\nsubprocessors:\n  url: trust.zerotier.com\n  text: You can find more information on the third party service providers we use\ndpa:\n  available: true\n  url: null\n  text: With each third party service provider processing Personal Data the Owner has executed a Data Processing\n    Agreement\ndeletion:\n  route: contact details provided in this document\n  text: Any requests to exercise User rights can be directed to the Owner through the contact details provided in\n    this document.\nrights:\n- right: access\n  text: Users have the right to learn if Data is being processed by the Owner\n- right: erasure\n\
  \  text: Users have the right to obtain the erasure of their Data from the Owner.\n- right: object\n  text: Users have the right to object to the processing of their Data if the processing is carried out on a legal\n    basis other than consent.\n- right: opt out of sale\n  text: the right to opt out from the Sale of your Personal Information\nsale_or_sharing:\n  stance: allowed\n  text: 'Shared: Yes'\n"
source_yaml_url: https://artifacts.apis.io/zerotier/privacy/zerotier-privacy-policy.yml
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
- sale_or_sharing
summary_line: 20 quoted statements, read from ZeroTier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Networking
- Software Defined Networking
- SDN
- VPN
- Security
- Connectivity
- Overlay Network
- Zero Trust
- Infrastructure
---
