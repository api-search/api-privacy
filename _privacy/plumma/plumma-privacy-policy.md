---
api_specs:
- filename: plumma-connect-api-openapi.yml
  format: yaml
  label: Plumma CONNECT API
  slug: plumma-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plumma/openapi/plumma-connect-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Those fields are your name, your company, your work email address, optionally your role
  - category: communication
    text: your message, and optionally the name of the person who will read the coverage report.
  - category: behavioral
    text: the pages you view, the site you came from
  - category: location
    text: your approximate location
  - category: device
    text: your browser and device
  deletion:
    route: Write to legal (at) plumma (dot) it
    text: If you ask us to delete your enquiry before then, we will, unless we are required to keep it.
  dpa:
    available: true
    text: AWS acts as our processor under a data processing agreement.
    url: null
  purposes:
  - purpose: Respond to enquiries
    text: You asked us to get in touch about a commercial relationship, so the basis is article 6.1.b of the GDPR
  - purpose: Keep site available and investigate abuse
    text: We use this to keep the site available and to investigate abuse
  - purpose: Website analytics with consent
    text: With your consent we use Google Analytics to count which pages are read.
  residency:
  - region: European Union
    text: The site is stored in the European Union.
  retention:
  - period: a short operational period
    scope: Request logs
    text: Request logs are kept for a short operational period and then discarded.
  - period: fourteen months
    scope: Analytics data
    text: Analytics data , if you accept it, is kept by Google for fourteen months and then deleted.
  - period: six months
    scope: Consent answer in browser
    text: The note of your answer in your browser is kept for six months, after which the notice asks again.
  - period: twenty-four months
    scope: Enquiries and correspondence
    text: Enquiries and the correspondence that follows are kept for twenty-four months from the last message
  rights:
  - right: Access
    text: give you a copy of the personal data we hold about you
  - right: Rectification
    text: correct it where it is wrong
  - right: Erasure
    text: delete it
  - right: Restriction
    text: restrict what we do with it while a question about it is resolved
  - right: Portability
    text: give you, or another provider, a portable copy of what you gave us
  - right: Objection
    text: stop processing it where we rely on legitimate interest, by objecting
  - right: Withdraw consent
    text: withdraw your consent to analytics at any time
  role:
    text: The controller is Plumma S.r.l., a company incorporated in Italy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, we do not share it for advertising, and we pay nobody for access to it.
  subprocessors:
    text: We use Amazon Web Services EMEA SARL to host and deliver this site.
    url: null
  transfers:
  - mechanism: SCC
    text: Where that happens, the transfer relies on the European Commission's standard contractual clauses together with the supplementary measures described in the relevant provider's documentation.
  - mechanism: DPF
    text: Where it does, the transfer relies on the European Commission's adequacy decision for the EU-US Data Privacy Framework, to the extent Google LLC is certified under it
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Plumma
provenance_date: '2026-11-10'
provider_name: Plumma
provider_slug: plumma
slug: plumma-privacy-policy
source_date: '2026-11-10'
source_filename: plumma-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.plumma.it/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Plumma\naid: plumma\nurl: https://www.plumma.it/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is Plumma S.r.l., a company incorporated in Italy\ndata_categories:\n- category: contact\n  text: Those fields are your name, your company, your work email address, optionally your role\n- category: communication\n  text: your message, and optionally the name of the person who will read the coverage report.\n- category: behavioral\n  text: the pages you view, the site you came from\n- category: location\n  text: your approximate location\n- category: device\n  text: your browser\
  \ and device\npurposes:\n- purpose: Respond to enquiries\n  text: You asked us to get in touch about a commercial relationship, so the basis is article 6.1.b of the GDPR\n- purpose: Keep site available and investigate abuse\n  text: We use this to keep the site available and to investigate abuse\n- purpose: Website analytics with consent\n  text: With your consent we use Google Analytics to count which pages are read.\nretention:\n- scope: Request logs\n  period: a short operational period\n  text: Request logs are kept for a short operational period and then discarded.\n- scope: Analytics data\n  period: fourteen months\n  text: Analytics data , if you accept it, is kept by Google for fourteen months and then deleted.\n- scope: Consent answer in browser\n  period: six months\n  text: The note of your answer in your browser is kept for six months, after which the notice asks again.\n- scope: Enquiries and correspondence\n  period: twenty-four months\n  text: Enquiries and the correspondence\
  \ that follows are kept for twenty-four months from the last message\nresidency:\n- region: European Union\n  text: The site is stored in the European Union.\ntransfers:\n- mechanism: SCC\n  text: Where that happens, the transfer relies on the European Commission's standard contractual clauses together\n    with the supplementary measures described in the relevant provider's documentation.\n- mechanism: DPF\n  text: Where it does, the transfer relies on the European Commission's adequacy decision for the EU-US Data Privacy\n    Framework, to the extent Google LLC is certified under it\nsubprocessors:\n  url: null\n  text: We use Amazon Web Services EMEA SARL to host and deliver this site.\ndpa:\n  available: true\n  url: null\n  text: AWS acts as our processor under a data processing agreement.\ndeletion:\n  route: Write to legal (at) plumma (dot) it\n  text: If you ask us to delete your enquiry before then, we will, unless we are required to keep it.\nrights:\n- right: Access\n  text:\
  \ give you a copy of the personal data we hold about you\n- right: Rectification\n  text: correct it where it is wrong\n- right: Erasure\n  text: delete it\n- right: Restriction\n  text: restrict what we do with it while a question about it is resolved\n- right: Portability\n  text: give you, or another provider, a portable copy of what you gave us\n- right: Objection\n  text: stop processing it where we rely on legitimate interest, by objecting\n- right: Withdraw consent\n  text: withdraw your consent to analytics at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, we do not share it for advertising, and we pay nobody for access to it.\n"
source_yaml_url: https://artifacts.apis.io/plumma/privacy/plumma-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Plumma's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- Network APIs
- Italy
- Europe
- GSMA Open Gateway
- CAMARA
- API Aggregator
- Fraud Prevention
- Identity Verification
- SIM Swap
- KYC
- Age Verification
- Number Verification
- Telco Intelligence
- Software Development
---
