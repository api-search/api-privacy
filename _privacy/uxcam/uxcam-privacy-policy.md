---
api_specs:
- filename: uxcam-events-api-openapi.yml
  format: yaml
  label: UXCam Events API
  slug: uxcam-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-events-api-openapi.yml
- filename: uxcam-sessions-api-openapi.yml
  format: yaml
  label: UXCam Sessions API
  slug: uxcam-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-sessions-api-openapi.yml
- filename: uxcam-users-api-openapi.yml
  format: yaml
  label: UXCam Users API
  slug: uxcam-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-users-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Consistent random pseudo ID for every end-user
  - category: contact
    text: Email address
  - category: device
    text: 'Device details: type, version, model, operating system (OS)'
  - category: location
    text: Geographic location (country only)
  - category: behavioral
    text: 'Interaction patterns by the end-user on customers’ app (screen actions, gestures: taps, scrolls)'
  - category: professional
    text: Job title
  deletion:
    route: email privacy@uxcam.com
    text: If we are not under the obligation to keep the data for legal compliance and your data is not needed in the scope of an active contract or claim, we will remove your information upon your request.
  dpa:
    available: true
    text: UXCam offers a Data Processing Addendum (DPA) to provide such adequate safeguards
    url: null
  purposes:
  - purpose: debugging, quality management, app improvement
    text: We use this data for debugging, quality management, and app improvement purposes as well to provide customers with insights about app user experience and behavior in the form of statistics.
  - purpose: marketing emails
    text: based on your consent, to send you marketing emails;
  - purpose: recruitment
    text: We assess this information against the job requirements for our recruitment purposes only.
  residency:
  - region: United States
    text: Our Website and Services are hosted in the United States of America.
  retention:
  - period: 3 months
    scope: SDK data on free trial
    text: Data associated with a free trial is retained for 3 months;
  - period: 6 months
    scope: SDK data on free plan
    text: Data associated with a free plan is retained for 6 months;
  - period: 60 months
    scope: SDK data on Enterprise tier
    text: Data associated with the Enterprise tier is retained for 60 months;
  - period: 180 days
    scope: Applicant CVs
    text: We will store CVs and related job data for a period of 180 days.
  - period: null
    scope: Account data
    text: We will store your account data for as long as you use or pay for our services.
  rights:
  - right: access
    text: Access your information . You have the right to know what personal data we process.
  - right: rectification
    text: Verify your information and seek its rectification .
  - right: objection
    text: Object against the processing of your information .
  - right: restriction
    text: Restrict the processing of your information .
  - right: erasure
    text: Delete your personal data.
  - right: portability
    text: Transfer your personal data to another organization.
  - right: complaint
    text: Lodge a complaint with a supervisory authority
  role:
    text: From the data protection perspective, we act as a data processor for the information collected through the SDK and UXCam App, and as data controllers for the information collected through our website.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: To ensure compliance with data protection requirements on international transfers, the Standard Contractual Clauses (SCC) as adopted by the European Commission are signed with these providers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UXCam
provenance_date: '2026-11-10'
provider_name: UXCam
provider_slug: uxcam
slug: uxcam-privacy-policy
source_date: '2026-11-10'
source_filename: uxcam-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://uxcam.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UXCam\naid: uxcam\nurl: https://uxcam.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: From the data protection perspective, we act as a data processor for the information collected through the\n    SDK and UXCam App, and as data controllers for the information collected through our website.\ndata_categories:\n- category: identifying\n  text: Consistent random pseudo ID for every end-user\n- category: contact\n  text: Email address\n- category: device\n  text: 'Device details: type, version, model, operating system (OS)'\n- category: location\n  text: Geographic location (country\
  \ only)\n- category: behavioral\n  text: 'Interaction patterns by the end-user on customers’ app (screen actions, gestures: taps, scrolls)'\n- category: professional\n  text: Job title\npurposes:\n- purpose: debugging, quality management, app improvement\n  text: We use this data for debugging, quality management, and app improvement purposes as well to provide customers\n    with insights about app user experience and behavior in the form of statistics.\n- purpose: marketing emails\n  text: based on your consent, to send you marketing emails;\n- purpose: recruitment\n  text: We assess this information against the job requirements for our recruitment purposes only.\nretention:\n- scope: SDK data on free trial\n  period: 3 months\n  text: Data associated with a free trial is retained for 3 months;\n- scope: SDK data on free plan\n  period: 6 months\n  text: Data associated with a free plan is retained for 6 months;\n- scope: SDK data on Enterprise tier\n  period: 60 months\n  text: Data\
  \ associated with the Enterprise tier is retained for 60 months;\n- scope: Applicant CVs\n  period: 180 days\n  text: We will store CVs and related job data for a period of 180 days.\n- scope: Account data\n  period: null\n  text: We will store your account data for as long as you use or pay for our services.\nresidency:\n- region: United States\n  text: Our Website and Services are hosted in the United States of America.\ntransfers:\n- mechanism: SCC\n  text: To ensure compliance with data protection requirements on international transfers, the Standard Contractual\n    Clauses (SCC) as adopted by the European Commission are signed with these providers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: UXCam offers a Data Processing Addendum (DPA) to provide such adequate safeguards\ndeletion:\n  route: email privacy@uxcam.com\n  text: If we are not under the obligation to keep the data for legal compliance and your data is not needed in\n    the\
  \ scope of an active contract or claim, we will remove your information upon your request.\nrights:\n- right: access\n  text: Access your information . You have the right to know what personal data we process.\n- right: rectification\n  text: Verify your information and seek its rectification .\n- right: objection\n  text: Object against the processing of your information .\n- right: restriction\n  text: Restrict the processing of your information .\n- right: erasure\n  text: Delete your personal data.\n- right: portability\n  text: Transfer your personal data to another organization.\n- right: complaint\n  text: Lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uxcam/privacy/uxcam-privacy-policy.yml
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
summary_line: 26 quoted statements, read from UXCam's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Analytics
- Session Replay
- Mobile Analytics
- Heatmaps
- User Experience
- Crash Reporting
---
