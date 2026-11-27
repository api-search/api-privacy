---
api_specs:
- filename: odilelabs-com-account-api-openapi.yml
  format: yaml
  label: odilelabs-com Account API
  slug: odilelabs-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odilelabs-com/openapi/odilelabs-com-account-api-openapi.yml
- filename: odilelabs-com-lines-api-openapi.yml
  format: yaml
  label: odilelabs-com Lines API
  slug: odilelabs-com-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odilelabs-com/openapi/odilelabs-com-lines-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: When a caller reaches a number we operate for a business, we receive the caller's phone number, a transcript of the conversation, and any message, name, or callback number the caller gives.
  - category: financial
    text: Payment for the diagnostic goes through our payment processor; we never see a card number.
  - category: identifying
    text: If you sign up for a product we hold the business name, your email address, your phone number, and your business hours
  - category: behavioral
    text: It sets a cookie in your browser and records the page you viewed, the link that sent you and a coarse location from your IP address.
  - category: communication
    text: If we email you and you reply, that correspondence sits in our company mailbox.
  deletion:
    route: Email hello@odilelabs.com to request deletion
    text: Write to hello@odilelabs.com and ask for a copy of what we hold about you, or ask us to delete it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the receptionist for the business
    text: That data exists so the business owner can read what their callers wanted.
  - purpose: Measure and retarget Meta ads
    text: We use it to measure and retarget Meta ads.
  - purpose: Conversion measurement for ads
    text: We use this Google tag for conversion measurement.
  residency:
  - region: United States
    text: The documents and the findings are stored on our own server in the United States
  retention:
  - period: 90 days
    scope: Call records, audio and transcripts
    text: We keep call records, audio and transcripts for 90 days and the messages themselves for up to twelve months, then delete them.
  - period: 30 days
    scope: Gate audit log on Free plan
    text: The audit log is kept 30 days on the Free plan and 365 days on Pro, then deleted
  - period: up to 400 days
    scope: Meeting Notes record and transcript
    text: We keep the meeting record, its transcript and the recap for up to 400 days.
  - period: up to two years
    scope: Business automation inquiries
    text: These records are held with our hosting provider for up to two years
  rights:
  - right: Access copy
    text: Write to hello@odilelabs.com and ask for a copy of what we hold about you, or ask us to delete it.
  - right: Correction, deletion, export and objection (Gate, GDPR)
    text: You can ask for a copy of it, a correction, deletion, or an export, and object to how we use it, by writing to hello@odilelabs.com
  - right: Complain to data protection authority
    text: You can also complain to your data protection authority.
  role:
    text: Odile Labs (OdileUSA L.L.C.) is a Florida company founded by Tolga Coskun.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not use call transcripts or customer data to train models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: odilelabs-com
provenance_date: '2026-11-10'
provider_name: odilelabs-com
provider_slug: odilelabs-com
slug: odilelabs-com-privacy-policy
source_date: '2026-11-10'
source_filename: odilelabs-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://odilelabs.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: odilelabs-com\naid: odilelabs-com\nurl: https://odilelabs.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Odile Labs (OdileUSA L.L.C.) is a Florida company founded by Tolga Coskun.\ndata_categories:\n- category: contact\n  text: When a caller reaches a number we operate for a business, we receive the caller's phone number, a transcript\n    of the conversation, and any message, name, or callback number the caller gives.\n- category: financial\n  text: Payment for the diagnostic goes through our payment processor; we never see a card number.\n- category: identifying\n  text: If you\
  \ sign up for a product we hold the business name, your email address, your phone number, and your\n    business hours\n- category: behavioral\n  text: It sets a cookie in your browser and records the page you viewed, the link that sent you and a coarse location\n    from your IP address.\n- category: communication\n  text: If we email you and you reply, that correspondence sits in our company mailbox.\npurposes:\n- purpose: Operate the receptionist for the business\n  text: That data exists so the business owner can read what their callers wanted.\n- purpose: Measure and retarget Meta ads\n  text: We use it to measure and retarget Meta ads.\n- purpose: Conversion measurement for ads\n  text: We use this Google tag for conversion measurement.\nretention:\n- scope: Call records, audio and transcripts\n  period: 90 days\n  text: We keep call records, audio and transcripts for 90 days and the messages themselves for up to twelve months,\n    then delete them.\n- scope: Gate audit log on Free\
  \ plan\n  period: 30 days\n  text: The audit log is kept 30 days on the Free plan and 365 days on Pro, then deleted\n- scope: Meeting Notes record and transcript\n  period: up to 400 days\n  text: We keep the meeting record, its transcript and the recap for up to 400 days.\n- scope: Business automation inquiries\n  period: up to two years\n  text: These records are held with our hosting provider for up to two years\nresidency:\n- region: United States\n  text: The documents and the findings are stored on our own server in the United States\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@odilelabs.com to request deletion\n  text: Write to hello@odilelabs.com and ask for a copy of what we hold about you, or ask us to delete it.\nrights:\n- right: Access copy\n  text: Write to hello@odilelabs.com and ask for a copy of what we hold about you, or ask us to delete it.\n- right: Correction, deletion,\
  \ export and objection (Gate, GDPR)\n  text: You can ask for a copy of it, a correction, deletion, or an export, and object to how we use it, by writing\n    to hello@odilelabs.com\n- right: Complain to data protection authority\n  text: You can also complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not use call transcripts or customer data to train models.\n"
source_yaml_url: https://artifacts.apis.io/odilelabs-com/privacy/odilelabs-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from odilelabs-com's own page on 2026-11-10.
synthetic: false
tags:
- Communication Infrastructure
- AI Receptionist
- Phone Answering
- Developer API
---
