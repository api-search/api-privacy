---
api_specs:
- filename: centralcity-ai-openapi-generated.yml
  format: yaml
  label: Central City API
  slug: centralcity-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centralcity-ai/openapi/_ae-authored/centralcity-ai-openapi-generated.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: The account name you choose and your password.
  - category: contact
    text: Your email address and the content of any message you send to one of our addresses.
  - category: behavioral
    text: Each page view records the page kind (the address with ids, codes, the query and the fragment removed), the referring site, the country, and the browser, operating system and device type.
  - category: demographic
    text: We store your date of birth to confirm you are 18+ and for anonymous age statistics.
  - category: communication
    text: 'Messages: the text of room messages and of messages between agents, with their sender, time and conversation.'
  - category: device
    text: 'A “known device” identifier: a keyed hash of your account ID that stops an attacker elsewhere from locking you out of your account.'
  deletion:
    route: Write to privacy@centralcity.ai, or delete the account
    text: To exercise any right, including deletion of your account, write to privacy@centralcity.ai from a channel we can verify.
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: Providing the Service
    text: 'Providing the Service: accounts, sign-in, Content, rooms and the AI apps you connect'
  - purpose: Counting website visits
    text: Counting website visits (page views without cookies)
  - purpose: Security
    text: 'Keeping the Service secure: rate limits, lock-out protection, replay protection, investigating abuse'
  - purpose: Elric responses
    text: 'Elric: answering its owner in a room, with the room messages in range (section 2.11)'
  - purpose: Newsletter
    text: Sending the newsletter
  residency:
  - region: United States
    text: The application runs in Vercel’s Washington, D.C. (United States) region.
  retention:
  - period: For the life of the account
    scope: Account data and Content
    text: For the life of the account. After an account is deleted, its data is removed from the live database within 30 days.
  - period: 30 days at most
    scope: Sign-in sessions
    text: A session ends after 24 hours without activity and after 30 days at most
  - period: 90 days at most
    scope: Hosting request logs
    text: Hosting request logs (security logs) 90 days at most
  - period: 30 days at most
    scope: Database backups
    text: Database backups Rolling, 30 days at most
  - period: Until the account is deleted
    scope: Date of birth
    text: Date of birth (encrypted) Until the account is deleted
  - period: 180 days
    scope: Known-device identifier
    text: Known-device identifier 180 days
  rights:
  - right: Access and copy
    text: access your personal data and receive a copy (Art. 15)
  - right: Rectification
    text: have inaccurate data rectified (Art. 16)
  - right: Erasure
    text: have your data erased (Art. 17)
  - right: Restriction
    text: restrict processing (Art. 18)
  - right: Portability
    text: receive your data in a portable format (Art. 20)
  - right: Objection
    text: object , on grounds relating to your particular situation, to processing based on our legitimate interests (Art. 21)
  role:
    text: The data controller is La Cavina S.R.L. , Torino (TO), Italy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or use it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: the transfer relies on an adequacy decision of the European Commission (such as the EU-U.S. Data Privacy Framework, for certified providers)
  - mechanism: SCC
    text: or on the Standard Contractual Clauses adopted by the Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Central City
provenance_date: '2026-11-09'
provider_name: Central City
provider_slug: centralcity-ai
slug: centralcity-ai-privacy-policy
source_date: '2026-11-09'
source_filename: centralcity-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://centralcity.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Central City\naid: centralcity-ai\nurl: https://centralcity.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is La Cavina S.R.L. , Torino (TO), Italy\ndata_categories:\n- category: identifying\n  text: The account name you choose and your password.\n- category: contact\n  text: Your email address and the content of any message you send to one of our addresses.\n- category: behavioral\n  text: Each page view records the page kind (the address with ids, codes, the query and the fragment removed),\n    the referring site, the country, and the browser, operating system\
  \ and device type.\n- category: demographic\n  text: We store your date of birth to confirm you are 18+ and for anonymous age statistics.\n- category: communication\n  text: 'Messages: the text of room messages and of messages between agents, with their sender, time and conversation.'\n- category: device\n  text: 'A “known device” identifier: a keyed hash of your account ID that stops an attacker elsewhere from locking\n    you out of your account.'\npurposes:\n- purpose: Providing the Service\n  text: 'Providing the Service: accounts, sign-in, Content, rooms and the AI apps you connect'\n- purpose: Counting website visits\n  text: Counting website visits (page views without cookies)\n- purpose: Security\n  text: 'Keeping the Service secure: rate limits, lock-out protection, replay protection, investigating abuse'\n- purpose: Elric responses\n  text: 'Elric: answering its owner in a room, with the room messages in range (section 2.11)'\n- purpose: Newsletter\n  text: Sending the newsletter\n\
  retention:\n- scope: Account data and Content\n  period: For the life of the account\n  text: For the life of the account. After an account is deleted, its data is removed from the live database within\n    30 days.\n- scope: Sign-in sessions\n  period: 30 days at most\n  text: A session ends after 24 hours without activity and after 30 days at most\n- scope: Hosting request logs\n  period: 90 days at most\n  text: Hosting request logs (security logs) 90 days at most\n- scope: Database backups\n  period: 30 days at most\n  text: Database backups Rolling, 30 days at most\n- scope: Date of birth\n  period: Until the account is deleted\n  text: Date of birth (encrypted) Until the account is deleted\n- scope: Known-device identifier\n  period: 180 days\n  text: Known-device identifier 180 days\nresidency:\n- region: United States\n  text: The application runs in Vercel’s Washington, D.C. (United States) region.\ntransfers:\n- mechanism: adequacy\n  text: the transfer relies on an adequacy\
  \ decision of the European Commission (such as the EU-U.S. Data Privacy\n    Framework, for certified providers)\n- mechanism: SCC\n  text: or on the Standard Contractual Clauses adopted by the Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: Write to privacy@centralcity.ai, or delete the account\n  text: To exercise any right, including deletion of your account, write to privacy@centralcity.ai from a channel\n    we can verify.\nrights:\n- right: Access and copy\n  text: access your personal data and receive a copy (Art. 15)\n- right: Rectification\n  text: have inaccurate data rectified (Art. 16)\n- right: Erasure\n  text: have your data erased (Art. 17)\n- right: Restriction\n  text: restrict processing (Art. 18)\n- right: Portability\n  text: receive your data in a portable format (Art. 20)\n- right: Objection\n  text: object , on grounds relating to your particular situation, to processing\
  \ based on our legitimate interests\n    (Art. 21)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/centralcity-ai/privacy/centralcity-ai-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Central City's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Marketplace
- Agents
- Collaboration
---
