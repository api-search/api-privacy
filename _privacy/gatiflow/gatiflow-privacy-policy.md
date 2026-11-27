---
api_specs:
- filename: gatiflow-intelligence-api-openapi.yml
  format: yaml
  label: GatiFlow Intelligence API
  slug: gatiflow-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-intelligence-api-openapi.yml
- filename: gatiflow-public-api-openapi.yml
  format: yaml
  label: GatiFlow Public API
  slug: gatiflow-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-public-api-openapi.yml
- filename: gatiflow-usage-api-openapi.yml
  format: yaml
  label: GatiFlow Usage API
  slug: gatiflow-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-usage-api-openapi.yml
- filename: gatiflow-webhooks-api-openapi.yml
  format: yaml
  label: GatiFlow Webhooks API
  slug: gatiflow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-webhooks-api-openapi.yml
- filename: gatiflow-agent-api-openapi.yml
  format: yaml
  label: GatiFlow Agent API
  slug: gatiflow-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatiflow/openapi/gatiflow-agent-api-openapi.yml
claim_count: 45
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, organization name, full name (optional) — provided at registration
  - category: contact
    text: Email address — the address you type into the Trend Reading 101 card on the Academy
  - category: financial
    text: Billing information — processed by Stripe Inc.; we receive only customer and subscription identifiers
  - category: behavioral
    text: API usage events — endpoint, HTTP status, timestamp — retained for 90 days
  - category: device
    text: Page views on public pages — path, referrer and UTM parameters, country, device, browser, operating system
  - category: identifying
    text: Public username, display name, public bio excerpt, company affiliation (if publicly listed)
  - category: identifying
    source: https://gatiflow.io/privacy#processors
    text: Email address, organization name, full name (optional) — provided at registration
  - category: financial
    source: https://gatiflow.io/privacy#processors
    text: Billing information — processed by Stripe Inc.; we receive only customer and subscription identifiers
  - category: behavioral
    source: https://gatiflow.io/privacy#processors
    text: API usage events — endpoint, HTTP status, timestamp — retained for 90 days
  - category: device
    source: https://gatiflow.io/privacy#processors
    text: Page views on public pages — path, referrer and UTM parameters, country, device, browser, operating system
  - category: communication
    source: https://gatiflow.io/privacy#processors
    text: Article feedback — the message you type in the box at the foot of an Academy article or a Saturday Deep Dive
  - category: contact
    source: https://gatiflow.io/privacy#processors
    text: Email address — the address you type into the Trend Reading 101 card on the Academy
  deletion:
    route: Settings → Delete Account
    text: 'Erasure: Delete your organization via Settings → Delete Account — irreversible (GDPR Art. 17, LGPD Art. 18)'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery and personalized reports
    text: Topics of interest — configured by you for personalized reports
  - purpose: Market intelligence
    text: aggregating publicly available information for market intelligence
  - purpose: Operational monitoring and security
    text: IP address — used for rate limiting and security; not stored long-term
  - purpose: Course and newsletter delivery
    text: The course then sends its five lessons, one a day, and the certificate at the end
  - purpose: market intelligence
    source: https://gatiflow.io/privacy#processors
    text: 'Source Data: Legitimate interest (Art. 6(1)(f)) — aggregating publicly available information for market intelligence.'
  - purpose: service delivery
    source: https://gatiflow.io/privacy#processors
    text: 'We share data with the following processors strictly for service delivery:'
  residency:
  - region: United States
    text: Personal data is stored and processed in the United States, by the processors listed in section 6
  - region: European Union
    text: transactional email is processed by Brevo in the European Union
  - region: United States
    source: https://gatiflow.io/privacy#processors
    text: Personal data is stored and processed in the United States
  - region: European Union
    source: https://gatiflow.io/privacy#processors
    text: transactional email is processed by Brevo in the European Union
  retention:
  - period: 90 days
    scope: Account Data
    text: 'Account Data: retained while account is active + 90 days after deletion for legal compliance'
  - period: 90 days
    scope: Usage events
    text: 'Usage Events: 90 days (configurable via USAGE_RETENTION_DAYS)'
  - period: 730 days
    scope: Article feedback
    text: 'Article feedback: 730 days'
  - period: 30 days
    scope: Unconfirmed mailing-list sign-ups
    text: unconfirmed sign-ups are deleted after 30 days
  - period: 25 hours
    scope: Source Data cache
    text: 'Source Data cache: 25 hours (Redis TTL, auto-expires)'
  - period: 90 days
    scope: Usage events
    source: https://gatiflow.io/privacy#processors
    text: 'Usage Events: 90 days (configurable via USAGE_RETENTION_DAYS)'
  - period: 730 days
    scope: Article feedback
    source: https://gatiflow.io/privacy#processors
    text: 'Article feedback: 730 days'
  - period: 60 days
    scope: Signal snapshots
    source: https://gatiflow.io/privacy#processors
    text: 'Signal snapshots: 60 days'
  - period: 90 days
    scope: Account Data
    source: https://gatiflow.io/privacy#processors
    text: 'Account Data: retained while account is active + 90 days after deletion for legal compliance'
  rights:
  - right: Access
    text: 'Access: Export all your data via Settings → Data & Privacy → Export (GDPR Art. 15, LGPD Art. 18)'
  - right: Rectification
    text: 'Rectification: Update your profile via Settings (GDPR Art. 16)'
  - right: Portability
    text: 'Portability: Export returns machine-readable JSON (GDPR Art. 20)'
  - right: Restriction/Objection
    text: 'Restriction/Objection: Contact privacy@gatiflow.io (GDPR Arts. 18, 21)'
  - right: Opt-out for individuals in reports
    text: Any individual whose public data appears in GatiFlow reports may request removal at /opt-out or by emailing privacy@gatiflow.io with your platform username
  - right: Access
    source: https://gatiflow.io/privacy#processors
    text: Export all your data via Settings → Data & Privacy → Export (GDPR Art. 15, LGPD Art. 18)
  - right: Opt-out (Source Data)
    source: https://gatiflow.io/privacy#processors
    text: Any individual whose public data appears in GatiFlow reports may request removal at /opt-out
  - right: Restriction/Objection
    source: https://gatiflow.io/privacy#processors
    text: Contact privacy@gatiflow.io (GDPR Arts. 18, 21)
  role:
    text: GatiFlow ("we", "us") acts as data controller for Account Data (information about our customers) and as an independent controller for Source Data
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Stripe Inc. (billing) — USA, SCCs in place
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses (SCCs) and processor-specific safeguards for EU-US and BR-US transfers.
  - mechanism: SCC
    source: https://gatiflow.io/privacy#processors
    text: We rely on Standard Contractual Clauses (SCCs) and processor-specific safeguards for EU-US and BR-US transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GatiFlow
