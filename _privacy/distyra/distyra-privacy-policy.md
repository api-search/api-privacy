---
api_specs:
- filename: distyra-authentication-api-openapi.yml
  format: yaml
  label: Brightfield Software Authentication API
  slug: distyra-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-authentication-api-openapi.yml
- filename: distyra-billing-api-openapi.yml
  format: yaml
  label: Brightfield Software Billing API
  slug: distyra-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-billing-api-openapi.yml
- filename: distyra-catalog-api-openapi.yml
  format: yaml
  label: Brightfield Software Catalog API
  slug: distyra-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-catalog-api-openapi.yml
- filename: distyra-connect-api-openapi.yml
  format: yaml
  label: Brightfield Software Connect API
  slug: distyra-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-connect-api-openapi.yml
- filename: distyra-enrichment-api-openapi.yml
  format: yaml
  label: Brightfield Software Enrichment API
  slug: distyra-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-enrichment-api-openapi.yml
- filename: distyra-feedback-api-openapi.yml
  format: yaml
  label: Brightfield Software Feedback API
  slug: distyra-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-feedback-api-openapi.yml
- filename: distyra-system-api-openapi.yml
  format: yaml
  label: Brightfield Software System API
  slug: distyra-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-system-api-openapi.yml
- filename: distyra-underwriting-api-openapi.yml
  format: yaml
  label: Brightfield Software Underwriting API
  slug: distyra-underwriting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-underwriting-api-openapi.yml
- filename: distyra-webhooks-api-openapi.yml
  format: yaml
  label: Brightfield Software Webhooks API
  slug: distyra-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/distyra/openapi/distyra-webhooks-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and identity data (name, work email, organisation, authentication identifiers)
  - category: financial
    text: Billing and tax data (billing contact, company details, VAT ID, payment status)
  - category: device
    text: Signup record (the IP address and browser of the request that created your organisation)
  - category: behavioral
    text: Usage and administrative audit logs (API calls, endpoints, timestamps, key and acting-user attribution)
  - category: communication
    text: Communications (emails, contact-form messages, support requests)
  deletion:
    route: Account owners can delete their account in the portal settings; deletion is permanent after a 30-day recovery window, or right away on request
    text: delete your account (erasure), which freezes access immediately and permanently deletes your data after a 30-day recovery window, or right away on request
  dpa:
    available: true
    text: under a GDPR Article 28 Data Processing Agreement
    url: null
  purposes:
  - purpose: Account operation and service provision
    text: Create and run your account, authenticate you, provide the service, support you
  - purpose: Billing and tax compliance
    text: Take payment, issue compliant EU VAT invoices, meet accounting duties
  - purpose: Security and abuse prevention
    text: Meter usage accurately, secure the service, prevent abuse, give you an auditable request log
  - purpose: Enrichment of customer transaction data
    text: to produce the result they asked for, on their documented instructions
  - purpose: Advertising measurement
    text: Tell the ad platform that the click led to an enquiry, so we can tell which advertising is worth paying for
  residency:
  - region: European Union / EEA
    text: We process personal data within the European Union or wider EEA, on EU-owned infrastructure, across a primary region and a warm-standby region.
  retention:
  - period: the term of your agreement plus 90 days
    scope: Account, identity and portal data
    text: account, identity, and portal data for the term of your agreement plus 90 days
  - period: 7 years
    scope: Billing, invoicing and tax records
    text: billing, invoicing, and tax records for 7 years, as EU and Dutch law require
  - period: the term plus 2 years
    scope: Usage and administrative audit logs
    text: usage and administrative audit logs for the term plus 2 years
  - period: 30 days
    scope: Application and infrastructure logs
    text: application and infrastructure logs for 30 days, and edge access logs for up to 90 days
  - period: 30 days
    scope: Signup IP address and browser
    text: the IP address and browser of an organisation's signup for 30 days
  - period: 7 days
    scope: Raw uploaded statement files (processor)
    text: raw uploaded statement files are deleted within 7 days by default
  rights:
  - right: Access
    text: Under the GDPR you have the right to access your personal data
  - right: Correction and erasure
    text: to have it corrected or erased
  - right: Restriction and objection
    text: to restrict or object to its processing
  - right: Portability
    text: to data portability
  - right: Withdraw consent
    text: to withdraw consent where we rely on it (our current processing does not rely on consent)
  - right: Complaint to supervisory authority
    text: You may also lodge a complaint with a supervisory authority.
  role:
    text: We are the controller for the personal data of our own customers and site visitors
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal data, and we do not use customer transaction data to train any AI model, including our own.
  subprocessors:
    text: The current named providers, with their roles, countries, and which of them ever touch customer transaction data, are published on our EU hosting page
    url: https://www.distyra.eu/privacy-policy
  transfers:
  - mechanism: DPF
    text: currently Google, in the United States, under its standard terms and the EU-US Data Privacy Framework
  - mechanism: SCC
    text: including an adequacy decision or the Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Brightfield Software
