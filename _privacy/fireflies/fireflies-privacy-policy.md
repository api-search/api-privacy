---
api_specs:
- filename: fireflies-transcripts-api-openapi.yml
  format: yaml
  label: Fireflies.ai Transcripts API
  slug: fireflies-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fireflies/openapi/fireflies-transcripts-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information you provide in connection with registering for an account, such as your name, company name, email address, physical address, phone number
  - category: device
    text: 'Device Data: We collect information about the device you use to access our Services, such as hardware model, operating system, and device identifiers.'
  - category: location
    text: we may infer or derive information about your approximate location based on your IP address
  - category: communication
    text: 'Meeting and Call Information: If enabled, certain features and integrations of our Services will collect meeting and call details, such as the names and email addresses of participants and invitees, the title of the meeting, meeting audio and visual files'
  - category: behavioral
    text: 'Usage Data: We collect information about how you access and use our Services, such as the features you use, the actions you take (such as pages viewed and links clicked)'
  - category: financial
    text: Transaction and limited (non-PCI) payment data
  deletion:
    route: Email support@fireflies.ai or use account settings
    text: You can access, correct, and delete certain information stored within your Fireflies.ai account at any time by visiting https://app.fireflies.ai/settings or by using our live chat function.
  dpa:
    available: true
    text: User Content we process on behalf of our business customers, which is governed by our Terms of Service , Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide, operate and improve Services
    text: We use the information we collect to provide, operate, and improve our Services, including to capture audio and visual recordings of meetings, generate transcripts and summaries
  - purpose: Targeted advertising
    text: Target advertisements to you on third-party platforms and websites
  - purpose: Security
    text: Detect, investigate, respond to, prosecute, and help protect against security incidents and other malicious, deceptive, fraudulent, or illegal activity
  residency:
  - region: United States and other countries
    text: we and our service providers process and store personal information on servers located in the United States and other countries.
  retention:
  - period: 30 days
    scope: Account data
    text: If you close your account, we will delete personal information related to your account within 30 days.
  - period: null
    scope: Meeting content and Fireflies Talk data
    text: We also impose a Zero Data Retention policy for meeting content, which includes audio, video, transcripts, and summaries of the meeting, and Fireflies Talk data.
  rights:
  - right: Access
    text: You have the right to (1) request to know more about and access your personal information, including in a portable format
  - right: Deletion
    text: (2) request deletion of your personal information
  - right: Correction
    text: (3) request correction of inaccurate personal information
  - right: Opt out of sales, sharing, targeted advertising
    text: 'You may opt out of activities that we engage in that constitute “sales,” “sharing,” or “targeted advertising” under the State Privacy Laws by:'
  - right: Object or restrict processing
    text: In addition, you may have the right to object to certain processing or request we restrict certain processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: The activities described in this section may constitute “targeted advertising,” “sharing,” or “selling” under certain privacy laws.
  subprocessors:
    text: More information about our subprocessors is available at https://trust.fireflies.ai/subprocessors .
    url: https://trust.fireflies.ai/subprocessors
  transfers:
  - mechanism: DPF
    text: Fireflies.ai complies with the EU-U.S. and Swiss-U.S. Data Privacy Frameworks and the UK Extension to the EU-U.S. Data Privacy Framework
  - mechanism: other
    text: we take steps to ensure that your personal information receives an adequate level of protection (by putting in place appropriate safeguards, such as contractual clauses)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fireflies.ai
provenance_date: '2026-11-09'
provider_name: Fireflies.ai
provider_slug: fireflies
slug: fireflies-privacy-policy
source_date: '2026-11-09'
source_filename: fireflies-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fireflies.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fireflies.ai\naid: fireflies\nurl: https://fireflies.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Information you provide in connection with registering for an account, such as your name, company name,\n    email address, physical address, phone number\n- category: device\n  text: 'Device Data: We collect information about the device you use to access our Services, such as hardware model,\n    operating system, and device identifiers.'\n- category: location\n  text: we may infer or derive information about your approximate\
  \ location based on your IP address\n- category: communication\n  text: 'Meeting and Call Information: If enabled, certain features and integrations of our Services will collect\n    meeting and call details, such as the names and email addresses of participants and invitees, the title of the\n    meeting, meeting audio and visual files'\n- category: behavioral\n  text: 'Usage Data: We collect information about how you access and use our Services, such as the features you\n    use, the actions you take (such as pages viewed and links clicked)'\n- category: financial\n  text: Transaction and limited (non-PCI) payment data\npurposes:\n- purpose: Provide, operate and improve Services\n  text: We use the information we collect to provide, operate, and improve our Services, including to capture audio\n    and visual recordings of meetings, generate transcripts and summaries\n- purpose: Targeted advertising\n  text: Target advertisements to you on third-party platforms and websites\n- purpose:\
  \ Security\n  text: Detect, investigate, respond to, prosecute, and help protect against security incidents and other malicious,\n    deceptive, fraudulent, or illegal activity\nretention:\n- scope: Account data\n  period: 30 days\n  text: If you close your account, we will delete personal information related to your account within 30 days.\n- scope: Meeting content and Fireflies Talk data\n  period: null\n  text: We also impose a Zero Data Retention policy for meeting content, which includes audio, video, transcripts,\n    and summaries of the meeting, and Fireflies Talk data.\nresidency:\n- region: United States and other countries\n  text: we and our service providers process and store personal information on servers located in the United States\n    and other countries.\ntransfers:\n- mechanism: DPF\n  text: Fireflies.ai complies with the EU-U.S. and Swiss-U.S. Data Privacy Frameworks and the UK Extension to the\n    EU-U.S. Data Privacy Framework\n- mechanism: other\n  text: we take\
  \ steps to ensure that your personal information receives an adequate level of protection (by putting\n    in place appropriate safeguards, such as contractual clauses)\nsubprocessors:\n  url: https://trust.fireflies.ai/subprocessors\n  text: More information about our subprocessors is available at https://trust.fireflies.ai/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: User Content we process on behalf of our business customers, which is governed by our Terms of Service ,\n    Data Processing Agreement\ndeletion:\n  route: Email support@fireflies.ai or use account settings\n  text: You can access, correct, and delete certain information stored within your Fireflies.ai account at any time\n    by visiting https://app.fireflies.ai/settings or by using our live chat function.\nrights:\n- right: Access\n  text: You have the right to (1) request to know more about and access your personal information, including in\n    a portable format\n- right: Deletion\n  text: (2) request\
  \ deletion of your personal information\n- right: Correction\n  text: (3) request correction of inaccurate personal information\n- right: Opt out of sales, sharing, targeted advertising\n  text: 'You may opt out of activities that we engage in that constitute “sales,” “sharing,” or “targeted advertising”\n    under the State Privacy Laws by:'\n- right: Object or restrict processing\n  text: In addition, you may have the right to object to certain processing or request we restrict certain processing.\nsale_or_sharing:\n  stance: conditional\n  text: The activities described in this section may constitute “targeted advertising,” “sharing,” or “selling”\n    under certain privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/fireflies/privacy/fireflies-privacy-policy.yml
stated_fields:
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
summary_line: 23 quoted statements, read from Fireflies.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Meeting Assistant
- Transcription
- Summary
- Action Items
- GraphQL
- Meetings
- Productivity
- Collaboration
- Conversation Intelligence
- A2A
---
