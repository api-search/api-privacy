---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address , which is how you sign in.
  - category: health
    text: 'Much of this is health information. We treat it as sensitive: it''s used to provide Body Lab to you and for nothing else.'
  - category: location
    text: It only uses your location if you allow it
  - category: device
    text: Signing in from an app or device stores a token (hashed, so it can't be read back) and the device's name.
  - category: health
    text: 'Recovery readings : resting heart rate, heart-rate variability, time asleep, sleep score and device energy scores.'
  - category: demographic
    text: sex, birth year, height, weight
  - category: communication
    text: Our email provider sends sign-in emails and the beta access email, so it processes your email address and each code
  deletion:
    route: In-app account deletion (Settings → Account) or per-item deletion
    text: Deleting your account (Settings → Account) removes your profile, activities, readings, lab results, sessions, connected services and connected apps from our database immediately, and deletes your uploaded files.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Body Lab
    text: 'To provide Body Lab: calculate training load and recovery, prescribe sessions, and show your history.'
  - purpose: Sign-in and security
    text: To sign you in, keep your account secure, and prevent abuse.
  - purpose: Import from connected services
    text: To import from services you connect, and answer apps you connect.
  - purpose: Beta waitlist email
    text: To email you once when there's a spot in the beta, if you joined the waitlist.
  - purpose: Diagnostics
    text: To diagnose problems and improve how Body Lab works.
  residency:
  - region: United States
    text: Your information is processed in the United States.
  retention:
  - period: as long as you have an account
    scope: Account data
    text: We keep your information for as long as you have an account.
  - period: within a day
    scope: Sign-in codes and request addresses
    text: Codes and those addresses are deleted within a day.
  - period: 30 days
    scope: Deleted files
    text: deleted files remain recoverable in our file storage for 30 days
  - period: 30 days
    scope: Nightly database backups
    text: nightly database backups are kept for 30 days
  rights:
  - right: Access and download
    text: See and correct your data in the app, and download a copy of it from Settings.
  - right: Object or restrict processing, portability
    text: you may have further rights, such as to object to or restrict processing or to data portability.
  - right: Complain to authority
    text: You can also complain to your local data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your information, use it for advertising, or share it with anyone to use for their own purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Body Lab
provenance_date: '2026-11-09'
provider_name: Body Lab
provider_slug: bodylab-lol
slug: bodylab-lol-privacy-policy
source_date: '2026-11-09'
source_filename: bodylab-lol-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bodylab.lol/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Body Lab\naid: bodylab-lol\nurl: https://bodylab.lol/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address , which is how you sign in.\n- category: health\n  text: 'Much of this is health information. We treat it as sensitive: it''s used to provide Body Lab to you and\n    for nothing else.'\n- category: location\n  text: It only uses your location if you allow it\n- category: device\n  text: Signing in from an app or device stores a token (hashed, so it can't be read back) and the device's name.\n- category: health\n  text:\
  \ 'Recovery readings : resting heart rate, heart-rate variability, time asleep, sleep score and device energy\n    scores.'\n- category: demographic\n  text: sex, birth year, height, weight\n- category: communication\n  text: Our email provider sends sign-in emails and the beta access email, so it processes your email address and\n    each code\npurposes:\n- purpose: Provide Body Lab\n  text: 'To provide Body Lab: calculate training load and recovery, prescribe sessions, and show your history.'\n- purpose: Sign-in and security\n  text: To sign you in, keep your account secure, and prevent abuse.\n- purpose: Import from connected services\n  text: To import from services you connect, and answer apps you connect.\n- purpose: Beta waitlist email\n  text: To email you once when there's a spot in the beta, if you joined the waitlist.\n- purpose: Diagnostics\n  text: To diagnose problems and improve how Body Lab works.\nretention:\n- scope: Account data\n  period: as long as you have an account\n\
  \  text: We keep your information for as long as you have an account.\n- scope: Sign-in codes and request addresses\n  period: within a day\n  text: Codes and those addresses are deleted within a day.\n- scope: Deleted files\n  period: 30 days\n  text: deleted files remain recoverable in our file storage for 30 days\n- scope: Nightly database backups\n  period: 30 days\n  text: nightly database backups are kept for 30 days\nresidency:\n- region: United States\n  text: Your information is processed in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app account deletion (Settings → Account) or per-item deletion\n  text: Deleting your account (Settings → Account) removes your profile, activities, readings, lab results, sessions,\n    connected services and connected apps from our database immediately, and deletes your uploaded files.\nrights:\n- right: Access and download\n  text: See\
  \ and correct your data in the app, and download a copy of it from Settings.\n- right: Object or restrict processing, portability\n  text: you may have further rights, such as to object to or restrict processing or to data portability.\n- right: Complain to authority\n  text: You can also complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your information, use it for advertising, or share it with anyone to use for their own purposes.\n"
source_yaml_url: https://artifacts.apis.io/bodylab-lol/privacy/bodylab-lol-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Body Lab's own page on 2026-11-09.
synthetic: false
tags:
- Fitness
- Health
- Training
- Free
- Company
---
