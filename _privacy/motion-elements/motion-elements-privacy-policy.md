---
api_specs:
- filename: motion-elements-account-api-openapi.yml
  format: yaml
  label: Motion Elements Account API
  slug: motion-elements-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-account-api-openapi.yml
- filename: motion-elements-elements-api-openapi.yml
  format: yaml
  label: Motion Elements API
  slug: motion-elements-elements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-elements-api-openapi.yml
- filename: motion-elements-media-types-api-openapi.yml
  format: yaml
  label: Motion Elements Media types API
  slug: motion-elements-media-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-media-types-api-openapi.yml
- filename: motion-elements-search-api-openapi.yml
  format: yaml
  label: Motion Elements Search API
  slug: motion-elements-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-search-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register an account online with us, we collect the Personal Information you provide to us, including your name, email address, password, company name, job function, industry and software that you are using.
  - category: financial
    text: In order to pay you and report sales to you, you will be asked to provide certain Personal Information such as payment information, payment method, payment emails, tax information.
  - category: device
    text: This information may include your IP (Internet Protocol), your browser type, access times, the website that referred you to us, and navigational information such as the pages you view on the Site.
  - category: identifying
    text: We may verify this information by asking you to upload a scan of a government issued ID, driving license identification, passport ID (which will be stored securely on our servers), or provide a credit card number.
  deletion:
    route: email privacy@motionelements.com
    text: If you wish to delete your account or request that we no longer use your information to provide you services contact us at privacy@motionelements.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: order processing and license transactions
    text: we collect your username, password, full name, telephone number, email address and billing address, company name, company title, and other Personal Information to process your orders and complete the license transaction
  - purpose: marketing communications
    text: From time to time we may notify you of special promotions, new products or services, or other information that may interest you.
  - purpose: referral program
    text: We store this information for the sole purpose of sending this one-time email and tracking the success of our referral program.
  residency:
  - region: Singapore
    text: This Site is operated in Singapore and may be accessed abroad.
  retention:
  - period: null
    scope: personal information generally
    text: We will retain your Personal Information for as long as your account is active, your information is needed to provide you services, or as required to fulfill our legal obligations, resolve disputes, and enforce our agreements.
  - period: 60 days
    scope: deletion requests
    text: We will respond to your request within 60 days.
  rights:
  - right: access and correction
    text: individuals located in certain countries, including the European Economic Area, have the right to receive a copy of, review and/or update your personal information and to correct any of your personal information in our records that is inaccurate.
  - right: restriction or deletion
    text: Under the GDPR, you have the right to restrict processing of or request deletion of your Personal Information.
  - right: opt out of marketing
    text: you will have the ability to opt out of such communications at any time by clicking on the unsubscribe option available in each email communication.
  role:
    text: Company is the controller and, unless otherwise noted, is also the processor of data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Motion Elements
provenance_date: '2026-11-10'
provider_name: Motion Elements
provider_slug: motion-elements
slug: motion-elements-privacy-policy
source_date: '2026-11-10'
source_filename: motion-elements-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.motionelements.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Motion Elements\naid: motion-elements\nurl: https://www.motionelements.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Company is the controller and, unless otherwise noted, is also the processor of data.\ndata_categories:\n- category: identifying\n  text: When you register an account online with us, we collect the Personal Information you provide to us, including\n    your name, email address, password, company name, job function, industry and software that you are using.\n- category: financial\n  text: In order to pay you and report sales to you, you will be asked to provide\
  \ certain Personal Information such\n    as payment information, payment method, payment emails, tax information.\n- category: device\n  text: This information may include your IP (Internet Protocol), your browser type, access times, the website that\n    referred you to us, and navigational information such as the pages you view on the Site.\n- category: identifying\n  text: We may verify this information by asking you to upload a scan of a government issued ID, driving license\n    identification, passport ID (which will be stored securely on our servers), or provide a credit card number.\npurposes:\n- purpose: order processing and license transactions\n  text: we collect your username, password, full name, telephone number, email address and billing address, company\n    name, company title, and other Personal Information to process your orders and complete the license transaction\n- purpose: marketing communications\n  text: From time to time we may notify you of special promotions,\
  \ new products or services, or other information\n    that may interest you.\n- purpose: referral program\n  text: We store this information for the sole purpose of sending this one-time email and tracking the success of\n    our referral program.\nretention:\n- scope: personal information generally\n  period: null\n  text: We will retain your Personal Information for as long as your account is active, your information is needed\n    to provide you services, or as required to fulfill our legal obligations, resolve disputes, and enforce our\n    agreements.\n- scope: deletion requests\n  period: 60 days\n  text: We will respond to your request within 60 days.\nresidency:\n- region: Singapore\n  text: This Site is operated in Singapore and may be accessed abroad.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@motionelements.com\n  text: If you wish to delete your account or request that we no\
  \ longer use your information to provide you services\n    contact us at privacy@motionelements.com .\nrights:\n- right: access and correction\n  text: individuals located in certain countries, including the European Economic Area, have the right to receive\n    a copy of, review and/or update your personal information and to correct any of your personal information in\n    our records that is inaccurate.\n- right: restriction or deletion\n  text: Under the GDPR, you have the right to restrict processing of or request deletion of your Personal Information.\n- right: opt out of marketing\n  text: you will have the ability to opt out of such communications at any time by clicking on the unsubscribe option\n    available in each email communication.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/motion-elements/privacy/motion-elements-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Motion Elements's own page on 2026-11-10.
synthetic: false
tags:
- Media
- Stock Media
- Video
- Music
- Sound Effects
- Templates
- Marketplace
- Creative Assets
- Generative AI
- Search
- Company
---
