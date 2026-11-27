---
api_specs:
- filename: 0sand1s-co-uk-cis-api-openapi.yml
  format: yaml
  label: 0s and 1s CIS API
  slug: 0sand1s-co-uk-cis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0sand1s-co-uk/openapi/0sand1s-co-uk-cis-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: we keep the email address you sign in with
  - category: identifying
    text: 'For its subcontractors, we keep what you enter: names, trading names, UTRs, National Insurance numbers, company numbers, partnership details, VAT status and email addresses.'
  - category: device
    text: we keep a one-way hash of your IP address with that link, to stop the form being abused
  - category: financial
    text: If you choose a plan, we keep the customer and subscription references Stripe gives us.
  - category: communication
    text: If you email us, we keep that email and our reply.
  deletion:
    route: Delete the firm in Settings, or close your account in Settings
    text: A firm's records until you delete the firm in Settings, which removes them at once, or until your account is deleted.
  dpa:
    available: true
    text: our data processing agreement sets out how we process a firm's information
    url: null
  purposes:
  - purpose: run the service
    text: 'We use your account details to run the service you signed up for: sign-in links, billing and messages about your account.'
  - purpose: stop abuse
    text: We keep the IP address hashes because we have a legitimate interest in stopping abuse.
  - purpose: occasional updates
    text: If you joined the list, we use that address to send occasional updates about 0s and 1s.
  - purpose: subcontractor work
    text: 'We use subcontractor information only to do what the firm asks: verify subcontractors, work out deductions, file returns and send statements.'
  residency:
  - region: EU (Ireland)
    text: This information is stored in a database hosted by Supabase in the EU (Ireland), encrypted at rest and in transit.
  retention:
  - period: up to 2 days
    scope: demo and its IP hash
    text: The demo, and its IP address hash, for up to 2 days.
  - period: null
    scope: firm records
    text: A firm's records until you delete the firm in Settings, which removes them at once, or until your account is deleted.
  - period: 30 days
    scope: closed account
    text: 30 days later we delete the account, every firm in it, and your sign-in links.
  rights:
  - right: access
    text: You can ask for a copy of what we hold about you
  - right: correction or erasure
    text: ask us to correct or delete it
  - right: objection
    text: or object to how we use it
  - right: withdraw consent
    text: You can withdraw it at any time by replying "stop" to any email from us
  - right: complaint
    text: you can complain to the Information Commissioner's Office at ico.org.uk
  role:
    text: 'We are the data controller for your account: your email address, your plan and how you sign in. For the information a firm enters about its subcontractors, the firm is the controller and we process it on the firm''s behalf, under our terms .'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any of it, or share it with anyone else.
  subprocessors:
    text: Our sub-processors page gives the safeguard for each provider, and our data processing agreement sets out how we process a firm's information.
    url: null
  transfers:
  - mechanism: other
    text: Where a provider handles data outside the UK, we rely on safeguards UK law accepts, such as the UK addendum to the EU standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 0s and 1s
provenance_date: '2026-11-09'
provider_name: 0s and 1s
provider_slug: 0sand1s-co-uk
slug: 0sand1s-co-uk-privacy-policy
source_date: '2026-11-09'
source_filename: 0sand1s-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://0sand1s.co.uk/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 0s and 1s\naid: 0sand1s-co-uk\nurl: https://0sand1s.co.uk/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'We are the data controller for your account: your email address, your plan and how you sign in. For the\n    information a firm enters about its subcontractors, the firm is the controller and we process it on the firm''s\n    behalf, under our terms .'\ndata_categories:\n- category: contact\n  text: we keep the email address you sign in with\n- category: identifying\n  text: 'For its subcontractors, we keep what you enter: names, trading names, UTRs, National Insurance numbers,\n   \
  \ company numbers, partnership details, VAT status and email addresses.'\n- category: device\n  text: we keep a one-way hash of your IP address with that link, to stop the form being abused\n- category: financial\n  text: If you choose a plan, we keep the customer and subscription references Stripe gives us.\n- category: communication\n  text: If you email us, we keep that email and our reply.\npurposes:\n- purpose: run the service\n  text: 'We use your account details to run the service you signed up for: sign-in links, billing and messages about\n    your account.'\n- purpose: stop abuse\n  text: We keep the IP address hashes because we have a legitimate interest in stopping abuse.\n- purpose: occasional updates\n  text: If you joined the list, we use that address to send occasional updates about 0s and 1s.\n- purpose: subcontractor work\n  text: 'We use subcontractor information only to do what the firm asks: verify subcontractors, work out deductions,\n    file returns and send statements.'\n\
  retention:\n- scope: demo and its IP hash\n  period: up to 2 days\n  text: The demo, and its IP address hash, for up to 2 days.\n- scope: firm records\n  period: null\n  text: A firm's records until you delete the firm in Settings, which removes them at once, or until your account\n    is deleted.\n- scope: closed account\n  period: 30 days\n  text: 30 days later we delete the account, every firm in it, and your sign-in links.\nresidency:\n- region: EU (Ireland)\n  text: This information is stored in a database hosted by Supabase in the EU (Ireland), encrypted at rest and in\n    transit.\ntransfers:\n- mechanism: other\n  text: Where a provider handles data outside the UK, we rely on safeguards UK law accepts, such as the UK addendum\n    to the EU standard contractual clauses.\nsubprocessors:\n  url: null\n  text: Our sub-processors page gives the safeguard for each provider, and our data processing agreement sets out\n    how we process a firm's information.\ndpa:\n  available: true\n\
  \  url: null\n  text: our data processing agreement sets out how we process a firm's information\ndeletion:\n  route: Delete the firm in Settings, or close your account in Settings\n  text: A firm's records until you delete the firm in Settings, which removes them at once, or until your account\n    is deleted.\nrights:\n- right: access\n  text: You can ask for a copy of what we hold about you\n- right: correction or erasure\n  text: ask us to correct or delete it\n- right: objection\n  text: or object to how we use it\n- right: withdraw consent\n  text: You can withdraw it at any time by replying \"stop\" to any email from us\n- right: complaint\n  text: you can complain to the Information Commissioner's Office at ico.org.uk\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any of it, or share it with anyone else.\n"
source_yaml_url: https://artifacts.apis.io/0sand1s-co-uk/privacy/0sand1s-co-uk-privacy-policy.yml
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
summary_line: 24 quoted statements, read from 0s and 1s's own page on 2026-11-09.
synthetic: false
tags:
- Construction
- Payroll
- Tax
- United Kingdom
- Software
- CIS
---
