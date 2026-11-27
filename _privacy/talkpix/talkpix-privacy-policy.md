---
api_specs:
- filename: talkpix-estimate-api-openapi.yml
  format: yaml
  label: TalkPix API Estimate API
  slug: talkpix-estimate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-estimate-api-openapi.yml
- filename: talkpix-me-api-openapi.yml
  format: yaml
  label: TalkPix API Me API
  slug: talkpix-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-me-api-openapi.yml
- filename: talkpix-talkpix-api-api-api-openapi.yml
  format: yaml
  label: TalkPix API TalkPix API API
  slug: talkpix-talkpix-api-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-talkpix-api-api-api-openapi.yml
- filename: talkpix-uploads-api-openapi.yml
  format: yaml
  label: TalkPix API Uploads API
  slug: talkpix-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-uploads-api-openapi.yml
- filename: talkpix-videos-api-openapi.yml
  format: yaml
  label: TalkPix API Videos API
  slug: talkpix-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-videos-api-openapi.yml
- filename: talkpix-voices-api-openapi.yml
  format: yaml
  label: TalkPix API Voices API
  slug: talkpix-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-voices-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email address and basic profile.'
  - category: biometric
    text: We do not build a faceprint or face-geometry template, do not run face recognition, and do not attempt to identify, match, or verify anyone from a photo.
  - category: financial
    text: We never see or store your full card number.
  - category: communication
    text: 'Support and reports: messages you send us, support tickets, and reports submitted about publicly shared content.'
  - category: behavioral
    text: 'Explore activity: the videos you like, the creators you block and the reports you send'
  - category: device
    text: analytics cookies and advertising identifiers (such as Google gclid , UTM parameters, and click identifiers from other ad platforms)
  deletion:
    route: Account → Delete your account, or email support@talkpix.ai
    text: You can delete your account yourself at any time under Account → Delete your account , or by emailing support@talkpix.ai from the account’s address
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Generate requested videos
    text: Generate the videos you request and let you access your results.
  - purpose: Process payments
    text: Process payments and maintain your credit balance.
  - purpose: Operate and improve service
    text: Operate, secure, and improve the service, and measure our advertising.
  - purpose: Legal compliance
    text: Comply with the law and enforce our Terms of Use.
  retention:
  - period: 30 days
    scope: Generation inputs and outputs from video and image studios
    text: are automatically deleted 30 days after they are created by a daily sweep.
  - period: six years
    scope: Account, credit-ledger and transaction records after deletion
    text: 'So for six years from deletion we keep, without your email address: each order’s date, type, template, length, credits and status'
  - period: null
    scope: Saved libraries such as cloned voices and characters
    text: These are kept until you delete them, or ask us to
  rights:
  - right: access, correct, export, or delete
    text: you may have the right to access, correct, export, or delete your personal data, and to object to certain processing.
  - right: complain to supervisory authority
    text: You also have the right to complain to a supervisory authority.
  role:
    text: TalkPix is an independent business operated from Türkiye , and is the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data or use your uploaded photos, audio, scripts, or generated media to train AI models.
  subprocessors:
    text: the apps show this list and ask your permission before your first upload
    url: null
  transfers:
  - mechanism: other
    text: Where the law requires it, those transfers rely on the standard contractual protections offered in each provider’s data processing terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TalkPix API
provenance_date: '2026-11-10'
provider_name: TalkPix API
provider_slug: talkpix
slug: talkpix-privacy-policy
source_date: '2026-11-10'
source_filename: talkpix-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.talkpix.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TalkPix API\naid: talkpix\nurl: https://www.talkpix.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: TalkPix is an independent business operated from Türkiye , and is the data controller for the personal data\n    described here.\ndata_categories:\n- category: identifying\n  text: 'Account data: your email address and basic profile.'\n- category: biometric\n  text: We do not build a faceprint or face-geometry template, do not run face recognition, and do not attempt to\n    identify, match, or verify anyone from a photo.\n- category: financial\n  text: We never see or store your full\
  \ card number.\n- category: communication\n  text: 'Support and reports: messages you send us, support tickets, and reports submitted about publicly shared\n    content.'\n- category: behavioral\n  text: 'Explore activity: the videos you like, the creators you block and the reports you send'\n- category: device\n  text: analytics cookies and advertising identifiers (such as Google gclid , UTM parameters, and click identifiers\n    from other ad platforms)\npurposes:\n- purpose: Generate requested videos\n  text: Generate the videos you request and let you access your results.\n- purpose: Process payments\n  text: Process payments and maintain your credit balance.\n- purpose: Operate and improve service\n  text: Operate, secure, and improve the service, and measure our advertising.\n- purpose: Legal compliance\n  text: Comply with the law and enforce our Terms of Use.\nretention:\n- scope: Generation inputs and outputs from video and image studios\n  period: 30 days\n  text: are automatically\
  \ deleted 30 days after they are created by a daily sweep.\n- scope: Account, credit-ledger and transaction records after deletion\n  period: six years\n  text: 'So for six years from deletion we keep, without your email address: each order’s date, type, template,\n    length, credits and status'\n- scope: Saved libraries such as cloned voices and characters\n  period: null\n  text: These are kept until you delete them, or ask us to\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where the law requires it, those transfers rely on the standard contractual protections offered in each\n    provider’s data processing terms.\nsubprocessors:\n  url: null\n  text: the apps show this list and ask your permission before your first upload\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account → Delete your account, or email support@talkpix.ai\n  text: You can delete your account yourself at any time under Account → Delete your account , or by emailing support@talkpix.ai\n\
  \    from the account’s address\nrights:\n- right: access, correct, export, or delete\n  text: you may have the right to access, correct, export, or delete your personal data, and to object to certain\n    processing.\n- right: complain to supervisory authority\n  text: You also have the right to complain to a supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data or use your uploaded photos, audio, scripts, or generated media to train\n    AI models.\n"
source_yaml_url: https://artifacts.apis.io/talkpix/privacy/talkpix-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from TalkPix API's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Talking Photo
- Media
---
