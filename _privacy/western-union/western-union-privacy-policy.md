---
api_specs:
- filename: western-union-balances-api-openapi.yml
  format: yaml
  label: western-union Balances API
  slug: western-union-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-union/openapi/western-union-balances-api-openapi.yml
- filename: western-union-batches-api-openapi.yml
  format: yaml
  label: western-union Batches API
  slug: western-union-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-union/openapi/western-union-batches-api-openapi.yml
- filename: western-union-customers-api-openapi.yml
  format: yaml
  label: western-union Customers API
  slug: western-union-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-union/openapi/western-union-customers-api-openapi.yml
- filename: western-union-health-api-openapi.yml
  format: yaml
  label: western-union Health API
  slug: western-union-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-union/openapi/western-union-health-api-openapi.yml
- filename: western-union-orders-api-openapi.yml
  format: yaml
  label: western-union Orders API
  slug: western-union-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-union/openapi/western-union-orders-api-openapi.yml
- filename: western-union-payments-api-openapi.yml
  format: yaml
  label: western-union Payments API
  slug: western-union-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-union/openapi/western-union-payments-api-openapi.yml
- filename: western-union-quotes-api-openapi.yml
  format: yaml
  label: western-union Quotes API
  slug: western-union-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-union/openapi/western-union-quotes-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Basic personal information such as your name, contact information (for example, your postal address, email address, telephone number), photo or other image of you (if you choose to provide it), place of birth, date of birth, gender, citizenship, occupation, marital status, and government or national identification numbers and accompanying documentation
  - category: financial
    text: Financial and transactional information such as your money transfers, payments, deposits and the source/destination of funds for each, information about how you use our Services, bank and credit information, and employer information
  - category: biometric
    text: Sensitive or special categories of information, such as biometric information used to uniquely identify you (for example, fingerprints or facial recognition) or criminal conviction information.
  - category: device
    text: information about your device (such as device properties, settings, applications, storage and usage information)
  - category: location
    text: geolocation if enabled
  - category: behavioral
    text: Information about you that is acquired through your use of social media
  deletion:
    route: Contact Western Union or visit the data subject rights page to request deletion
    text: You have the right to ask us to delete certain information about you, to restrict certain uses of information relating to you, and to object to certain uses of it. To exercise these rights, please visit http://www.westernunion.com/datasubjectrights or contact Western Union through the section titled “CONTACTING US”.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Performing the Services
    text: To assist us in providing Services and customer support to you, to help you to receive a personalized experience
  - purpose: Advertising
    text: To deliver information specific to your interests on Western Union and non-Western Union websites and applications
  - purpose: Targeted advertising for partners
    text: Providing advertising and marketing services for advertising partners, including targeted advertising
  - purpose: Train AI technologies
    text: 'To train artificial intelligence technologies which includes but is not limited to: utilized for customer care, customer onboarding and the prevention of fraud or other unlawful activity'
  - purpose: Analytics
    text: To perform analytics on understanding our customers, improving their experience
  - purpose: Fraud prevention
    text: To promote safety, reduce financial risk, and combat fraud across our Services
  residency:
  - region: USA
    text: We transfer certain personal information about you to our data centers located in the USA or within a region as required by local law
  retention:
  - period: null
    scope: Personal information generally
    text: Your personal information will be retained in accordance with statutory periods contained in regulations applicable to financial transactions and accounts including those in anti-money laundering, anti-terrorist financing and other laws applicable to us.
  - period: null
    scope: Otherwise
    text: we will retain your information only if necessary for the specific purposes for which it was collected, or to resolve any query you may raise.
  rights:
  - right: Right to know and access
    text: You have the right to know if we are processing your personal information and to ask us for a copy of your information free of charge.
  - right: Right to correction
    text: You have the right to ask us to correct information about you that is incomplete, inaccurate or out-of-date.
  - right: Right to withdraw consent
    text: To the extent we are processing personal information based on your consent, you may withdraw your consent as permitted by applicable law.
  - right: Right to lodge a complaint
    text: You also have the right to lodge a complaint with a relevant data protection regulator or supervisory authority about our processing of personal information.
  - right: Right to stop marketing communications
    text: You have the right to stop us from sending you marketing communications.
  role:
    text: The company providing your service and acting as the data controller of your personal data in relation to that service is identified in the applicable Terms and Conditions .
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Western Union does not sell your personal information to third parties in exchange for money. Western Union does participate in advertising, marketing and analytic programs from which we and third parties with whom we contract may derive value; such exchanges may constitute a “sale” under applicable law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Personal information transferred outside the EEA, the UK, and Switzerland to countries that the European Commission or UK Information Commissioner’s Office (ICO) have not found to provide adequate protection will be protected by appropriate Standard Contractual Clauses or other EU or UK –approved mechanisms, as required by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: The Western Union Company
provenance_date: '2026-11-10'
provider_name: The Western Union Company
provider_slug: western-union
slug: western-union-privacy-policy
source_date: '2026-11-10'
source_filename: western-union-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.westernunion.com/global/en/privacy-statement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: The Western Union Company\naid: western-union\nurl: https://www.westernunion.com/global/en/privacy-statement.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: The company providing your service and acting as the data controller of your personal data in relation to\n    that service is identified in the applicable Terms and Conditions .\ndata_categories:\n- category: identifying\n  text: Basic personal information such as your name, contact information (for example, your postal address, email\n    address, telephone number), photo or other image of you (if you choose to\
  \ provide it), place of birth, date\n    of birth, gender, citizenship, occupation, marital status, and government or national identification numbers\n    and accompanying documentation\n- category: financial\n  text: Financial and transactional information such as your money transfers, payments, deposits and the source/destination\n    of funds for each, information about how you use our Services, bank and credit information, and employer information\n- category: biometric\n  text: Sensitive or special categories of information, such as biometric information used to uniquely identify\n    you (for example, fingerprints or facial recognition) or criminal conviction information.\n- category: device\n  text: information about your device (such as device properties, settings, applications, storage and usage information)\n- category: location\n  text: geolocation if enabled\n- category: behavioral\n  text: Information about you that is acquired through your use of social media\npurposes:\n\
  - purpose: Performing the Services\n  text: To assist us in providing Services and customer support to you, to help you to receive a personalized experience\n- purpose: Advertising\n  text: To deliver information specific to your interests on Western Union and non-Western Union websites and applications\n- purpose: Targeted advertising for partners\n  text: Providing advertising and marketing services for advertising partners, including targeted advertising\n- purpose: Train AI technologies\n  text: 'To train artificial intelligence technologies which includes but is not limited to: utilized for customer\n    care, customer onboarding and the prevention of fraud or other unlawful activity'\n- purpose: Analytics\n  text: To perform analytics on understanding our customers, improving their experience\n- purpose: Fraud prevention\n  text: To promote safety, reduce financial risk, and combat fraud across our Services\nretention:\n- scope: Personal information generally\n  period: null\n  text:\
  \ Your personal information will be retained in accordance with statutory periods contained in regulations\n    applicable to financial transactions and accounts including those in anti-money laundering, anti-terrorist financing\n    and other laws applicable to us.\n- scope: Otherwise\n  period: null\n  text: we will retain your information only if necessary for the specific purposes for which it was collected,\n    or to resolve any query you may raise.\nresidency:\n- region: USA\n  text: We transfer certain personal information about you to our data centers located in the USA or within a region\n    as required by local law\ntransfers:\n- mechanism: SCC\n  text: Personal information transferred outside the EEA, the UK, and Switzerland to countries that the European\n    Commission or UK Information Commissioner’s Office (ICO) have not found to provide adequate protection will\n    be protected by appropriate Standard Contractual Clauses or other EU or UK –approved mechanisms, as required\n\
  \    by law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact Western Union or visit the data subject rights page to request deletion\n  text: You have the right to ask us to delete certain information about you, to restrict certain uses of information\n    relating to you, and to object to certain uses of it. To exercise these rights, please visit http://www.westernunion.com/datasubjectrights\n    or contact Western Union through the section titled “CONTACTING US”.\nrights:\n- right: Right to know and access\n  text: You have the right to know if we are processing your personal information and to ask us for a copy of your\n    information free of charge.\n- right: Right to correction\n  text: You have the right to ask us to correct information about you that is incomplete, inaccurate or out-of-date.\n- right: Right to withdraw consent\n  text: To the extent we are processing personal information based on your consent,\
  \ you may withdraw your consent\n    as permitted by applicable law.\n- right: Right to lodge a complaint\n  text: You also have the right to lodge a complaint with a relevant data protection regulator or supervisory authority\n    about our processing of personal information.\n- right: Right to stop marketing communications\n  text: You have the right to stop us from sending you marketing communications.\nsale_or_sharing:\n  stance: conditional\n  text: Western Union does not sell your personal information to third parties in exchange for money. Western Union\n    does participate in advertising, marketing and analytic programs from which we and third parties with whom we\n    contract may derive value; such exchanges may constitute a “sale” under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/western-union/privacy/western-union-privacy-policy.yml
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
summary_line: 24 quoted statements, read from The Western Union Company's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 500
- Financial Services
- Payments
- Money Transfer
- Remittances
- Cross-Border Payments
- Foreign Exchange
- Open Banking
- United States
---
