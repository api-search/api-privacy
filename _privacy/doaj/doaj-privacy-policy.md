---
api_specs:
- filename: doaj-bulk-api-api-openapi.yml
  format: yaml
  label: DOAJ Bulk API
  slug: doaj-bulk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-bulk-api-api-openapi.yml
- filename: doaj-crud-applications-api-openapi.yml
  format: yaml
  label: DOAJ CRUD Applications API
  slug: doaj-crud-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-crud-applications-api-openapi.yml
- filename: doaj-crud-articles-api-openapi.yml
  format: yaml
  label: DOAJ CRUD Articles API
  slug: doaj-crud-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-crud-articles-api-openapi.yml
- filename: doaj-crud-journals-api-openapi.yml
  format: yaml
  label: DOAJ CRUD Journals API
  slug: doaj-crud-journals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-crud-journals-api-openapi.yml
- filename: doaj-search-api-openapi.yml
  format: yaml
  label: DOAJ Search API
  slug: doaj-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doaj/openapi/doaj-search-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name Your email address Your DOAJ account ID Your password Your API key
  - category: contact
    text: Your address (if provided) Your telephone number (if provided) Your LinkedIn profile (if provided)
  - category: financial
    text: DOAJ Team's banking details are held in Billy, our accounting software, to make payments.
  - category: device
    text: When you use DOAJ, we set cookies on your machine.
  deletion:
    route: email to Deputy Director
    text: Account holders may request that DOAJ delete their account from the DOAJ Admin system at any time. Do this by emailing Dominic Mitchell .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: process journal application
    text: We need these details to process your application.
  - purpose: keep users informed of updates
    text: It also has a duty to keep users informed about updates to user accounts, features and functionality, policy changes, or changes in support levels.
  - purpose: marketing emails
    text: to send you occasional DOAJ marketing emails*
  - purpose: volunteer coordination
    text: We use this list to coordinate volunteer activities, ensure each Editorial Group has enough volunteers
  retention:
  - period: seven years
    scope: rejected or removed journal application data
    text: If/when we reject an application or remove a journal from DOAJ, we usually delete the data after seven years.
  - period: two months
    scope: volunteer applications
    text: We delete old applications after two months.
  - period: null
    scope: job applications
    text: Once the recruitment process is complete, we delete all the data and files you provided.
  rights:
  - right: access
    text: You may access, review and edit your account details by logging into your DOAJ account .
  - right: subject access request
    text: An SAR is the process by which a user can request details of a site's information about them and how it is used.
  - right: withdraw consent
    text: you can withdraw your consent for us to store and process your personal data at any time by submitting an email to Dominic Mitchell.
  - right: complain
    text: If you need to complain about how DOAJ has handled an SAR or your request to withdraw consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: DOAJ does not share personal data with any organisation or individual outside the immediate DOAJ organisation, nor will it grant requests from industry organisations for access to user data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DOAJ
provenance_date: '2026-11-09'
provider_name: DOAJ
provider_slug: doaj
slug: doaj-privacy-policy
source_date: '2026-11-09'
source_filename: doaj-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://doaj.org/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DOAJ\naid: doaj\nurl: https://doaj.org/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name Your email address Your DOAJ account ID Your password Your API key\n- category: contact\n  text: Your address (if provided) Your telephone number (if provided) Your LinkedIn profile (if provided)\n- category: financial\n  text: DOAJ Team's banking details are held in Billy, our accounting software, to make payments.\n- category: device\n  text: When you use DOAJ, we set cookies on your machine.\npurposes:\n- purpose: process journal\
  \ application\n  text: We need these details to process your application.\n- purpose: keep users informed of updates\n  text: It also has a duty to keep users informed about updates to user accounts, features and functionality, policy\n    changes, or changes in support levels.\n- purpose: marketing emails\n  text: to send you occasional DOAJ marketing emails*\n- purpose: volunteer coordination\n  text: We use this list to coordinate volunteer activities, ensure each Editorial Group has enough volunteers\nretention:\n- scope: rejected or removed journal application data\n  period: seven years\n  text: If/when we reject an application or remove a journal from DOAJ, we usually delete the data after seven years.\n- scope: volunteer applications\n  period: two months\n  text: We delete old applications after two months.\n- scope: job applications\n  period: null\n  text: Once the recruitment process is complete, we delete all the data and files you provided.\nresidency: []\ntransfers: []\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to Deputy Director\n  text: Account holders may request that DOAJ delete their account from the DOAJ Admin system at any time. Do this\n    by emailing Dominic Mitchell .\nrights:\n- right: access\n  text: You may access, review and edit your account details by logging into your DOAJ account .\n- right: subject access request\n  text: An SAR is the process by which a user can request details of a site's information about them and how it\n    is used.\n- right: withdraw consent\n  text: you can withdraw your consent for us to store and process your personal data at any time by submitting an\n    email to Dominic Mitchell.\n- right: complain\n  text: If you need to complain about how DOAJ has handled an SAR or your request to withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: DOAJ does not share personal data with any organisation or individual outside the\
  \ immediate DOAJ organisation,\n    nor will it grant requests from industry organisations for access to user data.\n"
source_yaml_url: https://artifacts.apis.io/doaj/privacy/doaj-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from DOAJ's own page on 2026-11-09.
synthetic: false
tags:
- Open Access
- Journals
- Scholarly Publishing
- Metadata
---
