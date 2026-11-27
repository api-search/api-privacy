---
api_specs:
- filename: riverscript-com-openapi-generated.yml
  format: yaml
  label: riverscript-com API
  slug: riverscript-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riverscript-com/openapi/_ae-authored/riverscript-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Account data (email address, settings, balance, subscription status)
  - category: identifying
    text: Security and anti-abuse data. The IP address you registered from, stored with your account record, and the approximate country it resolves to.
  - category: behavioral
    text: PostHog records how signed-in users use the product, such as the pages they open and the features they use, linked to their account and email address.
  - category: communication
    text: Support communications. If you email us or use the in-app feedback and support buttons, we keep your message and our reply.
  - category: device
    text: Error diagnostics. When something breaks, our error tracker (Sentry, hosted in the EU) records the technical details of the failure
  deletion:
    route: Settings → Privacy
    text: Erasure — delete your account and all associated data at any time from Settings → Privacy
  dpa:
    available: true
    text: our Data Processing Terms apply automatically — you do not need to sign anything.
    url: null
  purposes:
  - purpose: Operating the service
    text: Operating the service you paid for Contract performance — Art. 6(1)(b)
  - purpose: Fraud and abuse prevention
    text: Fraud, abuse and account-farming prevention Legitimate interests — Art. 6(1)(f)
  - purpose: Error diagnostics
    text: Error diagnostics and service reliability Legitimate interests — Art. 6(1)(f)
  residency:
  - region: European Union
    text: Core infrastructure (servers and database) is located within the EU.
  retention:
  - period: 7 days
    scope: Source audio/video files
    text: Every audio and video file that reaches our servers is automatically and permanently deleted 7 days after upload
  - period: Until you delete them or close your account
    scope: Transcripts and derived output
    text: Transcripts and derived output. Transcripts, translations, summaries, and AI chat output generated from your content, stored in your account until you delete them or close your account.
  - period: up to 90 days
    scope: Error diagnostics
    text: Sentry's standard event retention (currently up to 90 days)
  - period: 7 days
    scope: Database backups
    text: Deleted data may persist in our database backups for up to 7 days
  rights:
  - right: Access
    text: Access — request a copy of your personal data
  - right: Rectification
    text: Rectification — correct inaccurate data
  - right: Erasure
    text: Erasure — delete your account and all associated data at any time from Settings → Privacy
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format
  - right: Objection
    text: Object — object to processing based on legitimate interests
  - right: Restriction
    text: Restriction — request that we limit processing in certain circumstances
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share it.
  subprocessors:
    text: A full list, including what each one processes and where, is on the Subprocessors page.
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are conducted under Standard Contractual Clauses (SCCs) adopted by the European Commission
  - mechanism: DPF
    text: or under the EU-US Data Privacy Framework where the provider is certified.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: riverscript-com
provenance_date: '2026-11-10'
provider_name: riverscript-com
provider_slug: riverscript-com
slug: riverscript-com-privacy-policy
source_date: '2026-11-10'
source_filename: riverscript-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://riverscript.com/docs/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: riverscript-com\naid: riverscript-com\nurl: https://riverscript.com/docs/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Account data (email address, settings, balance, subscription status)\n- category: identifying\n  text: Security and anti-abuse data. The IP address you registered from, stored with your account record, and the\n    approximate country it resolves to.\n- category: behavioral\n  text: PostHog records how signed-in users use the product, such as the pages they open and the features they use,\n    linked to their\
  \ account and email address.\n- category: communication\n  text: Support communications. If you email us or use the in-app feedback and support buttons, we keep your message\n    and our reply.\n- category: device\n  text: Error diagnostics. When something breaks, our error tracker (Sentry, hosted in the EU) records the technical\n    details of the failure\npurposes:\n- purpose: Operating the service\n  text: Operating the service you paid for Contract performance — Art. 6(1)(b)\n- purpose: Fraud and abuse prevention\n  text: Fraud, abuse and account-farming prevention Legitimate interests — Art. 6(1)(f)\n- purpose: Error diagnostics\n  text: Error diagnostics and service reliability Legitimate interests — Art. 6(1)(f)\nretention:\n- scope: Source audio/video files\n  period: 7 days\n  text: Every audio and video file that reaches our servers is automatically and permanently deleted 7 days after\n    upload\n- scope: Transcripts and derived output\n  period: Until you delete them or close\
  \ your account\n  text: Transcripts and derived output. Transcripts, translations, summaries, and AI chat output generated from\n    your content, stored in your account until you delete them or close your account.\n- scope: Error diagnostics\n  period: up to 90 days\n  text: Sentry's standard event retention (currently up to 90 days)\n- scope: Database backups\n  period: 7 days\n  text: Deleted data may persist in our database backups for up to 7 days\nresidency:\n- region: European Union\n  text: Core infrastructure (servers and database) is located within the EU.\ntransfers:\n- mechanism: SCC\n  text: These transfers are conducted under Standard Contractual Clauses (SCCs) adopted by the European Commission\n- mechanism: DPF\n  text: or under the EU-US Data Privacy Framework where the provider is certified.\nsubprocessors:\n  url: null\n  text: A full list, including what each one processes and where, is on the Subprocessors page.\ndpa:\n  available: true\n  url: null\n  text: our Data\
  \ Processing Terms apply automatically — you do not need to sign anything.\ndeletion:\n  route: Settings → Privacy\n  text: Erasure — delete your account and all associated data at any time from Settings → Privacy\nrights:\n- right: Access\n  text: Access — request a copy of your personal data\n- right: Rectification\n  text: Rectification — correct inaccurate data\n- right: Erasure\n  text: Erasure — delete your account and all associated data at any time from Settings → Privacy\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format\n- right: Objection\n  text: Object — object to processing based on legitimate interests\n- right: Restriction\n  text: Restriction — request that we limit processing in certain circumstances\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share it.\n"
source_yaml_url: https://artifacts.apis.io/riverscript-com/privacy/riverscript-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from riverscript-com's own page on 2026-11-10.
synthetic: false
tags:
- Audio
- Transcription
- Artificial Intelligence
- Video
- Software-as-a-Service
---
