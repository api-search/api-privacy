---
api_specs:
- filename: umami-authentication-api-openapi.yml
  format: yaml
  label: Umami Authentication API
  slug: umami-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-authentication-api-openapi.yml
- filename: umami-teams-api-openapi.yml
  format: yaml
  label: Umami Teams API
  slug: umami-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-teams-api-openapi.yml
- filename: umami-users-api-openapi.yml
  format: yaml
  label: Umami Users API
  slug: umami-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-users-api-openapi.yml
- filename: umami-websites-api-openapi.yml
  format: yaml
  label: Umami Websites API
  slug: umami-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-websites-api-openapi.yml
- filename: umami-account-api-openapi.yml
  format: yaml
  label: Umami Account API
  slug: umami-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-account-api-openapi.yml
- filename: umami-administration-api-openapi.yml
  format: yaml
  label: Umami Administration API
  slug: umami-administration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-administration-api-openapi.yml
- filename: umami-boards-api-openapi.yml
  format: yaml
  label: Umami Boards API
  slug: umami-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-boards-api-openapi.yml
- filename: umami-collection-api-openapi.yml
  format: yaml
  label: Umami Collection API
  slug: umami-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-collection-api-openapi.yml
- filename: umami-dashboard-api-openapi.yml
  format: yaml
  label: Umami Dashboard API
  slug: umami-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-dashboard-api-openapi.yml
- filename: umami-links-api-openapi.yml
  format: yaml
  label: Umami Links API
  slug: umami-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-links-api-openapi.yml
- filename: umami-pixels-api-openapi.yml
  format: yaml
  label: Umami Pixels API
  slug: umami-pixels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-pixels-api-openapi.yml
- filename: umami-realtime-api-openapi.yml
  format: yaml
  label: Umami Realtime API
  slug: umami-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-realtime-api-openapi.yml
- filename: umami-scripts-api-openapi.yml
  format: yaml
  label: Umami Scripts API
  slug: umami-scripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-scripts-api-openapi.yml
- filename: umami-shares-api-openapi.yml
  format: yaml
  label: Umami Shares API
  slug: umami-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-shares-api-openapi.yml
- filename: umami-system-api-openapi.yml
  format: yaml
  label: Umami System API
  slug: umami-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-system-api-openapi.yml
