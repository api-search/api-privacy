---
api_specs:
- filename: carragent-com-agents-api-openapi.yml
  format: yaml
  label: carragent-com Agents API
  slug: carragent-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carragent-com/openapi/carragent-com-agents-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your name, email, business name, role, language and time zone'
  - category: financial
    text: 'Billing: your plan, subscription status and invoices, and the billing details needed for invoices and tax.'
  - category: communication
    text: 'Forwarded email: for the Front desk and Supplier invoices agents, the messages your business forwards to its own Carragent addresses'
  - category: device
    text: 'Technical data: IP address and browser details, to keep the service secure and fix errors.'
  deletion:
    route: Write to admin@carragent.com
    text: Write to admin@carragent.com to ask what personal information we hold about you, to get a copy, to correct it, to have it deleted or to withdraw your consent where the law allows.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run account and features
    text: 'To run your account and the features your business turns on: syncing your tools, reading the email it forwards, preparing and sending the messages you approve or your rules allow'
  - purpose: Billing and tax records
    text: To bill you and keep the records that tax law requires.
  - purpose: Partner program
    text: 'To run the partner program: credit the partner who referred a business when it makes its first payment, and pay them through Stripe or PayPal.'
  - purpose: Security
    text: To keep the service secure, prevent abuse and fix problems.
  residency:
  - region: Supabase database region
    text: 'Region: us-west-2 (Oregon).'
  - region: Outside Canada
    text: Most of these providers store or process data outside Canada, mainly in the United States
  retention:
  - period: null
    scope: Connected-tool data, forwarded email, logged invoices, agents
    text: while your plan is active, except where the next lines are shorter. When it ends, we keep them 30 days, then delete them.
  - period: 90 days
    scope: Forwarded email text and subject
    text: the text, subject, sender’s name, our short summary and the attachment list for 90 days
  - period: 180 days
    scope: 'Emails the agents send: text and subject'
    text: the text and subject for 180 days
  - period: as long as tax law requires
    scope: Billing records
    text: 'Billing records: as long as tax law requires (in Canada, generally six years).'
  rights:
  - right: Access, correction, deletion
    text: Write to admin@carragent.com to ask what personal information we hold about you, to get a copy, to correct it, to have it deleted or to withdraw your consent where the law allows.
  - right: Data portability
    text: In Quebec, Law 25 also gives you the right to data portability and to be told when a decision is based only on automated processing.
  - right: Complaint
    text: you can complain to the Office of the Privacy Commissioner of Canada or, in Quebec, to the Commission d’accès à l’information.
  role:
    text: 'Controller: for information about you as our customer or visitor (your account, billing, the AI diagnosis, emails you send us and site data), we decide how it is used, and this notice applies directly.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information and do not use it for advertising.
  subprocessors:
    text: 'Supabase: database (including the email your business forwards and the invoices the agents log), sign-in, file storage and encrypted token storage (Vault).'
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on the providers’ data protection terms, including standard contractual clauses where they apply.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: carragent-com
provenance_date: '2026-11-09'
provider_name: carragent-com
provider_slug: carragent-com
slug: carragent-com-privacy-policy
source_date: '2026-11-09'
source_filename: carragent-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carragent.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: carragent-com\naid: carragent-com\nurl: https://carragent.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Controller: for information about you as our customer or visitor (your account, billing, the AI diagnosis,\n    emails you send us and site data), we decide how it is used, and this notice applies directly.'\ndata_categories:\n- category: identifying\n  text: 'Account: your name, email, business name, role, language and time zone'\n- category: financial\n  text: 'Billing: your plan, subscription status and invoices, and the billing details needed for invoices and tax.'\n- category:\
  \ communication\n  text: 'Forwarded email: for the Front desk and Supplier invoices agents, the messages your business forwards to\n    its own Carragent addresses'\n- category: device\n  text: 'Technical data: IP address and browser details, to keep the service secure and fix errors.'\npurposes:\n- purpose: Run account and features\n  text: 'To run your account and the features your business turns on: syncing your tools, reading the email it forwards,\n    preparing and sending the messages you approve or your rules allow'\n- purpose: Billing and tax records\n  text: To bill you and keep the records that tax law requires.\n- purpose: Partner program\n  text: 'To run the partner program: credit the partner who referred a business when it makes its first payment,\n    and pay them through Stripe or PayPal.'\n- purpose: Security\n  text: To keep the service secure, prevent abuse and fix problems.\nretention:\n- scope: Connected-tool data, forwarded email, logged invoices, agents\n  period:\
  \ null\n  text: while your plan is active, except where the next lines are shorter. When it ends, we keep them 30 days,\n    then delete them.\n- scope: Forwarded email text and subject\n  period: 90 days\n  text: the text, subject, sender’s name, our short summary and the attachment list for 90 days\n- scope: 'Emails the agents send: text and subject'\n  period: 180 days\n  text: the text and subject for 180 days\n- scope: Billing records\n  period: as long as tax law requires\n  text: 'Billing records: as long as tax law requires (in Canada, generally six years).'\nresidency:\n- region: Supabase database region\n  text: 'Region: us-west-2 (Oregon).'\n- region: Outside Canada\n  text: Most of these providers store or process data outside Canada, mainly in the United States\ntransfers:\n- mechanism: SCC\n  text: We rely on the providers’ data protection terms, including standard contractual clauses where they apply.\nsubprocessors:\n  url: null\n  text: 'Supabase: database (including the\
  \ email your business forwards and the invoices the agents log), sign-in,\n    file storage and encrypted token storage (Vault).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to admin@carragent.com\n  text: Write to admin@carragent.com to ask what personal information we hold about you, to get a copy, to correct\n    it, to have it deleted or to withdraw your consent where the law allows.\nrights:\n- right: Access, correction, deletion\n  text: Write to admin@carragent.com to ask what personal information we hold about you, to get a copy, to correct\n    it, to have it deleted or to withdraw your consent where the law allows.\n- right: Data portability\n  text: In Quebec, Law 25 also gives you the right to data portability and to be told when a decision is based only\n    on automated processing.\n- right: Complaint\n  text: you can complain to the Office of the Privacy Commissioner of Canada or, in Quebec, to the Commission d’accès\n    à l’information.\n\
  sale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information and do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/carragent-com/privacy/carragent-com-privacy-policy.yml
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
summary_line: 22 quoted statements, read from carragent-com's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Business tools integration
---
