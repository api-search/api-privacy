---
api_specs:
- filename: converly-io-action-types-api-openapi.yml
  format: yaml
  label: Converly Action Types API
  slug: converly-io-action-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-action-types-api-openapi.yml
- filename: converly-io-billing-api-openapi.yml
  format: yaml
  label: Converly Billing API
  slug: converly-io-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-billing-api-openapi.yml
- filename: converly-io-destination-types-api-openapi.yml
  format: yaml
  label: Converly Destination Types API
  slug: converly-io-destination-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-destination-types-api-openapi.yml
- filename: converly-io-destinations-api-openapi.yml
  format: yaml
  label: Converly Destinations API
  slug: converly-io-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-destinations-api-openapi.yml
- filename: converly-io-events-api-openapi.yml
  format: yaml
  label: Converly Events API
  slug: converly-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-events-api-openapi.yml
- filename: converly-io-flows-api-openapi.yml
  format: yaml
  label: Converly Flows API
  slug: converly-io-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-flows-api-openapi.yml
- filename: converly-io-handoffs-api-openapi.yml
  format: yaml
  label: Converly Handoffs API
  slug: converly-io-handoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-handoffs-api-openapi.yml
- filename: converly-io-invoices-api-openapi.yml
  format: yaml
  label: Converly Invoices API
  slug: converly-io-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-invoices-api-openapi.yml
- filename: converly-io-plans-api-openapi.yml
  format: yaml
  label: Converly Plans API
  slug: converly-io-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-plans-api-openapi.yml
- filename: converly-io-signup-api-openapi.yml
  format: yaml
  label: Converly Signup API
  slug: converly-io-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-signup-api-openapi.yml
- filename: converly-io-site-integrations-api-openapi.yml
  format: yaml
  label: Converly Site Integrations API
  slug: converly-io-site-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-site-integrations-api-openapi.yml
- filename: converly-io-sites-api-openapi.yml
  format: yaml
  label: Converly Sites API
  slug: converly-io-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-sites-api-openapi.yml
- filename: converly-io-subscription-api-openapi.yml
  format: yaml
  label: Converly Subscription API
  slug: converly-io-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-subscription-api-openapi.yml
- filename: converly-io-test-event-api-openapi.yml
  format: yaml
  label: Converly Test Event API
  slug: converly-io-test-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-test-event-api-openapi.yml
- filename: converly-io-trigger-types-api-openapi.yml
  format: yaml
  label: Converly Trigger Types API
  slug: converly-io-trigger-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-trigger-types-api-openapi.yml
- filename: converly-io-usage-api-openapi.yml
  format: yaml
  label: Converly Usage API
  slug: converly-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converly-io/openapi/converly-io-usage-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Personal information submitted in the form: email address, phone number, first name, last name, and any other fields the website operator chooses to capture'
  - category: identifying
    text: Name and email address (for account creation and product communications)
  - category: financial
    text: Billing information (processed by Stripe — Converly does not store full card numbers; we receive only the last four digits and card brand)
  - category: device
    text: The visitor’s IP address and browser user agent
  - category: behavioral
    text: The URL of the page where the form was submitted, and the URL of the page that referred the visitor there
  - category: communication
    text: Advertising cookies set by the visitor’s browser (e.g. Facebook’s _fbp and _fbc cookies)
  deletion:
    route: Email privacy@converly.io or close account from dashboard
    text: Customers can request earlier deletion of any of their data at any time by emailing privacy@converly.io or by closing their account from within the dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Converly service
    text: 'Provide the Converly service: track conversions, display the dashboard, and forward conversion events to the advertising and analytics platforms the customer has connected'
  - purpose: Authenticate and secure
    text: Authenticate customers and secure the service
  - purpose: Billing
    text: Bill customers (via Stripe)
  - purpose: Transactional email
    text: Send transactional emails (account notifications, billing receipts, password resets)
  - purpose: Diagnostics and abuse
    text: Diagnose technical issues and investigate abuse
  residency:
  - region: United States
    text: Our infrastructure subprocessors that store or process conversion data are located in the United States (see Section 4.2).
  retention:
  - period: 7 days
    scope: Plaintext personal information from form submissions
    text: Plaintext personal information (email, phone, first name, last name), IP address, and user agent are stored for 7 days so the website operator can review their conversion activity in the Converly dashboard.
  - period: 30 days
    scope: Form-submission metadata
    text: the entire record is then automatically deleted at 30 days .
  - period: Deleted within 90 days of account closure
    scope: Customer account data
    text: Customer account data (name, email, company, billing) Retained while the account is active; deleted within 90 days of account closure
  - period: Deleted within 7 days of disconnection
    scope: OAuth tokens
    text: OAuth tokens for connected ad platforms Retained while the connection is active; deleted within 7 days of disconnection
  - period: 7 years
    scope: Billing records and invoices
    text: Billing records and invoices 7 years (legal and tax requirement)
  - period: 30 days
    scope: Server and application logs
    text: Server and application logs 30 days
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correct
    text: Correct inaccurate or incomplete information
  - right: Delete
    text: Delete your personal information
  - right: Restrict or object
    text: Restrict or object to processing
  - right: Portability
    text: Receive your information in a portable format
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent
  - right: Opt out of sale or sharing
    text: Opt out of the sale or sharing of personal information (Converly does not sell personal information; this right is provided automatically)
  - right: Complain
    text: Lodge a complaint with your local data protection authority
  role:
    text: For this group, Converly is the data controller . Visitors to a Converly customer’s website — people who submit forms on a website that has Converly installed. For this group, the website operator who installed Converly is the data controller , and Converly is the data processor acting on their instructions.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: 'We do not : Sell personal information to third parties under any circumstances'
  subprocessors:
    text: We rely on the following third-party service providers (“subprocessors”) to operate Converly. Each is contractually bound by appropriate data-protection terms.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required by GDPR, UK GDPR, or other applicable law, we rely on Standard Contractual Clauses (SCCs) approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Converly
