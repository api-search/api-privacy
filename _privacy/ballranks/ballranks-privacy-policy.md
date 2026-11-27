---
api_specs:
- filename: ballranks-rankings-and-projections-api-openapi.yml
  format: yaml
  label: Ball Ranks API
  slug: ballranks-rankings-and-projections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ballranks/openapi/ballranks-rankings-and-projections-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and sign-in information. If you create an account with email and password, Supabase Auth processes your email address, password credential, account identifier, email-confirmation status, and authentication records.
  - category: contact
    text: Customer support. Our tawk.to support widget processes messages, replies, timestamps, any contact details you provide, and technical information such as your IP address, browser, and device to deliver support and let us follow up.
  - category: financial
    text: Ball Ranks does not receive your full card number.
  - category: device
    text: Vercel Web Analytics records page views and aggregated information such as the page visited, referrer, approximate location, device type, operating system, browser, and event time.
  - category: behavioral
    text: Landing-page testing. On the homepage and Premium landing page, we store a random visit identifier, the page variation shown, visible time on the page, and clicks on the main rankings, chat, and Premium actions.
  - category: communication
    text: BallChat information. We store conversation titles, your messages, BallChat responses, relevant tool results, timestamps, and the number of free messages used for the current UTC day.
  deletion:
    route: email help@ballranks.com from the address connected to your account
    text: To request deletion of the associated account data, email help@ballranks.com from the address connected to your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate accounts
    text: Authenticate accounts, maintain signed-in sessions, and support password confirmation and reset.
  - purpose: Process Premium purchases
    text: Process Premium purchases, provide season access, manage billing, and handle refunds or disputes.
  - purpose: Measure advertising performance
    text: Measure advertising performance and attribute defined actions to Ball Ranks ads.
  - purpose: Security and legal compliance
    text: Comply with law, enforce our agreements, and investigate fraud, abuse, or security incidents.
  retention:
  - period: while your account remains active
    scope: Account records and chat conversations
    text: Account records, API-key metadata, saved rosters, watch lists, chat conversations, and the current daily usage record are retained while your account remains active or until you ask us to delete them, unless a longer period is required for legal, security, or dispute-resolution purposes.
  - period: within 48 hours
    scope: Rate-limit counters
    text: Rate-limit counters are targeted for deletion within 48 hours.
  - period: 13 months
    scope: Anonymous landing-page testing records
    text: Anonymous landing-page testing records are deleted after 13 months.
  - period: 30 days
    scope: Anthropic commercial API inputs
    text: standard API inputs and outputs are deleted from its systems within 30 days, subject to exceptions for legal obligations and usage-policy enforcement.
  rights:
  - right: access, correct, delete, or obtain a copy
    text: Depending on where you live, you may have rights to access, correct, delete, or obtain a copy of personal information; object to or restrict certain processing; withdraw consent; or appeal our response.
  - right: complain to data-protection authority
    text: You may also have the right to complain to your local data-protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information. We do not disclose personal information for cross-context behavioral advertising or targeted advertising, and we do not use data brokers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Ball Ranks and its service providers may process information in the United States and other countries that may have different data-protection laws from your home country. Where required, we rely on contractual and other lawful safeguards for those transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ball Ranks
provenance_date: '2026-11-09'
provider_name: Ball Ranks
provider_slug: ballranks
slug: ballranks-privacy-policy
source_date: '2026-11-09'
source_filename: ballranks-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ballranks.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ball Ranks\naid: ballranks\nurl: https://ballranks.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and sign-in information. If you create an account with email and password, Supabase Auth processes\n    your email address, password credential, account identifier, email-confirmation status, and authentication records.\n- category: contact\n  text: Customer support. Our tawk.to support widget processes messages, replies, timestamps, any contact details\n    you provide, and technical information such as your IP address,\
  \ browser, and device to deliver support and let\n    us follow up.\n- category: financial\n  text: Ball Ranks does not receive your full card number.\n- category: device\n  text: Vercel Web Analytics records page views and aggregated information such as the page visited, referrer, approximate\n    location, device type, operating system, browser, and event time.\n- category: behavioral\n  text: Landing-page testing. On the homepage and Premium landing page, we store a random visit identifier, the\n    page variation shown, visible time on the page, and clicks on the main rankings, chat, and Premium actions.\n- category: communication\n  text: BallChat information. We store conversation titles, your messages, BallChat responses, relevant tool results,\n    timestamps, and the number of free messages used for the current UTC day.\npurposes:\n- purpose: Authenticate accounts\n  text: Authenticate accounts, maintain signed-in sessions, and support password confirmation and reset.\n- purpose:\
  \ Process Premium purchases\n  text: Process Premium purchases, provide season access, manage billing, and handle refunds or disputes.\n- purpose: Measure advertising performance\n  text: Measure advertising performance and attribute defined actions to Ball Ranks ads.\n- purpose: Security and legal compliance\n  text: Comply with law, enforce our agreements, and investigate fraud, abuse, or security incidents.\nretention:\n- scope: Account records and chat conversations\n  period: while your account remains active\n  text: Account records, API-key metadata, saved rosters, watch lists, chat conversations, and the current daily\n    usage record are retained while your account remains active or until you ask us to delete them, unless a longer\n    period is required for legal, security, or dispute-resolution purposes.\n- scope: Rate-limit counters\n  period: within 48 hours\n  text: Rate-limit counters are targeted for deletion within 48 hours.\n- scope: Anonymous landing-page testing records\n\
  \  period: 13 months\n  text: Anonymous landing-page testing records are deleted after 13 months.\n- scope: Anthropic commercial API inputs\n  period: 30 days\n  text: standard API inputs and outputs are deleted from its systems within 30 days, subject to exceptions for legal\n    obligations and usage-policy enforcement.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Ball Ranks and its service providers may process information in the United States and other countries that\n    may have different data-protection laws from your home country. Where required, we rely on contractual and other\n    lawful safeguards for those transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email help@ballranks.com from the address connected to your account\n  text: To request deletion of the associated account data, email help@ballranks.com from the address connected\n    to your account.\nrights:\n- right: access, correct,\
  \ delete, or obtain a copy\n  text: Depending on where you live, you may have rights to access, correct, delete, or obtain a copy of personal\n    information; object to or restrict certain processing; withdraw consent; or appeal our response.\n- right: complain to data-protection authority\n  text: You may also have the right to complain to your local data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information. We do not disclose personal information for cross-context behavioral\n    advertising or targeted advertising, and we do not use data brokers.\n"
source_yaml_url: https://artifacts.apis.io/ballranks/privacy/ballranks-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Ball Ranks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fantasy Sports
- Artificial Intelligence
- Rankings
- Projections
---
