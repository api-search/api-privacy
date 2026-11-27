---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your Google account email, display name and profile picture, used to create and identify your BrowsingBee account.
  - category: behavioral
    text: 'For every tool call: your account, the tool name, the host name of the page (for example en.wikipedia.org , never the full address or query string)'
  - category: device
    text: Standard server logs with IP address and user agent, kept by Cloudflare for up to 7 days.
  deletion:
    route: Email hey@browsingbee.com from the Google address you signed in with
    text: To delete everything, email hey@browsingbee.com from the Google address you signed in with; we remove the account, tokens, usage rows and logs within 7 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and identification
    text: used to create and identify your BrowsingBee account
  - purpose: Quota application
    text: to apply the free or Pro quota
  - purpose: Abuse prevention and debugging
    text: Kept for 90 days for abuse prevention and debugging.
  residency:
  - region: Cloudflare global network
    text: Data is processed in Cloudflare’s global network.
  retention:
  - period: 24 hours
    scope: Screenshots
    text: Images you ask for are stored for 24 hours so the assistant can show them, then deleted automatically.
  - period: 90 days
    scope: Call log
    text: Kept for 90 days for abuse prevention and debugging.
  - period: until you delete the account
    scope: Usage counts and account
    text: 'Usage counts and account: until you delete the account.'
  - period: up to 7 days
    scope: Standard server logs
    text: kept by Cloudflare for up to 7 days.
  rights:
  - right: Access
    text: You can ask for a copy of the data we hold
  - right: Correction
    text: correct it
  - right: Deletion
    text: or delete it by emailing hey@browsingbee.com .
  - right: Complain to data protection authority
    text: If you are in the EU/UK you also have the right to complain to your local data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not build profiles, sell data or show ads.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BrowsingBee
provenance_date: '2026-11-09'
provider_name: BrowsingBee
provider_slug: browsingbee-com
slug: browsingbee-com-privacy-policy
source_date: '2026-11-09'
source_filename: browsingbee-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.browsingbee.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BrowsingBee\naid: browsingbee-com\nurl: https://www.browsingbee.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your Google account email, display name and profile picture, used to create and identify your BrowsingBee\n    account.\n- category: behavioral\n  text: 'For every tool call: your account, the tool name, the host name of the page (for example en.wikipedia.org\n    , never the full address or query string)'\n- category: device\n  text: Standard server logs with IP address and user agent, kept by Cloudflare for up to\
  \ 7 days.\npurposes:\n- purpose: Account creation and identification\n  text: used to create and identify your BrowsingBee account\n- purpose: Quota application\n  text: to apply the free or Pro quota\n- purpose: Abuse prevention and debugging\n  text: Kept for 90 days for abuse prevention and debugging.\nretention:\n- scope: Screenshots\n  period: 24 hours\n  text: Images you ask for are stored for 24 hours so the assistant can show them, then deleted automatically.\n- scope: Call log\n  period: 90 days\n  text: Kept for 90 days for abuse prevention and debugging.\n- scope: Usage counts and account\n  period: until you delete the account\n  text: 'Usage counts and account: until you delete the account.'\n- scope: Standard server logs\n  period: up to 7 days\n  text: kept by Cloudflare for up to 7 days.\nresidency:\n- region: Cloudflare global network\n  text: Data is processed in Cloudflare’s global network.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Email hey@browsingbee.com from the Google address you signed in with\n  text: To delete everything, email hey@browsingbee.com from the Google address you signed in with; we remove the\n    account, tokens, usage rows and logs within 7 days.\nrights:\n- right: Access\n  text: You can ask for a copy of the data we hold\n- right: Correction\n  text: correct it\n- right: Deletion\n  text: or delete it by emailing hey@browsingbee.com .\n- right: Complain to data protection authority\n  text: If you are in the EU/UK you also have the right to complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not build profiles, sell data or show ads.\n"
source_yaml_url: https://artifacts.apis.io/browsingbee-com/privacy/browsingbee-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from BrowsingBee's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Browser
- Connector
- Claude
- ChatGPT
---
