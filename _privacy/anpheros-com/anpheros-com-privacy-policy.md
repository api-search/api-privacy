---
api_specs:
- filename: anpheros-com-access-requests-api-openapi.yml
  format: yaml
  label: anpheros-com Access requests API
  slug: anpheros-com-access-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-access-requests-api-openapi.yml
- filename: anpheros-com-admin-api-openapi.yml
  format: yaml
  label: anpheros-com Admin API
  slug: anpheros-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-admin-api-openapi.yml
- filename: anpheros-com-anpheros-search-api-openapi.yml
  format: yaml
  label: anpheros-com Anpheros Search API
  slug: anpheros-com-anpheros-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-anpheros-search-api-openapi.yml
- filename: anpheros-com-fhir-r4-api-openapi.yml
  format: yaml
  label: anpheros-com FHIR R4 API
  slug: anpheros-com-fhir-r4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-fhir-r4-api-openapi.yml
- filename: anpheros-com-icd-10-to-icd-11-api-openapi.yml
  format: yaml
  label: anpheros-com ICD-10 to ICD-11 API
  slug: anpheros-com-icd-10-to-icd-11-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-icd-10-to-icd-11-api-openapi.yml
- filename: anpheros-com-oauth-api-openapi.yml
  format: yaml
  label: anpheros-com OAuth API
  slug: anpheros-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-oauth-api-openapi.yml
- filename: anpheros-com-patient-me-api-openapi.yml
  format: yaml
  label: anpheros-com Patient (me) API
  slug: anpheros-com-patient-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-patient-me-api-openapi.yml
- filename: anpheros-com-rest-v1-api-openapi.yml
  format: yaml
  label: anpheros-com REST v1 API
  slug: anpheros-com-rest-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-rest-v1-api-openapi.yml
- filename: anpheros-com-smart-health-links-api-openapi.yml
  format: yaml
  label: anpheros-com SMART Health Links API
  slug: anpheros-com-smart-health-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-smart-health-links-api-openapi.yml
- filename: anpheros-com-webhooks-api-openapi.yml
  format: yaml
  label: anpheros-com Webhooks API
  slug: anpheros-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anpheros-com/openapi/anpheros-com-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: health
    text: 'Anpheros Daily keeps your medical record: symptoms, measurements, weight, sleep, activity, medications, lab results, documents, vaccines, conditions, appointments, pregnancy, the emergency card, the profiles of your family members.'
  - category: identifying
    text: Email address, name, profile photo (optional), authentication identifier, chosen language and country, subscription plan, devices linked to the account.
  - category: location
    text: your device language and the country you connected from, derived from your connection by Cloudflare at that moment (the IP address is not kept for this).
  - category: device
    text: Server logs (IP address, time, request path, response code, internal identifiers), with no medical content.
  deletion:
    route: Settings › Profile › Delete account
    text: 'When you delete the account (Settings › Profile › Delete account): the account is locked immediately'
  dpa:
    available: true
    text: All processors are bound by data processing agreements under Article 28 GDPR.
    url: null
  purposes:
  - purpose: Keep medical record and show it to you
    text: To keep your and your family's medical record and show it to you in the app
  - purpose: AI assistant answers
    text: To answer your questions through the AI assistant and extract values from scanned documents
  - purpose: Account emails
    text: To send account emails (confirmation, password reset, important changes)
  - purpose: Newsletter
    text: To send you the newsletter
  residency:
  - region: Netherlands (europe-west4)
    text: 'Hosting: Google Cloud, region europe-west4 (Netherlands): servers, database (Cloud SQL) and files (Cloud Storage), encrypted at rest and in transit.'
  retention:
  - period: null
    scope: Account data while account active
    text: For as long as you have an account.
  - period: 90 days
    scope: Account deletion
    text: 'For 90 days you can change your mind: signing in again cancels the request.'
  - period: 3 years
    scope: Access log
    text: The access log (who opened what, when) is kept for 3 years and then deleted
  - period: 8 days
    scope: Backups
    text: deleted data leaves our backups within 8 days
  - period: 30 days
    scope: Technical logs
    text: Technical logs are kept for 30 days.
  rights:
  - right: Access
    text: Access, rectification, erasure, restriction, portability (PDF export or HL7 FHIR format from the app), objection, withdrawal of consent and a complaint to the Romanian supervisory authority
  - right: Portability
    text: portability (PDF export or HL7 FHIR format from the app)
  - right: Objection
    text: objection, withdrawal of consent
  role:
    text: 'Controller: Adrian Kereky, a natural person, Romania (until the company that will take over the service is incorporated; the change will be announced here).'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not use your data for advertising, do not sell it and do not build marketing profiles.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'Accounts in other countries: the AI features use Google''s global service, which may run the request in any Google data centre worldwide; these transfers are covered by Google''s standard contractual clauses.'
  - mechanism: DPF
    text: data may be transferred to Google LLC in the United States under the EU–US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: anpheros-com
