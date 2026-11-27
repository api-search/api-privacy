---
claim_count: 37
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, and the name and authentication details held by our identity provider.
  - category: device
    text: operating system, CPU architecture
  - category: location
    text: Technical metadata inherent to any network request, including source IP address.
  - category: financial
    text: Your subscription plan, billing history and payment status.
  - category: behavioral
    text: 'PostHog also records session replays across all our sites: mouse movement, clicks, scrolling and page navigation.'
  - category: communication
    text: 'If you complete the onboarding questionnaire: your name, company, intended use case, platform, expected volume, how you found us, and anything you type into the free-text fields.'
  deletion:
    route: Delete your account via the account; contact privacy@ai-coustics.com
    text: Delete your account and we delete the personal data associated with it, except where we are legally required to keep it - invoices being the main case, and the usage records the invoices are built from.
  dpa:
    available: true
    text: Business customers processing third-party personal data can request a data processing agreement at privacy@ai-coustics.com.
    url: null
  purposes:
  - purpose: Authorizing the license and metering usage for billing
    text: 'Purpose: authorizing the license, metering usage for billing, and diagnosing reliability and performance problems.'
  - purpose: Distributing model files
    text: 'Purpose: distributing the model files the SDK needs.'
  - purpose: Producing the transcript requested in the playground
    text: 'Purpose: producing the transcript you asked for.'
  - purpose: Producing call analysis
    text: 'Purpose: producing the analysis you asked for.'
  - purpose: Creating and running accounts and billing
    text: 'Purpose: creating and running your account, billing you, supporting you, and understanding which marketing works.'
  residency:
  - region: Germany (AWS Frankfurt)
    text: Our own infrastructure runs in AWS eu-central-1 in Frankfurt, Germany.
  - region: United States
    text: Personal data reaches the United States through the sub-processors marked above.
  retention:
  - period: 30 days
    scope: Account record
    text: For the life of the account, then 30 days
  - period: 10 years
    scope: Usage and session records
    text: Usage and session records 10 years
  - period: 10 years
    scope: Invoices and payment records
    text: Invoices and payment records 10 years, German statutory retention
  - period: 90 days
    scope: Server and application logs
    text: Server and application logs 90 days
  - period: 24 months
    scope: Product analytics
    text: Product analytics 24 months
  - period: 30 days
    scope: Session replays
    text: Session replays 30 days
  - period: Not retained
    scope: Playground audio
    text: Playground audio Not retained
  - period: Not retained
    scope: Call analysis demo audio
    text: Call analysis demo audio Not retained
  - period: Up to 35 days
    scope: Backups
    text: Backups Up to 35 days
  rights:
  - right: Access
    text: to access your personal data (Art. 15)
  - right: Rectification
    text: to have inaccurate data corrected (Art. 16)
  - right: Erasure
    text: to have your data erased (Art. 17)
  - right: Restriction
    text: to restrict processing (Art. 18)
  - right: Portability
    text: to data portability (Art. 20)
  - right: Objection
    text: to object to processing based on our legitimate interests (Art. 21)
  - right: Withdraw consent
    text: Where processing rests on consent, you can withdraw it at any time from the Privacy Settings control on our cookie policy
  - right: Complain to supervisory authority
    text: You also have the right to complain to a supervisory authority (Art. 77).
  role:
    text: We are a controller for data about your account, your use of the developer portal and our websites, your billing relationship with us, and the telemetry the SDK reports. We are a processor for any personal data contained in audio your own application processes with our SDK.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: We publish changes to this list on our sub-processor page .
    url: https://ai-coustics.com/legal/privacy-policy
  transfers:
  - mechanism: SCC
    text: Transfers outside the EEA are covered by the European Commission's Standard Contractual Clauses, except for Google and LinkedIn, whose transfers to the United States rely on the EU-US Data Privacy Framework.
  - mechanism: DPF
    text: Transfers to Google and LinkedIn in the United States rely on the EU-US Data Privacy Framework instead.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ai-coustics
