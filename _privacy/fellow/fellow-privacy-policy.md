---
api_specs:
- filename: fellow-action-items-api-openapi.yml
  format: yaml
  label: Fellow Action Items API
  slug: fellow-action-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-action-items-api-openapi.yml
- filename: fellow-notes-api-openapi.yml
  format: yaml
  label: Fellow Notes API
  slug: fellow-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-notes-api-openapi.yml
- filename: fellow-recordings-api-openapi.yml
  format: yaml
  label: Fellow Recordings API
  slug: fellow-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-recordings-api-openapi.yml
- filename: fellow-users-api-openapi.yml
  format: yaml
  label: Fellow Users API
  slug: fellow-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-users-api-openapi.yml
- filename: fellow-webhooks-api-openapi.yml
  format: yaml
  label: Fellow Webhooks API
  slug: fellow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fellow/openapi/fellow-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: We will store information such as your first name, last name, job title, department and email address.
  - category: contact
    text: We collect names, email addresses and other business contact information about individuals who represent our customers
  - category: behavioral
    text: 'Logs: We record some information from your interactions with our Services automatically in our logs.'
  - category: biometric
    text: Fellow offers automatic speaker labeling for hybrid and in-person meetings by collecting and processing voice samples from workspace users.
  - category: communication
    text: Communications within the @Fellow bot and metadata derived from such communications and OAuth Tokens.
  - category: device
    text: 'Servers: Our servers (hosted by Amazon Web Services) collect information including the type of browser and O/S you use, your IP Address'
  deletion:
    route: Request via contact email or user settings
    text: You may contact us at [email protected] in order to request a copy, change or delete any Personal Data that we have on file for your Account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide tailored experience and respond to requests
    text: In general, we use the Personal Data we have about you to offer you a more tailored experience and to respond to any requests you send us in a more comprehensive fashion.
  - purpose: Marketing with consent
    text: Send marketing-related messages to our Services with your consent (from which you will be able to unsubscribe).
  - purpose: Analytics to improve Services
    text: We use Anonymized Platform Usage Data retrieved from our database
  residency:
  - region: Primary data center
    text: Voice samples are encrypted and stored securely in our primary data center using industry-standard security protocols.
  retention:
  - period: null
    scope: Biometric data
    text: We retain biometric data only for the duration of a user's active engagement with Fellow's Services.
  - period: 15 days
    scope: Deleted account information
    text: We will delete this information within 15 days of your request.
  - period: up to an additional 30 days
    scope: Backup servers
    text: Your information may stay on our backup servers for up to an additional 30 days but will no longer be present thereafter.
  rights:
  - right: access
    text: the right to request access to, obtain, correct, amend, delete, or limit the use of your Personal Data
  - right: withdraw consent
    text: If you have given us consent to process your personal data, you may withdraw this consent at any time.
  - right: object
    text: you have the right to object to the processing of personal data concerning you at any time on grounds relating to your particular situation
  - right: lodge complaint
    text: You also have the right to lodge a complaint with a supervisory authority.
  role:
    text: When Fellow processes data on behalf of Organizations as part of an agreement, Fellow acts as a “data processor,” while the Organization is the “data controller.”
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A full list of our sub-processors, including our AI sub-processors, is available here .
    url: https://fellow.ai/privacy-policy
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) adopted by the European Commission or the UK International Data Transfer Agreement/Addendum, as applicable (Art. 46 GDPR)
  - mechanism: adequacy
    text: Adequacy decisions issued by the European Commission (Art. 45 GDPR)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fellow
provenance_date: '2026-11-09'
provider_name: Fellow
provider_slug: fellow
slug: fellow-privacy-policy
source_date: '2026-11-09'
source_filename: fellow-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fellow.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fellow\naid: fellow\nurl: https://fellow.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When Fellow processes data on behalf of Organizations as part of an agreement, Fellow acts as a “data processor,”\n    while the Organization is the “data controller.”\ndata_categories:\n- category: identifying\n  text: We will store information such as your first name, last name, job title, department and email address.\n- category: contact\n  text: We collect names, email addresses and other business contact information about individuals who represent\n    our customers\n- category: behavioral\n\
  \  text: 'Logs: We record some information from your interactions with our Services automatically in our logs.'\n- category: biometric\n  text: Fellow offers automatic speaker labeling for hybrid and in-person meetings by collecting and processing\n    voice samples from workspace users.\n- category: communication\n  text: Communications within the @Fellow bot and metadata derived from such communications and OAuth Tokens.\n- category: device\n  text: 'Servers: Our servers (hosted by Amazon Web Services) collect information including the type of browser\n    and O/S you use, your IP Address'\npurposes:\n- purpose: Provide tailored experience and respond to requests\n  text: In general, we use the Personal Data we have about you to offer you a more tailored experience and to respond\n    to any requests you send us in a more comprehensive fashion.\n- purpose: Marketing with consent\n  text: Send marketing-related messages to our Services with your consent (from which you will be able to\
  \ unsubscribe).\n- purpose: Analytics to improve Services\n  text: We use Anonymized Platform Usage Data retrieved from our database\nretention:\n- scope: Biometric data\n  period: null\n  text: We retain biometric data only for the duration of a user's active engagement with Fellow's Services.\n- scope: Deleted account information\n  period: 15 days\n  text: We will delete this information within 15 days of your request.\n- scope: Backup servers\n  period: up to an additional 30 days\n  text: Your information may stay on our backup servers for up to an additional 30 days but will no longer be present\n    thereafter.\nresidency:\n- region: Primary data center\n  text: Voice samples are encrypted and stored securely in our primary data center using industry-standard security\n    protocols.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) adopted by the European Commission or the UK International Data Transfer\n    Agreement/Addendum, as applicable (Art. 46 GDPR)\n\
  - mechanism: adequacy\n  text: Adequacy decisions issued by the European Commission (Art. 45 GDPR)\nsubprocessors:\n  url: https://fellow.ai/privacy-policy\n  text: A full list of our sub-processors, including our AI sub-processors, is available here .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via contact email or user settings\n  text: You may contact us at [email protected] in order to request a copy, change or delete any Personal Data that\n    we have on file for your Account.\nrights:\n- right: access\n  text: the right to request access to, obtain, correct, amend, delete, or limit the use of your Personal Data\n- right: withdraw consent\n  text: If you have given us consent to process your personal data, you may withdraw this consent at any time.\n- right: object\n  text: you have the right to object to the processing of personal data concerning you at any time on grounds relating\n    to your particular situation\n- right: lodge complaint\n\
  \  text: You also have the right to lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fellow/privacy/fellow-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Fellow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Meetings
- Artificial Intelligence
- Meeting Notes
- Transcription
- Productivity
- Action Items
- Webhook
- MCP
---
