---
api_specs:
- filename: hasdata-com-amazon-openapi-generated.yml
  format: yaml
  label: hasdata-com amazon API
  slug: amazon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-amazon-openapi-generated.yml
- filename: hasdata-com-core-openapi-generated.yml
  format: yaml
  label: hasdata-com core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-core-openapi-generated.yml
- filename: hasdata-com-tiktok-openapi-generated.yml
  format: yaml
  label: hasdata-com tiktok API
  slug: tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-tiktok-openapi-generated.yml
- filename: hasdata-com-walmart-openapi-generated.yml
  format: yaml
  label: hasdata-com walmart API
  slug: walmart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-walmart-openapi-generated.yml
- filename: hasdata-com-yelp-openapi-generated.yml
  format: yaml
  label: hasdata-com yelp API
  slug: yelp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-yelp-openapi-generated.yml
- filename: hasdata-com-youtube-openapi-generated.yml
  format: yaml
  label: hasdata-com youtube API
  slug: youtube-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-youtube-openapi-generated.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address — used for account login, transactional emails (welcome email, payment receipts), and product update emails with your consent
  - category: contact
    text: Email address — used for account login, transactional emails (welcome email, payment receipts), and product update emails with your consent
  - category: financial
    text: Payment information — processed by Stripe; we do not store your credit card details directly
  - category: location
    text: Geolocation data — derived from your IP address, used but not stored
  - category: device
    text: Usage data — collected via Google Analytics and Amplitude, including pages visited, session duration, referral source, device information, and product usage patterns
  - category: behavioral
    text: API usage data — request volume, endpoints used, credits used and remaining, error rates, response times, and details of your most recent API requests
  - category: professional
    text: This can include your name, job title, and public professional profile (such as LinkedIn), and your company’s industry, location, size, revenue, and funding.
  deletion:
    route: Email privacy@hasdata.com
    text: To exercise any of these rights, contact us at privacy@hasdata.com .
  dpa:
    available: true
    text: Enterprise customers who process personal data through HasData’s APIs and require a Data Processing Agreement for GDPR or other compliance purposes may request one by contacting privacy@hasdata.com .
    url: null
  purposes:
  - purpose: Account login
    text: To identify you when you log in to the Services
  - purpose: Process payments
    text: To process payments through Stripe
  - purpose: Monitor, debug and improve services
    text: To monitor, debug, and improve the Services
  - purpose: Review account activity for policy violations
    text: To review account activity, including recent requests, for potential violations of our Acceptable Use Policy
  - purpose: Legal compliance
    text: To comply with applicable laws and legal obligations
  retention:
  - period: 12 months after account deletion
    scope: Account data
    text: 'Account data (email, profile): For the duration of your account, plus 12 months after account deletion to support dispute resolution and legal obligations.'
  - period: 7 years
    scope: Payment records
    text: 'Payment records: 7 years from the date of transaction, as required for tax and accounting purposes.'
  - period: 90 days
    scope: Server logs (IP addresses)
    text: 'Server logs (IP addresses): 90 days from collection.'
  - period: 30 days
    scope: API response data, real-time APIs
    text: 'API response data — real-time APIs (copies of data returned by our APIs): 30 days from the date of the request.'
  - period: For the duration of your account
    scope: API response data, no-code scrapers
    text: 'API response data — no-code scrapers (copies of data returned by our no-code scraping tools): For the duration of your account.'
  rights:
  - right: Access
    text: Access — request a copy of the personal data we hold about you.
  - right: Rectification
    text: Rectification — request correction of inaccurate or incomplete personal data.
  - right: Erasure
    text: Erasure (“right to be forgotten”) — request deletion of your personal data, subject to legal retention obligations.
  - right: Restriction
    text: Restriction — request that we restrict processing of your personal data in certain circumstances.
  - right: Data portability
    text: Data portability — receive your personal data in a structured, commonly used, machine-readable format.
  - right: Object
    text: Object — object to processing based on legitimate interest, including profiling.
  - right: Withdraw consent
    text: Withdraw consent — withdraw consent for marketing emails at any time without affecting the lawfulness of processing based on consent before withdrawal.
  - right: Know
    text: Know — request disclosure of the categories and specific pieces of personal information we have collected about you.
  role:
    text: HasData acts as a data processor with respect to any personal data contained in API responses — you, the customer, are the data controller responsible for your use of that data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission
  - mechanism: adequacy
    text: Transfers to countries with an adequacy decision from the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: hasdata-com
