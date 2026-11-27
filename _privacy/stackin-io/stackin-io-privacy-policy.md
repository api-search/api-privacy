---
api_specs:
- filename: stackin-io-openapi-generated.yml
  format: yaml
  label: stackin-io API
  slug: stackin-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackin-io/openapi/_ae-authored/stackin-io-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: full name and email, used to sign in.'
  - category: contact
    text: 'Company: legal name, tax registrations and address, required by law to issue an invoice.'
  - category: financial
    text: 'Payment: when you subscribe to a plan or buy credits, the card is processed by Stripe. We never receive or store your card number.'
  - category: device
    text: 'Usage and diagnostics: access logs, IP address, API calls and errors, used to run the service, investigate failures and prevent abuse.'
  deletion:
    route: Close the account on the My account page, or write to dpo@stackin.io
    text: You can edit your name and email on the My account page, and close the account there — that anonymizes your login data. For anything else, write to dpo@stackin.io.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Legal obligation
    text: Legal obligation, for the fields fiscal law requires.
  - purpose: Contract performance
    text: Performance of a contract, to keep your account, issue your invoices and bill for the service.
  - purpose: Security and fraud prevention
    text: Legitimate interest, for security, fraud prevention and diagnosing failures.
  residency:
  - region: United States
    text: All of stackin's infrastructure runs in the United States
  retention:
  - period: as long as the account exists
    scope: Account data
    text: Account data for as long as the account exists.
  - period: at least five years after issuance
    scope: Invoices and company records
    text: Invoices and your company's records for at least five years after issuance
  - period: six months
    scope: Access logs
    text: Access logs for six months , under the Brazilian Internet Act .
  rights:
  - right: Confirmation and access
    text: The LGPD gives you confirmation and access, correction, anonymization or deletion, portability, information about sharing, and the right to withdraw consent.
  role:
    text: The controller is Fernando Celmer, CNPJ 68.849.750/0001-76, in Florianópolis, Brazil.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data and do not share it for third-party marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Those transfers rely on the contractual clauses and safeguards those providers offer, under article 33 of the LGPD .
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: stackin-io
provenance_date: '2026-11-10'
provider_name: stackin-io
provider_slug: stackin-io
slug: stackin-io-privacy-policy
source_date: '2026-11-10'
source_filename: stackin-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.stackin.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: stackin-io\naid: stackin-io\nurl: https://app.stackin.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is Fernando Celmer, CNPJ 68.849.750/0001-76, in Florianópolis, Brazil.\ndata_categories:\n- category: identifying\n  text: 'Account: full name and email, used to sign in.'\n- category: contact\n  text: 'Company: legal name, tax registrations and address, required by law to issue an invoice.'\n- category: financial\n  text: 'Payment: when you subscribe to a plan or buy credits, the card is processed by Stripe. We never receive\n    or store your card number.'\n- category:\
  \ device\n  text: 'Usage and diagnostics: access logs, IP address, API calls and errors, used to run the service, investigate\n    failures and prevent abuse.'\npurposes:\n- purpose: Legal obligation\n  text: Legal obligation, for the fields fiscal law requires.\n- purpose: Contract performance\n  text: Performance of a contract, to keep your account, issue your invoices and bill for the service.\n- purpose: Security and fraud prevention\n  text: Legitimate interest, for security, fraud prevention and diagnosing failures.\nretention:\n- scope: Account data\n  period: as long as the account exists\n  text: Account data for as long as the account exists.\n- scope: Invoices and company records\n  period: at least five years after issuance\n  text: Invoices and your company's records for at least five years after issuance\n- scope: Access logs\n  period: six months\n  text: Access logs for six months , under the Brazilian Internet Act .\nresidency:\n- region: United States\n  text: All of\
  \ stackin's infrastructure runs in the United States\ntransfers:\n- mechanism: other\n  text: Those transfers rely on the contractual clauses and safeguards those providers offer, under article 33 of\n    the LGPD .\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Close the account on the My account page, or write to dpo@stackin.io\n  text: You can edit your name and email on the My account page, and close the account there — that anonymizes your\n    login data. For anything else, write to dpo@stackin.io.\nrights:\n- right: Confirmation and access\n  text: The LGPD gives you confirmation and access, correction, anonymization or deletion, portability, information\n    about sharing, and the right to withdraw consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data and do not share it for third-party marketing.\n"
source_yaml_url: https://artifacts.apis.io/stackin-io/privacy/stackin-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from stackin-io's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Tax
- Brazil
- Invoicing
- Software-as-a-Service
---
