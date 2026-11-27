---
api_specs:
- filename: knit-departments-api-openapi.yml
  format: yaml
  label: Knit Departments API
  slug: knit-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knit/openapi/knit-departments-api-openapi.yml
- filename: knit-employees-api-openapi.yml
  format: yaml
  label: Knit Employees API
  slug: knit-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knit/openapi/knit-employees-api-openapi.yml
- filename: knit-integrations-api-openapi.yml
  format: yaml
  label: Knit Integrations API
  slug: knit-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knit/openapi/knit-integrations-api-openapi.yml
- filename: knit-jobs-api-openapi.yml
  format: yaml
  label: Knit Jobs API
  slug: knit-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knit/openapi/knit-jobs-api-openapi.yml
- filename: knit-locations-api-openapi.yml
  format: yaml
  label: Knit Locations API
  slug: knit-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knit/openapi/knit-locations-api-openapi.yml
- filename: knit-syncs-api-openapi.yml
  format: yaml
  label: Knit Syncs API
  slug: knit-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knit/openapi/knit-syncs-api-openapi.yml
- filename: knit-time-off-api-openapi.yml
  format: yaml
  label: Knit Time Off API
  slug: knit-time-off-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knit/openapi/knit-time-off-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Your contact information (such as name, address, email address and phone number);
  - category: identifying
    text: Personal information contained in legal agreements (such as invoices and orders);
  - category: device
    text: IP address, browser type and other information relating to the device through which they access the Services
  - category: behavioral
    text: to track user activity and collect site data
  - category: communication
    text: Any other Personal Information you submit to us in the form of an email or via any function within the Services
  - category: professional
    text: If you apply for a job with us through a third-party platform (such as Glassdoor or LinkedIn), we will collect certain Personal Information you make available to us through such third-party platform;
  deletion:
    route: Email the support team of the application or the DPO at kunal@getknit.dev
    text: You can request the deletion of any data stored on our servers by contacting the support team of the application you are using or by contacting our DPO, Kunal Swaroop Mishra, at kunal@getknit.dev directly.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Services
    text: To provide the Services;
  - purpose: Marketing communications
    text: To provide you with information about our products and services that we believe you may find of interest, including to send you mailing lists, and marketing and promotional e-mails;
  - purpose: Google data functionality
    text: The Google user data we access is used solely to enable the functionality of the third-party application you have authorized.
  - purpose: Improve the Services
    text: To improve the Services and offerings or services provided by us and to better understand how users access and use the Services and offerings provided by us.
  residency:
  - region: India
    text: If you are accessing the Services from outside India, by providing your information to the Services, you are consenting to and authorizing the transfer of your information to India for storage, use, processing, maintenance and onward transfer of such information to other entities, regardless of their location
  retention:
  - period: null
    scope: Google user data
    text: We retain your Google user data only for as long as it is necessary to provide our API services to the application you have authorized.
  - period: 30 days
    scope: Google user data deletion on request
    text: Upon receiving a deletion request, we will permanently remove all of your Google user data from our systems within a specified period, such as 30 days.
  rights:
  - right: Access
    text: 'Right of access: You have a right to access the personal data you have provided by requesting us to provide you with the same.'
  - right: Rectification
    text: 'Right to rectification: You have a right to request us to amend or update your personal data if it is inaccurate or incomplete.'
  - right: Erasure
    text: 'Right to erasure: You have a right to request us to delete your personal data.'
  - right: Restrict processing
    text: 'Right to restrict: You have a right to request us to temporarily or permanently stop processing all or some of your personal data.'
  - right: Object
    text: 'Right to object: You have a right, at any time, to object to our processing of your personal data under certain circumstances.'
  - right: Data portability
    text: 'Right to data portability: You have a right to request us to provide you with a copy of your personal data in electronic format'
  - right: Not subject to automated decision-making
    text: 'Right not to be subject to automated decision-making: You have a right to not be subject to a decision based solely on automated decision making, including profiling.'
  role:
    text: Knit processes data on behalf of our developer clients.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell your Personal Information, but we may allow our advertising partners to collect certain device identifiers and electronic network activity that allows them to show ads within their systems that are targeted to your interests.
  subprocessors:
    text: We may use third-party service providers (sub-processors) for our own infrastructure, such as cloud hosting.
    url: null
  transfers:
  - mechanism: SCC
    text: such as the Standard Contractual Clauses approved by the EU Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Knit
