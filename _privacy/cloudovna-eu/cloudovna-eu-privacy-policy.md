---
api_specs:
- filename: cloudovna-eu-catalog-api-openapi.yml
  format: yaml
  label: Cloudovňa Catalog API
  slug: cloudovna-eu-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-catalog-api-openapi.yml
- filename: cloudovna-eu-health-api-openapi.yml
  format: yaml
  label: Cloudovňa Health API
  slug: cloudovna-eu-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-health-api-openapi.yml
- filename: cloudovna-eu-hooks-api-openapi.yml
  format: yaml
  label: Cloudovňa Hooks API
  slug: cloudovna-eu-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-hooks-api-openapi.yml
- filename: cloudovna-eu-images-api-openapi.yml
  format: yaml
  label: Cloudovňa Images API
  slug: cloudovna-eu-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-images-api-openapi.yml
- filename: cloudovna-eu-integrations-api-openapi.yml
  format: yaml
  label: Cloudovňa Integrations API
  slug: cloudovna-eu-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-integrations-api-openapi.yml
- filename: cloudovna-eu-invitations-api-openapi.yml
  format: yaml
  label: Cloudovňa Invitations API
  slug: cloudovna-eu-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-invitations-api-openapi.yml
- filename: cloudovna-eu-invoices-api-openapi.yml
  format: yaml
  label: Cloudovňa Invoices API
  slug: cloudovna-eu-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-invoices-api-openapi.yml
- filename: cloudovna-eu-mcp-api-openapi.yml
  format: yaml
  label: Cloudovňa MCP API
  slug: cloudovna-eu-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-mcp-api-openapi.yml
- filename: cloudovna-eu-oauth-api-openapi.yml
  format: yaml
  label: Cloudovňa OAuth API
  slug: cloudovna-eu-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-oauth-api-openapi.yml
- filename: cloudovna-eu-organizations-api-openapi.yml
  format: yaml
  label: Cloudovňa Organizations API
  slug: cloudovna-eu-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-organizations-api-openapi.yml
- filename: cloudovna-eu-payments-api-openapi.yml
  format: yaml
  label: Cloudovňa Payments API
  slug: cloudovna-eu-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-payments-api-openapi.yml
- filename: cloudovna-eu-pool-api-openapi.yml
  format: yaml
  label: Cloudovňa Pool API
  slug: cloudovna-eu-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-pool-api-openapi.yml
- filename: cloudovna-eu-public-api-openapi.yml
  format: yaml
  label: Cloudovňa Public API
  slug: cloudovna-eu-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-public-api-openapi.yml
- filename: cloudovna-eu-services-api-openapi.yml
  format: yaml
  label: Cloudovňa Services API
  slug: cloudovna-eu-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-services-api-openapi.yml
- filename: cloudovna-eu-stacks-api-openapi.yml
  format: yaml
  label: Cloudovňa Stacks API
  slug: cloudovna-eu-stacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-stacks-api-openapi.yml
- filename: cloudovna-eu-well-known-api-openapi.yml
  format: yaml
  label: Cloudovňa .well Known API
  slug: cloudovna-eu-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-well-known-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: name, email, your password stored only as a hash (PBKDF2), invoice language and the date your email was verified.'
  - category: contact
    text: 'Billing details, if you fill them in: first and last name, company name, address, company ID, tax ID, VAT ID and phone.'
  - category: financial
    text: 'Payments: amounts, status and the payment provider''s identifiers. Card or account details are not sent to us and we do not store them.'
  - category: device
    text: 'Technical data: your IP address is used during a request to limit repeated attempts and is not stored.'
  - category: communication
    text: Health check results for your services, and emails you exchange with us.
  - category: other
    text: 'Access to other services, if you link them: your Docker Hub or GitHub username and access token, and a Cloudflare API token.'
  deletion:
    route: Write to the provider's privacy contact email to close your account
    text: For a copy of your data or to close your account, write to [email protected] .
  dpa:
    available: true
    text: we process it as your processor under the Data processing agreement, which is part of every order.
    url: null
  purposes:
  - purpose: Contract performance
    text: 'Performance of the contract, Article 6(1)(b) GDPR: running your account, providing the services, payments, service emails (email verification, password reset, payment requests, invoices, downtime alerts) and support.'
  - purpose: Legal obligation
    text: 'Legal obligation, Article 6(1)(c) GDPR: issuing and keeping invoices under accounting and tax law.'
  - purpose: Security and legitimate interest
    text: 'Legitimate interest, Article 6(1)(f) GDPR: keeping the service secure, preventing abuse and establishing or defending legal claims.'
  residency:
  - region: EU
    text: The servers running your services and holding your data are in the EU.
  retention:
  - period: 10 years
    scope: Invoices
    text: Invoices are kept for 10 years, as accounting law requires.
  - period: 7 days
    scope: Health check results
    text: Health check results are kept for 7 days.
  - period: 14 days
    scope: Unpaid order
    text: An unpaid order is withdrawn after 14 days.
  - period: 90 days
    scope: Suspended service
    text: A service suspended for an unpaid renewal is removed after 90 days, with its data and backups.
  - period: up to 12 months
    scope: Own disaster recovery backups
    text: Our own disaster recovery backups of the servers are kept for up to 12 months and then overwritten.
  rights:
  - right: access
    text: You have the right of access to your data and to a copy of it, to rectification, erasure, restriction of processing and portability
  - right: object
    text: the right to object to processing based on legitimate interest
  role:
    text: Data about you as a customer (your account, billing, messages) we process as the controller, and this policy applies to it.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not use data for marketing and we do not sell it.
  subprocessors:
    text: 'Contabo GmbH, Munich (Germany): the servers that run your containers and databases.'
    url: null
  transfers:
  - mechanism: DPF
    text: Transfers to them rely on the EU-U.S. Data Privacy Framework where the company is certified, and otherwise on the European Commission's standard contractual clauses.
  - mechanism: SCC
    text: Transfers to them rely on the EU-U.S. Data Privacy Framework where the company is certified, and otherwise on the European Commission's standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cloudovňa
