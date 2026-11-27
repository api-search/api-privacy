---
api_specs:
- filename: flowmingo-flowmingo-api-api-openapi.yml
  format: yaml
  label: Flowmingo Flowmingo API
  slug: flowmingo-flowmingo-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmingo/openapi/flowmingo-flowmingo-api-api-openapi.yml
- filename: flowmingo-scheduler-api-openapi.yml
  format: yaml
  label: Flowmingo Scheduler API
  slug: flowmingo-scheduler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmingo/openapi/flowmingo-scheduler-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: CV details (name, email, work/education history, contact details)
  - category: identifying
    text: Account details and login credentials
  - category: financial
    text: Billing and payment information
  - category: device
    text: Device information, IP addresses, browser/device identifiers, cookies, cache, and diagnostic logs
  - category: communication
    text: Written and video/audio interview responses
  - category: behavioral
    text: AI evaluation reports/assessment test results purchased directly by candidates (Flowmingo is the controller)
  - category: other
    text: Other information voluntarily provided by candidates during interviews or assessments (e.g., references, portfolio links, or additional documentation)
  deletion:
    route: Contact compliance@flowmingo.ai or deletion on recruiter instruction
    text: When you ask us to delete your connected account's data, we delete the tokens and those records, unless the law requires us to keep them longer.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Platform operation and compliance
    text: retain and process its own copy of candidate data for limited and clearly defined purposes (e.g., platform security, quality assurance, legal compliance)
  - purpose: AI training and evaluation (DCP)
    text: AI training, AI evaluation, benchmarking, quality assurance, safety testing, and related research and development
  - purpose: Billing and payment processing
    text: Recruiter billing & payment processing Legal obligation (6(1)(c))
  residency:
  - region: Singapore
    text: Personal data may be transferred outside the EEA, including to Singapore, where Flowmingo is based
  retention:
  - period: 2 years
    scope: Recruiter-owned candidate data
    text: will be deleted when instructed by the recruiter or when the recruiter account is closed and inactive for more than 2 years
  - period: 2 years
    scope: Candidate-paid reports/tests
    text: 'Candidate-paid reports/tests: retained for 2 years by default, unless renewed or deleted at the candidate''s request.'
  - period: 2 years
    scope: Recruiter accounts
    text: 'Recruiter accounts: retained for 2 years post-closure.'
  - period: 7 years
    scope: Billing/payment records
    text: 'Billing/payment records: retained up to 7 years (legal obligation).'
  rights:
  - right: Human intervention
    text: Request human intervention by contacting Flowmingo at compliance@flowmingo.ai.
  - right: Contest automated assessments
    text: Express their views or contest automated assessments (requests will be forwarded and tracked).
  - right: Withdraw consent (DCP)
    text: candidates can withdraw consent at any time through the method described in the DCP screens or by contacting us.
  - right: Opt-out of AI model improvement
    text: Opt-out of AI model improvement uses.
  role:
    text: Flowmingo acts both as a processor (on behalf of recruiters) and as a controller of its own copy of that data
    value: both
  sale_or_sharing:
    stance: conditional
    text: DCP datasets may be shared with trusted organizations globally.
  subprocessors:
    text: A current list of these providers, and where each is located, is available on request from compliance@flowmingo.ai.
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers rely on Standard Contractual Clauses (SCCs) and Transfer Impact Assessments (TIAs).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Flowmingo
provenance_date: '2026-11-09'
provider_name: Flowmingo
provider_slug: flowmingo
slug: flowmingo-privacy-policy
source_date: '2026-11-09'
source_filename: flowmingo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flowmingo.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Flowmingo\naid: flowmingo\nurl: https://flowmingo.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Flowmingo acts both as a processor (on behalf of recruiters) and as a controller of its own copy of that\n    data\ndata_categories:\n- category: contact\n  text: CV details (name, email, work/education history, contact details)\n- category: identifying\n  text: Account details and login credentials\n- category: financial\n  text: Billing and payment information\n- category: device\n  text: Device information, IP addresses, browser/device identifiers, cookies, cache, and diagnostic\
  \ logs\n- category: communication\n  text: Written and video/audio interview responses\n- category: behavioral\n  text: AI evaluation reports/assessment test results purchased directly by candidates (Flowmingo is the controller)\n- category: other\n  text: Other information voluntarily provided by candidates during interviews or assessments (e.g., references,\n    portfolio links, or additional documentation)\npurposes:\n- purpose: Platform operation and compliance\n  text: retain and process its own copy of candidate data for limited and clearly defined purposes (e.g., platform\n    security, quality assurance, legal compliance)\n- purpose: AI training and evaluation (DCP)\n  text: AI training, AI evaluation, benchmarking, quality assurance, safety testing, and related research and development\n- purpose: Billing and payment processing\n  text: Recruiter billing & payment processing Legal obligation (6(1)(c))\nretention:\n- scope: Recruiter-owned candidate data\n  period: 2 years\n  text:\
  \ will be deleted when instructed by the recruiter or when the recruiter account is closed and inactive for\n    more than 2 years\n- scope: Candidate-paid reports/tests\n  period: 2 years\n  text: 'Candidate-paid reports/tests: retained for 2 years by default, unless renewed or deleted at the candidate''s\n    request.'\n- scope: Recruiter accounts\n  period: 2 years\n  text: 'Recruiter accounts: retained for 2 years post-closure.'\n- scope: Billing/payment records\n  period: 7 years\n  text: 'Billing/payment records: retained up to 7 years (legal obligation).'\nresidency:\n- region: Singapore\n  text: Personal data may be transferred outside the EEA, including to Singapore, where Flowmingo is based\ntransfers:\n- mechanism: SCC\n  text: Transfers rely on Standard Contractual Clauses (SCCs) and Transfer Impact Assessments (TIAs).\nsubprocessors:\n  url: null\n  text: A current list of these providers, and where each is located, is available on request from compliance@flowmingo.ai.\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact compliance@flowmingo.ai or deletion on recruiter instruction\n  text: When you ask us to delete your connected account's data, we delete the tokens and those records, unless\n    the law requires us to keep them longer.\nrights:\n- right: Human intervention\n  text: Request human intervention by contacting Flowmingo at compliance@flowmingo.ai.\n- right: Contest automated assessments\n  text: Express their views or contest automated assessments (requests will be forwarded and tracked).\n- right: Withdraw consent (DCP)\n  text: candidates can withdraw consent at any time through the method described in the DCP screens or by contacting\n    us.\n- right: Opt-out of AI model improvement\n  text: Opt-out of AI model improvement uses.\nsale_or_sharing:\n  stance: conditional\n  text: DCP datasets may be shared with trusted organizations globally.\n"
source_yaml_url: https://artifacts.apis.io/flowmingo/privacy/flowmingo-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Flowmingo's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
