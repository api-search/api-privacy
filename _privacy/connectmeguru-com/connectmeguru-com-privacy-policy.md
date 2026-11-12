---
api_specs:
- filename: connectmeguru-com-agentic-api-openapi.yml
  format: yaml
  label: ConnectMeGuru Agentic API
  slug: connectmeguru-com-agentic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connectmeguru-com/openapi/connectmeguru-com-agentic-api-openapi.yml
- filename: connectmeguru-com-discount-api-openapi.yml
  format: yaml
  label: ConnectMeGuru Discount API
  slug: connectmeguru-com-discount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connectmeguru-com/openapi/connectmeguru-com-discount-api-openapi.yml
- filename: connectmeguru-com-products-api-openapi.yml
  format: yaml
  label: ConnectMeGuru Products API
  slug: connectmeguru-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connectmeguru-com/openapi/connectmeguru-com-products-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address provided for account creation, login verification, and delivery of your eSIM profile, activation QR codes, and purchase invoices.
  - category: identifying
    text: Internal transaction identifiers, promotional discount codes, and digital travel wallet balances (denominated in USD).
  - category: device
    text: Originating IP address and user-agent string, automatically recorded during checkouts, top-ups, and balance operations
  - category: location
    text: Calculating accurate destination and regional taxes (such as European Union VAT OSS) based on originating network location.
  deletion:
    route: Request via support email
    text: You may request the permanent deletion of your account and associated personal data, subject only to mandatory legal tax retention obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: Provisioning on-demand cellular data profiles via telecommunications carrier interfaces.
  - purpose: Tax calculation
    text: Calculating accurate destination and regional taxes (such as European Union VAT OSS) based on originating network location.
  - purpose: Fraud prevention
    text: Safeguarding our platform against payment fraud, spam, and duplicate transactions.
  - purpose: Account login
    text: Authorizing secure customer login sessions via one-time email verification codes (OTPs).
  retention:
  - period: five (5) years
    scope: Financial and invoicing records
    text: 'Financial & Invoicing Records: Retained for five (5) years in accordance with international tax compliance, accounting standards, and statutory audit obligations.'
  - period: the duration of your data plan validity plus ninety (90) days
    scope: eSIM operational records
    text: 'eSIM Operational Records: Retained for the duration of your data plan validity plus ninety (90) days to support data top-ups and customer service inquiries.'
  - period: fifteen (15) minutes
    scope: One-time verification codes
    text: One-time verification codes expire automatically within fifteen (15) minutes
  - period: ninety (90) days
    scope: Server and security logs
    text: IP address logs recorded for tax and security verification are archived in encrypted storage and routinely cycled after ninety (90) days.
  rights:
  - right: Access and portability
    text: You may request a machine-readable export of all personal data and order history associated with your account.
  - right: Correction
    text: You may update or correct your account information at any time.
  - right: Erasure
    text: You may request the permanent deletion of your account and associated personal data, subject only to mandatory legal tax retention obligations.
  - right: Revocation of AI access
    text: You can disconnect and revoke ChatGPT or API tool authorizations at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal data to third parties or advertising networks.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ConnectMeGuru
provenance_date: '2026-11-09'
provider_name: ConnectMeGuru
provider_slug: connectmeguru-com
slug: connectmeguru-com-privacy-policy
source_date: '2026-11-09'
source_filename: connectmeguru-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.connectmeguru.com/pages/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ConnectMeGuru\naid: connectmeguru-com\nurl: https://www.connectmeguru.com/pages/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address provided for account creation, login verification, and delivery of your eSIM profile, activation\n    QR codes, and purchase invoices.\n- category: identifying\n  text: Internal transaction identifiers, promotional discount codes, and digital travel wallet balances (denominated\n    in USD).\n- category: device\n  text: Originating IP address and user-agent string, automatically recorded during\
  \ checkouts, top-ups, and balance\n    operations\n- category: location\n  text: Calculating accurate destination and regional taxes (such as European Union VAT OSS) based on originating\n    network location.\npurposes:\n- purpose: Service delivery\n  text: Provisioning on-demand cellular data profiles via telecommunications carrier interfaces.\n- purpose: Tax calculation\n  text: Calculating accurate destination and regional taxes (such as European Union VAT OSS) based on originating\n    network location.\n- purpose: Fraud prevention\n  text: Safeguarding our platform against payment fraud, spam, and duplicate transactions.\n- purpose: Account login\n  text: Authorizing secure customer login sessions via one-time email verification codes (OTPs).\nretention:\n- scope: Financial and invoicing records\n  period: five (5) years\n  text: 'Financial & Invoicing Records: Retained for five (5) years in accordance with international tax compliance,\n    accounting standards, and statutory audit\
  \ obligations.'\n- scope: eSIM operational records\n  period: the duration of your data plan validity plus ninety (90) days\n  text: 'eSIM Operational Records: Retained for the duration of your data plan validity plus ninety (90) days to\n    support data top-ups and customer service inquiries.'\n- scope: One-time verification codes\n  period: fifteen (15) minutes\n  text: One-time verification codes expire automatically within fifteen (15) minutes\n- scope: Server and security logs\n  period: ninety (90) days\n  text: IP address logs recorded for tax and security verification are archived in encrypted storage and routinely\n    cycled after ninety (90) days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via support email\n  text: You may request the permanent deletion of your account and associated personal data, subject only to mandatory\n    legal tax retention obligations.\n\
  rights:\n- right: Access and portability\n  text: You may request a machine-readable export of all personal data and order history associated with your account.\n- right: Correction\n  text: You may update or correct your account information at any time.\n- right: Erasure\n  text: You may request the permanent deletion of your account and associated personal data, subject only to mandatory\n    legal tax retention obligations.\n- right: Revocation of AI access\n  text: You can disconnect and revoke ChatGPT or API tool authorizations at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal data to third parties or advertising networks.\n"
source_yaml_url: https://artifacts.apis.io/connectmeguru-com/privacy/connectmeguru-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from ConnectMeGuru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- eSIM
- Travel
- Telecommunications
- Mobile Data
- Connectivity
- Wholesale
- Model Context Protocol
- AI Agents
---
