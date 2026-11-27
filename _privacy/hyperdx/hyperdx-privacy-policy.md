---
api_specs:
- filename: hyperdx-alerts-api-openapi.yml
  format: yaml
  label: HyperDX Alerts API
  slug: hyperdx-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-alerts-api-openapi.yml
- filename: hyperdx-charts-api-openapi.yml
  format: yaml
  label: HyperDX Charts API
  slug: hyperdx-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-charts-api-openapi.yml
- filename: hyperdx-connections-api-openapi.yml
  format: yaml
  label: HyperDX Connections API
  slug: hyperdx-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-connections-api-openapi.yml
- filename: hyperdx-dashboards-api-openapi.yml
  format: yaml
  label: HyperDX Dashboards API
  slug: hyperdx-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-dashboards-api-openapi.yml
- filename: hyperdx-saved-searches-api-openapi.yml
  format: yaml
  label: HyperDX Saved Searches API
  slug: hyperdx-saved-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-saved-searches-api-openapi.yml
- filename: hyperdx-search-api-openapi.yml
  format: yaml
  label: HyperDX Search API
  slug: hyperdx-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-search-api-openapi.yml
- filename: hyperdx-sources-api-openapi.yml
  format: yaml
  label: HyperDX Sources API
  slug: hyperdx-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-sources-api-openapi.yml
- filename: hyperdx-team-api-openapi.yml
  format: yaml
  label: HyperDX Team API
  slug: hyperdx-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-team-api-openapi.yml
- filename: hyperdx-webhooks-api-openapi.yml
  format: yaml
  label: HyperDX Webhooks API
  slug: hyperdx-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: we typically ask for identifying information such as your name, email address, and maybe a company name
  - category: financial
    text: we ask for your credit card and billing address
  - category: location
    text: We log all access to all accounts by full IP address
  - category: device
    text: your browser automatically shares certain information such as which operating system and browser version you are using
  - category: behavioral
    text: We track that information, along with the pages you are visiting, page load timing, and which website referred you
  - category: communication
    text: When you write DeploySentinel with a question or to ask for help, we keep that correspondence, including the email address
  - category: demographic
    text: We don’t collect any characteristics of protected classifications including age, race, gender, religion, sexual orientation, gender identity, gender expression, or physical and mental abilities or disabilities.
  deletion:
    route: data deletion request to privacy@deploysentinel.com
    text: Many of these rights can be exercised by signing in and directly updating your account information. If you have questions about exercising these rights or need assistance, please contact us at privacy@deploysentinel.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account personalization and invoices
    text: That’s just so you can personalize your new account, and we can send you invoices, updates, or other essential information.
  - purpose: charging and tax
    text: That’s so we can charge you for service, calculate taxes due, and send you invoices.
  - purpose: security logging
    text: We log all access to all accounts by full IP address so that we can always verify no unauthorized access has happened.
  - purpose: statistical analytics and design testing
    text: for statistical purposes like conversion rates and to test new designs
  - purpose: anti-bot protection
    text: We use CAPTCHA (opens in a new tab) services across our applications to mitigate brute force logins and in as a means of spam protection.
  residency:
  - region: United States
    text: Our products and other web properties are operated in the United States.
  retention:
  - period: as long as your product account is active
    scope: login data
    text: We keep this login data for as long as your product account is active.
  rights:
  - right: Right to Know
    text: You have the right to know what personal information is collected, used, shared or sold.
  - right: Right of Access
    text: This includes your right to access the personal information we gather about you
  - right: Right to Correction
    text: You have the right to request correction of your personal information.
  - right: Right to Erasure
    text: This is your right to request, subject to certain limitations under applicable law, that your personal information be erased from our possession and, by extension, all of our service providers.
  - right: Right to Complain
    text: You have the right to make a complaint regarding our handling of your personal information with the appropriate supervisory authority.
  - right: Right to Restrict Processing
    text: This is your right to request restriction of how and why your personal information is used or processed, including opting out of sale of personal information.
  - right: Right to Object
    text: You have the right, in certain situations, to object to how or why your personal information is processed.
  - right: Right to Portability
    text: You have the right to receive the personal information we have about you and the right to transmit it to another party.
  role:
    text: 'We promise we never sell your data: never have, never will.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: 'We promise we never sell your data: never have, never will.'
  subprocessors:
    text: We do use some third-party services to run our applications and only to the extent necessary process some or all of your personal information via these third parties.
    url: null
  transfers:
  - mechanism: other
    text: any information you provide to us will be transferred to and stored in the United States . By using our Site, participating in any of our services and/or providing us with your information, you consent to this transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HyperDX
