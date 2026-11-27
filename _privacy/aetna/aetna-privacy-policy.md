---
api_specs:
- filename: aetna-endpoint-api-openapi.yml
  format: yaml
  label: Aetna Endpoint API
  slug: aetna-endpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-endpoint-api-openapi.yml
- filename: aetna-location-api-openapi.yml
  format: yaml
  label: Aetna Location API
  slug: aetna-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-location-api-openapi.yml
- filename: aetna-organization-api-openapi.yml
  format: yaml
  label: Aetna Organization API
  slug: aetna-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-organization-api-openapi.yml
- filename: aetna-organizationaffiliation-api-openapi.yml
  format: yaml
  label: Aetna Organization Affiliation API
  slug: aetna-organizationaffiliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-organizationaffiliation-api-openapi.yml
- filename: aetna-practitioner-api-openapi.yml
  format: yaml
  label: Aetna Practitioner API
  slug: aetna-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-practitioner-api-openapi.yml
- filename: aetna-providerdirectorydata-api-openapi.yml
  format: yaml
  label: Aetna Providerdirectorydata API
  slug: aetna-providerdirectorydata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-providerdirectorydata-api-openapi.yml
- filename: aetna-patient-access-api-openapi.yml
  format: yaml
  label: Aetna Patient Access API
  slug: aetna-patient-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-patient-access-api-openapi.yml
- filename: aetna-provider-directory-api-openapi.yml
  format: yaml
  label: Aetna Provider Directory API
  slug: aetna-provider-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-provider-directory-api-openapi.yml
- filename: aetna-healthcare-service-api-openapi.yml
  format: yaml
  label: Aetna Healthcare Service API
  slug: aetna-healthcare-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-healthcare-service-api-openapi.yml
- filename: aetna-insurance-plan-api-openapi.yml
  format: yaml
  label: Aetna Insurance Plan API
  slug: aetna-insurance-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-insurance-plan-api-openapi.yml
- filename: aetna-practitioner-role-api-openapi.yml
  format: yaml
  label: Aetna Practitioner Role API
  slug: aetna-practitioner-role-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-practitioner-role-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information , such as name, postal address, email address and phone number.
  - category: device
    text: Device and network information , such as IP address, cookies and other online identifiers.
  - category: behavioral
    text: Internet activity and interactions , such as the webpages you visit and how you use the Services.
  - category: location
    text: Non-precise geolocation data , such as the state you live in.
  - category: other
    text: Preferences and feedback , such as communications you wish to receive or surveys.
  - category: financial
    text: Payment or financial information , such as your EFT (Electronic Funds Transfer) banking information if you initiate a payment transaction with us.
  deletion:
    route: Member Services at the phone number on your ID card
    text: You can request the removal or modification of the personal information you have provided to us by contacting Member Services at the phone number on your ID card.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: marketing communications
    text: Send you communications and marketing materials , such as when you create an account.
  - purpose: business purposes and analytics
    text: For our business purposes , such as data analysis, audits, fraud monitoring and prevention, detect and investigate incidents or breaches, developing our Services and new products and services.
  - purpose: personalization
    text: To personalize and tailor the Services , such as providing you with content, products and services that are most likely to appeal to you.
  residency:
  - region: United States
    text: The Services are designed for users from, and are controlled and operated by us from, the United States.
  retention:
  - period: null
    scope: after a change or deletion request
    text: Please note that we may need to retain certain information for recordkeeping purposes and/or to complete any transactions that you began prior to requesting such change or deletion.
  rights:
  - right: removal or modification of information
    text: You can request the removal or modification of the personal information you have provided to us by contacting Member Services at the phone number on your ID card.
  - right: communication preferences
    text: You can change your communication preferences at any time on your profile page or by contacting Member Services at the phone number on your ID card.
  - right: California shared-information request
    text: you may request that we provide you with certain information about the entities with which we have shared our customers' personal information for direct marketing purposes during the preceding calendar year.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: By using the Services, you consent to the transfer of your information to the United States or storage of your information in the United States
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aetna
provenance_date: '2026-11-09'
provider_name: Aetna
provider_slug: aetna
slug: aetna-privacy-policy
source_date: '2026-11-09'
source_filename: aetna-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aetna.com/legal-notices/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aetna\naid: aetna\nurl: https://www.aetna.com/legal-notices/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact information , such as name, postal address, email address and phone number.\n- category: device\n  text: Device and network information , such as IP address, cookies and other online identifiers.\n- category: behavioral\n  text: Internet activity and interactions , such as the webpages you visit and how you use the Services.\n- category: location\n  text: Non-precise geolocation data , such as the\
  \ state you live in.\n- category: other\n  text: Preferences and feedback , such as communications you wish to receive or surveys.\n- category: financial\n  text: Payment or financial information , such as your EFT (Electronic Funds Transfer) banking information if you\n    initiate a payment transaction with us.\npurposes:\n- purpose: marketing communications\n  text: Send you communications and marketing materials , such as when you create an account.\n- purpose: business purposes and analytics\n  text: For our business purposes , such as data analysis, audits, fraud monitoring and prevention, detect and investigate\n    incidents or breaches, developing our Services and new products and services.\n- purpose: personalization\n  text: To personalize and tailor the Services , such as providing you with content, products and services that\n    are most likely to appeal to you.\nretention:\n- scope: after a change or deletion request\n  period: null\n  text: Please note that we may need\
  \ to retain certain information for recordkeeping purposes and/or to complete\n    any transactions that you began prior to requesting such change or deletion.\nresidency:\n- region: United States\n  text: The Services are designed for users from, and are controlled and operated by us from, the United States.\ntransfers:\n- mechanism: other\n  text: By using the Services, you consent to the transfer of your information to the United States or storage of\n    your information in the United States\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Member Services at the phone number on your ID card\n  text: You can request the removal or modification of the personal information you have provided to us by contacting\n    Member Services at the phone number on your ID card.\nrights:\n- right: removal or modification of information\n  text: You can request the removal or modification of the personal information you have provided\
  \ to us by contacting\n    Member Services at the phone number on your ID card.\n- right: communication preferences\n  text: You can change your communication preferences at any time on your profile page or by contacting Member Services\n    at the phone number on your ID card.\n- right: California shared-information request\n  text: you may request that we provide you with certain information about the entities with which we have shared\n    our customers' personal information for direct marketing purposes during the preceding calendar year.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aetna/privacy/aetna-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from Aetna's own page on 2026-11-09.
synthetic: false
tags:
- Health Insurance
- Healthcare
- FHIR
- Patient Access
- Provider Directory
- Drug Formulary
- Prior Authorization
- CMS Interoperability
- SMART on FHIR
- CARIN Blue Button
- Da Vinci
- Payers
- Fortune 100
- CVS Health
---
