---
api_specs:
- filename: botdoor-co-openapi-generated.yml
  format: yaml
  label: Botdoor API
  slug: botdoor-co-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botdoor-co/openapi/_ae-authored/botdoor-co-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and workspace name.
  - category: contact
    text: Waitlist email. The address you enter on botdoor.co, and when you joined.
  - category: device
    text: Our host records each request's IP address, browser user agent, page and status, as web servers normally do.
  - category: behavioral
    text: Cloudflare's script records the page address, the referring page, your browser, device type and country, and timing data
  - category: communication
    text: A queue of the emails we send (recipient, type, when, and whether it was delivered), kept 30 days.
  - category: other
    text: Posts and media. The text, thread, poll and option settings of each post, which key or person created it, its approval status and live links.
  deletion:
    route: Email privacy@botdoor.co
    text: Email privacy@botdoor.co and we will delete your account, posts, previews and waitlist entry, and disconnect your social accounts at Zernio.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide Botdoor: sign you in, run your bots'' API keys, publish the posts you approve or allow, and show their status.'
  - purpose: Service emails
    text: 'To send service emails: claim and password-reset links, and, unless you turn them off in Settings, posts waiting for approval, posted, failed, and accounts that need reconnecting.'
  - purpose: Security
    text: 'To keep Botdoor secure and working: rate limits, abuse prevention, debugging.'
  - purpose: Waitlist and updates
    text: 'To tell waitlist emails when sign-up in the browser opens, and to send Botdoor updates. Legal basis: your consent, which you can withdraw at any time.'
  residency:
  - region: Singapore
    text: Botdoor's own database and files are stored in Singapore.
  - region: UK and Western Europe
    text: Zernio stores what it holds mainly in the UK and Western Europe, and our providers may access or process data in other countries, including the United States.
  retention:
  - period: while your account is open
    scope: Account, posts and previews
    text: 'Account, posts and previews: while your account is open. We delete them when you ask us to close it.'
  - period: 24 hours old
    scope: Unused uploads
    text: media that no post uses is deleted automatically once it is 24 hours old, at the next weekly cleanup.
  - period: 7 days after sign-up
    scope: Unclaimed workspaces
    text: a workspace your bot created and you never claimed is deleted 7 days after sign-up, with its keys and posts.
  - period: about 2 days
    scope: Security counters
    text: we delete every counter automatically about 2 days after it started (sooner on request).
  - period: 30 days
    scope: Emails queue
    text: A queue of the emails we send (recipient, type, when, and whether it was delivered), kept 30 days.
  rights:
  - right: Access
    text: You can ask to see the personal information we hold about you, correct it, get a copy, delete it, or object to or limit how we use it
  - right: Withdraw consent
    text: you can withdraw consent at any time.
  role:
    text: We are responsible for the personal information described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information, share it for advertising, or use it to train AI models.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: our providers may access or process data in other countries, including the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Botdoor
provenance_date: '2026-11-09'
provider_name: Botdoor
provider_slug: botdoor-co
slug: botdoor-co-privacy-policy
source_date: '2026-11-09'
source_filename: botdoor-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://botdoor.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Botdoor\naid: botdoor-co\nurl: https://botdoor.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for the personal information described here.\ndata_categories:\n- category: identifying\n  text: Your email address and workspace name.\n- category: contact\n  text: Waitlist email. The address you enter on botdoor.co, and when you joined.\n- category: device\n  text: Our host records each request's IP address, browser user agent, page and status, as web servers normally\n    do.\n- category: behavioral\n  text: Cloudflare's script records the page address, the referring\
  \ page, your browser, device type and country,\n    and timing data\n- category: communication\n  text: A queue of the emails we send (recipient, type, when, and whether it was delivered), kept 30 days.\n- category: other\n  text: Posts and media. The text, thread, poll and option settings of each post, which key or person created it,\n    its approval status and live links.\npurposes:\n- purpose: Provide the service\n  text: 'To provide Botdoor: sign you in, run your bots'' API keys, publish the posts you approve or allow, and\n    show their status.'\n- purpose: Service emails\n  text: 'To send service emails: claim and password-reset links, and, unless you turn them off in Settings, posts\n    waiting for approval, posted, failed, and accounts that need reconnecting.'\n- purpose: Security\n  text: 'To keep Botdoor secure and working: rate limits, abuse prevention, debugging.'\n- purpose: Waitlist and updates\n  text: 'To tell waitlist emails when sign-up in the browser opens, and to\
  \ send Botdoor updates. Legal basis: your\n    consent, which you can withdraw at any time.'\nretention:\n- scope: Account, posts and previews\n  period: while your account is open\n  text: 'Account, posts and previews: while your account is open. We delete them when you ask us to close it.'\n- scope: Unused uploads\n  period: 24 hours old\n  text: media that no post uses is deleted automatically once it is 24 hours old, at the next weekly cleanup.\n- scope: Unclaimed workspaces\n  period: 7 days after sign-up\n  text: a workspace your bot created and you never claimed is deleted 7 days after sign-up, with its keys and posts.\n- scope: Security counters\n  period: about 2 days\n  text: we delete every counter automatically about 2 days after it started (sooner on request).\n- scope: Emails queue\n  period: 30 days\n  text: A queue of the emails we send (recipient, type, when, and whether it was delivered), kept 30 days.\nresidency:\n- region: Singapore\n  text: Botdoor's own database and\
  \ files are stored in Singapore.\n- region: UK and Western Europe\n  text: Zernio stores what it holds mainly in the UK and Western Europe, and our providers may access or process\n    data in other countries, including the United States.\ntransfers:\n- mechanism: other\n  text: our providers may access or process data in other countries, including the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@botdoor.co\n  text: Email privacy@botdoor.co and we will delete your account, posts, previews and waitlist entry, and disconnect\n    your social accounts at Zernio.\nrights:\n- right: Access\n  text: You can ask to see the personal information we hold about you, correct it, get a copy, delete it, or object\n    to or limit how we use it\n- right: Withdraw consent\n  text: you can withdraw consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information, share\
  \ it for advertising, or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/botdoor-co/privacy/botdoor-co-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Botdoor's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Automation
- AI Bots
- Scheduling
- Marketing
---
