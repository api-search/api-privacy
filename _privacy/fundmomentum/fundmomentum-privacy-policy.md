---
api_specs:
- filename: fundmomentum-api-api-openapi.yml
  format: yaml
  label: Fund Momentum API
  slug: fundmomentum-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundmomentum/openapi/fundmomentum-api-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register for an account, we collect your name and email address.
  - category: financial
    text: 'Payment Information: When you subscribe to our paid plans, your payment information is collected and processed directly by our payment processor, Stripe.'
  - category: behavioral
    text: We collect information about your interactions with the Service, such as your search queries (country, funding stage, industry focus) and funds you save to your favorites.
  - category: device
    text: we store a salted hash of the IP address, a hash of the IP address combined with the client identifier, the first 200 characters of the user-agent string, the country derived from the IP address, and daily call counts.
  - category: location
    text: Records page views, session duration, approximate location (country/city derived from a truncated IP address, which Google does not store), device and browser type, traffic sources
  deletion:
    route: Account deletion from profile settings, or request by email to michael@fundmomentum.vc
    text: You can also manage your account information and delete your account from your profile settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate and maintain service
    text: Provide, operate, and maintain our Service.
  - purpose: Improve and personalize service
    text: Improve, personalize, and expand our Service.
  - purpose: Communication
    text: Communicate with you, including for customer service and to send you updates about the Service.
  - purpose: Analytics
    text: Monitor and analyze usage and trends via Google Analytics to improve your experience.
  - purpose: Fraud prevention
    text: Prevent fraudulent activity.
  - purpose: API authentication and rate limiting
    text: Authenticate and rate-limit MCP API access
  - purpose: AI-powered startup matching
    text: Process AI-powered startup matching via third-party AI providers (Anthropic)
  retention:
  - period: 30 days
    scope: Account data
    text: When you delete your account, we will delete or anonymize your personal information within 30 days, except where we are required to retain certain information by law.
  - period: 90 days
    scope: MCP keyless address hashes and client data
    text: The address hashes, client strings and country are deleted after 90 days.
  - period: 14 months
    scope: Google Analytics 4 user-level data
    text: Retention of user-level data in GA4 is set to 14 months.
  - period: 16 months
    scope: Google Search Console query data
    text: Query data is retained by Google for 16 months in aggregated form.
  rights:
  - right: Access, update or delete
    text: The right to access, update, or delete the information we have on you.
  - right: Object to processing
    text: The right to object to our processing of your personal data.
  - right: Data portability
    text: The right to data portability.
  - right: Withdraw consent to analytics cookies
    text: The right to withdraw consent to analytics cookies at any time.
  - right: Lodge a complaint
    text: you have the right to lodge a complaint with a supervisory authority.
  role:
    text: 'The controller responsible for the processing of personal data on fundmomentum.vc within the meaning of Art. 4(7) GDPR is: Michael Wolfgang Schneider , sole proprietor, trading as Fund Momentum'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Google LLC is certified under the EU-US Data Privacy Framework; where that does not apply, Standard Contractual Clauses are in place.
  - mechanism: SCC
    text: including using Standard Contractual Clauses approved by the European Commission when necessary
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fund Momentum
provenance_date: '2026-11-09'
provider_name: Fund Momentum
provider_slug: fundmomentum
slug: fundmomentum-privacy-policy
source_date: '2026-11-09'
source_filename: fundmomentum-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fundmomentum.vc/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fund Momentum\naid: fundmomentum\nurl: https://fundmomentum.vc/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller responsible for the processing of personal data on fundmomentum.vc within the meaning of\n    Art. 4(7) GDPR is: Michael Wolfgang Schneider , sole proprietor, trading as Fund Momentum'\ndata_categories:\n- category: identifying\n  text: When you register for an account, we collect your name and email address.\n- category: financial\n  text: 'Payment Information: When you subscribe to our paid plans, your payment information is collected and processed\n    directly\
  \ by our payment processor, Stripe.'\n- category: behavioral\n  text: We collect information about your interactions with the Service, such as your search queries (country, funding\n    stage, industry focus) and funds you save to your favorites.\n- category: device\n  text: we store a salted hash of the IP address, a hash of the IP address combined with the client identifier,\n    the first 200 characters of the user-agent string, the country derived from the IP address, and daily call counts.\n- category: location\n  text: Records page views, session duration, approximate location (country/city derived from a truncated IP address,\n    which Google does not store), device and browser type, traffic sources\npurposes:\n- purpose: Provide, operate and maintain service\n  text: Provide, operate, and maintain our Service.\n- purpose: Improve and personalize service\n  text: Improve, personalize, and expand our Service.\n- purpose: Communication\n  text: Communicate with you, including for\
  \ customer service and to send you updates about the Service.\n- purpose: Analytics\n  text: Monitor and analyze usage and trends via Google Analytics to improve your experience.\n- purpose: Fraud prevention\n  text: Prevent fraudulent activity.\n- purpose: API authentication and rate limiting\n  text: Authenticate and rate-limit MCP API access\n- purpose: AI-powered startup matching\n  text: Process AI-powered startup matching via third-party AI providers (Anthropic)\nretention:\n- scope: Account data\n  period: 30 days\n  text: When you delete your account, we will delete or anonymize your personal information within 30 days, except\n    where we are required to retain certain information by law.\n- scope: MCP keyless address hashes and client data\n  period: 90 days\n  text: The address hashes, client strings and country are deleted after 90 days.\n- scope: Google Analytics 4 user-level data\n  period: 14 months\n  text: Retention of user-level data in GA4 is set to 14 months.\n- scope:\
  \ Google Search Console query data\n  period: 16 months\n  text: Query data is retained by Google for 16 months in aggregated form.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Google LLC is certified under the EU-US Data Privacy Framework; where that does not apply, Standard Contractual\n    Clauses are in place.\n- mechanism: SCC\n  text: including using Standard Contractual Clauses approved by the European Commission when necessary\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion from profile settings, or request by email to michael@fundmomentum.vc\n  text: You can also manage your account information and delete your account from your profile settings.\nrights:\n- right: Access, update or delete\n  text: The right to access, update, or delete the information we have on you.\n- right: Object to processing\n  text: The right to object to our processing of your personal data.\n- right: Data portability\n\
  \  text: The right to data portability.\n- right: Withdraw consent to analytics cookies\n  text: The right to withdraw consent to analytics cookies at any time.\n- right: Lodge a complaint\n  text: you have the right to lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/fundmomentum/privacy/fundmomentum-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Fund Momentum's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fundraising
- Venture Capital
- Data Intelligence
- AI Agents
---
