---
api_specs:
- filename: gusto-asyncapi.yml
  format: yaml
  label: Gusto Embedded Payroll API
  slug: embedded-payroll-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-asyncapi.yml
- filename: gusto-companies-api-openapi.yml
  format: yaml
  label: Gusto Companies API
  slug: gusto-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-companies-api-openapi.yml
- filename: gusto-contractors-api-openapi.yml
  format: yaml
  label: Gusto Contractors API
  slug: gusto-contractors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-contractors-api-openapi.yml
- filename: gusto-employees-api-openapi.yml
  format: yaml
  label: Gusto Employees API
  slug: gusto-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-employees-api-openapi.yml
- filename: gusto-flows-api-openapi.yml
  format: yaml
  label: Gusto Flows API
  slug: gusto-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-flows-api-openapi.yml
- filename: gusto-payrolls-api-openapi.yml
  format: yaml
  label: Gusto Payrolls API
  slug: gusto-payrolls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-payrolls-api-openapi.yml
- filename: gusto-reports-api-openapi.yml
  format: yaml
  label: Gusto Reports API
  slug: gusto-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-reports-api-openapi.yml
- filename: gusto-webhooks-api-openapi.yml
  format: yaml
  label: Gusto Webhooks API
  slug: gusto-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-webhooks-api-openapi.yml
- filename: gusto-bank-accounts-api-openapi.yml
  format: yaml
  label: Gusto Bank Accounts API
  slug: gusto-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-bank-accounts-api-openapi.yml
- filename: gusto-contractor-payments-api-openapi.yml
  format: yaml
  label: Gusto Contractor Payments API
  slug: gusto-contractor-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-contractor-payments-api-openapi.yml
- filename: gusto-pay-schedules-api-openapi.yml
  format: yaml
  label: Gusto Pay Schedules API
  slug: gusto-pay-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gusto/openapi/gusto-pay-schedules-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Government identifiers , such as Social Security number and government-issued photo ID such as a driver’s license, military ID, or passport
  - category: contact
    text: Contact information , such as full name, mailing address, email address, telephone number, and business contact information
  - category: financial
    text: Financial information , such as credit card information, payment card number, payment card expiration date and CVV code, bank account number, routing number, and balance and transaction information
  - category: location
    text: Geolocation data, such as approximate location derived from IP address and precise location data if you have granted permission to share
  - category: behavioral
    text: Inferences, such as information from the categories of personal information described above in order to create inferences about you
  - category: device
    text: Internet or electronic usage data, such as data related to network and website interaction history, IP address, website cookie information, interaction with advertisements, device information, network log, and browsing time
  - category: health
    text: Insurance benefits information , such as dependents, health insurance policy information, claim information, and any other information required to provide broker services
  - category: biometric
    text: Biometric information, such as facial photographs for office visitors
  - category: communication
    text: Communication information , such as any information provided when you communicate with us by phone, email, or chatbot
  - category: professional
    text: Professional information , such as employer, job title, professional qualifications, and employment history
  - category: demographic
    text: Demographic information , such as gender, date of birth, age, racial or ethnic origin, marital status, and disability information
  deletion:
    route: Privacy Request Portal
    text: if you request to delete your personal information, we may retain some or all of it for legal purposes
  dpa:
    available: true
    text: For more information about how we process personal information on behalf of our customers, please see the Employer Data Processing Addendum .
    url: https://gusto.com/legal/terms/privacy
  purposes:
  - purpose: Provide services and process transactions
    text: Provide our Services ; Process transactions ;
  - purpose: Develop and improve services, including AI
    text: Develop and improve our business and Services, including evaluating, operating, and creating new products and features, which may include the use of AI
  - purpose: Advertising and marketing
    text: Advertise and market our products and services to send you information about third-party products and services
  - purpose: Fraud prevention and security
    text: Prevent fraud and maintain security by protecting against, identifying, and preventing fraud, theft, and other illegal activity
  - purpose: Legal compliance
    text: Comply with legal obligations , including applicable law, regulation, industry standards, legal process, preparing and filing required reports, and defending against legal claims
  retention:
  - period: null
    scope: personal information generally
    text: We will retain your personal information for as long as necessary to fulfill the purposes described in the How We Use Personal Information section above, unless otherwise required by applicable laws.
  rights:
  - right: access
    text: request access to a copy of the personal information we hold about you
  - right: deletion
    text: request the deletion of your personal information
  - right: correction
    text: request the correction of inaccurate, incomplete, or outdated personal information we have collected
  - right: withdraw consent
    text: withdraw your consent if we have collected and processed your personal information with your consent
  - right: opt out of sale or sharing
    text: To request that we do not “sell” or “share” your personal information for the purposes of targeted advertising, you may submit your request through our Privacy Request Portal .
  - right: non-discrimination
    text: be free from discrimination for the exercise of a privacy right
  - right: complaint
    text: lodge a complaint with your local data protection authority
  role:
    text: collects, uses, and shares your personal information for our own purposes as a “controller” or “business”
    value: controller
  sale_or_sharing:
    stance: allowed
    text: We may "sell" or "share" your personal information as those terms are defined under applicable U.S. state privacy laws.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If your personal information is transferred to a country other than your home country, we will take measures to protect your personal information, for example, by implementing appropriate contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Gusto
