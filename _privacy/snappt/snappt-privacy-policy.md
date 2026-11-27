---
api_specs:
- filename: snappt-account-api-openapi.yml
  format: yaml
  label: Snappt Account API
  slug: snappt-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-account-api-openapi.yml
- filename: snappt-applicant-sessions-api-openapi.yml
  format: yaml
  label: Snappt Applicant Sessions API
  slug: snappt-applicant-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-applicant-sessions-api-openapi.yml
- filename: snappt-applicants-api-openapi.yml
  format: yaml
  label: Snappt Applicants API
  slug: snappt-applicants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-applicants-api-openapi.yml
- filename: snappt-id-verification-api-openapi.yml
  format: yaml
  label: Snappt ID Verification API
  slug: snappt-id-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-id-verification-api-openapi.yml
- filename: snappt-internal-idv-api-openapi.yml
  format: yaml
  label: Snappt Internal IDV API
  slug: snappt-internal-idv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-internal-idv-api-openapi.yml
- filename: snappt-properties-api-openapi.yml
  format: yaml
  label: Snappt Properties API
  slug: snappt-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-properties-api-openapi.yml
- filename: snappt-webhooks-api-openapi.yml
  format: yaml
  label: Snappt Webhooks API
  slug: snappt-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-webhooks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your first and last name, alias, phone number, postal address, email address, Social Security number, driver’s license number, unique online identifiers, account log-ins, tax identification number, I-20 number, and any similar identifiers.
  - category: financial
    text: Bank and payment card statements, investment account statements, records related to applicant histories, on-time payment histories, tax statements, utility bills, paystubs and pay statements
  - category: biometric
    text: Faceprint, including your photograph and certain biometric data based on your photograph
  - category: location
    text: Precise geolocation data.
  - category: behavioral
    text: usage data, such as time spent on the Sites, pages visited, links clicked, language preferences
  - category: device
    text: Browser and device data, such as IP address, device type, operating system and internet browser type, screen resolution
  - category: demographic
    text: Age (40 years or older), race, color, ancestry, national origin, citizenship, religion or creed, marital status, medical condition
  - category: professional
    text: Records evidencing employment, paystub information, such as income amounts, employer, employer address
  deletion:
    route: email support@snappt.com
    text: Right to Delete . You have the right to request the deletion of your personal information that is collected or maintained by us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: fraud prevention and financial verification
    text: To provide fraud prevention (including identity verification) and financial verification services, on behalf of and for the exclusive benefit of Snappt Customers
  - purpose: customer support
    text: To provide you with customer support, including to contact you in response to an inquiry that you sent
  - purpose: improve products and services
    text: To provide you with better products and services and improve and grow our and our integration partners’ business
  - purpose: targeted advertising
    text: We “sell”/“share” your personal information with third parties as those terms are defined by California law, but only in the context of sharing your personal information with third party advertising platforms to facilitate targeted digital advertising.
  residency:
  - region: United States
    text: Snappt is a U.S. company with Users, Customers, and service providers located in the U.S. and in other countries.
  retention:
  - period: three (3) years after your last interaction with Snappt
    scope: Illinois biometric information
    text: it has been three (3) years after your last interaction with Snappt, whichever occurs earlier
  - period: null
    scope: general personal information
    text: We will not retain any personal information we collect about you for longer than is reasonably necessary for the disclosed purpose of using such personal information.
  rights:
  - right: know and access
    text: Right to Know and Access . You may have the right to request what personal information we collect, use, disclose, and/or sell, as applicable.
  - right: correct
    text: Right to Correct . You have the right to request the correction of your inaccurate personal information.
  - right: opt out of sale/sharing
    text: Right to Opt-Out of Sale/Sharing of my Personal Information . You have the right to request to be opted out from any sales/sharing of your personal information by us
  - right: limit use of sensitive personal information
    text: Right to Limit Use and Disclosure . You have the right to limit the use or disclosure of your sensitive personal information
  - right: non-discrimination
    text: Right to Non-Discrimination . You have the right not to be denied goods or services
  role:
    text: collects and handles personal information on behalf of each Customer and for that Customer’s exclusive benefit
    value: both
  sale_or_sharing:
    stance: conditional
    text: We “sell”/“share” your personal information with third parties as those terms are defined by California law, but only in the context of sharing your personal information with third party advertising platforms to facilitate targeted digital advertising.
  subprocessors:
    text: those services providers listed at https://snappt.com/msa
    url: https://snappt.com/msa
  transfers:
  - mechanism: adequacy
    text: transferring your personal information to a country where authorities have determined there is an adequate level of protection of your personal information
  - mechanism: SCC
    text: or by implementing Standard Contractual Clauses with our Customers, service providers, and others.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Snappt
