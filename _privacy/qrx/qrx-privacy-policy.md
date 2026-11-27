---
api_specs:
- filename: qrx-codes-api-openapi.yml
  format: yaml
  label: QRX Codes API
  slug: qrx-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrx/openapi/qrx-codes-api-openapi.yml
- filename: qrx-qrx-api-api-openapi.yml
  format: yaml
  label: QRX QRX API
  slug: qrx-qrx-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrx/openapi/qrx-qrx-api-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data including your name, age, and gender.
  - category: contact
    text: Contact Data including your address and email.
  - category: financial
    text: Financial Data including bank account and payment card details (through our third party payment processor, who stores such information and we do not have access to that information).
  - category: location
    text: geo-location data
  - category: behavioral
    text: search queries and/or browsing behaviour
  - category: device
    text: device and network information
  - category: communication
    text: Marketing and Communications Data including your preferences in receiving marketing from us and our third parties and your communication preferences.
  - category: professional
    text: Professional data including where you are a worker of ours or applying for a role with us, your professional history such as your previous positions and professional experience.
  deletion:
    route: Account deletion in the app, or email hello@qrx.codes for feedback deletion
    text: you can delete your account in the app (Account, then Delete account)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Enable access and use of the Platform
    text: To enable you to access and use the Platform, including to provide you with a login.
  - purpose: Analytics, market research and business development
    text: For analytics, market research and business development, including to operate and improve our business, associated applications and associated social media platforms.
  - purpose: Advertising and marketing
    text: For advertising and marketing, including to send you promotional information about our events and experiences and information that we consider may be of interest to you.
  - purpose: Targeting and advertising cookies
    text: Targeting and advertising cookies. These cookies record your visit to our website, the pages you have visited and the links you have followed.
  residency:
  - region: Australia
    text: We store your personal information in Australia.
  retention:
  - period: null
    scope: Personal information generally
    text: We will only retain your personal information for as long as reasonably necessary to fulfil the purposes we collected it for, including for the purposes of satisfying any legal, regulatory, tax, accounting or reporting requirements.
  - period: about a day
    scope: Uploaded pictures
    text: The uploaded file is kept in private storage for about a day while your codes are made and is then deleted, normally within 25 hours of the upload
  - period: 12 months
    scope: Feedback
    text: 'How long we keep it : 12 months, after which we delete it, with any image, from our database and our team chat.'
  rights:
  - right: Access
    text: You may request access to the personal information that we hold about you.
  - right: Correction
    text: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant or misleading, please contact us using the details below.
  - right: Objection and unsubscribe
    text: To object to processing for direct marketing/unsubscribe from our email database or opt-out of communications (including marketing communications), please contact us using the details below
  - right: Complaint
    text: If you wish to make a complaint, please contact us using the details below and provide us with full details of the complaint.
  - right: Erasure, restriction and portability (EU/UK)
    text: to have your personal information rectified or deleted, to restrict our processing of that information
  role:
    text: MakerX Pty Ltd (ABN 54 651 621 966) ( we, us or our ), understands that protecting your personal information is important.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell this information, and we share it only with the service providers described above that help us make, store and deliver your codes.
  subprocessors:
    text: IT service providers including Clerk, data storage, web-hosting and server providers;
    url: null
  transfers:
  - mechanism: SCC
    text: including standard contractual clauses in our agreements with third parties that are overseas.
  - mechanism: adequacy
    text: only transferring your personal information to countries that have been deemed by applicable data protection laws to provide an adequate level of protection for personal information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: QRX
provenance_date: '2026-11-10'
provider_name: QRX
provider_slug: qrx
slug: qrx-privacy-policy
source_date: '2026-11-10'
source_filename: qrx-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://qrx.codes/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: QRX\naid: qrx\nurl: https://qrx.codes/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: MakerX Pty Ltd (ABN 54 651 621 966) ( we, us or our ), understands that protecting your personal information\n    is important.\ndata_categories:\n- category: identifying\n  text: Identity Data including your name, age, and gender.\n- category: contact\n  text: Contact Data including your address and email.\n- category: financial\n  text: Financial Data including bank account and payment card details (through our third party payment processor,\n    who stores such information and we do not have access\
  \ to that information).\n- category: location\n  text: geo-location data\n- category: behavioral\n  text: search queries and/or browsing behaviour\n- category: device\n  text: device and network information\n- category: communication\n  text: Marketing and Communications Data including your preferences in receiving marketing from us and our third\n    parties and your communication preferences.\n- category: professional\n  text: Professional data including where you are a worker of ours or applying for a role with us, your professional\n    history such as your previous positions and professional experience.\npurposes:\n- purpose: Enable access and use of the Platform\n  text: To enable you to access and use the Platform, including to provide you with a login.\n- purpose: Analytics, market research and business development\n  text: For analytics, market research and business development, including to operate and improve our business,\n    associated applications and associated social media\
  \ platforms.\n- purpose: Advertising and marketing\n  text: For advertising and marketing, including to send you promotional information about our events and experiences\n    and information that we consider may be of interest to you.\n- purpose: Targeting and advertising cookies\n  text: Targeting and advertising cookies. These cookies record your visit to our website, the pages you have visited\n    and the links you have followed.\nretention:\n- scope: Personal information generally\n  period: null\n  text: We will only retain your personal information for as long as reasonably necessary to fulfil the purposes\n    we collected it for, including for the purposes of satisfying any legal, regulatory, tax, accounting or reporting\n    requirements.\n- scope: Uploaded pictures\n  period: about a day\n  text: The uploaded file is kept in private storage for about a day while your codes are made and is then deleted,\n    normally within 25 hours of the upload\n- scope: Feedback\n  period:\
  \ 12 months\n  text: 'How long we keep it : 12 months, after which we delete it, with any image, from our database and our team\n    chat.'\nresidency:\n- region: Australia\n  text: We store your personal information in Australia.\ntransfers:\n- mechanism: SCC\n  text: including standard contractual clauses in our agreements with third parties that are overseas.\n- mechanism: adequacy\n  text: only transferring your personal information to countries that have been deemed by applicable data protection\n    laws to provide an adequate level of protection for personal information\nsubprocessors:\n  url: null\n  text: IT service providers including Clerk, data storage, web-hosting and server providers;\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion in the app, or email hello@qrx.codes for feedback deletion\n  text: you can delete your account in the app (Account, then Delete account)\nrights:\n- right: Access\n  text: You may request access to the\
  \ personal information that we hold about you.\n- right: Correction\n  text: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant\n    or misleading, please contact us using the details below.\n- right: Objection and unsubscribe\n  text: To object to processing for direct marketing/unsubscribe from our email database or opt-out of communications\n    (including marketing communications), please contact us using the details below\n- right: Complaint\n  text: If you wish to make a complaint, please contact us using the details below and provide us with full details\n    of the complaint.\n- right: Erasure, restriction and portability (EU/UK)\n  text: to have your personal information rectified or deleted, to restrict our processing of that information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell this information, and we share it only with the service providers described above that help\n    us make, store and deliver\
  \ your codes.\n"
source_yaml_url: https://artifacts.apis.io/qrx/privacy/qrx-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from QRX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- QR Codes
- Artificial Intelligence
- Art
---