provenance_date: '2026-11-09'
provider_name: HyperDX
provider_slug: hyperdx
slug: hyperdx-privacy-policy
source_date: '2026-11-09'
source_filename: hyperdx-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.hyperdx.io/terms/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HyperDX\naid: hyperdx\nurl: https://www.hyperdx.io/terms/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'We promise we never sell your data: never have, never will.'\ndata_categories:\n- category: identifying\n  text: we typically ask for identifying information such as your name, email address, and maybe a company name\n- category: financial\n  text: we ask for your credit card and billing address\n- category: location\n  text: We log all access to all accounts by full IP address\n- category: device\n  text: your browser automatically shares certain information such as which operating\
  \ system and browser version\n    you are using\n- category: behavioral\n  text: We track that information, along with the pages you are visiting, page load timing, and which website referred\n    you\n- category: communication\n  text: When you write DeploySentinel with a question or to ask for help, we keep that correspondence, including\n    the email address\n- category: demographic\n  text: We don’t collect any characteristics of protected classifications including age, race, gender, religion,\n    sexual orientation, gender identity, gender expression, or physical and mental abilities or disabilities.\npurposes:\n- purpose: account personalization and invoices\n  text: That’s just so you can personalize your new account, and we can send you invoices, updates, or other essential\n    information.\n- purpose: charging and tax\n  text: That’s so we can charge you for service, calculate taxes due, and send you invoices.\n- purpose: security logging\n  text: We log all access to all accounts\
  \ by full IP address so that we can always verify no unauthorized access\n    has happened.\n- purpose: statistical analytics and design testing\n  text: for statistical purposes like conversion rates and to test new designs\n- purpose: anti-bot protection\n  text: We use CAPTCHA (opens in a new tab) services across our applications to mitigate brute force logins and\n    in as a means of spam protection.\nretention:\n- scope: login data\n  period: as long as your product account is active\n  text: We keep this login data for as long as your product account is active.\nresidency:\n- region: United States\n  text: Our products and other web properties are operated in the United States.\ntransfers:\n- mechanism: other\n  text: any information you provide to us will be transferred to and stored in the United States . By using our\n    Site, participating in any of our services and/or providing us with your information, you consent to this transfer.\nsubprocessors:\n  url: null\n  text: We\
  \ do use some third-party services to run our applications and only to the extent necessary process some\n    or all of your personal information via these third parties.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: data deletion request to privacy@deploysentinel.com\n  text: Many of these rights can be exercised by signing in and directly updating your account information. If you\n    have questions about exercising these rights or need assistance, please contact us at privacy@deploysentinel.com\n    .\nrights:\n- right: Right to Know\n  text: You have the right to know what personal information is collected, used, shared or sold.\n- right: Right of Access\n  text: This includes your right to access the personal information we gather about you\n- right: Right to Correction\n  text: You have the right to request correction of your personal information.\n- right: Right to Erasure\n  text: This is your right to request, subject to certain limitations under applicable\
  \ law, that your personal information\n    be erased from our possession and, by extension, all of our service providers.\n- right: Right to Complain\n  text: You have the right to make a complaint regarding our handling of your personal information with the appropriate\n    supervisory authority.\n- right: Right to Restrict Processing\n  text: This is your right to request restriction of how and why your personal information is used or processed,\n    including opting out of sale of personal information.\n- right: Right to Object\n  text: You have the right, in certain situations, to object to how or why your personal information is processed.\n- right: Right to Portability\n  text: You have the right to receive the personal information we have about you and the right to transmit it to\n    another party.\nsale_or_sharing:\n  stance: prohibited\n  text: 'We promise we never sell your data: never have, never will.'\n"
source_yaml_url: https://artifacts.apis.io/hyperdx/privacy/hyperdx-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from HyperDX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Observability
- Monitoring
- Logging
- Tracing
- Metrics
- OpenTelemetry
- ClickHouse
- Open Source
- Alerting
- Dashboards
- Session Replay
- Developer Tools
- Agents
---