- filename: umami-two-factor-authentication-api-openapi.yml
  format: yaml
  label: Umami Two-factor authentication API
  slug: umami-two-factor-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-two-factor-authentication-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: email addresses names usernames passwords contact preferences
  - category: device
    text: We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: information about how and when you use our Services
  - category: financial
    text: All payment data is stored by Stripe.
  - category: device
    source: https://umami.is/dpa
    text: browser, operating-system, device, language, screen, and similar technical metadata
  - category: location
    source: https://umami.is/dpa
    text: country, region, city, or other approximate location information
  - category: behavioral
    source: https://umami.is/dpa
    text: session, interaction, heatmap, or replay-related information where the applicable feature is enabled
  deletion:
    route: Account termination request or contact email
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: true
    text: Umami processes that data on their behalf under the Data Processing Agreement
    url: null
  purposes:
  - purpose: Account creation and management
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: Deliver services
    text: To deliver and facilitate delivery of services to the user.
  - purpose: Respond to support inquiries
    text: To respond to user inquiries/offer support to users.
  - purpose: Fulfil orders
    text: To fulfill and manage your orders.
  - purpose: Support, security and abuse prevention
    source: https://umami.is/dpa
    text: providing customer support, troubleshooting, maintenance, monitoring, security, abuse prevention, and incident response
  retention:
  - period: As long as the user has an account with us
    scope: Categories A, B, G
    text: Category A - As long as the user has an account with us
  - period: null
    scope: General
    text: No purpose in this notice will require us keeping your personal information for longer than the period of time in which users have an account with us.
  - period: null
    scope: Customer Personal Data
    source: https://umami.is/dpa
    text: As configured by Customer, described in the Agreement or applicable product documentation, required to provide the Services, or required by law.
  rights:
  - right: Access
    text: to request access and obtain a copy of your personal information
  - right: Deletion
    text: You can ask for the deletion of your personal information.
  - right: Correction
    text: You may request correction of your personal data if it is incorrect or no longer relevant
  - right: Objection
    text: You may object to the processing of your personal information.
  - right: Opt out of sale or sharing
    text: You may request to opt out from future selling or sharing of your personal information to third parties.
  - right: Audit and information
    source: https://umami.is/dpa
    text: Upon reasonable written request, Umami will make available information reasonably necessary to demonstrate compliance with this DPA.
  - right: Assistance with Data Subject Requests
    source: https://umami.is/dpa
    text: Umami will provide reasonable assistance through appropriate technical and organizational measures to help Customer respond to Data Subject Requests.
  role:
    text: Umami processes information for its own business operations, including visits to our website, account administration, billing, and customer communications.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will not sell or share personal information in the future belonging to website visitors, users, and other consumers.
  subprocessors:
    text: A current list of our subprocessors is available at https://umami.is/subprocessors .
    url: https://umami.is/subprocessors
  transfers:
  - mechanism: SCC
    source: https://umami.is/dpa
    text: the EU SCCs are incorporated into this DPA and apply as described in Schedule 3
  - mechanism: other
    source: https://umami.is/dpa
    text: the UK Addendum is incorporated into this DPA
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Umami
provenance_date: '2026-11-10'
provider_name: Umami
provider_slug: umami
slug: umami-privacy-policy
source_date: '2026-11-10'
source_filename: umami-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://umami.is/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Umami\naid: umami\nurl: https://umami.is/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://umami.is/dpa\n  - https://umami.is/privacy\nrole:\n  value: both\n  text: Umami processes information for its own business operations, including visits to our website, account administration,\n    billing, and customer communications.\ndata_categories:\n- category: identifying\n  text: email addresses names usernames passwords contact preferences\n- category: device\n  text: We collect device data such as information about your computer, phone, tablet, or other device you use to\n    access the Services.\n\
  - category: location\n  text: We collect location data such as information about your device's location, which can be either precise or\n    imprecise.\n- category: behavioral\n  text: information about how and when you use our Services\n- category: financial\n  text: All payment data is stored by Stripe.\n- category: device\n  text: browser, operating-system, device, language, screen, and similar technical metadata\n  source: https://umami.is/dpa\n- category: location\n  text: country, region, city, or other approximate location information\n  source: https://umami.is/dpa\n- category: behavioral\n  text: session, interaction, heatmap, or replay-related information where the applicable feature is enabled\n  source: https://umami.is/dpa\npurposes:\n- purpose: Account creation and management\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: Deliver services\n  text: To deliver and facilitate delivery of services to the user.\n- purpose:\
  \ Respond to support inquiries\n  text: To respond to user inquiries/offer support to users.\n- purpose: Fulfil orders\n  text: To fulfill and manage your orders.\n- purpose: Support, security and abuse prevention\n  text: providing customer support, troubleshooting, maintenance, monitoring, security, abuse prevention, and incident\n    response\n  source: https://umami.is/dpa\nretention:\n- scope: Categories A, B, G\n  period: As long as the user has an account with us\n  text: Category A - As long as the user has an account with us\n- scope: General\n  period: null\n  text: No purpose in this notice will require us keeping your personal information for longer than the period of\n    time in which users have an account with us.\n- scope: Customer Personal Data\n  period: null\n  text: As configured by Customer, described in the Agreement or applicable product documentation, required to provide\n    the Services, or required by law.\n  source: https://umami.is/dpa\nresidency: []\ntransfers:\n\
  - mechanism: SCC\n  text: the EU SCCs are incorporated into this DPA and apply as described in Schedule 3\n  source: https://umami.is/dpa\n- mechanism: other\n  text: the UK Addendum is incorporated into this DPA\n  source: https://umami.is/dpa\nsubprocessors:\n  url: https://umami.is/subprocessors\n  text: A current list of our subprocessors is available at https://umami.is/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: Umami processes that data on their behalf under the Data Processing Agreement\ndeletion:\n  route: Account termination request or contact email\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: Access\n  text: to request access and obtain a copy of your personal information\n- right: Deletion\n  text: You can ask for the deletion of your personal information.\n- right: Correction\n  text: You may request correction of your personal data if it\
  \ is incorrect or no longer relevant\n- right: Objection\n  text: You may object to the processing of your personal information.\n- right: Opt out of sale or sharing\n  text: You may request to opt out from future selling or sharing of your personal information to third parties.\n- right: Audit and information\n  text: Upon reasonable written request, Umami will make available information reasonably necessary to demonstrate\n    compliance with this DPA.\n  source: https://umami.is/dpa\n- right: Assistance with Data Subject Requests\n  text: Umami will provide reasonable assistance through appropriate technical and organizational measures to help\n    Customer respond to Data Subject Requests.\n  source: https://umami.is/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell or share personal information in the future belonging to website visitors, users, and other\n    consumers.\n"
source_yaml_url: https://artifacts.apis.io/umami/privacy/umami-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from Umami's own page on 2026-11-10.
synthetic: false
tags:
- Cookieless Tracking
- Open Source
- Privacy
- Web Analytics
- Website Analytics
- Product Analytics
- Event Tracking
- Self-Hosted
- GDPR
- Session Replay
- Heatmaps
- Marketing Attribution
---