provenance_date: '2026-11-09'
provider_name: Converly
provider_slug: converly-io
slug: converly-io-privacy-policy
source_date: '2026-11-09'
source_filename: converly-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://converly.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Converly\naid: converly-io\nurl: https://converly.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For this group, Converly is the data controller . Visitors to a Converly customer’s website — people who\n    submit forms on a website that has Converly installed. For this group, the website operator who installed Converly\n    is the data controller , and Converly is the data processor acting on their instructions.\ndata_categories:\n- category: contact\n  text: 'Personal information submitted in the form: email address, phone number, first name, last name, and any\n    other fields\
  \ the website operator chooses to capture'\n- category: identifying\n  text: Name and email address (for account creation and product communications)\n- category: financial\n  text: Billing information (processed by Stripe — Converly does not store full card numbers; we receive only the\n    last four digits and card brand)\n- category: device\n  text: The visitor’s IP address and browser user agent\n- category: behavioral\n  text: The URL of the page where the form was submitted, and the URL of the page that referred the visitor there\n- category: communication\n  text: Advertising cookies set by the visitor’s browser (e.g. Facebook’s _fbp and _fbc cookies)\npurposes:\n- purpose: Provide the Converly service\n  text: 'Provide the Converly service: track conversions, display the dashboard, and forward conversion events to\n    the advertising and analytics platforms the customer has connected'\n- purpose: Authenticate and secure\n  text: Authenticate customers and secure the service\n\
  - purpose: Billing\n  text: Bill customers (via Stripe)\n- purpose: Transactional email\n  text: Send transactional emails (account notifications, billing receipts, password resets)\n- purpose: Diagnostics and abuse\n  text: Diagnose technical issues and investigate abuse\nretention:\n- scope: Plaintext personal information from form submissions\n  period: 7 days\n  text: Plaintext personal information (email, phone, first name, last name), IP address, and user agent are stored\n    for 7 days so the website operator can review their conversion activity in the Converly dashboard.\n- scope: Form-submission metadata\n  period: 30 days\n  text: the entire record is then automatically deleted at 30 days .\n- scope: Customer account data\n  period: Deleted within 90 days of account closure\n  text: Customer account data (name, email, company, billing) Retained while the account is active; deleted within\n    90 days of account closure\n- scope: OAuth tokens\n  period: Deleted within 7 days\
  \ of disconnection\n  text: OAuth tokens for connected ad platforms Retained while the connection is active; deleted within 7 days of\n    disconnection\n- scope: Billing records and invoices\n  period: 7 years\n  text: Billing records and invoices 7 years (legal and tax requirement)\n- scope: Server and application logs\n  period: 30 days\n  text: Server and application logs 30 days\nresidency:\n- region: United States\n  text: Our infrastructure subprocessors that store or process conversion data are located in the United States\n    (see Section 4.2).\ntransfers:\n- mechanism: SCC\n  text: Where required by GDPR, UK GDPR, or other applicable law, we rely on Standard Contractual Clauses (SCCs)\n    approved by the European Commission\nsubprocessors:\n  url: null\n  text: We rely on the following third-party service providers (“subprocessors”) to operate Converly. Each is contractually\n    bound by appropriate data-protection terms.\ndpa:\n  available: null\n  url: null\n  text: null\n\
  deletion:\n  route: Email privacy@converly.io or close account from dashboard\n  text: Customers can request earlier deletion of any of their data at any time by emailing privacy@converly.io\n    or by closing their account from within the dashboard.\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correct\n  text: Correct inaccurate or incomplete information\n- right: Delete\n  text: Delete your personal information\n- right: Restrict or object\n  text: Restrict or object to processing\n- right: Portability\n  text: Receive your information in a portable format\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent\n- right: Opt out of sale or sharing\n  text: Opt out of the sale or sharing of personal information (Converly does not sell personal information; this\n    right is provided automatically)\n- right: Complain\n  text: Lodge a complaint with your local data protection authority\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: 'We do not : Sell personal information to third parties under any circumstances'\n"
source_yaml_url: https://artifacts.apis.io/converly-io/privacy/converly-io-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Converly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Conversion Tracking
- Marketing
- Advertising
- Analytics
- MCP
- REST API
---
