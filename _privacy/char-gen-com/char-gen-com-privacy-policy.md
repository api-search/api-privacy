---
api_specs:
- filename: char-gen-com-account-catalog-api-openapi.yml
  format: yaml
  label: CharGen Account & catalog API
  slug: char-gen-com-account-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-account-catalog-api-openapi.yml
- filename: char-gen-com-billing-api-openapi.yml
  format: yaml
  label: CharGen Billing API
  slug: char-gen-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-billing-api-openapi.yml
- filename: char-gen-com-entities-api-openapi.yml
  format: yaml
  label: CharGen Entities API
  slug: char-gen-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-entities-api-openapi.yml
- filename: char-gen-com-generations-api-openapi.yml
  format: yaml
  label: CharGen Generations API
  slug: char-gen-com-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-generations-api-openapi.yml
- filename: char-gen-com-ping-api-openapi.yml
  format: yaml
  label: CharGen Ping API
  slug: char-gen-com-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-ping-api-openapi.yml
- filename: char-gen-com-public-pricing-api-openapi.yml
  format: yaml
  label: CharGen Public pricing API
  slug: char-gen-com-public-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/char-gen-com/openapi/char-gen-com-public-pricing-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data including first name and last name.
  - category: contact
    text: Contact Data including billing address, delivery address, email address, and telephone numbers.
  - category: financial
    text: Financial Data including bank account and payment card details (through third-party payment processors).
  - category: location
    text: Technical and Usage Data including internet protocol (IP) address, your login data, your browser session and geo-location data
  - category: device
    text: device and network information
  - category: behavioral
    text: statistics on page views and sessions, acquisition sources, search queries and/or browsing behaviour
  - category: biometric
    text: it describes a physical characteristic of a real person, so it is biometric information and we treat it as sensitive information.
  - category: communication
    text: Voice Data including audio recordings of game sessions that you upload, the transcripts we produce from them
  - category: professional
    text: Professional Data including where you are a worker of ours or applying for a role with us
  deletion:
    route: Account → Delete account in the app, or email contact@char-gen.com, or request at char-gen.com/contact#delete-account
    text: You can also request deletion without signing in at char-gen.com/contact#delete-account , or email contact@char-gen.com from your account email address.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Services and deliver products
    text: To provide our Services to you, including to dispatch and deliver our products to you.
  - purpose: Analytics and service improvement
    text: For analytics including profiling on our website, market research and business development
  - purpose: Advertising and marketing
    text: For advertising and marketing, including to send you promotional information about our products and experiences
  - purpose: Transcribe game sessions and Voice ID
    text: To transcribe game sessions you record and, where Voice ID is switched on and everyone recorded has agreed to it, to label who is speaking in the transcript.
  - purpose: Legal obligations
    text: To comply with our legal obligations or if otherwise required or authorised by law.
  residency:
  - region: United Kingdom
    text: While we store personal information in the United Kingdom
  - region: European Economic Area
    text: processes it on servers in the European Economic Area (EEA).
  - region: United States
    text: Soniox processes the audio on servers in the United States.
  retention:
  - period: until that agreement is withdrawn or the player is removed from the campaign roster
    scope: Voice profiles
    text: We keep the voice profiles for a player until that agreement is withdrawn or the player is removed from the campaign roster.
  - period: 7 days
    scope: Unconfirmed Table reminder email addresses
    text: we delete an address that is not confirmed after 7 days.
  - period: 180 days
    scope: Discord bot usage records
    text: We delete them after 180 days
  - period: one hour
    scope: Claude access tokens
    text: Access tokens expire after one hour and refresh tokens after 90 days.
  - period: null
    scope: MCP activity and connection records
    text: We do not automatically purge MCP activity or connection records. They remain until you request deletion by emailing contact@char-gen.com.
  rights:
  - right: Access
    text: You may request access to the personal information that we hold about you.
  - right: Correction
    text: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant or misleading, please contact us using the details below.
  - right: Restrict and unsubscribe
    text: To object to processing for direct marketing/unsubscribe from our email database or opt-out of communications
  - right: Complaints
    text: If you wish to make a complaint, please contact us using the details below
  - right: Erasure (EU/UK)
    text: to have your personal information rectified or deleted, to restrict our processing of that information
  role:
    text: CharGen is owned and operated by Vorontsov Consulting Services LTD (we, us, or our).
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: including standard contractual clauses in our agreements with third parties that are overseas.
  - mechanism: adequacy
    text: only transferring your personal information to countries that have been deemed by applicable data protection laws to provide an adequate level of protection for personal information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CharGen
