---
api_specs:
- filename: community-member-data-api-openapi.yml
  format: yaml
  label: Community Member Data API
  slug: community-member-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/community/openapi/community-member-data-api-openapi.yml
- filename: community-messaging-api-openapi.yml
  format: yaml
  label: Community Messaging API
  slug: community-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/community/openapi/community-messaging-api-openapi.yml
- filename: community-tags-api-openapi.yml
  format: yaml
  label: Community Tags API
  slug: community-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/community/openapi/community-tags-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: communication
    text: we collect your messages, including message-related information (such as the phone number from which the message was sent, when the message was sent, the content of the message
  - category: contact
    text: such as your name, email, phone number, and demographic information such as your date of birth, gender identity, location, or interests
  - category: location
    text: We may also collect information about your location, such as by using your IP address to determine your approximate location.
  - category: device
    text: This includes information about the type of device and operating system you use, your phone number, your IP address and location, cookie and device identifiers
  - category: financial
    text: such as your credit or debit card number, card expiration date, CVV code, and billing address.
  - category: behavioral
    text: We or the Leader may analyze your activities (including your Contact Info, Messaging Info, and imported data) and generate insights about you (“Member Info”).
  deletion:
    route: email privacy@community.com
    text: You can delete your information by emailing privacy@community.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the platform and messaging
    text: to operate the Community platform for Community Leaders, including by offering our websites and apps, analyzing Messaging Info and Contact Info
  - purpose: marketing
    text: to market Community to potential and current Community Members and Community Leaders
  - purpose: improve and develop services
    text: to otherwise develop, operate, improve, deliver, promote, maintain, and protect Community services
  - purpose: security and legal compliance
    text: to keep Community and our users safe and secure, to enforce our Terms and other usage policies, to comply with legal requirements
  retention:
  - period: null
    scope: personal data generally
    text: Information will be retained only for so long as reasonably necessary for the purposes set out above, in accordance with applicable laws.
  - period: null
    scope: legal preservation
    text: There may be legal requirements for us to retain your information, for instance if we receive valid legal process asking us to preserve data
  rights:
  - right: access
    text: to request access to, rectification, erasure, and portability of your information
  - right: object or restrict processing
    text: You may also be entitled, in accordance with applicable law, to object to or request restriction of processing of your information
  - right: deletion (CCPA)
    text: Additionally, you may request that we delete personal information we have collected from you as defined under the CCPA.
  - right: opt out of texts
    text: message “STOP” (case insensitive) to their Community Number.
  role:
    text: Community.com, Inc. ( “we,” “our,” or “us” ) collects, uses, and otherwise processes personal data
    value: controller
  sale_or_sharing:
    stance: unstated
    text: In the past 12 months, we have not sold your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we make use of the European Commission-approved standard contractual data protection clauses
  - mechanism: other
    text: or other appropriate legal mechanisms to safeguard the transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Community
provenance_date: '2026-11-09'
provider_name: Community
provider_slug: community
slug: community-privacy-policy
source_date: '2026-11-09'
source_filename: community-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://community.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Community\naid: community\nurl: https://community.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Community.com, Inc. ( “we,” “our,” or “us” ) collects, uses, and otherwise processes personal data\ndata_categories:\n- category: communication\n  text: we collect your messages, including message-related information (such as the phone number from which the\n    message was sent, when the message was sent, the content of the message\n- category: contact\n  text: such as your name, email, phone number, and demographic information such as your date of birth, gender identity,\n\
  \    location, or interests\n- category: location\n  text: We may also collect information about your location, such as by using your IP address to determine your\n    approximate location.\n- category: device\n  text: This includes information about the type of device and operating system you use, your phone number, your\n    IP address and location, cookie and device identifiers\n- category: financial\n  text: such as your credit or debit card number, card expiration date, CVV code, and billing address.\n- category: behavioral\n  text: We or the Leader may analyze your activities (including your Contact Info, Messaging Info, and imported\n    data) and generate insights about you (“Member Info”).\npurposes:\n- purpose: operate the platform and messaging\n  text: to operate the Community platform for Community Leaders, including by offering our websites and apps, analyzing\n    Messaging Info and Contact Info\n- purpose: marketing\n  text: to market Community to potential and current\
  \ Community Members and Community Leaders\n- purpose: improve and develop services\n  text: to otherwise develop, operate, improve, deliver, promote, maintain, and protect Community services\n- purpose: security and legal compliance\n  text: to keep Community and our users safe and secure, to enforce our Terms and other usage policies, to comply\n    with legal requirements\nretention:\n- scope: personal data generally\n  period: null\n  text: Information will be retained only for so long as reasonably necessary for the purposes set out above, in\n    accordance with applicable laws.\n- scope: legal preservation\n  period: null\n  text: There may be legal requirements for us to retain your information, for instance if we receive valid legal\n    process asking us to preserve data\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we make use of the European Commission-approved standard contractual data protection clauses\n- mechanism: other\n  text: or other appropriate legal mechanisms\
  \ to safeguard the transfer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@community.com\n  text: You can delete your information by emailing privacy@community.com .\nrights:\n- right: access\n  text: to request access to, rectification, erasure, and portability of your information\n- right: object or restrict processing\n  text: You may also be entitled, in accordance with applicable law, to object to or request restriction of processing\n    of your information\n- right: deletion (CCPA)\n  text: Additionally, you may request that we delete personal information we have collected from you as defined\n    under the CCPA.\n- right: opt out of texts\n  text: message “STOP” (case insensitive) to their Community Number.\nsale_or_sharing:\n  stance: unstated\n  text: In the past 12 months, we have not sold your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/community/privacy/community-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Community's own page on 2026-11-09.
synthetic: false
tags:
- Messaging
- SMS
- Communications
- Marketing
- Creators
- Webhook
- Company
---
