---
api_specs:
- filename: wisepim-gtin-api-openapi.yml
  format: yaml
  label: WISEPIM Open Data API GTIN API
  slug: wisepim-gtin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wisepim/openapi/wisepim-gtin-api-openapi.yml
- filename: wisepim-hs-codes-api-openapi.yml
  format: yaml
  label: WISEPIM Open Data API HS codes API
  slug: wisepim-hs-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wisepim/openapi/wisepim-hs-codes-api-openapi.yml
- filename: wisepim-marketplace-fees-api-openapi.yml
  format: yaml
  label: WISEPIM Open Data API Marketplace fees API
  slug: wisepim-marketplace-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wisepim/openapi/wisepim-marketplace-fees-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data when you create an account: name, email, company name, industry, website, preferred language and your answers in onboarding'
  - category: behavioral
    text: 'Usage data when you visit the website or use the app: pages viewed, tools used, clicks, device and browser type, and approximate location from your IP address'
  - category: communication
    text: Your email address, language and the consent text you agreed to when you ask for a result by email, a rate alert, a guide or a report
  - category: device
    text: 'Technical data needed to run the service: IP address (hashed where we use it for rate limits), security and error logs'
  deletion:
    route: Self-service deletion in Settings under Data & Privacy, or by email
    text: Download your personal data and delete your account yourself in Settings under Data & Privacy (deletion becomes final after 14 days); you can also exercise any right by email to the address below
  dpa:
    available: true
    text: Data processing agreements available on request
    url: null
  purposes:
  - purpose: Providing account, app and free tools
    text: Providing your account, the app and the free tools you use
  - purpose: Newsletter and product updates
    text: Newsletter and product updates
  - purpose: Website and product analytics
    text: Website and product analytics, A/B tests, your tool profile and linking it to your account
  - purpose: Ad conversion measurement
    text: Ad conversion measurement
  - purpose: Security and abuse prevention
    text: Security and abuse prevention (bot checks, rate limits, error logs)
  residency:
  - region: European Union
    text: We host and store your account and product data in the European Union.
  retention:
  - period: As long as your account exists
    scope: Account data
    text: As long as your account exists. When you delete your account in Settings, you're signed out right away and have 14 days to cancel.
  - period: 24 months after your last activity
    scope: Email and free tool requests
    text: 24 months after your last activity, such as a new request or an unsubscribe.
  - period: 30 days
    scope: Unconfirmed alerts
    text: Unconfirmed alerts 30 days, then deleted
  - period: 7 years
    scope: Invoices
    text: Invoices 7 years, as Dutch tax law requires
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your data (the "right to be forgotten")
  - right: Portability
    text: Take your data with you (data portability)
  - right: Object
    text: Object to processing, including the profiling described under "Your tool profile"
  - right: Withdraw consent
    text: Withdraw consent at any time
  - right: Complain
    text: Complain to the Dutch Data Protection Authority (Autoriteit Persoonsgegevens)
  role:
    text: For the product data you upload to the app, we act as your processor; that is covered by the Data Processing Agreement below.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell personal data, and we never use your product or order data to train AI models
  subprocessors:
    text: 'We use these providers, each under a data processing agreement, and only for the purpose listed:'
    url: null
  transfers:
  - mechanism: adequacy
    text: Where a provider processes data outside the EU, the transfer relies on an adequacy decision (such as the EU-US Data Privacy Framework)
  - mechanism: SCC
    text: or the European Commission's standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WISEPIM Open Data API
provenance_date: '2026-11-10'
provider_name: WISEPIM Open Data API
provider_slug: wisepim
slug: wisepim-privacy-policy
source_date: '2026-11-10'
source_filename: wisepim-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://wisepim.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WISEPIM Open Data API\naid: wisepim\nurl: https://wisepim.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For the product data you upload to the app, we act as your processor; that is covered by the Data Processing\n    Agreement below.\ndata_categories:\n- category: identifying\n  text: 'Account data when you create an account: name, email, company name, industry, website, preferred language\n    and your answers in onboarding'\n- category: behavioral\n  text: 'Usage data when you visit the website or use the app: pages viewed, tools used, clicks, device and browser\n    type, and approximate\
  \ location from your IP address'\n- category: communication\n  text: Your email address, language and the consent text you agreed to when you ask for a result by email, a rate\n    alert, a guide or a report\n- category: device\n  text: 'Technical data needed to run the service: IP address (hashed where we use it for rate limits), security\n    and error logs'\npurposes:\n- purpose: Providing account, app and free tools\n  text: Providing your account, the app and the free tools you use\n- purpose: Newsletter and product updates\n  text: Newsletter and product updates\n- purpose: Website and product analytics\n  text: Website and product analytics, A/B tests, your tool profile and linking it to your account\n- purpose: Ad conversion measurement\n  text: Ad conversion measurement\n- purpose: Security and abuse prevention\n  text: Security and abuse prevention (bot checks, rate limits, error logs)\nretention:\n- scope: Account data\n  period: As long as your account exists\n  text: As long\
  \ as your account exists. When you delete your account in Settings, you're signed out right away and\n    have 14 days to cancel.\n- scope: Email and free tool requests\n  period: 24 months after your last activity\n  text: 24 months after your last activity, such as a new request or an unsubscribe.\n- scope: Unconfirmed alerts\n  period: 30 days\n  text: Unconfirmed alerts 30 days, then deleted\n- scope: Invoices\n  period: 7 years\n  text: Invoices 7 years, as Dutch tax law requires\nresidency:\n- region: European Union\n  text: We host and store your account and product data in the European Union.\ntransfers:\n- mechanism: adequacy\n  text: Where a provider processes data outside the EU, the transfer relies on an adequacy decision (such as the\n    EU-US Data Privacy Framework)\n- mechanism: SCC\n  text: or the European Commission's standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'We use these providers, each under a data processing agreement, and only for the purpose\
  \ listed:'\ndpa:\n  available: true\n  url: null\n  text: Data processing agreements available on request\ndeletion:\n  route: Self-service deletion in Settings under Data & Privacy, or by email\n  text: Download your personal data and delete your account yourself in Settings under Data & Privacy (deletion\n    becomes final after 14 days); you can also exercise any right by email to the address below\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your data (the \"right to be forgotten\")\n- right: Portability\n  text: Take your data with you (data portability)\n- right: Object\n  text: Object to processing, including the profiling described under \"Your tool profile\"\n- right: Withdraw consent\n  text: Withdraw consent at any time\n- right: Complain\n  text: Complain to the Dutch Data Protection Authority (Autoriteit Persoonsgegevens)\nsale_or_sharing:\n  stance: prohibited\n  text: We never\
  \ sell personal data, and we never use your product or order data to train AI models\n"
source_yaml_url: https://artifacts.apis.io/wisepim/privacy/wisepim-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from WISEPIM Open Data API's own page on 2026-11-10.
synthetic: false
tags:
- Product Information Management
- Artificial Intelligence
- E-Commerce
- Catalog Enrichment
- Translation
- Wholesale
- Retail
---