provenance_date: '2026-11-09'
provider_name: hasdata-com
provider_slug: hasdata-com
slug: hasdata-com-privacy-policy
source_date: '2026-11-09'
source_filename: hasdata-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hasdata.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: hasdata-com\naid: hasdata-com\nurl: https://hasdata.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: HasData acts as a data processor with respect to any personal data contained in API responses — you, the\n    customer, are the data controller responsible for your use of that data.\ndata_categories:\n- category: identifying\n  text: Email address — used for account login, transactional emails (welcome email, payment receipts), and product\n    update emails with your consent\n- category: contact\n  text: Email address — used for account login, transactional emails (welcome email,\
  \ payment receipts), and product\n    update emails with your consent\n- category: financial\n  text: Payment information — processed by Stripe; we do not store your credit card details directly\n- category: location\n  text: Geolocation data — derived from your IP address, used but not stored\n- category: device\n  text: Usage data — collected via Google Analytics and Amplitude, including pages visited, session duration, referral\n    source, device information, and product usage patterns\n- category: behavioral\n  text: API usage data — request volume, endpoints used, credits used and remaining, error rates, response times,\n    and details of your most recent API requests\n- category: professional\n  text: This can include your name, job title, and public professional profile (such as LinkedIn), and your company’s\n    industry, location, size, revenue, and funding.\npurposes:\n- purpose: Account login\n  text: To identify you when you log in to the Services\n- purpose: Process payments\n\
  \  text: To process payments through Stripe\n- purpose: Monitor, debug and improve services\n  text: To monitor, debug, and improve the Services\n- purpose: Review account activity for policy violations\n  text: To review account activity, including recent requests, for potential violations of our Acceptable Use Policy\n- purpose: Legal compliance\n  text: To comply with applicable laws and legal obligations\nretention:\n- scope: Account data\n  period: 12 months after account deletion\n  text: 'Account data (email, profile): For the duration of your account, plus 12 months after account deletion\n    to support dispute resolution and legal obligations.'\n- scope: Payment records\n  period: 7 years\n  text: 'Payment records: 7 years from the date of transaction, as required for tax and accounting purposes.'\n- scope: Server logs (IP addresses)\n  period: 90 days\n  text: 'Server logs (IP addresses): 90 days from collection.'\n- scope: API response data, real-time APIs\n  period: 30 days\n\
  \  text: 'API response data — real-time APIs (copies of data returned by our APIs): 30 days from the date of the\n    request.'\n- scope: API response data, no-code scrapers\n  period: For the duration of your account\n  text: 'API response data — no-code scrapers (copies of data returned by our no-code scraping tools): For the duration\n    of your account.'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission\n- mechanism: adequacy\n  text: Transfers to countries with an adequacy decision from the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Enterprise customers who process personal data through HasData’s APIs and require a Data Processing Agreement\n    for GDPR or other compliance purposes may request one by contacting privacy@hasdata.com .\ndeletion:\n  route: Email privacy@hasdata.com\n  text: To exercise any of these rights, contact us at privacy@hasdata.com\
  \ .\nrights:\n- right: Access\n  text: Access — request a copy of the personal data we hold about you.\n- right: Rectification\n  text: Rectification — request correction of inaccurate or incomplete personal data.\n- right: Erasure\n  text: Erasure (“right to be forgotten”) — request deletion of your personal data, subject to legal retention obligations.\n- right: Restriction\n  text: Restriction — request that we restrict processing of your personal data in certain circumstances.\n- right: Data portability\n  text: Data portability — receive your personal data in a structured, commonly used, machine-readable format.\n- right: Object\n  text: Object — object to processing based on legitimate interest, including profiling.\n- right: Withdraw consent\n  text: Withdraw consent — withdraw consent for marketing emails at any time without affecting the lawfulness of\n    processing based on consent before withdrawal.\n- right: Know\n  text: Know — request disclosure of the categories and specific\
  \ pieces of personal information we have collected\n    about you.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/hasdata-com/privacy/hasdata-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from hasdata-com's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Data Pipeline
- Artificial Intelligence
- Automation
---
