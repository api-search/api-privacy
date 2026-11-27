---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Accounts. Signing in is optional and goes through Google or Microsoft . We store the provider's name, the stable account id it gives us, and your name and email address as the provider reports them.
  - category: contact
    text: the email address only if you chose to give one
  - category: location
    text: and a two-letter country code. These records hold no IP address, no browser identifier and none of your agenda's contents.
  - category: device
    text: Web server access logs. IP address, user agent, requested path and timestamp for every request.
  - category: behavioral
    text: On the templates page, what you type into the search box is recorded in Matomo once you stop typing, with the number of templates it found
  - category: financial
    text: we keep your subscription status, current billing period end, the identifiers Stripe gives us for that subscription, and a record of the billing events Stripe notifies us of.
  - category: communication
    text: What you write on the feedback board or send us by email
  deletion:
    route: delete the agenda via connected assistant (delete_agenda tool), or email support with the share token; account deletion requires canceling any live subscription first
    text: If your account has a live subscription, it must be canceled before the account itself can be deleted
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: We rely instead on legitimate interest to operate the service, keep it secure, and understand product usage through analytics
  - purpose: billing and subscription
    text: and on contract to bill and provide a Plus subscription to the people who buy one.
  residency:
  - region: Germany
    text: Data is stored at rest on servers in Germany.
  - region: United States
    text: Lignologic Solutions LLC is a United States entity, so personal data is also accessible from the US by the staff who operate the service.
  retention:
  - period: 7 days
    scope: anonymous agenda
    text: An anonymous agenda — one nobody has signed in to claim — is deleted 7 days after it was created, on a schedule
  - period: 30 days
    scope: web server access logs
    text: Web server access logs are kept for 30 days and then rotated out.
  - period: 12 months after the item is closed
    scope: feedback submissions
    text: Feedback submissions are kept while open, and for 12 months after the item is closed.
  - period: 180 days
    scope: Matomo raw visit data
    text: Matomo's raw visit data is kept for 180 days and purged automatically after that
  - period: as long as accounting and tax obligations require
    scope: billing records
    text: Billing records are kept for as long as accounting and tax obligations require.
  rights:
  - right: access
    text: you have the right to access, correct, erase, restrict or object to our processing of your data
  - right: portability
    text: and the right to receive it in a portable format
  - right: complaint
    text: You also have the right to lodge a complaint with your local data protection supervisory authority.
  - right: know, delete, correct, opt out of sale or sharing (CCPA)
    text: you have the right to know what personal information we hold about you, to delete it, to correct it, to opt out of its sale or sharing
  role:
    text: Lignologic Solutions LLC, a company formed in Wisconsin, at USA, is the controller of the personal data described on this page.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information
  subprocessors:
    text: 'Those providers are: Hetzner (hosting), Cloudflare (DNS, CDN and proxy, and R2 storage for Plus logo uploads), Stripe (payments), our transactional mail provider, and — only for users who choose to sign in — Google or Microsoft (identity).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BriefMe
provenance_date: '2026-11-09'
provider_name: BriefMe
provider_slug: briefme-us
slug: briefme-us-privacy-policy
source_date: '2026-11-09'
source_filename: briefme-us-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://briefme.us/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BriefMe\naid: briefme-us\nurl: https://briefme.us/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Lignologic Solutions LLC, a company formed in Wisconsin, at USA, is the controller of the personal data\n    described on this page.\ndata_categories:\n- category: identifying\n  text: Accounts. Signing in is optional and goes through Google or Microsoft . We store the provider's name, the\n    stable account id it gives us, and your name and email address as the provider reports them.\n- category: contact\n  text: the email address only if you chose to give one\n- category: location\n\
  \  text: and a two-letter country code. These records hold no IP address, no browser identifier and none of your\n    agenda's contents.\n- category: device\n  text: Web server access logs. IP address, user agent, requested path and timestamp for every request.\n- category: behavioral\n  text: On the templates page, what you type into the search box is recorded in Matomo once you stop typing, with\n    the number of templates it found\n- category: financial\n  text: we keep your subscription status, current billing period end, the identifiers Stripe gives us for that subscription,\n    and a record of the billing events Stripe notifies us of.\n- category: communication\n  text: What you write on the feedback board or send us by email\npurposes:\n- purpose: operate the service\n  text: We rely instead on legitimate interest to operate the service, keep it secure, and understand product usage\n    through analytics\n- purpose: billing and subscription\n  text: and on contract to bill and\
  \ provide a Plus subscription to the people who buy one.\nretention:\n- scope: anonymous agenda\n  period: 7 days\n  text: An anonymous agenda — one nobody has signed in to claim — is deleted 7 days after it was created, on a schedule\n- scope: web server access logs\n  period: 30 days\n  text: Web server access logs are kept for 30 days and then rotated out.\n- scope: feedback submissions\n  period: 12 months after the item is closed\n  text: Feedback submissions are kept while open, and for 12 months after the item is closed.\n- scope: Matomo raw visit data\n  period: 180 days\n  text: Matomo's raw visit data is kept for 180 days and purged automatically after that\n- scope: billing records\n  period: as long as accounting and tax obligations require\n  text: Billing records are kept for as long as accounting and tax obligations require.\nresidency:\n- region: Germany\n  text: Data is stored at rest on servers in Germany.\n- region: United States\n  text: Lignologic Solutions LLC is\
  \ a United States entity, so personal data is also accessible from the US by the\n    staff who operate the service.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Those providers are: Hetzner (hosting), Cloudflare (DNS, CDN and proxy, and R2 storage for Plus logo uploads),\n    Stripe (payments), our transactional mail provider, and — only for users who choose to sign in — Google or Microsoft\n    (identity).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete the agenda via connected assistant (delete_agenda tool), or email support with the share token;\n    account deletion requires canceling any live subscription first\n  text: If your account has a live subscription, it must be canceled before the account itself can be deleted\nrights:\n- right: access\n  text: you have the right to access, correct, erase, restrict or object to our processing of your data\n- right: portability\n  text: and the right to receive it in a portable format\n- right: complaint\n\
  \  text: You also have the right to lodge a complaint with your local data protection supervisory authority.\n- right: know, delete, correct, opt out of sale or sharing (CCPA)\n  text: you have the right to know what personal information we hold about you, to delete it, to correct it, to\n    opt out of its sale or sharing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information\n"
source_yaml_url: https://artifacts.apis.io/briefme-us/privacy/briefme-us-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from BriefMe's own page on 2026-11-09.
synthetic: false
tags:
- Timer
- Meetings
- Productivity
- Software-as-a-Service
- Free
---
