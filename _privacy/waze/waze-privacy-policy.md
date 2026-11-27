---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: information required when setting up an Account, such as your name or email address.'
  - category: contact
    text: phone number, “home” or “work” addresses
  - category: location
    text: Location and route information is collected for example in the form of GPS and other sensor data from your device
  - category: behavioral
    text: Terms or venues you searched; Your views and interactions with content and ads
  - category: device
    text: your device type, unique identifiers, operating system type & version, battery usage
  - category: communication
    text: Communication you conduct through the Waze Services
  - category: financial
    text: when Waze processes a payment for you
  - category: other
    text: Your voice and audio information when you use voice and audio features
  deletion:
    route: Delete Account function in the in-app Privacy Setting or on the Waze website
    text: please use the “Delete Account” function available under the in-app Privacy Setting and on the Waze website
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to deliver our services.
  - purpose: Maintain and improve services
    text: And we use your information to improve the Services or to develop new features or services.
  - purpose: Personalized services and ads
    text: Depending on your settings, we may also show you personalized ads based on your interests and activity.
  - purpose: Measure performance
    text: We use data for analytics and measurement to understand how our Services are used.
  - purpose: Communicate with you
    text: We also use your information to send you updates, notices, announcements, users’ requests
  residency:
  - region: worldwide
    text: We store data on servers located around the world
  - region: European Union and U.S.A.
    text: which may be located in the European Union and the U.S.A., potentially countries outside of your jurisdiction
  retention:
  - period: null
    scope: Information retained until you remove it
    text: We’ll keep this data in your Waze Account until you choose to remove it and/or update it.
  - period: null
    scope: Information retained until Waze Account is deleted
    text: we may keep some data for the life of your Waze Account
  - period: null
    scope: Data that expires after a specific period
    text: we extract your calendar events for several days in advance and delete them after their occurrence
  rights:
  - right: access, correct, delete, restrict
    text: request access to, review, update, correct, remove, delete, and restrict the processing of your information
  - right: export
    text: You can also export a copy of data in your Waze account
  - right: object
    text: You also have the right to object to the processing of your information.
  role:
    text: The data controller responsible for your information is Waze Mobile Ltd., a company incorporated and operating under the laws of Israel
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Waze does not sell, rent or lease your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: your information may be processed on servers located outside of the country where you live
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Waze
provenance_date: '2026-11-10'
provider_name: Waze
provider_slug: waze
slug: waze-privacy-policy
source_date: '2026-11-10'
source_filename: waze-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://support.google.com/waze/answer/12075406
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Waze\naid: waze\nurl: https://support.google.com/waze/answer/12075406\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller responsible for your information is Waze Mobile Ltd., a company incorporated and operating\n    under the laws of Israel\ndata_categories:\n- category: identifying\n  text: 'Account Information: information required when setting up an Account, such as your name or email address.'\n- category: contact\n  text: phone number, “home” or “work” addresses\n- category: location\n  text: Location and route information is collected for example in the form of GPS and\
  \ other sensor data from your\n    device\n- category: behavioral\n  text: Terms or venues you searched; Your views and interactions with content and ads\n- category: device\n  text: your device type, unique identifiers, operating system type & version, battery usage\n- category: communication\n  text: Communication you conduct through the Waze Services\n- category: financial\n  text: when Waze processes a payment for you\n- category: other\n  text: Your voice and audio information when you use voice and audio features\npurposes:\n- purpose: Provide services\n  text: We use your information to deliver our services.\n- purpose: Maintain and improve services\n  text: And we use your information to improve the Services or to develop new features or services.\n- purpose: Personalized services and ads\n  text: Depending on your settings, we may also show you personalized ads based on your interests and activity.\n- purpose: Measure performance\n  text: We use data for analytics and measurement\
  \ to understand how our Services are used.\n- purpose: Communicate with you\n  text: We also use your information to send you updates, notices, announcements, users’ requests\nretention:\n- scope: Information retained until you remove it\n  period: null\n  text: We’ll keep this data in your Waze Account until you choose to remove it and/or update it.\n- scope: Information retained until Waze Account is deleted\n  period: null\n  text: we may keep some data for the life of your Waze Account\n- scope: Data that expires after a specific period\n  period: null\n  text: we extract your calendar events for several days in advance and delete them after their occurrence\nresidency:\n- region: worldwide\n  text: We store data on servers located around the world\n- region: European Union and U.S.A.\n  text: which may be located in the European Union and the U.S.A., potentially countries outside of your jurisdiction\ntransfers:\n- mechanism: other\n  text: your information may be processed on servers\
  \ located outside of the country where you live\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete Account function in the in-app Privacy Setting or on the Waze website\n  text: please use the “Delete Account” function available under the in-app Privacy Setting and on the Waze website\nrights:\n- right: access, correct, delete, restrict\n  text: request access to, review, update, correct, remove, delete, and restrict the processing of your information\n- right: export\n  text: You can also export a copy of data in your Waze account\n- right: object\n  text: You also have the right to object to the processing of your information.\nsale_or_sharing:\n  stance: prohibited\n  text: Waze does not sell, rent or lease your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/waze/privacy/waze-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Waze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Navigation
- Maps
- Traffic
- Location
- Transportation
- Smart Cities
---
