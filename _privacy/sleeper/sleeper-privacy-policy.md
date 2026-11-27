---
api_specs:
- filename: sleeper-drafts-api-openapi.yml
  format: yaml
  label: Sleeper Drafts API
  slug: sleeper-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-drafts-api-openapi.yml
- filename: sleeper-leagues-api-openapi.yml
  format: yaml
  label: Sleeper Leagues API
  slug: sleeper-leagues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-leagues-api-openapi.yml
- filename: sleeper-matchups-api-openapi.yml
  format: yaml
  label: Sleeper Matchups API
  slug: sleeper-matchups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-matchups-api-openapi.yml
- filename: sleeper-players-api-openapi.yml
  format: yaml
  label: Sleeper Players API
  slug: sleeper-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-players-api-openapi.yml
- filename: sleeper-playoffs-api-openapi.yml
  format: yaml
  label: Sleeper Playoffs API
  slug: sleeper-playoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-playoffs-api-openapi.yml
- filename: sleeper-state-api-openapi.yml
  format: yaml
  label: Sleeper State API
  slug: sleeper-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-state-api-openapi.yml
- filename: sleeper-transactions-api-openapi.yml
  format: yaml
  label: Sleeper Transactions API
  slug: sleeper-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-transactions-api-openapi.yml
- filename: sleeper-users-api-openapi.yml
  format: yaml
  label: Sleeper Users API
  slug: sleeper-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sleeper/openapi/sleeper-users-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Sign-in information, including e-mail address, name, authentication information, telephone/mobile phone numbers, and/or any passwords you create
  - category: location
    text: Time zone setting and location
  - category: device
    text: Device and advertising identifiers
  - category: financial
    text: Payment information, from you or on behalf of our payment service providers
  - category: behavioral
    text: Information about the links you click, pages you view, and advertising you interact with within the Services
  - category: communication
    text: Photo, chat, and messages information, including photos, animated images, and direct or private messages sent to other users
  - category: demographic
    text: Age-range, and should you identity as under 18 (or as applicable, 16), your birthdate
  deletion:
    route: Account deletion via app settings or sleeper.com/deleteaccount
    text: You may also delete your entire platform account by going to sleeper.com/deleteaccount and completing the deletion request form.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing requested products and services
    text: Administering and providing products and services that you request, including allowing you to participate in games and other features of our Services
  - purpose: Advertising
    text: Providing you relevant advertising, including advertising that you see while using the Services
  - purpose: Improving services and analytics
    text: Improving our Services and to ensure that content is presented in the most relevant and effective manner for you and your device, including troubleshooting, data analytics, testing, research, and statistical and survey purposes
  residency:
  - region: United States
    text: We and many of our third-party vendors are based in the United States
  retention:
  - period: null
    scope: General personal information
    text: Your information will be retained only for so long as reasonably necessary, for the purposes set out herein, and in accordance with applicable law.
  rights:
  - right: Access
    text: You can access and verify what information our Services have collected and currently contains by logging into your account and visiting your account profile page.
  - right: Correction
    text: 'Right to Correct : You have the right to request correction of any inaccurate information we hold about you.'
  - right: Deletion
    text: 'Right to Delete* : You have the right to request that we delete any of your information that we have collected from you directly or from other sources and retained, subject to certain exceptions.'
  - right: Opt-out of sale
    text: 'Right to opt-out of a sale : You have the right to opt-out of our sale or our use of information for targeted advertising purposes.'
  - right: Portability
    text: Additionally, you may request that we provide the specific pieces of information we collect about you in a portable format.
  - right: Object to processing
    text: Object to Processing . When applicable, you have the right to object to the processing of your information by submitting a request via email as described below.
  role:
    text: Note that Blitz Studios, Inc. is the controller of personal data collected through the Services.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell your information for monetary consideration; however, we may share your information with third-party service providers in a way that may be considered a sale of your information under applicable U.S. Privacy Laws.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: To the extent we disclose your information to third-party vendors, we use contractual safeguards to help ensure that such third-party vendors are bound to duties of confidentiality.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sleeper
provenance_date: '2026-11-10'
provider_name: Sleeper
provider_slug: sleeper
slug: sleeper-privacy-policy
source_date: '2026-11-10'
source_filename: sleeper-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://support.sleeper.com/en/articles/5486618-privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sleeper\naid: sleeper\nurl: https://support.sleeper.com/en/articles/5486618-privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Note that Blitz Studios, Inc. is the controller of personal data collected through the Services.\ndata_categories:\n- category: identifying\n  text: Sign-in information, including e-mail address, name, authentication information, telephone/mobile phone\n    numbers, and/or any passwords you create\n- category: location\n  text: Time zone setting and location\n- category: device\n  text: Device and advertising identifiers\n- category: financial\n  text: Payment\
  \ information, from you or on behalf of our payment service providers\n- category: behavioral\n  text: Information about the links you click, pages you view, and advertising you interact with within the Services\n- category: communication\n  text: Photo, chat, and messages information, including photos, animated images, and direct or private messages\n    sent to other users\n- category: demographic\n  text: Age-range, and should you identity as under 18 (or as applicable, 16), your birthdate\npurposes:\n- purpose: Providing requested products and services\n  text: Administering and providing products and services that you request, including allowing you to participate\n    in games and other features of our Services\n- purpose: Advertising\n  text: Providing you relevant advertising, including advertising that you see while using the Services\n- purpose: Improving services and analytics\n  text: Improving our Services and to ensure that content is presented in the most relevant and effective\
  \ manner\n    for you and your device, including troubleshooting, data analytics, testing, research, and statistical and survey\n    purposes\nretention:\n- scope: General personal information\n  period: null\n  text: Your information will be retained only for so long as reasonably necessary, for the purposes set out herein,\n    and in accordance with applicable law.\nresidency:\n- region: United States\n  text: We and many of our third-party vendors are based in the United States\ntransfers:\n- mechanism: other\n  text: To the extent we disclose your information to third-party vendors, we use contractual safeguards to help\n    ensure that such third-party vendors are bound to duties of confidentiality.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion via app settings or sleeper.com/deleteaccount\n  text: You may also delete your entire platform account by going to sleeper.com/deleteaccount and completing\
  \ the\n    deletion request form.\nrights:\n- right: Access\n  text: You can access and verify what information our Services have collected and currently contains by logging\n    into your account and visiting your account profile page.\n- right: Correction\n  text: 'Right to Correct : You have the right to request correction of any inaccurate information we hold about\n    you.'\n- right: Deletion\n  text: 'Right to Delete* : You have the right to request that we delete any of your information that we have collected\n    from you directly or from other sources and retained, subject to certain exceptions.'\n- right: Opt-out of sale\n  text: 'Right to opt-out of a sale : You have the right to opt-out of our sale or our use of information for targeted\n    advertising purposes.'\n- right: Portability\n  text: Additionally, you may request that we provide the specific pieces of information we collect about you in\n    a portable format.\n- right: Object to processing\n  text: Object to Processing\
  \ . When applicable, you have the right to object to the processing of your information\n    by submitting a request via email as described below.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your information for monetary consideration; however, we may share your information with\n    third-party service providers in a way that may be considered a sale of your information under applicable U.S.\n    Privacy Laws.\n"
source_yaml_url: https://artifacts.apis.io/sleeper/privacy/sleeper-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Sleeper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fantasy Sports
- Sports
- Fantasy Football
- Gaming
- Sports Data
- League
- Consumer
---
