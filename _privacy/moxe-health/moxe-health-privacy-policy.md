---
api_specs:
- filename: moxe-health-claims-api-openapi.yml
  format: yaml
  label: Moxe Health Claims API
  slug: moxe-health-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxe-health/openapi/moxe-health-claims-api-openapi.yml
- filename: moxe-health-patient-api-openapi.yml
  format: yaml
  label: Moxe Health Patient API
  slug: moxe-health-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxe-health/openapi/moxe-health-patient-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up for an account, we ask you for your name, email address, title, your organization, and phone number.
  - category: device
    text: We receive information about the device and software you use to access our Services, which may include IP address, web browser type, operating system version, and application installations, and device identifiers.
  - category: behavioral
    text: we automatically receive information about your interactions with our Services, like the pages or other content you view, the searches you conduct, and the dates and times of your visits.
  - category: professional
    text: We will collect the information you choose to provide on your resume, such as your education and employment experience.
  - category: demographic
    text: We may receive additional information about you, such as demographic data, from third parties such as data or marketing partners
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, improve Services
    text: To provide, maintain, improve, and enhance our Services;
  - purpose: Marketing and advertising
    text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials that may be relevant, valuable or otherwise of interest to you;
  - purpose: Fraud and abuse prevention
    text: To find and prevent fraud and abuse, and respond to trust and safety issues that may arise;
  residency:
  - region: United States
    text: Our Services are hosted in the United States and intended for visitors located within the United States.
  rights:
  - right: Unsubscribe from promotional emails
    text: You can unsubscribe from our promotional emails via the link provided in the emails.
  role:
    text: Moxe does so in its capacity as a “business associate” to those health care providers.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not rent, sell, or share information about you with nonaffiliated companies for their direct marketing purposes, unless we have your permission.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we may transfer your data from the U.S. to other countries or regions in connection with storage and processing of data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Moxe Health
provenance_date: '2026-11-10'
provider_name: Moxe Health
provider_slug: moxe-health
slug: moxe-health-privacy-policy
source_date: '2026-11-10'
source_filename: moxe-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://moxehealth.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Moxe Health\naid: moxe-health\nurl: https://moxehealth.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Moxe does so in its capacity as a “business associate” to those health care providers.\ndata_categories:\n- category: identifying\n  text: When you sign up for an account, we ask you for your name, email address, title, your organization, and\n    phone number.\n- category: device\n  text: We receive information about the device and software you use to access our Services, which may include IP\n    address, web browser type, operating system version, and application installations,\
  \ and device identifiers.\n- category: behavioral\n  text: we automatically receive information about your interactions with our Services, like the pages or other\n    content you view, the searches you conduct, and the dates and times of your visits.\n- category: professional\n  text: We will collect the information you choose to provide on your resume, such as your education and employment\n    experience.\n- category: demographic\n  text: We may receive additional information about you, such as demographic data, from third parties such as data\n    or marketing partners\npurposes:\n- purpose: Provide, maintain, improve Services\n  text: To provide, maintain, improve, and enhance our Services;\n- purpose: Marketing and advertising\n  text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials\n    that may be relevant, valuable or otherwise of interest to you;\n- purpose: Fraud and abuse prevention\n  text: To find and prevent\
  \ fraud and abuse, and respond to trust and safety issues that may arise;\nretention: []\nresidency:\n- region: United States\n  text: Our Services are hosted in the United States and intended for visitors located within the United States.\ntransfers:\n- mechanism: other\n  text: we may transfer your data from the U.S. to other countries or regions in connection with storage and processing\n    of data\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Unsubscribe from promotional emails\n  text: You can unsubscribe from our promotional emails via the link provided in the emails.\nsale_or_sharing:\n  stance: conditional\n  text: We do not rent, sell, or share information about you with nonaffiliated companies for their direct marketing\n    purposes, unless we have your permission.\n"
source_yaml_url: https://artifacts.apis.io/moxe-health/privacy/moxe-health-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- residency
- transfers
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Moxe Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- Interoperability
- Clinical Data
- Payers
- Providers
- Electronic Health Records
- Health Data Exchange
- Claims
- Risk Adjustment
---
