---
api_specs:
- filename: convertlyft-com-tools-api-openapi.yml
  format: yaml
  label: Convertlyft Tools API
  slug: convertlyft-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertlyft-com/openapi/convertlyft-com-tools-api-openapi.yml
claim_count: 52
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email, company, the messages you send
  - category: device
    text: IP address, device and browser type, operating system, referring URL, pages viewed
  - category: financial
    text: 'Billing data (paid plans only): plan, billing address, and transaction history.'
  - category: behavioral
    text: 'Usage data : how you use the dashboard (features used, pages accessed)'
  - category: contact
    text: We may receive limited business contact information (name, email, role) from public sources
  - category: identifying
    source: https://convertlyft.com/dpa
    text: the shopper identifiers Shopify includes in its customer data request and redaction webhooks
  - category: financial
    source: https://convertlyft.com/dpa
    text: checkout events (order value, currency, order id, item count)
  - category: behavioral
    source: https://convertlyft.com/dpa
    text: behavior data (clicks, scrolls, form interactions)
  - category: device
    source: https://convertlyft.com/dpa
    text: technical data (device, browser, errors, performance)
  - category: behavioral
    source: https://convertlyft.com/dpa
    text: visit data (session IDs, timestamps)
  - category: financial
    source: https://convertlyft.com/subprocessors
    text: Card details (entered on Stripe, never stored by us), billing address, and transaction history
  - category: contact
    source: https://convertlyft.com/subprocessors
    text: Recipient email address and message content
  - category: identifying
    source: https://convertlyft.com/subprocessors
    text: Access and refresh tokens for the customer's own connected accounts
  - category: device
    source: https://convertlyft.com/subprocessors
    text: Browser and device signals and the IP address of the person completing the check
  - category: communication
    source: https://convertlyft.com/subprocessors
    text: Messages you send us and your email address
  deletion:
    route: Self-service deletion in Settings; or email privacy@convertlyft.com
    text: You can delete your sites’ data yourself at any time in Settings; that deletion is permanent.
  dpa:
    available: true
    text: under our Data Processing Agreement (" DPA ")
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'To provide the Service (contract): operate your account, deliver dashboards and digests, provide support, send transactional and security notices, process billing.'
  - purpose: Legitimate interests
    text: 'Legitimate interests : improve and secure the Service, prevent fraud and abuse, perform internal analytics and reporting'
  - purpose: Aggregated research
    text: We may aggregate or de-identify information so it can no longer reasonably identify you, and use it for any lawful purpose — including research, benchmarks, and published industry studies.
  - purpose: Provide the Service
    source: https://convertlyft.com/dpa
    text: collection, storage, aggregation, analysis, and display of visitor event data to provide the Service
  - purpose: Application hosting
    source: https://convertlyft.com/subprocessors
    text: Application hosting, delivery and serverless execution
  - purpose: Payment processing
    source: https://convertlyft.com/subprocessors
    text: Processes payments for paid plans and one-off purchases
  - purpose: Error reporting
    source: https://convertlyft.com/subprocessors
    text: Receives error reports from the dashboard and our servers
  - purpose: Bot protection
    source: https://convertlyft.com/subprocessors
    text: the Turnstile bot check on sign-in and password reset
  - purpose: Model calls
    source: https://convertlyft.com/subprocessors
    text: Routes the model calls behind questions asked in the dashboard, written reports, error explanations and drafted fixes
  residency:
  - region: Germany
    text: our servers are located in Germany (database and application servers)
  - region: United States
    text: and the United States (scheduled jobs and error reports)
  - region: Germany
    source: https://convertlyft.com/dpa
    text: Customer Personal Data is stored and processed in Germany (database and application servers)
  - region: United States
    source: https://convertlyft.com/dpa
    text: the United States (scheduled jobs and error reports)
  - region: Germany
    source: https://convertlyft.com/subprocessors
    text: Germany (application servers)
  - region: Germany
    source: https://convertlyft.com/subprocessors
    text: Supabase Primary database, authentication, and file storage Germany
  retention:
  - period: null
    scope: Active accounts
    text: We keep personal information for as long as your account is active or as needed to provide the Service
  - period: 12 months
    scope: Closed accounts
    text: If you close your account, we keep your account and site data for 12 months in case you come back, and then delete it.
  - period: 30 days
    scope: Shopify app stores
    text: Shopify allows 30 days for this; a run that cannot finish is tried again the next hour.
  - period: 90 days
    scope: Customer Personal Data after account termination
    source: https://convertlyft.com/dpa
    text: Within 90 days after account termination, we will delete or anonymize Customer Personal Data
  - period: 30 days
    scope: Customer redaction requests
    source: https://convertlyft.com/dpa
    text: Customer redaction requests are completed within 30 days.
  rights:
  - right: access, correct, or delete
    text: access, correct, or delete your personal information
  - right: object or restrict processing
    text: object to or restrict processing
  - right: data portability
    text: data portability
  - right: withdraw consent
    text: withdraw consent (where processing is based on consent)
  - right: opt out of marketing
    text: opt out of marketing communications
  - right: complain to supervisory authority
    text: lodge a complaint with your local supervisory authority
  - right: Access, deletion, portability, objection
    source: https://convertlyft.com/dpa
    text: Customer is responsible for responding to data-subject requests (access, deletion, portability, objection)
  - right: Tools or exports to locate and delete data
    source: https://convertlyft.com/dpa
    text: tools or exports to locate and delete a visitor's data
  - right: object to new subprocessor
    source: https://convertlyft.com/subprocessors
    text: a customer may object on reasonable data-protection grounds under DPA §4
  role:
    text: the customer is the data controller and we act as their processor/service provider under our Data Processing Agreement
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not share it with third parties for their own advertising.
  subprocessors:
    text: A current list is available at convertlyft.com/subprocessors .
    url: convertlyft.com/subprocessors
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards, including EU Standard Contractual Clauses or the UK International Data Transfer Agreement
  - mechanism: SCC
    source: https://convertlyft.com/dpa
    text: 'the parties rely on the EU Standard Contractual Clauses (Module 2: controller-to-processor)'
  - mechanism: other
    source: https://convertlyft.com/dpa
    text: the UK IDTA/Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Convertlyft
