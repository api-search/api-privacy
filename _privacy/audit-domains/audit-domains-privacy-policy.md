---
api_specs:
- filename: audit-domains-account-api-openapi.yml
  format: yaml
  label: audit.domains Account API
  slug: audit-domains-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-account-api-openapi.yml
- filename: audit-domains-appraisals-api-openapi.yml
  format: yaml
  label: audit.domains Appraisals API
  slug: audit-domains-appraisals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-appraisals-api-openapi.yml
- filename: audit-domains-bulk-api-openapi.yml
  format: yaml
  label: audit.domains Bulk API
  slug: audit-domains-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-bulk-api-openapi.yml
- filename: audit-domains-machine-api-openapi.yml
  format: yaml
  label: audit.domains Machine API
  slug: audit-domains-machine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-machine-api-openapi.yml
- filename: audit-domains-sales-api-openapi.yml
  format: yaml
  label: audit.domains Sales API
  slug: audit-domains-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audit-domains/openapi/audit-domains-sales-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, password'
  - category: financial
    text: 'Payment Information: Billing address, payment method details (processed securely by Square - we do not store full credit card details)'
  - category: behavioral
    text: 'Usage Data: Pages viewed, features used, time spent, click patterns'
  - category: device
    text: 'Device Information: Browser type, operating system, device identifiers'
  - category: location
    text: 'Location Data: IP address, general geographic location'
  - category: communication
    text: 'Communications: Support messages, feedback, and correspondence'
  deletion:
    route: Self-service account deletion in Account > Data & privacy; deletion scheduled 30 days ahead
    text: 'You can download a copy of your data and delete your account yourself: sign in, open Account , then Data & privacy . Deletion is scheduled 30 days ahead so you can change your mind; after that the account and its data are erased.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: 'Provide Services: Process domain valuations, generate reports, save your data'
  - purpose: Billing
    text: 'Billing: Process payments, send invoices, manage subscriptions'
  - purpose: Improve service
    text: 'Improve Service: Analyze usage patterns, optimize algorithms, fix bugs'
  - purpose: Security
    text: 'Security: Detect fraud, prevent abuse, enforce our Terms'
  retention:
  - period: 30 days
    scope: Account data
    text: 'Account Data: Until you delete your account, plus 30 days'
  - period: 7 years
    scope: Payment records
    text: 'Payment Records: 7 years for tax and accounting purposes'
  - period: 26 months
    scope: Analytics data
    text: 'Analytics Data: No more than 26 months in PostHog or Google Analytics'
  - period: 3 years
    scope: Support communications
    text: 'Support Communications: 3 years or as required by law'
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Rectification: Correct inaccurate or incomplete data'
  - right: Erasure
    text: 'Erasure: Request deletion of your data (“right to be forgotten”)'
  - right: Portability
    text: 'Portability: Receive your data in a machine-readable format'
  - right: Object
    text: 'Object: Object to processing based on legitimate interests'
  - right: Know (CCPA)
    text: 'Know: What personal information we collect and how we use it'
  - right: Opt-out of sale (CCPA)
    text: 'Opt-Out: Opt out of the “sale” of personal information (we don’t sell data)'
  role:
    text: audit.domains ("we," "us," or "our") respects your privacy and is committed to protecting your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: audit.domains
provenance_date: '2026-11-09'
provider_name: audit.domains
provider_slug: audit-domains
slug: audit-domains-privacy-policy
source_date: '2026-11-09'
source_filename: audit-domains-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://audit.domains/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: audit.domains\naid: audit-domains\nurl: https://audit.domains/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: audit.domains (\"we,\" \"us,\" or \"our\") respects your privacy and is committed to protecting your personal\n    data.\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, password'\n- category: financial\n  text: 'Payment Information: Billing address, payment method details (processed securely by Square - we do not\n    store full credit card details)'\n- category: behavioral\n  text: 'Usage Data: Pages viewed, features used, time\
  \ spent, click patterns'\n- category: device\n  text: 'Device Information: Browser type, operating system, device identifiers'\n- category: location\n  text: 'Location Data: IP address, general geographic location'\n- category: communication\n  text: 'Communications: Support messages, feedback, and correspondence'\npurposes:\n- purpose: Provide services\n  text: 'Provide Services: Process domain valuations, generate reports, save your data'\n- purpose: Billing\n  text: 'Billing: Process payments, send invoices, manage subscriptions'\n- purpose: Improve service\n  text: 'Improve Service: Analyze usage patterns, optimize algorithms, fix bugs'\n- purpose: Security\n  text: 'Security: Detect fraud, prevent abuse, enforce our Terms'\nretention:\n- scope: Account data\n  period: 30 days\n  text: 'Account Data: Until you delete your account, plus 30 days'\n- scope: Payment records\n  period: 7 years\n  text: 'Payment Records: 7 years for tax and accounting purposes'\n- scope: Analytics data\n\
  \  period: 26 months\n  text: 'Analytics Data: No more than 26 months in PostHog or Google Analytics'\n- scope: Support communications\n  period: 3 years\n  text: 'Support Communications: 3 years or as required by law'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service account deletion in Account > Data & privacy; deletion scheduled 30 days ahead\n  text: 'You can download a copy of your data and delete your account yourself: sign in, open Account , then Data\n    & privacy . Deletion is scheduled 30 days ahead so you can change your mind; after that the account and its\n    data are erased.'\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Rectification\n  text: 'Rectification: Correct inaccurate or incomplete data'\n- right: Erasure\n  text: 'Erasure:\
  \ Request deletion of your data (“right to be forgotten”)'\n- right: Portability\n  text: 'Portability: Receive your data in a machine-readable format'\n- right: Object\n  text: 'Object: Object to processing based on legitimate interests'\n- right: Know (CCPA)\n  text: 'Know: What personal information we collect and how we use it'\n- right: Opt-out of sale (CCPA)\n  text: 'Opt-Out: Opt out of the “sale” of personal information (we don’t sell data)'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/audit-domains/privacy/audit-domains-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from audit.domains's own page on 2026-11-09.
synthetic: false
tags:
- Domain
- Valuation
- Analytics
- Portfolio
---
