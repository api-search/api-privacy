---
claim_count: 34
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your email address and name from Sign in with Apple.'
  - category: health
    text: Allergy information can be health data; you choose whether to give it.
  - category: communication
    text: 'AI chat: your messages, and short notes the assistant saves about your tastes ("memories")'
  - category: location
    text: 'Voice: when you use the mic or voice cooking, your audio is sent for processing.'
  - category: financial
    text: 'Subscription: your subscription status and purchase history, from Apple through RevenueCat.'
  - category: device
    text: 'Device: a push notification token, if you allow notifications.'
  - category: other
    text: 'Photos: photos you import to turn into a recipe.'
  - category: contact
    source: https://chewable.fit/privacy-policy
    text: Email address
  - category: demographic
    source: https://chewable.fit/privacy-policy
    text: Age
  - category: other
    source: https://chewable.fit/privacy-policy
    text: Weight
  - category: other
    source: https://chewable.fit/privacy-policy
    text: Height
  - category: identifying
    source: https://chewable.fit/privacy-policy
    text: Optional profile data such as name or profile picture
  - category: device
    source: https://chewable.fit/privacy-policy
    text: technical log data such as your device’s IP address, OS version, crash report, and timestamp
  deletion:
    route: In-app account deletion under Settings
    text: You can delete your account in the app under Settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: We process your account, recipe, list and subscription data to provide the service you signed up for.
  - purpose: AI features
    text: To answer you, Foodie sends what you type or say, the photos you import, and your food preferences and allergies to OpenAI or Google.
  - purpose: Security and diagnostics
    text: We keep diagnostic logs based on our legitimate interest in keeping Foodie secure and working.
  - purpose: account access, personalization, and training insights
    source: https://chewable.fit/privacy-policy
    text: This data is stored securely in our database to support core features such as account access, personalization, and training insights.
  - purpose: debug and improve the app
    source: https://chewable.fit/privacy-policy
    text: This is only used to debug and improve the app.
  residency:
  - region: Own servers
    text: Our API, database and images run on servers we operate.
  retention:
  - period: until you delete your account
    scope: Account data
    text: We keep your data until you delete your account.
  - period: null
    scope: Voice recordings
    text: We do not keep voice recordings.
  - period: up to 30 days
    scope: AI providers
    text: AI providers keep what we send them only as their API terms allow, for example up to 30 days for abuse monitoring at OpenAI.
  - period: null
    scope: Server logs
    text: Server logs are kept for a limited time and then deleted.
  - period: null
    scope: account personal data
    source: https://chewable.fit/privacy-policy
    text: When you do, all personal data associated with your account is permanently deleted from our system.
  rights:
  - right: access, correct, export and delete
    text: You have the right to access, correct, export and delete your personal data
  - right: object or restrict processing
    text: to object to or restrict its processing
  - right: withdraw permission
    text: to withdraw your permission at any time
  - right: complain to authority
    text: You can also complain to the Norwegian Data Protection Authority (Datatilsynet) or to the data protection authority where you live.
  role:
    text: Chewable AS is the data controller for the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'These services process it for us: OpenAI (USA): chat, recipe import from text and photos, voice transcription, step explanations, substitutes and the embeddings behind chat memories.'
    url: null
  transfers:
  - mechanism: SCC
    text: When data goes to a provider outside the EEA, we rely on the EU standard contractual clauses or the EU-US Data Privacy Framework.
  - mechanism: DPF
    text: When data goes to a provider outside the EEA, we rely on the EU standard contractual clauses or the EU-US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chewable
