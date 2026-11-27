---
api_specs:
- filename: agentdrives-com-accounts-api-openapi.yml
  format: yaml
  label: agentdrives-com Accounts API
  slug: agentdrives-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-accounts-api-openapi.yml
- filename: agentdrives-com-claims-api-openapi.yml
  format: yaml
  label: agentdrives-com Claims API
  slug: agentdrives-com-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-claims-api-openapi.yml
- filename: agentdrives-com-directory-api-openapi.yml
  format: yaml
  label: agentdrives-com Directory API
  slug: agentdrives-com-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-directory-api-openapi.yml
- filename: agentdrives-com-follows-api-openapi.yml
  format: yaml
  label: agentdrives-com Follows API
  slug: agentdrives-com-follows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-follows-api-openapi.yml
- filename: agentdrives-com-newsletter-api-openapi.yml
  format: yaml
  label: agentdrives-com Newsletter API
  slug: agentdrives-com-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-newsletter-api-openapi.yml
- filename: agentdrives-com-orders-api-openapi.yml
  format: yaml
  label: agentdrives-com Orders API
  slug: agentdrives-com-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-orders-api-openapi.yml
- filename: agentdrives-com-pay-over-http-402-api-openapi.yml
  format: yaml
  label: agentdrives-com Pay over HTTP 402 API
  slug: agentdrives-com-pay-over-http-402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-pay-over-http-402-api-openapi.yml
- filename: agentdrives-com-support-api-openapi.yml
  format: yaml
  label: agentdrives-com Support API
  slug: agentdrives-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdrives-com/openapi/agentdrives-com-support-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your account: email, name if given, your Google profile if you sign in with Google, API keys (hashed)'
  - category: contact
    text: 'Questions and requests: hello@agentdrives.com'
  - category: financial
    text: the billing address you give at checkout and, for a business, its name and VAT ID (they go on our invoice)
  - category: device
    text: 'Sign-ins: IP address and browser'
  - category: communication
    text: Messages between you and us, support questions, forms (with the IP address a form came from)
  deletion:
    route: Account deletion in account settings or via API
    text: Delete your account in your account or with POST /api/auth/delete-user
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account contract
    text: To give you an account (contract)
  - purpose: Legal books
    text: keep the books (legal obligation)
  - purpose: Site security
    text: To keep the site secure and running (legitimate interest)
  - purpose: Monthly report consent
    text: The monthly report and offers (consent)
  residency:
  - region: Netherlands
    text: AgentDrives is based in the Netherlands.
  - region: Germany
    text: Hetzner Our servers and database Germany
  retention:
  - period: Until you delete it
    scope: Account data
    text: Until you delete it
  - period: 30 days
    scope: Sign-in IP and browser
    text: The IP address and browser for 30 days.
  - period: 7 years
    scope: Orders and payments
    text: 7 years (Dutch tax law)
  - period: 7 days
    scope: Access log
    text: Our access log. The IP address, the request's headers (such as the app's name), the address it called and the time, for 7 days.
  - period: 13 months
    scope: Task search
    text: For 13 months.
  - period: 12 months
    scope: Encrypted backups
    text: Encrypted backups hold copies of this data for up to 12 months, to recover from a failure.
  - period: 24 months
    scope: Drive records
    text: 'Records and screenshots: 24 months in our evidence store, and on our server until we delete them'
  rights:
  - right: Access, correction, deletion, portability, restriction, objection
    text: You can see, correct or delete your data, get a copy of it, limit how we use it, and object to its use.
  - right: Complaint to authority
    text: You can also complain to the Dutch data protection authority, the Autoriteit Persoonsgegevens
  role:
    text: We are responsible for your data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell it or use it for ads.
  subprocessors:
    text: Who processes it for us
    url: null
  transfers:
  - mechanism: DPF
    text: For transfers to the USA we rely on the EU–US Data Privacy Framework or the EU's standard contractual clauses.
  - mechanism: SCC
    text: the EU's standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agentdrives-com
provenance_date: '2026-11-09'
provider_name: agentdrives-com
provider_slug: agentdrives-com
slug: agentdrives-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentdrives-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentdrives.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agentdrives-com\naid: agentdrives-com\nurl: https://agentdrives.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for your data.\ndata_categories:\n- category: identifying\n  text: 'Your account: email, name if given, your Google profile if you sign in with Google, API keys (hashed)'\n- category: contact\n  text: 'Questions and requests: hello@agentdrives.com'\n- category: financial\n  text: the billing address you give at checkout and, for a business, its name and VAT ID (they go on our invoice)\n- category: device\n  text: 'Sign-ins: IP address and browser'\n\
  - category: communication\n  text: Messages between you and us, support questions, forms (with the IP address a form came from)\npurposes:\n- purpose: Account contract\n  text: To give you an account (contract)\n- purpose: Legal books\n  text: keep the books (legal obligation)\n- purpose: Site security\n  text: To keep the site secure and running (legitimate interest)\n- purpose: Monthly report consent\n  text: The monthly report and offers (consent)\nretention:\n- scope: Account data\n  period: Until you delete it\n  text: Until you delete it\n- scope: Sign-in IP and browser\n  period: 30 days\n  text: The IP address and browser for 30 days.\n- scope: Orders and payments\n  period: 7 years\n  text: 7 years (Dutch tax law)\n- scope: Access log\n  period: 7 days\n  text: Our access log. The IP address, the request's headers (such as the app's name), the address it called and\n    the time, for 7 days.\n- scope: Task search\n  period: 13 months\n  text: For 13 months.\n- scope: Encrypted\
  \ backups\n  period: 12 months\n  text: Encrypted backups hold copies of this data for up to 12 months, to recover from a failure.\n- scope: Drive records\n  period: 24 months\n  text: 'Records and screenshots: 24 months in our evidence store, and on our server until we delete them'\nresidency:\n- region: Netherlands\n  text: AgentDrives is based in the Netherlands.\n- region: Germany\n  text: Hetzner Our servers and database Germany\ntransfers:\n- mechanism: DPF\n  text: For transfers to the USA we rely on the EU–US Data Privacy Framework or the EU's standard contractual clauses.\n- mechanism: SCC\n  text: the EU's standard contractual clauses\nsubprocessors:\n  url: null\n  text: Who processes it for us\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion in account settings or via API\n  text: Delete your account in your account or with POST /api/auth/delete-user\nrights:\n- right: Access, correction, deletion, portability, restriction, objection\n\
  \  text: You can see, correct or delete your data, get a copy of it, limit how we use it, and object to its use.\n- right: Complaint to authority\n  text: You can also complain to the Dutch data protection authority, the Autoriteit Persoonsgegevens\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell it or use it for ads.\n"
source_yaml_url: https://artifacts.apis.io/agentdrives-com/privacy/agentdrives-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from agentdrives-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Lab
- Software
- Testing
- Data
---
