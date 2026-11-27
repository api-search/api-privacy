---
api_specs:
- filename: chikoh-com-contest-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Contest Intelligence API
  slug: chikoh-com-contest-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-contest-intelligence-api-openapi.yml
- filename: chikoh-com-entertainment-api-openapi.yml
  format: yaml
  label: Chikoh Entertainment API
  slug: chikoh-com-entertainment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-entertainment-api-openapi.yml
- filename: chikoh-com-entertainment-predictions-api-openapi.yml
  format: yaml
  label: Chikoh Entertainment Predictions API
  slug: chikoh-com-entertainment-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-entertainment-predictions-api-openapi.yml
- filename: chikoh-com-market-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Market Intelligence API
  slug: chikoh-com-market-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-market-intelligence-api-openapi.yml
- filename: chikoh-com-player-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Player Intelligence API
  slug: chikoh-com-player-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-player-intelligence-api-openapi.yml
- filename: chikoh-com-strategic-intelligence-api-openapi.yml
  format: yaml
  label: Chikoh Strategic Intelligence API
  slug: chikoh-com-strategic-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikoh-com/openapi/chikoh-com-strategic-intelligence-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Email address, name, password'
  - category: contact
    text: 'Alerts: Your phone number if you turn on SMS or WhatsApp alerts, and your Discord id if you connect Discord'
  - category: financial
    text: 'Payment Information: Billing details processed through Stripe (we do not store full payment card details)'
  - category: location
    text: 'Location Data: Your country and, in the US, your state, as reported by Cloudflare from your IP address'
  - category: behavioral
    text: 'Usage Data: Requests to our servers (pages and features used) in server logs, and page-view and click totals that carry no identifier'
  - category: device
    text: 'Device Information: IP address, browser type, operating system, device identifiers'
  - category: communication
    text: 'Communications: Messages sent through our AI chat feature, files and screenshots you upload (for example a roster screenshot), and support messages'
  deletion:
    route: Self-service deletion in Settings
    text: You can download a copy of your data (a JSON file) and delete your account yourself, in Settings, at any time — no request to us is needed.
  dpa:
    available: true
    text: For data processing terms, see our Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Provide and maintain the Service
  - purpose: Generate AI-powered recommendations
    text: Generate AI-powered recommendations and insights
  - purpose: Process payments
    text: Process payments and manage subscriptions
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud or abuse
  - purpose: Marketing communications
    text: Send marketing communications (with your consent)
  residency:
  - region: EU (Frankfurt)
    text: our database is operated by Supabase in the EU (Frankfurt)
  - region: Germany
    text: Our servers are operated by Hetzner Online GmbH in Germany, behind Cloudflare
  retention:
  - period: Retained while your account is active
    scope: Account data
    text: 'Account data: Retained while your account is active.'
  - period: null
    scope: Account deletion
    text: Copies in our database provider's backups are removed when those backups expire, within 7 days
  - period: 90 days
    scope: Page-view and click totals
    text: 'Page-view and click totals: Daily counts with no identifier, deleted after 90 days'
  - period: Kept while your account exists
    scope: AI chats
    text: 'AI chats: Kept while your account exists so you can see your history; deleted with your account'
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal information'
  - right: Correction
    text: 'Correction: Update or correct inaccurate information'
  - right: Deletion
    text: 'Deletion: Request deletion of your account and data'
  - right: Data Portability
    text: 'Data Portability: Request your data in a portable format (JSON or CSV)'
  - right: Object to Processing
    text: 'Object to Processing: Object to processing based on legitimate interests'
  - right: Restrict Processing
    text: 'Restrict Processing: Request that we limit how we use your data'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information and do not share it for cross-context behavioral advertising.
  subprocessors:
    text: Each one, what it receives and where it is located is listed on our subprocessors page
    url: https://chikoh.com/legal/privacy
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) for transfers outside the EU/EEA where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chikoh
provenance_date: '2026-11-09'
provider_name: Chikoh
provider_slug: chikoh-com
slug: chikoh-com-privacy-policy
source_date: '2026-11-09'
source_filename: chikoh-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chikoh.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chikoh\naid: chikoh-com\nurl: https://chikoh.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Email address, name, password'\n- category: contact\n  text: 'Alerts: Your phone number if you turn on SMS or WhatsApp alerts, and your Discord id if you connect Discord'\n- category: financial\n  text: 'Payment Information: Billing details processed through Stripe (we do not store full payment card details)'\n- category: location\n  text: 'Location Data: Your country and, in the US, your state, as reported\
  \ by Cloudflare from your IP address'\n- category: behavioral\n  text: 'Usage Data: Requests to our servers (pages and features used) in server logs, and page-view and click totals\n    that carry no identifier'\n- category: device\n  text: 'Device Information: IP address, browser type, operating system, device identifiers'\n- category: communication\n  text: 'Communications: Messages sent through our AI chat feature, files and screenshots you upload (for example\n    a roster screenshot), and support messages'\npurposes:\n- purpose: Provide and maintain the Service\n  text: Provide and maintain the Service\n- purpose: Generate AI-powered recommendations\n  text: Generate AI-powered recommendations and insights\n- purpose: Process payments\n  text: Process payments and manage subscriptions\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud or abuse\n- purpose: Marketing communications\n  text: Send marketing communications (with your consent)\nretention:\n- scope:\
  \ Account data\n  period: Retained while your account is active\n  text: 'Account data: Retained while your account is active.'\n- scope: Account deletion\n  period: null\n  text: Copies in our database provider's backups are removed when those backups expire, within 7 days\n- scope: Page-view and click totals\n  period: 90 days\n  text: 'Page-view and click totals: Daily counts with no identifier, deleted after 90 days'\n- scope: AI chats\n  period: Kept while your account exists\n  text: 'AI chats: Kept while your account exists so you can see your history; deleted with your account'\nresidency:\n- region: EU (Frankfurt)\n  text: our database is operated by Supabase in the EU (Frankfurt)\n- region: Germany\n  text: Our servers are operated by Hetzner Online GmbH in Germany, behind Cloudflare\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) for transfers outside the EU/EEA where applicable\nsubprocessors:\n  url: https://chikoh.com/legal/privacy\n  text: Each\
  \ one, what it receives and where it is located is listed on our subprocessors page\ndpa:\n  available: true\n  url: null\n  text: For data processing terms, see our Data Processing Agreement\ndeletion:\n  route: Self-service deletion in Settings\n  text: You can download a copy of your data (a JSON file) and delete your account yourself, in Settings, at any\n    time — no request to us is needed.\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal information'\n- right: Correction\n  text: 'Correction: Update or correct inaccurate information'\n- right: Deletion\n  text: 'Deletion: Request deletion of your account and data'\n- right: Data Portability\n  text: 'Data Portability: Request your data in a portable format (JSON or CSV)'\n- right: Object to Processing\n  text: 'Object to Processing: Object to processing based on legitimate interests'\n- right: Restrict Processing\n  text: 'Restrict Processing: Request that we limit how we use your data'\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell your personal information and do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/chikoh-com/privacy/chikoh-com-privacy-policy.yml
stated_fields:
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
summary_line: 29 quoted statements, read from Chikoh's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fantasy Sports
- Sports Analytics
- Reality TV
- Predictions
- Gaming
- AI Agents
- MCP
---
