---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address. You type it to sign in or to buy, and an account exists from the moment you start a checkout with it, even before you sign in.
  - category: behavioral
    text: 'The work you send in to be scored: the full text you paste, up to 100,000 characters each time, with its score.'
  - category: financial
    text: What you bought and when, with Stripe's ids for the payment and the membership. Never your card number.
  - category: identifying
    text: Your IP address, only to limit abuse (how many sign-in links or checkouts one address asks for).
  - category: communication
    text: What you send in the feedback box, with the lesson you sent it from.
  deletion:
    route: Self-service deletion at /account/delete
    text: Delete your account in one step at /account/delete .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Scoring submitted work
    text: 'AI model providers : receive the text you submit so a model can help score it'
  - purpose: Product analytics
    text: 'Product analytics : receives events such as a purchase or a first score, keyed by a random account id'
  - purpose: Payment processing
    text: 'Payment processor (Stripe) : takes your card and billing details on its own checkout page, under its own privacy policy.'
  retention:
  - period: 15 minutes
    scope: Sign-in links
    text: Sign-in links work once and expire 15 minutes after we send them.
  - period: 30 days
    scope: Sign-in
    text: A sign-in lasts 30 days, or until you sign out.
  - period: 30 days
    scope: Analytics events queue
    text: Analytics events wait in a queue until they are sent, and are cleared from it 30 days later.
  - period: null
    scope: Entrance exam address and errand
    text: 'The address and errand are kept until you ask us to erase them: write to support@ai-phd.com .'
  rights:
  - right: Access copy
    text: For a copy of what we hold about you, write to support@ai-phd.com .
  - right: Erasure of entrance exam data
    text: 'The address and errand are kept until you ask us to erase them: write to support@ai-phd.com .'
  - right: Stop practice emails
    text: Stop practice emails with the one-click link at the bottom of each one.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent anything about you.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI PhD
provenance_date: '2026-11-09'
provider_name: AI PhD
provider_slug: ai-phd-com
slug: ai-phd-com-privacy-policy
source_date: '2026-11-09'
source_filename: ai-phd-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ai-phd.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI PhD\naid: ai-phd-com\nurl: https://ai-phd.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your email address. You type it to sign in or to buy, and an account exists from the moment you start a\n    checkout with it, even before you sign in.\n- category: behavioral\n  text: 'The work you send in to be scored: the full text you paste, up to 100,000 characters each time, with its\n    score.'\n- category: financial\n  text: What you bought and when, with Stripe's ids for the payment and the membership. Never your card number.\n\
  - category: identifying\n  text: Your IP address, only to limit abuse (how many sign-in links or checkouts one address asks for).\n- category: communication\n  text: What you send in the feedback box, with the lesson you sent it from.\npurposes:\n- purpose: Scoring submitted work\n  text: 'AI model providers : receive the text you submit so a model can help score it'\n- purpose: Product analytics\n  text: 'Product analytics : receives events such as a purchase or a first score, keyed by a random account id'\n- purpose: Payment processing\n  text: 'Payment processor (Stripe) : takes your card and billing details on its own checkout page, under its own\n    privacy policy.'\nretention:\n- scope: Sign-in links\n  period: 15 minutes\n  text: Sign-in links work once and expire 15 minutes after we send them.\n- scope: Sign-in\n  period: 30 days\n  text: A sign-in lasts 30 days, or until you sign out.\n- scope: Analytics events queue\n  period: 30 days\n  text: Analytics events wait in a queue\
  \ until they are sent, and are cleared from it 30 days later.\n- scope: Entrance exam address and errand\n  period: null\n  text: 'The address and errand are kept until you ask us to erase them: write to support@ai-phd.com .'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service deletion at /account/delete\n  text: Delete your account in one step at /account/delete .\nrights:\n- right: Access copy\n  text: For a copy of what we hold about you, write to support@ai-phd.com .\n- right: Erasure of entrance exam data\n  text: 'The address and errand are kept until you ask us to erase them: write to support@ai-phd.com .'\n- right: Stop practice emails\n  text: Stop practice emails with the one-click link at the bottom of each one.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent anything about you.\n"
source_yaml_url: https://artifacts.apis.io/ai-phd-com/privacy/ai-phd-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from AI PhD's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Artificial Intelligence
- Courses
- Learning
- Platform
---