provenance_date: '2026-11-09'
provider_name: Convertlyft
provider_slug: convertlyft-com
slug: convertlyft-com-privacy-policy
source_date: '2026-11-09'
source_filename: convertlyft-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://convertlyft.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Convertlyft\naid: convertlyft-com\nurl: https://convertlyft.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://convertlyft.com/dpa\n  - https://convertlyft.com/privacy\n  - https://convertlyft.com/subprocessors\nrole:\n  value: both\n  text: the customer is the data controller and we act as their processor/service provider under our Data Processing\n    Agreement\ndata_categories:\n- category: identifying\n  text: name, email, company, the messages you send\n- category: device\n  text: IP address, device and browser type, operating system, referring URL, pages viewed\n- category: financial\n \
  \ text: 'Billing data (paid plans only): plan, billing address, and transaction history.'\n- category: behavioral\n  text: 'Usage data : how you use the dashboard (features used, pages accessed)'\n- category: contact\n  text: We may receive limited business contact information (name, email, role) from public sources\n- category: identifying\n  text: the shopper identifiers Shopify includes in its customer data request and redaction webhooks\n  source: https://convertlyft.com/dpa\n- category: financial\n  text: checkout events (order value, currency, order id, item count)\n  source: https://convertlyft.com/dpa\n- category: behavioral\n  text: behavior data (clicks, scrolls, form interactions)\n  source: https://convertlyft.com/dpa\n- category: device\n  text: technical data (device, browser, errors, performance)\n  source: https://convertlyft.com/dpa\n- category: behavioral\n  text: visit data (session IDs, timestamps)\n  source: https://convertlyft.com/dpa\n- category: financial\n  text:\
  \ Card details (entered on Stripe, never stored by us), billing address, and transaction history\n  source: https://convertlyft.com/subprocessors\n- category: contact\n  text: Recipient email address and message content\n  source: https://convertlyft.com/subprocessors\n- category: identifying\n  text: Access and refresh tokens for the customer's own connected accounts\n  source: https://convertlyft.com/subprocessors\n- category: device\n  text: Browser and device signals and the IP address of the person completing the check\n  source: https://convertlyft.com/subprocessors\n- category: communication\n  text: Messages you send us and your email address\n  source: https://convertlyft.com/subprocessors\npurposes:\n- purpose: Provide the Service\n  text: 'To provide the Service (contract): operate your account, deliver dashboards and digests, provide support,\n    send transactional and security notices, process billing.'\n- purpose: Legitimate interests\n  text: 'Legitimate interests : improve\
  \ and secure the Service, prevent fraud and abuse, perform internal analytics\n    and reporting'\n- purpose: Aggregated research\n  text: We may aggregate or de-identify information so it can no longer reasonably identify you, and use it for\n    any lawful purpose — including research, benchmarks, and published industry studies.\n- purpose: Provide the Service\n  text: collection, storage, aggregation, analysis, and display of visitor event data to provide the Service\n  source: https://convertlyft.com/dpa\n- purpose: Application hosting\n  text: Application hosting, delivery and serverless execution\n  source: https://convertlyft.com/subprocessors\n- purpose: Payment processing\n  text: Processes payments for paid plans and one-off purchases\n  source: https://convertlyft.com/subprocessors\n- purpose: Error reporting\n  text: Receives error reports from the dashboard and our servers\n  source: https://convertlyft.com/subprocessors\n- purpose: Bot protection\n  text: the Turnstile bot\
  \ check on sign-in and password reset\n  source: https://convertlyft.com/subprocessors\n- purpose: Model calls\n  text: Routes the model calls behind questions asked in the dashboard, written reports, error explanations and\n    drafted fixes\n  source: https://convertlyft.com/subprocessors\nretention:\n- scope: Active accounts\n  period: null\n  text: We keep personal information for as long as your account is active or as needed to provide the Service\n- scope: Closed accounts\n  period: 12 months\n  text: If you close your account, we keep your account and site data for 12 months in case you come back, and then\n    delete it.\n- scope: Shopify app stores\n  period: 30 days\n  text: Shopify allows 30 days for this; a run that cannot finish is tried again the next hour.\n- scope: Customer Personal Data after account termination\n  period: 90 days\n  text: Within 90 days after account termination, we will delete or anonymize Customer Personal Data\n  source: https://convertlyft.com/dpa\n\
  - scope: Customer redaction requests\n  period: 30 days\n  text: Customer redaction requests are completed within 30 days.\n  source: https://convertlyft.com/dpa\nresidency:\n- region: Germany\n  text: our servers are located in Germany (database and application servers)\n- region: United States\n  text: and the United States (scheduled jobs and error reports)\n- region: Germany\n  text: Customer Personal Data is stored and processed in Germany (database and application servers)\n  source: https://convertlyft.com/dpa\n- region: United States\n  text: the United States (scheduled jobs and error reports)\n  source: https://convertlyft.com/dpa\n- region: Germany\n  text: Germany (application servers)\n  source: https://convertlyft.com/subprocessors\n- region: Germany\n  text: Supabase Primary database, authentication, and file storage Germany\n  source: https://convertlyft.com/subprocessors\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards, including EU Standard Contractual\
  \ Clauses or the UK International Data\n    Transfer Agreement\n- mechanism: SCC\n  text: 'the parties rely on the EU Standard Contractual Clauses (Module 2: controller-to-processor)'\n  source: https://convertlyft.com/dpa\n- mechanism: other\n  text: the UK IDTA/Addendum\n  source: https://convertlyft.com/dpa\nsubprocessors:\n  url: convertlyft.com/subprocessors\n  text: A current list is available at convertlyft.com/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: under our Data Processing Agreement (\" DPA \")\ndeletion:\n  route: Self-service deletion in Settings; or email privacy@convertlyft.com\n  text: You can delete your sites’ data yourself at any time in Settings; that deletion is permanent.\nrights:\n- right: access, correct, or delete\n  text: access, correct, or delete your personal information\n- right: object or restrict processing\n  text: object to or restrict processing\n- right: data portability\n  text: data portability\n- right: withdraw consent\n  text:\
  \ withdraw consent (where processing is based on consent)\n- right: opt out of marketing\n  text: opt out of marketing communications\n- right: complain to supervisory authority\n  text: lodge a complaint with your local supervisory authority\n- right: Access, deletion, portability, objection\n  text: Customer is responsible for responding to data-subject requests (access, deletion, portability, objection)\n  source: https://convertlyft.com/dpa\n- right: Tools or exports to locate and delete data\n  text: tools or exports to locate and delete a visitor's data\n  source: https://convertlyft.com/dpa\n- right: object to new subprocessor\n  text: a customer may object on reasonable data-protection grounds under DPA §4\n  source: https://convertlyft.com/subprocessors\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not share it with third parties for their own advertising.\n"
source_yaml_url: https://artifacts.apis.io/convertlyft-com/privacy/convertlyft-com-privacy-policy.yml
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
summary_line: 52 quoted statements, read from Convertlyft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Analytics
- Conversion Rate Optimization
- Session Replay
- Heatmaps
- SEO
- Error Tracking
- MCP
---
