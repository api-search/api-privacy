---
api_specs:
- filename: builtonrails-com-openapi-generated.yml
  format: yaml
  label: BuiltOnRails API
  slug: builtonrails-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/builtonrails-com/openapi/_ae-authored/builtonrails-com-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your email address, a username, and anything optional you fill in: name, bio, website, social handles, and how you want your profile card to look.'
  - category: identifying
    text: If you sign in with GitHub or X we store the numeric account id, the handle, and when you connected.
  - category: other
    text: GitHub connections also store an access token so we can read your public repository statistics.
  - category: location
    text: the IP address of your last sign-in and the city and country it resolves to
  - category: behavioral
    text: Sign-in count and time, the IP address of your last sign-in and the city and country it resolves to, when you were last active, and a count of profile views.
  - category: communication
    text: Which emails went to you and when, so you are not sent the same thing twice.
  deletion:
    route: settings or email
    text: You can delete it from settings or by emailing us, and we will act on that.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: security
    text: The IP is kept so you can spot a sign-in that was not you.
  - purpose: avoid duplicate emails
    text: Which emails went to you and when, so you are not sent the same thing twice.
  - purpose: repository statistics
    text: GitHub connections also store an access token so we can read your public repository statistics.
  retention:
  - period: until you delete the account
    scope: Account data
    text: Account data stays until you delete the account.
  - period: while the account is active
    scope: Sign-in location history
    text: Sign-in location history is kept while the account is active.
  - period: null
    scope: Delivery records
    text: Delivery records are kept so we do not resend things.
  rights:
  - right: access
    text: You can ask for a copy of what we hold
  - right: correction
    text: ask us to correct it
  - right: deletion
    text: ask us to delete it.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information and we do not share it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BuiltOnRails
provenance_date: '2026-11-09'
provider_name: BuiltOnRails
provider_slug: builtonrails-com
slug: builtonrails-com-privacy-policy
source_date: '2026-11-09'
source_filename: builtonrails-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://builtonrails.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BuiltOnRails\naid: builtonrails-com\nurl: https://builtonrails.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Your email address, a username, and anything optional you fill in: name, bio, website, social handles,\n    and how you want your profile card to look.'\n- category: identifying\n  text: If you sign in with GitHub or X we store the numeric account id, the handle, and when you connected.\n- category: other\n  text: GitHub connections also store an access token so we can read your public repository statistics.\n- category:\
  \ location\n  text: the IP address of your last sign-in and the city and country it resolves to\n- category: behavioral\n  text: Sign-in count and time, the IP address of your last sign-in and the city and country it resolves to, when\n    you were last active, and a count of profile views.\n- category: communication\n  text: Which emails went to you and when, so you are not sent the same thing twice.\npurposes:\n- purpose: security\n  text: The IP is kept so you can spot a sign-in that was not you.\n- purpose: avoid duplicate emails\n  text: Which emails went to you and when, so you are not sent the same thing twice.\n- purpose: repository statistics\n  text: GitHub connections also store an access token so we can read your public repository statistics.\nretention:\n- scope: Account data\n  period: until you delete the account\n  text: Account data stays until you delete the account.\n- scope: Sign-in location history\n  period: while the account is active\n  text: Sign-in location history\
  \ is kept while the account is active.\n- scope: Delivery records\n  period: null\n  text: Delivery records are kept so we do not resend things.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: settings or email\n  text: You can delete it from settings or by emailing us, and we will act on that.\nrights:\n- right: access\n  text: You can ask for a copy of what we hold\n- right: correction\n  text: ask us to correct it\n- right: deletion\n  text: ask us to delete it.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information and we do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/builtonrails-com/privacy/builtonrails-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from BuiltOnRails's own page on 2026-11-09.
synthetic: false
tags:
- Ruby on Rails
- Stack Data
---
