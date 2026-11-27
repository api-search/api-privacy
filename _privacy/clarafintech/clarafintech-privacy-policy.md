---
api_specs:
- filename: clarafintech-accounts-payable-api-openapi.yml
  format: yaml
  label: Clarafintech Accounts Payable API
  slug: clarafintech-accounts-payable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-accounts-payable-api-openapi.yml
- filename: clarafintech-authentication-api-openapi.yml
  format: yaml
  label: Clarafintech Authentication API
  slug: clarafintech-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-authentication-api-openapi.yml
- filename: clarafintech-billing-statements-api-openapi.yml
  format: yaml
  label: Clarafintech Billing Statements API
  slug: clarafintech-billing-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-billing-statements-api-openapi.yml
- filename: clarafintech-cards-api-openapi.yml
  format: yaml
  label: Clarafintech Cards API
  slug: clarafintech-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-cards-api-openapi.yml
- filename: clarafintech-digital-account-api-openapi.yml
  format: yaml
  label: Clarafintech Digital Account API
  slug: clarafintech-digital-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-digital-account-api-openapi.yml
- filename: clarafintech-extracted-documents-api-openapi.yml
  format: yaml
  label: Clarafintech Extracted Documents API
  slug: clarafintech-extracted-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-extracted-documents-api-openapi.yml
- filename: clarafintech-invoices-api-openapi.yml
  format: yaml
  label: Clarafintech Invoices API
  slug: clarafintech-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-invoices-api-openapi.yml
- filename: clarafintech-reimbursements-api-openapi.yml
  format: yaml
  label: Clarafintech Reimbursements API
  slug: clarafintech-reimbursements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-reimbursements-api-openapi.yml
- filename: clarafintech-transactions-api-openapi.yml
  format: yaml
  label: Clarafintech Transactions API
  slug: clarafintech-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-transactions-api-openapi.yml
- filename: clarafintech-users-api-openapi.yml
  format: yaml
  label: Clarafintech Users API
  slug: clarafintech-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clarafintech/openapi/clarafintech-users-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name Number and details of valid official identification Address Business and/or personal email Phone number
  - category: financial
    text: Financial Data Information provided by credit information institutions Bank account statements provided by the applicant Financial statements Account numbers at financial institutions
  - category: biometric
    text: Biometric Data (see Section I) Measurable physical, physiological or behavioral properties or personality traits attributable to a single person, such as fingerprints or facial photographs
  - category: location
    text: We collect geolocation data from the device from which you access our services, in order to comply with current regulatory provisions
  - category: behavioral
    text: We may collect information about your interactions with our services, including the pages you visit and the actions you take
  - category: device
    text: 'Mobile device identifiers: tags that make it possible to identify mobile devices'
  deletion:
    route: ARCO rights request via arco@clara.team
    text: to have it deleted from our records or databases when you consider that it is not being used properly (Cancellation)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Marketing or advertising
    text: Marketing or advertising
  - purpose: Training AI and algorithms
    text: Using the information to develop, train, validate, improve and commercialize algorithms, analytical models, automation tools, artificial intelligence systems, technology products and financial solutions developed by Clara or by third parties with whom Clara maintains commercial relationships
  - purpose: Sharing aggregated information with third parties
    text: Sharing, licensing, commercializing, transferring or making available to third parties aggregated, anonymized, statistical or de-identified information derived from the use of Clara’s services
  rights:
  - right: Access
    text: You have the right to know what personal data we hold about you, what we use it for and the conditions of its use (Access).
  - right: Rectification
    text: You also have the right to request the correction of your personal information if it is outdated, inaccurate or incomplete (Rectification)
  - right: Cancellation
    text: to have it deleted from our records or databases when you consider that it is not being used properly (Cancellation)
  - right: Opposition
    text: to object to the use of your personal data for specific purposes (Opposition)
  - right: Revoke consent
    text: You may revoke any consent you have given us for the processing of your personal data.
  role:
    text: is the party responsible for the processing, use and protection of the personal data of individuals
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Clara may share with domestic or international third parties statistical, anonymized, aggregated or de-identified information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clarafintech
provenance_date: '2026-11-09'
provider_name: Clarafintech
provider_slug: clarafintech
slug: clarafintech-privacy-policy
source_date: '2026-11-09'
source_filename: clarafintech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clara.com/global/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clarafintech\naid: clarafintech\nurl: https://www.clara.com/global/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: is the party responsible for the processing, use and protection of the personal data of individuals\ndata_categories:\n- category: identifying\n  text: Name Number and details of valid official identification Address Business and/or personal email Phone number\n- category: financial\n  text: Financial Data Information provided by credit information institutions Bank account statements provided\n    by the applicant Financial statements Account numbers at financial institutions\n\
  - category: biometric\n  text: Biometric Data (see Section I) Measurable physical, physiological or behavioral properties or personality\n    traits attributable to a single person, such as fingerprints or facial photographs\n- category: location\n  text: We collect geolocation data from the device from which you access our services, in order to comply with\n    current regulatory provisions\n- category: behavioral\n  text: We may collect information about your interactions with our services, including the pages you visit and\n    the actions you take\n- category: device\n  text: 'Mobile device identifiers: tags that make it possible to identify mobile devices'\npurposes:\n- purpose: Marketing or advertising\n  text: Marketing or advertising\n- purpose: Training AI and algorithms\n  text: Using the information to develop, train, validate, improve and commercialize algorithms, analytical models,\n    automation tools, artificial intelligence systems, technology products and financial solutions\
  \ developed by\n    Clara or by third parties with whom Clara maintains commercial relationships\n- purpose: Sharing aggregated information with third parties\n  text: Sharing, licensing, commercializing, transferring or making available to third parties aggregated, anonymized,\n    statistical or de-identified information derived from the use of Clara’s services\nretention: []\nresidency: []\ntransfers:\n- mechanism: other\n  text: Clara may share with domestic or international third parties statistical, anonymized, aggregated or de-identified\n    information\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: ARCO rights request via arco@clara.team\n  text: to have it deleted from our records or databases when you consider that it is not being used properly (Cancellation)\nrights:\n- right: Access\n  text: You have the right to know what personal data we hold about you, what we use it for and the conditions of\n    its\
  \ use (Access).\n- right: Rectification\n  text: You also have the right to request the correction of your personal information if it is outdated, inaccurate\n    or incomplete (Rectification)\n- right: Cancellation\n  text: to have it deleted from our records or databases when you consider that it is not being used properly (Cancellation)\n- right: Opposition\n  text: to object to the use of your personal data for specific purposes (Opposition)\n- right: Revoke consent\n  text: You may revoke any consent you have given us for the processing of your personal data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clarafintech/privacy/clarafintech-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from Clarafintech's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Spend Management
- Latin America
- Corporate Cards
- Financial Automation
- Company
---
