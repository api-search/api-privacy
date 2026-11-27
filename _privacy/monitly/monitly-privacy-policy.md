---
api_specs:
- filename: monitly-charts-api-openapi.yml
  format: yaml
  label: Monitly Charts API
  slug: monitly-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-charts-api-openapi.yml
- filename: monitly-datasets-api-openapi.yml
  format: yaml
  label: Monitly Datasets API
  slug: monitly-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-datasets-api-openapi.yml
- filename: monitly-mcp-api-openapi.yml
  format: yaml
  label: Monitly MCP API
  slug: monitly-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monitly/openapi/monitly-mcp-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Email address, display name, and password when you create an account'
  - category: behavioral
    text: 'Usage Data: Information about how you use our service, including search queries and dataset preferences'
  - category: device
    text: 'Technical Data: IP address, browser type, device information, and cookies'
  - category: communication
    text: 'Communication Data: Emails and messages you send to our support team'
  - category: other
    text: We may receive information from third-party services when you use them to sign in to Monitly (e.g., Google OAuth).
  deletion:
    route: Delete your account
    text: When you delete your account, we will delete or anonymize your personal information within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision
    text: To provide, maintain, and improve our data tracking and monitoring services
  - purpose: Account management
    text: To create and manage your account, process payments, and provide customer support
  - purpose: Personalization
    text: To customize your experience and provide relevant data insights and recommendations
  - purpose: Communication
    text: To send you important service updates, security notifications, and marketing communications (with your consent)
  - purpose: Analytics
    text: To analyze service usage patterns and improve our platform
  - purpose: Legal compliance
    text: To comply with applicable laws, regulations, and legal processes
  retention:
  - period: 30 days
    scope: Account deletion
    text: When you delete your account, we will delete or anonymize your personal information within 30 days, except where retention is required for legal or legitimate business purposes.
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal information'
  - right: Rectification
    text: 'Rectification: Request correction of inaccurate or incomplete information'
  - right: Erasure
    text: 'Erasure: Request deletion of your personal information'
  - right: Portability
    text: 'Portability: Request transfer of your data to another service'
  - right: Restriction
    text: 'Restriction: Request limitation of processing in certain circumstances'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interests'
  - right: Withdraw consent
    text: 'Withdraw Consent: Withdraw consent for processing based on consent'
  role:
    text: The data controller for Monitly is Content Writer LLC
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: For transfers outside the European Economic Area (EEA), we rely on adequacy decisions, standard contractual clauses, or other appropriate safeguards as required by law.
  - mechanism: SCC
    text: For transfers outside the European Economic Area (EEA), we rely on adequacy decisions, standard contractual clauses, or other appropriate safeguards as required by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Monitly
provenance_date: '2026-11-10'
provider_name: Monitly
provider_slug: monitly
slug: monitly-privacy-policy
source_date: '2026-11-10'
source_filename: monitly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://monit.ly/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Monitly\naid: monitly\nurl: https://monit.ly/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for Monitly is Content Writer LLC\ndata_categories:\n- category: identifying\n  text: 'Account Information: Email address, display name, and password when you create an account'\n- category: behavioral\n  text: 'Usage Data: Information about how you use our service, including search queries and dataset preferences'\n- category: device\n  text: 'Technical Data: IP address, browser type, device information, and cookies'\n- category: communication\n  text: 'Communication Data:\
  \ Emails and messages you send to our support team'\n- category: other\n  text: We may receive information from third-party services when you use them to sign in to Monitly (e.g., Google\n    OAuth).\npurposes:\n- purpose: Service provision\n  text: To provide, maintain, and improve our data tracking and monitoring services\n- purpose: Account management\n  text: To create and manage your account, process payments, and provide customer support\n- purpose: Personalization\n  text: To customize your experience and provide relevant data insights and recommendations\n- purpose: Communication\n  text: To send you important service updates, security notifications, and marketing communications (with your consent)\n- purpose: Analytics\n  text: To analyze service usage patterns and improve our platform\n- purpose: Legal compliance\n  text: To comply with applicable laws, regulations, and legal processes\nretention:\n- scope: Account deletion\n  period: 30 days\n  text: When you delete your account,\
  \ we will delete or anonymize your personal information within 30 days, except\n    where retention is required for legal or legitimate business purposes.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: For transfers outside the European Economic Area (EEA), we rely on adequacy decisions, standard contractual\n    clauses, or other appropriate safeguards as required by law.\n- mechanism: SCC\n  text: For transfers outside the European Economic Area (EEA), we rely on adequacy decisions, standard contractual\n    clauses, or other appropriate safeguards as required by law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account\n  text: When you delete your account, we will delete or anonymize your personal information within 30 days\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal information'\n- right: Rectification\n  text: 'Rectification: Request correction of inaccurate\
  \ or incomplete information'\n- right: Erasure\n  text: 'Erasure: Request deletion of your personal information'\n- right: Portability\n  text: 'Portability: Request transfer of your data to another service'\n- right: Restriction\n  text: 'Restriction: Request limitation of processing in certain circumstances'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interests'\n- right: Withdraw consent\n  text: 'Withdraw Consent: Withdraw consent for processing based on consent'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/monitly/privacy/monitly-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Monitly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Statistics
- Dashboards
---