provenance_date: '2026-11-09'
provider_name: Cloudovňa
provider_slug: cloudovna-eu
slug: cloudovna-eu-privacy-policy
source_date: '2026-11-09'
source_filename: cloudovna-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cloudovna.eu/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cloudovňa\naid: cloudovna-eu\nurl: https://cloudovna.eu/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Data about you as a customer (your account, billing, messages) we process as the controller, and this policy\n    applies to it.\ndata_categories:\n- category: identifying\n  text: 'Account: name, email, your password stored only as a hash (PBKDF2), invoice language and the date your\n    email was verified.'\n- category: contact\n  text: 'Billing details, if you fill them in: first and last name, company name, address, company ID, tax ID, VAT\n    ID and phone.'\n- category: financial\n\
  \  text: 'Payments: amounts, status and the payment provider''s identifiers. Card or account details are not sent\n    to us and we do not store them.'\n- category: device\n  text: 'Technical data: your IP address is used during a request to limit repeated attempts and is not stored.'\n- category: communication\n  text: Health check results for your services, and emails you exchange with us.\n- category: other\n  text: 'Access to other services, if you link them: your Docker Hub or GitHub username and access token, and a\n    Cloudflare API token.'\npurposes:\n- purpose: Contract performance\n  text: 'Performance of the contract, Article 6(1)(b) GDPR: running your account, providing the services, payments,\n    service emails (email verification, password reset, payment requests, invoices, downtime alerts) and support.'\n- purpose: Legal obligation\n  text: 'Legal obligation, Article 6(1)(c) GDPR: issuing and keeping invoices under accounting and tax law.'\n- purpose: Security and legitimate\
  \ interest\n  text: 'Legitimate interest, Article 6(1)(f) GDPR: keeping the service secure, preventing abuse and establishing\n    or defending legal claims.'\nretention:\n- scope: Invoices\n  period: 10 years\n  text: Invoices are kept for 10 years, as accounting law requires.\n- scope: Health check results\n  period: 7 days\n  text: Health check results are kept for 7 days.\n- scope: Unpaid order\n  period: 14 days\n  text: An unpaid order is withdrawn after 14 days.\n- scope: Suspended service\n  period: 90 days\n  text: A service suspended for an unpaid renewal is removed after 90 days, with its data and backups.\n- scope: Own disaster recovery backups\n  period: up to 12 months\n  text: Our own disaster recovery backups of the servers are kept for up to 12 months and then overwritten.\nresidency:\n- region: EU\n  text: The servers running your services and holding your data are in the EU.\ntransfers:\n- mechanism: DPF\n  text: Transfers to them rely on the EU-U.S. Data Privacy Framework\
  \ where the company is certified, and otherwise\n    on the European Commission's standard contractual clauses.\n- mechanism: SCC\n  text: Transfers to them rely on the EU-U.S. Data Privacy Framework where the company is certified, and otherwise\n    on the European Commission's standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'Contabo GmbH, Munich (Germany): the servers that run your containers and databases.'\ndpa:\n  available: true\n  url: null\n  text: we process it as your processor under the Data processing agreement, which is part of every order.\ndeletion:\n  route: Write to the provider's privacy contact email to close your account\n  text: For a copy of your data or to close your account, write to [email protected] .\nrights:\n- right: access\n  text: You have the right of access to your data and to a copy of it, to rectification, erasure, restriction of\n    processing and portability\n- right: object\n  text: the right to object to processing based on legitimate\
  \ interest\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use data for marketing and we do not sell it.\n"
source_yaml_url: https://artifacts.apis.io/cloudovna-eu/privacy/cloudovna-eu-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Cloudovňa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Hosting
- Containers
- Docker
- Databases
- PostgreSQL
- SQL Server
- European Union
- MCP
---
