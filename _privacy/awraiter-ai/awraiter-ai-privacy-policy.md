---
api_specs:
- filename: awraiter-ai-catalog-api-openapi.yml
  format: yaml
  label: AwrAiter Catalog API
  slug: awraiter-ai-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awraiter-ai/openapi/awraiter-ai-catalog-api-openapi.yml
- filename: awraiter-ai-read-api-openapi.yml
  format: yaml
  label: AwrAiter Read API
  slug: awraiter-ai-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awraiter-ai/openapi/awraiter-ai-read-api-openapi.yml
- filename: awraiter-ai-write-api-openapi.yml
  format: yaml
  label: AwrAiter Write API
  slug: awraiter-ai-write-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awraiter-ai/openapi/awraiter-ai-write-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Telegram user ID, username, first and last name, profile photo, interface language
  - category: contact
    text: Correspondence messages you send us by Telegram or email you
  - category: financial
    text: Billing plan, subscription status, renewal date, invoices, credit balance and usage
  - category: device
    text: IP address, browser and device data, session cookies, server logs and error reports
  - category: behavioral
    text: Usage analytics which pages and features you open and actions such as publishing a post or running an analysis
  - category: communication
    text: Public data of monitored sources titles, text, author names and publication dates of public news articles and public Telegram posts you add as sources for your channels
  deletion:
    route: 'In-panel: Account → Delete my account'
    text: Account → Delete my account — permanent erasure of the account and, where you are the last owner, of the team's channels, content plans, posts, reports and uploaded files.
  dpa:
    available: true
    text: A separate data processing agreement is available on request.
    url: null
  purposes:
  - purpose: Account and panel operation
    text: Creating your account, running the panel, publishing your posts, showing your statistics performance of a contract — Art. 6(1)(b)
  - purpose: Security
    text: 'Keeping the Service secure: rate limits, abuse and fraud detection, logs legitimate interest in protecting the Service and its users — Art. 6(1)(f)'
  - purpose: Product analytics
    text: 'Product analytics: seeing which features are used, so we know what to improve consent — Art. 6(1)(a)'
  - purpose: AI processing
    text: When you use a feature that writes, rewrites, translates or analyses text, the material you selected — a draft, a source article, a channel's post history or its statistics — is sent to a third-party AI provider so that it can produce the result.
  residency:
  - region: Germany (EU)
    text: Our servers and databases are in Germany.
  retention:
  - period: while the account exists
    scope: Account and content
    text: Account, team, channels, plans, posts, uploaded files while the account exists; deleted when you delete the account
  - period: 10 years
    scope: Invoices and accounting
    text: Invoices and accounting records 10 years, as required by Italian tax law
  - period: up to 12 months
    scope: Server, API and security logs
    text: Server, API and security logs up to 12 months
  - period: 90 days
    scope: Error reports
    text: Error reports (GlitchTip) 90 days
  - period: within 30 days
    scope: Backups
    text: Backups rolling, overwritten within 30 days
  - period: up to 24 months after the last message
    scope: Support correspondence
    text: Support correspondence up to 24 months after the last message
  rights:
  - right: access
    text: Under Articles 15 to 22 GDPR you may ask for access to your data, rectification, erasure, restriction, portability
  - right: withdraw consent
    text: Where processing rests on consent, you may withdraw it at any time without affecting what was done before.
  - right: object
    text: you may object to processing based on legitimate interest
  - right: export
    text: Account → Export my data — a machine-readable export of your account, team, channels, plans and posts.
  - right: complaint
    text: you may lodge a complaint with the Italian supervisory authority (Garante per la protezione dei dati personali, www.garanteprivacy.it)
  role:
    text: The data controller is Mediazione Italia S.r.l.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information and we do not share it for cross-context behavioural advertising
  subprocessors:
    text: The exact set of AI providers in use can change as we add or drop models; this table is kept current and we announce material changes on this page.
    url: null
  transfers:
  - mechanism: SCC
    text: For those transfers we rely on the European Commission's Standard Contractual Clauses, or on an adequacy decision where one applies
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AwrAiter
provenance_date: '2026-11-09'
provider_name: AwrAiter
provider_slug: awraiter-ai
slug: awraiter-ai-privacy-policy
source_date: '2026-11-09'
source_filename: awraiter-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://awraiter.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AwrAiter\naid: awraiter-ai\nurl: https://awraiter.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The data controller is Mediazione Italia S.r.l.\ndata_categories:\n- category: identifying\n  text: Telegram user ID, username, first and last name, profile photo, interface language\n- category: contact\n  text: Correspondence messages you send us by Telegram or email you\n- category: financial\n  text: Billing plan, subscription status, renewal date, invoices, credit balance and usage\n- category: device\n  text: IP address, browser and device data, session cookies, server logs and\
  \ error reports\n- category: behavioral\n  text: Usage analytics which pages and features you open and actions such as publishing a post or running an analysis\n- category: communication\n  text: Public data of monitored sources titles, text, author names and publication dates of public news articles\n    and public Telegram posts you add as sources for your channels\npurposes:\n- purpose: Account and panel operation\n  text: Creating your account, running the panel, publishing your posts, showing your statistics performance of\n    a contract — Art. 6(1)(b)\n- purpose: Security\n  text: 'Keeping the Service secure: rate limits, abuse and fraud detection, logs legitimate interest in protecting\n    the Service and its users — Art. 6(1)(f)'\n- purpose: Product analytics\n  text: 'Product analytics: seeing which features are used, so we know what to improve consent — Art. 6(1)(a)'\n- purpose: AI processing\n  text: When you use a feature that writes, rewrites, translates or analyses text,\
  \ the material you selected — a\n    draft, a source article, a channel's post history or its statistics — is sent to a third-party AI provider so\n    that it can produce the result.\nretention:\n- scope: Account and content\n  period: while the account exists\n  text: Account, team, channels, plans, posts, uploaded files while the account exists; deleted when you delete\n    the account\n- scope: Invoices and accounting\n  period: 10 years\n  text: Invoices and accounting records 10 years, as required by Italian tax law\n- scope: Server, API and security logs\n  period: up to 12 months\n  text: Server, API and security logs up to 12 months\n- scope: Error reports\n  period: 90 days\n  text: Error reports (GlitchTip) 90 days\n- scope: Backups\n  period: within 30 days\n  text: Backups rolling, overwritten within 30 days\n- scope: Support correspondence\n  period: up to 24 months after the last message\n  text: Support correspondence up to 24 months after the last message\nresidency:\n\
  - region: Germany (EU)\n  text: Our servers and databases are in Germany.\ntransfers:\n- mechanism: SCC\n  text: For those transfers we rely on the European Commission's Standard Contractual Clauses, or on an adequacy\n    decision where one applies\nsubprocessors:\n  url: null\n  text: The exact set of AI providers in use can change as we add or drop models; this table is kept current and\n    we announce material changes on this page.\ndpa:\n  available: true\n  url: null\n  text: A separate data processing agreement is available on request.\ndeletion:\n  route: 'In-panel: Account → Delete my account'\n  text: Account → Delete my account — permanent erasure of the account and, where you are the last owner, of the\n    team's channels, content plans, posts, reports and uploaded files.\nrights:\n- right: access\n  text: Under Articles 15 to 22 GDPR you may ask for access to your data, rectification, erasure, restriction, portability\n- right: withdraw consent\n  text: Where processing\
  \ rests on consent, you may withdraw it at any time without affecting what was done before.\n- right: object\n  text: you may object to processing based on legitimate interest\n- right: export\n  text: Account → Export my data — a machine-readable export of your account, team, channels, plans and posts.\n- right: complaint\n  text: you may lodge a complaint with the Italian supervisory authority (Garante per la protezione dei dati personali,\n    www.garanteprivacy.it)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information and we do not share it for cross-context behavioural advertising\n"
source_yaml_url: https://artifacts.apis.io/awraiter-ai/privacy/awraiter-ai-privacy-policy.yml
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
summary_line: 28 quoted statements, read from AwrAiter's own page on 2026-11-09.
synthetic: false
tags:
- Telegram
- Content Planning
- Analytics
- AI Integration
- Software-as-a-Service
---
