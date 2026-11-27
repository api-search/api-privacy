---
api_specs:
- filename: lightricks-asyncvideogeneration-api-openapi.yml
  format: yaml
  label: Lightricks Async Video Generation API
  slug: lightricks-asyncvideogeneration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightricks/openapi/lightricks-asyncvideogeneration-api-openapi.yml
- filename: lightricks-upload-api-openapi.yml
  format: yaml
  label: Lightricks Upload API
  slug: lightricks-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightricks/openapi/lightricks-upload-api-openapi.yml
- filename: lightricks-video-generation-api-openapi.yml
  format: yaml
  label: Lightricks Video Generation API
  slug: lightricks-video-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightricks/openapi/lightricks-video-generation-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: financial
    text: payment information (which will include your bank account details or Apple-Pay/Google - Pay account)
  - category: behavioral
    text: Services, features used, time stamp and duration of use, click stream data, errors that occurred
  - category: location
    text: your approximate location extracted from the IP address (e.g., country and Zip)
  - category: demographic
    text: demographic data, such as age (or age group) and gender and other characteristics such as skin tone
  deletion:
    route: Request deletion of your Personal Data and account, or delete the project or App
    text: Your output image or other created artwork will be stored on our Lightricks Cloud until you request us to delete your Personal Data and your account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: AI training and machine learning (consent-based)
    text: Subject to your consent, we will use the data sets listed under this Table B for AI training and machine learning purposes (“ AI Training Data ”).
  - purpose: Direct marketing
    text: We may further send you other materials and content, including marketing materials (“Direct Marketing”).
  - purpose: Interest-based advertising
    text: Some of the Apps further display interest -based ads or other marke ting and promotions which are based on the Usage Data.
  retention:
  - period: up to 30 days
    scope: Uploaded photos, videos and images
    text: The photos, videos and images you upload are stored for up to 30 days
  - period: up to 30 days
    scope: AI Tools Inputs
    text: Inputs are usually retained for a short-term period of up to 30 days after the AI Tools Outputs are generated
  - period: within 2 years
    scope: Face and Voice Recognition Models and Face and Voice Models
    text: Face and Voice Recognition Models and Face and Voice Models will be permanently deleted within 2 years after the last time you have used our Services
  - period: 24 hours
    scope: Face Data in App models
    text: Face and Voice Recognition Models, or Face and Voice Models, are automatically deleted within 24 hours.
  - period: within 2 years
    scope: AI Training Data
    text: AI Training Data will be permanently deleted within 2 years after we process them for training purposes
  rights:
  - right: Withdraw consent
    text: You have the right to withdraw your consent at any time, as set forth under Section 8 Your Rights, below, or through the App’s Privacy Settings.
  - right: Opt out of direct marketing
    text: You can opt -out at any time through the “ unsubscribe” link within the email at any time
  role:
    text: Lightricks Ltd. is incorporated under the laws of the state of Israel and, unless otherwise explicitly mentioned in the table below, is the “ data controller ”
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lightricks
provenance_date: '2026-11-09'
provider_name: Lightricks
provider_slug: lightricks
slug: lightricks-privacy-policy
source_date: '2026-11-09'
source_filename: lightricks-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://static.lightricks.com/legal/privacy-policy.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lightricks\naid: lightricks\nurl: https://static.lightricks.com/legal/privacy-policy.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Lightricks Ltd. is incorporated under the laws of the state of Israel and, unless otherwise explicitly mentioned\n    in the table below, is the “ data controller ”\ndata_categories:\n- category: financial\n  text: payment information (which will include your bank account details or Apple-Pay/Google - Pay account)\n- category: behavioral\n  text: Services, features used, time stamp and duration of use, click stream data, errors that occurred\n\
  - category: location\n  text: your approximate location extracted from the IP address (e.g., country and Zip)\n- category: demographic\n  text: demographic data, such as age (or age group) and gender and other characteristics such as skin tone\npurposes:\n- purpose: AI training and machine learning (consent-based)\n  text: Subject to your consent, we will use the data sets listed under this Table B for AI training and machine\n    learning purposes (“ AI Training Data ”).\n- purpose: Direct marketing\n  text: We may further send you other materials and content, including marketing materials (“Direct Marketing”).\n- purpose: Interest-based advertising\n  text: Some of the Apps further display interest -based ads or other marke ting and promotions which are based\n    on the Usage Data.\nretention:\n- scope: Uploaded photos, videos and images\n  period: up to 30 days\n  text: The photos, videos and images you upload are stored for up to 30 days\n- scope: AI Tools Inputs\n  period: up to\
  \ 30 days\n  text: Inputs are usually retained for a short-term period of up to 30 days after the AI Tools Outputs are generated\n- scope: Face and Voice Recognition Models and Face and Voice Models\n  period: within 2 years\n  text: Face and Voice Recognition Models and Face and Voice Models will be permanently deleted within 2 years after\n    the last time you have used our Services\n- scope: Face Data in App models\n  period: 24 hours\n  text: Face and Voice Recognition Models, or Face and Voice Models, are automatically deleted within 24 hours.\n- scope: AI Training Data\n  period: within 2 years\n  text: AI Training Data will be permanently deleted within 2 years after we process them for training purposes\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of your Personal Data and account, or delete the project or App\n  text: Your output image or other created artwork\
  \ will be stored on our Lightricks Cloud until you request us to\n    delete your Personal Data and your account\nrights:\n- right: Withdraw consent\n  text: You have the right to withdraw your consent at any time, as set forth under Section 8 Your Rights, below,\n    or through the App’s Privacy Settings.\n- right: Opt out of direct marketing\n  text: You can opt -out at any time through the “ unsubscribe” link within the email at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lightricks/privacy/lightricks-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from Lightricks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Artificial Intelligence
- Generative AI
- Video
- Video Generation
- Media
- Machine Learning
- Creative Tools
---
