---
api_specs:
- filename: burrow-events-api-openapi.yml
  format: yaml
  label: Burrow Events API
  slug: burrow-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/burrow/openapi/burrow-events-api-openapi.yml
- filename: burrow-mcp-api-openapi.yml
  format: yaml
  label: Burrow MCP API
  slug: burrow-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/burrow/openapi/burrow-mcp-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address Required to create an account, log in, send invoices, and deliver essential communications like updates and security alerts.
  - category: identifying
    text: Name and profile image Collected during registration or via third-party sign-in.
  - category: behavioral
    text: We collect anonymous, aggregate usage data for statistical purposes only — referral sources, top pages, visit duration, device type, country, and browser.
  - category: device
    text: No cookies are stored in the browser
  deletion:
    route: Contact us to request account deletion
    text: You may request account deletion by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: process information solely to provide the service you signed up for.
  - purpose: Build dashboards and reports
    text: This data is used to ingest events, build dashboards, and generate reports within Burrow.
  - purpose: AI insights
    text: The Scout Agent uses third-party large language model providers to process your queries and operational data in order to generate insights, summaries, and configuration recommendations.
  retention:
  - period: null
    scope: Account data
    text: We retain your information as long as your account is active and as necessary to provide the Services, comply with legal obligations, resolve disputes, and enforce our agreements.
  - period: 15 minutes
    scope: Invite token cookie
    text: a temporary invite token cookie for up to 15 minutes during sign-up when accepting an invitation
  - period: 7 days
    scope: Preference cookie
    text: a preference cookie for up to 7 days to remember your sidebar layout preference
  rights:
  - right: Access, correct, or delete
    text: You have the right to access, correct, or delete your personal data at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We promise we never sell your data — never have, never will.
  subprocessors:
    text: A complete list of sub-processors is available upon request. Contact us if you need this information for compliance purposes.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Burrow
provenance_date: '2026-11-09'
provider_name: Burrow
provider_slug: burrow
slug: burrow-privacy-policy
source_date: '2026-11-09'
source_filename: burrow-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://useburrow.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Burrow\naid: burrow\nurl: https://useburrow.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address Required to create an account, log in, send invoices, and deliver essential communications\n    like updates and security alerts.\n- category: identifying\n  text: Name and profile image Collected during registration or via third-party sign-in.\n- category: behavioral\n  text: We collect anonymous, aggregate usage data for statistical purposes only — referral sources, top pages,\n    visit duration, device type, country, and\
  \ browser.\n- category: device\n  text: No cookies are stored in the browser\npurposes:\n- purpose: Provide the service\n  text: process information solely to provide the service you signed up for.\n- purpose: Build dashboards and reports\n  text: This data is used to ingest events, build dashboards, and generate reports within Burrow.\n- purpose: AI insights\n  text: The Scout Agent uses third-party large language model providers to process your queries and operational\n    data in order to generate insights, summaries, and configuration recommendations.\nretention:\n- scope: Account data\n  period: null\n  text: We retain your information as long as your account is active and as necessary to provide the Services, comply\n    with legal obligations, resolve disputes, and enforce our agreements.\n- scope: Invite token cookie\n  period: 15 minutes\n  text: a temporary invite token cookie for up to 15 minutes during sign-up when accepting an invitation\n- scope: Preference cookie\n  period:\
  \ 7 days\n  text: a preference cookie for up to 7 days to remember your sidebar layout preference\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: A complete list of sub-processors is available upon request. Contact us if you need this information for\n    compliance purposes.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us to request account deletion\n  text: You may request account deletion by contacting us.\nrights:\n- right: Access, correct, or delete\n  text: You have the right to access, correct, or delete your personal data at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We promise we never sell your data — never have, never will.\n"
source_yaml_url: https://artifacts.apis.io/burrow/privacy/burrow-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Burrow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Reporting
- Automation
---
