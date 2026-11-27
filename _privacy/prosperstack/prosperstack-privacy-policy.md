---
api_specs:
- filename: prosperstack-customer-portal-api-openapi.yml
  format: yaml
  label: ProsperStack Customer Portal API
  slug: prosperstack-customer-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-customer-portal-api-openapi.yml
- filename: prosperstack-events-api-openapi.yml
  format: yaml
  label: ProsperStack Events API
  slug: prosperstack-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-events-api-openapi.yml
- filename: prosperstack-flow-sessions-api-openapi.yml
  format: yaml
  label: ProsperStack Flow Sessions API
  slug: prosperstack-flow-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-flow-sessions-api-openapi.yml
- filename: prosperstack-flows-api-openapi.yml
  format: yaml
  label: ProsperStack Flows API
  slug: prosperstack-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-flows-api-openapi.yml
- filename: prosperstack-offer-links-api-openapi.yml
  format: yaml
  label: ProsperStack Offer Links API
  slug: prosperstack-offer-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-offer-links-api-openapi.yml
- filename: prosperstack-offers-api-openapi.yml
  format: yaml
  label: ProsperStack Offers API
  slug: prosperstack-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-offers-api-openapi.yml
- filename: prosperstack-payments-api-openapi.yml
  format: yaml
  label: ProsperStack Payments API
  slug: prosperstack-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-payments-api-openapi.yml
- filename: prosperstack-properties-api-openapi.yml
  format: yaml
  label: ProsperStack Properties API
  slug: prosperstack-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-properties-api-openapi.yml
- filename: prosperstack-subscribers-api-openapi.yml
  format: yaml
  label: ProsperStack Subscribers API
  slug: prosperstack-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-subscribers-api-openapi.yml
- filename: prosperstack-subscriptions-api-openapi.yml
  format: yaml
  label: ProsperStack Subscriptions API
  slug: prosperstack-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-subscriptions-api-openapi.yml
- filename: prosperstack-webhooks-api-openapi.yml
  format: yaml
  label: ProsperStack Webhooks API
  slug: prosperstack-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prosperstack/openapi/prosperstack-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: we require individuals who sign up for a ProsperStack account to provide an email address and password
  - category: contact
    text: This will include your name, credit card, and contact information.
  - category: financial
    text: We keep a record of the purchases you’ve made.
  - category: location
    text: We may determine the approximate location of your device from your IP address.
  - category: behavioral
    text: we collect information about the actions that site administrators and users perform on a ProsperStack account, who did what and when
  - category: device
    text: unique device identifiers, language preference, referring site, the date and time of access, operating system, and mobile network information
  - category: communication
    text: we store a copy of our communications (including any call recordings as permitted by applicable law)
  - category: professional
    text: You may provide us with information like your name, contact information, resume or CV, and work authorization verification as part of the application process.
  deletion:
    route: account settings or contact us by email
    text: You can usually access, correct, or delete your personal data using your account settings and tools that we offer
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services
    text: To provide our Services. For example, to set up and maintain your account, provide customer service, process payments and orders, and verify user information.
  - purpose: marketing
    text: To market our Services and measure, gauge, and improve the effectiveness of our marketing.
  - purpose: security and fraud protection
    text: To protect our Services, our users, and the public.
  - purpose: improve services
    text: To ensure quality, maintain safety, and improve our Services.
  retention:
  - period: approximately 30 days
    scope: web server logs
    text: we keep the web server logs that record information about a visitor to one of ProsperStack's websites, like the visitor’s IP address, browser type, and operating system, for approximately 30 days.
  rights:
  - right: access
    text: Request access to your personal data;
  - right: correction or deletion
    text: Request correction or deletion of your personal data;
  - right: objection
    text: Object to our use and processing of your personal data;
  - right: restriction
    text: Request that we limit our use and processing of your personal data; and
  - right: portability
    text: Request portability of your personal data.
  - right: opt out of sale
    text: Opt out of any sale of personal information; and
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We have a long-standing policy that we do not sell our users' data.
  subprocessors:
    text: Sub-processors
    url: null
  transfers:
  - mechanism: DPF
    text: or ensuring they have signed up to the Data Privacy Framework (DPF) Program
  - mechanism: SCC
    text: In the case of US based entities, entering into European Commission approved standard contractual arrangements with them
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ProsperStack
provenance_date: '2026-11-10'
provider_name: ProsperStack
provider_slug: prosperstack
slug: prosperstack-privacy-policy
source_date: '2026-11-10'
source_filename: prosperstack-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://prosperstack.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ProsperStack\naid: prosperstack\nurl: https://prosperstack.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we require individuals who sign up for a ProsperStack account to provide an email address and password\n- category: contact\n  text: This will include your name, credit card, and contact information.\n- category: financial\n  text: We keep a record of the purchases you’ve made.\n- category: location\n  text: We may determine the approximate location of your device from your IP address.\n- category: behavioral\n\
  \  text: we collect information about the actions that site administrators and users perform on a ProsperStack account,\n    who did what and when\n- category: device\n  text: unique device identifiers, language preference, referring site, the date and time of access, operating system,\n    and mobile network information\n- category: communication\n  text: we store a copy of our communications (including any call recordings as permitted by applicable law)\n- category: professional\n  text: You may provide us with information like your name, contact information, resume or CV, and work authorization\n    verification as part of the application process.\npurposes:\n- purpose: provide services\n  text: To provide our Services. For example, to set up and maintain your account, provide customer service, process\n    payments and orders, and verify user information.\n- purpose: marketing\n  text: To market our Services and measure, gauge, and improve the effectiveness of our marketing.\n- purpose:\
  \ security and fraud protection\n  text: To protect our Services, our users, and the public.\n- purpose: improve services\n  text: To ensure quality, maintain safety, and improve our Services.\nretention:\n- scope: web server logs\n  period: approximately 30 days\n  text: we keep the web server logs that record information about a visitor to one of ProsperStack's websites, like\n    the visitor’s IP address, browser type, and operating system, for approximately 30 days.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: or ensuring they have signed up to the Data Privacy Framework (DPF) Program\n- mechanism: SCC\n  text: In the case of US based entities, entering into European Commission approved standard contractual arrangements\n    with them\nsubprocessors:\n  url: null\n  text: Sub-processors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings or contact us by email\n  text: You can usually access, correct, or delete your personal data using\
  \ your account settings and tools that\n    we offer\nrights:\n- right: access\n  text: Request access to your personal data;\n- right: correction or deletion\n  text: Request correction or deletion of your personal data;\n- right: objection\n  text: Object to our use and processing of your personal data;\n- right: restriction\n  text: Request that we limit our use and processing of your personal data; and\n- right: portability\n  text: Request portability of your personal data.\n- right: opt out of sale\n  text: Opt out of any sale of personal information; and\nsale_or_sharing:\n  stance: prohibited\n  text: We have a long-standing policy that we do not sell our users' data.\n"
source_yaml_url: https://artifacts.apis.io/prosperstack/privacy/prosperstack-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ProsperStack's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retention
- Subscription
- Analytics
- Software-as-a-Service
---
