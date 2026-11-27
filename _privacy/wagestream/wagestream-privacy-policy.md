---
api_specs:
- filename: wagestream-absences-api-openapi.yml
  format: yaml
  label: Wagestream Absences API
  slug: wagestream-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-absences-api-openapi.yml
- filename: wagestream-employees-api-openapi.yml
  format: yaml
  label: Wagestream Employees API
  slug: wagestream-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-employees-api-openapi.yml
- filename: wagestream-enrollment-api-openapi.yml
  format: yaml
  label: Wagestream Enrollment API
  slug: wagestream-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-enrollment-api-openapi.yml
- filename: wagestream-off-cycle-payment-api-openapi.yml
  format: yaml
  label: Wagestream Off Cycle Payment API
  slug: wagestream-off-cycle-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-off-cycle-payment-api-openapi.yml
- filename: wagestream-shifts-api-openapi.yml
  format: yaml
  label: Wagestream Shifts API
  slug: wagestream-shifts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wagestream/openapi/wagestream-shifts-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data includes full name; username or similar identifier; title; date of birth; gender; age; nationality and language(s)
  - category: contact
    text: Contact Data includes your home address; email address and telephone numbers.
  - category: financial
    text: Financial Data includes sort code; account name; account number; salary and statutory payments.
  - category: location
    text: Technical Data includes data related to website visits and App usage, such as Internet Protocol (IP) address; mobile device identifier
  - category: health
    text: Health Data includes data about your health such as absence data, where shared by your employer
  - category: biometric
    text: Face / Biometric Data – As Stream is a financial services provider, we are required to undertake Know Your Customer (KYC) and Anti-Money Laundering (AML) compliance checks
  - category: behavioral
    text: Behavioural Data information inferred from your activity on the Platform, which may be grouped into segments
  - category: communication
    text: our communications with you (which may include correspondences, call and video records, automated transcriptions and AI generated analysis thereof).
  deletion:
    route: Contact the DPO using the contact details in the notice, or exercise the right to request erasure
    text: Request erasure of your Personal Data . This enables you to ask us to delete or remove Personal Data where there is no good reason for us continuing to process it.
  dpa:
    available: true
    text: Where we are a Processor of your Personal Data we will operate under the terms of a Data Protection Agreement with the relevant Controller.
    url: null
  purposes:
  - purpose: Account creation and service provision
    text: To register you as a new user
  - purpose: Compliance and fraud prevention
    text: To keep your data and identity secure and comply with our AML, KYC and Consumer Duty obligations.
  - purpose: Targeted online advertising
    text: We may use your email address for audience matching on third-party platforms (such as search engines) so you see relevant ads for our products when browsing those platforms.
  - purpose: Credit modelling
    text: To develop and use models that inform eligibility and terms for financial products offered by Stream Financial Services Ltd.
  residency:
  - region: UK
    text: Many of our external third parties are based outside the UK so their processing of your Personal Data will involve a transfer of data outside the UK.
  retention:
  - period: five years
    scope: Relationship data
    text: We may store your information for as long as you’re using Stream, and for five years after the end of our relationship with your employer to comply with the law.
  - period: three years
    scope: Platform use and marketing activities
    text: Information related with Platform use and marketing activities are typically stored for three years.
  - period: up to three years
    scope: Facial biometric data held by Onfido
    text: Onfido stores this data for up to three years for legal and compliance purposes.
  rights:
  - right: Access
    text: Request access to your Personal Data .
  - right: Correction
    text: Request correction of the Personal Data that we hold about you .
  - right: Erasure
    text: Request erasure of your Personal Data .
  - right: Objection
    text: Object to processing of your Personal Data .
  - right: Restriction
    text: Request the restriction of processing of your Personal Data .
  - right: Portability
    text: Request the transfer of your Personal Data .
  - right: Withdraw consent
    text: Withdraw consent .
  role:
    text: This Privacy Notice covers the position where Stream is the Controller of your Personal Data. Please see the end of this Privacy Notice for a statement concerning where Stream is a Processor.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Third parties to whom we may choose to sell, transfer, or merge parts of our business or our assets.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: transferring your Personal Data to a recipient in a country that the UK or European Commission (respectively) has decided provides adequate protection for Personal Data
  - mechanism: BCR
    text: to a recipient that has achieved binding corporate rules authorisation in accordance with applicable data protection laws
  - mechanism: SCC
    text: to a recipient that has executed standard contractual clauses adopted or approved by the UK or European Commission (respectively).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Wagestream
