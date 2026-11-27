---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address when you register an account or contact us
  - category: other
    text: URLs, titles, descriptions, folders and tags that you save in Shiori
  - category: device
    text: IP address, browser type, device information, and operating system version
  - category: behavioral
    text: Bookmark counts, feature usage patterns, and service interactions
  - category: financial
    text: Subscription history and payment information (processed securely by Stripe)
  - category: communication
    text: Messages you send us through support channels
  deletion:
    route: Account panel in the extension or on the Shiori website
    text: You can start account deletion from the Account panel in the extension or on the Shiori website.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the service
    text: Provide and maintain the Shiori service
  - purpose: Synchronize bookmarks
    text: Synchronize your bookmarks across devices
  - purpose: Process payments
    text: Process subscription payments and manage billing
  - purpose: Marketing with consent
    text: Send marketing communications (with your consent)
  retention:
  - period: null
    scope: account deletion
    text: When account deletion completes, we remove your bookmarks, folders, tags, account, sessions and access tokens from the active service and delete the linked WorkOS identity.
  - period: null
    scope: backups and security logs
    text: Copies in rotating backups and security logs expire according to their retention cycles.
  rights:
  - right: Access
    text: Request a copy of your personal data
  - right: Deletion
    text: Request deletion of your personal data
  - right: Portability
    text: Request your data in a portable format (we support JSON, CSV, and HTML export)
  - right: Withdraw consent
    text: Withdraw consent for marketing or cookies at any time
  role:
    text: We act as the data controller for all personal information collected through our services.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Shiori
provenance_date: '2026-11-10'
provider_name: Shiori
provider_slug: shiori
slug: shiori-privacy-policy
source_date: '2026-11-10'
source_filename: shiori-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shioriapp.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Shiori\naid: shiori\nurl: https://shioriapp.io/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We act as the data controller for all personal information collected through our services.\ndata_categories:\n- category: identifying\n  text: Name and email address when you register an account or contact us\n- category: other\n  text: URLs, titles, descriptions, folders and tags that you save in Shiori\n- category: device\n  text: IP address, browser type, device information, and operating system version\n- category: behavioral\n  text: Bookmark counts, feature usage patterns, and\
  \ service interactions\n- category: financial\n  text: Subscription history and payment information (processed securely by Stripe)\n- category: communication\n  text: Messages you send us through support channels\npurposes:\n- purpose: Provide and maintain the service\n  text: Provide and maintain the Shiori service\n- purpose: Synchronize bookmarks\n  text: Synchronize your bookmarks across devices\n- purpose: Process payments\n  text: Process subscription payments and manage billing\n- purpose: Marketing with consent\n  text: Send marketing communications (with your consent)\nretention:\n- scope: account deletion\n  period: null\n  text: When account deletion completes, we remove your bookmarks, folders, tags, account, sessions and access tokens\n    from the active service and delete the linked WorkOS identity.\n- scope: backups and security logs\n  period: null\n  text: Copies in rotating backups and security logs expire according to their retention cycles.\nresidency: []\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account panel in the extension or on the Shiori website\n  text: You can start account deletion from the Account panel in the extension or on the Shiori website.\nrights:\n- right: Access\n  text: Request a copy of your personal data\n- right: Deletion\n  text: Request deletion of your personal data\n- right: Portability\n  text: Request your data in a portable format (we support JSON, CSV, and HTML export)\n- right: Withdraw consent\n  text: Withdraw consent for marketing or cookies at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/shiori/privacy/shiori-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Shiori's own page on 2026-11-10.
synthetic: false
tags:
- Bookmarks
- Self-Hosted
- Open Source
- Go
- CLI
---
