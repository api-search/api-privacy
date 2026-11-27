---
api_specs:
- filename: signzy-authentication-api-openapi.yml
  format: yaml
  label: Signzy Authentication API
  slug: signzy-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-authentication-api-openapi.yml
- filename: signzy-banking-api-openapi.yml
  format: yaml
  label: Signzy Banking API
  slug: signzy-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-banking-api-openapi.yml
- filename: signzy-identity-india-api-openapi.yml
  format: yaml
  label: Signzy Identity (India) API
  slug: signzy-identity-india-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-identity-india-api-openapi.yml
- filename: signzy-identity-us-api-openapi.yml
  format: yaml
  label: Signzy Identity (US) API
  slug: signzy-identity-us-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-identity-us-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, date of birth, address, email, phone number, and other contact details provided during registration or via API payloads.
  - category: biometric
    text: Facial images, facial biometric templates, and liveness check results collected via our Face Match and Liveness Check APIs.
  - category: device
    text: IP addresses, device identifiers, browser types, cookie data, and usage logs that help us manage, secure, and improve our API Services.
  - category: location
    text: The location of your device.
  - category: identifying
    text: Images and data extracted from driver’s licenses, passports, national IDs, EIN documents, and SSN information submitted through our verification APIs.
  deletion:
    route: Request deletion via Privacy@Signzy.com or via the customer as data controller
    text: Request deletion of your Personal Information, subject to any legal or contractual constraints.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: identity and business verification
    text: To perform identity, document, and business verifications via our APIs
  - purpose: AML and fraud prevention
    text: To conduct PEP screenings and monitor for fraudulent activities, ensuring compliance with AML and other regulatory mandates.
  residency:
  - region: United States, India, and other jurisdictions
    text: Personal Information may be maintained, processed, and stored by Signzy and our authorised affiliates, partners and service providers in the United States of America, India, and other jurisdictions as necessary
  retention:
  - period: null
    scope: personal information
    text: Specific retention periods may vary based on the type of data and regulatory requirements.
  rights:
  - right: Access and Correction
    text: Request access to and correction of your Personal Information.
  - right: Deletion
    text: Request deletion of your Personal Information, subject to any legal or contractual constraints.
  - right: Objection and Restriction
    text: Object to or request restrictions on certain processing activities.
  - right: Data Portability
    text: Request a copy of your data in a structured, commonly used, and machine-readable format.
  role:
    text: We are categorised as a ‘data processor’ under data protection laws when operating our business and providing Services to our Visitors and Users.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your Personal Information.
  subprocessors:
    text: Trusted vendors who assist us with hosting, data processing, analytics, security, and other functions under strict confidentiality obligations.
    url: null
  transfers:
  - mechanism: other
    text: we will implement adequate safeguards to ensure that your data remains protected in accordance not only with U.S. laws but also with the EU GDPR, the UK GDPR, Canadian privacy legislation
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Signzy
provenance_date: '2026-11-10'
provider_name: Signzy
provider_slug: signzy
slug: signzy-privacy-policy
source_date: '2026-11-10'
source_filename: signzy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.signzy.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Signzy\naid: signzy\nurl: https://www.signzy.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: We are categorised as a ‘data processor’ under data protection laws when operating our business and providing\n    Services to our Visitors and Users.\ndata_categories:\n- category: identifying\n  text: Name, date of birth, address, email, phone number, and other contact details provided during registration\n    or via API payloads.\n- category: biometric\n  text: Facial images, facial biometric templates, and liveness check results collected via our Face Match and Liveness\n    Check\
  \ APIs.\n- category: device\n  text: IP addresses, device identifiers, browser types, cookie data, and usage logs that help us manage, secure,\n    and improve our API Services.\n- category: location\n  text: The location of your device.\n- category: identifying\n  text: Images and data extracted from driver’s licenses, passports, national IDs, EIN documents, and SSN information\n    submitted through our verification APIs.\npurposes:\n- purpose: identity and business verification\n  text: To perform identity, document, and business verifications via our APIs\n- purpose: AML and fraud prevention\n  text: To conduct PEP screenings and monitor for fraudulent activities, ensuring compliance with AML and other\n    regulatory mandates.\nretention:\n- scope: personal information\n  period: null\n  text: Specific retention periods may vary based on the type of data and regulatory requirements.\nresidency:\n- region: United States, India, and other jurisdictions\n  text: Personal Information\
  \ may be maintained, processed, and stored by Signzy and our authorised affiliates, partners\n    and service providers in the United States of America, India, and other jurisdictions as necessary\ntransfers:\n- mechanism: other\n  text: we will implement adequate safeguards to ensure that your data remains protected in accordance not only\n    with U.S. laws but also with the EU GDPR, the UK GDPR, Canadian privacy legislation\nsubprocessors:\n  url: null\n  text: Trusted vendors who assist us with hosting, data processing, analytics, security, and other functions under\n    strict confidentiality obligations.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via Privacy@Signzy.com or via the customer as data controller\n  text: Request deletion of your Personal Information, subject to any legal or contractual constraints.\nrights:\n- right: Access and Correction\n  text: Request access to and correction of your Personal Information.\n- right: Deletion\n\
  \  text: Request deletion of your Personal Information, subject to any legal or contractual constraints.\n- right: Objection and Restriction\n  text: Object to or request restrictions on certain processing activities.\n- right: Data Portability\n  text: Request a copy of your data in a structured, commonly used, and machine-readable format.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your Personal Information.\n"
source_yaml_url: https://artifacts.apis.io/signzy/privacy/signzy-privacy-policy.yml
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
summary_line: 18 quoted statements, read from Signzy's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- KYC
- KYB
- AML
- Onboarding
- Compliance
- RegTech
---
