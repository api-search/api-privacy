---
api_specs:
- filename: jid-com-monitors-api-openapi.yml
  format: yaml
  label: jid-com Monitors API
  slug: jid-com-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-monitors-api-openapi.yml
- filename: jid-com-qualify-api-openapi.yml
  format: yaml
  label: jid-com Qualify API
  slug: jid-com-qualify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-qualify-api-openapi.yml
- filename: jid-com-screen-api-openapi.yml
  format: yaml
  label: jid-com Screen API
  slug: jid-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-screen-api-openapi.yml
- filename: jid-com-search-api-openapi.yml
  format: yaml
  label: jid-com Search API
  slug: jid-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-search-api-openapi.yml
- filename: jid-com-signal-api-openapi.yml
  format: yaml
  label: jid-com Signal API
  slug: jid-com-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-signal-api-openapi.yml
- filename: jid-com-verify-api-openapi.yml
  format: yaml
  label: jid-com Verify API
  slug: jid-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-verify-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: your e-mail address, a short business profile and your certification if you create an account
  - category: contact
    text: your name, e-mail and message if you report an error
  - category: financial
    text: Stripe billing identifiers if you add a card
  - category: location
    text: approximate location derived from your IP address
  - category: device
    text: browser, device type, screen size, language
  - category: behavioral
    text: events such as page views, scrolls, clicks on links that leave the site
  - category: communication
    text: the content of your message and our reply
  - category: professional
    text: Your name, work e-mail address, company, role, company website, what you are building
  deletion:
    route: Written request to privacy@jid.com, or account closure
    text: deleted within 30 days after you ask us to close it
  dpa:
    available: true
    text: under the data processing terms in the API and MCP Terms
    url: /api-terms
  purposes:
  - purpose: measure page reads
    text: to count which pages are read
  - purpose: run accounts and prevent misuse
    text: We use it to run your account, to understand how Jid is used, and to prevent misuse.
  residency:
  - region: United States
    text: Jid is operated from the United States, and our providers process data mainly in the United States.
  retention:
  - period: 90 days, 1 year or 2 years
    scope: Leads inbox
    text: Each lead is deleted at the end of the period you chose (90 days, 1 year or 2 years; 1 year unless you choose otherwise)
  - period: 30 days
    scope: Qualification results and receipts
    text: Deleted after 30 days; 13 months, with the message, only if the API customer opts in
  - period: 15 minutes
    scope: Sign-in links
    text: Expire after 15 minutes; deleted within a few days
  - period: 14 months
    scope: Google Analytics event data
    text: event-level data is kept for no more than 14 months
  - period: 90 days
    scope: Network signal
    text: Rows are deleted after 90 days.
  rights:
  - right: access
    text: know what personal data we hold about you and get a copy (access, and under the CCPA the right to know)
  - right: correction
    text: have inaccurate data corrected
  - right: deletion
    text: have data deleted
  - right: objection
    text: object to processing based on legitimate interests, including the publication described in section 3
  - right: portability
    text: receive data you gave us in a portable format
  role:
    text: Controller or processor. We are the controller for our website, accounts, API keys and billing, claims, disputes, design partner applications, the business files we publish, community reports, and the security and abuse records we keep.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not share it for cross-context behavioural advertising
  subprocessors:
    text: We use the service providers listed on the Subprocessors page ( /subprocessors ) to host, store, bill and send e-mail.
    url: /subprocessors
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses (with the UK Addendum)
  - mechanism: DPF
    text: a provider's certification under the EU-US Data Privacy Framework and its UK and Swiss extensions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: jid-com
provenance_date: '2026-11-09'
provider_name: jid-com
provider_slug: jid-com
slug: jid-com-privacy-policy
source_date: '2026-11-09'
source_filename: jid-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://jid.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: jid-com\naid: jid-com\nurl: https://jid.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: Controller or processor. We are the controller for our website, accounts, API keys and billing, claims,\n    disputes, design partner applications, the business files we publish, community reports, and the security and\n    abuse records we keep.\ndata_categories:\n- category: identifying\n  text: your e-mail address, a short business profile and your certification if you create an account\n- category: contact\n  text: your name, e-mail and message if you report an error\n- category:\
  \ financial\n  text: Stripe billing identifiers if you add a card\n- category: location\n  text: approximate location derived from your IP address\n- category: device\n  text: browser, device type, screen size, language\n- category: behavioral\n  text: events such as page views, scrolls, clicks on links that leave the site\n- category: communication\n  text: the content of your message and our reply\n- category: professional\n  text: Your name, work e-mail address, company, role, company website, what you are building\npurposes:\n- purpose: measure page reads\n  text: to count which pages are read\n- purpose: run accounts and prevent misuse\n  text: We use it to run your account, to understand how Jid is used, and to prevent misuse.\nretention:\n- scope: Leads inbox\n  period: 90 days, 1 year or 2 years\n  text: Each lead is deleted at the end of the period you chose (90 days, 1 year or 2 years; 1 year unless you choose\n    otherwise)\n- scope: Qualification results and receipts\n  period:\
  \ 30 days\n  text: Deleted after 30 days; 13 months, with the message, only if the API customer opts in\n- scope: Sign-in links\n  period: 15 minutes\n  text: Expire after 15 minutes; deleted within a few days\n- scope: Google Analytics event data\n  period: 14 months\n  text: event-level data is kept for no more than 14 months\n- scope: Network signal\n  period: 90 days\n  text: Rows are deleted after 90 days.\nresidency:\n- region: United States\n  text: Jid is operated from the United States, and our providers process data mainly in the United States.\ntransfers:\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses (with the UK Addendum)\n- mechanism: DPF\n  text: a provider's certification under the EU-US Data Privacy Framework and its UK and Swiss extensions\nsubprocessors:\n  url: /subprocessors\n  text: We use the service providers listed on the Subprocessors page ( /subprocessors ) to host, store, bill and\n    send e-mail.\ndpa:\n  available: true\n\
  \  url: /api-terms\n  text: under the data processing terms in the API and MCP Terms\ndeletion:\n  route: Written request to privacy@jid.com, or account closure\n  text: deleted within 30 days after you ask us to close it\nrights:\n- right: access\n  text: know what personal data we hold about you and get a copy (access, and under the CCPA the right to know)\n- right: correction\n  text: have inaccurate data corrected\n- right: deletion\n  text: have data deleted\n- right: objection\n  text: object to processing based on legitimate interests, including the publication described in section 3\n- right: portability\n  text: receive data you gave us in a portable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not share it for cross-context behavioural advertising\n"
source_yaml_url: https://artifacts.apis.io/jid-com/privacy/jid-com-privacy-policy.yml
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
summary_line: 28 quoted statements, read from jid-com's own page on 2026-11-09.
synthetic: false
tags:
- Trust
- Artificial Intelligence
- Compliance
- Data
- Verification
---
