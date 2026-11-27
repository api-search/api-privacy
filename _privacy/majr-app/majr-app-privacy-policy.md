---
api_specs:
- filename: majr-app-audit-api-openapi.yml
  format: yaml
  label: majr-app Audit API
  slug: majr-app-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-audit-api-openapi.yml
- filename: majr-app-discovery-api-openapi.yml
  format: yaml
  label: majr-app Discovery API
  slug: majr-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-discovery-api-openapi.yml
- filename: majr-app-drafting-api-openapi.yml
  format: yaml
  label: majr-app Drafting API
  slug: majr-app-drafting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-drafting-api-openapi.yml
- filename: majr-app-encode-api-openapi.yml
  format: yaml
  label: majr-app Encode API
  slug: majr-app-encode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-encode-api-openapi.yml
- filename: majr-app-generation-api-openapi.yml
  format: yaml
  label: majr-app Generation API
  slug: majr-app-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-generation-api-openapi.yml
- filename: majr-app-healthz-api-openapi.yml
  format: yaml
  label: majr-app Healthz API
  slug: majr-app-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-healthz-api-openapi.yml
- filename: majr-app-jobs-api-openapi.yml
  format: yaml
  label: majr-app Jobs API
  slug: majr-app-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-jobs-api-openapi.yml
- filename: majr-app-uploads-api-openapi.yml
  format: yaml
  label: majr-app Uploads API
  slug: majr-app-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-uploads-api-openapi.yml
- filename: majr-app-usage-api-openapi.yml
  format: yaml
  label: majr-app Usage API
  slug: majr-app-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-usage-api-openapi.yml
- filename: majr-app-voice-api-openapi.yml
  format: yaml
  label: majr-app Voice API
  slug: majr-app-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/majr-app/openapi/majr-app-voice-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, which our sign-in service (majr-identity, hosted by Supabase) uses to email you a one-time code
  - category: other
    text: Service Data — the inputs your agents send (prompts, text, media, files, URLs, records) and the outputs we return.
  - category: device
    text: Error reports — the type and stack trace of a failure.
  - category: behavioral
    text: 'Usage analytics — counts and identifiers only: which capability ran, over which interface, how long it took, whether it succeeded.'
  deletion:
    route: Email support@majr.app
    text: Email support@majr.app to exercise a right.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Route and fulfil agent requests
    text: Route and fulfil the requests your agents make
  - purpose: Sign-in and API keys
    text: Sign you in by email and issue the API keys you ask for
  - purpose: Abuse and security
    text: Detect and prevent abuse, fraud, and security incidents
  - purpose: Aggregate usage measurement
    text: Measure aggregate usage to decide what to build next
  - purpose: Marketing email
    text: Send marketing email
  residency:
  - region: United States
    text: We process data in the United States.
  retention:
  - period: 72 hours after upload
    scope: Media uploaded for encoding
    text: Deleted 72 hours after upload
  - period: 7 days
    scope: Failed encoding job snapshots
    text: Snapshots of a failed encoding job, kept to diagnose it 7 days
  - period: 90 days
    scope: Error reports
    text: Error reports 90 days
  - period: Until you ask us to delete your account
    scope: Sign-in identity
    text: Your sign-in identity (email address) at majr-identity Until you ask us to delete your account
  - period: Until you ask us to delete it
    scope: Access-request contact record
    text: Access-request contact record Until you ask us to delete it
  - period: about ten days
    scope: Database backups
    text: Deleted records survive in backups until they roll off the hosting platform’s rotation, a window of about ten days
  rights:
  - right: access, correction, deletion, export, restriction
    text: Depending on where you live, you can ask us to give you a copy of your personal data, correct it, delete it, export it, or restrict how we process it.
  - right: objection and withdrawal of consent
    text: You can object to processing we base on legitimate interests, and withdraw any consent you have given.
  role:
    text: We are the controller for information about people who visit majr.app or sign in to get an API key.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information
  subprocessors:
    text: Fly.io Application and API hosting United States Yes
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers out of the EEA, the UK, or Switzerland we rely on the European Commission’s Standard Contractual Clauses and the UK Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: majr-app
provenance_date: '2026-11-10'
provider_name: majr-app
provider_slug: majr-app
slug: majr-app-privacy-policy
source_date: '2026-11-10'
source_filename: majr-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://majr.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: majr-app\naid: majr-app\nurl: https://majr.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for information about people who visit majr.app or sign in to get an API key.\ndata_categories:\n- category: contact\n  text: Your email address, which our sign-in service (majr-identity, hosted by Supabase) uses to email you a one-time\n    code\n- category: other\n  text: Service Data — the inputs your agents send (prompts, text, media, files, URLs, records) and the outputs\n    we return.\n- category: device\n  text: Error reports — the type and stack trace of a failure.\n\
  - category: behavioral\n  text: 'Usage analytics — counts and identifiers only: which capability ran, over which interface, how long it\n    took, whether it succeeded.'\npurposes:\n- purpose: Route and fulfil agent requests\n  text: Route and fulfil the requests your agents make\n- purpose: Sign-in and API keys\n  text: Sign you in by email and issue the API keys you ask for\n- purpose: Abuse and security\n  text: Detect and prevent abuse, fraud, and security incidents\n- purpose: Aggregate usage measurement\n  text: Measure aggregate usage to decide what to build next\n- purpose: Marketing email\n  text: Send marketing email\nretention:\n- scope: Media uploaded for encoding\n  period: 72 hours after upload\n  text: Deleted 72 hours after upload\n- scope: Failed encoding job snapshots\n  period: 7 days\n  text: Snapshots of a failed encoding job, kept to diagnose it 7 days\n- scope: Error reports\n  period: 90 days\n  text: Error reports 90 days\n- scope: Sign-in identity\n  period: Until\
  \ you ask us to delete your account\n  text: Your sign-in identity (email address) at majr-identity Until you ask us to delete your account\n- scope: Access-request contact record\n  period: Until you ask us to delete it\n  text: Access-request contact record Until you ask us to delete it\n- scope: Database backups\n  period: about ten days\n  text: Deleted records survive in backups until they roll off the hosting platform’s rotation, a window of about\n    ten days\nresidency:\n- region: United States\n  text: We process data in the United States.\ntransfers:\n- mechanism: SCC\n  text: For transfers out of the EEA, the UK, or Switzerland we rely on the European Commission’s Standard Contractual\n    Clauses and the UK Addendum\nsubprocessors:\n  url: null\n  text: Fly.io Application and API hosting United States Yes\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@majr.app\n  text: Email support@majr.app to exercise a right.\nrights:\n- right: access,\
  \ correction, deletion, export, restriction\n  text: Depending on where you live, you can ask us to give you a copy of your personal data, correct it, delete\n    it, export it, or restrict how we process it.\n- right: objection and withdrawal of consent\n  text: You can object to processing we base on legitimate interests, and withdraw any consent you have given.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information\n"
source_yaml_url: https://artifacts.apis.io/majr-app/privacy/majr-app-privacy-policy.yml
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
summary_line: 23 quoted statements, read from majr-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Media
- SEO
- Encoding
- Agent Services
---
