---
api_specs:
- filename: assertible-triggers-api-openapi.yml
  format: yaml
  label: Assertible API
  slug: assertible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assertible/openapi/assertible-triggers-api-openapi.yml
- filename: assertible-deployments-api-openapi.yml
  format: yaml
  label: Assertible Deployments API
  slug: assertible-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assertible/openapi/assertible-deployments-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register with the site, you will be asked to provide certain personal information, including your name and email address.
  - category: device
    text: We will also capture login timestamps, and usage statistics, as well as IP addresses.
  - category: behavioral
    text: We use session and login cookies, which help us keep track of when a person is logged in and determine the content or sites users link to, and which services people use.
  deletion:
    route: Email admin@assertible.com to cancel your account
    text: If you would like to cease all communications from us, please send an email to admin@assertible.com and we will cancel your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision and monitoring
    text: except as necessary to provide the services offered, to monitor usage, and to improve the service
  - purpose: analytics
    text: we may use a third party analytics tool like Kissmetrics to learn how you are using Assertible
  - purpose: notifications and support
    text: We also use your personal information to send you notifications about the service and to respond to customer support requests.
  - purpose: aggregate statistical analysis
    text: We will also aggregate user information and perform statistical analyses of the collective behavior of our members and visitors
  rights:
  - right: access and change
    text: You can access and change your personal information or cancel your account by logging in to your account settings page.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never share your personal information with advertisers or send you promotions for unrelated services.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Assertible
provenance_date: '2026-11-09'
provider_name: Assertible
provider_slug: assertible
slug: assertible-privacy-policy
source_date: '2026-11-09'
source_filename: assertible-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://assertible.com/privacypolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Assertible\naid: assertible\nurl: https://assertible.com/privacypolicy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you register with the site, you will be asked to provide certain personal information, including your\n    name and email address.\n- category: device\n  text: We will also capture login timestamps, and usage statistics, as well as IP addresses.\n- category: behavioral\n  text: We use session and login cookies, which help us keep track of when a person is logged in and determine the\n    content or sites users link\
  \ to, and which services people use.\npurposes:\n- purpose: service provision and monitoring\n  text: except as necessary to provide the services offered, to monitor usage, and to improve the service\n- purpose: analytics\n  text: we may use a third party analytics tool like Kissmetrics to learn how you are using Assertible\n- purpose: notifications and support\n  text: We also use your personal information to send you notifications about the service and to respond to customer\n    support requests.\n- purpose: aggregate statistical analysis\n  text: We will also aggregate user information and perform statistical analyses of the collective behavior of our\n    members and visitors\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email admin@assertible.com to cancel your account\n  text: If you would like to cease all communications from us, please send an email to admin@assertible.com\
  \ and\n    we will cancel your account.\nrights:\n- right: access and change\n  text: You can access and change your personal information or cancel your account by logging in to your account\n    settings page.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never share your personal information with advertisers or send you promotions for unrelated services.\n"
source_yaml_url: https://artifacts.apis.io/assertible/privacy/assertible-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Assertible's own page on 2026-11-09.
synthetic: false
tags:
- API Testing
- Monitoring
- Quality Assurance
- Testing
- CI/CD
- Developer Tools
---
