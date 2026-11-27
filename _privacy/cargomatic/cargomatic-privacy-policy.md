---
api_specs:
- filename: cargomatic-authorization-api-openapi.yml
  format: yaml
  label: Cargomatic Authorization API
  slug: cargomatic-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-authorization-api-openapi.yml
- filename: cargomatic-carrier-api-openapi.yml
  format: yaml
  label: Cargomatic Carrier API
  slug: cargomatic-carrier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-carrier-api-openapi.yml
- filename: cargomatic-document-api-openapi.yml
  format: yaml
  label: Cargomatic Document API
  slug: cargomatic-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-document-api-openapi.yml
- filename: cargomatic-shipper-api-openapi.yml
  format: yaml
  label: Cargomatic Shipper API
  slug: cargomatic-shipper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-shipper-api-openapi.yml
- filename: cargomatic-stops-api-openapi.yml
  format: yaml
  label: Cargomatic Stops API
  slug: cargomatic-stops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cargomatic/openapi/cargomatic-stops-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers . Such as your name, alias, email, phone number, billing and shipping address, unique personal identifier, online identifier, IP address, account name, or other similar identifiers.
  - category: contact
    text: Contact Information. When you contact us, including if you request more information about our Services, request a demo, or otherwise communicate us, we collect your name, email address, phone number, the nature of your inquiry, and any other information you choose to provide.
  - category: financial
    text: Customer Records . Includes your account and profile information and customer records that contain personal information, such as name, account name, other characteristics or descriptions, email, address, phone number, and other contact information, account credentials, communications preferences, billing and payment information
  - category: location
    text: GPS Information. Certain vehicles with shipments being transported through the Services may be tracked via GPS.
  - category: behavioral
    text: Internet or Other Electronic Network Activity Information . Includes, but is not limited to, browsing history, clickstream data, search history, and information regarding interactions with our Site, mobile application, advertisements, or emails
  - category: device
    text: Device, Browsing, and Usage Information. We track and collect information as you use our online Services, such as browser type, domain names, access times, date/time stamps, operating system, language, device type, unique ID
  - category: communication
    text: Audio, Electronic, Visual, or Similar Information . Includes information collected via call recordings if you are interacting with us in a customer service capacity or if you call us on a recorded line
  deletion:
    route: Verifiable request via CCPA contact channels
    text: Right to Delete . You have the right to request we delete your personal information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: to provide, operate, maintain, and enhance our products and the Services
  - purpose: Marketing and promotions
    text: to contact you for marketing and promotional purposes
  - purpose: Track shipment location
    text: in the case of carriers and shippers, to track the location of shipments transported through the Services
  - purpose: Fraud prevention and security
    text: to prevent and detect fraud, unauthorized activities and access, and other misuse
  - purpose: Legal compliance
    text: to comply with applicable legal or regulatory obligations, including as part of a judicial proceeding
  residency:
  - region: United States
    text: The Service is hosted in the United States and is intended and designed for use solely by persons located in the U.S.
  retention:
  - period: null
    scope: Personal information
    text: We retain your personal information for as long as needed or permitted, based on the reason we obtained it (consistent with applicable law).
  rights:
  - right: Right to know/access
    text: 'Right to Know/Access . With respect to the personal information we have collected about you, you have the right to request:'
  - right: Right to correct
    text: Right to Correct . You have the right to request that we correct incorrect personal information about you.
  - right: Right to delete
    text: Right to Delete . You have the right to request we delete your personal information.
  - right: Right to opt-out of sales and sharing
    text: Right to Opt-Out of Sales and Sharing . You have the right to opt-out of “sales” and “sharing” of your personal information
  - right: Right to non-discrimination
    text: Right to Non-Discrimination . We will not discriminate against you for exercising any of the rights described in this section.
  role:
    text: The shipper is the controller of consignee information, and any requests regarding this information should be directed to the relevant shipper.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: we may be considered as “selling” or “sharing” personal information because of our use of third-party ad and analytics cookies.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you nonetheless attempt to use the Service from other regions of the world with different governing laws, please note that you are transferring your personal information from those regions to the U.S. for storage and processing.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cargomatic
