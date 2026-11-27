---
api_specs:
- filename: calvingwatch-com-public-knowledge-api-openapi.yml
  format: yaml
  label: CalvingWatch Public knowledge API
  slug: calvingwatch-com-public-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calvingwatch-com/openapi/calvingwatch-com-public-knowledge-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Tester and account details: name, email, phone, country, county for Irish tester applications, camera app, account id and consent records.'
  - category: other
    text: 'Camera frames: still JPEG images from the calving shed or pen.'
  - category: behavioral
    text: 'AI, alert and feedback records: stage, confidence, observations, alerts, acknowledgements, escalation state and farmer feedback.'
  - category: device
    text: 'Device data: push-notification token and notification preferences'
  deletion:
    route: In-app deletion under Settings → Delete account, the public account deletion page, or email
    text: Signed-in users can start deletion in the app under Settings → Delete account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide accounts, setup, alerts and support
    text: Provide accounts, setup, alerts and support where Maranox is controller.
  - purpose: Train and improve CalvingWatch
    text: Train and improve CalvingWatch with testers' pictures and alarm answers.
  - purpose: Share or license tester data with partners
    text: Share or license testers' data to partners in agriculture and research (testers who agreed from 13 October 2026).
  - purpose: Diagnose app crashes and setup blockers
    text: Understand aggregate app setup blockers and diagnose app crashes.
  residency:
  - region: Finland (EU)
    text: kept on our own GPU server in Finland (EU) to teach our own AI to tell one cow from another.
  - region: EU (Google multi-region)
    text: through Google's EU multi-region endpoint
  retention:
  - period: 90 days
    scope: Operational camera frames and analysis logs
    text: Default 90 days.
  - period: until you leave the tester programme and ask us to delete them
    scope: Training archive
    text: Kept until you leave the tester programme and ask us to delete them, or ask us to delete your data.
  - period: While the relationship is active, then deleted or minimised unless law requires retention
    scope: Account, waitlist and support data
    text: While the relationship is active, then deleted or minimised unless law requires retention.
  - period: 90 days
    scope: Opted-in Firebase Crashlytics reports
    text: Google states that stack traces and associated Crashlytics/Firebase installation identifiers are kept for 90 days before removal from live and backup systems begins.
  rights:
  - right: Access, correction, deletion, restriction, portable copy, objection, withdrawal of consent
    text: You can ask to access, correct, delete, restrict or receive a portable copy of your personal data, object where applicable, and withdraw consent.
  - right: Complaint to supervisory authority
    text: You can complain to the Irish Data Protection Commission.
  role:
    text: For account, waitlist, billing, website and support data, Maranox Technologies Limited is the controller.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Testers who agree from 13 October 2026 also agree that we may share or license this data to partners in agriculture and research.
  subprocessors:
    text: The current provider register is at /subprocessors/
    url: /subprocessors/
  transfers:
  - mechanism: other
    text: Some Google metadata and other provider processing may therefore occur outside the EEA; where it does, it must use a valid transfer mechanism such as an adequacy decision, Standard Contractual Clauses or provider data-processing terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CalvingWatch
provenance_date: '2026-11-09'
provider_name: CalvingWatch
provider_slug: calvingwatch-com
slug: calvingwatch-com-privacy-policy
source_date: '2026-11-09'
source_filename: calvingwatch-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://calvingwatch.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CalvingWatch\naid: calvingwatch-com\nurl: https://calvingwatch.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account, waitlist, billing, website and support data, Maranox Technologies Limited is the controller.\ndata_categories:\n- category: identifying\n  text: 'Tester and account details: name, email, phone, country, county for Irish tester applications, camera app,\n    account id and consent records.'\n- category: other\n  text: 'Camera frames: still JPEG images from the calving shed or pen.'\n- category: behavioral\n  text: 'AI, alert and feedback records: stage, confidence,\
  \ observations, alerts, acknowledgements, escalation state\n    and farmer feedback.'\n- category: device\n  text: 'Device data: push-notification token and notification preferences'\npurposes:\n- purpose: Provide accounts, setup, alerts and support\n  text: Provide accounts, setup, alerts and support where Maranox is controller.\n- purpose: Train and improve CalvingWatch\n  text: Train and improve CalvingWatch with testers' pictures and alarm answers.\n- purpose: Share or license tester data with partners\n  text: Share or license testers' data to partners in agriculture and research (testers who agreed from 13 October\n    2026).\n- purpose: Diagnose app crashes and setup blockers\n  text: Understand aggregate app setup blockers and diagnose app crashes.\nretention:\n- scope: Operational camera frames and analysis logs\n  period: 90 days\n  text: Default 90 days.\n- scope: Training archive\n  period: until you leave the tester programme and ask us to delete them\n  text: Kept until you\
  \ leave the tester programme and ask us to delete them, or ask us to delete your data.\n- scope: Account, waitlist and support data\n  period: While the relationship is active, then deleted or minimised unless law requires retention\n  text: While the relationship is active, then deleted or minimised unless law requires retention.\n- scope: Opted-in Firebase Crashlytics reports\n  period: 90 days\n  text: Google states that stack traces and associated Crashlytics/Firebase installation identifiers are kept for\n    90 days before removal from live and backup systems begins.\nresidency:\n- region: Finland (EU)\n  text: kept on our own GPU server in Finland (EU) to teach our own AI to tell one cow from another.\n- region: EU (Google multi-region)\n  text: through Google's EU multi-region endpoint\ntransfers:\n- mechanism: other\n  text: Some Google metadata and other provider processing may therefore occur outside the EEA; where it does, it\n    must use a valid transfer mechanism such as\
  \ an adequacy decision, Standard Contractual Clauses or provider data-processing\n    terms.\nsubprocessors:\n  url: /subprocessors/\n  text: The current provider register is at /subprocessors/\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app deletion under Settings → Delete account, the public account deletion page, or email\n  text: Signed-in users can start deletion in the app under Settings → Delete account.\nrights:\n- right: Access, correction, deletion, restriction, portable copy, objection, withdrawal of consent\n  text: You can ask to access, correct, delete, restrict or receive a portable copy of your personal data, object\n    where applicable, and withdraw consent.\n- right: Complaint to supervisory authority\n  text: You can complain to the Irish Data Protection Commission.\nsale_or_sharing:\n  stance: conditional\n  text: Testers who agree from 13 October 2026 also agree that we may share or license this data to partners in\n    agriculture\
  \ and research.\n"
source_yaml_url: https://artifacts.apis.io/calvingwatch-com/privacy/calvingwatch-com-privacy-policy.yml
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
summary_line: 21 quoted statements, read from CalvingWatch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Artificial Intelligence
- Livestock
- Monitoring
- Ireland
---
