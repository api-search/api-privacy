---
api_specs:
- filename: anyimagedetector-detection-api-openapi.yml
  format: yaml
  label: AnyImageDetector Detection API
  slug: anyimagedetector-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyimagedetector/openapi/anyimagedetector-detection-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account Information — Your name, email address, and other details you provide when creating an account.
  - category: device
    text: Device Information — Device type, operating system, and browser type, used to optimize compatibility and performance.
  - category: behavioral
    text: Usage Data — Information about how you interact with the service, including features accessed, frequency of use, and interaction patterns.
  - category: financial
    text: Payment Information — Billing details handled by trusted third-party payment processors. We do not store full card numbers on our servers.
  - category: other
    text: Detection Content — The image file or public image URL you submit, plus the result metadata needed to provide the requested detection.
  - category: behavioral
    text: Session Replay Data — A visual reconstruction of selected production sessions that helps us understand navigation, interaction patterns, and product failures.
  deletion:
    route: Account settings or contacting us by email
    text: You can do this through your account settings or by contacting us at the email address below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve service
    text: Provide, maintain, and improve the service.
  - purpose: Process transactions
    text: Process transactions and send related confirmations.
  - purpose: Fraud and abuse prevention
    text: Detect, prevent, and address fraud and abuse.
  - purpose: Return detection result
    text: Process a submitted image solely to return the requested detection result.
  - purpose: Usability diagnosis via session replay
    text: Diagnose usability issues and improve the service using privacy-protected session replays.
  retention:
  - period: null
    scope: Submitted image files
    text: Submitted image files are not added to your detection history.
  - period: null
    scope: Result metadata for signed-in users
    text: For signed-in users, result metadata such as the score and verdict may remain in detection history until it is deleted under the available account controls or retention process.
  - period: null
    scope: Session replays
    text: Privacy-protected session replays are retained for a limited period according to our analytics provider's configured retention.
  - period: null
    scope: Security, billing, and usage logs
    text: Security, billing, and usage logs are retained only as reasonably needed to operate the service, prevent abuse, and meet legal obligations.
  rights:
  - right: Access
    text: You have the right to access, update, export, or delete your personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AnyImageDetector
provenance_date: '2026-11-09'
provider_name: AnyImageDetector
provider_slug: anyimagedetector
slug: anyimagedetector-privacy-policy
source_date: '2026-11-09'
source_filename: anyimagedetector-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://imagedetector.online/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AnyImageDetector\naid: anyimagedetector\nurl: https://imagedetector.online/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account Information — Your name, email address, and other details you provide when creating an account.\n- category: device\n  text: Device Information — Device type, operating system, and browser type, used to optimize compatibility and\n    performance.\n- category: behavioral\n  text: Usage Data — Information about how you interact with the service, including features accessed, frequency\n    of use,\
  \ and interaction patterns.\n- category: financial\n  text: Payment Information — Billing details handled by trusted third-party payment processors. We do not store\n    full card numbers on our servers.\n- category: other\n  text: Detection Content — The image file or public image URL you submit, plus the result metadata needed to provide\n    the requested detection.\n- category: behavioral\n  text: Session Replay Data — A visual reconstruction of selected production sessions that helps us understand navigation,\n    interaction patterns, and product failures.\npurposes:\n- purpose: Provide and improve service\n  text: Provide, maintain, and improve the service.\n- purpose: Process transactions\n  text: Process transactions and send related confirmations.\n- purpose: Fraud and abuse prevention\n  text: Detect, prevent, and address fraud and abuse.\n- purpose: Return detection result\n  text: Process a submitted image solely to return the requested detection result.\n- purpose: Usability\
  \ diagnosis via session replay\n  text: Diagnose usability issues and improve the service using privacy-protected session replays.\nretention:\n- scope: Submitted image files\n  period: null\n  text: Submitted image files are not added to your detection history.\n- scope: Result metadata for signed-in users\n  period: null\n  text: For signed-in users, result metadata such as the score and verdict may remain in detection history until\n    it is deleted under the available account controls or retention process.\n- scope: Session replays\n  period: null\n  text: Privacy-protected session replays are retained for a limited period according to our analytics provider's\n    configured retention.\n- scope: Security, billing, and usage logs\n  period: null\n  text: Security, billing, and usage logs are retained only as reasonably needed to operate the service, prevent\n    abuse, and meet legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or contacting us by email\n  text: You can do this through your account settings or by contacting us at the email address below.\nrights:\n- right: Access\n  text: You have the right to access, update, export, or delete your personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/anyimagedetector/privacy/anyimagedetector-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from AnyImageDetector's own page on 2026-11-09.
synthetic: false
tags:
- AI image detection
- Image Analysis
- Computer Vision
- Content Moderation
- Trust and Safety
- Fact Checking
- media verification
- Developer Tools
- Synthetic Media
- Fraud Prevention
---
