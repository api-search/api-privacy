---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your name, email address, and password.
  - category: financial
    text: We retain transaction records including subscription tier and renewal date for account management purposes.
  - category: biometric
    text: Face images uploaded for features such as Virtual Try-On and Swap Face are used solely to fulfill your generation request and are not used to identify you or any individual.
  - category: device
    text: Device model, operating system version, and app version
  - category: behavioral
    text: Pages visited, features used, tool interactions, and session duration.
  - category: communication
    text: If you contact our support team or submit feedback, we retain the contents of your messages and metadata to resolve your inquiry and improve our Services.
  - category: location
    text: IP address
  deletion:
    route: In-app Settings > Account > Delete Account, or email support@fashiondiffusion.ai
    text: To delete your account and associated data from within the iOS app, go to Settings > Account > Delete Account .
  dpa:
    available: null
    text: Each provider is bound by strict data processing agreements.
    url: null
  purposes:
  - purpose: Provide and operate the platform
    text: Provide and operate the platform and mobile application
  - purpose: Process AI generation requests
    text: Process AI generation requests
  - purpose: Manage subscription and payments
    text: Manage your subscription and payments
  - purpose: Detect fraud or misuse
    text: Detect fraud or misuse
  - purpose: Marketing emails with opt-in
    text: If you opt in, we may send product updates and marketing emails.
  residency:
  - region: United States
    text: All data is hosted on AWS infrastructure in the United States
  retention:
  - period: 24 hours
    scope: Temporary AI processing copies
    text: Processing copies created during inference are deleted within 24 hours of generation.
  - period: life of your account plus 30 days
    scope: Account data
    text: We retain account data for the life of your account plus 30 days
  - period: 7 years
    scope: Billing records
    text: billing records for 7 years as required by law
  rights:
  - right: Access, correction, deletion
    text: You may request to access, correct, or delete your personal data at any time by contacting us
  - right: GDPR portability, restriction, complaint
    text: 'EEA / UK / Switzerland users: You have additional rights under GDPR including data portability, restriction of processing, and the right to lodge a complaint with your local data protection authority.'
  - right: CCPA know and deletion
    text: 'California residents: You have rights under the CCPA to know what data we hold and to request its deletion.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal data.
  subprocessors:
    text: AWS — cloud hosting and storage
    url: null
  transfers:
  - mechanism: SCC
    text: For data transfers to the US, we rely on Standard Contractual Clauses (SCCs).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fashion Diffusion
provenance_date: '2026-11-09'
provider_name: Fashion Diffusion
provider_slug: fashiondiffusion
slug: fashiondiffusion-privacy-policy
source_date: '2026-11-09'
source_filename: fashiondiffusion-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fashiondiffusion.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fashion Diffusion\naid: fashiondiffusion\nurl: https://www.fashiondiffusion.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your name, email address, and password.\n- category: financial\n  text: We retain transaction records including subscription tier and renewal date for account management purposes.\n- category: biometric\n  text: Face images uploaded for features such as Virtual Try-On and Swap Face are used solely to fulfill your generation\n    request and are not used to identify\
  \ you or any individual.\n- category: device\n  text: Device model, operating system version, and app version\n- category: behavioral\n  text: Pages visited, features used, tool interactions, and session duration.\n- category: communication\n  text: If you contact our support team or submit feedback, we retain the contents of your messages and metadata\n    to resolve your inquiry and improve our Services.\n- category: location\n  text: IP address\npurposes:\n- purpose: Provide and operate the platform\n  text: Provide and operate the platform and mobile application\n- purpose: Process AI generation requests\n  text: Process AI generation requests\n- purpose: Manage subscription and payments\n  text: Manage your subscription and payments\n- purpose: Detect fraud or misuse\n  text: Detect fraud or misuse\n- purpose: Marketing emails with opt-in\n  text: If you opt in, we may send product updates and marketing emails.\nretention:\n- scope: Temporary AI processing copies\n  period: 24 hours\n\
  \  text: Processing copies created during inference are deleted within 24 hours of generation.\n- scope: Account data\n  period: life of your account plus 30 days\n  text: We retain account data for the life of your account plus 30 days\n- scope: Billing records\n  period: 7 years\n  text: billing records for 7 years as required by law\nresidency:\n- region: United States\n  text: All data is hosted on AWS infrastructure in the United States\ntransfers:\n- mechanism: SCC\n  text: For data transfers to the US, we rely on Standard Contractual Clauses (SCCs).\nsubprocessors:\n  url: null\n  text: AWS — cloud hosting and storage\ndpa:\n  available: null\n  url: null\n  text: Each provider is bound by strict data processing agreements.\ndeletion:\n  route: In-app Settings > Account > Delete Account, or email support@fashiondiffusion.ai\n  text: To delete your account and associated data from within the iOS app, go to Settings > Account > Delete Account\n    .\nrights:\n- right: Access, correction,\
  \ deletion\n  text: You may request to access, correct, or delete your personal data at any time by contacting us\n- right: GDPR portability, restriction, complaint\n  text: 'EEA / UK / Switzerland users: You have additional rights under GDPR including data portability, restriction\n    of processing, and the right to lodge a complaint with your local data protection authority.'\n- right: CCPA know and deletion\n  text: 'California residents: You have rights under the CCPA to know what data we hold and to request its deletion.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal data.\n"
source_yaml_url: https://artifacts.apis.io/fashiondiffusion/privacy/fashiondiffusion-privacy-policy.yml
stated_fields:
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
summary_line: 24 quoted statements, read from Fashion Diffusion's own page on 2026-11-09.
synthetic: false
tags:
- Fashion
- E-Commerce
- Retail
- Generative AI
- Image Generation
- Virtual Try-On
- Computer Vision
- Video Generation
- Product Photography
- Creative / Design Tools
---
