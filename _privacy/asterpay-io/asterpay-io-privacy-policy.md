---
api_specs:
- filename: asterpay-io-ai-api-openapi.yml
  format: yaml
  label: AsterPay AI API
  slug: asterpay-io-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-ai-api-openapi.yml
- filename: asterpay-io-crypto-api-openapi.yml
  format: yaml
  label: AsterPay Crypto API
  slug: asterpay-io-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-crypto-api-openapi.yml
- filename: asterpay-io-data-api-openapi.yml
  format: yaml
  label: AsterPay Data API
  slug: asterpay-io-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-data-api-openapi.yml
- filename: asterpay-io-discovery-api-openapi.yml
  format: yaml
  label: AsterPay Discovery API
  slug: asterpay-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-discovery-api-openapi.yml
- filename: asterpay-io-market-api-openapi.yml
  format: yaml
  label: AsterPay Market API
  slug: asterpay-io-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-market-api-openapi.yml
- filename: asterpay-io-sessions-api-openapi.yml
  format: yaml
  label: AsterPay Sessions API
  slug: asterpay-io-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-sessions-api-openapi.yml
- filename: asterpay-io-settlement-api-openapi.yml
  format: yaml
  label: AsterPay Settlement API
  slug: asterpay-io-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-settlement-api-openapi.yml
- filename: asterpay-io-trust-api-openapi.yml
  format: yaml
  label: AsterPay Trust API
  slug: asterpay-io-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-trust-api-openapi.yml
- filename: asterpay-io-utility-api-openapi.yml
  format: yaml
  label: AsterPay Utility API
  slug: asterpay-io-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asterpay-io/openapi/asterpay-io-utility-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account & merchant data: name, business email, role, company name, VAT ID, registered address, dashboard credentials.'
  - category: financial
    text: 'Transaction & settlement data: transaction hashes, amounts, timestamps, source and destination wallet addresses, IBAN/BIC of beneficiary accounts, conversion rates, fee breakdowns, refund and chargeback records.'
  - category: behavioral
    text: 'KYA (Know Your Agent) data: agent identifiers (e.g. ERC-8004 ID), wallet addresses, behavioural signals, operator attestations, Trust Score components.'
  - category: device
    text: 'Technical data: IP address, user agent, request headers, API key identifiers (hashed), error and rate-limit logs.'
  - category: communication
    text: 'Communications: support tickets, partnership emails, scheduling data via cal.eu/asterpay.'
  - category: other
    text: 'Sanctions screening data: screening verdicts and identifiers exchanged with our enterprise sanctions / AML screening provider against EU, UN, OFAC and HM Treasury lists.'
  deletion:
    route: request under data-subject rights
    text: erasure (subject to retention obligations)
  dpa:
    available: true
    text: All processors are bound by Art. 28 GDPR data-processing agreements.
    url: null
  purposes:
  - purpose: service provision
    text: 'Provision of services (Art. 6(1)(b) GDPR — contract): operating accounts, processing payments, computing Trust Score, executing EUR settlement.'
  - purpose: legal compliance
    text: 'Compliance with legal obligations (Art. 6(1)(c) GDPR): KYB, AML, sanctions screening, Travel Rule, VAT, MiCA-related record keeping, EU AI Act transparency.'
  - purpose: legitimate interests
    text: 'Legitimate interests (Art. 6(1)(f) GDPR): fraud prevention, security monitoring, abuse detection, product analytics, partner due diligence.'
  - purpose: consent-based processing
    text: 'Consent (Art. 6(1)(a) GDPR): marketing communications, non-essential cookies and any features explicitly described as opt-in.'
  residency:
  - region: EU
    text: Cloud and hosting providers (Cloudflare, Railway, Supabase) for application infrastructure, with EU data-residency options where available
  retention:
  - period: 5 years after end of business relationship
    scope: KYB and AML records
    text: 'KYB and AML records: retained for the periods required by EU AML legislation (currently 5 years after end of business relationship, extendable to 10 years where mandated).'
  - period: minimum 5 years
    scope: transaction and settlement records
    text: 'Transaction and settlement records: minimum 5 years.'
  - period: rolling 90 days
    scope: technical logs
    text: 'Technical logs: rolling 90 days unless retained longer for security investigation.'
  rights:
  - right: GDPR rights
    text: access, rectification, erasure (subject to retention obligations), restriction, data portability, objection to processing based on legitimate interests, and to withdraw consent.
  - right: human review of automated decisions
    text: you have the right to obtain human review and to contest the decision
  role:
    text: is the data controller for personal data processed in connection with AsterPay services.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloud and hosting providers (Cloudflare, Railway, Supabase) for application infrastructure
    url: null
  transfers:
  - mechanism: SCC
    text: Where personal data is transferred outside the European Economic Area, we rely on Standard Contractual Clauses (SCCs) or other approved transfer mechanisms under Chapter V GDPR.
  - mechanism: DPF
    text: Google may process this data outside the EU under the EU Standard Contractual Clauses and the EU-US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AsterPay
