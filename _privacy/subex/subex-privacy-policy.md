---
api_specs:
- filename: subex-analytics-api-openapi.yml
  format: yaml
  label: Subex Analytics API
  slug: subex-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subex/openapi/subex-analytics-api-openapi.yml
- filename: subex-fraud-management-api-openapi.yml
  format: yaml
  label: Subex Fraud Management API
  slug: subex-fraud-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subex/openapi/subex-fraud-management-api-openapi.yml
- filename: subex-reconciliation-api-openapi.yml
  format: yaml
  label: Subex Reconciliation API
  slug: subex-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subex/openapi/subex-reconciliation-api-openapi.yml
- filename: subex-revenue-assurance-api-openapi.yml
  format: yaml
  label: Subex Revenue Assurance API
  slug: subex-revenue-assurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subex/openapi/subex-revenue-assurance-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Full name, business email address, phone number, company name, job title, and country.
  - category: professional
    text: Name, contact details, CV/resume, qualifications, work history, and any other information you choose to include.
  - category: device
    text: Anonymous IP address, browser type, device type, pages visited, time on page, and referring website.
  deletion:
    route: Email dpo@subex.com with the subject line 'Privacy Rights Request'
    text: Email us at dpo@subex.com with the subject line ‘Privacy Rights Request’.
  dpa:
    available: true
    text: We have signed data processing agreements with each of them.
    url: null
  purposes:
  - purpose: Respond to enquiries
    text: To respond to your enquiry, send you information you requested, and if you have opted in, to keep you updated about Subex products and events.
  - purpose: Assess job applications
    text: To assess your application and, if successful, to progress your candidacy.
  - purpose: Website analytics and security
    text: To understand how our website is used so we can improve it, and to maintain the security of our systems.
  residency:
  - region: India, UK, US, Singapore, UAE
    text: Your personal data may be transferred to and stored in countries outside your home country, including India, the United Kingdom, the United States, Singapore, and the UAE.
  retention:
  - period: 3 years
    scope: Enquiry / contact form data
    text: Enquiry / contact form data 3 years from your last interaction with us, or until you request deletion.
  - period: 2 years
    scope: Job application data (unsuccessful)
    text: Job application data (unsuccessful) 2 years (or longer with your consent).
  - period: 13 months
    scope: Website analytics data
    text: Website analytics data 13 months.
  - period: 90 days
    scope: Security logs
    text: Security logs 90 days (unless an incident requires longer retention).
  - period: 7 years
    scope: Contract and financial records
    text: Contract and financial records 7 years (required by accounting and tax law).
  rights:
  - right: Access
    text: You can ask us for a copy of the personal data we hold about you at any time.
  - right: Delete
    text: You can ask us to delete your personal data. We will do so unless we have a legal reason to keep it.
  - right: Correct
    text: If any of your personal data is wrong or out of date, you can ask us to fix it.
  - right: Object
    text: You can object to us using your data for marketing, or where we rely on ‘legitimate interests’.
  - right: Withdraw consent
    text: If you gave us consent to process your data, you can take it back at any time — it won’t affect anything we already did lawfully.
  role:
    text: Subex Limited (India) — the main data controller
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We use Standard Contractual Clauses (SCCs) legal contracts approved by the European Commission that require the recipient to protect your data to the same standard as the GDPR.
  - mechanism: adequacy
    text: The destination country has been approved of providing adequate data protection (for example, the UK has an adequacy decision from the EU).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Subex
provenance_date: '2026-11-10'
provider_name: Subex
provider_slug: subex
slug: subex-privacy-policy
source_date: '2026-11-10'
source_filename: subex-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.subex.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Subex\naid: subex\nurl: https://www.subex.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Subex Limited (India) — the main data controller\ndata_categories:\n- category: contact\n  text: Full name, business email address, phone number, company name, job title, and country.\n- category: professional\n  text: Name, contact details, CV/resume, qualifications, work history, and any other information you choose to\n    include.\n- category: device\n  text: Anonymous IP address, browser type, device type, pages visited, time on page, and referring website.\npurposes:\n- purpose:\
  \ Respond to enquiries\n  text: To respond to your enquiry, send you information you requested, and if you have opted in, to keep you updated\n    about Subex products and events.\n- purpose: Assess job applications\n  text: To assess your application and, if successful, to progress your candidacy.\n- purpose: Website analytics and security\n  text: To understand how our website is used so we can improve it, and to maintain the security of our systems.\nretention:\n- scope: Enquiry / contact form data\n  period: 3 years\n  text: Enquiry / contact form data 3 years from your last interaction with us, or until you request deletion.\n- scope: Job application data (unsuccessful)\n  period: 2 years\n  text: Job application data (unsuccessful) 2 years (or longer with your consent).\n- scope: Website analytics data\n  period: 13 months\n  text: Website analytics data 13 months.\n- scope: Security logs\n  period: 90 days\n  text: Security logs 90 days (unless an incident requires longer retention).\n\
  - scope: Contract and financial records\n  period: 7 years\n  text: Contract and financial records 7 years (required by accounting and tax law).\nresidency:\n- region: India, UK, US, Singapore, UAE\n  text: Your personal data may be transferred to and stored in countries outside your home country, including India,\n    the United Kingdom, the United States, Singapore, and the UAE.\ntransfers:\n- mechanism: SCC\n  text: We use Standard Contractual Clauses (SCCs) legal contracts approved by the European Commission that require\n    the recipient to protect your data to the same standard as the GDPR.\n- mechanism: adequacy\n  text: The destination country has been approved of providing adequate data protection (for example, the UK has\n    an adequacy decision from the EU).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We have signed data processing agreements with each of them.\ndeletion:\n  route: Email dpo@subex.com with the subject line 'Privacy\
  \ Rights Request'\n  text: Email us at dpo@subex.com with the subject line ‘Privacy Rights Request’.\nrights:\n- right: Access\n  text: You can ask us for a copy of the personal data we hold about you at any time.\n- right: Delete\n  text: You can ask us to delete your personal data. We will do so unless we have a legal reason to keep it.\n- right: Correct\n  text: If any of your personal data is wrong or out of date, you can ask us to fix it.\n- right: Object\n  text: You can object to us using your data for marketing, or where we rely on ‘legitimate interests’.\n- right: Withdraw consent\n  text: If you gave us consent to process your data, you can take it back at any time — it won’t affect anything\n    we already did lawfully.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/subex/privacy/subex-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Subex's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- Revenue Assurance
- Fraud Prevention
- Analytics
- BSS/OSS
---
