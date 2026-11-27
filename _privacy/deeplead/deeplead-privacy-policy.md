---
api_specs:
- filename: deeplead-account-api-openapi.yml
  format: yaml
  label: Deeplead Account API
  slug: deeplead-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-account-api-openapi.yml
- filename: deeplead-businesses-api-openapi.yml
  format: yaml
  label: Deeplead Businesses API
  slug: deeplead-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-businesses-api-openapi.yml
- filename: deeplead-contacts-api-openapi.yml
  format: yaml
  label: Deeplead Contacts API
  slug: deeplead-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-contacts-api-openapi.yml
- filename: deeplead-deliverability-api-openapi.yml
  format: yaml
  label: Deeplead Deliverability API
  slug: deeplead-deliverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-deliverability-api-openapi.yml
- filename: deeplead-organizations-api-openapi.yml
  format: yaml
  label: Deeplead Organizations API
  slug: deeplead-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-organizations-api-openapi.yml
- filename: deeplead-persons-api-openapi.yml
  format: yaml
  label: Deeplead Persons API
  slug: deeplead-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeplead/openapi/deeplead-persons-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may hold your name, job title, seniority and role, your employer and its details
  - category: contact
    text: your work email address, business phone numbers (a direct dial, or a mobile number a source lists as a business contact)
  - category: professional
    text: professional or employment-related information from the sources listed above
  - category: location
    text: your work location (city, region, country)
  - category: communication
    text: the name, mobile number and message you provide, together with your consent choices
  deletion:
    route: Email privacy@deeplead.io, or use deeplead.io/opt-out to be removed from search
    text: To have every record we hold about you deleted, or to ask what we hold and where it came from, email privacy@deeplead.io . We answer within one month.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: B2B prospecting
    text: Our interest, and our customers' interest, is business-to-business prospecting and communication with people about their professional role.
  - purpose: Chat and SMS support
    text: Our team uses this information to answer enquiries, provide assistance and manage your communication preferences.
  - purpose: Marketing SMS with consent
    text: With your separate consent, Wagner Consulting UG (haftungsbeschränkt), operating as Deeplead, may send promotional texts about our services
  residency:
  - region: Outside the user's country including United States
    text: Data may be processed outside your country, including in the United States, under the safeguards required by law
  retention:
  - period: null
    scope: B2B database records
    text: while it is relevant for business outreach
  - period: null
    scope: Chat and SMS records
    text: We keep chat and SMS records for as long as needed for the conversation, our relationship with you, compliance and the resolution of disputes.
  - period: null
    scope: Google email and OAuth tokens
    text: for as long as your account is active on our platform OR until you specifically revoke access to your Google account
  - period: 30 days
    scope: Mobile app session
    text: the session expires after 30 days
  rights:
  - right: access, correction, deletion, restriction, portability
    text: you may request access, correction, deletion, restriction or portability of your personal information, object to processing, withdraw consent
  - right: object
    text: You can object at any time (Art. 21 GDPR).
  - right: opt out of sale or sharing
    text: to opt out of its sale or sharing.
  role:
    text: Deeplead is operated by Wagner Consulting UG (haftungsbeschränkt), Germany.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Making this data available to customers may count as "selling" or "sharing" personal information under California law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: under the safeguards required by law, such as the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Deeplead
provenance_date: '2026-11-09'
provider_name: Deeplead
provider_slug: deeplead
slug: deeplead-privacy-policy
source_date: '2026-11-09'
source_filename: deeplead-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.deeplead.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Deeplead\naid: deeplead\nurl: https://www.deeplead.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Deeplead is operated by Wagner Consulting UG (haftungsbeschränkt), Germany.\ndata_categories:\n- category: identifying\n  text: we may hold your name, job title, seniority and role, your employer and its details\n- category: contact\n  text: your work email address, business phone numbers (a direct dial, or a mobile number a source lists as a business\n    contact)\n- category: professional\n  text: professional or employment-related information from the sources listed above\n\
  - category: location\n  text: your work location (city, region, country)\n- category: communication\n  text: the name, mobile number and message you provide, together with your consent choices\npurposes:\n- purpose: B2B prospecting\n  text: Our interest, and our customers' interest, is business-to-business prospecting and communication with people\n    about their professional role.\n- purpose: Chat and SMS support\n  text: Our team uses this information to answer enquiries, provide assistance and manage your communication preferences.\n- purpose: Marketing SMS with consent\n  text: With your separate consent, Wagner Consulting UG (haftungsbeschränkt), operating as Deeplead, may send promotional\n    texts about our services\nretention:\n- scope: B2B database records\n  period: null\n  text: while it is relevant for business outreach\n- scope: Chat and SMS records\n  period: null\n  text: We keep chat and SMS records for as long as needed for the conversation, our relationship with you,\
  \ compliance\n    and the resolution of disputes.\n- scope: Google email and OAuth tokens\n  period: null\n  text: for as long as your account is active on our platform OR until you specifically revoke access to your Google\n    account\n- scope: Mobile app session\n  period: 30 days\n  text: the session expires after 30 days\nresidency:\n- region: Outside the user's country including United States\n  text: Data may be processed outside your country, including in the United States, under the safeguards required\n    by law\ntransfers:\n- mechanism: SCC\n  text: under the safeguards required by law, such as the EU Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@deeplead.io, or use deeplead.io/opt-out to be removed from search\n  text: To have every record we hold about you deleted, or to ask what we hold and where it came from, email privacy@deeplead.io\n    . We answer within\
  \ one month.\nrights:\n- right: access, correction, deletion, restriction, portability\n  text: you may request access, correction, deletion, restriction or portability of your personal information, object\n    to processing, withdraw consent\n- right: object\n  text: You can object at any time (Art. 21 GDPR).\n- right: opt out of sale or sharing\n  text: to opt out of its sale or sharing.\nsale_or_sharing:\n  stance: conditional\n  text: Making this data available to customers may count as \"selling\" or \"sharing\" personal information under California\n    law.\n"
source_yaml_url: https://artifacts.apis.io/deeplead/privacy/deeplead-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Deeplead's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lead Generation
- Cold Email
- Artificial Intelligence
- Sales Automation
---
