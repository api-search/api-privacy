---
api_specs:
- filename: thatch-health-deductions-api-openapi.yml
  format: yaml
  label: Thatch Health Deductions API
  slug: thatch-health-deductions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-deductions-api-openapi.yml
- filename: thatch-health-employees-api-openapi.yml
  format: yaml
  label: Thatch Health Employees API
  slug: thatch-health-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-employees-api-openapi.yml
- filename: thatch-health-employer-onboarding-sessions-api-openapi.yml
  format: yaml
  label: Thatch Health Employer onboarding sessions API
  slug: thatch-health-employer-onboarding-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-employer-onboarding-sessions-api-openapi.yml
- filename: thatch-health-employers-api-openapi.yml
  format: yaml
  label: Thatch Health Employers API
  slug: thatch-health-employers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-employers-api-openapi.yml
- filename: thatch-health-enrollments-api-openapi.yml
  format: yaml
  label: Thatch Health Enrollments API
  slug: thatch-health-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-enrollments-api-openapi.yml
- filename: thatch-health-members-api-openapi.yml
  format: yaml
  label: Thatch Health Members API
  slug: thatch-health-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-members-api-openapi.yml
- filename: thatch-health-pay-schedules-api-openapi.yml
  format: yaml
  label: Thatch Health Pay Schedules API
  slug: thatch-health-pay-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thatch-health/openapi/thatch-health-pay-schedules-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: A real name, postal address, email address, Social Security number, account name, IP address, unique personal identifier, telephone number, employment information, bank account number, insurance policy number, and health insurance information.
  - category: health
    text: Examples of PHI we may encounter include information about your health plan coverage, data used to determine your eligibility for benefits, and records of health-related goods or services purchased using your ICHRA allowance.
  - category: location
    text: We collect IP-based information about your physical location or movements.
  - category: behavioral
    text: Profile reflecting a person’s preferences.
  - category: device
    text: IP address, device model, device ID, operating system version, device language, operating system, browser type, mobile network information, and advertising ID.
  - category: financial
    text: Products or services purchased, obtained, or considered (e.g., marketplace purchases and plan selections).
  - category: professional
    text: Job title, salary, other compensation details, licenses or certification, and dependents or beneficiaries.
  deletion:
    route: Contact us or Account dashboard
    text: You may also contact us at any time using the contact information provided in Section XVI of this Policy to inform us of any changes or errors in any Personal Information we have about you to ensure that it is complete, accurate, and as current as possible or to delete your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and develop Services
    text: Provide, support, personalize, and develop our Services, including monitoring and analyzing the effectiveness of content and features
  - purpose: Process payments and transactions
    text: Process your requests, purchases, transactions, and payments, including facilitating premium payments, marketplace purchases, and qualified medical expense claims
  - purpose: Marketing
    text: Promote and market our Platform and/or Services, the products and services of our affiliates, and the products and services of third-party partners.
  - purpose: AI and model training
    text: We may use information we collect to internally refine, improve, and train the models and algorithms that support our AI features, in accordance with applicable law.
  - purpose: Security and fraud
    text: Help maintain the safety, security, and integrity of our business, Platform, products, Services, databases, and other technology assets.
  retention:
  - period: null
    scope: Personal Information
    text: We retain your Personal Information for as long as we continue to provide the Services to you, or for a period in which we reasonably foresee continuing to provide the Services.
  - period: 24 hours
    scope: Stripe session cookie
    text: These are considered session cookies and typically only remain on your browser for 24 hours.
  rights:
  - right: Access and correction
    text: You may request to review or change your Personal Information in your Thatch Account dashboard.
  - right: Opt out of marketing email
    text: you can opt-out at any time by clicking the unsubscribe link at the bottom of any email or other marketing communications you receive from us
  - right: Deletion of children's data on request
    text: If you are the parent or guardian of a child under 18 years of age whom you believe might have provided us with their Personal Information, you may contact us using the contact information provided in Section XVI of this Policy to request the Personal Information be deleted.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Thatch Health
provenance_date: '2026-11-10'
provider_name: Thatch Health
provider_slug: thatch-health
slug: thatch-health-privacy-policy
source_date: '2026-11-10'
source_filename: thatch-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thatch.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Thatch Health\naid: thatch-health\nurl: https://thatch.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: A real name, postal address, email address, Social Security number, account name, IP address, unique personal\n    identifier, telephone number, employment information, bank account number, insurance policy number, and health\n    insurance information.\n- category: health\n  text: Examples of PHI we may encounter include information about your health plan coverage, data used to determine\n    your eligibility\
  \ for benefits, and records of health-related goods or services purchased using your ICHRA allowance.\n- category: location\n  text: We collect IP-based information about your physical location or movements.\n- category: behavioral\n  text: Profile reflecting a person’s preferences.\n- category: device\n  text: IP address, device model, device ID, operating system version, device language, operating system, browser\n    type, mobile network information, and advertising ID.\n- category: financial\n  text: Products or services purchased, obtained, or considered (e.g., marketplace purchases and plan selections).\n- category: professional\n  text: Job title, salary, other compensation details, licenses or certification, and dependents or beneficiaries.\npurposes:\n- purpose: Provide and develop Services\n  text: Provide, support, personalize, and develop our Services, including monitoring and analyzing the effectiveness\n    of content and features\n- purpose: Process payments and transactions\n\
  \  text: Process your requests, purchases, transactions, and payments, including facilitating premium payments, marketplace\n    purchases, and qualified medical expense claims\n- purpose: Marketing\n  text: Promote and market our Platform and/or Services, the products and services of our affiliates, and the products\n    and services of third-party partners.\n- purpose: AI and model training\n  text: We may use information we collect to internally refine, improve, and train the models and algorithms that\n    support our AI features, in accordance with applicable law.\n- purpose: Security and fraud\n  text: Help maintain the safety, security, and integrity of our business, Platform, products, Services, databases,\n    and other technology assets.\nretention:\n- scope: Personal Information\n  period: null\n  text: We retain your Personal Information for as long as we continue to provide the Services to you, or for a\n    period in which we reasonably foresee continuing to provide the Services.\n\
  - scope: Stripe session cookie\n  period: 24 hours\n  text: These are considered session cookies and typically only remain on your browser for 24 hours.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us or Account dashboard\n  text: You may also contact us at any time using the contact information provided in Section XVI of this Policy\n    to inform us of any changes or errors in any Personal Information we have about you to ensure that it is complete,\n    accurate, and as current as possible or to delete your account.\nrights:\n- right: Access and correction\n  text: You may request to review or change your Personal Information in your Thatch Account dashboard.\n- right: Opt out of marketing email\n  text: you can opt-out at any time by clicking the unsubscribe link at the bottom of any email or other marketing\n    communications you receive from us\n- right: Deletion of children's\
  \ data on request\n  text: If you are the parent or guardian of a child under 18 years of age whom you believe might have provided\n    us with their Personal Information, you may contact us using the contact information provided in Section XVI\n    of this Policy to request the Personal Information be deleted.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thatch-health/privacy/thatch-health-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 18 quoted statements, read from Thatch Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Benefits
- ICHRA
- Insurance
- Payroll
- Embedded Benefits
- Human Resources
---
