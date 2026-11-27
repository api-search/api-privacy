---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, password (stored as a hash by our authentication provider)
  - category: contact
    text: billing email
  - category: financial
    text: We receive your plan, billing status, billing email, and transaction history.
  - category: location
    text: approximate location derived from IP
  - category: behavioral
    text: pages viewed, features used, clicks, referring URLs and campaign parameters
  - category: device
    text: browser and device type
  - category: communication
    text: We keep records of your support conversations, meetings you book with us, feedback, and email preferences.
  - category: professional
    text: we may use your email domain to look up public information about your company
  deletion:
    route: Account deletion requests by email to legal@dreambase.com, processed within 30 days; manual deletion of connections, datasets, dashboards and metrics in the app
    text: 'Account deletion requests: processed within 30 days of your request to legal@dreambase.com'
  dpa:
    available: true
    text: A Data Processing Agreement is available on request.
    url: null
  purposes:
  - purpose: provide and secure the Service
    text: To provide, operate, and secure the Service, including running queries, computing metrics, detecting issues, and sending the alerts you configure
  - purpose: AI-assisted answers
    text: To generate AI-assisted answers, SQL, datasets, dashboards, insights, and health checks for your workspace
  - purpose: payments
    text: To process payments, manage trials and subscriptions, and enforce plan limits
  - purpose: product improvement
    text: To understand usage, fix bugs, and improve the Service
  - purpose: marketing
    text: To send product updates and marketing, which you can opt out of at any time
  residency:
  - region: United States
    text: Dreambase is based in the United States, and our providers may process information in the United States and other countries.
  retention:
  - period: as long as your account or workspace is active, or until you delete them
    scope: Account and workspace data, saved datasets, dashboards, metrics, and chats
    text: for as long as your account or workspace is active, or until you delete them
  - period: 7 days
    scope: Temporary chat datasets
    text: 'Temporary chat datasets: deleted automatically after 7 days'
  - period: 14 days
    scope: Observability minute-level metrics and log signals
    text: minute-level metrics and detailed log signals for 14 days
  - period: null
    scope: Billing records
    text: 'Billing records: kept as required for tax and accounting purposes'
  - period: at least 90 days
    scope: Encrypted backups
    text: encrypted backups are retained for at least 90 days
  rights:
  - right: access, correct, delete, export
    text: you may have the right to access, correct, delete, or export your personal information
  - right: object or restrict processing
    text: to object to or restrict certain processing, to withdraw consent
  - right: non-discrimination
    text: to not be discriminated against for exercising these rights
  - right: complain to data protection authority
    text: You may also complain to your local data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not use Customer Data to train AI models, whether our own or third parties'.
  subprocessors:
    text: These include Supabase (application database, authentication, storage, and encrypted secrets), Vercel (hosting and compute), OpenAI, Google, and Anthropic (AI models), Polar (billing), Resend (email), PostHog and Segment (product analytics and error tracking), Intercom (in-app support), Cal.com (scheduling), Slack (internal notifications and alerts you set up), and logo.dev (company logos).
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dreambase
provenance_date: '2026-11-09'
provider_name: Dreambase
provider_slug: dreambase
slug: dreambase-privacy-policy
source_date: '2026-11-09'
source_filename: dreambase-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dreambase.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dreambase\naid: dreambase\nurl: https://dreambase.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, password (stored as a hash by our authentication provider)\n- category: contact\n  text: billing email\n- category: financial\n  text: We receive your plan, billing status, billing email, and transaction history.\n- category: location\n  text: approximate location derived from IP\n- category: behavioral\n  text: pages viewed, features used, clicks, referring URLs and campaign parameters\n\
  - category: device\n  text: browser and device type\n- category: communication\n  text: We keep records of your support conversations, meetings you book with us, feedback, and email preferences.\n- category: professional\n  text: we may use your email domain to look up public information about your company\npurposes:\n- purpose: provide and secure the Service\n  text: To provide, operate, and secure the Service, including running queries, computing metrics, detecting issues,\n    and sending the alerts you configure\n- purpose: AI-assisted answers\n  text: To generate AI-assisted answers, SQL, datasets, dashboards, insights, and health checks for your workspace\n- purpose: payments\n  text: To process payments, manage trials and subscriptions, and enforce plan limits\n- purpose: product improvement\n  text: To understand usage, fix bugs, and improve the Service\n- purpose: marketing\n  text: To send product updates and marketing, which you can opt out of at any time\nretention:\n- scope:\
  \ Account and workspace data, saved datasets, dashboards, metrics, and chats\n  period: as long as your account or workspace is active, or until you delete them\n  text: for as long as your account or workspace is active, or until you delete them\n- scope: Temporary chat datasets\n  period: 7 days\n  text: 'Temporary chat datasets: deleted automatically after 7 days'\n- scope: Observability minute-level metrics and log signals\n  period: 14 days\n  text: minute-level metrics and detailed log signals for 14 days\n- scope: Billing records\n  period: null\n  text: 'Billing records: kept as required for tax and accounting purposes'\n- scope: Encrypted backups\n  period: at least 90 days\n  text: encrypted backups are retained for at least 90 days\nresidency:\n- region: United States\n  text: Dreambase is based in the United States, and our providers may process information in the United States\n    and other countries.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards\
  \ such as the European Commission's Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: These include Supabase (application database, authentication, storage, and encrypted secrets), Vercel (hosting\n    and compute), OpenAI, Google, and Anthropic (AI models), Polar (billing), Resend (email), PostHog and Segment\n    (product analytics and error tracking), Intercom (in-app support), Cal.com (scheduling), Slack (internal notifications\n    and alerts you set up), and logo.dev (company logos).\ndpa:\n  available: true\n  url: null\n  text: A Data Processing Agreement is available on request.\ndeletion:\n  route: Account deletion requests by email to legal@dreambase.com, processed within 30 days; manual deletion of\n    connections, datasets, dashboards and metrics in the app\n  text: 'Account deletion requests: processed within 30 days of your request to legal@dreambase.com'\nrights:\n- right: access, correct, delete, export\n  text: you may have the right to access, correct,\
  \ delete, or export your personal information\n- right: object or restrict processing\n  text: to object to or restrict certain processing, to withdraw consent\n- right: non-discrimination\n  text: to not be discriminated against for exercising these rights\n- right: complain to data protection authority\n  text: You may also complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not use Customer Data to train AI models, whether our\n    own or third parties'.\n"
source_yaml_url: https://artifacts.apis.io/dreambase/privacy/dreambase-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Dreambase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Business Intelligence
- Supabase
- PostgreSQL
- Dashboards
- Data
- Artificial Intelligence
- Reporting
---
