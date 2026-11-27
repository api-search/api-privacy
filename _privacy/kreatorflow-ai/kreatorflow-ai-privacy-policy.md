---
api_specs:
- filename: kreatorflow-ai-audio-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Audio API
  slug: kreatorflow-ai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-audio-api-openapi.yml
- filename: kreatorflow-ai-images-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Images API
  slug: kreatorflow-ai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-images-api-openapi.yml
- filename: kreatorflow-ai-jobs-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Jobs API
  slug: kreatorflow-ai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-jobs-api-openapi.yml
- filename: kreatorflow-ai-lip-sync-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Lip Sync API
  slug: kreatorflow-ai-lip-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-lip-sync-api-openapi.yml
- filename: kreatorflow-ai-mcp-api-openapi.yml
  format: yaml
  label: kreatorflow-ai MCP API
  slug: kreatorflow-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-mcp-api-openapi.yml
- filename: kreatorflow-ai-models-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Models API
  slug: kreatorflow-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-models-api-openapi.yml
- filename: kreatorflow-ai-uploads-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Uploads API
  slug: kreatorflow-ai-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-uploads-api-openapi.yml
- filename: kreatorflow-ai-video-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Video API
  slug: kreatorflow-ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-video-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account : email address, display name, username (your public handle), and optionally a bio, profile picture and cover image.'
  - category: demographic
    text: 'Age and country : your date of birth, to confirm you are 18 or over, and your country'
  - category: financial
    text: 'Payments : your plan, purchases, credit and token balances and history.'
  - category: biometric
    text: voice samples you use for voice cloning
  - category: behavioral
    text: 'Usage : pages you visit, the site that sent you, campaign tags in the link, and steps in sign-up and checkout'
  - category: device
    text: 'Sign-in records : for each session, your IP address and browser details'
  - category: communication
    text: 'Support : messages and attachments you send us (including email replies to our support emails)'
  deletion:
    route: Settings lets you delete your account
    text: You can download your data or delete your account in Settings at any time.
  dpa:
    available: true
    text: under our Data Processing Addendum , which forms part of the API terms
    url: null
  purposes:
  - purpose: Run account and service
    text: Create and run your account, make the images, videos and audio you request, save your library, run the editor, API and connector
  - purpose: Payments and receipts
    text: Take payments, give credits and tokens, send receipts and service emails
  - purpose: Safety checks
    text: Safety checks on prompts, uploads and outputs; review of Explore posts; handling reports, takedowns and appeals
  - purpose: Fraud prevention
    text: Preventing fraud, payment abuse and multiple accounts for free credits; securing sign-in; error monitoring
  - purpose: Marketing emails
    text: Marketing emails and offers Consent (the box at sign-up, which you can withdraw at any time)
  residency:
  - region: Malaysia and Singapore
    text: Our database, file storage and servers are in Malaysia and Singapore.
  retention:
  - period: About 30 days after you delete your account
    scope: Account and profile
    text: About 30 days after you delete your account, we delete or anonymise your personal data
  - period: 90 days after the job finishes
    scope: API job inputs
    text: API job inputs (prompts and request details) 90 days after the job finishes
  - period: 12 months after the session ends
    scope: Sign-in records
    text: Sign-in records (IP address and browser) 12 months after the session ends
  - period: 7 years
    scope: Payment, tax and accounting records
    text: Payment, tax and accounting records 7 years, as the law requires
  - period: 30 to 45 days
    scope: Error logs
    text: Error logs 30 to 45 days
  - period: 12 months
    scope: Confirmations for faces and voices
    text: Confirmations for faces and voices While your account is open, then 12 months
  rights:
  - right: access
    text: access your data and get a copy (Settings has a download of your account data, or email us)
  - right: correct
    text: correct inaccurate data
  - right: delete
    text: delete your data (Settings lets you delete your account, including Google sign-in accounts)
  - right: restrict and object
    text: restrict how we use your data, and object to uses based on legitimate interests, including marketing, which we will always stop
  - right: portability
    text: receive the data you gave us in a machine-readable format
  - right: withdraw consent
    text: withdraw consent at any time
  role:
    text: 'We decide how and why your personal data is used, so we are its controller . The one exception is personal data that developers and business customers send us about their own users through the API: there we act for them as a processor (see section 11).'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data or share it for other companies' advertising.
  subprocessors:
    text: Our Cookie Policy names the companies whose cookies you can allow, and we will give the names of our other providers on request at privacy@kreatorflow.ai
    url: null
  transfers:
  - mechanism: other
    text: we protect it with the UK International Data Transfer Agreement or the UK Addendum to the EU Standard Contractual Clauses (and the EU Standard Contractual Clauses for data from the EU)
  - mechanism: DPF
    text: except US companies certified under the UK-US Data Bridge or EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: kreatorflow-ai
