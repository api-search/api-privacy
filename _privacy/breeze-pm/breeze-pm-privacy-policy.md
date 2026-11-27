---
api_specs:
- filename: breeze-pm-openapi-generated.yml
  format: yaml
  label: breeze-pm API
  slug: breeze-pm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/breeze-pm/openapi/_ae-authored/breeze-pm-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, password (stored only as a salted hash), avatar, job title, time zone, language, notification preferences and two-factor authentication settings.
  - category: financial
    text: Team name, the Service Plan subscribed to, whether it is billed monthly or annually, the date paid until
  - category: location
    text: IP address, approximate geographical location derived from it, device and browser information, session information
  - category: communication
    text: Messages sent through in-app chat, comments and project discussion, and the content of email sent to or from the Service.
  - category: other
    text: Prompts submitted to the Breeze AI assistant built into the Service, the task and project content supplied to it as context, and audio recorded for voice note transcription.
  deletion:
    route: 'Via the Service: profile, project or account deletion'
    text: delete their user profile, delete individual projects, and cancel the account, which deletes its Content immediately
  dpa:
    available: true
    text: on the terms of the Data Processing Agreement at https://www.breeze.pm/dpa , which forms part of the Agreement and takes effect automatically.
    url: https://www.breeze.pm/dpa
  purposes:
  - purpose: Providing and improving the Service
    text: for the purposes of (i) providing the Service, (ii) improving or otherwise modifying the Service and notifying Customer and other relevant Data Subjects thereof
  - purpose: User statistics and analyses
    text: (vii) user statistics and other Service-related analyses
  residency:
  - region: Outside country of domicile, including OECD and EEA countries
    text: that Data may be processed in the country of their domicile as well as outside it, including in any member state of the Organisation for Economic Co-operation and Development (OECD) and any country participating in the European Economic Area (EEA)
  - region: France (EU)
    text: France (EU)
  retention:
  - period: For as long as the User Account exists
    scope: Account and profile data
    text: For as long as the User Account exists. Deleted when the End User deletes their profile, or when the account is cancelled
  - period: For the term of the Agreement
    scope: Content placed in the Service
    text: For the term of the Agreement. Cancelling the Service deletes it immediately and irrevocably; there is no post-termination retrieval window, so anything to be kept must be exported before cancelling
  - period: 14 days
    scope: MCP connector server request logs
    text: On the Breeze MCP connector service described in section 17, this period is 14 days
  - period: seven years
    scope: Subscription records for Stripe subscriptions
    text: for the seven years required by Estonian accounting law
  rights:
  - right: Access
    text: Upon Customer's request, Supplier will grant Customer access to, or, at Supplier's option, provide Customer with a statement of, all Personal Data that Supplier maintains about Customer
  - right: Erasure
    text: to have data erased
  - right: Portability
    text: to receive their data in a portable, machine-readable form
  - right: Objection
    text: to object to processing carried out on the basis of Supplier's legitimate interests
  - right: Complaint
    text: and to lodge a complaint with a data protection supervisory authority
  role:
    text: Supplier is the controller of the Data identified as such in section 6, and is a processor acting on the Customer's behalf in respect of User Data (see section 11).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Supplier does not sell Data, does not share it for cross-context behavioural advertising
  subprocessors:
    text: 'The current list is:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: breeze-pm
provenance_date: '2026-11-09'
provider_name: breeze-pm
provider_slug: breeze-pm
slug: breeze-pm-privacy-policy
source_date: '2026-11-09'
source_filename: breeze-pm-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.breeze.pm/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: breeze-pm\naid: breeze-pm\nurl: https://www.breeze.pm/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Supplier is the controller of the Data identified as such in section 6, and is a processor acting on the\n    Customer's behalf in respect of User Data (see section 11).\ndata_categories:\n- category: identifying\n  text: Name, email address, password (stored only as a salted hash), avatar, job title, time zone, language, notification\n    preferences and two-factor authentication settings.\n- category: financial\n  text: Team name, the Service Plan subscribed to, whether it is billed monthly\
  \ or annually, the date paid until\n- category: location\n  text: IP address, approximate geographical location derived from it, device and browser information, session information\n- category: communication\n  text: Messages sent through in-app chat, comments and project discussion, and the content of email sent to or\n    from the Service.\n- category: other\n  text: Prompts submitted to the Breeze AI assistant built into the Service, the task and project content supplied\n    to it as context, and audio recorded for voice note transcription.\npurposes:\n- purpose: Providing and improving the Service\n  text: for the purposes of (i) providing the Service, (ii) improving or otherwise modifying the Service and notifying\n    Customer and other relevant Data Subjects thereof\n- purpose: User statistics and analyses\n  text: (vii) user statistics and other Service-related analyses\nretention:\n- scope: Account and profile data\n  period: For as long as the User Account exists\n  text: For\
  \ as long as the User Account exists. Deleted when the End User deletes their profile, or when the account\n    is cancelled\n- scope: Content placed in the Service\n  period: For the term of the Agreement\n  text: For the term of the Agreement. Cancelling the Service deletes it immediately and irrevocably; there is no\n    post-termination retrieval window, so anything to be kept must be exported before cancelling\n- scope: MCP connector server request logs\n  period: 14 days\n  text: On the Breeze MCP connector service described in section 17, this period is 14 days\n- scope: Subscription records for Stripe subscriptions\n  period: seven years\n  text: for the seven years required by Estonian accounting law\nresidency:\n- region: Outside country of domicile, including OECD and EEA countries\n  text: that Data may be processed in the country of their domicile as well as outside it, including in any member\n    state of the Organisation for Economic Co-operation and Development (OECD)\
  \ and any country participating in\n    the European Economic Area (EEA)\n- region: France (EU)\n  text: France (EU)\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'The current list is:'\ndpa:\n  available: true\n  url: https://www.breeze.pm/dpa\n  text: on the terms of the Data Processing Agreement at https://www.breeze.pm/dpa , which forms part of the Agreement\n    and takes effect automatically.\ndeletion:\n  route: 'Via the Service: profile, project or account deletion'\n  text: delete their user profile, delete individual projects, and cancel the account, which deletes its Content\n    immediately\nrights:\n- right: Access\n  text: Upon Customer's request, Supplier will grant Customer access to, or, at Supplier's option, provide Customer\n    with a statement of, all Personal Data that Supplier maintains about Customer\n- right: Erasure\n  text: to have data erased\n- right: Portability\n  text: to receive their data in a portable, machine-readable form\n- right: Objection\n\
  \  text: to object to processing carried out on the basis of Supplier's legitimate interests\n- right: Complaint\n  text: and to lodge a complaint with a data protection supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: Supplier does not sell Data, does not share it for cross-context behavioural advertising\n"
source_yaml_url: https://artifacts.apis.io/breeze-pm/privacy/breeze-pm-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from breeze-pm's own page on 2026-11-09.
synthetic: false
tags:
- Project Management
- Task Management
- Time Tracking
- Kanban
- Remote Work
---
