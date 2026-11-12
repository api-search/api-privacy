---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account info : email, display name, and either a hashed password or an OAuth identifier (Google / Facebook) if you sign in with one of those.'
  - category: other
    text: 'Photos you upload : source images you submit so we can generate new images for you.'
  - category: location
    text: optional location for mentor matching
  - category: biometric
    text: if you use selfie verification, the selfie you submit and a match score
  - category: financial
    text: our payment processor handles the card details directly
  - category: device
    text: 'Technical logs : user agent, request timestamps, and error stack traces.'
  - category: communication
    text: the messages in a conversation you bring to us, including what the other person wrote
  deletion:
    route: in-app self-service or by request
    text: 'Delete your account and data: instant via self-service, or by request.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation
    text: 'To run the service: authenticate you, generate the images you ask for, deliver messages and notifications.'
  - purpose: payments and credits
    text: To process payments and grant credits / unlocks.
  - purpose: fraud and abuse prevention
    text: To prevent fraud, abuse, and unauthorized access.
  - purpose: service improvement
    text: 'To improve the service: measure performance, fix bugs.'
  residency:
  - region: Israel and other regions
    text: CMeIn operates from Israel, and our hosting and AI providers may process data in the EU, the US, and other Microsoft Azure regions.
  retention:
  - period: until you delete the account
    scope: Active account
    text: 'Active account : all data is retained until you delete the account.'
  - period: up to 30 days
    scope: Encrypted backups
    text: encrypted backups containing your data are retained for up to 30 days, then permanently overwritten.
  - period: until you delete the conversation or your account
    scope: Wingman conversations
    text: 'Wingman conversations : kept until you delete the conversation or your account.'
  - period: up to 90 days
    scope: IP-level access logs
    text: IP-level access logs are kept for up to 90 days for security purposes.
  rights:
  - right: access
    text: Access the personal data we hold about you.
  - right: correction
    text: 'Correct inaccurate data: update your email or display name on the Account page anytime.'
  - right: export
    text: 'Export a copy of your data: email support@cmein.com and we''ll respond within 30 days.'
  - right: object or restrict
    text: Object to or restrict certain processing.
  - right: withdraw consent
    text: Withdraw consent at any time where processing is consent-based.
  - right: complaint
    text: Lodge a complaint with your local data protection authority.
  role:
    text: CMeIn is the data controller for the personal information collected through the service.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: CMeIn never sells your data.
  subprocessors:
    text: 'Microsoft Azure : hosting, database, blob storage, and Azure OpenAI for image generation.'
    url: null
  transfers:
  - mechanism: SCC
    text: Where data is transferred outside the EEA / UK, we rely on Standard Contractual Clauses or equivalent safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CMeIn
provenance_date: '2026-11-09'
provider_name: CMeIn
provider_slug: cmein-com
slug: cmein-com-privacy-policy
source_date: '2026-11-09'
source_filename: cmein-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cmein.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CMeIn\naid: cmein-com\nurl: https://cmein.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CMeIn is the data controller for the personal information collected through the service.\ndata_categories:\n- category: identifying\n  text: 'Account info : email, display name, and either a hashed password or an OAuth identifier (Google / Facebook)\n    if you sign in with one of those.'\n- category: other\n  text: 'Photos you upload : source images you submit so we can generate new images for you.'\n- category: location\n  text: optional location for mentor matching\n- category: biometric\n\
  \  text: if you use selfie verification, the selfie you submit and a match score\n- category: financial\n  text: our payment processor handles the card details directly\n- category: device\n  text: 'Technical logs : user agent, request timestamps, and error stack traces.'\n- category: communication\n  text: the messages in a conversation you bring to us, including what the other person wrote\npurposes:\n- purpose: service operation\n  text: 'To run the service: authenticate you, generate the images you ask for, deliver messages and notifications.'\n- purpose: payments and credits\n  text: To process payments and grant credits / unlocks.\n- purpose: fraud and abuse prevention\n  text: To prevent fraud, abuse, and unauthorized access.\n- purpose: service improvement\n  text: 'To improve the service: measure performance, fix bugs.'\nretention:\n- scope: Active account\n  period: until you delete the account\n  text: 'Active account : all data is retained until you delete the account.'\n-\
  \ scope: Encrypted backups\n  period: up to 30 days\n  text: encrypted backups containing your data are retained for up to 30 days, then permanently overwritten.\n- scope: Wingman conversations\n  period: until you delete the conversation or your account\n  text: 'Wingman conversations : kept until you delete the conversation or your account.'\n- scope: IP-level access logs\n  period: up to 90 days\n  text: IP-level access logs are kept for up to 90 days for security purposes.\nresidency:\n- region: Israel and other regions\n  text: CMeIn operates from Israel, and our hosting and AI providers may process data in the EU, the US, and other\n    Microsoft Azure regions.\ntransfers:\n- mechanism: SCC\n  text: Where data is transferred outside the EEA / UK, we rely on Standard Contractual Clauses or equivalent safeguards.\nsubprocessors:\n  url: null\n  text: 'Microsoft Azure : hosting, database, blob storage, and Azure OpenAI for image generation.'\ndpa:\n  available: null\n  url: null\n \
  \ text: null\ndeletion:\n  route: in-app self-service or by request\n  text: 'Delete your account and data: instant via self-service, or by request.'\nrights:\n- right: access\n  text: Access the personal data we hold about you.\n- right: correction\n  text: 'Correct inaccurate data: update your email or display name on the Account page anytime.'\n- right: export\n  text: 'Export a copy of your data: email support@cmein.com and we''ll respond within 30 days.'\n- right: object or restrict\n  text: Object to or restrict certain processing.\n- right: withdraw consent\n  text: Withdraw consent at any time where processing is consent-based.\n- right: complaint\n  text: Lodge a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: CMeIn never sells your data.\n"
source_yaml_url: https://artifacts.apis.io/cmein-com/privacy/cmein-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from CMeIn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Image Generation
- Photos
- Dating
- Headshots
- Consumer Apps
- MCP
---
