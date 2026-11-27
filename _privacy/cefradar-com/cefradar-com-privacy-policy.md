---
api_specs:
- filename: cefradar-com-account-api-openapi.yml
  format: yaml
  label: CEF Radar Account API
  slug: cefradar-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-account-api-openapi.yml
- filename: cefradar-com-events-api-openapi.yml
  format: yaml
  label: CEF Radar Events API
  slug: cefradar-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-events-api-openapi.yml
- filename: cefradar-com-funds-api-openapi.yml
  format: yaml
  label: CEF Radar Funds API
  slug: cefradar-com-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-funds-api-openapi.yml
- filename: cefradar-com-investors-api-openapi.yml
  format: yaml
  label: CEF Radar Investors API
  slug: cefradar-com-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-investors-api-openapi.yml
- filename: cefradar-com-search-api-openapi.yml
  format: yaml
  label: CEF Radar Search API
  slug: cefradar-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cefradar-com/openapi/cefradar-com-search-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address, the funds and investors you follow, when you signed in
  - category: identifying
    text: which outside account you sign in with, if you use one
  - category: device
    text: your browser type
  - category: communication
    text: When you write to us we keep your message and our reply
  deletion:
    route: Delete my account on alerts page
    text: '"Delete my account" on your alerts page removes everything at once.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: send alerts you asked for
    text: 'Why: to send the alerts you asked for, and to keep the site safe.'
  - purpose: security and abuse prevention
    text: Our legitimate interest is keeping the site safe and finding abuse, such as someone asking for hundreds of sign-in links (Art. 6(1)(f)).
  - purpose: optional weekly summary with consent
    text: We send it only with your consent (Art. 6(1)(a))
  residency:
  - region: European Union (France and Ireland)
    text: If you are in the United States, your information is stored in the European Union (France and Ireland).
  retention:
  - period: Until you delete it
    scope: account and funds followed
    text: Your account and the funds you follow Until you delete it
  - period: 90 days
    scope: traffic logs
    text: Traffic logs 90 days
  - period: 30 days
    scope: application logs
    text: Application logs 30 days
  - period: 14 days
    scope: backups
    text: Backups 14 days
  - period: 24 hours
    scope: sign-in links
    text: Sign-in links 24 hours
  rights:
  - right: access
    text: 'See what we keep: download what we keep about you (sign in first).'
  - right: rectification
    text: 'Correct it: to change your address, delete your account and sign up again with the new one.'
  - right: erasure
    text: 'Delete it: "Delete my account" on your alerts page removes everything at once.'
  - right: restriction
    text: 'Restrict it: ask us to pause using your information while a question is settled.'
  - right: portability
    text: 'Take it with you: the download above is a plain file you can keep or give to someone else.'
  - right: withdraw consent
    text: 'Withdraw consent: the Stop link in any Monday summary, or the checkbox on your alerts page.'
  - right: object
    text: You can object at any time - especially to our legitimate-interest processing and to any marketing email.
  role:
    text: The person responsible for your information - the law calls this the "controller" - is IPL Mateusz Duliński
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell, rent or share your information for advertising.
  subprocessors:
    text: 'OVH SAS (France): hosts our server and our backups. Cloudflare, Inc. (a U.S. company with servers worldwide)'
    url: null
  transfers:
  - mechanism: DPF
    text: Transfers rely on the EU-U.S. Data Privacy Framework (Commission Decision (EU) 2023/1795 - these companies are certified)
  - mechanism: SCC
    text: as a back-up, the standard contractual clauses (Decision (EU) 2021/914) in their data-processing agreements
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CEF Radar
provenance_date: '2026-11-09'
provider_name: CEF Radar
provider_slug: cefradar-com
slug: cefradar-com-privacy-policy
source_date: '2026-11-09'
source_filename: cefradar-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cefradar.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CEF Radar\naid: cefradar-com\nurl: https://cefradar.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The person responsible for your information - the law calls this the \"controller\" - is IPL Mateusz Duliński\ndata_categories:\n- category: contact\n  text: your email address, the funds and investors you follow, when you signed in\n- category: identifying\n  text: which outside account you sign in with, if you use one\n- category: device\n  text: your browser type\n- category: communication\n  text: When you write to us we keep your message and our reply\npurposes:\n- purpose: send\
  \ alerts you asked for\n  text: 'Why: to send the alerts you asked for, and to keep the site safe.'\n- purpose: security and abuse prevention\n  text: Our legitimate interest is keeping the site safe and finding abuse, such as someone asking for hundreds\n    of sign-in links (Art. 6(1)(f)).\n- purpose: optional weekly summary with consent\n  text: We send it only with your consent (Art. 6(1)(a))\nretention:\n- scope: account and funds followed\n  period: Until you delete it\n  text: Your account and the funds you follow Until you delete it\n- scope: traffic logs\n  period: 90 days\n  text: Traffic logs 90 days\n- scope: application logs\n  period: 30 days\n  text: Application logs 30 days\n- scope: backups\n  period: 14 days\n  text: Backups 14 days\n- scope: sign-in links\n  period: 24 hours\n  text: Sign-in links 24 hours\nresidency:\n- region: European Union (France and Ireland)\n  text: If you are in the United States, your information is stored in the European Union (France and Ireland).\n\
  transfers:\n- mechanism: DPF\n  text: Transfers rely on the EU-U.S. Data Privacy Framework (Commission Decision (EU) 2023/1795 - these companies\n    are certified)\n- mechanism: SCC\n  text: as a back-up, the standard contractual clauses (Decision (EU) 2021/914) in their data-processing agreements\nsubprocessors:\n  url: null\n  text: 'OVH SAS (France): hosts our server and our backups. Cloudflare, Inc. (a U.S. company with servers worldwide)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete my account on alerts page\n  text: '\"Delete my account\" on your alerts page removes everything at once.'\nrights:\n- right: access\n  text: 'See what we keep: download what we keep about you (sign in first).'\n- right: rectification\n  text: 'Correct it: to change your address, delete your account and sign up again with the new one.'\n- right: erasure\n  text: 'Delete it: \"Delete my account\" on your alerts page removes everything at once.'\n- right: restriction\n\
  \  text: 'Restrict it: ask us to pause using your information while a question is settled.'\n- right: portability\n  text: 'Take it with you: the download above is a plain file you can keep or give to someone else.'\n- right: withdraw consent\n  text: 'Withdraw consent: the Stop link in any Monday summary, or the checkbox on your alerts page.'\n- right: object\n  text: You can object at any time - especially to our legitimate-interest processing and to any marketing email.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell, rent or share your information for advertising.\n"
source_yaml_url: https://artifacts.apis.io/cefradar-com/privacy/cefradar-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from CEF Radar's own page on 2026-11-09.
synthetic: false
tags:
- Closed‑end funds
- SEC Filings
- Investor alerts
- Fund Activity
- Buybacks
---
