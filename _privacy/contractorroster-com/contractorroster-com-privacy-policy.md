---
api_specs:
- filename: contractorroster-com-billing-api-openapi.yml
  format: yaml
  label: ContractorRoster Billing API
  slug: contractorroster-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contractorroster-com/openapi/contractorroster-com-billing-api-openapi.yml
- filename: contractorroster-com-contractors-api-openapi.yml
  format: yaml
  label: ContractorRoster Contractors API
  slug: contractorroster-com-contractors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contractorroster-com/openapi/contractorroster-com-contractors-api-openapi.yml
- filename: contractorroster-com-coverage-api-openapi.yml
  format: yaml
  label: ContractorRoster Coverage API
  slug: contractorroster-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contractorroster-com/openapi/contractorroster-com-coverage-api-openapi.yml
- filename: contractorroster-com-reference-api-openapi.yml
  format: yaml
  label: ContractorRoster Reference API
  slug: contractorroster-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contractorroster-com/openapi/contractorroster-com-reference-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect your email address and the information required to process your payment.
  - category: identifying
    text: Identifiers (business name, license number, business address, phone, email)
  - category: financial
    text: Payment card data is processed directly by Stripe and is never stored on our servers.
  - category: device
    text: We collect standard web server logs, including IP addresses, browser type, pages visited, and referral URLs.
  - category: professional
    text: professional or commercial information (trade, license type, status, issue and expiration dates)
  - category: location
    text: project location (ZIP code)
  deletion:
    route: email request to privacy contact or request form at contractorroster.com/opt-out
    text: If you wish to request deletion of your email address from our records, contact us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: process payment and deliver CSV
    text: To process your payment and deliver your CSV to your email address.
  - purpose: fraud and abuse prevention
    text: To detect and prevent fraud, abuse, or unauthorized use.
  - purpose: aggregate usage understanding
    text: To understand how the service is used in aggregate (e.g., which states and trades are most searched) so we can improve it.
  retention:
  - period: null
    scope: email address and order record
    text: We retain your email address and order record for as long as necessary to provide support, comply with legal obligations, and resolve disputes.
  - period: null
    scope: project requests
    text: We retain project requests only as long as they are needed to make and support introductions
  rights:
  - right: opt out of sale or sharing
    text: Opt out of the sale or sharing of your personal information.
  - right: deletion
    text: Request deletion of your personal information from our dataset.
  - right: know
    text: Request to know the categories and specific pieces of personal information we hold about you
  - right: correction
    text: Request correction of inaccurate personal information.
  role:
    text: ContractorRoster, a brand of JB Alan LLC, operates contractorroster.com.
    value: controller
  sale_or_sharing:
    stance: allowed
    text: ContractorRoster sells business records — licensed contractors, and additional categories such as dentists, chiropractors, restaurants, and retail businesses — which can include personal information
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ContractorRoster
provenance_date: '2026-11-09'
provider_name: ContractorRoster
provider_slug: contractorroster-com
slug: contractorroster-com-privacy-policy
source_date: '2026-11-09'
source_filename: contractorroster-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://contractorroster.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ContractorRoster\naid: contractorroster-com\nurl: https://contractorroster.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ContractorRoster, a brand of JB Alan LLC, operates contractorroster.com.\ndata_categories:\n- category: contact\n  text: We collect your email address and the information required to process your payment.\n- category: identifying\n  text: Identifiers (business name, license number, business address, phone, email)\n- category: financial\n  text: Payment card data is processed directly by Stripe and is never stored on our servers.\n- category: device\n  text:\
  \ We collect standard web server logs, including IP addresses, browser type, pages visited, and referral URLs.\n- category: professional\n  text: professional or commercial information (trade, license type, status, issue and expiration dates)\n- category: location\n  text: project location (ZIP code)\npurposes:\n- purpose: process payment and deliver CSV\n  text: To process your payment and deliver your CSV to your email address.\n- purpose: fraud and abuse prevention\n  text: To detect and prevent fraud, abuse, or unauthorized use.\n- purpose: aggregate usage understanding\n  text: To understand how the service is used in aggregate (e.g., which states and trades are most searched) so\n    we can improve it.\nretention:\n- scope: email address and order record\n  period: null\n  text: We retain your email address and order record for as long as necessary to provide support, comply with legal\n    obligations, and resolve disputes.\n- scope: project requests\n  period: null\n  text: We\
  \ retain project requests only as long as they are needed to make and support introductions\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to privacy contact or request form at contractorroster.com/opt-out\n  text: If you wish to request deletion of your email address from our records, contact us at [email protected]\n    .\nrights:\n- right: opt out of sale or sharing\n  text: Opt out of the sale or sharing of your personal information.\n- right: deletion\n  text: Request deletion of your personal information from our dataset.\n- right: know\n  text: Request to know the categories and specific pieces of personal information we hold about you\n- right: correction\n  text: Request correction of inaccurate personal information.\nsale_or_sharing:\n  stance: allowed\n  text: ContractorRoster sells business records — licensed contractors, and additional categories such as dentists,\n\
  \    chiropractors, restaurants, and retail businesses — which can include personal information\n"
source_yaml_url: https://artifacts.apis.io/contractorroster-com/privacy/contractorroster-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from ContractorRoster's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Contractors
- Business Data
- Licensing Records
- Lead Generation
- Data Enrichment
- MCP
- Construction
---
