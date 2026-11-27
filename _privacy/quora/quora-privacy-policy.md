---
api_specs:
- filename: quora-models-api-openapi.yml
  format: yaml
  label: Quora Models API
  slug: quora-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-models-api-openapi.yml
- filename: quora-responses-api-openapi.yml
  format: yaml
  label: Quora Responses API
  slug: quora-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-responses-api-openapi.yml
- filename: quora-usage-api-openapi.yml
  format: yaml
  label: Quora Usage API
  slug: quora-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-usage-api-openapi.yml
- filename: quora-chat-completions-api-openapi.yml
  format: yaml
  label: Quora Chat Completions API
  slug: quora-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-chat-completions-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, and other information you provide
  - category: contact
    text: phone number, and email address
  - category: financial
    text: we collect payment information if you are a paid Quora creator via the Quora Partner Program
  - category: location
    text: Geolocation data, such as approximate location data (we don’t collect precise geolocation, but can infer general location from your IP address)
  - category: behavioral
    text: Platform Engagement Data. We collect platform engagement and browsing information, such as IP address, date and time stamp, user agent, Quora cookie ID, URLs visited
  - category: device
    text: browser type, type of computer or mobile device, browser language, IP address, mobile carrier, unique device identifier
  - category: communication
    text: We maintain a record when you communicate with us via email, through the Quora Platform, or otherwise.
  - category: professional
    text: Employment information, such as employment details you add to your profile
  - category: demographic
    text: You can choose to add your photo, country of residence, place of employment, education history
  deletion:
    route: Account deletion in profile settings or email privacy@quora.com
    text: If you choose to “Delete Account” in your profile settings, then all your content will be removed from public visibility on the Quora Platform, and it may not be restored by us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide our Services
    text: To provide you the services we offer on the Quora Platform and make the Quora Platform available to the public
  - purpose: Personalization
    text: To tailor the content and information that we or our third party content publishers or advertisers may send or display to you in the Quora Platform.
  - purpose: Billing and payment
    text: To collect payments (for example, if you are a Quora+ subscriber) and pay our service providers and content creators.
  - purpose: Advertising
    text: To display interest-based, retargeted, contextual, and behavioral advertising to you in the Quora Platform.
  - purpose: Marketing and promotions
    text: For marketing and promotional purposes, such as to send you news, special offers, promotions
  - purpose: Analytics
    text: To gather analytics and metrics to better understand how users use the Quora Platform.
  - purpose: Comply with law
    text: To comply with legal obligations, as part of our general business operations
  - purpose: Prevent fraud and misuse
    text: To investigate, prevent, or take action regarding illegal activities, suspected fraud
  residency:
  - region: United States
    text: Quora Inc. is headquartered in the United States, and has operations, entities, and service providers in the United States and throughout the world.
  retention:
  - period: null
    scope: Active account relationship
    text: We keep your personal information for as long as we have a relationship with you.
  - period: null
    scope: After relationship ends
    text: we will retain your personal information for a period of time that enables us to maintain business records for audit purposes, comply with record retention requirements under the law, and defend or bring any existing or potential legal claims.
  rights:
  - right: Access
    text: Access your personal information
  - right: Rectify
    text: Rectify the personal information we hold about you
  - right: Erase
    text: Erase your personal information
  - right: Restrict
    text: Restrict our use of your personal information
  - right: Object
    text: Object to our use of your personal information
  - right: Opt out of targeted advertising
    text: Opt out of targeted advertising
  - right: Data portability
    text: Data portability
  - right: Withdraw consent
    text: Withdraw consent you have given at any time
  role:
    text: Quora Inc. is the data controller of your personal information and is responsible for providing you with this Privacy Policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on transfer mechanisms such as the European-Commission approved Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Quora
provenance_date: '2026-11-10'
provider_name: Quora
provider_slug: quora
slug: quora-privacy-policy
source_date: '2026-11-10'
source_filename: quora-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.quora.com/about/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Quora\naid: quora\nurl: https://www.quora.com/about/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Quora Inc. is the data controller of your personal information and is responsible for providing you with\n    this Privacy Policy.\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, and other information you provide\n- category: contact\n  text: phone number, and email address\n- category: financial\n  text: we collect payment information if you are a paid Quora creator via the Quora Partner Program\n- category: location\n  text: Geolocation data,\
  \ such as approximate location data (we don’t collect precise geolocation, but can infer\n    general location from your IP address)\n- category: behavioral\n  text: Platform Engagement Data. We collect platform engagement and browsing information, such as IP address, date\n    and time stamp, user agent, Quora cookie ID, URLs visited\n- category: device\n  text: browser type, type of computer or mobile device, browser language, IP address, mobile carrier, unique device\n    identifier\n- category: communication\n  text: We maintain a record when you communicate with us via email, through the Quora Platform, or otherwise.\n- category: professional\n  text: Employment information, such as employment details you add to your profile\n- category: demographic\n  text: You can choose to add your photo, country of residence, place of employment, education history\npurposes:\n- purpose: Provide our Services\n  text: To provide you the services we offer on the Quora Platform and make the Quora\
  \ Platform available to the\n    public\n- purpose: Personalization\n  text: To tailor the content and information that we or our third party content publishers or advertisers may send\n    or display to you in the Quora Platform.\n- purpose: Billing and payment\n  text: To collect payments (for example, if you are a Quora+ subscriber) and pay our service providers and content\n    creators.\n- purpose: Advertising\n  text: To display interest-based, retargeted, contextual, and behavioral advertising to you in the Quora Platform.\n- purpose: Marketing and promotions\n  text: For marketing and promotional purposes, such as to send you news, special offers, promotions\n- purpose: Analytics\n  text: To gather analytics and metrics to better understand how users use the Quora Platform.\n- purpose: Comply with law\n  text: To comply with legal obligations, as part of our general business operations\n- purpose: Prevent fraud and misuse\n  text: To investigate, prevent, or take action regarding\
  \ illegal activities, suspected fraud\nretention:\n- scope: Active account relationship\n  period: null\n  text: We keep your personal information for as long as we have a relationship with you.\n- scope: After relationship ends\n  period: null\n  text: we will retain your personal information for a period of time that enables us to maintain business records\n    for audit purposes, comply with record retention requirements under the law, and defend or bring any existing\n    or potential legal claims.\nresidency:\n- region: United States\n  text: Quora Inc. is headquartered in the United States, and has operations, entities, and service providers in\n    the United States and throughout the world.\ntransfers:\n- mechanism: SCC\n  text: we rely on transfer mechanisms such as the European-Commission approved Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion in profile settings\
  \ or email privacy@quora.com\n  text: If you choose to “Delete Account” in your profile settings, then all your content will be removed from public\n    visibility on the Quora Platform, and it may not be restored by us.\nrights:\n- right: Access\n  text: Access your personal information\n- right: Rectify\n  text: Rectify the personal information we hold about you\n- right: Erase\n  text: Erase your personal information\n- right: Restrict\n  text: Restrict our use of your personal information\n- right: Object\n  text: Object to our use of your personal information\n- right: Opt out of targeted advertising\n  text: Opt out of targeted advertising\n- right: Data portability\n  text: Data portability\n- right: Withdraw consent\n  text: Withdraw consent you have given at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties\n"
source_yaml_url: https://artifacts.apis.io/quora/privacy/quora-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from Quora's own page on 2026-11-10.
synthetic: false
tags:
- Community
- Knowledge
- Q&A
---
