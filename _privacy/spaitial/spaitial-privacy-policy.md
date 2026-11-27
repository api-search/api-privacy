---
api_specs:
- filename: spaitial-files-api-openapi.yml
  format: yaml
  label: SpAItial Files API
  slug: spaitial-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-files-api-openapi.yml
- filename: spaitial-models-api-openapi.yml
  format: yaml
  label: SpAItial Models API
  slug: spaitial-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-models-api-openapi.yml
- filename: spaitial-panoramas-api-openapi.yml
  format: yaml
  label: SpAItial Panoramas API
  slug: spaitial-panoramas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-panoramas-api-openapi.yml
- filename: spaitial-worlds-api-openapi.yml
  format: yaml
  label: SpAItial Worlds API
  slug: spaitial-worlds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-worlds-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name; last name.
  - category: contact
    text: Delivery address; billing address; email address; telephone number.
  - category: financial
    text: Bank account details; payment card details.
  - category: behavioral
    text: Data relating to your browsing and in-product activity, obtained through cookies, analytics scripts and similar technologies (including, where you have consented, PostHog)
  - category: device
    text: IP address; browser type and operating system; geolocation, to ensure we’re showing you the correct notices and information
  - category: location
    text: geolocation, to ensure we’re showing you the correct notices and information
  - category: communication
    text: the content of any messaging you send using contact channels made available on the Site
  - category: other
    text: Content that you upload, submit or otherwise make available through our Services, including images, text prompts, instructions and other inputs provided to our AI-powered features ("Input Data")
  - category: other
    text: The SpAItial Capture account, notification, camera-frame, ARKit environment-scanning, optional raw motion, diagnostic and App Store transaction data described in "SPAITIAL CAPTURE".
  deletion:
    route: Settings > Delete account in SpAItial Capture or the SpAItial dashboard, or email privacy@spaitial.ai
    text: You can initiate deletion of your SpAItial account under Settings > Delete account in SpAItial Capture or the SpAItial dashboard (accounts linked to Sign in with Apple must use SpAItial Capture), or contact privacy@spaitial.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Site usage analysis
    text: We do this so that we can better understand which parts of our Site are more or less popular and improve the structure and navigation of our Site.
  - purpose: Capture 3D world generation
    text: We use capture images and environment-scanning data to upload, align, reconstruct and deliver the 3D world you request.
  - purpose: AI model training and service improvement
    text: This includes using such data to train and fine-tune our proprietary AI models.
  - purpose: Marketing by email
    text: We use your Identity Data, Contact Data and Marketing and Communications Data to send you (or the organisation you represent) marketing communications by email where you have opted in
  - purpose: Customer service
    text: We use this information to manage and respond to your enquiry.
  residency:
  - region: Europe
    text: SpAItial is based in Europe and provides Services globally, including to users in the United States.
  retention:
  - period: up to three years
    scope: Other personal data
    text: Where we process any other personal data, we will retain relevant personal data for up to three years from the date of our last interaction with you
  - period: indefinitely
    scope: Marketing suppression list
    text: we will need to retain certain personal data on a suppression list indefinitely
  - period: null
    scope: Local capture bundles
    text: Local capture bundles stay on your iPhone until you delete the scan in SpAItial Capture or remove the app.
  rights:
  - right: access
    text: to obtain copies of your personal data
  - right: rectification
    text: to have your personal data corrected or deleted
  - right: restriction
    text: to limit the way in which your personal data is used
  - right: objection
    text: to object to our use of your personal data
  - right: portability
    text: to transfer your personal data
  - right: automated decision-making
    text: not to be subject to decisions based on automated processing (including profiling)
  - right: complaint
    text: to complain to a supervisory authority
  role:
    text: For the purpose of the UK GDPR SpAItial Ltd will be considered an independent controller of your personal data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Our current subprocessors are listed publicly.
    url: https://spaitial.ai/subprocessors
  transfers:
  - mechanism: adequacy
    text: We may transfer your personal data to countries that have been deemed to provide an adequate level of protection for personal data by the European Commission and/or by the UK government.
  - mechanism: SCC
    text: Where we use certain service providers, we may use specific contracts approved by the European Commission and/or the ICO which give personal data similar protection to the protection it has in the UK and EEA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SpAItial
