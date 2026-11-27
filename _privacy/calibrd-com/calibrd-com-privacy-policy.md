---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in we collect your email address via Clerk (our authentication provider).
  - category: contact
    text: You give us an email address, we write the report, and we send it to you as a PDF.
  - category: financial
    text: Payments are handled by Stripe — we do not see or store your card details.
  - category: communication
    text: If you record a spoken answer — in the free practice tool on our interview-prep guides, in the optional Speak input mode, or while running a voice mock interview — your audio is transmitted to OpenAI's Whisper API for transcription.
  - category: professional
    text: CV text. When you are signed in, the CV you paste or upload stays in your account, encrypted at rest, only to personalize your reports
  deletion:
    route: Delete my account in workspace profile, or email privacy@calibrd.com
    text: To delete everything, open your profile in the workspace and choose Delete my account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate you and manage your account
    text: Authenticate you and manage your account
  - purpose: Generate interview report and AI coaching
    text: Generate your interview report and AI coaching responses
  - purpose: Transcribe spoken answers and voice interviewer questions
    text: Transcribe spoken answers, and voice the interviewer's questions, when you use Speak mode or a mock interview
  - purpose: Enforce credit and plan limits
    text: Enforce credit and plan limits
  - purpose: Send transactional emails
    text: Send transactional emails (sign-in codes, receipts, and the PDF report from a free scan or free resume review)
  retention:
  - period: null
    scope: Signed-in workspace and account records
    text: Your workspace and account records are kept for as long as your account is active.
  - period: null
    scope: Free scan and resume review email address
    text: The email address you gave for a free scan or free resume review, which we keep so the offer stays one per address, and to send you guides if you ticked the box.
  - period: null
    scope: Anonymous voice practice count per IP
    text: A count of anonymous voice practice per IP address, which resets after a day.
  - period: null
    scope: Free scan CV, job description and report
    text: Your CV, the job description and the report are all discarded once the email is sent.
  - period: null
    scope: Audio for transcription
    text: The audio is not stored after the transcript is returned, and OpenAI does not train on API traffic by default.
  rights:
  - right: access, correct, export, or delete
    text: Depending on your jurisdiction you may have the right to access, correct, export, or delete your personal data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, share it with advertisers, or use it to train AI models.
  subprocessors:
    text: 'Third-party services These are every company that touches your data on our behalf, and what each one is for: Clerk — authentication and session management Stripe — payment processing Vercel — hosting for the website and our API, and the page-view analytics described below Neon — the database holding account records'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Calibrd
provenance_date: '2026-11-09'
provider_name: Calibrd
provider_slug: calibrd-com
slug: calibrd-com-privacy-policy
source_date: '2026-11-09'
source_filename: calibrd-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.calibrd.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Calibrd\naid: calibrd-com\nurl: https://www.calibrd.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign in we collect your email address via Clerk (our authentication provider).\n- category: contact\n  text: You give us an email address, we write the report, and we send it to you as a PDF.\n- category: financial\n  text: Payments are handled by Stripe — we do not see or store your card details.\n- category: communication\n  text: If you record a spoken answer — in the free practice tool on our interview-prep guides,\
  \ in the optional\n    Speak input mode, or while running a voice mock interview — your audio is transmitted to OpenAI's Whisper API\n    for transcription.\n- category: professional\n  text: CV text. When you are signed in, the CV you paste or upload stays in your account, encrypted at rest, only\n    to personalize your reports\npurposes:\n- purpose: Authenticate you and manage your account\n  text: Authenticate you and manage your account\n- purpose: Generate interview report and AI coaching\n  text: Generate your interview report and AI coaching responses\n- purpose: Transcribe spoken answers and voice interviewer questions\n  text: Transcribe spoken answers, and voice the interviewer's questions, when you use Speak mode or a mock interview\n- purpose: Enforce credit and plan limits\n  text: Enforce credit and plan limits\n- purpose: Send transactional emails\n  text: Send transactional emails (sign-in codes, receipts, and the PDF report from a free scan or free resume review)\nretention:\n\
  - scope: Signed-in workspace and account records\n  period: null\n  text: Your workspace and account records are kept for as long as your account is active.\n- scope: Free scan and resume review email address\n  period: null\n  text: The email address you gave for a free scan or free resume review, which we keep so the offer stays one per\n    address, and to send you guides if you ticked the box.\n- scope: Anonymous voice practice count per IP\n  period: null\n  text: A count of anonymous voice practice per IP address, which resets after a day.\n- scope: Free scan CV, job description and report\n  period: null\n  text: Your CV, the job description and the report are all discarded once the email is sent.\n- scope: Audio for transcription\n  period: null\n  text: The audio is not stored after the transcript is returned, and OpenAI does not train on API traffic by default.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Third-party services These are every company that\
  \ touches your data on our behalf, and what each one is\n    for: Clerk — authentication and session management Stripe — payment processing Vercel — hosting for the website\n    and our API, and the page-view analytics described below Neon — the database holding account records'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete my account in workspace profile, or email privacy@calibrd.com\n  text: To delete everything, open your profile in the workspace and choose Delete my account\nrights:\n- right: access, correct, export, or delete\n  text: Depending on your jurisdiction you may have the right to access, correct, export, or delete your personal\n    data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, share it with advertisers, or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/calibrd-com/privacy/calibrd-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Calibrd's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Interview Coaching
- Resume
- Hiring
---
