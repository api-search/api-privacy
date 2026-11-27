---
api_specs:
- filename: openhandle-instagram-api-openapi.yml
  format: yaml
  label: Openhandle Instagram API
  slug: openhandle-instagram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-instagram-api-openapi.yml
- filename: openhandle-reddit-api-openapi.yml
  format: yaml
  label: Openhandle Reddit API
  slug: openhandle-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-reddit-api-openapi.yml
- filename: openhandle-test-data-api-openapi.yml
  format: yaml
  label: Openhandle Test Data API
  slug: openhandle-test-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-test-data-api-openapi.yml
- filename: openhandle-tiktok-api-openapi.yml
  format: yaml
  label: Openhandle Tiktok API
  slug: openhandle-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-tiktok-api-openapi.yml
- filename: openhandle-twitter-api-openapi.yml
  format: yaml
  label: Openhandle Twitter API
  slug: openhandle-twitter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-twitter-api-openapi.yml
- filename: openhandle-utilities-api-openapi.yml
  format: yaml
  label: Openhandle Utilities API
  slug: openhandle-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-utilities-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and a hashed password.
  - category: financial
    text: We store billing status, invoices, spend settings, and usage-based charges. We never store card numbers.
  - category: device
    text: A session cookie for dashboard sign-in, and two first-party cookies that last up to 30 days
  - category: communication
    text: Emails you send us.
  - category: behavioral
    text: we remember the referral code or the campaign, and the first page you saw.
  - category: other
    text: Public profile fields, public post content and metrics, public comments and their authors, and public follower lists.
  deletion:
    route: Delete the account; or email hello@openhandle.dev for social media profile removal
    text: After you delete the account, we delete or anonymize it within 30 days, unless law requires us to keep it longer.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the API, MCP server and dashboard
    text: Providing the API, the MCP server, and the dashboard Contract (art. 6(1)(b))
  - purpose: Billing and invoicing
    text: Billing and invoicing Contract; legal obligation (art. 6(1)(c))
  - purpose: Abuse prevention and security
    text: Abuse prevention, rate limiting, security Legitimate interest (art. 6(1)(f))
  - purpose: Product improvement from aggregated usage
    text: Product improvement from aggregated usage Legitimate interest
  - purpose: Analytics, research and monitoring by customers of public data
    text: giving programmatic access to information the person has made public, for purposes such as analytics, research, and monitoring by our customers.
  retention:
  - period: 30 days
    scope: Account data
    text: After you delete the account, we delete or anonymize it within 30 days, unless law requires us to keep it longer.
  - period: 90 days
    scope: Request logs
    text: 'Request logs: 90 days.'
  - period: 30 days
    scope: Connected agent refresh tokens
    text: Refresh tokens rotate and expire after 30 days.
  - period: 7 years
    scope: Invoices and billing records
    text: 'Invoices and billing records: 7 years, as tax law requires.'
  - period: 31 days
    scope: Cached public social media answers
    text: We cache answers for up to 31 days so repeat reads are cheaper and faster.
  - period: one year
    scope: Identity history
    text: We keep it for one year after we last saw the alias.
  rights:
  - right: access
    text: Under the GDPR you can ask for access, correction, deletion, restriction, and portability of your data.
  - right: object
    text: You can object to processing based on legitimate interest.
  - right: complaint
    text: You can also file a complaint with your supervisory authority. In the Netherlands this is the Autoriteit Persoonsgegevens.
  - right: remove public profile from service
    text: If you own an account and do not want it readable through Openhandle, email hello@openhandle.dev with the profile link.
  role:
    text: We are the controller for the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: 'We share personal data only with processors we need to run the service: — Stripe . payment processing and invoices. — Google . sign-in, if you choose to sign in with Google. — Cloud providers . hosting, databases, encrypted backups, and media delivery.'
    url: null
  transfers:
  - mechanism: adequacy
    text: Where a processor is outside the EEA, transfers rely on adequacy decisions or standard contractual clauses.
  - mechanism: SCC
    text: Where a processor is outside the EEA, transfers rely on adequacy decisions or standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Openhandle
provenance_date: '2026-11-10'
provider_name: Openhandle
provider_slug: openhandle
slug: openhandle-privacy-policy
source_date: '2026-11-10'
source_filename: openhandle-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://openhandle.dev/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Openhandle\naid: openhandle\nurl: https://openhandle.dev/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller for the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: Name, email address, and a hashed password.\n- category: financial\n  text: We store billing status, invoices, spend settings, and usage-based charges. We never store card numbers.\n- category: device\n  text: A session cookie for dashboard sign-in, and two first-party cookies that last up to 30 days\n- category: communication\n  text: Emails you\
  \ send us.\n- category: behavioral\n  text: we remember the referral code or the campaign, and the first page you saw.\n- category: other\n  text: Public profile fields, public post content and metrics, public comments and their authors, and public follower\n    lists.\npurposes:\n- purpose: Providing the API, MCP server and dashboard\n  text: Providing the API, the MCP server, and the dashboard Contract (art. 6(1)(b))\n- purpose: Billing and invoicing\n  text: Billing and invoicing Contract; legal obligation (art. 6(1)(c))\n- purpose: Abuse prevention and security\n  text: Abuse prevention, rate limiting, security Legitimate interest (art. 6(1)(f))\n- purpose: Product improvement from aggregated usage\n  text: Product improvement from aggregated usage Legitimate interest\n- purpose: Analytics, research and monitoring by customers of public data\n  text: giving programmatic access to information the person has made public, for purposes such as analytics, research,\n    and monitoring by\
  \ our customers.\nretention:\n- scope: Account data\n  period: 30 days\n  text: After you delete the account, we delete or anonymize it within 30 days, unless law requires us to keep it\n    longer.\n- scope: Request logs\n  period: 90 days\n  text: 'Request logs: 90 days.'\n- scope: Connected agent refresh tokens\n  period: 30 days\n  text: Refresh tokens rotate and expire after 30 days.\n- scope: Invoices and billing records\n  period: 7 years\n  text: 'Invoices and billing records: 7 years, as tax law requires.'\n- scope: Cached public social media answers\n  period: 31 days\n  text: We cache answers for up to 31 days so repeat reads are cheaper and faster.\n- scope: Identity history\n  period: one year\n  text: We keep it for one year after we last saw the alias.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where a processor is outside the EEA, transfers rely on adequacy decisions or standard contractual clauses.\n- mechanism: SCC\n  text: Where a processor is outside\
  \ the EEA, transfers rely on adequacy decisions or standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'We share personal data only with processors we need to run the service: — Stripe . payment processing and\n    invoices. — Google . sign-in, if you choose to sign in with Google. — Cloud providers . hosting, databases,\n    encrypted backups, and media delivery.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete the account; or email hello@openhandle.dev for social media profile removal\n  text: After you delete the account, we delete or anonymize it within 30 days, unless law requires us to keep it\n    longer.\nrights:\n- right: access\n  text: Under the GDPR you can ask for access, correction, deletion, restriction, and portability of your data.\n- right: object\n  text: You can object to processing based on legitimate interest.\n- right: complaint\n  text: You can also file a complaint with your supervisory authority. In the Netherlands\
  \ this is the Autoriteit\n    Persoonsgegevens.\n- right: remove public profile from service\n  text: If you own an account and do not want it readable through Openhandle, email hello@openhandle.dev with the\n    profile link.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/openhandle/privacy/openhandle-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Openhandle's own page on 2026-11-10.
synthetic: false
tags:
- Social Data
- Instagram
- TikTok
- Twitter
- Reddit
- Public Data
- social-media-api
- MCP
- creator-analytics
- Social Listening
---
