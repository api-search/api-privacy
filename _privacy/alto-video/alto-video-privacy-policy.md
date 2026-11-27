---
api_specs:
- filename: alto-video-openapi-generated.yml
  format: yaml
  label: Alto API
  slug: alto-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alto-video/openapi/_ae-authored/alto-video-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: your IP address, and the approximate city (with its coordinates), region, country and network Cloudflare derives from it
  - category: contact
    text: your name, email address and, if you use it, your Google account's email and profile name
  - category: behavioral
    text: which parts of the video played, for how long, at what speed, with pauses, seeks and buffering counts
  - category: device
    text: your browser, operating system, language, timezone, screen size, and the page that linked you
  - category: communication
    text: if the creator turned on an email gate, the email address you enter before the video plays
  - category: financial
    text: Payment details never touch our servers; see Polar below.
  deletion:
    route: write to support@alto.video or contact the creator who sent the link
    text: To delete your account, or to ask what we hold about you and get a copy, write to support@alto.video from the address on the account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: show creators viewing analytics
    text: the creator who sent it can see how the video was watched
  - purpose: advertising
    text: We do not use this data for advertising, sell it, or combine it across creators.
  - purpose: product email
    text: We email you to confirm your address, to reset a password you have forgotten
  - purpose: product analytics
    text: PostHog measures how alto.video is used.
  residency:
  - region: United States
    text: Cloudflare stores the database and files in its global network, primarily in the United States, and serves videos from the location nearest the viewer.
  retention:
  - period: until the video is deleted
    scope: video and its visit records
    text: A video and everything about it (the file, the copies we make of it, its cover, its visit records with their IP addresses, its transcript, and its title, description, chapters and link names) stays until the video is deleted
  - period: six months
    scope: free plan videos nobody plays
    text: When nobody but its creator has played a free plan video for six months, we email the creator 30 days and 7 days before archiving it
  - period: null
    scope: archived video
    text: Thirty days later it is deleted exactly as above, unless the creator keeps it or upgrades to Pro first.
  - period: up to 30 days
    scope: session cookies
    text: Session cookies keep you signed in for up to 30 days.
  - period: 180 days
    scope: viewer ID cookie
    text: a random viewer ID, stored in a cookie named alto_viewer for 180 days
  - period: within 30 days
    scope: database backups
    text: Backups of the database roll off within 30 days, so what is deleted is gone from them by then.
  rights:
  - right: access
    text: these are the access, portability, correction and erasure rights that law gives you
  - right: erasure
    text: these are the access, portability, correction and erasure rights that law gives you
  - right: complain to authority
    text: you may also complain to your local authority
  role:
    text: Alto is run by Twisted Vector LLC .
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not use this data for advertising, sell it, or combine it across creators.
  subprocessors:
    text: 'Only the companies that run the pieces we do not: Cloudflare hosts everything'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Alto
provenance_date: '2026-11-09'
provider_name: Alto
provider_slug: alto-video
slug: alto-video-privacy-policy
source_date: '2026-11-09'
source_filename: alto-video-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alto.video/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Alto\naid: alto-video\nurl: https://alto.video/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Alto is run by Twisted Vector LLC .\ndata_categories:\n- category: identifying\n  text: your IP address, and the approximate city (with its coordinates), region, country and network Cloudflare\n    derives from it\n- category: contact\n  text: your name, email address and, if you use it, your Google account's email and profile name\n- category: behavioral\n  text: which parts of the video played, for how long, at what speed, with pauses, seeks and buffering counts\n- category: device\n  text:\
  \ your browser, operating system, language, timezone, screen size, and the page that linked you\n- category: communication\n  text: if the creator turned on an email gate, the email address you enter before the video plays\n- category: financial\n  text: Payment details never touch our servers; see Polar below.\npurposes:\n- purpose: show creators viewing analytics\n  text: the creator who sent it can see how the video was watched\n- purpose: advertising\n  text: We do not use this data for advertising, sell it, or combine it across creators.\n- purpose: product email\n  text: We email you to confirm your address, to reset a password you have forgotten\n- purpose: product analytics\n  text: PostHog measures how alto.video is used.\nretention:\n- scope: video and its visit records\n  period: until the video is deleted\n  text: A video and everything about it (the file, the copies we make of it, its cover, its visit records with their\n    IP addresses, its transcript, and its title, description,\
  \ chapters and link names) stays until the video is\n    deleted\n- scope: free plan videos nobody plays\n  period: six months\n  text: When nobody but its creator has played a free plan video for six months, we email the creator 30 days and\n    7 days before archiving it\n- scope: archived video\n  period: null\n  text: Thirty days later it is deleted exactly as above, unless the creator keeps it or upgrades to Pro first.\n- scope: session cookies\n  period: up to 30 days\n  text: Session cookies keep you signed in for up to 30 days.\n- scope: viewer ID cookie\n  period: 180 days\n  text: a random viewer ID, stored in a cookie named alto_viewer for 180 days\n- scope: database backups\n  period: within 30 days\n  text: Backups of the database roll off within 30 days, so what is deleted is gone from them by then.\nresidency:\n- region: United States\n  text: Cloudflare stores the database and files in its global network, primarily in the United States, and serves\n    videos from the location\
  \ nearest the viewer.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Only the companies that run the pieces we do not: Cloudflare hosts everything'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: write to support@alto.video or contact the creator who sent the link\n  text: To delete your account, or to ask what we hold about you and get a copy, write to support@alto.video from\n    the address on the account.\nrights:\n- right: access\n  text: these are the access, portability, correction and erasure rights that law gives you\n- right: erasure\n  text: these are the access, portability, correction and erasure rights that law gives you\n- right: complain to authority\n  text: you may also complain to your local authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use this data for advertising, sell it, or combine it across creators.\n"
source_yaml_url: https://artifacts.apis.io/alto-video/privacy/alto-video-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Alto's own page on 2026-11-09.
synthetic: false
tags:
- Video Hosting
- Sales Enablement
- Demo Analytics
- Privacy
- Software-as-a-Service
---