provenance_date: '2026-11-10'
provider_name: Snappt
provider_slug: snappt
slug: snappt-privacy-policy
source_date: '2026-11-10'
source_filename: snappt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://snappt.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Snappt\naid: snappt\nurl: https://snappt.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: collects and handles personal information on behalf of each Customer and for that Customer’s exclusive benefit\ndata_categories:\n- category: identifying\n  text: Your first and last name, alias, phone number, postal address, email address, Social Security number, driver’s\n    license number, unique online identifiers, account log-ins, tax identification number, I-20 number, and any\n    similar identifiers.\n- category: financial\n  text: Bank and payment card statements,\
  \ investment account statements, records related to applicant histories,\n    on-time payment histories, tax statements, utility bills, paystubs and pay statements\n- category: biometric\n  text: Faceprint, including your photograph and certain biometric data based on your photograph\n- category: location\n  text: Precise geolocation data.\n- category: behavioral\n  text: usage data, such as time spent on the Sites, pages visited, links clicked, language preferences\n- category: device\n  text: Browser and device data, such as IP address, device type, operating system and internet browser type, screen\n    resolution\n- category: demographic\n  text: Age (40 years or older), race, color, ancestry, national origin, citizenship, religion or creed, marital\n    status, medical condition\n- category: professional\n  text: Records evidencing employment, paystub information, such as income amounts, employer, employer address\npurposes:\n- purpose: fraud prevention and financial verification\n\
  \  text: To provide fraud prevention (including identity verification) and financial verification services, on behalf\n    of and for the exclusive benefit of Snappt Customers\n- purpose: customer support\n  text: To provide you with customer support, including to contact you in response to an inquiry that you sent\n- purpose: improve products and services\n  text: To provide you with better products and services and improve and grow our and our integration partners’\n    business\n- purpose: targeted advertising\n  text: We “sell”/“share” your personal information with third parties as those terms are defined by California\n    law, but only in the context of sharing your personal information with third party advertising platforms to\n    facilitate targeted digital advertising.\nretention:\n- scope: Illinois biometric information\n  period: three (3) years after your last interaction with Snappt\n  text: it has been three (3) years after your last interaction with Snappt, whichever occurs\
  \ earlier\n- scope: general personal information\n  period: null\n  text: We will not retain any personal information we collect about you for longer than is reasonably necessary\n    for the disclosed purpose of using such personal information.\nresidency:\n- region: United States\n  text: Snappt is a U.S. company with Users, Customers, and service providers located in the U.S. and in other countries.\ntransfers:\n- mechanism: adequacy\n  text: transferring your personal information to a country where authorities have determined there is an adequate\n    level of protection of your personal information\n- mechanism: SCC\n  text: or by implementing Standard Contractual Clauses with our Customers, service providers, and others.\nsubprocessors:\n  url: https://snappt.com/msa\n  text: those services providers listed at https://snappt.com/msa\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@snappt.com\n  text: Right to Delete . You have the right to request\
  \ the deletion of your personal information that is collected\n    or maintained by us.\nrights:\n- right: know and access\n  text: Right to Know and Access . You may have the right to request what personal information we collect, use,\n    disclose, and/or sell, as applicable.\n- right: correct\n  text: Right to Correct . You have the right to request the correction of your inaccurate personal information.\n- right: opt out of sale/sharing\n  text: Right to Opt-Out of Sale/Sharing of my Personal Information . You have the right to request to be opted\n    out from any sales/sharing of your personal information by us\n- right: limit use of sensitive personal information\n  text: Right to Limit Use and Disclosure . You have the right to limit the use or disclosure of your sensitive\n    personal information\n- right: non-discrimination\n  text: Right to Non-Discrimination . You have the right not to be denied goods or services\nsale_or_sharing:\n  stance: conditional\n  text: We “sell”/“share”\
  \ your personal information with third parties as those terms are defined by California\n    law, but only in the context of sharing your personal information with third party advertising platforms to\n    facilitate targeted digital advertising.\n"
source_yaml_url: https://artifacts.apis.io/snappt/privacy/snappt-privacy-policy.yml
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
- sale_or_sharing
summary_line: 26 quoted statements, read from Snappt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fraud Prevention
- Document Verification
- Identity Verification
- Income Verification
- Property Management
- Multifamily
- Real Estate
- PropTech
- Tenant Screening
- Rental Applications
- Webhook
---
