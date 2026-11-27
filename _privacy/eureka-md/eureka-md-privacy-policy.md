---
api_specs:
- filename: eureka-md-openapi-generated.yml
  format: yaml
  label: Eureka Health API
  slug: eureka-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eureka-md/openapi/_ae-authored/eureka-md-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact and account information , such as name, email address, phone number, postal address, account credentials, authentication information, and communication preferences.
  - category: demographic
    text: date of birth, sex or gender information, government identifier information, photographs, selfie images
  - category: health
    text: Health and care-related information , such as symptoms, medical history, medications, allergies, diagnoses, treatment history, pharmacy information, laboratory information
  - category: financial
    text: payment card information (generally via payment processors)
  - category: location
    text: Approximate location information , such as location inferred from IP address and, where enabled by your device or browser and permitted by law, more precise location information.
  - category: device
    text: Device and browser information , such as IP address, device identifiers, browser type, operating system, language settings, mobile carrier, and app or browser version.
  - category: behavioral
    text: Usage and log information , such as pages viewed, clicks, navigation paths, session timestamps, referrers, crash reports, performance metrics, search queries, and interactions with features.
  - category: communication
    text: Support and communications , such as emails, text messages, calls, voicemails, support tickets, survey responses, and other correspondence you send to us or through the Service.
  deletion:
    route: Email support@eureka.md to request account deletion
    text: You may request deletion of your account by contacting support@eureka.md .
  dpa:
    available: null
    text: Where required, we enter into contracts, including business associate agreements or equivalent contractual restrictions, with subcontractors that create, receive, maintain, or transmit PHI on our behalf.
    url: null
  purposes:
  - purpose: provide, operate and improve the Service
    text: To provide, operate, maintain, secure, and improve the Service;
  - purpose: connect users with Providers
    text: To connect users with Providers, facilitate scheduling, support virtual encounters, enable communications, and otherwise support the delivery of care by independent Providers;
  - purpose: marketing communications
    text: To send marketing, educational, promotional, survey, and similar communications, subject to your preferences and applicable law;
  - purpose: de-identified analytics
    text: To create de-identified, anonymized, or aggregated data sets, reports, analytics, statistics, and business insights;
  residency:
  - region: United States
    text: The Service is intended for use in the United States.
  retention:
  - period: null
    scope: general information
    text: We retain information for as long as reasonably necessary for the purposes described in this Privacy Policy
  - period: null
    scope: medical records and PHI
    text: Medical records and PHI may be retained by Providers or on their behalf for periods required by healthcare laws and professional recordkeeping obligations, even if you close your account or ask us to delete information.
  rights:
  - right: access
    text: provide access to certain personal information
  - right: correct
    text: correct inaccuracies in certain personal information
  - right: delete
    text: delete certain personal information
  - right: portability
    text: provide a portable copy of certain personal information
  - right: opt out or limit processing
    text: limit or opt out of certain processing where applicable law grants that right.
  role:
    text: Eureka may process PHI on behalf of Providers as a service provider, contractor, processor, or business associate, as applicable.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information to data brokers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: your information may be transferred to, stored in, and processed in the United States and other jurisdictions where our service providers operate, subject to applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Eureka Health
provenance_date: '2026-11-09'
provider_name: Eureka Health
provider_slug: eureka-md
slug: eureka-md-privacy-policy
source_date: '2026-11-09'
source_filename: eureka-md-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eureka.md/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Eureka Health\naid: eureka-md\nurl: https://eureka.md/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Eureka may process PHI on behalf of Providers as a service provider, contractor, processor, or business\n    associate, as applicable.\ndata_categories:\n- category: identifying\n  text: Contact and account information , such as name, email address, phone number, postal address, account credentials,\n    authentication information, and communication preferences.\n- category: demographic\n  text: date of birth, sex or gender information, government identifier information, photographs, selfie\
  \ images\n- category: health\n  text: Health and care-related information , such as symptoms, medical history, medications, allergies, diagnoses,\n    treatment history, pharmacy information, laboratory information\n- category: financial\n  text: payment card information (generally via payment processors)\n- category: location\n  text: Approximate location information , such as location inferred from IP address and, where enabled by your\n    device or browser and permitted by law, more precise location information.\n- category: device\n  text: Device and browser information , such as IP address, device identifiers, browser type, operating system,\n    language settings, mobile carrier, and app or browser version.\n- category: behavioral\n  text: Usage and log information , such as pages viewed, clicks, navigation paths, session timestamps, referrers,\n    crash reports, performance metrics, search queries, and interactions with features.\n- category: communication\n  text: Support and\
  \ communications , such as emails, text messages, calls, voicemails, support tickets, survey responses,\n    and other correspondence you send to us or through the Service.\npurposes:\n- purpose: provide, operate and improve the Service\n  text: To provide, operate, maintain, secure, and improve the Service;\n- purpose: connect users with Providers\n  text: To connect users with Providers, facilitate scheduling, support virtual encounters, enable communications,\n    and otherwise support the delivery of care by independent Providers;\n- purpose: marketing communications\n  text: To send marketing, educational, promotional, survey, and similar communications, subject to your preferences\n    and applicable law;\n- purpose: de-identified analytics\n  text: To create de-identified, anonymized, or aggregated data sets, reports, analytics, statistics, and business\n    insights;\nretention:\n- scope: general information\n  period: null\n  text: We retain information for as long as reasonably\
  \ necessary for the purposes described in this Privacy Policy\n- scope: medical records and PHI\n  period: null\n  text: Medical records and PHI may be retained by Providers or on their behalf for periods required by healthcare\n    laws and professional recordkeeping obligations, even if you close your account or ask us to delete information.\nresidency:\n- region: United States\n  text: The Service is intended for use in the United States.\ntransfers:\n- mechanism: other\n  text: your information may be transferred to, stored in, and processed in the United States and other jurisdictions\n    where our service providers operate, subject to applicable law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Where required, we enter into contracts, including business associate agreements or equivalent contractual\n    restrictions, with subcontractors that create, receive, maintain, or transmit PHI on our behalf.\ndeletion:\n  route: Email support@eureka.md\
  \ to request account deletion\n  text: You may request deletion of your account by contacting support@eureka.md .\nrights:\n- right: access\n  text: provide access to certain personal information\n- right: correct\n  text: correct inaccuracies in certain personal information\n- right: delete\n  text: delete certain personal information\n- right: portability\n  text: provide a portable copy of certain personal information\n- right: opt out or limit processing\n  text: limit or opt out of certain processing where applicable law grants that right.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information to data brokers.\n"
source_yaml_url: https://artifacts.apis.io/eureka-md/privacy/eureka-md-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Eureka Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Automation
- Claims
- Prior Authorization
- Software-as-a-Service
---
