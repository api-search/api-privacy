---
api_specs:
- filename: clickwise-net-account-api-openapi.yml
  format: yaml
  label: Clickwise Account API
  slug: clickwise-net-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-account-api-openapi.yml
- filename: clickwise-net-deals-api-openapi.yml
  format: yaml
  label: Clickwise Deals API
  slug: clickwise-net-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-deals-api-openapi.yml
- filename: clickwise-net-feeds-api-openapi.yml
  format: yaml
  label: Clickwise Feeds API
  slug: clickwise-net-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-feeds-api-openapi.yml
- filename: clickwise-net-links-api-openapi.yml
  format: yaml
  label: Clickwise Links API
  slug: clickwise-net-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-links-api-openapi.yml
- filename: clickwise-net-monetize-api-openapi.yml
  format: yaml
  label: Clickwise Monetize API
  slug: clickwise-net-monetize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-monetize-api-openapi.yml
- filename: clickwise-net-news-api-openapi.yml
  format: yaml
  label: Clickwise News API
  slug: clickwise-net-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-news-api-openapi.yml
- filename: clickwise-net-offers-api-openapi.yml
  format: yaml
  label: Clickwise Offers API
  slug: clickwise-net-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-offers-api-openapi.yml
- filename: clickwise-net-onboarding-api-openapi.yml
  format: yaml
  label: Clickwise Onboarding API
  slug: clickwise-net-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-onboarding-api-openapi.yml
- filename: clickwise-net-postbacks-api-openapi.yml
  format: yaml
  label: Clickwise Postbacks API
  slug: clickwise-net-postbacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-postbacks-api-openapi.yml
- filename: clickwise-net-products-api-openapi.yml
  format: yaml
  label: Clickwise Products API
  slug: clickwise-net-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-products-api-openapi.yml
- filename: clickwise-net-programs-api-openapi.yml
  format: yaml
  label: Clickwise Programs API
  slug: clickwise-net-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-programs-api-openapi.yml
- filename: clickwise-net-public-api-openapi.yml
  format: yaml
  label: Clickwise Public API
  slug: clickwise-net-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-public-api-openapi.yml
- filename: clickwise-net-reporting-api-openapi.yml
  format: yaml
  label: Clickwise Reporting API
  slug: clickwise-net-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-reporting-api-openapi.yml
- filename: clickwise-net-subscribers-api-openapi.yml
  format: yaml
  label: Clickwise Subscribers API
  slug: clickwise-net-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-subscribers-api-openapi.yml
