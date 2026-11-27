---
api_specs:
- filename: onlinecompiler-io-account-api-openapi.yml
  format: yaml
  label: onlinecompiler-io Account API
  slug: onlinecompiler-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onlinecompiler-io/openapi/onlinecompiler-io-account-api-openapi.yml
- filename: onlinecompiler-io-judge-api-openapi.yml
  format: yaml
  label: onlinecompiler-io Judge API
  slug: onlinecompiler-io-judge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onlinecompiler-io/openapi/onlinecompiler-io-judge-api-openapi.yml
- filename: onlinecompiler-io-reference-api-openapi.yml
  format: yaml
  label: onlinecompiler-io Reference API
  slug: onlinecompiler-io-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onlinecompiler-io/openapi/onlinecompiler-io-reference-api-openapi.yml
- filename: onlinecompiler-io-run-api-openapi.yml
  format: yaml
  label: onlinecompiler-io Run API
  slug: onlinecompiler-io-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onlinecompiler-io/openapi/onlinecompiler-io-run-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Your email address, and your name when you sign in with Google.'
  - category: contact
    text: Name, email, and message content when you use our contact form, kept for two years.
  - category: device
    text: IP address, browser type, timestamps, and API usage metrics for analytics and abuse prevention.
  - category: location
    text: 'the country we look up from it: a run''s address for 365 days'
  - category: financial
    text: We store your Stripe customer and subscription IDs, your plan and its status.
  - category: other
    text: Source code, input data, and compiler selection submitted for execution.
  deletion:
    route: Account deletion request or account deletion
    text: When you ask us to delete your account, we delete its execution history with it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Execute code and deliver results
    text: To execute code and deliver results via our API and WebSocket services.
  - purpose: Service health and abuse prevention
    text: To monitor service health, prevent abuse, and enforce rate limits.
  - purpose: Improve platform
    text: To improve our platform based on aggregate usage patterns.
  - purpose: Account news
    text: To send account holders occasional news about the service.
  residency:
  - region: European Union
    text: Servers in the European Union that run the service and its database.
  - region: India
    text: 'Some providers handle data elsewhere: Amazon Web Services SES in India, and Stripe and Google in the United States.'
  - region: United States
    text: Stripe and Google in the United States.
  retention:
  - period: 365 days
    scope: Execution history
    text: Execution history keeps each run's code, input, output, errors and IP address for 365 days
  - period: two years
    scope: Contact form messages
    text: Name, email, and message content when you use our contact form, kept for two years.
  - period: 30 days
    scope: Sign-in link records
    text: Records of the sign-in links we email you (your email and IP address) are deleted after 30 days
  - period: 30 days
    scope: Database backups
    text: Database backups are kept on the same servers in the European Union for 30 days, then deleted.
  - period: 60 days
    scope: Returned program files
    text: Files returned by a program are kept for 60 days on our server
  - period: 90 days
    scope: Free plan submissions
    text: 90 days on Free, 1 year on Starter and 2 years on Pro.
  - period: null
    scope: Account data
    text: Account data is kept while your account is active.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correction or deletion
    text: Request correction or deletion of your data.
  - right: Portability
    text: Ask for a copy of your execution history, and of the data you gave us, in a machine-readable format you can take elsewhere.
  - right: Objection
    text: Object to uses based on our legitimate interests, described above.
  - right: Withdraw consent
    text: Withdraw consent you gave us at any time, for the future.
  - right: Complaint
    text: Complain to a data protection authority, such as the one where you live or work
  role:
    text: which is responsible for the personal information described here
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information.
  subprocessors:
    text: Each provider, what it does and where, is on the sub-processors page
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the providers' data processing terms, which include the EU Standard Contractual Clauses (and the UK addendum to them)
  - mechanism: DPF
    text: or on their certification under the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: onlinecompiler-io
provenance_date: '2026-11-10'
provider_name: onlinecompiler-io
provider_slug: onlinecompiler-io
slug: onlinecompiler-io-privacy-policy
source_date: '2026-11-10'
source_filename: onlinecompiler-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://onlinecompiler.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: onlinecompiler-io\naid: onlinecompiler-io\nurl: https://onlinecompiler.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: which is responsible for the personal information described here\ndata_categories:\n- category: identifying\n  text: 'Account Information: Your email address, and your name when you sign in with Google.'\n- category: contact\n  text: Name, email, and message content when you use our contact form, kept for two years.\n- category: device\n  text: IP address, browser type, timestamps, and API usage metrics for analytics and abuse prevention.\n- category: location\n\
  \  text: 'the country we look up from it: a run''s address for 365 days'\n- category: financial\n  text: We store your Stripe customer and subscription IDs, your plan and its status.\n- category: other\n  text: Source code, input data, and compiler selection submitted for execution.\npurposes:\n- purpose: Execute code and deliver results\n  text: To execute code and deliver results via our API and WebSocket services.\n- purpose: Service health and abuse prevention\n  text: To monitor service health, prevent abuse, and enforce rate limits.\n- purpose: Improve platform\n  text: To improve our platform based on aggregate usage patterns.\n- purpose: Account news\n  text: To send account holders occasional news about the service.\nretention:\n- scope: Execution history\n  period: 365 days\n  text: Execution history keeps each run's code, input, output, errors and IP address for 365 days\n- scope: Contact form messages\n  period: two years\n  text: Name, email, and message content when you use\
  \ our contact form, kept for two years.\n- scope: Sign-in link records\n  period: 30 days\n  text: Records of the sign-in links we email you (your email and IP address) are deleted after 30 days\n- scope: Database backups\n  period: 30 days\n  text: Database backups are kept on the same servers in the European Union for 30 days, then deleted.\n- scope: Returned program files\n  period: 60 days\n  text: Files returned by a program are kept for 60 days on our server\n- scope: Free plan submissions\n  period: 90 days\n  text: 90 days on Free, 1 year on Starter and 2 years on Pro.\n- scope: Account data\n  period: null\n  text: Account data is kept while your account is active.\nresidency:\n- region: European Union\n  text: Servers in the European Union that run the service and its database.\n- region: India\n  text: 'Some providers handle data elsewhere: Amazon Web Services SES in India, and Stripe and Google in the United\n    States.'\n- region: United States\n  text: Stripe and Google\
  \ in the United States.\ntransfers:\n- mechanism: SCC\n  text: we rely on the providers' data processing terms, which include the EU Standard Contractual Clauses (and\n    the UK addendum to them)\n- mechanism: DPF\n  text: or on their certification under the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: Each provider, what it does and where, is on the sub-processors page\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion request or account deletion\n  text: When you ask us to delete your account, we delete its execution history with it.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correction or deletion\n  text: Request correction or deletion of your data.\n- right: Portability\n  text: Ask for a copy of your execution history, and of the data you gave us, in a machine-readable format you\n    can take elsewhere.\n- right: Objection\n  text: Object to uses based on our legitimate\
  \ interests, described above.\n- right: Withdraw consent\n  text: Withdraw consent you gave us at any time, for the future.\n- right: Complaint\n  text: Complain to a data protection authority, such as the one where you live or work\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information.\n"
source_yaml_url: https://artifacts.apis.io/onlinecompiler-io/privacy/onlinecompiler-io-privacy-policy.yml
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
summary_line: 32 quoted statements, read from onlinecompiler-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code Execution
- Developer Tools
- Education
- Artificial Intelligence
---
