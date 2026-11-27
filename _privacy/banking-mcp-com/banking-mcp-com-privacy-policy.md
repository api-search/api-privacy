---
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: For your account we store your email address, your language, when you signed up, when your trial ends
  - category: financial
    text: 'We do not store balances or transactions: they are fetched from finAPI for every request your assistant makes and passed only to that assistant.'
  - category: financial
    text: per account, its name, IBAN, type and currency
  - category: device
    text: Per page view we process the page address, the referring website, browser, operating system and screen size, plus your IP address.
  - category: location
    text: The IP address is used only to determine your country
  - category: communication
    text: If you write to us, we process your message and email address to answer your request
  deletion:
    route: Delete your account in your account settings; data is removed and banks disconnected at finAPI and Stripe subscription cancelled.
    text: If you delete your account, we immediately remove your account data, sessions, assistants including their activity and your bank data, disconnect your banks at finAPI and cancel your subscription at Stripe.
  dpa:
    available: true
    text: DPA under Art. 28 GDPR
    url: null
  purposes:
  - purpose: providing the service
    text: BankingMCP connects your bank accounts to AI assistants of your choice. We process only the data that service needs.
  - purpose: visitor statistics
    text: To understand how the website is used, we count page views with the open-source software Plausible Analytics
  - purpose: service emails and tips
    text: we send you at most two emails about using the service
  - purpose: security and abuse prevention
    text: To prevent abuse (for example mass sign-in attempts or requests), we count requests per IP address and per connection briefly in memory
  residency:
  - region: Germany
    text: Website, app and database run on servers of Hetzner Online GmbH in Germany (data centres in Nuremberg and Falkenstein).
  retention:
  - period: 14 days
    scope: database backups
    text: The backups are encrypted with AES-256, kept on the same server and deleted after 14 days.
  - period: 90 days
    scope: assistant activity logs
    text: These entries are deleted after 90 days.
  - period: as long as your account exists
    scope: account data
    text: We keep your data for as long as your account exists.
  - period: 10 minutes
    scope: sign-in codes
    text: Codes are stored only as a cryptographic hash and expire after 10 minutes.
  - period: 30 days
    scope: sessions
    text: It ends after 7 days without use, after 30 days at the latest, or when you sign out.
  rights:
  - right: access
    text: You have the right of access (Art. 15 GDPR)
  - right: rectification
    text: rectification (Art. 16)
  - right: erasure
    text: erasure (Art. 17)
  - right: restriction of processing
    text: restriction of processing (Art. 18)
  - right: data portability
    text: data portability (Art. 20)
  - right: objection
    text: Where we process data based on legitimate interests, you can object (Art. 21).
  - right: complaint
    text: You can also lodge a complaint with a data protection supervisory authority.
  role:
    text: Controller Escher Consulting GmbH, Höhenweg 2c, 44265 Dortmund, Germany.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your financial data, do not use it for advertising and do not train AI models on it.
  subprocessors:
    text: Hetzner processes the data solely on our behalf under a data processing agreement (Art. 28 GDPR).
    url: null
  transfers:
  - mechanism: DPF
    text: Stripe may also process data in the USA, on the basis of the EU-US Data Privacy Framework and the EU standard contractual clauses.
  - mechanism: SCC
    text: Stripe may also process data in the USA, on the basis of the EU-US Data Privacy Framework and the EU standard contractual clauses.
  - mechanism: other
    text: from then on the provider's own privacy terms apply, it acts on its own responsibility and may process data outside the EU.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Escher Consulting GmbH
provenance_date: '2026-11-09'
provider_name: Escher Consulting GmbH
provider_slug: banking-mcp-com
slug: banking-mcp-com-privacy-policy
source_date: '2026-11-09'
source_filename: banking-mcp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://banking-mcp.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Escher Consulting GmbH\naid: banking-mcp-com\nurl: https://banking-mcp.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller Escher Consulting GmbH, Höhenweg 2c, 44265 Dortmund, Germany.\ndata_categories:\n- category: identifying\n  text: For your account we store your email address, your language, when you signed up, when your trial ends\n- category: financial\n  text: 'We do not store balances or transactions: they are fetched from finAPI for every request your assistant\n    makes and passed only to that assistant.'\n- category: financial\n  text: per account, its name,\
  \ IBAN, type and currency\n- category: device\n  text: Per page view we process the page address, the referring website, browser, operating system and screen size,\n    plus your IP address.\n- category: location\n  text: The IP address is used only to determine your country\n- category: communication\n  text: If you write to us, we process your message and email address to answer your request\npurposes:\n- purpose: providing the service\n  text: BankingMCP connects your bank accounts to AI assistants of your choice. We process only the data that service\n    needs.\n- purpose: visitor statistics\n  text: To understand how the website is used, we count page views with the open-source software Plausible Analytics\n- purpose: service emails and tips\n  text: we send you at most two emails about using the service\n- purpose: security and abuse prevention\n  text: To prevent abuse (for example mass sign-in attempts or requests), we count requests per IP address and per\n    connection briefly\
  \ in memory\nretention:\n- scope: database backups\n  period: 14 days\n  text: The backups are encrypted with AES-256, kept on the same server and deleted after 14 days.\n- scope: assistant activity logs\n  period: 90 days\n  text: These entries are deleted after 90 days.\n- scope: account data\n  period: as long as your account exists\n  text: We keep your data for as long as your account exists.\n- scope: sign-in codes\n  period: 10 minutes\n  text: Codes are stored only as a cryptographic hash and expire after 10 minutes.\n- scope: sessions\n  period: 30 days\n  text: It ends after 7 days without use, after 30 days at the latest, or when you sign out.\nresidency:\n- region: Germany\n  text: Website, app and database run on servers of Hetzner Online GmbH in Germany (data centres in Nuremberg and\n    Falkenstein).\ntransfers:\n- mechanism: DPF\n  text: Stripe may also process data in the USA, on the basis of the EU-US Data Privacy Framework and the EU standard\n    contractual clauses.\n\
  - mechanism: SCC\n  text: Stripe may also process data in the USA, on the basis of the EU-US Data Privacy Framework and the EU standard\n    contractual clauses.\n- mechanism: other\n  text: from then on the provider's own privacy terms apply, it acts on its own responsibility and may process data\n    outside the EU.\nsubprocessors:\n  url: null\n  text: Hetzner processes the data solely on our behalf under a data processing agreement (Art. 28 GDPR).\ndpa:\n  available: true\n  url: null\n  text: DPA under Art. 28 GDPR\ndeletion:\n  route: Delete your account in your account settings; data is removed and banks disconnected at finAPI and Stripe\n    subscription cancelled.\n  text: If you delete your account, we immediately remove your account data, sessions, assistants including their\n    activity and your bank data, disconnect your banks at finAPI and cancel your subscription at Stripe.\nrights:\n- right: access\n  text: You have the right of access (Art. 15 GDPR)\n- right: rectification\n\
  \  text: rectification (Art. 16)\n- right: erasure\n  text: erasure (Art. 17)\n- right: restriction of processing\n  text: restriction of processing (Art. 18)\n- right: data portability\n  text: data portability (Art. 20)\n- right: objection\n  text: Where we process data based on legitimate interests, you can object (Art. 21).\n- right: complaint\n  text: You can also lodge a complaint with a data protection supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your financial data, do not use it for advertising and do not train AI models on it.\n"
source_yaml_url: https://artifacts.apis.io/banking-mcp-com/privacy/banking-mcp-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from Escher Consulting GmbH's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Artificial Intelligence
- Finance
- Open Banking
- MCP
- Europe
---
