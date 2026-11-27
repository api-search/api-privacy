---
api_specs:
- filename: compabase-companies-api-openapi.yml
  format: yaml
  label: Compabase Companies API
  slug: compabase-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-companies-api-openapi.yml
- filename: compabase-health-api-openapi.yml
  format: yaml
  label: Compabase Health API
  slug: compabase-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-health-api-openapi.yml
- filename: compabase-persons-api-openapi.yml
  format: yaml
  label: Compabase Persons API
  slug: compabase-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-persons-api-openapi.yml
- filename: compabase-usage-api-openapi.yml
  format: yaml
  label: Compabase Usage API
  slug: compabase-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-usage-api-openapi.yml
- filename: compabase-watchlist-api-openapi.yml
  format: yaml
  label: Compabase Watchlist API
  slug: compabase-watchlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-watchlist-api-openapi.yml
- filename: compabase-financials-api-openapi.yml
  format: yaml
  label: Compabase Financials API
  slug: compabase-financials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-financials-api-openapi.yml
- filename: compabase-news-api-openapi.yml
  format: yaml
  label: Compabase News API
  slug: compabase-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-news-api-openapi.yml
- filename: compabase-registers-api-openapi.yml
  format: yaml
  label: Compabase Registers API
  slug: compabase-registers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-registers-api-openapi.yml
- filename: compabase-tenders-api-openapi.yml
  format: yaml
  label: Compabase Tenders API
  slug: compabase-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-tenders-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: email address associated with the account
  - category: financial
    text: tax identification number (NIP/VAT), invoice details
  - category: behavioral
    text: 'platform usage history: company profiles viewed, searches and filters used, exports, and API and MCP server calls (with date, time and IP address)'
  - category: device
    text: 'Basic technical logs may include: IP address, query metadata, timestamps.'
  - category: identifying
    text: 'Profiles may present, among others: entity name, KRS, NIP, REGON, legal form, address, status, registration dates, financial data'
  deletion:
    route: null
    text: Each request and objection is assessed individually.
  dpa:
    available: true
    text: All processors act under data processing agreements (Art. 28 GDPR) where required.
    url: null
  purposes:
  - purpose: maintaining portal account and providing platform services
    text: maintaining the portal account and providing platform services, performing contracts and delivering ordered services
  - purpose: issuing VAT invoices and keeping accounting records
    text: issuing VAT invoices, keeping accounting records.
  - purpose: counterparty verification and security of business dealings
    text: providing structured access to public business information from official registers for counterparty verification and the security of business dealings
  - purpose: analysing platform usage and tailoring it
    text: analysing platform usage and tailoring it to users’ needs
  residency:
  - region: EU
    text: The primary platform infrastructure and databases are hosted in the EU.
  retention:
  - period: 12 months
    scope: Platform usage history
    text: 'Platform usage history (profiles viewed, searches, exports, API and MCP calls): 12 months from the event.'
  - period: 3 years
    scope: Log of access to beneficial ownership data
    text: 'Log of access to beneficial ownership data: 3 years from the date of access.'
  - period: usually 3 or 6 years
    scope: Portal user account data
    text: 'Portal user account data: for as long as the account is active and, after its deletion, until the general limitation periods for civil-law claims expire (usually 3 or 6 years under the Polish Civil Code).'
  rights:
  - right: access
    text: access their data (Article 15 GDPR)
  - right: rectification
    text: request rectification (Article 16 GDPR)
  - right: erasure
    text: request erasure (Article 17 GDPR)
  - right: restriction
    text: request restriction of processing (Article 18 GDPR)
  - right: portability
    text: data portability (Article 20 GDPR)
  - right: objection
    text: object to processing based on Article 6(1)(f) GDPR (Article 21 GDPR)
  role:
    text: The Data Controller for the Compabase platform is Content Writer Sp. z o.o., headquartered at ul. Strzelecka 29A/39, 61-846 Poznań, Poland.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data as separate products.
  subprocessors:
    text: the hosting provider — Hetzner Online GmbH (servers in Germany and Finland)
    url: null
  transfers:
  - mechanism: SCC
    text: In such cases, appropriate safeguards are applied, including EU Standard Contractual Clauses or equivalent legal mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Compabase
provenance_date: '2026-11-09'
provider_name: Compabase
provider_slug: compabase
slug: compabase-privacy-policy
source_date: '2026-11-09'
source_filename: compabase-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://compabase.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Compabase\naid: compabase\nurl: https://compabase.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Data Controller for the Compabase platform is Content Writer Sp. z o.o., headquartered at ul. Strzelecka\n    29A/39, 61-846 Poznań, Poland.\ndata_categories:\n- category: contact\n  text: email address associated with the account\n- category: financial\n  text: tax identification number (NIP/VAT), invoice details\n- category: behavioral\n  text: 'platform usage history: company profiles viewed, searches and filters used, exports, and API and MCP server\n    calls (with date, time\
  \ and IP address)'\n- category: device\n  text: 'Basic technical logs may include: IP address, query metadata, timestamps.'\n- category: identifying\n  text: 'Profiles may present, among others: entity name, KRS, NIP, REGON, legal form, address, status, registration\n    dates, financial data'\npurposes:\n- purpose: maintaining portal account and providing platform services\n  text: maintaining the portal account and providing platform services, performing contracts and delivering ordered\n    services\n- purpose: issuing VAT invoices and keeping accounting records\n  text: issuing VAT invoices, keeping accounting records.\n- purpose: counterparty verification and security of business dealings\n  text: providing structured access to public business information from official registers for counterparty verification\n    and the security of business dealings\n- purpose: analysing platform usage and tailoring it\n  text: analysing platform usage and tailoring it to users’ needs\nretention:\n\
  - scope: Platform usage history\n  period: 12 months\n  text: 'Platform usage history (profiles viewed, searches, exports, API and MCP calls): 12 months from the event.'\n- scope: Log of access to beneficial ownership data\n  period: 3 years\n  text: 'Log of access to beneficial ownership data: 3 years from the date of access.'\n- scope: Portal user account data\n  period: usually 3 or 6 years\n  text: 'Portal user account data: for as long as the account is active and, after its deletion, until the general\n    limitation periods for civil-law claims expire (usually 3 or 6 years under the Polish Civil Code).'\nresidency:\n- region: EU\n  text: The primary platform infrastructure and databases are hosted in the EU.\ntransfers:\n- mechanism: SCC\n  text: In such cases, appropriate safeguards are applied, including EU Standard Contractual Clauses or equivalent\n    legal mechanisms.\nsubprocessors:\n  url: null\n  text: the hosting provider — Hetzner Online GmbH (servers in Germany and Finland)\n\
  dpa:\n  available: true\n  url: null\n  text: All processors act under data processing agreements (Art. 28 GDPR) where required.\ndeletion:\n  route: null\n  text: Each request and objection is assessed individually.\nrights:\n- right: access\n  text: access their data (Article 15 GDPR)\n- right: rectification\n  text: request rectification (Article 16 GDPR)\n- right: erasure\n  text: request erasure (Article 17 GDPR)\n- right: restriction\n  text: request restriction of processing (Article 18 GDPR)\n- right: portability\n  text: data portability (Article 20 GDPR)\n- right: objection\n  text: object to processing based on Article 6(1)(f) GDPR (Article 21 GDPR)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data as separate products.\n"
source_yaml_url: https://artifacts.apis.io/compabase/privacy/compabase-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Compabase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Polish
- Business
- Finance
- Risk Management
- Artificial Intelligence
---