provenance_date: '2026-11-09'
provider_name: kreatorflow-ai
provider_slug: kreatorflow-ai
slug: kreatorflow-ai-privacy-policy
source_date: '2026-11-09'
source_filename: kreatorflow-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kreatorflow.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: kreatorflow-ai\naid: kreatorflow-ai\nurl: https://kreatorflow.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'We decide how and why your personal data is used, so we are its controller . The one exception is personal\n    data that developers and business customers send us about their own users through the API: there we act for\n    them as a processor (see section 11).'\ndata_categories:\n- category: identifying\n  text: 'Account : email address, display name, username (your public handle), and optionally a bio, profile picture\n    and cover image.'\n- category: demographic\n  text:\
  \ 'Age and country : your date of birth, to confirm you are 18 or over, and your country'\n- category: financial\n  text: 'Payments : your plan, purchases, credit and token balances and history.'\n- category: biometric\n  text: voice samples you use for voice cloning\n- category: behavioral\n  text: 'Usage : pages you visit, the site that sent you, campaign tags in the link, and steps in sign-up and checkout'\n- category: device\n  text: 'Sign-in records : for each session, your IP address and browser details'\n- category: communication\n  text: 'Support : messages and attachments you send us (including email replies to our support emails)'\npurposes:\n- purpose: Run account and service\n  text: Create and run your account, make the images, videos and audio you request, save your library, run the editor,\n    API and connector\n- purpose: Payments and receipts\n  text: Take payments, give credits and tokens, send receipts and service emails\n- purpose: Safety checks\n  text: Safety checks\
  \ on prompts, uploads and outputs; review of Explore posts; handling reports, takedowns and\n    appeals\n- purpose: Fraud prevention\n  text: Preventing fraud, payment abuse and multiple accounts for free credits; securing sign-in; error monitoring\n- purpose: Marketing emails\n  text: Marketing emails and offers Consent (the box at sign-up, which you can withdraw at any time)\nretention:\n- scope: Account and profile\n  period: About 30 days after you delete your account\n  text: About 30 days after you delete your account, we delete or anonymise your personal data\n- scope: API job inputs\n  period: 90 days after the job finishes\n  text: API job inputs (prompts and request details) 90 days after the job finishes\n- scope: Sign-in records\n  period: 12 months after the session ends\n  text: Sign-in records (IP address and browser) 12 months after the session ends\n- scope: Payment, tax and accounting records\n  period: 7 years\n  text: Payment, tax and accounting records 7 years, as\
  \ the law requires\n- scope: Error logs\n  period: 30 to 45 days\n  text: Error logs 30 to 45 days\n- scope: Confirmations for faces and voices\n  period: 12 months\n  text: Confirmations for faces and voices While your account is open, then 12 months\nresidency:\n- region: Malaysia and Singapore\n  text: Our database, file storage and servers are in Malaysia and Singapore.\ntransfers:\n- mechanism: other\n  text: we protect it with the UK International Data Transfer Agreement or the UK Addendum to the EU Standard Contractual\n    Clauses (and the EU Standard Contractual Clauses for data from the EU)\n- mechanism: DPF\n  text: except US companies certified under the UK-US Data Bridge or EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: Our Cookie Policy names the companies whose cookies you can allow, and we will give the names of our other\n    providers on request at privacy@kreatorflow.ai\ndpa:\n  available: true\n  url: null\n  text: under our Data Processing Addendum\
  \ , which forms part of the API terms\ndeletion:\n  route: Settings lets you delete your account\n  text: You can download your data or delete your account in Settings at any time.\nrights:\n- right: access\n  text: access your data and get a copy (Settings has a download of your account data, or email us)\n- right: correct\n  text: correct inaccurate data\n- right: delete\n  text: delete your data (Settings lets you delete your account, including Google sign-in accounts)\n- right: restrict and object\n  text: restrict how we use your data, and object to uses based on legitimate interests, including marketing, which\n    we will always stop\n- right: portability\n  text: receive the data you gave us in a machine-readable format\n- right: withdraw consent\n  text: withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data or share it for other companies' advertising.\n"
source_yaml_url: https://artifacts.apis.io/kreatorflow-ai/privacy/kreatorflow-ai-privacy-policy.yml
stated_fields:
- role
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
summary_line: 32 quoted statements, read from kreatorflow-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Image
- Voice
- Platform
---
