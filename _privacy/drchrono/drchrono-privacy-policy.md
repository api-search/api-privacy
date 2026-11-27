---
api_specs:
- filename: drchrono-administrative-api-openapi.yml
  format: yaml
  label: drchrono Administrative API
  slug: drchrono-administrative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-administrative-api-openapi.yml
- filename: drchrono-audit-api-openapi.yml
  format: yaml
  label: drchrono Audit API
  slug: drchrono-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-audit-api-openapi.yml
- filename: drchrono-availability-api-openapi.yml
  format: yaml
  label: drchrono Availability API
  slug: drchrono-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-availability-api-openapi.yml
- filename: drchrono-billing-api-openapi.yml
  format: yaml
  label: drchrono Billing API
  slug: drchrono-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-billing-api-openapi.yml
- filename: drchrono-clinical-api-openapi.yml
  format: yaml
  label: drchrono Clinical API
  slug: drchrono-clinical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-clinical-api-openapi.yml
- filename: drchrono-practice-management-api-openapi.yml
  format: yaml
  label: drchrono Practice Management API
  slug: drchrono-practice-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-practice-management-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact information, such as your and the Patients’ full name, email address, mobile phone number, and address
  - category: financial
    text: Payment information, such as your or the Patients’ credit card number, expiration date, and credit card security code
  - category: health
    text: Personal health information, including information about the Patient’s diagnosis, previous treatments, general health, health insurance
  - category: device
    text: Information we collect automatically. DrChrono and our third-party partners, such as analytics service providers, may collect certain information automatically
  - category: location
    text: We may also collect certain location information when you use our DrChrono Services, such as your computer’s IP address, your mobile device’s GPS signal
  deletion:
    route: Email request to delete Personal Information
    text: You may also request that we delete your Personal Information by sending us an email at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and improving services
    text: Providing and improving the DrChrono Services
  - purpose: Marketing to customers
    text: Sending you information about additional clinical services or general wellness from us or on behalf of our affiliates and trusted third-party partners
  - purpose: Research
    text: Conducting research using your information, which may be subject to your separate written authorization
  residency:
  - region: United States
    text: DrChrono maintains information in the United States and in accordance with the laws of the United States
  retention:
  - period: seven years
    scope: Archived information
    text: DrChrono may retain archived information for a period of seven years (or longer if required by law)
  - period: indefinitely
    scope: Non-personal information
    text: DrChrono indefinitely stores non-personal information, as well as any feedback you provide us.
  rights:
  - right: Opt out of certain general communications
    text: You may opt out of receiving certain general communications by emailing us at [email protected] .
  - right: Refuse or disable cookies
    text: You may be able to refuse or disable cookies by adjusting your web browser settings.
  - right: Request California disclosure information
    text: California residents are entitled once a year, free of charge, to request and obtain certain information regarding our disclosure, if any, of certain categories of Personal Information to third parties for their direct marketing purposes
  role:
    text: DrChrono acts as a service provider for health service providers and does not own or control the information that is submitted to us through the DrChrono Services.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Mobile numbers will not be shared with third parties for the purpose of sending their own marketing messages.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: you consent to the transfer of such data to the United States for processing by us in accordance with this Privacy Policy
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: drchrono
provenance_date: '2026-11-09'
provider_name: drchrono
provider_slug: drchrono
slug: drchrono-privacy-policy
source_date: '2026-11-09'
source_filename: drchrono-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.drchrono.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: drchrono\naid: drchrono\nurl: https://www.drchrono.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: DrChrono acts as a service provider for health service providers and does not own or control the information\n    that is submitted to us through the DrChrono Services.\ndata_categories:\n- category: identifying\n  text: Contact information, such as your and the Patients’ full name, email address, mobile phone number, and address\n- category: financial\n  text: Payment information, such as your or the Patients’ credit card number, expiration date, and credit card\n    security code\n\
  - category: health\n  text: Personal health information, including information about the Patient’s diagnosis, previous treatments, general\n    health, health insurance\n- category: device\n  text: Information we collect automatically. DrChrono and our third-party partners, such as analytics service providers,\n    may collect certain information automatically\n- category: location\n  text: We may also collect certain location information when you use our DrChrono Services, such as your computer’s\n    IP address, your mobile device’s GPS signal\npurposes:\n- purpose: Providing and improving services\n  text: Providing and improving the DrChrono Services\n- purpose: Marketing to customers\n  text: Sending you information about additional clinical services or general wellness from us or on behalf of our\n    affiliates and trusted third-party partners\n- purpose: Research\n  text: Conducting research using your information, which may be subject to your separate written authorization\nretention:\n\
  - scope: Archived information\n  period: seven years\n  text: DrChrono may retain archived information for a period of seven years (or longer if required by law)\n- scope: Non-personal information\n  period: indefinitely\n  text: DrChrono indefinitely stores non-personal information, as well as any feedback you provide us.\nresidency:\n- region: United States\n  text: DrChrono maintains information in the United States and in accordance with the laws of the United States\ntransfers:\n- mechanism: other\n  text: you consent to the transfer of such data to the United States for processing by us in accordance with this\n    Privacy Policy\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to delete Personal Information\n  text: You may also request that we delete your Personal Information by sending us an email at [email protected]\n    .\nrights:\n- right: Opt out of certain general communications\n  text: You\
  \ may opt out of receiving certain general communications by emailing us at [email protected] .\n- right: Refuse or disable cookies\n  text: You may be able to refuse or disable cookies by adjusting your web browser settings.\n- right: Request California disclosure information\n  text: California residents are entitled once a year, free of charge, to request and obtain certain information\n    regarding our disclosure, if any, of certain categories of Personal Information to third parties for their direct\n    marketing purposes\nsale_or_sharing:\n  stance: conditional\n  text: Mobile numbers will not be shared with third parties for the purpose of sending their own marketing messages.\n"
source_yaml_url: https://artifacts.apis.io/drchrono/privacy/drchrono-privacy-policy.yml
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
summary_line: 18 quoted statements, read from drchrono's own page on 2026-11-09.
synthetic: false
tags:
- Electronic Health Records
- Healthcare
- Medical Records
- Practice Management
- HIPAA
- Appointments
- Billing
- Prescriptions
- Lab Integration
- FHIR
- SMART on FHIR
- USCDI
- Interoperability
- Webhook
- Authentication
- ONC Certified
- Telehealth
- Revenue Cycle Management
---
