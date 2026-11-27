---
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your Google account's stable subject identifier is used to derive an internal account identifier; your email address is not used as the account identity.
  - category: behavioral
    text: search analytics such as search queries, page URLs, dates, countries, devices, clicks, impressions, click-through rates and positions
  - category: contact
    text: Google’s user-information response may include an email address; the reviewed application uses the subject identifier and does not persist an email profile.
  - category: device
    text: Infrastructure may process technical request metadata and operational logs, such as timestamps, network information and error status.
  deletion:
    route: email contact address
    text: To request deletion of service-held connection records, email the contact address above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate connection and call Google APIs
    text: Account identifiers and OAuth credentials are used to authenticate your connection and call Google's APIs on your behalf.
  - purpose: provide requested MCP functionality
    text: Search Console information is used only to provide the MCP functionality you request.
  - purpose: Analytics functionality
    text: are used only to authenticate requests necessary to provide the user-requested Analytics functionality
  residency:
  - region: unstated
    text: this policy does not promise storage in a particular country.
  retention:
  - period: no automatic expiry
    scope: Google refresh-token records
    text: Google refresh-token records have no automatic expiry set by this application and remain until removed, even if Google invalidates them.
  - period: null
    scope: Access-token caches
    text: Access-token caches expire after the lifetime returned by Google (with a minimum cache-record lifetime of 60 seconds)
  - period: ten minutes
    scope: Authorization transactions
    text: authorization transactions expire after ten minutes
  - period: thirty-day lifetime
    scope: MCP refresh grants
    text: MCP refresh grants have a thirty-day lifetime.
  rights:
  - right: deletion request
    text: To request deletion of service-held connection records, email the contact address above.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Vosik Signals does not sell Google user data, share it for advertising, use it for data brokerage or credit decisions, or use Google user data to train generalized AI models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: vosiksignals-win
provenance_date: '2026-11-10'
provider_name: vosiksignals-win
provider_slug: vosiksignals-win
slug: vosiksignals-win-privacy-policy
source_date: '2026-11-10'
source_filename: vosiksignals-win-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vosiksignals.win/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: vosiksignals-win\naid: vosiksignals-win\nurl: https://vosiksignals.win/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your Google account's stable subject identifier is used to derive an internal account identifier; your email\n    address is not used as the account identity.\n- category: behavioral\n  text: search analytics such as search queries, page URLs, dates, countries, devices, clicks, impressions, click-through\n    rates and positions\n- category: contact\n  text: Google’s user-information response may include an email\
  \ address; the reviewed application uses the subject\n    identifier and does not persist an email profile.\n- category: device\n  text: Infrastructure may process technical request metadata and operational logs, such as timestamps, network\n    information and error status.\npurposes:\n- purpose: authenticate connection and call Google APIs\n  text: Account identifiers and OAuth credentials are used to authenticate your connection and call Google's APIs\n    on your behalf.\n- purpose: provide requested MCP functionality\n  text: Search Console information is used only to provide the MCP functionality you request.\n- purpose: Analytics functionality\n  text: are used only to authenticate requests necessary to provide the user-requested Analytics functionality\nretention:\n- scope: Google refresh-token records\n  period: no automatic expiry\n  text: Google refresh-token records have no automatic expiry set by this application and remain until removed,\n    even if Google invalidates them.\n\
  - scope: Access-token caches\n  period: null\n  text: Access-token caches expire after the lifetime returned by Google (with a minimum cache-record lifetime of\n    60 seconds)\n- scope: Authorization transactions\n  period: ten minutes\n  text: authorization transactions expire after ten minutes\n- scope: MCP refresh grants\n  period: thirty-day lifetime\n  text: MCP refresh grants have a thirty-day lifetime.\nresidency:\n- region: unstated\n  text: this policy does not promise storage in a particular country.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email contact address\n  text: To request deletion of service-held connection records, email the contact address above.\nrights:\n- right: deletion request\n  text: To request deletion of service-held connection records, email the contact address above.\nsale_or_sharing:\n  stance: prohibited\n  text: Vosik Signals does not sell Google user data, share\
  \ it for advertising, use it for data brokerage or credit\n    decisions, or use Google user data to train generalized AI models.\n"
source_yaml_url: https://artifacts.apis.io/vosiksignals-win/privacy/vosiksignals-win-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from vosiksignals-win's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software
- Tools
- Data
- Automation
- Artificial Intelligence
---
