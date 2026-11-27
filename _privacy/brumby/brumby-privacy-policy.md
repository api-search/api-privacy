---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address — provided during account creation
  - category: financial
    text: Organisation name and billing details — for account management and invoicing
  - category: location
    text: Paddock boundaries and maps — geofences and property layouts you define in the app
  - category: device
    text: Device information — operating system, device model, and app version
  - category: behavioral
    text: App usage data — features accessed, session duration, and interaction patterns within the Brumby app
  - category: other
    text: Aerial imagery and video — footage captured by the drone during scheduled missions on your property
  deletion:
    route: contact support@brumby.com
    text: You may request earlier deletion of your data at any time.
  dpa:
    available: true
    text: AWS processes data on our behalf under a Data Processing Agreement
    url: null
  purposes:
  - purpose: Service delivery
    text: To operate missions, generate reports, and deliver results to your device.
  - purpose: AI model development
    text: To improve our AI systems for cattle detection, pasture analysis, and autonomous navigation.
  - purpose: No advertising or profiling
    text: We do not use your data for advertising, behavioural profiling, or any purpose not listed above.
  residency:
  - region: Australia
    text: with cloud infrastructure in AWS Sydney (ap-southeast-2)
  - region: United States
    text: for certain redundancy functions, AWS US East.
  retention:
  - period: the duration of your account, plus 90 days following account closure
    scope: Account data
    text: retained for the duration of your account, plus 90 days following account closure
  - period: 24 months
    scope: Mission reports and telemetry
    text: retained for 24 months by default, after which they are automatically deleted or anonymised
  - period: 90 days following mission completion
    scope: Raw aerial imagery
    text: retained for 90 days following mission completion, then permanently deleted from our systems
  - period: 7 years
    scope: Billing records
    text: retained for 7 years to comply with financial and tax regulations
  - period: 12 months
    scope: Log and audit data
    text: retained for 12 months for security and diagnostic purposes
  rights:
  - right: Access
    text: request a copy of the personal data we hold about you
  - right: Deletion
    text: request that your personal data be deleted (subject to legal retention requirements)
  - right: Objection
    text: object to processing based on legitimate interests, including AI model training
  - right: Portability
    text: request your data in a structured, machine-readable format
  role:
    text: GrazeMate, Inc. is the data controller responsible for the personal data collected through the Brumby Services.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your data.
  subprocessors:
    text: Data processing agreements with all sub-processors
    url: null
  transfers:
  - mechanism: SCC
    text: Standard contractual clauses where required under GDPR
  - mechanism: other
    text: Transfers only to countries or services with adequate data protection frameworks
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Brumby
provenance_date: '2026-11-09'
provider_name: Brumby
provider_slug: brumby
slug: brumby-privacy-policy
source_date: '2026-11-09'
source_filename: brumby-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://brumby.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Brumby\naid: brumby\nurl: https://brumby.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: GrazeMate, Inc. is the data controller responsible for the personal data collected through the Brumby Services.\ndata_categories:\n- category: identifying\n  text: Name and email address — provided during account creation\n- category: financial\n  text: Organisation name and billing details — for account management and invoicing\n- category: location\n  text: Paddock boundaries and maps — geofences and property layouts you define in the app\n- category: device\n  text: Device information\
  \ — operating system, device model, and app version\n- category: behavioral\n  text: App usage data — features accessed, session duration, and interaction patterns within the Brumby app\n- category: other\n  text: Aerial imagery and video — footage captured by the drone during scheduled missions on your property\npurposes:\n- purpose: Service delivery\n  text: To operate missions, generate reports, and deliver results to your device.\n- purpose: AI model development\n  text: To improve our AI systems for cattle detection, pasture analysis, and autonomous navigation.\n- purpose: No advertising or profiling\n  text: We do not use your data for advertising, behavioural profiling, or any purpose not listed above.\nretention:\n- scope: Account data\n  period: the duration of your account, plus 90 days following account closure\n  text: retained for the duration of your account, plus 90 days following account closure\n- scope: Mission reports and telemetry\n  period: 24 months\n  text: retained\
  \ for 24 months by default, after which they are automatically deleted or anonymised\n- scope: Raw aerial imagery\n  period: 90 days following mission completion\n  text: retained for 90 days following mission completion, then permanently deleted from our systems\n- scope: Billing records\n  period: 7 years\n  text: retained for 7 years to comply with financial and tax regulations\n- scope: Log and audit data\n  period: 12 months\n  text: retained for 12 months for security and diagnostic purposes\nresidency:\n- region: Australia\n  text: with cloud infrastructure in AWS Sydney (ap-southeast-2)\n- region: United States\n  text: for certain redundancy functions, AWS US East.\ntransfers:\n- mechanism: SCC\n  text: Standard contractual clauses where required under GDPR\n- mechanism: other\n  text: Transfers only to countries or services with adequate data protection frameworks\nsubprocessors:\n  url: null\n  text: Data processing agreements with all sub-processors\ndpa:\n  available: true\n\
  \  url: null\n  text: AWS processes data on our behalf under a Data Processing Agreement\ndeletion:\n  route: contact support@brumby.com\n  text: You may request earlier deletion of your data at any time.\nrights:\n- right: Access\n  text: request a copy of the personal data we hold about you\n- right: Deletion\n  text: request that your personal data be deleted (subject to legal retention requirements)\n- right: Objection\n  text: object to processing based on legitimate interests, including AI model training\n- right: Portability\n  text: request your data in a structured, machine-readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your data.\n"
source_yaml_url: https://artifacts.apis.io/brumby/privacy/brumby-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Brumby's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Precision Agriculture
- Livestock
- Cattle
- Drones
- Robotics
- Artificial Intelligence
- Remote Sensing
- Y Combinator
---
