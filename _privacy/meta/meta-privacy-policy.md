---
api_specs:
- filename: meta-custom-audiences-api-openapi.yml
  format: yaml
  label: Meta Custom Audiences API
  slug: meta-custom-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meta/openapi/meta-custom-audiences-api-openapi.yml
- filename: meta-pages-api-openapi.yml
  format: yaml
  label: Meta Pages API
  slug: meta-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meta/openapi/meta-pages-api-openapi.yml
- filename: meta-users-api-openapi.yml
  format: yaml
  label: Meta Users API
  slug: meta-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meta/openapi/meta-users-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers that tell your device apart from other users’
  - category: contact
    text: Information you’ve shared through your device settings (like GPS location)
  - category: location
    text: Location-related information
  - category: financial
    text: Purchases or other transactions you make, including truncated credit card information
  - category: communication
    text: Messages you send and receive, including their content, subject to applicable law
  - category: behavioral
    text: Types of content you view or interact with, and how you interact with it
  - category: device
    text: Device characteristics and device software
  - category: biometric
    text: Your photo or video selfie if you provide it when you contact us for account support
  - category: demographic
    text: Any information with special protections that you choose to provide, such as your religious views, your sexual orientation, political views, health, racial or ethnic origin, philosophical beliefs or trade union membership
  deletion:
    route: Delete your information or account
    text: Delete your information or account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, personalize and improve Products
    text: We use information we have to provide and improve our Products.
  - purpose: Promote safety, security and integrity
    text: We use information we collect to help protect people from harm and provide safe, secure Products.
  - purpose: Measurement, analytics and business services
    text: Lots of people rely on our Products to run or promote their businesses or share content.
  - purpose: Communicate with you
    text: We communicate with you using information you've given us, like contact information you've entered on your profile.
  - purpose: Research and innovate for social good
    text: We use information we have, information from researchers and datasets from publicly available sources, professional groups and non-profit groups to conduct and support research.
  - purpose: Personalized ads
    text: Receiving and using information from third parties to tailor the ads you see
  residency:
  - region: United States
    text: 'Meta Platforms, Inc. ATTN: Privacy Operations 1 Meta Way Menlo Park, CA 94025'
  retention:
  - period: null
    scope: General retention
    text: We keep information as long as we need it to provide our Products, comply with legal obligations or protect our or other’s interests.
  - period: null
    scope: Message vanish mode
    text: messages sent using Messenger’s vanish mode are retained for less time than regular messages
  rights:
  - right: Access, download, port or delete information
    text: Access your information Your information and permissions Ad preferences Manage your data Port, download or delete your information
  - right: Other privacy rights under applicable laws
    text: You may also have other privacy rights under applicable laws.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell any of your information to anyone, and we never will.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Transferring, storing or processing your information across borders, including from and to the United States and other countries
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Meta
provenance_date: '2026-11-10'
provider_name: Meta
provider_slug: meta
slug: meta-privacy-policy
source_date: '2026-11-10'
source_filename: meta-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.facebook.com/privacy/policy/?entry_point=data_policy_redirect&entry=0
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Meta\naid: meta\nurl: https://www.facebook.com/privacy/policy/?entry_point=data_policy_redirect&entry=0\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers that tell your device apart from other users’\n- category: contact\n  text: Information you’ve shared through your device settings (like GPS location)\n- category: location\n  text: Location-related information\n- category: financial\n  text: Purchases or other transactions you make, including truncated credit card information\n- category: communication\n  text: Messages you\
  \ send and receive, including their content, subject to applicable law\n- category: behavioral\n  text: Types of content you view or interact with, and how you interact with it\n- category: device\n  text: Device characteristics and device software\n- category: biometric\n  text: Your photo or video selfie if you provide it when you contact us for account support\n- category: demographic\n  text: Any information with special protections that you choose to provide, such as your religious views, your\n    sexual orientation, political views, health, racial or ethnic origin, philosophical beliefs or trade union membership\npurposes:\n- purpose: Provide, personalize and improve Products\n  text: We use information we have to provide and improve our Products.\n- purpose: Promote safety, security and integrity\n  text: We use information we collect to help protect people from harm and provide safe, secure Products.\n- purpose: Measurement, analytics and business services\n  text: Lots of people\
  \ rely on our Products to run or promote their businesses or share content.\n- purpose: Communicate with you\n  text: We communicate with you using information you've given us, like contact information you've entered on your\n    profile.\n- purpose: Research and innovate for social good\n  text: We use information we have, information from researchers and datasets from publicly available sources, professional\n    groups and non-profit groups to conduct and support research.\n- purpose: Personalized ads\n  text: Receiving and using information from third parties to tailor the ads you see\nretention:\n- scope: General retention\n  period: null\n  text: We keep information as long as we need it to provide our Products, comply with legal obligations or protect\n    our or other’s interests.\n- scope: Message vanish mode\n  period: null\n  text: messages sent using Messenger’s vanish mode are retained for less time than regular messages\nresidency:\n- region: United States\n  text: 'Meta\
  \ Platforms, Inc. ATTN: Privacy Operations 1 Meta Way Menlo Park, CA 94025'\ntransfers:\n- mechanism: other\n  text: Transferring, storing or processing your information across borders, including from and to the United States\n    and other countries\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your information or account\n  text: Delete your information or account\nrights:\n- right: Access, download, port or delete information\n  text: Access your information Your information and permissions Ad preferences Manage your data Port, download\n    or delete your information\n- right: Other privacy rights under applicable laws\n  text: You may also have other privacy rights under applicable laws.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell any of your information to anyone, and we never will.\n"
source_yaml_url: https://artifacts.apis.io/meta/privacy/meta-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Meta's own page on 2026-11-10.
synthetic: false
tags:
- Meta
- Advertising
- Analytics
- Artificial Intelligence
- Messaging
- Social
- Social Media
- Virtual Reality
---
