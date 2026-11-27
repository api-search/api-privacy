---
api_specs:
- filename: editsquare-projects-api-openapi.yml
  format: yaml
  label: Edit Square Projects API
  slug: editsquare-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-projects-api-openapi.yml
- filename: editsquare-renders-api-openapi.yml
  format: yaml
  label: Edit Square Renders API
  slug: editsquare-renders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-renders-api-openapi.yml
- filename: editsquare-teams-api-openapi.yml
  format: yaml
  label: Edit Square Teams API
  slug: editsquare-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-teams-api-openapi.yml
- filename: editsquare-templates-api-openapi.yml
  format: yaml
  label: Edit Square Templates API
  slug: editsquare-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-templates-api-openapi.yml
- filename: editsquare-users-api-openapi.yml
  format: yaml
  label: Edit Square Users API
  slug: editsquare-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/editsquare/openapi/editsquare-users-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, and profile picture if you add one
  - category: financial
    text: We receive your billing name, email, country, the plan and add-ons you have bought, invoice history, and a token that identifies your payment method
  - category: location
    text: rough location derived from IP address
  - category: behavioral
    text: the pages and features you use, the actions you take in the editor (for example “export started”)
  - category: device
    text: technical details such as browser type, screen size, operating system
  - category: communication
    text: When you email us, contact support, or reply to one of our emails, we keep the correspondence.
  - category: other
    text: This may include personal data about you or other people, such as faces, voices and names that appear in your videos.
  deletion:
    route: Delete account or projects from the dashboard, or email hello@editsquare.com
    text: 'Much of this you can do yourself: you can update your details, export your projects, and delete projects and your account from the dashboard.'
  dpa:
    available: null
    text: That processing is governed by the Data Processing Addendum in our Terms of Service .
    url: null
  purposes:
  - purpose: Providing the service
    text: 'Providing the service: running the editor, storing and syncing projects, rendering, teams, API and player'
  - purpose: Product analytics
    text: Understanding how the product is used, fixing bugs and improving it
  - purpose: Security and enforcement
    text: Keeping the service secure and enforcing our Terms
  residency:
  - region: European Union
    text: We use PostHog, hosted in the EU, to understand how the product is used.
  - region: European Union (France)
    text: Scaleway Cloud render workers European Union (France)
  retention:
  - period: 30 days
    scope: Account data
    text: When you delete your account, or ask us to, we delete it within 30 days
  - period: 24 months
    scope: Analytics
    text: 'Analytics: 24 months, after which data is deleted or anonymised.'
  - period: six years
    scope: Billing records
    text: 'Billing records: six years after the end of the financial year they relate to, as required by UK tax law.'
  - period: two years
    scope: Support correspondence
    text: 'Support correspondence: two years after the matter is closed.'
  - period: 90 days
    scope: Request and security logs
    text: 'Request and security logs: up to 90 days.'
  rights:
  - right: access
    text: access the personal data we hold about you
  - right: correct
    text: correct it if it is inaccurate
  - right: delete
    text: delete it, in some circumstances
  - right: restrict
    text: restrict how we use it, in some circumstances
  - right: object
    text: object to processing based on legitimate interests, and to direct marketing at any time
  - right: portability
    text: port data you gave us to another service in a machine-readable format
  - right: withdraw consent
    text: withdraw consent where we rely on it, without affecting processing done before you withdrew
  role:
    text: The data controller is Edit Square Ltd , company number 09971898, registered office 71-75 Shelton Street, London, United Kingdom, WC2H 9JQ.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share it with advertisers.
  subprocessors:
    text: We share personal data only with the service providers below, who process it on our behalf under contracts that require them to protect it
    url: null
  transfers:
  - mechanism: adequacy
    text: the UK’s adequacy regulations (including the UK Extension to the EU-US Data Privacy Framework, where the provider is certified)
  - mechanism: other
    text: the UK International Data Transfer Agreement or Addendum
  - mechanism: SCC
    text: the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Edit Square
provenance_date: '2026-11-09'
provider_name: Edit Square
provider_slug: editsquare
slug: editsquare-privacy-policy
source_date: '2026-11-09'
source_filename: editsquare-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://editsquare.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Edit Square\naid: editsquare\nurl: https://editsquare.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Edit Square Ltd , company number 09971898, registered office 71-75 Shelton Street,\n    London, United Kingdom, WC2H 9JQ.\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, and profile picture if you add one\n- category: financial\n  text: We receive your billing name, email, country, the plan and add-ons you have bought, invoice history, and\n    a token that identifies your payment method\n- category: location\n  text:\
  \ rough location derived from IP address\n- category: behavioral\n  text: the pages and features you use, the actions you take in the editor (for example “export started”)\n- category: device\n  text: technical details such as browser type, screen size, operating system\n- category: communication\n  text: When you email us, contact support, or reply to one of our emails, we keep the correspondence.\n- category: other\n  text: This may include personal data about you or other people, such as faces, voices and names that appear in\n    your videos.\npurposes:\n- purpose: Providing the service\n  text: 'Providing the service: running the editor, storing and syncing projects, rendering, teams, API and player'\n- purpose: Product analytics\n  text: Understanding how the product is used, fixing bugs and improving it\n- purpose: Security and enforcement\n  text: Keeping the service secure and enforcing our Terms\nretention:\n- scope: Account data\n  period: 30 days\n  text: When you delete your\
  \ account, or ask us to, we delete it within 30 days\n- scope: Analytics\n  period: 24 months\n  text: 'Analytics: 24 months, after which data is deleted or anonymised.'\n- scope: Billing records\n  period: six years\n  text: 'Billing records: six years after the end of the financial year they relate to, as required by UK tax law.'\n- scope: Support correspondence\n  period: two years\n  text: 'Support correspondence: two years after the matter is closed.'\n- scope: Request and security logs\n  period: 90 days\n  text: 'Request and security logs: up to 90 days.'\nresidency:\n- region: European Union\n  text: We use PostHog, hosted in the EU, to understand how the product is used.\n- region: European Union (France)\n  text: Scaleway Cloud render workers European Union (France)\ntransfers:\n- mechanism: adequacy\n  text: the UK’s adequacy regulations (including the UK Extension to the EU-US Data Privacy Framework, where the\n    provider is certified)\n- mechanism: other\n  text: the UK\
  \ International Data Transfer Agreement or Addendum\n- mechanism: SCC\n  text: the EU Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: We share personal data only with the service providers below, who process it on our behalf under contracts\n    that require them to protect it\ndpa:\n  available: null\n  url: null\n  text: That processing is governed by the Data Processing Addendum in our Terms of Service .\ndeletion:\n  route: Delete account or projects from the dashboard, or email hello@editsquare.com\n  text: 'Much of this you can do yourself: you can update your details, export your projects, and delete projects\n    and your account from the dashboard.'\nrights:\n- right: access\n  text: access the personal data we hold about you\n- right: correct\n  text: correct it if it is inaccurate\n- right: delete\n  text: delete it, in some circumstances\n- right: restrict\n  text: restrict how we use it, in some circumstances\n- right: object\n  text: object to processing\
  \ based on legitimate interests, and to direct marketing at any time\n- right: portability\n  text: port data you gave us to another service in a machine-readable format\n- right: withdraw consent\n  text: withdraw consent where we rely on it, without affecting processing done before you withdrew\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/editsquare/privacy/editsquare-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from Edit Square's own page on 2026-11-09.
synthetic: false
tags:
- Motion Graphics
- Video Editing
- Cloud Rendering
---
