---
api_specs:
- filename: ayhire-com-account-api-openapi.yml
  format: yaml
  label: ayhire-com Account API
  slug: ayhire-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-account-api-openapi.yml
- filename: ayhire-com-company-maps-api-openapi.yml
  format: yaml
  label: ayhire-com Company maps API
  slug: ayhire-com-company-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-company-maps-api-openapi.yml
- filename: ayhire-com-integrations-api-openapi.yml
  format: yaml
  label: ayhire-com Integrations API
  slug: ayhire-com-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-integrations-api-openapi.yml
- filename: ayhire-com-people-api-openapi.yml
  format: yaml
  label: ayhire-com People API
  slug: ayhire-com-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-people-api-openapi.yml
- filename: ayhire-com-research-api-openapi.yml
  format: yaml
  label: ayhire-com Research API
  slug: ayhire-com-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-research-api-openapi.yml
- filename: ayhire-com-roles-api-openapi.yml
  format: yaml
  label: ayhire-com Roles API
  slug: ayhire-com-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-roles-api-openapi.yml
- filename: ayhire-com-watching-api-openapi.yml
  format: yaml
  label: ayhire-com Watching API
  slug: ayhire-com-watching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-watching-api-openapi.yml
- filename: ayhire-com-workspaces-api-openapi.yml
  format: yaml
  label: ayhire-com Workspaces API
  slug: ayhire-com-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayhire-com/openapi/ayhire-com-workspaces-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address , from signing in with an email link, Google or GitHub.
  - category: contact
    text: Your company's name and icon , if you sign up with a work email
  - category: behavioral
    text: the pages you open, what you click, how long pages take to load, errors, and recordings of sessions that replay what was on screen
  - category: location
    text: It also sees your browser, device and an approximate location from your IP address.
  - category: financial
    text: Your card details stay with Stripe; we never see or store your full card number.
  - category: professional
    text: your public profile (name, bio, location, company, blog, public email if you list one, and whether you have marked yourself available for hire)
  deletion:
    route: Write to team@ayhire.com
    text: You can ask to see what we hold about you, to correct it, or to delete it. Developers can also ask us to remove what we hold about them. Write to team@ayhire.com and we will reply within one month.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Show what changed since you last looked
    text: 'Your activity feed : new matches for a role, changes in someone''s availability, and changes found in people your workspace watches, so Home can show what changed since you last looked.'
  - purpose: Website analytics
    text: We use it to see where the site confuses people and to improve it, never to sell or advertise.
  - purpose: Scoring developers' public work
    text: four scores out of 10 and a few short findings about your public work (and anything worth checking), made by an AI model from the details above
  retention:
  - period: 30 days
    scope: Analyses and availability checks
    text: An analysis or availability check is reused for 30 days, then refreshed the next time someone asks for that developer.
  - period: three days
    scope: Contribution calendar
    text: A contribution calendar is refreshed after three days.
  - period: 30 days
    scope: Emails and webhook deliveries waiting to go out
    text: Emails and webhook deliveries waiting to go out are kept at most 30 days.
  - period: six months
    scope: Watch changes
    text: Changes are deleted after six months, and once nobody watches you the record is deleted within 30 days.
  - period: about 90 days
    scope: Connected app ended connection record
    text: We delete the record of an ended connection after about 90 days.
  rights:
  - right: access
    text: You can ask to see what we hold about you
  - right: correction
    text: to correct it
  - right: deletion
    text: or to delete it
  - right: complain to data protection authority
    text: If you are in the EU or UK, you can also complain to your data protection authority.
  - right: object to being watched
    text: To have these records deleted now, or to object to being watched, write to team@ayhire.com .
  role:
    text: AyHire is run by AY Automate (“we”).
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Who else handles the data Supabase : our database and sign-in. Cloudflare : runs the website and the app, so it handles every request, including your IP address.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ayhire-com
provenance_date: '2026-11-09'
provider_name: ayhire-com
provider_slug: ayhire-com
slug: ayhire-com-privacy-policy
source_date: '2026-11-09'
source_filename: ayhire-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ayhire.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ayhire-com\naid: ayhire-com\nurl: https://ayhire.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AyHire is run by AY Automate (“we”).\ndata_categories:\n- category: identifying\n  text: Your email address , from signing in with an email link, Google or GitHub.\n- category: contact\n  text: Your company's name and icon , if you sign up with a work email\n- category: behavioral\n  text: the pages you open, what you click, how long pages take to load, errors, and recordings of sessions that\n    replay what was on screen\n- category: location\n  text: It also sees your browser, device\
  \ and an approximate location from your IP address.\n- category: financial\n  text: Your card details stay with Stripe; we never see or store your full card number.\n- category: professional\n  text: your public profile (name, bio, location, company, blog, public email if you list one, and whether you have\n    marked yourself available for hire)\npurposes:\n- purpose: Show what changed since you last looked\n  text: 'Your activity feed : new matches for a role, changes in someone''s availability, and changes found in people\n    your workspace watches, so Home can show what changed since you last looked.'\n- purpose: Website analytics\n  text: We use it to see where the site confuses people and to improve it, never to sell or advertise.\n- purpose: Scoring developers' public work\n  text: four scores out of 10 and a few short findings about your public work (and anything worth checking), made\n    by an AI model from the details above\nretention:\n- scope: Analyses and availability checks\n\
  \  period: 30 days\n  text: An analysis or availability check is reused for 30 days, then refreshed the next time someone asks for that\n    developer.\n- scope: Contribution calendar\n  period: three days\n  text: A contribution calendar is refreshed after three days.\n- scope: Emails and webhook deliveries waiting to go out\n  period: 30 days\n  text: Emails and webhook deliveries waiting to go out are kept at most 30 days.\n- scope: Watch changes\n  period: six months\n  text: Changes are deleted after six months, and once nobody watches you the record is deleted within 30 days.\n- scope: Connected app ended connection record\n  period: about 90 days\n  text: We delete the record of an ended connection after about 90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Who else handles the data Supabase : our database and sign-in. Cloudflare : runs the website and the app,\n    so it handles every request, including your IP address.'\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: Write to team@ayhire.com\n  text: You can ask to see what we hold about you, to correct it, or to delete it. Developers can also ask us to\n    remove what we hold about them. Write to team@ayhire.com and we will reply within one month.\nrights:\n- right: access\n  text: You can ask to see what we hold about you\n- right: correction\n  text: to correct it\n- right: deletion\n  text: or to delete it\n- right: complain to data protection authority\n  text: If you are in the EU or UK, you can also complain to your data protection authority.\n- right: object to being watched\n  text: To have these records deleted now, or to object to being watched, write to team@ayhire.com .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ayhire-com/privacy/ayhire-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 22 quoted statements, read from ayhire-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Hiring
- Developer Tools
- Recruiting
- Open Source
---