provenance_date: '2026-11-09'
provider_name: CharGen
provider_slug: char-gen-com
slug: char-gen-com-privacy-policy
source_date: '2026-11-09'
source_filename: char-gen-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://char-gen.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CharGen\naid: char-gen-com\nurl: https://char-gen.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CharGen is owned and operated by Vorontsov Consulting Services LTD (we, us, or our).\ndata_categories:\n- category: identifying\n  text: Identity Data including first name and last name.\n- category: contact\n  text: Contact Data including billing address, delivery address, email address, and telephone numbers.\n- category: financial\n  text: Financial Data including bank account and payment card details (through third-party payment processors).\n- category: location\n  text: Technical\
  \ and Usage Data including internet protocol (IP) address, your login data, your browser session\n    and geo-location data\n- category: device\n  text: device and network information\n- category: behavioral\n  text: statistics on page views and sessions, acquisition sources, search queries and/or browsing behaviour\n- category: biometric\n  text: it describes a physical characteristic of a real person, so it is biometric information and we treat it\n    as sensitive information.\n- category: communication\n  text: Voice Data including audio recordings of game sessions that you upload, the transcripts we produce from\n    them\n- category: professional\n  text: Professional Data including where you are a worker of ours or applying for a role with us\npurposes:\n- purpose: Provide Services and deliver products\n  text: To provide our Services to you, including to dispatch and deliver our products to you.\n- purpose: Analytics and service improvement\n  text: For analytics including profiling\
  \ on our website, market research and business development\n- purpose: Advertising and marketing\n  text: For advertising and marketing, including to send you promotional information about our products and experiences\n- purpose: Transcribe game sessions and Voice ID\n  text: To transcribe game sessions you record and, where Voice ID is switched on and everyone recorded has agreed\n    to it, to label who is speaking in the transcript.\n- purpose: Legal obligations\n  text: To comply with our legal obligations or if otherwise required or authorised by law.\nretention:\n- scope: Voice profiles\n  period: until that agreement is withdrawn or the player is removed from the campaign roster\n  text: We keep the voice profiles for a player until that agreement is withdrawn or the player is removed from\n    the campaign roster.\n- scope: Unconfirmed Table reminder email addresses\n  period: 7 days\n  text: we delete an address that is not confirmed after 7 days.\n- scope: Discord bot usage records\n\
  \  period: 180 days\n  text: We delete them after 180 days\n- scope: Claude access tokens\n  period: one hour\n  text: Access tokens expire after one hour and refresh tokens after 90 days.\n- scope: MCP activity and connection records\n  period: null\n  text: We do not automatically purge MCP activity or connection records. They remain until you request deletion\n    by emailing contact@char-gen.com.\nresidency:\n- region: United Kingdom\n  text: While we store personal information in the United Kingdom\n- region: European Economic Area\n  text: processes it on servers in the European Economic Area (EEA).\n- region: United States\n  text: Soniox processes the audio on servers in the United States.\ntransfers:\n- mechanism: SCC\n  text: including standard contractual clauses in our agreements with third parties that are overseas.\n- mechanism: adequacy\n  text: only transferring your personal information to countries that have been deemed by applicable data protection\n    laws to provide\
  \ an adequate level of protection for personal information\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account → Delete account in the app, or email contact@char-gen.com, or request at char-gen.com/contact#delete-account\n  text: You can also request deletion without signing in at char-gen.com/contact#delete-account , or email contact@char-gen.com\n    from your account email address.\nrights:\n- right: Access\n  text: You may request access to the personal information that we hold about you.\n- right: Correction\n  text: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant\n    or misleading, please contact us using the details below.\n- right: Restrict and unsubscribe\n  text: To object to processing for direct marketing/unsubscribe from our email database or opt-out of communications\n- right: Complaints\n  text: If you wish to make a complaint, please contact\
  \ us using the details below\n- right: Erasure (EU/UK)\n  text: to have your personal information rectified or deleted, to restrict our processing of that information\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/char-gen-com/privacy/char-gen-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 31 quoted statements, read from CharGen's own page on 2026-11-09.
synthetic: false
tags:
- AI Art
- RPG Tools
- Character Generation
- Map Generation
- Campaign Building
- Audio Generation
---
