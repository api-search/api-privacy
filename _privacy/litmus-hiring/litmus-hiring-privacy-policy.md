---
api_specs:
- filename: litmus-hiring-invites-api-openapi.yml
  format: yaml
  label: Litmus Hiring Invites API
  slug: litmus-hiring-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litmus-hiring/openapi/litmus-hiring-invites-api-openapi.yml
- filename: litmus-hiring-roles-api-openapi.yml
  format: yaml
  label: Litmus Hiring Roles API
  slug: litmus-hiring-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litmus-hiring/openapi/litmus-hiring-roles-api-openapi.yml
- filename: litmus-hiring-submissions-api-openapi.yml
  format: yaml
  label: Litmus Hiring Submissions API
  slug: litmus-hiring-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/litmus-hiring/openapi/litmus-hiring-submissions-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and profile details provided during sign-up or through third-party authentication (e.g., Google).
  - category: behavioral
    text: Code submissions, commit history, assessment responses submitted by candidates, and records of AI assistant usage during the assessment
  - category: communication
    text: Video and audio are uploaded to Litmus storage.
  - category: device
    text: Pages visited, features used, browser type, and device information collected automatically.
  - category: financial
    text: Billing details processed securely through Stripe. We do not store credit card numbers on our servers.
  - category: location
    text: Litmus reads your calendar events (read-only access) to show your busy times on the interview availability grid
  deletion:
    route: Contact us
    text: You may request deletion by contacting us, subject to applicable legal exceptions and retention that remains necessary and lawful for the relevant purpose.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: To provide and maintain the Service
  - purpose: Candidate assessment administration and evaluation
    text: For candidates, to administer assessments, preserve assessment integrity, generate or support evaluation outputs
  - purpose: Model training and product development
    text: develop, train, test, and improve Litmus products, assessment systems, and AI models using candidate submissions, assessment activity, evaluation outputs, and lawfully received outcomes
  - purpose: De-identified data licensing
    text: We may license individual de-identified assessment records, not only aggregated statistics, to third parties for these purposes
  retention:
  - period: null
    scope: Account and billing data
    text: Account and billing data are retained for as long as your account is active and as needed to comply with legal and accounting obligations.
  - period: null
    scope: Candidate submissions, recordings, transcripts
    text: Candidate submissions, video walkthroughs, interview recordings, audio, transcripts, and assessment activity data are kept until they are deleted
  - period: 30 days
    scope: Refused submissions
    text: If we refuse a submission after receiving it, we keep the refused upload for 30 days so it can be recovered if the refusal was a mistake
  - period: 30 days
    scope: Hosted workspace terminal recordings
    text: every recording 30 days after it was made.
  - period: 30 days
    scope: Deleted candidate recordings on Vercel Blob
    text: we keep the candidates' walkthrough recordings and the interview-call audio stored with Vercel Blob for 30 days so a mistaken deletion can be reversed
  rights:
  - right: Access and copy
    text: Access, know, and receive a copy of your personal information
  - right: Correction
    text: Correct inaccurate information
  - right: Deletion
    text: Request deletion of your data
  - right: Portability
    text: Request portability of your data
  - right: Object or restrict
    text: Object to or restrict certain processing
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent
  - right: Appeal
    text: Appeal a decision on a privacy request
  role:
    text: Litmus Ltd. ("Litmus", "we", "us", or "our") respects your privacy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not currently sell personal information or share personal information for cross-context behavioral advertising as those terms are used under California privacy law.
  subprocessors:
    text: 'Beyond storage and hosting, these are the providers that receive candidate audio, video, or transcripts to process them: Anthropic, for assessment generation and grading'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Litmus Hiring
provenance_date: '2026-11-09'
provider_name: Litmus Hiring
provider_slug: litmus-hiring
slug: litmus-hiring-privacy-policy
source_date: '2026-11-09'
source_filename: litmus-hiring-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://litmushiring.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Litmus Hiring\naid: litmus-hiring\nurl: https://litmushiring.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Litmus Ltd. (\"Litmus\", \"we\", \"us\", or \"our\") respects your privacy.\ndata_categories:\n- category: identifying\n  text: Name, email address, and profile details provided during sign-up or through third-party authentication (e.g.,\n    Google).\n- category: behavioral\n  text: Code submissions, commit history, assessment responses submitted by candidates, and records of AI assistant\n    usage during the assessment\n- category: communication\n  text: Video and audio\
  \ are uploaded to Litmus storage.\n- category: device\n  text: Pages visited, features used, browser type, and device information collected automatically.\n- category: financial\n  text: Billing details processed securely through Stripe. We do not store credit card numbers on our servers.\n- category: location\n  text: Litmus reads your calendar events (read-only access) to show your busy times on the interview availability\n    grid\npurposes:\n- purpose: Provide and maintain the Service\n  text: To provide and maintain the Service\n- purpose: Candidate assessment administration and evaluation\n  text: For candidates, to administer assessments, preserve assessment integrity, generate or support evaluation\n    outputs\n- purpose: Model training and product development\n  text: develop, train, test, and improve Litmus products, assessment systems, and AI models using candidate submissions,\n    assessment activity, evaluation outputs, and lawfully received outcomes\n- purpose: De-identified\
  \ data licensing\n  text: We may license individual de-identified assessment records, not only aggregated statistics, to third parties\n    for these purposes\nretention:\n- scope: Account and billing data\n  period: null\n  text: Account and billing data are retained for as long as your account is active and as needed to comply with\n    legal and accounting obligations.\n- scope: Candidate submissions, recordings, transcripts\n  period: null\n  text: Candidate submissions, video walkthroughs, interview recordings, audio, transcripts, and assessment activity\n    data are kept until they are deleted\n- scope: Refused submissions\n  period: 30 days\n  text: If we refuse a submission after receiving it, we keep the refused upload for 30 days so it can be recovered\n    if the refusal was a mistake\n- scope: Hosted workspace terminal recordings\n  period: 30 days\n  text: every recording 30 days after it was made.\n- scope: Deleted candidate recordings on Vercel Blob\n  period: 30 days\n\
  \  text: we keep the candidates' walkthrough recordings and the interview-call audio stored with Vercel Blob for\n    30 days so a mistaken deletion can be reversed\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Beyond storage and hosting, these are the providers that receive candidate audio, video, or transcripts\n    to process them: Anthropic, for assessment generation and grading'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us\n  text: You may request deletion by contacting us, subject to applicable legal exceptions and retention that remains\n    necessary and lawful for the relevant purpose.\nrights:\n- right: Access and copy\n  text: Access, know, and receive a copy of your personal information\n- right: Correction\n  text: Correct inaccurate information\n- right: Deletion\n  text: Request deletion of your data\n- right: Portability\n  text: Request portability of your data\n- right: Object or restrict\n  text: Object to\
  \ or restrict certain processing\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent\n- right: Appeal\n  text: Appeal a decision on a privacy request\nsale_or_sharing:\n  stance: prohibited\n  text: We do not currently sell personal information or share personal information for cross-context behavioral\n    advertising as those terms are used under California privacy law.\n"
source_yaml_url: https://artifacts.apis.io/litmus-hiring/privacy/litmus-hiring-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Litmus Hiring's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hiring
- Recruiting
- Technical Assessment
- Developer Hiring
- MCP
- Interviewing
- Y Combinator
---