provenance_date: '2026-11-09'
provider_name: Brightfield Software
provider_slug: distyra
slug: distyra-privacy-policy
source_date: '2026-11-09'
source_filename: distyra-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.distyra.eu/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Brightfield Software\naid: distyra\nurl: https://www.distyra.eu/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for the personal data of our own customers and site visitors\ndata_categories:\n- category: identifying\n  text: Account and identity data (name, work email, organisation, authentication identifiers)\n- category: financial\n  text: Billing and tax data (billing contact, company details, VAT ID, payment status)\n- category: device\n  text: Signup record (the IP address and browser of the request that created your organisation)\n- category: behavioral\n\
  \  text: Usage and administrative audit logs (API calls, endpoints, timestamps, key and acting-user attribution)\n- category: communication\n  text: Communications (emails, contact-form messages, support requests)\npurposes:\n- purpose: Account operation and service provision\n  text: Create and run your account, authenticate you, provide the service, support you\n- purpose: Billing and tax compliance\n  text: Take payment, issue compliant EU VAT invoices, meet accounting duties\n- purpose: Security and abuse prevention\n  text: Meter usage accurately, secure the service, prevent abuse, give you an auditable request log\n- purpose: Enrichment of customer transaction data\n  text: to produce the result they asked for, on their documented instructions\n- purpose: Advertising measurement\n  text: Tell the ad platform that the click led to an enquiry, so we can tell which advertising is worth paying\n    for\nretention:\n- scope: Account, identity and portal data\n  period: the term of your\
  \ agreement plus 90 days\n  text: account, identity, and portal data for the term of your agreement plus 90 days\n- scope: Billing, invoicing and tax records\n  period: 7 years\n  text: billing, invoicing, and tax records for 7 years, as EU and Dutch law require\n- scope: Usage and administrative audit logs\n  period: the term plus 2 years\n  text: usage and administrative audit logs for the term plus 2 years\n- scope: Application and infrastructure logs\n  period: 30 days\n  text: application and infrastructure logs for 30 days, and edge access logs for up to 90 days\n- scope: Signup IP address and browser\n  period: 30 days\n  text: the IP address and browser of an organisation's signup for 30 days\n- scope: Raw uploaded statement files (processor)\n  period: 7 days\n  text: raw uploaded statement files are deleted within 7 days by default\nresidency:\n- region: European Union / EEA\n  text: We process personal data within the European Union or wider EEA, on EU-owned infrastructure,\
  \ across a primary\n    region and a warm-standby region.\ntransfers:\n- mechanism: DPF\n  text: currently Google, in the United States, under its standard terms and the EU-US Data Privacy Framework\n- mechanism: SCC\n  text: including an adequacy decision or the Standard Contractual Clauses\nsubprocessors:\n  url: https://www.distyra.eu/privacy-policy\n  text: The current named providers, with their roles, countries, and which of them ever touch customer transaction\n    data, are published on our EU hosting page\ndpa:\n  available: true\n  url: null\n  text: under a GDPR Article 28 Data Processing Agreement\ndeletion:\n  route: Account owners can delete their account in the portal settings; deletion is permanent after a 30-day recovery\n    window, or right away on request\n  text: delete your account (erasure), which freezes access immediately and permanently deletes your data after\n    a 30-day recovery window, or right away on request\nrights:\n- right: Access\n  text: Under the\
  \ GDPR you have the right to access your personal data\n- right: Correction and erasure\n  text: to have it corrected or erased\n- right: Restriction and objection\n  text: to restrict or object to its processing\n- right: Portability\n  text: to data portability\n- right: Withdraw consent\n  text: to withdraw consent where we rely on it (our current processing does not rely on consent)\n- right: Complaint to supervisory authority\n  text: You may also lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal data, and we do not use customer transaction data to train any AI model, including\n    our own.\n"
source_yaml_url: https://artifacts.apis.io/distyra/privacy/distyra-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Brightfield Software's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Fintech
- European
---
