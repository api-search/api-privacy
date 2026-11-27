---
api_specs:
- filename: racq-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: RACQ Bank Banking Account Balances API
  slug: racq-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/racq-bank/openapi/racq-bank-banking-account-balances-api-openapi.yml
- filename: racq-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: RACQ Bank Banking Account Direct Debits API
  slug: racq-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/racq-bank/openapi/racq-bank-banking-account-direct-debits-api-openapi.yml
- filename: racq-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: RACQ Bank Banking Account Scheduled Payments API
  slug: racq-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/racq-bank/openapi/racq-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: racq-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: RACQ Bank Banking Account Transactions API
  slug: racq-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/racq-bank/openapi/racq-bank-banking-account-transactions-api-openapi.yml
- filename: racq-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: RACQ Bank Banking Accounts API
  slug: racq-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/racq-bank/openapi/racq-bank-banking-accounts-api-openapi.yml
- filename: racq-bank-banking-payees-api-openapi.yml
  format: yaml
  label: RACQ Bank Banking Payees API
  slug: racq-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/racq-bank/openapi/racq-bank-banking-payees-api-openapi.yml
- filename: racq-bank-banking-products-api-openapi.yml
  format: yaml
  label: RACQ Bank Banking Products API
  slug: racq-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/racq-bank/openapi/racq-bank-banking-products-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: identity information and government related identifiers (for example, drivers license, tax file number or tax identification number)
  - category: contact
    text: Personal and contact details (including name, address, email address, phone number and/or date of birth)
  - category: financial
    text: financial information, credit information, employment-related information
  - category: location
    text: information about any requests for assistance, including location information
  - category: behavioral
    text: information about your use of our banking services and products (including internet banking)
  - category: device
    text: We record your server or IP address, the date and time of your visit, pages visited, documents downloaded
  - category: health
    text: health information (should you choose to cover a pre-existing medical condition)
  - category: communication
    text: your communication history with RACQ
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide requested product or service
    text: Generally, this is to provide you the product or service that you have requested, to process payments, for the resolution of any complaint or dispute, or to consider your employment application.
  - purpose: Verify identity
    text: verifying your identity, including where we are required to do so by law
  - purpose: Assess applications including creditworthiness
    text: considering and assessing your application for a product or service, which may include considering your creditworthiness
  - purpose: Train and deploy AI models
    text: to train, develop, and deploy artificial intelligence models, including for customer support, internal knowledge management and process optimisation and automation
  - purpose: Marketing
    text: We may use your personal information, including your contact details, to provide you with information we think will interest you about our products and services, where we have your express or inferred consent.
  rights:
  - right: Access
    text: You may request access to the personal information that we hold about you at any time from the Privacy Officer
  - right: Correction
    text: You can request that we update this information by emailing racq@racq.com.au
  - right: Marketing opt-out
    text: You may opt out at any time if you no longer wish to receive marketing information
  - right: Complaint
    text: If you believe that we have not fulfilled our obligations under the Privacy Act or you do not agree with a decision made by RACQ in relation to accessing or correcting your personal information, you can make a complaint to our Privacy Officer
  role:
    text: We are committed to handling personal information in compliance with the Privacy Act 1988 (Cth) and the Australian Privacy Principles contained within the Act.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may disclose your personal information to recipients located overseas, where permitted by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RACQ Bank
provenance_date: '2026-11-10'
provider_name: RACQ Bank
provider_slug: racq-bank
slug: racq-bank-privacy-policy
source_date: '2026-11-10'
source_filename: racq-bank-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.racq.com.au/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RACQ Bank\naid: racq-bank\nurl: https://www.racq.com.au/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are committed to handling personal information in compliance with the Privacy Act 1988 (Cth) and the\n    Australian Privacy Principles contained within the Act.\ndata_categories:\n- category: identifying\n  text: identity information and government related identifiers (for example, drivers license, tax file number or\n    tax identification number)\n- category: contact\n  text: Personal and contact details (including name, address, email address, phone number and/or date\
  \ of birth)\n- category: financial\n  text: financial information, credit information, employment-related information\n- category: location\n  text: information about any requests for assistance, including location information\n- category: behavioral\n  text: information about your use of our banking services and products (including internet banking)\n- category: device\n  text: We record your server or IP address, the date and time of your visit, pages visited, documents downloaded\n- category: health\n  text: health information (should you choose to cover a pre-existing medical condition)\n- category: communication\n  text: your communication history with RACQ\npurposes:\n- purpose: Provide requested product or service\n  text: Generally, this is to provide you the product or service that you have requested, to process payments, for\n    the resolution of any complaint or dispute, or to consider your employment application.\n- purpose: Verify identity\n  text: verifying your identity,\
  \ including where we are required to do so by law\n- purpose: Assess applications including creditworthiness\n  text: considering and assessing your application for a product or service, which may include considering your\n    creditworthiness\n- purpose: Train and deploy AI models\n  text: to train, develop, and deploy artificial intelligence models, including for customer support, internal knowledge\n    management and process optimisation and automation\n- purpose: Marketing\n  text: We may use your personal information, including your contact details, to provide you with information we\n    think will interest you about our products and services, where we have your express or inferred consent.\nretention: []\nresidency: []\ntransfers:\n- mechanism: other\n  text: We may disclose your personal information to recipients located overseas, where permitted by law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n \
  \ text: null\nrights:\n- right: Access\n  text: You may request access to the personal information that we hold about you at any time from the Privacy Officer\n- right: Correction\n  text: You can request that we update this information by emailing racq@racq.com.au\n- right: Marketing opt-out\n  text: You may opt out at any time if you no longer wish to receive marketing information\n- right: Complaint\n  text: If you believe that we have not fulfilled our obligations under the Privacy Act or you do not agree with\n    a decision made by RACQ in relation to accessing or correcting your personal information, you can make a complaint\n    to our Privacy Officer\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/racq-bank/privacy/racq-bank-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- transfers
- rights
summary_line: 19 quoted statements, read from RACQ Bank's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Product Reference Data
- ADI
- Mutual
---
