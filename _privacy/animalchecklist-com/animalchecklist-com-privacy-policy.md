---
api_specs:
- filename: animalchecklist-com-account-api-openapi.yml
  format: yaml
  label: animalchecklist-com Account API
  slug: animalchecklist-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-account-api-openapi.yml
- filename: animalchecklist-com-catalogue-api-openapi.yml
  format: yaml
  label: animalchecklist-com Catalogue API
  slug: animalchecklist-com-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-catalogue-api-openapi.yml
- filename: animalchecklist-com-diagnostics-api-openapi.yml
  format: yaml
  label: animalchecklist-com Diagnostics API
  slug: animalchecklist-com-diagnostics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-diagnostics-api-openapi.yml
- filename: animalchecklist-com-leaderboard-api-openapi.yml
  format: yaml
  label: animalchecklist-com Leaderboard API
  slug: animalchecklist-com-leaderboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-leaderboard-api-openapi.yml
- filename: animalchecklist-com-quiz-api-openapi.yml
  format: yaml
  label: animalchecklist-com Quiz API
  slug: animalchecklist-com-quiz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-quiz-api-openapi.yml
- filename: animalchecklist-com-recognition-api-openapi.yml
  format: yaml
  label: animalchecklist-com Recognition API
  slug: animalchecklist-com-recognition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-recognition-api-openapi.yml
- filename: animalchecklist-com-sightings-api-openapi.yml
  format: yaml
  label: animalchecklist-com Sightings API
  slug: animalchecklist-com-sightings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-sightings-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: we store your email address, login tokens and session records
  - category: device
    text: PostHog receives the IP address and browser details needed to deliver the chat.
  - category: identifying
    text: we store the Stripe customer and subscription IDs, payment status, billing period, plan and number of photo searches
  - category: other
    text: Your browser stores your sightings in localStorage.
  - category: other
    text: If you report a photo, we store the animal, reason, optional note and submission time to review it.
  deletion:
    route: In-account data export and account deletion, or email request
    text: Signed-in users can download their account data and delete their account.
  dpa:
    available: true
    text: 'Provider terms: https://posthog.com/privacy and https://posthog.com/dpa.'
    url: https://posthog.com/dpa
  purposes:
  - purpose: Provide checklist and sync
    text: We process these records to provide the checklist and sync you request under GDPR Article 6(1)(b).
  - purpose: Support enquiries
    text: 'Support legal basis: GDPR Article 6(1)(b) for contractual support, and Article 6(1)(f) for our interest in answering other enquiries you request.'
  - purpose: Optional measurement with consent
    text: Optional measurement and feedback use your consent under GDPR Article 6(1)(a) and section 25(1) TDDDG.
  - purpose: Abuse prevention and reliability
    text: We use IP-based limits and error reports to prevent abuse and keep the service reliable under GDPR Article 6(1)(f).
  residency:
  - region: EU
    text: It uses PostHog's EU hosting.
  retention:
  - period: null
    scope: Support correspondence
    text: We delete support correspondence when it is no longer needed to handle the enquiry, unless legal retention duties or open claims require us to keep it.
  - period: 30 days
    scope: Browser identifier
    text: A separate random browser identifier expires after 30 days.
  - period: 30 days
    scope: Authentication cookie
    text: The strictly necessary ac_session cookie keeps you signed in for up to 30 days.
  - period: seven days
    scope: Unfinished quiz rounds
    text: Unfinished rounds expire after seven days.
  - period: 90 days
    scope: Photo reports
    text: An hourly cleanup removes reports older than 90 days.
  - period: 24 hours
    scope: Recognition jobs
    text: Jobs and clues expire after 24 hours.
  rights:
  - right: Access, rectification, erasure, restriction, portability, objection
    text: You have the rights of access (Article 15), rectification (16), erasure (17), restriction (18), portability (20) and objection (21), and you can withdraw consent at any time (Article 7(3)).
  - right: Complain to authority
    text: You can complain to a data protection authority, including the Hessian Commissioner for Data Protection and Freedom of Information.
  role:
    text: Arne Kellmann, Odenwaldstr. 134L, 64372 Ober-Ramstadt, Germany, animalchecklist@arnekellmann.de, is responsible for this processing.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: EU hosting does not exclude access by PostHog or its subprocessors outside the EU; its data processing terms describe the safeguards for such transfers.
  - mechanism: other
    text: These providers may process data outside the EU.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: animalchecklist-com