provenance_date: '2026-11-10'
provider_name: SpAItial
provider_slug: spaitial
slug: spaitial-privacy-policy
source_date: '2026-11-10'
source_filename: spaitial-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://spaitial.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SpAItial\naid: spaitial\nurl: https://spaitial.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the purpose of the UK GDPR SpAItial Ltd will be considered an independent controller of your personal\n    data.\ndata_categories:\n- category: identifying\n  text: First name; last name.\n- category: contact\n  text: Delivery address; billing address; email address; telephone number.\n- category: financial\n  text: Bank account details; payment card details.\n- category: behavioral\n  text: Data relating to your browsing and in-product activity, obtained through cookies, analytics\
  \ scripts and\n    similar technologies (including, where you have consented, PostHog)\n- category: device\n  text: IP address; browser type and operating system; geolocation, to ensure we’re showing you the correct notices\n    and information\n- category: location\n  text: geolocation, to ensure we’re showing you the correct notices and information\n- category: communication\n  text: the content of any messaging you send using contact channels made available on the Site\n- category: other\n  text: Content that you upload, submit or otherwise make available through our Services, including images, text\n    prompts, instructions and other inputs provided to our AI-powered features (\"Input Data\")\n- category: other\n  text: The SpAItial Capture account, notification, camera-frame, ARKit environment-scanning, optional raw motion,\n    diagnostic and App Store transaction data described in \"SPAITIAL CAPTURE\".\npurposes:\n- purpose: Site usage analysis\n  text: We do this so that we can\
  \ better understand which parts of our Site are more or less popular and improve\n    the structure and navigation of our Site.\n- purpose: Capture 3D world generation\n  text: We use capture images and environment-scanning data to upload, align, reconstruct and deliver the 3D world\n    you request.\n- purpose: AI model training and service improvement\n  text: This includes using such data to train and fine-tune our proprietary AI models.\n- purpose: Marketing by email\n  text: We use your Identity Data, Contact Data and Marketing and Communications Data to send you (or the organisation\n    you represent) marketing communications by email where you have opted in\n- purpose: Customer service\n  text: We use this information to manage and respond to your enquiry.\nretention:\n- scope: Other personal data\n  period: up to three years\n  text: Where we process any other personal data, we will retain relevant personal data for up to three years from\n    the date of our last interaction\
  \ with you\n- scope: Marketing suppression list\n  period: indefinitely\n  text: we will need to retain certain personal data on a suppression list indefinitely\n- scope: Local capture bundles\n  period: null\n  text: Local capture bundles stay on your iPhone until you delete the scan in SpAItial Capture or remove the app.\nresidency:\n- region: Europe\n  text: SpAItial is based in Europe and provides Services globally, including to users in the United States.\ntransfers:\n- mechanism: adequacy\n  text: We may transfer your personal data to countries that have been deemed to provide an adequate level of protection\n    for personal data by the European Commission and/or by the UK government.\n- mechanism: SCC\n  text: Where we use certain service providers, we may use specific contracts approved by the European Commission\n    and/or the ICO which give personal data similar protection to the protection it has in the UK and EEA.\nsubprocessors:\n  url: https://spaitial.ai/subprocessors\n\
  \  text: Our current subprocessors are listed publicly.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings > Delete account in SpAItial Capture or the SpAItial dashboard, or email privacy@spaitial.ai\n  text: You can initiate deletion of your SpAItial account under Settings > Delete account in SpAItial Capture or\n    the SpAItial dashboard (accounts linked to Sign in with Apple must use SpAItial Capture), or contact privacy@spaitial.ai\n    .\nrights:\n- right: access\n  text: to obtain copies of your personal data\n- right: rectification\n  text: to have your personal data corrected or deleted\n- right: restriction\n  text: to limit the way in which your personal data is used\n- right: objection\n  text: to object to our use of your personal data\n- right: portability\n  text: to transfer your personal data\n- right: automated decision-making\n  text: not to be subject to decisions based on automated processing (including profiling)\n- right: complaint\n\
  \  text: to complain to a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spaitial/privacy/spaitial-privacy-policy.yml
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
summary_line: 30 quoted statements, read from SpAItial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Spatial AI
- World Models
- 3D
- Gaussian Splatting
- Generative AI
- Developer API
- MCP
---