provenance_date: '2026-11-09'
provider_name: Cargomatic
provider_slug: cargomatic
slug: cargomatic-privacy-policy
source_date: '2026-11-09'
source_filename: cargomatic-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cargomatic.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cargomatic\naid: cargomatic\nurl: https://cargomatic.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The shipper is the controller of consignee information, and any requests regarding this information should\n    be directed to the relevant shipper.\ndata_categories:\n- category: identifying\n  text: Identifiers . Such as your name, alias, email, phone number, billing and shipping address, unique personal\n    identifier, online identifier, IP address, account name, or other similar identifiers.\n- category: contact\n  text: Contact Information. When you contact us, including\
  \ if you request more information about our Services,\n    request a demo, or otherwise communicate us, we collect your name, email address, phone number, the nature of\n    your inquiry, and any other information you choose to provide.\n- category: financial\n  text: Customer Records . Includes your account and profile information and customer records that contain personal\n    information, such as name, account name, other characteristics or descriptions, email, address, phone number,\n    and other contact information, account credentials, communications preferences, billing and payment information\n- category: location\n  text: GPS Information. Certain vehicles with shipments being transported through the Services may be tracked via\n    GPS.\n- category: behavioral\n  text: Internet or Other Electronic Network Activity Information . Includes, but is not limited to, browsing history,\n    clickstream data, search history, and information regarding interactions with our Site, mobile\
  \ application,\n    advertisements, or emails\n- category: device\n  text: Device, Browsing, and Usage Information. We track and collect information as you use our online Services,\n    such as browser type, domain names, access times, date/time stamps, operating system, language, device type,\n    unique ID\n- category: communication\n  text: Audio, Electronic, Visual, or Similar Information . Includes information collected via call recordings if\n    you are interacting with us in a customer service capacity or if you call us on a recorded line\npurposes:\n- purpose: Provide and improve services\n  text: to provide, operate, maintain, and enhance our products and the Services\n- purpose: Marketing and promotions\n  text: to contact you for marketing and promotional purposes\n- purpose: Track shipment location\n  text: in the case of carriers and shippers, to track the location of shipments transported through the Services\n- purpose: Fraud prevention and security\n  text: to prevent\
  \ and detect fraud, unauthorized activities and access, and other misuse\n- purpose: Legal compliance\n  text: to comply with applicable legal or regulatory obligations, including as part of a judicial proceeding\nretention:\n- scope: Personal information\n  period: null\n  text: We retain your personal information for as long as needed or permitted, based on the reason we obtained\n    it (consistent with applicable law).\nresidency:\n- region: United States\n  text: The Service is hosted in the United States and is intended and designed for use solely by persons located\n    in the U.S.\ntransfers:\n- mechanism: other\n  text: If you nonetheless attempt to use the Service from other regions of the world with different governing laws,\n    please note that you are transferring your personal information from those regions to the U.S. for storage and\n    processing.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Verifiable\
  \ request via CCPA contact channels\n  text: Right to Delete . You have the right to request we delete your personal information.\nrights:\n- right: Right to know/access\n  text: 'Right to Know/Access . With respect to the personal information we have collected about you, you have the\n    right to request:'\n- right: Right to correct\n  text: Right to Correct . You have the right to request that we correct incorrect personal information about you.\n- right: Right to delete\n  text: Right to Delete . You have the right to request we delete your personal information.\n- right: Right to opt-out of sales and sharing\n  text: Right to Opt-Out of Sales and Sharing . You have the right to opt-out of “sales” and “sharing” of your personal\n    information\n- right: Right to non-discrimination\n  text: Right to Non-Discrimination . We will not discriminate against you for exercising any of the rights described\n    in this section.\nsale_or_sharing:\n  stance: conditional\n  text: we may be considered\
  \ as “selling” or “sharing” personal information because of our use of third-party ad\n    and analytics cookies.\n"
source_yaml_url: https://artifacts.apis.io/cargomatic/privacy/cargomatic-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Cargomatic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Freight
- Drayage
- Transportation
- Supply Chain
- Shipping
- Trucking
- Marketplace
- Intermodal
---
