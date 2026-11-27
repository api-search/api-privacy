---
api_specs:
- filename: rtcstats-rtcstats-api-api-openapi.yml
  format: yaml
  label: rtcStats API
  slug: rtcstats-rtcstats-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rtcstats/openapi/rtcstats-rtcstats-api-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: we ask for identifying information such as your name, email address, and maybe a company name
  - category: financial
    text: we may store a record of the payment transaction, including the last 4 digits of the credit card number
  - category: location
    text: we log the full IP address used to sign up a product account
  - category: device
    text: your browser and operating system versions, your IP address, which web pages you visited and how long they took to load
  - category: behavioral
    text: We collect information about your browsing activity for analytics and statistical purposes
  - category: communication
    text: When you email rtcStats with a question or to ask for help, we keep that correspondence, including your email address
  - category: identifying
    source: https://rtcstats.com/compliance
    text: whatever identifiers you choose to attach to a session (user id, conference id, session id, title)
  - category: contact
    source: https://rtcstats.com/compliance
    text: Email address, name, chat transcript
  - category: device
    source: https://rtcstats.com/compliance
    text: device and browser information
  - category: behavioral
    source: https://rtcstats.com/compliance
    text: Pseudonymous usage and performance events
  deletion:
    route: cancel account or delete account
    text: If you choose to cancel your account, your content will become immediately inaccessible and should be purged from our systems in full within 60 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide requested products and services
    text: To provide products or services you've requested.
  - purpose: analytics and statistics
    text: We collect information about your browsing activity for analytics and statistical purposes such as conversion rate testing and experimenting with new product designs.
  - purpose: invoicing and billing
    text: send you invoices, and detect fraudulent credit card transactions
  - purpose: marketing with consent
    text: With your consent, we will send you our newsletter and other updates.
  - purpose: Run the hosted service
    source: https://rtcstats.com/compliance
    text: Third parties that process data on our behalf in order to run the hosted service.
  - purpose: Generate session summaries
    source: https://rtcstats.com/compliance
    text: Generating the plain-English summary of a session
  residency:
  - region: United States
    text: Our products and other web properties are operated in the United States.
  - region: United States
    text: All data infrastructure is located in the U.S.
  - region: United States
    source: https://rtcstats.com/compliance
    text: The hosted service runs in the United States.
  - region: European Union
    source: https://rtcstats.com/compliance
    text: Crisp In-app support chat Email address, name, chat transcript European Union
  retention:
  - period: 60 days
    scope: deleted account content
    text: If you delete your account, we'll delete the content within 60 days.
  - period: as long as your product account is active
    scope: login data
    text: we keep this login data for as long as your product account is active
  - period: Each plan carries a retention period
    scope: Session data
    source: https://rtcstats.com/compliance
    text: 'Each plan carries a retention period: the window in which we show you a session and guarantee it is stored.'
  rights:
  - right: access
    text: Right of Access This includes your right to access the personal information we gather about you.
  - right: correction
    text: Right to Correction You have the right to request correction of your personal information.
  - right: erasure
    text: Right to Erasure This is your right to request that your personal information be erased from our possession.
  - right: restrict processing
    text: Right to Restrict Processing This is your right to request restriction of how and why your personal information is used.
  - right: object
    text: Right to Object You have the right, in certain situations, to object to how your personal information is processed.
  - right: portability
    text: Right to Portability You have the right to receive the personal information we have about you and transmit it to another party.
  - right: complain
    text: Right to Complain You have the right to make a complaint regarding our handling of your personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 'We promise we never sell your data: never have, never will.'
  subprocessors:
    text: We use some third-party subprocessors to help run our applications and provide the Services to you.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: rtcStats
