---
api_specs:
- filename: tenderapi-eu-organisations-api-openapi.yml
  format: yaml
  label: tenderapi-eu Organisations API
  slug: tenderapi-eu-organisations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-eu/openapi/tenderapi-eu-organisations-api-openapi.yml
- filename: tenderapi-eu-tenders-api-openapi.yml
  format: yaml
  label: tenderapi-eu Tenders API
  slug: tenderapi-eu-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-eu/openapi/tenderapi-eu-tenders-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data : your email address, a hash of your password (never the password itself), email verification status, your plan, and the names and creation dates of your API keys.'
  - category: financial
    text: 'Billing data : the Stripe customer and subscription IDs and the subscription status.'
  - category: device
    text: 'Technical data : IP addresses, request paths, timestamps and user agents in server logs'
  - category: behavioral
    text: 'Usage data : the number of API requests per day and month, and when each API key was last used'
  - category: communication
    text: 'Communication : emails you send to us and our replies.'
  - category: other
    text: 'Tender notices : public procurement notices can contain names, emails and phone numbers of contact persons at contracting authorities.'
  deletion:
    route: email
    text: To exercise them, or to delete your account, email [email protected] .
  dpa:
    available: true
    text: which process data on our behalf under data processing agreements
    url: null
  purposes:
  - purpose: Providing the Service, account, billing and support
    text: 'Providing the Service, your account, billing and support: performance of our contract with you (Art. 6(1)(b) GDPR).'
  - purpose: Security, rate limiting and abuse prevention
    text: 'Security, rate limiting, abuse prevention, debugging and cookieless analytics: our legitimate interest in running a secure and reliable service (Art. 6(1)(f) GDPR).'
  - purpose: Republishing contact details from tender notices
    text: 'Republishing contact details from public tender notices: our legitimate interest, and that of our users, in access to public procurement information (Art. 6(1)(f) GDPR).'
  - purpose: Tax and accounting records
    text: 'Keeping records required by tax and accounting law: legal obligation (Art. 6(1)(c) GDPR).'
  residency:
  - region: Germany
    text: 'Hetzner Online GmbH, Germany: API servers.'
  - region: Germany
    text: 'Elestio: managed database, hosted at Hetzner in Germany.'
  - region: EU (Ireland)
    text: 'Resend (Plus Five Five, Inc.), USA, sent from the EU (Ireland): sending service emails.'
  retention:
  - period: until your account is deleted
    scope: Account, API key and usage data
    text: 'Account, API key and usage data: until your account is deleted.'
  - period: usually within days
    scope: Server logs
    text: 'Server logs: rotated automatically, usually within days.'
  - period: at most one day
    scope: Rate-limiting data
    text: 'Rate-limiting data: held in memory for at most one day.'
  - period: 10 years
    scope: Billing records
    text: 'Billing records: as long as tax and accounting law requires, typically 10 years.'
  rights:
  - right: access, rectification, erasure
    text: You have the right to access, rectify and erase your personal data, to restrict or object to its processing, and to data portability.
  - right: complain to supervisory authority
    text: You can also complain to a data protection supervisory authority.
  role:
    text: Controller Jure Vito Srovin, Staretova ulica 17, 1000 Ljubljana, Slovenia.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or use it for advertising.
  subprocessors:
    text: 'We use the following providers, which process data on our behalf under data processing agreements:'
    url: null
  transfers:
  - mechanism: DPF
    text: Where they do, transfers are protected by the EU–US Data Privacy Framework or the European Commission's Standard Contractual Clauses.
  - mechanism: SCC
    text: Where they do, transfers are protected by the EU–US Data Privacy Framework or the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tenderapi-eu
provenance_date: '2026-11-10'
provider_name: tenderapi-eu
provider_slug: tenderapi-eu
slug: tenderapi-eu-privacy-policy
source_date: '2026-11-10'
source_filename: tenderapi-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tenderapi.eu/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tenderapi-eu\naid: tenderapi-eu\nurl: https://tenderapi.eu/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller Jure Vito Srovin, Staretova ulica 17, 1000 Ljubljana, Slovenia.\ndata_categories:\n- category: contact\n  text: 'Account data : your email address, a hash of your password (never the password itself), email verification\n    status, your plan, and the names and creation dates of your API keys.'\n- category: financial\n  text: 'Billing data : the Stripe customer and subscription IDs and the subscription status.'\n- category: device\n  text: 'Technical data : IP addresses,\
  \ request paths, timestamps and user agents in server logs'\n- category: behavioral\n  text: 'Usage data : the number of API requests per day and month, and when each API key was last used'\n- category: communication\n  text: 'Communication : emails you send to us and our replies.'\n- category: other\n  text: 'Tender notices : public procurement notices can contain names, emails and phone numbers of contact persons\n    at contracting authorities.'\npurposes:\n- purpose: Providing the Service, account, billing and support\n  text: 'Providing the Service, your account, billing and support: performance of our contract with you (Art. 6(1)(b)\n    GDPR).'\n- purpose: Security, rate limiting and abuse prevention\n  text: 'Security, rate limiting, abuse prevention, debugging and cookieless analytics: our legitimate interest\n    in running a secure and reliable service (Art. 6(1)(f) GDPR).'\n- purpose: Republishing contact details from tender notices\n  text: 'Republishing contact details from\
  \ public tender notices: our legitimate interest, and that of our users,\n    in access to public procurement information (Art. 6(1)(f) GDPR).'\n- purpose: Tax and accounting records\n  text: 'Keeping records required by tax and accounting law: legal obligation (Art. 6(1)(c) GDPR).'\nretention:\n- scope: Account, API key and usage data\n  period: until your account is deleted\n  text: 'Account, API key and usage data: until your account is deleted.'\n- scope: Server logs\n  period: usually within days\n  text: 'Server logs: rotated automatically, usually within days.'\n- scope: Rate-limiting data\n  period: at most one day\n  text: 'Rate-limiting data: held in memory for at most one day.'\n- scope: Billing records\n  period: 10 years\n  text: 'Billing records: as long as tax and accounting law requires, typically 10 years.'\nresidency:\n- region: Germany\n  text: 'Hetzner Online GmbH, Germany: API servers.'\n- region: Germany\n  text: 'Elestio: managed database, hosted at Hetzner in Germany.'\n\
  - region: EU (Ireland)\n  text: 'Resend (Plus Five Five, Inc.), USA, sent from the EU (Ireland): sending service emails.'\ntransfers:\n- mechanism: DPF\n  text: Where they do, transfers are protected by the EU–US Data Privacy Framework or the European Commission's\n    Standard Contractual Clauses.\n- mechanism: SCC\n  text: Where they do, transfers are protected by the EU–US Data Privacy Framework or the European Commission's\n    Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: 'We use the following providers, which process data on our behalf under data processing agreements:'\ndpa:\n  available: true\n  url: null\n  text: which process data on our behalf under data processing agreements\ndeletion:\n  route: email\n  text: To exercise them, or to delete your account, email [email protected] .\nrights:\n- right: access, rectification, erasure\n  text: You have the right to access, rectify and erase your personal data, to restrict or object to its processing,\n    and\
  \ to data portability.\n- right: complain to supervisory authority\n  text: You can also complain to a data protection supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/tenderapi-eu/privacy/tenderapi-eu-privacy-policy.yml
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
summary_line: 26 quoted statements, read from tenderapi-eu's own page on 2026-11-10.
synthetic: false
tags:
- EU
- Procurement
- Tenders
- Data
---
