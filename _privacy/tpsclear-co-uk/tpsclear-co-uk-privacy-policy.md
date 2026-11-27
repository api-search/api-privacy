---
api_specs:
- filename: tpsclear-co-uk-openapi-generated.yml
  format: yaml
  label: tpsclear-co-uk API
  slug: tpsclear-co-uk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tpsclear-co-uk/openapi/_ae-authored/tpsclear-co-uk-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: communication
    text: UK and Australian phone numbers submitted for screening.
  - category: identifying
    text: 'Account identifiers required to authenticate the request: CRM-side OAuth tokens, API keys, customer account IDs.'
  - category: contact
    text: Email address, name, organisation, a phone number if you ask us to call you back, and any message content sent to us.
  - category: device
    text: Standard server logs (IP address, user agent) retained for security and abuse-prevention purposes.
  deletion:
    route: email privacy@tpsclear.co.uk
    text: To exercise any of these rights, email privacy@tpsclear.co.uk .
  dpa:
    available: true
    text: Our Data Processing Agreement is published at tpsclear.co.uk/dpa .
    url: tpsclear.co.uk/dpa
  purposes:
  - purpose: service delivery
    text: To deliver the TPSClear screening service to customers and account holders.
  - purpose: security and abuse prevention
    text: To secure the service, prevent abuse, improve performance, monitor usage against fair limits, and respond to support enquiries.
  - purpose: legal obligation
    text: Where we are required by law to retain records or respond to lawful requests.
  residency:
  - region: United Kingdom
    text: service hosted in London, United Kingdom
  - region: EU
    text: managed Postgres in an EU region
  retention:
  - period: 24 months
    scope: Screening audit log
    text: Audit records are retained for 24 months, then deleted
  - period: null
    scope: Free checker
    text: Numbers entered and their verdicts are not retained.
  - period: 12 months
    scope: Dead number check results
    text: These records are retained for 12 months, then deleted.
  - period: 24 months
    scope: CRM screening log
    text: Entries are retained for 24 months, then deleted.
  - period: 60 days
    scope: Screening result cache
    text: Cached verdicts are deleted no later than 60 days after the underlying check.
  - period: 12 months
    scope: Operational telemetry
    text: Operational telemetry (timestamps, error codes, usage counts) is retained for up to 12 months, then deleted or fully anonymised.
  rights:
  - right: access
    text: access the personal data we hold about you
  - right: erasure
    text: have your data erased in certain circumstances
  - right: objection and restriction
    text: restrict or object to certain types of processing
  - right: portability
    text: data portability where applicable
  role:
    text: TPSClear is the data processor , processing this data on the customer's documented instructions to perform the screening service.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share customer data with third parties for marketing purposes.
  subprocessors:
    text: A current list of sub-processors with locations and transfer mechanisms is published at tpsclear.co.uk/subprocessors .
    url: tpsclear.co.uk/subprocessors
  transfers:
  - mechanism: SCC
    text: including the UK International Data Transfer Addendum and equivalent Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tpsclear-co-uk
provenance_date: '2026-11-10'
provider_name: tpsclear-co-uk
provider_slug: tpsclear-co-uk
slug: tpsclear-co-uk-privacy-policy
source_date: '2026-11-10'
source_filename: tpsclear-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tpsclear.co.uk/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tpsclear-co-uk\naid: tpsclear-co-uk\nurl: https://tpsclear.co.uk/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: TPSClear is the data processor , processing this data on the customer's documented instructions to perform\n    the screening service.\ndata_categories:\n- category: communication\n  text: UK and Australian phone numbers submitted for screening.\n- category: identifying\n  text: 'Account identifiers required to authenticate the request: CRM-side OAuth tokens, API keys, customer account\n    IDs.'\n- category: contact\n  text: Email address, name, organisation, a phone number if\
  \ you ask us to call you back, and any message content\n    sent to us.\n- category: device\n  text: Standard server logs (IP address, user agent) retained for security and abuse-prevention purposes.\npurposes:\n- purpose: service delivery\n  text: To deliver the TPSClear screening service to customers and account holders.\n- purpose: security and abuse prevention\n  text: To secure the service, prevent abuse, improve performance, monitor usage against fair limits, and respond\n    to support enquiries.\n- purpose: legal obligation\n  text: Where we are required by law to retain records or respond to lawful requests.\nretention:\n- scope: Screening audit log\n  period: 24 months\n  text: Audit records are retained for 24 months, then deleted\n- scope: Free checker\n  period: null\n  text: Numbers entered and their verdicts are not retained.\n- scope: Dead number check results\n  period: 12 months\n  text: These records are retained for 12 months, then deleted.\n- scope: CRM screening log\n\
  \  period: 24 months\n  text: Entries are retained for 24 months, then deleted.\n- scope: Screening result cache\n  period: 60 days\n  text: Cached verdicts are deleted no later than 60 days after the underlying check.\n- scope: Operational telemetry\n  period: 12 months\n  text: Operational telemetry (timestamps, error codes, usage counts) is retained for up to 12 months, then deleted\n    or fully anonymised.\nresidency:\n- region: United Kingdom\n  text: service hosted in London, United Kingdom\n- region: EU\n  text: managed Postgres in an EU region\ntransfers:\n- mechanism: SCC\n  text: including the UK International Data Transfer Addendum and equivalent Standard Contractual Clauses\nsubprocessors:\n  url: tpsclear.co.uk/subprocessors\n  text: A current list of sub-processors with locations and transfer mechanisms is published at tpsclear.co.uk/subprocessors\n    .\ndpa:\n  available: true\n  url: tpsclear.co.uk/dpa\n  text: Our Data Processing Agreement is published at tpsclear.co.uk/dpa\
  \ .\ndeletion:\n  route: email privacy@tpsclear.co.uk\n  text: To exercise any of these rights, email privacy@tpsclear.co.uk .\nrights:\n- right: access\n  text: access the personal data we hold about you\n- right: erasure\n  text: have your data erased in certain circumstances\n- right: objection and restriction\n  text: restrict or object to certain types of processing\n- right: portability\n  text: data portability where applicable\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share customer data with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/tpsclear-co-uk/privacy/tpsclear-co-uk-privacy-policy.yml
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
summary_line: 25 quoted statements, read from tpsclear-co-uk's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- United Kingdom
- HubSpot
- Phone Screening
- Compliance
---