provenance_date: '2026-11-09'
provider_name: Chewable
provider_slug: chewable-fit
slug: chewable-fit-privacy-policy
source_date: '2026-11-09'
source_filename: chewable-fit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://foodie.chewable.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chewable\naid: chewable-fit\nurl: https://foodie.chewable.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://chewable.fit/privacy-policy\n  - https://foodie.chewable.app/privacy\nrole:\n  value: controller\n  text: Chewable AS is the data controller for the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: 'Account: your email address and name from Sign in with Apple.'\n- category: health\n  text: Allergy information can be health data; you choose whether to give it.\n- category: communication\n  text: 'AI chat: your messages, and short notes the assistant\
  \ saves about your tastes (\"memories\")'\n- category: location\n  text: 'Voice: when you use the mic or voice cooking, your audio is sent for processing.'\n- category: financial\n  text: 'Subscription: your subscription status and purchase history, from Apple through RevenueCat.'\n- category: device\n  text: 'Device: a push notification token, if you allow notifications.'\n- category: other\n  text: 'Photos: photos you import to turn into a recipe.'\n- category: contact\n  text: Email address\n  source: https://chewable.fit/privacy-policy\n- category: demographic\n  text: Age\n  source: https://chewable.fit/privacy-policy\n- category: other\n  text: Weight\n  source: https://chewable.fit/privacy-policy\n- category: other\n  text: Height\n  source: https://chewable.fit/privacy-policy\n- category: identifying\n  text: Optional profile data such as name or profile picture\n  source: https://chewable.fit/privacy-policy\n- category: device\n  text: technical log data such as your device’s\
  \ IP address, OS version, crash report, and timestamp\n  source: https://chewable.fit/privacy-policy\npurposes:\n- purpose: Provide the service\n  text: We process your account, recipe, list and subscription data to provide the service you signed up for.\n- purpose: AI features\n  text: To answer you, Foodie sends what you type or say, the photos you import, and your food preferences and allergies\n    to OpenAI or Google.\n- purpose: Security and diagnostics\n  text: We keep diagnostic logs based on our legitimate interest in keeping Foodie secure and working.\n- purpose: account access, personalization, and training insights\n  text: This data is stored securely in our database to support core features such as account access, personalization,\n    and training insights.\n  source: https://chewable.fit/privacy-policy\n- purpose: debug and improve the app\n  text: This is only used to debug and improve the app.\n  source: https://chewable.fit/privacy-policy\nretention:\n- scope: Account\
  \ data\n  period: until you delete your account\n  text: We keep your data until you delete your account.\n- scope: Voice recordings\n  period: null\n  text: We do not keep voice recordings.\n- scope: AI providers\n  period: up to 30 days\n  text: AI providers keep what we send them only as their API terms allow, for example up to 30 days for abuse monitoring\n    at OpenAI.\n- scope: Server logs\n  period: null\n  text: Server logs are kept for a limited time and then deleted.\n- scope: account personal data\n  period: null\n  text: When you do, all personal data associated with your account is permanently deleted from our system.\n  source: https://chewable.fit/privacy-policy\nresidency:\n- region: Own servers\n  text: Our API, database and images run on servers we operate.\ntransfers:\n- mechanism: SCC\n  text: When data goes to a provider outside the EEA, we rely on the EU standard contractual clauses or the EU-US\n    Data Privacy Framework.\n- mechanism: DPF\n  text: When data goes\
  \ to a provider outside the EEA, we rely on the EU standard contractual clauses or the EU-US\n    Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: 'These services process it for us: OpenAI (USA): chat, recipe import from text and photos, voice transcription,\n    step explanations, substitutes and the embeddings behind chat memories.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app account deletion under Settings\n  text: You can delete your account in the app under Settings.\nrights:\n- right: access, correct, export and delete\n  text: You have the right to access, correct, export and delete your personal data\n- right: object or restrict processing\n  text: to object to or restrict its processing\n- right: withdraw permission\n  text: to withdraw your permission at any time\n- right: complain to authority\n  text: You can also complain to the Norwegian Data Protection Authority (Datatilsynet) or to the data protection\n    authority where\
  \ you live.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/chewable-fit/privacy/chewable-fit-privacy-policy.yml
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
summary_line: 34 quoted statements, read from Chewable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile App
- iOS
- Recipes
- Meal Planning
- Fitness
- Strength Training
- Fashion
- Virtual Try-On
- Artificial Intelligence
- MCP
---
