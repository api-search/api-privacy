---
api_specs:
- filename: volt-io-account-holder-verification-api-openapi.yml
  format: yaml
  label: Volt Account Holder Verification API
  slug: volt-io-account-holder-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volt-io/openapi/volt-io-account-holder-verification-api-openapi.yml
- filename: volt-io-accounts-api-openapi.yml
  format: yaml
  label: Volt Accounts API
  slug: volt-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volt-io/openapi/volt-io-accounts-api-openapi.yml
- filename: volt-io-aliases-api-openapi.yml
  format: yaml
  label: Volt Aliases API
  slug: volt-io-aliases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volt-io/openapi/volt-io-aliases-api-openapi.yml
- filename: volt-io-named-accounts-api-openapi.yml
  format: yaml
  label: Volt Named Accounts API
  slug: volt-io-named-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volt-io/openapi/volt-io-named-accounts-api-openapi.yml
- filename: volt-io-sandbox-api-openapi.yml
  format: yaml
  label: Volt Sandbox API
  slug: volt-io-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volt-io/openapi/volt-io-sandbox-api-openapi.yml
- filename: volt-io-transactions-api-openapi.yml
  format: yaml
  label: Volt Transactions API
  slug: volt-io-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volt-io/openapi/volt-io-transactions-api-openapi.yml
- filename: volt-io-trusted-accounts-api-openapi.yml
  format: yaml
  label: Volt Trusted accounts API
  slug: volt-io-trusted-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volt-io/openapi/volt-io-trusted-accounts-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: identity data including first name, last name, title, date of birth
  - category: contact
    text: contact information including your current residential address, previous addresses, email address and telephone numbers
  - category: device
    text: technical data such as internet protocol (IP) address, browser type and version, time zone setting and location
  - category: professional
    text: where you are an employee of a Volt partner or merchant, we may receive information from your employer relating to your role, responsibilities and access permissions
  - category: financial
    text: where you are an owner or director of a partner or merchant we may collect commercial data including percentage ownership of company (including beneficial ownership), political exposure
  deletion:
    route: contact us using the details set out above
    text: To exercise any of these rights, you can get in touch with us, or make a complaint, using the details set out above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: contract performance and payments
    text: managing payments, fees and charges; collecting and recovering money owed to us
  - purpose: legitimate interests
    text: monitor use of our website and use your information to help us monitor, improve and protect our services
  - purpose: legal and regulatory obligations
    text: to discharge our obligations as a regulated financial service provider including ‘know your customer’ checks, anti-money-laundering checks
  - purpose: consent-based marketing and cookies
    text: Where we have obtained your consent, for example we may send you direct marketing communications and place cookies or use similar technologies
  retention:
  - period: six years
    scope: customer contract and transaction data
    text: we process this for six years after you cease being a customer for legal and regulatory purposes
  - period: null
    scope: marketing or consent-based processing
    text: we process the data until you ask us to stop and for a short period after this
  rights:
  - right: access
    text: You have the right to ask us for a copy of your personal data
  - right: correction, deletion or restriction
    text: to correct, delete or restrict (stop any active) processing of your personal data
  - right: portability
    text: to obtain the personal data you provide to us for a contract or with your consent in a structured, machine readable format
  - right: objection
    text: you can object to the processing of your personal data in some circumstances
  - right: withdraw consent
    text: If we collect and process your personal information with your consent, you have the right to withdraw your consent at any time
  role:
    text: Volt Technologies ‘Holdings Limited’ is the controller and responsible for your personal data
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Third parties to whom we may choose to sell, transfer, or merge parts of our business or our assets.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We will only transfer your personal data to countries that have been deemed to provide an adequate level of protection for personal data by the European Commission and equivalent authorities in the United Kingdom, or with whom we have put in place appropriate measures
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Volt
provenance_date: '2026-11-10'
provider_name: Volt
provider_slug: volt-io
slug: volt-io-privacy-policy
source_date: '2026-11-10'
source_filename: volt-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.volt.io/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Volt\naid: volt-io\nurl: https://www.volt.io/legal/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Volt Technologies ‘Holdings Limited’ is the controller and responsible for your personal data\ndata_categories:\n- category: identifying\n  text: identity data including first name, last name, title, date of birth\n- category: contact\n  text: contact information including your current residential address, previous addresses, email address and telephone\n    numbers\n- category: device\n  text: technical data such as internet protocol (IP) address, browser type and version, time zone\
  \ setting and location\n- category: professional\n  text: where you are an employee of a Volt partner or merchant, we may receive information from your employer relating\n    to your role, responsibilities and access permissions\n- category: financial\n  text: where you are an owner or director of a partner or merchant we may collect commercial data including percentage\n    ownership of company (including beneficial ownership), political exposure\npurposes:\n- purpose: contract performance and payments\n  text: managing payments, fees and charges; collecting and recovering money owed to us\n- purpose: legitimate interests\n  text: monitor use of our website and use your information to help us monitor, improve and protect our services\n- purpose: legal and regulatory obligations\n  text: to discharge our obligations as a regulated financial service provider including ‘know your customer’ checks,\n    anti-money-laundering checks\n- purpose: consent-based marketing and cookies\n  text:\
  \ Where we have obtained your consent, for example we may send you direct marketing communications and place\n    cookies or use similar technologies\nretention:\n- scope: customer contract and transaction data\n  period: six years\n  text: we process this for six years after you cease being a customer for legal and regulatory purposes\n- scope: marketing or consent-based processing\n  period: null\n  text: we process the data until you ask us to stop and for a short period after this\nresidency: []\ntransfers:\n- mechanism: other\n  text: We will only transfer your personal data to countries that have been deemed to provide an adequate level\n    of protection for personal data by the European Commission and equivalent authorities in the United Kingdom,\n    or with whom we have put in place appropriate measures\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us using the details set out above\n  text: To exercise\
  \ any of these rights, you can get in touch with us, or make a complaint, using the details set\n    out above.\nrights:\n- right: access\n  text: You have the right to ask us for a copy of your personal data\n- right: correction, deletion or restriction\n  text: to correct, delete or restrict (stop any active) processing of your personal data\n- right: portability\n  text: to obtain the personal data you provide to us for a contract or with your consent in a structured, machine\n    readable format\n- right: objection\n  text: you can object to the processing of your personal data in some circumstances\n- right: withdraw consent\n  text: If we collect and process your personal information with your consent, you have the right to withdraw your\n    consent at any time\nsale_or_sharing:\n  stance: conditional\n  text: Third parties to whom we may choose to sell, transfer, or merge parts of our business or our assets.\n"
source_yaml_url: https://artifacts.apis.io/volt-io/privacy/volt-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Volt's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Open Banking
- Account-to-Account
- Real-Time Payments
- Payment Initiation
- Payouts
- Recurring Payments
- Cross-Border
- Pay by Bank
---
