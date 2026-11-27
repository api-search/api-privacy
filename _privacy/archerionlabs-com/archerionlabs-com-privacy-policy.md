---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: other
    text: the text you give Speed Reader, your account if you sign in, billing records if you pay, and the details you submit when requesting a NASC invitation
  - category: contact
    text: If you make one, we store your email address.
  - category: identifying
    text: If you sign in with Google, we store the basic profile Google hands back with it.
  - category: financial
    text: What lands in our database is the Stripe customer and subscription identifier, the status of the subscription, the tier, and when the current period ends.
  - category: device
    text: basic browser and device type, and event time
  deletion:
    route: Self-serve delete control for reading history rows; account deletion via the Your data control; email for other requests
    text: Every row of your reading history has a delete control.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Speed Reader service
    text: storing your text and running your account is necessary to give you the service you asked for
  - purpose: Rate limiting
    text: Rate limiting is our legitimate interest in keeping the service standing.
  - purpose: Website measurement and bug fixing
    text: We use them to understand which writing and links lead people to NASC and to fix website bugs, never for advertising.
  - purpose: Billing records
    text: Billing records are contractual, and we keep the tax-relevant parts as long as the law requires.
  residency:
  - region: United States
    text: On servers in the United States.
  retention:
  - period: null
    scope: Free plan reading session
    text: It expires one hour after you create it, and it is marked finished the moment you reach the end.
  - period: null
    scope: Paid plan reading history
    text: On a paid plan the row has no expiry, because the point of paying is a reading history that survives. It stays until you delete it
  - period: two hours
    scope: IP rate-limit counter rows
    text: Those counter rows are deleted after two hours.
  - period: 180 days
    scope: Server visit counter rows
    text: They are deleted after 180 days and cannot identify unique visitors.
  - period: up to one year
    scope: PostHog events
    text: The free plan retains events for up to one year.
  - period: seven days
    scope: Database backups
    text: our database host takes a backup every day and keeps each one for seven days.
  rights:
  - right: access
    text: You can ask for a copy of what we hold
  - right: correction
    text: ask us to correct it
  - right: erasure
    text: ask us to delete it
  - right: portability
    text: ask for it in a portable format
  - right: objection
    text: or object to how we are using it
  - right: complain to authority
    text: If you are in the EU or the UK you can also complain to your data protection authority
  role:
    text: For anyone reading this under the GDPR, we are the data controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not run advertising or sell your data.
  subprocessors:
    text: We use the following providers to operate the site. PostHog Processes the cookieless website measurements described in section 07. Vercel Hosts the site and runs the server code. Supabase The database and the sign-in system.
    url: null
  transfers:
  - mechanism: SCC
    text: Our providers cover that transfer under the European Commission’s standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: archerionlabs-com
provenance_date: '2026-11-09'
provider_name: archerionlabs-com
provider_slug: archerionlabs-com
slug: archerionlabs-com-privacy-policy
source_date: '2026-11-09'
source_filename: archerionlabs-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://archerionlabs.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: archerionlabs-com\naid: archerionlabs-com\nurl: https://archerionlabs.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For anyone reading this under the GDPR, we are the data controller.\ndata_categories:\n- category: other\n  text: the text you give Speed Reader, your account if you sign in, billing records if you pay, and the details\n    you submit when requesting a NASC invitation\n- category: contact\n  text: If you make one, we store your email address.\n- category: identifying\n  text: If you sign in with Google, we store the basic profile Google hands back with it.\n- category:\
  \ financial\n  text: What lands in our database is the Stripe customer and subscription identifier, the status of the subscription,\n    the tier, and when the current period ends.\n- category: device\n  text: basic browser and device type, and event time\npurposes:\n- purpose: Provide Speed Reader service\n  text: storing your text and running your account is necessary to give you the service you asked for\n- purpose: Rate limiting\n  text: Rate limiting is our legitimate interest in keeping the service standing.\n- purpose: Website measurement and bug fixing\n  text: We use them to understand which writing and links lead people to NASC and to fix website bugs, never for\n    advertising.\n- purpose: Billing records\n  text: Billing records are contractual, and we keep the tax-relevant parts as long as the law requires.\nretention:\n- scope: Free plan reading session\n  period: null\n  text: It expires one hour after you create it, and it is marked finished the moment you reach the end.\n\
  - scope: Paid plan reading history\n  period: null\n  text: On a paid plan the row has no expiry, because the point of paying is a reading history that survives. It\n    stays until you delete it\n- scope: IP rate-limit counter rows\n  period: two hours\n  text: Those counter rows are deleted after two hours.\n- scope: Server visit counter rows\n  period: 180 days\n  text: They are deleted after 180 days and cannot identify unique visitors.\n- scope: PostHog events\n  period: up to one year\n  text: The free plan retains events for up to one year.\n- scope: Database backups\n  period: seven days\n  text: our database host takes a backup every day and keeps each one for seven days.\nresidency:\n- region: United States\n  text: On servers in the United States.\ntransfers:\n- mechanism: SCC\n  text: Our providers cover that transfer under the European Commission’s standard contractual clauses.\nsubprocessors:\n  url: null\n  text: We use the following providers to operate the site. PostHog\
  \ Processes the cookieless website measurements\n    described in section 07. Vercel Hosts the site and runs the server code. Supabase The database and the sign-in\n    system.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-serve delete control for reading history rows; account deletion via the Your data control; email for\n    other requests\n  text: Every row of your reading history has a delete control.\nrights:\n- right: access\n  text: You can ask for a copy of what we hold\n- right: correction\n  text: ask us to correct it\n- right: erasure\n  text: ask us to delete it\n- right: portability\n  text: ask for it in a portable format\n- right: objection\n  text: or object to how we are using it\n- right: complain to authority\n  text: If you are in the EU or the UK you can also complain to your data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not run advertising or sell your data.\n"
source_yaml_url: https://artifacts.apis.io/archerionlabs-com/privacy/archerionlabs-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from archerionlabs-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Tools
- Enterprise
---
