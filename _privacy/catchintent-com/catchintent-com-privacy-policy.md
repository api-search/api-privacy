---
api_specs:
- filename: catchintent-com-discovery-api-openapi.yml
  format: yaml
  label: CatchIntent Discovery API
  slug: catchintent-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-discovery-api-openapi.yml
- filename: catchintent-com-health-api-openapi.yml
  format: yaml
  label: CatchIntent Health API
  slug: catchintent-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-health-api-openapi.yml
- filename: catchintent-com-mcp-api-openapi.yml
  format: yaml
  label: CatchIntent MCP API
  slug: catchintent-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-mcp-api-openapi.yml
- filename: catchintent-com-oauth-api-openapi.yml
  format: yaml
  label: CatchIntent OAuth API
  slug: catchintent-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catchintent-com/openapi/catchintent-com-oauth-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Business email, name, and encrypted password
  - category: professional
    text: profile data (name, headline, current role, company, location, public engagement) for people matched against your ICP
  - category: financial
    text: Kelviq stores card details, billing address, and tax identifiers directly.
  - category: device
    text: Browser, OS, device identifiers, and IP address
  - category: behavioral
    text: Pages visited, features used, time spent, and clicks
  deletion:
    route: Delete your account from the dashboard or rights section
    text: Delete your account (we delete within 30 days)
  dpa:
    available: null
    text: All are bound by data processing agreements and may only use your data to provide their service to us
    url: null
  purposes:
  - purpose: Run the product and agents
    text: Operate agents on your behalf — scan LinkedIn for the signals you’ve enabled, score matches against your ICP, enrich profiles, and draft openers
  - purpose: Improve the product
    text: Aggregate and de-identified usage data is used to improve signal quality, AI scoring rubrics, and product performance
  - purpose: Security and compliance
    text: Detect abuse, prevent fraud, and protect the platform
  residency:
  - region: European Union (Germany)
    text: Our primary infrastructure is in the European Union (Germany).
  retention:
  - period: 30 days
    scope: Account data and leads after cancellation
    text: Account data and leads are deleted within 30 days of cancellation
  - period: 7 years
    scope: Billing records
    text: Billing records are retained 7 years for tax and audit compliance
  - period: 90 days
    scope: Backups
    text: Backups containing your data are purged within 90 days
  rights:
  - right: Access
    text: Access the data we hold on you
  - right: Correction
    text: Correct anything inaccurate via your dashboard
  - right: Export
    text: Export your data in JSON or CSV
  - right: Erasure, restriction, portability, objection, withdrawal of consent
    text: You also have the rights to erasure, restriction, portability, objection, withdrawal of consent, and to lodge a complaint with your local supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell, rent, or trade your data. Ever.
  subprocessors:
    text: Hetzner, AWS, and Cloudflare — infrastructure, hosting, AI compute, and CDN
    url: null
  transfers:
  - mechanism: SCC
    text: we use Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CatchIntent
provenance_date: '2026-11-09'
provider_name: CatchIntent
provider_slug: catchintent-com
slug: catchintent-com-privacy-policy
source_date: '2026-11-09'
source_filename: catchintent-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://catchintent.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CatchIntent\naid: catchintent-com\nurl: https://catchintent.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Business email, name, and encrypted password\n- category: professional\n  text: profile data (name, headline, current role, company, location, public engagement) for people matched against\n    your ICP\n- category: financial\n  text: Kelviq stores card details, billing address, and tax identifiers directly.\n- category: device\n  text: Browser, OS, device identifiers, and IP address\n- category: behavioral\n \
  \ text: Pages visited, features used, time spent, and clicks\npurposes:\n- purpose: Run the product and agents\n  text: Operate agents on your behalf — scan LinkedIn for the signals you’ve enabled, score matches against your\n    ICP, enrich profiles, and draft openers\n- purpose: Improve the product\n  text: Aggregate and de-identified usage data is used to improve signal quality, AI scoring rubrics, and product\n    performance\n- purpose: Security and compliance\n  text: Detect abuse, prevent fraud, and protect the platform\nretention:\n- scope: Account data and leads after cancellation\n  period: 30 days\n  text: Account data and leads are deleted within 30 days of cancellation\n- scope: Billing records\n  period: 7 years\n  text: Billing records are retained 7 years for tax and audit compliance\n- scope: Backups\n  period: 90 days\n  text: Backups containing your data are purged within 90 days\nresidency:\n- region: European Union (Germany)\n  text: Our primary infrastructure is in\
  \ the European Union (Germany).\ntransfers:\n- mechanism: SCC\n  text: we use Standard Contractual Clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: Hetzner, AWS, and Cloudflare — infrastructure, hosting, AI compute, and CDN\ndpa:\n  available: null\n  url: null\n  text: All are bound by data processing agreements and may only use your data to provide their service to us\ndeletion:\n  route: Delete your account from the dashboard or rights section\n  text: Delete your account (we delete within 30 days)\nrights:\n- right: Access\n  text: Access the data we hold on you\n- right: Correction\n  text: Correct anything inaccurate via your dashboard\n- right: Export\n  text: Export your data in JSON or CSV\n- right: Erasure, restriction, portability, objection, withdrawal of consent\n  text: You also have the rights to erasure, restriction, portability, objection, withdrawal of consent, and to\n    lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We don’t sell, rent, or trade your data. Ever.\n"
source_yaml_url: https://artifacts.apis.io/catchintent-com/privacy/catchintent-com-privacy-policy.yml
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
summary_line: 21 quoted statements, read from CatchIntent's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Sales
- Intent Data
- Artificial Intelligence
- Outbound
---
