---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address if you create an account for cloud sync (Premium only)
  - category: identifying
    text: 'Anonymous Identifier: When you use the app, a random anonymous identifier is created via Firebase Authentication.'
  - category: behavioral
    text: 'Analytics: Anonymous usage data via Google Analytics (can be disabled)'
  - category: device
    text: 'Crash Reports: Technical error reports via Firebase Crashlytics'
  - category: device
    text: 'Device Information: Device type, OS version, app version'
  - category: behavioral
    text: 'Daily Marks: Your daily check-ins (good/bad/nothing) and optional notes'
  - category: identifying
    text: We receive your account ID and your email address.
  - category: device
    text: the device's push token, its platform and when it was last seen
  - category: financial
    text: 'If you connect WIP or Bluesky (Pro): for each network, its name, your public account name there (WIP username, Bluesky handle)'
  deletion:
    route: Email privacy@aimyear.com from the address you signed in with
    text: Email privacy@aimyear.com from the address you signed in with, and we will delete your account and all its server data within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain app
    text: To provide and maintain the app functionality
  - purpose: Sync across devices
    text: To sync your data across devices (Premium users)
  - purpose: AI goal-setting assistant
    text: To run the AI goal-setting assistant when you open it (all users, with daily limits on the free plan
  - purpose: Improve app and fix bugs
    text: To improve the app and fix bugs
  - purpose: Reminder notifications
    text: To send reminder notifications (if enabled)
  residency:
  - region: European Union
    text: This data is stored in Google Cloud Firestore in the European Union (multi-region eur3).
  - region: United States
    text: The server itself runs on Google Cloud Run in the United States.
  retention:
  - period: null
    scope: Free users data
    text: 'Free Users: All your data is stored locally on your device only. We do not have access to it.'
  - period: null
    scope: AI conversations
    text: Conversations are not stored on our servers. Each chat session is processed in real-time and discarded after the response is delivered.
  - period: 30 days
    scope: Server logs
    text: Logs are kept in Google Cloud Logging for 30 days
  rights:
  - right: Access
    text: Access your data
  - right: Export
    text: Export your data
  - right: Delete
    text: Delete your data
  - right: Opt out of analytics
    text: Opt out of analytics
  - right: Disable AI features
    text: Disable AI features
  role:
    text: AimYear ("we", "our", or "us") is committed to protecting your privacy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: 'We do not sell, trade, or share your personal data with third parties, except:'
  subprocessors:
    text: Service providers necessary for app functionality (Firebase, RevenueCat, AI providers such as OpenAI, Anthropic, or Google)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AimYear
provenance_date: '2026-11-09'
provider_name: AimYear
provider_slug: aimyear-com
slug: aimyear-com-privacy-policy
source_date: '2026-11-09'
source_filename: aimyear-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aimyear.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AimYear\naid: aimyear-com\nurl: https://aimyear.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AimYear (\"we\", \"our\", or \"us\") is committed to protecting your privacy.\ndata_categories:\n- category: identifying\n  text: Email address if you create an account for cloud sync (Premium only)\n- category: identifying\n  text: 'Anonymous Identifier: When you use the app, a random anonymous identifier is created via Firebase Authentication.'\n- category: behavioral\n  text: 'Analytics: Anonymous usage data via Google Analytics (can be disabled)'\n- category: device\n  text:\
  \ 'Crash Reports: Technical error reports via Firebase Crashlytics'\n- category: device\n  text: 'Device Information: Device type, OS version, app version'\n- category: behavioral\n  text: 'Daily Marks: Your daily check-ins (good/bad/nothing) and optional notes'\n- category: identifying\n  text: We receive your account ID and your email address.\n- category: device\n  text: the device's push token, its platform and when it was last seen\n- category: financial\n  text: 'If you connect WIP or Bluesky (Pro): for each network, its name, your public account name there (WIP username,\n    Bluesky handle)'\npurposes:\n- purpose: Provide and maintain app\n  text: To provide and maintain the app functionality\n- purpose: Sync across devices\n  text: To sync your data across devices (Premium users)\n- purpose: AI goal-setting assistant\n  text: To run the AI goal-setting assistant when you open it (all users, with daily limits on the free plan\n- purpose: Improve app and fix bugs\n  text: To improve\
  \ the app and fix bugs\n- purpose: Reminder notifications\n  text: To send reminder notifications (if enabled)\nretention:\n- scope: Free users data\n  period: null\n  text: 'Free Users: All your data is stored locally on your device only. We do not have access to it.'\n- scope: AI conversations\n  period: null\n  text: Conversations are not stored on our servers. Each chat session is processed in real-time and discarded after\n    the response is delivered.\n- scope: Server logs\n  period: 30 days\n  text: Logs are kept in Google Cloud Logging for 30 days\nresidency:\n- region: European Union\n  text: This data is stored in Google Cloud Firestore in the European Union (multi-region eur3).\n- region: United States\n  text: The server itself runs on Google Cloud Run in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service providers necessary for app functionality (Firebase, RevenueCat, AI providers such as OpenAI, Anthropic,\n    or Google)\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@aimyear.com from the address you signed in with\n  text: Email privacy@aimyear.com from the address you signed in with, and we will delete your account and all its\n    server data within 30 days.\nrights:\n- right: Access\n  text: Access your data\n- right: Export\n  text: Export your data\n- right: Delete\n  text: Delete your data\n- right: Opt out of analytics\n  text: Opt out of analytics\n- right: Disable AI features\n  text: Disable AI features\nsale_or_sharing:\n  stance: prohibited\n  text: 'We do not sell, trade, or share your personal data with third parties, except:'\n"
source_yaml_url: https://artifacts.apis.io/aimyear-com/privacy/aimyear-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from AimYear's own page on 2026-11-09.
synthetic: false
tags:
- Productivity
- Artificial Intelligence
- Goal Tracking
- Startups
- Free Tier
---