provenance_date: '2026-11-09'
provider_name: Knit
provider_slug: knit
slug: knit-privacy-policy
source_date: '2026-11-09'
source_filename: knit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://getknit.dev/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Knit\naid: knit\nurl: https://getknit.dev/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Knit processes data on behalf of our developer clients.\ndata_categories:\n- category: contact\n  text: Your contact information (such as name, address, email address and phone number);\n- category: identifying\n  text: Personal information contained in legal agreements (such as invoices and orders);\n- category: device\n  text: IP address, browser type and other information relating to the device through which they access the Services\n- category: behavioral\n  text: to track user activity and\
  \ collect site data\n- category: communication\n  text: Any other Personal Information you submit to us in the form of an email or via any function within the Services\n- category: professional\n  text: If you apply for a job with us through a third-party platform (such as Glassdoor or LinkedIn), we will collect\n    certain Personal Information you make available to us through such third-party platform;\npurposes:\n- purpose: Provide the Services\n  text: To provide the Services;\n- purpose: Marketing communications\n  text: To provide you with information about our products and services that we believe you may find of interest,\n    including to send you mailing lists, and marketing and promotional e-mails;\n- purpose: Google data functionality\n  text: The Google user data we access is used solely to enable the functionality of the third-party application\n    you have authorized.\n- purpose: Improve the Services\n  text: To improve the Services and offerings or services provided by\
  \ us and to better understand how users access\n    and use the Services and offerings provided by us.\nretention:\n- scope: Google user data\n  period: null\n  text: We retain your Google user data only for as long as it is necessary to provide our API services to the application\n    you have authorized.\n- scope: Google user data deletion on request\n  period: 30 days\n  text: Upon receiving a deletion request, we will permanently remove all of your Google user data from our systems\n    within a specified period, such as 30 days.\nresidency:\n- region: India\n  text: If you are accessing the Services from outside India, by providing your information to the Services, you\n    are consenting to and authorizing the transfer of your information to India for storage, use, processing, maintenance\n    and onward transfer of such information to other entities, regardless of their location\ntransfers:\n- mechanism: SCC\n  text: such as the Standard Contractual Clauses approved by the EU Commission.\n\
  subprocessors:\n  url: null\n  text: We may use third-party service providers (sub-processors) for our own infrastructure, such as cloud hosting.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the support team of the application or the DPO at kunal@getknit.dev\n  text: You can request the deletion of any data stored on our servers by contacting the support team of the application\n    you are using or by contacting our DPO, Kunal Swaroop Mishra, at kunal@getknit.dev directly.\nrights:\n- right: Access\n  text: 'Right of access: You have a right to access the personal data you have provided by requesting us to provide\n    you with the same.'\n- right: Rectification\n  text: 'Right to rectification: You have a right to request us to amend or update your personal data if it is inaccurate\n    or incomplete.'\n- right: Erasure\n  text: 'Right to erasure: You have a right to request us to delete your personal data.'\n- right: Restrict processing\n  text: 'Right\
  \ to restrict: You have a right to request us to temporarily or permanently stop processing all or\n    some of your personal data.'\n- right: Object\n  text: 'Right to object: You have a right, at any time, to object to our processing of your personal data under\n    certain circumstances.'\n- right: Data portability\n  text: 'Right to data portability: You have a right to request us to provide you with a copy of your personal data\n    in electronic format'\n- right: Not subject to automated decision-making\n  text: 'Right not to be subject to automated decision-making: You have a right to not be subject to a decision\n    based solely on automated decision making, including profiling.'\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your Personal Information, but we may allow our advertising partners to collect certain device\n    identifiers and electronic network activity that allows them to show ads within their systems that are targeted\n    to your interests.\n"
source_yaml_url: https://artifacts.apis.io/knit/privacy/knit-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Knit's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- HR Integrations
- HRIS
- Unified API
- Integration Platform
- API Management
- iPaaS
- Automation
- SaaS Integration
- AI Agents
---
