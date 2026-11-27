---
api_specs:
- filename: datahyena-com-acquisitions-api-openapi.yml
  format: yaml
  label: datahyena-com Acquisitions API
  slug: datahyena-com-acquisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-acquisitions-api-openapi.yml
- filename: datahyena-com-companies-api-openapi.yml
  format: yaml
  label: datahyena-com Companies API
  slug: datahyena-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-companies-api-openapi.yml
- filename: datahyena-com-exec-moves-api-openapi.yml
  format: yaml
  label: datahyena-com Exec Moves API
  slug: datahyena-com-exec-moves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-exec-moves-api-openapi.yml
- filename: datahyena-com-funding-events-api-openapi.yml
  format: yaml
  label: datahyena-com Funding Events API
  slug: datahyena-com-funding-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-funding-events-api-openapi.yml
- filename: datahyena-com-hiring-signals-api-openapi.yml
  format: yaml
  label: datahyena-com Hiring Signals API
  slug: datahyena-com-hiring-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-hiring-signals-api-openapi.yml
- filename: datahyena-com-investors-api-openapi.yml
  format: yaml
  label: datahyena-com Investors API
  slug: datahyena-com-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-investors-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Business email, name, and encrypted password
  - category: communication
    text: Email addresses of team members you invite
  - category: behavioral
    text: Pages visited and features used in the dashboard
  - category: device
    text: Browser, OS, device identifiers, and IP address
  - category: financial
    text: Kelviq stores card details, billing address, and tax identifiers directly.
  deletion:
    route: delete your account
    text: Delete your account, which we action within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the product
    text: Authenticate your API keys, serve the signals you request, and meter your credit usage
  - purpose: improve the product
    text: Aggregated, de-identified usage data is used to improve coverage, data quality, and performance
  - purpose: security and compliance
    text: Detect abuse, prevent fraud, and protect the platform
  retention:
  - period: for the duration of your account
    scope: account data while account is active
    text: We retain account data, API keys, and usage logs for the duration of your account.
  - period: 30 days
    scope: account data after closure
    text: Account data is deleted within 30 days of closure
  - period: 90 days
    scope: backups
    text: Backups containing your data are purged within 90 days
  - period: as required for tax and audit compliance
    scope: billing records
    text: Billing records are retained as required for tax and audit compliance
  rights:
  - right: access
    text: Access the data we hold on you
  - right: correction
    text: Correct anything inaccurate via your dashboard
  - right: export
    text: Export your account data
  - right: GDPR rights
    text: You also have the rights to erasure, restriction, portability, objection, withdrawal of consent, and to lodge a complaint with your local supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell, rent, or trade your account or usage data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When data is processed outside your region, we rely on appropriate safeguards such as Standard Contractual Clauses and require recipients to provide equivalent protection.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: datahyena-com
provenance_date: '2026-11-09'
provider_name: datahyena-com
provider_slug: datahyena-com
slug: datahyena-com-privacy-policy
source_date: '2026-11-09'
source_filename: datahyena-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://datahyena.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: datahyena-com\naid: datahyena-com\nurl: https://datahyena.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Business email, name, and encrypted password\n- category: communication\n  text: Email addresses of team members you invite\n- category: behavioral\n  text: Pages visited and features used in the dashboard\n- category: device\n  text: Browser, OS, device identifiers, and IP address\n- category: financial\n  text: Kelviq stores card details, billing address, and tax identifiers directly.\npurposes:\n- purpose: run the product\n\
  \  text: Authenticate your API keys, serve the signals you request, and meter your credit usage\n- purpose: improve the product\n  text: Aggregated, de-identified usage data is used to improve coverage, data quality, and performance\n- purpose: security and compliance\n  text: Detect abuse, prevent fraud, and protect the platform\nretention:\n- scope: account data while account is active\n  period: for the duration of your account\n  text: We retain account data, API keys, and usage logs for the duration of your account.\n- scope: account data after closure\n  period: 30 days\n  text: Account data is deleted within 30 days of closure\n- scope: backups\n  period: 90 days\n  text: Backups containing your data are purged within 90 days\n- scope: billing records\n  period: as required for tax and audit compliance\n  text: Billing records are retained as required for tax and audit compliance\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: When data is processed outside your region, we\
  \ rely on appropriate safeguards such as Standard Contractual\n    Clauses and require recipients to provide equivalent protection.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete your account\n  text: Delete your account, which we action within 30 days\nrights:\n- right: access\n  text: Access the data we hold on you\n- right: correction\n  text: Correct anything inaccurate via your dashboard\n- right: export\n  text: Export your account data\n- right: GDPR rights\n  text: You also have the rights to erasure, restriction, portability, objection, withdrawal of consent, and to\n    lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell, rent, or trade your account or usage data.\n"
source_yaml_url: https://artifacts.apis.io/datahyena-com/privacy/datahyena-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from datahyena-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Funding
- M&A
- Hiring
---