provenance_date: '2026-11-10'
provider_name: rtcStats
provider_slug: rtcstats
slug: rtcstats-privacy-policy
source_date: '2026-11-10'
source_filename: rtcstats-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rtcstats.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: rtcStats\naid: rtcstats\nurl: https://rtcstats.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://rtcstats.com/compliance\n  - https://rtcstats.com/privacy\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we ask for identifying information such as your name, email address, and maybe a company name\n- category: financial\n  text: we may store a record of the payment transaction, including the last 4 digits of the credit card number\n- category: location\n  text: we log the full IP address used to sign up a product account\n- category: device\n  text: your\
  \ browser and operating system versions, your IP address, which web pages you visited and how long they\n    took to load\n- category: behavioral\n  text: We collect information about your browsing activity for analytics and statistical purposes\n- category: communication\n  text: When you email rtcStats with a question or to ask for help, we keep that correspondence, including your\n    email address\n- category: identifying\n  text: whatever identifiers you choose to attach to a session (user id, conference id, session id, title)\n  source: https://rtcstats.com/compliance\n- category: contact\n  text: Email address, name, chat transcript\n  source: https://rtcstats.com/compliance\n- category: device\n  text: device and browser information\n  source: https://rtcstats.com/compliance\n- category: behavioral\n  text: Pseudonymous usage and performance events\n  source: https://rtcstats.com/compliance\npurposes:\n- purpose: provide requested products and services\n  text: To provide products\
  \ or services you've requested.\n- purpose: analytics and statistics\n  text: We collect information about your browsing activity for analytics and statistical purposes such as conversion\n    rate testing and experimenting with new product designs.\n- purpose: invoicing and billing\n  text: send you invoices, and detect fraudulent credit card transactions\n- purpose: marketing with consent\n  text: With your consent, we will send you our newsletter and other updates.\n- purpose: Run the hosted service\n  text: Third parties that process data on our behalf in order to run the hosted service.\n  source: https://rtcstats.com/compliance\n- purpose: Generate session summaries\n  text: Generating the plain-English summary of a session\n  source: https://rtcstats.com/compliance\nretention:\n- scope: deleted account content\n  period: 60 days\n  text: If you delete your account, we'll delete the content within 60 days.\n- scope: login data\n  period: as long as your product account is active\n\
  \  text: we keep this login data for as long as your product account is active\n- scope: Session data\n  period: Each plan carries a retention period\n  text: 'Each plan carries a retention period: the window in which we show you a session and guarantee it is stored.'\n  source: https://rtcstats.com/compliance\nresidency:\n- region: United States\n  text: Our products and other web properties are operated in the United States.\n- region: United States\n  text: All data infrastructure is located in the U.S.\n- region: United States\n  text: The hosted service runs in the United States.\n  source: https://rtcstats.com/compliance\n- region: European Union\n  text: Crisp In-app support chat Email address, name, chat transcript European Union\n  source: https://rtcstats.com/compliance\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use some third-party subprocessors to help run our applications and provide the Services to you.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: cancel account or delete account\n  text: If you choose to cancel your account, your content will become immediately inaccessible and should be purged\n    from our systems in full within 60 days.\nrights:\n- right: access\n  text: Right of Access This includes your right to access the personal information we gather about you.\n- right: correction\n  text: Right to Correction You have the right to request correction of your personal information.\n- right: erasure\n  text: Right to Erasure This is your right to request that your personal information be erased from our possession.\n- right: restrict processing\n  text: Right to Restrict Processing This is your right to request restriction of how and why your personal information\n    is used.\n- right: object\n  text: Right to Object You have the right, in certain situations, to object to how your personal information is\n    processed.\n- right: portability\n  text: Right to Portability You have the right to receive the personal\
  \ information we have about you and transmit\n    it to another party.\n- right: complain\n  text: Right to Complain You have the right to make a complaint regarding our handling of your personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: 'We promise we never sell your data: never have, never will.'\n"
source_yaml_url: https://artifacts.apis.io/rtcstats/privacy/rtcstats-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 33 quoted statements, read from rtcStats's own page on 2026-11-10.
synthetic: false
tags:
- WebRTC
- Observability
- Monitoring
- Debugging
- Real-Time Communication
- Video
- Voice
- Artificial Intelligence
- MCP
- Developer Tools
---
