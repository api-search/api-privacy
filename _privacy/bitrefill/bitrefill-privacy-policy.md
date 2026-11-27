---
api_specs:
- filename: bitrefill-account-api-openapi.yml
  format: yaml
  label: Bitrefill Account API
  slug: bitrefill-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-account-api-openapi.yml
- filename: bitrefill-checkout-api-openapi.yml
  format: yaml
  label: Bitrefill Checkout API
  slug: bitrefill-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-checkout-api-openapi.yml
- filename: bitrefill-discovery-api-openapi.yml
  format: yaml
  label: Bitrefill Discovery API
  slug: bitrefill-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-discovery-api-openapi.yml
- filename: bitrefill-payments-api-openapi.yml
  format: yaml
  label: Bitrefill Payments API
  slug: bitrefill-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitrefill/openapi/bitrefill-payments-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Basic identification data email address; phone number
  - category: contact
    text: address (and respective proof of address)
  - category: financial
    text: Financial data tax identification number; proof of income
  - category: financial
    text: Wallet data wallet address; wallet provider; bank identification number; financial service provider
  - category: biometric
    text: Bitrefill may collect biometric data in the context of an identification verification procedure.
  - category: location
    text: IP address and geolocation
  - category: device
    text: Device, browser and app data device; operating system; browser; plugins; network; IP address
  - category: behavioral
    text: Analytics data clicks; actions; time spent; age group; geography; survey responses
  - category: communication
    text: Customer Support data data provided to Customer Support or in response to customer surveys
  - category: professional
    text: Professional data employer registration number (or comparable number issued by a government)
  deletion:
    route: Request to support@bitrefill.com
    text: If you request us to delete your personal data, we will comply with that request to the extent possible.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Open and maintain account
    text: To open and maintain your account.
  - purpose: Sell products and provide services
    text: To sell you the Products and provide you with services
  - purpose: Advertising, analytics and recommendations
    text: For advertisement, data analytics and to provide recommendations
  - purpose: Legal and compliance
    text: To comply with internal and external policies, guidelines, rules and legislation
  - purpose: Hiring
    text: To review HR applications and make hiring decisions
  residency:
  - region: EEA
    text: Although we strive to ensure that your personal data remains within the EEA whenever possible
  retention:
  - period: a minimum of 7 years
    scope: Tax information
    text: We will keep information that is relevant for tax purposes for a minimum of 7 years.
  - period: 30 (thirty) days
    scope: Chats with Bitrefill Assistant
    text: Your chats with Bitrefill Assistant, including transcriptions of voice messages, are retained for 30 (thirty) days
  - period: null
    scope: Job applications
    text: We will keep information about your application for a job at Bitrefill until the moment we fill out the position
  - period: null
    scope: Account data
    text: If you have an account with us, we will keep your data collected in relation to your account activity for as long as the account exists.
  rights:
  - right: Access, correct or erase
    text: Right to access, correct or erase your personal data.
  - right: Object to processing
    text: Right to object to processing.
  - right: Restrict processing
    text: Right to restrict processing.
  - right: Portability
    text: Right to transfer your personal data.
  - right: Withdraw consent
    text: Right to withdraw consent.
  role:
    text: Airfill is a data controller of the personal data collected through our websites www.bitrefill.com and www.airfill.com
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Those providers are identified, with links to their privacy policies, in Section 3.1.
    url: null
  transfers:
  - mechanism: adequacy
    text: we rely on adequacy decisions from the European Commission, whenever possible
  - mechanism: SCC
    text: and on the European Commission’s Standard Contractual Clauses to enable the transfer of data to third countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bitrefill
provenance_date: '2026-11-09'
provider_name: Bitrefill
provider_slug: bitrefill
slug: bitrefill-privacy-policy
source_date: '2026-11-09'
source_filename: bitrefill-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bitrefill.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bitrefill\naid: bitrefill\nurl: https://www.bitrefill.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Airfill is a data controller of the personal data collected through our websites www.bitrefill.com and www.airfill.com\ndata_categories:\n- category: identifying\n  text: Basic identification data email address; phone number\n- category: contact\n  text: address (and respective proof of address)\n- category: financial\n  text: Financial data tax identification number; proof of income\n- category: financial\n  text: Wallet data wallet address; wallet provider; bank identification\
  \ number; financial service provider\n- category: biometric\n  text: Bitrefill may collect biometric data in the context of an identification verification procedure.\n- category: location\n  text: IP address and geolocation\n- category: device\n  text: Device, browser and app data device; operating system; browser; plugins; network; IP address\n- category: behavioral\n  text: Analytics data clicks; actions; time spent; age group; geography; survey responses\n- category: communication\n  text: Customer Support data data provided to Customer Support or in response to customer surveys\n- category: professional\n  text: Professional data employer registration number (or comparable number issued by a government)\npurposes:\n- purpose: Open and maintain account\n  text: To open and maintain your account.\n- purpose: Sell products and provide services\n  text: To sell you the Products and provide you with services\n- purpose: Advertising, analytics and recommendations\n  text: For advertisement,\
  \ data analytics and to provide recommendations\n- purpose: Legal and compliance\n  text: To comply with internal and external policies, guidelines, rules and legislation\n- purpose: Hiring\n  text: To review HR applications and make hiring decisions\nretention:\n- scope: Tax information\n  period: a minimum of 7 years\n  text: We will keep information that is relevant for tax purposes for a minimum of 7 years.\n- scope: Chats with Bitrefill Assistant\n  period: 30 (thirty) days\n  text: Your chats with Bitrefill Assistant, including transcriptions of voice messages, are retained for 30 (thirty)\n    days\n- scope: Job applications\n  period: null\n  text: We will keep information about your application for a job at Bitrefill until the moment we fill out the\n    position\n- scope: Account data\n  period: null\n  text: If you have an account with us, we will keep your data collected in relation to your account activity for\n    as long as the account exists.\nresidency:\n- region: EEA\n\
  \  text: Although we strive to ensure that your personal data remains within the EEA whenever possible\ntransfers:\n- mechanism: adequacy\n  text: we rely on adequacy decisions from the European Commission, whenever possible\n- mechanism: SCC\n  text: and on the European Commission’s Standard Contractual Clauses to enable the transfer of data to third countries.\nsubprocessors:\n  url: null\n  text: Those providers are identified, with links to their privacy policies, in Section 3.1.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to support@bitrefill.com\n  text: If you request us to delete your personal data, we will comply with that request to the extent possible.\nrights:\n- right: Access, correct or erase\n  text: Right to access, correct or erase your personal data.\n- right: Object to processing\n  text: Right to object to processing.\n- right: Restrict processing\n  text: Right to restrict processing.\n- right: Portability\n  text: Right to transfer\
  \ your personal data.\n- right: Withdraw consent\n  text: Right to withdraw consent.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bitrefill/privacy/bitrefill-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 30 quoted statements, read from Bitrefill's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Gift Cards
- Mobile Top-Up
---
