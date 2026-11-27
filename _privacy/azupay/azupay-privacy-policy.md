---
api_specs:
- filename: azupay-api-keys-api-openapi.yml
  format: yaml
  label: Azupay API Keys API
  slug: azupay-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-api-keys-api-openapi.yml
- filename: azupay-billing-and-transaction-reports-api-openapi.yml
  format: yaml
  label: Azupay Billing and Transaction Reports API
  slug: azupay-billing-and-transaction-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-billing-and-transaction-reports-api-openapi.yml
- filename: azupay-check-accounts-api-openapi.yml
  format: yaml
  label: Azupay Check Accounts API
  slug: azupay-check-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-check-accounts-api-openapi.yml
- filename: azupay-clients-api-openapi.yml
  format: yaml
  label: Azupay Clients API
  slug: azupay-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-clients-api-openapi.yml
- filename: azupay-current-balances-api-openapi.yml
  format: yaml
  label: Azupay Current Balances API
  slug: azupay-current-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-current-balances-api-openapi.yml
- filename: azupay-payment-agreement-api-openapi.yml
  format: yaml
  label: Azupay Payment Agreement API
  slug: azupay-payment-agreement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-agreement-api-openapi.yml
- filename: azupay-payment-agreement-request-api-openapi.yml
  format: yaml
  label: Azupay Payment Agreement Request API
  slug: azupay-payment-agreement-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-agreement-request-api-openapi.yml
- filename: azupay-payment-api-openapi.yml
  format: yaml
  label: Azupay Payment API
  slug: azupay-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-api-openapi.yml
- filename: azupay-payment-initiation-api-openapi.yml
  format: yaml
  label: Azupay Payment Initiation API
  slug: azupay-payment-initiation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-initiation-api-openapi.yml
- filename: azupay-payment-request-api-openapi.yml
  format: yaml
  label: Azupay Payment Request API
  slug: azupay-payment-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-request-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Azupay may handle information such as individual’s names, signatures, addresses, phone numbers, date of birth
  - category: contact
    text: name, company name, email address, telephone number, payment details, billing address, geographic location, IP address
  - category: financial
    text: credit information and other information that may be considered sensitive information
  - category: biometric
    text: which may include document based verification and biometric verification (such as selfie matching)
  - category: device
    text: use of browser cookies for session management, preference tracking and analytical purposes
  deletion:
    route: contact Azupay at the privacy email address
    text: 'Customers can review, correct, update or delete Personal Information by contacting Azupay at: [email protected] .'
  dpa:
    available: true
    text: Where required, data processing agreements (DPAs) and supplemental measures are put in place with third-party vendors handling personal data.
    url: null
  purposes:
  - purpose: identity verification and AML/CTF compliance
    text: We are required to collect, use and disclose your personal information to verify your identity and comply with our obligations under the Anti-Money Laundering and Counter-Terrorism Financing Act 2006 (Cth).
  - purpose: deliver products and services
    text: Azupay will use the information it collects to deliver its products and services to its customers in a compliant manner.
  - purpose: fraud detection
    text: Legitimate interests, such as preventing fraud, detecting suspicious or unlawful activity, ensuring the security of our services
  residency:
  - region: Australia
    text: Information we collect about you will be processed in Australia.
  retention:
  - period: seven (7) years
    scope: AML/CTF compliance records
    text: Personal information collected for AML/CTF compliance is retained for at least seven (7) years after the end of the customer relationship, as required by applicable law.
  rights:
  - right: access and correction
    text: customers have the right to access and correct the personal information Azupay holds about them
  - right: erasure
    text: Right to erasure (right to be forgotten)
  - right: object
    text: Right to object
  - right: complaint to OAIC
    text: If you are not satisfied with our response, you may contact the Office of the Australian Information Commissioner (OAIC)
  role:
    text: Azupay may use automated decision-making (ADM) processes in certain circumstances
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Azupay does not and will not sell or deal in Personal Information or any customer information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If Personal Information is transferred and processed outside Australia, it will only be transferred to countries that have equivalent privacy protections required by Australian business under Australian privacy laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Azupay
provenance_date: '2026-11-09'
provider_name: Azupay
provider_slug: azupay
slug: azupay-privacy-policy
source_date: '2026-11-09'
source_filename: azupay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://azupay.com.au/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Azupay\naid: azupay\nurl: https://azupay.com.au/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Azupay may use automated decision-making (ADM) processes in certain circumstances\ndata_categories:\n- category: identifying\n  text: Azupay may handle information such as individual’s names, signatures, addresses, phone numbers, date of\n    birth\n- category: contact\n  text: name, company name, email address, telephone number, payment details, billing address, geographic location,\n    IP address\n- category: financial\n  text: credit information and other information that may\
  \ be considered sensitive information\n- category: biometric\n  text: which may include document based verification and biometric verification (such as selfie matching)\n- category: device\n  text: use of browser cookies for session management, preference tracking and analytical purposes\npurposes:\n- purpose: identity verification and AML/CTF compliance\n  text: We are required to collect, use and disclose your personal information to verify your identity and comply\n    with our obligations under the Anti-Money Laundering and Counter-Terrorism Financing Act 2006 (Cth).\n- purpose: deliver products and services\n  text: Azupay will use the information it collects to deliver its products and services to its customers in a compliant\n    manner.\n- purpose: fraud detection\n  text: Legitimate interests, such as preventing fraud, detecting suspicious or unlawful activity, ensuring the\n    security of our services\nretention:\n- scope: AML/CTF compliance records\n  period: seven (7) years\n\
  \  text: Personal information collected for AML/CTF compliance is retained for at least seven (7) years after the\n    end of the customer relationship, as required by applicable law.\nresidency:\n- region: Australia\n  text: Information we collect about you will be processed in Australia.\ntransfers:\n- mechanism: other\n  text: If Personal Information is transferred and processed outside Australia, it will only be transferred to countries\n    that have equivalent privacy protections required by Australian business under Australian privacy laws.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Where required, data processing agreements (DPAs) and supplemental measures are put in place with third-party\n    vendors handling personal data.\ndeletion:\n  route: contact Azupay at the privacy email address\n  text: 'Customers can review, correct, update or delete Personal Information by contacting Azupay at: [email protected]\n    .'\nrights:\n- right:\
  \ access and correction\n  text: customers have the right to access and correct the personal information Azupay holds about them\n- right: erasure\n  text: Right to erasure (right to be forgotten)\n- right: object\n  text: Right to object\n- right: complaint to OAIC\n  text: If you are not satisfied with our response, you may contact the Office of the Australian Information Commissioner\n    (OAIC)\nsale_or_sharing:\n  stance: prohibited\n  text: Azupay does not and will not sell or deal in Personal Information or any customer information.\n"
source_yaml_url: https://artifacts.apis.io/azupay/privacy/azupay-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Azupay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Australia
- Real-Time Payments
- Account-to-Account
- New Payments Platform
- PayID
- PayTo
- Money Transfer
- Confirmation of Payee
- Open Banking
---
