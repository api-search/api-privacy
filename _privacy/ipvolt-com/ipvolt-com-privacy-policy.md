---
api_specs:
- filename: ipvolt-com-openapi-generated.yml
  format: yaml
  label: ipvolt-com API
  slug: ipvolt-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipvolt-com/openapi/_ae-authored/ipvolt-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store a username, the email address and wallet addresses you sign in with
  - category: contact
    text: If you email us, we keep that correspondence.
  - category: financial
    text: When you top up through NOWPayments, we record the amount, NOWPayments' invoice and payment references and status
  - category: location
    text: Events can include the public page visited, campaign labels, form interactions, broad device information and approximate location.
  - category: behavioral
    text: we use this to understand which pages help people sign up.
  - category: device
    text: the transactions it reported (transaction ID, coin, network and amount)
  deletion:
    route: email hello@ipvolt.com
    text: For access, correction or deletion requests, contact hello@ipvolt.com
  dpa:
    available: null
    text: it has not yet given us a data processing agreement
    url: null
  purposes:
  - purpose: provide service and handle payments
    text: To provide the service, handle payments and answer your messages under our contract with you;
  - purpose: legal obligations
    text: to keep the financial records the law requires and answer lawful requests from authorities, under our legal obligations;
  - purpose: legitimate interests
    text: in our legitimate interests, to secure the service, limit sign-in attempts, prevent fraud and abuse, handle abuse reports, handle disputes
  residency:
  - region: Finland
    text: Hetzner (server hosting in Helsinki, Finland)
  retention:
  - period: up to two years
    scope: account and order records
    text: Account and order records are kept while your account is open and for up to two years after it closes
  - period: up to 90 days
    scope: server logs
    text: Server logs are kept for up to 90 days, and database backups for 14 days.
  - period: 14 days
    scope: database backups
    text: database backups for 14 days
  - period: 90 days
    scope: API request log
    text: we delete each entry after 90 days
  - period: about a day
    scope: sign-in codes and sign-in hashes
    text: We delete these after about a day.
  - period: 30 days
    scope: support chat conversations
    text: We keep each conversation for 30 days after it starts and then delete it
  - period: about 90 days
    scope: residential supplier usage and audit records (as reported by supplier)
    text: that it keeps daily key usage and audit records for about 90 days
  rights:
  - right: access, correction, deletion, restriction, portability
    text: You can ask for a copy of your data, for its correction or deletion, for its use to be restricted, or to receive data you gave us in a portable format
  - right: object
    text: and you can object to uses based on our legitimate interests.
  - right: complain to authority
    text: You can also complain to the data protection authority where you live or work.
  role:
    text: ipvolt is operated by the individual or individuals who run ipvolt, who are the controller of the personal data described on this page.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Where a service provider that processes data for us is certified under the EU–US Data Privacy Framework
  - mechanism: SCC
    text: otherwise we rely on the standard contractual clauses in its data processing terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ipvolt-com
provenance_date: '2026-11-09'
provider_name: ipvolt-com
provider_slug: ipvolt-com
slug: ipvolt-com-privacy-policy
source_date: '2026-11-09'
source_filename: ipvolt-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ipvolt.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ipvolt-com\naid: ipvolt-com\nurl: https://ipvolt.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ipvolt is operated by the individual or individuals who run ipvolt, who are the controller of the personal\n    data described on this page.\ndata_categories:\n- category: identifying\n  text: We store a username, the email address and wallet addresses you sign in with\n- category: contact\n  text: If you email us, we keep that correspondence.\n- category: financial\n  text: When you top up through NOWPayments, we record the amount, NOWPayments' invoice and payment references and\n \
  \   status\n- category: location\n  text: Events can include the public page visited, campaign labels, form interactions, broad device information\n    and approximate location.\n- category: behavioral\n  text: we use this to understand which pages help people sign up.\n- category: device\n  text: the transactions it reported (transaction ID, coin, network and amount)\npurposes:\n- purpose: provide service and handle payments\n  text: To provide the service, handle payments and answer your messages under our contract with you;\n- purpose: legal obligations\n  text: to keep the financial records the law requires and answer lawful requests from authorities, under our legal\n    obligations;\n- purpose: legitimate interests\n  text: in our legitimate interests, to secure the service, limit sign-in attempts, prevent fraud and abuse, handle\n    abuse reports, handle disputes\nretention:\n- scope: account and order records\n  period: up to two years\n  text: Account and order records are kept\
  \ while your account is open and for up to two years after it closes\n- scope: server logs\n  period: up to 90 days\n  text: Server logs are kept for up to 90 days, and database backups for 14 days.\n- scope: database backups\n  period: 14 days\n  text: database backups for 14 days\n- scope: API request log\n  period: 90 days\n  text: we delete each entry after 90 days\n- scope: sign-in codes and sign-in hashes\n  period: about a day\n  text: We delete these after about a day.\n- scope: support chat conversations\n  period: 30 days\n  text: We keep each conversation for 30 days after it starts and then delete it\n- scope: residential supplier usage and audit records (as reported by supplier)\n  period: about 90 days\n  text: that it keeps daily key usage and audit records for about 90 days\nresidency:\n- region: Finland\n  text: Hetzner (server hosting in Helsinki, Finland)\ntransfers:\n- mechanism: DPF\n  text: Where a service provider that processes data for us is certified under the\
  \ EU–US Data Privacy Framework\n- mechanism: SCC\n  text: otherwise we rely on the standard contractual clauses in its data processing terms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: it has not yet given us a data processing agreement\ndeletion:\n  route: email hello@ipvolt.com\n  text: For access, correction or deletion requests, contact hello@ipvolt.com\nrights:\n- right: access, correction, deletion, restriction, portability\n  text: You can ask for a copy of your data, for its correction or deletion, for its use to be restricted, or to\n    receive data you gave us in a portable format\n- right: object\n  text: and you can object to uses based on our legitimate interests.\n- right: complain to authority\n  text: You can also complain to the data protection authority where you live or work.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ipvolt-com/privacy/ipvolt-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from ipvolt-com's own page on 2026-11-09.
synthetic: false
tags:
- Proxy
- Developer Tools
- Infrastructure
- Networking
- Data
---