provenance_date: '2026-11-09'
provider_name: Gusto
provider_slug: gusto
slug: gusto-privacy-policy
source_date: '2026-11-09'
source_filename: gusto-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gusto.com/legal/terms/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Gusto\naid: gusto\nurl: https://gusto.com/legal/terms/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: collects, uses, and shares your personal information for our own purposes as a “controller” or “business”\ndata_categories:\n- category: identifying\n  text: Government identifiers , such as Social Security number and government-issued photo ID such as a driver’s\n    license, military ID, or passport\n- category: contact\n  text: Contact information , such as full name, mailing address, email address, telephone number, and business\n    contact information\n- category: financial\n\
  \  text: Financial information , such as credit card information, payment card number, payment card expiration date\n    and CVV code, bank account number, routing number, and balance and transaction information\n- category: location\n  text: Geolocation data, such as approximate location derived from IP address and precise location data if you\n    have granted permission to share\n- category: behavioral\n  text: Inferences, such as information from the categories of personal information described above in order to\n    create inferences about you\n- category: device\n  text: Internet or electronic usage data, such as data related to network and website interaction history, IP address,\n    website cookie information, interaction with advertisements, device information, network log, and browsing time\n- category: health\n  text: Insurance benefits information , such as dependents, health insurance policy information, claim information,\n    and any other information required to provide\
  \ broker services\n- category: biometric\n  text: Biometric information, such as facial photographs for office visitors\n- category: communication\n  text: Communication information , such as any information provided when you communicate with us by phone, email,\n    or chatbot\n- category: professional\n  text: Professional information , such as employer, job title, professional qualifications, and employment history\n- category: demographic\n  text: Demographic information , such as gender, date of birth, age, racial or ethnic origin, marital status, and\n    disability information\npurposes:\n- purpose: Provide services and process transactions\n  text: Provide our Services ; Process transactions ;\n- purpose: Develop and improve services, including AI\n  text: Develop and improve our business and Services, including evaluating, operating, and creating new products\n    and features, which may include the use of AI\n- purpose: Advertising and marketing\n  text: Advertise and market\
  \ our products and services to send you information about third-party products and services\n- purpose: Fraud prevention and security\n  text: Prevent fraud and maintain security by protecting against, identifying, and preventing fraud, theft, and\n    other illegal activity\n- purpose: Legal compliance\n  text: Comply with legal obligations , including applicable law, regulation, industry standards, legal process,\n    preparing and filing required reports, and defending against legal claims\nretention:\n- scope: personal information generally\n  period: null\n  text: We will retain your personal information for as long as necessary to fulfill the purposes described in the\n    How We Use Personal Information section above, unless otherwise required by applicable laws.\nresidency: []\ntransfers:\n- mechanism: other\n  text: If your personal information is transferred to a country other than your home country, we will take measures\n    to protect your personal information, for example,\
  \ by implementing appropriate contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://gusto.com/legal/terms/privacy\n  text: For more information about how we process personal information on behalf of our customers, please see the\n    Employer Data Processing Addendum .\ndeletion:\n  route: Privacy Request Portal\n  text: if you request to delete your personal information, we may retain some or all of it for legal purposes\nrights:\n- right: access\n  text: request access to a copy of the personal information we hold about you\n- right: deletion\n  text: request the deletion of your personal information\n- right: correction\n  text: request the correction of inaccurate, incomplete, or outdated personal information we have collected\n- right: withdraw consent\n  text: withdraw your consent if we have collected and processed your personal information with your consent\n- right: opt out of sale or sharing\n  text: To request that we do not\
  \ “sell” or “share” your personal information for the purposes of targeted advertising,\n    you may submit your request through our Privacy Request Portal .\n- right: non-discrimination\n  text: be free from discrimination for the exercise of a privacy right\n- right: complaint\n  text: lodge a complaint with your local data protection authority\nsale_or_sharing:\n  stance: allowed\n  text: We may \"sell\" or \"share\" your personal information as those terms are defined under applicable U.S. state\n    privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/gusto/privacy/gusto-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Gusto's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Payroll
- Benefits
- Enterprise Software
- Embedded Finance
- Employee Benefits
---