provenance_date: '2026-11-09'
provider_name: animalchecklist-com
provider_slug: animalchecklist-com
slug: animalchecklist-com-privacy-policy
source_date: '2026-11-09'
source_filename: animalchecklist-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://animalchecklist.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: animalchecklist-com\naid: animalchecklist-com\nurl: https://animalchecklist.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Arne Kellmann, Odenwaldstr. 134L, 64372 Ober-Ramstadt, Germany, animalchecklist@arnekellmann.de, is responsible\n    for this processing.\ndata_categories:\n- category: contact\n  text: we store your email address, login tokens and session records\n- category: device\n  text: PostHog receives the IP address and browser details needed to deliver the chat.\n- category: identifying\n  text: we store the Stripe customer and subscription IDs, payment status, billing\
  \ period, plan and number of photo\n    searches\n- category: other\n  text: Your browser stores your sightings in localStorage.\n- category: other\n  text: If you report a photo, we store the animal, reason, optional note and submission time to review it.\npurposes:\n- purpose: Provide checklist and sync\n  text: We process these records to provide the checklist and sync you request under GDPR Article 6(1)(b).\n- purpose: Support enquiries\n  text: 'Support legal basis: GDPR Article 6(1)(b) for contractual support, and Article 6(1)(f) for our interest\n    in answering other enquiries you request.'\n- purpose: Optional measurement with consent\n  text: Optional measurement and feedback use your consent under GDPR Article 6(1)(a) and section 25(1) TDDDG.\n- purpose: Abuse prevention and reliability\n  text: We use IP-based limits and error reports to prevent abuse and keep the service reliable under GDPR Article\n    6(1)(f).\nretention:\n- scope: Support correspondence\n  period: null\n\
  \  text: We delete support correspondence when it is no longer needed to handle the enquiry, unless legal retention\n    duties or open claims require us to keep it.\n- scope: Browser identifier\n  period: 30 days\n  text: A separate random browser identifier expires after 30 days.\n- scope: Authentication cookie\n  period: 30 days\n  text: The strictly necessary ac_session cookie keeps you signed in for up to 30 days.\n- scope: Unfinished quiz rounds\n  period: seven days\n  text: Unfinished rounds expire after seven days.\n- scope: Photo reports\n  period: 90 days\n  text: An hourly cleanup removes reports older than 90 days.\n- scope: Recognition jobs\n  period: 24 hours\n  text: Jobs and clues expire after 24 hours.\nresidency:\n- region: EU\n  text: It uses PostHog's EU hosting.\ntransfers:\n- mechanism: other\n  text: EU hosting does not exclude access by PostHog or its subprocessors outside the EU; its data processing terms\n    describe the safeguards for such transfers.\n- mechanism:\
  \ other\n  text: These providers may process data outside the EU.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://posthog.com/dpa\n  text: 'Provider terms: https://posthog.com/privacy and https://posthog.com/dpa.'\ndeletion:\n  route: In-account data export and account deletion, or email request\n  text: Signed-in users can download their account data and delete their account.\nrights:\n- right: Access, rectification, erasure, restriction, portability, objection\n  text: You have the rights of access (Article 15), rectification (16), erasure (17), restriction (18), portability\n    (20) and objection (21), and you can withdraw consent at any time (Article 7(3)).\n- right: Complain to authority\n  text: You can complain to a data protection authority, including the Hessian Commissioner for Data Protection\n    and Freedom of Information.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/animalchecklist-com/privacy/animalchecklist-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from animalchecklist-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Animals
- Checklist
- Mobile App
- Free
---