provenance_date: '2026-11-10'
provider_name: Wagestream
provider_slug: wagestream
slug: wagestream-privacy-policy
source_date: '2026-11-10'
source_filename: wagestream-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://stream.co/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Wagestream\naid: wagestream\nurl: https://stream.co/en/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This Privacy Notice covers the position where Stream is the Controller of your Personal Data. Please see\n    the end of this Privacy Notice for a statement concerning where Stream is a Processor.\ndata_categories:\n- category: identifying\n  text: Identity Data includes full name; username or similar identifier; title; date of birth; gender; age; nationality\n    and language(s)\n- category: contact\n  text: Contact Data includes your home address; email address and telephone numbers.\n\
  - category: financial\n  text: Financial Data includes sort code; account name; account number; salary and statutory payments.\n- category: location\n  text: Technical Data includes data related to website visits and App usage, such as Internet Protocol (IP) address;\n    mobile device identifier\n- category: health\n  text: Health Data includes data about your health such as absence data, where shared by your employer\n- category: biometric\n  text: Face / Biometric Data – As Stream is a financial services provider, we are required to undertake Know Your\n    Customer (KYC) and Anti-Money Laundering (AML) compliance checks\n- category: behavioral\n  text: Behavioural Data information inferred from your activity on the Platform, which may be grouped into segments\n- category: communication\n  text: our communications with you (which may include correspondences, call and video records, automated transcriptions\n    and AI generated analysis thereof).\npurposes:\n- purpose: Account creation\
  \ and service provision\n  text: To register you as a new user\n- purpose: Compliance and fraud prevention\n  text: To keep your data and identity secure and comply with our AML, KYC and Consumer Duty obligations.\n- purpose: Targeted online advertising\n  text: We may use your email address for audience matching on third-party platforms (such as search engines) so\n    you see relevant ads for our products when browsing those platforms.\n- purpose: Credit modelling\n  text: To develop and use models that inform eligibility and terms for financial products offered by Stream Financial\n    Services Ltd.\nretention:\n- scope: Relationship data\n  period: five years\n  text: We may store your information for as long as you’re using Stream, and for five years after the end of our\n    relationship with your employer to comply with the law.\n- scope: Platform use and marketing activities\n  period: three years\n  text: Information related with Platform use and marketing activities are typically\
  \ stored for three years.\n- scope: Facial biometric data held by Onfido\n  period: up to three years\n  text: Onfido stores this data for up to three years for legal and compliance purposes.\nresidency:\n- region: UK\n  text: Many of our external third parties are based outside the UK so their processing of your Personal Data will\n    involve a transfer of data outside the UK.\ntransfers:\n- mechanism: adequacy\n  text: transferring your Personal Data to a recipient in a country that the UK or European Commission (respectively)\n    has decided provides adequate protection for Personal Data\n- mechanism: BCR\n  text: to a recipient that has achieved binding corporate rules authorisation in accordance with applicable data\n    protection laws\n- mechanism: SCC\n  text: to a recipient that has executed standard contractual clauses adopted or approved by the UK or European\n    Commission (respectively).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n\
  \  text: Where we are a Processor of your Personal Data we will operate under the terms of a Data Protection Agreement\n    with the relevant Controller.\ndeletion:\n  route: Contact the DPO using the contact details in the notice, or exercise the right to request erasure\n  text: Request erasure of your Personal Data . This enables you to ask us to delete or remove Personal Data where\n    there is no good reason for us continuing to process it.\nrights:\n- right: Access\n  text: Request access to your Personal Data .\n- right: Correction\n  text: Request correction of the Personal Data that we hold about you .\n- right: Erasure\n  text: Request erasure of your Personal Data .\n- right: Objection\n  text: Object to processing of your Personal Data .\n- right: Restriction\n  text: Request the restriction of processing of your Personal Data .\n- right: Portability\n  text: Request the transfer of your Personal Data .\n- right: Withdraw consent\n  text: Withdraw consent .\nsale_or_sharing:\n\
  \  stance: conditional\n  text: Third parties to whom we may choose to sell, transfer, or merge parts of our business or our assets.\n"
source_yaml_url: https://artifacts.apis.io/wagestream/privacy/wagestream-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Wagestream's own page on 2026-11-10.
synthetic: false
tags:
- Financial Wellbeing
- Earned Wage Access
- Fintech
- Payroll
- Human Resources
- Workforce Management
- Time and Attendance
- Employee Benefits
- Workplace Savings
- HR Integrations
- B Corp
- United Kingdom
---
