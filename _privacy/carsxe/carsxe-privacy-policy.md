---
api_specs:
- filename: carsxe-specifications-api-openapi.yml
  format: yaml
  label: CarsXE Specifications API
  slug: carsxe-specifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-specifications-api-openapi.yml
- filename: carsxe-market-value-api-openapi.yml
  format: yaml
  label: CarsXE Market Value API
  slug: carsxe-market-value-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-market-value-api-openapi.yml
- filename: carsxe-recalls-api-openapi.yml
  format: yaml
  label: CarsXE Recalls API
  slug: carsxe-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-recalls-api-openapi.yml
- filename: carsxe-history-api-openapi.yml
  format: yaml
  label: CarsXE History API
  slug: carsxe-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-history-api-openapi.yml
- filename: carsxe-images-api-openapi.yml
  format: yaml
  label: CarsXE Images API
  slug: carsxe-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-images-api-openapi.yml
- filename: carsxe-recognition-api-openapi.yml
  format: yaml
  label: CarsXE Recognition API
  slug: carsxe-recognition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-recognition-api-openapi.yml
- filename: carsxe-year-make-model-api-openapi.yml
  format: yaml
  label: CarsXE Year Make Model API
  slug: carsxe-year-make-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-year-make-model-api-openapi.yml
- filename: carsxe-lien-theft-api-openapi.yml
  format: yaml
  label: CarsXE Lien & Theft API
  slug: carsxe-lien-theft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-lien-theft-api-openapi.yml
- filename: carsxe-auth-api-openapi.yml
  format: yaml
  label: CarsXE Auth API
  slug: carsxe-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-auth-api-openapi.yml
- filename: carsxe-plate-decoder-api-openapi.yml
  format: yaml
  label: CarsXE Plate Decoder API
  slug: carsxe-plate-decoder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carsxe/openapi/carsxe-plate-decoder-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Users may be asked for, as appropriate, name, email address, mailing address, phone number, credit card information.
  - category: identifying
    text: Account and authentication API keys, OAuth tokens, and account identifiers used to authorize a request
  - category: device
    text: Non-personal identification information may include the browser name, the type of computer and technical information about Users means of connection to our Site
  - category: financial
    text: Account profile and payment records associated with a CarsXE subscription
  deletion:
    route: Contact us
    text: Users may request that associated personally identification information in our system is removed by contacting us at https://carsxe.com/contact .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Personalize user experience
    text: To personalize user experience.
  - purpose: Process transactions
    text: To process transactions. We may use the information Users provide about themselves when placing an order only to provide service to that order.
  - purpose: Send periodic emails
    text: To send periodic emails. The email address Users provide for order processing will be used to send them ordered reports, updates pertaining to their order, and promotions related to used car buying.
  - purpose: Provide vehicle-data lookup via API/MCP
    text: We process this information to provide the requested vehicle-data lookup; to authenticate and authorize the request; to bill usage and enforce plan limits; to operate, secure, and debug the API and MCP service; and to comply with applicable law.
  retention:
  - period: about 90 days
    scope: API and MCP logs and tool payloads
    text: 'API and MCP logs and tool payloads: about 90 days, then we delete them or keep only aggregated records.'
  - period: 24 to 72 hours
    scope: Images fetched from customer URLs
    text: 'Images fetched from customer URLs: 24 to 72 hours, then we delete them.'
  - period: for the life of the account
    scope: Account and billing records
    text: 'Account and billing records: for the life of the account, and for a limited time after the account is closed.'
  rights:
  - right: Request removal of personal information
    text: Users may request that associated personally identification information in our system is removed by contacting us at https://carsxe.com/contact .
  - right: Refuse to supply personal information
    text: Users can always refuse to supply personally identification information
  - right: Stop using ChatGPT app or disconnect MCP connector
    text: You can stop using the ChatGPT app or disconnect the MCP connector in that client.
  - right: Rotate or revoke API keys
    text: Account holders can rotate or revoke API keys in the CarsXE dashboard.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We may share your business name and payment history to trusted affiliates for the purpose of referral tracking as specified above.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CarsXE
provenance_date: '2026-11-09'
provider_name: CarsXE
provider_slug: carsxe
slug: carsxe-privacy-policy
source_date: '2026-11-09'
source_filename: carsxe-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carsxe.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CarsXE\naid: carsxe\nurl: https://carsxe.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Users may be asked for, as appropriate, name, email address, mailing address, phone number, credit card\n    information.\n- category: identifying\n  text: Account and authentication API keys, OAuth tokens, and account identifiers used to authorize a request\n- category: device\n  text: Non-personal identification information may include the browser name, the type of computer and technical\n    information about Users means of connection\
  \ to our Site\n- category: financial\n  text: Account profile and payment records associated with a CarsXE subscription\npurposes:\n- purpose: Personalize user experience\n  text: To personalize user experience.\n- purpose: Process transactions\n  text: To process transactions. We may use the information Users provide about themselves when placing an order\n    only to provide service to that order.\n- purpose: Send periodic emails\n  text: To send periodic emails. The email address Users provide for order processing will be used to send them\n    ordered reports, updates pertaining to their order, and promotions related to used car buying.\n- purpose: Provide vehicle-data lookup via API/MCP\n  text: We process this information to provide the requested vehicle-data lookup; to authenticate and authorize\n    the request; to bill usage and enforce plan limits; to operate, secure, and debug the API and MCP service; and\n    to comply with applicable law.\nretention:\n- scope: API and MCP\
  \ logs and tool payloads\n  period: about 90 days\n  text: 'API and MCP logs and tool payloads: about 90 days, then we delete them or keep only aggregated records.'\n- scope: Images fetched from customer URLs\n  period: 24 to 72 hours\n  text: 'Images fetched from customer URLs: 24 to 72 hours, then we delete them.'\n- scope: Account and billing records\n  period: for the life of the account\n  text: 'Account and billing records: for the life of the account, and for a limited time after the account is closed.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us\n  text: Users may request that associated personally identification information in our system is removed by contacting\n    us at https://carsxe.com/contact .\nrights:\n- right: Request removal of personal information\n  text: Users may request that associated personally identification information in our system is removed by\
  \ contacting\n    us at https://carsxe.com/contact .\n- right: Refuse to supply personal information\n  text: Users can always refuse to supply personally identification information\n- right: Stop using ChatGPT app or disconnect MCP connector\n  text: You can stop using the ChatGPT app or disconnect the MCP connector in that client.\n- right: Rotate or revoke API keys\n  text: Account holders can rotate or revoke API keys in the CarsXE dashboard.\nsale_or_sharing:\n  stance: conditional\n  text: We may share your business name and payment history to trusted affiliates for the purpose of referral tracking\n    as specified above.\n"
source_yaml_url: https://artifacts.apis.io/carsxe/privacy/carsxe-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from CarsXE's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- Vehicles
- VIN
- Vehicle Data
- License Plate
- OCR
- Automobiles
- Recalls
- Market Value
- Vehicle History
- MCP
- Agents
---
