---
api_specs:
- filename: nayya-benefits-api-openapi.yml
  format: yaml
  label: Nayya Benefits API
  slug: nayya-benefits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-benefits-api-openapi.yml
- filename: nayya-carriers-api-openapi.yml
  format: yaml
  label: Nayya Carriers API
  slug: nayya-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-carriers-api-openapi.yml
- filename: nayya-connections-api-openapi.yml
  format: yaml
  label: Nayya Connections API
  slug: nayya-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-connections-api-openapi.yml
- filename: nayya-dependents-api-openapi.yml
  format: yaml
  label: Nayya Dependents API
  slug: nayya-dependents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-dependents-api-openapi.yml
- filename: nayya-employees-api-openapi.yml
  format: yaml
  label: Nayya Employees API
  slug: nayya-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-employees-api-openapi.yml
- filename: nayya-employers-api-openapi.yml
  format: yaml
  label: Nayya Employers API
  slug: nayya-employers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-employers-api-openapi.yml
- filename: nayya-enrollments-api-openapi.yml
  format: yaml
  label: Nayya Enrollments API
  slug: nayya-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-enrollments-api-openapi.yml
- filename: nayya-recommendations-api-openapi.yml
  format: yaml
  label: Nayya Recommendations API
  slug: nayya-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-recommendations-api-openapi.yml
- filename: nayya-rule-templates-api-openapi.yml
  format: yaml
  label: Nayya Rule Templates API
  slug: nayya-rule-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-rule-templates-api-openapi.yml
- filename: nayya-snapshots-api-openapi.yml
  format: yaml
  label: Nayya Snapshots API
  slug: nayya-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-snapshots-api-openapi.yml
- filename: nayya-token-api-openapi.yml
  format: yaml
  label: Nayya Token API
  slug: nayya-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nayya/openapi/nayya-token-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, date of birth, social security number, address, phone number
  - category: health
    text: 'Health and healthcare information : medical conditions and activities, medical insurance-related information'
  - category: financial
    text: 'Financial Information : compensation, soft credit information, mortgage and other loan debt, spending preferences'
  - category: location
    text: 'Location Information : We may derive a rough estimate of your location from your IP address.'
  - category: behavioral
    text: 'Usage Information : Information about how you use our Service, such as the types of content that you view or engage with'
  - category: device
    text: 'Device Information : The manufacturer and model, operating system, browser type, IP address, and unique identifiers of the device'
  - category: communication
    text: 'Communication Information : We may collect information when you contact us with questions, feedback or concerns'
  deletion:
    route: Right to Delete request via privacynotices@nayya.com
    text: You may have the right to request that we delete certain personal information we have collected about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service and website delivery
    text: provide, operate, maintain, and secure the Services and Website
  - purpose: Marketing and advertising
    text: send you direct marketing communications, such as notifying you of special promotions, offers and events via email and other means.
  - purpose: Service improvement
    text: support, analyze, and improve the Services and Website and create new features
  - purpose: Compliance and protection
    text: comply with applicable laws, lawful requests, and legal process
  - purpose: Artificial intelligence
    text: We use artificial intelligence and machine learning technologies to provide, operate, secure, and improve the Services and Website
  residency:
  - region: United States
    text: Your information is stored in the United States.
  retention:
  - period: null
    scope: user information
    text: We retain your information in line with our Data Management Policy.
  rights:
  - right: Right to know
    text: You may have the right to request what personal information we have collected, used, disclosed, and shared about you in the preceding 12 months
  - right: Right to delete
    text: You may have the right to request that we delete certain personal information we have collected about you.
  - right: Right to correct
    text: You may have the right to request that we correct inaccurate personal information we have about you.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information for monetary consideration; however, our use of certain advertising and analytics technologies described in Section 3.6 may be considered a “sale” or “sharing” of personal information for targeted or cross-context behavioral advertising under some state privacy laws.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If it is necessary to transfer your information, we will ensure that your personal information is protected by appropriate safeguards as required by applicable data protection laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nayya
provenance_date: '2026-11-10'
provider_name: Nayya
provider_slug: nayya
slug: nayya-privacy-policy
source_date: '2026-11-10'
source_filename: nayya-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://legal.nayya.com/privacy-policies/privacy-policy-ea8d3103
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nayya\naid: nayya\nurl: https://legal.nayya.com/privacy-policies/privacy-policy-ea8d3103\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, date of birth, social security number, address, phone number\n- category: health\n  text: 'Health and healthcare information : medical conditions and activities, medical insurance-related information'\n- category: financial\n  text: 'Financial Information : compensation, soft credit information, mortgage and other loan debt, spending preferences'\n- category: location\n  text: 'Location\
  \ Information : We may derive a rough estimate of your location from your IP address.'\n- category: behavioral\n  text: 'Usage Information : Information about how you use our Service, such as the types of content that you view\n    or engage with'\n- category: device\n  text: 'Device Information : The manufacturer and model, operating system, browser type, IP address, and unique\n    identifiers of the device'\n- category: communication\n  text: 'Communication Information : We may collect information when you contact us with questions, feedback or\n    concerns'\npurposes:\n- purpose: Service and website delivery\n  text: provide, operate, maintain, and secure the Services and Website\n- purpose: Marketing and advertising\n  text: send you direct marketing communications, such as notifying you of special promotions, offers and events\n    via email and other means.\n- purpose: Service improvement\n  text: support, analyze, and improve the Services and Website and create new features\n\
  - purpose: Compliance and protection\n  text: comply with applicable laws, lawful requests, and legal process\n- purpose: Artificial intelligence\n  text: We use artificial intelligence and machine learning technologies to provide, operate, secure, and improve\n    the Services and Website\nretention:\n- scope: user information\n  period: null\n  text: We retain your information in line with our Data Management Policy.\nresidency:\n- region: United States\n  text: Your information is stored in the United States.\ntransfers:\n- mechanism: other\n  text: If it is necessary to transfer your information, we will ensure that your personal information is protected\n    by appropriate safeguards as required by applicable data protection laws.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Right to Delete request via privacynotices@nayya.com\n  text: You may have the right to request that we delete certain personal information\
  \ we have collected about you.\nrights:\n- right: Right to know\n  text: You may have the right to request what personal information we have collected, used, disclosed, and shared\n    about you in the preceding 12 months\n- right: Right to delete\n  text: You may have the right to request that we delete certain personal information we have collected about you.\n- right: Right to correct\n  text: You may have the right to request that we correct inaccurate personal information we have about you.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information for monetary consideration; however, our use of certain advertising\n    and analytics technologies described in Section 3.6 may be considered a “sale” or “sharing” of personal information\n    for targeted or cross-context behavioral advertising under some state privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/nayya/privacy/nayya-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Nayya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Employee Benefits
- Insurance
- Insurtech
- Health
- Decision Support
- Human Resources
- Enrollment
- Recommendations
- Artificial Intelligence
---
