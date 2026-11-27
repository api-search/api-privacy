---
claim_count: 15
description: ''
doc:
  data_categories:
  - category: device
    text: It records the page you visit, the referrer, and your browser, operating system, device type and country.
  - category: behavioral
    text: what you click on the site (such as copying the install command, opening the setup prompt or opening a FAQ)
  - category: location
    text: and your browser, device and approximate location.
  - category: identifying
    text: the caller's IP address and user agent
  - category: contact
    text: Adwarp reads the email addresses on your machine, trims and lowercases them, and hashes every address with SHA-256 before anything is uploaded.
  deletion:
    route: delete the local ~/.adwarp folder and revoke access in Google account permissions and LinkedIn settings
    text: To remove all of it, delete that folder, then revoke Adwarp's access in your Google account permissions and in your LinkedIn settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: website analytics
    text: Google Analytics 4 sets 2 first-party cookies, _ga and _ga_CJNMP1ED9L , that last up to 2 years, to tell visits apart and see which pages people read.
  - purpose: LinkedIn matched audiences
    text: When you build a LinkedIn matched audience from a contact list, whether a CSV, a Salesforce query or a HubSpot list or search, Adwarp reads the email addresses on your machine
  - purpose: change comparison
    text: Adwarp reads it to compare performance before and after a change.
  retention:
  - period: 14 months
    scope: Google Analytics data
    text: Google keeps the data for 14 months.
  - period: 2 years
    scope: Google Analytics cookies
    text: that last up to 2 years
  rights:
  - right: withdraw analytics consent
    text: 'Change your choice any time with Cookie settings at the bottom of every page: declining switches Google Analytics off and deletes its cookies.'
  - right: request about data
    text: For questions or a request about your data, open an issue at github.com/ adwarp-dev /adwarp/issues .
  role:
    text: Adwarp is operated by its maintainer, Stan Rymkiewicz.
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Adwarp sells no data and shows no ads.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Adwarp
provenance_date: '2026-11-09'
provider_name: Adwarp
provider_slug: adwarp-dev
slug: adwarp-dev-privacy-policy
source_date: '2026-11-09'
source_filename: adwarp-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adwarp.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Adwarp\naid: adwarp-dev\nurl: https://adwarp.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: Adwarp is operated by its maintainer, Stan Rymkiewicz.\ndata_categories:\n- category: device\n  text: It records the page you visit, the referrer, and your browser, operating system, device type and country.\n- category: behavioral\n  text: what you click on the site (such as copying the install command, opening the setup prompt or opening a FAQ)\n- category: location\n  text: and your browser, device and approximate location.\n- category: identifying\n  text: the caller's IP address and user\
  \ agent\n- category: contact\n  text: Adwarp reads the email addresses on your machine, trims and lowercases them, and hashes every address with\n    SHA-256 before anything is uploaded.\npurposes:\n- purpose: website analytics\n  text: Google Analytics 4 sets 2 first-party cookies, _ga and _ga_CJNMP1ED9L , that last up to 2 years, to tell\n    visits apart and see which pages people read.\n- purpose: LinkedIn matched audiences\n  text: When you build a LinkedIn matched audience from a contact list, whether a CSV, a Salesforce query or a HubSpot\n    list or search, Adwarp reads the email addresses on your machine\n- purpose: change comparison\n  text: Adwarp reads it to compare performance before and after a change.\nretention:\n- scope: Google Analytics data\n  period: 14 months\n  text: Google keeps the data for 14 months.\n- scope: Google Analytics cookies\n  period: 2 years\n  text: that last up to 2 years\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete the local ~/.adwarp folder and revoke access in Google account permissions and LinkedIn settings\n  text: To remove all of it, delete that folder, then revoke Adwarp's access in your Google account permissions\n    and in your LinkedIn settings.\nrights:\n- right: withdraw analytics consent\n  text: 'Change your choice any time with Cookie settings at the bottom of every page: declining switches Google\n    Analytics off and deletes its cookies.'\n- right: request about data\n  text: For questions or a request about your data, open an issue at github.com/ adwarp-dev /adwarp/issues .\nsale_or_sharing:\n  stance: prohibited\n  text: Adwarp sells no data and shows no ads.\n"
source_yaml_url: https://artifacts.apis.io/adwarp-dev/privacy/adwarp-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Adwarp's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Open Source
- CLI
- LinkedIn
- Google Ads
---