- filename: clickwise-net-widgets-api-openapi.yml
  format: yaml
  label: Clickwise Widgets API
  slug: clickwise-net-widgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickwise-net/openapi/clickwise-net-widgets-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: username, first and last name, email address, and your password, which is stored as a salted hash rather than in clear text
  - category: financial
    text: 'the payment details you enter: PayPal ID and name, or bank name, account holder, bank country and address, IBAN or SWIFT code and account number'
  - category: location
    text: the country estimated from your IP address (section 3.7)
  - category: device
    text: your IP address, your user agent, the protocol version
  - category: communication
    text: Calls to our phone numbers and to the web call page, and messages to our WhatsApp number, are answered by an AI assistant, not by a person.
  - category: behavioral
    text: the screens viewed, as a route template without identifiers or URL parameters
  deletion:
    route: Email privacy@hello.clickwise.net
    text: To exercise these rights, contact privacy@hello.clickwise.net .
  dpa:
    available: null
    text: The provider-by-provider assessment of processor or independent-controller roles and the associated data processing agreements remains pending.
    url: null
  purposes:
  - purpose: Create and run accounts, sign-in and two-factor authentication
    text: Create and run accounts, sign-in and two-factor authentication
  - purpose: Evaluate onboarding applications, including automated evaluation
    text: Evaluate onboarding applications, including automated evaluation
  - purpose: Calculate, reconcile and pay commissions
    text: Calculate, reconcile and pay commissions, invoice merchants and keep commission, accounting and tax records
  - purpose: Security, fraud and invalid-traffic prevention
    text: Security, fraud and invalid-traffic prevention, rate limiting and troubleshooting
  - purpose: Outreach to prospective partners
    text: Outreach to prospective partners
  residency:
  - region: Google Cloud europe-west1 (Belgium)
    text: Our application servers, databases, cache and file storage are in Google Cloud's europe-west1 region (Belgium).
  - region: Google Cloud us-central1 (Iowa, United States)
    text: The voice-line and WhatsApp records in 3.8 are stored in Google Cloud's us-central1 region (Iowa, United States).
  retention:
  - period: 30 days
    scope: Server logs
    text: 'Server logs: 30 days.'
  - period: 400 days
    scope: Product events
    text: Product events are kept for 400 days, and technical events (API timings, errors and background tasks) for 90 days.
  - period: 30 days
    scope: Brainstorm transcripts
    text: 'Brainstorm with Clickwise transcripts (3.8): deleted 30 days after the call.'
  - period: up to seven years
    scope: Commission and tax records
    text: for SOFT DEV FZ LLC, up to seven years under UAE tax law
  - period: no automatic deletion schedule
    scope: Accounts, clicks, conversion reports, onboarding applications
    text: There is currently no automatic deletion schedule for accounts, affiliate clicks and conversion reports, commission records, MCP call records, onboarding applications, contact records or emails.
  rights:
  - right: access
    text: you may have the right to access your data, correct it, delete it, restrict or object to its processing
  - right: portability
    text: receive it in a portable format
  - right: withdraw consent
    text: withdraw consent where processing relies on consent
  - right: complain
    text: complain to a data protection authority
  - right: human review of automated decision
    text: You can request human review of an automated decision by writing to privacy@hello.clickwise.net .
  role:
    text: Clickwise is the controller for the processing described in this policy, except for the clicks and sales of a merchant's visitors, which Clickwise processes as that merchant's processor (section 3.3).
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For the clicks and sales we process as a merchant's processor, our merchant terms incorporate the EU Standard Contractual Clauses (controller to processor).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clickwise
provenance_date: '2026-11-09'
provider_name: Clickwise
provider_slug: clickwise-net
slug: clickwise-net-privacy-policy
source_date: '2026-11-09'
source_filename: clickwise-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://partners.clickwise.net/en/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clickwise\naid: clickwise-net\nurl: https://partners.clickwise.net/en/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Clickwise is the controller for the processing described in this policy, except for the clicks and sales\n    of a merchant's visitors, which Clickwise processes as that merchant's processor (section 3.3).\ndata_categories:\n- category: identifying\n  text: username, first and last name, email address, and your password, which is stored as a salted hash rather\n    than in clear text\n- category: financial\n  text: 'the payment details you enter: PayPal ID and name,\
  \ or bank name, account holder, bank country and address,\n    IBAN or SWIFT code and account number'\n- category: location\n  text: the country estimated from your IP address (section 3.7)\n- category: device\n  text: your IP address, your user agent, the protocol version\n- category: communication\n  text: Calls to our phone numbers and to the web call page, and messages to our WhatsApp number, are answered by\n    an AI assistant, not by a person.\n- category: behavioral\n  text: the screens viewed, as a route template without identifiers or URL parameters\npurposes:\n- purpose: Create and run accounts, sign-in and two-factor authentication\n  text: Create and run accounts, sign-in and two-factor authentication\n- purpose: Evaluate onboarding applications, including automated evaluation\n  text: Evaluate onboarding applications, including automated evaluation\n- purpose: Calculate, reconcile and pay commissions\n  text: Calculate, reconcile and pay commissions, invoice merchants and\
  \ keep commission, accounting and tax records\n- purpose: Security, fraud and invalid-traffic prevention\n  text: Security, fraud and invalid-traffic prevention, rate limiting and troubleshooting\n- purpose: Outreach to prospective partners\n  text: Outreach to prospective partners\nretention:\n- scope: Server logs\n  period: 30 days\n  text: 'Server logs: 30 days.'\n- scope: Product events\n  period: 400 days\n  text: Product events are kept for 400 days, and technical events (API timings, errors and background tasks) for\n    90 days.\n- scope: Brainstorm transcripts\n  period: 30 days\n  text: 'Brainstorm with Clickwise transcripts (3.8): deleted 30 days after the call.'\n- scope: Commission and tax records\n  period: up to seven years\n  text: for SOFT DEV FZ LLC, up to seven years under UAE tax law\n- scope: Accounts, clicks, conversion reports, onboarding applications\n  period: no automatic deletion schedule\n  text: There is currently no automatic deletion schedule for accounts,\
  \ affiliate clicks and conversion reports,\n    commission records, MCP call records, onboarding applications, contact records or emails.\nresidency:\n- region: Google Cloud europe-west1 (Belgium)\n  text: Our application servers, databases, cache and file storage are in Google Cloud's europe-west1 region (Belgium).\n- region: Google Cloud us-central1 (Iowa, United States)\n  text: The voice-line and WhatsApp records in 3.8 are stored in Google Cloud's us-central1 region (Iowa, United\n    States).\ntransfers:\n- mechanism: SCC\n  text: For the clicks and sales we process as a merchant's processor, our merchant terms incorporate the EU Standard\n    Contractual Clauses (controller to processor).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: The provider-by-provider assessment of processor or independent-controller roles and the associated data\n    processing agreements remains pending.\ndeletion:\n  route: Email privacy@hello.clickwise.net\n\
  \  text: To exercise these rights, contact privacy@hello.clickwise.net .\nrights:\n- right: access\n  text: you may have the right to access your data, correct it, delete it, restrict or object to its processing\n- right: portability\n  text: receive it in a portable format\n- right: withdraw consent\n  text: withdraw consent where processing relies on consent\n- right: complain\n  text: complain to a data protection authority\n- right: human review of automated decision\n  text: You can request human review of an automated decision by writing to privacy@hello.clickwise.net .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clickwise-net/privacy/clickwise-net-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 27 quoted statements, read from Clickwise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Affiliate Marketing
- Affiliate Network
- Performance Marketing
- tracked-links
- Publishers
- E-Commerce
- MCP
---