provenance_date: '2026-11-09'
provider_name: ai-coustics
provider_slug: ai-coustics
slug: ai-coustics-privacy-policy
source_date: '2026-11-09'
source_filename: ai-coustics-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ai-coustics.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ai-coustics\naid: ai-coustics\nurl: https://ai-coustics.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are a controller for data about your account, your use of the developer portal and our websites, your\n    billing relationship with us, and the telemetry the SDK reports. We are a processor for any personal data contained\n    in audio your own application processes with our SDK.\ndata_categories:\n- category: identifying\n  text: Email address, and the name and authentication details held by our identity provider.\n- category: device\n  text: operating system, CPU\
  \ architecture\n- category: location\n  text: Technical metadata inherent to any network request, including source IP address.\n- category: financial\n  text: Your subscription plan, billing history and payment status.\n- category: behavioral\n  text: 'PostHog also records session replays across all our sites: mouse movement, clicks, scrolling and page navigation.'\n- category: communication\n  text: 'If you complete the onboarding questionnaire: your name, company, intended use case, platform, expected\n    volume, how you found us, and anything you type into the free-text fields.'\npurposes:\n- purpose: Authorizing the license and metering usage for billing\n  text: 'Purpose: authorizing the license, metering usage for billing, and diagnosing reliability and performance\n    problems.'\n- purpose: Distributing model files\n  text: 'Purpose: distributing the model files the SDK needs.'\n- purpose: Producing the transcript requested in the playground\n  text: 'Purpose: producing the transcript\
  \ you asked for.'\n- purpose: Producing call analysis\n  text: 'Purpose: producing the analysis you asked for.'\n- purpose: Creating and running accounts and billing\n  text: 'Purpose: creating and running your account, billing you, supporting you, and understanding which marketing\n    works.'\nretention:\n- scope: Account record\n  period: 30 days\n  text: For the life of the account, then 30 days\n- scope: Usage and session records\n  period: 10 years\n  text: Usage and session records 10 years\n- scope: Invoices and payment records\n  period: 10 years\n  text: Invoices and payment records 10 years, German statutory retention\n- scope: Server and application logs\n  period: 90 days\n  text: Server and application logs 90 days\n- scope: Product analytics\n  period: 24 months\n  text: Product analytics 24 months\n- scope: Session replays\n  period: 30 days\n  text: Session replays 30 days\n- scope: Playground audio\n  period: Not retained\n  text: Playground audio Not retained\n- scope:\
  \ Call analysis demo audio\n  period: Not retained\n  text: Call analysis demo audio Not retained\n- scope: Backups\n  period: Up to 35 days\n  text: Backups Up to 35 days\nresidency:\n- region: Germany (AWS Frankfurt)\n  text: Our own infrastructure runs in AWS eu-central-1 in Frankfurt, Germany.\n- region: United States\n  text: Personal data reaches the United States through the sub-processors marked above.\ntransfers:\n- mechanism: SCC\n  text: Transfers outside the EEA are covered by the European Commission's Standard Contractual Clauses, except\n    for Google and LinkedIn, whose transfers to the United States rely on the EU-US Data Privacy Framework.\n- mechanism: DPF\n  text: Transfers to Google and LinkedIn in the United States rely on the EU-US Data Privacy Framework instead.\nsubprocessors:\n  url: https://ai-coustics.com/legal/privacy-policy\n  text: We publish changes to this list on our sub-processor page .\ndpa:\n  available: true\n  url: null\n  text: Business customers\
  \ processing third-party personal data can request a data processing agreement at privacy@ai-coustics.com.\ndeletion:\n  route: Delete your account via the account; contact privacy@ai-coustics.com\n  text: Delete your account and we delete the personal data associated with it, except where we are legally required\n    to keep it - invoices being the main case, and the usage records the invoices are built from.\nrights:\n- right: Access\n  text: to access your personal data (Art. 15)\n- right: Rectification\n  text: to have inaccurate data corrected (Art. 16)\n- right: Erasure\n  text: to have your data erased (Art. 17)\n- right: Restriction\n  text: to restrict processing (Art. 18)\n- right: Portability\n  text: to data portability (Art. 20)\n- right: Objection\n  text: to object to processing based on our legitimate interests (Art. 21)\n- right: Withdraw consent\n  text: Where processing rests on consent, you can withdraw it at any time from the Privacy Settings control on\n    our cookie\
  \ policy\n- right: Complain to supervisory authority\n  text: You also have the right to complain to a supervisory authority (Art. 77).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/ai-coustics/privacy/ai-coustics-privacy-policy.yml
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
summary_line: 37 quoted statements, read from ai-coustics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Audio
- Speech Enhancement
- Voice AI
- Speech Recognition
- SDK
- Real-Time
- Machine Learning
---