provenance_date: '2026-11-09'
provider_name: AsterPay
provider_slug: asterpay-io
slug: asterpay-io-privacy-policy
source_date: '2026-11-09'
source_filename: asterpay-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asterpay.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AsterPay\naid: asterpay-io\nurl: https://asterpay.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: is the data controller for personal data processed in connection with AsterPay services.\ndata_categories:\n- category: identifying\n  text: 'Account & merchant data: name, business email, role, company name, VAT ID, registered address, dashboard\n    credentials.'\n- category: financial\n  text: 'Transaction & settlement data: transaction hashes, amounts, timestamps, source and destination wallet addresses,\n    IBAN/BIC of beneficiary accounts, conversion rates, fee breakdowns, refund\
  \ and chargeback records.'\n- category: behavioral\n  text: 'KYA (Know Your Agent) data: agent identifiers (e.g. ERC-8004 ID), wallet addresses, behavioural signals,\n    operator attestations, Trust Score components.'\n- category: device\n  text: 'Technical data: IP address, user agent, request headers, API key identifiers (hashed), error and rate-limit\n    logs.'\n- category: communication\n  text: 'Communications: support tickets, partnership emails, scheduling data via cal.eu/asterpay.'\n- category: other\n  text: 'Sanctions screening data: screening verdicts and identifiers exchanged with our enterprise sanctions /\n    AML screening provider against EU, UN, OFAC and HM Treasury lists.'\npurposes:\n- purpose: service provision\n  text: 'Provision of services (Art. 6(1)(b) GDPR — contract): operating accounts, processing payments, computing\n    Trust Score, executing EUR settlement.'\n- purpose: legal compliance\n  text: 'Compliance with legal obligations (Art. 6(1)(c) GDPR): KYB,\
  \ AML, sanctions screening, Travel Rule, VAT,\n    MiCA-related record keeping, EU AI Act transparency.'\n- purpose: legitimate interests\n  text: 'Legitimate interests (Art. 6(1)(f) GDPR): fraud prevention, security monitoring, abuse detection, product\n    analytics, partner due diligence.'\n- purpose: consent-based processing\n  text: 'Consent (Art. 6(1)(a) GDPR): marketing communications, non-essential cookies and any features explicitly\n    described as opt-in.'\nretention:\n- scope: KYB and AML records\n  period: 5 years after end of business relationship\n  text: 'KYB and AML records: retained for the periods required by EU AML legislation (currently 5 years after end\n    of business relationship, extendable to 10 years where mandated).'\n- scope: transaction and settlement records\n  period: minimum 5 years\n  text: 'Transaction and settlement records: minimum 5 years.'\n- scope: technical logs\n  period: rolling 90 days\n  text: 'Technical logs: rolling 90 days unless retained\
  \ longer for security investigation.'\nresidency:\n- region: EU\n  text: Cloud and hosting providers (Cloudflare, Railway, Supabase) for application infrastructure, with EU data-residency\n    options where available\ntransfers:\n- mechanism: SCC\n  text: Where personal data is transferred outside the European Economic Area, we rely on Standard Contractual Clauses\n    (SCCs) or other approved transfer mechanisms under Chapter V GDPR.\n- mechanism: DPF\n  text: Google may process this data outside the EU under the EU Standard Contractual Clauses and the EU-US Data\n    Privacy Framework.\nsubprocessors:\n  url: null\n  text: Cloud and hosting providers (Cloudflare, Railway, Supabase) for application infrastructure\ndpa:\n  available: true\n  url: null\n  text: All processors are bound by Art. 28 GDPR data-processing agreements.\ndeletion:\n  route: request under data-subject rights\n  text: erasure (subject to retention obligations)\nrights:\n- right: GDPR rights\n  text: access, rectification,\
  \ erasure (subject to retention obligations), restriction, data portability, objection\n    to processing based on legitimate interests, and to withdraw consent.\n- right: human review of automated decisions\n  text: you have the right to obtain human review and to contest the decision\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asterpay-io/privacy/asterpay-io-privacy-policy.yml
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
summary_line: 22 quoted statements, read from AsterPay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Fintech
- Artificial Intelligence
- EUR
- Settlement
---
