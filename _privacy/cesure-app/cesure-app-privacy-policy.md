---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your email address and authentication credentials via Supabase (hosted in the EU)
  - category: contact
    text: Confirming your address, resetting your password and the alerts about your account (your password changed, a verification method added or removed) are emails our own server composes and hands to that relay, which therefore receives your email address
  - category: financial
    text: we store with your account the listing bought and its version, the amount paid and the VAT collected
  - category: behavioral
    text: we store how long you played and edited, how many tracks, imports, exports and sessions you made, and one line per day of activity
  - category: device
    text: usage data (screen views, features used, device model, OS version) is collected via Firebase Analytics
  - category: location
    text: the app never receives more than "given" or "missing"
  - category: communication
    text: we store your message along with your app version, platform, language and the screen you sent it from
  - category: demographic
    text: country of residence, status, social security number (an individual resident in France) or business number (SIRET), year of exemption
  deletion:
    route: Delete account button on the "Me" screen; or write to contact@cesure.app
    text: The "Me" screen carries a button that deletes it, and that button can also refuse
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate you and provide account-related features
    text: Account data is used solely to authenticate you and provide account-related features.
  - purpose: show your own progress
    text: Practice statistics are used to show you your own progress; your streak, computed from them, is also shown to your friends.
  - purpose: grant and verify paid access
    text: Subscription data is used solely to grant and verify your access to the paid features.
  - purpose: fix crashes and performance
    text: Crash reports and performance data are used to identify and fix what breaks or drags.
  - purpose: understand app usage
    text: Analytics data is used to understand how the app is used and prioritize improvements.
  - purpose: pay creators and meet tax obligations
    text: A creator's tax data is used solely to pay them and to make the withholdings and returns the law requires of Cesure.
  residency:
  - region: EU
    text: we store your email address and authentication credentials via Supabase (hosted in the EU)
  retention:
  - period: null
    scope: account data
    text: Account data is retained as long as your account exists.
  - period: up to 14 months
    scope: crash and analytics data at Firebase
    text: crash and analytics data is retained for up to 14 months per Firebase policy
  - period: 14 days
    scope: drafts from public tools
    text: That score is kept on our servers as a draft, named by a random identifier, for 14 days after the last time it is read or changed, then deleted
  - period: 30 minutes
    scope: session files
    text: it transits through our servers temporarily (deleted after 30 minutes)
  - period: fourteen days
    scope: unsaved tab drafts on device
    text: a draft you never save is discarded after fourteen days
  - period: six years
    scope: creator payouts and tax documents
    text: kept for as long as tax law requires (six years, article L102 B of the French Tax Procedure Code)
  rights:
  - right: access
    text: You may request access to, correction of, or deletion of your personal data by contacting us at contact@cesure.app.
  - right: correction
    text: You may request access to, correction of, or deletion of your personal data by contacting us at contact@cesure.app.
  - right: deletion
    text: You may request access to, correction of, or deletion of your personal data by contacting us at contact@cesure.app.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data to third parties.
  subprocessors:
    text: 'Third-Party Services: Supabase (supabase.com) — authentication, account storage, and the scores, profiles and statistics described above.'
    url: null
  transfers:
  - mechanism: other
    text: What it reads leaves Cesure for its provider — OpenAI for ChatGPT (chatgpt.com), Anthropic for Claude (claude.ai, claude.com)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cesure
provenance_date: '2026-11-09'
provider_name: Cesure
provider_slug: cesure-app
slug: cesure-app-privacy-policy
source_date: '2026-11-09'
source_filename: cesure-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cesure.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cesure\naid: cesure-app\nurl: https://cesure.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we store your email address and authentication credentials via Supabase (hosted in the EU)\n- category: contact\n  text: Confirming your address, resetting your password and the alerts about your account (your password changed,\n    a verification method added or removed) are emails our own server composes and hands to that relay, which therefore\n    receives your email address\n- category: financial\n  text: we store with your account\
  \ the listing bought and its version, the amount paid and the VAT collected\n- category: behavioral\n  text: we store how long you played and edited, how many tracks, imports, exports and sessions you made, and one\n    line per day of activity\n- category: device\n  text: usage data (screen views, features used, device model, OS version) is collected via Firebase Analytics\n- category: location\n  text: the app never receives more than \"given\" or \"missing\"\n- category: communication\n  text: we store your message along with your app version, platform, language and the screen you sent it from\n- category: demographic\n  text: country of residence, status, social security number (an individual resident in France) or business number\n    (SIRET), year of exemption\npurposes:\n- purpose: authenticate you and provide account-related features\n  text: Account data is used solely to authenticate you and provide account-related features.\n- purpose: show your own progress\n  text: Practice\
  \ statistics are used to show you your own progress; your streak, computed from them, is also shown\n    to your friends.\n- purpose: grant and verify paid access\n  text: Subscription data is used solely to grant and verify your access to the paid features.\n- purpose: fix crashes and performance\n  text: Crash reports and performance data are used to identify and fix what breaks or drags.\n- purpose: understand app usage\n  text: Analytics data is used to understand how the app is used and prioritize improvements.\n- purpose: pay creators and meet tax obligations\n  text: A creator's tax data is used solely to pay them and to make the withholdings and returns the law requires\n    of Cesure.\nretention:\n- scope: account data\n  period: null\n  text: Account data is retained as long as your account exists.\n- scope: crash and analytics data at Firebase\n  period: up to 14 months\n  text: crash and analytics data is retained for up to 14 months per Firebase policy\n- scope: drafts from\
  \ public tools\n  period: 14 days\n  text: That score is kept on our servers as a draft, named by a random identifier, for 14 days after the last time\n    it is read or changed, then deleted\n- scope: session files\n  period: 30 minutes\n  text: it transits through our servers temporarily (deleted after 30 minutes)\n- scope: unsaved tab drafts on device\n  period: fourteen days\n  text: a draft you never save is discarded after fourteen days\n- scope: creator payouts and tax documents\n  period: six years\n  text: kept for as long as tax law requires (six years, article L102 B of the French Tax Procedure Code)\nresidency:\n- region: EU\n  text: we store your email address and authentication credentials via Supabase (hosted in the EU)\ntransfers:\n- mechanism: other\n  text: What it reads leaves Cesure for its provider — OpenAI for ChatGPT (chatgpt.com), Anthropic for Claude (claude.ai,\n    claude.com)\nsubprocessors:\n  url: null\n  text: 'Third-Party Services: Supabase (supabase.com)\
  \ — authentication, account storage, and the scores, profiles\n    and statistics described above.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account button on the \"Me\" screen; or write to contact@cesure.app\n  text: The \"Me\" screen carries a button that deletes it, and that button can also refuse\nrights:\n- right: access\n  text: You may request access to, correction of, or deletion of your personal data by contacting us at contact@cesure.app.\n- right: correction\n  text: You may request access to, correction of, or deletion of your personal data by contacting us at contact@cesure.app.\n- right: deletion\n  text: You may request access to, correction of, or deletion of your personal data by contacting us at contact@cesure.app.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/cesure-app/privacy/cesure-app-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Cesure's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Guitar
- Artificial Intelligence
- Web App
- Collaboration
---
