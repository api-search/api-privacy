---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address
  - category: identifying
    text: The name and callback address of the agent you connect with
  - category: health
    text: Allergies and medical diets are health data.
  - category: behavioral
    text: 'Tool calls: which tool your agent called, with what arguments (the search text, the ingredients, the recipe id, what you asked us to remember about how you eat), and any error'
  - category: device
    text: 'Server logs: IP address, request path, user agent, timestamp'
  - category: financial
    text: Your Cookidoo login (email, password, session tokens), only if you connect a Thermomix / Bimby
  - category: communication
    text: Whether you opted in to the newsletter, and when
  deletion:
    route: Email the provider from the account address to have the whole account deleted
    text: have the whole account deleted. Email [email protected] from the address on the account; we act within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account sign-in
    text: It is your account. We use it to send sign-in codes and, only if you opt in, the newsletter.
  - purpose: Security and debugging
    text: Security and debugging.
  - purpose: Finding abuse and fixing bugs
    text: To find abuse, fix bugs, and see which questions the tools fail to answer.
  - purpose: Recipe suggestions
    text: To leave out recipes you cannot or will not eat and to pick ones that fit.
  - purpose: Advertising
    text: We do not profile you or run advertising.
  residency:
  - region: EU
    text: The service runs on our own servers in the EU.
  retention:
  - period: 30 days
    scope: Server logs
    text: Security and debugging. 30 days
  - period: Up to 180 days
    scope: Sign-in tokens
    text: Up to 180 days
  - period: null
    scope: Account data
    text: Until you ask us to delete the account
  - period: 24 hours
    scope: Household invite link
    text: an invite link works for 24 hours
  rights:
  - right: Access
    text: You can ask for a copy of everything we hold about you
  - right: Rectification
    text: have it corrected
  - right: Erasure
    text: have the whole account deleted
  role:
    text: Capsule One B.V. is the data controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No data is sold, rented or shared for marketing.
  subprocessors:
    text: Mailgun (EU region) delivers sign-in emails and the newsletter. It sees your email address, the code and the newsletter content.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ask Recipes
provenance_date: '2026-11-09'
provider_name: Ask Recipes
provider_slug: ask-recipes
slug: ask-recipes-privacy-policy
source_date: '2026-11-09'
source_filename: ask-recipes-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ask.recipes/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ask Recipes\naid: ask-recipes\nurl: https://ask.recipes/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Capsule One B.V. is the data controller.\ndata_categories:\n- category: contact\n  text: Your email address\n- category: identifying\n  text: The name and callback address of the agent you connect with\n- category: health\n  text: Allergies and medical diets are health data.\n- category: behavioral\n  text: 'Tool calls: which tool your agent called, with what arguments (the search text, the ingredients, the recipe\n    id, what you asked us to remember about how you eat), and any\
  \ error'\n- category: device\n  text: 'Server logs: IP address, request path, user agent, timestamp'\n- category: financial\n  text: Your Cookidoo login (email, password, session tokens), only if you connect a Thermomix / Bimby\n- category: communication\n  text: Whether you opted in to the newsletter, and when\npurposes:\n- purpose: Account sign-in\n  text: It is your account. We use it to send sign-in codes and, only if you opt in, the newsletter.\n- purpose: Security and debugging\n  text: Security and debugging.\n- purpose: Finding abuse and fixing bugs\n  text: To find abuse, fix bugs, and see which questions the tools fail to answer.\n- purpose: Recipe suggestions\n  text: To leave out recipes you cannot or will not eat and to pick ones that fit.\n- purpose: Advertising\n  text: We do not profile you or run advertising.\nretention:\n- scope: Server logs\n  period: 30 days\n  text: Security and debugging. 30 days\n- scope: Sign-in tokens\n  period: Up to 180 days\n  text: Up to 180\
  \ days\n- scope: Account data\n  period: null\n  text: Until you ask us to delete the account\n- scope: Household invite link\n  period: 24 hours\n  text: an invite link works for 24 hours\nresidency:\n- region: EU\n  text: The service runs on our own servers in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Mailgun (EU region) delivers sign-in emails and the newsletter. It sees your email address, the code and\n    the newsletter content.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the provider from the account address to have the whole account deleted\n  text: have the whole account deleted. Email [email protected] from the address on the account; we act within 30\n    days.\nrights:\n- right: Access\n  text: You can ask for a copy of everything we hold about you\n- right: Rectification\n  text: have it corrected\n- right: Erasure\n  text: have the whole account deleted\nsale_or_sharing:\n  stance: prohibited\n  text: No data is sold,\
  \ rented or shared for marketing.\n"
source_yaml_url: https://artifacts.apis.io/ask-recipes/privacy/ask-recipes-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Ask Recipes's own page on 2026-11-09.
synthetic: false
tags:
- AI Cooking Assistant
- Recipe Search
---
