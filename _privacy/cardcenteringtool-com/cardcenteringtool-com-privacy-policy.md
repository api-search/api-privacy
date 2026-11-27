---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email and OAuth profile. When you sign in with Google or Apple, your provider gives us your email address, a unique user ID, and (optionally) your display name.
  - category: contact
    text: Support messages. If you contact support from the App or by email, we receive the message and the reply-to email you provide so we can respond.
  - category: location
    text: Location (Card shops). When you open Card shops and allow location access, the App reads your device's position once (while the App is in use) and sends it to our server with that one request to find shops within the radius you pick.
  - category: behavioral
    text: PostHog records the pages and screens you open, the buttons, links and controls you tap or click, the order you move through a feature in, how long each step takes, and the errors you run into.
  - category: device
    text: Device model, operating-system version, app version, language, and unique device identifiers, plus in-app events (screens viewed, actions taken) used to operate and improve the App.
  - category: device
    text: Server logs. Standard request logs (IP address, user agent, path, status, timestamp) are retained for ~30 days for debugging and abuse prevention.
  deletion:
    route: Delete my account control in Settings, or email
    text: The fastest way to delete everything is the "Delete my account" control in Settings — it removes your profile, saved cards, uploaded images, and credit history in one shot.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate users and keep saved cards available
    text: To authenticate you and keep your saved cards available.
  - purpose: Run centering analysis and AI cleanup
    text: To run the centering analysis, the surface inspection, and the AI-cleanup pass that removes the background and straightens the card.
  - purpose: Process subscription purchases
    text: To process subscription purchases — through the Apple App Store on iPhone, or Stripe on the website, both routed via RevenueCat.
  - purpose: Transactional messages and support
    text: To send transactional messages (receipts, security alerts) and to respond to support requests.
  - purpose: Marketing measurement and product improvement
    text: To measure marketing performance and improve the product based on aggregated usage signals.
  residency:
  - region: United States
    text: PostHog processes this data on servers in the United States
  - region: European Union
    text: Plausible — cookie-less page-view counting on the Site, hosted in the EU.
  retention:
  - period: null
    scope: Saved cards and uploaded images
    text: Saved cards and uploaded images are kept until you delete them in the App or website, or until you delete your account.
  - period: null
    scope: Unsaved uploads
    text: Unsaved uploads are discarded immediately after analysis completes.
  - period: within 7 days
    scope: Account data
    text: Account data is removed within 7 days of you requesting account deletion from Settings.
  - period: ~30 days
    scope: Server logs
    text: Standard request logs (IP address, user agent, path, status, timestamp) are retained for ~30 days for debugging and abuse prevention.
  rights:
  - right: Access, correction, deletion
    text: You can request access to, correction of, or deletion of your personal information at any time.
  - right: GDPR rights
    text: If you live in the EU/UK, you also have rights under GDPR.
  - right: CCPA rights
    text: If you live in California, you have rights under CCPA.
  role:
    text: Midpoint - Card Centering Tool ("we", "us", or "our") is operated by I Lov Guitars Inc.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Card Centering Tool
provenance_date: '2026-11-09'
provider_name: Card Centering Tool
provider_slug: cardcenteringtool-com
slug: cardcenteringtool-com-privacy-policy
source_date: '2026-11-09'
source_filename: cardcenteringtool-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cardcenteringtool.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Card Centering Tool\naid: cardcenteringtool-com\nurl: https://www.cardcenteringtool.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Midpoint - Card Centering Tool (\"we\", \"us\", or \"our\") is operated by I Lov Guitars Inc.\ndata_categories:\n- category: identifying\n  text: Email and OAuth profile. When you sign in with Google or Apple, your provider gives us your email address,\n    a unique user ID, and (optionally) your display name.\n- category: contact\n  text: Support messages. If you contact support from the App or by email, we receive the message and the reply-to\n  \
  \  email you provide so we can respond.\n- category: location\n  text: Location (Card shops). When you open Card shops and allow location access, the App reads your device's position\n    once (while the App is in use) and sends it to our server with that one request to find shops within the radius\n    you pick.\n- category: behavioral\n  text: PostHog records the pages and screens you open, the buttons, links and controls you tap or click, the order\n    you move through a feature in, how long each step takes, and the errors you run into.\n- category: device\n  text: Device model, operating-system version, app version, language, and unique device identifiers, plus in-app\n    events (screens viewed, actions taken) used to operate and improve the App.\n- category: device\n  text: Server logs. Standard request logs (IP address, user agent, path, status, timestamp) are retained for ~30\n    days for debugging and abuse prevention.\npurposes:\n- purpose: Authenticate users and keep saved\
  \ cards available\n  text: To authenticate you and keep your saved cards available.\n- purpose: Run centering analysis and AI cleanup\n  text: To run the centering analysis, the surface inspection, and the AI-cleanup pass that removes the background\n    and straightens the card.\n- purpose: Process subscription purchases\n  text: To process subscription purchases — through the Apple App Store on iPhone, or Stripe on the website, both\n    routed via RevenueCat.\n- purpose: Transactional messages and support\n  text: To send transactional messages (receipts, security alerts) and to respond to support requests.\n- purpose: Marketing measurement and product improvement\n  text: To measure marketing performance and improve the product based on aggregated usage signals.\nretention:\n- scope: Saved cards and uploaded images\n  period: null\n  text: Saved cards and uploaded images are kept until you delete them in the App or website, or until you delete\n    your account.\n- scope: Unsaved uploads\n\
  \  period: null\n  text: Unsaved uploads are discarded immediately after analysis completes.\n- scope: Account data\n  period: within 7 days\n  text: Account data is removed within 7 days of you requesting account deletion from Settings.\n- scope: Server logs\n  period: ~30 days\n  text: Standard request logs (IP address, user agent, path, status, timestamp) are retained for ~30 days for debugging\n    and abuse prevention.\nresidency:\n- region: United States\n  text: PostHog processes this data on servers in the United States\n- region: European Union\n  text: Plausible — cookie-less page-view counting on the Site, hosted in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete my account control in Settings, or email\n  text: The fastest way to delete everything is the \"Delete my account\" control in Settings — it removes your profile,\n    saved cards, uploaded images, and credit history in\
  \ one shot.\nrights:\n- right: Access, correction, deletion\n  text: You can request access to, correction of, or deletion of your personal information at any time.\n- right: GDPR rights\n  text: If you live in the EU/UK, you also have rights under GDPR.\n- right: CCPA rights\n  text: If you live in California, you have rights under CCPA.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information\n"
source_yaml_url: https://artifacts.apis.io/cardcenteringtool-com/privacy/cardcenteringtool-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Card Centering Tool's own page on 2026-11-09.
synthetic: false
tags:
- Cards
- Grading
- Trading Cards
- Marketplace
---