provenance_date: '2026-11-09'
provider_name: GatiFlow
provider_slug: gatiflow
slug: gatiflow-privacy-policy
source_date: '2026-11-09'
source_filename: gatiflow-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gatiflow.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GatiFlow\naid: gatiflow\nurl: https://gatiflow.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://gatiflow.io/privacy\n  - https://gatiflow.io/privacy#processors\nrole:\n  value: both\n  text: GatiFlow (\"we\", \"us\") acts as data controller for Account Data (information about our customers) and as\n    an independent controller for Source Data\ndata_categories:\n- category: identifying\n  text: Email address, organization name, full name (optional) — provided at registration\n- category: contact\n  text: Email address — the address you type into the Trend Reading 101 card on the Academy\n- category:\
  \ financial\n  text: Billing information — processed by Stripe Inc.; we receive only customer and subscription identifiers\n- category: behavioral\n  text: API usage events — endpoint, HTTP status, timestamp — retained for 90 days\n- category: device\n  text: Page views on public pages — path, referrer and UTM parameters, country, device, browser, operating system\n- category: identifying\n  text: Public username, display name, public bio excerpt, company affiliation (if publicly listed)\n- category: identifying\n  text: Email address, organization name, full name (optional) — provided at registration\n  source: https://gatiflow.io/privacy#processors\n- category: financial\n  text: Billing information — processed by Stripe Inc.; we receive only customer and subscription identifiers\n  source: https://gatiflow.io/privacy#processors\n- category: behavioral\n  text: API usage events — endpoint, HTTP status, timestamp — retained for 90 days\n  source: https://gatiflow.io/privacy#processors\n\
  - category: device\n  text: Page views on public pages — path, referrer and UTM parameters, country, device, browser, operating system\n  source: https://gatiflow.io/privacy#processors\n- category: communication\n  text: Article feedback — the message you type in the box at the foot of an Academy article or a Saturday Deep\n    Dive\n  source: https://gatiflow.io/privacy#processors\n- category: contact\n  text: Email address — the address you type into the Trend Reading 101 card on the Academy\n  source: https://gatiflow.io/privacy#processors\npurposes:\n- purpose: Service delivery and personalized reports\n  text: Topics of interest — configured by you for personalized reports\n- purpose: Market intelligence\n  text: aggregating publicly available information for market intelligence\n- purpose: Operational monitoring and security\n  text: IP address — used for rate limiting and security; not stored long-term\n- purpose: Course and newsletter delivery\n  text: The course then sends its\
  \ five lessons, one a day, and the certificate at the end\n- purpose: market intelligence\n  text: 'Source Data: Legitimate interest (Art. 6(1)(f)) — aggregating publicly available information for market\n    intelligence.'\n  source: https://gatiflow.io/privacy#processors\n- purpose: service delivery\n  text: 'We share data with the following processors strictly for service delivery:'\n  source: https://gatiflow.io/privacy#processors\nretention:\n- scope: Account Data\n  period: 90 days\n  text: 'Account Data: retained while account is active + 90 days after deletion for legal compliance'\n- scope: Usage events\n  period: 90 days\n  text: 'Usage Events: 90 days (configurable via USAGE_RETENTION_DAYS)'\n- scope: Article feedback\n  period: 730 days\n  text: 'Article feedback: 730 days'\n- scope: Unconfirmed mailing-list sign-ups\n  period: 30 days\n  text: unconfirmed sign-ups are deleted after 30 days\n- scope: Source Data cache\n  period: 25 hours\n  text: 'Source Data cache: 25 hours\
  \ (Redis TTL, auto-expires)'\n- scope: Usage events\n  period: 90 days\n  text: 'Usage Events: 90 days (configurable via USAGE_RETENTION_DAYS)'\n  source: https://gatiflow.io/privacy#processors\n- scope: Article feedback\n  period: 730 days\n  text: 'Article feedback: 730 days'\n  source: https://gatiflow.io/privacy#processors\n- scope: Signal snapshots\n  period: 60 days\n  text: 'Signal snapshots: 60 days'\n  source: https://gatiflow.io/privacy#processors\n- scope: Account Data\n  period: 90 days\n  text: 'Account Data: retained while account is active + 90 days after deletion for legal compliance'\n  source: https://gatiflow.io/privacy#processors\nresidency:\n- region: United States\n  text: Personal data is stored and processed in the United States, by the processors listed in section 6\n- region: European Union\n  text: transactional email is processed by Brevo in the European Union\n- region: United States\n  text: Personal data is stored and processed in the United States\n  source:\
  \ https://gatiflow.io/privacy#processors\n- region: European Union\n  text: transactional email is processed by Brevo in the European Union\n  source: https://gatiflow.io/privacy#processors\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses (SCCs) and processor-specific safeguards for EU-US and BR-US transfers.\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses (SCCs) and processor-specific safeguards for EU-US and BR-US transfers.\n  source: https://gatiflow.io/privacy#processors\nsubprocessors:\n  url: null\n  text: Stripe Inc. (billing) — USA, SCCs in place\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Delete Account\n  text: 'Erasure: Delete your organization via Settings → Delete Account — irreversible (GDPR Art. 17, LGPD Art.\n    18)'\nrights:\n- right: Access\n  text: 'Access: Export all your data via Settings → Data & Privacy → Export (GDPR Art. 15, LGPD Art. 18)'\n- right: Rectification\n  text:\
  \ 'Rectification: Update your profile via Settings (GDPR Art. 16)'\n- right: Portability\n  text: 'Portability: Export returns machine-readable JSON (GDPR Art. 20)'\n- right: Restriction/Objection\n  text: 'Restriction/Objection: Contact privacy@gatiflow.io (GDPR Arts. 18, 21)'\n- right: Opt-out for individuals in reports\n  text: Any individual whose public data appears in GatiFlow reports may request removal at /opt-out or by emailing\n    privacy@gatiflow.io with your platform username\n- right: Access\n  text: Export all your data via Settings → Data & Privacy → Export (GDPR Art. 15, LGPD Art. 18)\n  source: https://gatiflow.io/privacy#processors\n- right: Opt-out (Source Data)\n  text: Any individual whose public data appears in GatiFlow reports may request removal at /opt-out\n  source: https://gatiflow.io/privacy#processors\n- right: Restriction/Objection\n  text: Contact privacy@gatiflow.io (GDPR Arts. 18, 21)\n  source: https://gatiflow.io/privacy#processors\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/gatiflow/privacy/gatiflow-privacy-policy.yml
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
summary_line: 45 quoted statements, read from GatiFlow's own page on 2026-11-09.
synthetic: false
tags:
- Market Intelligence
- Developer Signals
- Trends
- Hiring
- Open Source
- Research
- B2B SaaS
- Artificial Intelligence
---
