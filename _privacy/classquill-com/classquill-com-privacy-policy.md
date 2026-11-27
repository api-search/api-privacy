---
api_specs:
- filename: classquill-com-billing-api-openapi.yml
  format: yaml
  label: ClassQuill Billing API
  slug: classquill-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-billing-api-openapi.yml
- filename: classquill-com-blog-api-openapi.yml
  format: yaml
  label: ClassQuill Blog API
  slug: classquill-com-blog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-blog-api-openapi.yml
- filename: classquill-com-bookings-api-openapi.yml
  format: yaml
  label: ClassQuill Bookings API
  slug: classquill-com-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-bookings-api-openapi.yml
- filename: classquill-com-coursework-api-openapi.yml
  format: yaml
  label: ClassQuill Coursework API
  slug: classquill-com-coursework-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-coursework-api-openapi.yml
- filename: classquill-com-curriculum-api-openapi.yml
  format: yaml
  label: ClassQuill Curriculum API
  slug: classquill-com-curriculum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-curriculum-api-openapi.yml
- filename: classquill-com-general-api-openapi.yml
  format: yaml
  label: ClassQuill General API
  slug: classquill-com-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-general-api-openapi.yml
- filename: classquill-com-operations-api-openapi.yml
  format: yaml
  label: ClassQuill Operations API
  slug: classquill-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-operations-api-openapi.yml
- filename: classquill-com-pricing-api-openapi.yml
  format: yaml
  label: ClassQuill Pricing API
  slug: classquill-com-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-pricing-api-openapi.yml
- filename: classquill-com-reports-api-openapi.yml
  format: yaml
  label: ClassQuill Reports API
  slug: classquill-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-reports-api-openapi.yml
- filename: classquill-com-sessions-api-openapi.yml
  format: yaml
  label: ClassQuill Sessions API
  slug: classquill-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-sessions-api-openapi.yml
- filename: classquill-com-students-parents-api-openapi.yml
  format: yaml
  label: ClassQuill Students & Parents API
  slug: classquill-com-students-parents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-students-parents-api-openapi.yml
- filename: classquill-com-tutors-api-openapi.yml
  format: yaml
  label: ClassQuill Tutors API
  slug: classquill-com-tutors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-tutors-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity Data: Your name, email address, and business name provided during signup.'
  - category: contact
    text: 'Contact Data: Business address, phone number, and billing contact information.'
  - category: financial
    text: 'Billing Data: Payment method details are handled by Stripe. We store only transaction records and subscription status for billing management.'
  - category: location
    text: Location information for in-person session matching and mileage tracking
  - category: behavioral
    text: We collect data about how users interact with the platform (pages visited, features used, session duration) to improve the Service.
  - category: device
    text: Sentry may collect IP address, browser information, and error context when issues occur.
  deletion:
    route: Request via email to the contact address
    text: Request deletion of your Personal Data (subject to legal retention obligations).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Provide and maintain the Service — operating the platform and managing your account and subscriptions.
  - purpose: Billing and payments
    text: Billing and payments — processing subscription charges and seat adjustments.
  - purpose: Service improvement
    text: Service improvement — analysing usage patterns to improve features (using aggregated, anonymised data).
  - purpose: Communications
    text: Communications — sending service updates, product announcements, and billing notifications.
  residency:
  - region: Outside Australia
    text: Your information, including Personal Data, may be transferred to and maintained on computers located outside of Australia where data protection laws may differ.
  retention:
  - period: up to 12 months
    scope: Analytics data
    text: 'Analytics data: Anonymised usage data retained for up to 12 months.'
  - period: up to 90 days
    scope: Error logs
    text: 'Error logs: Retained for up to 90 days.'
  - period: until you delete it or cancel your account
    scope: Student & session data
    text: 'Student & session data: Retained until you delete it or cancel your account.'
  rights:
  - right: Access
    text: Access a copy of the Personal Data we hold about you.
  - right: Correction
    text: Request correction of any inaccurate Personal Data.
  - right: Deletion
    text: Request deletion of your Personal Data (subject to legal retention obligations).
  - right: Data export
    text: Request a data export of your account and business data before cancellation.
  role:
    text: For your ClassQuill account and subscription, we are the Data Controller. For student and client data that your business stores within ClassQuill, your tutoring business is the Data Controller and ClassQuill acts as a Data Processor on your behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: By using the Service, you consent to this transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClassQuill
provenance_date: '2026-11-09'
provider_name: ClassQuill
provider_slug: classquill-com
slug: classquill-com-privacy-policy
source_date: '2026-11-09'
source_filename: classquill-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://classquill.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClassQuill\naid: classquill-com\nurl: https://classquill.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your ClassQuill account and subscription, we are the Data Controller. For student and client data that\n    your business stores within ClassQuill, your tutoring business is the Data Controller and ClassQuill acts as\n    a Data Processor on your behalf.\ndata_categories:\n- category: identifying\n  text: 'Identity Data: Your name, email address, and business name provided during signup.'\n- category: contact\n  text: 'Contact Data: Business address, phone number, and billing\
  \ contact information.'\n- category: financial\n  text: 'Billing Data: Payment method details are handled by Stripe. We store only transaction records and subscription\n    status for billing management.'\n- category: location\n  text: Location information for in-person session matching and mileage tracking\n- category: behavioral\n  text: We collect data about how users interact with the platform (pages visited, features used, session duration)\n    to improve the Service.\n- category: device\n  text: Sentry may collect IP address, browser information, and error context when issues occur.\npurposes:\n- purpose: Provide and maintain the Service\n  text: Provide and maintain the Service — operating the platform and managing your account and subscriptions.\n- purpose: Billing and payments\n  text: Billing and payments — processing subscription charges and seat adjustments.\n- purpose: Service improvement\n  text: Service improvement — analysing usage patterns to improve features (using aggregated,\
  \ anonymised data).\n- purpose: Communications\n  text: Communications — sending service updates, product announcements, and billing notifications.\nretention:\n- scope: Analytics data\n  period: up to 12 months\n  text: 'Analytics data: Anonymised usage data retained for up to 12 months.'\n- scope: Error logs\n  period: up to 90 days\n  text: 'Error logs: Retained for up to 90 days.'\n- scope: Student & session data\n  period: until you delete it or cancel your account\n  text: 'Student & session data: Retained until you delete it or cancel your account.'\nresidency:\n- region: Outside Australia\n  text: Your information, including Personal Data, may be transferred to and maintained on computers located outside\n    of Australia where data protection laws may differ.\ntransfers:\n- mechanism: other\n  text: By using the Service, you consent to this transfer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via\
  \ email to the contact address\n  text: Request deletion of your Personal Data (subject to legal retention obligations).\nrights:\n- right: Access\n  text: Access a copy of the Personal Data we hold about you.\n- right: Correction\n  text: Request correction of any inaccurate Personal Data.\n- right: Deletion\n  text: Request deletion of your Personal Data (subject to legal retention obligations).\n- right: Data export\n  text: Request a data export of your account and business data before cancellation.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/classquill-com/privacy/classquill-com-privacy-policy.yml
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
summary_line: 22 quoted statements, read from ClassQuill's own page on 2026-11-09.
synthetic: false
tags:
- Tutoring
- Scheduling
- Invoicing
- Payroll
- Learning Platform
- Education
---
