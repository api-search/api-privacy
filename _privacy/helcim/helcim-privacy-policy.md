---
api_specs:
- filename: helcim-ach-payment-api-openapi.yml
  format: yaml
  label: Helcim ACH Payment API
  slug: helcim-ach-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-ach-payment-api-openapi.yml
- filename: helcim-card-batch-api-openapi.yml
  format: yaml
  label: Helcim Card Batch API
  slug: helcim-card-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-card-batch-api-openapi.yml
- filename: helcim-card-terminal-api-openapi.yml
  format: yaml
  label: Helcim Card Terminal API
  slug: helcim-card-terminal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-card-terminal-api-openapi.yml
- filename: helcim-card-transaction-api-openapi.yml
  format: yaml
  label: Helcim Card Transaction API
  slug: helcim-card-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-card-transaction-api-openapi.yml
- filename: helcim-customer-api-openapi.yml
  format: yaml
  label: Helcim Customer API
  slug: helcim-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-customer-api-openapi.yml
- filename: helcim-device-api-openapi.yml
  format: yaml
  label: Helcim Device API
  slug: helcim-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-device-api-openapi.yml
- filename: helcim-general-api-openapi.yml
  format: yaml
  label: Helcim General API
  slug: helcim-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-general-api-openapi.yml
- filename: helcim-invoice-api-openapi.yml
  format: yaml
  label: Helcim Invoice API
  slug: helcim-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-invoice-api-openapi.yml
- filename: helcim-payment-api-openapi.yml
  format: yaml
  label: Helcim Payment API
  slug: helcim-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helcim/openapi/helcim-payment-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, postal address, signature, and phone number; passport number, driver's license number, social security number
  - category: financial
    text: Bank account information, bank statements, financial statements
  - category: location
    text: Internet Protocol (IP) address, approximate location
  - category: behavioral
    text: Actions taken on the Services such as clicks per page, navigation behaviours, pages visited, redirection logs
  - category: device
    text: Browser, operating system and device characteristics and settings, user agent string, user settings
  - category: biometric
    text: biometric information
  deletion:
    route: Email request to privacy contact
    text: If you have a direct relationship with Helcim and would like to access, correct, amend or delete any of your personally identifiable information collected or held by Helcim via its Services or Website or exercise the data privacy rights applicable to your jurisdiction, please email [email protected] .
  dpa:
    available: true
    text: For more information, please reference Helcim's Data Processing Addendum, which is available on our website.
    url: null
  purposes:
  - purpose: Provide services
    text: To Provide Our Services . We use your Personal Information to provide you with our Services
  - purpose: Machine learning and product improvement
    text: Improving, upgrading or enhancing our Services, including through automation and machine learning
  - purpose: Marketing and targeted advertising
    text: We may take advantage of certain targeted or interest-based advertising
  - purpose: Fraud prevention and security
    text: Detecting security incidents, protecting against malicious, deceptive, fraudulent or illegal activity
  residency:
  - region: Canada and United States
    text: your Personal Data may be transferred to, processed, sub-processed and stored in Canada and the United States, where our servers, sub-processors, and central database are located.
  retention:
  - period: one year
    scope: Biometric data
    text: We retain biometric data for a period of one year from the date the record was created.
  - period: null
    scope: Anti-money laundering and fraud monitoring records
    text: we retain Personal Information used to conduct our anti-money laundering activities and operate our fraud prevention and monitoring program for a minimum period of five (5) years.
  - period: null
    scope: General personal information
    text: we retain all the Personal Information we collect as described in this Privacy Policy for as long as you use our Services or as necessary to fulfill the purposes for which it was collected
  rights:
  - right: Access
    text: Request access to your Personal Data (commonly known as a "data subject access request")
  - right: Correction
    text: Request correction of the Personal Data that we hold about you .
  - right: Erasure
    text: Request erasure of your Personal Data .
  - right: Object to processing
    text: Object to processing of your Personal Data .
  - right: Restriction of processing
    text: Request restriction of processing of your Personal Data .
  - right: Data portability
    text: Request the transfer of your Personal Data to you or to a third party .
  - right: Withdraw consent
    text: Withdraw consent at any time where we are relying on consent to process your Personal Data .
  - right: Lodge complaint with DPA
    text: Lodging a Complaint with a Data Protection Authority .
  role:
    text: we are solely a Processor acting on your behalf
    value: both
  sale_or_sharing:
    stance: conditional
    text: Helcim does not sell Personal Information and has not sold any Personal Information in the prior 12 months as of the "last updated" date of this Privacy Policy.
  subprocessors:
    text: This also includes our sub-processors and Service Providers that provide us with IT support and tools, cloud hosting, customer service tools, marketing and analytics, identity verification, and related services.
    url: null
  transfers:
  - mechanism: SCC
    text: Helcim relies on the European Union's Standard Contractual Clauses (the " SCCs ") and other legal mechanisms as safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Helcim
