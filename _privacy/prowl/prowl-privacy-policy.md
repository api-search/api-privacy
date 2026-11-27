---
claim_count: 12
description: ''
doc:
  data_categories:
  - category: device
    text: your browser details, date and time of visit, etc., are stored through the Google Analytics application
  - category: communication
    text: Your notifications are stored in plain text on the Prowl server until such a time as you delete your account
  - category: device
    text: Your IP address is stored on the Prowl servers, but only for applying a rate limit.
  deletion:
    route: account removal and notification deletion in the Prowl application
    text: You can at any time remove your account, which also permanently and irretrievably removes the notifications, settings, and other information about your user account from the Prowl servers.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: statistics
    text: which stores a cookie to uniquely identify you for the use of statistics
  - purpose: notification delivery
    text: Notifications (messages sent from the Growl plugin, or over the API) are delivered to the Prowl server over SSL/TLS
  - purpose: account access
    text: This session cookie allows the Prowl server to identify you and allow you to modify your account and its information on the webpage.
  - purpose: rate limiting
    text: Your IP address is stored on the Prowl servers, but only for applying a rate limit.
  retention:
  - period: null
    scope: notifications
    text: Your notifications are stored in plain text on the Prowl server until such a time as you delete your account, delete the notification inside the Prowl application, or the notifications expire and are automatically removed.
  - period: within a week
    scope: backups
    text: your data is still preserved in the backups until they are replaced by more recent backups within a week.
  rights:
  - right: account removal
    text: You can at any time remove your account
  - right: email removal
    text: From the settings page (when logged in) you can remove the email address tied to your account.
  role:
    text: null
    value: unstated
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
name: Prowl
provenance_date: '2026-11-10'
provider_name: Prowl
provider_slug: prowl
slug: prowl-privacy-policy
source_date: '2026-11-10'
source_filename: prowl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.prowlapp.com/privacy.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Prowl\naid: prowl\nurl: https://www.prowlapp.com/privacy.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: your browser details, date and time of visit, etc., are stored through the Google Analytics application\n- category: communication\n  text: Your notifications are stored in plain text on the Prowl server until such a time as you delete your account\n- category: device\n  text: Your IP address is stored on the Prowl servers, but only for applying a rate limit.\npurposes:\n- purpose: statistics\n  text: which stores a cookie to uniquely\
  \ identify you for the use of statistics\n- purpose: notification delivery\n  text: Notifications (messages sent from the Growl plugin, or over the API) are delivered to the Prowl server over\n    SSL/TLS\n- purpose: account access\n  text: This session cookie allows the Prowl server to identify you and allow you to modify your account and its\n    information on the webpage.\n- purpose: rate limiting\n  text: Your IP address is stored on the Prowl servers, but only for applying a rate limit.\nretention:\n- scope: notifications\n  period: null\n  text: Your notifications are stored in plain text on the Prowl server until such a time as you delete your account,\n    delete the notification inside the Prowl application, or the notifications expire and are automatically removed.\n- scope: backups\n  period: within a week\n  text: your data is still preserved in the backups until they are replaced by more recent backups within a week.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n\
  \  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account removal and notification deletion in the Prowl application\n  text: You can at any time remove your account, which also permanently and irretrievably removes the notifications,\n    settings, and other information about your user account from the Prowl servers.\nrights:\n- right: account removal\n  text: You can at any time remove your account\n- right: email removal\n  text: From the settings page (when logged in) you can remove the email address tied to your account.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prowl/privacy/prowl-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 12 quoted statements, read from Prowl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Push Notifications
- iOS
- Mobile
---
