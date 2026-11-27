---
api_specs:
- filename: hiver-conversations-api-openapi.yml
  format: yaml
  label: Hiver Conversations API
  slug: hiver-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiver/openapi/hiver-conversations-api-openapi.yml
- filename: hiver-inbox-api-openapi.yml
  format: yaml
  label: Hiver Inbox API
  slug: hiver-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiver/openapi/hiver-inbox-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and last name; user name and password
  - category: contact
    text: phone number; cell phone number; email address
  - category: financial
    text: billing address; postal address; bank information; credit card information
  - category: location
    text: geolocation
  - category: device
    text: internet protocol address; device IDs; device characteristics/operating system; browser type
  - category: communication
    text: Email information sender/recipient email addresses; display name; headers; subject; content/messages; folders/labels; timestamps; attachments
  - category: behavioral
    text: feature usage; administrative events (such as setting changes); browsing time; essential cookie information
  - category: other
    text: audio recordings (voiceprints)
  deletion:
    route: Account deletion or written request to privacy@hiverhq.com or security@hiverhq.com
    text: You may delete your account with us at any time or you may request that we delete the personal information which we maintain about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Services
    text: To provide you with our Services
  - purpose: Maintain and improve Services
    text: To maintain and improve our Services
  - purpose: Marketing communications
    text: To send you communications related to our Services, such as newsletters, promotions, advertisements, and marketing information
  - purpose: Legal and accounting records
    text: To maintain and process records for tax and accounting purposes
  residency:
  - region: United States (Teams app data)
    text: We store this information on Amazon Web Services in the United States (us-west-2, Oregon).
  retention:
  - period: fourteen (14) calendar days
    scope: Platform personal information
    text: We delete your personal information within fourteen (14) calendar days after termination of the access and use of the Platform
  - period: two (2) months
    scope: Platform encrypted backups
    text: certain personal information may remain in our encrypted backups for a period of up to two (2) months after termination of the Platform
  - period: one (1) hour
    scope: Gmail content and attachments
    text: Gmail content/message and attachments will be deleted within one (1) hour of collection
  - period: ninety (90) calendar days
    scope: AI Provider activity logs and capability-gap reports
    text: The activity logs and capability-gap reports are stored for ninety (90) calendar days from date of creation.
  rights:
  - right: Access
    text: You have a right to access your personal information that we collect, use, process, and store.
  - right: Correction
    text: You have a right to correct your personal information that we collect, use, process, and store.
  - right: Deletion
    text: You have a right to delete your personal information that we collect, use, process, and store.
  - right: Restrict processing
    text: You may have a right to request that we restrict processing of your personal information under certain circumstances
  - right: Portability
    text: You may have the right, if it is possible, given our then-current automated systems and data architecture, to receive your personal information in machine readable format
  - right: Objection
    text: You may have the right, in limited circumstances, to object to our processing of your personal information.
  - right: Withdraw consent
    text: you have the right to withdraw your consent by deleting your account.
  - right: Lodge a complaint
    text: You have a right to file a complaint with the appropriate government agency
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information to third parties for a monetary payment or something else of values received in return. However, we may provide your personal information to third parties where we do not receive a monetary payment
  subprocessors:
    text: The AI providers currently supported are named at hiverhq.com/third-party-subprocessors
    url: hiverhq.com/third-party-subprocessors
  transfers:
  - mechanism: other
    text: If you reside outside of the United States, we will transfer your personal information to the United States, and we will put in place the required safeguards so that the transfer of your personal information complies with data protection laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hiver
provenance_date: '2026-11-09'
provider_name: Hiver
provider_slug: hiver
slug: hiver-privacy-policy
source_date: '2026-11-09'
source_filename: hiver-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hiverhq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hiver\naid: hiver\nurl: https://hiverhq.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: first and last name; user name and password\n- category: contact\n  text: phone number; cell phone number; email address\n- category: financial\n  text: billing address; postal address; bank information; credit card information\n- category: location\n  text: geolocation\n- category: device\n  text: internet protocol address; device IDs; device characteristics/operating system; browser type\n- category: communication\n  text: Email information\
  \ sender/recipient email addresses; display name; headers; subject; content/messages; folders/labels;\n    timestamps; attachments\n- category: behavioral\n  text: feature usage; administrative events (such as setting changes); browsing time; essential cookie information\n- category: other\n  text: audio recordings (voiceprints)\npurposes:\n- purpose: Provide Services\n  text: To provide you with our Services\n- purpose: Maintain and improve Services\n  text: To maintain and improve our Services\n- purpose: Marketing communications\n  text: To send you communications related to our Services, such as newsletters, promotions, advertisements, and\n    marketing information\n- purpose: Legal and accounting records\n  text: To maintain and process records for tax and accounting purposes\nretention:\n- scope: Platform personal information\n  period: fourteen (14) calendar days\n  text: We delete your personal information within fourteen (14) calendar days after termination of the access and\n\
  \    use of the Platform\n- scope: Platform encrypted backups\n  period: two (2) months\n  text: certain personal information may remain in our encrypted backups for a period of up to two (2) months after\n    termination of the Platform\n- scope: Gmail content and attachments\n  period: one (1) hour\n  text: Gmail content/message and attachments will be deleted within one (1) hour of collection\n- scope: AI Provider activity logs and capability-gap reports\n  period: ninety (90) calendar days\n  text: The activity logs and capability-gap reports are stored for ninety (90) calendar days from date of creation.\nresidency:\n- region: United States (Teams app data)\n  text: We store this information on Amazon Web Services in the United States (us-west-2, Oregon).\ntransfers:\n- mechanism: other\n  text: If you reside outside of the United States, we will transfer your personal information to the United States,\n    and we will put in place the required safeguards so that the transfer of your\
  \ personal information complies\n    with data protection laws.\nsubprocessors:\n  url: hiverhq.com/third-party-subprocessors\n  text: The AI providers currently supported are named at hiverhq.com/third-party-subprocessors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or written request to privacy@hiverhq.com or security@hiverhq.com\n  text: You may delete your account with us at any time or you may request that we delete the personal information\n    which we maintain about you.\nrights:\n- right: Access\n  text: You have a right to access your personal information that we collect, use, process, and store.\n- right: Correction\n  text: You have a right to correct your personal information that we collect, use, process, and store.\n- right: Deletion\n  text: You have a right to delete your personal information that we collect, use, process, and store.\n- right: Restrict processing\n  text: You may have a right to request that we restrict processing\
  \ of your personal information under certain circumstances\n- right: Portability\n  text: You may have the right, if it is possible, given our then-current automated systems and data architecture,\n    to receive your personal information in machine readable format\n- right: Objection\n  text: You may have the right, in limited circumstances, to object to our processing of your personal information.\n- right: Withdraw consent\n  text: you have the right to withdraw your consent by deleting your account.\n- right: Lodge a complaint\n  text: You have a right to file a complaint with the appropriate government agency\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information to third parties for a monetary payment or something else of values\n    received in return. However, we may provide your personal information to third parties where we do not receive\n    a monetary payment\n"
source_yaml_url: https://artifacts.apis.io/hiver/privacy/hiver-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Hiver's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Service
- Help Desk
- Shared Inbox
- Email
- Ticketing
- Collaboration
- Gmail
- Google Workspace
- Omnichannel
- Live Chat
- Software-as-a-Service
- Artificial Intelligence
---
