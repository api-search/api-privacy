---
api_specs:
- filename: soldfetch-com-bulk-search-api-openapi.yml
  format: yaml
  label: soldfetch-com Bulk Search API
  slug: soldfetch-com-bulk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-bulk-search-api-openapi.yml
- filename: soldfetch-com-capabilities-api-openapi.yml
  format: yaml
  label: soldfetch-com Capabilities API
  slug: soldfetch-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-capabilities-api-openapi.yml
- filename: soldfetch-com-item-api-openapi.yml
  format: yaml
  label: soldfetch-com Item API
  slug: soldfetch-com-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-item-api-openapi.yml
- filename: soldfetch-com-public-api-openapi.yml
  format: yaml
  label: soldfetch-com Public API
  slug: soldfetch-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-public-api-openapi.yml
- filename: soldfetch-com-rapidapi-api-openapi.yml
  format: yaml
  label: soldfetch-com Rapidapi API
  slug: soldfetch-com-rapidapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-rapidapi-api-openapi.yml
- filename: soldfetch-com-requests-api-openapi.yml
  format: yaml
  label: soldfetch-com Requests API
  slug: soldfetch-com-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-requests-api-openapi.yml
- filename: soldfetch-com-scrape-api-openapi.yml
  format: yaml
  label: soldfetch-com Scrape API
  slug: soldfetch-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-scrape-api-openapi.yml
- filename: soldfetch-com-usage-api-openapi.yml
  format: yaml
  label: soldfetch-com Usage API
  slug: soldfetch-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soldfetch-com/openapi/soldfetch-com-usage-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and profile information — such as your name, email address, profile image, and authentication-provider identifiers.
  - category: financial
    text: Billing information — billing contact details, Stripe customer or subscription references, purchase amounts, and payment status.
  - category: device
    text: Device and browser information — browser type, operating system, language, and similar technical data.
  - category: location
    text: Network and security information — IP address, browser identifiers, authentication events, and abuse-prevention signals.
  - category: behavioral
    text: Product analytics — interactions with the site or dashboard, collected automatically.
  - category: communication
    text: Communications — information you include in support, feedback, sales, or other messages to us.
  deletion:
    route: Email contact@soldfetch.com to exercise a right; organization administrators can manage member access and certain account information in the dashboard.
    text: To exercise a right, email contact@soldfetch.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account management
    text: create and manage accounts, organizations, memberships, and sessions
  - purpose: Request processing
    text: process API requests and route them to appropriate upstream services
  - purpose: Billing
    text: process purchases and maintain billing and transaction records
  - purpose: Security and abuse prevention
    text: detect abuse, prevent fraud, investigate errors, and protect the Service
  - purpose: Analytics and improvement
    text: understand performance and improve reliability and product design
  retention:
  - period: 7, 30, or 90 days
    scope: API request logs
    text: Generally retained for 7, 30, or 90 days according to the applicable plan; a configured enterprise period may differ.
  - period: approximately one hour
    scope: Generated exports
    text: Configured to expire automatically after approximately one hour.
  - period: null
    scope: Account and organization data
    text: Retained while the account or organization is active, then deleted or de-identified subject to legal, security, and backup requirements.
  - period: null
    scope: Billing and transaction records
    text: Retained as required for tax, accounting, fraud prevention, dispute resolution, and other legal purposes.
  rights:
  - right: access, correction, deletion
    text: request access to, correction of, or deletion of your personal information
  - right: restriction or objection
    text: request restriction of processing or object to certain processing
  - right: portability
    text: receive certain information in a portable format
  - right: withdraw consent
    text: withdraw consent without affecting processing already completed on the basis of consent
  - right: appeal or complain
    text: appeal a decision about a privacy request or complain to a data-protection authority
  role:
    text: SoldFetch is the controller of personal information we collect directly for account administration, billing, security, product operations, analytics, and support.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: SoldFetch does not sell personal information or share it for cross-context behavioral advertising.
  subprocessors:
    text: 'Our principal categories of service providers include: Provider or category Purpose Information involved Supabase Authentication, database, and account infrastructure'
    url: null
  transfers:
  - mechanism: other
    text: Where applicable law requires transfer safeguards, we rely on an adequacy decision, approved contractual terms, or another recognized transfer mechanism, and we assess or supplement safeguards where required.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: soldfetch-com
provenance_date: '2026-11-10'
provider_name: soldfetch-com
provider_slug: soldfetch-com
slug: soldfetch-com-privacy-policy
source_date: '2026-11-10'
source_filename: soldfetch-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://soldfetch.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: soldfetch-com\naid: soldfetch-com\nurl: https://soldfetch.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: SoldFetch is the controller of personal information we collect directly for account administration, billing,\n    security, product operations, analytics, and support.\ndata_categories:\n- category: identifying\n  text: Account and profile information — such as your name, email address, profile image, and authentication-provider\n    identifiers.\n- category: financial\n  text: Billing information — billing contact details, Stripe customer or subscription references, purchase\
  \ amounts,\n    and payment status.\n- category: device\n  text: Device and browser information — browser type, operating system, language, and similar technical data.\n- category: location\n  text: Network and security information — IP address, browser identifiers, authentication events, and abuse-prevention\n    signals.\n- category: behavioral\n  text: Product analytics — interactions with the site or dashboard, collected automatically.\n- category: communication\n  text: Communications — information you include in support, feedback, sales, or other messages to us.\npurposes:\n- purpose: Account management\n  text: create and manage accounts, organizations, memberships, and sessions\n- purpose: Request processing\n  text: process API requests and route them to appropriate upstream services\n- purpose: Billing\n  text: process purchases and maintain billing and transaction records\n- purpose: Security and abuse prevention\n  text: detect abuse, prevent fraud, investigate errors, and\
  \ protect the Service\n- purpose: Analytics and improvement\n  text: understand performance and improve reliability and product design\nretention:\n- scope: API request logs\n  period: 7, 30, or 90 days\n  text: Generally retained for 7, 30, or 90 days according to the applicable plan; a configured enterprise period\n    may differ.\n- scope: Generated exports\n  period: approximately one hour\n  text: Configured to expire automatically after approximately one hour.\n- scope: Account and organization data\n  period: null\n  text: Retained while the account or organization is active, then deleted or de-identified subject to legal, security,\n    and backup requirements.\n- scope: Billing and transaction records\n  period: null\n  text: Retained as required for tax, accounting, fraud prevention, dispute resolution, and other legal purposes.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where applicable law requires transfer safeguards, we rely on an adequacy decision, approved\
  \ contractual\n    terms, or another recognized transfer mechanism, and we assess or supplement safeguards where required.\nsubprocessors:\n  url: null\n  text: 'Our principal categories of service providers include: Provider or category Purpose Information involved\n    Supabase Authentication, database, and account infrastructure'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@soldfetch.com to exercise a right; organization administrators can manage member access and\n    certain account information in the dashboard.\n  text: To exercise a right, email contact@soldfetch.com.\nrights:\n- right: access, correction, deletion\n  text: request access to, correction of, or deletion of your personal information\n- right: restriction or objection\n  text: request restriction of processing or object to certain processing\n- right: portability\n  text: receive certain information in a portable format\n- right: withdraw consent\n  text: withdraw consent without\
  \ affecting processing already completed on the basis of consent\n- right: appeal or complain\n  text: appeal a decision about a privacy request or complain to a data-protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: SoldFetch does not sell personal information or share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/soldfetch-com/privacy/soldfetch-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from soldfetch-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- eBay
- Listings
- Pricing
- Reseller
---
