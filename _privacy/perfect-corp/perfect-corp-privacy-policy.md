---
api_specs:
- filename: perfect-corp-s2s-api-openapi.yml
  format: yaml
  label: Perfect Corp S2s API
  slug: perfect-corp-s2s-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perfect-corp/openapi/perfect-corp-s2s-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: name, address, phone numbers and email address
  - category: financial
    text: we will process your contact and billing information, such as your name, address, and credit card information
  - category: biometric
    text: a scan of your face or any data or information based on the scan of your face which may include your face geometry
  - category: location
    text: we may collect and process information about your location
  - category: device
    text: device type, operating system version and type, unique identifiers (such as mobile advertising ID and MAC address)
  - category: behavioral
    text: we may collect and process information about how you use our Service via Google Analytics or Countly
  - category: communication
    text: we will process your contact data as well as the contents of your request
  deletion:
    route: contact privacyteam@perfectcorp.com
    text: We provide you with the ability to access, rectify, update and erase your data on our Service by contacting us at privacyteam@perfectcorp.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve the Service
    text: To provide and improve the Service, and to develop new products and services.
  - purpose: personalized Services (biometric)
    text: may use any biometric information that we or such third party collect, capture, receive or otherwise obtain only to provide personalized Services and not for identification, facial recognition or any other purpose
  - purpose: order completion and billing
    text: We will only use this data to complete your order, for billing purposes, and for internal accounting.
  retention:
  - period: 2 years
    scope: Opt-in photos for get photo / save and share
    text: we will temporarily store your photos in our email server, for no longer than 2 years
  - period: 1 hour
    scope: Original photo for analysis session
    text: Original photo will be retained for 1 hour after analysis session.
  - period: 24 hours
    scope: Facebook share photo
    text: photo is temporarily stored on Perfect server for 24 hours for Facebook to retrieve.
  - period: 3 days
    scope: Aging virtual try-on data
    text: Data collected will be retained for 3 days after termination or expiry of each VTO session.
  - period: 90 days
    scope: Beauty Advisor 1-on-1 data
    text: 90 days after termination or expiry of the SOW
  - period: 24 hours
    scope: YouCam for Web original photo
    text: the original photo will be deleted from Perfect’s server within 24 hours after it is submitted
  rights:
  - right: access, rectification, erasure, portability, restriction
    text: right to request access to and rectification or erasure of your personal data, data portability, restriction of processing of your personal data
  - right: deletion
    text: Right to deletion.
  - right: correct inaccurate information
    text: Right to correct inaccurate personal information.
  - right: know and access
    text: Right to know and right to access.
  - right: opt-out of sale or share
    text: you have the right to opt-out of the sale or share of your personal information if we ever notify you that we engage in such activity
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or otherwise share your data to any third-party for a business or commercial purpose under any circumstances.
  subprocessors:
    text: Perfect server is established on Amazon Web Services (AWS)
    url: null
  transfers:
  - mechanism: other
    text: we will seek assurances from the recipients of such information (prior to the transfer) that they will safeguard the information in a manner consistent with this policy
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Perfect Corp
provenance_date: '2026-11-10'
provider_name: Perfect Corp
provider_slug: perfect-corp
slug: perfect-corp-privacy-policy
source_date: '2026-11-10'
source_filename: perfect-corp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.perfectcorp.com/business/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Perfect Corp\naid: perfect-corp\nurl: https://www.perfectcorp.com/business/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: name, address, phone numbers and email address\n- category: financial\n  text: we will process your contact and billing information, such as your name, address, and credit card information\n- category: biometric\n  text: a scan of your face or any data or information based on the scan of your face which may include your face\n    geometry\n- category: location\n  text: we may collect and process information about\
  \ your location\n- category: device\n  text: device type, operating system version and type, unique identifiers (such as mobile advertising ID and MAC\n    address)\n- category: behavioral\n  text: we may collect and process information about how you use our Service via Google Analytics or Countly\n- category: communication\n  text: we will process your contact data as well as the contents of your request\npurposes:\n- purpose: provide and improve the Service\n  text: To provide and improve the Service, and to develop new products and services.\n- purpose: personalized Services (biometric)\n  text: may use any biometric information that we or such third party collect, capture, receive or otherwise obtain\n    only to provide personalized Services and not for identification, facial recognition or any other purpose\n- purpose: order completion and billing\n  text: We will only use this data to complete your order, for billing purposes, and for internal accounting.\nretention:\n- scope: Opt-in\
  \ photos for get photo / save and share\n  period: 2 years\n  text: we will temporarily store your photos in our email server, for no longer than 2 years\n- scope: Original photo for analysis session\n  period: 1 hour\n  text: Original photo will be retained for 1 hour after analysis session.\n- scope: Facebook share photo\n  period: 24 hours\n  text: photo is temporarily stored on Perfect server for 24 hours for Facebook to retrieve.\n- scope: Aging virtual try-on data\n  period: 3 days\n  text: Data collected will be retained for 3 days after termination or expiry of each VTO session.\n- scope: Beauty Advisor 1-on-1 data\n  period: 90 days\n  text: 90 days after termination or expiry of the SOW\n- scope: YouCam for Web original photo\n  period: 24 hours\n  text: the original photo will be deleted from Perfect’s server within 24 hours after it is submitted\nresidency: []\ntransfers:\n- mechanism: other\n  text: we will seek assurances from the recipients of such information (prior to\
  \ the transfer) that they will safeguard\n    the information in a manner consistent with this policy\nsubprocessors:\n  url: null\n  text: Perfect server is established on Amazon Web Services (AWS)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact privacyteam@perfectcorp.com\n  text: We provide you with the ability to access, rectify, update and erase your data on our Service by contacting\n    us at privacyteam@perfectcorp.com\nrights:\n- right: access, rectification, erasure, portability, restriction\n  text: right to request access to and rectification or erasure of your personal data, data portability, restriction\n    of processing of your personal data\n- right: deletion\n  text: Right to deletion.\n- right: correct inaccurate information\n  text: Right to correct inaccurate personal information.\n- right: know and access\n  text: Right to know and right to access.\n- right: opt-out of sale or share\n  text: you have the right to opt-out of the sale\
  \ or share of your personal information if we ever notify you that\n    we engage in such activity\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or otherwise share your data to any third-party for a business or commercial purpose\n    under any circumstances.\n"
source_yaml_url: https://artifacts.apis.io/perfect-corp/privacy/perfect-corp-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Perfect Corp's own page on 2026-11-10.
synthetic: false
tags:
- Beauty
- Skincare
- Cosmetics
- Fashion
- Apparel
- Jewelry
- Watches
- Hair
- Virtual Try-On
- Image Editing
- Generative AI
- Computer Vision
- Augmented Reality
- Visual Commerce
- Artificial Intelligence
- Machine Learning
- Video Generation
- skin-analysis
- MCP
- Agents
- Photo Editing
- Beauty Tech
- Retail
- ar-try-on
- A2A
---
