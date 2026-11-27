---
api_specs:
- filename: remem-me-access-api-openapi.yml
  format: yaml
  label: remem-me Access API
  slug: remem-me-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/remem-me/openapi/remem-me-access-api-openapi.yml
- filename: remem-me-collections-api-openapi.yml
  format: yaml
  label: remem-me Collections API
  slug: remem-me-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/remem-me/openapi/remem-me-collections-api-openapi.yml
- filename: remem-me-replication-api-openapi.yml
  format: yaml
  label: remem-me Replication API
  slug: remem-me-replication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/remem-me/openapi/remem-me-replication-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: email addresses passwords if you use a Remember Me account
  - category: contact
    text: email addresses
  - category: behavioral
    text: the verses you keep in them (reference, passage, source, topic, note and image URL), your labels and collections, and your review progress
  - category: device
    text: the platform (Android, iOS, macOS or web) and the app version
  - category: communication
    text: Notes are free text that you write and control; we store them only to show and sync them.
  deletion:
    route: Email support@remem.me or delete account via account settings
    text: To request to review, update, or delete your personal information, please email us at support@remem.me.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and authentication
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: service delivery
    text: To deliver and facilitate delivery of services to the user.
  - purpose: service reliability monitoring
    text: We use them only to detect when a Bible source stops working (our legitimate interest, see section 3)
  - purpose: improve AI assistant connection
    text: We use them to see how the connection is used and to improve it (our legitimate interest, see section 3)
  residency:
  - region: France
    text: Our servers and database are hosted by alwaysdata in France.
  retention:
  - period: 360 days
    scope: unused accounts
    text: If you do not use your Remember Me account for 360 days, we may delete it together with your verses and other data.
  - period: null
    scope: diagnostic reports
    text: retain them only for as long as necessary for this purpose
  rights:
  - right: access
    text: the right (i) to request access and obtain a copy of your personal information
  - right: rectification or erasure
    text: (ii) to request rectification or erasure
  - right: restriction
    text: (iii) to restrict the processing of your personal information
  - right: portability
    text: (iv) if applicable, to data portability
  - right: objection
    text: You may object to the processing of your personal information.
  - right: withdraw consent
    text: You have the right to withdraw your consent at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Poimena will not sell or share personal information in the future belonging to website visitors, users, and other consumers.
  subprocessors:
    text: The diagnostic reports and the usage counts described in section 1 are processed on our behalf by our monitoring provider, New Relic.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: remem-me
provenance_date: '2026-11-10'
provider_name: remem-me
provider_slug: remem-me
slug: remem-me-privacy-policy
source_date: '2026-11-10'
source_filename: remem-me-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.remem.me/docs/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: remem-me\naid: remem-me\nurl: https://www.remem.me/docs/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: email addresses passwords if you use a Remember Me account\n- category: contact\n  text: email addresses\n- category: behavioral\n  text: the verses you keep in them (reference, passage, source, topic, note and image URL), your labels and collections,\n    and your review progress\n- category: device\n  text: the platform (Android, iOS, macOS or web) and the app version\n- category: communication\n  text: Notes are free text\
  \ that you write and control; we store them only to show and sync them.\npurposes:\n- purpose: account creation and authentication\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: service delivery\n  text: To deliver and facilitate delivery of services to the user.\n- purpose: service reliability monitoring\n  text: We use them only to detect when a Bible source stops working (our legitimate interest, see section 3)\n- purpose: improve AI assistant connection\n  text: We use them to see how the connection is used and to improve it (our legitimate interest, see section 3)\nretention:\n- scope: unused accounts\n  period: 360 days\n  text: If you do not use your Remember Me account for 360 days, we may delete it together with your verses and\n    other data.\n- scope: diagnostic reports\n  period: null\n  text: retain them only for as long as necessary for this purpose\nresidency:\n- region: France\n  text: Our servers and database\
  \ are hosted by alwaysdata in France.\ntransfers: []\nsubprocessors:\n  url: null\n  text: The diagnostic reports and the usage counts described in section 1 are processed on our behalf by our monitoring\n    provider, New Relic.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@remem.me or delete account via account settings\n  text: To request to review, update, or delete your personal information, please email us at support@remem.me.\nrights:\n- right: access\n  text: the right (i) to request access and obtain a copy of your personal information\n- right: rectification or erasure\n  text: (ii) to request rectification or erasure\n- right: restriction\n  text: (iii) to restrict the processing of your personal information\n- right: portability\n  text: (iv) if applicable, to data portability\n- right: objection\n  text: You may object to the processing of your personal information.\n- right: withdraw consent\n  text: You have the right to withdraw\
  \ your consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: Poimena will not sell or share personal information in the future belonging to website visitors, users,\n    and other consumers.\n"
source_yaml_url: https://artifacts.apis.io/remem-me/privacy/remem-me-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from remem-me's own page on 2026-11-10.
synthetic: false
tags:
- Bible
- Memory
- Non-Profit
- Education
- Mobile App
- Open Source
---