provenance_date: '2026-11-09'
provider_name: Helcim
provider_slug: helcim
slug: helcim-privacy-policy
source_date: '2026-11-09'
source_filename: helcim-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://legal.helcim.com/ca/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Helcim\naid: helcim\nurl: https://legal.helcim.com/ca/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we are solely a Processor acting on your behalf\ndata_categories:\n- category: identifying\n  text: Name, email address, postal address, signature, and phone number; passport number, driver's license number,\n    social security number\n- category: financial\n  text: Bank account information, bank statements, financial statements\n- category: location\n  text: Internet Protocol (IP) address, approximate location\n- category: behavioral\n  text: Actions taken on the Services such as\
  \ clicks per page, navigation behaviours, pages visited, redirection\n    logs\n- category: device\n  text: Browser, operating system and device characteristics and settings, user agent string, user settings\n- category: biometric\n  text: biometric information\npurposes:\n- purpose: Provide services\n  text: To Provide Our Services . We use your Personal Information to provide you with our Services\n- purpose: Machine learning and product improvement\n  text: Improving, upgrading or enhancing our Services, including through automation and machine learning\n- purpose: Marketing and targeted advertising\n  text: We may take advantage of certain targeted or interest-based advertising\n- purpose: Fraud prevention and security\n  text: Detecting security incidents, protecting against malicious, deceptive, fraudulent or illegal activity\nretention:\n- scope: Biometric data\n  period: one year\n  text: We retain biometric data for a period of one year from the date the record was created.\n\
  - scope: Anti-money laundering and fraud monitoring records\n  period: null\n  text: we retain Personal Information used to conduct our anti-money laundering activities and operate our fraud\n    prevention and monitoring program for a minimum period of five (5) years.\n- scope: General personal information\n  period: null\n  text: we retain all the Personal Information we collect as described in this Privacy Policy for as long as you\n    use our Services or as necessary to fulfill the purposes for which it was collected\nresidency:\n- region: Canada and United States\n  text: your Personal Data may be transferred to, processed, sub-processed and stored in Canada and the United States,\n    where our servers, sub-processors, and central database are located.\ntransfers:\n- mechanism: SCC\n  text: Helcim relies on the European Union's Standard Contractual Clauses (the \" SCCs \") and other legal mechanisms\n    as safeguards.\nsubprocessors:\n  url: null\n  text: This also includes our\
  \ sub-processors and Service Providers that provide us with IT support and tools, cloud\n    hosting, customer service tools, marketing and analytics, identity verification, and related services.\ndpa:\n  available: true\n  url: null\n  text: For more information, please reference Helcim's Data Processing Addendum, which is available on our website.\ndeletion:\n  route: Email request to privacy contact\n  text: If you have a direct relationship with Helcim and would like to access, correct, amend or delete any of\n    your personally identifiable information collected or held by Helcim via its Services or Website or exercise\n    the data privacy rights applicable to your jurisdiction, please email [email protected] .\nrights:\n- right: Access\n  text: Request access to your Personal Data (commonly known as a \"data subject access request\")\n- right: Correction\n  text: Request correction of the Personal Data that we hold about you .\n- right: Erasure\n  text: Request erasure of your\
  \ Personal Data .\n- right: Object to processing\n  text: Object to processing of your Personal Data .\n- right: Restriction of processing\n  text: Request restriction of processing of your Personal Data .\n- right: Data portability\n  text: Request the transfer of your Personal Data to you or to a third party .\n- right: Withdraw consent\n  text: Withdraw consent at any time where we are relying on consent to process your Personal Data .\n- right: Lodge complaint with DPA\n  text: Lodging a Complaint with a Data Protection Authority .\nsale_or_sharing:\n  stance: conditional\n  text: Helcim does not sell Personal Information and has not sold any Personal Information in the prior 12 months\n    as of the \"last updated\" date of this Privacy Policy.\n"
source_yaml_url: https://artifacts.apis.io/helcim/privacy/helcim-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Helcim's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Canada
- Payment Gateway
- Payment Processing
- Acquiring
- Merchant Services
- ACH
- Invoicing
- Payment Terminals
- Small Business
---
