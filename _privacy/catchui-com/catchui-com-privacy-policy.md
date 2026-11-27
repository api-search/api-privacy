---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: 'we store: your email address and a user ID'
  - category: behavioral
    text: your cards (including image crops), correction feedback, and review history
  - category: device
    text: error text, page path, browser version
  - category: financial
    text: We store only your Stripe customer ID and subscription status (plan, period end)
  - category: location
    text: hashed IP addresses
  deletion:
    route: In-app Delete account button or email to support@catchui.com
    text: deletion is immediate and also cancels any active subscription
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Screenshot recognition
    text: the image is compressed in your browser and sent to our API, which forwards it to our AI vision provider
  - purpose: Free-tier quota enforcement
    text: To enforce free-tier limits, anonymous scans are counted against a key derived from your IP address
  - purpose: Abuse prevention and debugging
    text: for abuse prevention and debugging
  - purpose: Payments
    text: Subscriptions are processed by Stripe
  - purpose: Advertising
    text: Some pages may display ads served by Google AdSense
  residency:
  - region: Hong Kong
    text: We are based in Hong Kong
  - region: United States
    text: use processors in the United States
  - region: China
    text: The AI provider may process the image on servers located in China
  retention:
  - period: null
    scope: Screenshots and recognition output
    text: the image is processed in memory and discarded when the response is returned
  - period: ~26 hours
    scope: Anonymous quota keys
    text: expiring within ~26 hours
  - period: about a week
    scope: Anonymous error reports
    text: kept for about a week
  - period: while your account exists
    scope: Synced account data
    text: Synced data is kept while your account exists
  rights:
  - right: Delete local data
    text: Local data is yours to delete at any time
  - right: Export library
    text: The app's account menu also offers a JSON export of your library
  - right: Opt out of personalized ads
    text: You can opt out of personalized advertising at Google Ads Settings
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or profile you ourselves
  subprocessors:
    text: 8. Processors
    url: null
  transfers:
  - mechanism: other
    text: By using the Service you acknowledge these transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CatchUI
provenance_date: '2026-11-09'
provider_name: CatchUI
provider_slug: catchui-com
slug: catchui-com-privacy-policy
source_date: '2026-11-09'
source_filename: catchui-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://catchui.com/legal/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CatchUI\naid: catchui-com\nurl: https://catchui.com/legal/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'we store: your email address and a user ID'\n- category: behavioral\n  text: your cards (including image crops), correction feedback, and review history\n- category: device\n  text: error text, page path, browser version\n- category: financial\n  text: We store only your Stripe customer ID and subscription status (plan, period end)\n- category: location\n  text: hashed IP addresses\npurposes:\n- purpose: Screenshot recognition\n\
  \  text: the image is compressed in your browser and sent to our API, which forwards it to our AI vision provider\n- purpose: Free-tier quota enforcement\n  text: To enforce free-tier limits, anonymous scans are counted against a key derived from your IP address\n- purpose: Abuse prevention and debugging\n  text: for abuse prevention and debugging\n- purpose: Payments\n  text: Subscriptions are processed by Stripe\n- purpose: Advertising\n  text: Some pages may display ads served by Google AdSense\nretention:\n- scope: Screenshots and recognition output\n  period: null\n  text: the image is processed in memory and discarded when the response is returned\n- scope: Anonymous quota keys\n  period: ~26 hours\n  text: expiring within ~26 hours\n- scope: Anonymous error reports\n  period: about a week\n  text: kept for about a week\n- scope: Synced account data\n  period: while your account exists\n  text: Synced data is kept while your account exists\nresidency:\n- region: Hong Kong\n  text:\
  \ We are based in Hong Kong\n- region: United States\n  text: use processors in the United States\n- region: China\n  text: The AI provider may process the image on servers located in China\ntransfers:\n- mechanism: other\n  text: By using the Service you acknowledge these transfers.\nsubprocessors:\n  url: null\n  text: 8. Processors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app Delete account button or email to support@catchui.com\n  text: deletion is immediate and also cancels any active subscription\nrights:\n- right: Delete local data\n  text: Local data is yours to delete at any time\n- right: Export library\n  text: The app's account menu also offers a JSON export of your library\n- right: Opt out of personalized ads\n  text: You can opt out of personalized advertising at Google Ads Settings\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or profile you ourselves\n"
source_yaml_url: https://artifacts.apis.io/catchui-com/privacy/catchui-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from CatchUI's own page on 2026-11-09.
synthetic: false
tags:
- UI
- Design
- Education
- Artificial Intelligence
- Tool
---
