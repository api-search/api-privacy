---
api_specs:
- filename: normapi-com-openapi.yml
  format: yaml
  label: NormAPI REST API
  slug: normapi-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/normapi-com/openapi/normapi-com-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 'we process: your email address, the sign-in method you chose, one-time confirmation tokens (valid for 24 hours)'
  - category: financial
    text: the details you enter — including names, addresses, email addresses, phone numbers and bank details — go to our API
  - category: behavioral
    text: the page you opened, the referrer, an approximate location at country level, device type and browser
  - category: identifying
    text: your IP address and your browser play no part in it
  deletion:
    route: account area under “Settings”
    text: You can do that yourself at any time — in the account area under “Settings”, immediately and without asking us
  dpa:
    available: true
    text: A data processing agreement under Art. 28 GDPR is in place.
    url: null
  purposes:
  - purpose: performing the check or creation you requested
    text: The legal basis is Art. 6(1)(b) or (f) GDPR — performing the check you requested.
  - purpose: audience measurement
    text: The legal basis is our legitimate interest in data-minimising audience measurement, Art. 6(1)(f) GDPR.
  - purpose: server security
    text: The legal basis is Art. 6(1)(f) GDPR — legitimate interest in operating the site securely.
  - purpose: ruleset-change notifications with consent
    text: The legal basis is your consent under Art. 6(1)(a) GDPR, and you can withdraw it at any time
  residency:
  - region: Germany (Düsseldorf)
    text: operated by WIIT AG, Joachim-Erwin-Platz 3, 40212 Düsseldorf, Germany, in its data centres in Düsseldorf.
  - region: European Union (mailing list and Mailjet)
    text: We keep the list ourselves, on our own servers in the European Union.
  - region: Frankfurt am Main (PostHog EU cloud)
    text: Processing takes place on their EU cloud in Frankfurt am Main
  retention:
  - period: immediately after validation
    scope: invoice validation uploads
    text: Uploaded invoices are processed in memory only and discarded immediately after validation.
  - period: seven days
    scope: request log
    text: Entries are deleted after seven days.
  - period: one day
    scope: sign-in attempts
    text: delete the entries after one day
  - period: at midnight
    scope: free invoice daily counters
    text: The count is stored nowhere and dropped at midnight.
  - period: until you delete it or the account
    scope: letterhead
    text: The letterhead stays stored until you delete it or the account
  - period: until you delete the account
    scope: account data
    text: Account data is stored until you delete the account.
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: You have the right of access (Art. 15 GDPR), rectification (Art. 16), erasure (Art. 17), restriction of processing (Art. 18), data portability (Art. 20), and objection (Art. 21).
  - right: lodge a complaint
    text: You also have the right to lodge a complaint with a supervisory authority.
  role:
    text: 'Controller Dmytro Yalanskyi Email: datenschutz@normapi.de'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: NormAPI
provenance_date: '2026-11-10'
provider_name: NormAPI
provider_slug: normapi-com
slug: normapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: normapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://normapi.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: NormAPI\naid: normapi-com\nurl: https://normapi.com/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller Dmytro Yalanskyi Email: datenschutz@normapi.de'\ndata_categories:\n- category: contact\n  text: 'we process: your email address, the sign-in method you chose, one-time confirmation tokens (valid for 24\n    hours)'\n- category: financial\n  text: the details you enter — including names, addresses, email addresses, phone numbers and bank details — go\n    to our API\n- category: behavioral\n  text: the page you opened, the referrer, an approximate location at country level,\
  \ device type and browser\n- category: identifying\n  text: your IP address and your browser play no part in it\npurposes:\n- purpose: performing the check or creation you requested\n  text: The legal basis is Art. 6(1)(b) or (f) GDPR — performing the check you requested.\n- purpose: audience measurement\n  text: The legal basis is our legitimate interest in data-minimising audience measurement, Art. 6(1)(f) GDPR.\n- purpose: server security\n  text: The legal basis is Art. 6(1)(f) GDPR — legitimate interest in operating the site securely.\n- purpose: ruleset-change notifications with consent\n  text: The legal basis is your consent under Art. 6(1)(a) GDPR, and you can withdraw it at any time\nretention:\n- scope: invoice validation uploads\n  period: immediately after validation\n  text: Uploaded invoices are processed in memory only and discarded immediately after validation.\n- scope: request log\n  period: seven days\n  text: Entries are deleted after seven days.\n- scope: sign-in\
  \ attempts\n  period: one day\n  text: delete the entries after one day\n- scope: free invoice daily counters\n  period: at midnight\n  text: The count is stored nowhere and dropped at midnight.\n- scope: letterhead\n  period: until you delete it or the account\n  text: The letterhead stays stored until you delete it or the account\n- scope: account data\n  period: until you delete the account\n  text: Account data is stored until you delete the account.\nresidency:\n- region: Germany (Düsseldorf)\n  text: operated by WIIT AG, Joachim-Erwin-Platz 3, 40212 Düsseldorf, Germany, in its data centres in Düsseldorf.\n- region: European Union (mailing list and Mailjet)\n  text: We keep the list ourselves, on our own servers in the European Union.\n- region: Frankfurt am Main (PostHog EU cloud)\n  text: Processing takes place on their EU cloud in Frankfurt am Main\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: A data processing agreement\
  \ under Art. 28 GDPR is in place.\ndeletion:\n  route: account area under “Settings”\n  text: You can do that yourself at any time — in the account area under “Settings”, immediately and without asking\n    us\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: You have the right of access (Art. 15 GDPR), rectification (Art. 16), erasure (Art. 17), restriction of\n    processing (Art. 18), data portability (Art. 20), and objection (Art. 21).\n- right: lodge a complaint\n  text: You also have the right to lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/normapi-com/privacy/normapi-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
summary_line: 22 quoted statements, read from NormAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Invoicing
- XRechnung
- ZUGFeRD
- Germany
---