provenance_date: '2026-11-09'
provider_name: anpheros-com
provider_slug: anpheros-com
slug: anpheros-com-privacy-policy
source_date: '2026-11-09'
source_filename: anpheros-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anpheros.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: anpheros-com\naid: anpheros-com\nurl: https://anpheros.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller: Adrian Kereky, a natural person, Romania (until the company that will take over the service\n    is incorporated; the change will be announced here).'\ndata_categories:\n- category: health\n  text: 'Anpheros Daily keeps your medical record: symptoms, measurements, weight, sleep, activity, medications,\n    lab results, documents, vaccines, conditions, appointments, pregnancy, the emergency card, the profiles of your\n    family members.'\n- category: identifying\n\
  \  text: Email address, name, profile photo (optional), authentication identifier, chosen language and country, subscription\n    plan, devices linked to the account.\n- category: location\n  text: your device language and the country you connected from, derived from your connection by Cloudflare at that\n    moment (the IP address is not kept for this).\n- category: device\n  text: Server logs (IP address, time, request path, response code, internal identifiers), with no medical content.\npurposes:\n- purpose: Keep medical record and show it to you\n  text: To keep your and your family's medical record and show it to you in the app\n- purpose: AI assistant answers\n  text: To answer your questions through the AI assistant and extract values from scanned documents\n- purpose: Account emails\n  text: To send account emails (confirmation, password reset, important changes)\n- purpose: Newsletter\n  text: To send you the newsletter\nretention:\n- scope: Account data while account active\n\
  \  period: null\n  text: For as long as you have an account.\n- scope: Account deletion\n  period: 90 days\n  text: 'For 90 days you can change your mind: signing in again cancels the request.'\n- scope: Access log\n  period: 3 years\n  text: The access log (who opened what, when) is kept for 3 years and then deleted\n- scope: Backups\n  period: 8 days\n  text: deleted data leaves our backups within 8 days\n- scope: Technical logs\n  period: 30 days\n  text: Technical logs are kept for 30 days.\nresidency:\n- region: Netherlands (europe-west4)\n  text: 'Hosting: Google Cloud, region europe-west4 (Netherlands): servers, database (Cloud SQL) and files (Cloud\n    Storage), encrypted at rest and in transit.'\ntransfers:\n- mechanism: SCC\n  text: 'Accounts in other countries: the AI features use Google''s global service, which may run the request in\n    any Google data centre worldwide; these transfers are covered by Google''s standard contractual clauses.'\n- mechanism: DPF\n  text: data\
  \ may be transferred to Google LLC in the United States under the EU–US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: All processors are bound by data processing agreements under Article 28 GDPR.\ndeletion:\n  route: Settings › Profile › Delete account\n  text: 'When you delete the account (Settings › Profile › Delete account): the account is locked immediately'\nrights:\n- right: Access\n  text: Access, rectification, erasure, restriction, portability (PDF export or HL7 FHIR format from the app), objection,\n    withdrawal of consent and a complaint to the Romanian supervisory authority\n- right: Portability\n  text: portability (PDF export or HL7 FHIR format from the app)\n- right: Objection\n  text: objection, withdrawal of consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use your data for advertising, do not sell it and do not build marketing profiles.\n"
source_yaml_url: https://artifacts.apis.io/anpheros-com/privacy/anpheros-com-privacy-policy.yml
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
- sale_or_sharing
summary_line: 23 quoted statements, read from anpheros-com's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Digital Health
- FHIR
- Medical Records
---
